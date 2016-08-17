#### Test 79426650471aed9_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-17 10:40:36.742  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 10:40:36.749  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 10:40:36.751  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 10:40:36.788  1513  2257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-17 10:40:36.788  1513  2257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 10:40:36.788  1513  2257 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:40:36.788  1513  2257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:40:36.812  3480  3480 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 10:40:36.812  3480  3480 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 10:40:36.813  3480  3480 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-17 10:40:37.012   873  1306 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-17 10:40:37.435   873  1853 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-17 10:40:37.440  3749  3749 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-17 10:40:37.445  3749  3749 D AndroidRuntime: CheckJNI is OFF
08-17 10:40:37.480  3749  3749 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-17 10:40:37.526  3749  3749 I Radio-JNI: register_android_hardware_Radio DONE
08-17 10:40:37.546  3749  3749 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 10:40:37.551   873  1371 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 10:40:37.600  1992  2004 W SearchService: Abort, client detached.
08-17 10:40:37.608  1992  1992 I HotwordDetector: Closing mic
08-17 10:40:37.608  1992  2315 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@39cd087
08-17 10:40:37.609  1992  2329 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-17 10:40:37.613  3749  3749 D AndroidRuntime: Shutting down VM
08-17 10:40:37.625   873  1901 I ActivityManager: Start proc 3758:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-17 10:40:37.664   376  2331 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-17 10:40:37.664   376  2331 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-17 10:40:37.669   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-17 10:40:37.672  1992  2322 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-17 10:40:37.672  1992  2326 I MicroRecognitionRnrImpl: Detection finished
08-17 10:40:37.709  3758  3758 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-17 10:40:37.738  3758  3758 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-17 10:40:37.746  3758  3758 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3451-3454)
08-17 10:40:37.747  3758  3758 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 10:40:37.761  3758  3758 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8837316}
08-17 10:40:37.762  3758  3758 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 10:40:37.762  3758  3758 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 10:40:37.767  3758  3758 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 10:40:37.768  3758  3758 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 10:40:37.783  3758  3758 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-17 10:40:37.792  3758  3758 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 10:40:37.792  3758  3758 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 10:40:37.792  3758  3758 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 10:40:37.792  3758  3758 I Adreno  : Build Date                       : 10/20/15
08-17 10:40:37.792  3758  3758 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 10:40:37.792  3758  3758 I Adreno  : Local Branch                     : M14
08-17 10:40:37.792  3758  3758 I Adreno  : Remote Branch                    : 
08-17 10:40:37.792  3758  3758 I Adreno  : Remote Branch                    : 
08-17 10:40:37.792  3758  3758 I Adreno  : Reconstruct Branch               : 
08-17 10:40:37.839   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@579d083:true
,08-17 10:40:37.918  3758  3758 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 10:40:37.935  3758  3758 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-17 10:40:38.053  3758  3799 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-17 10:40:38.061  3758  3784 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-17 10:40:38.107  3758  3799 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 10:40:38.205   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +593ms
,08-17 10:40:38.216  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-17 10:40:38.337  3758  3758 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3758
,08-17 10:40:38.457   873   884 I ActivityManager: Killing 3198:com.google.android.gm/u0a78 (adj 15): empty #17
,08-17 10:40:38.490   873   884 I ActivityManager: Killing 3097:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-17 10:40:38.500  3758  3758 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 10:40:38.755  3758  3801 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1682179792
,08-17 10:40:38.762  3758  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 10:40:38.762  3758  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 10:40:38.762  3758  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 10:40:38.762  3758  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 10:40:38.762  3758  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 10:40:38.762  3758  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6cb22ba added. We now have 1 listener(s)
,08-17 10:40:38.769  3758  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-17 10:40:38.770  3758  3801 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 10:40:38.771  3758  3801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:40:38.771  3758  3801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-17 10:40:38.775  3758  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f64d61 added. We now have 1 listener(s)
08-17 10:40:38.776  3758  3801 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:40:38.787   873  1307 D WifiService: New client listening to asynchronous messages
,08-17 10:40:38.792  3758  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:40:38.792  3758  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-17 10:40:38.792  3758  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-17 10:40:38.792  3758  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 10:40:38.792  3758  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 10:40:38.799  3758  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:40:38.800  3758  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-17 10:40:38.814  3758  3801 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-17 10:40:38.815  3758  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:40:38.815  3758  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:40:38.815  3758  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:40:38.815  3758  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:40:38.815  3758  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:40:38.815  3758  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:40:38.815  3758  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:40:38.815  3758  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:40:38.815  3758  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-17 10:40:38.815  3758  3801 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:40:38.815  3758  3801 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 10:40:38.967  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:40:38.971  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:40:38.973  3758  3758 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 10:40:39.340  3758  3767 I art     : Background sticky concurrent mark sweep GC freed 73756(6MB) AllocSpace objects, 17(1116KB) LOS objects, 27% free, 23MB/32MB, paused 673us total 112.955ms
,08-17 10:40:40.178  3758  3810 W jxcore-log: Initializing JXcore engine
,08-17 10:40:40.178  3758  3810 W jxcore-log: JXcore engine is ready
,08-17 10:40:40.216  3810  3810 W Thread-322: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8957 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-17 10:40:40.216  3810  3810 W Thread-322: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11605]" dev="sockfs" ino=11605 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-17 10:40:40.216  3810  3810 W Thread-322: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-17 10:40:40.216  3810  3810 W Thread-322: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26641]" dev="sockfs" ino=26641 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-17 10:40:40.233  3758  3810 W jxcore-log: Starting JXcore engine
,08-17 10:40:40.313  3758  3810 W jxcore-log: Platform android
08-17 10:40:40.313  3758  3810 W jxcore-log: 
,08-17 10:40:40.313  3758  3810 W jxcore-log: Process ARCH arm
08-17 10:40:40.313  3758  3810 W jxcore-log: 
,08-17 10:40:40.530  3758  3810 I jxcore-log: JXcore Cordova bridge is ready!
08-17 10:40:40.530  3758  3810 I jxcore-log: 
,08-17 10:40:40.531  3758  3810 W jxcore-log: JXcore engine is started
,08-17 10:40:40.543  3758  3801 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 10:40:40.550  3758  3758 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 10:40:44.031  3023  3818 V KeepSync: Connecting to GoogleApiClient
,08-17 10:40:44.033   873  1901 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 10:40:44.113  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:40:44.114  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:40:44.145  1513  2876 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 10:40:44.146  1513  2876 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 10:40:44.146  1513  2876 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:40:44.146  1513  2876 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:40:44.167  1731  3819 V BaseAuthAsyncOperation: access token request failed
,08-17 10:40:44.168  3023  3818 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 10:40:44.236  1513  3436 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-17 10:40:44.237  1513  3436 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-17 10:40:44.237  1513  3436 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:40:44.237  1513  3436 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:40:44.264  3023  3818 E KeepSync: IOException
08-17 10:40:44.264  3023  3818 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 10:40:44.264  3023  3818 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:40:44.264  3023  3818 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 10:40:44.264  3023  3818 E KeepSync: 	... 10 more
,08-17 10:40:44.264  3023  3818 W KeepSync: Sync result 2
,08-17 10:40:44.277   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129664, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:40:56.629  3758  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 10:40:56.629  3758  3810 I jxcore-log: 
,08-17 10:40:56.632  3758  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 10:40:56.632  3758  3810 I jxcore-log: 
,08-17 10:40:56.647  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:40:56.647  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:40:56.647  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:40:56.647  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:40:56.647  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:40:56.647  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:40:56.647  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:40:56.647  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:40:56.655  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:40:56.661  3758  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 10:40:56.661  3758  3810 I jxcore-log: 
,08-17 10:40:56.669  3758  3810 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 10:40:56.669  3758  3810 I jxcore-log: 
,08-17 10:40:57.019  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:40:57.025  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:40:57.029  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:40:57.055  1513  3436 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 10:40:57.055  1513  3436 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-17 10:40:57.056  1513  3436 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:40:57.056  1513  3436 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:40:57.069  3480  3480 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 10:40:57.069  3480  3480 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-17 10:40:57.069  3480  3480 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-17 10:40:57.110  3758  3810 I jxcore-log: Running unit tests
08-17 10:40:57.110  3758  3810 I jxcore-log: 
,08-17 10:40:57.111  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 10:40:57.111  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfe0b04 added. We now have 2 listener(s)
,08-17 10:40:57.112  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 10:40:57.112  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:40:57.112  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:40:57.113  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:40:57.113  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89e18ed added. We now have 2 listener(s)
08-17 10:40:57.113  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:40:57.113  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:40:57.117  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:40:57.121  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:40:57.121  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:40:57.121  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:40:57.121  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:40:57.121  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:40:57.121  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:40:57.121  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:40:57.121  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:40:57.123  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:40:57.123  3758  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:40:57.123  3758  3810 D ExecuteNativeTests: Running unit tests
,08-17 10:40:57.126  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:40:57.128  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:40:57.187  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 10:40:57.187  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 added. We now have 3 listener(s)
08-17 10:40:57.189  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 10:40:57.189  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 10:40:57.189  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 10:40:57.189  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:40:57.189  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 added. We now have 3 listener(s)
,08-17 10:40:57.189  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:40:57.189  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:40:57.199  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:40:57.206  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:40:57.206  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:40:57.206  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:40:57.206  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:40:57.206  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:40:57.206  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:40:57.206  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:40:57.206  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:40:57.208  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:40:57.208  3758  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:40:57.211  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 10:40:57.211  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 10:40:57.211  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:40:57.211  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 10:40:57.211  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:40:57.212  3758  3810 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-17 10:40:57.213  3758  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 10:40:57.213  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-17 10:40:57.213  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:40:57.213  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 10:40:57.213  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:40:57.213  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:40:57.214  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-17 10:40:57.214  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:40:57.214  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:40:57.214  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:40:57.214  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:40:57.214  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:40:57.214  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:40:57.214  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 removed from the list
,08-17 10:40:57.215  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:40:57.215  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 removed from the list
08-17 10:40:57.215  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:40:57.215  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:40:57.215  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:40:57.215  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:40:57.216  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:40:57.216  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:40:57.216  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:40:57.216  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:40:57.218  3758  3810 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 10:40:57.219  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:40:57.219  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:40:57.219  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:40:57.219  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:40:57.219  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:40:57.219  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:40:57.219  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
,08-17 10:40:57.219  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:40:57.219  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:40:57.219  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:40:57.219  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:40:57.219  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:40:57.220  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:40:57.220  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:40:57.221  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:40:57.221  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:40:57.221  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:40:57.221  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
,08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610],
08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 10:40:57.225  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 10:40:57.226  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 10:40:57.227  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:40:57.227  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:40:57.227  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:40:57.227  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:40:57.227  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:40:57.227  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:40:57.227  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
,08-17 10:40:57.228  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:40:57.228  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:40:57.228  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:40:57.228  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:40:57.228  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:40:57.228  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:40:57.228  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:40:57.229  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:40:57.229  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:40:57.229  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:40:57.229  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:40:57.230  3758  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 10:40:57.231  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:40:57.236  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:40:57.236  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:40:57.236  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:40:57.236  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:40:57.236  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:40:57.236  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:40:57.236  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:40:57.236  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:40:57.242  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:40:57.242  3758  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:40:57.243  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:40:57.243  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:40:57.243  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:40:57.244  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:40:57.244  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:40:57.244  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:40:57.246  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:40:57.252  3758  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 10:40:57.252  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 10:40:57.258  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:40:57.260  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 10:40:57.260  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 10:40:57.265  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-17 10:40:57.269  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-17 10:40:57.269  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 10:40:57.269  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 10:40:57.270  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 10:40:57.271  3758  3810 D BluetoothAdapter: STATE_ON
,08-17 10:40:57.275  2609  2624 D BtGatt.GattService: registerClient() - UUID=2d73d44e-e9d0-4c23-a43e-2d46c6ff4885
,08-17 10:40:57.276  2609  2643 D BtGatt.GattService: onClientRegistered() - UUID=2d73d44e-e9d0-4c23-a43e-2d46c6ff4885, clientIf=5
,08-17 10:40:57.276  3758  3769 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 10:40:57.277  2609  2620 D BtGatt.GattService: start scan with filters
,08-17 10:40:57.281  2609  2659 D BtGatt.ScanManager: handling starting scan
,08-17 10:40:57.281  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 10:40:57.282  2609  2659 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
08-17 10:40:57.282  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 10:40:57.282  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 10:40:57.283  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 10:40:57.289  2609  2643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 10:40:57.289  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:40:57.290  2609  2659 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 10:40:57.291  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:40:57.292  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:40:57.291  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 10:40:57.297  2609  2643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 10:40:57.297  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:40:57.297  2609  2659 D BtGatt.ScanManager: Starting BLE batch scan
08-17 10:40:57.297  2609  2659 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 10:40:57.299  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:40:57.306  3758  3810 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 10:40:57.309  2609  2643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 10:40:57.309  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:40:57.314  2609  2643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 10:40:57.314  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:40:57.795  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-17 10:40:57.796  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:40:57.796  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:40:58.820  2609  2609 D BtGatt.ScanManager: awakened up at time 144528
,08-17 10:40:58.823  2609  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:40:58.856  2609  2643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-17 10:40:58.856  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:40:58.857  2609  2643 D BtGatt.GattService: current time is 144565068317
,08-17 10:40:58.857  2609  2643 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -89, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -77, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -105, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -84, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-17 10:40:58.859  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 10:40:58.860  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-17 10:40:58.860  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-17 10:40:58.860  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-17 10:40:58.861  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-17 10:41:00.363  2609  2609 D BtGatt.ScanManager: awakened up at time 146071
,08-17 10:41:00.366  2609  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:41:00.433  2609  2643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-17 10:41:00.434  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:00.434  2609  2643 D BtGatt.GattService: current time is 146142587172
,08-17 10:41:00.436  2609  2643 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -89, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -100, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -94, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -91, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-17 10:41:00.437  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 10:41:00.438  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-17 10:41:00.439  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-17 10:41:00.440  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-17 10:41:00.440  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-17 10:41:00.441  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-17 10:41:00.983   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-17 10:41:01.936  2609  2609 D BtGatt.ScanManager: awakened up at time 147644
,08-17 10:41:01.940  2609  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:41:01.971  2609  2643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-17 10:41:01.971  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:01.971  2609  2643 D BtGatt.GattService: current time is 147679680832
,08-17 10:41:01.972  2609  2643 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-17 10:41:01.973  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-17 10:41:01.974  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-17 10:41:02.316  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:41:02.317  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:41:02.317  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 10:41:02.318  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:02.318  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-17 10:41:02.318  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 10:41:02.319  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 10:41:02.319  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 10:41:02.319  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 10:41:02.321  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 10:41:02.322  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 10:41:02.324  3758  3810 D BluetoothAdapter: STATE_ON
08-17 10:41:02.326  2609  2624 D BtGatt.GattService: stopScan() - queue size =1
,08-17 10:41:02.329  2609  2755 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 10:41:02.331  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:41:02.331  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 10:41:02.332  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 10:41:02.332  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 10:41:02.332  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 10:41:02.336  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
08-17 10:41:02.337  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 10:41:02.338  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
08-17 10:41:02.339  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 10:41:02.340  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:41:02.345  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:41:02.346  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 10:41:02.346  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:41:02.346  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:02.346  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:02.347  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:41:02.347  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:02.347  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:41:02.347  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:02.347  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:41:02.347  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:02.350  2609  2643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 10:41:02.350  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:02.351  2609  2659 D BtGatt.ScanManager: stopping BLe Batch
08-17 10:41:02.358  2609  2643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 10:41:02.358  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:41:02.359  2609  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:41:02.371  2609  2643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 10:41:02.371  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:02.847  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 10:41:04.022   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-17 10:41:04.271   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-17 10:41:04.282  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-17 10:41:04.290   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 10:41:04.290   873   893 I Adreno  : Build Date                       : 10/20/15
08-17 10:41:04.290   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 10:41:04.290   873   893 I Adreno  : Local Branch                     : M14
08-17 10:41:04.290   873   893 I Adreno  : Remote Branch                    : 
08-17 10:41:04.290   873   893 I Adreno  : Remote Branch                    : 
08-17 10:41:04.290   873   893 I Adreno  : Reconstruct Branch               : 
,08-17 10:41:04.316   281  1405 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (222 us)
,08-17 10:41:04.938  3758  3758 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 10:41:04.938  3758  3758 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 10:41:04.975   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-17 10:41:04.977  3758  3758 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3dd221c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@502a, 16908290=android.view.AbsSavedState$1@502a}, android:focusedViewId=100}]}]
08-17 10:41:04.977  3758  3758 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-17 10:41:04.978  3758  3758 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 10:41:04.978  3758  3758 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-17 10:41:05.000   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-17 10:41:05.003   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-17 10:41:05.003   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-17 10:41:05.003   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-17 10:41:05.016   873   882 I art     : Background partial concurrent mark sweep GC freed 26723(1711KB) AllocSpace objects, 7(148KB) LOS objects, 33% free, 28MB/43MB, paused 11.955ms total 110.538ms
,08-17 10:41:05.230   281   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-17 10:41:05.235   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-17 10:41:05.240   873  1334 D SurfaceControl: Excessive delay in setPowerMode(): 237ms
,08-17 10:41:05.246   873   893 I DreamManagerService: Entering dreamland.
,08-17 10:41:05.247   873   893 I PowerManagerService: Dozing...
,08-17 10:41:05.249   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-17 10:41:05.307   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-17 10:41:05.308   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-17 10:41:05.318   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:41:05.326  1900  3827 D NfcService: Discovery configuration equal, not updating.
,08-17 10:41:05.337   873  1306 E native  : do suspend false
,08-17 10:41:05.358   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 10:41:05.372   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:41:05.379   873  1306 E native  : do suspend true
,08-17 10:41:05.439   376  1314 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-17 10:41:05.440   376  1314 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-17 10:41:05.827   873  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-17 10:41:07.349  3758  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 10:41:07.357  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:41:07.372  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:41:07.372  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:07.372  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:07.372  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:07.372  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:41:07.372  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:41:07.372  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:41:07.372  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:41:07.378  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:41:07.379  3758  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:41:07.380  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 10:41:07.380  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 10:41:07.380  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 10:41:07.380  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:41:07.381  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:41:07.387  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:07.391  3758  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 10:41:07.392  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 10:41:07.395  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:07.405  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:41:07.408  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 10:41:07.408  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 10:41:07.417  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 10:41:07.417  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 10:41:07.418  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 10:41:07.420  3758  3810 D BluetoothAdapter: STATE_ON
,08-17 10:41:07.425  2609  2755 D BtGatt.GattService: registerClient() - UUID=a761a6dd-6297-49c4-a6a3-689c99f555c3
,08-17 10:41:07.426  2609  2643 D BtGatt.GattService: onClientRegistered() - UUID=a761a6dd-6297-49c4-a6a3-689c99f555c3, clientIf=5
,08-17 10:41:07.427  3758  3769 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 10:41:07.428  2609  2624 D BtGatt.GattService: start scan with filters
,08-17 10:41:07.435  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 10:41:07.435  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 10:41:07.436  2609  2659 D BtGatt.ScanManager: handling starting scan
,08-17 10:41:07.436  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 10:41:07.436  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 10:41:07.450  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:41:07.450  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 10:41:07.450  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:41:07.451  2609  2643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 10:41:07.451  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:41:07.451  2609  2659 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 10:41:07.459  2609  2643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 10:41:07.459  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:41:07.459  2609  2659 D BtGatt.ScanManager: Starting BLE batch scan
08-17 10:41:07.460  2609  2659 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 10:41:07.461  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:41:07.467  3758  3810 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 10:41:07.470  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:41:07.470  3758  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 10:41:07.470  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:07.470  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 10:41:07.470  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:07.470  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-17 10:41:07.471  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 10:41:07.471  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 10:41:07.471  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 10:41:07.471  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 10:41:07.471  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 10:41:07.471  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 10:41:07.477  3758  3810 D BluetoothAdapter: STATE_ON
,08-17 10:41:07.480  2609  2620 D BtGatt.GattService: stopScan() - queue size =1
,08-17 10:41:07.481  2609  2643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 10:41:07.481  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:41:07.481  2609  2747 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 10:41:07.482  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:41:07.483  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 10:41:07.483  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 10:41:07.483  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 10:41:07.483  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 10:41:07.485  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:41:07.485  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 10:41:07.485  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 10:41:07.485  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 10:41:07.486  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:41:07.487  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:41:07.487  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 10:41:07.487  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 10:41:07.488  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:41:07.488  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:07.488  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:41:07.488  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:07.488  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:41:07.488  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:07.488  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:41:07.488  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:07.489  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:07.489  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:07.490  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:07.491  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:07.491  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:41:07.491  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:07.492  3758  3810 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 10:41:07.494  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:41:07.497  2609  2643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 10:41:07.497  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:07.503  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:41:07.503  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:07.503  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:07.503  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:07.503  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:41:07.503  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:41:07.503  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:41:07.503  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:41:07.505  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:41:07.506  3758  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:41:07.507  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 10:41:07.507  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 10:41:07.507  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 10:41:07.507  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:41:07.507  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 10:41:07.510  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-17 10:41:07.511  2609  2643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 10:41:07.512  3758  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 10:41:07.511  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:07.512  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 10:41:07.512  2609  2659 D BtGatt.ScanManager: stopping BLe Batch
,08-17 10:41:07.515  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:07.518  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:41:07.519  2609  2643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 10:41:07.520  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:07.520  2609  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:41:07.520  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 10:41:07.520  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 10:41:07.523  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 10:41:07.524  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 10:41:07.524  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 10:41:07.525  3758  3810 D BluetoothAdapter: STATE_ON
,08-17 10:41:07.527  2609  2620 D BtGatt.GattService: registerClient() - UUID=8b2457ff-55b3-4b2d-927c-a4f75776ce29
,08-17 10:41:07.528  2609  2643 D BtGatt.GattService: onClientRegistered() - UUID=8b2457ff-55b3-4b2d-927c-a4f75776ce29, clientIf=5
,08-17 10:41:07.528  3758  3770 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 10:41:07.528  2609  2643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 10:41:07.529  2609  2756 D BtGatt.GattService: start scan with filters
08-17 10:41:07.529  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:07.531  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 10:41:07.531  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 10:41:07.531  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 10:41:07.531  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 10:41:07.532  2609  2659 D BtGatt.ScanManager: handling starting scan
,08-17 10:41:07.534  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:41:07.535  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 10:41:07.535  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:41:07.536  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:41:07.540  3758  3810 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 10:41:07.542  2609  2643 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 10:41:07.542  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:41:07.543  2609  2659 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 10:41:07.549  2609  2643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 10:41:07.549  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:07.549  2609  2659 D BtGatt.ScanManager: Starting BLE batch scan
08-17 10:41:07.550  2609  2659 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,08-17 10:41:07.562  2609  2643 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 10:41:07.562  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:07.569  2609  2643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 10:41:07.569  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:08.036  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-17 10:41:08.037  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:41:08.037  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:41:09.076  2609  2609 D BtGatt.ScanManager: awakened up at time 154783
,08-17 10:41:09.080  2609  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:41:09.129  2609  2643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-17 10:41:09.129  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:09.130  2609  2643 D BtGatt.GattService: current time is 154838223101
,08-17 10:41:09.131  2609  2643 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -78, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -89, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -84, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -92, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 53, 33, -121, 80, 73, -44, 1, -128, -107, 3, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 20, 126, -35, 2, 2, -29, 21, 63, -99, -42, 52, 0]
,08-17 10:41:09.132  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-17 10:41:09.133  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-17 10:41:09.134  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-17 10:41:09.135  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-17 10:41:09.136  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-17 10:41:09.137  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-17 10:41:09.138  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 20, 126, -35, 2, 2, -29, 21, 63, -99, -42, 52]
,08-17 10:41:10.632  2609  2609 D BtGatt.ScanManager: awakened up at time 156340
,08-17 10:41:10.636  2609  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:41:10.684  2609  2643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-17 10:41:10.684  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:10.685  2609  2643 D BtGatt.GattService: current time is 156393187562
,08-17 10:41:10.687  2609  2643 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -90, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -94, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -96, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -91, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-17 10:41:10.688  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-17 10:41:10.690  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-17 10:41:10.690  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-17 10:41:10.691  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-17 10:41:10.693  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-17 10:41:10.694  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-17 10:41:11.857  2147  2640 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 10:41:12.187  2609  2609 D BtGatt.ScanManager: awakened up at time 157895
,08-17 10:41:12.191  2609  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:41:12.223  2609  2643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-17 10:41:12.224  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:12.224  2609  2643 D BtGatt.GattService: current time is 157932577685
08-17 10:41:12.225  2609  2643 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -93, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0]
08-17 10:41:12.226  2609  2643 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-17 10:41:12.541  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:41:12.541  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:41:12.542  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 10:41:12.542  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:12.542  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-17 10:41:12.543  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 10:41:12.543  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 10:41:12.543  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 10:41:12.544  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 10:41:12.544  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 10:41:12.545  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 10:41:12.547  3758  3810 D BluetoothAdapter: STATE_ON
08-17 10:41:12.549  2609  2624 D BtGatt.GattService: stopScan() - queue size =1
,08-17 10:41:12.552  2609  2747 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 10:41:12.553  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:41:12.553  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 10:41:12.554  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 10:41:12.554  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 10:41:12.554  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 10:41:12.558  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:41:12.559  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 10:41:12.559  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 10:41:12.559  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 10:41:12.563  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:41:12.567  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 10:41:12.567  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 10:41:12.568  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 10:41:12.569  2609  2643 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 10:41:12.570  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:12.571  2609  2659 D BtGatt.ScanManager: stopping BLe Batch
,08-17 10:41:12.587  2609  2643 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 10:41:12.587  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:12.588  2609  2659 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:41:12.603  2609  2643 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 10:41:12.604  2609  2643 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:41:13.069  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 10:41:13.070  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:13.070  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:41:14.437  3561  3832 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 10:41:14.469  3561  3835 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 10:41:14.480  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:14.484  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:14.524  1513  2876 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-17 10:41:14.524  1513  2876 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 10:41:14.524  1513  2876 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:41:14.525  1513  2876 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:41:14.601  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:14.609  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:14.646  1513  2876 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 10:41:14.646  1513  2876 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-17 10:41:14.647  1513  2876 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:41:14.647  1513  2876 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:41:14.661  1513  2257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 10:41:14.661  1513  2257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 10:41:14.661  1513  2257 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:41:14.662  1513  2257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:41:14.670  3561  3835 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:41:14.671  3561  3832 E BooksSync: Soft error
08-17 10:41:14.671  3561  3832 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:41:14.671  3561  3832 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 10:41:14.671  3561  3832 E BooksSync: Sync error
08-17 10:41:14.671  3561  3832 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:41:14.671  3561  3832 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 10:41:14.672  3561  3832 I BooksSync: Finished books sync
,08-17 10:41:14.685   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 130228, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:41:14.700  3521  3834 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 10:41:14.700  3521  3834 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at jdm.a(PG:82)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at jcs.o(PG:406)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at jcn.a(PG:1379)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at jcs.i(PG:143)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at blb.a(PG:3937)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at czp.a(PG:18188)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at czp.a(PG:9081)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at czq.run(PG:1686)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:41:14.700  3521  3834 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at jdj.a(PG:4091)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at jdj.a(PG:1125)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at jdm.a(PG:77)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	... 12 more
08-17 10:41:14.700  3521  3834 E HttpOperation: Caused by: faj: BadAuthentication
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at fal.a(PG:38)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	at jdj.a(PG:4089)
08-17 10:41:14.700  3521  3834 E HttpOperation: 	... 14 more
,08-17 10:41:14.772  1513  2199 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 10:41:14.773  1513  2199 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 10:41:14.773  1513  2199 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:41:14.773  1513  2199 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:41:14.821  3521  3834 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 10:41:14.821  3521  3834 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at jdm.a(PG:82)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at jcs.o(PG:406)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at jcn.a(PG:1379)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at jcs.i(PG:143)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at hec.a(PG:42)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at hee.a(PG:102)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at czr.a(PG:65)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at kka.a(PG:108)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at czp.a(PG:19176)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at czp.a(PG:9081)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at czq.run(PG:1686)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:41:14.821  3521  3834 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at jdj.a(PG:4091)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at jdj.a(PG:1125)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at jdm.a(PG:77)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	... 15 more
08-17 10:41:14.821  3521  3834 E HttpOperation: Caused by: faj: BadAuthentication
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at fal.a(PG:38)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	at jdj.a(PG:4089)
08-17 10:41:14.821  3521  3834 E HttpOperation: 	... 17 more
,08-17 10:41:14.823  3521  3834 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 10:41:14.823  3521  3834 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at hec.a(PG:42)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at hee.a(PG:102)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at czr.a(PG:65)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at kka.a(PG:108)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	... 15 more
08-17 10:41:14.823  3521  3834 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at fal.a(PG:38)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	at jdj.a(PG:4089)
08-17 10:41:14.823  3521  3834 E ExperimentLoader: 	... 17 more
,08-17 10:41:14.959   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 132149, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:41:17.023   873  1306 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-17 10:41:17.238  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:17.419  1513  3838 I VacuumService: Vacuum at: now=1471423277419 tag=VacuumService
,08-17 10:41:17.539  1513  3839 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-17 10:41:17.542  1513  3839 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 10:41:17.554  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:17.567  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:41:17.567  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:17.567  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:17.568  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:17.568  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.568  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:41:17.568  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
,08-17 10:41:17.568  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.568  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.568  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:17.568  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.569  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:17.569  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.571  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:17.571  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:17.571  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:41:17.571  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
,08-17 10:41:17.572  3758  3810 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 10:41:17.573  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:17.573  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:17.573  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:41:17.573  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:41:17.573  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.574  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.574  1513  3839 W Uploader:  no longer exists, so no auth token.
,08-17 10:41:17.574  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:17.574  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.574  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.574  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:17.574  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.574  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:17.574  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.574  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.576  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:17.576  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:17.576  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:41:17.576  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.578  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-17 10:41:17.578  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:17.578  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:17.578  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:17.579  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:17.579  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.579  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:17.579  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:17.579  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.579  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.579  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:17.579  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.579  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.579  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:17.579  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.581  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:17.581  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:17.581  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.581  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
,08-17 10:41:17.581  3758  3810 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 10:41:17.582  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:17.582  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:17.582  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:41:17.582  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:17.582  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.582  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.582  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:17.582  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.582  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.582  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:41:17.583  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.583  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.583  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.583  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:17.583  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:17.583  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:17.583  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.584  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.584  3758  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 10:41:17.584  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:17.584  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:17.584  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:17.584  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:17.584  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.585  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.585  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:17.585  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.585  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.585  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:17.585  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.585  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.585  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.585  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:17.586  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:17.587  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:17.587  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.587  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.587  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 10:41:17.589  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:41:17.589  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:41:17.589  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 10:41:17.589  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:41:17.589  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:41:17.590  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 10:41:17.590  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:41:17.590  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 10:41:17.590  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:17.591  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:17.591  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:17.591  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:17.591  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.591  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.591  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:17.592  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.593  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.593  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:17.593  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.593  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.593  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.595  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.599  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:17.599  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:17.599  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.599  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.601  3758  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:41:17.602  3758  3810 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 10:41:17.602  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 10:41:17.609  3758  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:41:17.609  3758  3810 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 10:41:17.609  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 10:41:17.609  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 10:41:17.609  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 10:41:17.609  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 10:41:17.610  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 10:41:17.610  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 10:41:17.610  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 10:41:17.610  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 10:41:17.610  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 10:41:17.610  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 10:41:17.610  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 10:41:17.610  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 10:41:17.610  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 10:41:17.611  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 10:41:17.611  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 10:41:17.611  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 10:41:17.611  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 10:41:17.611  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 10:41:17.611  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 10:41:17.611  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 10:41:17.611  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 10:41:17.611  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 10:41:17.612  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 10:41:17.612  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 10:41:17.612  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 10:41:17.612  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 10:41:17.612  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 10:41:17.612  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-17 10:41:17.612  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 10:41:17.612  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 10:41:17.612  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 10:41:17.612  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 10:41:17.613  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:41:17.613  3758  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 10:41:17.613  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-17 10:41:17.613  3758  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 10:41:17.613  3758  3810 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 10:41:17.613  3758  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:41:17.613  3758  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 10:41:17.614  3758  3810 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 10:41:17.614  3758  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:41:17.614  3758  3810 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 10:41:17.614  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 10:41:17.616  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 10:41:17.617  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 10:41:17.617  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-17 10:41:17.618  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 10:41:17.618  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 10:41:17.618  3758  3810 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 10:41:17.619  3758  3810 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 10:41:17.619  3758  3810 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 10:41:17.620  3758  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 386)
08-17 10:41:17.620  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:17.621  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:17.621  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:17.621  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:17.621  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.621  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.621  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 10:41:17.622  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:17.622  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.622  3758  3845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:41:17.622  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.622  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:17.622  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.622  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.623  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.623  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.623  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:17.624  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:17.624  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.624  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.625  3758  3810 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 10:41:17.626  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:17.626  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:17.626  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:17.626  3758  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
08-17 10:41:17.626  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:17.626  3758  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 386)
08-17 10:41:17.627  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.627  3758  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
08-17 10:41:17.627  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.627  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:17.627  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.627  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.628  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:17.628  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.628  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.628  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.628  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.628  2609  2741 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-17 10:41:17.629  3758  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 386)
08-17 10:41:17.629  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:17.629  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:17.629  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.629  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.631  3480  3480 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 10:41:17.631  3480  3480 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 10:41:17.631  3758  3810 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 10:41:17.631  3480  3480 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
08-17 10:41:17.631  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:17.632  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:17.632  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:17.632  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:17.632  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.632  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.632  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:17.632  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.632  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.632  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:17.632  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.632  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.632  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.632  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.634  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:17.634  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:17.635  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.635  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.637  3758  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 10:41:17.637  3758  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 10:41:17.637  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 10:41:17.637  3758  3810 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 10:41:17.637  3758  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 10:41:17.638  3758  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 10:41:17.638  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 10:41:17.638  3758  3810 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 10:41:17.638  3758  3810 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 10:41:17.638  3758  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 10:41:17.638  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 10:41:17.638  3758  3810 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 10:41:17.638  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:17.638  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:17.639  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:17.639  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:17.639  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.639  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.639  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:17.639  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.639  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.639  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:17.639  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.639  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.639  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.640  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.641  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:17.641  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:17.641  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.641  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.641  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:17.642  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.642  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:17.642  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:17.642  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:17.642  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:17.642  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:17.642  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:17.642  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:22.609   873  1853 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:41:22.643  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:41:22.644  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:22.644  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:22.644  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:22.644  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:22.645  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
,08-17 10:41:22.645  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:22.646  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:22.646  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:22.646  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:22.647  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:22.647  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.647  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
,08-17 10:41:22.648  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:22.648  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
,08-17 10:41:22.648  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:22.649  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:22.649  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:22.649  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:22.650  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:22.654  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:22.654  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:41:22.654  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:41:22.655  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:22.658  3758  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-17 10:41:22.659  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:41:22.661  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 10:41:22.664  3758  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-17 10:41:22.664  3758  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-17 10:41:22.665  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-17 10:41:22.665  3758  3758 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-17 10:41:22.665  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 10:41:22.667  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:41:22.667  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 10:41:22.667  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 10:41:22.667  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 10:41:22.668  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.668  3758  3848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:41:22.668  3758  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-17 10:41:22.668  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:22.669  3758  3758 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 10:41:22.669  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:22.669  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 10:41:22.669  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 10:41:22.669  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 10:41:22.670  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:22.670  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.673  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:41:22.673  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:22.673  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:41:22.673  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 10:41:22.673  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:22.673  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:41:22.673  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:22.673  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:22.673  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:22.673  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:22.673  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.674  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:22.674  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:22.674  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:22.674  3758  3848 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 10:41:22.674  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:22.674  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:22.674  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.674  3758  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 10:41:22.674  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:22.674  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-17 10:41:22.674  3758  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 10:41:22.676  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:22.676  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:41:22.676  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:22.676  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:22.676  3758  3758 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 10:41:22.677  3758  3810 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-17 10:41:22.677  3758  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 10:41:22.678  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 10:41:22.679  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 10:41:22.679  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 10:41:22.680  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:22.680  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:22.680  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:41:22.681  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:22.681  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:22.681  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.681  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
08-17 10:41:22.681  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:22.681  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:22.681  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:41:22.681  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:22.681  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.681  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:22.682  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.683  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:22.683  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:22.683  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-17 10:41:22.683  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
,08-17 10:41:22.689  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:41:22.689  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:22.689  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:41:22.690  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 10:41:22.690  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:22.690  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.690  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
,08-17 10:41:22.690  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:22.690  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:22.690  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:22.690  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:22.690  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.690  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:22.690  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:22.692  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:41:22.692  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:22.692  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:22.692  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
,08-17 10:41:22.693  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:41:22.693  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:41:22.693  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 10:41:22.694  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:41:22.694  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:22.694  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.694  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4b19da3 not in the list
,08-17 10:41:22.694  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:22.694  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
08-17 10:41:22.694  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:22.694  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:22.694  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.694  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:22.694  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:41:22.695  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:41:22.695  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:41:22.695  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:22.696  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb9f8a0 not in the list
,08-17 10:41:22.697  3758  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 10:41:22.697  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 10:41:22.697  3758  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-17 10:41:22.697  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 10:41:22.697  3758  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 10:41:22.697  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-17 10:41:22.700  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-17 10:41:22.700  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 10:41:22.700  3758  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1,
08-17 10:41:22.701  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-17 10:41:22.701  3758  3810 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 10:41:22.701  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 10:41:22.701  3758  3810 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2,
08-17 10:41:22.701  3758  3810 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-17 10:41:22.701  3758  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 10:41:22.702  3758  3810 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-17 10:41:22.702  3758  3810 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 10:41:22.702  3758  3810 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 10:41:22.702  3758  3810 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-17 10:41:22.702  3758  3810 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 10:41:22.703  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:41:22.703  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3153593 added. We now have 3 listener(s)
,08-17 10:41:22.703  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:41:22.705  3758  3810 D BluetoothAdapter: enable(): BT is already enabled..!
,08-17 10:41:22.705   873  1901 D WifiService: setWifiEnabled: true pid=3758, uid=10000
08-17 10:41:22.705   873  1901 E WifiService: Invoking mWifiStateMachine.setWifiEnabled,
,08-17 10:41:22.754  2609  2699 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-17 10:41:22.754  2609  2699 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-17 10:41:23.174  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 10:41:26.042  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:26.044  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:26.076  1513  3839 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-17 10:41:26.076  1513  3839 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-17 10:41:26.076  1513  3839 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:41:26.076  1513  3839 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:41:26.100  1513  3839 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 10:41:26.100  1513  3839 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 10:41:26.100  1513  3839 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 10:41:26.560  1513  3839 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-17 10:41:26.560  1513  3839 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-17 10:41:26.560  1513  3839 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:41:26.561  1513  3839 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:41:26.584  1513  3839 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 10:41:26.584  1513  3839 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 10:41:26.584  1513  3839 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 10:41:27.044  1513  3839 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-17 10:41:27.045  1513  3839 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-17 10:41:27.045  1513  3839 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:41:27.045  1513  3839 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:41:27.068  1513  3839 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-17 10:41:27.068  1513  3839 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-17 10:41:27.068  1513  3839 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-17 10:41:27.711  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:41:27.712  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@90cc9d0 added. We now have 4 listener(s)
,08-17 10:41:27.712  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:41:27.728  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:27.729  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@90cc9d0 removed from the list
,08-17 10:41:27.729  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:27.729  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:27.730  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:27.732  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:41:27.732  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6cf7dc9 added. We now have 4 listener(s)
08-17 10:41:27.733  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:41:27.735  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:41:27.735  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6cf7dc9 removed from the list
,08-17 10:41:27.736  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:27.736  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:41:27.736  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:27.738  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:41:27.738  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@121fcce added. We now have 4 listener(s)
08-17 10:41:27.739  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:41:27.743   873   884 D WifiService: setWifiEnabled: false pid=3758, uid=10000
08-17 10:41:27.743   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:41:27.754  2609  2637 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 10:41:27.755  2609  2637 D BluetoothAdapterProperties: Setting state to 13
,08-17 10:41:27.755  2609  2637 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 10:41:27.756  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:41:27.756  2609  2637 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 10:41:27.757  2609  2637 I BluetoothAdapterState: Entering PendingCommandState
08-17 10:41:27.761  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 10:41:27.763  2609  2643 D BluetoothAdapterProperties: Scan Mode:20
08-17 10:41:27.764  2609  2637 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-17 10:41:27.771  2609  2609 D BluetoothMapService: onReceive
08-17 10:41:27.771  2609  2609 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:41:27.771  2609  2609 D BluetoothMapService: STATE_TURNING_OFF
08-17 10:41:27.771   873  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 10:41:27.771  2609  2609 D BluetoothMapService: MAP Service closeService in
08-17 10:41:27.771   873  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-17 10:41:27.771  2609  2609 D BluetoothMapMasInstance0: MAP Service shutdown
08-17 10:41:27.771   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 10:41:27.771  2609  2609 D ObexServerSockets0: shutdown(block = true)
08-17 10:41:27.771   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:41:27.772  2609  2609 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-17 10:41:27.772  2609  2609 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 10:41:27.772  2609  2758 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 10:41:27.772  2609  2757 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 10:41:27.773  2609  2741 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 10:41:27.774  2609  2609 I BtOppRfcommListener: stopping Accept Thread
,08-17 10:41:27.774  2609  3404 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 10:41:27.775  2609  3404 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 10:41:27.777  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:27.778  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:41:27.778  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:27.778  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:27.778  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:27.778  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:27.778  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:41:27.778  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:41:27.778  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:41:27.778  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.779  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:41:27.779  3758  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:41:27.782   873  1306 E native  : do suspend true
08-17 10:41:27.784  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:27.787   873   886 I ActivityManager: Start proc 3858:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-17 10:41:27.789  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:27.792  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:27.793  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:27.793  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:27.793  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:27.793  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:27.793  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:27.793  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:41:27.793  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:41:27.793  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:41:27.793  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:27.793  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:41:27.797   873  1855 D DhcpClient: Clearing IP address
08-17 10:41:27.799  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.802  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:27.802  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:27.802  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:27.802  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:27.802  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:27.802  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:41:27.802  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:41:27.802  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:41:27.796  2609  2609 D HeadsetService: Received stop request...Stopping profile...
,08-17 10:41:27.796   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-17 10:41:27.803  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:27.803  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:41:27.804  1920  1935 D BluetoothHeadset: Proxy object disconnected
,08-17 10:41:27.805   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 10:41:27.805  1363  2013 D BluetoothHeadset: Proxy object disconnected
08-17 10:41:27.805  2609  2609 D A2dpService: Received stop request...Stopping profile...
08-17 10:41:27.806   873   873 D BluetoothHeadset: Proxy object disconnected
,08-17 10:41:27.806  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-17 10:41:27.806  2609  2750 D A2dpStateMachine: Exit Disconnected: -1
08-17 10:41:27.806   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 10:41:27.808  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:27.810  1363  1363 D BluetoothA2dp: Proxy object disconnected
,08-17 10:41:27.810   873   873 D BluetoothA2dp: Proxy object disconnected
08-17 10:41:27.810  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:27.811  2609  2609 D HidService: Received stop request...Stopping profile...
08-17 10:41:27.811  2609  2609 D HidService: Stopping Bluetooth HidService
08-17 10:41:27.812  1363  1363 D BluetoothInputDevice: Proxy object disconnected
,08-17 10:41:27.812  1363  1363 D HidProfile: Bluetooth service disconnected
08-17 10:41:27.812  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:27.814   372   871 D CommandListener: Setting iface cfg
08-17 10:41:27.814  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:27.815  2609  2609 D HealthService: Received stop request...Stopping profile...
08-17 10:41:27.816   873  1870 D DhcpClient: Receive thread stopped
08-17 10:41:27.816  2609  2609 D PanService: Received stop request...Stopping profile...
08-17 10:41:27.817  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 10:41:27.817  1363  1363 D PanProfile: Bluetooth service disconnected
08-17 10:41:27.817  2609  2609 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 10:41:27.817  2609  2609 D BluetoothMapService: stop()
08-17 10:41:27.818  2609  2609 D BluetoothMapAppObserver: deinitObservers()
,08-17 10:41:27.818  2609  2609 D BluetoothMapAppObserver: removeReceiver()
,08-17 10:41:27.819   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 10:41:27.819  2609  2609 V BluetoothAdapterState: isTurningOff()=true
08-17 10:41:27.819  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-17 10:41:27.819   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-17 10:41:27.819  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:27.820  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:41:27.820   873  1306 D WifiStateMachine: Start Disconnecting Watchdog 1
08-17 10:41:27.821   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 10:41:27.821   873  1306 E native  : do suspend true
08-17 10:41:27.821  2609  2609 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 10:41:27.821  2609  2609 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 10:41:27.821  2609  2643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 10:41:27.821  2609  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:41:27.821  2609  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 10:41:27.821  2609  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:41:27.825   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-17 10:41:27.828  2609  2609 V BluetoothAdapterState: isTurningOff()=true
08-17 10:41:27.828  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-17 10:41:27.828  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:27.828  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:27.829   402   402 E Parcel  : Reading a NULL string not supported here.
08-17 10:41:27.829  2609  2643 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-17 10:41:27.831  1363  1363 D BluetoothMap: Proxy object disconnected
,08-17 10:41:27.831  1363  1363 D MapProfile: Bluetooth service disconnected
08-17 10:41:27.831  2609  2643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 10:41:27.831  2609  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:41:27.831  2609  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 10:41:27.831  2609  2699 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 10:41:27.831  2609  2699 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:41:27.831  2609  2699 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 10:41:27.831  2609  2699 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-17 10:41:27.832  2609  2609 V BluetoothAdapterState: isTurningOff()=true
08-17 10:41:27.832  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-17 10:41:27.832  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:27.832  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:27.833  2609  2609 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-17 10:41:27.833  2609  2643 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 10:41:27.833  2609  2609 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 10:41:27.836  2609  2609 V BluetoothAdapterState: isTurningOff()=true
08-17 10:41:27.836  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-17 10:41:27.836  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:27.836  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:41:27.836  2609  2609 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 10:41:27.836  2609  2643 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 10:41:27.836  2609  2609 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 10:41:27.837  2609  2609 V BluetoothAdapterState: isTurningOff()=true
,08-17 10:41:27.837  2609  2609 V BluetoothAdapterState: isTurningOn()=false
08-17 10:41:27.837  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:27.837  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:41:27.837  2609  2609 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 10:41:27.838  2609  2609 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 10:41:27.839  2609  2609 D BluetoothMapService: MAP Service closeService in
08-17 10:41:27.812  1513  2106 V NativeCrypto: Read error: ssl=0xaedf1c00: I/O error during system call, Connection timed out
08-17 10:41:27.839  2609  2609 V BluetoothAdapterState: isTurningOff()=true
08-17 10:41:27.839  2609  2609 V BluetoothAdapterState: isTurningOn()=false
,08-17 10:41:27.840  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:27.840  2609  2609 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:27.840  2609  2637 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 10:41:27.840  2609  2637 D BluetoothAdapterProperties: Setting state to 15
08-17 10:41:27.840  2609  2637 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-17 10:41:27.841  2609  2637 I BluetoothAdapterState: Entering BleOnState
08-17 10:41:27.841   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:41:27.841  2609  2609 D BluetoothMapService: cleanup()
08-17 10:41:27.841  1363  2013 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:41:27.841  2609  2609 D BluetoothMapService: MAP Service closeService in
08-17 10:41:27.841  1363  1388 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:41:27.843  1363  1389 D BluetoothPan: onBluetoothStateChange on: false
08-17 10:41:27.843  1363  2253 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 10:41:27.845   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:41:27.845  1363  2013 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 10:41:27.846   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 10:41:27.846   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:41:27.847  1363  1388 D BluetoothMap: onBluetoothStateChange: up=false
08-17 10:41:27.848  1920  1935 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:41:27.848  2609  2637 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 10:41:27.848  2609  2637 D BluetoothAdapterProperties: Setting state to 16
08-17 10:41:27.849  2609  2637 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-17 10:41:27.849  2609  2637 D BluetoothAdapterProperties: onBleDisable
08-17 10:41:27.849  2609  2637 I BluetoothAdapterState: Entering PendingCommandState
08-17 10:41:27.850  2609  2639 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 10:41:27.851  2609  2643 D BluetoothAdapterProperties: Scan Mode:20
08-17 10:41:27.852  2609  2699 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 10:41:27.852  2609  2699 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:41:27.853  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.853  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:27.853  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:27.853  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:27.853  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:27.853  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:27.853  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:27.853  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:27.853  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:41:27.853  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.854  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:27.856  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.856  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:27.856  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:27.856  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:27.856  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:27.856  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:27.856  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:27.856  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:27.856  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:27.857  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.857  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:41:27.857  1513  2106 V NativeCrypto: SSL shutdown failed: ssl=0xaedf1c00: I/O error during system call, Broken pipe
08-17 10:41:27.858  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.858  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:27.858  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:27.858  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:27.858  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:27.858  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:27.858  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:27.858  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:27.858  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:27.859  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.859  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:27.861  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:27.861  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:27.862  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:27.866   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:41:27.876  3858  3858 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-17 10:41:27.885  3858  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 10:41:27.886   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:41:27.886   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-17 10:41:27.887   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-17 10:41:27.887   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:41:27.888   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 10:41:27.891   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-17 10:41:27.893  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:27.894  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:27.895  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:27.896  3396  3396 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6cb22ba and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-17 10:41:27.903  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:41:27.914   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c556d5d:true
,08-17 10:41:27.916   873  1901 I ActivityManager: Start proc 3876:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-17 10:41:27.917   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:41:27.919  2147  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 10:41:27.919  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:27.919  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:27.919  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:27.919  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:27.919  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:27.919  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:27.919  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:27.919  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:27.919  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:27.920  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.920  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:27.921   873  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 10:41:27.922  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.922  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:27.922  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:27.922  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:27.922  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:27.922  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:27.922  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:27.922  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:27.922  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:27.922  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.923  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:27.924  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.924  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:27.924  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:27.924  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:27.924  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:27.924  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:27.924  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:27.924  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:27.924  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:27.925  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:27.926  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:41:27.945   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-17 10:41:27.952  3858  3858 D LocalBluetoothProfileManager: Adding local MAP profile
,08-17 10:41:27.957  3858  3858 D BluetoothMap: Create BluetoothMap proxy object
,08-17 10:41:27.964  3858  3858 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-17 10:41:27.968  3876  3876 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-17 10:41:27.983  3858  3858 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:41:27.992   873  1910 I ActivityManager: Killing 2959:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-17 10:41:28.055  2609  2643 I bt_hci  : shut_down
,08-17 10:41:28.056  2609  2660 D bt_hwcfg: hw_epilog_process
,08-17 10:41:28.057  2609  2660 I bt_vendor: low_power_mode_cb
,08-17 10:41:28.084  2609  2660 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 10:41:28.084  2609  2660 I bt_vendor: epilog_cb
,08-17 10:41:28.084  2609  2660 I bt_hci  : epilog_finished_callback
,08-17 10:41:28.104  2609  2643 I bt_hci_h4: hal_close
,08-17 10:41:28.104  2609  2643 I bt_userial_vendor: device fd = 51 close
,08-17 10:41:28.174  3876  3876 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:41:28.174  3876  3876 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:41:28.174  3876  3876 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:41:28.174  3876  3876 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:41:28.174  3876  3876 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.k.d(PG:583)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:41:28.174  3876  3876 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:41:28.174  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:41:28.175  3876  3876 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:41:28.175  3876  3876 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:41:28.175  3876  3876 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:41:28.181  3858  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 10:41:28.189  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:41:28.200  3858  3858 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:41:28.207   873  2249 I ActivityManager: Killing 3396:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-17 10:41:28.289  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 10:41:28.292  1731  1731 D SystemUpdateService: onCreate
,08-17 10:41:28.295  2609  2639 D bt_stack_manager: event_shut_down_stack finished.
,08-17 10:41:28.296  2609  2637 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-17 10:41:28.297  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 10:41:28.300  2609  2609 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 10:41:28.301  2609  2609 D BtGatt.GattService: Received stop request...Stopping profile...
,08-17 10:41:28.301  2609  2609 D BtGatt.GattService: stop()
,08-17 10:41:28.301  2609  2609 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 10:41:28.301  2609  2637 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 10:41:28.310  2609  2609 V BluetoothAdapterState: isTurningOff()=false
08-17 10:41:28.310  2609  2609 V BluetoothAdapterState: isTurningOn()=false
,08-17 10:41:28.310  2609  2609 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:28.310  2609  2609 V BluetoothAdapterState: isBleTurningOff()=true
,08-17 10:41:28.310  2609  2637 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 10:41:28.310  2609  2637 D BluetoothAdapterProperties: Setting state to 10
,08-17 10:41:28.310  2609  2637 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-17 10:41:28.311  2609  2637 I BluetoothAdapterState: Entering OffState
08-17 10:41:28.312   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 10:41:28.321  1731  3909 I SystemUpdateService: active receiver: enabled
,08-17 10:41:28.322  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 10:41:28.325  2609  2609 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-17 10:41:28.325  2609  2609 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 10:41:28.326  2609  2639 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-17 10:41:28.326  2609  2609 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 10:41:28.330  2609  2639 D bt_stack_manager: event_clean_up_stack finished.
,08-17 10:41:28.332  1731  2402 I iu.UploadsManager: num queued entries: 0
,08-17 10:41:28.333  1731  2402 I iu.UploadsManager: num updated entries: 0
,08-17 10:41:28.335  2609  2609 I art     : System.exit called, status: 0
,08-17 10:41:28.335  2609  2609 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 10:41:28.343  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 10:41:28.345  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 10:41:28.358  1731  3909 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 10:41:28.362   873  1371 I ActivityManager: Start proc 3912:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-17 10:41:28.374  1731  2402 I iu.SyncManager: NEXT; no task
,08-17 10:41:28.378  1731  3909 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-17 10:41:28.379  1731  3909 I SystemUpdateService: now status is 0 (complete)
,08-17 10:41:28.379  1731  3909 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 10:41:28.379  1731  3909 I SystemUpdateService: file has been verified
08-17 10:41:28.379  1731  3909 I SystemUpdateService: OTA package size = 12249756
,08-17 10:41:28.385  1731  3909 I SystemUpdateService: showing system update notification
,08-17 10:41:28.407   873  1371 I ActivityManager: Process com.android.bluetooth (pid 2609) has died
,08-17 10:41:28.421  3912  3912 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-17 10:41:28.425  3912  3912 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:41:28.429  1731  1731 D SystemUpdateService: onDestroy
,08-17 10:41:28.433  3912  3912 D SprintDMHelper: simOperator: 
,08-17 10:41:28.434  3912  3912 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 10:41:28.464   873  1933 I ActivityManager: Start proc 3925:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-17 10:41:28.465   873  1933 I ActivityManager: Killing 3442:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-17 10:41:28.512  3876  3895 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 10:41:28.527   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@cb9ef83:true
,08-17 10:41:28.654   873  1928 I ActivityManager: Start proc 3941:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-17 10:41:28.659  3038  3940 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 10:41:28.716  3941  3941 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-17 10:41:28.769  3941  3941 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 10:41:28.769  3941  3941 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 10:41:28.769  3941  3941 I GAv4    :   adb logcat -s GAv4
,08-17 10:41:28.788  3941  3941 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 10:41:28.794  3941  3941 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 10:41:28.823  3941  3958 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 10:41:28.928  3941  3941 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-17 10:41:28.962  3941  3941 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-17 10:41:28.978  3941  3941 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 4675-4685)
08-17 10:41:28.978  3941  3941 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 10:41:28.987  3941  3941 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {891ae6a}
,08-17 10:41:28.987  3941  3941 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 10:41:28.988  3941  3941 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 10:41:28.997  3941  3941 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 10:41:28.999  3941  3941 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 10:41:29.015  3941  3941 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 10:41:29.030  3941  3941 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 10:41:29.031  3941  3941 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 10:41:29.031  3941  3941 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 10:41:29.031  3941  3941 I Adreno  : Build Date                       : 10/20/15
08-17 10:41:29.031  3941  3941 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 10:41:29.031  3941  3941 I Adreno  : Local Branch                     : M14
08-17 10:41:29.031  3941  3941 I Adreno  : Remote Branch                    : 
08-17 10:41:29.031  3941  3941 I Adreno  : Remote Branch                    : 
08-17 10:41:29.031  3941  3941 I Adreno  : Reconstruct Branch               : 
,08-17 10:41:29.088  3941  3941 I NSApplication: Starting up...
,08-17 10:41:29.099  3941  3987 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 10:41:29.138   873  1910 I ActivityManager: Start proc 3992:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-17 10:41:29.139   873  1910 I ActivityManager: Killing 1686:android.process.acore/u0a5 (adj 15): empty #17
,08-17 10:41:29.227  3992  3992 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-17 10:41:29.417   873  1921 I ActivityManager: Killing 3641:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-17 10:41:29.531   873  1371 I ActivityManager: Start proc 4006:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-17 10:41:29.594  4006  4006 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-17 10:41:29.628  4006  4006 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-17 10:41:29.676   873  1901 I ActivityManager: Killing 3658:com.android.musicfx/u0a18 (adj 15): empty #17
,08-17 10:41:32.782   873  1926 D WifiService: setWifiEnabled: true pid=3758, uid=10000
,08-17 10:41:32.783   873  1926 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:41:32.797   873  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-17 10:41:32.806  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:32.806  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:32.806  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:32.806  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:32.806  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:32.806  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:32.806  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:32.806  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:32.806  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:41:32.806  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:32.807  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:41:32.809  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:32.809  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:32.809  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:32.809  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:32.809  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:32.809  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:32.809  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:32.809  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:32.809  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:41:32.809  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:32.809  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:41:32.812  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:32.812  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:32.812  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:32.812  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:32.812  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:32.812  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:32.812  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:32.812  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:32.812  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:41:32.812  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:32.812  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:41:32.835   873  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-17 10:41:32.836   873  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 10:41:32.837   873  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 10:41:32.838   873  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 10:41:32.839   873  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-17 10:41:32.839   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 10:41:32.839   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 10:41:32.865   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 10:41:32.866   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 10:41:32.867   372   871 D CommandListener: Setting iface cfg
08-17 10:41:32.868   873  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-17 10:41:32.868   873  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 10:41:32.877   873  1305 D WifiNative-HAL: p2pGetDeviceAddress
08-17 10:41:32.878   873  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 10:41:32.881   873  1306 E native  : do suspend true
,08-17 10:41:32.918   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:41:33.694   873   884 I ActivityManager: Killing 2226:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-17 10:41:34.292   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 10:41:34.315   873  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.44 rxSuccessRate=7.94 delta 1000 -> 994
,08-17 10:41:34.317   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-17 10:41:34.317   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:41:34.331   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 10:41:34.370   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 10:41:34.372  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 10:41:34.807  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 10:41:34.853  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 10:41:34.854  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 10:41:34.861   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:41:34.880   873  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-17 10:41:34.881   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 10:41:34.881   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 10:41:34.912   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:41:34.937   372   871 D CommandListener: Setting iface cfg
,08-17 10:41:34.941   873  1306 D WifiStateMachine: Start Dhcp Watchdog 2
,08-17 10:41:34.955   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 10:41:34.967   873  4041 D DhcpClient: Receive thread started
,08-17 10:41:35.053   873  1306 E native  : do suspend false
,08-17 10:41:35.076   873  1855 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 10:41:35.089   873  4041 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172642, domain null
,08-17 10:41:35.090   873  1855 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172642 seconds
,08-17 10:41:35.093   873  1855 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 10:41:35.110   873  4041 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 10:41:35.111   873  1855 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 10:41:35.116   372   871 D CommandListener: Setting iface cfg
,08-17 10:41:35.128   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 10:41:35.128   873  1855 D DhcpClient: Scheduling renewal in 86399s
,08-17 10:41:35.132   873  1306 E native  : do suspend true
,08-17 10:41:35.164   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 10:41:35.169   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 10:41:35.171   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 10:41:35.174   873  1308 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 10:41:35.187   873  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 10:41:35.227   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 10:41:35.228   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-17 10:41:35.229   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-17 10:41:35.230   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-17 10:41:35.231   873  1308 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-17 10:41:35.238   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 10:41:35.244   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-17 10:41:35.244   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-17 10:41:35.244   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-17 10:41:35.244   873  1308 D ConnectivityService:    accepting network in place of null
,08-17 10:41:35.244   873  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 10:41:35.245   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 10:41:35.246   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 10:41:35.258   873  4040 D NetlinkSocketObserver: NeighborEvent{elapsedMs=180965, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:41:35.276   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:41:35.309   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:41:35.313   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 10:41:35.313   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:41:35.314   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-17 10:41:35.316   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-17 10:41:35.337   873  4039 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.20.78,2a00:1450:4001:813::200e
,08-17 10:41:35.339  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:35.339  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:35.339  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:35.339  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:35.339  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:35.339  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:35.339  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:41:35.339  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:41:35.339  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:41:35.339  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:35.339  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:41:35.341  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:35.341  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:35.341  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:35.341  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:35.341  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:35.341  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:35.341  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:41:35.341  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:41:35.341  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:41:35.341  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:35.341  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:41:35.351  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:35.351  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:35.351  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:35.351  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:35.351  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:41:35.351  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:35.351  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:41:35.351  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:41:35.351  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:41:35.351  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:35.351  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:41:35.352  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 10:41:35.356  1731  1731 D SystemUpdateService: onCreate
,08-17 10:41:35.360  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 10:41:35.380  1731  4051 I SystemUpdateService: active receiver: enabled
,08-17 10:41:35.381  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 10:41:35.389  1731  2402 I iu.UploadsManager: num queued entries: 0
,08-17 10:41:35.390  1731  2402 I iu.UploadsManager: num updated entries: 0
,08-17 10:41:35.395  1731  2402 I iu.SyncManager: NEXT; no task
,08-17 10:41:35.393  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-17 10:41:35.392  1731  4051 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 10:41:35.397  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 10:41:35.399  3912  3912 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:41:35.403   873  4039 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 08:41:35 GMT], X-Android-Received-Millis=[1471423295403], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471423295376]}
,08-17 10:41:35.404   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 10:41:35.404   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-17 10:41:35.404   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 10:41:35.405   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 10:41:35.411  1731  4053 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-17 10:41:35.411  1731  4053 W BaseAppContext: Using Auth Proxy for data requests.
,08-17 10:41:35.414  1731  4053 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
08-17 10:41:35.414  3912  3912 D SprintDMHelper: simOperator: 
08-17 10:41:35.414  3912  3912 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 10:41:35.421  1731  4051 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 10:41:35.421  1731  4051 I SystemUpdateService: now status is 0 (complete)
,08-17 10:41:35.421  1731  4051 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 10:41:35.421  1731  4051 I SystemUpdateService: file has been verified
,08-17 10:41:35.430  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:35.437  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:35.422  1731  4051 I SystemUpdateService: OTA package size = 12249756
,08-17 10:41:35.470  1731  4051 I SystemUpdateService: showing system update notification
,08-17 10:41:35.515  1513  2199 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 10:41:35.515  1513  2199 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-17 10:41:35.515  1513  2199 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 10:41:35.515  1513  2199 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-17 10:41:35.519  1731  1731 D SystemUpdateService: onDestroy
,08-17 10:41:35.539  1731  4053 E MDM     : [179] SitrepService.a: Error sending sitrep.
,08-17 10:41:35.578  3038  4059 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 10:41:36.314   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 10:41:37.788   873  1928 D WifiService: setWifiEnabled: false pid=3758, uid=10000
,08-17 10:41:37.788   873  1928 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:41:37.817  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 10:41:37.824   873  1306 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-17 10:41:37.825   873  1306 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-17 10:41:37.825   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 10:41:37.825   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:41:37.844   873  1306 E native  : do suspend true
,08-17 10:41:37.859   873  1855 D DhcpClient: Clearing IP address
,08-17 10:41:37.859   372   871 D CommandListener: Clearing all IP addresses on wlan0
,08-17 10:41:37.865   372   871 D CommandListener: Setting iface cfg
,08-17 10:41:37.869  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:41:37.874  1513  4063 V NativeCrypto: Read error: ssl=0x9b092400: I/O error during system call, Connection timed out,
,08-17 10:41:37.876  1513  4063 V NativeCrypto: SSL shutdown failed: ssl=0x9b092400: I/O error during system call, Broken pipe
,08-17 10:41:37.885   873  2249 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-17 10:41:37.887   873  4039 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-17 10:41:37.894   873  4039 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-17 10:41:37.895   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-17 10:41:37.898   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-17 10:41:37.900   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 10:41:37.900   873  1306 D WifiStateMachine: Start Disconnecting Watchdog 2
08-17 10:41:37.901   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 10:41:37.901   873  1306 E native  : do suspend true
08-17 10:41:37.901   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 10:41:37.905   402   402 E Parcel  : Reading a NULL string not supported here.
,08-17 10:41:37.905   873  4041 D DhcpClient: Receive thread stopped
,08-17 10:41:37.907   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-17 10:41:37.911   372   871 D CommandListener: Clearing all IP addresses on wlan0
08-17 10:41:37.913   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-17 10:41:37.915   873  1308 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-17 10:41:37.926  1513  2257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-17 10:41:37.926  1513  2257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 10:41:37.926  1513  2257 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:41:37.926  1513  2257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:41:37.931   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:41:37.934  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:37.934  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:37.934  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:37.934  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:37.934  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:37.934  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:37.934  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:37.934  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:37.934  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:37.934  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:37.934  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:41:37.936  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:37.936  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:37.936  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:37.936  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:37.936  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:37.936  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:37.936  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:37.936  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:37.936  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:37.937  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:37.937  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:37.937  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:37.938  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:37.938  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:37.938  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:37.938  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:37.938  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:37.938  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:37.938  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:37.938  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:41:37.938  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:37.938  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:37.938  2147  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 10:41:37.939   873  1306 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-17 10:41:37.951  3480  3480 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-17 10:41:37.952  3480  3480 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 10:41:37.953  3480  3480 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-17 10:41:37.956   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:41:37.982   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:41:37.983   873  1308 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 10:41:37.983   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 10:41:37.985   873   890 D Tethering: MasterInitialState.processMessage what=3
08-17 10:41:37.988  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:37.988  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:37.990  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:37.994  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 10:41:37.998  1731  1731 D SystemUpdateService: onCreate
,08-17 10:41:38.000  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 10:41:38.009  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 10:41:38.011  1731  2402 I iu.UploadsManager: num queued entries: 0
,08-17 10:41:38.012  1731  2402 I iu.UploadsManager: num updated entries: 0
,08-17 10:41:38.016  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 10:41:38.017  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 10:41:38.018  3912  3912 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:41:38.022  3912  3912 D SprintDMHelper: simOperator: 
,08-17 10:41:38.022  3912  3912 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 10:41:38.043  3038  4080 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 10:41:38.043   372   871 E Netd    : netlink response contains error (No such file or directory)
,08-17 10:41:38.033  1731  4076 I SystemUpdateService: active receiver: enabled
08-17 10:41:38.044   873  1308 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-17 10:41:38.044   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 10:41:38.047  1731  2402 I iu.SyncManager: NEXT; no task
,08-17 10:41:38.054  1731  4076 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 10:41:38.055  1731  4076 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 10:41:38.055  1731  4076 I SystemUpdateService: now status is 0 (complete)
08-17 10:41:38.055  1731  4076 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 10:41:38.055  1731  4076 I SystemUpdateService: file has been verified
08-17 10:41:38.056  1731  4076 I SystemUpdateService: OTA package size = 12249756
,08-17 10:41:38.060  1731  4076 I SystemUpdateService: showing system update notification
,08-17 10:41:38.067  1731  1731 D SystemUpdateService: onDestroy
,08-17 10:41:42.842   873   890 I ActivityManager: Start proc 4085:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 10:41:42.963  4085  4085 D AdapterServiceConfig: Adding HeadsetService
,08-17 10:41:42.964  4085  4085 D AdapterServiceConfig: Adding A2dpService
,08-17 10:41:42.964  4085  4085 D AdapterServiceConfig: Adding HidService
,08-17 10:41:42.964  4085  4085 D AdapterServiceConfig: Adding HealthService
,08-17 10:41:42.964  4085  4085 D AdapterServiceConfig: Adding PanService
,08-17 10:41:42.965  4085  4085 D AdapterServiceConfig: Adding GattService
,08-17 10:41:42.965  4085  4085 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 10:41:42.982   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1232f11:true
,08-17 10:41:42.982  4085  4085 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 10:41:42.989  4085  4085 I bt_bluedroid: init
,08-17 10:41:42.989  4085  4097 I BluetoothAdapterState: Entering OffState
,08-17 10:41:42.996  4085  4098 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 10:41:42.996  4085  4098 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 10:41:42.996  4085  4098 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 10:41:42.997  4085  4098 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 10:41:42.999  4085  4085 I bt_bluedroid: get_profile_interface socket
,08-17 10:41:43.002  4085  4101 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-17 10:41:43.003  4085  4101 D BluetoothAdapterProperties: Name is: Nexus 6
08-17 10:41:43.004  4085  4085 I bt_bluedroid: get_profile_interface sdp
,08-17 10:41:43.011  4085  4096 I bt_bluedroid: config_hci_snoop_log
,08-17 10:41:43.014   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 10:41:43.069  4085  4097 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 10:41:43.069  4085  4097 D BluetoothAdapterProperties: Setting state to 14
08-17 10:41:43.070  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 10:41:43.074  4085  4097 D BluetoothBondStateMachine: make
,08-17 10:41:43.078  4085  4102 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 10:41:43.085  4085  4097 I BluetoothAdapterState: Entering PendingCommandState
,08-17 10:41:43.087  4085  4085 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 10:41:43.096  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:43.099  4085  4085 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 10:41:43.101  4085  4085 D BtGatt.GattService: Received start request. Starting profile...
08-17 10:41:43.101  4085  4085 D BtGatt.GattService: start()
,08-17 10:41:43.102  4085  4085 I bt_bluedroid: get_profile_interface gatt
08-17 10:41:43.104  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:43.104  4085  4085 D BtGatt.AdvertiseManager: advertise manager created
,08-17 10:41:43.117  4085  4085 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:41:43.118  4085  4085 V BluetoothAdapterState: isTurningOn()=false
,08-17 10:41:43.118  4085  4085 V BluetoothAdapterState: isBleTurningOn()=true
,08-17 10:41:43.118  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:43.120  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 10:41:43.121  4085  4097 I bt_bluedroid: enable
08-17 10:41:43.121  4085  4098 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 10:41:43.122  4085  4098 I bt_hci  : start_up
,08-17 10:41:43.141  4085  4098 I bt_vendor: alloc value 0xb39e5189
,08-17 10:41:43.141  4085  4098 I bt_vendor: init
08-17 10:41:43.141  4085  4098 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 10:41:43.142  4085  4098 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 10:41:43.250   873  1308 D ConnectivityService: handlePromptUnvalidated 101
,08-17 10:41:43.251  4085  4098 D bt_hci  : start_up starting async portion
,08-17 10:41:43.251  4085  4105 I bt_hci  : event_finish_startup
08-17 10:41:43.252  4085  4105 I bt_hci_h4: hal_open
,08-17 10:41:43.252  4085  4105 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 10:41:43.263  4085  4105 I bt_userial_vendor: device fd = 51 open
,08-17 10:41:43.293  4085  4105 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 10:41:43.324  4085  4105 D bt_hwcfg: Chipset BCM4354A2
,08-17 10:41:43.325  4085  4105 D bt_hwcfg: Target name = [BCM4354A2]
,08-17 10:41:43.326  4085  4105 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 10:41:43.990  4085  4105 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 10:41:43.991  4085  4105 D bt_hwcfg: Settlement delay -- 100 ms
08-17 10:41:43.991  4085  4105 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 10:41:44.108  4085  4105 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 10:41:44.110  4085  4105 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 10:41:44.139  4085  4105 I bt_hwcfg: vendor lib fwcfg completed
,08-17 10:41:44.139  4085  4105 I bt_vendor: firmware callback
,08-17 10:41:44.140  4085  4105 I bt_hci  : firmware_config_callback
,08-17 10:41:44.153  4085  4107 I bt_btu  : btu_task pending for preload complete event
,08-17 10:41:44.154  4085  4107 I bt_btu_task: Bluetooth chip preload is complete
,08-17 10:41:44.154  4085  4107 I bt_btu  : btu_task received preload complete event
,08-17 10:41:44.164  4085  4107 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 10:41:44.165  4085  4107 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 10:41:44.165  4085  4107 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 10:41:44.166  4085  4107 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 10:41:44.166  4085  4107 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 10:41:44.166  4085  4107 I         : BTE_InitTraceLevels -- TRC_A2D
,08-17 10:41:44.167  4085  4107 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-17 10:41:44.167  4085  4107 I         : BTE_InitTraceLevels -- TRC_BTM
,08-17 10:41:44.167  4085  4107 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 10:41:44.167  4085  4107 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 10:41:44.168  4085  4107 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 10:41:44.168  4085  4107 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 10:41:44.168  4085  4107 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 10:41:44.168  4085  4107 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 10:41:44.169  4085  4107 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 10:41:44.302  4085  4107 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3962d9d
,08-17 10:41:44.302  4085  4107 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3962d9d 
,08-17 10:41:44.313  4085  4101 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 10:41:44.314  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 10:41:44.315  4085  4101 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 10:41:44.318  4085  4101 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 10:41:44.323  4085  4101 D BluetoothAdapterProperties: Scan Mode:20
,08-17 10:41:44.323  4085  4101 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 10:41:44.324  4085  4101 D bt_hci  : do_postload posting postload work item
,08-17 10:41:44.324  4085  4105 I bt_hci  : event_postload
,08-17 10:41:44.324  4085  4105 I bt_vendor: sco_config_cb
,08-17 10:41:44.324  4085  4105 I bt_hci  : sco_config_callback postload finished.
08-17 10:41:44.329  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:44.329  4085  4105 I bt_vendor: low_power_mode_cb
08-17 10:41:44.330  4085  4101 D bt_bte_conf: Device ID record 1 : primary
08-17 10:41:44.330  4085  4101 D bt_bte_conf:   vendorId            = 000f
08-17 10:41:44.330  4085  4101 D bt_bte_conf:   vendorIdSource      = 0001
08-17 10:41:44.330  4085  4101 D bt_bte_conf:   product             = 1200
08-17 10:41:44.330  4085  4101 D bt_bte_conf:   version             = 1436,
08-17 10:41:44.330  4085  4101 D bt_bte_conf:   clientExecutableURL = 
08-17 10:41:44.330  4085  4101 D bt_bte_conf:   serviceDescription  = 
,08-17 10:41:44.330  4085  4101 D bt_bte_conf:   documentationURL    = 
08-17 10:41:44.330  4085  4101 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 10:41:44.331  4085  4098 D bt_stack_manager: event_start_up_stack finished
08-17 10:41:44.331  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 10:41:44.332  4085  4097 D BluetoothAdapterProperties: Setting state to 15
08-17 10:41:44.332  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 10:41:44.333  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:44.334  4085  4097 I BluetoothAdapterState: Entering BleOnState
08-17 10:41:44.338  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:44.341  4085  4097 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 10:41:44.341  4085  4097 D BluetoothAdapterProperties: Setting state to 11
08-17 10:41:44.341  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 10:41:44.354  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:44.356  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:44.356  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:44.357  4085  4085 D HeadsetService: Received start request. Starting profile...
08-17 10:41:44.358  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:44.363  4085  4085 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 10:41:44.363  4085  4085 D HeadsetStateMachine: make
,08-17 10:41:44.371  4085  4097 I BluetoothAdapterState: Entering PendingCommandState
,08-17 10:41:44.374  4085  4085 D HeadsetStateMachine: max_hf_connections = 1
08-17 10:41:44.374  4085  4085 I bt_bluedroid: get_profile_interface handsfree
,08-17 10:41:44.375  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-17 10:41:44.375  4085  4101 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 10:41:44.380  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:44.381  4085  4085 D A2dpService: Received start request. Starting profile...
,08-17 10:41:44.382  4085  4085 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 10:41:44.382  4085  4085 I bt_bluedroid: get_profile_interface avrcp
,08-17 10:41:44.390  4085  4085 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 10:41:44.390  4085  4085 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-17 10:41:44.390  4085  4085 D A2dpStateMachine: make
,08-17 10:41:44.393  4085  4085 I bt_bluedroid: get_profile_interface a2dp
,08-17 10:41:44.394  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 10:41:44.395  4085  4116 D A2dpStateMachine: Enter Disconnected: -2
,08-17 10:41:44.396  4085  4085 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 10:41:44.398  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:44.400  3858  3858 D BluetoothInputDevice: Proxy object connected
,08-17 10:41:44.401  4085  4085 D HidService: Received start request. Starting profile...
08-17 10:41:44.401  4085  4085 I bt_bluedroid: get_profile_interface hidhost
,08-17 10:41:44.401  3858  3858 D HidProfile: Bluetooth service connected
,08-17 10:41:44.401  4085  4085 D HidService: setHidService(): set to: null
08-17 10:41:44.401  4085  4101 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39443e5
08-17 10:41:44.402  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-17 10:41:44.406  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:41:44.408  4085  4085 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 10:41:44.409  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
08-17 10:41:44.410  4085  4085 D HealthService: Received start request. Starting profile...
,08-17 10:41:44.413  4085  4085 I bt_bluedroid: get_profile_interface health
,08-17 10:41:44.413  4085  4085 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 10:41:44.415  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:44.416  3858  3858 D BluetoothPan: BluetoothPAN Proxy object connected
,08-17 10:41:44.417  4085  4085 D PanService: Received start request. Starting profile...
08-17 10:41:44.417  3858  3858 D PanProfile: Bluetooth service connected
,08-17 10:41:44.417  4085  4085 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 10:41:44.418  4085  4085 I bt_bluedroid: get_profile_interface pan
08-17 10:41:44.418  4085  4101 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 10:41:44.423  4085  4085 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:44.426  3858  3858 D BluetoothMap: Proxy object connected
,08-17 10:41:44.426  3858  3858 D MapProfile: Bluetooth service connected
,08-17 10:41:44.426  4085  4085 D BluetoothMapService: Received start request. Starting profile...
08-17 10:41:44.426  4085  4085 D BluetoothMapService: start()
08-17 10:41:44.426  3858  3858 D BluetoothMap: getConnectedDevices()
,08-17 10:41:44.429  3858  3858 D BluetoothMap: Bluetooth is Not enabled
,08-17 10:41:44.431  4085  4085 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 10:41:44.433  4085  4085 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 10:41:44.433  4085  4085 D BluetoothMapAppObserver: createReceiver()
,08-17 10:41:44.435  4085  4085 D BluetoothMapAppObserver: initObservers()
,08-17 10:41:44.435  4085  4085 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 10:41:44.446  4085  4085 V BluetoothAdapterState: isTurningOff()=false
08-17 10:41:44.446  4085  4085 V BluetoothAdapterState: isTurningOn()=true
08-17 10:41:44.446  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:44.446  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:41:44.450  4085  4114 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 10:41:44.450  4085  4085 V BluetoothAdapterState: isTurningOff()=false
08-17 10:41:44.450  4085  4085 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:41:44.450  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:41:44.450  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:44.451  4085  4085 V BluetoothAdapterState: isTurningOff()=false
08-17 10:41:44.451  4085  4085 V BluetoothAdapterState: isTurningOn()=true
08-17 10:41:44.451  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:44.451  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:41:44.453  4085  4085 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:41:44.453  4085  4085 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:41:44.453  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:41:44.453  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:44.453  4085  4085 V BluetoothAdapterState: isTurningOff()=false
08-17 10:41:44.453  4085  4085 V BluetoothAdapterState: isTurningOn()=true
,08-17 10:41:44.453  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:41:44.453  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:44.453  4085  4085 V BluetoothAdapterState: isTurningOff()=false
08-17 10:41:44.454  4085  4085 V BluetoothAdapterState: isTurningOn()=true
08-17 10:41:44.454  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:41:44.454  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:44.454  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 10:41:44.454  4085  4097 D BluetoothAdapterProperties: ScanMode =  20
08-17 10:41:44.454  4085  4097 D BluetoothAdapterProperties: State =  11
,08-17 10:41:44.457  4085  4101 D BluetoothAdapterProperties: Scan Mode:21
08-17 10:41:44.458  4085  4101 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 10:41:44.458  4085  4097 D BluetoothAdapterProperties: Setting state to 12
08-17 10:41:44.459  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 10:41:44.460   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 10:41:44.461  1363  1388 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:41:44.462  4085  4097 I BluetoothAdapterState: Entering OnState
08-17 10:41:44.463  3858  3868 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 10:41:44.464  4085  4085 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 10:41:44.464  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:44.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:44.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:44.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:44.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:41:44.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:44.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:44.464  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:44.465  1363  2253 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 10:41:44.466  4085  4085 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 10:41:44.467  3858  3869 D BluetoothMap: onBluetoothStateChange: up=true
08-17 10:41:44.468  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:44.468  1363  2013 D BluetoothPan: onBluetoothStateChange on: true
08-17 10:41:44.469  4085  4085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:41:44.470  1363  1388 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 10:41:44.470  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 10:41:44.471  1363  1363 D PanProfile: Bluetooth service connected
08-17 10:41:44.472   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 10:41:44.474  4085  4085 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:41:44.474  1363  2253 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 10:41:44.474  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:44.474  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:44.474  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:44.474  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:44.474  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:41:44.474  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:44.474  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:44.474  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:41:44.475  4085  4085 D ObexServerSockets: Succeed to create listening sockets 
08-17 10:41:44.476  4085  4085 D ObexServerSockets0: startAccept()
08-17 10:41:44.476  4085  4085 D ObexServerSockets0: prepareForNewConnect()
08-17 10:41:44.478  1363  1363 D BluetoothInputDevice: Proxy object connected
,08-17 10:41:44.479   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:41:44.478  1363  1363 D HidProfile: Bluetooth service connected
08-17 10:41:44.479   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:41:44.479  3858  3868 D BluetoothPan: onBluetoothStateChange on: true
08-17 10:41:44.479  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:41:44.479  1363  1389 D BluetoothMap: onBluetoothStateChange: up=true
08-17 10:41:44.479  4085  4085 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-17 10:41:44.480  4085  4085 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-17 10:41:44.482  1920  3469 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:41:44.482   873   873 D BluetoothA2dp: Proxy object connected
08-17 10:41:44.483  3858  3869 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 10:41:44.484  4085  4123 D ObexServerSockets0: Accepting socket connection...
,08-17 10:41:44.484  4085  4122 D ObexServerSockets0: Accepting socket connection...
08-17 10:41:44.485  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:44.485  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:44.485  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:44.485  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:44.485  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:41:44.485  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:44.485  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:44.485  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:44.487  4085  4085 D BluetoothMapService: onReceive
,08-17 10:41:44.487  4085  4085 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:41:44.487  4085  4085 D BluetoothMapService: STATE_ON
08-17 10:41:44.488  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:44.490  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:44.490  1363  1363 D BluetoothMap: Proxy object connected
,08-17 10:41:44.490  1363  1363 D MapProfile: Bluetooth service connected
08-17 10:41:44.490  1363  1363 D BluetoothMap: getConnectedDevices()
08-17 10:41:44.490  3858  3858 D LocalBluetoothProfileManager: Adding local A2DP profile
08-17 10:41:44.490   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 10:41:44.492  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:44.494  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:44.497  3858  3858 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-17 10:41:44.500  1363  1363 D BluetoothA2dp: Proxy object connected
,08-17 10:41:44.506  3858  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 10:41:44.508  4085  4085 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 10:41:44.508  4085  4085 D ObexServerSockets0: prepareForNewConnect()
,08-17 10:41:44.512  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:41:44.511  3858  3858 D BluetoothA2dp: Proxy object connected
,08-17 10:41:44.522  3858  3858 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:41:44.522  1363  1363 D BluetoothPbap: Proxy object connected
08-17 10:41:44.522  1363  1363 D PbapServerProfile: Bluetooth service connected
08-17 10:41:44.523  3858  3858 D BluetoothPbap: Proxy object connected
,08-17 10:41:44.523  3858  3858 D PbapServerProfile: Bluetooth service connected
,08-17 10:41:44.529  4085  4132 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:41:44.551  4085  4136 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:41:44.553  4085  4136 I BtOppRfcommListener: Accept thread started.
,08-17 10:41:44.561  1920  2119 D BluetoothHeadset: Proxy object connected
,08-17 10:41:44.562   873   873 D BluetoothHeadset: Proxy object connected
,08-17 10:41:44.562  1363  2253 D BluetoothHeadset: Proxy object connected,
08-17 10:41:44.562  1363  1363 D HeadsetProfile: Bluetooth service connected
08-17 10:41:44.563  1363  1389 D BluetoothHeadset: Proxy object connected
,08-17 10:41:44.563   873   873 D BluetoothHeadset: Proxy object connected
,08-17 10:41:44.563   873   873 D BluetoothHeadset: Proxy object connected
08-17 10:41:44.565  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-17 10:41:44.578   873   890 D BluetoothHeadset: Proxy object connected
,08-17 10:41:44.580   873   890 D BluetoothHeadset: Proxy object connected
,08-17 10:41:44.582  1920  1935 D BluetoothHeadset: Proxy object connected
,08-17 10:41:44.603  3858  3868 D BluetoothHeadset: Proxy object connected
,08-17 10:41:44.604  3858  3858 D HeadsetProfile: Bluetooth service connected
,08-17 10:41:47.803  4085  4097 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 10:41:47.804  4085  4097 D BluetoothAdapterProperties: Setting state to 13
,08-17 10:41:47.804  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 10:41:47.806  4085  4097 D BluetoothAdapterProperties: onBluetoothDisable()
,08-17 10:41:47.808  4085  4097 I BluetoothAdapterState: Entering PendingCommandState
,08-17 10:41:47.817  4085  4085 D BluetoothMapService: onReceive
08-17 10:41:47.818  4085  4085 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 10:41:47.818  4085  4085 D BluetoothMapService: STATE_TURNING_OFF
,08-17 10:41:47.819  4085  4085 D BluetoothMapService: MAP Service closeService in
08-17 10:41:47.819  4085  4085 D BluetoothMapMasInstance0: MAP Service shutdown
08-17 10:41:47.819  4085  4085 D ObexServerSockets0: shutdown(block = true)
08-17 10:41:47.820  4085  4122 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-17 10:41:47.823  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:47.824  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:47.824  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:47.824  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:47.824  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:47.824  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:47.824  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:47.824  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:47.824  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:41:47.825  4085  4085 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 10:41:47.826  4085  4123 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 10:41:47.827  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:47.827  4085  4110 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-17 10:41:47.827  4085  4085 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 10:41:47.828  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:47.829  4085  4085 I BtOppRfcommListener: stopping Accept Thread
,08-17 10:41:47.829  4085  4136 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-17 10:41:47.830  4085  4136 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 10:41:47.834  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 10:41:47.834  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:47.834  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:47.834  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:47.834  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:47.834  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:47.834  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:47.834  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:47.834  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:47.835  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:47.835  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:47.837  4085  4101 D BluetoothAdapterProperties: Scan Mode:20
,08-17 10:41:47.838  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-17 10:41:47.839  3858  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 10:41:47.839  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:47.839  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:47.839  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:47.839  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:47.839  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:47.839  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 10:41:47.839  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:47.839  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:47.839  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:47.840  3758  3758 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 10:41:47.840  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:41:47.843  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:47.844  4085  4085 D HeadsetService: Received stop request...Stopping profile...
,08-17 10:41:47.844  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:47.846  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:47.848  1920  3470 D BluetoothHeadset: Proxy object disconnected
08-17 10:41:47.848   873   873 D BluetoothHeadset: Proxy object disconnected
,08-17 10:41:47.849  4085  4085 D A2dpService: Received stop request...Stopping profile...
,08-17 10:41:47.849  4085  4116 D A2dpStateMachine: Exit Disconnected: -1
,08-17 10:41:47.853  4085  4085 V BluetoothAdapterState: isTurningOff()=true
08-17 10:41:47.856  4085  4085 V BluetoothAdapterState: isTurningOn()=false
08-17 10:41:47.856  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:41:47.849  1363  1389 D BluetoothHeadset: Proxy object disconnected
08-17 10:41:47.856  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:41:47.856   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 10:41:47.857  3858  3869 D BluetoothHeadset: Proxy object disconnected
08-17 10:41:47.857  4085  4085 D HidService: Received stop request...Stopping profile...
08-17 10:41:47.857  4085  4085 D HidService: Stopping Bluetooth HidService
,08-17 10:41:47.857   873   873 D BluetoothHeadset: Proxy object disconnected
08-17 10:41:47.852  1363  1363 D BluetoothA2dp: Proxy object disconnected
08-17 10:41:47.857   873   873 D BluetoothA2dp: Proxy object disconnected
,08-17 10:41:47.857  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-17 10:41:47.858  1363  1363 D BluetoothInputDevice: Proxy object disconnected
08-17 10:41:47.858  1363  1363 D HidProfile: Bluetooth service disconnected
08-17 10:41:47.858  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 10:41:47.860  4085  4085 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...,
08-17 10:41:47.860  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 10:41:47.860  4085  4085 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 10:41:47.860  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:41:47.860  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 10:41:47.860  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:41:47.861  4085  4101 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-17 10:41:47.861  4085  4085 D HealthService: Received stop request...Stopping profile...
08-17 10:41:47.861  3858  3858 D DockEventReceiver: finishStartingService: stopping service
08-17 10:41:47.863  3858  3858 D BluetoothA2dp: Proxy object disconnected
,08-17 10:41:47.863  4085  4085 V BluetoothAdapterState: isTurningOff()=true
08-17 10:41:47.863  3858  3858 D HeadsetProfile: Bluetooth service disconnected
08-17 10:41:47.863  4085  4085 V BluetoothAdapterState: isTurningOn()=false
08-17 10:41:47.863  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:47.863  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:47.863  3858  3858 D BluetoothInputDevice: Proxy object disconnected
08-17 10:41:47.863  3858  3858 D HidProfile: Bluetooth service disconnected
08-17 10:41:47.864  4085  4085 D PanService: Received stop request...Stopping profile...
,08-17 10:41:47.865  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 10:41:47.865  1363  1363 D PanProfile: Bluetooth service disconnected
08-17 10:41:47.866  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 10:41:47.867  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:41:47.867  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:41:47.867  4085  4107 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-17 10:41:47.867  4085  4085 D BluetoothMapService: Received stop request...Stopping profile...
08-17 10:41:47.867  4085  4107 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:41:47.867  4085  4085 D BluetoothMapService: stop()
08-17 10:41:47.867  4085  4107 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 10:41:47.867  4085  4107 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 10:41:47.864  3858  3858 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 10:41:47.868  4085  4085 D BluetoothMapAppObserver: deinitObservers()
,08-17 10:41:47.868  4085  4085 D BluetoothMapAppObserver: removeReceiver()
08-17 10:41:47.868  3858  3858 D PanProfile: Bluetooth service disconnected
08-17 10:41:47.869  1363  1363 D BluetoothMap: Proxy object disconnected
08-17 10:41:47.869  1363  1363 D MapProfile: Bluetooth service disconnected
08-17 10:41:47.870  3858  3858 D BluetoothMap: Proxy object disconnected
,08-17 10:41:47.870  3858  3858 D MapProfile: Bluetooth service disconnected
08-17 10:41:47.871  1363  1363 D BluetoothPbap: Proxy object disconnected
08-17 10:41:47.871  1363  1363 D PbapServerProfile: Bluetooth service disconnected
08-17 10:41:47.871  3858  3858 D BluetoothPbap: Proxy object disconnected
08-17 10:41:47.871  3858  3858 D PbapServerProfile: Bluetooth service disconnected
,08-17 10:41:47.871  4085  4085 V BluetoothAdapterState: isTurningOff()=true
08-17 10:41:47.871  4085  4085 V BluetoothAdapterState: isTurningOn()=false
08-17 10:41:47.872  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:47.872  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:47.872  4085  4085 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...,
08-17 10:41:47.872  4085  4101 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 10:41:47.872  4085  4085 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 10:41:47.873  4085  4085 V BluetoothAdapterState: isTurningOff()=true
,08-17 10:41:47.873  4085  4085 V BluetoothAdapterState: isTurningOn()=false
,08-17 10:41:47.873  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:47.873  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:47.873  4085  4085 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-17 10:41:47.873  4085  4101 E bt_btif : btif_in_execute_service_request: Unknown service being enabled,
08-17 10:41:47.873  4085  4085 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 10:41:47.874  4085  4085 V BluetoothAdapterState: isTurningOff()=true
08-17 10:41:47.874  4085  4085 V BluetoothAdapterState: isTurningOn()=false
08-17 10:41:47.874  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:47.874  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:41:47.874  4085  4085 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 10:41:47.874  4085  4085 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 10:41:47.875  4085  4085 D BluetoothMapService: MAP Service closeService in
,08-17 10:41:47.875  4085  4085 V BluetoothAdapterState: isTurningOff()=true
08-17 10:41:47.875  4085  4085 V BluetoothAdapterState: isTurningOn()=false
08-17 10:41:47.875  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:47.875  4085  4085 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:47.875  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 10:41:47.875  4085  4097 D BluetoothAdapterProperties: Setting state to 15
,08-17 10:41:47.875  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 10:41:47.876  4085  4097 I BluetoothAdapterState: Entering BleOnState
08-17 10:41:47.876  4085  4085 D BluetoothMapService: cleanup()
08-17 10:41:47.876  4085  4085 D BluetoothMapService: MAP Service closeService in
08-17 10:41:47.878   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 10:41:47.878  3858  3869 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:41:47.878  1363  2253 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:41:47.879  3858  3868 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 10:41:47.879  1363  1388 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:41:47.880  3858  3869 D BluetoothMap: onBluetoothStateChange: up=false
08-17 10:41:47.880  3858  3868 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 10:41:47.881  1363  2013 D BluetoothPan: onBluetoothStateChange on: false
08-17 10:41:47.881  1363  1389 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 10:41:47.881   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 10:41:47.882  1363  2253 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 10:41:47.882   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:41:47.882   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:41:47.882  3858  3869 D BluetoothPan: onBluetoothStateChange on: false
08-17 10:41:47.883  1363  1388 D BluetoothMap: onBluetoothStateChange: up=false
08-17 10:41:47.883  1920  1934 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 10:41:47.884  3858  3868 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 10:41:47.884  4085  4097 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 10:41:47.884  4085  4097 D BluetoothAdapterProperties: Setting state to 16
08-17 10:41:47.885  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 10:41:47.888  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:47.889  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:47.891  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:47.891  3858  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 10:41:47.888  4085  4097 D BluetoothAdapterProperties: onBleDisable
08-17 10:41:47.891  4085  4097 I BluetoothAdapterState: Entering PendingCommandState
08-17 10:41:47.892  4085  4098 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 10:41:47.893  4085  4107 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 10:41:47.893  4085  4107 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 10:41:47.894  4085  4101 D BluetoothAdapterProperties: Scan Mode:20
08-17 10:41:47.896  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:47.897  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:47.898  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:47.898  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:41:47.906  3858  3858 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:41:48.097  4085  4101 I bt_hci  : shut_down
,08-17 10:41:48.097  4085  4105 D bt_hwcfg: hw_epilog_process
,08-17 10:41:48.109  4085  4105 I bt_vendor: low_power_mode_cb
,08-17 10:41:48.132  4085  4105 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 10:41:48.133  4085  4105 I bt_vendor: epilog_cb
08-17 10:41:48.133  4085  4105 I bt_hci  : epilog_finished_callback
,08-17 10:41:48.140  4085  4101 I bt_hci_h4: hal_close
,08-17 10:41:48.142  4085  4101 I bt_userial_vendor: device fd = 51 close
,08-17 10:41:48.258  4085  4098 D bt_stack_manager: event_shut_down_stack finished.
08-17 10:41:48.259  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 10:41:48.264  4085  4097 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 10:41:48.265  4085  4085 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 10:41:48.267  4085  4085 D BtGatt.GattService: Received stop request...Stopping profile...
,08-17 10:41:48.268  4085  4085 D BtGatt.GattService: stop()
08-17 10:41:48.269  4085  4085 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 10:41:48.276  4085  4085 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:41:48.276  4085  4085 V BluetoothAdapterState: isTurningOn()=false
,08-17 10:41:48.276  4085  4085 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:41:48.277  4085  4085 V BluetoothAdapterState: isBleTurningOff()=true
,08-17 10:41:48.277  4085  4097 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 10:41:48.278  4085  4097 D BluetoothAdapterProperties: Setting state to 10
08-17 10:41:48.279  4085  4097 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-17 10:41:48.281  4085  4097 I BluetoothAdapterState: Entering OffState
,08-17 10:41:48.284   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 10:41:48.311  4085  4085 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 10:41:48.311  4085  4085 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-17 10:41:48.314  4085  4098 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 10:41:48.318  4085  4098 D bt_stack_manager: event_clean_up_stack finished.
,08-17 10:41:48.318  4085  4085 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 10:41:48.321  4085  4085 I art     : System.exit called, status: 0
,08-17 10:41:48.321  4085  4085 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 10:41:48.373   873  1933 I ActivityManager: Process com.android.bluetooth (pid 4085) has died
,08-17 10:41:52.801  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 10:41:52.801  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:52.808  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:41:52.809  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@121fcce removed from the list
,08-17 10:41:52.809  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:52.809  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:52.810  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:52.815  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:41:52.816  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33cb2fc added. We now have 4 listener(s)
,08-17 10:41:52.817  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:41:52.820  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:41:52.820  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33cb2fc removed from the list
,08-17 10:41:52.820  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:41:52.820  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:41:52.820  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:41:52.821  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:41:52.821  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a492d85 added. We now have 4 listener(s)
08-17 10:41:52.821  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:41:57.830  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:57.877   873   890 I ActivityManager: Start proc 4146:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 10:41:58.007  4146  4146 D AdapterServiceConfig: Adding HeadsetService
,08-17 10:41:58.007  4146  4146 D AdapterServiceConfig: Adding A2dpService
08-17 10:41:58.008  4146  4146 D AdapterServiceConfig: Adding HidService
08-17 10:41:58.008  4146  4146 D AdapterServiceConfig: Adding HealthService
08-17 10:41:58.008  4146  4146 D AdapterServiceConfig: Adding PanService
,08-17 10:41:58.008  4146  4146 D AdapterServiceConfig: Adding GattService
08-17 10:41:58.009  4146  4146 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 10:41:58.023  4146  4146 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 10:41:58.023   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a88a26a:true
,08-17 10:41:58.028  4146  4146 I bt_bluedroid: init
,08-17 10:41:58.029  4146  4158 I BluetoothAdapterState: Entering OffState
,08-17 10:41:58.035  4146  4159 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 10:41:58.036  4146  4159 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 10:41:58.036  4146  4159 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-17 10:41:58.036  4146  4159 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 10:41:58.038  4146  4146 I bt_bluedroid: get_profile_interface socket
08-17 10:41:58.040  4146  4146 I bt_bluedroid: get_profile_interface sdp
,08-17 10:41:58.044  4146  4162 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 10:41:58.045  4146  4157 I bt_bluedroid: config_hci_snoop_log
,08-17 10:41:58.048  4146  4162 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 10:41:58.051   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 10:41:58.064  4146  4158 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 10:41:58.065  4146  4158 D BluetoothAdapterProperties: Setting state to 14
,08-17 10:41:58.065  4146  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 10:41:58.070  4146  4158 D BluetoothBondStateMachine: make
,08-17 10:41:58.075  4146  4163 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 10:41:58.085  4146  4158 I BluetoothAdapterState: Entering PendingCommandState
08-17 10:41:58.086  4146  4146 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 10:41:58.091  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:58.092  4146  4146 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 10:41:58.093  4146  4146 D BtGatt.GattService: Received start request. Starting profile...
08-17 10:41:58.093  4146  4146 D BtGatt.GattService: start()
08-17 10:41:58.093  4146  4146 I bt_bluedroid: get_profile_interface gatt
,08-17 10:41:58.094  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
08-17 10:41:58.095  4146  4146 D BtGatt.AdvertiseManager: advertise manager created
,08-17 10:41:58.109  4146  4146 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:41:58.110  4146  4146 V BluetoothAdapterState: isTurningOn()=false
,08-17 10:41:58.110  4146  4146 V BluetoothAdapterState: isBleTurningOn()=true
,08-17 10:41:58.110  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:58.111  4146  4158 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-17 10:41:58.112  4146  4158 I bt_bluedroid: enable
08-17 10:41:58.113  4146  4159 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-17 10:41:58.114  4146  4159 I bt_hci  : start_up
,08-17 10:41:58.129  4146  4159 I bt_vendor: alloc value 0xb39e5189
08-17 10:41:58.129  4146  4159 I bt_vendor: init
08-17 10:41:58.129  4146  4159 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 10:41:58.130  4146  4159 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 10:41:58.237  4146  4159 D bt_hci  : start_up starting async portion,
08-17 10:41:58.238  4146  4166 I bt_hci  : event_finish_startup
08-17 10:41:58.238  4146  4166 I bt_hci_h4: hal_open
08-17 10:41:58.238  4146  4166 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 10:41:58.250  4146  4166 I bt_userial_vendor: device fd = 51 open
,08-17 10:41:58.281  4146  4166 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 10:41:58.312  4146  4166 D bt_hwcfg: Chipset BCM4354A2
,08-17 10:41:58.312  4146  4166 D bt_hwcfg: Target name = [BCM4354A2]
,08-17 10:41:58.313  4146  4166 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 10:41:59.157  4146  4166 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 10:41:59.158  4146  4166 D bt_hwcfg: Settlement delay -- 100 ms
08-17 10:41:59.159  4146  4166 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 10:41:59.277  4146  4166 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 10:41:59.278  4146  4166 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 10:41:59.306  4146  4166 I bt_hwcfg: vendor lib fwcfg completed
,08-17 10:41:59.306  4146  4166 I bt_vendor: firmware callback
08-17 10:41:59.307  4146  4166 I bt_hci  : firmware_config_callback
,08-17 10:41:59.320  4146  4168 I bt_btu  : btu_task pending for preload complete event
,08-17 10:41:59.321  4146  4168 I bt_btu_task: Bluetooth chip preload is complete
,08-17 10:41:59.321  4146  4168 I bt_btu  : btu_task received preload complete event
,08-17 10:41:59.330  4146  4168 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 10:41:59.331  4146  4168 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 10:41:59.331  4146  4168 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 10:41:59.331  4146  4168 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 10:41:59.332  4146  4168 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 10:41:59.332  4146  4168 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 10:41:59.332  4146  4168 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 10:41:59.332  4146  4168 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 10:41:59.333  4146  4168 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 10:41:59.333  4146  4168 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 10:41:59.333  4146  4168 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 10:41:59.333  4146  4168 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 10:41:59.334  4146  4168 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 10:41:59.334  4146  4168 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 10:41:59.334  4146  4168 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 10:41:59.481  4146  4168 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3962d9d
,08-17 10:41:59.481  4146  4168 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3962d9d 
,08-17 10:41:59.495  4146  4162 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 10:41:59.496  4146  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 10:41:59.497  4146  4162 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 10:41:59.499  4146  4162 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 10:41:59.501  4146  4162 D BluetoothAdapterProperties: Scan Mode:20
,08-17 10:41:59.502  4146  4162 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 10:41:59.502  4146  4162 D bt_hci  : do_postload posting postload work item
08-17 10:41:59.503  4146  4166 I bt_hci  : event_postload
,08-17 10:41:59.503  4146  4166 I bt_vendor: sco_config_cb
,08-17 10:41:59.503  4146  4166 I bt_hci  : sco_config_callback postload finished.
,08-17 10:41:59.506  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:59.507  4146  4162 D bt_bte_conf: Device ID record 1 : primary
,08-17 10:41:59.507  4146  4162 D bt_bte_conf:   vendorId            = 000f
08-17 10:41:59.508  4146  4166 I bt_vendor: low_power_mode_cb
08-17 10:41:59.510  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:59.507  4146  4162 D bt_bte_conf:   vendorIdSource      = 0001
08-17 10:41:59.510  4146  4162 D bt_bte_conf:   product             = 1200
08-17 10:41:59.511  4146  4162 D bt_bte_conf:   version             = 1436
,08-17 10:41:59.513  4146  4162 D bt_bte_conf:   clientExecutableURL = 
08-17 10:41:59.513  4146  4162 D bt_bte_conf:   serviceDescription  = 
08-17 10:41:59.513  4146  4162 D bt_bte_conf:   documentationURL    = 
08-17 10:41:59.514  4146  4162 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 10:41:59.515  4146  4159 D bt_stack_manager: event_start_up_stack finished
,08-17 10:41:59.516  4146  4158 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-17 10:41:59.517  4146  4158 D BluetoothAdapterProperties: Setting state to 15
08-17 10:41:59.517  4146  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 10:41:59.518  4146  4158 I BluetoothAdapterState: Entering BleOnState
,08-17 10:41:59.526  4146  4158 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-17 10:41:59.526  4146  4158 D BluetoothAdapterProperties: Setting state to 11
,08-17 10:41:59.526  4146  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-17 10:41:59.541  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
08-17 10:41:59.544  4146  4146 D HeadsetService: Received start request. Starting profile...
08-17 10:41:59.547  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:59.549  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:59.551  4146  4146 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 10:41:59.552  4146  4146 D HeadsetStateMachine: make
,08-17 10:41:59.562  4146  4158 I BluetoothAdapterState: Entering PendingCommandState
,08-17 10:41:59.568  4146  4146 D HeadsetStateMachine: max_hf_connections = 1
,08-17 10:41:59.569  4146  4146 I bt_bluedroid: get_profile_interface handsfree
,08-17 10:41:59.569  4146  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-17 10:41:59.569  4146  4162 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 10:41:59.573  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:59.574  4146  4146 D A2dpService: Received start request. Starting profile...
,08-17 10:41:59.574  4146  4146 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-17 10:41:59.575  4146  4146 I bt_bluedroid: get_profile_interface avrcp
,08-17 10:41:59.581  4146  4146 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 10:41:59.581  4146  4146 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-17 10:41:59.581  4146  4146 D A2dpStateMachine: make
,08-17 10:41:59.583  4146  4146 I bt_bluedroid: get_profile_interface a2dp
,08-17 10:41:59.584  4146  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 10:41:59.585  4146  4176 D A2dpStateMachine: Enter Disconnected: -2
,08-17 10:41:59.587  4146  4146 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 10:41:59.588  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:59.589  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 10:41:59.589  4146  4146 D HidService: Received start request. Starting profile...
,08-17 10:41:59.589  4146  4146 I bt_bluedroid: get_profile_interface hidhost
08-17 10:41:59.589  4146  4146 D HidService: setHidService(): set to: null
,08-17 10:41:59.589  4146  4162 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39443e5
08-17 10:41:59.589  4146  4162 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 10:41:59.589  4146  4146 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-17 10:41:59.590  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:59.591  4146  4146 D HealthService: Received start request. Starting profile...
,08-17 10:41:59.592  4146  4146 I bt_bluedroid: get_profile_interface health
,08-17 10:41:59.593  4146  4146 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 10:41:59.593  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:59.594  4146  4146 D PanService: Received start request. Starting profile...
,08-17 10:41:59.594  4146  4146 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-17 10:41:59.594  4146  4146 I bt_bluedroid: get_profile_interface pan
,08-17 10:41:59.595  4146  4162 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 10:41:59.596  4146  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
,08-17 10:41:59.597  4146  4146 D BluetoothMapService: Received start request. Starting profile...
,08-17 10:41:59.597  4146  4146 D BluetoothMapService: start(),
,08-17 10:41:59.599  4146  4146 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 10:41:59.600  4146  4146 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 10:41:59.600  4146  4146 D BluetoothMapAppObserver: createReceiver()
,08-17 10:41:59.601  4146  4146 D BluetoothMapAppObserver: initObservers()
,08-17 10:41:59.601  4146  4146 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 10:41:59.607  4146  4146 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:41:59.608  4146  4146 V BluetoothAdapterState: isTurningOn()=true
08-17 10:41:59.608  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:59.608  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:59.609  4146  4174 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 10:41:59.610  4146  4146 V BluetoothAdapterState: isTurningOff()=false
08-17 10:41:59.610  4146  4146 V BluetoothAdapterState: isTurningOn()=true
08-17 10:41:59.610  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:59.610  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:59.610  4146  4146 V BluetoothAdapterState: isTurningOff()=false
08-17 10:41:59.610  4146  4146 V BluetoothAdapterState: isTurningOn()=true
08-17 10:41:59.610  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:59.610  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 10:41:59.612  4146  4146 V BluetoothAdapterState: isTurningOff()=false
08-17 10:41:59.612  4146  4146 V BluetoothAdapterState: isTurningOn()=true
08-17 10:41:59.612  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:59.613  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:59.613  4146  4146 V BluetoothAdapterState: isTurningOff()=false
,08-17 10:41:59.613  4146  4146 V BluetoothAdapterState: isTurningOn()=true
08-17 10:41:59.613  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
08-17 10:41:59.613  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:59.613  4146  4146 V BluetoothAdapterState: isTurningOff()=false
08-17 10:41:59.613  4146  4146 V BluetoothAdapterState: isTurningOn()=true
08-17 10:41:59.613  4146  4146 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 10:41:59.613  4146  4146 V BluetoothAdapterState: isBleTurningOff()=false
08-17 10:41:59.613  4146  4158 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-17 10:41:59.613  4146  4158 D BluetoothAdapterProperties: ScanMode =  20
08-17 10:41:59.614  4146  4158 D BluetoothAdapterProperties: State =  11
08-17 10:41:59.614  4146  4158 D BluetoothAdapterProperties: Setting state to 12
08-17 10:41:59.615  4146  4158 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 10:41:59.615   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:41:59.616  4146  4158 I BluetoothAdapterState: Entering OnState
,08-17 10:41:59.616  4146  4162 D BluetoothAdapterProperties: Scan Mode:21
08-17 10:41:59.616  4146  4162 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 10:41:59.616  3858  3868 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 10:41:59.618  1363  2013 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:41:59.619  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:59.619  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:59.619  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:59.619  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:59.619  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:41:59.619  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:59.619  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:59.619  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:59.619  3858  3869 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 10:41:59.621  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:41:59.621  1363  1389 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 10:41:59.623  1363  1363 D BluetoothA2dp: Proxy object connected
08-17 10:41:59.624  3858  3868 D BluetoothMap: onBluetoothStateChange: up=true
08-17 10:41:59.624  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:41:59.624  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:41:59.624  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:41:59.624  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:41:59.624  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:41:59.624  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:41:59.624  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:41:59.624  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 10:41:59.626  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 10:41:59.626  3858  3869 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:41:59.626  1363  1388 D BluetoothPan: onBluetoothStateChange on: true
08-17 10:41:59.627  4146  4146 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 10:41:59.627  4146  4146 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 10:41:59.628  1363  2013 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 10:41:59.629  4146  4146 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:41:59.629   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 10:41:59.630   873   873 D BluetoothA2dp: Proxy object connected
,08-17 10:41:59.630  1363  2253 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 10:41:59.632  4146  4146 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:41:59.632  3858  3858 D BluetoothA2dp: Proxy object connected
08-17 10:41:59.633  4146  4146 D ObexServerSockets: Succeed to create listening sockets 
08-17 10:41:59.633  4146  4146 D ObexServerSockets0: startAccept()
08-17 10:41:59.633  4146  4146 D ObexServerSockets0: prepareForNewConnect()
08-17 10:41:59.634  4146  4146 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-17 10:41:59.634  4146  4146 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 10:41:59.635   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 10:41:59.635  4146  4184 D ObexServerSockets0: Accepting socket connection...
08-17 10:41:59.636  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 10:41:59.636  1363  1363 D PanProfile: Bluetooth service connected
08-17 10:41:59.636  4146  4183 D ObexServerSockets0: Accepting socket connection...
08-17 10:41:59.636  1363  1363 D BluetoothInputDevice: Proxy object connected
08-17 10:41:59.637  1363  1363 D HidProfile: Bluetooth service connected
08-17 10:41:59.637   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:41:59.637  3858  3869 D BluetoothPan: onBluetoothStateChange on: true
,08-17 10:41:59.639  3858  3858 D BluetoothMap: Proxy object connected
08-17 10:41:59.639  3858  3858 D MapProfile: Bluetooth service connected,
08-17 10:41:59.639  3858  3858 D BluetoothMap: getConnectedDevices()
08-17 10:41:59.639  1363  2013 D BluetoothMap: onBluetoothStateChange: up=true
08-17 10:41:59.641  1363  1363 D BluetoothMap: Proxy object connected
08-17 10:41:59.641  1920  3470 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 10:41:59.641  1363  1363 D MapProfile: Bluetooth service connected
08-17 10:41:59.641  1363  1363 D BluetoothMap: getConnectedDevices()
08-17 10:41:59.641  3858  3858 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 10:41:59.641  3858  3858 D PanProfile: Bluetooth service connected
08-17 10:41:59.641  3858  4182 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 10:41:59.644   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 10:41:59.645  4146  4146 D BluetoothMapService: onReceive
08-17 10:41:59.645  4146  4146 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 10:41:59.646  4146  4146 D BluetoothMapService: STATE_ON
,08-17 10:41:59.646  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:41:59.644  3858  3858 D BluetoothInputDevice: Proxy object connected
08-17 10:41:59.646  3858  3858 D HidProfile: Bluetooth service connected
08-17 10:41:59.647  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:41:59.653  3858  3858 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 10:41:59.662  1513  1513 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 10:41:59.665  4146  4146 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 10:41:59.665  4146  4146 D ObexServerSockets0: prepareForNewConnect()
08-17 10:41:59.666  4146  4188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:41:59.671  1363  1363 D BluetoothPbap: Proxy object connected
08-17 10:41:59.671  1363  1363 D PbapServerProfile: Bluetooth service connected
,08-17 10:41:59.672  3858  3858 D DockEventReceiver: finishStartingService: stopping service
,08-17 10:41:59.673  3858  3858 D BluetoothPbap: Proxy object connected
,08-17 10:41:59.673  3858  3858 D PbapServerProfile: Bluetooth service connected
,08-17 10:41:59.690  4146  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 10:41:59.691  4146  4194 I BtOppRfcommListener: Accept thread started.
,08-17 10:41:59.717  1920  1934 D BluetoothHeadset: Proxy object connected
,08-17 10:41:59.718   873   873 D BluetoothHeadset: Proxy object connected
08-17 10:41:59.718  1363  2253 D BluetoothHeadset: Proxy object connected
,08-17 10:41:59.718   873   873 D BluetoothHeadset: Proxy object connected
08-17 10:41:59.718  1363  1363 D HeadsetProfile: Bluetooth service connected
08-17 10:41:59.719  3858  3869 D BluetoothHeadset: Proxy object connected
08-17 10:41:59.719  1363  2013 D BluetoothHeadset: Proxy object connected
08-17 10:41:59.719   873   873 D BluetoothHeadset: Proxy object connected
,08-17 10:41:59.720  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-17 10:41:59.721  3858  3858 D HeadsetProfile: Bluetooth service connected
,08-17 10:41:59.727  3858  4182 D BluetoothHeadset: Proxy object connected
08-17 10:41:59.727  3858  3858 D HeadsetProfile: Bluetooth service connected
,08-17 10:41:59.735   873   890 D BluetoothHeadset: Proxy object connected
,08-17 10:41:59.737   873   890 D BluetoothHeadset: Proxy object connected
,08-17 10:41:59.741  1920  3469 D BluetoothHeadset: Proxy object connected
,08-17 10:42:02.850  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:42:02.850  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:42:02.850  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:42:02.850  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 10:42:02.850  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:42:02.850  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:42:02.850  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:42:02.850  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:42:02.858  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:42:02.859  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 10:42:02.860  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a492d85 removed from the list
,08-17 10:42:02.860  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:42:02.860  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:42:02.861  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:42:02.863  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:42:02.864  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e517da added. We now have 4 listener(s)
,08-17 10:42:02.864  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:42:02.868   873  1921 D WifiService: setWifiEnabled: false pid=3758, uid=10000
,08-17 10:42:02.869   873  1921 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:42:04.323  1856  1897 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-17 10:42:04.323  1856  1897 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-17 10:42:04.372  1513  1513 I ConfigService: onCreate
,08-17 10:42:07.882  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:42:07.884   873   883 D WifiService: setWifiEnabled: true pid=3758, uid=10000
08-17 10:42:07.884   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 10:42:07.900   873  1306 D WifiConfigStore: Loading config and enabling all networks 
,08-17 10:42:07.918  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:42:07.918  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:42:07.918  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:42:07.918  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:42:07.918  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:42:07.918  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:42:07.918  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:42:07.918  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:42:07.922  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:42:07.928  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:42:07.928  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:42:07.928  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:42:07.928  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:42:07.928  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:42:07.928  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 10:42:07.928  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 10:42:07.928  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 10:42:07.931  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 10:42:07.942   873  1306 D WifiConfigStore: loaded 0 passpoint configs
,08-17 10:42:07.943   873  1306 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-17 10:42:07.944   873  1306 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 10:42:07.945   873  1306 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-17 10:42:07.945   873  1306 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 10:42:07.945   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 10:42:07.946   873  1306 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 10:42:07.964   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 10:42:07.965   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 10:42:07.967   372   871 D CommandListener: Setting iface cfg
,08-17 10:42:08.021   873  1305 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-17 10:42:08.022   873  1305 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 10:42:08.030   873  1306 E native  : do suspend true
,08-17 10:42:08.031   873  1305 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 10:42:08.048   873  1305 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 10:42:08.068   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:42:09.466  1513  1513 I ConfigService: onDestroy
,08-17 10:42:09.485   873  1306 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 10:42:09.615   873  1306 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.19 rxSuccessRate=9.50 delta 1000 -> 994
,08-17 10:42:09.617   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-17 10:42:09.618   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:42:09.634   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 10:42:09.703   873  1306 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 10:42:09.707  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 10:42:10.137  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 10:42:10.184  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 10:42:10.185  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 10:42:10.187   873  1306 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 10:42:10.204   873  1306 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 10:42:10.204   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:42:10.205   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 10:42:10.226   873  1306 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 10:42:10.246   372   871 D CommandListener: Setting iface cfg
,08-17 10:42:10.248   873  1306 D WifiStateMachine: Start Dhcp Watchdog 3
,08-17 10:42:10.262   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 10:42:10.281   873  4207 D DhcpClient: Receive thread started
,08-17 10:42:10.377   873  1306 E native  : do suspend false
,08-17 10:42:10.405   873  1855 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 10:42:10.419   873  4207 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-17 10:42:10.420   873  1855 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
08-17 10:42:10.424   873  1855 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 10:42:10.437   873  4207 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 10:42:10.438   873  1855 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 10:42:10.448   372   871 D CommandListener: Setting iface cfg
,08-17 10:42:10.458   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 10:42:10.460   873  1306 E native  : do suspend true
08-17 10:42:10.461   873  1855 D DhcpClient: Scheduling renewal in 86399s
,08-17 10:42:10.475   873  1306 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 10:42:10.476   873  1306 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 10:42:10.476   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 10:42:10.478   873  1306 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 10:42:10.478   873  1308 D ConnectivityService: Adding iface wlan0 to network 102
,08-17 10:42:10.523   873  1308 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 10:42:10.523   873  1308 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-17 10:42:10.526   873  1308 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-17 10:42:10.528   873  1308 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-17 10:42:10.531   873  1308 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-17 10:42:10.545   873  1308 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 10:42:10.550   873  1308 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-17 10:42:10.550   873  1308 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-17 10:42:10.550   873  1308 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-17 10:42:10.550   873  1308 D ConnectivityService:    accepting network in place of null
08-17 10:42:10.551   873  1306 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-17 10:42:10.552   873  1308 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-17 10:42:10.552   873  1306 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 10:42:10.562   873  4206 D NetlinkSocketObserver: NeighborEvent{elapsedMs=216270, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 10:42:10.582   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:42:10.615   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 10:42:10.622   873  1308 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-17 10:42:10.622   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:42:10.627   873  1308 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-17 10:42:10.630   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-17 10:42:10.636   873  4205 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.78,2a00:1450:4001:815::200e
,08-17 10:42:10.660  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:42:10.660  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:42:10.660  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:42:10.660  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:42:10.660  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:42:10.660  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:42:10.660  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:42:10.660  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:42:10.662  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:42:10.663  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-17 10:42:10.667  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:42:10.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:42:10.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:42:10.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:42:10.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:42:10.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:42:10.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:42:10.667  3758  3758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 10:42:10.670  3758  3758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 10:42:10.671  1731  1731 D SystemUpdateService: onCreate
,08-17 10:42:10.675  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 10:42:10.694  1731  4216 I SystemUpdateService: active receiver: enabled
,08-17 10:42:10.698  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 10:42:10.704  1731  2402 I iu.UploadsManager: num queued entries: 0
08-17 10:42:10.704  1731  2402 I iu.UploadsManager: num updated entries: 0
,08-17 10:42:10.707  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-17 10:42:10.708  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 10:42:10.710  3912  3912 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 10:42:10.716  1731  4219 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 10:42:10.716  1731  4219 W BaseAppContext: Using Auth Proxy for data requests.
08-17 10:42:10.716   873  4205 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 08:42:10 GMT], X-Android-Received-Millis=[1471423330715], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471423330683]}
08-17 10:42:10.717  3912  3912 D SprintDMHelper: simOperator: 
08-17 10:42:10.717   873  1308 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 10:42:10.717  3912  3912 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-17 10:42:10.717   873  1308 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-17 10:42:10.717   873  1308 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 10:42:10.718   873  1308 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 10:42:10.730  1731  4219 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 10:42:10.743  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:42:10.748  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:42:10.758  1731  4216 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 10:42:10.779  1731  4216 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 10:42:10.705  1731  2402 I iu.SyncManager: NEXT; no task
,08-17 10:42:10.780  1731  4216 I SystemUpdateService: now status is 0 (complete)
,08-17 10:42:10.780  1731  4216 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 10:42:10.780  1731  4216 I SystemUpdateService: file has been verified
08-17 10:42:10.780  1731  4216 I SystemUpdateService: OTA package size = 12249756
,08-17 10:42:10.797  1731  4216 I SystemUpdateService: showing system update notification
,08-17 10:42:10.810  1731  1731 D SystemUpdateService: onDestroy
,08-17 10:42:10.814  1513  3436 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 10:42:10.814  1513  3436 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 10:42:10.814  1513  3436 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:42:10.815  1513  3436 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:42:10.830  1731  4219 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-17 10:42:10.894  3038  4222 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 10:42:11.623   873  1308 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-17 10:42:12.911  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 10:42:12.911  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:42:12.911  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:42:12.911  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:42:12.911  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:42:12.911  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:42:12.911  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:42:12.911  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:42:12.917  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:42:12.918  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:42:12.919  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e517da removed from the list
,08-17 10:42:12.919  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:42:12.921  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:42:12.921  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:42:12.934  3758  4228 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-17 10:42:12.935  3758  4228 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 10:42:15.942  3758  4229 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-17 10:42:15.942  3758  4228 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-17 10:42:15.943  3758  4229 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-17 10:42:15.943  3758  4228 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-17 10:42:15.944  3758  4229 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:42:15.945  3758  4228 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:42:15.945  3758  4229 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:42:15.947  3758  4229 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-17 10:42:15.947  3758  4228 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:42:15.951  3758  4231 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 417, name: IncomingSocketThread/Sender)
08-17 10:42:15.951  3758  4228 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-17 10:42:15.955  3758  4233 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 419, name: IncomingSocketThread/Receiver)
,08-17 10:42:15.956  3758  4233 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 419, thread name: IncomingSocketThread/Receiver)
08-17 10:42:15.956  3758  4233 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-17 10:42:15.957  3758  4232 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 418, name: OutgoingSocketThread/Sender)
08-17 10:42:15.957  3758  4233 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 419, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-17 10:42:15.957  3758  4234 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 420, name: OutgoingSocketThread/Receiver)
08-17 10:42:15.957  3758  4234 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 420, thread name: OutgoingSocketThread/Receiver)
08-17 10:42:15.957  3758  4234 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-17 10:42:15.957  3758  4234 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 420, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-17 10:42:18.558   873  1308 D ConnectivityService: handlePromptUnvalidated 102
,08-17 10:42:18.941  3758  3810 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 10:42:18.945  3758  3810 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 10:42:18.953  3758  3810 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3dd221c Bundle[{}]
,08-17 10:42:18.953  3758  3810 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 10:42:18.953  3758  3810 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-17 10:42:18.954  3758  3810 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-17 10:42:18.955  3758  3810 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-17 10:42:18.956  3758  3810 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 10:42:18.957  3758  3810 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 10:42:18.962  3758  3810 I System.out: Running OutgoingSocketThread
,08-17 10:42:18.966  3758  4235 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-17 10:42:18.966  3758  4235 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 10:42:21.975  3758  4237 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-17 10:42:21.975  3758  4237 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-17 10:42:21.976  3758  4237 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:42:21.976  3758  4235 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-17 10:42:21.977  3758  4235 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-17 10:42:21.977  3758  4237 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:42:21.977  3758  4235 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-17 10:42:21.980  3758  4239 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: IncomingSocketThread/Sender)
08-17 10:42:21.982  3758  4237 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-17 10:42:21.983  3758  4235 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-17 10:42:21.987  3758  4240 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: IncomingSocketThread/Receiver),
08-17 10:42:21.989  3758  4235 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-17 10:42:21.989  3758  4241 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: OutgoingSocketThread/Sender)
08-17 10:42:21.989  3758  4240 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: IncomingSocketThread/Receiver)
08-17 10:42:21.990  3758  4240 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-17 10:42:21.990  3758  4240 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-17 10:42:21.993  3758  4242 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: OutgoingSocketThread/Receiver)
,08-17 10:42:21.994  3758  4242 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: OutgoingSocketThread/Receiver)
08-17 10:42:21.995  3758  4242 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-17 10:42:21.996  3758  4242 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-17 10:42:24.977  3758  3810 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 441)
,08-17 10:42:24.980  3758  3810 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 10:42:24.981  3758  3810 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
,08-17 10:42:24.986  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 10:42:24.986  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96bc40b added. We now have 3 listener(s)
,08-17 10:42:24.988  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 10:42:24.988  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:42:24.988  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:42:24.989  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:42:24.989  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42002e8 added. We now have 4 listener(s)
08-17 10:42:24.989  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:42:24.990  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:42:24.993  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:42:25.002  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:42:25.002  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:42:25.002  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:42:25.002  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:42:25.002  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:42:25.002  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:42:25.002  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:42:25.002  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:42:25.009  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:42:25.009  3758  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 10:42:25.011  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 10:42:25.011  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:42:25.011  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:42:25.012  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:42:25.012  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:42:25.012  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:42:25.012  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:42:25.013  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:42:25.013  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96bc40b removed from the list
08-17 10:42:25.013  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:42:25.013  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42002e8 removed from the list
08-17 10:42:25.015  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:42:25.016  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:42:25.016  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:42:25.017  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:42:25.017  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:42:25.019  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:42:25.019  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:42:25.019  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:42:25.019  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42002e8 not in the list
08-17 10:42:25.019  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:42:25.019  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:42:25.021  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:42:25.022  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:42:25.022  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:42:25.022  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42002e8 not in the list
08-17 10:42:25.022  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:42:25.022  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:42:25.022  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:42:25.022  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96bc40b not in the list
08-17 10:42:25.023  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:42:25.023  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8cd7a6 added. We now have 3 listener(s)
08-17 10:42:25.025  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 10:42:25.025  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 10:42:25.025  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:42:25.025  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 10:42:25.026  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1095e7 added. We now have 4 listener(s)
08-17 10:42:25.026  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:42:25.026  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 10:42:25.030  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:42:25.039  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:42:25.039  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:42:25.039  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:42:25.039  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:42:25.039  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:42:25.039  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:42:25.039  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:42:25.039  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:42:25.043  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:42:25.043  3758  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:42:25.045  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 10:42:25.045  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 10:42:25.045  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 10:42:25.045  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:42:25.045  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 10:42:25.046  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:42:25.052  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:42:25.052  3758  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 10:42:25.052  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 10:42:25.062  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:42:25.064  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 10:42:25.064  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 10:42:25.071  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 10:42:25.072  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 10:42:25.072  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 10:42:25.073  3758  3810 D BluetoothAdapter: STATE_ON,
,08-17 10:42:25.078  4146  4186 D BtGatt.GattService: registerClient() - UUID=906987f6-f739-4e8f-8e93-0a9fd1936b2e
,08-17 10:42:25.080  4146  4162 D BtGatt.GattService: onClientRegistered() - UUID=906987f6-f739-4e8f-8e93-0a9fd1936b2e, clientIf=5
,08-17 10:42:25.081  3758  3769 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 10:42:25.082  4146  4157 D BtGatt.GattService: start scan with filters
,08-17 10:42:25.090  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 10:42:25.090  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 10:42:25.090  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 10:42:25.090  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-17 10:42:25.091  4146  4165 D BtGatt.ScanManager: handling starting scan
,08-17 10:42:25.094  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 10:42:25.095  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 10:42:25.095  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 10:42:25.096  4146  4165 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@efe86f0
08-17 10:42:25.098  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:42:25.103  3758  3810 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 10:42:25.103  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 10:42:25.103  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 10:42:25.103  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 10:42:25.103  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 10:42:25.104  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 10:42:25.104  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
08-17 10:42:25.104  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 10:42:25.104  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 10:42:25.105  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 10:42:25.105  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 10:42:25.106  3758  3810 D BluetoothAdapter: STATE_ON
08-17 10:42:25.109  4146  4186 D BtGatt.GattService: stopScan() - queue size =1
08-17 10:42:25.110  4146  4162 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 10:42:25.110  4146  4162 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:42:25.111  4146  4157 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 10:42:25.112  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:42:25.112  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 10:42:25.112  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 10:42:25.113  4146  4165 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 10:42:25.113  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 10:42:25.113  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 10:42:25.115  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 10:42:25.116  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-17 10:42:25.116  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 10:42:25.116  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 10:42:25.118  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:42:25.120  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:42:25.120  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 10:42:25.121  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 10:42:25.126  4146  4162 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 10:42:25.127  4146  4162 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:42:25.128  4146  4165 D BtGatt.ScanManager: Starting BLE batch scan
08-17 10:42:25.128  4146  4165 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 10:42:25.155  4146  4162 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 10:42:25.156  4146  4162 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:42:25.170  4146  4162 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 10:42:25.171  4146  4162 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:42:25.195  4146  4162 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-17 10:42:25.195  4146  4162 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:42:25.196  4146  4165 D BtGatt.ScanManager: stopping BLe Batch
,08-17 10:42:25.215  4146  4162 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 10:42:25.215  4146  4162 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 10:42:25.216  4146  4165 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 10:42:25.234  4146  4162 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 10:42:25.235  4146  4162 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 10:42:25.622  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 10:42:25.622  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:42:25.623  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:42:28.121  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:42:28.121  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 10:42:28.122  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 10:42:28.122  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:42:28.123  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:42:28.123  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:42:28.123  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 10:42:28.124  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8cd7a6 removed from the list
,08-17 10:42:28.124  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:42:28.124  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1095e7 removed from the list
08-17 10:42:28.125  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:42:28.125  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:42:28.127  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:42:28.127  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:42:28.130  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:42:28.131  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:42:28.131  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:42:28.131  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1095e7 not in the list
08-17 10:42:28.132  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:42:28.132  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:42:28.135  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:42:28.136  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:42:28.136  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:42:28.136  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1095e7 not in the list
08-17 10:42:28.136  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:42:28.137  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:42:28.137  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:42:28.137  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d8cd7a6 not in the list
,08-17 10:42:28.140  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 10:42:28.140  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20e4700 added. We now have 3 listener(s)
,08-17 10:42:28.144  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 10:42:28.145  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 10:42:28.145  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 10:42:28.145  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:42:28.146  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b66b39 added. We now have 4 listener(s)
08-17 10:42:28.146  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 10:42:28.147  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:42:28.152  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:42:28.161  3758  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 10:42:28.161  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 10:42:28.161  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 10:42:28.161  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 10:42:28.161  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 10:42:28.161  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 10:42:28.161  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 10:42:28.161  3758  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 10:42:28.165  3758  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 10:42:28.166  3758  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 10:42:28.167  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-17 10:42:28.169  3758  3810 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-17 10:42:28.169  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-17 10:42:28.172  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 10:42:28.172  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-17 10:42:28.173  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-17 10:42:28.173  3758  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 10:42:28.173  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:42:28.174  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-17 10:42:28.175  3758  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 10:42:28.175  3758  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 10:42:28.175  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 10:42:28.175  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-17 10:42:28.175  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 10:42:28.176  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 10:42:28.178  3758  3758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 10:42:28.178  3758  3758 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 10:42:28.179  3758  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 10:42:28.182  3758  3810 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 10:42:28.182  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 10:42:28.188  3758  4243 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-17 10:42:28.192  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 10:42:28.193  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 10:42:28.194  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 10:42:28.200  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-17 10:42:28.201  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 10:42:28.201  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-17 10:42:28.202  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-17 10:42:28.203  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-17 10:42:28.203  3758  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-17 10:42:28.204  3758  3810 D BluetoothAdapter: STATE_ON
,08-17 10:42:28.210  4146  4186 D BtGatt.GattService: registerClient() - UUID=18e5841c-ab1a-4359-8bd7-95225fc55a17
,08-17 10:42:28.211  4146  4162 D BtGatt.GattService: onClientRegistered() - UUID=18e5841c-ab1a-4359-8bd7-95225fc55a17, clientIf=5
,08-17 10:42:28.211  3758  3771 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-17 10:42:28.216  4146  4164 D BtGatt.AdvertiseManager: message : 0
,08-17 10:42:28.221  4146  4164 D BtGatt.AdvertiseManager: starting multi advertising
,08-17 10:42:28.244  4146  4162 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-17 10:42:28.261  4146  4162 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-17 10:42:28.264  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-17 10:42:28.265  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 10:42:28.273  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 10:42:28.277  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-17 10:42:28.278  3758  3758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-17 10:42:28.278  3758  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-17 10:42:28.278  3758  3758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-17 10:42:28.279  3758  3758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-17 10:42:28.279  3758  3758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-17 10:42:28.282  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-17 10:42:28.284  3758  3758 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-17 10:42:28.285  3758  3758 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-17 10:42:28.786  3758  3758 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-17 10:42:28.786  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 10:42:28.786  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-17 10:42:31.283  3758  3810 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 10:42:31.284  3758  3810 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-17 10:42:31.284  3758  3810 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 10:42:31.285  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 10:42:31.285  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 10:42:31.286  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-17 10:42:31.286  3758  4243 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 10:42:31.286  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-17 10:42:31.287  3758  4243 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 10:42:31.287  3758  3810 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 10:42:31.287  3758  4243 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 10:42:31.287  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 10:42:31.287  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 10:42:31.288  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 10:42:31.288  3758  3758 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 10:42:31.288  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 10:42:31.288  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 10:42:31.291  3758  3810 D BluetoothAdapter: STATE_ON
,08-17 10:42:31.291  3758  3810 D BluetoothLeScanner: could not find callback wrapper
08-17 10:42:31.292  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 10:42:31.292  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-17 10:42:31.295  4146  4164 D BtGatt.AdvertiseManager: message : 1
08-17 10:42:31.297  4146  4164 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-17 10:42:31.305  4146  4162 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-17 10:42:31.306  4146  4162 D BtGatt.GattService: Client app is not null!
,08-17 10:42:31.307  4146  4185 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 10:42:31.308  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 10:42:31.309  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-17 10:42:31.309  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-17 10:42:31.309  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED],
08-17 10:42:31.309  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-17 10:42:31.313  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 10:42:31.313  3758  3810 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 10:42:31.313  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 10:42:31.314  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-17 10:42:31.317  3758  3758 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 10:42:31.317  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:42:31.317  3758  3758 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 10:42:31.318  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:42:31.318  3758  3758 D AndroidRuntime: Shutting down VM
08-17 10:42:31.318  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 10:42:31.318  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 10:42:31.319  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20e4700 removed from the list
--------- beginning of crash
08-17 10:42:31.319  3758  3758 E AndroidRuntime: FATAL EXCEPTION: main
08-17 10:42:31.319  3758  3758 E AndroidRuntime: Process: com.test.thalitest, PID: 3758
08-17 10:42:31.319  3758  3758 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
08-17 10:42:31.319  3758  3758 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
08-17 10:42:31.319  3758  3758 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
08-17 10:42:31.319  3758  3758 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
08-17 10:42:31.319  3758  3758 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 10:42:31.319  3758  3758 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 10:42:31.319  3758  3758 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 10:42:31.319  3758  3758 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 10:42:31.319  3758  3758 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 10:42:31.319  3758  3758 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 10:42:31.319  3758  3758 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 10:42:31.319  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:42:31.319  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b66b39 removed from the list
08-17 10:42:31.319  3758  3810 D io.jxcore.node.ConnectivityMonitor: stop
08-17 10:42:31.320  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:42:31.321  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 10:42:31.321  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:42:31.324   873  1921 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
08-17 10:42:31.324  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 10:42:31.324  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 10:42:31.325  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:42:31.325  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b66b39 not in the list
,08-17 10:42:31.325  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 10:42:31.326  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 10:42:31.328  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 10:42:31.328  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 10:42:31.329  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 10:42:31.329  3758  3810 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b66b39 not in the list
08-17 10:42:31.329  3758  3810 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 10:42:31.329  3758  3810 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-17 10:42:31.329  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 10:42:31.329  3758  3810 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20e4700 not in the list
,08-17 10:42:31.331  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 10:42:31.331  3758  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@232b8a added. We now have 3 listener(s)
08-17 10:42:31.331   873  1921 I ActivityManager: Killing 3679:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-17 10:42:31.340  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 10:42:31.340  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 10:42:31.341  3758  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 10:42:31.341  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 10:42:31.341  3758  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf9c5fb added. We now have 4 listener(s)
08-17 10:42:31.341  3758  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 10:42:31.349  3758  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 10:42:31.417  3758  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 10:42:31.417   873   886 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{ff47648 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{1a1c43a 3758 com.test.thalitest/10000/u0 remote:a554f65}: process crashing
08-17 10:42:31.417   873   886 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{ad07ce1 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{1a1c43a 3758 com.test.thalitest/10000/u0 remote:a554f65}: process crashing
,08-17 10:42:31.426  3758  3758 I Process : Sending signal. PID: 3758 SIG: 9
,08-17 10:42:31.562   873  1307 D WifiService: Client connection lost with reason: 4
,08-17 10:42:31.562   873  1921 I WindowState: WIN DEATH: Window{6294d2e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 10:42:31.562   873  1901 D GraphicsStats: Buffer count: 2
,08-17 10:42:31.590   873  1928 I ActivityManager: Process com.test.thalitest (pid 3758) has died
,08-17 10:42:31.637   873  1926 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3758 uid 10000
,08-17 10:42:31.638  1856  1856 I Keyboard.Facilitator: onFinishInput()
,08-17 10:42:51.108  3023  4246 V KeepSync: Connecting to GoogleApiClient
,08-17 10:42:51.109   873  2249 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 10:42:51.177  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:42:51.178  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:42:51.207  1513  2257 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 10:42:51.207  1513  2257 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-17 10:42:51.207  1513  2257 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:42:51.207  1513  2257 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:42:51.234  1731  4247 V BaseAuthAsyncOperation: access token request failed
,08-17 10:42:51.236  3023  4246 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 10:42:51.296  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-17 10:42:51.296  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-17 10:42:51.296  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:42:51.297  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:42:51.317  3023  4246 E KeepSync: IOException
08-17 10:42:51.317  3023  4246 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 10:42:51.317  3023  4246 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 10:42:51.317  3023  4246 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 10:42:51.317  3023  4246 E KeepSync: 	... 10 more
,08-17 10:42:51.317  3023  4246 W KeepSync: Sync result 2
,08-17 10:42:51.324   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 256637, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:42:51.697   873  4206 D NetlinkSocketObserver: NeighborEvent{elapsedMs=257404, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-17 10:43:02.757   873  4206 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 10:43:14.855  1513  2191 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 10:43:21.455  3561  4253 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 10:43:21.498  3561  4254 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 10:43:21.514  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:43:21.517  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:43:21.556  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-17 10:43:21.556  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 10:43:21.557  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:43:21.557  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:43:21.594  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:43:21.597  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 10:43:21.632  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-17 10:43:21.633  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 10:43:21.633  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 10:43:21.633  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 10:43:21.656  3561  4254 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 10:43:21.658  3561  4253 E BooksSync: Soft error
08-17 10:43:21.658  3561  4253 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:43:21.658  3561  4253 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 10:43:21.658  3561  4253 E BooksSync: Sync error
08-17 10:43:21.658  3561  4253 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 10:43:21.658  3561  4253 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-17 10:43:21.658  3561  4253 I BooksSync: Finished books sync
,08-17 10:43:21.672   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 286425, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 10:43:31.679  1856  1897 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-17 10:43:31.679  1856  1897 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-17 10:43:31.710  1513  1513 I ConfigService: onCreate

```
