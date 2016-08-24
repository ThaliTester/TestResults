#### Test 79763830e108614_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-24 13:23:43.721  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:23:43.733  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 13:23:43.737  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-24 13:23:43.786  1529  2124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-24 13:23:43.786  1529  2124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 13:23:43.786  1529  2124 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:23:43.786  1529  2124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-24 13:23:43.819  3509  3509 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-24 13:23:43.820  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-24 13:23:43.821  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-24 13:23:44.379  3794  3794 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 13:23:44.384  3794  3794 D AndroidRuntime: CheckJNI is OFF
08-24 13:23:44.420  3794  3794 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 13:23:44.462  3794  3794 I Radio-JNI: register_android_hardware_Radio DONE
08-24 13:23:44.482  3794  3794 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 13:23:44.486   873  2014 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 13:23:44.520  1979  3748 W SearchService: Abort, client detached.
08-24 13:23:44.541  1979  2348 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@92273ea
08-24 13:23:44.541  1979  1979 I HotwordDetector: Closing mic
08-24 13:23:44.541  1979  2354 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-24 13:23:44.561  3794  3794 D AndroidRuntime: Shutting down VM
08-24 13:23:44.577   873  3114 I ActivityManager: Start proc 3804:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-24 13:23:44.613   376  2356 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-24 13:23:44.615   376  2356 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-24 13:23:44.621   376  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-24 13:23:44.622  1979  2353 I MicroRecognitionRnrImpl: Detection finished
08-24 13:23:44.623  1979  2352 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-24 13:23:44.665  3804  3804 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-24 13:23:44.693  3804  3804 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-24 13:23:44.701  3804  3804 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1077-1080)
08-24 13:23:44.701  3804  3804 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 13:23:44.717  3804  3804 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fc013cf}
08-24 13:23:44.717  3804  3804 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 13:23:44.718  3804  3804 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 13:23:44.723  3804  3804 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 13:23:44.724  3804  3804 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 13:23:44.741  3804  3804 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-24 13:23:44.750  3804  3804 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 13:23:44.750  3804  3804 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 13:23:44.750  3804  3804 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 13:23:44.750  3804  3804 I Adreno  : Build Date                       : 10/20/15
08-24 13:23:44.750  3804  3804 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 13:23:44.750  3804  3804 I Adreno  : Local Branch                     : M14
08-24 13:23:44.750  3804  3804 I Adreno  : Remote Branch                    : 
08-24 13:23:44.750  3804  3804 I Adreno  : Remote Branch                    : 
08-24 13:23:44.750  3804  3804 I Adreno  : Reconstruct Branch               : 
,08-24 13:23:44.827   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8155a00:true
,08-24 13:23:44.867  3804  3804 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 13:23:44.879  3804  3804 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-24 13:23:44.940  3804  3842 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-24 13:23:44.953  3804  3829 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-24 13:23:44.980  3804  3842 I OpenGLRenderer: Initialized EGL, version 1.4
,08-24 13:23:45.068   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +507ms
,08-24 13:23:45.075  1849  1849 I Keyboard.Facilitator: onFinishInput()
,08-24 13:23:45.139  3804  3804 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3804
,08-24 13:23:45.330  3804  3804 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 13:23:45.413   873  2108 I ActivityManager: Killing 2969:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-24 13:23:45.445   873  2108 I ActivityManager: Killing 3206:com.google.android.gm/u0a78 (adj 15): empty #18
,08-24 13:23:45.528  3804  3845 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1713768144
,08-24 13:23:45.537  3804  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 13:23:45.537  3804  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 13:23:45.537  3804  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 13:23:45.537  3804  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 13:23:45.537  3804  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-24 13:23:45.537  3804  3845 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b9a723 added. We now have 1 listener(s)
,08-24 13:23:45.541  3804  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-24 13:23:45.543  3804  3845 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-24 13:23:45.544  3804  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 13:23:45.545  3804  3845 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 13:23:45.550  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 13:23:45.551  3804  3845 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21c079e added. We now have 1 listener(s)
08-24 13:23:45.551  3804  3845 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 13:23:45.556   873  1306 D WifiService: New client listening to asynchronous messages
,08-24 13:23:45.557  3804  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 13:23:45.557  3804  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-24 13:23:45.559  3804  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-24 13:23:45.559  3804  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-24 13:23:45.559  3804  3845 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-24 13:23:45.562  3804  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 13:23:45.562  3804  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-24 13:23:45.568  3804  3845 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-24 13:23:45.570  3804  3845 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:23:45.570  3804  3845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:23:45.570  3804  3845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 13:23:45.570  3804  3845 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:23:45.570  3804  3845 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:23:45.570  3804  3845 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:23:45.570  3804  3845 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:23:45.570  3804  3845 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 13:23:45.570  3804  3845 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-24 13:23:45.570  3804  3845 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 13:23:45.573  3804  3845 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-24 13:23:45.573  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 13:23:45.576  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 13:23:45.608  3804  3804 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 13:23:45.756   873  1305 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-24 13:23:46.030  3804  3814 I art     : Background sticky concurrent mark sweep GC freed 68506(6MB) AllocSpace objects, 18(1604KB) LOS objects, 29% free, 23MB/32MB, paused 708us total 108.354ms
,08-24 13:23:46.747  3804  3854 W jxcore-log: Initializing JXcore engine
,08-24 13:23:46.748  3804  3854 W jxcore-log: JXcore engine is ready
,08-24 13:23:46.812  3854  3854 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8949 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-24 13:23:46.812  3854  3854 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10867]" dev="sockfs" ino=10867 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-24 13:23:46.812  3854  3854 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 13:23:46.815  3854  3854 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26153]" dev="sockfs" ino=26153 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-24 13:23:46.834  3804  3854 W jxcore-log: Starting JXcore engine
,08-24 13:23:46.923  3804  3854 W jxcore-log: Platform android
08-24 13:23:46.923  3804  3854 W jxcore-log: 
,08-24 13:23:46.923  3804  3854 W jxcore-log: Process ARCH arm
08-24 13:23:46.923  3804  3854 W jxcore-log: 
,08-24 13:23:47.102  3804  3854 I jxcore-log: JXcore Cordova bridge is ready!
08-24 13:23:47.102  3804  3854 I jxcore-log: 
,08-24 13:23:47.102  3804  3854 W jxcore-log: JXcore engine is started
,08-24 13:23:47.116  3804  3845 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 13:23:47.123  3804  3804 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-24 13:23:48.045   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=124423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:23:48.378   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-24 13:23:49.501  3010  3856 V KeepSync: Connecting to GoogleApiClient
,08-24 13:23:49.501   873  2099 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 13:23:49.561  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:23:49.565  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:23:49.624  1529  2366 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 13:23:49.624  1529  2366 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-24 13:23:49.624  1529  2366 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:23:49.624  1529  2366 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:23:49.640  1744  3857 V BaseAuthAsyncOperation: access token request failed
,08-24 13:23:49.641  3010  3856 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 13:23:49.692  1529  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 13:23:49.692  1529  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 13:23:49.692  1529  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 13:23:49.692  1529  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:23:49.709  3010  3856 E KeepSync: IOException
08-24 13:23:49.709  3010  3856 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 13:23:49.709  3010  3856 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 13:23:49.709  3010  3856 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 13:23:49.709  3010  3856 E KeepSync: 	... 10 more
,08-24 13:23:49.709  3010  3856 W KeepSync: Sync result 2
,08-24 13:23:49.722   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 125429, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 13:23:51.403   873  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-24 13:23:56.813  3804  3854 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 13:23:56.813  3804  3854 I jxcore-log: 
,08-24 13:23:56.815  3804  3854 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 13:23:56.815  3804  3854 I jxcore-log: 
,08-24 13:23:56.827  3804  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:23:56.827  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:23:56.827  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-24 13:23:56.827  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:23:56.827  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:23:56.827  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:23:56.827  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:23:56.827  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-24 13:23:56.833  3804  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-24 13:23:56.839  3804  3854 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 13:23:56.839  3804  3854 I jxcore-log: 
,08-24 13:23:56.846  3804  3854 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 13:23:56.846  3804  3854 I jxcore-log: 
,08-24 13:23:57.374  3804  3854 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-24 13:23:57.375  3804  3854 I jxcore-log: Failed to execute UT.
08-24 13:23:57.375  3804  3854 I jxcore-log: 
,08-24 13:23:57.376  3804  3854 I jxcore-log: Unit Test app is loaded
08-24 13:23:57.376  3804  3854 I jxcore-log: 
,08-24 13:23:57.381  3804  3854 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 13:23:57.381  3804  3854 I jxcore-log: 
,08-24 13:23:57.388  3804  3854 I jxcore-log: My device name is: motorola-Nexus 6
08-24 13:23:57.388  3804  3854 I jxcore-log: 
,08-24 13:23:57.390  3804  3854 I jxcore-log: WARN testUtils: myNameCallback not set!
08-24 13:23:57.390  3804  3854 I jxcore-log: 
,08-24 13:23:57.408  3804  3804 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-24 13:24:01.460  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 13:24:01.460  3804  3854 I jxcore-log: 
,08-24 13:24:02.390  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 13:24:02.390  3804  3854 I jxcore-log: 
,08-24 13:24:02.416  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 13:24:02.416  3804  3854 I jxcore-log: 
,08-24 13:24:02.421  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 13:24:02.421  3804  3854 I jxcore-log: 
,08-24 13:24:02.446  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 13:24:02.446  3804  3854 I jxcore-log: 
,08-24 13:24:02.451  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 13:24:02.451  3804  3854 I jxcore-log: 
,08-24 13:24:03.994  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:04.008  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:04.012  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:04.045  1529  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 13:24:04.045  1529  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 13:24:04.046  1529  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:04.046  1529  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:04.092  3509  3509 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-24 13:24:04.092  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-24 13:24:04.093  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-24 13:24:05.788  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 13:24:05.788  3804  3854 I jxcore-log: 
,08-24 13:24:05.799  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 13:24:05.799  3804  3854 I jxcore-log: 
,08-24 13:24:05.808  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 13:24:05.808  3804  3854 I jxcore-log: 
,08-24 13:24:05.999  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 13:24:05.999  3804  3854 I jxcore-log: 
,08-24 13:24:06.818  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 13:24:06.818  3804  3854 I jxcore-log: 
,08-24 13:24:07.056  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 13:24:07.056  3804  3854 I jxcore-log: 
,08-24 13:24:07.063  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 13:24:07.063  3804  3854 I jxcore-log: 
,08-24 13:24:07.257  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 13:24:07.257  3804  3854 I jxcore-log: 
,08-24 13:24:07.278  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 13:24:07.278  3804  3854 I jxcore-log: 
,08-24 13:24:07.283  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 13:24:07.283  3804  3854 I jxcore-log: 
,08-24 13:24:07.289  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 13:24:07.289  3804  3854 I jxcore-log: 
,08-24 13:24:07.305  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 13:24:07.305  3804  3854 I jxcore-log: 
,08-24 13:24:07.324  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 13:24:07.324  3804  3854 I jxcore-log: 
,08-24 13:24:07.405  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 13:24:07.405  3804  3854 I jxcore-log: 
,08-24 13:24:07.411  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 13:24:07.411  3804  3854 I jxcore-log: 
,08-24 13:24:07.438  3804  3854 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 13:24:07.438  3804  3854 I jxcore-log: 
,08-24 13:24:07.453  3804  3854 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-24 13:24:07.455  3804  3854 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-24 13:24:07.455  3804  3854 I jxcore-log: 
,08-24 13:24:13.450   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-24 13:24:13.466  1849  1849 I Keyboard.Facilitator: onFinishInput()
,08-24 13:24:13.479   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-24 13:24:13.479   873   893 I Adreno  : Build Date                       : 10/20/15
08-24 13:24:13.479   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-24 13:24:13.479   873   893 I Adreno  : Local Branch                     : M14
08-24 13:24:13.479   873   893 I Adreno  : Remote Branch                    : 
08-24 13:24:13.479   873   893 I Adreno  : Remote Branch                    : 
08-24 13:24:13.479   873   893 I Adreno  : Reconstruct Branch               : 
,08-24 13:24:13.513   281   359 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (172 us)
,08-24 13:24:14.130  3804  3804 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-24 13:24:14.130  3804  3804 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-24 13:24:14.179   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-24 13:24:14.183  3804  3804 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@18f131d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2acaf43, 16908290=android.view.AbsSavedState$1@2acaf43}, android:focusedViewId=100}]}]
,08-24 13:24:14.183  3804  3804 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-24 13:24:14.185  3804  3804 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-24 13:24:14.186  3804  3804 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-24 13:24:14.192   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-24 13:24:14.196   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-24 13:24:14.198   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
08-24 13:24:14.198   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-24 13:24:14.424   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-24 13:24:14.429   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-24 13:24:14.435   873  1330 D SurfaceControl: Excessive delay in setPowerMode(): 238ms
,08-24 13:24:14.442   873   893 I DreamManagerService: Entering dreamland.
,08-24 13:24:14.443   873   893 I PowerManagerService: Dozing...
,08-24 13:24:14.445   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-24 13:24:14.530   376  1313 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-24 13:24:14.531   376  1313 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-24 13:24:14.546   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 13:24:14.568   873  1305 E native  : do suspend false
,08-24 13:24:14.571  1897  3872 D NfcService: Discovery configuration equal, not updating.
,08-24 13:24:14.593   873  1305 D WifiConfigStore: No blacklist allowed without epno enabled
,08-24 13:24:14.624   873  1305 D WifiConfigStore: Retrieve network priorities after PNO.
,08-24 13:24:14.632   873  1305 E native  : do suspend true
,08-24 13:24:14.655   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-24 13:24:14.656   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-24 13:24:15.053   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-24 13:24:19.742  2136  2646 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 13:24:21.233  3751  3877 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 13:24:21.283  3751  3878 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 13:24:21.309  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:21.315  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:21.399  1529  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 13:24:21.400  1529  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 13:24:21.400  1529  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:21.401  1529  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:21.486  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:21.495  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:21.576  1529  1547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 13:24:21.577  1529  1547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 13:24:21.578  1529  1547 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:21.578  1529  1547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:21.636  3751  3878 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 13:24:21.641  3751  3877 E BooksSync: Soft error
08-24 13:24:21.641  3751  3877 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 13:24:21.641  3751  3877 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 13:24:21.642  3751  3877 E BooksSync: Sync error
08-24 13:24:21.642  3751  3877 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 13:24:21.642  3751  3877 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 13:24:21.642  3751  3877 I BooksSync: Finished books sync
,08-24 13:24:21.656   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157484, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 13:24:24.305   873  1690 I ActivityManager: Start proc 3880:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-24 13:24:24.323  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:24.352  3880  3880 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-24 13:24:24.407  3880  3892 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-24 13:24:24.414   873   884 I ActivityManager: Start proc 3898:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,08-24 13:24:24.437  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:24.446  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:24.448  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:24.450  3898  3898 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-24 13:24:24.466  1529  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 13:24:24.466  1529  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-24 13:24:24.466  1529  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:24.467  1529  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:24.482  3509  3509 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 13:24:24.482  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-24 13:24:24.483  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-24 13:24:24.489  3898  3898 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-24 13:24:24.490  3880  3892 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-24 13:24:24.517  3880  3892 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-24 13:24:24.537  3898  3926 V GoogleAuthProtoRequest: [325] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 13:24:24.557  3930  3930 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads139633108.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads139633108.dex
,08-24 13:24:24.559  1529  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-24 13:24:24.559  1529  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 13:24:24.559  1529  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:24.559  1529  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:24.565  3880  3880 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 13:24:24.572  3898  3926 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 13:24:24.575   873  3114 I ActivityManager: Killing 3049:com.google.android.talk/u0a61 (adj 15): empty #17
,08-24 13:24:24.602  3930  3930 I dex2oat : dex2oat took 45.448ms (threads: 4) arena alloc=347KB java alloc=29KB native alloc=1642KB free=1685KB
,08-24 13:24:24.725  3880  3880 W InstanceID/Rpc: Found 10011
,08-24 13:24:24.786   873  2013 I ActivityManager: Killing 3565:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-24 13:24:24.943  1529  3987 I VacuumService: Vacuum at: now=1472037864943 tag=VacuumService
,08-24 13:24:25.113  1529  3988 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-24 13:24:25.116  1529  3988 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-24 13:24:25.176  1529  3988 W Uploader:  no longer exists, so no auth token.
,08-24 13:24:25.768   873  1305 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-24 13:24:26.651  1529  3988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-24 13:24:26.651  1529  3988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-24 13:24:26.652  1529  3988 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:26.652  1529  3988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:26.676  1529  3988 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 13:24:26.676  1529  3988 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 13:24:26.676  1529  3988 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 13:24:27.041  1529  3988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-24 13:24:27.041  1529  3988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-24 13:24:27.042  1529  3988 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:27.042  1529  3988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:27.062  1529  3988 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 13:24:27.062  1529  3988 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 13:24:27.062  1529  3988 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 13:24:27.925  1529  3988 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-24 13:24:27.925  1529  3988 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-24 13:24:27.925  1529  3988 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:27.925  1529  3988 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:27.946  1529  3988 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 13:24:27.946  1529  3988 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-24 13:24:27.946  1529  3988 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-24 13:24:29.831   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 13:24:51.968  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:51.973  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:52.009  1529  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 13:24:52.010  1529  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 13:24:52.010  1529  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:52.010  1529  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:52.049  3546  4004 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 13:24:52.049  3546  4004 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at jdm.a(PG:82)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at jcs.o(PG:406)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at jcn.a(PG:1379)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at jcs.i(PG:143)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at blb.a(PG:3937)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at czp.a(PG:18188)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at czp.a(PG:9081)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at czq.run(PG:1686)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:24:52.049  3546  4004 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at jdj.a(PG:4091)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at jdj.a(PG:1125)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at jdm.a(PG:77)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	... 12 more
08-24 13:24:52.049  3546  4004 E HttpOperation: Caused by: faj: BadAuthentication
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at fal.a(PG:38)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	at jdj.a(PG:4089)
08-24 13:24:52.049  3546  4004 E HttpOperation: 	... 14 more
,08-24 13:24:52.111  1529  1547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 13:24:52.111  1529  1547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 13:24:52.111  1529  1547 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:52.111  1529  1547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:52.128  3546  4004 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 13:24:52.128  3546  4004 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at jdm.a(PG:82)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at jcs.o(PG:406)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at jcn.a(PG:1379)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at jcs.i(PG:143)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at hec.a(PG:42)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at hee.a(PG:102)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at czr.a(PG:65)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at kka.a(PG:108)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at czp.a(PG:19176)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at czp.a(PG:9081)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at czq.run(PG:1686)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:24:52.128  3546  4004 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at jdj.a(PG:4091)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at jdj.a(PG:1125)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at jdm.a(PG:77)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	... 15 more
08-24 13:24:52.128  3546  4004 E HttpOperation: Caused by: faj: BadAuthentication
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at fal.a(PG:38)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	at jdj.a(PG:4089)
08-24 13:24:52.128  3546  4004 E HttpOperation: 	... 17 more
,08-24 13:24:52.128  3546  4004 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 13:24:52.128  3546  4004 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at hec.a(PG:42)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at hee.a(PG:102)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at czr.a(PG:65)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at kka.a(PG:108)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	... 15 more
08-24 13:24:52.128  3546  4004 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at fal.a(PG:38)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 13:24:52.128  3546  4004 E ExperimentLoader: 	... 17 more
,08-24 13:24:52.242   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 161101, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 13:24:58.333  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:58.335  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:58.350  3898  4007 V GoogleAuthProtoRequest: [326] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 13:24:58.392  1529  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-24 13:24:58.392  1529  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-24 13:24:58.392  1529  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 13:24:58.392  1529  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 13:24:58.415  3898  4007 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 13:24:58.488  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:24:58.521  1529  2366 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-24 13:24:58.521  1529  2366 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-24 13:24:58.521  1529  2366 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:24:58.521  1529  2366 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:24:58.542  3509  3509 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-24 13:24:58.542  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-24 13:24:58.542  3509  3509 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-24 13:25:12.739   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:25:13.507  1849  1893 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-24 13:25:13.507  1849  1893 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-24 13:25:13.536  1529  1529 I ConfigService: onCreate
,08-24 13:25:18.573  1529  1529 I ConfigService: onDestroy
,08-24 13:25:51.198  3010  4012 V KeepSync: Connecting to GoogleApiClient
08-24 13:25:51.199   873  2104 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 13:25:51.262  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:25:51.264  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:25:51.297  1529  1547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-24 13:25:51.297  1529  1547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-24 13:25:51.297  1529  1547 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:25:51.298  1529  1547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:25:51.319  1744  4013 V BaseAuthAsyncOperation: access token request failed
,08-24 13:25:51.320  3010  4012 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-24 13:25:51.380  1529  2366 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-24 13:25:51.380  1529  2366 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 13:25:51.380  1529  2366 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:25:51.380  1529  2366 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:25:51.406  3010  4012 E KeepSync: IOException
08-24 13:25:51.406  3010  4012 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 13:25:51.406  3010  4012 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 13:25:51.406  3010  4012 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 13:25:51.406  3010  4012 E KeepSync: 	... 10 more
08-24 13:25:51.406  3010  4012 W KeepSync: Sync result 2
,08-24 13:25:51.422   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 247345, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 13:25:58.556  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:25:58.557  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:25:58.574  3898  4015 V GoogleAuthProtoRequest: [327] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 13:25:58.600  1529  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-24 13:25:58.601  1529  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 13:25:58.601  1529  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:25:58.601  1529  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:25:58.622  3898  4015 W ExperimentUpdateService: [327] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: [327] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 13:25:58.623  3898  4015 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 13:26:11.139   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 13:26:51.638  3751  4022 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 13:26:51.671  3751  4023 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 13:26:51.684  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:26:51.686  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:26:51.711  1529  2124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 13:26:51.711  1529  2124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 13:26:51.711  1529  2124 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:26:51.712  1529  2124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:26:51.740  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:26:51.746  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:26:51.773  1529  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 13:26:51.774  1529  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 13:26:51.774  1529  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:26:51.774  1529  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:26:51.795  3751  4023 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 13:26:51.796  3751  4022 E BooksSync: Soft error
08-24 13:26:51.796  3751  4022 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 13:26:51.796  3751  4022 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 13:26:51.796  3751  4022 E BooksSync: Sync error
08-24 13:26:51.796  3751  4022 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 13:26:51.796  3751  4022 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 13:26:51.796  3751  4022 I BooksSync: Finished books sync
,08-24 13:26:51.810   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 281728, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 13:26:55.778   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=312157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:27:08.885   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 13:27:22.257  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:27:22.259  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:27:22.293  1529  1547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 13:27:22.293  1529  1547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 13:27:22.293  1529  1547 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:27:22.293  1529  1547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:27:22.311  3546  4026 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 13:27:22.311  3546  4026 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at jdm.a(PG:82)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at jcs.o(PG:406)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at jcn.a(PG:1379)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at jcs.i(PG:143)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at blb.a(PG:3937)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at czp.a(PG:18188)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at czp.a(PG:9081)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at czq.run(PG:1686)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:27:22.311  3546  4026 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at jdj.a(PG:4091)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at jdj.a(PG:1125)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at jdm.a(PG:77)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	... 12 more
08-24 13:27:22.311  3546  4026 E HttpOperation: Caused by: faj: BadAuthentication
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at fal.a(PG:38)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	at jdj.a(PG:4089)
08-24 13:27:22.311  3546  4026 E HttpOperation: 	... 14 more
,08-24 13:27:22.367  1529  2124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 13:27:22.367  1529  2124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-24 13:27:22.367  1529  2124 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:27:22.367  1529  2124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:27:22.413  3546  4026 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 13:27:22.413  3546  4026 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at jdm.a(PG:82)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at jcs.o(PG:406)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at jcn.a(PG:1379)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at jcs.i(PG:143)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at hec.a(PG:42)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at hee.a(PG:102)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at czr.a(PG:65)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at kka.a(PG:108)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at czp.a(PG:19176)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at czp.a(PG:9081)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at czq.run(PG:1686)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:27:22.413  3546  4026 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at jdj.a(PG:4091)
,08-24 13:27:22.413  3546  4026 E HttpOperation: 	at jdj.a(PG:1125)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at jdm.a(PG:77)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	... 15 more
08-24 13:27:22.413  3546  4026 E HttpOperation: Caused by: faj: BadAuthentication
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at fal.a(PG:38)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	at jdj.a(PG:4089)
08-24 13:27:22.413  3546  4026 E HttpOperation: 	... 17 more
08-24 13:27:22.414  3546  4026 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 13:27:22.414  3546  4026 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at hec.a(PG:42)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at hee.a(PG:102)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at czr.a(PG:65)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at kka.a(PG:108)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 13:27:22.414  3546  4026 E ExperimentLoader: ,	at jdj.a(PG:4091)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	... 15 more
08-24 13:27:22.414  3546  4026 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at fal.a(PG:38)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 13:27:22.414  3546  4026 E ExperimentLoader: 	... 17 more
,08-24 13:27:22.586   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 319450, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 13:27:25.377  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:27:25.476  1529  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-24 13:27:25.476  1529  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-24 13:27:25.477  1529  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:27:25.477  1529  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:27:25.527  1529  2423 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-24 13:27:25.527  1529  2423 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-24 13:27:25.527  1529  2423 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-24 13:27:25.527  1529  2423 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-24 13:27:25.527  1529  2423 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-24 13:27:25.527  1529  2423 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-24 13:27:25.527  1529  2423 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-24 13:27:25.543  3509  3538 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-24 13:27:25.543  3509  3538 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-24 13:27:25.543  3509  3538 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-24 13:27:25.543  3509  3538 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-24 13:27:25.543  3509  3538 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-24 13:27:25.543  3509  3538 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-24 13:27:25.543  3509  3538 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-24 13:27:58.760  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:27:58.762  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:27:58.775  3898  4037 V GoogleAuthProtoRequest: [328] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 13:27:58.802  1529  2124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-24 13:27:58.802  1529  2124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 13:27:58.802  1529  2124 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:27:58.802  1529  2124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:27:58.816  3898  4037 W ExperimentUpdateService: [328] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: [328] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 13:27:58.817  3898  4037 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 13:28:10.391   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=386770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:28:33.299   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 13:29:17.859   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=454237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:29:33.125   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=469504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 13:29:54.165  3010  4044 V KeepSync: Connecting to GoogleApiClient
08-24 13:29:54.166   873  2014 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-24 13:29:54.217  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:29:54.220  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:29:54.256  1529  1547 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-24 13:29:54.256  1529  1547 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-24 13:29:54.256  1529  1547 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:29:54.256  1529  1547 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:29:54.277  1744  4045 V BaseAuthAsyncOperation: access token request failed
,08-24 13:29:54.279  3010  4044 V KeepSync: GoogleApiClient failed to connect with error code: 4,
,08-24 13:29:54.348  1529  2124 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-24 13:29:54.349  1529  2124 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-24 13:29:54.349  1529  2124 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-24 13:29:54.349  1529  2124 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:29:54.385  3010  4044 E KeepSync: IOException
08-24 13:29:54.385  3010  4044 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-24 13:29:54.385  3010  4044 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-24 13:29:54.385  3010  4044 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-24 13:29:54.385  3010  4044 E KeepSync: 	... 10 more
08-24 13:29:54.385  3010  4044 W KeepSync: Sync result 2
,08-24 13:29:54.402   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 490290, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 13:30:17.805   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=514184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:30:59.367  3751  4049 I BooksSync: Starting books sync for 61035162, extras: ade
,08-24 13:30:59.409  3751  4050 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-24 13:30:59.420  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:30:59.422  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:30:59.457  1529  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-24 13:30:59.457  1529  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 13:30:59.457  1529  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:30:59.457  1529  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:30:59.487  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:30:59.490  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:30:59.521  1529  2366 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-24 13:30:59.521  1529  2366 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-24 13:30:59.522  1529  2366 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:30:59.522  1529  2366 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:30:59.548  3751  4050 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-24 13:30:59.549  3751  4049 E BooksSync: Soft error,
08-24 13:30:59.549  3751  4049 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 13:30:59.549  3751  4049 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-24 13:30:59.549  3751  4049 E BooksSync: Sync error
08-24 13:30:59.549  3751  4049 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-24 13:30:59.549  3751  4049 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-24 13:30:59.549  3751  4049 I BooksSync: Finished books sync
,08-24 13:30:59.561   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 555574, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 13:31:31.072   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 13:31:44.516  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:31:44.521  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:31:44.553  1529  2366 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-24 13:31:44.553  1529  2366 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 13:31:44.553  1529  2366 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:31:44.553  1529  2366 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:31:44.579  3546  4053 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-24 13:31:44.579  3546  4053 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at jdm.a(PG:82)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at jcs.o(PG:406)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at jcn.a(PG:1379)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at jcs.i(PG:143)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at blb.a(PG:3937)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at czp.a(PG:18188)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at czp.a(PG:9081)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at czq.run(PG:1686)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:31:44.579  3546  4053 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at jdj.a(PG:4091)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at jdj.a(PG:1125)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at jdm.a(PG:77)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	... 12 more
08-24 13:31:44.579  3546  4053 E HttpOperation: Caused by: faj: BadAuthentication
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at fal.a(PG:38)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	at jdj.a(PG:4089)
08-24 13:31:44.579  3546  4053 E HttpOperation: 	... 14 more
,08-24 13:31:44.671  1529  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-24 13:31:44.671  1529  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-24 13:31:44.671  1529  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
08-24 13:31:44.671  1529  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:31:44.689  3546  4053 E HttpOperation: [getmobileexperiments] Unexpected exception
08-24 13:31:44.689  3546  4053 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at jdm.a(PG:82)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at jcs.o(PG:406)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at jcn.a(PG:1379)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at jcs.i(PG:143)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at hec.a(PG:42)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at hee.a(PG:102)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at czr.a(PG:65)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at kka.a(PG:108)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at czp.a(PG:19176)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at czp.a(PG:9081)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at czq.run(PG:1686)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:31:44.689  3546  4053 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at jdj.a(PG:4091)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at jdj.a(PG:1125)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at jdm.a(PG:77)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	... 15 more
08-24 13:31:44.689  3546  4053 E HttpOperation: Caused by: faj: BadAuthentication
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at fal.a(PG:38)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	at jdj.a(PG:4089)
08-24 13:31:44.689  3546  4053 E HttpOperation: 	... 17 more
,08-24 13:31:44.690  3546  4053 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-24 13:31:44.690  3546  4053 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at jdm.a(PG:82)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at jcs.o(PG:406)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at jcn.a(PG:1379)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at jcs.i(PG:143)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at hec.a(PG:42)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at hee.a(PG:102)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at czr.a(PG:65)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at kka.a(PG:108)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at czp.a(PG:19176)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at czp.a(PG:9081)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at czq.run(PG:1686)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at jdj.a(PG:4091)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at jdj.a(PG:1125)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at jdm.a(PG:77)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	... 15 more
08-24 13:31:44.690  3546  4053 E ExperimentLoader: Caused by: faj: BadAuthentication
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at fal.a(PG:38)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	at jdj.a(PG:4089)
08-24 13:31:44.690  3546  4053 E ExperimentLoader: 	... 17 more
,08-24 13:31:44.824   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 600622, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-24 13:31:54.380  1529  2220 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 13:31:58.738  1744  4056 I EventLogService: Opted in for usage reporting
,08-24 13:31:58.757  1744  4056 I EventLogService: Aggregate from 1472036446315 (log), 1472036446315 (data)
,08-24 13:31:58.848  1744  4056 W EventLogAggregator: Unknown tag: snet_gcore
08-24 13:31:58.848  1744  4056 W EventLogAggregator: Unknown tag: snet_launch_service
,08-24 13:31:58.904  1744  4056 I ServiceDumpSys: dumping service [account]
,08-24 13:32:15.778   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=632157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:32:28.888  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:32:28.890  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:32:28.901  3898  4065 V GoogleAuthProtoRequest: [329] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 13:32:28.921  1529  2423 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-24 13:32:28.922  1529  2423 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 13:32:28.922  1529  2423 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 13:32:28.922  1529  2423 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:32:28.936  3898  4065 W ExperimentUpdateService: [329] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: [329] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 13:32:28.937  3898  4065 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 13:32:30.845   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-24 13:33:15.513   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=691891, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:40:03.818   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1100197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-24 13:40:12.525   873  1870 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1108904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-24 13:40:29.150  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:40:29.152  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-24 13:40:29.164  3898  4091 V GoogleAuthProtoRequest: [330] a.<init>: mAccountName set to: thalitester@gmail.com
,08-24 13:40:29.192  1529  2366 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-24 13:40:29.192  1529  2366 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-24 13:40:29.192  1529  2366 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-24 13:40:29.192  1529  2366 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: [330] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: [330] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-24 13:40:29.209  3898  4091 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-24 13:42:01.787   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),08-24 13:47:15.492  4108  4108 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-24 13:47:15.496  4108  4108 D AndroidRuntime: CheckJNI is OFF
08-24 13:47:15.532  4108  4108 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-24 13:47:15.578  4108  4108 I Radio-JNI: register_android_hardware_Radio DONE
08-24 13:47:15.598  4108  4108 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-24 13:47:15.611   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-24 13:47:15.612   873   886 I ActivityManager: Killing 3804:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-24 13:47:15.717   873  1372 D GraphicsStats: Buffer count: 2
08-24 13:47:15.717   873  1972 I WindowState: WIN DEATH: Window{2334330 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 13:47:15.718   873  1306 D WifiService: Client connection lost with reason: 4
08-24 13:47:15.741   873   896 W PackageSettings: Skipping PackageSetting{3207a0a com.example.hello/10273} due to missing metadata
08-24 13:47:15.771   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-24 13:47:15.772   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-24 13:47:15.772   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-24 13:47:15.772   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-24 13:47:15.772   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:47:15.772   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:47:15.772   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:47:15.772   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 13:47:15.773   873   886 I ActivityManager:   Force finishing activity ActivityRecord{50f2491 u0 com.test.thalitest/.MainActivity t2}
08-24 13:47:15.773   873   896 I art     : Starting a blocking GC Explicit
08-24 13:47:15.785   873  1373 W ActivityManager: Spurious death for ProcessRecord{cc8b30f 0:com.test.thalitest/u0a0}, curProc for 3804: null
08-24 13:47:15.835   873   896 I art     : Explicit concurrent mark sweep GC freed 19133(1347KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 811us total 60.670ms
08-24 13:47:15.857   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-24 13:47:15.862  4108  4108 I art     : System.exit called, status: 0
08-24 13:47:15.862  4108  4108 I AndroidRuntime: VM exiting with result code 0.
08-24 13:47:15.863   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-24 13:47:15.884   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-24 13:47:15.888  2684  2684 D BluetoothMapAppObserver: onReceive
08-24 13:47:15.888  2684  2684 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-24 13:47:15.889  2136  2298 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 13:47:15.890   873  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 13:47:15.896  3639  3639 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-24 13:47:15.897  1849  1849 I Keyboard.Facilitator: resetDictionaries() : en_US
08-24 13:47:15.911  1849  4119 I Keyboard.Facilitator.DecoderInitializer: run()
08-24 13:47:15.913  1849  4119 I Decoder : createOrResetDecoder
08-24 13:47:15.930  1915  1915 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-24 13:47:15.940  1529  1529 I ConfigService: onCreate
08-24 13:47:15.944  3492  4122 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 13:47:15.967  1849  4119 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-24 13:47:15.987  3492  4122 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
--------- beginning of crash
08-24 13:47:15.988  3492  4122 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-24 13:47:15.988  3492  4122 E AndroidRuntime: Process: android.process.acore, PID: 3492
08-24 13:47:15.988  3492  4122 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:47:15.988  3492  4122 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:47:15.991  3492  4122 I Process : Sending signal. PID: 3492 SIG: 9
08-24 13:47:15.995   873  4127 E DropBoxManagerService: Can't write: system_app_crash
08-24 13:47:15.995   873  4127 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 13:47:15.995   873  4127 E DropBoxManagerService: 	... 5 more
08-24 13:47:16.001  1529  1529 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-24 13:47:16.002   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 13:47:16.004  1529  1529 D AndroidRuntime: Shutting down VM
08-24 13:47:16.005  1529  1529 E AndroidRuntime: FATAL EXCEPTION: main
08-24 13:47:16.005  1529  1529 E AndroidRuntime: Process: com.google.process.gapps, PID: 1529
08-24 13:47:16.005  1529  1529 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-24 13:47:16.005  1529  1529 E AndroidRuntime: 	... 8 more
08-24 13:47:16.008  1529  1529 I Process : Sending signal. PID: 1529 SIG: 9
08-24 13:47:16.008   873  4129 E DropBoxManagerService: Can't write: system_app_crash
08-24 13:47:16.008   873  4129 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 13:47:16.008   873  4129 E DropBoxManagerService: 	... 5 more
08-24 13:47:16.015  1932  2019 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-24 13:47:16.018   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-24 13:47:16.018   873   885 E PackageManager: Failed to write settings, restoring backup
08-24 13:47:16.018   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-24 13:47:16.018   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-24 13:47:16.018   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-24 13:47:16.018   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-24 13:47:16.018   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-24 13:47:16.018   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:47:16.018   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:47:16.018   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:47:16.021   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-24 13:47:16.021   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-24 13:47:16.021   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 13:47:16.021   873   886 E DropBoxManagerService: 	... 13 more
08-24 13:47:16.023  1849  4119 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-24 13:47:16.025  1849  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-24 13:47:16.025  1849  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-24 13:47:16.027   873  2108 I ActivityManager: Start proc 4130:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-24 13:47:16.028  1932  2019 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-24 13:47:16.028  1932  2019 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1932
08-24 13:47:16.028  1932  2019 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:47:16.028  1932  2019 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:47:16.029   873  2104 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-24 13:47:16.030   873  4136 E DropBoxManagerService: Can't write: system_app_crash
08-24 13:47:16.030   873  4136 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 13:47:16.030   873  4136 E DropBoxManagerService: 	... 5 more
08-24 13:47:16.032  1932  2019 I Process : Sending signal. PID: 1932 SIG: 9
08-24 13:47:16.037  1849  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-24 13:47:16.037  1849  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-24 13:47:16.038  1849  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-24 13:47:16.038  1849  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-24 13:47:16.038  1849  4119 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-24 13:47:16.038  1849  4119 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-24 13:47:16.039  1849  4119 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-24 13:47:16.039  1849  4119 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-24 13:47:16.039  1849  4119 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-24 13:47:16.039  1849  4119 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-24 13:47:16.046   873  2013 I ActivityManager: Process android.process.acore (pid 3492) has died
08-24 13:47:16.047   873  2013 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-24 13:47:16.093   873  1306 D WifiService: Client connection lost with reason: 4
08-24 13:47:16.104   873  2013 D GraphicsStats: Buffer count: 1
08-24 13:47:16.104   873  2104 I WindowState: WIN DEATH: Window{c30f718 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-24 13:47:16.108   873  3114 I ActivityManager: Process com.google.process.gapps (pid 1529) has died
08-24 13:47:16.108   873  3114 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-24 13:47:16.108   873  3114 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-24 13:47:16.108   873  3114 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-24 13:47:16.108   873  3114 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 30999ms
08-24 13:47:16.125   873  2099 I ActivityManager: Start proc 4144:com.google.process.gapps/u0a11 for service com.google.android.gms/.gcm.http.GoogleHttpService
08-24 13:47:16.125   873  2013 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1932) has died
08-24 13:47:16.126   873  2013 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 30982ms
08-24 13:47:16.136  1744  1744 W RocketImpressions: ClearcutLogger connection suspended: 1
08-24 13:47:16.176  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-24 13:47:16.176  1744  1744 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-24 13:47:16.183  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-24 13:47:16.183  1744  1744 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-24 13:47:16.193  1744  4161 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-24 13:47:16.201  4144  4144 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-24 13:47:16.205   873  1972 I ActivityManager: Start proc 4163:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
08-24 13:47:16.207  1979  4160 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-24 13:47:16.230  1744  4161 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-24 13:47:16.230  1744  4161 E AndroidRuntime: Process: com.google.android.gms, PID: 1744
08-24 13:47:16.230  1744  4161 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-24 13:47:16.230  1744  4161 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-24 13:47:16.232  1744  4161 I Process : Sending signal. PID: 1744 SIG: 9
08-24 13:47:16.234   873  4175 E DropBoxManagerService: Can't write: system_app_crash
08-24 13:47:16.234   873  4175 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 13:47:16.234   873  4175 E DropBoxManagerService: 	... 5 more
08-24 13:47:16.249  1979  4160 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-24 13:47:16.267  4144  4144 I MultiDex: VM with version 2.1.0 has multidex support
08-24 13:47:16.275   279   279 E lowmemorykiller: Error writing /proc/1744/oom_score_adj; errno=22
08-24 13:47:16.278  4144  4144 I MultiDex: install
08-24 13:47:16.279  4144  4144 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-24 13:47:16.280  1979  4160 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-24 13:47:16.281  1979  4160 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-24 13:47:16.281  1979  4160 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1979
08-24 13:47:16.281  1979  4160 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:47:16.281  1979  4160 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 13:47:16.283   873  1690 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-24 13:47:16.284   873  1690 I ActivityManager: Killing 1979:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
08-24 13:47:16.287   873  4176 E DropBoxManagerService: Can't write: system_app_crash
08-24 13:47:16.287   873  4176 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-24 13:47:16.287   873  4176 E DropBoxManagerService: 	... 5 more
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-24 13:47:16.321  4163  4163 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-24 13:47:16.321  4163  4163 D AndroidRuntime: Shutting down VM
08-24 13:47:16.343   873  2099 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@3e41b66)
08-24 13:47:16.347   873  1307 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 13:47:16.349   873  1307 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-24 13:47:16.354  4130  4156 W GmsClient: service died
08-24 13:47:16.362   873  1306 D WifiService: Client connection lost with reason: 4
08-24 13:47:16.362  4130  4130 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
08-24 13:47:16.369   873  1690 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-24 13:47:16.373   279   279 E lowmemorykiller: Error opening /proc/1744/oom_score_adj; errno=2

```
