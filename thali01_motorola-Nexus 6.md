#### Test 8291203002d4a60_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
,09-09 02:06:39.938   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
09-09 02:06:40.606  3811  3811 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 02:06:40.611  3811  3811 D AndroidRuntime: CheckJNI is OFF
09-09 02:06:40.654  3811  3811 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 02:06:40.705  3811  3811 I Radio-JNI: register_android_hardware_Radio DONE
09-09 02:06:40.728  3811  3811 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 02:06:40.731   874  1993 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-09 02:06:40.762  2018  2414 W SearchService: Abort, client detached.
09-09 02:06:40.773  2018  2018 I HotwordDetector: Closing mic
09-09 02:06:40.774  2018  2359 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fb5e07e
09-09 02:06:40.774  2018  2368 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-09 02:06:40.792  3811  3811 D AndroidRuntime: Shutting down VM
09-09 02:06:40.813   874  1992 I ActivityManager: Start proc 3820:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-09 02:06:40.828   377  2370 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-09 02:06:40.829   377  2370 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-09 02:06:40.835   377  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-09 02:06:40.838  2018  2366 I MicroRecognitionRnrImpl: Detection finished
09-09 02:06:40.838  2018  2362 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-09 02:06:40.895  3820  3820 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-09 02:06:40.920  3820  3820 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-09 02:06:40.927  3820  3820 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6973-6976)
09-09 02:06:40.927  3820  3820 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 02:06:40.942  3820  3820 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d0cf593}
09-09 02:06:40.942  3820  3820 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 02:06:40.943  3820  3820 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-09 02:06:40.948  3820  3820 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-09 02:06:40.949  3820  3820 E SysUtils: ApplicationContext is null in ApplicationStatus
09-09 02:06:40.961  3820  3820 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-09 02:06:40.970  3820  3820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 02:06:40.970  3820  3820 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 02:06:40.970  3820  3820 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 02:06:40.970  3820  3820 I Adreno  : Build Date                       : 10/20/15
09-09 02:06:40.970  3820  3820 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 02:06:40.970  3820  3820 I Adreno  : Local Branch                     : M14
09-09 02:06:40.970  3820  3820 I Adreno  : Remote Branch                    : 
09-09 02:06:40.970  3820  3820 I Adreno  : Remote Branch                    : 
09-09 02:06:40.970  3820  3820 I Adreno  : Reconstruct Branch               : 
09-09 02:06:41.019   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@60aa746:true
,09-09 02:06:41.050  3820  3820 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 02:06:41.063  3820  3820 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-09 02:06:41.133  3820  3859 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-09 02:06:41.140  3820  3846 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-09 02:06:41.191  3820  3859 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 02:06:41.306   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +512ms
,09-09 02:06:41.317  1873  1873 I Keyboard.Facilitator: onFinishInput()
,09-09 02:06:41.381  3820  3820 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3820
,09-09 02:06:41.498  3820  3820 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-09 02:06:41.620   874  2177 I ActivityManager: Killing 2975:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-09 02:06:41.683   874  2177 I ActivityManager: Killing 3225:com.google.android.gm/u0a78 (adj 15): empty #18
,09-09 02:06:41.846  3820  3861 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1679361744
,09-09 02:06:41.854  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 02:06:41.854  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 02:06:41.854  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 02:06:41.854  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 02:06:41.854  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 02:06:41.854  3820  3861 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dedc1a7 added. We now have 1 listener(s)
,09-09 02:06:41.857  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-09 02:06:41.858  3820  3861 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 02:06:41.859  3820  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 02:06:41.859  3820  3861 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
,09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-09 02:06:41.862  3820  3861 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8dfb6f2 added. We now have 1 listener(s)
09-09 02:06:41.863  3820  3861 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 02:06:41.867   874  1311 D WifiService: New client listening to asynchronous messages
,09-09 02:06:41.867  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 02:06:41.867  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 02:06:41.868  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-09 02:06:41.868  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 02:06:41.868  3820  3861 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-09 02:06:41.870  3820  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 02:06:41.871  3820  3861 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-09 02:06:41.875  3820  3861 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 02:06:41.875  3820  3861 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:06:41.875  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:06:41.875  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:06:41.875  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:06:41.875  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:06:41.875  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:06:41.875  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:06:41.875  3820  3861 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:06:41.875  3820  3861 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-09 02:06:41.875  3820  3861 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 02:06:41.876  3820  3861 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 02:06:41.945  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:06:41.951  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:06:41.956  3820  3820 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 02:06:42.437  3820  3830 I art     : Background sticky concurrent mark sweep GC freed 73062(6MB) AllocSpace objects, 17(1308KB) LOS objects, 29% free, 23MB/32MB, paused 484us total 104.482ms
,09-09 02:06:42.837  3820  3870 W jxcore-log: Initializing JXcore engine
,09-09 02:06:42.837  3820  3870 W jxcore-log: JXcore engine is ready
,09-09 02:06:42.877  3870  3870 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-09 02:06:42.877  3870  3870 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11853]" dev="sockfs" ino=11853 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-09 02:06:42.877  3870  3870 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-09 02:06:42.877  3870  3870 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[24386]" dev="sockfs" ino=24386 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-09 02:06:42.892  3820  3870 W jxcore-log: Starting JXcore engine
,09-09 02:06:42.971   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 02:06:43.032  3820  3870 W jxcore-log: Platform android
09-09 02:06:43.032  3820  3870 W jxcore-log: 
,09-09 02:06:43.033  3820  3870 W jxcore-log: Process ARCH arm
09-09 02:06:43.033  3820  3870 W jxcore-log: ,
,09-09 02:06:43.242  3820  3870 I jxcore-log: JXcore Cordova bridge is ready!
09-09 02:06:43.242  3820  3870 I jxcore-log: 
,09-09 02:06:43.242  3820  3870 W jxcore-log: JXcore engine is started
,09-09 02:06:43.247  3820  3861 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 02:06:43.251  3820  3820 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 02:06:43.415   874  1885 D NetlinkSocketObserver: NeighborEvent{elapsedMs=119463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:06:46.033  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:06:46.046  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:06:46.049  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:06:46.079  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 02:06:46.079  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 02:06:46.080  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:06:46.080  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:06:46.105  3527  3527 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 02:06:46.105  3527  3527 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 02:06:46.105  3527  3527 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-09 02:06:46.265   874  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-09 02:06:49.993  3021  3880 V KeepSync: Connecting to GoogleApiClient
09-09 02:06:49.994   874  2177 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 02:06:50.095  1523  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-09 02:06:50.095  1523  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 02:06:50.095  1523  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:06:50.095  1523  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:06:50.133  1745  3881 V BaseAuthAsyncOperation: access token request failed
,09-09 02:06:50.134  3021  3880 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 02:06:50.229  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 02:06:50.230  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 02:06:50.230  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:06:50.230  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,09-09 02:06:50.276  3021  3880 E KeepSync: IOException
09-09 02:06:50.276  3021  3880 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 02:06:50.276  3021  3880 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 02:06:50.276  3021  3880 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 02:06:50.276  3021  3880 E KeepSync: 	... 10 more
,09-09 02:06:50.276  3021  3880 W KeepSync: Sync result 2
,09-09 02:06:50.285   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 125512, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:06:58.106   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 02:06:58.369  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-09 02:06:58.369  3820  3870 I jxcore-log: 
,09-09 02:06:58.372  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-09 02:06:58.372  3820  3870 I jxcore-log: 
,09-09 02:06:58.383  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:06:58.383  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:06:58.383  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:06:58.383  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:06:58.383  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:06:58.383  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:06:58.383  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:06:58.383  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:06:58.386  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:06:58.389  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-09 02:06:58.389  3820  3870 I jxcore-log: 
,09-09 02:06:58.391  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-09 02:06:58.391  3820  3870 I jxcore-log: 
,09-09 02:06:58.828  3820  3870 I jxcore-log: Running unit tests
09-09 02:06:58.828  3820  3870 I jxcore-log: 
,09-09 02:06:58.828  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 02:06:58.829  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e42c27 added. We now have 2 listener(s)
,09-09 02:06:58.830  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 02:06:58.831  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 02:06:58.831  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 02:06:58.831  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 02:06:58.831  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c4ded4 added. We now have 2 listener(s)
09-09 02:06:58.831  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 02:06:58.832  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 02:06:58.843  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:06:58.855  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:06:58.855  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:06:58.855  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:06:58.855  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:06:58.855  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:06:58.855  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:06:58.855  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:06:58.855  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:06:58.860  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:06:58.861  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 02:06:58.862  3820  3870 D executeNativeTests: Running unit tests
,09-09 02:06:58.868  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:06:58.875  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:06:59.001  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 02:06:59.001  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 added. We now have 3 listener(s)
,09-09 02:06:59.003  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 02:06:59.003  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-09 02:06:59.003  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 02:06:59.003  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 02:06:59.003  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 added. We now have 3 listener(s)
09-09 02:06:59.003  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 02:06:59.004  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 02:06:59.011  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:06:59.023  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-09 02:06:59.023  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:06:59.023  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:06:59.023  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:06:59.023  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:06:59.023  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:06:59.023  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:06:59.023  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:06:59.028  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:06:59.029  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 02:06:59.036  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:06:59.036  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-09 02:06:59.037  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 02:06:59.037  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 02:06:59.038  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-09 02:06:59.041  3820  3870 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-09 02:06:59.041  3820  3870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-09 02:06:59.041  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 02:06:59.042  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 02:06:59.042  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 02:06:59.042  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 02:06:59.042  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:06:59.043  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:06:59.043  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:06:59.043  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:06:59.043  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:06:59.044  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 02:06:59.044  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 02:06:59.044  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 removed from the list
09-09 02:06:59.044  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:06:59.044  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 removed from the list
09-09 02:06:59.045  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:06:59.046  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:06:59.046  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:06:59.046  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:06:59.047  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:06:59.048  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:06:59.048  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:06:59.048  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:06:59.048  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:06:59.050  3820  3870 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-09 02:06:59.051  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:06:59.051  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:06:59.051  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:06:59.051  3820  3870 I org.thaliproject.p2p.btcon,nectorlib.ConnectionManager: dispose
09-09 02:06:59.051  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:06:59.052  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:06:59.052  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:06:59.052  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:06:59.052  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:06:59.052  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:06:59.052  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:06:59.052  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:06:59.052  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:06:59.052  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:06:59.054  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:06:59.054  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:06:59.054  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:06:59.055  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:06:59.062  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 02:06:59.062  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 02:06:59.063  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-09 02:06:59.064  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-09 02:06:59.065  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-09 02:06:59.065  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 02:06:59.065  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-09 02:06:59.065  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 02:06:59.065  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-09 02:06:59.065  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-09 02:06:59.065  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-09 02:06:59.065  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:06:59.065  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:06:59.065  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:06:59.066  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:06:59.066  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:06:59.066  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:06:59.067  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:06:59.067  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:06:59.067  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:06:59.067  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:06:59.067  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:06:59.067  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:06:59.067  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:06:59.067  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:06:59.069  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:06:59.069  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:06:59.069  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:06:59.069  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:06:59.070  3820  3870 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 02:06:59.072  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 02:06:59.082  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:06:59.082  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:06:59.082  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:06:59.082  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:06:59.082  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:06:59.082  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:06:59.082  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:06:59.082  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 02:06:59.086  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 02:06:59.086  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 02:06:59.088  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 02:06:59.088  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 02:06:59.089  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 02:06:59.089  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 02:06:59.089  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 02:06:59.089  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:06:59.094  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:06:59.098  3820  3870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 02:06:59.099  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 02:06:59.110  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 02:06:59.116  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 02:06:59.117  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 02:06:59.124  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-09 02:06:59.131  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-09 02:06:59.132  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-09 02:06:59.132  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 02:06:59.135  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 02:06:59.137  3820  3870 D BluetoothAdapter: STATE_ON
,09-09 02:06:59.151  2684  2696 D BtGatt.GattService: registerClient() - UUID=1419f55e-31ba-4666-aa5c-99c99ceadb1d,
,09-09 02:06:59.153  2684  2703 D BtGatt.GattService: onClientRegistered() - UUID=1419f55e-31ba-4666-aa5c-99c99ceadb1d, clientIf=5
,09-09 02:06:59.155  3820  3833 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 02:06:59.159  2684  3461 D BtGatt.GattService: start scan with filters
,09-09 02:06:59.167  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 02:06:59.167  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 02:06:59.168  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-09 02:06:59.168  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-09 02:06:59.168  2684  2706 D BtGatt.ScanManager: handling starting scan
,09-09 02:06:59.171  2684  2706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
,09-09 02:06:59.174  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 02:06:59.175  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-09 02:06:59.176  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 02:06:59.180  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 02:06:59.184  3820  3870 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 02:06:59.186  2684  2703 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 02:06:59.186  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:06:59.187  2684  2706 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 02:06:59.202  2684  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 02:06:59.203  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:06:59.205  2684  2706 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 02:06:59.205  2684  2706 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 02:06:59.242  2684  2703 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 02:06:59.242  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:06:59.261  2684  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 02:06:59.261  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:06:59.679  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 02:06:59.680  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 02:06:59.680  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 02:07:00.766  2684  2684 D BtGatt.ScanManager: awakened up at time 136814
,09-09 02:07:00.769  2684  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:07:00.820  2684  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-09 02:07:00.820  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:00.821  2684  2703 D BtGatt.GattService: current time is 136870251300
09-09 02:07:00.823  2684  2703 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -94, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -78, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -63, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 02:07:00.827  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 02:07:00.830  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 02:07:00.832  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-09 02:07:00.832  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-09 02:07:00.833  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-09 02:07:00.834  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 02:07:01.141   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 02:07:02.323  2684  2684 D BtGatt.ScanManager: awakened up at time 138371
,09-09 02:07:02.325  2684  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:07:02.337  2684  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 02:07:02.338  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:03.839  2684  2684 D BtGatt.ScanManager: awakened up at time 139888
,09-09 02:07:03.844  2684  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:07:03.854  2684  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 02:07:03.854  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:04.170   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 02:07:04.194  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 02:07:04.194  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 02:07:04.195  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 02:07:04.195  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-09 02:07:04.195  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 02:07:04.196  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 02:07:04.196  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 02:07:04.196  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 02:07:04.197  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 02:07:04.199  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 02:07:04.199  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 02:07:04.202  3820  3870 D BluetoothAdapter: STATE_ON
09-09 02:07:04.205  2684  2695 D BtGatt.GattService: stopScan() - queue size =1
09-09 02:07:04.207  2684  3461 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 02:07:04.211  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 02:07:04.211  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 02:07:04.212  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 02:07:04.213  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 02:07:04.213  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 02:07:04.215  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 02:07:04.216  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 02:07:04.216  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
,09-09 02:07:04.217  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 02:07:04.218  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 02:07:04.221  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 02:07:04.221  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 02:07:04.222  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 02:07:04.222  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 02:07:04.223  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:04.223  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 02:07:04.223  2684  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 02:07:04.223  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:04.223  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:04.223  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:04.224  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:04.224  2684  2706 D BtGatt.ScanManager: stopping BLe Batch
09-09 02:07:04.224  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 02:07:04.224  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:04.234  2684  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 02:07:04.234  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:04.234  2684  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:07:04.252  2684  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,09-09 02:07:04.252  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:07:04.252  2684  2703 D BtGatt.GattService: current time is 140300855548
09-09 02:07:04.252  2684  2703 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -90, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-09 02:07:04.252  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-09 02:07:04.253  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-09 02:07:04.253  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-09 02:07:04.723  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 02:07:06.399  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:06.414  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:06.419  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:06.474  1523  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 02:07:06.474  1523  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 02:07:06.475  1523  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:07:06.475  1523  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:07:06.515  3527  3527 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 02:07:06.517  3527  3527 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 02:07:06.520  3527  3527 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-09 02:07:09.226  3820  3870 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-09 02:07:09.233  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:07:09.248  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:07:09.248  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:09.248  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:09.248  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:09.248  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:07:09.248  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:09.248  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:07:09.248  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:07:09.255  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:07:09.256  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 02:07:09.257  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 02:07:09.258  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-09 02:07:09.260  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-09 02:07:09.260  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 02:07:09.261  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-09 02:07:09.264  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:09.273  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:09.276  3820  3870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 02:07:09.276  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 02:07:09.287  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 02:07:09.289  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 02:07:09.289  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 02:07:09.297  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 02:07:09.298  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 02:07:09.298  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-09 02:07:09.302  3820  3870 D BluetoothAdapter: STATE_ON
,09-09 02:07:09.307  2684  2695 D BtGatt.GattService: registerClient() - UUID=fd6de94e-0641-49fd-9b29-1d7a4a7c77d2
,09-09 02:07:09.308  2684  2703 D BtGatt.GattService: onClientRegistered() - UUID=fd6de94e-0641-49fd-9b29-1d7a4a7c77d2, clientIf=5
,09-09 02:07:09.309  3820  3831 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-09 02:07:09.311  2684  3461 D BtGatt.GattService: start scan with filters
,09-09 02:07:09.318  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 02:07:09.318  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 02:07:09.318  2684  2706 D BtGatt.ScanManager: handling starting scan
09-09 02:07:09.319  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 02:07:09.319  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 02:07:09.329  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 02:07:09.330  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 02:07:09.331  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 02:07:09.334  2684  2703 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 02:07:09.334  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:07:09.335  2684  2706 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 02:07:09.338  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 02:07:09.349  3820  3870 I io.jxcore.node.ConnectionHelper: start: OK
,09-09 02:07:09.352  2684  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 02:07:09.352  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:09.352  2684  2706 D BtGatt.ScanManager: Starting BLE batch scan
09-09 02:07:09.353  2684  2706 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 02:07:09.353  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:09.353  3820  3870 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 02:07:09.353  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:09.354  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 02:07:09.354  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:09.354  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 02:07:09.354  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 02:07:09.354  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 02:07:09.354  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 02:07:09.354  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 02:07:09.354  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 02:07:09.354  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 02:07:09.356  3820  3870 D BluetoothAdapter: STATE_ON
,09-09 02:07:09.356  2684  3461 D BtGatt.GattService: stopScan() - queue size =1
09-09 02:07:09.357  2684  2695 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 02:07:09.357  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 02:07:09.357  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 02:07:09.357  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 02:07:09.358  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 02:07:09.358  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-09 02:07:09.359  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 02:07:09.359  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 02:07:09.359  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-09 02:07:09.359  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 02:07:09.359  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 02:07:09.361  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 02:07:09.361  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 02:07:09.361  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 02:07:09.362  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:09.362  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:09.362  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 02:07:09.362  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:09.362  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:09.362  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:09.362  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:09.362  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:09.363  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:09.363  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:09.364  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:09.364  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:09.364  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:09.364  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:09.365  3820  3870 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-09 02:07:09.370  2684  2703 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-09 02:07:09.370  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:07:09.370  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:07:09.375  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:07:09.375  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:09.375  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:09.375  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:09.375  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:07:09.375  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:09.375  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:07:09.375  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:07:09.377  2684  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-09 02:07:09.377  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:09.378  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:09.378  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 02:07:09.378  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-09 02:07:09.379  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 02:07:09.379  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 02:07:09.379  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 02:07:09.379  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 02:07:09.381  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:09.382  3820  3870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 02:07:09.382  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 02:07:09.384  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:09.385  2684  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-09 02:07:09.385  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:07:09.386  2684  2706 D BtGatt.ScanManager: stopping BLe Batch
,09-09 02:07:09.387  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 02:07:09.387  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 02:07:09.387  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-09 02:07:09.391  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 02:07:09.391  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 02:07:09.391  2684  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 02:07:09.391  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:07:09.391  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 02:07:09.391  2684  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:07:09.392  3820  3870 D BluetoothAdapter: STATE_ON
,09-09 02:07:09.394  2684  2695 D BtGatt.GattService: registerClient() - UUID=eaf8d76c-974f-40b6-ba9c-8bdd74c0ea45
,09-09 02:07:09.397  2684  2703 D BtGatt.GattService: onClientRegistered() - UUID=eaf8d76c-974f-40b6-ba9c-8bdd74c0ea45, clientIf=5
,09-09 02:07:09.398  3820  3833 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 02:07:09.398  2684  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-09 02:07:09.398  2684  2696 D BtGatt.GattService: start scan with filters
09-09 02:07:09.398  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:09.400  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 02:07:09.400  2684  2706 D BtGatt.ScanManager: handling starting scan
09-09 02:07:09.400  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 02:07:09.400  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 02:07:09.400  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 02:07:09.403  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 02:07:09.403  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 02:07:09.403  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 02:07:09.404  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 02:07:09.406  2684  2703 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-09 02:07:09.406  3820  3870 I io.jxcore.node.ConnectionHelper: start: OK
09-09 02:07:09.407  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:07:09.407  2684  2706 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 02:07:09.412  2684  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 02:07:09.412  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:07:09.412  2684  2706 D BtGatt.ScanManager: Starting BLE batch scan
09-09 02:07:09.412  2684  2706 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 02:07:09.421  2684  2703 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 02:07:09.421  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:09.428  2684  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 02:07:09.428  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:09.904  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 02:07:09.905  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 02:07:09.905  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 02:07:10.222   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-09 02:07:10.933  2684  2684 D BtGatt.ScanManager: awakened up at time 146982
,09-09 02:07:10.936  2684  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:07:10.986  2684  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-09 02:07:10.986  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:10.986  2684  2703 D BtGatt.GattService: current time is 147035300750
,09-09 02:07:10.987  2684  2703 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -80, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -94, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 02:07:10.989  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 02:07:10.990  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-09 02:07:10.990  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 02:07:10.991  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-09 02:07:10.992  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 02:07:10.993  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 02:07:12.489  2684  2684 D BtGatt.ScanManager: awakened up at time 148538
,09-09 02:07:12.492  2684  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:07:12.505  2684  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 02:07:12.505  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:14.008   874  1298 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-09 02:07:14.008  2684  2684 D BtGatt.ScanManager: awakened up at time 150057
,09-09 02:07:14.011  2684  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:07:14.030  1873  1873 I Keyboard.Facilitator: onFinishInput()
,09-09 02:07:14.036   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 02:07:14.036   874   894 I Adreno  : Build Date                       : 10/20/15
09-09 02:07:14.036   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 02:07:14.036   874   894 I Adreno  : Local Branch                     : M14
09-09 02:07:14.036   874   894 I Adreno  : Remote Branch                    : 
09-09 02:07:14.036   874   894 I Adreno  : Remote Branch                    : 
09-09 02:07:14.036   874   894 I Adreno  : Reconstruct Branch               : 
,09-09 02:07:14.041  2684  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,09-09 02:07:14.041  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:07:14.041  2684  2703 D BtGatt.GattService: current time is 150090260638
09-09 02:07:14.041  2684  2703 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -88, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 02:07:14.042  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-09 02:07:14.042  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 02:07:14.057   280  1301 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (160 us)
,09-09 02:07:14.407  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 02:07:14.407  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 02:07:14.408  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 02:07:14.409  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:14.409  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 02:07:14.410  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 02:07:14.410  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-09 02:07:14.410  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-09 02:07:14.410  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 02:07:14.411  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-09 02:07:14.411  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 02:07:14.413  3820  3870 D BluetoothAdapter: STATE_ON
,09-09 02:07:14.415  2684  2695 D BtGatt.GattService: stopScan() - queue size =1
09-09 02:07:14.420  2684  3461 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 02:07:14.422  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 02:07:14.423  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 02:07:14.423  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-09 02:07:14.424  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-09 02:07:14.425  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 02:07:14.432  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 02:07:14.433  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 02:07:14.433  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 02:07:14.434  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 02:07:14.435  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 02:07:14.437  2684  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
09-09 02:07:14.437  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:14.438  2684  2706 D BtGatt.ScanManager: stopping BLe Batch
,09-09 02:07:14.441  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 02:07:14.441  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 02:07:14.442  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 02:07:14.454  2684  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-09 02:07:14.455  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:07:14.455  2684  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:07:14.482  2684  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-09 02:07:14.482  2684  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:07:14.483  2684  2703 D BtGatt.GattService: current time is 150532411255
,09-09 02:07:14.484  2684  2703 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-09 02:07:14.485  2684  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 02:07:14.652  3820  3820 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-09 02:07:14.652  3820  3820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-09 02:07:14.691   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-09 02:07:14.698  3820  3820 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9f4c2e8 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@14f295d, 16908290=android.view.AbsSavedState$1@14f295d}, android:focusedViewId=100}]}]
,09-09 02:07:14.699  3820  3820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-09 02:07:14.700   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-09 02:07:14.700  3820  3820 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-09 02:07:14.700  3820  3820 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-09 02:07:14.706   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-09 02:07:14.713   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-09 02:07:14.713   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-09 02:07:14.935   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-09 02:07:14.940   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-09 02:07:14.945  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 02:07:14.945   874  1334 D SurfaceControl: Excessive delay in setPowerMode(): 233ms
,09-09 02:07:14.945  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:14.945  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 02:07:14.948   874   894 I DreamManagerService: Entering dreamland.
09-09 02:07:14.949   874   894 I PowerManagerService: Dozing...
09-09 02:07:14.952   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-09 02:07:15.020   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-09 02:07:15.021   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-09 02:07:15.030   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 02:07:15.051   874  1310 E native  : do suspend false
,09-09 02:07:15.051  1916  3892 D NfcService: Discovery configuration equal, not updating.
,09-09 02:07:15.079   874  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 02:07:15.098   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 02:07:15.108   874  1310 E native  : do suspend true
,09-09 02:07:15.153   377  1281 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-09 02:07:15.154   377  1281 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-09 02:07:15.537   874  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-09 02:07:19.443  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 02:07:19.444  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:19.444  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:07:19.445  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 02:07:19.445  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:19.446  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 02:07:19.446  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:19.446  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:07:19.447  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.447  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:19.447  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:19.449  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:19.449  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:19.452  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:19.453  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 02:07:19.453  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.453  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:19.456  3820  3870 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-09 02:07:19.458  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:19.459  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:19.459  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 02:07:19.460  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:19.461  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:19.461  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.461  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
,09-09 02:07:19.462  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.462  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.462  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:19.463  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.463  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.463  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.463  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:19.465  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:19.466  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:19.466  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:07:19.466  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:19.469  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-09 02:07:19.469  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:19.469  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:19.470  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 02:07:19.470  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 02:07:19.471  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.471  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.471  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
,09-09 02:07:19.472  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.472  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.472  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 02:07:19.472  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.473  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.473  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:19.473  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:19.475  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 02:07:19.475  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:19.476  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.476  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:19.478  3820  3870 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-09 02:07:19.478  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:19.479  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 02:07:19.479  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 02:07:19.480  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:19.480  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.480  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:19.480  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:19.481  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:07:19.481  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.481  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:19.481  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.482  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:19.482  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.482  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:19.484  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 02:07:19.485  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:19.485  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.485  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.486  3820  3870 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-09 02:07:19.486  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:19.486  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:19.486  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:07:19.486  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 02:07:19.486  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.487  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.487  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:19.487  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.487  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.487  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:19.487  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:19.487  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.487  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.487  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.488  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:19.488  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:19.489  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.489  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:19.489  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 02:07:19.489  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 02:07:19.490  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 02:07:19.490  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-09 02:07:19.490  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-09 02:07:19.490  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 02:07:19.490  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-09 02:07:19.490  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 02:07:19.490  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-09 02:07:19.490  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:19.490  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 02:07:19.491  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:07:19.491  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:19.491  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.491  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.491  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
,09-09 02:07:19.491  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.491  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.491  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:19.491  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.491  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.492  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:19.492  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.493  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:19.493  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:19.493  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.493  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.494  3820  3870 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 02:07:19.494  3820  3870 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-09 02:07:19.494  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-09 02:07:19.498  3820  3870 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 02:07:19.498  3820  3870 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-09 02:07:19.498  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-09 02:07:19.498  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-09 02:07:19.499  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-09 02:07:19.499  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-09 02:07:19.499  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-09 02:07:19.499  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-09 02:07:19.499  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-09 02:07:19.499  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-09 02:07:19.499  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-09 02:07:19.499  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-09 02:07:19.499  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-09 02:07:19.499  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-09 02:07:19.500  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-09 02:07:19.500  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-09 02:07:19.500  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-09 02:07:19.500  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-09 02:07:19.500  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-09 02:07:19.500  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-09 02:07:19.500  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-09 02:07:19.500  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-09 02:07:19.500  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-09 02:07:19.500  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-09 02:07:19.501  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-09 02:07:19.501  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-09 02:07:19.501  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-09 02:07:19.501  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-09 02:07:19.501  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-09 02:07:19.501  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-09 02:07:19.501  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-09 02:07:19.501  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-09 02:07:19.501  3820  3870 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-09 02:07:19.502  3820  3870 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-09 02:07:19.502  3820  3870 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-09 02:07:19.502  3820  3870 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-09 02:07:19.502  3820  3870 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 02:07:19.502  3820  3870 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-09 02:07:19.502  3820  3870 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 02:07:19.503  3820  3870 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-09 02:07:19.503  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-09 02:07:19.505  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-09 02:07:19.506  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-09 02:07:19.506  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-09 02:07:19.507  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-09 02:07:19.507  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-09 02:07:19.507  3820  3870 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-09 02:07:19.507  3820  3870 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-09 02:07:19.507  3820  3870 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-09 02:07:19.508  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:19.508  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:19.508  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 02:07:19.509  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:19.509  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.509  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.509  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-09 02:07:19.510  3820  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 394)
09-09 02:07:19.510  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:19.510  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:07:19.510  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.510  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:19.510  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.510  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.512  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.512  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.514  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 02:07:19.514  3820  3896 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 02:07:19.514  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:19.514  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.514  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.514  3820  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 394
09-09 02:07:19.515  3820  3870 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-09 02:07:19.516  3820  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 394)
09-09 02:07:19.516  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:19.516  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:19.516  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:07:19.516  3820  3897 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 394)
,09-09 02:07:19.517  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:19.517  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.517  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.518  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:19.518  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.518  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.518  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 02:07:19.518  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.518  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.518  3820  3896 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 394)
09-09 02:07:19.518  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.518  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.519  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:19.519  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 02:07:19.519  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.520  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.520  3820  3870 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-09 02:07:19.520  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:19.521  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:19.521  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-09 02:07:19.521  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:19.521  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.521  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.521  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:19.521  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.521  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.521  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 02:07:19.521  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.522  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.522  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.522  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.523  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:19.523  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:19.523  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.523  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.523  3820  3870 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-09 02:07:19.524  3820  3870 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-09 02:07:19.524  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 02:07:19.524  3820  3870 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-09 02:07:19.524  3820  3870 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 02:07:19.524  3820  3870 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-09 02:07:19.524  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 02:07:19.524  3820  3870 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-09 02:07:19.524  3820  3870 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-09 02:07:19.524  3820  3870 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-09 02:07:19.525  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-09 02:07:19.525  3820  3870 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-09 02:07:19.526  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:19.526  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:19.526  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:07:19.526  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:19.526  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.526  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.526  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:19.526  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.526  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.526  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:19.526  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.526  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.526  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.526  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.527  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:19.528  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:19.528  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.528  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.528  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:19.528  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.528  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:19.528  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:19.528  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:19.528  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:19.528  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:19.528  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:19.529  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:20.543  2131  2655 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 02:07:20.585  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:20.591  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:20.673  1523  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 02:07:20.674  1523  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 02:07:20.675  1523  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:07:20.675  1523  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:07:20.733  3565  3900 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 02:07:20.733  3565  3900 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at jdm.a(PG:82)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at jcs.o(PG:406)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at jcn.a(PG:1379)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at jcs.i(PG:143)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at blb.a(PG:3937)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at czp.a(PG:18188)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at czp.a(PG:9081)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at czq.run(PG:1686)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:07:20.733  3565  3900 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at jdj.a(PG:4091)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at jdj.a(PG:1125)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at jdm.a(PG:77)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	... 12 more
09-09 02:07:20.733  3565  3900 E HttpOperation: Caused by: faj: BadAuthentication
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at fal.a(PG:38)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	at jdj.a(PG:4089)
09-09 02:07:20.733  3565  3900 E HttpOperation: 	... 14 more
,09-09 02:07:20.825  1523  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 02:07:20.826  1523  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 02:07:20.826  1523  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:07:20.827  1523  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:07:20.871  3565  3900 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 02:07:20.871  3565  3900 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at jdm.a(PG:82)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at jcs.o(PG:406)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at jcn.a(PG:1379)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at jcs.i(PG:143)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at hec.a(PG:42)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at hee.a(PG:102)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at czr.a(PG:65)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at kka.a(PG:108)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at czp.a(PG:19176)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at czp.a(PG:9081)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at czq.run(PG:1686)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:07:20.871  3565  3900 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at jdj.a(PG:4091)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at jdj.a(PG:1125)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at jdm.a(PG:77)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	... 15 more
09-09 02:07:20.871  3565  3900 E HttpOperation: Caused by: faj: BadAuthentication
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at fal.a(PG:38)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	at jdj.a(PG:4089)
09-09 02:07:20.871  3565  3900 E HttpOperation: 	... 17 more
,09-09 02:07:20.872  3565  3900 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 02:07:20.872  3565  3900 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at hec.a(PG:42)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at hee.a(PG:102)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at czr.a(PG:65)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at kka.a(PG:108)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	... 15 more
09-09 02:07:20.872  3565  3900 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at fal.a(PG:38)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 02:07:20.872  3565  3900 E ExperimentLoader: 	... 17 more
,09-09 02:07:21.018   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126609, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:07:24.529  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:07:24.530  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:24.530  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 02:07:24.530  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.531  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.531  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
,09-09 02:07:24.532  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 02:07:24.532  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:24.533  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:07:24.534  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 02:07:24.534  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.534  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.535  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
,09-09 02:07:24.535  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:24.535  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:24.536  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:24.536  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:24.536  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:24.536  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.537  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.540  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 02:07:24.541  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:24.541  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:24.542  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:24.547  3820  3870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-09 02:07:24.548  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 02:07:24.550  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-09 02:07:24.551  3820  3870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-09 02:07:24.551  3820  3870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 02:07:24.551  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-09 02:07:24.551  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 02:07:24.552  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 02:07:24.552  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:24.552  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 02:07:24.552  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-09 02:07:24.552  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 02:07:24.552  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:24.552  3820  3870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-09 02:07:24.553  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-09 02:07:24.553  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:24.553  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:24.553  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 02:07:24.553  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 02:07:24.553  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 02:07:24.553  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.554  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.555  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 02:07:24.555  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 02:07:24.555  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 02:07:24.555  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 02:07:24.555  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:24.555  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:24.556  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:24.556  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:07:24.556  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:24.556  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.556  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.556  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
,09-09 02:07:24.556  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:24.556  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:24.556  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:24.557  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.557  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.557  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.557  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:24.558  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:24.558  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:24.558  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:24.558  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:24.559  3820  3870 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-09 02:07:24.560  3820  3870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-09 02:07:24.560  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-09 02:07:24.562  3820  3902 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-09 02:07:24.562  3820  3902 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 02:07:24.562  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 02:07:24.563  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-09 02:07:24.563  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-09 02:07:24.563  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 02:07:24.563  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:24.563  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:07:24.563  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:24.563  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.563  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.564  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:24.564  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:07:24.564  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:24.564  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:24.564  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.564  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.564  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.564  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.565  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 02:07:24.565  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:24.566  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:24.566  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:24.570  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 02:07:24.570  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:24.570  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:07:24.571  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:07:24.571  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.571  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:24.571  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:24.571  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:24.571  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:24.571  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:24.571  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:24.571  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.571  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.571  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.572  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:24.573  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-09 02:07:24.573  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:24.573  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:24.574  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:07:24.574  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:07:24.574  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:07:24.574  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 02:07:24.574  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.575  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.575  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20b2d22 not in the list
09-09 02:07:24.575  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:07:24.575  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
09-09 02:07:24.575  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:24.575  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:24.575  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.575  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:24.575  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:24.576  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:07:24.576  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:07:24.576  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:24.577  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cec3b3 not in the list
,09-09 02:07:24.578  3820  3870 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-09 02:07:24.578  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 02:07:24.578  3820  3870 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-09 02:07:24.578  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-09 02:07:24.579  3820  3870 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-09 02:07:24.579  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-09 02:07:24.582  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-09 02:07:24.582  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-09 02:07:24.583  3820  3870 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-09 02:07:24.583  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-09 02:07:24.583  3820  3870 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-09 02:07:24.583  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-09 02:07:24.583  3820  3870 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-09 02:07:24.583  3820  3870 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-09 02:07:24.584  3820  3870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-09 02:07:24.584  3820  3870 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-09 02:07:24.585  3820  3870 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-09 02:07:24.585  3820  3870 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-09 02:07:24.585  3820  3870 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-09 02:07:24.585  3820  3870 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-09 02:07:24.586  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 02:07:24.586  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@83d22d2 added. We now have 3 listener(s)
09-09 02:07:24.586  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 02:07:24.589  3820  3870 D BluetoothAdapter: enable(): BT is already enabled..!
,09-09 02:07:24.589   874   885 D WifiService: setWifiEnabled: true pid=3820, uid=10000
09-09 02:07:24.589   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 02:07:24.646  2684  2796 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-09 02:07:24.646  2684  2813 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-09 02:07:25.056  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 02:07:26.279   874  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-09 02:07:27.135  1745  3904 I EventLogService: Opted in for usage reporting
,09-09 02:07:27.137  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-09 02:07:27.140  1745  3904 I EventLogService: Aggregate from 1473377846962 (log), 1473377846962 (data)
,09-09 02:07:27.257  1523  3906 I VacuumService: Vacuum at: now=1473379647257 tag=VacuumService
,09-09 02:07:27.425  1523  3907 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-09 02:07:27.429  1523  3907 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-09 02:07:27.481  1523  3907 W Uploader:  no longer exists, so no auth token.
,09-09 02:07:27.500  1745  3904 W EventLogAggregator: Unknown tag: snet_gcore
09-09 02:07:27.500  1745  3904 W EventLogAggregator: Unknown tag: snet_launch_service
,09-09 02:07:27.548  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:27.565  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:27.568  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:27.597  1745  3904 I ServiceDumpSys: dumping service [account]
,09-09 02:07:27.620  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-09 02:07:27.620  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 02:07:27.620  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:07:27.621  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:07:27.649  3527  3527 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 02:07:27.649  3527  3527 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-09 02:07:27.649  3527  3527 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-09 02:07:28.566  1523  3907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-09 02:07:28.567  1523  3907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-09 02:07:28.569  1523  3907 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:07:28.570  1523  3907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:07:28.599  1523  3907 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 02:07:28.599  1523  3907 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 02:07:28.599  1523  3907 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 02:07:29.367  1523  3907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-09 02:07:29.367  1523  3907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-09 02:07:29.368  1523  3907 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:07:29.368  1523  3907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:07:29.388  1523  3907 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 02:07:29.388  1523  3907 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-09 02:07:29.388  1523  3907 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-09 02:07:29.442   874  1885 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:07:29.597  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 02:07:29.597  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30fffa3 added. We now have 4 listener(s)
09-09 02:07:29.598  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 02:07:29.611  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:07:29.612  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30fffa3 removed from the list
09-09 02:07:29.612  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:29.612  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:07:29.612  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:29.615  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 02:07:29.615  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c5b2a0 added. We now have 4 listener(s)
,09-09 02:07:29.616  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 02:07:29.619  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:07:29.620  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8c5b2a0 removed from the list
09-09 02:07:29.620  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 02:07:29.620  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:29.620  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:07:29.623  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 02:07:29.623  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59fe59 added. We now have 4 listener(s)
09-09 02:07:29.624  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 02:07:29.630   874  1713 D WifiService: setWifiEnabled: false pid=3820, uid=10000
,09-09 02:07:29.631   874  1713 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 02:07:29.643  2684  2699 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 02:07:29.644  2684  2699 D BluetoothAdapterProperties: Setting state to 13
09-09 02:07:29.644  2684  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-09 02:07:29.646  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:07:29.647  2684  2699 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 02:07:29.652  2684  2699 I BluetoothAdapterState: Entering PendingCommandState
09-09 02:07:29.652  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:29.653  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:07:29.653  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:29.653  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:29.653  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:29.653  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:29.653  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:29.653  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:07:29.653  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:07:29.654  2684  2684 D BluetoothMapService: onReceive
09-09 02:07:29.654  2684  2684 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 02:07:29.654  2684  2684 D BluetoothMapService: STATE_TURNING_OFF
,09-09 02:07:29.655  2684  2684 D BluetoothMapService: MAP Service closeService in
09-09 02:07:29.655  2684  2684 D BluetoothMapMasInstance0: MAP Service shutdown
,09-09 02:07:29.655  2684  2684 D ObexServerSockets0: shutdown(block = true)
,09-09 02:07:29.655  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:29.656  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:29.656  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 02:07:29.656  2684  2825 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 02:07:29.657  2684  2684 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 02:07:29.657  2684  2684 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 02:07:29.658  2684  2813 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-09 02:07:29.659  2684  2826 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 02:07:29.659  2684  2684 I BtOppRfcommListener: stopping Accept Thread
,09-09 02:07:29.660  2684  3448 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-09 02:07:29.660  2684  3448 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-09 02:07:29.661  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:29.663  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-09 02:07:29.664  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:29.668  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:29.669  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:29.669  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:29.669  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:29.669  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:29.669  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:29.669  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:29.669  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:07:29.669  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:07:29.669  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:29.670  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:29.670   874  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 02:07:29.670   874  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 02:07:29.671   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 02:07:29.671   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 02:07:29.673  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.673  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-09 02:07:29.673  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:29.673  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:29.673  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:29.673  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:29.673  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:29.673  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:07:29.673  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 02:07:29.674  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:29.674  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:07:29.677  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:29.680   874   887 I ActivityManager: Start proc 3922:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-09 02:07:29.681  2684  2703 D BluetoothAdapterProperties: Scan Mode:20
,09-09 02:07:29.681  2684  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 02:07:29.684  2684  2684 D HeadsetService: Received stop request...Stopping profile...
09-09 02:07:29.686   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 02:07:29.687   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 02:07:29.687  1366  2295 D BluetoothHeadset: Proxy object disconnected
09-09 02:07:29.687  2684  2684 V BluetoothAdapterState: isTurningOff()=true
,09-09 02:07:29.687   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 02:07:29.687  2684  2684 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:29.687  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 02:07:29.687  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:29.687  1932  2233 D BluetoothHeadset: Proxy object disconnected
,09-09 02:07:29.688  1366  1366 D HeadsetProfile: Bluetooth service disconnected
09-09 02:07:29.688  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:29.689  2684  2684 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 02:07:29.689  2684  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.,
,09-09 02:07:29.689   874  1310 E native  : do suspend true
09-09 02:07:29.689  2684  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 02:07:29.689  2684  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 02:07:29.689  2684  2703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 02:07:29.689  2684  2703 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 02:07:29.690  2684  2684 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 02:07:29.691  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:29.691  2684  2684 D A2dpService: Received stop request...Stopping profile...
,09-09 02:07:29.691  2684  2818 D A2dpStateMachine: Exit Disconnected: -1
09-09 02:07:29.693  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:29.694  1366  1366 D BluetoothA2dp: Proxy object disconnected
,09-09 02:07:29.694   874   874 D BluetoothA2dp: Proxy object disconnected
,09-09 02:07:29.695  2684  2684 D HidService: Received stop request...Stopping profile...
,09-09 02:07:29.695  2684  2684 D HidService: Stopping Bluetooth HidService
,09-09 02:07:29.696  1366  1366 D BluetoothInputDevice: Proxy object disconnected
,09-09 02:07:29.696  1366  1366 D HidProfile: Bluetooth service disconnected
09-09 02:07:29.696  2684  2684 D HealthService: Received stop request...Stopping profile...
09-09 02:07:29.697  2684  2684 D PanService: Received stop request...Stopping profile...
09-09 02:07:29.698   874  1887 D DhcpClient: Clearing IP address
,09-09 02:07:29.698  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 02:07:29.698  1366  1366 D PanProfile: Bluetooth service disconnected
09-09 02:07:29.699   373   872 D CommandListener: Setting iface cfg
09-09 02:07:29.699  2684  2684 D BluetoothMapService: Received stop request...Stopping profile...
09-09 02:07:29.699  2684  2684 D BluetoothMapService: stop()
,09-09 02:07:29.699  2684  2684 D BluetoothMapAppObserver: deinitObservers()
09-09 02:07:29.699  2684  2684 D BluetoothMapAppObserver: removeReceiver()
09-09 02:07:29.700  1366  1366 D BluetoothMap: Proxy object disconnected
09-09 02:07:29.701  1366  1366 D MapProfile: Bluetooth service disconnected
,09-09 02:07:29.701  2684  2684 V BluetoothAdapterState: isTurningOff()=true
09-09 02:07:29.701  2684  2684 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:29.701  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:29.701  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:29.702   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-09 02:07:29.702  2684  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 02:07:29.702  2684  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 02:07:29.702  2684  2796 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 02:07:29.702  2684  2796 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 02:07:29.702  2684  2796 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 02:07:29.702  2684  2796 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 02:07:29.702  2684  2703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 02:07:29.703  2684  2684 V BluetoothAdapterState: isTurningOff()=true
,09-09 02:07:29.703  2684  2684 V BluetoothAdapterState: isTurningOn()=false
,09-09 02:07:29.703  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 02:07:29.703  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:29.703  2684  2684 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-09 02:07:29.703  2684  2703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 02:07:29.703  2684  2684 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 02:07:29.704  2684  2684 V BluetoothAdapterState: isTurningOff()=true
09-09 02:07:29.704  2684  2684 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:29.704  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 02:07:29.704  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:29.704  2684  2684 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-09 02:07:29.704  2684  2703 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 02:07:29.704  2684  2684 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 02:07:29.705  2684  2684 V BluetoothAdapterState: isTurningOff()=true
09-09 02:07:29.705  2684  2684 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:29.705  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:29.705  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 02:07:29.705  2684  2684 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 02:07:29.705  2684  2684 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 02:07:29.705   874  1888 D DhcpClient: Receive thread stopped
09-09 02:07:29.706  2684  2684 D BluetoothMapService: MAP Service closeService in
09-09 02:07:29.706  2684  2684 V BluetoothAdapterState: isTurningOff()=true
,09-09 02:07:29.706  2684  2684 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:29.706  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 02:07:29.706  2684  2684 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:29.707  2684  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 02:07:29.707  2684  2699 D BluetoothAdapterProperties: Setting state to 15
09-09 02:07:29.707  2684  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 02:07:29.707  2684  2684 D BluetoothMapService: cleanup()
09-09 02:07:29.707  2684  2684 D BluetoothMapService: MAP Service closeService in
,09-09 02:07:29.707  2684  2699 I BluetoothAdapterState: Entering BleOnState
09-09 02:07:29.707  1366  1386 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 02:07:29.708  1366  2050 D BluetoothMap: onBluetoothStateChange: up=false
09-09 02:07:29.708  1366  1378 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 02:07:29.709  1366  2295 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 02:07:29.709   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 02:07:29.709   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-09 02:07:29.713   874  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
09-09 02:07:29.714   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 02:07:29.714   874  1310 E native  : do suspend true
09-09 02:07:29.715   396   396 E Parcel  : Reading a NULL string not supported here.
09-09 02:07:29.716   874  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-09 02:07:29.718  1366  1378 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 02:07:29.718   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 02:07:29.718   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 02:07:29.718   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 02:07:29.718  1932  2232 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 02:07:29.718   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 02:07:29.719  1366  2050 D BluetoothPan: onBluetoothStateChange on: false
09-09 02:07:29.719  2684  2699 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 02:07:29.719  2684  2699 D BluetoothAdapterProperties: Setting state to 16
09-09 02:07:29.719  2684  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-09 02:07:29.720  2684  2699 D BluetoothAdapterProperties: onBleDisable
09-09 02:07:29.720  2684  2699 I BluetoothAdapterState: Entering PendingCommandState
09-09 02:07:29.720  2684  2700 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 02:07:29.720  2684  2703 D BluetoothAdapterProperties: Scan Mode:20
09-09 02:07:29.721  2684  2796 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 02:07:29.721  2684  2796 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 02:07:29.727  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.727  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:29.727  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:29.727  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:29.727  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:29.727  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:29.727  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:29.727  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:29.727  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:07:29.728  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.728  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:29.730  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.730  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:29.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:29.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:29.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:29.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:29.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:29.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:29.730  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:29.731  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.731  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:29.732  1523  2126 V NativeCrypto: Read error: ssl=0xaa234a00: I/O error during system call, Connection timed out
,09-09 02:07:29.732  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.732  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:29.732  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:29.732  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:29.732  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:29.732  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:29.732  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:29.732  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:29.732  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:29.733  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.733  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:29.734  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:29.736  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:29.737  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:29.740  1523  2126 V NativeCrypto: SSL shutdown failed: ssl=0xaa234a00: I/O error during system call, Broken pipe
,09-09 02:07:29.744   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 02:07:29.761   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 02:07:29.761   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 02:07:29.762   874  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-09 02:07:29.762   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 02:07:29.764   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 02:07:29.765   874   891 D Tethering: MasterInitialState.processMessage what=3
09-09 02:07:29.767  3399  3399 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dedc1a7 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-09 02:07:29.768  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:29.770  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:29.771  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:29.778   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-09 02:07:29.780  2131  2334 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 02:07:29.780  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.780  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:29.780  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:29.780  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:29.780  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:29.780  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:29.780  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:29.780  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:29.780  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:29.780   874  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-09 02:07:29.781  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.781  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:29.782  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.782  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:29.782  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:29.782  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:29.782  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:29.782  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:29.782  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:29.782  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:29.782  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:07:29.783  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.783  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:29.784  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.784  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:29.784  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:29.784  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:29.784  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:29.784  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:29.784  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:29.784  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:29.784  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:07:29.785  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:29.785  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:29.796  3922  3922 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-09 02:07:29.804  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 02:07:29.809  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 02:07:29.812   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@486fa0c:true
09-09 02:07:29.813   373   872 E Netd    : netlink response contains error (No such file or directory)
09-09 02:07:29.815  1523  3907 D Uploader: Network request failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,09-09 02:07:29.832   874   885 I ActivityManager: Start proc 3944:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-09 02:07:29.858  3922  3922 D LocalBluetoothProfileManager: Adding local MAP profile
,09-09 02:07:29.865  3944  3944 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-09 02:07:29.867  3922  3922 D BluetoothMap: Create BluetoothMap proxy object
,09-09 02:07:29.871  3922  3922 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-09 02:07:29.889  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,09-09 02:07:29.891   874  1991 I ActivityManager: Killing 3061:com.google.android.talk/u0a61 (adj 15): empty #17
,09-09 02:07:29.924  2684  2703 I bt_hci  : shut_down
,09-09 02:07:30.023  2684  2707 D bt_hwcfg: hw_epilog_process
,09-09 02:07:30.023  2684  2707 I bt_vendor: low_power_mode_cb
,09-09 02:07:30.045  2684  2707 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-09 02:07:30.046  2684  2707 I bt_vendor: epilog_cb
,09-09 02:07:30.046  2684  2707 I bt_hci  : epilog_finished_callback
,09-09 02:07:30.052  2684  2703 I bt_hci_h4: hal_close
09-09 02:07:30.053  2684  2703 I bt_userial_vendor: device fd = 51 close
,09-09 02:07:30.106  3944  3944 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:07:30.106  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:07:30.107  3944  3944 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:07:30.107  3944  3944 D StrictMode: StrictMode policy violation; ~duration=91 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:07:30.107  3944  3944 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:07:30.107  3944  3944 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.k.d(PG:583)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.e.b(PG:170)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:07:30.107  3944  3944 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:07:30.107  3944  3944 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.File.exists(File.java:361)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:07:30.107  3944  3944 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:07:30.107  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:07:30.116  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 02:07:30.128  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-09 02:07:30.133  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,09-09 02:07:30.189   874  1992 I ActivityManager: Start proc 3975:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-09 02:07:30.189   874  1992 I ActivityManager: Killing 3579:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-09 02:07:30.262  2684  2700 D bt_stack_manager: event_shut_down_stack finished.
,09-09 02:07:30.263  2684  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 02:07:30.267  2684  2699 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 02:07:30.268  2684  2684 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 02:07:30.268  2684  2684 D BtGatt.GattService: Received stop request...Stopping profile...
,09-09 02:07:30.268  2684  2684 D BtGatt.GattService: stop()
09-09 02:07:30.268  2684  2684 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 02:07:30.270  2684  2684 V BluetoothAdapterState: isTurningOff()=false
09-09 02:07:30.270  2684  2684 V BluetoothAdapterState: isTurningOn()=false
,09-09 02:07:30.270  2684  2684 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:30.270  2684  2684 V BluetoothAdapterState: isBleTurningOff()=true
,09-09 02:07:30.270  2684  2699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 02:07:30.271  2684  2699 D BluetoothAdapterProperties: Setting state to 10
,09-09 02:07:30.271  2684  2699 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-09 02:07:30.271  2684  2699 I BluetoothAdapterState: Entering OffState
,09-09 02:07:30.272   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-09 02:07:30.275  3975  3975 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-09 02:07:30.286  2684  2684 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 02:07:30.286  2684  2684 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-09 02:07:30.287  2684  2684 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 02:07:30.287  2684  2700 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-09 02:07:30.289  2684  2700 D bt_stack_manager: event_clean_up_stack finished.
,09-09 02:07:30.300  2684  2684 I art     : System.exit called, status: 0
,09-09 02:07:30.300  2684  2684 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 02:07:30.367   874  1373 I ActivityManager: Process com.android.bluetooth (pid 2684) has died
,09-09 02:07:30.398  3944  3970 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-09 02:07:30.481  3975  3995 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-09 02:07:30.481  3975  3995 I Babel_SMS: MmsConfig.loadMmsSettings
09-09 02:07:30.482  3975  3995 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
09-09 02:07:30.482  3975  3995 I Babel_SMS: MmsConfig.loadFromDatabase
,09-09 02:07:30.541  3975  3995 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-09 02:07:30.541  3975  3995 I Babel_SMS: MmsConfig.loadFromResources
,09-09 02:07:30.548  3975  3995 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-09 02:07:30.552  3975  3995 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-09 02:07:30.582  3975  3975 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-09 02:07:30.582   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a781f04:true
,09-09 02:07:30.584  3975  3975 I Babel_Crash: startup - clean
,09-09 02:07:30.607  3975  3975 I Babel_telephony: TeleModule.launchCompleted
,09-09 02:07:30.619   874  1994 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 02:07:30.629  3975  3975 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-09 02:07:30.638  3975  3975 W Babel   : BAM#gBA: invalid account id: -1
09-09 02:07:30.638  3975  3975 W Babel   : BAM#gBA: invalid account id: -1
09-09 02:07:30.638  3975  3975 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-09 02:07:30.650  3975  4000 I Babel   : deleted: false for 0
,09-09 02:07:30.655   874   885 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-09 02:07:30.677  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 02:07:30.683  1745  1745 D SystemUpdateService: onCreate
,09-09 02:07:30.698  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 02:07:30.707  1745  4002 I SystemUpdateService: active receiver: enabled
,09-09 02:07:30.719  1745  4002 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 02:07:30.721  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 02:07:30.726  1745  2432 I iu.UploadsManager: num queued entries: 0
09-09 02:07:30.726  1745  4002 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-09 02:07:30.727  1745  2432 I iu.UploadsManager: num updated entries: 0
09-09 02:07:30.727  1745  4002 I SystemUpdateService: now status is 0 (complete)
,09-09 02:07:30.727  1745  4002 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 02:07:30.727  1745  4002 I SystemUpdateService: file has been verified
,09-09 02:07:30.727  1745  2432 I iu.SyncManager: NEXT; no task
09-09 02:07:30.727  1745  4002 I SystemUpdateService: OTA package size = 12249756
,09-09 02:07:30.736  1745  4002 I SystemUpdateService: showing system update notification
,09-09 02:07:30.746  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 02:07:30.748  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 02:07:30.759  3975  3975 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 02:07:30.762   874  1714 I ActivityManager: Start proc 4004:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-09 02:07:30.765  1745  1745 D SystemUpdateService: onDestroy
,09-09 02:07:30.797  4004  4004 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-09 02:07:30.806  4004  4004 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 02:07:30.825  4004  4004 D SprintDMHelper: simOperator: 
09-09 02:07:30.825  4004  4004 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 02:07:30.828  3975  3975 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-09 02:07:30.839  3975  3975 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-09 02:07:30.841  3975  3975 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 02:07:30.855   874   884 I ActivityManager: Start proc 4016:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-09 02:07:30.858  3975  3975 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 02:07:30.863  3975  3975 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-09 02:07:30.871   874  1713 I ActivityManager: Killing 3399:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-09 02:07:30.959  3975  3975 I vclib   : onServiceConnected
,09-09 02:07:31.076   874  1714 I ActivityManager: Start proc 4031:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-09 02:07:31.080  3975  4030 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-09 02:07:31.084   874  1991 I ActivityManager: Killing 3471:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-09 02:07:31.168  4031  4031 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-09 02:07:31.241  4031  4031 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 02:07:31.241  4031  4031 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 02:07:31.241  4031  4031 I GAv4    :   adb logcat -s GAv4
,09-09 02:07:31.258  4031  4031 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 02:07:31.264  4031  4031 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 02:07:31.288  4031  4048 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 02:07:31.410  4031  4031 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-09 02:07:31.451  4031  4031 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-09 02:07:31.463  4031  4031 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7505-7511)
,09-09 02:07:31.463  4031  4031 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-09 02:07:31.473  4031  4031 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3746297}
,09-09 02:07:31.474  4031  4031 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-09 02:07:31.474  4031  4031 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 02:07:31.484  4031  4031 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-09 02:07:31.486  4031  4031 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 02:07:31.503  4031  4031 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-09 02:07:31.516  4031  4031 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 02:07:31.516  4031  4031 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 02:07:31.516  4031  4031 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-09 02:07:31.516  4031  4031 I Adreno  : Build Date                       : 10/20/15
09-09 02:07:31.516  4031  4031 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-09 02:07:31.516  4031  4031 I Adreno  : Local Branch                     : M14
09-09 02:07:31.516  4031  4031 I Adreno  : Remote Branch                    : 
09-09 02:07:31.516  4031  4031 I Adreno  : Remote Branch                    : 
09-09 02:07:31.516  4031  4031 I Adreno  : Reconstruct Branch               : 
,09-09 02:07:31.582  4031  4031 I NSApplication: Starting up...
,09-09 02:07:31.591  4031  4077 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-09 02:07:31.630   874  1713 I ActivityManager: Start proc 4082:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-09 02:07:31.636   874  1713 I ActivityManager: Killing 3510:android.process.acore/u0a5 (adj 15): empty #17
,09-09 02:07:31.735  4082  4082 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-09 02:07:31.947   874  1713 I ActivityManager: Killing 3674:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-09 02:07:32.034   874  1965 I ActivityManager: Start proc 4096:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-09 02:07:32.155  4096  4096 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-09 02:07:32.211  4096  4096 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-09 02:07:32.224   874   884 I ActivityManager: Killing 3691:com.android.musicfx/u0a18 (adj 15): empty #17
,09-09 02:07:34.659   874  1993 D WifiService: setWifiEnabled: true pid=3820, uid=10000
,09-09 02:07:34.659   874  1993 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 02:07:34.674   874  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-09 02:07:34.682  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:34.682  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:34.682  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:34.682  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:34.682  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:34.682  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:34.682  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:34.682  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:34.682  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:07:34.683  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:34.683  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:07:34.685  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:34.686  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:34.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:34.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:34.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:34.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:34.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:34.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:34.686  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:07:34.686  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:34.686  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:34.689  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:34.689  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:34.689  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:34.689  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:34.689  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:34.689  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:34.689  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:34.689  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:34.689  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:07:34.689  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:34.690  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:07:34.700   874  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-09 02:07:34.702   874  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 02:07:34.703   874  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-09 02:07:34.705   874  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-09 02:07:34.705   874  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-09 02:07:34.705   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-09 02:07:34.705   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 02:07:34.731   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 02:07:34.731   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 02:07:34.733   373   872 D CommandListener: Setting iface cfg
,09-09 02:07:34.741   874  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-09 02:07:34.741   874  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 02:07:34.741   874  1310 E native  : do suspend true
,09-09 02:07:34.753   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 02:07:34.756   874  1309 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 02:07:34.762   874  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 02:07:35.420   874  1991 I ActivityManager: Killing 2254:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-09 02:07:36.036   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 02:07:36.086   874  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.69 rxSuccessRate=9.62 delta 1000 -> 994
,09-09 02:07:36.089   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 02:07:36.089   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 02:07:36.108   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 02:07:36.164   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 02:07:36.167  1472  1472 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 02:07:36.656  1472  1472 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 02:07:36.709  1472  1472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 02:07:36.710  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 02:07:36.715   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 02:07:36.739   874  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 02:07:36.740   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 02:07:36.740   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 02:07:36.769   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 02:07:36.783   373   872 D CommandListener: Setting iface cfg
,09-09 02:07:36.783   874  1310 D WifiStateMachine: Start Dhcp Watchdog 2
,09-09 02:07:36.799   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 02:07:36.820   874  4131 D DhcpClient: Receive thread started
,09-09 02:07:36.906   874  1310 E native  : do suspend false
,09-09 02:07:36.926   874  1887 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 02:07:36.943   874  4131 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172649, domain null
,09-09 02:07:36.944   874  1887 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172649 seconds
,09-09 02:07:36.950   874  1887 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 02:07:36.975   874  4131 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 02:07:36.979   874  1887 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 02:07:36.985   373   872 D CommandListener: Setting iface cfg
,09-09 02:07:36.997   874  1887 D DhcpClient: Scheduling renewal in 86399s
,09-09 02:07:36.997   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-09 02:07:37.000   874  1310 E native  : do suspend true
,09-09 02:07:37.017   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 02:07:37.020   874  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 02:07:37.021   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 02:07:37.023   874  1312 D ConnectivityService: Adding iface wlan0 to network 101
,09-09 02:07:37.036   874  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 02:07:37.115   874  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 02:07:37.115   874  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101,
,09-09 02:07:37.119   874  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-09 02:07:37.124   874  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-09 02:07:37.128   874  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-09 02:07:37.145   874  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 02:07:37.159   874  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-09 02:07:37.160   874  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-09 02:07:37.160   874  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-09 02:07:37.162   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 02:07:37.163   874  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-09 02:07:37.163   874  1312 D ConnectivityService:    accepting network in place of null
,09-09 02:07:37.164   874  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 02:07:37.175   874  4130 D NetlinkSocketObserver: NeighborEvent{elapsedMs=173223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:07:37.209   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 02:07:37.251   874  4129 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.46,2a00:1450:401b:801::200e
,09-09 02:07:37.290   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 02:07:37.299   874  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 02:07:37.300   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 02:07:37.309   874  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-09 02:07:37.319   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 02:07:37.327  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:37.327   874  4129 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 00:07:37 GMT], X-Android-Received-Millis=[1473379657325], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473379657296]}
09-09 02:07:37.328  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:37.328  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:37.328  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:37.328  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:37.328  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:37.328  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:37.328  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:07:37.328  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 02:07:37.328  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:37.328  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:37.332  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:37.332  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:37.332  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:37.332  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:37.332  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:37.332  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:37.332  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:37.332  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:07:37.332  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 02:07:37.332  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:37.333   874  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-09 02:07:37.333  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:07:37.333   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-09 02:07:37.333   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-09 02:07:37.345   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 02:07:37.348  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:37.348  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:37.348  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:37.348  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:37.348  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:37.348  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:37.348  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:07:37.348  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:07:37.348  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-09 02:07:37.349  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:37.349  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:07:37.363  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 02:07:37.366  1745  1745 D SystemUpdateService: onCreate
,09-09 02:07:37.367  3774  4141 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 02:07:37.370  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 02:07:37.389  1745  4143 I SystemUpdateService: active receiver: enabled
,09-09 02:07:37.393  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 02:07:37.404  1745  2432 I iu.UploadsManager: num queued entries: 0
,09-09 02:07:37.406  1745  4143 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 02:07:37.407  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 02:07:37.409  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 02:07:37.411  1745  2432 I iu.UploadsManager: num updated entries: 0
,09-09 02:07:37.413  4004  4004 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 02:07:37.420  1745  4147 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-09 02:07:37.420  1745  4147 W BaseAppContext: Using Auth Proxy for data requests.
,09-09 02:07:37.422  1745  4147 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 02:07:37.422  4004  4004 D SprintDMHelper: simOperator: 
,09-09 02:07:37.422  4004  4004 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 02:07:37.436  1745  4143 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-09 02:07:37.436  1745  4143 I SystemUpdateService: now status is 0 (complete)
,09-09 02:07:37.436  1745  4143 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 02:07:37.436  1745  4143 I SystemUpdateService: file has been verified
,09-09 02:07:37.436  1745  4143 I SystemUpdateService: OTA package size = 12249756
,09-09 02:07:37.454  1745  2432 I iu.SyncManager: NEXT; no task
,09-09 02:07:37.459  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:37.460  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:37.483  1745  4143 I SystemUpdateService: showing system update notification
,09-09 02:07:37.511  3774  4154 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 02:07:37.541  1523  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 02:07:37.541  1523  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 02:07:37.541  1523  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:07:37.541  1523  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:07:37.574  3975  4150 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 02:07:37.592  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 02:07:37.592  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 02:07:37.592  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:07:37.592  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:07:37.606  3774  4154 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 02:07:37.607  3774  4141 E BooksSync: Soft error
09-09 02:07:37.607  3774  4141 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 02:07:37.607  3774  4141 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 02:07:37.609  3774  4141 E BooksSync: Sync error
09-09 02:07:37.609  3774  4141 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 02:07:37.609  3774  4141 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 02:07:37.609  3774  4141 I BooksSync: Finished books sync
,09-09 02:07:37.620   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 161175, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:07:37.635  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-09 02:07:37.635  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 02:07:37.635  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:07:37.635  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:07:37.658  1745  1745 D SystemUpdateService: onDestroy
,09-09 02:07:37.666  1745  4147 E MDM     : [179] SitrepService.a: Error sending sitrep.
,09-09 02:07:37.742  1745  1745 I GCM     : Message from null null
,09-09 02:07:37.743  1745  1745 E GCM     : Dropping message from null
,09-09 02:07:38.299   874  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-09 02:07:39.667   874  1714 D WifiService: setWifiEnabled: false pid=3820, uid=10000
,09-09 02:07:39.667   874  1714 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 02:07:39.705  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-09 02:07:39.715   874  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-09 02:07:39.715   874  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-09 02:07:39.716   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 02:07:39.716   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 02:07:39.739   874  1310 E native  : do suspend true
,09-09 02:07:39.760   874  1887 D DhcpClient: Clearing IP address
,09-09 02:07:39.762   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 02:07:39.772   373   872 D CommandListener: Setting iface cfg
,09-09 02:07:39.786  1523  4157 V NativeCrypto: Read error: ssl=0x9ad7be00: I/O error during system call, Connection timed out
,09-09 02:07:39.790   874  4131 D DhcpClient: Receive thread stopped
,09-09 02:07:39.793   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-09 02:07:39.794   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-09 02:07:39.797  1523  4157 V NativeCrypto: SSL shutdown failed: ssl=0x9ad7be00: I/O error during system call, Broken pipe
,09-09 02:07:39.801   874  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
09-09 02:07:39.801   396   396 E Parcel  : Reading a NULL string not supported here.
,09-09 02:07:39.804   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 02:07:39.804   874  1310 E native  : do suspend true
,09-09 02:07:39.814   874  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-09 02:07:39.843   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 02:07:39.869   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 02:07:39.869   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-09 02:07:39.872   874  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-09 02:07:39.873   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 02:07:39.880   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2,
,09-09 02:07:39.885   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 02:07:39.890  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:39.890  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:39.890  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:39.890  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:39.890  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:39.890  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:39.890  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:39.890  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:39.890  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:39.890  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:39.890  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:39.895  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:39.895  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:39.895  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:39.895  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:39.895  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:39.895  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:39.895  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:39.895  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:39.895  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:39.895  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:39.896  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:39.897  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:39.897  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:39.897  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:39.897  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:39.897  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:07:39.897  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:39.897  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:39.897  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:39.897  3820  3820 V io.jxcore.node.ConnectivityMonitor:  ,   - active network type is Wi-Fi: false
09-09 02:07:39.898  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:39.898  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:07:39.911  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-09 02:07:39.912   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 02:07:39.916  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:39.916  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:39.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:39.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:39.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:39.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:39.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:39.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:39.916  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:39.916  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:39.916  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:07:39.917   874  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-09 02:07:39.919  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:39.919  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:39.919  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:39.919  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:39.919  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:39.919  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:39.919  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:39.919  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:39.919  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:39.919  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:39.919  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:07:39.921  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:39.921  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:39.921  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:39.921  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:39.921  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:39.921  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:39.921  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:39.921  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:39.921  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:07:39.921  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:39.922  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:39.922  1745  1745 D SystemUpdateService: onCreate
09-09 02:07:39.923  2131  2334 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-09 02:07:39.929  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-09 02:07:39.942  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-09 02:07:39.944  1745  2432 I iu.UploadsManager: num queued entries: 0
,09-09 02:07:39.951  1745  4168 I SystemUpdateService: active receiver: enabled
,09-09 02:07:39.954  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 02:07:39.955  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 02:07:39.956  4004  4004 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 02:07:39.957  1745  2432 I iu.UploadsManager: num updated entries: 0
,09-09 02:07:39.958  1745  2432 I iu.SyncManager: NEXT; no task
,09-09 02:07:39.961  4004  4004 D SprintDMHelper: simOperator: 
09-09 02:07:39.961  4004  4004 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 02:07:39.970   373   872 E Netd    : netlink response contains error (No such file or directory)
09-09 02:07:39.971   874  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-09 02:07:39.978  3975  4172 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-09 02:07:39.983  1745  4168 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 02:07:39.988  1745  4168 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-09 02:07:39.988  1745  4168 I SystemUpdateService: now status is 0 (complete)
,09-09 02:07:39.988  1745  4168 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-09 02:07:39.992  1745  4168 I SystemUpdateService: file has been verified
,09-09 02:07:39.993  1745  4168 I SystemUpdateService: OTA package size = 12249756
,09-09 02:07:39.999  1745  4168 I SystemUpdateService: showing system update notification
,09-09 02:07:40.008  1745  1745 D SystemUpdateService: onDestroy
,09-09 02:07:44.722   874   891 I ActivityManager: Start proc 4175:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 02:07:44.839  4175  4175 D AdapterServiceConfig: Adding HeadsetService
,09-09 02:07:44.840  4175  4175 D AdapterServiceConfig: Adding A2dpService
,09-09 02:07:44.841  4175  4175 D AdapterServiceConfig: Adding HidService
,09-09 02:07:44.842  4175  4175 D AdapterServiceConfig: Adding HealthService
09-09 02:07:44.842  4175  4175 D AdapterServiceConfig: Adding PanService
09-09 02:07:44.843  4175  4175 D AdapterServiceConfig: Adding GattService
09-09 02:07:44.844  4175  4175 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 02:07:44.865   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27a3543:true
,09-09 02:07:44.865  4175  4175 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 02:07:44.871  4175  4175 I bt_bluedroid: init
,09-09 02:07:44.871  4175  4187 I BluetoothAdapterState: Entering OffState
,09-09 02:07:44.879  4175  4188 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 02:07:44.879  4175  4188 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-09 02:07:44.881  4175  4188 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 02:07:44.882  4175  4188 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 02:07:44.884  4175  4175 I bt_bluedroid: get_profile_interface socket
,09-09 02:07:44.887  4175  4175 I bt_bluedroid: get_profile_interface sdp
09-09 02:07:44.891  4175  4186 I bt_bluedroid: config_hci_snoop_log
09-09 02:07:44.891  4175  4191 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 02:07:44.895   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-09 02:07:44.897  4175  4191 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 02:07:44.904  4175  4187 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 02:07:44.905  4175  4187 D BluetoothAdapterProperties: Setting state to 14
09-09 02:07:44.905  4175  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 02:07:44.910  4175  4187 D BluetoothBondStateMachine: make
,09-09 02:07:44.915  4175  4192 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 02:07:44.924  4175  4187 I BluetoothAdapterState: Entering PendingCommandState
,09-09 02:07:44.925  4175  4175 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 02:07:44.931  4175  4175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
,09-09 02:07:44.932  4175  4175 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 02:07:44.933  4175  4175 D BtGatt.GattService: Received start request. Starting profile...
09-09 02:07:44.933  4175  4175 D BtGatt.GattService: start()
,09-09 02:07:44.934  4175  4175 I bt_bluedroid: get_profile_interface gatt
,09-09 02:07:44.935  4175  4175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
09-09 02:07:44.935  4175  4175 D BtGatt.AdvertiseManager: advertise manager created
,09-09 02:07:44.949  4175  4175 V BluetoothAdapterState: isTurningOff()=false
,09-09 02:07:44.949  4175  4175 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:44.949  4175  4175 V BluetoothAdapterState: isBleTurningOn()=true
09-09 02:07:44.949  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 02:07:44.950  4175  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 02:07:44.951  4175  4187 I bt_bluedroid: enable
09-09 02:07:44.951  4175  4188 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-09 02:07:44.953  4175  4188 I bt_hci  : start_up
,09-09 02:07:44.976  4175  4188 I bt_vendor: alloc value 0xb39e3189
09-09 02:07:44.976  4175  4188 I bt_vendor: init
09-09 02:07:44.976  4175  4188 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-09 02:07:44.977  4175  4188 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 02:07:45.088  4175  4188 D bt_hci  : start_up starting async portion
09-09 02:07:45.088  4175  4195 I bt_hci  : event_finish_startup
09-09 02:07:45.089  4175  4195 I bt_hci_h4: hal_open
09-09 02:07:45.089  4175  4195 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 02:07:45.097  4175  4195 I bt_userial_vendor: device fd = 51 open
,09-09 02:07:45.129  4175  4195 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 02:07:45.160  4175  4195 D bt_hwcfg: Chipset BCM4354A2
09-09 02:07:45.161  4175  4195 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 02:07:45.162  4175  4195 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 02:07:45.165   874  1312 D ConnectivityService: handlePromptUnvalidated 101
,09-09 02:07:45.818  4175  4195 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 02:07:45.820  4175  4195 D bt_hwcfg: Settlement delay -- 100 ms
,09-09 02:07:45.820  4175  4195 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 02:07:45.937  4175  4195 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 02:07:45.938  4175  4195 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 02:07:45.968  4175  4195 I bt_hwcfg: vendor lib fwcfg completed
,09-09 02:07:45.968  4175  4195 I bt_vendor: firmware callback
,09-09 02:07:45.968  4175  4195 I bt_hci  : firmware_config_callback
,09-09 02:07:45.979  4175  4197 I bt_btu  : btu_task pending for preload complete event
,09-09 02:07:45.980  4175  4197 I bt_btu_task: Bluetooth chip preload is complete
,09-09 02:07:45.980  4175  4197 I bt_btu  : btu_task received preload complete event
,09-09 02:07:45.990  4175  4197 I         : BTE_InitTraceLevels -- TRC_HCI
,09-09 02:07:45.990  4175  4197 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-09 02:07:45.991  4175  4197 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 02:07:45.991  4175  4197 I         : BTE_InitTraceLevels -- TRC_AVDT
09-09 02:07:45.991  4175  4197 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 02:07:45.992  4175  4197 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 02:07:45.992  4175  4197 I         : BTE_InitTraceLevels -- TRC_BNEP
09-09 02:07:45.992  4175  4197 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 02:07:45.992  4175  4197 I         : BTE_InitTraceLevels -- TRC_GAP
09-09 02:07:45.992  4175  4197 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 02:07:45.993  4175  4197 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 02:07:45.993  4175  4197 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 02:07:45.993  4175  4197 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 02:07:45.993  4175  4197 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 02:07:45.994  4175  4197 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 02:07:46.132  4175  4197 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3960d9d
,09-09 02:07:46.133  4175  4197 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3960d9d 
,09-09 02:07:46.140  4175  4191 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-09 02:07:46.142  4175  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 02:07:46.143  4175  4191 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 02:07:46.146  4175  4191 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 02:07:46.150  4175  4191 D BluetoothAdapterProperties: Scan Mode:20
,09-09 02:07:46.150  4175  4191 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 02:07:46.151  4175  4191 D bt_hci  : do_postload posting postload work item
,09-09 02:07:46.151  4175  4195 I bt_hci  : event_postload
,09-09 02:07:46.151  4175  4195 I bt_vendor: sco_config_cb
,09-09 02:07:46.152  4175  4195 I bt_hci  : sco_config_callback postload finished.
09-09 02:07:46.154  4175  4191 D bt_bte_conf: Device ID record 1 : primary,
09-09 02:07:46.154  4175  4191 D bt_bte_conf:   vendorId            = 000f
,09-09 02:07:46.154  4175  4191 D bt_bte_conf:   vendorIdSource      = 0001
09-09 02:07:46.154  4175  4191 D bt_bte_conf:   product             = 1200
,09-09 02:07:46.155  4175  4191 D bt_bte_conf:   version             = 1436
09-09 02:07:46.155  4175  4191 D bt_bte_conf:   clientExecutableURL = ,
09-09 02:07:46.155  4175  4191 D bt_bte_conf:   serviceDescription  = 
,09-09 02:07:46.155  4175  4191 D bt_bte_conf:   documentationURL    = 
,09-09 02:07:46.156  4175  4191 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-09 02:07:46.156  4175  4188 D bt_stack_manager: event_start_up_stack finished
09-09 02:07:46.156  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:46.158  4175  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 02:07:46.159  4175  4187 D BluetoothAdapterProperties: Setting state to 15
09-09 02:07:46.159  4175  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-09 02:07:46.162  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:46.163  4175  4195 I bt_vendor: low_power_mode_cb
09-09 02:07:46.164  4175  4187 I BluetoothAdapterState: Entering BleOnState
09-09 02:07:46.169  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:46.169  4175  4187 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 02:07:46.169  4175  4187 D BluetoothAdapterProperties: Setting state to 11
,09-09 02:07:46.170  4175  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 02:07:46.174  4175  4175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
09-09 02:07:46.175  4175  4175 D HeadsetService: Received start request. Starting profile...
09-09 02:07:46.178  4175  4175 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 02:07:46.180  4175  4175 D HeadsetStateMachine: make
09-09 02:07:46.181  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:46.185  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:46.186  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:46.187  4175  4187 I BluetoothAdapterState: Entering PendingCommandState
,09-09 02:07:46.197  4175  4175 D HeadsetStateMachine: max_hf_connections = 1
,09-09 02:07:46.197  4175  4175 I bt_bluedroid: get_profile_interface handsfree
,09-09 02:07:46.197  4175  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 02:07:46.197  4175  4191 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-09 02:07:46.201  4175  4175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
,09-09 02:07:46.202  4175  4175 D A2dpService: Received start request. Starting profile...
,09-09 02:07:46.203  4175  4175 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-09 02:07:46.203  4175  4175 I bt_bluedroid: get_profile_interface avrcp
,09-09 02:07:46.210  4175  4175 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-09 02:07:46.210  4175  4175 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-09 02:07:46.210  4175  4175 D A2dpStateMachine: make
,09-09 02:07:46.211  4175  4175 I bt_bluedroid: get_profile_interface a2dp
,09-09 02:07:46.212  4175  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 02:07:46.213  4175  4175 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 02:07:46.214  4175  4175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
09-09 02:07:46.215  4175  4206 D A2dpStateMachine: Enter Disconnected: -2
09-09 02:07:46.216  4175  4175 D HidService: Received start request. Starting profile...
09-09 02:07:46.216  4175  4175 I bt_bluedroid: get_profile_interface hidhost
09-09 02:07:46.216  4175  4175 D HidService: setHidService(): set to: null
09-09 02:07:46.216  4175  4191 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39423e5
,09-09 02:07:46.217  3922  3922 D BluetoothInputDevice: Proxy object connected
09-09 02:07:46.217  4175  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-09 02:07:46.217  4175  4175 I BluetoothHealthServiceJni: classInitNative: succeeds
09-09 02:07:46.217  3922  3922 D HidProfile: Bluetooth service connected
09-09 02:07:46.217  4175  4175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
09-09 02:07:46.218  4175  4175 D HealthService: Received start request. Starting profile...
,09-09 02:07:46.219  4175  4175 I bt_bluedroid: get_profile_interface health
,09-09 02:07:46.220  4175  4175 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-09 02:07:46.221  4175  4175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
09-09 02:07:46.222  3922  3922 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 02:07:46.222  4175  4175 D PanService: Received start request. Starting profile...
,09-09 02:07:46.222  4175  4175 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-09 02:07:46.222  3922  3922 D PanProfile: Bluetooth service connected
09-09 02:07:46.222  4175  4175 I bt_bluedroid: get_profile_interface pan
,09-09 02:07:46.223  4175  4191 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 02:07:46.224  4175  4175 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
,09-09 02:07:46.226  4175  4175 D BluetoothMapService: Received start request. Starting profile...
09-09 02:07:46.226  4175  4175 D BluetoothMapService: start()
09-09 02:07:46.226  3922  3922 D BluetoothMap: Proxy object connected
09-09 02:07:46.226  3922  3922 D MapProfile: Bluetooth service connected
,09-09 02:07:46.226  3922  3922 D BluetoothMap: getConnectedDevices()
09-09 02:07:46.227  3922  3922 D BluetoothMap: Bluetooth is Not enabled
,09-09 02:07:46.228  4175  4175 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-09 02:07:46.229  4175  4175 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 02:07:46.229  4175  4175 D BluetoothMapAppObserver: createReceiver()
,09-09 02:07:46.230  4175  4175 D BluetoothMapAppObserver: initObservers()
09-09 02:07:46.230  4175  4175 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 02:07:46.237  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 02:07:46.239  4175  4175 V BluetoothAdapterState: isTurningOff()=false
09-09 02:07:46.239  4175  4175 V BluetoothAdapterState: isTurningOn()=true
,09-09 02:07:46.239  4175  4204 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-09 02:07:46.239  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:46.239  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 02:07:46.240  4175  4175 V BluetoothAdapterState: isTurningOff()=false
09-09 02:07:46.240  4175  4175 V BluetoothAdapterState: isTurningOn()=true
,09-09 02:07:46.240  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:46.240  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:46.240  4175  4175 V BluetoothAdapterState: isTurningOff()=false
09-09 02:07:46.240  4175  4175 V BluetoothAdapterState: isTurningOn()=true
09-09 02:07:46.241  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:46.241  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:46.241  4175  4175 V BluetoothAdapterState: isTurningOff()=false
09-09 02:07:46.241  4175  4175 V BluetoothAdapterState: isTurningOn()=true
,09-09 02:07:46.241  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:46.241  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:46.241  4175  4175 V BluetoothAdapterState: isTurningOff()=false
09-09 02:07:46.241  4175  4175 V BluetoothAdapterState: isTurningOn()=true
09-09 02:07:46.241  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:46.241  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:46.242  4175  4175 V BluetoothAdapterState: isTurningOff()=false
,09-09 02:07:46.242  4175  4175 V BluetoothAdapterState: isTurningOn()=true
09-09 02:07:46.242  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:46.242  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:46.242  4175  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-09 02:07:46.242  4175  4187 D BluetoothAdapterProperties: ScanMode =  20
,09-09 02:07:46.242  4175  4187 D BluetoothAdapterProperties: State =  11
09-09 02:07:46.242  4175  4187 D BluetoothAdapterProperties: Setting state to 12
09-09 02:07:46.242  4175  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-09 02:07:46.243  4175  4187 I BluetoothAdapterState: Entering OnState
,09-09 02:07:46.243  1366  1386 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 02:07:46.244  4175  4191 D BluetoothAdapterProperties: Scan Mode:21
09-09 02:07:46.244  4175  4191 D BluetoothAdapterProperties: Discoverable Timeout:120
09-09 02:07:46.248  1366  2295 D BluetoothMap: onBluetoothStateChange: up=true
09-09 02:07:46.249  1366  1366 D BluetoothA2dp: Proxy object connected
09-09 02:07:46.250  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:46.250  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:46.250  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:46.250  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:46.250  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:07:46.250  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:46.250  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:46.250  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:46.251  1366  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 02:07:46.251  1366  1366 D BluetoothMap: Proxy object connected
09-09 02:07:46.251  1366  1366 D MapProfile: Bluetooth service connected
09-09 02:07:46.251  1366  1366 D BluetoothMap: getConnectedDevices()
,09-09 02:07:46.253  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:46.255  4175  4175 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 02:07:46.256  1366  1366 D BluetoothInputDevice: Proxy object connected
09-09 02:07:46.256  1366  1366 D HidProfile: Bluetooth service connected
09-09 02:07:46.256  4175  4175 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-09 02:07:46.259  3922  3934 D BluetoothMap: onBluetoothStateChange: up=true
,09-09 02:07:46.259  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:46.259  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:46.259  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:46.259  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:46.259  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:07:46.259  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:46.259  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:46.259  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:46.259  4175  4175 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 02:07:46.259  1366  1378 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 02:07:46.261  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:07:46.262  4175  4175 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 02:07:46.264  4175  4175 D ObexServerSockets: Succeed to create listening sockets 
,09-09 02:07:46.264  4175  4175 D ObexServerSockets0: startAccept()
,09-09 02:07:46.265  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:46.265  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:46.265  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:46.265  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:46.265  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:07:46.265  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:46.265  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:46.265  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:07:46.265  1366  2295 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 02:07:46.265  4175  4175 D ObexServerSockets0: prepareForNewConnect()
09-09 02:07:46.265  3922  3932 D BluetoothPan: onBluetoothStateChange on: true
,09-09 02:07:46.265   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 02:07:46.266   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 02:07:46.266   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 02:07:46.266   874   874 D BluetoothA2dp: Proxy object connected
,09-09 02:07:46.266  1932  2233 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 02:07:46.266  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:07:46.267   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 02:07:46.267  3922  3934 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 02:07:46.267  1366  2050 D BluetoothPan: onBluetoothStateChange on: true
09-09 02:07:46.268  4175  4175 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-09 02:07:46.268  4175  4175 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 02:07:46.269  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 02:07:46.269  1366  1366 D PanProfile: Bluetooth service connected
09-09 02:07:46.269  3922  3932 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 02:07:46.270  4175  4213 D ObexServerSockets0: Accepting socket connection...
,09-09 02:07:46.270  4175  4212 D ObexServerSockets0: Accepting socket connection...
09-09 02:07:46.272  4175  4175 D BluetoothMapService: onReceive
09-09 02:07:46.272  4175  4175 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 02:07:46.273  4175  4175 D BluetoothMapService: STATE_ON
09-09 02:07:46.273   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,09-09 02:07:46.274  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:46.275  3922  3922 D LocalBluetoothProfileManager: Adding local A2DP profile
09-09 02:07:46.276  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:46.277  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:46.278  3922  3922 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-09 02:07:46.283  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 02:07:46.285  3922  3922 D BluetoothA2dp: Proxy object connected
,09-09 02:07:46.289  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 02:07:46.295  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,09-09 02:07:46.296  3922  3922 D BluetoothPbap: Proxy object connected
,09-09 02:07:46.297  3922  3922 D PbapServerProfile: Bluetooth service connected
,09-09 02:07:46.299  1366  1366 D BluetoothPbap: Proxy object connected
,09-09 02:07:46.299  1366  1366 D PbapServerProfile: Bluetooth service connected
,09-09 02:07:46.301  4175  4175 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 02:07:46.301  4175  4175 D ObexServerSockets0: prepareForNewConnect()
,09-09 02:07:46.303  4175  4218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 02:07:46.317  4175  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 02:07:46.318  4175  4222 I BtOppRfcommListener: Accept thread started.
,09-09 02:07:46.366   874   874 D BluetoothHeadset: Proxy object connected
,09-09 02:07:46.366   874   874 D BluetoothHeadset: Proxy object connected
,09-09 02:07:46.367  1932  2085 D BluetoothHeadset: Proxy object connected
09-09 02:07:46.367   874   891 D BluetoothHeadset: Proxy object connected
09-09 02:07:46.367  1366  1386 D BluetoothHeadset: Proxy object connected
,09-09 02:07:46.367  1366  1366 D HeadsetProfile: Bluetooth service connected
09-09 02:07:46.368   874   874 D BluetoothHeadset: Proxy object connected
,09-09 02:07:46.368  1932  1946 D BluetoothHeadset: Proxy object connected
,09-09 02:07:46.381  3922  3934 D BluetoothHeadset: Proxy object connected
,09-09 02:07:46.381  3922  3922 D HeadsetProfile: Bluetooth service connected
,09-09 02:07:47.903  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:47.917  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:47.923  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:07:47.993  1523  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-09 02:07:47.994  1523  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-09 02:07:47.994  1523  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:07:47.994  1523  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:07:48.046  3527  3527 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-09 02:07:48.047  3527  3527 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-09 02:07:48.048  3527  3527 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-09 02:07:49.689  4175  4187 D BluetoothAdapterState: Current state: ON, message: 23
,09-09 02:07:49.689  4175  4187 D BluetoothAdapterProperties: Setting state to 13
,09-09 02:07:49.690  4175  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-09 02:07:49.692  4175  4187 D BluetoothAdapterProperties: onBluetoothDisable()
,09-09 02:07:49.695  4175  4187 I BluetoothAdapterState: Entering PendingCommandState
,09-09 02:07:49.704  4175  4175 D BluetoothMapService: onReceive
,09-09 02:07:49.705  4175  4175 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-09 02:07:49.705  4175  4175 D BluetoothMapService: STATE_TURNING_OFF
09-09 02:07:49.706  4175  4175 D BluetoothMapService: MAP Service closeService in
,09-09 02:07:49.706  4175  4175 D BluetoothMapMasInstance0: MAP Service shutdown
09-09 02:07:49.707  4175  4175 D ObexServerSockets0: shutdown(block = true)
,09-09 02:07:49.707  4175  4212 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-09 02:07:49.711  4175  4175 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-09 02:07:49.712  4175  4213 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-09 02:07:49.713  4175  4191 D BluetoothAdapterProperties: Scan Mode:20
,09-09 02:07:49.714  4175  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-09 02:07:49.714  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:49.714  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-09 02:07:49.714  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:49.714  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:49.714  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:49.714  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:49.714  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:49.714  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:49.714  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:49.717  4175  4199 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-09 02:07:49.718  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:49.718  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:07:49.721  4175  4175 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-09 02:07:49.721  4175  4175 I BtOppRfcommListener: stopping Accept Thread
,09-09 02:07:49.722  4175  4222 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-09 02:07:49.723  4175  4222 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-09 02:07:49.723  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:49.724  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:07:49.724  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:49.724  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:49.724  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:49.724  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:49.724  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:49.724  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:49.724  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:49.725  4175  4175 D HeadsetService: Received stop request...Stopping profile...
,09-09 02:07:49.726  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-09 02:07:49.726  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:49.726  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:07:49.728   874   874 D BluetoothHeadset: Proxy object disconnected
09-09 02:07:49.728   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 02:07:49.728  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-09 02:07:49.729  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-09 02:07:49.729  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:07:49.729  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:07:49.729  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:07:49.729  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-09 02:07:49.729  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:07:49.729  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:07:49.729  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-09 02:07:49.729  1366  1386 D BluetoothHeadset: Proxy object disconnected
,09-09 02:07:49.729  3820  3820 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-09 02:07:49.729  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:07:49.730  4175  4175 D A2dpService: Received stop request...Stopping profile...
,09-09 02:07:49.730  3922  3932 D BluetoothHeadset: Proxy object disconnected
09-09 02:07:49.731   874   874 D BluetoothHeadset: Proxy object disconnected
,09-09 02:07:49.731  4175  4206 D A2dpStateMachine: Exit Disconnected: -1
09-09 02:07:49.731  1932  1946 D BluetoothHeadset: Proxy object disconnected
,09-09 02:07:49.731  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:49.733  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:49.733   874   874 D BluetoothA2dp: Proxy object disconnected
09-09 02:07:49.734  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:49.735  4175  4175 D HidService: Received stop request...Stopping profile...
09-09 02:07:49.735  4175  4175 D HidService: Stopping Bluetooth HidService
,09-09 02:07:49.737  4175  4175 D HealthService: Received stop request...Stopping profile...
,09-09 02:07:49.737  1366  1366 D HeadsetProfile: Bluetooth service disconnected
09-09 02:07:49.738  1366  1366 D BluetoothA2dp: Proxy object disconnected
,09-09 02:07:49.738  1366  1366 D BluetoothInputDevice: Proxy object disconnected
09-09 02:07:49.738  1366  1366 D HidProfile: Bluetooth service disconnected
09-09 02:07:49.739  4175  4175 D PanService: Received stop request...Stopping profile...
09-09 02:07:49.739  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-09 02:07:49.740  1366  1366 D PanProfile: Bluetooth service disconnected
,09-09 02:07:49.740  4175  4175 V BluetoothAdapterState: isTurningOff()=true
09-09 02:07:49.740  4175  4175 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:49.740  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:49.740  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 02:07:49.740  3922  3922 D DockEventReceiver: finishStartingService: stopping service
09-09 02:07:49.741  3922  3922 D HeadsetProfile: Bluetooth service disconnected
09-09 02:07:49.742  4175  4175 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-09 02:07:49.742  4175  4175 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-09 02:07:49.742  4175  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-09 02:07:49.742  3922  3922 D BluetoothA2dp: Proxy object disconnected
09-09 02:07:49.742  4175  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 02:07:49.742  4175  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 02:07:49.742  4175  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 02:07:49.742  4175  4191 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-09 02:07:49.742  3922  3922 D BluetoothInputDevice: Proxy object disconnected
09-09 02:07:49.742  3922  3922 D HidProfile: Bluetooth service disconnected
09-09 02:07:49.743  3922  3922 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-09 02:07:49.743  3922  3922 D PanProfile: Bluetooth service disconnected
09-09 02:07:49.746  4175  4175 D BluetoothMapService: Received stop request...Stopping profile...
09-09 02:07:49.746  4175  4175 D BluetoothMapService: stop()
09-09 02:07:49.748  4175  4175 D BluetoothMapAppObserver: deinitObservers()
09-09 02:07:49.748  4175  4175 D BluetoothMapAppObserver: removeReceiver()
09-09 02:07:49.750  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
09-09 02:07:49.752  1366  1366 D BluetoothMap: Proxy object disconnected
09-09 02:07:49.752  1366  1366 D MapProfile: Bluetooth service disconnected
09-09 02:07:49.752  4175  4175 V BluetoothAdapterState: isTurningOff()=true
09-09 02:07:49.753  3922  3922 D BluetoothMap: Proxy object disconnected
09-09 02:07:49.753  3922  3922 D MapProfile: Bluetooth service disconnected
,09-09 02:07:49.753  4175  4175 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:49.754  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:49.754  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:49.755  4175  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 02:07:49.755  4175  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-09 02:07:49.755  4175  4197 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 02:07:49.755  4175  4197 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-09 02:07:49.756  4175  4197 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-09 02:07:49.756  4175  4197 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-09 02:07:49.756  4175  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-09 02:07:49.756  4175  4175 V BluetoothAdapterState: isTurningOff()=true
,09-09 02:07:49.756  4175  4175 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:49.756  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:49.756  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:49.756  4175  4175 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-09 02:07:49.756  4175  4175 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-09 02:07:49.757  4175  4191 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-09 02:07:49.757  4175  4175 V BluetoothAdapterState: isTurningOff()=true
,09-09 02:07:49.757  4175  4175 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:49.757  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:49.757  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:07:49.757  4175  4175 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-09 02:07:49.757  4175  4191 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-09 02:07:49.758  4175  4175 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-09 02:07:49.758  4175  4175 V BluetoothAdapterState: isTurningOff()=true
09-09 02:07:49.758  4175  4175 V BluetoothAdapterState: isTurningOn()=false
,09-09 02:07:49.758  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 02:07:49.758  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 02:07:49.759  4175  4175 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-09 02:07:49.759  4175  4175 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-09 02:07:49.761  1366  1366 D BluetoothPbap: Proxy object disconnected
09-09 02:07:49.761  1366  1366 D PbapServerProfile: Bluetooth service disconnected
09-09 02:07:49.761  3922  3922 D BluetoothPbap: Proxy object disconnected
09-09 02:07:49.761  3922  3922 D PbapServerProfile: Bluetooth service disconnected
09-09 02:07:49.762  4175  4175 D BluetoothMapService: MAP Service closeService in
09-09 02:07:49.762  4175  4175 V BluetoothAdapterState: isTurningOff()=true
09-09 02:07:49.762  4175  4175 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:49.762  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:07:49.762  4175  4175 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 02:07:49.762  4175  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-09 02:07:49.762  4175  4187 D BluetoothAdapterProperties: Setting state to 15
09-09 02:07:49.762  4175  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-09 02:07:49.763  1366  2050 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 02:07:49.764  4175  4187 I BluetoothAdapterState: Entering BleOnState
09-09 02:07:49.764  1366  1386 D BluetoothMap: onBluetoothStateChange: up=false
09-09 02:07:49.764  4175  4175 D BluetoothMapService: cleanup()
09-09 02:07:49.765  4175  4175 D BluetoothMapService: MAP Service closeService in
,09-09 02:07:49.764  1366  1378 D BluetoothInputDevice: onBluetoothStateChange: up=false,
09-09 02:07:49.765  3922  3934 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 02:07:49.767  3922  3932 D BluetoothMap: onBluetoothStateChange: up=false
09-09 02:07:49.768  1366  2295 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 02:07:49.769  1366  2050 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 02:07:49.769  3922  3934 D BluetoothPan: onBluetoothStateChange on: false
09-09 02:07:49.769   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 02:07:49.769   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 02:07:49.769   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-09 02:07:49.770  1932  2232 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 02:07:49.770   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-09 02:07:49.771  3922  3932 D BluetoothHeadset: onBluetoothStateChange: up=false
09-09 02:07:49.771  3922  3934 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-09 02:07:49.772  1366  1386 D BluetoothPan: onBluetoothStateChange on: false
09-09 02:07:49.772  3922  3932 D BluetoothPbap: onBluetoothStateChange: up=false
,09-09 02:07:49.773  4175  4187 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-09 02:07:49.773  4175  4187 D BluetoothAdapterProperties: Setting state to 16
09-09 02:07:49.773  4175  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-09 02:07:49.773  4175  4187 D BluetoothAdapterProperties: onBleDisable
,09-09 02:07:49.774  4175  4187 I BluetoothAdapterState: Entering PendingCommandState
09-09 02:07:49.775  4175  4188 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-09 02:07:49.776  4175  4191 D BluetoothAdapterProperties: Scan Mode:20
09-09 02:07:49.776  4175  4197 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-09 02:07:49.776  4175  4197 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-09 02:07:49.776  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:49.778  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:49.780  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:49.781  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:49.781  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 02:07:49.782  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:49.783  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:07:49.785  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 02:07:49.793  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,09-09 02:07:49.979  4175  4191 I bt_hci  : shut_down
,09-09 02:07:49.979  4175  4195 D bt_hwcfg: hw_epilog_process
,09-09 02:07:49.991  4175  4195 I bt_vendor: low_power_mode_cb
,09-09 02:07:50.011  4175  4195 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-09 02:07:50.012  4175  4195 I bt_vendor: epilog_cb
,09-09 02:07:50.012  4175  4195 I bt_hci  : epilog_finished_callback
,09-09 02:07:50.020  4175  4191 I bt_hci_h4: hal_close
,09-09 02:07:50.022  4175  4191 I bt_userial_vendor: device fd = 51 close
,09-09 02:07:50.147  4175  4188 D bt_stack_manager: event_shut_down_stack finished.
,09-09 02:07:50.148  4175  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-09 02:07:50.154  4175  4187 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-09 02:07:50.154  4175  4175 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 02:07:50.155  4175  4175 D BtGatt.GattService: Received stop request...Stopping profile...
09-09 02:07:50.156  4175  4175 D BtGatt.GattService: stop()
09-09 02:07:50.156  4175  4175 D BtGatt.AdvertiseManager: advertise clients cleared
,09-09 02:07:50.161  4175  4175 V BluetoothAdapterState: isTurningOff()=false
,09-09 02:07:50.162  4175  4175 V BluetoothAdapterState: isTurningOn()=false
09-09 02:07:50.162  4175  4175 V BluetoothAdapterState: isBleTurningOn()=false
,09-09 02:07:50.162  4175  4175 V BluetoothAdapterState: isBleTurningOff()=true
09-09 02:07:50.163  4175  4187 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-09 02:07:50.164  4175  4187 D BluetoothAdapterProperties: Setting state to 10
,09-09 02:07:50.164  4175  4187 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-09 02:07:50.166  4175  4187 I BluetoothAdapterState: Entering OffState
,09-09 02:07:50.167   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-09 02:07:50.187  4175  4175 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-09 02:07:50.187  4175  4175 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-09 02:07:50.187  4175  4188 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-09 02:07:50.190  4175  4188 D bt_stack_manager: event_clean_up_stack finished.
09-09 02:07:50.190  4175  4175 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-09 02:07:50.201  4175  4175 I art     : System.exit called, status: 0
,09-09 02:07:50.201  4175  4175 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-09 02:07:50.262   874  1965 I ActivityManager: Process com.android.bluetooth (pid 4175) has died
,09-09 02:07:54.686  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:54.686  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:54.692  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:07:54.692  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@59fe59 removed from the list
,09-09 02:07:54.692  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:54.693  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:54.693  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:54.699  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 02:07:54.699  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@218f2ff added. We now have 4 listener(s)
,09-09 02:07:54.700  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 02:07:54.702  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:07:54.702  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@218f2ff removed from the list
,09-09 02:07:54.702  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:07:54.703  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:07:54.703  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:07:54.705  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 02:07:54.706  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee358cc added. We now have 4 listener(s)
,09-09 02:07:54.706  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 02:07:59.716  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:07:59.764   874   891 I ActivityManager: Start proc 4233:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-09 02:07:59.901  4233  4233 D AdapterServiceConfig: Adding HeadsetService
,09-09 02:07:59.901  4233  4233 D AdapterServiceConfig: Adding A2dpService
09-09 02:07:59.901  4233  4233 D AdapterServiceConfig: Adding HidService
09-09 02:07:59.902  4233  4233 D AdapterServiceConfig: Adding HealthService
09-09 02:07:59.902  4233  4233 D AdapterServiceConfig: Adding PanService
09-09 02:07:59.902  4233  4233 D AdapterServiceConfig: Adding GattService
09-09 02:07:59.902  4233  4233 D AdapterServiceConfig: Adding BluetoothMapService
,09-09 02:07:59.916   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5fa0fd6:true
,09-09 02:07:59.916  4233  4233 D BluetoothAdapterState: make() - Creating AdapterState
,09-09 02:07:59.922  4233  4233 I bt_bluedroid: init
,09-09 02:07:59.923  4233  4245 I BluetoothAdapterState: Entering OffState
,09-09 02:07:59.928  4233  4246 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-09 02:07:59.929  4233  4246 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-09 02:07:59.929  4233  4246 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-09 02:07:59.929  4233  4246 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-09 02:07:59.930  4233  4233 I bt_bluedroid: get_profile_interface socket
,09-09 02:07:59.932  4233  4233 I bt_bluedroid: get_profile_interface sdp
,09-09 02:07:59.937  4233  4244 I bt_bluedroid: config_hci_snoop_log
,09-09 02:07:59.937  4233  4249 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 02:07:59.939   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-09 02:07:59.939  4233  4249 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 02:07:59.953  4233  4245 D BluetoothAdapterState: Current state: OFF, message: 0
,09-09 02:07:59.954  4233  4245 D BluetoothAdapterProperties: Setting state to 14
09-09 02:07:59.954  4233  4245 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-09 02:07:59.959  4233  4245 D BluetoothBondStateMachine: make
,09-09 02:07:59.965  4233  4250 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-09 02:07:59.974  4233  4245 I BluetoothAdapterState: Entering PendingCommandState
,09-09 02:07:59.976  4233  4233 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-09 02:07:59.982  4233  4233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
,09-09 02:07:59.983  4233  4233 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-09 02:07:59.985  4233  4233 D BtGatt.GattService: Received start request. Starting profile...
09-09 02:07:59.985  4233  4233 D BtGatt.GattService: start()
09-09 02:07:59.985  4233  4233 I bt_bluedroid: get_profile_interface gatt
09-09 02:07:59.987  4233  4233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
09-09 02:07:59.987  4233  4233 D BtGatt.AdvertiseManager: advertise manager created
,09-09 02:08:00.002  4233  4233 V BluetoothAdapterState: isTurningOff()=false
,09-09 02:08:00.002  4233  4233 V BluetoothAdapterState: isTurningOn()=false
,09-09 02:08:00.002  4233  4233 V BluetoothAdapterState: isBleTurningOn()=true
,09-09 02:08:00.003  4233  4233 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:08:00.003  4233  4245 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-09 02:08:00.004  4233  4245 I bt_bluedroid: enable
,09-09 02:08:00.004  4233  4246 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-09 02:08:00.005  4233  4246 I bt_hci  : start_up
,09-09 02:08:00.026  4233  4246 I bt_vendor: alloc value 0xb39e3189
09-09 02:08:00.026  4233  4246 I bt_vendor: init
09-09 02:08:00.026  4233  4246 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-09 02:08:00.026  4233  4246 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-09 02:08:00.134  4233  4246 D bt_hci  : start_up starting async portion
,09-09 02:08:00.135  4233  4253 I bt_hci  : event_finish_startup
09-09 02:08:00.135  4233  4253 I bt_hci_h4: hal_open
09-09 02:08:00.135  4233  4253 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-09 02:08:00.145  4233  4253 I bt_userial_vendor: device fd = 51 open
,09-09 02:08:00.177  4233  4253 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 02:08:00.208  4233  4253 D bt_hwcfg: Chipset BCM4354A2
,09-09 02:08:00.208  4233  4253 D bt_hwcfg: Target name = [BCM4354A2]
,09-09 02:08:00.209  4233  4253 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-09 02:08:01.058  4233  4253 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-09 02:08:01.060  4233  4253 D bt_hwcfg: Settlement delay -- 100 ms
09-09 02:08:01.060  4233  4253 I bt_hwcfg: Setting fw settlement delay to 100 
,09-09 02:08:01.178  4233  4253 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-09 02:08:01.180  4233  4253 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-09 02:08:01.208  4233  4253 I bt_hwcfg: vendor lib fwcfg completed
09-09 02:08:01.208  4233  4253 I bt_vendor: firmware callback
09-09 02:08:01.208  4233  4253 I bt_hci  : firmware_config_callback
,09-09 02:08:01.221  4233  4255 I bt_btu  : btu_task pending for preload complete event
,09-09 02:08:01.222  4233  4255 I bt_btu_task: Bluetooth chip preload is complete
,09-09 02:08:01.222  4233  4255 I bt_btu  : btu_task received preload complete event
,09-09 02:08:01.232  4233  4255 I         : BTE_InitTraceLevels -- TRC_HCI
09-09 02:08:01.232  4233  4255 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-09 02:08:01.233  4233  4255 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-09 02:08:01.233  4233  4255 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-09 02:08:01.233  4233  4255 I         : BTE_InitTraceLevels -- TRC_AVRC
09-09 02:08:01.233  4233  4255 I         : BTE_InitTraceLevels -- TRC_A2D
09-09 02:08:01.234  4233  4255 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-09 02:08:01.234  4233  4255 I         : BTE_InitTraceLevels -- TRC_BTM
09-09 02:08:01.234  4233  4255 I         : BTE_InitTraceLevels -- TRC_GAP
,09-09 02:08:01.235  4233  4255 I         : BTE_InitTraceLevels -- TRC_PAN
09-09 02:08:01.235  4233  4255 I         : BTE_InitTraceLevels -- TRC_SDP
09-09 02:08:01.235  4233  4255 I         : BTE_InitTraceLevels -- TRC_GATT
09-09 02:08:01.235  4233  4255 I         : BTE_InitTraceLevels -- TRC_SMP
09-09 02:08:01.235  4233  4255 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-09 02:08:01.236  4233  4255 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-09 02:08:01.389  4233  4255 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3960d9d
,09-09 02:08:01.389  4233  4255 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3960d9d 
,09-09 02:08:01.400  4233  4249 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-09 02:08:01.402  4233  4249 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-09 02:08:01.403  4233  4249 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-09 02:08:01.406  4233  4249 D BluetoothAdapterProperties: Name is: Nexus 6
,09-09 02:08:01.411  4233  4249 D BluetoothAdapterProperties: Scan Mode:20
,09-09 02:08:01.412  4233  4249 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 02:08:01.412  4233  4249 D bt_hci  : do_postload posting postload work item
,09-09 02:08:01.413  4233  4253 I bt_hci  : event_postload
,09-09 02:08:01.413  4233  4253 I bt_vendor: sco_config_cb
,09-09 02:08:01.413  4233  4253 I bt_hci  : sco_config_callback postload finished.
,09-09 02:08:01.418  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:01.420  4233  4249 D bt_bte_conf: Device ID record 1 : primary
,09-09 02:08:01.420  4233  4249 D bt_bte_conf:   vendorId            = 000f
09-09 02:08:01.420  4233  4249 D bt_bte_conf:   vendorIdSource      = 0001
,09-09 02:08:01.421  4233  4249 D bt_bte_conf:   product             = 1200
,09-09 02:08:01.421  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:01.422  4233  4249 D bt_bte_conf:   version             = 1436
,09-09 02:08:01.422  4233  4249 D bt_bte_conf:   clientExecutableURL = 
,09-09 02:08:01.422  4233  4249 D bt_bte_conf:   serviceDescription  = 
,09-09 02:08:01.423  4233  4249 D bt_bte_conf:   documentationURL    = 
,09-09 02:08:01.423  4233  4253 I bt_vendor: low_power_mode_cb
09-09 02:08:01.423  4233  4249 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-09 02:08:01.425  4233  4246 D bt_stack_manager: event_start_up_stack finished
09-09 02:08:01.426  4233  4245 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-09 02:08:01.426  4233  4245 D BluetoothAdapterProperties: Setting state to 15
,09-09 02:08:01.426  4233  4245 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-09 02:08:01.427  4233  4245 I BluetoothAdapterState: Entering BleOnState
,09-09 02:08:01.430  4233  4245 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-09 02:08:01.430  4233  4245 D BluetoothAdapterProperties: Setting state to 11
,09-09 02:08:01.430  4233  4245 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-09 02:08:01.439  4233  4233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
09-09 02:08:01.446  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:08:01.448  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:01.449  4233  4233 D HeadsetService: Received start request. Starting profile...
,09-09 02:08:01.456  4233  4245 I BluetoothAdapterState: Entering PendingCommandState
,09-09 02:08:01.456  4233  4233 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-09 02:08:01.456  4233  4233 D HeadsetStateMachine: make
,09-09 02:08:01.466  4233  4233 D HeadsetStateMachine: max_hf_connections = 1
,09-09 02:08:01.466  4233  4233 I bt_bluedroid: get_profile_interface handsfree
,09-09 02:08:01.467  4233  4249 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-09 02:08:01.467  4233  4249 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-09 02:08:01.472  4233  4233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
,09-09 02:08:01.473  4233  4233 D A2dpService: Received start request. Starting profile...
,09-09 02:08:01.475  4233  4233 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-09 02:08:01.476  4233  4233 I bt_bluedroid: get_profile_interface avrcp
,09-09 02:08:01.491  4233  4233 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-09 02:08:01.491  4233  4233 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-09 02:08:01.492  4233  4233 D A2dpStateMachine: make
,09-09 02:08:01.494  4233  4233 I bt_bluedroid: get_profile_interface a2dp
,09-09 02:08:01.495  4233  4249 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-09 02:08:01.500  4233  4264 D A2dpStateMachine: Enter Disconnected: -2
,09-09 02:08:01.502  4233  4233 I BluetoothHidServiceJni: classInitNative: succeeds
,09-09 02:08:01.505  4233  4233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
,09-09 02:08:01.505  4233  4233 D HidService: Received start request. Starting profile...
09-09 02:08:01.506  4233  4233 I bt_bluedroid: get_profile_interface hidhost
09-09 02:08:01.506  4233  4249 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39423e5
09-09 02:08:01.506  4233  4249 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-09 02:08:01.506  4233  4233 D HidService: setHidService(): set to: null
09-09 02:08:01.506  4233  4233 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-09 02:08:01.507  4233  4233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
09-09 02:08:01.508  4233  4233 D HealthService: Received start request. Starting profile...
,09-09 02:08:01.509  4233  4233 I bt_bluedroid: get_profile_interface health
,09-09 02:08:01.511  4233  4233 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-09 02:08:01.512  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 02:08:01.512  4233  4233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
09-09 02:08:01.513  4233  4233 D PanService: Received start request. Starting profile...
,09-09 02:08:01.513  4233  4233 D BluetoothPanServiceJni: initializeNative(L110): pan
09-09 02:08:01.513  4233  4233 I bt_bluedroid: get_profile_interface pan
09-09 02:08:01.513  4233  4249 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-09 02:08:01.516  4233  4233 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
,09-09 02:08:01.516  4233  4233 D BluetoothMapService: Received start request. Starting profile...
09-09 02:08:01.516  4233  4233 D BluetoothMapService: start()
,09-09 02:08:01.519  4233  4233 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-09 02:08:01.519  4233  4233 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-09 02:08:01.519  4233  4233 D BluetoothMapAppObserver: createReceiver()
,09-09 02:08:01.521  4233  4233 D BluetoothMapAppObserver: initObservers()
09-09 02:08:01.521  4233  4233 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-09 02:08:01.528  4233  4262 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-09 02:08:01.529  4233  4233 V BluetoothAdapterState: isTurningOff()=false
09-09 02:08:01.529  4233  4233 V BluetoothAdapterState: isTurningOn()=true
09-09 02:08:01.529  4233  4233 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:08:01.529  4233  4233 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 02:08:01.530  4233  4233 V BluetoothAdapterState: isTurningOff()=false
,09-09 02:08:01.530  4233  4233 V BluetoothAdapterState: isTurningOn()=true
09-09 02:08:01.530  4233  4233 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:08:01.530  4233  4233 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 02:08:01.531  4233  4233 V BluetoothAdapterState: isTurningOff()=false
09-09 02:08:01.531  4233  4233 V BluetoothAdapterState: isTurningOn()=true
09-09 02:08:01.531  4233  4233 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:08:01.531  4233  4233 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:08:01.531  4233  4233 V BluetoothAdapterState: isTurningOff()=false
,09-09 02:08:01.531  4233  4233 V BluetoothAdapterState: isTurningOn()=true
09-09 02:08:01.531  4233  4233 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:08:01.531  4233  4233 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:08:01.533  4233  4233 V BluetoothAdapterState: isTurningOff()=false
09-09 02:08:01.533  4233  4233 V BluetoothAdapterState: isTurningOn()=true
09-09 02:08:01.533  4233  4233 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:08:01.533  4233  4233 V BluetoothAdapterState: isBleTurningOff()=false
09-09 02:08:01.533  4233  4233 V BluetoothAdapterState: isTurningOff()=false
,09-09 02:08:01.533  4233  4233 V BluetoothAdapterState: isTurningOn()=true
09-09 02:08:01.533  4233  4233 V BluetoothAdapterState: isBleTurningOn()=false
09-09 02:08:01.533  4233  4233 V BluetoothAdapterState: isBleTurningOff()=false
,09-09 02:08:01.534  4233  4245 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-09 02:08:01.534  4233  4245 D BluetoothAdapterProperties: ScanMode =  20
09-09 02:08:01.534  4233  4245 D BluetoothAdapterProperties: State =  11
,09-09 02:08:01.534  4233  4245 D BluetoothAdapterProperties: Setting state to 12
09-09 02:08:01.534  4233  4245 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-09 02:08:01.536  1366  1378 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-09 02:08:01.537  4233  4249 D BluetoothAdapterProperties: Scan Mode:21
,09-09 02:08:01.538  4233  4249 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-09 02:08:01.538  4233  4245 I BluetoothAdapterState: Entering OnState
09-09 02:08:01.539  1366  2295 D BluetoothMap: onBluetoothStateChange: up=true
09-09 02:08:01.541  1366  1366 D BluetoothA2dp: Proxy object connected
,09-09 02:08:01.542  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:08:01.542  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:01.542  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:01.542  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:08:01.542  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:01.542  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:08:01.542  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:08:01.542  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:08:01.543  1366  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-09 02:08:01.544  1366  1366 D BluetoothMap: Proxy object connected
,09-09 02:08:01.544  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:08:01.544  1366  1366 D MapProfile: Bluetooth service connected
09-09 02:08:01.544  1366  1366 D BluetoothMap: getConnectedDevices()
,09-09 02:08:01.545  3922  3934 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 02:08:01.547  1366  1366 D BluetoothInputDevice: Proxy object connected
09-09 02:08:01.547  1366  1366 D HidProfile: Bluetooth service connected
09-09 02:08:01.547  4233  4233 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-09 02:08:01.548  3922  3932 D BluetoothMap: onBluetoothStateChange: up=true
09-09 02:08:01.548  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:08:01.548  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:01.548  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:01.548  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:08:01.548  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:01.548  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:08:01.548  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:08:01.548  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:08:01.548  4233  4233 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-09 02:08:01.549  1366  2050 D BluetoothPbap: onBluetoothStateChange: up=true
09-09 02:08:01.550  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-09 02:08:01.550  4233  4233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 02:08:01.548  3922  3922 D BluetoothA2dp: Proxy object connected
09-09 02:08:01.552  1366  1378 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 02:08:01.552  3922  3932 D BluetoothPan: onBluetoothStateChange on: true
09-09 02:08:01.552  4233  4233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 02:08:01.553  4233  4233 D ObexServerSockets: Succeed to create listening sockets 
09-09 02:08:01.553  4233  4233 D ObexServerSockets0: startAccept()
09-09 02:08:01.553  4233  4233 D ObexServerSockets0: prepareForNewConnect()
,09-09 02:08:01.555   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 02:08:01.555   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 02:08:01.555   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-09 02:08:01.555  4233  4233 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-09 02:08:01.555  4233  4233 D BluetoothSdpJni: SDP Create record success - handle: 0
09-09 02:08:01.555   874   874 D BluetoothA2dp: Proxy object connected
09-09 02:08:01.556  1932  2232 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-09 02:08:01.556   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 02:08:01.556  3922  3934 D BluetoothHeadset: onBluetoothStateChange: up=true
09-09 02:08:01.556  4233  4272 D ObexServerSockets0: Accepting socket connection...
09-09 02:08:01.557  4233  4273 D ObexServerSockets0: Accepting socket connection...
09-09 02:08:01.557  3922  4271 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-09 02:08:01.560  1366  1386 D BluetoothPan: onBluetoothStateChange on: true
09-09 02:08:01.560  3922  3922 D BluetoothMap: Proxy object connected
,09-09 02:08:01.560  3922  3922 D MapProfile: Bluetooth service connected
09-09 02:08:01.560  3922  3922 D BluetoothMap: getConnectedDevices()
09-09 02:08:01.562  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 02:08:01.562  1366  1366 D PanProfile: Bluetooth service connected
09-09 02:08:01.562  3922  3932 D BluetoothPbap: onBluetoothStateChange: up=true
,09-09 02:08:01.565  4233  4233 D BluetoothMapService: onReceive
,09-09 02:08:01.565  4233  4233 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-09 02:08:01.565   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-09 02:08:01.565  4233  4233 D BluetoothMapService: STATE_ON
09-09 02:08:01.564  3922  3922 D BluetoothPan: BluetoothPAN Proxy object connected
09-09 02:08:01.566  3922  3922 D PanProfile: Bluetooth service connected
,09-09 02:08:01.566  3922  3922 D BluetoothInputDevice: Proxy object connected
09-09 02:08:01.566  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:08:01.566  3922  3922 D HidProfile: Bluetooth service connected
09-09 02:08:01.567  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:01.571  3922  3922 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-09 02:08:01.577  1523  1523 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-09 02:08:01.581  3922  3922 D DockEventReceiver: finishStartingService: stopping service
,09-09 02:08:01.586  3922  3922 D BluetoothPbap: Proxy object connected
,09-09 02:08:01.586  3922  3922 D PbapServerProfile: Bluetooth service connected
,09-09 02:08:01.591  4233  4233 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-09 02:08:01.591  4233  4233 D ObexServerSockets0: prepareForNewConnect()
,09-09 02:08:01.592  1366  1366 D BluetoothPbap: Proxy object connected
,09-09 02:08:01.592  1366  1366 D PbapServerProfile: Bluetooth service connected
09-09 02:08:01.593  4233  4277 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 02:08:01.613  4233  4281 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-09 02:08:01.614  4233  4281 I BtOppRfcommListener: Accept thread started.
,09-09 02:08:01.654   874   874 D BluetoothHeadset: Proxy object connected
09-09 02:08:01.654   874   874 D BluetoothHeadset: Proxy object connected
09-09 02:08:01.654  1366  1386 D BluetoothHeadset: Proxy object connected
09-09 02:08:01.654   874   891 D BluetoothHeadset: Proxy object connected
09-09 02:08:01.655   874   891 D BluetoothHeadset: Proxy object connected
,09-09 02:08:01.655  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-09 02:08:01.655  3922  3932 D BluetoothHeadset: Proxy object connected
,09-09 02:08:01.657  1932  1945 D BluetoothHeadset: Proxy object connected
09-09 02:08:01.658  3922  3922 D HeadsetProfile: Bluetooth service connected
09-09 02:08:01.659   874   874 D BluetoothHeadset: Proxy object connected
,09-09 02:08:01.659   874   891 D BluetoothHeadset: Proxy object connected
09-09 02:08:01.659  3922  3934 D BluetoothHeadset: Proxy object connected
09-09 02:08:01.660  1932  2233 D BluetoothHeadset: Proxy object connected
,09-09 02:08:01.666  3922  3922 D HeadsetProfile: Bluetooth service connected
,09-09 02:08:04.736  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:08:04.736  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:04.736  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:04.736  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-09 02:08:04.736  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:04.736  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:08:04.736  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:08:04.736  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:08:04.743  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:08:04.744  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:04.745  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ee358cc removed from the list
,09-09 02:08:04.745  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 02:08:04.745  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:08:04.746  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:04.748  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 02:08:04.749  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a32715 added. We now have 4 listener(s)
09-09 02:08:04.749  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 02:08:04.753   874   884 D WifiService: setWifiEnabled: false pid=3820, uid=10000
,09-09 02:08:04.753   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 02:08:09.767  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:09.769   874   885 D WifiService: setWifiEnabled: true pid=3820, uid=10000
09-09 02:08:09.769   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-09 02:08:09.782   874  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-09 02:08:09.800  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:08:09.800  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:09.800  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:09.800  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:08:09.800  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:09.800  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:08:09.800  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:08:09.800  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:08:09.807  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:08:09.813  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:08:09.813  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:09.813  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:09.813  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:08:09.813  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:09.813  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-09 02:08:09.813  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-09 02:08:09.813  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-09 02:08:09.817  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-09 02:08:09.836   874  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-09 02:08:09.839   874  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-09 02:08:09.839   874  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-09 02:08:09.840   874  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-09 02:08:09.840   874  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-09 02:08:09.841   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-09 02:08:09.841   874  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-09 02:08:09.862   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-09 02:08:09.862   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-09 02:08:09.863   373   872 D CommandListener: Setting iface cfg
,09-09 02:08:09.916   874  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-09 02:08:09.916   874  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-09 02:08:09.926   874  1309 D WifiNative-HAL: p2pGetDeviceAddress
,09-09 02:08:09.927   874  1310 E native  : do suspend true
09-09 02:08:09.928   874  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-09 02:08:09.989   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 02:08:11.284   874  1310 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-09 02:08:11.430   874  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.44 rxSuccessRate=11.06 delta 1000 -> 994
,09-09 02:08:11.431   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-09 02:08:11.432   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 02:08:11.447   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-09 02:08:11.526   874  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-09 02:08:11.533  1472  1472 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-09 02:08:11.967  1472  1472 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-09 02:08:12.019  1472  1472 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-09 02:08:12.020  1472  1472 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-09 02:08:12.022   874  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-09 02:08:12.034   874  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-09 02:08:12.034   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-09 02:08:12.035   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-09 02:08:12.057   874  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-09 02:08:12.075   373   872 D CommandListener: Setting iface cfg
,09-09 02:08:12.076   874  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,09-09 02:08:12.092   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-09 02:08:12.108   874  4291 D DhcpClient: Receive thread started
,09-09 02:08:12.208   874  1310 E native  : do suspend false
,09-09 02:08:12.236   874  1887 D DhcpClient: Broadcasting DHCPDISCOVER
,09-09 02:08:12.249   874  4291 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-09 02:08:12.251   874  1887 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-09 02:08:12.255   874  1887 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-09 02:08:12.271   874  4291 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-09 02:08:12.275   874  1887 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-09 02:08:12.281   373   872 D CommandListener: Setting iface cfg
,09-09 02:08:12.293   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-09 02:08:12.294   874  1887 D DhcpClient: Scheduling renewal in 86399s
,09-09 02:08:12.296   874  1310 E native  : do suspend true
,09-09 02:08:12.321   874  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-09 02:08:12.325   874  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-09 02:08:12.327   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-09 02:08:12.333   874  1312 D ConnectivityService: Adding iface wlan0 to network 102
,09-09 02:08:12.334   874  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-09 02:08:12.382   874  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-09 02:08:12.382   874  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-09 02:08:12.384   874  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-09 02:08:12.385   874  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-09 02:08:12.387   874  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-09 02:08:12.403   874  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 02:08:12.416   874  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-09 02:08:12.416   874  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-09 02:08:12.417   874  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-09 02:08:12.417   874  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-09 02:08:12.417   874  1312 D ConnectivityService:    accepting network in place of null
09-09 02:08:12.418   874  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-09 02:08:12.420   874  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-09 02:08:12.438   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=208486, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:08:12.469   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 02:08:12.512   874  4289 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:401b:801::200e
,09-09 02:08:12.519   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-09 02:08:12.525   874  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-09 02:08:12.525   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-09 02:08:12.533   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-09 02:08:12.530   874  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-09 02:08:12.552  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:08:12.552  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:12.552  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:12.552  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:08:12.552  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:12.552  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:08:12.552  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:08:12.552  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:08:12.555  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:08:12.560  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:08:12.560  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:12.560  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:12.560  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:08:12.560  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:12.560  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:08:12.560  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:08:12.560  3820  3820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:08:12.563  1745  1745 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-09 02:08:12.563  3820  3820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:08:12.577  1745  1745 D SystemUpdateService: onCreate
09-09 02:08:12.578   874  4289 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 09 Sep 2016 00:08:12 GMT], X-Android-Received-Millis=[1473379692577], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473379692555]}
,09-09 02:08:12.579   874  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-09 02:08:12.579   874  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-09 02:08:12.579   874  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-09 02:08:12.580   874  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-09 02:08:12.582  1745  1745 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-09 02:08:12.585  1745  4302 I SystemUpdateService: active receiver: enabled
,09-09 02:08:12.595  1745  4302 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-09 02:08:12.602  1745  4302 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-09 02:08:12.602  1745  4302 I SystemUpdateService: now status is 0 (complete)
09-09 02:08:12.602  1745  4302 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-09 02:08:12.602  1745  4302 I SystemUpdateService: file has been verified
,09-09 02:08:12.603  1745  1745 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-09 02:08:12.607  1745  2432 I iu.UploadsManager: num queued entries: 0
,09-09 02:08:12.608  1745  2432 I iu.UploadsManager: num updated entries: 0
,09-09 02:08:12.602  1745  4302 I SystemUpdateService: OTA package size = 12249756
,09-09 02:08:12.612  1745  1745 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-09 02:08:12.615  1745  1745 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-09 02:08:12.617  1745  2432 I iu.SyncManager: NEXT; no task
,09-09 02:08:12.621  4004  4004 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-09 02:08:12.624  1745  4304 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-09 02:08:12.624  1745  4304 W BaseAppContext: Using Auth Proxy for data requests.
09-09 02:08:12.626  1745  4304 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,09-09 02:08:12.631  4004  4004 D SprintDMHelper: simOperator: 
,09-09 02:08:12.632  4004  4004 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-09 02:08:12.639  1745  4302 I SystemUpdateService: showing system update notification
,09-09 02:08:12.648  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:08:12.657  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:08:12.676  3774  4310 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 02:08:12.739  1745  1745 D SystemUpdateService: onDestroy
,09-09 02:08:12.742  3975  4307 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-09 02:08:12.758  3774  4314 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 02:08:12.765  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-09 02:08:12.765  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-09 02:08:12.766  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:08:12.766  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:08:12.773  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 02:08:12.773  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 02:08:12.773  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:08:12.773  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:08:12.820  1523  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 02:08:12.821  1523  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 02:08:12.821  1523  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:08:12.821  1523  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:08:12.828  1745  4304 E MDM     : [185] SitrepService.a: Error sending sitrep.
,09-09 02:08:12.834  3774  4314 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 02:08:12.835  3774  4310 E BooksSync: Soft error
09-09 02:08:12.835  3774  4310 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 02:08:12.835  3774  4310 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 02:08:12.835  3774  4310 E BooksSync: Sync error
09-09 02:08:12.835  3774  4310 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 02:08:12.835  3774  4310 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 02:08:12.835  3774  4310 I BooksSync: Finished books sync
,09-09 02:08:12.848   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 204686, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:08:12.873  1523  4312 I GCM     : Ack for not saved message 142
,09-09 02:08:13.526   874  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-09 02:08:14.071  1873  1967 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-09 02:08:14.072  1873  1967 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-09 02:08:14.113  1523  1523 I ConfigService: onCreate
,09-09 02:08:14.795  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-09 02:08:14.795  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:14.795  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:14.795  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:08:14.795  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:14.795  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:08:14.795  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:08:14.795  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:08:14.802  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:08:14.803  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:14.803  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5a32715 removed from the list
,09-09 02:08:14.804  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:08:14.804  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:14.804  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:08:14.816  3820  4316 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-09 02:08:14.817  3820  4316 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 02:08:17.823  3820  4317 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-09 02:08:17.824  3820  4316 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-09 02:08:17.825  3820  4317 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-09 02:08:17.825  3820  4316 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-09 02:08:17.826  3820  4316 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 02:08:17.826  3820  4317 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 02:08:17.828  3820  4316 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 02:08:17.828  3820  4317 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 02:08:17.832  3820  4317 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-09 02:08:17.832  3820  4316 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 02:08:17.833  3820  4319 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Sender)
,09-09 02:08:17.836  3820  4320 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Sender)
,09-09 02:08:17.840  3820  4322 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: IncomingSocketThread/Receiver)
,09-09 02:08:17.842  3820  4322 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 428, thread name: IncomingSocketThread/Receiver)
,09-09 02:08:17.842  3820  4322 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-09 02:08:17.843  3820  4322 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 428, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 02:08:17.845  3820  4321 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: OutgoingSocketThread/Receiver)
,09-09 02:08:17.847  3820  4321 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: OutgoingSocketThread/Receiver)
09-09 02:08:17.848  3820  4321 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-09 02:08:17.848  3820  4321 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-09 02:08:19.158  1523  1523 I ConfigService: onDestroy
,09-09 02:08:20.424   874  1312 D ConnectivityService: handlePromptUnvalidated 102
,09-09 02:08:20.823  3820  3870 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-09 02:08:20.826  3820  3870 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-09 02:08:20.834  3820  3870 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9f4c2e8 Bundle[{}]
,09-09 02:08:20.834  3820  3870 I io.jxcore.node.LifeCycleMonitor: start: OK
09-09 02:08:20.834  3820  3870 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-09 02:08:20.835  3820  3870 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-09 02:08:20.835  3820  3870 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-09 02:08:20.836  3820  3870 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 02:08:20.836  3820  3870 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-09 02:08:20.840  3820  3870 I System.out: Running OutgoingSocketThread
,09-09 02:08:20.844  3820  4324 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-09 02:08:20.844  3820  4324 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-09 02:08:23.853  3820  4325 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-09 02:08:23.854  3820  4325 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-09 02:08:23.854  3820  4324 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-09 02:08:23.854  3820  4325 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 02:08:23.855  3820  4324 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-09 02:08:23.855  3820  4324 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 02:08:23.855  3820  4325 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 02:08:23.857  3820  4324 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-09 02:08:23.857  3820  4325 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321),
09-09 02:08:23.860  3820  4327 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Sender)
09-09 02:08:23.864  3820  4328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Sender)
09-09 02:08:23.867  3820  4329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Receiver)
09-09 02:08:23.868  3820  4324 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-09 02:08:23.869  3820  4329 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: IncomingSocketThread/Receiver)
09-09 02:08:23.869  3820  4329 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-09 02:08:23.869  3820  4330 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Receiver)
09-09 02:08:23.870  3820  4329 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-09 02:08:23.871  3820  4330 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: OutgoingSocketThread/Receiver)
09-09 02:08:23.871  3820  4330 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-09 02:08:23.872  3820  4330 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-09 02:08:26.856  3820  3870 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,09-09 02:08:26.858  3820  3870 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-09 02:08:26.858  3820  3870 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 450)
,09-09 02:08:26.864  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 02:08:26.864  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9e3a2a added. We now have 3 listener(s)
,09-09 02:08:26.866  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 02:08:26.866  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 02:08:26.866  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 02:08:26.867  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 02:08:26.867  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e93c01b added. We now have 4 listener(s)
09-09 02:08:26.867  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 02:08:26.867  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 02:08:26.871  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:08:26.881  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:08:26.881  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:26.881  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:26.881  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:08:26.881  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:26.881  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:08:26.881  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:08:26.881  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:08:26.887  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:08:26.887  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
09-09 02:08:26.887  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-09 02:08:26.888  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-09 02:08:26.888  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:08:26.888  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:08:26.888  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:26.888  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 02:08:26.888  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 02:08:26.888  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9e3a2a removed from the list
09-09 02:08:26.888  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:08:26.888  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e93c01b removed from the list
,09-09 02:08:26.892  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:26.900  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:08:26.900  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 02:08:26.900  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:26.900  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:08:26.900  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:26.903  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:08:26.904  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:08:26.904  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:08:26.904  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e93c01b not in the list
,09-09 02:08:26.905  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:26.905  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:26.908  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:08:26.908  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:08:26.908  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:26.908  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e93c01b not in the list
09-09 02:08:26.909  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:08:26.909  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:08:26.909  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:26.910  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b9e3a2a not in the list
09-09 02:08:26.911  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 02:08:26.912  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71c1f91 added. We now have 3 listener(s)
,09-09 02:08:26.917  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 02:08:26.918  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 02:08:26.918  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 02:08:26.919  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-09 02:08:26.919  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bdcef6 added. We now have 4 listener(s)
09-09 02:08:26.919  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 02:08:26.920  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 02:08:26.926  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:08:26.936  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:08:26.936  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:26.936  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:26.936  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:08:26.936  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:26.936  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:08:26.936  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:08:26.936  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:08:26.941  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 02:08:26.941  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 02:08:26.942  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 02:08:26.942  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 02:08:26.942  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 02:08:26.942  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 02:08:26.942  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 02:08:26.947  3820  3870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 02:08:26.947  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 02:08:26.948  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:26.953  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 02:08:26.953  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:08:26.955  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 02:08:26.955  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 02:08:26.964  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 02:08:26.964  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 02:08:26.964  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 02:08:26.965  3820  3870 D BluetoothAdapter: STATE_ON
,09-09 02:08:26.971  4233  4270 D BtGatt.GattService: registerClient() - UUID=e23530bc-c4e3-46a1-9808-eff74e345670
,09-09 02:08:26.973  4233  4249 D BtGatt.GattService: onClientRegistered() - UUID=e23530bc-c4e3-46a1-9808-eff74e345670, clientIf=5
,09-09 02:08:26.975  3820  3833 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 02:08:26.977  4233  4244 D BtGatt.GattService: start scan with filters
,09-09 02:08:26.983  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-09 02:08:26.984  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-09 02:08:26.984  4233  4252 D BtGatt.ScanManager: handling starting scan
09-09 02:08:26.984  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 02:08:26.984  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 02:08:26.987  4233  4252 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e82ed85
,09-09 02:08:26.990  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 02:08:26.991  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-09 02:08:26.992  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 02:08:27.000  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-09 02:08:27.000  4233  4249 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 02:08:27.000  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:08:27.002  4233  4252 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 02:08:27.007  3820  3870 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-09 02:08:27.007  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 02:08:27.007  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 02:08:27.008  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:27.008  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 02:08:27.008  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 02:08:27.008  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 02:08:27.008  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 02:08:27.008  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 02:08:27.009  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 02:08:27.009  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-09 02:08:27.010  3820  3870 D BluetoothAdapter: STATE_ON
09-09 02:08:27.012  4233  4270 D BtGatt.GattService: stopScan() - queue size =1
,09-09 02:08:27.013  4233  4244 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 02:08:27.013  4233  4249 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-09 02:08:27.014  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:08:27.014  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 02:08:27.014  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-09 02:08:27.014  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 02:08:27.015  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 02:08:27.015  4233  4252 D BtGatt.ScanManager: Starting BLE batch scan
09-09 02:08:27.015  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 02:08:27.015  4233  4252 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-09 02:08:27.016  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 02:08:27.017  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 02:08:27.017  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 02:08:27.018  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 02:08:27.019  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 02:08:27.021  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 02:08:27.022  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 02:08:27.022  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 02:08:27.037  4233  4249 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 02:08:27.037  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:08:27.046  4233  4249 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 02:08:27.046  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:08:27.060  4233  4249 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 02:08:27.061  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:08:27.061  4233  4252 D BtGatt.ScanManager: stopping BLe Batch
,09-09 02:08:27.080  4233  4249 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 02:08:27.080  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:08:27.081  4233  4252 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:08:27.097  4233  4249 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-09 02:08:27.097  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:08:27.098  4233  4249 D BtGatt.GattService: current time is 223146571187
09-09 02:08:27.098  4233  4249 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -81, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 02:08:27.101  4233  4249 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 02:08:27.523  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 02:08:27.524  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:08:27.524  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 02:08:30.023  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 02:08:30.023  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:08:30.024  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:08:30.025  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 02:08:30.025  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:30.025  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 02:08:30.026  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 02:08:30.026  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71c1f91 removed from the list
09-09 02:08:30.026  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:08:30.027  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bdcef6 removed from the list
09-09 02:08:30.027  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
,09-09 02:08:30.027  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:30.029  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:08:30.029  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:30.034  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 02:08:30.034  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:08:30.035  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:30.035  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bdcef6 not in the list
,09-09 02:08:30.035  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:30.036  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:08:30.039  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:08:30.039  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 02:08:30.039  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:30.040  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bdcef6 not in the list
09-09 02:08:30.040  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:08:30.040  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:08:30.041  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:30.041  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71c1f91 not in the list
09-09 02:08:30.043  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 02:08:30.043  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed01793 added. We now have 3 listener(s)
,09-09 02:08:30.050  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 02:08:30.051  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 02:08:30.051  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 02:08:30.052  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 02:08:30.052  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47b03d0 added. We now have 4 listener(s)
09-09 02:08:30.052  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 02:08:30.054  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 02:08:30.062  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:08:30.074  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:08:30.074  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:30.074  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:30.074  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:08:30.074  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:30.074  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:08:30.074  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:08:30.074  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:08:30.080  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-09 02:08:30.080  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 02:08:30.082  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 02:08:30.084  3820  3870 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,09-09 02:08:30.084  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-09 02:08:30.085  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-09 02:08:30.085  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-09 02:08:30.085  3820  3870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-09 02:08:30.085  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:08:30.087  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:30.089  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-09 02:08:30.090  3820  3870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true,
09-09 02:08:30.090  3820  3870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-09 02:08:30.091  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-09 02:08:30.091  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-09 02:08:30.091  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 02:08:30.091  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 02:08:30.094  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-09 02:08:30.095  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-09 02:08:30.101  3820  3870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-09 02:08:30.101  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-09 02:08:30.102  3820  4331 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-09 02:08:30.106  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-09 02:08:30.106  3820  4331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-09 02:08:30.107  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-09 02:08:30.107  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 02:08:30.109  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-09 02:08:30.110  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 02:08:30.110  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-09 02:08:30.111  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-09 02:08:30.111  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-09 02:08:30.112  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-09 02:08:30.112  3820  3870 D BluetoothAdapter: STATE_ON
,09-09 02:08:30.115  4233  4244 D BtGatt.GattService: registerClient() - UUID=3ca1ce8b-97f3-4eec-86fd-e0e9343ccabd
09-09 02:08:30.115  4233  4249 D BtGatt.GattService: onClientRegistered() - UUID=3ca1ce8b-97f3-4eec-86fd-e0e9343ccabd, clientIf=5
,09-09 02:08:30.116  3820  3831 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-09 02:08:30.117  4233  4251 D BtGatt.AdvertiseManager: message : 0
,09-09 02:08:30.119  4233  4251 D BtGatt.AdvertiseManager: starting multi advertising
,09-09 02:08:30.128  4233  4249 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-09 02:08:30.135  4233  4249 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-09 02:08:30.136  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-09 02:08:30.137  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 02:08:30.139  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 02:08:30.141  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-09 02:08:30.141  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-09 02:08:30.141  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-09 02:08:30.141  3820  3820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-09 02:08:30.141  3820  3820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-09 02:08:30.141  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-09 02:08:30.143  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 02:08:30.145  3820  3820 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 02:08:30.145  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-09 02:08:30.646  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-09 02:08:30.646  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-09 02:08:30.647  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 02:08:33.145  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 02:08:33.145  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-09 02:08:33.146  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-09 02:08:33.146  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-09 02:08:33.146  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-09 02:08:33.146  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-09 02:08:33.147  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-09 02:08:33.147  3820  4331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-09 02:08:33.147  3820  3870 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-09 02:08:33.148  3820  4331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-09 02:08:33.148  3820  4331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-09 02:08:33.148  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-09 02:08:33.148  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 02:08:33.149  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 02:08:33.149  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-09 02:08:33.149  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 02:08:33.150  3820  3820 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-09 02:08:33.153  3820  3870 D BluetoothAdapter: STATE_ON
09-09 02:08:33.154  3820  3870 D BluetoothLeScanner: could not find callback wrapper
09-09 02:08:33.154  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-09 02:08:33.155  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-09 02:08:33.160  4233  4251 D BtGatt.AdvertiseManager: message : 1
,09-09 02:08:33.161  4233  4251 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-09 02:08:33.169  4233  4249 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-09 02:08:33.169  4233  4249 D BtGatt.GattService: Client app is not null!
,09-09 02:08:33.171  4233  4269 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 02:08:33.172  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-09 02:08:33.172  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-09 02:08:33.172  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-09 02:08:33.172  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-09 02:08:33.172  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-09 02:08:33.175  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 02:08:33.175  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 02:08:33.175  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-09 02:08:33.177  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
,09-09 02:08:33.179  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:08:33.179  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-09 02:08:33.180  3820  3820 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-09 02:08:33.180  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 02:08:33.180  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-09 02:08:33.180  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 02:08:33.180  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:08:33.180  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:33.180  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-09 02:08:33.180  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 02:08:33.180  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed01793 removed from the list
09-09 02:08:33.181  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:33.181  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47b03d0 removed from the list
09-09 02:08:33.181  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:08:33.181  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:33.181  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:33.182  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:33.184  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-09 02:08:33.184  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:08:33.184  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:33.185  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47b03d0 not in the list
09-09 02:08:33.185  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:33.185  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:08:33.187  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:08:33.187  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:08:33.187  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:33.187  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@47b03d0 not in the list
09-09 02:08:33.187  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-09 02:08:33.187  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:33.187  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:33.187  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed01793 not in the list
09-09 02:08:33.188  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-09 02:08:33.188  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddcff85 added. We now have 3 listener(s)
09-09 02:08:33.190  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-09 02:08:33.190  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 02:08:33.191  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 02:08:33.191  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 02:08:33.191  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d181da added. We now have 4 listener(s)
09-09 02:08:33.191  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-09 02:08:33.191  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 02:08:33.195  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:08:33.201  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:08:33.201  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:33.201  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:33.201  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:08:33.201  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:33.201  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:08:33.201  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:08:33.201  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:08:33.203  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-09 02:08:33.203  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 02:08:33.204  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 02:08:33.204  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-09 02:08:33.204  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-09 02:08:33.204  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-09 02:08:33.204  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-09 02:08:33.210  3820  3870 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-09 02:08:33.210  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-09 02:08:33.211  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:33.215  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-09 02:08:33.216  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:33.217  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-09 02:08:33.217  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-09 02:08:33.222  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-09 02:08:33.222  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-09 02:08:33.222  3820  3870 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-09 02:08:33.223  3820  3870 D BluetoothAdapter: STATE_ON
,09-09 02:08:33.226  4233  4244 D BtGatt.GattService: registerClient() - UUID=47838a05-f6a0-4980-8dbd-5b8f4d16cbec
,09-09 02:08:33.227  4233  4249 D BtGatt.GattService: onClientRegistered() - UUID=47838a05-f6a0-4980-8dbd-5b8f4d16cbec, clientIf=5
,09-09 02:08:33.228  3820  3833 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-09 02:08:33.229  4233  4243 D BtGatt.GattService: start scan with filters
,09-09 02:08:33.234  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-09 02:08:33.234  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-09 02:08:33.234  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-09 02:08:33.234  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-09 02:08:33.235  4233  4252 D BtGatt.ScanManager: handling starting scan
,09-09 02:08:33.242  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 02:08:33.243  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-09 02:08:33.244  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-09 02:08:33.249  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-09 02:08:33.250  4233  4249 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-09 02:08:33.250  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:08:33.250  4233  4252 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-09 02:08:33.259  4233  4249 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-09 02:08:33.259  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:08:33.260  4233  4252 D BtGatt.ScanManager: Starting BLE batch scan
,09-09 02:08:33.261  4233  4252 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-09 02:08:33.291  4233  4249 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-09 02:08:33.291  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:08:33.309  4233  4249 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-09 02:08:33.309  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:08:33.680  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 02:08:33.744  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-09 02:08:33.744  3820  3820 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 02:08:33.745  3820  3820 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-09 02:08:34.815  4233  4233 D BtGatt.ScanManager: awakened up at time 230864
,09-09 02:08:34.817  4233  4252 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:08:34.865  4233  4249 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-09 02:08:34.865  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:08:34.865  4233  4249 D BtGatt.GattService: current time is 230913767022
,09-09 02:08:34.865  4233  4249 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -80, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -91, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 02:08:34.865  4233  4249 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-09 02:08:34.866  4233  4249 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-09 02:08:34.866  4233  4249 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-09 02:08:34.866  4233  4249 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-09 02:08:34.866  4233  4249 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-09 02:08:36.265  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 02:08:36.265  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-09 02:08:36.266  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-09 02:08:36.266  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:36.266  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-09 02:08:36.267  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-09 02:08:36.267  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-09 02:08:36.267  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-09 02:08:36.267  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-09 02:08:36.268  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-09 02:08:36.269  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-09 02:08:36.271  3820  3870 D BluetoothAdapter: STATE_ON
,09-09 02:08:36.273  4233  4269 D BtGatt.GattService: stopScan() - queue size =1
,09-09 02:08:36.276  4233  4243 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-09 02:08:36.277  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-09 02:08:36.278  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-09 02:08:36.278  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-09 02:08:36.278  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-09 02:08:36.279  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-09 02:08:36.282  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-09 02:08:36.283  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-09 02:08:36.283  3820  3870 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-09 02:08:36.284  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-09 02:08:36.285  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 02:08:36.287  4233  4233 D BtGatt.ScanManager: awakened up at time 232335
,09-09 02:08:36.291  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 02:08:36.292  3820  3820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-09 02:08:36.292  3820  3820 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-09 02:08:36.293  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:08:36.294  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:36.294  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 02:08:36.294  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-09 02:08:36.295  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddcff85 removed from the list
09-09 02:08:36.295  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:08:36.296  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d181da removed from the list
09-09 02:08:36.296  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:08:36.296  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:36.297  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:36.297  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:36.300  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:08:36.300  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:08:36.300  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:08:36.301  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d181da not in the list
,09-09 02:08:36.301  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:36.301  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:08:36.302  4233  4249 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-09 02:08:36.302  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-09 02:08:36.303  4233  4252 D BtGatt.ScanManager: stopping BLe Batch
,09-09 02:08:36.304  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:08:36.304  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:08:36.304  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:36.304  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d181da not in the list
,09-09 02:08:36.305  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:08:36.305  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:36.305  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:36.305  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddcff85 not in the list
,09-09 02:08:36.307  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-09 02:08:36.307  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e35d7e7 added. We now have 3 listener(s)
,09-09 02:08:36.311  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-09 02:08:36.311  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 02:08:36.312  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-09 02:08:36.312  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-09 02:08:36.312  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85f7f94 added. We now have 4 listener(s)
09-09 02:08:36.313  3820  3870 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 02:08:36.314  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-09 02:08:36.317  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 02:08:36.318  4233  4249 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-09 02:08:36.318  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:08:36.318  4233  4252 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-09 02:08:36.322  3820  3870 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 02:08:36.322  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 02:08:36.322  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 02:08:36.322  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 02:08:36.322  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 02:08:36.322  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 02:08:36.322  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 02:08:36.322  3820  3870 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 02:08:36.324  4233  4249 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-09 02:08:36.325  4233  4249 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-09 02:08:36.325  3820  3870 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-09 02:08:36.325  3820  3870 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 02:08:36.326  3820  3870 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-09 02:08:36.326  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-09 02:08:36.326  3820  3870 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-09 02:08:36.327  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:08:36.327  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:08:36.327  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-09 02:08:36.327  3820  3870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 02:08:36.327  3820  3870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e35d7e7 removed from the list
,09-09 02:08:36.327  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:36.327  3820  3870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85f7f94 removed from the list
09-09 02:08:36.328  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:36.330  3820  3820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 02:08:36.330  3820  3870 D io.jxcore.node.ConnectivityMonitor: stop
09-09 02:08:36.330  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:36.331  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 02:08:36.331  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:08:36.332  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:08:36.332  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:08:36.332  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 02:08:36.332  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85f7f94 not in the list
09-09 02:08:36.332  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:36.332  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-09 02:08:36.333  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-09 02:08:36.333  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-09 02:08:36.333  3820  3870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-09 02:08:36.333  3820  3870 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@85f7f94 not in the list
09-09 02:08:36.333  3820  3870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 02:08:36.333  3820  3870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-09 02:08:36.333  3820  3870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-09 02:08:36.333  3820  3870 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e35d7e7 not in the list
,09-09 02:08:36.335  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-09 02:08:36.335  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-09 02:08:36.335  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-09 02:08:36.335  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-09 02:08:36.335  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-09 02:08:36.335  3820  3870 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-09 02:08:36.502   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=232550, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:08:36.793  3820  3820 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-09 02:08:38.350  3820  4333 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,09-09 02:08:40.348  3820  3870 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 459
,09-09 02:08:40.348  3820  3870 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 459, name: My test thread name)
,09-09 02:08:40.355  3820  4334 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: My test thread name)
,09-09 02:08:40.355  3820  4334 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 460, thread name: My test thread name)
09-09 02:08:40.356  3820  4334 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 460, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-09 02:08:40.360  3820  3870 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-09 02:08:40.369  3820  4335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 464, name: My test thread name)
,09-09 02:08:40.370  3820  4335 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 464, thread name: My test thread name): Test exception.
09-09 02:08:40.370  3820  4335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 464, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-09 02:08:40.378  3820  3870 I jxcore-log: Total number of executed tests:  82
09-09 02:08:40.378  3820  3870 I jxcore-log: 
,09-09 02:08:40.379  3820  3870 I jxcore-log: Number of passed tests:  82
09-09 02:08:40.379  3820  3870 I jxcore-log: 
09-09 02:08:40.380  3820  3870 I jxcore-log: Number of failed tests:  0
09-09 02:08:40.380  3820  3870 I jxcore-log: 
,09-09 02:08:40.380  3820  3870 I jxcore-log: Number of ignored tests:  0
09-09 02:08:40.380  3820  3870 I jxcore-log: 
09-09 02:08:40.381  3820  3870 I jxcore-log: Total duration:  101374
09-09 02:08:40.381  3820  3870 I jxcore-log: 
,09-09 02:08:40.390  3820  3870 I jxcore-log: Unit Test app is loaded
09-09 02:08:40.390  3820  3870 I jxcore-log: 
,09-09 02:08:40.410  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.410  3820  3870 I jxcore-log: 
,09-09 02:08:40.416  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.416  3820  3870 I jxcore-log: 
,09-09 02:08:40.417  3820  3820 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-09 02:08:40.418  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.418  3820  3870 I jxcore-log: 
,09-09 02:08:40.419  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.419  3820  3870 I jxcore-log: 
,09-09 02:08:40.421  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 02:08:40.421  3820  3870 I jxcore-log: 
,09-09 02:08:40.422  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 02:08:40.422  3820  3870 I jxcore-log: 
09-09 02:08:40.425  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.425  3820  3870 I jxcore-log: 
09-09 02:08:40.427  3820  4333 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
09-09 02:08:40.427  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.427  3820  3870 I jxcore-log: 
,09-09 02:08:40.428  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 02:08:40.428  3820  3870 I jxcore-log: 
,09-09 02:08:40.429  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 02:08:40.429  3820  3870 I jxcore-log: 
09-09 02:08:40.430  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 02:08:40.430  3820  3870 I jxcore-log: 
,09-09 02:08:40.431  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.431  3820  3870 I jxcore-log: 
,09-09 02:08:40.432  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.432  3820  3870 I jxcore-log: 
09-09 02:08:40.433  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.433  3820  3870 I jxcore-log: 
,09-09 02:08:40.434  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.434  3820  3870 I jxcore-log: 
,09-09 02:08:40.435  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.435  3820  3870 I jxcore-log: 
,09-09 02:08:40.436  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.436  3820  3870 I jxcore-log: 
,09-09 02:08:40.437  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.437  3820  3870 I jxcore-log: 
,09-09 02:08:40.437  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.437  3820  3870 I jxcore-log: 
,09-09 02:08:40.438  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.438  3820  3870 I jxcore-log: 
,09-09 02:08:40.439  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.439  3820  3870 I jxcore-log: 
,09-09 02:08:40.440  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.440  3820  3870 I jxcore-log: 
,09-09 02:08:40.441  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.441  3820  3870 I jxcore-log: 
,09-09 02:08:40.442  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.442  3820  3870 I jxcore-log: 
,09-09 02:08:40.443  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.443  3820  3870 I jxcore-log: 
,09-09 02:08:40.443  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.443  3820  3870 I jxcore-log: 
,09-09 02:08:40.444  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.444  3820  3870 I jxcore-log: 
,09-09 02:08:40.446  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.446  3820  3870 I jxcore-log: 
,09-09 02:08:40.446  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.446  3820  3870 I jxcore-log: 
,09-09 02:08:40.447  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.447  3820  3870 I jxcore-log: 
,09-09 02:08:40.448  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.448  3820  3870 I jxcore-log: 
09-09 02:08:40.448  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.448  3820  3870 I jxcore-log: 
,09-09 02:08:40.449  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.449  3820  3870 I jxcore-log: 
,09-09 02:08:40.449  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.449  3820  3870 I jxcore-log: 
09-09 02:08:40.450  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.450  3820  3870 I jxcore-log: 
,09-09 02:08:40.450  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.450  3820  3870 I jxcore-log: 
,09-09 02:08:40.451  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.451  3820  3870 I jxcore-log: 
,09-09 02:08:40.451  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.451  3820  3870 I jxcore-log: 
09-09 02:08:40.452  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.452  3820  3870 I jxcore-log: 
,09-09 02:08:40.452  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.452  3820  3870 I jxcore-log: 
09-09 02:08:40.453  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-09 02:08:40.453  3820  3870 I jxcore-log: 
,09-09 02:08:40.453  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.453  3820  3870 I jxcore-log: 
,09-09 02:08:40.454  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-09 02:08:40.454  3820  3870 I jxcore-log: 
,09-09 02:08:40.454  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.454  3820  3870 I jxcore-log: 
09-09 02:08:40.455  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.455  3820  3870 I jxcore-log: 
,09-09 02:08:40.456  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.456  3820  3870 I jxcore-log: 
,09-09 02:08:40.456  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.456  3820  3870 I jxcore-log: 
,09-09 02:08:40.457  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.457  3820  3870 I jxcore-log: 
09-09 02:08:40.457  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 02:08:40.457  3820  3870 I jxcore-log: 
,09-09 02:08:40.458  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.458  3820  3870 I jxcore-log: 
,09-09 02:08:40.458  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-09 02:08:40.458  3820  3870 I jxcore-log: 
09-09 02:08:40.459  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.459  3820  3870 I jxcore-log: 
,09-09 02:08:40.459  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 02:08:40.459  3820  3870 I jxcore-log: 
,09-09 02:08:40.460  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-09 02:08:40.460  3820  3870 I jxcore-log: 
09-09 02:08:40.460  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-09 02:08:40.460  3820  3870 I jxcore-log: 
,09-09 02:08:40.461  3820  3870 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-09 02:08:40.461  3820  3870 I jxcore-log: 
,09-09 02:08:40.464  3820  3870 I jxcore-log: My device name is: motorola-Nexus 6,
09-09 02:08:40.464  3820  3870 I jxcore-log: 
,09-09 02:08:40.466  3820  3870 I jxcore-log: Running for WIFI network type
09-09 02:08:40.466  3820  3870 I jxcore-log: 
,09-09 02:08:43.004  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-09 02:08:43.004  3820  3870 I jxcore-log: 
,09-09 02:08:43.500  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-09 02:08:43.500  3820  3870 I jxcore-log: 
,09-09 02:08:43.533  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-09 02:08:43.533  3820  3870 I jxcore-log: 
,09-09 02:08:45.059  3774  4336 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 02:08:45.086  3774  4337 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 02:08:45.108  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-09 02:08:45.108  3820  3870 I jxcore-log: 
,09-09 02:08:45.128  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:08:45.130  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:08:45.148  1523  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 02:08:45.148  1523  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 02:08:45.148  1523  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:08:45.149  1523  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:08:45.174  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:08:45.176  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:08:45.196  1523  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 02:08:45.196  1523  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-09 02:08:45.196  1523  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:08:45.196  1523  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:08:45.216  3774  4337 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 02:08:45.217  3774  4336 E BooksSync: Soft error
09-09 02:08:45.217  3774  4336 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 02:08:45.217  3774  4336 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-09 02:08:45.217  3774  4336 E BooksSync: Sync error
09-09 02:08:45.217  3774  4336 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 02:08:45.217  3774  4336 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 02:08:45.217  3774  4336 I BooksSync: Finished books sync
,09-09 02:08:45.234   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 240994, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:08:45.376  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-09 02:08:45.376  3820  3870 I jxcore-log: 
,09-09 02:08:45.382  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-09 02:08:45.382  3820  3870 I jxcore-log: 
,09-09 02:08:45.388  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-09 02:08:45.388  3820  3870 I jxcore-log: 
,09-09 02:08:45.660  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-09 02:08:45.660  3820  3870 I jxcore-log: 
,09-09 02:08:45.678  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-09 02:08:45.678  3820  3870 I jxcore-log: 
,09-09 02:08:45.683  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-09 02:08:45.683  3820  3870 I jxcore-log: 
,09-09 02:08:46.444  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-09 02:08:46.444  3820  3870 I jxcore-log: 
,09-09 02:08:46.621  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-09 02:08:46.621  3820  3870 I jxcore-log: 
,09-09 02:08:46.973  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-09 02:08:46.973  3820  3870 I jxcore-log: 
,09-09 02:08:46.984  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-09 02:08:46.984  3820  3870 I jxcore-log: 
,09-09 02:08:46.992  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-09 02:08:46.992  3820  3870 I jxcore-log: 
,09-09 02:08:46.999  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-09 02:08:46.999  3820  3870 I jxcore-log: 
,09-09 02:08:47.042  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-09 02:08:47.042  3820  3870 I jxcore-log: 
,09-09 02:08:47.092  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-09 02:08:47.092  3820  3870 I jxcore-log: 
,09-09 02:08:47.100  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-09 02:08:47.100  3820  3870 I jxcore-log: 
,09-09 02:08:47.108  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-09 02:08:47.108  3820  3870 I jxcore-log: 
,09-09 02:08:47.129  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
,09-09 02:08:47.129  3820  3870 I jxcore-log: 
,09-09 02:08:47.134  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-09 02:08:47.134  3820  3870 I jxcore-log: 
,09-09 02:08:47.140  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-09 02:08:47.140  3820  3870 I jxcore-log: 
,09-09 02:08:47.158  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-09 02:08:47.158  3820  3870 I jxcore-log: 
,09-09 02:08:47.185  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-09 02:08:47.185  3820  3870 I jxcore-log: 
,09-09 02:08:47.197  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-09 02:08:47.197  3820  3870 I jxcore-log: 
,09-09 02:08:47.211  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-09 02:08:47.211  3820  3870 I jxcore-log: 
,09-09 02:08:47.223  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-09 02:08:47.223  3820  3870 I jxcore-log: 
,09-09 02:08:47.240  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-09 02:08:47.240  3820  3870 I jxcore-log: 
,09-09 02:08:47.251  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-09 02:08:47.251  3820  3870 I jxcore-log: 
,09-09 02:08:47.257  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-09 02:08:47.257  3820  3870 I jxcore-log: 
,09-09 02:08:47.288  3820  3870 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-09 02:08:47.288  3820  3870 I jxcore-log: 
,09-09 02:08:47.301  3820  3870 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-09 02:08:47.302  3820  3870 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-09 02:08:47.302  3820  3870 I jxcore-log: 
,09-09 02:08:47.304  3820  3870 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-09 02:08:47.304  3820  3870 I jxcore-log: 
,09-09 02:08:47.305  3820  3870 I jxcore-log: ThaliTape :: Started ThaliTape
09-09 02:08:47.305  3820  3870 I jxcore-log: 
,09-09 02:08:47.310  3820  3870 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-09 02:08:47.310  3820  3870 I jxcore-log: 
,09-09 02:08:47.385  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:08:47.385  3820  3870 I jxcore-log: 
,09-09 02:08:47.385  3820  3870 I jxcore-log: websocket error
09-09 02:08:47.385  3820  3870 I jxcore-log: 
09-09 02:08:47.385  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:08:47.385  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:08:47.385  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:08:47.385  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:08:47.385  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:08:47.385  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:08:47.385  3820  3870 I jxcore-log: 
,09-09 02:08:48.633  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:08:48.633  3820  3870 I jxcore-log: 
09-09 02:08:48.635  3820  3870 I jxcore-log: websocket error
09-09 02:08:48.635  3820  3870 I jxcore-log: 
09-09 02:08:48.635  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:08:48.635  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:08:48.635  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:08:48.635  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:08:48.635  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:08:48.635  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:08:48.635  3820  3870 I jxcore-log: 
,09-09 02:08:50.475  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:08:50.475  3820  3870 I jxcore-log: 
09-09 02:08:50.477  3820  3870 I jxcore-log: websocket error
09-09 02:08:50.477  3820  3870 I jxcore-log: 
09-09 02:08:50.477  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:08:50.477  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:08:50.477  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:08:50.477  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:08:50.477  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:08:50.477  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:08:50.477  3820  3870 I jxcore-log: 
,09-09 02:08:52.362   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=248410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 02:08:53.950  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:08:53.950  3820  3870 I jxcore-log: 
,09-09 02:08:53.950  3820  3870 I jxcore-log: websocket error
09-09 02:08:53.950  3820  3870 I jxcore-log: 
,09-09 02:08:53.950  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:08:53.950  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:08:53.950  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:08:53.950  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:08:53.950  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:08:53.950  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:08:53.950  3820  3870 I jxcore-log: 
,09-09 02:08:59.007  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:08:59.007  3820  3870 I jxcore-log: 
09-09 02:08:59.008  3820  3870 I jxcore-log: websocket error
09-09 02:08:59.008  3820  3870 I jxcore-log: 
,09-09 02:08:59.008  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:08:59.008  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:08:59.008  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:08:59.008  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:08:59.008  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:08:59.008  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:08:59.008  3820  3870 I jxcore-log: 
,09-09 02:09:04.093  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:09:04.093  3820  3870 I jxcore-log: 
,09-09 02:09:04.093  3820  3870 I jxcore-log: websocket error
09-09 02:09:04.093  3820  3870 I jxcore-log: 
09-09 02:09:04.094  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:09:04.094  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:09:04.094  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:09:04.094  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:04.094  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:09:04.094  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:04.094  3820  3870 I jxcore-log: 
,09-09 02:09:09.158  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:09:09.158  3820  3870 I jxcore-log: 
,09-09 02:09:09.158  3820  3870 I jxcore-log: websocket error
09-09 02:09:09.158  3820  3870 I jxcore-log: 
,09-09 02:09:09.159  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:09:09.159  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:09:09.159  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:09:09.159  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:09.159  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:09:09.159  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:09.159  3820  3870 I jxcore-log: 
,09-09 02:09:14.213  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:09:14.213  3820  3870 I jxcore-log: 
,09-09 02:09:14.214  3820  3870 I jxcore-log: websocket error
09-09 02:09:14.214  3820  3870 I jxcore-log: 
09-09 02:09:14.214  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:09:14.214  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:09:14.214  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:09:14.214  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:14.214  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:09:14.214  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:14.214  3820  3870 I jxcore-log: 
,09-09 02:09:15.644  3021  4344 V KeepSync: Connecting to GoogleApiClient
,09-09 02:09:15.644   874  2177 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 02:09:15.710  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:09:15.713  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:09:15.748  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 02:09:15.748  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-09 02:09:15.748  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:09:15.748  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:09:15.770  1745  4345 V BaseAuthAsyncOperation: access token request failed
,09-09 02:09:15.772  3021  4344 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 02:09:15.841  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 02:09:15.841  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 02:09:15.842  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:09:15.842  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:09:15.864  3021  4344 E KeepSync: IOException
09-09 02:09:15.864  3021  4344 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 02:09:15.864  3021  4344 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 02:09:15.864  3021  4344 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 02:09:15.864  3021  4344 E KeepSync: 	... 10 more
,09-09 02:09:15.864  3021  4344 W KeepSync: Sync result 2
,09-09 02:09:15.874   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 247702, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:09:15.949   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:09:19.276  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:09:19.276  3820  3870 I jxcore-log: 
09-09 02:09:19.276  3820  3870 I jxcore-log: websocket error
09-09 02:09:19.276  3820  3870 I jxcore-log: 
,09-09 02:09:19.276  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:09:19.276  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:09:19.276  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:09:19.276  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:19.276  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:09:19.276  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:19.276  3820  3870 I jxcore-log: 
,09-09 02:09:24.256   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=280304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-09 02:09:24.330  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:09:24.330  3820  3870 I jxcore-log: 
,09-09 02:09:24.330  3820  3870 I jxcore-log: websocket error
09-09 02:09:24.330  3820  3870 I jxcore-log: 
09-09 02:09:24.330  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:09:24.330  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:09:24.330  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:09:24.330  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:24.330  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:09:24.330  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:24.330  3820  3870 I jxcore-log: 
,09-09 02:09:29.416  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:09:29.416  3820  3870 I jxcore-log: 
09-09 02:09:29.416  3820  3870 I jxcore-log: websocket error
09-09 02:09:29.416  3820  3870 I jxcore-log: 
,09-09 02:09:29.416  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:09:29.416  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:09:29.416  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:09:29.416  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:29.416  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:09:29.416  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:29.416  3820  3870 I jxcore-log: 
,09-09 02:09:34.481  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:09:34.481  3820  3870 I jxcore-log: 
09-09 02:09:34.481  3820  3870 I jxcore-log: websocket error
09-09 02:09:34.481  3820  3870 I jxcore-log: 
,09-09 02:09:34.482  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:09:34.482  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:09:34.482  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:09:34.482  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:34.482  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:09:34.482  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:34.482  3820  3870 I jxcore-log: 
,09-09 02:09:39.535  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:09:39.535  3820  3870 I jxcore-log: 
,09-09 02:09:39.535  3820  3870 I jxcore-log: websocket error
09-09 02:09:39.535  3820  3870 I jxcore-log: 
09-09 02:09:39.535  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:09:39.535  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:09:39.535  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:09:39.535  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:39.535  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:09:39.535  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:39.535  3820  3870 I jxcore-log: 
,09-09 02:09:44.593  3820  3870 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-09 02:09:44.593  3820  3870 I jxcore-log: 
,09-09 02:09:44.593  3820  3870 I jxcore-log: websocket error
09-09 02:09:44.593  3820  3870 I jxcore-log: 
09-09 02:09:44.594  3820  3870 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-09 02:09:44.594  3820  3870 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-09 02:09:44.594  3820  3870 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-09 02:09:44.594  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:44.594  3820  3870 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-09 02:09:44.594  3820  3870 I jxcore-log: emit@events.js:82:1
09-09 02:09:44.594  3820  3870 I jxcore-log: 
,09-09 02:09:46.207  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:09:46.211  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:09:46.259  1523  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 02:09:46.259  1523  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 02:09:46.259  1523  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:09:46.259  1523  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:09:46.276  3565  4352 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 02:09:46.276  3565  4352 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at jdm.a(PG:82)
,09-09 02:09:46.276  3565  4352 E HttpOperation: 	at jcs.o(PG:406)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at jcn.a(PG:1379)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at jcs.i(PG:143)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at blb.a(PG:3937)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at czp.a(PG:18188)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at czp.a(PG:9081)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at czq.run(PG:1686)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:09:46.276  3565  4352 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at jdj.a(PG:4091)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at jdj.a(PG:1125)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at jdm.a(PG:77)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	... 12 more
09-09 02:09:46.276  3565  4352 E HttpOperation: Caused by: faj: BadAuthentication
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at fal.a(PG:38)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	at jdj.a(PG:4089)
09-09 02:09:46.276  3565  4352 E HttpOperation: 	... 14 more
,09-09 02:09:46.315  1523  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 02:09:46.316  1523  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 02:09:46.316  1523  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:09:46.316  1523  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:09:46.334  3565  4352 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 02:09:46.334  3565  4352 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at jdm.a(PG:82)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at jcs.o(PG:406)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at jcn.a(PG:1379)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at jcs.i(PG:143)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at hec.a(PG:42)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at hee.a(PG:102)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at czr.a(PG:65)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at kka.a(PG:108)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at czp.a(PG:19176)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at czp.a(PG:9081)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at czq.run(PG:1686)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:09:46.334  3565  4352 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at jdj.a(PG:4091)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at jdj.a(PG:1125)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at jdm.a(PG:77)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	... 15 more
09-09 02:09:46.334  3565  4352 E HttpOperation: Caused by: faj: BadAuthentication
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at fal.a(PG:38)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	at jdj.a(PG:4089)
09-09 02:09:46.334  3565  4352 E HttpOperation: 	... 17 more
,09-09 02:09:46.335  3565  4352 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 02:09:46.335  3565  4352 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at hec.a(PG:42)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at hee.a(PG:102)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at czr.a(PG:65)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at kka.a(PG:108)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	... 15 more
09-09 02:09:46.335  3565  4352 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at fal.a(PG:38)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 02:09:46.335  3565  4352 E ExperimentLoader: 	... 17 more
,09-09 02:09:46.478   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 280055, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:09:47.842   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=303890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:09:49.927  3820  3870 I jxcore-log: ThaliTape :: Reconnected to the test server
09-09 02:09:49.927  3820  3870 I jxcore-log: 
,09-09 02:09:49.942  3820  3870 I jxcore-log: ThaliTape :: Connected to the test server
09-09 02:09:49.942  3820  3870 I jxcore-log: 
,09-09 02:09:54.629   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=310677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:10:14.562   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=330610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:10:16.715  3774  4364 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 02:10:16.736  3774  4365 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 02:10:16.746  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:16.751  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:16.766  1523  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 02:10:16.766  1523  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 02:10:16.766  1523  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:10:16.767  1523  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:10:16.774  3021  4363 V KeepSync: Connecting to GoogleApiClient
,09-09 02:10:16.774   874  1396 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 02:10:16.786  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:16.791  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:16.811  1523  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-09 02:10:16.811  1523  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 02:10:16.812  1523  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:10:16.812  1523  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:10:16.826  3774  4365 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 02:10:16.826  3774  4364 E BooksSync: Soft error
09-09 02:10:16.826  3774  4364 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 02:10:16.826  3774  4364 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 02:10:16.826  3774  4364 E BooksSync: Sync error
09-09 02:10:16.826  3774  4364 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 02:10:16.826  3774  4364 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 02:10:16.826  3774  4364 I BooksSync: Finished books sync
,09-09 02:10:16.848  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:16.851   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 305477, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:10:16.852  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:16.873  1523  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 02:10:16.873  1523  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 02:10:16.873  1523  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:10:16.874  1523  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:10:16.886  1745  4366 V BaseAuthAsyncOperation: access token request failed
,09-09 02:10:16.887  3021  4363 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 02:10:16.928  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-09 02:10:16.928  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-09 02:10:16.928  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:10:16.929  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:10:16.947  3021  4363 E KeepSync: IOException
09-09 02:10:16.947  3021  4363 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 02:10:16.947  3021  4363 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 02:10:16.947  3021  4363 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 02:10:16.947  3021  4363 E KeepSync: 	... 10 more
,09-09 02:10:16.947  3021  4363 W KeepSync: Sync result 2
09-09 02:10:16.951   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 302734, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:10:19.949   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=335997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:10:26.090  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:26.102  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:26.105  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:26.160  1523  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-09 02:10:26.160  1523  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-09 02:10:26.160  1523  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:10:26.161  1523  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:10:26.197  1523  2318 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-09 02:10:26.197  1523  2318 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-09 02:10:26.197  1523  2318 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-09 02:10:26.197  1523  2318 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-09 02:10:26.197  1523  2318 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-09 02:10:26.197  1523  2318 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-09 02:10:26.197  1523  2318 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 02:10:26.209  3527  3556 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-09 02:10:26.209  3527  3556 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-09 02:10:26.209  3527  3556 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-09 02:10:26.209  3527  3556 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-09 02:10:26.209  3527  3556 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-09 02:10:26.209  3527  3556 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-09 02:10:26.209  3527  3556 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-09 02:10:45.164  1523  2181 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-09 02:10:47.296  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:47.297  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:10:47.333  1523  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 02:10:47.333  1523  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 02:10:47.333  1523  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:10:47.333  1523  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:10:47.356  3565  4373 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 02:10:47.356  3565  4373 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at jdm.a(PG:82)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at jcs.o(PG:406)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at jcn.a(PG:1379)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at jcs.i(PG:143)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at blb.a(PG:3937)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at czp.a(PG:18188)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at czp.a(PG:9081)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at czq.run(PG:1686)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:10:47.356  3565  4373 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at jdj.a(PG:4091)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at jdj.a(PG:1125)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at jdm.a(PG:77)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	... 12 more
09-09 02:10:47.356  3565  4373 E HttpOperation: Caused by: faj: BadAuthentication
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at fal.a(PG:38)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	at jdj.a(PG:4089)
09-09 02:10:47.356  3565  4373 E HttpOperation: 	... 14 more
,09-09 02:10:47.402  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 02:10:47.403  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-09 02:10:47.403  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:10:47.403  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:10:47.425  3565  4373 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 02:10:47.425  3565  4373 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at jdm.a(PG:82)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at jcs.o(PG:406)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at jcn.a(PG:1379)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at jcs.i(PG:143)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at hec.a(PG:42)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at hee.a(PG:102)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at czr.a(PG:65)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at kka.a(PG:108)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at czp.a(PG:19176)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at czp.a(PG:9081)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at czq.run(PG:1686)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:10:47.425  3565  4373 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at jdj.a(PG:4091)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at jdj.a(PG:1125)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at jdm.a(PG:77)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	... 15 more
09-09 02:10:47.425  3565  4373 E HttpOperation: Caused by: faj: BadAuthentication
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at fal.a(PG:38)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	at jdj.a(PG:4089)
09-09 02:10:47.425  3565  4373 E HttpOperation: 	... 17 more
09-09 02:10:47.425  3565  4373 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 02:10:47.425  3565  4373 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at hec.a(PG:42)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at hee.a(PG:102)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at czr.a(PG:65)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at kka.a(PG:108)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	... 15 more
09-09 02:10:47.425  3565  4373 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at fal.a(PG:38)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 02:10:47.425  3565  4373 E ExperimentLoader: 	... 17 more
,09-09 02:10:47.581   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 334784, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:11:03.576   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=379624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:11:10.082   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=386130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:11:18.833  3021  4377 V KeepSync: Connecting to GoogleApiClient
09-09 02:11:18.834   874  1994 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 02:11:18.893  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:11:18.896  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:11:18.936  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 02:11:18.936  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 02:11:18.936  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:11:18.936  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:11:18.963  1745  4378 V BaseAuthAsyncOperation: access token request failed
,09-09 02:11:18.965  3021  4377 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 02:11:19.034  1523  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 02:11:19.034  1523  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 02:11:19.034  1523  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:11:19.034  1523  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:11:19.059  3021  4377 E KeepSync: IOException
09-09 02:11:19.059  3021  4377 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 02:11:19.059  3021  4377 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 02:11:19.059  3021  4377 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 02:11:19.059  3021  4377 E KeepSync: 	... 10 more
09-09 02:11:19.059  3021  4377 W KeepSync: Sync result 2
,09-09 02:11:19.075   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 394622, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:11:28.696   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=404744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:11:34.789   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=410837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:11:52.406  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:11:52.410  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:11:52.454  1523  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 02:11:52.454  1523  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 02:11:52.454  1523  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:11:52.454  1523  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:11:52.474  3565  4383 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 02:11:52.474  3565  4383 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at jdm.a(PG:82)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at jcs.o(PG:406)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at jcn.a(PG:1379)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at jcs.i(PG:143)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at blb.a(PG:3937)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at czp.a(PG:18188)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at czp.a(PG:9081)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at czq.run(PG:1686)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:11:52.474  3565  4383 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at jdj.a(PG:4091)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at jdj.a(PG:1125)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at jdm.a(PG:77)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	... 12 more
09-09 02:11:52.474  3565  4383 E HttpOperation: Caused by: faj: BadAuthentication
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at fal.a(PG:38)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	at jdj.a(PG:4089)
09-09 02:11:52.474  3565  4383 E HttpOperation: 	... 14 more
,09-09 02:11:52.526  1523  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 02:11:52.526  1523  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 02:11:52.526  1523  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:11:52.526  1523  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:11:52.541  3565  4383 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 02:11:52.541  3565  4383 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at jdm.a(PG:82)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at jcs.o(PG:406)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at jcn.a(PG:1379)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at jcs.i(PG:143)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at hec.a(PG:42)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at hee.a(PG:102)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at czr.a(PG:65)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at kka.a(PG:108)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at czp.a(PG:19176)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at czp.a(PG:9081)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at czq.run(PG:1686)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:11:52.541  3565  4383 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at jdj.a(PG:4091)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at jdj.a(PG:1125)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at jdm.a(PG:77)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	... 15 more
09-09 02:11:52.541  3565  4383 E HttpOperation: Caused by: faj: BadAuthentication
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at fal.a(PG:38)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	at jdj.a(PG:4089)
09-09 02:11:52.541  3565  4383 E HttpOperation: 	... 17 more
,09-09 02:11:52.541  3565  4383 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 02:11:52.541  3565  4383 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at hec.a(PG:42)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at hee.a(PG:102)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at czr.a(PG:65)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at kka.a(PG:108)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	... 15 more
09-09 02:11:52.541  3565  4383 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at fal.a(PG:38)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 02:11:52.541  3565  4383 E ExperimentLoader: 	... 17 more
,09-09 02:11:52.658   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 428144, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:11:53.762   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=429810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:12:00.216   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=436264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:12:18.829   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=454877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:12:25.282   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=461330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:12:25.338  3774  4386 I BooksSync: Starting books sync for 61035162, extras: ade
,09-09 02:12:25.367  3774  4387 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-09 02:12:25.380  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:12:25.382  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:12:25.420  1523  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 02:12:25.420  1523  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 02:12:25.420  1523  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:12:25.420  1523  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:12:25.463  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:12:25.466  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:12:25.519  1523  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-09 02:12:25.519  1523  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-09 02:12:25.519  1523  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:12:25.520  1523  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:12:25.548  3774  4387 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-09 02:12:25.549  3774  4386 E BooksSync: Soft error
09-09 02:12:25.549  3774  4386 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 02:12:25.549  3774  4386 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 02:12:25.549  3774  4386 E BooksSync: Sync error
09-09 02:12:25.549  3774  4386 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-09 02:12:25.549  3774  4386 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-09 02:12:25.549  3774  4386 I BooksSync: Finished books sync
,09-09 02:12:25.569   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 461287, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:12:43.896   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=479944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:12:50.349   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=486397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:13:08.909   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=504957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:13:15.402   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=511450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:13:22.415  3021  4391 V KeepSync: Connecting to GoogleApiClient
,09-09 02:13:22.416   874  1993 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-09 02:13:22.470  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:13:22.472  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:13:22.498  1523  2982 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-09 02:13:22.499  1523  2982 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-09 02:13:22.499  1523  2982 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:13:22.499  1523  2982 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:13:22.515  1745  4392 V BaseAuthAsyncOperation: access token request failed
,09-09 02:13:22.516  3021  4391 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-09 02:13:22.563  1523  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-09 02:13:22.563  1523  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-09 02:13:22.563  1523  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:13:22.563  1523  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:13:22.582  3021  4391 E KeepSync: IOException
09-09 02:13:22.582  3021  4391 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-09 02:13:22.582  3021  4391 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-09 02:13:22.582  3021  4391 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-09 02:13:22.582  3021  4391 E KeepSync: 	... 10 more
09-09 02:13:22.583  3021  4391 W KeepSync: Sync result 2
,09-09 02:13:22.599   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 518367, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:13:33.976   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=530024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:13:40.483   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=536531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:13:59.042   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=555090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:14:01.945  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:14:01.951  1523  1523 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-09 02:14:01.989  1523  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-09 02:14:01.989  1523  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 02:14:01.989  1523  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-09 02:14:01.989  1523  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:14:02.011  3565  4396 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-09 02:14:02.011  3565  4396 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at jdm.a(PG:82)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at jcs.o(PG:406)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at jcn.a(PG:1379)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at jcs.i(PG:143)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at blb.a(PG:3937)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at czp.a(PG:18188)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at czp.a(PG:9081)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at czq.run(PG:1686)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:14:02.011  3565  4396 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at jdj.a(PG:4091)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at jdj.a(PG:1125)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at jdm.a(PG:77)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	... 12 more
09-09 02:14:02.011  3565  4396 E HttpOperation: Caused by: faj: BadAuthentication
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at fal.a(PG:38)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	at jdj.a(PG:4089)
09-09 02:14:02.011  3565  4396 E HttpOperation: 	... 14 more
,09-09 02:14:02.100  1523  2318 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-09 02:14:02.100  1523  2318 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-09 02:14:02.100  1523  2318 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-09 02:14:02.100  1523  2318 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-09 02:14:02.130  3565  4396 E HttpOperation: [getmobileexperiments] Unexpected exception
09-09 02:14:02.130  3565  4396 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at jdm.a(PG:82)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at jcs.o(PG:406)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at jcn.a(PG:1379)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at jcs.i(PG:143)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at hec.a(PG:42)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at hee.a(PG:102)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at czr.a(PG:65)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at kka.a(PG:108)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at czp.a(PG:19176)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at czp.a(PG:9081)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at czq.run(PG:1686)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:14:02.130  3565  4396 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at jdj.a(PG:4091)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at jdj.a(PG:1125)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at jdm.a(PG:77)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	... 15 more
09-09 02:14:02.130  3565  4396 E HttpOperation: Caused by: faj: BadAuthentication
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at fal.a(PG:38)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	at jdj.a(PG:4089)
09-09 02:14:02.130  3565  4396 E HttpOperation: 	... 17 more
,09-09 02:14:02.130  3565  4396 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-09 02:14:02.130  3565  4396 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at jdm.a(PG:82)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at jcs.o(PG:406)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at jcn.a(PG:1379)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at jcs.i(PG:143)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at hec.a(PG:42)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at hee.a(PG:102)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at czr.a(PG:65)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at kka.a(PG:108)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at czp.a(PG:19176)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at czp.a(PG:9081)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at czq.run(PG:1686)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at jdj.a(PG:4091)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at jdj.a(PG:1125)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at jdm.a(PG:77)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	... 15 more
09-09 02:14:02.130  3565  4396 E ExperimentLoader: Caused by: faj: BadAuthentication
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at fal.a(PG:38)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	at jdj.a(PG:4089)
09-09 02:14:02.130  3565  4396 E ExperimentLoader: 	... 17 more
,09-09 02:14:02.302   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 557735, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-09 02:14:05.562   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=561610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:14:24.162   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=580210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:14:30.629   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=586677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:14:49.229   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=605277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:14:55.682   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=611730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:15:14.296   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=630344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:15:20.749   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=636797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:15:39.363   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=655410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:15:45.816   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=661863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:16:04.429   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=680477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:16:10.882   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=686930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:16:29.443   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=705491, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:16:35.935   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=711983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:16:54.509   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=730557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:17:01.003   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=737051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:17:19.576   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=755624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:17:26.069   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=762117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:17:44.696   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=780744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:17:51.149   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=787197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:18:09.762   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=805810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:18:16.216   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=812264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:18:34.829   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=830877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:18:41.269   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=837317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:18:59.896   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=855944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:19:06.349   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=862397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:19:24.962   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=881010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:19:31.402   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=887450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:19:35.496   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=891544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:19:56.469   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=912517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:20:00.562   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=916610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:20:21.522   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=937570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:20:25.615   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=941663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:20:46.589   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=962637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:20:50.696   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=966744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:21:11.656   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=987704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:21:15.748   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=991797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:21:36.722   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1012770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:21:40.815   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1016863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:22:01.789   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1037837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:22:05.882   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1041930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:22:26.856   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1062904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:22:30.949   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1066997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:22:51.922   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1087970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:22:56.015   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1092063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:23:16.989   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1113037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:23:22.042   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1118090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:23:42.069   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1138117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:23:46.162   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1142210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:24:07.122   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1163170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:24:11.215   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1167263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:24:32.189   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1188237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:24:45.923   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1201971, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:24:57.255   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1213303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:25:02.188   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,09-09 02:25:10.989   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1227037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:25:22.336   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1238384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:25:36.056   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1252104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:25:47.389   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1263437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:26:01.122   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1277170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:26:12.482   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1288530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:26:26.189   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1302237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:26:37.549   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1313597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:26:51.255   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1327303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:27:02.616   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1338664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:27:16.322   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1352370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:27:27.669   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1363717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:27:41.389   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1377437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:27:52.722   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1388770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:28:06.455   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1402503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:28:17.803   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1413850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:28:31.522   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1427571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:28:42.869   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1438917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:28:56.589   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1452637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:29:07.922   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1463970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:29:21.656   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1477704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:29:33.015   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1489063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:29:36.042   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1492090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-09 02:29:58.096   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1514144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-09 02:30:01.122   874  4290 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1517170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-09 02:30:11.688  4446  4446 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-09 02:30:11.693  4446  4446 D AndroidRuntime: CheckJNI is OFF
09-09 02:30:11.729  4446  4446 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-09 02:30:11.769  4446  4446 I Radio-JNI: register_android_hardware_Radio DONE
09-09 02:30:11.790  4446  4446 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-09 02:30:11.801   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-09 02:30:11.802   874   887 I ActivityManager: Killing 3820:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-09 02:30:11.924   874   897 W PackageSettings: Skipping PackageSetting{3d2349e com.example.hello/10273} due to missing metadata
09-09 02:30:11.932   874  1396 I WindowState: WIN DEATH: Window{c716df6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-09 02:30:11.933   874  1311 D WifiService: Client connection lost with reason: 4
09-09 02:30:11.933   874  1373 D GraphicsStats: Buffer count: 2
09-09 02:30:11.973   874   897 I art     : Starting a blocking GC Explicit
09-09 02:30:11.994   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-09 02:30:11.994   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-09 02:30:11.995   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-09 02:30:11.995   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-09 02:30:11.995   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:30:11.995   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:11.995   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 02:30:11.995   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 02:30:11.995   874   887 I ActivityManager:   Force finishing activity ActivityRecord{9384c1f u0 com.test.thalitest/.MainActivity t4}
09-09 02:30:11.999   874  1991 W ActivityManager: Spurious death for ProcessRecord{85024c1 0:com.test.thalitest/u0a0}, curProc for 3820: null
09-09 02:30:12.021   874   897 I art     : Explicit concurrent mark sweep GC freed 54170(4MB) AllocSpace objects, 9(180KB) LOS objects, 33% free, 29MB/43MB, paused 734us total 47.049ms
09-09 02:30:12.041   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-09 02:30:12.043  4446  4446 I art     : System.exit called, status: 0
09-09 02:30:12.043  4446  4446 I AndroidRuntime: VM exiting with result code 0.
09-09 02:30:12.047   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-09 02:30:12.062   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-09 02:30:12.067  4233  4233 D BluetoothMapAppObserver: onReceive
09-09 02:30:12.067  4233  4233 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-09 02:30:12.074  1873  1873 I Keyboard.Facilitator: resetDictionaries() : en_US
09-09 02:30:12.074   874  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-09 02:30:12.079  2131  2303 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-09 02:30:12.080  3660  3660 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-09 02:30:12.086  1873  4460 I Keyboard.Facilitator.DecoderInitializer: run()
09-09 02:30:12.088  1873  4460 I Decoder : createOrResetDecoder
09-09 02:30:12.094   874  1994 I ActivityManager: Start proc 4462:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-09 02:30:12.136  1932  1932 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-09 02:30:12.156  1523  1523 I ConfigService: onCreate
09-09 02:30:12.159  4462  4462 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 02:30:12.163  1523  4476 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-09 02:30:12.163  1523  4476 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-09 02:30:12.167   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-09 02:30:12.169  1523  4476 W SQLiteOpenHelper: Opened config.db in read-only mode
09-09 02:30:12.178   874  1993 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3820 uid 10000
09-09 02:30:12.179  1873  1873 I Keyboard.Facilitator: onFinishInput()
09-09 02:30:12.192  1873  4460 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-09 02:30:12.206   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-09 02:30:12.207   874   886 E PackageManager: Failed to write settings, restoring backup
09-09 02:30:12.207   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-09 02:30:12.207   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-09 02:30:12.207   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-09 02:30:12.207   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-09 02:30:12.207   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-09 02:30:12.207   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:30:12.207   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:12.207   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 02:30:12.212   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-09 02:30:12.212   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-09 02:30:12.212   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 02:30:12.212   874   887 E DropBoxManagerService: 	... 13 more
09-09 02:30:12.214  1947  2031 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-09 02:30:12.218  1873  4460 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-09 02:30:12.220  1873  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-09 02:30:12.220  1873  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-09 02:30:12.222  1873  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-09 02:30:12.222  1873  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-09 02:30:12.223  1873  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-09 02:30:12.223  1873  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-09 02:30:12.223  1873  4460 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-09 02:30:12.223  1873  4460 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-09 02:30:12.224  1873  4460 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-09 02:30:12.224  1873  4460 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-09 02:30:12.224  1873  4460 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-09 02:30:12.224  1873  4460 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-09 02:30:12.227   874  1373 I ActivityManager: Start proc 4480:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-09 02:30:12.228  1947  2031 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-09 02:30:12.228  1947  2031 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1947
09-09 02:30:12.228  1947  2031 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:12.228  1947  2031 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 02:30:12.230   874  1714 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 02:30:12.230   874  4486 E DropBoxManagerService: Can't write: system_app_crash
09-09 02:30:12.230   874  4486 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 02:30:12.230   874  4486 E DropBoxManagerService: 	... 5 more
09-09 02:30:12.235  1947  2031 I Process : Sending signal. PID: 1947 SIG: 9
09-09 02:30:12.252  4462  4462 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-09 02:30:12.276  4462  4495 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-09 02:30:12.287   874  1994 I ActivityManager: Start proc 4496:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:12.289  4462  4479 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:12.289  4462  4479 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 02:30:12.308   874  1993 D GraphicsStats: Buffer count: 1
09-09 02:30:12.308   874   884 I WindowState: WIN DEATH: Window{13d1ac4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-09 02:30:12.319   874  1713 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1947) has died
09-09 02:30:12.320   874  1713 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-09 02:30:12.322   874  1713 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 02:30:12.346   874   887 I ActivityManager: Start proc 4509:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 02:30:12.355  4496  4496 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-09 02:30:12.380  1523  1523 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-09 02:30:12.380  1523  1523 D AndroidRuntime: Shutting down VM
09-09 02:30:12.381  1523  1523 E AndroidRuntime: FATAL EXCEPTION: main
09-09 02:30:12.381  1523  1523 E AndroidRuntime: Process: com.google.process.gapps, PID: 1523
09-09 02:30:12.381  1523  1523 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-09 02:30:12.381  1523  1523 E AndroidRuntime: 	... 8 more
09-09 02:30:12.385   874  4524 E DropBoxManagerService: Can't write: system_app_crash
09-09 02:30:12.385   874  4524 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 02:30:12.385   874  4524 E DropBoxManagerService: 	... 5 more
09-09 02:30:12.385  1523  1523 I Process : Sending signal. PID: 1523 SIG: 9
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:30:12.402  4509  4509 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:30:12.403  4509  4509 D AndroidRuntime: Shutting down VM
09-09 02:30:12.405   874  1311 D WifiService: Client connection lost with reason: 4
09-09 02:30:12.429   874   884 I ActivityManager: Process com.google.process.gapps (pid 1523) has died
09-09 02:30:12.429  4462  4479 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-09 02:30:12.430   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-09 02:30:12.430   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-09 02:30:12.430   874   884 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 20999ms
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:12.433  4462  4495 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-09 02:30:12.434  4462  4495 E AndroidRuntime: Process: android.process.acore, PID: 4462
09-09 02:30:12.434  4462  4495 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:12.434  4462  4495 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-09 02:30:12.435  4462  4479 I Process : Sending signal. PID: 4462 SIG: 9
09-09 02:30:12.438   278   278 E lowmemorykiller: Error writing /proc/4462/oom_score_adj; errno=22
09-09 02:30:12.448  3712  3712 W RocketImpressions: ClearcutLogger connection suspended: 1
09-09 02:30:12.450  4509  4509 E AndroidRuntime: FATAL EXCEPTION: main
09-09 02:30:12.450  4509  4509 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4509
09-09 02:30:12.450  4509  4509 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-09 02:30:12.450  4509  4509 E AndroidRuntime: 	... 10 more
09-09 02:30:12.452  1745  1745 W RocketImpressions: ClearcutLogger connection suspended: 1
09-09 02:30:12.457   874  4526 E DropBoxManagerService: Can't write: system_app_crash
09-09 02:30:12.457   874  4526 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 02:30:12.457   874  4526 E DropBoxManagerService: 	... 5 more
09-09 02:30:12.459   874  4299 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-09 02:30:12.460   874  4528 E DropBoxManagerService: Can't write: system_app_crash
09-09 02:30:12.460   874  4528 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-09 02:30:12.460   874  4528 E DropBoxManagerService: 	... 5 more
09-09 02:30:12.461  4509  4509 I Process : Sending signal. PID: 4509 SIG: 9
09-09 02:30:12.476   874   884 I ActivityManager: Start proc 4530:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
09-09 02:30:12.485   874  1991 I ActivityManager: Killing 3712:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-09 02:30:12.526   874  1992 I ActivityManager: Process android.process.acore (pid 4462) has died
09-09 02:30:12.527   874  1992 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30903ms
09-09 02:30:12.531   874  2177 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4509) has died
09-09 02:30:12.533   874  2177 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-09 02:30:12.533   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
