#### Test 823372352b31b5a_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-25 13:18:17.636  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:18:17.647  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 13:18:17.651  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 13:18:17.709  1522  2087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 13:18:17.710  1522  2087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 13:18:17.710  1522  2087 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:18:17.710  1522  2087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 13:18:17.744  3499  3499 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 13:18:17.745  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 13:18:17.746  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-25 13:18:18.291  3832  3832 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 13:18:18.295  3832  3832 D AndroidRuntime: CheckJNI is OFF
08-25 13:18:18.332  3832  3832 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 13:18:18.374  3832  3832 I Radio-JNI: register_android_hardware_Radio DONE
08-25 13:18:18.394  3832  3832 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 13:18:18.398   872  1707 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 13:18:18.441  1991  2003 W SearchService: Abort, client detached.
08-25 13:18:18.446  1991  1991 I HotwordDetector: Closing mic
08-25 13:18:18.447  1991  2346 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c32e35b
08-25 13:18:18.447  1991  2358 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-25 13:18:18.450  3832  3832 D AndroidRuntime: Shutting down VM
08-25 13:18:18.467   872  2082 I ActivityManager: Start proc 3841:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-25 13:18:18.507   375  2360 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-25 13:18:18.508   375  2360 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-25 13:18:18.516   375  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-25 13:18:18.519  1991  2357 I MicroRecognitionRnrImpl: Detection finished
08-25 13:18:18.519  1991  2353 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-25 13:18:18.546  3841  3841 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 13:18:18.567  3841  3841 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 13:18:18.576  3841  3841 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9628-9632)
08-25 13:18:18.576  3841  3841 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 13:18:18.590  3841  3841 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {11362ae}
08-25 13:18:18.591  3841  3841 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 13:18:18.591  3841  3841 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 13:18:18.596  3841  3841 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-25 13:18:18.597  3841  3841 E SysUtils: ApplicationContext is null in ApplicationStatus
08-25 13:18:18.613  3841  3841 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-25 13:18:18.622  3841  3841 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 13:18:18.622  3841  3841 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 13:18:18.622  3841  3841 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 13:18:18.622  3841  3841 I Adreno  : Build Date                       : 10/20/15
08-25 13:18:18.622  3841  3841 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 13:18:18.622  3841  3841 I Adreno  : Local Branch                     : M14
08-25 13:18:18.622  3841  3841 I Adreno  : Remote Branch                    : 
08-25 13:18:18.622  3841  3841 I Adreno  : Remote Branch                    : 
08-25 13:18:18.622  3841  3841 I Adreno  : Reconstruct Branch               : 
08-25 13:18:18.708   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d9da14d:true
,08-25 13:18:18.751  3841  3841 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 13:18:18.767  3841  3841 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-25 13:18:18.856  3841  3879 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-25 13:18:18.868  3841  3866 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-25 13:18:18.925  3841  3879 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 13:18:19.012   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +564ms
,08-25 13:18:19.028  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-25 13:18:19.082  3841  3841 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3841
,08-25 13:18:19.235  3841  3841 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 13:18:19.289   872  1706 I ActivityManager: Killing 3390:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-25 13:18:19.337   872  1706 I ActivityManager: Killing 3556:com.google.process.gapps/u0a99 (adj 15): empty #18
,08-25 13:18:19.417  3841  3882 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1681721040
,08-25 13:18:19.426  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 13:18:19.426  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 13:18:19.426  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 13:18:19.426  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 13:18:19.426  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-25 13:18:19.426  3841  3882 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@168ad5d added. We now have 1 listener(s)
08-25 13:18:19.428  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-25 13:18:19.429  3841  3882 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 13:18:19.429  3841  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:18:19.430  3841  3882 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 13:18:19.433  3841  3882 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bc006a0 added. We now have 1 listener(s)
,08-25 13:18:19.433  3841  3882 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:18:19.444   872  1303 D WifiService: New client listening to asynchronous messages
,08-25 13:18:19.448  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 13:18:19.448  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-25 13:18:19.451  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 13:18:19.451  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 13:18:19.451  3841  3882 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 13:18:19.459  3841  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:19.460  3841  3882 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-25 13:18:19.477  3841  3882 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 13:18:19.477  3841  3882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:19.477  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:19.477  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:19.477  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:19.477  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:19.477  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:19.477  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:19.477  3841  3882 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:19.477  3841  3882 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-25 13:18:19.478  3841  3882 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:18:19.478  3841  3882 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 13:18:19.484  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:19.491  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:19.524  3841  3841 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 13:18:20.719  3841  3891 W jxcore-log: Initializing JXcore engine
,08-25 13:18:20.719  3841  3891 W jxcore-log: JXcore engine is ready
,08-25 13:18:20.760  3891  3891 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-25 13:18:20.760  3891  3891 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9562]" dev="sockfs" ino=9562 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-25 13:18:20.760  3891  3891 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-25 13:18:20.760  3891  3891 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25522]" dev="sockfs" ino=25522 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-25 13:18:20.774  3841  3891 W jxcore-log: Starting JXcore engine
,08-25 13:18:20.853  3841  3891 W jxcore-log: Platform android
08-25 13:18:20.853  3841  3891 W jxcore-log: 
,08-25 13:18:20.854  3841  3891 W jxcore-log: Process ARCH arm
08-25 13:18:20.854  3841  3891 W jxcore-log: 
,08-25 13:18:21.050  3841  3891 I jxcore-log: JXcore Cordova bridge is ready!
08-25 13:18:21.050  3841  3891 I jxcore-log: 
,08-25 13:18:21.050  3841  3891 W jxcore-log: JXcore engine is started
,08-25 13:18:21.062  3841  3882 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 13:18:21.067  3841  3841 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 13:18:21.399   872  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-25 13:18:22.301   872  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-25 13:18:26.253  3029  3898 V KeepSync: Connecting to GoogleApiClient
,08-25 13:18:26.254   872  2156 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 13:18:26.301  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:18:26.302  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:18:26.324  1522  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 13:18:26.324  1522  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-25 13:18:26.324  1522  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:18:26.324  1522  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:18:26.348  1742  3899 V BaseAuthAsyncOperation: access token request failed
,08-25 13:18:26.350  3029  3898 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-25 13:18:26.402  1522  2088 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-25 13:18:26.402  1522  2088 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-25 13:18:26.402  1522  2088 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:18:26.403  1522  2088 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:18:26.432  3029  3898 E KeepSync: IOException
08-25 13:18:26.432  3029  3898 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 13:18:26.432  3029  3898 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 13:18:26.432  3029  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 13:18:26.432  3029  3898 E KeepSync: 	... 10 more
,08-25 13:18:26.432  3029  3898 W KeepSync: Sync result 2
,08-25 13:18:26.448   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 127145, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 13:18:31.879  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-25 13:18:31.879  3841  3891 I jxcore-log: 
,08-25 13:18:33.733  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-25 13:18:33.733  3841  3891 I jxcore-log: 
,08-25 13:18:33.763  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-25 13:18:33.763  3841  3891 I jxcore-log: 
,08-25 13:18:33.780  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-25 13:18:33.780  3841  3891 I jxcore-log: 
,08-25 13:18:33.804  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-25 13:18:33.804  3841  3891 I jxcore-log: 
,08-25 13:18:33.809  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-25 13:18:33.809  3841  3891 I jxcore-log: 
,08-25 13:18:36.682  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 13:18:36.682  3841  3891 I jxcore-log: 
,08-25 13:18:36.684  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 13:18:36.684  3841  3891 I jxcore-log: 
,08-25 13:18:36.697  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:36.697  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-25 13:18:36.697  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:36.697  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:36.697  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:36.697  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:36.697  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:36.697  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:36.701  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:36.704  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 13:18:36.704  3841  3891 I jxcore-log: 
08-25 13:18:36.706  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 13:18:36.706  3841  3891 I jxcore-log: 
,08-25 13:18:38.152  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:18:38.171  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:18:38.179  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:18:38.261  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 13:18:38.261  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-25 13:18:38.261  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 13:18:38.262  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:18:38.309  3499  3499 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 13:18:38.310  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 13:18:38.311  3499  3499 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-25 13:18:40.461  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-25 13:18:40.461  3841  3891 I jxcore-log: 
,08-25 13:18:40.474  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-25 13:18:40.474  3841  3891 I jxcore-log: 
,08-25 13:18:40.484  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-25 13:18:40.484  3841  3891 I jxcore-log: 
,08-25 13:18:40.644  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-25 13:18:40.644  3841  3891 I jxcore-log: 
,08-25 13:18:41.601  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-25 13:18:41.601  3841  3891 I jxcore-log: 
,08-25 13:18:41.662  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-25 13:18:41.662  3841  3891 I jxcore-log: 
,08-25 13:18:41.670  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-25 13:18:41.670  3841  3891 I jxcore-log: 
,08-25 13:18:41.870  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-25 13:18:41.870  3841  3891 I jxcore-log: 
,08-25 13:18:41.895  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-25 13:18:41.895  3841  3891 I jxcore-log: 
,08-25 13:18:41.900  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-25 13:18:41.900  3841  3891 I jxcore-log: 
,08-25 13:18:41.906  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-25 13:18:41.906  3841  3891 I jxcore-log: 
,08-25 13:18:41.923  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-25 13:18:41.923  3841  3891 I jxcore-log: 
,08-25 13:18:41.943  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-25 13:18:41.943  3841  3891 I jxcore-log: 
,08-25 13:18:42.031  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-25 13:18:42.031  3841  3891 I jxcore-log: 
,08-25 13:18:42.037  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-25 13:18:42.037  3841  3891 I jxcore-log: 
,08-25 13:18:42.064  3841  3891 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-25 13:18:42.064  3841  3891 I jxcore-log: 
,08-25 13:18:42.080  3841  3891 D ExecuteNativeTests: Running unit tests
,08-25 13:18:42.148  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 13:18:42.148  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 added. We now have 2 listener(s)
,08-25 13:18:42.155  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 13:18:42.155  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:18:42.155  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 13:18:42.155  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:18:42.155  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 added. We now have 2 listener(s)
,08-25 13:18:42.156  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:18:42.157  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:18:42.166  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:42.174  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:42.174  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:42.174  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:42.174  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:42.174  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:42.174  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:42.174  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:42.174  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:42.180  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:42.181  3841  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:18:42.183  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 13:18:42.183  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 13:18:42.183  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 13:18:42.185  3841  3891 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 13:18:42.185  3841  3891 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 13:18:42.185  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 13:18:42.185  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 13:18:42.185  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 13:18:42.186  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:42.186  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:18:42.186  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.186  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:42.186  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:18:42.187  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-25 13:18:42.187  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:42.187  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 13:18:42.187  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 removed from the list
08-25 13:18:42.187  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:42.187  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 removed from the list
08-25 13:18:42.192  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-25 13:18:42.192  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 13:18:42.192  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:42.193  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.193  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:42.193  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.194  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:18:42.194  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.194  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
,08-25 13:18:42.195  3841  3891 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 13:18:42.196  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:42.196  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:18:42.196  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 13:18:42.196  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.196  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.197  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:42.197  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.197  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.197  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
,08-25 13:18:42.197  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.197  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.197  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.197  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.197  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.198  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:42.198  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.198  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.198  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 13:18:42.203  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710],
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 13:18:42.204  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 13:18:42.204  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.205  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.205  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.205  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.205  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.205  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.205  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.205  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.205  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.205  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.205  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.205  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.205  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.205  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.207  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.208  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.208  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.208  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.208  3841  3891 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 13:18:42.212  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:42.219  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:42.219  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:42.219  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:42.219  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:42.219  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:42.219  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:42.219  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:42.219  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:18:42.220  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:42.220  3841  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:18:42.220  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:18:42.221  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:18:42.221  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:18:42.221  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:42.221  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:18:42.222  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:42.227  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:42.229  3841  3891 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 13:18:42.229  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 13:18:42.235  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:18:42.237  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 13:18:42.237  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:18:42.239  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 13:18:42.242  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-25 13:18:42.242  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 13:18:42.242  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 13:18:42.243  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 13:18:42.244  3841  3891 D BluetoothAdapter: STATE_ON
,08-25 13:18:42.248  2683  2694 D BtGatt.GattService: registerClient() - UUID=7b71d24f-1338-4d15-bb1d-c4b232bc4b04
,08-25 13:18:42.249  2683  2707 D BtGatt.GattService: onClientRegistered() - UUID=7b71d24f-1338-4d15-bb1d-c4b232bc4b04, clientIf=5
,08-25 13:18:42.250  3841  3851 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 13:18:42.251  2683  2859 D BtGatt.GattService: start scan with filters
,08-25 13:18:42.254  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 13:18:42.254  2683  2711 D BtGatt.ScanManager: handling starting scan
,08-25 13:18:42.254  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 13:18:42.254  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 13:18:42.255  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:18:42.255  2683  2711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:18:42.256  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:18:42.257  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
,08-25 13:18:42.258  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 13:18:42.259  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 13:18:42.261  3841  3891 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 13:18:42.263  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.263  3841  3891 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 13:18:42.263  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.263  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 13:18:42.263  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:42.264  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 13:18:42.264  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 13:18:42.264  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:42.264  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:18:42.264  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 13:18:42.264  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:18:42.264  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 13:18:42.265  3841  3891 D BluetoothAdapter: STATE_ON
,08-25 13:18:42.266  2683  2694 D BtGatt.GattService: stopScan() - queue size =1
08-25 13:18:42.268  2683  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 13:18:42.268  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.268  2683  2711 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 13:18:42.272  2683  2859 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 13:18:42.273  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 13:18:42.273  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 13:18:42.273  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 13:18:42.273  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 13:18:42.273  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 13:18:42.275  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 13:18:42.277  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 13:18:42.278  2683  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 13:18:42.278  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:18:42.278  2683  2711 D BtGatt.ScanManager: Starting BLE batch scan
08-25 13:18:42.278  2683  2711 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 13:18:42.277  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 13:18:42.280  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 13:18:42.282  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:42.285  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 13:18:42.285  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:42.285  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:18:42.285  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:42.285  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:42.285  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:42.285  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
,08-25 13:18:42.285  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:42.286  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.286  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 13:18:42.286  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.287  3841  3891 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 13:18:42.289  2683  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 13:18:42.289  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:18:42.292  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:42.294  2683  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 13:18:42.294  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:18:42.299  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:42.299  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:42.299  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:42.299  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:42.299  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:42.299  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:42.299  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:42.299  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:42.304  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:18:42.304  2683  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 13:18:42.304  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.304  3841  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:18:42.304  2683  2711 D BtGatt.ScanManager: stopping BLe Batch
08-25 13:18:42.304  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 13:18:42.304  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:18:42.305  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 13:18:42.306  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:42.306  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:18:42.306  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:42.308  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:42.310  2683  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 13:18:42.310  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:18:42.310  2683  2711 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 13:18:42.311  3841  3891 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 13:18:42.311  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 13:18:42.315  2683  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 13:18:42.315  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:18:42.318  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:18:42.319  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 13:18:42.319  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:18:42.322  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 13:18:42.322  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 13:18:42.322  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 13:18:42.322  3841  3891 D BluetoothAdapter: STATE_ON
,08-25 13:18:42.324  2683  2695 D BtGatt.GattService: registerClient() - UUID=f4212ddb-5780-4b5d-86ac-9a532e5882eb
,08-25 13:18:42.324  2683  2707 D BtGatt.GattService: onClientRegistered() - UUID=f4212ddb-5780-4b5d-86ac-9a532e5882eb, clientIf=5
08-25 13:18:42.325  3841  3851 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 13:18:42.325  2683  2859 D BtGatt.GattService: start scan with filters
,08-25 13:18:42.327  2683  2711 D BtGatt.ScanManager: handling starting scan
08-25 13:18:42.327  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 13:18:42.327  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 13:18:42.327  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 13:18:42.327  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:18:42.329  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:18:42.329  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 13:18:42.329  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 13:18:42.330  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 13:18:42.332  3841  3891 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 13:18:42.333  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:42.333  3841  3891 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 13:18:42.333  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.333  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 13:18:42.333  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:42.334  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 13:18:42.334  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 13:18:42.334  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:42.334  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 13:18:42.334  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:18:42.334  2683  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 13:18:42.334  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:18:42.334  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:18:42.334  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 13:18:42.334  2683  2711 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
08-25 13:18:42.336  3841  3891 D BluetoothAdapter: STATE_ON
,08-25 13:18:42.336  2683  2694 D BtGatt.GattService: stopScan() - queue size =1
08-25 13:18:42.337  2683  2695 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 13:18:42.337  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:18:42.337  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 13:18:42.337  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 13:18:42.338  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 13:18:42.338  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 13:18:42.338  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 13:18:42.338  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 13:18:42.338  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 13:18:42.338  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 13:18:42.339  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:18:42.339  2683  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 13:18:42.339  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:18:42.339  2683  2711 D BtGatt.ScanManager: Starting BLE batch scan
08-25 13:18:42.339  2683  2711 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 13:18:42.339  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:42.340  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 13:18:42.340  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:42.340  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:18:42.340  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.340  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:42.340  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.340  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:42.340  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.340  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 13:18:42.340  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.340  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:42.340  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:42.341  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.341  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.341  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-25 13:18:42.341  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
,08-25 13:18:42.341  3841  3891 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 13:18:42.342  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:42.345  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:42.345  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:42.345  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:42.345  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:42.345  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:42.345  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:42.345  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:42.345  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:18:42.347  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:18:42.347  3841  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:18:42.347  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:18:42.349  2683  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 13:18:42.349  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.347  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 13:18:42.349  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:18:42.349  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:42.349  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 13:18:42.350  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:42.351  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:42.353  3841  3891 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 13:18:42.353  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 13:18:42.355  2683  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 13:18:42.355  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:18:42.357  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 13:18:42.357  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 13:18:42.357  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 13:18:42.360  2683  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 13:18:42.360  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.360  2683  2711 D BtGatt.ScanManager: stopping BLe Batch
08-25 13:18:42.361  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 13:18:42.361  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 13:18:42.361  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 13:18:42.361  3841  3891 D BluetoothAdapter: STATE_ON
,08-25 13:18:42.364  2683  2872 D BtGatt.GattService: registerClient() - UUID=c4c50a90-4c66-4cea-9799-602d26b75792
,08-25 13:18:42.364  2683  2707 D BtGatt.GattService: onClientRegistered() - UUID=c4c50a90-4c66-4cea-9799-602d26b75792, clientIf=5
08-25 13:18:42.364  3841  3851 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 13:18:42.364  2683  2695 D BtGatt.GattService: start scan with filters
,08-25 13:18:42.366  2683  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 13:18:42.366  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.366  2683  2711 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 13:18:42.367  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 13:18:42.367  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 13:18:42.367  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 13:18:42.367  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:18:42.370  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 13:18:42.370  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 13:18:42.370  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:18:42.371  2683  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 13:18:42.371  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.371  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 13:18:42.373  2683  2711 D BtGatt.ScanManager: handling starting scan
08-25 13:18:42.373  3841  3891 I io.jxcore.node.ConnectionHelper: start: OK
08-25 13:18:42.373  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.373  3841  3891 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 13:18:42.373  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.373  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 13:18:42.373  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.373  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 13:18:42.373  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 13:18:42.373  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:42.373  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:18:42.373  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:18:42.374  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:18:42.374  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 13:18:42.374  3841  3891 D BluetoothAdapter: STATE_ON
08-25 13:18:42.375  2683  2695 D BtGatt.GattService: stopScan() - queue size =1
,08-25 13:18:42.375  2683  2859 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 13:18:42.375  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:18:42.375  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 13:18:42.375  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 13:18:42.375  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 13:18:42.375  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 13:18:42.376  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:42.376  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 13:18:42.376  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 13:18:42.376  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:18:42.377  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:42.378  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:42.378  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:42.378  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:42.378  2683  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 13:18:42.378  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.378  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.378  2683  2711 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 13:18:42.378  3841  3891 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 13:18:42.378  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.379  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.379  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.379  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.379  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:18:42.379  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.379  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.379  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.379  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.379  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.379  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.379  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.380  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:42.380  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.380  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.380  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.381  3841  3891 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 13:18:42.381  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.381  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.381  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 13:18:42.381  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.381  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.381  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.381  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
,08-25 13:18:42.381  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.381  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.381  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.381  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.381  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.382  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.382  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.383  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.383  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.383  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:42.383  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.383  2683  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 13:18:42.383  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.383  2683  2711 D BtGatt.ScanManager: Starting BLE batch scan
08-25 13:18:42.383  2683  2711 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 13:18:42.384  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 13:18:42.384  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.384  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.384  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.384  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.384  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.384  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.384  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.384  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.384  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
,08-25 13:18:42.384  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.384  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.384  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.385  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.385  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.385  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.385  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.385  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:42.386  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.386  3841  3891 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 13:18:42.386  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:42.386  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.386  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.386  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.386  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.386  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.386  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.387  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:42.387  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.387  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.387  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.387  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.387  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.387  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.387  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.387  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.387  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.388  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
,08-25 13:18:42.388  3841  3891 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 13:18:42.388  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.388  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.388  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.388  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.388  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.388  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:42.388  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.389  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.389  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
,08-25 13:18:42.389  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.389  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.389  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:42.389  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.389  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.389  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.389  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.389  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.390  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
,08-25 13:18:42.390  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 13:18:42.391  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 13:18:42.391  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 13:18:42.391  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 13:18:42.391  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 13:18:42.391  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 13:18:42.392  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 13:18:42.392  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:18:42.392  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 13:18:42.392  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.392  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 13:18:42.392  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:42.392  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.393  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:18:42.393  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.393  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 13:18:42.393  2683  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 13:18:42.393  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:18:42.393  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:42.393  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:18:42.393  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:42.393  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.394  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.394  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:18:42.394  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.394  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
,08-25 13:18:42.395  3841  3891 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:18:42.395  3841  3891 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-25 13:18:42.395  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 13:18:42.398  2683  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 13:18:42.398  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.399  3841  3891 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:18:42.399  3841  3891 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-25 13:18:42.399  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 13:18:42.399  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 13:18:42.399  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 13:18:42.400  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-25 13:18:42.401  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 13:18:42.401  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-25 13:18:42.401  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 13:18:42.401  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 13:18:42.401  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-25 13:18:42.401  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 13:18:42.401  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 13:18:42.401  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-25 13:18:42.401  3841  3891 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 13:18:42.401  3841  3891 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-25 13:18:42.401  3841  3891 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 13:18:42.401  3841  3891 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:18:42.401  3841  3891 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 13:18:42.402  3841  3891 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-25 13:18:42.402  3841  3891 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 13:18:42.402  3841  3891 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-25 13:18:42.402  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 13:18:42.404  2683  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 13:18:42.405  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.405  2683  2711 D BtGatt.ScanManager: stopping BLe Batch
08-25 13:18:42.406  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-25 13:18:42.406  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 13:18:42.406  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-25 13:18:42.407  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 13:18:42.407  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 13:18:42.407  3841  3891 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 13:18:42.407  3841  3891 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-25 13:18:42.407  3841  3891 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 13:18:42.407  3841  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 397)
08-25 13:18:42.407  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-25 13:18:42.407  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.407  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 13:18:42.408  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.408  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.408  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.408  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-25 13:18:42.409  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.410  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.410  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
,08-25 13:18:42.410  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.410  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.410  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.410  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:18:42.410  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.411  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 13:18:42.411  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.411  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.411  2683  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0,
08-25 13:18:42.411  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.411  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:18:42.411  2683  2711 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 13:18:42.411  3841  3906 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
08-25 13:18:42.412  3841  3891 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-25 13:18:42.412  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.412  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.412  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 13:18:42.412  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.412  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.412  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.413  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.413  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.413  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.413  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.413  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.413  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.413  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.413  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.413  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.413  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.414  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.414  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.414  3841  3905 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:18:42.414  3841  3891 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 13:18:42.415  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.415  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.415  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.415  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.415  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.415  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.415  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.415  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.415  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.415  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.415  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the li,st - probably already removed
08-25 13:18:42.415  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.415  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.415  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.416  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.416  2683  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 13:18:42.416  2683  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:18:42.416  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.417  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.417  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.418  3841  3891 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 13:18:42.418  3841  3891 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 13:18:42.418  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 13:18:42.418  3841  3891 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 13:18:42.418  3841  3891 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 13:18:42.418  3841  3891 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 13:18:42.418  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 13:18:42.418  3841  3891 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 13:18:42.418  3841  3891 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 13:18:42.418  3841  3891 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 13:18:42.418  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 13:18:42.418  3841  3891 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 13:18:42.418  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.419  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.419  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.419  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.419  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.419  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.419  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.419  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.419  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.419  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.419  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.419  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.419  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.419  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.420  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.420  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.420  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.420  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.421  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.421  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.421  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.421  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.421  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.421  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.421  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.421  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.421  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.421  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.421  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.421  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.421  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.421  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.421  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.421  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.422  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.422  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.422  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.422  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.422  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.422  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.422  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.422  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.422  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.422  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.422  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.422  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.422  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.423  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.423  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.423  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.423  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.424  3841  3891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 13:18:42.424  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:18:42.425  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 13:18:42.425  3841  3891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 13:18:42.425  3841  3891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 13:18:42.426  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 13:18:42.426  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 13:18:42.426  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 13:18:42.426  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.426  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 13:18:42.426  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 13:18:42.426  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 13:18:42.426  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.426  3841  3891 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 13:18:42.426  3841  3841 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 13:18:42.426  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.426  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.426  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:18:42.426  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:18:42.427  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:18:42.427  3841  3907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:18:42.427  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.427  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.427  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:42.428  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:42.428  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:18:42.428  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:18:42.428  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.428  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.428  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.428  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.428  3841  3907 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 13:18:42.428  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.428  3841  3907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 13:18:42.428  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.428  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.428  3841  3907 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 13:18:42.429  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.429  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.429  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.429  3841  3841 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 13:18:42.429  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.429  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.429  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.429  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.429  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.430  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.430  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.430  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.430  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.431  3841  3891 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 13:18:42.431  3841  3891 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 13:18:42.431  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 13:18:42.432  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 13:18:42.432  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.432  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.432  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.433  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.433  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.433  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.433  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.433  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.433  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.433  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.433  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.433  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.433  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.433  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.434  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.434  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.434  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.434  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.437  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.437  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.437  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.437  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.437  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.437  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.437  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.438  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.438  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.438  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.438  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.438  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.438  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.438  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.439  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.439  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.439  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.439  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.439  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:18:42.439  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:18:42.439  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:18:42.440  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:18:42.440  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.440  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.440  3841  3891 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c46d522 not in the list
08-25 13:18:42.440  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.440  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.440  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:18:42.440  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.440  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.440  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:18:42.440  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:18:42.441  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:18:42.441  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:18:42.441  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:18:42.441  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9654bb3 not in the list
08-25 13:18:42.442  3841  3891 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 13:18:42.442  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 13:18:42.442  3841  3891 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 13:18:42.442  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 13:18:42.442  3841  3891 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 13:18:42.442  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 13:18:42.444  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 13:18:42.444  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 13:18:42.444  3841  3891 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 13:18:42.444  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 13:18:42.445  3841  3891 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 13:18:42.445  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 13:18:42.445  3841  3891 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 13:18:42.445  3841  3891 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 13:18:42.445  3841  3891 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 13:18:42.445  3841  3891 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 13:18:42.446  3841  3891 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 13:18:42.446  3841  3891 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 13:18:42.446  3841  3891 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 13:18:42.446  3841  3891 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 13:18:42.447  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:42.447  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cf2715d added. We now have 2 listener(s)
08-25 13:18:42.447  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:18:42.449  3841  3891 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 13:18:42.449   872  2152 D WifiService: setWifiEnabled: true pid=3841, uid=10000
08-25 13:18:42.449   872  2152 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 13:18:42.450  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:42.450  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cb2cad2 added. We now have 3 listener(s)
08-25 13:18:42.450  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:18:42.455  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:42.455  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25887a3 added. We now have 4 listener(s)
08-25 13:18:42.455  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:18:42.457  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:18:42.458  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4179aa0 added. We now have 5 listener(s)
08-25 13:18:42.458  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:18:42.461   872   883 D WifiService: setWifiEnabled: false pid=3841, uid=10000
08-25 13:18:42.461   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 13:18:42.465  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:18:42.467  2683  2702 D BluetoothAdapterState: Current state: ON, message: 23
08-25 13:18:42.467  2683  2702 D BluetoothAdapterProperties: Setting state to 13
08-25 13:18:42.467  2683  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 13:18:42.468  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:42.468  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:18:42.468  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:42.468  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:42.468  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:42.468  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:42.468  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:42.468  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:42.468  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:18:42.468  2683  2702 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 13:18:42.468  2683  2702 I BluetoothAdapterState: Entering PendingCommandState
08-25 13:18:42.468  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:42.469  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:42.469  3841  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:18:42.470  2683  2683 D BluetoothMapService: onReceive
08-25 13:18:42.470  2683  2683 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:42.470  2683  2683 D BluetoothMapService: STATE_TURNING_OFF
08-25 13:18:42.470  2683  2683 D BluetoothMapService: MAP Service closeService in
08-25 13:18:42.470  2683  2683 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 13:18:42.470  2683  2683 D ObexServerSockets0: shutdown(block = true)
08-25 13:18:42.471  2683  2683 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 13:18:42.471  2683  2683 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 13:18:42.471  2683  2854 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 13:18:42.471  2683  2884 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 13:18:42.471  2683  2885 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 13:18:42.472  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:42.474  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:42.475  2683  2683 I BtOppRfcommListener: stopping Accept Thread
08-25 13:18:42.475  2683  3444 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:18:42.475  2683  3444 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 13:18:42.477  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:42.477  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:42.477  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:42.477  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:42.477  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:42.477  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:42.477  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:42.477  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:42.477  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:18:42.478  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:42.478  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:42.481  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:42.482  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 13:18:42.484   872  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 13:18:42.484   872  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 13:18:42.485   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 13:18:42.485   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 13:18:42.490   872   885 I ActivityManager: Start proc 3910:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-25 13:18:42.491  2683  2707 D BluetoothAdapterProperties: Scan Mode:20
,08-25 13:18:42.491  2683  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 13:18:42.493   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-25 13:18:42.494   872  1877 D DhcpClient: Clearing IP address
08-25 13:18:42.495  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:42.495   371   870 D CommandListener: Setting iface cfg
,08-25 13:18:42.497  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:42.499  1522  2118 V NativeCrypto: Read error: ssl=0xaebeae00: I/O error during system call, Connection timed out
08-25 13:18:42.500  2683  2683 D HeadsetService: Received stop request...Stopping profile...
08-25 13:18:42.501  1522  2118 V NativeCrypto: SSL shutdown failed: ssl=0xaebeae00: I/O error during system call, Broken pipe
08-25 13:18:42.502   872  1302 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-25 13:18:42.504   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-25 13:18:42.504   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-25 13:18:42.504   394   394 E Parcel  : Reading a NULL string not supported here.
08-25 13:18:42.507  1911  2120 D BluetoothHeadset: Proxy object disconnected
08-25 13:18:42.507   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 13:18:42.507   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 13:18:42.507   872   872 D BluetoothHeadset: Proxy object disconnected
,08-25 13:18:42.508  1372  2033 D BluetoothHeadset: Proxy object disconnected
08-25 13:18:42.508  2683  2683 D A2dpService: Received stop request...Stopping profile...
08-25 13:18:42.508   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 13:18:42.508  2683  2864 D A2dpStateMachine: Exit Disconnected: -1
08-25 13:18:42.511  2683  2683 D HidService: Received stop request...Stopping profile...
08-25 13:18:42.511  2683  2683 D HidService: Stopping Bluetooth HidService
,08-25 13:18:42.512  1372  1372 D HeadsetProfile: Bluetooth service disconnected
,08-25 13:18:42.512  1372  1372 D BluetoothA2dp: Proxy object disconnected
08-25 13:18:42.512   872   872 D BluetoothA2dp: Proxy object disconnected
08-25 13:18:42.513   872  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 13:18:42.514  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:42.514  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:42.514  1372  1372 D BluetoothInputDevice: Proxy object disconnected
08-25 13:18:42.514   872  1884 D DhcpClient: Receive thread stopped
08-25 13:18:42.514  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:42.514  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 13:18:42.514  1372  1372 D HidProfile: Bluetooth service disconnected
08-25 13:18:42.516   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-25 13:18:42.519  2683  2683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 13:18:42.519  2683  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 13:18:42.519  2683  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 13:18:42.519  2683  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 13:18:42.519  2683  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 13:18:42.520  2683  2707 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 13:18:42.522   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 13:18:42.523  2683  2683 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 13:18:42.524  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:42.524  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:42.526  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:42.526  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:42.531  2683  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-25 13:18:42.531  2683  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 13:18:42.531  2683  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 13:18:42.531  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:42.531  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:42.531  2683  2827 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:18:42.531  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 13:18:42.531  2683  2827 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:18:42.531  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:42.531  2683  2827 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:18:42.531  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:42.532  2683  2827 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:18:42.532  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:42.532  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:42.532  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:42.532  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:42.532  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:42.532  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:42.532  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:42.532  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:42.532  2683  2683 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 13:18:42.532  2683  2683 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 13:18:42.532  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:42.532  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:18:42.532  2683  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 13:18:42.533  2683  2683 D HealthService: Received stop request...Stopping profile...
08-25 13:18:42.534  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:42.534  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:42.534  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:42.534  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:42.534  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:42.534  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:42.534  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:42.534  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:42.534  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:42.534  2683  2683 D PanService: Received stop request...Stopping profile...
08-25 13:18:42.535  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:42.535  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:18:42.536  2683  2683 D BluetoothMapService: Received stop request...Stopping profile...
08-25 13:18:42.536  2683  2683 D BluetoothMapService: stop()
08-25 13:18:42.537  2683  2683 D BluetoothMapAppObserver: deinitObservers()
08-25 13:18:42.537  2683  2683 D BluetoothMapAppObserver: removeReceiver()
,08-25 13:18:42.538  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:42.538  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:42.538  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:42.538  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:42.538  2683  2683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 13:18:42.538  2683  2707 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 13:18:42.538  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 13:18:42.538  1372  1372 D PanProfile: Bluetooth service disconnected
,08-25 13:18:42.538  2683  2683 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 13:18:42.539  1372  1372 D BluetoothMap: Proxy object disconnected
08-25 13:18:42.539  1372  1372 D MapProfile: Bluetooth service disconnected
08-25 13:18:42.539  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:42.539  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:42.539  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:42.539  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:42.540  2683  2683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-25 13:18:42.540  2683  2683 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 13:18:42.540  2683  2683 D BluetoothMapService: MAP Service closeService in
08-25 13:18:42.540  2683  2683 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:42.541  2683  2683 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:42.541  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:42.541  2683  2683 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:42.541  2683  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-25 13:18:42.541  2683  2702 D BluetoothAdapterProperties: Setting state to 15
,08-25 13:18:42.541  2683  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-25 13:18:42.542  1372  1385 D BluetoothPan: onBluetoothStateChange on: false
08-25 13:18:42.543  1911  2085 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:18:42.543  1372  1387 D BluetoothMap: onBluetoothStateChange: up=false
08-25 13:18:42.544  2683  2702 I BluetoothAdapterState: Entering BleOnState
08-25 13:18:42.544   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 13:18:42.544   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:18:42.544   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:18:42.544  1372  2033 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:18:42.544  1372  1385 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 13:18:42.545  2683  2683 D BluetoothMapService: cleanup()
08-25 13:18:42.545  2683  2683 D BluetoothMapService: MAP Service closeService in
08-25 13:18:42.546  1372  1387 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 13:18:42.546  1372  2033 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 13:18:42.546   872  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 13:18:42.547   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:18:42.547  2683  2702 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 13:18:42.547  2683  2702 D BluetoothAdapterProperties: Setting state to 16
,08-25 13:18:42.547  2683  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 13:18:42.549  2683  2702 D BluetoothAdapterProperties: onBleDisable
08-25 13:18:42.549  2683  2702 I BluetoothAdapterState: Entering PendingCommandState
,08-25 13:18:42.550  2683  2703 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-25 13:18:42.550  2683  2707 D BluetoothAdapterProperties: Scan Mode:20
08-25 13:18:42.551  2683  2827 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 13:18:42.551  2683  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 13:18:42.551  3841  3905 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
08-25 13:18:42.555  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:42.556  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:42.557  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:42.557  2168  2341 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:18:42.557  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:42.572   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 13:18:42.577  3910  3910 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-25 13:18:42.586  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 13:18:42.588   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 13:18:42.589   872  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-25 13:18:42.589   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:18:42.592   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8e8bf2b:true
,08-25 13:18:42.592   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-25 13:18:42.595  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:42.596  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:42.597  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:42.608   872  2156 I ActivityManager: Start proc 3927:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-25 13:18:42.634  3910  3910 D LocalBluetoothProfileManager: Adding local MAP profile
,08-25 13:18:42.634   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-25 13:18:42.637  3910  3910 D BluetoothMap: Create BluetoothMap proxy object
,08-25 13:18:42.642  3910  3910 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-25 13:18:42.646  3927  3927 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-25 13:18:42.656  3910  3910 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:18:42.665   872   882 I ActivityManager: Killing 3482:android.process.acore/u0a5 (adj 15): empty #17
,08-25 13:18:42.751  2683  2707 I bt_hci  : shut_down
,08-25 13:18:42.757  2683  2712 I bt_vendor: low_power_mode_cb
,08-25 13:18:42.762  2683  2712 D bt_hwcfg: hw_epilog_process
,08-25 13:18:42.778  3927  3927 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:18:42.778  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 13:18:42.779  3927  3927 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 13:18:42.779  3927  3927 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 13:18:42.779  3927  3927 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 13:18:42.779  3927  3927 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.k.d(PG:583)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 13:18:42.779  3927  3927 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 13:18:42.779  3927  3927 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 13:18:42.779  3927  3927 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:18:42.779  3927  3927 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 13:18:42.783  2683  2712 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-25 13:18:42.783  2683  2712 I bt_vendor: epilog_cb
,08-25 13:18:42.783  2683  2712 I bt_hci  : epilog_finished_callback
,08-25 13:18:42.803   872  1965 I ActivityManager: Start proc 3959:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-25 13:18:42.803   872  1965 I ActivityManager: Killing 3656:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-25 13:18:42.848  2683  2707 I bt_hci_h4: hal_close
,08-25 13:18:42.848  2683  2707 I bt_userial_vendor: device fd = 51 close
,08-25 13:18:42.874  3959  3959 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-25 13:18:42.929  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 13:18:42.998  2683  2703 D bt_stack_manager: event_shut_down_stack finished.
08-25 13:18:42.999  2683  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 13:18:43.018  2683  2683 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 13:18:43.018  2683  2702 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 13:18:43.022  2683  2683 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 13:18:43.023  2683  2683 D BtGatt.GattService: stop()
,08-25 13:18:43.023  2683  2683 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 13:18:43.031  2683  2683 V BluetoothAdapterState: isTurningOff()=false
,08-25 13:18:43.031  2683  2683 V BluetoothAdapterState: isTurningOn()=false
,08-25 13:18:43.031  2683  2683 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 13:18:43.031  2683  2683 V BluetoothAdapterState: isBleTurningOff()=true
,08-25 13:18:43.031  2683  2702 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-25 13:18:43.032  2683  2702 D BluetoothAdapterProperties: Setting state to 10
08-25 13:18:43.032  2683  2702 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 13:18:43.033  2683  2702 I BluetoothAdapterState: Entering OffState
08-25 13:18:43.035   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-25 13:18:43.049  2683  2683 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 13:18:43.049  2683  2683 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 13:18:43.049  2683  2683 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 13:18:43.050  2683  2703 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 13:18:43.053  2683  2703 D bt_stack_manager: event_clean_up_stack finished.
,08-25 13:18:43.064  2683  2683 I art     : System.exit called, status: 0
,08-25 13:18:43.065  2683  2683 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 13:18:43.148  3959  3980 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-25 13:18:43.148  3959  3980 I Babel_SMS: MmsConfig.loadMmsSettings
,08-25 13:18:43.149  3959  3980 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-25 13:18:43.149  3959  3980 I Babel_SMS: MmsConfig.loadFromDatabase
,08-25 13:18:43.161   872  2008 I ActivityManager: Process com.android.bluetooth (pid 2683) has died
,08-25 13:18:43.233  3959  3980 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-25 13:18:43.233  3959  3980 I Babel_SMS: MmsConfig.loadFromResources
,08-25 13:18:43.235  3959  3980 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
08-25 13:18:43.236  3959  3980 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-25 13:18:43.337  3959  3959 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 13:18:43.341  3959  3959 I Babel_Crash: startup - clean
,08-25 13:18:43.379  3959  3959 I Babel_telephony: TeleModule.launchCompleted
,08-25 13:18:43.385   872  2008 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 13:18:43.403  3959  3959 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-25 13:18:43.409  3959  3959 W Babel   : BAM#gBA: invalid account id: -1
08-25 13:18:43.410  3959  3959 W Babel   : BAM#gBA: invalid account id: -1
,08-25 13:18:43.411  3959  3959 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-25 13:18:43.420   872  2082 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-25 13:18:43.426  3959  3985 I Babel   : deleted: false for 0
,08-25 13:18:43.454   872  2081 I ActivityManager: Start proc 3987:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-25 13:18:43.478  3959  3959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:18:43.531  3987  3987 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-25 13:18:43.551  3959  3959 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 13:18:43.563  3959  3959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:18:43.579  3959  3959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:18:43.595  3959  3959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:18:43.607  3959  3959 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-25 13:18:43.623  3959  3959 I vclib   : onServiceConnected
,08-25 13:18:43.665  3987  3987 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-25 13:18:43.673  3927  3948 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-25 13:18:43.707  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 13:18:43.758   872  1357 I ActivityManager: Start proc 4012:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-25 13:18:43.761  3910  3910 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:18:43.772   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15a7483:true
,08-25 13:18:43.774   872  1357 I ActivityManager: Killing 3673:com.android.musicfx/u0a18 (adj 15): empty #17
,08-25 13:18:43.869  4012  4012 D AdapterServiceConfig: Adding HeadsetService
,08-25 13:18:43.870  4012  4012 D AdapterServiceConfig: Adding A2dpService
08-25 13:18:43.870  4012  4012 D AdapterServiceConfig: Adding HidService,
08-25 13:18:43.870  4012  4012 D AdapterServiceConfig: Adding HealthService
08-25 13:18:43.870  4012  4012 D AdapterServiceConfig: Adding PanService
,08-25 13:18:43.871  4012  4012 D AdapterServiceConfig: Adding GattService
08-25 13:18:43.871  4012  4012 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 13:18:43.876   872  1706 I ActivityManager: Killing 2257:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-25 13:18:43.920  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:43.940  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 13:18:43.946  1742  1742 D SystemUpdateService: onCreate
,08-25 13:18:43.949  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 13:18:43.956  1742  4024 I SystemUpdateService: active receiver: enabled
,08-25 13:18:43.958  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 13:18:43.959  1742  4024 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 13:18:43.962  1742  4024 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 13:18:43.963  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-25 13:18:43.963  1742  4024 I SystemUpdateService: now status is 0 (complete)
08-25 13:18:43.963  1742  4024 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 13:18:43.964  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-25 13:18:43.964  1742  2418 I iu.UploadsManager: num queued entries: 0
,08-25 13:18:43.963  1742  4024 I SystemUpdateService: file has been verified
08-25 13:18:43.966  1742  4024 I SystemUpdateService: OTA package size = 12249756
08-25 13:18:43.966  1742  2418 I iu.UploadsManager: num updated entries: 0
,08-25 13:18:43.969  1742  2418 I iu.SyncManager: NEXT; no task
08-25 13:18:43.970  1742  4024 I SystemUpdateService: showing system update notification
,08-25 13:18:43.988   872  1707 I ActivityManager: Start proc 4026:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-25 13:18:44.004  1742  1742 D SystemUpdateService: onDestroy
,08-25 13:18:44.016  4026  4026 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-25 13:18:44.018  4026  4026 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:18:44.027  4026  4026 D SprintDMHelper: simOperator: 
,08-25 13:18:44.027  4026  4026 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 13:18:44.049   872  1706 I ActivityManager: Start proc 4038:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-25 13:18:44.052   872  1706 I ActivityManager: Killing 3699:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-25 13:18:44.187   872  2149 I ActivityManager: Start proc 4053:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-25 13:18:44.191  3959  4052 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-25 13:18:44.194   872   882 I ActivityManager: Killing 3616:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-25 13:18:44.265  4053  4053 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-25 13:18:44.327  4053  4053 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 13:18:44.327  4053  4053 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 13:18:44.327  4053  4053 I GAv4    :   adb logcat -s GAv4
,08-25 13:18:44.341  4053  4053 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 13:18:44.346  4053  4053 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 13:18:44.371  4053  4070 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 13:18:44.483  4053  4053 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-25 13:18:44.524  4053  4053 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-25 13:18:44.536  4053  4053 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 5584-5592)
,08-25 13:18:44.536  4053  4053 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 13:18:44.547  4053  4053 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a1882}
,08-25 13:18:44.547  4053  4053 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 13:18:44.547  4053  4053 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 13:18:44.556  4053  4053 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 13:18:44.557  4053  4053 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 13:18:44.576  4053  4053 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 13:18:44.593  4053  4053 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 13:18:44.593  4053  4053 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 13:18:44.593  4053  4053 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 13:18:44.593  4053  4053 I Adreno  : Build Date                       : 10/20/15
08-25 13:18:44.593  4053  4053 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 13:18:44.593  4053  4053 I Adreno  : Local Branch                     : M14
08-25 13:18:44.593  4053  4053 I Adreno  : Remote Branch                    : 
08-25 13:18:44.593  4053  4053 I Adreno  : Remote Branch                    : 
08-25 13:18:44.593  4053  4053 I Adreno  : Reconstruct Branch               : 
,08-25 13:18:44.654  4053  4053 I NSApplication: Starting up...
,08-25 13:18:44.659  4053  4099 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 13:18:44.691   872  2081 I ActivityManager: Start proc 4104:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-25 13:18:44.693   872  2081 I ActivityManager: Killing 3537:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,08-25 13:18:44.789  4104  4104 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-25 13:18:45.010   872  2147 I ActivityManager: Start proc 4116:com.google.android.apps.plus/u0a74 for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver
,08-25 13:18:45.011   872  2147 I ActivityManager: Killing 3759:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-25 13:18:45.218   872  2152 I ActivityManager: Start proc 4132:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,08-25 13:18:45.234   872  2156 I ActivityManager: Killing 2969:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-25 13:18:45.288   872   883 I ActivityManager: Killing 3786:com.google.android.deskclock/u0a44 (adj 15): empty #17
,08-25 13:18:45.340  4132  4132 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-25 13:18:45.421  4132  4132 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-25 13:18:45.447  4116  4125 W art     : Suspending all threads took: 5.415ms
,08-25 13:18:45.476   872   883 D WifiService: setWifiEnabled: true pid=3841, uid=10000
,08-25 13:18:45.476   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 13:18:45.479   872  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-25 13:18:45.492  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:45.492  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:45.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:45.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:45.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:45.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:45.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:45.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:45.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:45.492  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:45.493  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:45.496  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:45.496  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:45.496  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:45.496  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:45.496  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:45.496  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:45.496  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:45.496  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:45.496  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:45.497  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:45.497  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:45.523  4132  4154 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,08-25 13:18:45.524   872  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-25 13:18:45.526   872  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 13:18:45.529   872  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 13:18:45.531   872  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-25 13:18:45.532   872  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 13:18:45.532   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-25 13:18:45.532   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 13:18:45.545   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 13:18:45.545   872  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.88 rxSuccessRate=6.38 delta 1000 -> 1000
08-25 13:18:45.546   371   870 D CommandListener: Setting iface cfg
,08-25 13:18:45.546   872  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
08-25 13:18:45.547   872  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 13:18:45.551   872  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 13:18:45.551   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-25 13:18:45.551   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 13:18:45.552   872  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 13:18:45.573   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 13:18:45.638   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 13:18:45.640  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 13:18:45.722  4132  4154 D ContactDirectoryManager: Found com.google.contacts.gal.provider
08-25 13:18:45.722  4132  4154 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,08-25 13:18:45.756   872  1706 I ActivityManager: Start proc 4160:com.google.android.gm.exchange/u0a77 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,08-25 13:18:45.785   872  1965 I ActivityManager: Killing 3804:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-25 13:18:45.831  4160  4160 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,08-25 13:18:45.882   872  2147 I ActivityManager: Start proc 4172:com.google.android.gm/u0a78 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,08-25 13:18:45.907   872  2081 I ActivityManager: Start proc 4182:com.google.process.gapps/u0a99 for content provider com.google.android.syncadapters.contacts/.GalProvider
,08-25 13:18:45.947   872  2156 I ActivityManager: Killing 2772:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-25 13:18:45.998   872  1386 I ActivityManager: Killing 1991:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-25 13:18:46.029  4172  4172 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,08-25 13:18:46.063  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 13:18:46.085   872  1303 D WifiService: Client connection lost with reason: 4
,08-25 13:18:46.115  4182  4182 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,08-25 13:18:46.120  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 13:18:46.121  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 13:18:46.125   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 13:18:46.127  4172  4199 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,08-25 13:18:46.133   872  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 13:18:46.133   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 13:18:46.133   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 13:18:46.148   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 13:18:46.158   371   870 D CommandListener: Setting iface cfg
,08-25 13:18:46.159   872  1302 D WifiStateMachine: Start Dhcp Watchdog 2
,08-25 13:18:46.164  4182  4182 I GoogleHttpClient: GMS http client unavailable, use old client
,08-25 13:18:46.180   872  1304 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-25 13:18:46.180   872  4205 D DhcpClient: Receive thread started
08-25 13:18:46.181   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 13:18:46.185  4132  4154 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,08-25 13:18:46.209  4132  4154 I ContactDirectoryManager: Discovered 0 contact directories in 618ms
,08-25 13:18:46.249  4172  4172 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-25 13:18:46.264   872  1302 E native  : do suspend false
,08-25 13:18:46.275  4172  4198 I Gmail   : getAccountsCursor
,08-25 13:18:46.278   872  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 13:18:46.293   872  4205 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172675, domain null
,08-25 13:18:46.294   872  1877 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172675 seconds
,08-25 13:18:46.295   872  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 13:18:46.304  4172  4213 E Gmail   : Error finding the version of the Email provider.....
08-25 13:18:46.304  4172  4213 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
08-25 13:18:46.304  4172  4213 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
08-25 13:18:46.304  4172  4213 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
08-25 13:18:46.304  4172  4213 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
08-25 13:18:46.304  4172  4213 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 13:18:46.304  4172  4213 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:18:46.304  4172  4213 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
08-25 13:18:46.304  4172  4213 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 13:18:46.305  4172  4213 W EmailMigration: We do not support migrating this version of the Email provider.
,08-25 13:18:46.316  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:18:46.317   872  4205 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 13:18:46.318   872  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-25 13:18:46.319   371   870 D CommandListener: Setting iface cfg
,08-25 13:18:46.325   872  1877 D DhcpClient: Scheduling renewal in 86399s
,08-25 13:18:46.326   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 13:18:46.335   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-25 13:18:46.336   872  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 13:18:46.336   872  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 13:18:46.337   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 13:18:46.338   872  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 13:18:46.338   872  1304 D ConnectivityService: Adding iface wlan0 to network 101
,08-25 13:18:46.391   872  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 13:18:46.391   872  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-25 13:18:46.392   872  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 13:18:46.393   872  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-25 13:18:46.393   872  1304 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 13:18:46.401   872  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 13:18:46.405   872  1304 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-25 13:18:46.405   872  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-25 13:18:46.405   872  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-25 13:18:46.405   872  1304 D ConnectivityService:    accepting network in place of null
,08-25 13:18:46.405   872  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-25 13:18:46.406   872  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-25 13:18:46.406   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 13:18:46.409   872  1965 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,08-25 13:18:46.423   872  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=147478, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 13:18:46.433  4160  4160 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-25 13:18:46.438   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 13:18:46.447  4160  4160 I Exchange: EasService.onCreate
,08-25 13:18:46.448  4172  4222 I Gmail   : Observing account changes for notifications
,08-25 13:18:46.459  4160  4227 I Exchange: RestartPingTask
,08-25 13:18:46.477   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 13:18:46.479   872  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 13:18:46.479   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:18:46.481   872  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 13:18:46.485   872   889 D Tethering: MasterInitialState.processMessage what=3
08-25 13:18:46.490  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:46.490  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:46.490  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:46.490  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:46.490  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:46.490  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:46.490  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:46.490  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:46.490  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:18:46.491  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:46.491  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:46.492  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:46.492  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:46.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:46.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:46.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:46.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:46.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:46.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:18:46.492  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:18:46.492  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:46.492  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:18:46.496   872  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:815::200e
08-25 13:18:46.498  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 13:18:46.501  1742  1742 D SystemUpdateService: onCreate
,08-25 13:18:46.506  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 13:18:46.508  1742  4232 I SystemUpdateService: active receiver: enabled
,08-25 13:18:46.510  1742  4232 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-25 13:18:46.515  1742  4232 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 13:18:46.518  1742  4232 I SystemUpdateService: now status is 0 (complete)
,08-25 13:18:46.518  1742  4232 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 13:18:46.518  1742  4232 I SystemUpdateService: file has been verified
08-25 13:18:46.518  1742  4232 I SystemUpdateService: OTA package size = 12249756
,08-25 13:18:46.528  1742  4232 I SystemUpdateService: showing system update notification
08-25 13:18:46.528  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 13:18:46.531  1742  2418 I iu.UploadsManager: num queued entries: 0
,08-25 13:18:46.531  1742  2418 I iu.UploadsManager: num updated entries: 0
,08-25 13:18:46.534  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 13:18:46.535  1742  2418 I iu.SyncManager: NEXT; no task
,08-25 13:18:46.535  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-25 13:18:46.536  1742  4236 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-25 13:18:46.536  1742  4236 W BaseAppContext: Using Auth Proxy for data requests.
08-25 13:18:46.537  4026  4026 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:18:46.537  1742  4236 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 13:18:46.541  4026  4026 D SprintDMHelper: simOperator: 
,08-25 13:18:46.541  4026  4026 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 13:18:46.543  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:18:46.545  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:18:46.552  1742  1742 D SystemUpdateService: onDestroy
,08-25 13:18:46.554  4160  4160 I Exchange: RestartPingsTask did not start any pings.
,08-25 13:18:46.554  4160  4160 I Exchange: PSS stopIfIdle
08-25 13:18:46.554  4160  4160 I Exchange: PSS has no active accounts; stopping service.
,08-25 13:18:46.557  4160  4160 I Exchange: onDestroy
,08-25 13:18:46.575  1522  2087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 13:18:46.575  1522  2087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-25 13:18:46.576  1522  2087 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:18:46.576  1522  2087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 13:18:46.576   872  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 11:18:46 GMT], X-Android-Received-Millis=[1472123926576], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472123926544]}
,08-25 13:18:46.577   872  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 13:18:46.578   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-25 13:18:46.578   872  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 13:18:46.579   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 13:18:46.593  1742  4236 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-25 13:18:46.668  3959  4240 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 13:18:46.857  1522  2087 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 13:18:46.857  1522  2087 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-25 13:18:46.858  1522  2087 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 13:18:46.858  1522  2087 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:18:46.881  4116  4239 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 13:18:46.881  4116  4239 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at jdm.a(PG:82)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at jcs.o(PG:406)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at jcn.a(PG:1379)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at jcs.i(PG:143)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at blb.a(PG:3937)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at czp.a(PG:18188)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at czp.a(PG:9081)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at czq.run(PG:1686)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 13:18:46.881  4116  4239 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at jdj.a(PG:4091)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at jdj.a(PG:1125)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at jdm.a(PG:77)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	... 12 more
08-25 13:18:46.881  4116  4239 E HttpOperation: Caused by: faj: BadAuthentication
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at fal.a(PG:38)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	at jdj.a(PG:4089)
08-25 13:18:46.881  4116  4239 E HttpOperation: 	... 14 more
,08-25 13:18:46.942  1522  3817 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 13:18:46.942  1522  3817 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 13:18:46.942  1522  3817 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 13:18:46.942  1522  3817 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:18:46.990  4116  4239 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 13:18:46.990  4116  4239 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at jdm.a(PG:82)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at jcs.o(PG:406)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at jcn.a(PG:1379)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at jcs.i(PG:143)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at hec.a(PG:42)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at hee.a(PG:102)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at czr.a(PG:65)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at kka.a(PG:108)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at czp.a(PG:19176)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at czp.a(PG:9081)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at czq.run(PG:1686)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 13:18:46.990  4116  4239 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at jdj.a(PG:4091)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at jdj.a(PG:1125)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at jdm.a(PG:77)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	... 15 more
08-25 13:18:46.990  4116  4239 E HttpOperation: Caused by: faj: BadAuthentication
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at fal.a(PG:38)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	at jdj.a(PG:4089)
08-25 13:18:46.990  4116  4239 E HttpOperation: 	... 17 more
,08-25 13:18:46.992  4116  4239 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 13:18:46.992  4116  4239 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at hec.a(PG:42)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at hee.a(PG:102)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at czr.a(PG:65)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at kka.a(PG:108)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at jdj.a(PG:1125)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	... 15 more
08-25 13:18:46.992  4116  4239 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at fal.a(PG:38)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 13:18:46.992  4116  4239 E ExperimentLoader: 	... 17 more
,08-25 13:18:47.084   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 128484, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 13:18:47.481   872  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 13:18:48.380   872  1386 I ActivityManager: Killing 3499:com.android.vending/u0a19 (adj 15): empty #17
,08-25 13:18:48.481   872  2149 D WifiService: setWifiEnabled: false pid=3841, uid=10000
,08-25 13:18:48.481   872  2149 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 13:18:48.518  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 13:18:48.524   872  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-25 13:18:48.525   872  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 13:18:48.525   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 13:18:48.525   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 13:18:48.540   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-25 13:18:48.540   872  1877 D DhcpClient: Clearing IP address
,08-25 13:18:48.544   371   870 D CommandListener: Setting iface cfg
08-25 13:18:48.550  1522  4246 V NativeCrypto: Read error: ssl=0x9aca9c00: I/O error during system call, Connection timed out
08-25 13:18:48.555  1522  4246 V NativeCrypto: SSL shutdown failed: ssl=0x9aca9c00: I/O error during system call, Broken pipe
08-25 13:18:48.560   872  2009 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-25 13:18:48.561   872  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-25 13:18:48.561   872  4205 D DhcpClient: Receive thread stopped
,08-25 13:18:48.564   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-25 13:18:48.564   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-25 13:18:48.568   394   394 E Parcel  : Reading a NULL string not supported here.
08-25 13:18:48.573   872  1302 D WifiStateMachine: Start Disconnecting Watchdog 2
08-25 13:18:48.575   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 13:18:48.575   872  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-25 13:18:48.576   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-25 13:18:48.577   872  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-25 13:18:48.620   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 13:18:48.638   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 13:18:48.639   872  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 13:18:48.639   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:18:48.641   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-25 13:18:48.644  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:48.644  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:48.644  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:48.644  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:48.644  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:48.644  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:48.644  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:48.644  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:48.644  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:48.644  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:48.644  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:48.645  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:48.645  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:48.645  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:48.645  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:48.645  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:18:48.645  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:48.645  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:48.645  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:48.645  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:48.645  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:48.645  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:48.648   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 13:18:48.653  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:48.653  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:48.653  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:48.653  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:48.653  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:48.653  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:48.653  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:48.653  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:48.653  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:18:48.653  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:48.653  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:48.654  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:48.654  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:48.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:48.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:48.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:48.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:48.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:48.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:48.654  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:48.654  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:48.654  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:18:48.655  2168  2341 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 13:18:48.656  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 13:18:48.656   872  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 13:18:48.659  1742  1742 D SystemUpdateService: onCreate
08-25 13:18:48.663  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 13:18:48.673  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-25 13:18:48.682  1742  2418 I iu.UploadsManager: num queued entries: 0
,08-25 13:18:48.682  1742  2418 I iu.UploadsManager: num updated entries: 0
08-25 13:18:48.683  1742  2418 I iu.SyncManager: NEXT; no task
,08-25 13:18:48.685  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 13:18:48.686  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 13:18:48.688  4026  4026 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:18:48.685  1742  4260 I SystemUpdateService: active receiver: enabled
,08-25 13:18:48.693  4026  4026 D SprintDMHelper: simOperator: 
,08-25 13:18:48.694  4026  4026 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 13:18:48.702  1742  4260 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 13:18:48.708  3959  4264 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 13:18:48.714  1742  4260 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 13:18:48.718  1742  4260 I SystemUpdateService: now status is 0 (complete)
,08-25 13:18:48.718  1742  4260 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-25 13:18:48.718  1742  4260 I SystemUpdateService: file has been verified
08-25 13:18:48.718  1742  4260 I SystemUpdateService: OTA package size = 12249756
,08-25 13:18:48.731   371   870 E Netd    : netlink response contains error (No such file or directory)
,08-25 13:18:48.738   872  1304 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-25 13:18:48.738   872  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 13:18:48.739  1742  4260 I SystemUpdateService: showing system update notification
,08-25 13:18:48.747  1742  1742 D SystemUpdateService: onDestroy
,08-25 13:18:49.132   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-25 13:18:49.140  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-25 13:18:49.161   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 13:18:49.161   872   892 I Adreno  : Build Date                       : 10/20/15
08-25 13:18:49.161   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 13:18:49.161   872   892 I Adreno  : Local Branch                     : M14
08-25 13:18:49.161   872   892 I Adreno  : Remote Branch                    : 
08-25 13:18:49.161   872   892 I Adreno  : Remote Branch                    : 
08-25 13:18:49.161   872   892 I Adreno  : Reconstruct Branch               : 
,08-25 13:18:49.207   281   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (204 us)
,08-25 13:18:49.854  3841  3841 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 13:18:49.854  3841  3841 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 13:18:49.888  3841  3841 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f7e2a74 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@dcec21e, 16908290=android.view.AbsSavedState$1@dcec21e}, android:focusedViewId=100}]}]
,08-25 13:18:49.888  3841  3841 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-25 13:18:49.889   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
08-25 13:18:49.889  3841  3841 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 13:18:49.890  3841  3841 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 13:18:49.906   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-25 13:18:49.912   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-25 13:18:49.914   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-25 13:18:49.914   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-25 13:18:49.930   872   881 I art     : Background partial concurrent mark sweep GC freed 62436(3MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 1.553ms total 108.374ms
,08-25 13:18:50.141   281   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-25 13:18:50.143   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-25 13:18:50.144   872  1328 D SurfaceControl: Excessive delay in setPowerMode(): 231ms
,08-25 13:18:50.146   872   892 I DreamManagerService: Entering dreamland.
,08-25 13:18:50.150   872   892 I PowerManagerService: Dozing...
,08-25 13:18:50.154   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-25 13:18:50.212   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-25 13:18:50.212   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-25 13:18:50.215   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 13:18:50.221   872  1302 E native  : do suspend false
,08-25 13:18:50.232  1897  4271 D NfcService: Discovery configuration equal, not updating.
,08-25 13:18:50.259   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 13:18:50.261   872  1302 E native  : do suspend true
,08-25 13:18:50.351   375  1311 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-25 13:18:50.351   375  1311 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-25 13:18:51.339  4172  4208 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-25 13:18:51.516   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9a04dc8:true
,08-25 13:18:51.517  4012  4012 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 13:18:51.520  4160  4225 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-25 13:18:51.526  4012  4012 I bt_bluedroid: init
,08-25 13:18:51.527  4012  4279 I BluetoothAdapterState: Entering OffState
,08-25 13:18:51.532  4012  4280 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 13:18:51.533  4012  4280 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 13:18:51.533  4012  4280 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 13:18:51.533  4012  4280 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 13:18:51.535  4012  4012 I bt_bluedroid: get_profile_interface socket
,08-25 13:18:51.539  4012  4283 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 13:18:51.540  4012  4012 I bt_bluedroid: get_profile_interface sdp
08-25 13:18:51.541  4012  4283 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 13:18:51.545  4012  4022 I bt_bluedroid: config_hci_snoop_log
,08-25 13:18:51.547   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 13:18:51.553  4012  4279 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 13:18:51.554  4012  4279 D BluetoothAdapterProperties: Setting state to 14
,08-25 13:18:51.555  4012  4279 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 13:18:51.559  4012  4279 D BluetoothBondStateMachine: make
,08-25 13:18:51.563  4012  4284 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 13:18:51.569  4012  4279 I BluetoothAdapterState: Entering PendingCommandState
,08-25 13:18:51.572  4012  4012 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 13:18:51.579  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:18:51.581  4012  4012 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 13:18:51.582  4012  4012 D BtGatt.GattService: Received start request. Starting profile...
,08-25 13:18:51.582  4012  4012 D BtGatt.GattService: start()
,08-25 13:18:51.583  4012  4012 I bt_bluedroid: get_profile_interface gatt
,08-25 13:18:51.585  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:18:51.585  4012  4012 D BtGatt.AdvertiseManager: advertise manager created
,08-25 13:18:51.595  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-25 13:18:51.595  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:51.595  4012  4012 V BluetoothAdapterState: isBleTurningOn()=true
08-25 13:18:51.595  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 13:18:51.596  4012  4279 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-25 13:18:51.597  4012  4279 I bt_bluedroid: enable
,08-25 13:18:51.597  4012  4280 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 13:18:51.598  4012  4280 I bt_hci  : start_up
,08-25 13:18:51.608  4012  4280 I bt_vendor: alloc value 0xb39b9189
,08-25 13:18:51.608  4012  4280 I bt_vendor: init
08-25 13:18:51.608  4012  4280 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 13:18:51.608  4012  4280 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 13:18:51.715  4012  4280 D bt_hci  : start_up starting async portion
,08-25 13:18:51.715  4012  4287 I bt_hci  : event_finish_startup
08-25 13:18:51.715  4012  4287 I bt_hci_h4: hal_open
08-25 13:18:51.716  4012  4287 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 13:18:51.725  4012  4287 I bt_userial_vendor: device fd = 51 open
,08-25 13:18:51.758  4012  4287 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 13:18:51.790  4012  4287 D bt_hwcfg: Chipset BCM4354A2
08-25 13:18:51.790  4012  4287 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 13:18:51.791  4012  4287 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 13:18:52.441  4012  4287 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 13:18:52.442  4012  4287 D bt_hwcfg: Settlement delay -- 100 ms
08-25 13:18:52.443  4012  4287 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 13:18:52.559  4012  4287 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 13:18:52.561  4012  4287 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 13:18:52.589  4012  4287 I bt_hwcfg: vendor lib fwcfg completed
,08-25 13:18:52.589  4012  4287 I bt_vendor: firmware callback
08-25 13:18:52.590  4012  4287 I bt_hci  : firmware_config_callback
,08-25 13:18:52.601  4012  4289 I bt_btu  : btu_task pending for preload complete event
,08-25 13:18:52.601  4012  4289 I bt_btu_task: Bluetooth chip preload is complete
08-25 13:18:52.601  4012  4289 I bt_btu  : btu_task received preload complete event
,08-25 13:18:52.611  4012  4289 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 13:18:52.611  4012  4289 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-25 13:18:52.611  4012  4289 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 13:18:52.611  4012  4289 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 13:18:52.612  4012  4289 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-25 13:18:52.612  4012  4289 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 13:18:52.612  4012  4289 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-25 13:18:52.612  4012  4289 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 13:18:52.613  4012  4289 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 13:18:52.613  4012  4289 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 13:18:52.613  4012  4289 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 13:18:52.613  4012  4289 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 13:18:52.614  4012  4289 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 13:18:52.614  4012  4289 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 13:18:52.614  4012  4289 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 13:18:52.750  4012  4289 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,08-25 13:18:52.750  4012  4289 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-25 13:18:52.759  4012  4283 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 13:18:52.760  4012  4283 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 13:18:52.761  4012  4283 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 13:18:52.766  4012  4283 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 13:18:52.769  4012  4283 D BluetoothAdapterProperties: Scan Mode:20
,08-25 13:18:52.771  4012  4283 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 13:18:52.772  4012  4283 D bt_hci  : do_postload posting postload work item
,08-25 13:18:52.772  4012  4287 I bt_hci  : event_postload
,08-25 13:18:52.772  4012  4287 I bt_vendor: sco_config_cb
,08-25 13:18:52.772  4012  4287 I bt_hci  : sco_config_callback postload finished.
,08-25 13:18:52.774  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:52.776  4012  4283 D bt_bte_conf: Device ID record 1 : primary
,08-25 13:18:52.776  4012  4283 D bt_bte_conf:   vendorId            = 000f
,08-25 13:18:52.776  4012  4283 D bt_bte_conf:   vendorIdSource      = 0001
08-25 13:18:52.776  4012  4283 D bt_bte_conf:   product             = 1200
,08-25 13:18:52.776  4012  4283 D bt_bte_conf:   version             = 1436
08-25 13:18:52.777  4012  4283 D bt_bte_conf:   clientExecutableURL = 
,08-25 13:18:52.777  4012  4283 D bt_bte_conf:   serviceDescription  = 
08-25 13:18:52.777  4012  4283 D bt_bte_conf:   documentationURL    = 
,08-25 13:18:52.778  4012  4283 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 13:18:52.778  4012  4287 I bt_vendor: low_power_mode_cb
,08-25 13:18:52.778  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:52.778  4012  4280 D bt_stack_manager: event_start_up_stack finished
,08-25 13:18:52.779  4012  4279 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 13:18:52.780  4012  4279 D BluetoothAdapterProperties: Setting state to 15
,08-25 13:18:52.780  4012  4279 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 13:18:52.781  4012  4279 I BluetoothAdapterState: Entering BleOnState
,08-25 13:18:52.787  4012  4279 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 13:18:52.787  4012  4279 D BluetoothAdapterProperties: Setting state to 11
08-25 13:18:52.787  4012  4279 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 13:18:52.797  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:52.800  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:52.804  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:18:52.805  4012  4012 D HeadsetService: Received start request. Starting profile...
,08-25 13:18:52.809  4012  4012 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 13:18:52.810  4012  4012 D HeadsetStateMachine: make
,08-25 13:18:52.816  4012  4279 I BluetoothAdapterState: Entering PendingCommandState
,08-25 13:18:52.821  4012  4012 D HeadsetStateMachine: max_hf_connections = 1
,08-25 13:18:52.821  4012  4012 I bt_bluedroid: get_profile_interface handsfree
08-25 13:18:52.822  4012  4283 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 13:18:52.822  4012  4283 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-25 13:18:52.826  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:18:52.827  4012  4012 D A2dpService: Received start request. Starting profile...
,08-25 13:18:52.827  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:52.828  4012  4012 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 13:18:52.828  4012  4012 I bt_bluedroid: get_profile_interface avrcp
,08-25 13:18:52.834  4012  4012 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 13:18:52.834  4012  4012 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 13:18:52.834  4012  4012 D A2dpStateMachine: make
,08-25 13:18:52.835  4012  4012 I bt_bluedroid: get_profile_interface a2dp
,08-25 13:18:52.836  4012  4283 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 13:18:52.837  4012  4298 D A2dpStateMachine: Enter Disconnected: -2
,08-25 13:18:52.838  4012  4012 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 13:18:52.838  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:18:52.840  4012  4012 D HidService: Received start request. Starting profile...
08-25 13:18:52.840  4012  4012 I bt_bluedroid: get_profile_interface hidhost
08-25 13:18:52.840  4012  4012 D HidService: setHidService(): set to: null
08-25 13:18:52.840  4012  4283 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-25 13:18:52.840  3910  3910 D BluetoothInputDevice: Proxy object connected
08-25 13:18:52.840  4012  4283 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 13:18:52.841  4012  4012 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 13:18:52.841  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:18:52.842  4012  4012 D HealthService: Received start request. Starting profile...
,08-25 13:18:52.842  3910  3910 D HidProfile: Bluetooth service connected
,08-25 13:18:52.843  4012  4012 I bt_bluedroid: get_profile_interface health
,08-25 13:18:52.844  4012  4012 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 13:18:52.845  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:18:52.846  4012  4012 D PanService: Received start request. Starting profile...
,08-25 13:18:52.846  3910  3910 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 13:18:52.846  4012  4012 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 13:18:52.846  4012  4012 I bt_bluedroid: get_profile_interface pan
08-25 13:18:52.847  4012  4283 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 13:18:52.847  3910  3910 D PanProfile: Bluetooth service connected
,08-25 13:18:52.849  4012  4012 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:18:52.850  4012  4012 D BluetoothMapService: Received start request. Starting profile...
08-25 13:18:52.850  4012  4012 D BluetoothMapService: start()
08-25 13:18:52.850  3910  3910 D BluetoothMap: Proxy object connected
,08-25 13:18:52.851  3910  3910 D MapProfile: Bluetooth service connected
08-25 13:18:52.851  3910  3910 D BluetoothMap: getConnectedDevices()
,08-25 13:18:52.852  3910  3910 D BluetoothMap: Bluetooth is Not enabled
08-25 13:18:52.852  4012  4012 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 13:18:52.852  4012  4012 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 13:18:52.853  4012  4012 D BluetoothMapAppObserver: createReceiver()
08-25 13:18:52.853  4012  4012 D BluetoothMapAppObserver: initObservers()
,08-25 13:18:52.854  4012  4012 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 13:18:52.860  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-25 13:18:52.860  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-25 13:18:52.860  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:52.860  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 13:18:52.862  4012  4296 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 13:18:52.864  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-25 13:18:52.864  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-25 13:18:52.864  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:52.864  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:52.864  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-25 13:18:52.864  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-25 13:18:52.864  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:52.864  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isTurningOff()=false
08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isTurningOn()=true
08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 13:18:52.865  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:52.866  4012  4279 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 13:18:52.866  4012  4279 D BluetoothAdapterProperties: ScanMode =  20
,08-25 13:18:52.866  4012  4279 D BluetoothAdapterProperties: State =  11
08-25 13:18:52.866  4012  4279 D BluetoothAdapterProperties: Setting state to 12
08-25 13:18:52.866  4012  4279 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 13:18:52.867  4012  4279 I BluetoothAdapterState: Entering OnState
08-25 13:18:52.867  1372  1387 D BluetoothPan: onBluetoothStateChange on: true
08-25 13:18:52.867  4012  4283 D BluetoothAdapterProperties: Scan Mode:21
08-25 13:18:52.867  4012  4283 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 13:18:52.869  1911  1924 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 13:18:52.870  1372  2033 D BluetoothMap: onBluetoothStateChange: up=true
08-25 13:18:52.870  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 13:18:52.870  1372  1372 D PanProfile: Bluetooth service connected
08-25 13:18:52.871  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:52.871  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:52.871  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:52.871  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:52.871  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:52.871  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:52.871  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:52.871  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:52.871  1372  1372 D BluetoothMap: Proxy object connected
,08-25 13:18:52.872  1372  1372 D MapProfile: Bluetooth service connected
08-25 13:18:52.872  1372  1372 D BluetoothMap: getConnectedDevices()
08-25 13:18:52.872   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 13:18:52.873   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:18:52.873  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:18:52.873  3910  3922 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 13:18:52.873   872   872 D BluetoothA2dp: Proxy object connected
08-25 13:18:52.875   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:18:52.875  1372  1387 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:18:52.876  1372  1385 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 13:18:52.877  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:52.877  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:52.877  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:52.877  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:52.877  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:18:52.877  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:52.877  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:52.877  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:52.878  1372  1372 D BluetoothA2dp: Proxy object connected
08-25 13:18:52.879  1372  1387 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 13:18:52.879  4012  4012 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 13:18:52.880  4012  4012 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-25 13:18:52.880  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:18:52.881  3910  3920 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 13:18:52.881  4012  4012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:18:52.881  1372  1372 D BluetoothInputDevice: Proxy object connected
08-25 13:18:52.881  1372  1385 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 13:18:52.881  1372  1372 D HidProfile: Bluetooth service connected
08-25 13:18:52.884  3910  3922 D BluetoothMap: onBluetoothStateChange: up=true
08-25 13:18:52.884  4012  4012 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:18:52.885  3910  3920 D BluetoothPan: onBluetoothStateChange on: true
,08-25 13:18:52.885   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:18:52.886  4012  4012 D ObexServerSockets: Succeed to create listening sockets 
08-25 13:18:52.886  4012  4012 D ObexServerSockets0: startAccept()
,08-25 13:18:52.886  4012  4012 D ObexServerSockets0: prepareForNewConnect()
08-25 13:18:52.886   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 13:18:52.888  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:52.890  3910  3910 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 13:18:52.890  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:52.892  4012  4012 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-25 13:18:52.893  4012  4012 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 13:18:52.893  4012  4304 D ObexServerSockets0: Accepting socket connection...
08-25 13:18:52.894  4012  4012 D BluetoothMapService: onReceive
08-25 13:18:52.894  4012  4012 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:18:52.894  4012  4012 D BluetoothMapService: STATE_ON
08-25 13:18:52.894  4012  4305 D ObexServerSockets0: Accepting socket connection...
08-25 13:18:52.894  3910  3910 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-25 13:18:52.900  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 13:18:52.904  3910  3910 D BluetoothA2dp: Proxy object connected
,08-25 13:18:52.907  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:52.917  1372  1372 D BluetoothPbap: Proxy object connected
08-25 13:18:52.917  1372  1372 D PbapServerProfile: Bluetooth service connected
,08-25 13:18:52.920  3910  3910 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:18:52.921  3910  3910 D BluetoothPbap: Proxy object connected
,08-25 13:18:52.921  3910  3910 D PbapServerProfile: Bluetooth service connected
08-25 13:18:52.924  4012  4012 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 13:18:52.924  4012  4012 D ObexServerSockets0: prepareForNewConnect()
,08-25 13:18:52.927  4012  4309 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:18:52.940  4012  4313 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:18:52.942  4012  4313 I BtOppRfcommListener: Accept thread started.
,08-25 13:18:52.972  1911  2085 D BluetoothHeadset: Proxy object connected
,08-25 13:18:52.973   872   872 D BluetoothHeadset: Proxy object connected
08-25 13:18:52.973   872   872 D BluetoothHeadset: Proxy object connected
,08-25 13:18:52.973   872   872 D BluetoothHeadset: Proxy object connected
,08-25 13:18:52.974   872   889 D BluetoothHeadset: Proxy object connected
08-25 13:18:52.974  1372  1387 D BluetoothHeadset: Proxy object connected
08-25 13:18:52.974  1372  1372 D HeadsetProfile: Bluetooth service connected
08-25 13:18:52.975   872   889 D BluetoothHeadset: Proxy object connected
,08-25 13:18:52.975  1372  2033 D BluetoothHeadset: Proxy object connected
,08-25 13:18:52.979  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-25 13:18:52.985   872   889 D BluetoothHeadset: Proxy object connected
,08-25 13:18:52.998  3910  3922 D BluetoothHeadset: Proxy object connected
,08-25 13:18:52.999  3910  3910 D HeadsetProfile: Bluetooth service connected
,08-25 13:18:54.411   872  1304 D ConnectivityService: handlePromptUnvalidated 101
,08-25 13:18:54.498  4012  4279 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 13:18:54.499  4012  4279 D BluetoothAdapterProperties: Setting state to 13
08-25 13:18:54.499  4012  4279 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-25 13:18:54.505  4012  4279 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 13:18:54.515  4012  4012 D BluetoothMapService: onReceive
08-25 13:18:54.517  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:54.515  4012  4012 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-25 13:18:54.517  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:54.517  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:54.517  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:54.517  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:54.517  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:54.517  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:54.517  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:54.517  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:54.517  4012  4012 D BluetoothMapService: STATE_TURNING_OFF
,08-25 13:18:54.518  4012  4012 D BluetoothMapService: MAP Service closeService in
08-25 13:18:54.519  4012  4012 D BluetoothMapMasInstance0: MAP Service shutdown
08-25 13:18:54.519  4012  4012 D ObexServerSockets0: shutdown(block = true)
08-25 13:18:54.520  4012  4304 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 13:18:54.521  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:54.521  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:18:54.521  4012  4283 D BluetoothAdapterProperties: Scan Mode:20
08-25 13:18:54.522  4012  4279 I BluetoothAdapterState: Entering PendingCommandState
08-25 13:18:54.522  4012  4279 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 13:18:54.525  4012  4012 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 13:18:54.526  4012  4012 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 13:18:54.526  4012  4305 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 13:18:54.528  4012  4012 I BtOppRfcommListener: stopping Accept Thread
08-25 13:18:54.528  4012  4292 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 13:18:54.528  4012  4313 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 13:18:54.529  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 13:18:54.529  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:18:54.529  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:18:54.529  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:18:54.529  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:18:54.529  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 13:18:54.529  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:18:54.529  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:18:54.529  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:18:54.531  3841  3841 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 13:18:54.531  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 13:18:54.531  4012  4313 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 13:18:54.535  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:54.537  4012  4012 D HeadsetService: Received stop request...Stopping profile...
08-25 13:18:54.538  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:54.541  1911  2120 D BluetoothHeadset: Proxy object disconnected
08-25 13:18:54.541   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 13:18:54.541   872   872 D BluetoothHeadset: Proxy object disconnected
08-25 13:18:54.541   872   872 D BluetoothHeadset: Proxy object disconnected
,08-25 13:18:54.542  3910  3920 D BluetoothHeadset: Proxy object disconnected
,08-25 13:18:54.542  1372  1387 D BluetoothHeadset: Proxy object disconnected
08-25 13:18:54.542  1372  1372 D HeadsetProfile: Bluetooth service disconnected
08-25 13:18:54.543  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 13:18:54.544  4012  4012 D A2dpService: Received stop request...Stopping profile...
08-25 13:18:54.544  4012  4298 D A2dpStateMachine: Exit Disconnected: -1
,08-25 13:18:54.549   872   872 D BluetoothA2dp: Proxy object disconnected
,08-25 13:18:54.549  1372  1372 D BluetoothA2dp: Proxy object disconnected
,08-25 13:18:54.550  4012  4012 D HidService: Received stop request...Stopping profile...
08-25 13:18:54.550  4012  4012 D HidService: Stopping Bluetooth HidService
,08-25 13:18:54.553  3910  3910 D HeadsetProfile: Bluetooth service disconnected
08-25 13:18:54.553  1372  1372 D BluetoothInputDevice: Proxy object disconnected
08-25 13:18:54.553  1372  1372 D HidProfile: Bluetooth service disconnected
08-25 13:18:54.554  4012  4012 D HealthService: Received stop request...Stopping profile...
,08-25 13:18:54.555  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:54.555  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:54.555  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:54.555  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 13:18:54.556  4012  4012 D PanService: Received stop request...Stopping profile...
,08-25 13:18:54.557  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 13:18:54.557  1372  1372 D PanProfile: Bluetooth service disconnected
,08-25 13:18:54.559  4012  4012 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-25 13:18:54.560  4012  4012 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 13:18:54.560  3910  3910 D DockEventReceiver: finishStartingService: stopping service
08-25 13:18:54.560  4012  4283 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 13:18:54.560  4012  4289 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 13:18:54.560  4012  4289 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 13:18:54.560  4012  4289 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 13:18:54.561  4012  4283 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-25 13:18:54.561  4012  4012 D BluetoothMapService: Received stop request...Stopping profile...
08-25 13:18:54.561  4012  4012 D BluetoothMapService: stop()
,08-25 13:18:54.561  3910  3910 D BluetoothA2dp: Proxy object disconnected
08-25 13:18:54.561  3910  3910 D BluetoothInputDevice: Proxy object disconnected
,08-25 13:18:54.561  3910  3910 D HidProfile: Bluetooth service disconnected
08-25 13:18:54.562  4012  4012 D BluetoothMapAppObserver: deinitObservers()
08-25 13:18:54.562  3910  3910 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-25 13:18:54.562  4012  4012 D BluetoothMapAppObserver: removeReceiver()
08-25 13:18:54.562  3910  3910 D PanProfile: Bluetooth service disconnected
,08-25 13:18:54.565  1372  1372 D BluetoothMap: Proxy object disconnected
08-25 13:18:54.565  1372  1372 D MapProfile: Bluetooth service disconnected
08-25 13:18:54.565  4012  4012 V BluetoothAdapterState: isTurningOff()=true
,08-25 13:18:54.565  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:54.565  3910  3910 D BluetoothMap: Proxy object disconnected
08-25 13:18:54.565  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 13:18:54.565  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 13:18:54.565  3910  3910 D MapProfile: Bluetooth service disconnected
08-25 13:18:54.567  4012  4289 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 13:18:54.567  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:54.567  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:54.567  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:54.567  4012  4289 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 13:18:54.567  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:54.567  4012  4283 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-25 13:18:54.567  4012  4289 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 13:18:54.568  4012  4289 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 13:18:54.568  4012  4289 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 13:18:54.568  4012  4289 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 13:18:54.570  4012  4012 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 13:18:54.570  4012  4283 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 13:18:54.571  4012  4012 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 13:18:54.571  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 13:18:54.571  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:54.572  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:54.572  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:54.572  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:54.572  4012  4012 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 13:18:54.572  4012  4283 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 13:18:54.573  4012  4012 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 13:18:54.573  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:54.573  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:54.573  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:54.573  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:54.573  4012  4012 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 13:18:54.573  4012  4012 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 13:18:54.574  4012  4012 D BluetoothMapService: MAP Service closeService in
08-25 13:18:54.574  4012  4012 V BluetoothAdapterState: isTurningOff()=true
08-25 13:18:54.574  4012  4012 V BluetoothAdapterState: isTurningOn()=false
08-25 13:18:54.574  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:18:54.574  4012  4012 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:18:54.575  4012  4279 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 13:18:54.575  4012  4279 D BluetoothAdapterProperties: Setting state to 15
08-25 13:18:54.575  4012  4279 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 13:18:54.575  1372  1387 D BluetoothPan: onBluetoothStateChange on: false
08-25 13:18:54.576  4012  4279 I BluetoothAdapterState: Entering BleOnState
08-25 13:18:54.575  4012  4012 D BluetoothMapService: cleanup()
08-25 13:18:54.576  4012  4012 D BluetoothMapService: MAP Service closeService in
08-25 13:18:54.576  1911  1923 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:18:54.577  3910  3920 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:18:54.578  1372  1372 D BluetoothPbap: Proxy object disconnected
08-25 13:18:54.578  1372  1372 D PbapServerProfile: Bluetooth service disconnected
08-25 13:18:54.578  1372  1385 D BluetoothMap: onBluetoothStateChange: up=false
08-25 13:18:54.578  3910  3910 D BluetoothPbap: Proxy object disconnected
08-25 13:18:54.578  3910  3910 D PbapServerProfile: Bluetooth service disconnected
08-25 13:18:54.579   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 13:18:54.581   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 13:18:54.583  3910  3920 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 13:18:54.585   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 13:18:54.586  1372  2033 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:18:54.586  1372  1387 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 13:18:54.587  1372  1385 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 13:18:54.587  3910  3922 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 13:18:54.588  1372  2033 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 13:18:54.589  3910  3920 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 13:18:54.589  3910  3922 D BluetoothPan: onBluetoothStateChange on: false
,08-25 13:18:54.590  3910  3920 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-25 13:18:54.591   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 13:18:54.591  4012  4279 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 13:18:54.591  4012  4279 D BluetoothAdapterProperties: Setting state to 16
08-25 13:18:54.591  4012  4279 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-25 13:18:54.592  4012  4279 D BluetoothAdapterProperties: onBleDisable
08-25 13:18:54.592  4012  4279 I BluetoothAdapterState: Entering PendingCommandState
08-25 13:18:54.592  4012  4280 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-25 13:18:54.594  4012  4289 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 13:18:54.594  4012  4289 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 13:18:54.602  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:54.604  4012  4283 D BluetoothAdapterProperties: Scan Mode:20
,08-25 13:18:54.605  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:18:54.605  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 13:18:54.606  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:54.607  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:18:54.610  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 13:18:54.612  3910  3910 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:18:54.795  4012  4283 I bt_hci  : shut_down
,08-25 13:18:54.796  4012  4287 D bt_hwcfg: hw_epilog_process
,08-25 13:18:54.799  4012  4287 I bt_vendor: low_power_mode_cb
,08-25 13:18:54.820  4012  4287 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 13:18:54.820  4012  4287 I bt_vendor: epilog_cb
,08-25 13:18:54.820  4012  4287 I bt_hci  : epilog_finished_callback
,08-25 13:18:54.832  4012  4283 I bt_hci_h4: hal_close
,08-25 13:18:54.833  4012  4283 I bt_userial_vendor: device fd = 51 close
,08-25 13:18:54.956  4012  4280 D bt_stack_manager: event_shut_down_stack finished.
,08-25 13:18:54.957  4012  4279 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 13:18:54.963  4012  4012 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 13:18:54.963  4012  4279 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-25 13:18:54.964  4012  4012 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 13:18:54.965  4012  4012 D BtGatt.GattService: stop()
08-25 13:18:54.966  4012  4012 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 13:18:54.971  4012  4012 V BluetoothAdapterState: isTurningOff()=false
,08-25 13:18:54.971  4012  4012 V BluetoothAdapterState: isTurningOn()=false
,08-25 13:18:54.972  4012  4012 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 13:18:54.972  4012  4012 V BluetoothAdapterState: isBleTurningOff()=true
08-25 13:18:54.973  4012  4279 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 13:18:54.974  4012  4279 D BluetoothAdapterProperties: Setting state to 10
08-25 13:18:54.975  4012  4279 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-25 13:18:54.978   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-25 13:18:54.978  4012  4279 I BluetoothAdapterState: Entering OffState
,08-25 13:18:55.008  4012  4012 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 13:18:55.008  4012  4012 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 13:18:55.009  4012  4280 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 13:18:55.019  4012  4280 D bt_stack_manager: event_clean_up_stack finished.
,08-25 13:18:55.020  4012  4012 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 13:18:55.029  4012  4012 I art     : System.exit called, status: 0
08-25 13:18:55.029  4012  4012 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 13:18:55.097   872  2009 I ActivityManager: Process com.android.bluetooth (pid 4012) has died
,08-25 13:18:55.651  2168  2642 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-25 13:18:57.496  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 13:18:57.496  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:19:00.504  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:00.504  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@161faff added. We now have 6 listener(s)
,08-25 13:19:00.505  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:19:00.508  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:19:00.509  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16bc0cc added. We now have 7 listener(s)
,08-25 13:19:00.509  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:00.511  3841  3891 I System.out: IsBluetoothEnabled
,08-25 13:19:00.523  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:00.575   872   889 I ActivityManager: Start proc 4325:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 13:19:00.698  4325  4325 D AdapterServiceConfig: Adding HeadsetService
,08-25 13:19:00.698  4325  4325 D AdapterServiceConfig: Adding A2dpService
,08-25 13:19:00.698  4325  4325 D AdapterServiceConfig: Adding HidService
,08-25 13:19:00.698  4325  4325 D AdapterServiceConfig: Adding HealthService
,08-25 13:19:00.699  4325  4325 D AdapterServiceConfig: Adding PanService
08-25 13:19:00.699  4325  4325 D AdapterServiceConfig: Adding GattService
08-25 13:19:00.699  4325  4325 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 13:19:00.718   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93392a5:true
,08-25 13:19:00.718  4325  4325 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 13:19:00.722  4325  4325 I bt_bluedroid: init
,08-25 13:19:00.723  4325  4337 I BluetoothAdapterState: Entering OffState
,08-25 13:19:00.729  4325  4338 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 13:19:00.730  4325  4338 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 13:19:00.730  4325  4338 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 13:19:00.730  4325  4338 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 13:19:00.732  4325  4325 I bt_bluedroid: get_profile_interface socket
08-25 13:19:00.734  4325  4325 I bt_bluedroid: get_profile_interface sdp
,08-25 13:19:00.738  4325  4341 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 13:19:00.739  4325  4336 I bt_bluedroid: config_hci_snoop_log
,08-25 13:19:00.741  4325  4341 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 13:19:00.742   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 13:19:00.750  4325  4337 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 13:19:00.751  4325  4337 D BluetoothAdapterProperties: Setting state to 14
,08-25 13:19:00.751  4325  4337 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-25 13:19:00.752  4325  4337 D BluetoothBondStateMachine: make
,08-25 13:19:00.756  4325  4342 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 13:19:00.761  4325  4337 I BluetoothAdapterState: Entering PendingCommandState
,08-25 13:19:00.763  4325  4325 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 13:19:00.767  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:19:00.768  4325  4325 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 13:19:00.769  4325  4325 D BtGatt.GattService: Received start request. Starting profile...
,08-25 13:19:00.769  4325  4325 D BtGatt.GattService: start()
,08-25 13:19:00.769  4325  4325 I bt_bluedroid: get_profile_interface gatt
,08-25 13:19:00.770  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
08-25 13:19:00.770  4325  4325 D BtGatt.AdvertiseManager: advertise manager created
,08-25 13:19:00.781  4325  4325 V BluetoothAdapterState: isTurningOff()=false
,08-25 13:19:00.781  4325  4325 V BluetoothAdapterState: isTurningOn()=false
,08-25 13:19:00.781  4325  4325 V BluetoothAdapterState: isBleTurningOn()=true
08-25 13:19:00.781  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:19:00.782  4325  4337 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-25 13:19:00.782  4325  4337 I bt_bluedroid: enable
,08-25 13:19:00.783  4325  4338 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 13:19:00.783  4325  4338 I bt_hci  : start_up
,08-25 13:19:00.804  4325  4338 I bt_vendor: alloc value 0xb3a25189
,08-25 13:19:00.804  4325  4338 I bt_vendor: init
08-25 13:19:00.804  4325  4338 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 13:19:00.804  4325  4338 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 13:19:00.914  4325  4338 D bt_hci  : start_up starting async portion
,08-25 13:19:00.915  4325  4345 I bt_hci  : event_finish_startup
,08-25 13:19:00.915  4325  4345 I bt_hci_h4: hal_open
08-25 13:19:00.915  4325  4345 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 13:19:00.926  4325  4345 I bt_userial_vendor: device fd = 51 open
,08-25 13:19:00.953  4325  4345 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 13:19:00.986  4325  4345 D bt_hwcfg: Chipset BCM4354A2
08-25 13:19:00.986  4325  4345 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 13:19:00.987  4325  4345 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 13:19:01.650  4325  4345 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 13:19:01.652  4325  4345 D bt_hwcfg: Settlement delay -- 100 ms
,08-25 13:19:01.652  4325  4345 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 13:19:01.770  4325  4345 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 13:19:01.771  4325  4345 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 13:19:01.799  4325  4345 I bt_hwcfg: vendor lib fwcfg completed
,08-25 13:19:01.800  4325  4345 I bt_vendor: firmware callback
08-25 13:19:01.800  4325  4345 I bt_hci  : firmware_config_callback
,08-25 13:19:01.813  4325  4347 I bt_btu  : btu_task pending for preload complete event
,08-25 13:19:01.813  4325  4347 I bt_btu_task: Bluetooth chip preload is complete
08-25 13:19:01.813  4325  4347 I bt_btu  : btu_task received preload complete event
,08-25 13:19:01.823  4325  4347 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 13:19:01.824  4325  4347 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 13:19:01.824  4325  4347 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-25 13:19:01.824  4325  4347 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 13:19:01.825  4325  4347 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 13:19:01.825  4325  4347 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 13:19:01.825  4325  4347 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-25 13:19:01.825  4325  4347 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 13:19:01.826  4325  4347 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 13:19:01.826  4325  4347 I         : BTE_InitTraceLevels -- TRC_PAN
,08-25 13:19:01.826  4325  4347 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 13:19:01.826  4325  4347 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 13:19:01.827  4325  4347 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 13:19:01.827  4325  4347 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-25 13:19:01.827  4325  4347 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 13:19:01.966  4325  4347 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39a2d9d
,08-25 13:19:01.966  4325  4347 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39a2d9d 
,08-25 13:19:01.992  4325  4341 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 13:19:01.993  4325  4341 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 13:19:01.993  4325  4341 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 13:19:01.997  4325  4341 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 13:19:01.999  4325  4341 D BluetoothAdapterProperties: Scan Mode:20
,08-25 13:19:01.999  4325  4341 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 13:19:02.001  4325  4341 D bt_hci  : do_postload posting postload work item
,08-25 13:19:02.001  4325  4345 I bt_hci  : event_postload
,08-25 13:19:02.002  4325  4345 I bt_vendor: sco_config_cb
,08-25 13:19:02.002  4325  4345 I bt_hci  : sco_config_callback postload finished.
,08-25 13:19:02.004  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:02.005  4325  4341 D bt_bte_conf: Device ID record 1 : primary
,08-25 13:19:02.005  4325  4341 D bt_bte_conf:   vendorId            = 000f
,08-25 13:19:02.005  4325  4341 D bt_bte_conf:   vendorIdSource      = 0001
,08-25 13:19:02.005  4325  4341 D bt_bte_conf:   product             = 1200
,08-25 13:19:02.006  4325  4341 D bt_bte_conf:   version             = 1436
,08-25 13:19:02.006  4325  4341 D bt_bte_conf:   clientExecutableURL = 
08-25 13:19:02.006  4325  4341 D bt_bte_conf:   serviceDescription  = 
08-25 13:19:02.006  4325  4341 D bt_bte_conf:   documentationURL    = 
08-25 13:19:02.007  4325  4341 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 13:19:02.007  4325  4338 D bt_stack_manager: event_start_up_stack finished
08-25 13:19:02.008  4325  4337 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 13:19:02.009  4325  4345 I bt_vendor: low_power_mode_cb
08-25 13:19:02.009  4325  4337 D BluetoothAdapterProperties: Setting state to 15
08-25 13:19:02.009  4325  4337 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-25 13:19:02.010  4325  4337 I BluetoothAdapterState: Entering BleOnState
,08-25 13:19:02.013  4325  4337 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 13:19:02.013  4325  4337 D BluetoothAdapterProperties: Setting state to 11
,08-25 13:19:02.014  4325  4337 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-25 13:19:02.019  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
08-25 13:19:02.020  4325  4325 D HeadsetService: Received start request. Starting profile...
08-25 13:19:02.023  4325  4325 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 13:19:02.023  4325  4325 D HeadsetStateMachine: make
08-25 13:19:02.028  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:02.036  4325  4337 I BluetoothAdapterState: Entering PendingCommandState
,08-25 13:19:02.041  4325  4325 D HeadsetStateMachine: max_hf_connections = 1
,08-25 13:19:02.041  4325  4325 I bt_bluedroid: get_profile_interface handsfree
,08-25 13:19:02.042  4325  4341 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-25 13:19:02.044  4325  4341 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-25 13:19:02.046  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:19:02.047  4325  4325 D A2dpService: Received start request. Starting profile...,
,08-25 13:19:02.048  4325  4325 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 13:19:02.048  4325  4325 I bt_bluedroid: get_profile_interface avrcp
,08-25 13:19:02.055  4325  4325 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 13:19:02.055  4325  4325 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-25 13:19:02.055  4325  4325 D A2dpStateMachine: make
,08-25 13:19:02.057  4325  4325 I bt_bluedroid: get_profile_interface a2dp
,08-25 13:19:02.058  4325  4341 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 13:19:02.062  4325  4356 D A2dpStateMachine: Enter Disconnected: -2
,08-25 13:19:02.064  4325  4325 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 13:19:02.065  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:19:02.066  4325  4325 D HidService: Received start request. Starting profile...
,08-25 13:19:02.067  4325  4325 I bt_bluedroid: get_profile_interface hidhost
08-25 13:19:02.067  4325  4341 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39843e5
08-25 13:19:02.068  4325  4341 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-25 13:19:02.068  4325  4325 D HidService: setHidService(): set to: null
,08-25 13:19:02.069  4325  4325 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 13:19:02.071  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:19:02.072  4325  4325 D HealthService: Received start request. Starting profile...
,08-25 13:19:02.074  4325  4325 I bt_bluedroid: get_profile_interface health
,08-25 13:19:02.078  4325  4325 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 13:19:02.079  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:19:02.081  4325  4325 D PanService: Received start request. Starting profile...
08-25 13:19:02.081  4325  4325 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 13:19:02.081  4325  4325 I bt_bluedroid: get_profile_interface pan
,08-25 13:19:02.082  4325  4341 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 13:19:02.085  4325  4325 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
,08-25 13:19:02.086  4325  4325 D BluetoothMapService: Received start request. Starting profile...
08-25 13:19:02.086  4325  4325 D BluetoothMapService: start()
08-25 13:19:02.090  4325  4325 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 13:19:02.091  4325  4325 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-25 13:19:02.091  4325  4325 D BluetoothMapAppObserver: createReceiver()
08-25 13:19:02.093  4325  4325 D BluetoothMapAppObserver: initObservers()
08-25 13:19:02.093  4325  4325 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 13:19:02.107  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 13:19:02.108  4325  4325 V BluetoothAdapterState: isTurningOff()=false
08-25 13:19:02.108  4325  4325 V BluetoothAdapterState: isTurningOn()=true
08-25 13:19:02.108  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:19:02.108  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 13:19:02.112  4325  4353 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 13:19:02.112  4325  4325 V BluetoothAdapterState: isTurningOff()=false
08-25 13:19:02.112  4325  4325 V BluetoothAdapterState: isTurningOn()=true
08-25 13:19:02.112  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:19:02.113  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 13:19:02.113  4325  4325 V BluetoothAdapterState: isTurningOff()=false
08-25 13:19:02.113  4325  4325 V BluetoothAdapterState: isTurningOn()=true
08-25 13:19:02.113  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:19:02.113  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:19:02.113  4325  4325 V BluetoothAdapterState: isTurningOff()=false
,08-25 13:19:02.113  4325  4325 V BluetoothAdapterState: isTurningOn()=true
08-25 13:19:02.113  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:19:02.113  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:19:02.114  4325  4325 V BluetoothAdapterState: isTurningOff()=false
08-25 13:19:02.114  4325  4325 V BluetoothAdapterState: isTurningOn()=true
08-25 13:19:02.114  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:19:02.114  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 13:19:02.114  4325  4325 V BluetoothAdapterState: isTurningOff()=false
08-25 13:19:02.114  4325  4325 V BluetoothAdapterState: isTurningOn()=true
,08-25 13:19:02.114  4325  4325 V BluetoothAdapterState: isBleTurningOn()=false
08-25 13:19:02.114  4325  4325 V BluetoothAdapterState: isBleTurningOff()=false
08-25 13:19:02.115  4325  4337 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 13:19:02.115  4325  4337 D BluetoothAdapterProperties: ScanMode =  20
08-25 13:19:02.115  4325  4337 D BluetoothAdapterProperties: State =  11
,08-25 13:19:02.119  4325  4341 D BluetoothAdapterProperties: Scan Mode:21
,08-25 13:19:02.119  4325  4341 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 13:19:02.119  4325  4337 D BluetoothAdapterProperties: Setting state to 12
08-25 13:19:02.119  4325  4337 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 13:19:02.120  1372  1387 D BluetoothPan: onBluetoothStateChange on: true
,08-25 13:19:02.121  4325  4337 I BluetoothAdapterState: Entering OnState
,08-25 13:19:02.122  1911  2085 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 13:19:02.123  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 13:19:02.123  1372  1372 D PanProfile: Bluetooth service connected
,08-25 13:19:02.127  3910  3922 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 13:19:02.128  1372  1385 D BluetoothMap: onBluetoothStateChange: up=true
08-25 13:19:02.128  4325  4325 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 13:19:02.129  4325  4325 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-25 13:19:02.129  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:02.129  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:02.129  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:19:02.129  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:02.129  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:02.129  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:02.129  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:02.129  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 13:19:02.130   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 13:19:02.131   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:19:02.131  3910  3920 D BluetoothPbap: onBluetoothStateChange: up=true
,08-25 13:19:02.131  4325  4325 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:02.133  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:19:02.134   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 13:19:02.135  1372  1387 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 13:19:02.135  4325  4325 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 13:19:02.136  1372  2033 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 13:19:02.137  4325  4325 D ObexServerSockets: Succeed to create listening sockets 
,08-25 13:19:02.137  4325  4325 D ObexServerSockets0: startAccept()
08-25 13:19:02.137  4325  4325 D ObexServerSockets0: prepareForNewConnect()
08-25 13:19:02.138  1372  1385 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 13:19:02.139  4325  4325 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 13:19:02.139  4325  4325 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-25 13:19:02.141  4325  4361 D ObexServerSockets0: Accepting socket connection...
,08-25 13:19:02.141  1372  1372 D BluetoothMap: Proxy object connected
,08-25 13:19:02.141  1372  1372 D MapProfile: Bluetooth service connected
,08-25 13:19:02.141   872   872 D BluetoothA2dp: Proxy object connected,
08-25 13:19:02.142  1372  1372 D BluetoothMap: getConnectedDevices()
08-25 13:19:02.142  4325  4362 D ObexServerSockets0: Accepting socket connection...
,08-25 13:19:02.143  3910  3922 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 13:19:02.145  1372  1372 D BluetoothA2dp: Proxy object connected
08-25 13:19:02.147  1372  1387 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 13:19:02.147  1372  1372 D BluetoothInputDevice: Proxy object connected
,08-25 13:19:02.147  1372  1372 D HidProfile: Bluetooth service connected
08-25 13:19:02.149  3910  3910 D BluetoothInputDevice: Proxy object connected
,08-25 13:19:02.149  3910  3910 D HidProfile: Bluetooth service connected
08-25 13:19:02.150  3910  3920 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 13:19:02.153  3910  4364 D BluetoothPan: onBluetoothStateChange on: true
,08-25 13:19:02.153  3910  3910 D BluetoothMap: Proxy object connected
,08-25 13:19:02.153  3910  3910 D MapProfile: Bluetooth service connected
08-25 13:19:02.153  3910  3910 D BluetoothMap: getConnectedDevices()
,08-25 13:19:02.157  3910  3920 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 13:19:02.158  3910  3910 D BluetoothPan: BluetoothPAN Proxy object connected
,08-25 13:19:02.158  3910  3910 D PanProfile: Bluetooth service connected
,08-25 13:19:02.159   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 13:19:02.161   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 13:19:02.161  3910  3910 D BluetoothA2dp: Proxy object connected
,08-25 13:19:02.164  4325  4325 D BluetoothMapService: onReceive
08-25 13:19:02.164  4325  4325 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 13:19:02.164  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:02.164  4325  4325 D BluetoothMapService: STATE_ON
,08-25 13:19:02.172  3910  3910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 13:19:02.181  3910  3910 D DockEventReceiver: finishStartingService: stopping service
,08-25 13:19:02.181  1522  1522 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 13:19:02.189  3910  3910 D BluetoothPbap: Proxy object connected
,08-25 13:19:02.189  4325  4325 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 13:19:02.189  4325  4325 D ObexServerSockets0: prepareForNewConnect()
,08-25 13:19:02.189  3910  3910 D PbapServerProfile: Bluetooth service connected
,08-25 13:19:02.191  1372  1372 D BluetoothPbap: Proxy object connected
,08-25 13:19:02.191  1372  1372 D PbapServerProfile: Bluetooth service connected
,08-25 13:19:02.202  4325  4369 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:19:02.217  4325  4373 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 13:19:02.219  4325  4373 I BtOppRfcommListener: Accept thread started.
,08-25 13:19:02.226  1911  2120 D BluetoothHeadset: Proxy object connected
,08-25 13:19:02.226   872   872 D BluetoothHeadset: Proxy object connected
,08-25 13:19:02.226   872   872 D BluetoothHeadset: Proxy object connected
08-25 13:19:02.226   872   872 D BluetoothHeadset: Proxy object connected
,08-25 13:19:02.227  3910  3922 D BluetoothHeadset: Proxy object connected
08-25 13:19:02.228  3910  3910 D HeadsetProfile: Bluetooth service connected
,08-25 13:19:02.228  1372  1385 D BluetoothHeadset: Proxy object connected
08-25 13:19:02.228  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-25 13:19:02.229  3910  3920 D BluetoothHeadset: Proxy object connected
,08-25 13:19:02.231   872   889 D BluetoothHeadset: Proxy object connected
,08-25 13:19:02.232  3910  3910 D HeadsetProfile: Bluetooth service connected
,08-25 13:19:02.234   872   889 D BluetoothHeadset: Proxy object connected
,08-25 13:19:02.236  1372  2033 D BluetoothHeadset: Proxy object connected
08-25 13:19:02.236  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-25 13:19:02.259   872   889 D BluetoothHeadset: Proxy object connected
,08-25 13:19:02.546  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:02.546  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:02.546  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:19:02.546  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 13:19:02.546  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:02.546  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:02.546  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:02.546  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:19:02.555  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:19:02.558  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:19:02.559  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9676f15 added. We now have 8 listener(s)
08-25 13:19:02.559  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:19:02.566   872  1932 D WifiService: setWifiEnabled: false pid=3841, uid=10000
,08-25 13:19:02.566   872  1932 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 13:19:02.579  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:02.580   872  1707 D WifiService: setWifiEnabled: true pid=3841, uid=10000
08-25 13:19:02.580   872  1707 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 13:19:02.594   872  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-25 13:19:02.611  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:02.611  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:02.611  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:19:02.611  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:02.611  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:02.611  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 13:19:02.611  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 13:19:02.611  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 13:19:02.615  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 13:19:02.620   872  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-25 13:19:02.621   872  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 13:19:02.622   872  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 13:19:02.623   872  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-25 13:19:02.623   872  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 13:19:02.623   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-25 13:19:02.623   872  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 13:19:02.641   872  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.18 rxSuccessRate=0.25 delta 1000 -> 1000
,08-25 13:19:02.641   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-25 13:19:02.641   872  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 13:19:02.644   371   870 D CommandListener: Setting iface cfg
,08-25 13:19:02.652   872  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
,08-25 13:19:02.652   872  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-25 13:19:02.654   872  1302 E native  : do suspend true
,08-25 13:19:02.663   872  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 13:19:02.667   872  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 13:19:02.669   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 13:19:02.670   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 13:19:02.691   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 13:19:02.739   872  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 13:19:02.743  1468  1468 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 13:19:03.168  1468  1468 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 13:19:03.204  1468  1468 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 13:19:03.204  1468  1468 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 13:19:03.209   872  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 13:19:03.218   872  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 13:19:03.218   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 13:19:03.218   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 13:19:03.238   872  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 13:19:03.246   371   870 D CommandListener: Setting iface cfg
,08-25 13:19:03.248   872  1302 D WifiStateMachine: Start Dhcp Watchdog 3
,08-25 13:19:03.256   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 13:19:03.301   872  4381 D DhcpClient: Receive thread started
,08-25 13:19:03.384   872  1302 E native  : do suspend false
,08-25 13:19:03.403   872  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 13:19:03.422   872  4381 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-25 13:19:03.423   872  1877 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-25 13:19:03.429   872  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 13:19:03.441   872  4381 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 13:19:03.445   872  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 13:19:03.453   371   870 D CommandListener: Setting iface cfg
,08-25 13:19:03.463   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 13:19:03.463   872  1877 D DhcpClient: Scheduling renewal in 86399s
,08-25 13:19:03.467   872  1302 E native  : do suspend true
,08-25 13:19:03.490   872  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 13:19:03.494   872  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 13:19:03.496   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 13:19:03.499   872  1304 D ConnectivityService: Adding iface wlan0 to network 102
,08-25 13:19:03.507   872  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 13:19:03.560   872  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 13:19:03.560   872  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-25 13:19:03.561   872  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-25 13:19:03.562   872  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102,
08-25 13:19:03.563   872  1304 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-25 13:19:03.573   872  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-25 13:19:03.578   872  1304 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-25 13:19:03.579   872  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-25 13:19:03.579   872  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-25 13:19:03.579   872  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-25 13:19:03.579   872  1304 D ConnectivityService:    accepting network in place of null
08-25 13:19:03.579   872  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 13:19:03.580   872  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 13:19:03.595  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:03.595  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:03.595  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:19:03.595  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:03.595  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:03.595  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:03.595  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:03.595  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:19:03.597  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:19:03.600  3841  3891 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-25 13:19:03.600  3841  3891 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 13:19:03.602  3841  3891 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f7e2a74 Bundle[{}]
,08-25 13:19:03.603  3841  3891 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 13:19:03.603  3841  3891 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 13:19:03.603   872  4380 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164659, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 13:19:03.603  3841  3891 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 13:19:03.604  3841  3891 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 13:19:03.604  3841  3891 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-25 13:19:03.605  3841  3891 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 13:19:03.609  3841  3891 I System.out: Running OutgoingSocketThread
,08-25 13:19:03.610  3841  4387 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 428)
,08-25 13:19:03.611  3841  4387 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46268
08-25 13:19:03.611  3841  4387 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 13:19:03.621   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 13:19:03.666   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 13:19:03.676   872  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-25 13:19:03.676   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 13:19:03.677   872  4379 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:804::200e
,08-25 13:19:03.684   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-25 13:19:03.694   872  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-25 13:19:03.706  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 13:19:03.706  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:03.706  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:19:03.706  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:03.706  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:03.706  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:03.706  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:03.706  3841  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 13:19:03.710  3841  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:19:03.750   872  4379 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 11:19:03 GMT], X-Android-Received-Millis=[1472123943749], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472123943720]}
,08-25 13:19:03.763   872   884 I ActivityManager: Start proc 4390:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-25 13:19:03.773   872  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 13:19:03.773   872  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-25 13:19:03.773   872  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-25 13:19:03.773  1742  1742 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-25 13:19:03.774   872  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 13:19:03.788  1742  1742 D SystemUpdateService: onCreate
,08-25 13:19:03.793  1742  1742 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 13:19:03.798  4390  4390 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-25 13:19:03.826  1742  1742 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 13:19:03.829  1742  2418 I iu.UploadsManager: num queued entries: 0
,08-25 13:19:03.830  1742  2418 I iu.UploadsManager: num updated entries: 0
,08-25 13:19:03.838  1742  4404 I SystemUpdateService: active receiver: enabled
,08-25 13:19:03.846  1742  1742 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 13:19:03.847  1742  1742 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 13:19:03.850  4026  4026 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 13:19:03.860  1742  4406 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-25 13:19:03.860  1742  4406 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 13:19:03.861  4026  4026 D SprintDMHelper: simOperator: 
08-25 13:19:03.862  4026  4026 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 13:19:03.861  1742  4406 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-25 13:19:03.876  1742  2418 I iu.SyncManager: NEXT; no task
,08-25 13:19:03.892  1742  4404 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 13:19:03.898  4390  4390 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-25 13:19:03.902  1742  4404 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 13:19:03.902  1742  4404 I SystemUpdateService: now status is 0 (complete)
,08-25 13:19:03.902  1742  4404 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 13:19:03.903  1742  4404 I SystemUpdateService: file has been verified
,08-25 13:19:03.904  1742  4404 I SystemUpdateService: OTA package size = 12249756
,08-25 13:19:03.909  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:19:03.910  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:19:03.913  1742  4404 I SystemUpdateService: showing system update notification
,08-25 13:19:03.917  4390  4390 I BooksApp: Created application version: 3.6.9 (30609)
,08-25 13:19:03.935  1742  1742 D SystemUpdateService: onDestroy
,08-25 13:19:03.952  1522  3817 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 13:19:03.952  1522  3817 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-25 13:19:03.952  1522  3817 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:19:03.953  1522  3817 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:19:03.987  1742  4406 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-25 13:19:03.993  3959  4412 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 13:19:04.032  4390  4418 I BooksSync: Starting books sync for 61035162, extras: ade
,08-25 13:19:04.142  4390  4426 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-25 13:19:04.221   872  1292 I ActivityManager: Start proc 4427:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,08-25 13:19:04.240  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 13:19:04.241  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-25 13:19:04.241  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:19:04.241  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:19:04.276  4427  4427 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,08-25 13:19:04.304  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:19:04.315  1522  3817 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-25 13:19:04.315  1522  3817 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-25 13:19:04.315  1522  3817 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:19:04.315  1522  3817 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:19:04.329  4390  4426 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-25 13:19:04.331  4390  4418 E BooksSync: Soft error
08-25 13:19:04.331  4390  4418 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 13:19:04.331  4390  4418 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-25 13:19:04.332  4390  4418 E BooksSync: Sync error
08-25 13:19:04.332  4390  4418 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-25 13:19:04.332  4390  4418 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-25 13:19:04.332  4390  4418 I BooksSync: Finished books sync
,08-25 13:19:04.339   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161623, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-25 13:19:04.359  4427  4427 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-25 13:19:04.412  1522  4457 I VacuumService: Vacuum at: now=1472123944412 tag=VacuumService
,08-25 13:19:04.426  4427  4427 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,08-25 13:19:04.439  4427  4427 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 13:19:04.440  4427  4427 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 13:19:04.472  4427  4467 D Ads     : Skipping gmscore version check
,08-25 13:19:04.476  4427  4427 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-25 13:19:04.476  4427  4427 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,08-25 13:19:04.478  4427  4467 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-25 13:19:04.487  1522  4458 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-25 13:19:04.495  1522  4458 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-25 13:19:04.553  4427  4427 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-25 13:19:04.575  1522  4458 W Uploader:  no longer exists, so no auth token.
,08-25 13:19:04.586  4427  4427 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-25 13:19:04.611  3841  3891 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 429)
,08-25 13:19:04.612  3841  3891 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 429)
,08-25 13:19:04.619  3841  3891 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-25 13:19:04.620  3841  3891 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 13:19:04.621  3841  3891 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 435)
,08-25 13:19:04.627  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 13:19:04.627  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@420e22a added. We now have 2 listener(s)
,08-25 13:19:04.633  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 13:19:04.633  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 13:19:04.633  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:04.634  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:19:04.634  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d65481b added. We now have 9 listener(s)
08-25 13:19:04.634  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:04.635  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:19:04.641  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:19:04.650  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:04.650  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:04.650  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:19:04.650  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:04.650  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:04.650  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:04.650  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:04.650  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:19:04.651  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:19:04.652  3841  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 13:19:04.652  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:04.652  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6dce791 added. We now have 3 listener(s)
,08-25 13:19:04.653  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 13:19:04.653  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 13:19:04.653  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:04.654  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:04.654  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c2f6f6 added. We now have 10 listener(s)
08-25 13:19:04.655  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:04.655  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:04.655  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:04.655  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 13:19:04.655  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:04.655  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.655  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:04.655  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:04.655  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@420e22a removed from the list
08-25 13:19:04.655  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.655  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d65481b removed from the list,
08-25 13:19:04.656  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:04.659  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:04.659  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 13:19:04.659  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:04.660  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.660  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:19:04.661  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:04.661  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:04.661  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:19:04.661  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d65481b not in the list
08-25 13:19:04.661  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.661  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:19:04.663  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:19:04.663  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:04.663  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.663  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c2f6f6 removed from the list
08-25 13:19:04.663  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:19:04.663  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.664  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:04.664  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 13:19:04.664  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6dce791 removed from the list
08-25 13:19:04.664  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:04.664  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3864af7 added. We now have 2 listener(s)
,08-25 13:19:04.666  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 13:19:04.666  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:04.666  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:04.666  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 13:19:04.667  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0f5d64 added. We now have 9 listener(s)
08-25 13:19:04.667  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:04.667  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:19:04.670  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:19:04.674   872  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-25 13:19:04.676  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:04.676  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:04.676  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:19:04.676  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:04.676  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:04.676  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:04.676  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:04.676  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:19:04.679  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:19:04.679  3841  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:19:04.679  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:04.680  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9f8c82 added. We now have 3 listener(s)
,08-25 13:19:04.682  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 13:19:04.682  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 13:19:04.682  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 13:19:04.682  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:04.682  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54a9f93 added. We now have 10 listener(s)
08-25 13:19:04.682  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:19:04.683  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:04.682  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:04.683  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:19:04.684  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 13:19:04.684  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:04.684  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 13:19:04.689  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:04.690  3841  3891 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 13:19:04.690  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 13:19:04.694  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:19:04.695  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 13:19:04.695  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:19:04.700  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 13:19:04.700  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 13:19:04.700  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 13:19:04.701  3841  3891 D BluetoothAdapter: STATE_ON
,08-25 13:19:04.704  4325  4354 D BtGatt.GattService: registerClient() - UUID=763e30e6-3c1e-46cb-a613-396f9678b209
08-25 13:19:04.706  4325  4341 D BtGatt.GattService: onClientRegistered() - UUID=763e30e6-3c1e-46cb-a613-396f9678b209, clientIf=5
,08-25 13:19:04.706  3841  3852 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 13:19:04.708  4325  4363 D BtGatt.GattService: start scan with filters
,08-25 13:19:04.715  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 13:19:04.715  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 13:19:04.715  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 13:19:04.715  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:19:04.715  4325  4344 D BtGatt.ScanManager: handling starting scan
08-25 13:19:04.718  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:19:04.718  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:19:04.718  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 13:19:04.720  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 13:19:04.720  4325  4344 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c0b39c8
08-25 13:19:04.723  3841  3891 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 13:19:04.723  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:04.723  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 13:19:04.723  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.723  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 13:19:04.723  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 13:19:04.724  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:19:04.724  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 13:19:04.725  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:19:04.725  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:19:04.725  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 13:19:04.725  4325  4341 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 13:19:04.725  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.726  3841  3891 D BluetoothAdapter: STATE_ON
,08-25 13:19:04.726  4325  4344 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 13:19:04.727  4325  4363 D BtGatt.GattService: stopScan() - queue size =1
08-25 13:19:04.728  4325  4335 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 13:19:04.729  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 13:19:04.729  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 13:19:04.729  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 13:19:04.729  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 13:19:04.730  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 13:19:04.731  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 13:19:04.731  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 13:19:04.731  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 13:19:04.731  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:19:04.732  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:19:04.732  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:19:04.733  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 13:19:04.733  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:19:04.736  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:04.736  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:04.736  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:04.736  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:04.736  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.736  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:04.736  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:04.737  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3864af7 removed from the list
08-25 13:19:04.737  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.737  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0f5d64 removed from the list
08-25 13:19:04.737  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:04.737  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:04.737  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.737  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:19:04.739  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:04.739  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:04.739  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:19:04.739  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d0f5d64 not in the list
08-25 13:19:04.739  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.739  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:19:04.740  4325  4341 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 13:19:04.740  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.740  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:04.740  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:04.741  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 13:19:04.741  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54a9f93 removed from the list
08-25 13:19:04.741  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:19:04.741  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.741  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:04.741  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:04.741  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9f8c82 removed from the list
,08-25 13:19:04.741  4325  4344 D BtGatt.ScanManager: Starting BLE batch scan
08-25 13:19:04.742  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:04.742  4325  4344 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 13:19:04.742  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf5a1ef added. We now have 2 listener(s)
08-25 13:19:04.744  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 13:19:04.744  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:04.744  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:04.744  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:04.744  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c6f4fc added. We now have 9 listener(s)
,08-25 13:19:04.744  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:04.744  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:19:04.748  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:19:04.755  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:04.755  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:04.755  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:19:04.755  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:04.755  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:04.755  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:04.755  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:04.755  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:19:04.758  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:19:04.758  3841  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:19:04.759  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 13:19:04.761  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:04.761  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54e29da added. We now have 3 listener(s)
,08-25 13:19:04.762  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:04.764  4325  4341 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-25 13:19:04.764  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 13:19:04.764  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:04.764  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.764  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:04.764  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:04.765  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba46e0b added. We now have 10 listener(s)
,08-25 13:19:04.765  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:04.765  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:04.766  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:04.766  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 13:19:04.766  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 13:19:04.766  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:04.766  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 13:19:04.772  3841  3891 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 13:19:04.772  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 13:19:04.772  4325  4341 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 13:19:04.772  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:19:04.778  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:19:04.779  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 13:19:04.779  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:19:04.782  4325  4341 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 13:19:04.782  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.782  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 13:19:04.783  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 13:19:04.783  4325  4344 D BtGatt.ScanManager: stopping BLe Batch
,08-25 13:19:04.783  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 13:19:04.784  3841  3891 D BluetoothAdapter: STATE_ON
,08-25 13:19:04.787  4325  4365 D BtGatt.GattService: registerClient() - UUID=e12f83a6-b8cd-4018-9e77-5d87f1865b9a
08-25 13:19:04.787  4325  4341 D BtGatt.GattService: onClientRegistered() - UUID=e12f83a6-b8cd-4018-9e77-5d87f1865b9a, clientIf=5
08-25 13:19:04.787  3841  4126 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 13:19:04.788  4325  4363 D BtGatt.GattService: start scan with filters
,08-25 13:19:04.789  4325  4341 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 13:19:04.789  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.789  4325  4344 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 13:19:04.791  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 13:19:04.791  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 13:19:04.791  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 13:19:04.791  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:19:04.793  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:19:04.794  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 13:19:04.794  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 13:19:04.795  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 13:19:04.798  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 13:19:04.798  3841  3891 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 13:19:04.798  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:04.798  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 13:19:04.798  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:04.798  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:04.798  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.798  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 13:19:04.799  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:04.799  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf5a1ef removed from the list
08-25 13:19:04.799  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.799  4325  4341 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 13:19:04.799  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c6f4fc removed from the list
08-25 13:19:04.799  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:04.799  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.799  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 13:19:04.799  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.799  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 13:19:04.799  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.800  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:04.800  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:04.800  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:19:04.800  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.801  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c6f4fc not in the list
08-25 13:19:04.801  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:19:04.801  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:19:04.801  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:19:04.801  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:19:04.801  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 13:19:04.802  4325  4344 D BtGatt.ScanManager: handling starting scan
08-25 13:19:04.802  3841  3891 D BluetoothAdapter: STATE_ON
,08-25 13:19:04.803  4325  4335 D BtGatt.GattService: stopScan() - queue size =1
,08-25 13:19:04.805  4325  4365 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 13:19:04.806  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 13:19:04.806  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 13:19:04.806  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 13:19:04.806  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 13:19:04.806  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 13:19:04.807  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:19:04.807  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 13:19:04.807  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 13:19:04.807  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:19:04.808  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:19:04.809  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:19:04.809  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:04.809  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.809  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:19:04.809  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba46e0b removed from the list
,08-25 13:19:04.809  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 13:19:04.809  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:04.809  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:19:04.809  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.809  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:04.809  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:04.809  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54e29da removed from the list
,08-25 13:19:04.810  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:04.810  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d29dfe7 added. We now have 2 listener(s)
08-25 13:19:04.812  4325  4341 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 13:19:04.812  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.812  4325  4344 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 13:19:04.813  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 13:19:04.813  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:04.813  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 13:19:04.813  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:04.813  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6e794 added. We now have 9 listener(s)
08-25 13:19:04.813  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:04.814  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:19:04.817  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:19:04.819  4325  4341 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 13:19:04.819  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.820  4325  4344 D BtGatt.ScanManager: Starting BLE batch scan
08-25 13:19:04.820  4325  4344 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 13:19:04.822  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:04.822  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:04.822  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:19:04.822  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:04.822  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:04.822  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:04.822  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:04.822  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:19:04.823  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 13:19:04.824  3841  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:19:04.825  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:04.825  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d81a32 added. We now have 3 listener(s)
,08-25 13:19:04.826  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:04.829  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 13:19:04.829  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 13:19:04.829  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:04.829  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:04.829  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daa9383 added. We now have 10 listener(s)
,08-25 13:19:04.829  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 13:19:04.829  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 13:19:04.829  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 13:19:04.829  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 13:19:04.830  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 13:19:04.830  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 13:19:04.830  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 13:19:04.832  4325  4341 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 13:19:04.832  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:19:04.833  3841  3891 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 13:19:04.833  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 13:19:04.836  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 13:19:04.837  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 13:19:04.837  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 13:19:04.839  4325  4341 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 13:19:04.839  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:19:04.840  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 13:19:04.841  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 13:19:04.841  3841  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 13:19:04.841  3841  3891 D BluetoothAdapter: STATE_ON
,08-25 13:19:04.843  4325  4354 D BtGatt.GattService: registerClient() - UUID=a48f40b0-ad13-4956-b5be-ca3f38e0babf
,08-25 13:19:04.843  4325  4341 D BtGatt.GattService: onClientRegistered() - UUID=a48f40b0-ad13-4956-b5be-ca3f38e0babf, clientIf=5
08-25 13:19:04.843  3841  4126 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 13:19:04.844  4325  4335 D BtGatt.GattService: start scan with filters
,08-25 13:19:04.846  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 13:19:04.846  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 13:19:04.846  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 13:19:04.846  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 13:19:04.847  4325  4341 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 13:19:04.847  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:19:04.847  4325  4344 D BtGatt.ScanManager: stopping BLe Batch
,08-25 13:19:04.849  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 13:19:04.849  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 13:19:04.849  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 13:19:04.851  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 13:19:04.855  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:04.855  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:04.855  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:04.855  4325  4341 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 13:19:04.855  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.855  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:04.855  4325  4344 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 13:19:04.855  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.855  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 13:19:04.855  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:04.855  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d29dfe7 removed from the list
08-25 13:19:04.855  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.855  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6e794 removed from the list
08-25 13:19:04.856  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:04.856  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:04.856  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.856  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 13:19:04.856  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.856  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:04.857  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:04.857  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:04.857  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.857  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b6e794 not in the list
08-25 13:19:04.857  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 13:19:04.857  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 13:19:04.857  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 13:19:04.857  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 13:19:04.858  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 13:19:04.858  3841  3891 D BluetoothAdapter: STATE_ON
08-25 13:19:04.858  4325  4363 D BtGatt.GattService: stopScan() - queue size =0
08-25 13:19:04.859  4325  4354 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 13:19:04.859  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 13:19:04.859  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 13:19:04.859  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 13:19:04.859  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 13:19:04.859  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 13:19:04.860  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:19:04.860  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 13:19:04.860  3841  3891 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 13:19:04.861  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 13:19:04.861  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:04.862  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:19:04.862  3841  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 13:19:04.862  3841  3841 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 13:19:04.862  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:04.862  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:04.862  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.862  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@daa9383 removed from the list
08-25 13:19:04.862  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 13:19:04.862  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.863  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:04.863  4325  4341 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 13:19:04.863  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:04.863  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.863  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d81a32 removed from the list
08-25 13:19:04.863  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:04.863  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf8e4df added. We now have 2 listener(s)
08-25 13:19:04.865  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 13:19:04.865  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:04.865  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 13:19:04.865  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:04.865  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2f952c added. We now have 9 listener(s)
08-25 13:19:04.865  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:19:04.868  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 13:19:04.869  4325  4344 D BtGatt.ScanManager: handling starting scan
,08-25 13:19:04.871  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 13:19:04.876  3841  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 13:19:04.876  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 13:19:04.876  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 13:19:04.876  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 13:19:04.876  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 13:19:04.876  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:04.876  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 13:19:04.876  3841  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 13:19:04.878  4325  4341 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 13:19:04.878  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.878  4325  4344 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 13:19:04.879  3841  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 13:19:04.879  3841  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 13:19:04.879  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 13:19:04.879  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf4bd8a added. We now have 3 listener(s)
08-25 13:19:04.881  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:04.883  3841  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 13:19:04.884  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 13:19:04.884  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 13:19:04.884  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 13:19:04.884  4325  4341 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 13:19:04.884  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 13:19:04.884  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 13:19:04.884  4325  4344 D BtGatt.ScanManager: Starting BLE batch scan
08-25 13:19:04.884  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb0effb added. We now have 10 listener(s)
08-25 13:19:04.884  4325  4344 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 13:19:04.884  3841  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 13:19:04.885  3841  3891 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 13:19:04.885  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:04.885  3841  3891 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 13:19:04.885  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:19:04.885  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.885  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 13:19:04.885  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:04.885  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf8e4df removed from the list
,08-25 13:19:04.885  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.885  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2f952c removed from the list
08-25 13:19:04.885  3841  3891 D io.jxcore.node.ConnectivityMonitor: stop
08-25 13:19:04.886  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:04.886  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:19:04.886  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:04.887  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:04.887  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 13:19:04.887  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.887  3841  3891 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2f952c not in the list
,08-25 13:19:04.887  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 13:19:04.887  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 13:19:04.888  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 13:19:04.888  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 13:19:04.888  3841  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 13:19:04.888  3841  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb0effb removed from the list
08-25 13:19:04.888  3841  3891 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 13:19:04.888  3841  3891 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 13:19:04.888  3841  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 13:19:04.888  3841  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 13:19:04.888  3841  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf4bd8a removed from the list
,08-25 13:19:04.889  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 13:19:04.889  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 13:19:04.889  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 13:19:04.889  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 13:19:04.889  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 13:19:04.890  3841  3891 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 13:19:04.895  4325  4341 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 13:19:04.895  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.896  3841  4472 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: My test thread name)
,08-25 13:19:04.896  3841  4472 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: My test thread name)
,08-25 13:19:04.896  3841  4472 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 13:19:04.898  3841  4473 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: My test thread name)
08-25 13:19:04.898  3841  4473 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: My test thread name)
08-25 13:19:04.898  3841  4473 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 13:19:04.900  3841  3891 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 13:19:04.900  3841  3891 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 13:19:04.900  4325  4341 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 13:19:04.900  3841  3891 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-25 13:19:04.900  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.900  3841  3891 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 13:19:04.900  3841  3891 D com.test.thalitest.ThaliTestRunner: Total duration: 22763 ms
08-25 13:19:04.902  3841  3891 I jxcore-log: Total number of executed tests:  80
08-25 13:19:04.902  3841  3891 I jxcore-log: 
08-25 13:19:04.902  3841  3891 I jxcore-log: Number of passed tests:  80
08-25 13:19:04.902  3841  3891 I jxcore-log: 
,08-25 13:19:04.902  3841  3891 I jxcore-log: Number of failed tests:  0
08-25 13:19:04.902  3841  3891 I jxcore-log: 
,08-25 13:19:04.902  3841  3891 I jxcore-log: Number of ignored tests:  0
08-25 13:19:04.902  3841  3891 I jxcore-log: 
08-25 13:19:04.902  3841  3891 I jxcore-log: Total duration:  22763
08-25 13:19:04.902  3841  3891 I jxcore-log: 
,08-25 13:19:04.902  3841  3891 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 13:19:04.902  3841  3891 I jxcore-log: 
,08-25 13:19:04.906  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.906  3841  3891 I jxcore-log: 
08-25 13:19:04.908  4325  4341 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 13:19:04.908  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.908  4325  4344 D BtGatt.ScanManager: stopping BLe Batch
08-25 13:19:04.910  3841  3841 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 13:19:04.911  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.911  3841  3891 I jxcore-log: 
08-25 13:19:04.912  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.912  3841  3891 I jxcore-log: 
08-25 13:19:04.913  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.913  3841  3891 I jxcore-log: 
08-25 13:19:04.914  4325  4341 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 13:19:04.914  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.914  4325  4344 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 13:19:04.914  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.914  3841  3891 I jxcore-log: 
08-25 13:19:04.915  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.915  3841  3891 I jxcore-log: 
08-25 13:19:04.918  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.918  3841  3891 I jxcore-log: 
08-25 13:19:04.919  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:04.919  3841  3891 I jxcore-log: 
08-25 13:19:04.920  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:04.920  3841  3891 I jxcore-log: 
08-25 13:19:04.921  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 13:19:04.921  3841  3891 I jxcore-log: 
08-25 13:19:04.922  4325  4341 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 13:19:04.922  4325  4341 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 13:19:04.922  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 13:19:04.922  3841  3891 I jxcore-log: 
08-25 13:19:04.929  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 13:19:04.929  3841  3891 I jxcore-log: 
08-25 13:19:04.930  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.930  3841  3891 I jxcore-log: 
08-25 13:19:04.930  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.930  3841  3891 I jxcore-log: 
08-25 13:19:04.931  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 13:19:04.931  3841  3891 I jxcore-log: 
08-25 13:19:04.932  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 13:19:04.932  3841  3891 I jxcore-log: 
08-25 13:19:04.932  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:04.932  3841  3891 I jxcore-log: 
08-25 13:19:04.933  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:04.933  3841  3891 I jxcore-log: 
08-25 13:19:04.933  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:19:04.933  3841  3891 I jxcore-log: 
08-25 13:19:04.934  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:19:04.934  3841  3891 I jxcore-log: 
08-25 13:19:04.935  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:04.935  3841  3891 I jxcore-log: 
08-25 13:19:04.935  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 13:19:04.935  3841  3891 I jxcore-log: 
08-25 13:19:04.936  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:19:04.936  3841  3891 I jxcore-log: 
08-25 13:19:04.936  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 13:19:04.936  3841  3891 I jxcore-log: 
08-25 13:19:04.936  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 13:19:04.936  3841  3891 I jxcore-log: 
08-25 13:19:04.937  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.937  3841  3891 I jxcore-log: 
08-25 13:19:04.938  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.938  3841  3891 I jxcore-log: 
08-25 13:19:04.938  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.938  3841  3891 I jxcore-log: 
08-25 13:19:04.939  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.939  3841  3891 I jxcore-log: 
08-25 13:19:04.939  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.939  3841  3891 I jxcore-log: 
08-25 13:19:04.940  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.940  3841  3891 I jxcore-log: 
08-25 13:19:04.940  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 13:19:04.940  3841  3891 I jxcore-log: 
,08-25 13:19:04.964  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:19:04.986  1522  2088 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 13:19:04.986  1522  2088 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 13:19:04.986  1522  2088 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:19:04.986  1522  2088 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:19:05.006  4427  4427 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 13:19:05.007  4427  4427 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 13:19:05.007  4427  4427 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-25 13:19:05.026   872  2156 I ActivityManager: Killing 4182:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-25 13:19:05.234  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 13:19:05.235  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 13:19:05.235  3841  3891 I jxcore-log: 
,08-25 13:19:05.310  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 13:19:05.311  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 13:19:05.311  3841  3891 I jxcore-log: 
,08-25 13:19:05.363  3841  3841 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 13:19:05.365  3841  3891 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 13:19:05.365  3841  3891 I jxcore-log: 
,08-25 13:19:05.436  4427  4427 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-25 13:19:05.462  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:19:05.507  1522  3817 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-25 13:19:05.507  1522  3817 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-25 13:19:05.507  1522  3817 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:19:05.507  1522  3817 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:19:05.534  4427  4427 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-25 13:19:05.541  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:19:05.564  1522  2088 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-25 13:19:05.564  1522  2088 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-25 13:19:05.564  1522  2088 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:19:05.564  1522  2088 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:19:05.569  4477  4477 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-25 13:19:05.573  4477  4477 D AndroidRuntime: CheckJNI is OFF
,08-25 13:19:05.609  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:19:05.611  4477  4477 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-25 13:19:05.627  4427  4481 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-25 13:19:05.631  4427  4427 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,08-25 13:19:05.631  4427  4427 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,08-25 13:19:05.640  1522  1534 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-25 13:19:05.640  1522  1534 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-25 13:19:05.640  1522  1534 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 13:19:05.641  1522  1534 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 13:19:05.647  4477  4477 I Radio-JNI: register_android_hardware_Radio DONE
08-25 13:19:05.666  4477  4477 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-25 13:19:05.667  4427  4427 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-25 13:19:05.672   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-25 13:19:05.672   872   885 I ActivityManager: Killing 3841:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-25 13:19:05.755   872   895 W PackageSettings: Skipping PackageSetting{81ed2f5 com.example.hello/10273} due to missing metadata
,08-25 13:19:05.758   872  1386 I WindowState: WIN DEATH: Window{fe677bd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 13:19:05.759   872  2149 D GraphicsStats: Buffer count: 2
08-25 13:19:05.759   872  1303 D WifiService: Client connection lost with reason: 4
,08-25 13:19:05.816   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-25 13:19:05.816   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-25 13:19:05.817   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-25 13:19:05.817   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-25 13:19:05.817   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:19:05.817   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:19:05.817   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 13:19:05.817   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 13:19:05.817   872   885 I ActivityManager:   Force finishing activity ActivityRecord{ae35dfa u0 com.test.thalitest/.MainActivity t2}
,08-25 13:19:05.822   872   895 I art     : Starting a blocking GC Explicit
,08-25 13:19:05.843   872  2156 W ActivityManager: Spurious death for ProcessRecord{5dec6d3 0:com.test.thalitest/u0a0}, curProc for 3841: null
,08-25 13:19:05.865  1522  4458 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-25 13:19:05.866  1522  4458 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-25 13:19:05.866  1522  4458 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 13:19:05.866  1522  4458 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:19:05.877  1522  4458 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-25 13:19:05.877  1522  4458 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-25 13:19:05.877  1522  4458 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-25 13:19:05.887   872   895 I art     : Explicit concurrent mark sweep GC freed 20954(1601KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 996us total 64.503ms
,08-25 13:19:05.912   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-25 13:19:05.920  4477  4477 I art     : System.exit called, status: 0
,08-25 13:19:05.920  4477  4477 I AndroidRuntime: VM exiting with result code 0.
,08-25 13:19:05.951   872   895 I ActivityManager: Start proc 4492:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-25 13:19:05.952   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-25 13:19:05.984   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-25 13:19:05.994   872  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 13:19:06.005  4325  4325 D BluetoothMapAppObserver: onReceive
,08-25 13:19:06.005  4325  4325 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-25 13:19:06.009  2168  2316 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 13:19:06.010  1851  1851 I Keyboard.Facilitator: resetDictionaries() : en_US
08-25 13:19:06.016  3642  3642 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-25 13:19:06.019  1851  4507 I Keyboard.Facilitator.DecoderInitializer: run()
,08-25 13:19:06.022  1851  4507 I Decoder : createOrResetDecoder
,08-25 13:19:06.059  1911  1911 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-25 13:19:06.063   872  1300 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-25 13:19:06.067  1522  1522 I ConfigService: onCreate
,08-25 13:19:06.069  4132  4154 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
08-25 13:19:06.069  4132  4154 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjEFB7799D1) - 
--------- beginning of crash
08-25 13:19:06.069  4132  4154 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-25 13:19:06.069  4132  4154 E AndroidRuntime: Process: android.process.acore, PID: 4132
08-25 13:19:06.069  4132  4154 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:19:06.069  4132  4154 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 13:19:06.071,  1522  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-25 13:19:06.071  1522  4509 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-25 13:19:06.071  1522  4509 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-25 13:19:06.074  4132  4508 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 13:19:06.087   872  2149 I ActivityManager: Start proc 4510:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-25 13:19:06.095  1522  4509 W SQLiteOpenHelper: Opened config.db in read-only mode
08-25 13:19:06.098   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 13:19:06.101   872  4515 E DropBoxManagerService: Can't write: system_app_crash
08-25 13:19:06.101   872  4515 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 13:19:06.101   872  4515 E DropBoxManagerService: 	... 5 more
,08-25 13:19:06.111   872  2082 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3841 uid 10000
,08-25 13:19:06.112  1851  4507 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-25 13:19:06.114  1851  1851 I Keyboard.Facilitator: onFinishInput()
,08-25 13:19:06.133  4132  4508 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,08-25 13:19:06.142  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 13:19:06.143   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-25 13:19:06.144   872   884 E PackageManager: Failed to write settings, restoring backup
08-25 13:19:06.144   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-25 13:19:06.144   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-25 13:19:06.144   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-25 13:19:06.144   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-25 13:19:06.144   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-25 13:19:06.144   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:19:06.144   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:19:06.144   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 13:19:06.145  1925  2011 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-25 13:19:06.147   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-25 13:19:06.147   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 13:19:06.147   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 13:19:06.147   872   885 E DropBoxManagerService: 	... 13 more
,08-25 13:19:06.153  4132  4508 I Process : Sending signal. PID: 4132 SIG: 9
,08-25 13:19:06.158   872  1357 I ActivityManager: Start proc 4523:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-25 13:19:06.160  1925  2011 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-25 13:19:06.160  1925  2011 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1925
08-25 13:19:06.160  1925  2011 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:19:06.160  1925  2011 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 13:19:06.162   872  2082 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 13:19:06.168   872  4529 E DropBoxManagerService: Can't write: system_app_crash
08-25 13:19:06.168   872  4529 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 13:19:06.168   872  4529 E DropBoxManagerService: 	... 5 more
,08-25 13:19:06.169  1925  2011 I Process : Sending signal. PID: 1925 SIG: 9
08-25 13:19:06.170  1522  3079 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-25 13:19:06.170  1522  3079 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-25 13:19:06.170  1522  3079 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 13:19:06.171  1522  3079 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 13:19:06.182  4510  4510 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-25 13:19:06.188  4427  4427 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
08-25 13:19:06.189  4427  4427 D Finsky  : [1] WearSupportService.startHygiene: disabled
,08-25 13:19:06.191  4427  4427 D Finsky  : [1] DailyHygiene.access$600: Logging device features
08-25 13:19:06.195  1851  4507 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-25 13:19:06.197  1851  4507 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-25 13:19:06.197  1851  4507 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-25 13:19:06.197  4427  4427 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 793 minutes (failures=5)
08-25 13:19:06.199  4427  4442 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.android.vending/shared_prefs/finsky.xml to backup file /data/user/0/com.android.vending/shared_prefs/finsky.xml.bak
,08-25 13:19:06.205  1851  4507 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-25 13:19:06.205  1851  4507 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-25 13:19:06.206  1851  4507 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-25 13:19:06.206  1851  4507 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-25 13:19:06.206  1851  4507 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-25 13:19:06.206  1851  4507 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-25 13:19:06.206  1851  4507 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-25 13:19:06.207  1851  4507 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-25 13:19:06.207  1851  4507 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-25 13:19:06.207  1851  4507 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-25 13:19:06.228  4427  4538 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-25 13:19:06.233  1522  1522 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-25 13:19:06.234  1522  1522 D AndroidRuntime: Shutting down VM
,08-25 13:19:06.234   279   279 E lowmemorykiller: Error writing /proc/4132/oom_score_adj; errno=22
08-25 13:19:06.235   279   279 E lowmemorykiller: Error writing /proc/4132/oom_score_adj; errno=22
08-25 13:19:06.235  1522  1522 E AndroidRuntime: FATAL EXCEPTION: main
08-25 13:19:06.235  1522  1522 E AndroidRuntime: Process: com.google.process.gapps, PID: 1522
08-25 13:19:06.235  1522  1522 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-25 13:19:06.235  1522  1522 E AndroidRuntime: 	... 8 more
,08-25 13:19:06.239   872  4542 E DropBoxManagerService: Can't write: system_app_crash
08-25 13:19:06.239   872  4542 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 13:19:06.239   872  4542 E DropBoxManagerService: 	... 5 more
,08-25 13:19:06.239   279   279 E lowmemorykiller: Error writing /proc/4132/oom_score_adj; errno=22
08-25 13:19:06.241  1522  1522 I Process : Sending signal. PID: 1522 SIG: 9
,08-25 13:19:06.303   279   279 E lowmemorykiller: Error writing /proc/4132/oom_score_adj; errno=22
08-25 13:19:06.303   872  1293 W InputDispatcher: channel 'c2628e0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-25 13:19:06.303   872  1293 E InputDispatcher: channel 'c2628e0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-25 13:19:06.305   872  1932 I WindowState: WIN DEATH: Window{c2628e0 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-25 13:19:06.306   872  1932 W InputDispatcher: Attempted to unregister already unregistered input channel 'c2628e0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,08-25 13:19:06.306   872  2149 D GraphicsStats: Buffer count: 1
,08-25 13:19:06.326   872  1707 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1925) has died
,08-25 13:19:06.327   872  1707 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-25 13:19:06.328   872  1707 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 13:19:06.341   872  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,08-25 13:19:06.344   872  1303 D WifiService: Client connection lost with reason: 4
,08-25 13:19:06.359   872   885 I ActivityManager: Start proc 4546:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 13:19:06.360   872  2152 I ActivityManager: Killing 4172:com.google.android.gm/u0a78 (adj 15): empty #17
,08-25 13:19:06.391   872  2081 I ActivityManager: Process com.google.process.gapps (pid 1522) has died
,08-25 13:19:06.392   872  2081 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.LightweightIndexService in 1000ms
08-25 13:19:06.392  1742  4545 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@b858fc4
08-25 13:19:06.392   872  2081 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-25 13:19:06.392   872  2081 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
,08-25 13:19:06.392   872  2081 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerIntentService in 31000ms
08-25 13:19:06.392   872  2081 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.uploader.UploaderService in 31000ms
08-25 13:19:06.393   872  2081 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
,08-25 13:19:06.393   872  2081 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 40999ms
,08-25 13:19:06.393   872  2081 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.phenotype.service.PhenotypeIntentService in 50999ms
,08-25 13:19:06.394   872  1932 I ActivityManager: Process android.process.acore (pid 4132) has died
,08-25 13:19:06.394   872  1932 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 50998ms
08-25 13:19:06.398  1742  1742 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-25 13:19:06.434   872  2081 I ActivityManager: Start proc 4558:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-25 13:19:06.450  4546  4546 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:19:06.450  4546  4546 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 13:19:06.451  4546  4546 D AndroidRuntime: Shutting down VM
,08-25 13:19:06.458  4546  4546 E AndroidRuntime: FATAL EXCEPTION: main
08-25 13:19:06.458  4546  4546 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4546
08-25 13:19:06.458  4546  4546 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 13:19:06.458  4546  4546 E AndroidRuntime: 	... 10 more
08-25 13:19:06.460   872  2081 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 13:19:06.461   872  4572 E DropBoxManagerService: Can't write: system_app_crash
08-25 13:19:06.461   872  4572 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 13:19:06.461   872  4572 E DropBoxManagerService: 	... 5 more
08-25 13:19:06.461  4546  4546 I Process : Sending signal. PID: 4546 SIG: 9

```
