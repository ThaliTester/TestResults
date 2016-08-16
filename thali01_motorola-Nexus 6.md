#### Test 80761374e4349a7_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-16 15:22:22.653   871  1876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
08-16 15:22:23.363  3858  3858 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 15:22:23.367  3858  3858 D AndroidRuntime: CheckJNI is OFF
08-16 15:22:23.404  3858  3858 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 15:22:23.448  3858  3858 I Radio-JNI: register_android_hardware_Radio DONE
08-16 15:22:23.469  3858  3858 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 15:22:23.477   871  1933 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 15:22:23.515  1992  2003 W SearchService: Abort, client detached.
08-16 15:22:23.520  1992  1992 I HotwordDetector: Closing mic
08-16 15:22:23.521  1992  2318 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@4243758
08-16 15:22:23.521  3858  3858 D AndroidRuntime: Shutting down VM
08-16 15:22:23.522  1992  2347 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 15:22:23.567   871  2162 I ActivityManager: Start proc 3868:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 15:22:23.581   374  2349 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 15:22:23.583   374  2349 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 15:22:23.593   374  1284 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 15:22:23.594  1992  2332 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 15:22:23.594  1992  2342 I MicroRecognitionRnrImpl: Detection finished
08-16 15:22:23.638  3868  3868 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 15:22:23.658  3868  3868 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 15:22:23.665  3868  3868 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9126-9129)
08-16 15:22:23.666  3868  3868 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 15:22:23.685  3868  3868 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a08290c}
08-16 15:22:23.686  3868  3868 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 15:22:23.686  3868  3868 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 15:22:23.697  3868  3868 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 15:22:23.699  3868  3868 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 15:22:23.718  3868  3868 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-16 15:22:23.731  3868  3868 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 15:22:23.731  3868  3868 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 15:22:23.731  3868  3868 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 15:22:23.731  3868  3868 I Adreno  : Build Date                       : 10/20/15
08-16 15:22:23.731  3868  3868 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 15:22:23.731  3868  3868 I Adreno  : Local Branch                     : M14
08-16 15:22:23.731  3868  3868 I Adreno  : Remote Branch                    : 
08-16 15:22:23.731  3868  3868 I Adreno  : Remote Branch                    : 
08-16 15:22:23.731  3868  3868 I Adreno  : Reconstruct Branch               : 
,08-16 15:22:23.839   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9861a0c:true
08-16 15:22:23.888  3868  3868 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 15:22:23.904  3868  3868 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-16 15:22:24.000  3868  3907 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-16 15:22:24.024  3868  3893 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-16 15:22:24.066  3868  3907 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 15:22:24.152   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +604ms
08-16 15:22:24.157  1862  1862 I Keyboard.Facilitator: onFinishInput()
08-16 15:22:24.237  3868  3868 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3868
08-16 15:22:24.377   871  1966 I ActivityManager: Killing 3609:com.google.android.apps.books/u0a34 (adj 15): empty #17
08-16 15:22:24.421  3868  3868 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-16 15:22:24.449   871  1966 I ActivityManager: Killing 3401:com.google.android.music:main/u0a66 (adj 15): empty #18
08-16 15:22:24.681  3868  3909 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1697187536
08-16 15:22:24.701  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 15:22:24.701  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 15:22:24.701  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 15:22:24.701  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 15:22:24.701  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 15:22:24.701  3868  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16f1cd0 added. We now have 1 listener(s)
08-16 15:22:24.711  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-16 15:22:24.713  3868  3909 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 15:22:24.714  3868  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:22:24.714  3868  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 15:22:24.726  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 15:22:24.727  3868  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@54c46ef added. We now have 1 listener(s)
08-16 15:22:24.728  3868  3909 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:22:24.735   871  1314 D WifiService: New client listening to asynchronous messages
08-16 15:22:24.737  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 15:22:24.737  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 15:22:24.737  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 15:22:24.737  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 15:22:24.738  3868  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 15:22:24.745  3868  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:22:24.746  3868  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-16 15:22:24.755  3868  3909 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-16 15:22:24.755  3868  3909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:22:24.755  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:22:24.755  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:22:24.755  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:22:24.755  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:22:24.755  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:22:24.755  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:22:24.755  3868  3909 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:22:24.755  3868  3909 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 15:22:24.755  3868  3909 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:22:24.757  3868  3909 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 15:22:24.943  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:22:24.952  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:22:24.961  3868  3868 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 15:22:25.317  3868  3877 I art     : Background sticky concurrent mark sweep GC freed 72367(6MB) AllocSpace objects, 17(1116KB) LOS objects, 27% free, 23MB/32MB, paused 602us total 139.070ms
,08-16 15:22:26.105  3868  3918 W jxcore-log: Initializing JXcore engine
08-16 15:22:26.105  3868  3918 W jxcore-log: JXcore engine is ready
,08-16 15:22:26.168  3918  3918 W Thread-341: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8951 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-16 15:22:26.168  3918  3918 W Thread-341: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11605]" dev="sockfs" ino=11605 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-16 15:22:26.168  3918  3918 W Thread-341: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 15:22:26.168  3918  3918 W Thread-341: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[28702]" dev="sockfs" ino=28702 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 15:22:26.182  3868  3918 W jxcore-log: Starting JXcore engine
,08-16 15:22:26.259  3868  3918 W jxcore-log: Platform android
08-16 15:22:26.259  3868  3918 W jxcore-log: 
08-16 15:22:26.260  3868  3918 W jxcore-log: Process ARCH arm
08-16 15:22:26.260  3868  3918 W jxcore-log: 
,08-16 15:22:26.475  3868  3918 I jxcore-log: JXcore Cordova bridge is ready!
08-16 15:22:26.475  3868  3918 I jxcore-log: 
08-16 15:22:26.476  3868  3918 W jxcore-log: JXcore engine is started
,08-16 15:22:26.488  3868  3909 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 15:22:26.496  3868  3868 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 15:22:26.668   871  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-16 15:22:33.906  3032  3926 V KeepSync: Connecting to GoogleApiClient
,08-16 15:22:33.907   871  1933 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 15:22:33.953  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:22:33.955  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:22:33.991  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 15:22:33.991  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 15:22:33.991  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:22:33.991  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:22:34.023  1740  3927 V BaseAuthAsyncOperation: access token request failed
,08-16 15:22:34.024  3032  3926 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 15:22:34.097  1520  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-16 15:22:34.097  1520  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 15:22:34.097  1520  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:22:34.097  1520  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:22:34.134  3032  3926 E KeepSync: IOException
08-16 15:22:34.134  3032  3926 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 15:22:34.134  3032  3926 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 15:22:34.134  3032  3926 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 15:22:34.134  3032  3926 E KeepSync: 	... 10 more
08-16 15:22:34.135  3032  3926 W KeepSync: Sync result 2
,08-16 15:22:34.143   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129208, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:22:36.715  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:22:36.745  1520  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 15:22:36.745  1520  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 15:22:36.745  1520  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:22:36.745  1520  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:22:36.765  3510  3510 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 15:22:36.765  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 15:22:36.765  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-16 15:22:42.571  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 15:22:42.571  3868  3918 I jxcore-log: 
,08-16 15:22:42.574  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 15:22:42.574  3868  3918 I jxcore-log: 
,08-16 15:22:42.587  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:22:42.587  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:22:42.587  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:22:42.587  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:22:42.587  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:22:42.587  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:22:42.587  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:22:42.587  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:22:42.595  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:22:42.607  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 15:22:42.607  3868  3918 I jxcore-log: 
,08-16 15:22:42.614  3868  3918 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 15:22:42.614  3868  3918 I jxcore-log: 
,08-16 15:22:43.032  3868  3918 I jxcore-log: Running unit tests
08-16 15:22:43.032  3868  3918 I jxcore-log: 
,08-16 15:22:43.033  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 15:22:43.033  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67acea added. We now have 2 listener(s)
,08-16 15:22:43.034  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 15:22:43.034  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:22:43.034  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:22:43.034  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:22:43.035  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9d01bdb added. We now have 2 listener(s)
,08-16 15:22:43.035  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:22:43.035  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 15:22:43.037  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 15:22:43.047  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:22:43.047  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:22:43.047  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:22:43.047  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:22:43.047  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:22:43.047  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:22:43.047  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:22:43.047  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:22:43.048  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:22:43.048  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:22:43.049  3868  3918 D ExecuteNativeTests: Running unit tests
,08-16 15:22:43.055  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:22:43.061  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:22:43.107  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 15:22:43.108  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 added. We now have 3 listener(s)
08-16 15:22:43.109  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 15:22:43.109  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:22:43.109  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 15:22:43.109  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 15:22:43.109  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 added. We now have 3 listener(s)
08-16 15:22:43.109  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:22:43.110  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 15:22:43.112  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 15:22:43.129  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:22:43.129  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:22:43.129  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:22:43.129  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:22:43.129  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:22:43.129  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:22:43.129  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:22:43.129  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:22:43.132  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:22:43.132  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 15:22:43.134  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 15:22:43.134  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 15:22:43.134  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 15:22:43.134  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 15:22:43.138  3868  3918 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 15:22:43.138  3868  3918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 15:22:43.138  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 15:22:43.138  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:22:43.138  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:22:43.138  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:22:43.139  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:22:43.139  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:22:43.139  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:22:43.146  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:22:43.146  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:22:43.146  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:22:43.146  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 15:22:43.147  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 removed from the list
08-16 15:22:43.147  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:22:43.147  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 removed from the list
08-16 15:22:43.147  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:22:43.148  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:22:43.148  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:22:43.149  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:22:43.149  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:22:43.151  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:22:43.151  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:22:43.152  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:22:43.152  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:22:43.152  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:22:43.154  3868  3918 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 15:22:43.154  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:22:43.154  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:22:43.154  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:22:43.154  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:22:43.154  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:22:43.155  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:22:43.155  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:22:43.155  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:22:43.155  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:22:43.155  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 15:22:43.155  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:22:43.155  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:22:43.155  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:22:43.155  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:22:43.156  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:22:43.156  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:22:43.156  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:22:43.156  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:22:43.160  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 15:22:43.160  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 15:22:43.160  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 15:22:43.161  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 15:22:43.162  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<,no peer name> 31:2110:2110:2110:2110:2110]
08-16 15:22:43.162  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 15:22:43.162  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 15:22:43.162  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 15:22:43.162  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 15:22:43.162  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 15:22:43.162  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 15:22:43.162  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 15:22:43.162  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 15:22:43.162  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:22:43.162  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:22:43.162  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:22:43.162  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:22:43.162  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:22:43.163  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:22:43.163  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:22:43.163  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:22:43.163  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:22:43.163  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:22:43.163  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:22:43.163  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:22:43.163  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:22:43.163  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:22:43.164  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:22:43.164  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:22:43.164  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:22:43.164  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:22:43.165  3868  3918 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 15:22:43.166 , 3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:22:43.170  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:22:43.170  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:22:43.170  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:22:43.170  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:22:43.170  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:22:43.170  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:22:43.170  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:22:43.170  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:22:43.171  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:22:43.171  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:22:43.176  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 15:22:43.176  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 15:22:43.176  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 15:22:43.176  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:22:43.176  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 15:22:43.177  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:22:43.180  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:22:43.183  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 15:22:43.183  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 15:22:43.188  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 15:22:43.189  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 15:22:43.190  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 15:22:43.192  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-16 15:22:43.194  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-16 15:22:43.194  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 15:22:43.194  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 15:22:43.195  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 15:22:43.195  3868  3918 D BluetoothAdapter: STATE_ON
,08-16 15:22:43.199  2678  2808 D BtGatt.GattService: registerClient() - UUID=87d30a4b-7980-4edf-b284-00a99090ec14
,08-16 15:22:43.199  2678  2703 D BtGatt.GattService: onClientRegistered() - UUID=87d30a4b-7980-4edf-b284-00a99090ec14, clientIf=5
08-16 15:22:43.200  3868  3879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 15:22:43.200  2678  2690 D BtGatt.GattService: start scan with filters
,08-16 15:22:43.203  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 15:22:43.204  2678  2706 D BtGatt.ScanManager: handling starting scan
08-16 15:22:43.204  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 15:22:43.204  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 15:22:43.204  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 15:22:43.205  2678  2706 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:22:43.207  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 15:22:43.208  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 15:22:43.208  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 15:22:43.209  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 15:22:43.211  3868  3918 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 15:22:43.213  2678  2703 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 15:22:43.213  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:43.214  2678  2706 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 15:22:43.218  2678  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 15:22:43.219  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:43.219  2678  2706 D BtGatt.ScanManager: Starting BLE batch scan
08-16 15:22:43.221  2678  2706 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 15:22:43.228  2678  2703 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 15:22:43.228  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:43.233  2678  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 15:22:43.233  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:43.710  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 15:22:43.710  3868  3868 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 15:22:43.711  3868  3868 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 15:22:44.741  2678  2678 D BtGatt.ScanManager: awakened up at time 140205,
08-16 15:22:44.744  2678  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 15:22:44.799  2678  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 15:22:44.799  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:44.799  2678  2703 D BtGatt.GattService: current time is 140263610230
,08-16 15:22:44.801  2678  2703 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -90, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -98, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 15:22:44.803  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 15:22:44.805  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 15:22:44.806  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 15:22:44.806  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 15:22:44.807  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 15:22:44.807  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 15:22:46.303  2678  2678 D BtGatt.ScanManager: awakened up at time 141767
,08-16 15:22:46.307  2678  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 15:22:46.334  2678  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-16 15:22:46.335  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:46.335  2678  2703 D BtGatt.GattService: current time is 141799273704
,08-16 15:22:46.336  2678  2703 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -90, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 15:22:46.337  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 15:22:46.338  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 15:22:46.339  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 15:22:47.838  2678  2678 D BtGatt.ScanManager: awakened up at time 143302
,08-16 15:22:47.841  2678  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 15:22:47.850  2678  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 15:22:47.851  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:47.947   871  1876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=143410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 15:22:48.221  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:22:48.222  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 15:22:48.223  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 15:22:48.223  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:22:48.223  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 15:22:48.224  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 15:22:48.224  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 15:22:48.224  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 15:22:48.225  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 15:22:48.226  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 15:22:48.227  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 15:22:48.229  3868  3918 D BluetoothAdapter: STATE_ON
,08-16 15:22:48.231  2678  2690 D BtGatt.GattService: stopScan() - queue size =1
,08-16 15:22:48.235  2678  2808 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 15:22:48.236  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 15:22:48.236  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 15:22:48.237  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 15:22:48.237  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 15:22:48.237  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 15:22:48.242  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 15:22:48.244  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 15:22:48.244  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 15:22:48.245  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 15:22:48.247  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 15:22:48.251  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 15:22:48.252  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 15:22:48.252  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 15:22:48.253  2678  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 15:22:48.253  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:48.253  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 15:22:48.254  2678  2706 D BtGatt.ScanManager: stopping BLe Batch
08-16 15:22:48.254  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:22:48.254  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:22:48.254  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:22:48.254  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:22:48.254  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:22:48.255  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:22:48.255  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:22:48.261  2678  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 15:22:48.261  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:48.262  2678  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 15:22:48.270  2678  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 15:22:48.270  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:48.753  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 15:22:48.844  1520  2187 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 15:22:53.256  3868  3918 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 15:22:53.262  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 15:22:53.276  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:22:53.276  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:22:53.276  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:22:53.276  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:22:53.276  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:22:53.276  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:22:53.276  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:22:53.276  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:22:53.281  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:22:53.282  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 15:22:53.283  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 15:22:53.283  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 15:22:53.284  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 15:22:53.284  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:22:53.284  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 15:22:53.289  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:22:53.292  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 15:22:53.292  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 15:22:53.297  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:22:53.303  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 15:22:53.305  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 15:22:53.305  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 15:22:53.314  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 15:22:53.314  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 15:22:53.315  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 15:22:53.317  3868  3918 D BluetoothAdapter: STATE_ON
,08-16 15:22:53.323  2678  2689 D BtGatt.GattService: registerClient() - UUID=ecdb2064-6296-4001-8229-a1460d1bed2e
,08-16 15:22:53.325  2678  2703 D BtGatt.GattService: onClientRegistered() - UUID=ecdb2064-6296-4001-8229-a1460d1bed2e, clientIf=5
,08-16 15:22:53.325  3868  3879 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 15:22:53.326  2678  2808 D BtGatt.GattService: start scan with filters
,08-16 15:22:53.333  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 15:22:53.334  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 15:22:53.334  2678  2706 D BtGatt.ScanManager: handling starting scan
,08-16 15:22:53.334  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 15:22:53.334  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 15:22:53.341  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 15:22:53.342  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 15:22:53.343  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 15:22:53.345  2678  2703 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 15:22:53.345  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:53.346  2678  2706 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 15:22:53.348  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 15:22:53.355  3868  3918 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 15:22:53.358  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:22:53.358  3868  3918 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 15:22:53.359  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 15:22:53.359  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 15:22:53.359  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:22:53.359  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 15:22:53.359  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 15:22:53.359  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 15:22:53.359  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 15:22:53.360  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 15:22:53.360  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 15:22:53.360  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 15:22:53.361  3868  3918 D BluetoothAdapter: STATE_ON
08-16 15:22:53.362  2678  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 15:22:53.362  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:53.362  2678  2706 D BtGatt.ScanManager: Starting BLE batch scan
08-16 15:22:53.362  2678  2706 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 15:22:53.363  2678  2690 D BtGatt.GattService: stopScan() - queue size =1
08-16 15:22:53.364  2678  2689 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 15:22:53.365  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:22:53.365  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 15:22:53.366  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 15:22:53.367  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 15:22:53.369  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 15:22:53.372  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 15:22:53.372  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 15:22:53.373  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 15:22:53.376  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 15:22:53.377  2678  2703 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 15:22:53.377  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:53.378  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 15:22:53.384  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 15:22:53.384  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 15:22:53.384  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 15:22:53.385  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 15:22:53.385  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:22:53.385  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 15:22:53.385  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
,08-16 15:22:53.385  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:22:53.385  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:22:53.385  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 15:22:53.385  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:22:53.386  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:22:53.386  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:22:53.386  2678  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 15:22:53.387  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:53.387  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 15:22:53.387  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:22:53.387  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:22:53.387  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:22:53.388  3868  3918 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 15:22:53.390  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 15:22:53.395  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:22:53.395  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:22:53.395  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:22:53.395  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:22:53.395  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:22:53.395  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:22:53.395  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:22:53.395  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:22:53.395  2678  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 15:22:53.395  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:53.395  2678  2706 D BtGatt.ScanManager: stopping BLe Batch
08-16 15:22:53.397  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:22:53.397  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:22:53.398  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 15:22:53.398  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 15:22:53.398  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 15:22:53.399  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:22:53.399  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 15:22:53.400  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:22:53.403  2678  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 15:22:53.403  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:53.403  2678  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-16 15:22:53.406  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 15:22:53.406  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 15:22:53.408  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:22:53.410  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 15:22:53.411  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 15:22:53.411  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 15:22:53.415  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 15:22:53.416  2678  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 15:22:53.416  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:53.416  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 15:22:53.416  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 15:22:53.418  3868  3918 D BluetoothAdapter: STATE_ON
,08-16 15:22:53.420  2678  2689 D BtGatt.GattService: registerClient() - UUID=a959bd7a-ec34-4fbd-9cf4-dee17a1f6a68
,08-16 15:22:53.420  2678  2703 D BtGatt.GattService: onClientRegistered() - UUID=a959bd7a-ec34-4fbd-9cf4-dee17a1f6a68, clientIf=5
08-16 15:22:53.421  3868  3880 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 15:22:53.421  2678  2808 D BtGatt.GattService: start scan with filters
,08-16 15:22:53.424  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 15:22:53.424  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 15:22:53.424  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 15:22:53.424  2678  2706 D BtGatt.ScanManager: handling starting scan
08-16 15:22:53.424  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 15:22:53.427  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 15:22:53.427  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 15:22:53.428  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 15:22:53.430  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 15:22:53.431  2678  2703 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 15:22:53.431  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:53.431  2678  2706 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,08-16 15:22:53.433  3868  3918 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 15:22:53.438  2678  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 15:22:53.438  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:53.439  2678  2706 D BtGatt.ScanManager: Starting BLE batch scan
08-16 15:22:53.439  2678  2706 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 15:22:53.450  2678  2703 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 15:22:53.450  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:53.457  2678  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 15:22:53.458  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:53.928  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 15:22:53.929  3868  3868 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 15:22:53.930  3868  3868 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 15:22:54.599   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 15:22:54.610  1862  1862 I Keyboard.Facilitator: onFinishInput()
,08-16 15:22:54.624   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 15:22:54.624   871   891 I Adreno  : Build Date                       : 10/20/15
08-16 15:22:54.624   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 15:22:54.624   871   891 I Adreno  : Local Branch                     : M14
08-16 15:22:54.624   871   891 I Adreno  : Remote Branch                    : 
08-16 15:22:54.624   871   891 I Adreno  : Remote Branch                    : 
08-16 15:22:54.624   871   891 I Adreno  : Reconstruct Branch               : 
,08-16 15:22:54.681   281  1305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (332 us)
,08-16 15:22:54.964  2678  2678 D BtGatt.ScanManager: awakened up at time 150428
,08-16 15:22:54.969  2678  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 15:22:55.009  2678  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 15:22:55.009  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:55.010  2678  2703 D BtGatt.GattService: current time is 150473809061
08-16 15:22:55.010  2678  2703 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -92, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -92, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -83, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -79, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
,08-16 15:22:55.011  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-16 15:22:55.011  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 15:22:55.011  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 15:22:55.011  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 15:22:55.012  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 15:22:55.012  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-16 15:22:55.330  3868  3868 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 15:22:55.330  3868  3868 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 15:22:55.370   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 15:22:55.371  3868  3868 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f9ad6c2 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@290a3bb, 16908290=android.view.AbsSavedState$1@290a3bb}, android:focusedViewId=100}]}]
,08-16 15:22:55.371  3868  3868 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-16 15:22:55.372  3868  3868 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 15:22:55.372  3868  3868 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 15:22:55.385   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 15:22:55.389   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-16 15:22:55.389   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-16 15:22:55.390   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 15:22:55.409   871   880 I art     : Background partial concurrent mark sweep GC freed 4999(354KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/43MB, paused 1.600ms total 115.828ms
,08-16 15:22:55.616   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 15:22:55.619   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 15:22:55.625   871  1338 D SurfaceControl: Excessive delay in setPowerMode(): 236ms
,08-16 15:22:55.628   871   891 I DreamManagerService: Entering dreamland.
,08-16 15:22:55.630   871   891 I PowerManagerService: Dozing...
,08-16 15:22:55.631   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 15:22:55.697   374  1285 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-16 15:22:55.698   374  1285 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 15:22:55.701  2678  2678 D BtGatt.ScanManager: awakened up at time 151165
,08-16 15:22:55.702  2678  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 15:22:55.714  1904  3938 D NfcService: Discovery configuration equal, not updating.
,08-16 15:22:55.714   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 15:22:55.731   871  1313 E native  : do suspend false
,08-16 15:22:55.733  2678  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-16 15:22:55.734  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:55.734  2678  2703 D BtGatt.GattService: current time is 151198050904
08-16 15:22:55.734  2678  2703 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -89, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -91, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 15:22:55.734  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 15:22:55.735  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 15:22:55.735  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 15:22:55.735  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 15:22:55.747   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 15:22:55.756   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 15:22:55.759   871  1313 E native  : do suspend true
,08-16 15:22:55.834   374   374 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 15:22:55.835   374   374 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 15:22:56.221   871  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-16 15:22:57.241  2678  2678 D BtGatt.ScanManager: awakened up at time 152705
,08-16 15:22:57.244  2678  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 15:22:57.275  2678  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-16 15:22:57.275  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:57.276  2678  2703 D BtGatt.GattService: current time is 152739900276
,08-16 15:22:57.276  2678  2703 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -84, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 15:22:57.277  2678  2703 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 15:22:58.433  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:22:58.434  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 15:22:58.434  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 15:22:58.434  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:22:58.435  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 15:22:58.435  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 15:22:58.436  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 15:22:58.436  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 15:22:58.436  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 15:22:58.436  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 15:22:58.437  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 15:22:58.438  3868  3918 D BluetoothAdapter: STATE_ON
,08-16 15:22:58.439  2678  2689 D BtGatt.GattService: stopScan() - queue size =1
,08-16 15:22:58.441  2678  2690 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 15:22:58.442  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:22:58.442  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 15:22:58.442  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 15:22:58.443  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 15:22:58.443  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 15:22:58.445  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 15:22:58.446  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 15:22:58.446  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 15:22:58.446  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 15:22:58.449  2678  2678 D BtGatt.ScanManager: awakened up at time 153912
08-16 15:22:58.449  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 15:22:58.451  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 15:22:58.452  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 15:22:58.453  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 15:22:58.455  2678  2703 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 15:22:58.456  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:58.456  2678  2706 D BtGatt.ScanManager: stopping BLe Batch
,08-16 15:22:58.465  2678  2703 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 15:22:58.465  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:22:58.466  2678  2706 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 15:22:58.472  2678  2703 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 15:22:58.472  2678  2703 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:22:58.956  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 15:22:58.957  3868  3868 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:22:58.957  3868  3868 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 15:22:59.739  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:22:59.742  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:22:59.754  3816  3942 V GoogleAuthProtoRequest: [327] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 15:22:59.788  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 15:22:59.788  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 15:22:59.788  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:22:59.789  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: [327] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: [327] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 15:22:59.821  3816  3942 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 15:22:59.882  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:22:59.919  1520  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 15:22:59.919  1520  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 15:22:59.919  1520  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:22:59.920  1520  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:22:59.942  3510  3510 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 15:22:59.942  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 15:22:59.942  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-16 15:23:01.064  2167  2642 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 15:23:03.452  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:23:03.453  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 15:23:03.453  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:23:03.454  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 15:23:03.454  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.454  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:23:03.455  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:03.455  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.455  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.456  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:03.456  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.458  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.458  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.461  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:03.462  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:03.462  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.463  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:03.465  3868  3918 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-16 15:23:03.467  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:23:03.467  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:03.468  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:23:03.468  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:03.468  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.469  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.469  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:03.471  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.471  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.471  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:03.471  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.471  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.471  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.471  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.473  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:03.473  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:03.473  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.473  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:03.474  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 15:23:03.474  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:23:03.475  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:03.475  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:23:03.475  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 15:23:03.475  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.475  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.475  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:03.475  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.475  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.475  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 15:23:03.475  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.475  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.476  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.476  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.477  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 15:23:03.477  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:03.477  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:03.477  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.477  3868  3918 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 15:23:03.478  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:23:03.478  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:03.478  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-16 15:23:03.478  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 15:23:03.478  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.478  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.478  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
,08-16 15:23:03.478  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.478  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:03.479  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:03.479  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:03.479  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.479  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.479  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.480  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:03.480  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:23:03.481  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.481  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:03.481  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-16 15:23:03.481  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:23:03.482  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:03.482  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:23:03.482  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:03.482  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:03.482  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.482  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:03.482  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 15:23:03.482  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:03.482  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 15:23:03.482  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.482  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.483  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:03.483  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.484  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 15:23:03.484  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:03.484  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:03.484  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:03.484  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 15:23:03.485  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 15:23:03.485  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 15:23:03.485  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 15:23:03.485  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:23:03.485  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:23:03.485  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 15:23:03.485  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 15:23:03.485  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 15:23:03.486  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:23:03.486  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:03.486  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:23:03.486  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:03.486  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:03.486  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.486  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:03.486  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:03.486  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.486  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:03.486  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:03.487  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.487  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:03.487  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.488  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 15:23:03.488  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:03.488  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:03.488  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.489  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 15:23:03.490  3868  3918 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 15:23:03.490  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 15:23:03.493  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 15:23:03.493  3868  3918 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 15:23:03.494  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-16 15:23:03.495  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-16 15:23:03.496  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 15:23:03.496  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 15:23:03.496  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-16 15:23:03.496  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 15:23:03.496  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 15:23:03.496  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 15:23:03.496  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-16 15:23:03.497  3868  3918 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 15:23:03.497  3868  3918 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 15:23:03.497  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 15:23:03.497  3868  3918 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-16 15:23:03.497  3868  3918 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 15:23:03.497  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 15:23:03.498  3868  3918 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 15:23:03.498  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-16 15:23:03.502  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 15:23:03.503  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 15:23:03.503  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 15:23:03.504  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-16 15:23:03.504  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 15:23:03.504  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 15:23:03.504  3868  3918 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 15:23:03.505  3868  3918 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-16 15:23:03.506  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:23:03.506  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:03.506  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:23:03.506  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:03.506  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.506  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.506  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 15:23:03.508  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:03.508  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:03.508  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.508  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:03.508  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.508  3868  3944 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 406)
08-16 15:23:03.508  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.508  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.508  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.510  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 15:23:03.510  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:03.510  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.511  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.511  3868  3945 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 406
08-16 15:23:03.512  3868  3944 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:23:03.512  3868  3918 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 15:23:03.514  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:23:03.514  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:03.514  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:23:03.514  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:03.514  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.515  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.515  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:03.515  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.515  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:03.515  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:03.515  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.515  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.515  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.515  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.517  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:03.517  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:03.517  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:03.517  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.518  3868  3918 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 15:23:03.519  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:23:03.519  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:03.519  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:23:03.520  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:03.520  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:03.520  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.520  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:03.520  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.520  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.520  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:03.521  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.521  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.521  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:03.521  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.522  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:03.522  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:03.522  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.522  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.523  3868  3918 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 15:23:03.523  3868  3918 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-16 15:23:03.523  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 15:23:03.523  3868  3918 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 15:23:03.523  3868  3918 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 15:23:03.523  3868  3918 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 15:23:03.523  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 15:23:03.524  3868  3918 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 15:23:03.524  3868  3918 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 15:23:03.524  3868  3918 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-16 15:23:03.524  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 15:23:03.524  3868  3918 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 15:23:03.524  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:23:03.524  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:03.524  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:23:03.524  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:03.524  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.524  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.524  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:03.525  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.525  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.525  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:03.525  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.525  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:03.525  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.525  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.526  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:03.526  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:03.526  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.526  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.527  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:03.527  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.527  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:03.527  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:03.527  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:03.527  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:03.527  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:03.527  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:03.527  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:04.314   871   883 I ActivityManager: Start proc 3946:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-16 15:23:04.391  3946  3946 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-16 15:23:04.489  1520  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 15:23:04.489  1520  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 15:23:04.489  1520  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 15:23:04.489  1520  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 15:23:04.490  3946  3946 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-16 15:23:04.502  3946  3946 I BooksApp: Created application version: 3.6.9 (30609)
,08-16 15:23:04.502  3548  3957 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 15:23:04.502  3548  3957 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at jdm.a(PG:82)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at blb.a(PG:3937)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at czp.a(PG:18188)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at czp.a(PG:9081)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:23:04.502  3548  3957 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	... 12 more
08-16 15:23:04.502  3548  3957 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at fal.a(PG:38)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:23:04.502  3548  3957 E HttpOperation: 	... 14 more
,08-16 15:23:04.541  1520  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 15:23:04.542  1520  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 15:23:04.543  1520  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:23:04.543  1520  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:04.556  3548  3957 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 15:23:04.556  3548  3957 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at jdm.a(PG:82)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at hec.a(PG:42)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at hee.a(PG:102)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at czr.a(PG:65)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at kka.a(PG:108)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at czp.a(PG:19176)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at czp.a(PG:9081)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:23:04.556  3548  3957 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	... 15 more
08-16 15:23:04.556  3548  3957 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at fal.a(PG:38)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:23:04.556  3548  3957 E HttpOperation: 	... 17 more
,08-16 15:23:04.556  3548  3957 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 15:23:04.556  3548  3957 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at hec.a(PG:42)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at hee.a(PG:102)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at czr.a(PG:65)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at kka.a(PG:108)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	... 15 more
08-16 15:23:04.556  3548  3957 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at fal.a(PG:38)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 15:23:04.556  3548  3957 E ExperimentLoader: 	... 17 more
,08-16 15:23:04.628  3946  3966 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 15:23:04.698   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 132445, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:23:04.764  3946  3972 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 15:23:04.831  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 15:23:04.832  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 15:23:04.832  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 15:23:04.833  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:04.908  1520  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 15:23:04.908  1520  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 15:23:04.908  1520  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:23:04.909  1520  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:04.952  3946  3972 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 15:23:04.963  3946  3966 E BooksSync: Soft error
08-16 15:23:04.963  3946  3966 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 15:23:04.963  3946  3966 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 15:23:04.964  3946  3966 E BooksSync: Sync error
08-16 15:23:04.964  3946  3966 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 15:23:04.964  3946  3966 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 15:23:04.968  3946  3966 I BooksSync: Finished books sync
,08-16 15:23:04.980   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 132062, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:23:04.987   871  1965 I ActivityManager: Killing 2969:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-16 15:23:06.682   871  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-16 15:23:08.528  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:08.529  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:08.529  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 15:23:08.530  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:08.530  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.530  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:08.531  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:23:08.531  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:08.531  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:23:08.532  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:08.532  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:08.532  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.533  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:08.533  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:08.533  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:08.534  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:08.534  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:08.534  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.535  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:08.535  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.538  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:08.539  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:23:08.539  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:08.539  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:08.544  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 15:23:08.545  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 15:23:08.548  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 15:23:08.548  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 15:23:08.549  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 15:23:08.549  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 15:23:08.549  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 15:23:08.549  3868  3868 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-16 15:23:08.549  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 15:23:08.550  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-16 15:23:08.550  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 15:23:08.550  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 15:23:08.550  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.550  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 15:23:08.550  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list,
,08-16 15:23:08.550  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:08.550  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 15:23:08.550  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 15:23:08.550  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 15:23:08.550  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:08.551  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.550  3868  3973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 15:23:08.551  3868  3868 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 15:23:08.551  3868  3973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 15:23:08.552  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 15:23:08.552  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:08.552  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:23:08.552  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 15:23:08.552  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:08.552  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:23:08.552  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:08.553  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:08.553  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.552  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 15:23:08.553  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:08.553  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:08.553  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:08.553  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 15:23:08.553  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:08.554  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:08.554  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.554  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:08.554  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.554  3868  3868 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 15:23:08.555  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:08.555  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:23:08.555  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:08.555  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:08.557  3868  3918 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 15:23:08.557  3868  3918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-16 15:23:08.557  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 15:23:08.557  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:23:08.557  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:23:08.557  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:23:08.558  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:08.558  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:23:08.558  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:08.558  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:08.558  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.558  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:08.558  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:08.558  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:08.558  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:08.558  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:08.558  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.558  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:08.559  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.561  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:08.561  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:08.561  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:08.561  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
,08-16 15:23:08.566  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:23:08.566  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:23:08.566  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:23:08.566  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:08.566  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:08.566  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.566  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
,08-16 15:23:08.567  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:08.567  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:08.567  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:08.567  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:08.567  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.567  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:08.567  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:08.568  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:08.568  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:08.568  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:08.568  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:08.569  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:23:08.570  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 15:23:08.570  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:23:08.570  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:23:08.570  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:08.570  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.570  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15220c1 not in the list
08-16 15:23:08.570  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:08.570  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:08.570  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:08.571  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:08.571  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.571  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:08.571  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:08.572  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:23:08.572  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:23:08.572  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:08.572  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c38f066 not in the list
08-16 15:23:08.573  3868  3918 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 15:23:08.573  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 15:23:08.573  3868  3918 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 15:23:08.573  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-16 15:23:08.574  3868  3918 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 15:23:08.574  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 15:23:08.577  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 15:23:08.577  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-16 15:23:08.580  3868  3918 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 15:23:08.580  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 15:23:08.580  3868  3918 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 15:23:08.580  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 15:23:08.580  3868  3918 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-16 15:23:08.580  3868  3918 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 15:23:08.581  3868  3918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 15:23:08.581  3868  3918 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 15:23:08.582  3868  3918 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 15:23:08.582  3868  3918 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-16 15:23:08.582  3868  3918 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 15:23:08.582  3868  3918 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 15:23:08.583  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:23:08.583  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@603bc31 added. We now have 3 listener(s)
08-16 15:23:08.583  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:23:08.585  3868  3918 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 15:23:08.585   871  2162 D WifiService: setWifiEnabled: true pid=3868, uid=10000
08-16 15:23:08.585   871  2162 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 15:23:08.648  2678  2789 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-16 15:23:08.648  2678  2805 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
08-16 15:23:08.649  3868  3944 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 406)
,08-16 15:23:09.055  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 15:23:09.506  3946  3963 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-16 15:23:13.591  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 15:23:13.592  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d43f16 added. We now have 4 listener(s)
,08-16 15:23:13.592  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:23:13.608  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:13.608  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d43f16 removed from the list
,08-16 15:23:13.608  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:13.609  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:23:13.609  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:13.612  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:23:13.613  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39bc097 added. We now have 4 listener(s)
08-16 15:23:13.614  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:23:13.617  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:13.618  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39bc097 removed from the list
08-16 15:23:13.618  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 15:23:13.618  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:13.619  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:13.622  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:23:13.622  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c93284 added. We now have 4 listener(s)
,08-16 15:23:13.623  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:23:13.629   871  1965 D WifiService: setWifiEnabled: false pid=3868, uid=10000
,08-16 15:23:13.630   871  1965 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 15:23:13.646  2678  2698 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 15:23:13.646  2678  2698 D BluetoothAdapterProperties: Setting state to 13
08-16 15:23:13.646  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:23:13.646  2678  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 15:23:13.649  2678  2698 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 15:23:13.650  2678  2698 I BluetoothAdapterState: Entering PendingCommandState
08-16 15:23:13.652  2678  2678 D BluetoothMapService: onReceive
,08-16 15:23:13.653  2678  2678 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 15:23:13.653  2678  2678 D BluetoothMapService: STATE_TURNING_OFF
,08-16 15:23:13.654  2678  2678 D BluetoothMapService: MAP Service closeService in
,08-16 15:23:13.654  2678  2678 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 15:23:13.654  2678  2678 D ObexServerSockets0: shutdown(block = true)
,08-16 15:23:13.658  2678  2818 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 15:23:13.660  2678  2678 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 15:23:13.661  2678  2819 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 15:23:13.662  2678  2805 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 15:23:13.663  2678  2678 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 15:23:13.663  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:13.663  2678  2678 I BtOppRfcommListener: stopping Accept Thread
08-16 15:23:13.663  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:23:13.663  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:13.663  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:13.663  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:13.663  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:13.663  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:13.663  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:23:13.663  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:23:13.664  2678  3430 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:23:13.665  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:13.666  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:23:13.666  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 15:23:13.667  2678  3430 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 15:23:13.669  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:13.671  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 15:23:13.672  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:13.674   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 15:23:13.675   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 15:23:13.675   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 15:23:13.675   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 15:23:13.677  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.677  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:13.677  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:13.677  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:13.677  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:13.677  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:13.677  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:13.677  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:23:13.677  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:23:13.678  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:13.678  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:13.681  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:13.681  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:13.681  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:13.681  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:13.681  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:13.681  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:13.681  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:13.681  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:23:13.681  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:23:13.681   871   884 I ActivityManager: Start proc 3979:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-16 15:23:13.682  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.682  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:13.683  2678  2703 D BluetoothAdapterProperties: Scan Mode:20
08-16 15:23:13.683  2678  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 15:23:13.687  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:13.688   871  1313 E native  : do suspend true
08-16 15:23:13.691  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:13.693  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:13.693  2678  2678 D HeadsetService: Received stop request...Stopping profile...
,08-16 15:23:13.695   871   871 D BluetoothHeadset: Proxy object disconnected
,08-16 15:23:13.695  1914  2172 D BluetoothHeadset: Proxy object disconnected
08-16 15:23:13.695  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:13.695   871   871 D BluetoothHeadset: Proxy object disconnected
08-16 15:23:13.695  1368  1985 D BluetoothHeadset: Proxy object disconnected
08-16 15:23:13.696  1368  1368 D HeadsetProfile: Bluetooth service disconnected
,08-16 15:23:13.696   871   871 D BluetoothHeadset: Proxy object disconnected
,08-16 15:23:13.696  2678  2678 D A2dpService: Received stop request...Stopping profile...
08-16 15:23:13.697  2678  2811 D A2dpStateMachine: Exit Disconnected: -1
08-16 15:23:13.699   871   871 D BluetoothA2dp: Proxy object disconnected
,08-16 15:23:13.699   871  1878 D DhcpClient: Clearing IP address
08-16 15:23:13.699  1368  1368 D BluetoothA2dp: Proxy object disconnected
08-16 15:23:13.699   370   869 D CommandListener: Clearing all IP addresses on wlan0
08-16 15:23:13.701  2678  2678 D HidService: Received stop request...Stopping profile...
08-16 15:23:13.701  2678  2678 D HidService: Stopping Bluetooth HidService
,08-16 15:23:13.702  1368  1368 D BluetoothInputDevice: Proxy object disconnected
08-16 15:23:13.702  1368  1368 D HidProfile: Bluetooth service disconnected
,08-16 15:23:13.702   370   869 D CommandListener: Setting iface cfg
08-16 15:23:13.702  2678  2678 D HealthService: Received stop request...Stopping profile...
08-16 15:23:13.703   871  1891 D DhcpClient: Receive thread stopped
08-16 15:23:13.704  2678  2678 D PanService: Received stop request...Stopping profile...
08-16 15:23:13.707  1368  1368 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 15:23:13.707  1368  1368 D PanProfile: Bluetooth service disconnected
08-16 15:23:13.707   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 15:23:13.707   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-16 15:23:13.707  1520  2155 V NativeCrypto: Read error: ssl=0xaa1f4800: I/O error during system call, Connection timed out
08-16 15:23:13.708  2678  2678 D BluetoothMapService: Received stop request...Stopping profile...
08-16 15:23:13.708  2678  2678 D BluetoothMapService: stop()
08-16 15:23:13.710   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 1
08-16 15:23:13.710   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 15:23:13.710   871  1313 E native  : do suspend true
08-16 15:23:13.711   430   430 E Parcel  : Reading a NULL string not supported here.
08-16 15:23:13.712  1520  2155 V NativeCrypto: SSL shutdown failed: ssl=0xaa1f4800: I/O error during system call, Broken pipe
08-16 15:23:13.712   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 15:23:13.713  2678  2678 D BluetoothMapAppObserver: deinitObservers()
,08-16 15:23:13.713  2678  2678 D BluetoothMapAppObserver: removeReceiver()
08-16 15:23:13.714  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-16 15:23:13.714  2678  2678 V BluetoothAdapterState: isTurningOn()=false
,08-16 15:23:13.716  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:13.716  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:13.717  2678  2678 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 15:23:13.718  2678  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 15:23:13.717  2678  2703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 15:23:13.718  2678  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 15:23:13.718  2678  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 15:23:13.717  2678  2678 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-16 15:23:13.718  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-16 15:23:13.718  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:13.718  2678  2703 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 15:23:13.718  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:13.718  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:13.719  2678  2703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 15:23:13.719  2678  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 15:23:13.719  2678  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 15:23:13.720  2678  2789 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:23:13.720  2678  2789 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-16 15:23:13.720  2678  2789 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:23:13.720  2678  2789 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:23:13.720  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-16 15:23:13.720  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:13.720  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 15:23:13.720  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:13.721  2678  2678 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 15:23:13.721  2678  2703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 15:23:13.721  2678  2678 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 15:23:13.721  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-16 15:23:13.721  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:13.721  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 15:23:13.721  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:13.722  2678  2678 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 15:23:13.722  2678  2703 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 15:23:13.722  2678  2678 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 15:23:13.722  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-16 15:23:13.722  2678  2678 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:13.722  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 15:23:13.722  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:13.723  2678  2678 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 15:23:13.723  2678  2678 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 15:23:13.724  2678  2678 D BluetoothMapService: MAP Service closeService in
08-16 15:23:13.725  2678  2678 V BluetoothAdapterState: isTurningOff()=true
08-16 15:23:13.725  2678  2678 V BluetoothAdapterState: isTurningOn()=false
,08-16 15:23:13.725  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:13.725  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:13.725  2678  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 15:23:13.725  2678  2698 D BluetoothAdapterProperties: Setting state to 15
08-16 15:23:13.725  2678  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 15:23:13.726  1368  1985 D BluetoothPan: onBluetoothStateChange on: false
08-16 15:23:13.726  2678  2698 I BluetoothAdapterState: Entering BleOnState
08-16 15:23:13.726  1368  2018 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 15:23:13.727   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:23:13.726  2678  2678 D BluetoothMapService: cleanup()
08-16 15:23:13.727  1914  2156 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 15:23:13.727  2678  2678 D BluetoothMapService: MAP Service closeService in
08-16 15:23:13.727   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:23:13.727   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:23:13.727   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 15:23:13.727  1368  1385 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:23:13.728  1368  1393 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 15:23:13.729  1368  1985 D BluetoothMap: onBluetoothStateChange: up=false
08-16 15:23:13.729  1368  2018 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 15:23:13.730  2678  2698 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-16 15:23:13.730  2678  2698 D BluetoothAdapterProperties: Setting state to 16
08-16 15:23:13.730  2678  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 15:23:13.733  2678  2698 D BluetoothAdapterProperties: onBleDisable
08-16 15:23:13.734  2678  2698 I BluetoothAdapterState: Entering PendingCommandState
08-16 15:23:13.734  2678  2700 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 15:23:13.734  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.734  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:13.734  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:13.734  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:13.734  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:13.734  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:13.734  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:13.734  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:13.734  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:13.735  2678  2789 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 15:23:13.735  2678  2789 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 15:23:13.735  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.735  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:13.735  2678  2703 D BluetoothAdapterProperties: Scan Mode:20
08-16 15:23:13.737  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.737  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:13.737  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:13.737  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:13.737  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:13.737  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:13.737  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:13.737  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:13.737  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:13.737  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:13.737  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:13.739  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.739  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:13.739  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:13.739  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:13.739  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:13.739  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:13.739  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:13.739  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:13.739  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:13.740  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.740  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:13.741  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:13.743  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:13.744  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:13.745  3979  3979 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-16 15:23:13.746   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 15:23:13.766  3979  3979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 15:23:13.768   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 15:23:13.768   370   869 D CommandListener: Clearing all IP addresses on wlan0
,08-16 15:23:13.769   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 15:23:13.769   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:23:13.771   871   888 D Tethering: MasterInitialState.processMessage what=3
08-16 15:23:13.773   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 15:23:13.776  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:13.778  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:13.779  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:13.779  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 15:23:13.783   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5b6bc77:true
,08-16 15:23:13.791   871  1386 I ActivityManager: Start proc 3997:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 15:23:13.793   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 15:23:13.796   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 15:23:13.797  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.797  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:13.797  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:13.797  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:13.797  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:13.797  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:13.797  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:13.797  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:13.797  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 15:23:13.797  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.797  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:23:13.798  2167  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:23:13.799  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.799  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:13.799  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:13.799  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:13.799  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:13.799  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:13.799  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:13.799  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:13.799  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 15:23:13.800  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.800  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:23:13.802  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:13.802  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:13.802  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:13.802  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:13.802  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:13.802  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:13.802  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:13.802  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:13.802  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:13.802  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:13.802  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:23:13.821  3979  3979 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 15:23:13.825  3979  3979 D BluetoothMap: Create BluetoothMap proxy object
,08-16 15:23:13.833   370   869 E Netd    : netlink response contains error (No such file or directory)
,08-16 15:23:13.834  3979  3979 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 15:23:13.837  3997  3997 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 15:23:13.841  3979  3979 D DockEventReceiver: finishStartingService: stopping service
,08-16 15:23:13.854   871  2163 I ActivityManager: Killing 3670:com.google.android.deskclock/u0a44 (adj 15): empty #17
,08-16 15:23:13.939  2678  2703 I bt_hci  : shut_down
,08-16 15:23:13.948  2678  2707 I bt_vendor: low_power_mode_cb
,08-16 15:23:13.948  2678  2707 D bt_hwcfg: hw_epilog_process
,08-16 15:23:13.977  2678  2707 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 15:23:13.977  2678  2707 I bt_vendor: epilog_cb
,08-16 15:23:13.977  2678  2707 I bt_hci  : epilog_finished_callback
,08-16 15:23:13.983  2678  2703 I bt_hci_h4: hal_close
,08-16 15:23:13.985  2678  2703 I bt_userial_vendor: device fd = 51 close
,08-16 15:23:13.995  3997  3997 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 15:23:13.995  3997  3997 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 15:23:13.995  3997  3997 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 15:23:13.995  3997  3997 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 15:23:13.995  3997  3997 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 15:23:13.995  3997  3997 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 15:23:13.995  3997  3997 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 15:23:13.995  3997  3997 D StrictMode: ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 15:23:13.995  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 15:23:13.996  3997  3997 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 15:23:13.996  3997  3997 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
,08-16 15:23:13.996  3997  3997 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 15:23:13.996  3997  3997 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 15:23:14.035   871   882 I ActivityManager: Start proc 4028:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-16 15:23:14.036   871   882 I ActivityManager: Killing 3688:com.qualcomm.timeservice/1000 (adj 15): empty #17
,08-16 15:23:14.119  2678  2700 D bt_stack_manager: event_shut_down_stack finished.
,08-16 15:23:14.120  2678  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 15:23:14.122  2678  2698 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 15:23:14.122  2678  2678 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 15:23:14.123  2678  2678 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 15:23:14.123  2678  2678 D BtGatt.GattService: stop()
08-16 15:23:14.124  2678  2678 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 15:23:14.129  2678  2678 V BluetoothAdapterState: isTurningOff()=false
,08-16 15:23:14.129  2678  2678 V BluetoothAdapterState: isTurningOn()=false
,08-16 15:23:14.130  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:14.130  2678  2678 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 15:23:14.131  2678  2698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 15:23:14.131  2678  2698 D BluetoothAdapterProperties: Setting state to 10
,08-16 15:23:14.131  2678  2698 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 15:23:14.133  2678  2698 I BluetoothAdapterState: Entering OffState
,08-16 15:23:14.134   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 15:23:14.137  4028  4028 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 15:23:14.161  2678  2678 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 15:23:14.161  2678  2678 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 15:23:14.161  2678  2700 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 15:23:14.164  2678  2700 D bt_stack_manager: event_clean_up_stack finished.
,08-16 15:23:14.164  2678  2678 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 15:23:14.165  2678  2678 I art     : System.exit called, status: 0
,08-16 15:23:14.166  2678  2678 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 15:23:14.215   871   882 I ActivityManager: Process com.android.bluetooth (pid 2678) has died
,08-16 15:23:14.398  4028  4049 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 15:23:14.399  4028  4049 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 15:23:14.405  3997  4020 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 15:23:14.410  4028  4049 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 15:23:14.410  4028  4049 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 15:23:14.469  4028  4049 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 15:23:14.469  4028  4049 I Babel_SMS: MmsConfig.loadFromResources
,08-16 15:23:14.472  4028  4049 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 15:23:14.473  4028  4049 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 15:23:14.505  4028  4028 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 15:23:14.507  4028  4028 I Babel_Crash: startup - clean
,08-16 15:23:14.534  4028  4028 I Babel_telephony: TeleModule.launchCompleted
,08-16 15:23:14.547   871  2163 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 15:23:14.564  4028  4028 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 15:23:14.571  4028  4028 W Babel   : BAM#gBA: invalid account id: -1
,08-16 15:23:14.572  4028  4028 W Babel   : BAM#gBA: invalid account id: -1
08-16 15:23:14.572  4028  4028 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 15:23:14.582  4028  4055 I Babel   : deleted: false for 0
,08-16 15:23:14.589  3510  3520 D Finsky  : [268] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-16 15:23:14.592   871  2162 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 15:23:14.597  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:14.627  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:14.637  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:14.638  3979  3979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 15:23:14.669   871  1398 I ActivityManager: Start proc 4058:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-16 15:23:14.672  3979  3979 D DockEventReceiver: finishStartingService: stopping service
,08-16 15:23:14.678   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9fff999:true
,08-16 15:23:14.724  4028  4028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 15:23:14.743  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-16 15:23:14.743  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-16 15:23:14.743  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:23:14.744  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:14.767  3510  3520 D Finsky  : [268] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-16 15:23:14.824  4028  4028 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 15:23:14.840  4028  4028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 15:23:14.851  4058  4058 D AdapterServiceConfig: Adding HeadsetService
08-16 15:23:14.852  4058  4058 D AdapterServiceConfig: Adding A2dpService
08-16 15:23:14.852  4058  4058 D AdapterServiceConfig: Adding HidService
08-16 15:23:14.852  4058  4058 D AdapterServiceConfig: Adding HealthService
,08-16 15:23:14.852  4058  4058 D AdapterServiceConfig: Adding PanService
08-16 15:23:14.852  4058  4058 D AdapterServiceConfig: Adding GattService
,08-16 15:23:14.852  4058  4058 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 15:23:14.854  4028  4028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 15:23:14.858  4028  4028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 15:23:14.865  4028  4028 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 15:23:14.867  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 15:23:14.895  4028  4028 I vclib   : onServiceConnected
08-16 15:23:14.897   871  1965 I ActivityManager: Killing 3492:android.process.acore/u0a5 (adj 15): empty #17
,08-16 15:23:15.006  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 15:23:15.017  1740  1740 D SystemUpdateService: onCreate
,08-16 15:23:15.024  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 15:23:15.034  1740  4070 I SystemUpdateService: active receiver: enabled
,08-16 15:23:15.043  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 15:23:15.044  1740  4070 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 15:23:15.047  1740  2423 I iu.UploadsManager: num queued entries: 0
,08-16 15:23:15.049  1740  2423 I iu.UploadsManager: num updated entries: 0
,08-16 15:23:15.051  1740  2423 I iu.SyncManager: NEXT; no task
,08-16 15:23:15.055  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 15:23:15.056  1740  4070 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 15:23:15.056  1740  4070 I SystemUpdateService: now status is 0 (complete)
08-16 15:23:15.056  1740  4070 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 15:23:15.056  1740  4070 I SystemUpdateService: file has been verified
08-16 15:23:15.056  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 15:23:15.057  1740  4070 I SystemUpdateService: OTA package size = 12249756
,08-16 15:23:15.064  1740  4070 I SystemUpdateService: showing system update notification
,08-16 15:23:15.077   871   881 I ActivityManager: Start proc 4072:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 15:23:15.092  1740  1740 D SystemUpdateService: onDestroy
,08-16 15:23:15.119  4072  4072 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 15:23:15.122  4072  4072 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:23:15.130  4072  4072 D SprintDMHelper: simOperator: 
08-16 15:23:15.130  4072  4072 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 15:23:15.145   871  1398 I ActivityManager: Start proc 4084:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 15:23:15.147   871  1398 I ActivityManager: Killing 3716:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 15:23:15.263   871  1936 I ActivityManager: Start proc 4099:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 15:23:15.266  4028  4098 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 15:23:15.270   871  2163 I ActivityManager: Killing 3729:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 15:23:15.322  4099  4099 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 15:23:15.376  4099  4099 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 15:23:15.376  4099  4099 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 15:23:15.376  4099  4099 I GAv4    :   adb logcat -s GAv4
,08-16 15:23:15.395  4099  4099 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 15:23:15.402  4099  4099 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 15:23:15.430  4099  4116 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 15:23:15.541  4099  4099 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 15:23:15.577  4099  4099 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 15:23:15.591  4099  4099 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1052-1055)
08-16 15:23:15.592  4099  4099 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 15:23:15.605  4099  4099 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d2b5a00}
,08-16 15:23:15.605  4099  4099 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 15:23:15.607  4099  4099 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 15:23:15.615  4099  4099 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 15:23:15.617  4099  4099 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 15:23:15.640  4099  4099 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 15:23:15.657  4099  4099 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 15:23:15.657  4099  4099 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 15:23:15.657  4099  4099 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 15:23:15.657  4099  4099 I Adreno  : Build Date                       : 10/20/15
08-16 15:23:15.657  4099  4099 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 15:23:15.657  4099  4099 I Adreno  : Local Branch                     : M14
08-16 15:23:15.657  4099  4099 I Adreno  : Remote Branch                    : 
08-16 15:23:15.657  4099  4099 I Adreno  : Remote Branch                    : 
08-16 15:23:15.657  4099  4099 I Adreno  : Reconstruct Branch               : 
,08-16 15:23:15.720  4099  4099 I NSApplication: Starting up...
08-16 15:23:15.723  4099  4145 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 15:23:15.760   871  1386 I ActivityManager: Start proc 4150:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 15:23:15.762   871  1386 I ActivityManager: Killing 2242:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 15:23:15.873  4150  4150 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 15:23:16.086   871  1398 I ActivityManager: Killing 3647:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-16 15:23:18.670   871  1400 D WifiService: setWifiEnabled: true pid=3868, uid=10000
,08-16 15:23:18.670   871  1400 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 15:23:18.684   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-16 15:23:18.693  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:18.693  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:18.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:18.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:18.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:18.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:18.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:18.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:18.693  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:18.693  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:18.694  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:18.696  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:18.697  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:18.697  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:18.697  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:18.697  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:18.697  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:18.697  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:18.697  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:18.697  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:18.697  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:18.697  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:23:18.700  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:18.700  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:18.700  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:18.700  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:18.700  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:18.700  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:18.700  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:18.700  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:18.700  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:18.700  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:18.700  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:23:18.720   871  1313 D WifiConfigStore: loaded 0 passpoint configs
,08-16 15:23:18.721   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 15:23:18.722   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 15:23:18.723   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory),
,08-16 15:23:18.723   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 15:23:18.723   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 15:23:18.723   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 15:23:18.743   370   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 15:23:18.744   370   869 D CommandListener: Setting iface cfg
,08-16 15:23:18.745   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-16 15:23:18.745   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 15:23:18.745   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 15:23:18.750   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 15:23:18.751   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 15:23:18.778   871  1313 E native  : do suspend true
,08-16 15:23:18.791   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 15:23:19.468   871  1933 I ActivityManager: Killing 3754:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 15:23:20.162   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 15:23:20.232   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.50 rxSuccessRate=12.44 delta 1000 -> 994
,08-16 15:23:20.233   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 15:23:20.233   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 15:23:20.250   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 15:23:20.300   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 15:23:20.302  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 15:23:20.740  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 15:23:20.787  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 15:23:20.788  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 15:23:20.800   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 15:23:20.817   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 15:23:20.817   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 15:23:20.817   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 15:23:20.850   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 15:23:20.868   370   869 D CommandListener: Setting iface cfg
08-16 15:23:20.869   871  1313 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 15:23:20.874   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 15:23:20.922   871  4176 D DhcpClient: Receive thread started
,08-16 15:23:21.004   871  1313 E native  : do suspend false
,08-16 15:23:21.023   871  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 15:23:21.036   871  4176 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172645, domain null
,08-16 15:23:21.037   871  1878 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172645 seconds
08-16 15:23:21.040   871  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 15:23:21.059   871  4176 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 15:23:21.060   871  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
08-16 15:23:21.066   370   869 D CommandListener: Setting iface cfg
,08-16 15:23:21.076   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 15:23:21.079   871  1878 D DhcpClient: Scheduling renewal in 86399s
,08-16 15:23:21.080   871  1313 E native  : do suspend true
,08-16 15:23:21.105   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 15:23:21.107   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 15:23:21.110   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 15:23:21.113   871  1315 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 15:23:21.114   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 15:23:21.162   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 15:23:21.162   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 15:23:21.164   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 15:23:21.165   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 15:23:21.167   871  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 15:23:21.186   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 15:23:21.199   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 15:23:21.199   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-16 15:23:21.200   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 15:23:21.200   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 15:23:21.201   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-16 15:23:21.201   871  1315 D ConnectivityService:    accepting network in place of null
,08-16 15:23:21.202   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 15:23:21.211   871  4175 D NetlinkSocketObserver: NeighborEvent{elapsedMs=176675, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 15:23:21.252   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 15:23:21.277   871  4174 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:817::200e
,08-16 15:23:21.319   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 15:23:21.324   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 15:23:21.324   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 15:23:21.325   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-16 15:23:21.327   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-16 15:23:21.336  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:21.336  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:21.336  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:21.336  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:21.336  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:21.336  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:21.336  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:21.336  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:23:21.336  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:23:21.337  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:21.337  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:23:21.346  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:21.346  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:21.346  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:21.346  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:21.346  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:21.346  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:21.346  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:21.346  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:23:21.346  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:23:21.346  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:21.346  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:21.349  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:23:21.349  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 15:23:21.349  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:21.349  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:21.349  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:21.349  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:21.349  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:21.349  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:21.349  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:23:21.349  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:23:21.349  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:21.349  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:23:21.358  1740  1740 D SystemUpdateService: onCreate
,08-16 15:23:21.361  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 15:23:21.364   871  4174 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 13:23:21 GMT], X-Android-Received-Millis=[1471353801363], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471353801334]}
,08-16 15:23:21.365   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 15:23:21.365   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 15:23:21.365   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 15:23:21.366   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 15:23:21.387  1740  4185 I SystemUpdateService: active receiver: enabled
,08-16 15:23:21.397  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 15:23:21.403  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 15:23:21.404  1740  2423 I iu.UploadsManager: num queued entries: 0
,08-16 15:23:21.404  1740  2423 I iu.UploadsManager: num updated entries: 0
,08-16 15:23:21.405  1740  2423 I iu.SyncManager: NEXT; no task
,08-16 15:23:21.406  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 15:23:21.408  1740  4185 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 15:23:21.414  4072  4072 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:23:21.419  1740  4189 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 15:23:21.420  1740  4189 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 15:23:21.421  1740  4185 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 15:23:21.421  1740  4185 I SystemUpdateService: now status is 0 (complete)
,08-16 15:23:21.421  1740  4185 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 15:23:21.421  1740  4185 I SystemUpdateService: file has been verified
,08-16 15:23:21.422  1740  4189 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 15:23:21.423  4072  4072 D SprintDMHelper: simOperator: 
,08-16 15:23:21.423  4072  4072 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 15:23:21.427  1740  4185 I SystemUpdateService: OTA package size = 12249756
,08-16 15:23:21.441  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:21.447  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:21.475  1740  4185 I SystemUpdateService: showing system update notification
,08-16 15:23:21.521  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 15:23:21.521  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-16 15:23:21.521  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 15:23:21.521  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:21.523  1740  1740 D SystemUpdateService: onDestroy
,08-16 15:23:21.546  1740  4189 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-16 15:23:21.573  4028  4191 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 15:23:22.325   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 15:23:23.677   871  1966 D WifiService: setWifiEnabled: false pid=3868, uid=10000
,08-16 15:23:23.677   871  1966 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 15:23:23.710  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 15:23:23.715   871  1313 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 15:23:23.715   871  1313 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 15:23:23.715   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 15:23:23.716   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 15:23:23.737   871  1313 E native  : do suspend true
,08-16 15:23:23.750   871  1878 D DhcpClient: Clearing IP address
,08-16 15:23:23.750   370   869 D CommandListener: Clearing all IP addresses on wlan0
,08-16 15:23:23.754   370   869 D CommandListener: Setting iface cfg
,08-16 15:23:23.764  1520  4195 V NativeCrypto: Read error: ssl=0x9a34ac00: I/O error during system call, Connection timed out
,08-16 15:23:23.768   871  4176 D DhcpClient: Receive thread stopped
,08-16 15:23:23.770   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 15:23:23.770   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 15:23:23.769  1520  4195 V NativeCrypto: SSL shutdown failed: ssl=0x9a34ac00: I/O error during system call, Broken pipe
,08-16 15:23:23.777   430   430 E Parcel  : Reading a NULL string not supported here.
,08-16 15:23:23.778   871  1313 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-16 15:23:23.782   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 15:23:23.782   871  1313 E native  : do suspend true
08-16 15:23:23.783   871  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 15:23:23.823   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 15:23:23.851   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 15:23:23.851   370   869 D CommandListener: Clearing all IP addresses on wlan0
08-16 15:23:23.853   871  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 15:23:23.853   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:23:23.859   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 15:23:23.860   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-16 15:23:23.867  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.867  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:23.867  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:23.867  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:23.867  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:23.867  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:23.867  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:23.867  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:23.867  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:23.868  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.868  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:23.870  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.870  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:23.870  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:23.870  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:23.870  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:23.870  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:23.870  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:23.870  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:23.870  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:23.870  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.871  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:23.873  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.873  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:23.873  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:23.873  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:23.873  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:23.873  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:23.873  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:23.873  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:23.873  3868  3868 V io.jxcore.node.ConnectivityMonitor:  ,   - active network type is Wi-Fi: false
08-16 15:23:23.873  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.874  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:23.884   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 15:23:23.886  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.886  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:23.886  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:23.886  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:23.886  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:23.886  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:23.886  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:23.886  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:23.886  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:23.886  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.886  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:23.887  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.888  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:23.888  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:23.888  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:23.888  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:23.888  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:23.888  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:23.888  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:23.888  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:23.888  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.888  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:23.889   871  1313 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 15:23:23.889  2167  2321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:23:23.890  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.890  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:23.890  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:23.890  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:23.890  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:23.890  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:23.890  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:23.890  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:23.890  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:23.890  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:23.890  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:23.891  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-16 15:23:23.900  1740  1740 D SystemUpdateService: onCreate
08-16 15:23:23.904  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 15:23:23.916  1740  4206 I SystemUpdateService: active receiver: enabled
08-16 15:23:23.917  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-16 15:23:23.919  1740  2423 I iu.UploadsManager: num queued entries: 0
08-16 15:23:23.928  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 15:23:23.929  1740  2423 I iu.UploadsManager: num updated entries: 0
08-16 15:23:23.942   370   869 E Netd    : netlink response contains error (No such file or directory)
08-16 15:23:23.942  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 15:23:23.943   871  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 15:23:23.944  4072  4072 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-16 15:23:23.948  1740  4206 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-16 15:23:23.950  4072  4072 D SprintDMHelper: simOperator: 
08-16 15:23:23.950  4072  4072 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-16 15:23:23.950  1740  4206 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 15:23:23.950  1740  4206 I SystemUpdateService: now status is 0 (complete)
08-16 15:23:23.950  1740  4206 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 15:23:23.950  1740  4206 I SystemUpdateService: file has been verified
08-16 15:23:23.950  1740  4206 I SystemUpdateService: OTA package size = 12249756
08-16 15:23:23.957  1740  2423 I iu.SyncManager: NEXT; no task
,08-16 15:23:23.967  4028  4210 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 15:23:23.973  1740  4206 I SystemUpdateService: showing system update notification
,08-16 15:23:23.988  1740  1740 D SystemUpdateService: onDestroy
,08-16 15:23:28.718   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e9808fb:true
,08-16 15:23:28.720  4058  4058 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 15:23:28.725  4058  4058 I bt_bluedroid: init
,08-16 15:23:28.726  4058  4215 I BluetoothAdapterState: Entering OffState
,08-16 15:23:28.731  4058  4216 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 15:23:28.731  4058  4216 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 15:23:28.732  4058  4216 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 15:23:28.732  4058  4216 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 15:23:28.734  4058  4058 I bt_bluedroid: get_profile_interface socket
,08-16 15:23:28.737  4058  4058 I bt_bluedroid: get_profile_interface sdp
,08-16 15:23:28.739  4058  4219 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 15:23:28.742  4058  4219 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 15:23:28.743  4058  4069 I bt_bluedroid: config_hci_snoop_log
08-16 15:23:28.745   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 15:23:28.753  4058  4215 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 15:23:28.754  4058  4215 D BluetoothAdapterProperties: Setting state to 14
08-16 15:23:28.755  4058  4215 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 15:23:28.760  4058  4215 D BluetoothBondStateMachine: make
,08-16 15:23:28.764  4058  4220 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 15:23:28.773  4058  4215 I BluetoothAdapterState: Entering PendingCommandState
,08-16 15:23:28.775  4058  4058 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 15:23:28.783  4058  4058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:28.785  4058  4058 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 15:23:28.787  4058  4058 D BtGatt.GattService: Received start request. Starting profile...
,08-16 15:23:28.787  4058  4058 D BtGatt.GattService: start()
08-16 15:23:28.788  4058  4058 I bt_bluedroid: get_profile_interface gatt
,08-16 15:23:28.790  4058  4058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
08-16 15:23:28.791  4058  4058 D BtGatt.AdvertiseManager: advertise manager created
,08-16 15:23:28.808  4058  4058 V BluetoothAdapterState: isTurningOff()=false
08-16 15:23:28.808  4058  4058 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:28.808  4058  4058 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 15:23:28.809  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 15:23:28.810  4058  4215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 15:23:28.810  4058  4215 I bt_bluedroid: enable
08-16 15:23:28.811  4058  4216 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 15:23:28.812  4058  4216 I bt_hci  : start_up
,08-16 15:23:28.835  4058  4216 I bt_vendor: alloc value 0xb3969189
08-16 15:23:28.835  4058  4216 I bt_vendor: init
08-16 15:23:28.835  4058  4216 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 15:23:28.835  4058  4216 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 15:23:28.942  4058  4216 D bt_hci  : start_up starting async portion
,08-16 15:23:28.942  4058  4223 I bt_hci  : event_finish_startup
08-16 15:23:28.943  4058  4223 I bt_hci_h4: hal_open
,08-16 15:23:28.943  4058  4223 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 15:23:28.953  4058  4223 I bt_userial_vendor: device fd = 51 open
,08-16 15:23:28.983  4058  4223 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 15:23:29.015  4058  4223 D bt_hwcfg: Chipset BCM4354A2
,08-16 15:23:29.015  4058  4223 D bt_hwcfg: Target name = [BCM4354A2]
08-16 15:23:29.016  4058  4223 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 15:23:29.205   871  1315 D ConnectivityService: handlePromptUnvalidated 101
,08-16 15:23:29.911  4058  4223 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-16 15:23:29.911  4058  4223 D bt_hwcfg: Settlement delay -- 100 ms
08-16 15:23:29.912  4058  4223 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 15:23:30.027  4058  4223 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-16 15:23:30.027  4058  4223 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 15:23:30.059  4058  4223 I bt_hwcfg: vendor lib fwcfg completed
,08-16 15:23:30.059  4058  4223 I bt_vendor: firmware callback
08-16 15:23:30.060  4058  4223 I bt_hci  : firmware_config_callback
,08-16 15:23:30.063  4058  4227 I bt_btu  : btu_task pending for preload complete event
,08-16 15:23:30.063  4058  4227 I bt_btu_task: Bluetooth chip preload is complete
08-16 15:23:30.063  4058  4227 I bt_btu  : btu_task received preload complete event
,08-16 15:23:30.070  4058  4227 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 15:23:30.071  4058  4227 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-16 15:23:30.071  4058  4227 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 15:23:30.071  4058  4227 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 15:23:30.071  4058  4227 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 15:23:30.072  4058  4227 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 15:23:30.072  4058  4227 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 15:23:30.072  4058  4227 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 15:23:30.072  4058  4227 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 15:23:30.072  4058  4227 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 15:23:30.073  4058  4227 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 15:23:30.073  4058  4227 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 15:23:30.073  4058  4227 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 15:23:30.073  4058  4227 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 15:23:30.074  4058  4227 I         : BTE_InitTraceLevels -- TRC_BTIF
08-16 15:23:30.077  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:30.086  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:30.089  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:30.125  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 15:23:30.126  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 15:23:30.126  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:23:30.126  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:30.150  3510  3510 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 15:23:30.151  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 15:23:30.151  3510  3510 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-16 15:23:30.203  4058  4227 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38e6d9d
,08-16 15:23:30.203  4058  4227 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38e6d9d 
,08-16 15:23:30.224  4058  4219 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 15:23:30.225  4058  4219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 15:23:30.225  4058  4219 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 15:23:30.227  4058  4219 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 15:23:30.230  4058  4219 D BluetoothAdapterProperties: Scan Mode:20
,08-16 15:23:30.230  4058  4219 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 15:23:30.230  4058  4219 D bt_hci  : do_postload posting postload work item
,08-16 15:23:30.231  4058  4223 I bt_hci  : event_postload
08-16 15:23:30.231  4058  4223 I bt_vendor: sco_config_cb
,08-16 15:23:30.231  4058  4223 I bt_hci  : sco_config_callback postload finished.
,08-16 15:23:30.234  4058  4219 D bt_bte_conf: Device ID record 1 : primary
,08-16 15:23:30.234  4058  4219 D bt_bte_conf:   vendorId            = 000f
,08-16 15:23:30.235  4058  4219 D bt_bte_conf:   vendorIdSource      = 0001
08-16 15:23:30.235  4058  4219 D bt_bte_conf:   product             = 1200
,08-16 15:23:30.235  4058  4219 D bt_bte_conf:   version             = 1436
08-16 15:23:30.235  4058  4219 D bt_bte_conf:   clientExecutableURL = 
,08-16 15:23:30.235  4058  4219 D bt_bte_conf:   serviceDescription  = 
,08-16 15:23:30.235  4058  4219 D bt_bte_conf:   documentationURL    = 
08-16 15:23:30.235  4058  4219 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 15:23:30.235  4058  4216 D bt_stack_manager: event_start_up_stack finished
08-16 15:23:30.235  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 15:23:30.236  4058  4215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 15:23:30.236  4058  4215 D BluetoothAdapterProperties: Setting state to 15
08-16 15:23:30.237  4058  4215 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 15:23:30.238  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:30.238  4058  4215 I BluetoothAdapterState: Entering BleOnState
08-16 15:23:30.241  4058  4223 I bt_vendor: low_power_mode_cb
08-16 15:23:30.241  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:30.247  4058  4215 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 15:23:30.247  4058  4215 D BluetoothAdapterProperties: Setting state to 11
,08-16 15:23:30.247  4058  4215 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 15:23:30.254  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:30.255  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:30.257  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:30.258  4058  4058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
08-16 15:23:30.259  4058  4058 D HeadsetService: Received start request. Starting profile...
08-16 15:23:30.262  4058  4058 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 15:23:30.262  4058  4058 D HeadsetStateMachine: make
,08-16 15:23:30.270  4058  4215 I BluetoothAdapterState: Entering PendingCommandState
,08-16 15:23:30.272  4058  4058 D HeadsetStateMachine: max_hf_connections = 1
,08-16 15:23:30.272  4058  4058 I bt_bluedroid: get_profile_interface handsfree
08-16 15:23:30.275  4058  4219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 15:23:30.275  4058  4219 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-16 15:23:30.276  4058  4058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:30.277  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 15:23:30.277  4058  4058 D A2dpService: Received start request. Starting profile...
,08-16 15:23:30.278  4058  4058 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 15:23:30.278  4058  4058 I bt_bluedroid: get_profile_interface avrcp
,08-16 15:23:30.284  4058  4058 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 15:23:30.285  4058  4058 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 15:23:30.285  4058  4058 D A2dpStateMachine: make
,08-16 15:23:30.286  4058  4058 I bt_bluedroid: get_profile_interface a2dp
,08-16 15:23:30.287  4058  4219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 15:23:30.288  4058  4237 D A2dpStateMachine: Enter Disconnected: -2
08-16 15:23:30.289  4058  4058 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 15:23:30.289  4058  4058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:30.291  4058  4058 D HidService: Received start request. Starting profile...
08-16 15:23:30.291  4058  4058 I bt_bluedroid: get_profile_interface hidhost
,08-16 15:23:30.291  4058  4058 D HidService: setHidService(): set to: null
08-16 15:23:30.291  4058  4219 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38c83e5
08-16 15:23:30.291  4058  4219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 15:23:30.291  4058  4058 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 15:23:30.292  4058  4058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:30.292  3979  3979 D BluetoothInputDevice: Proxy object connected
08-16 15:23:30.293  4058  4058 D HealthService: Received start request. Starting profile...
08-16 15:23:30.293  3979  3979 D HidProfile: Bluetooth service connected
,08-16 15:23:30.294  4058  4058 I bt_bluedroid: get_profile_interface health
,08-16 15:23:30.295  4058  4058 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 15:23:30.296  4058  4058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:30.297  3979  3979 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 15:23:30.297  4058  4058 D PanService: Received start request. Starting profile...
08-16 15:23:30.297  4058  4058 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 15:23:30.297  4058  4058 I bt_bluedroid: get_profile_interface pan
08-16 15:23:30.297  3979  3979 D PanProfile: Bluetooth service connected
,08-16 15:23:30.299  4058  4219 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 15:23:30.303  4058  4058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:30.304  4058  4058 D BluetoothMapService: Received start request. Starting profile...
,08-16 15:23:30.304  3979  3979 D BluetoothMap: Proxy object connected
08-16 15:23:30.304  4058  4058 D BluetoothMapService: start()
,08-16 15:23:30.304  3979  3979 D MapProfile: Bluetooth service connected
,08-16 15:23:30.304  3979  3979 D BluetoothMap: getConnectedDevices()
08-16 15:23:30.305  3979  3979 D BluetoothMap: Bluetooth is Not enabled
08-16 15:23:30.306  4058  4058 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 15:23:30.307  4058  4058 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 15:23:30.307  4058  4058 D BluetoothMapAppObserver: createReceiver()
,08-16 15:23:30.308  4058  4058 D BluetoothMapAppObserver: initObservers()
08-16 15:23:30.308  4058  4058 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 15:23:30.315  4058  4235 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 15:23:30.315  4058  4058 V BluetoothAdapterState: isTurningOff()=false
08-16 15:23:30.315  4058  4058 V BluetoothAdapterState: isTurningOn()=true
08-16 15:23:30.315  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 15:23:30.315  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 15:23:30.317  4058  4058 V BluetoothAdapterState: isTurningOff()=false
,08-16 15:23:30.317  4058  4058 V BluetoothAdapterState: isTurningOn()=true
,08-16 15:23:30.317  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:30.317  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 15:23:30.317  4058  4058 V BluetoothAdapterState: isTurningOff()=false
08-16 15:23:30.317  4058  4058 V BluetoothAdapterState: isTurningOn()=true
08-16 15:23:30.317  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 15:23:30.317  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isTurningOff()=false
08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isTurningOn()=true
,08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isTurningOff()=false
,08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isTurningOn()=true
08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isTurningOff()=false
,08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isTurningOn()=true
,08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 15:23:30.318  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:30.319  4058  4215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 15:23:30.319  4058  4215 D BluetoothAdapterProperties: ScanMode =  20
,08-16 15:23:30.319  4058  4215 D BluetoothAdapterProperties: State =  11
08-16 15:23:30.319  4058  4215 D BluetoothAdapterProperties: Setting state to 12,
,08-16 15:23:30.319  4058  4215 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 15:23:30.320  1368  1385 D BluetoothPan: onBluetoothStateChange on: true
08-16 15:23:30.321  4058  4215 I BluetoothAdapterState: Entering OnState
,08-16 15:23:30.321  4058  4219 D BluetoothAdapterProperties: Scan Mode:21
08-16 15:23:30.321  4058  4219 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 15:23:30.324  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:30.324  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:30.324  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:30.324  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:30.324  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:30.324  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:30.324  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:30.324  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:30.325  1368  1368 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 15:23:30.325  1368  1368 D PanProfile: Bluetooth service connected
,08-16 15:23:30.325  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:30.325  3979  3989 D BluetoothMap: onBluetoothStateChange: up=true
08-16 15:23:30.326  3979  3990 D BluetoothPan: onBluetoothStateChange on: true
08-16 15:23:30.326  1368  1985 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 15:23:30.327  1368  1368 D BluetoothInputDevice: Proxy object connected
08-16 15:23:30.327  1368  1368 D HidProfile: Bluetooth service connected
08-16 15:23:30.328   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:23:30.328  1914  2172 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:23:30.328   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:23:30.328   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:23:30.328   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 15:23:30.329  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:30.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:30.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:30.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:30.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:30.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:30.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:30.329  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:30.329  3979  3989 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 15:23:30.329  1368  1393 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:23:30.330  3979  3990 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 15:23:30.330   871   871 D BluetoothA2dp: Proxy object connected
08-16 15:23:30.331  1368  1385 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 15:23:30.331  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:30.332  1368  2018 D BluetoothMap: onBluetoothStateChange: up=true
08-16 15:23:30.333  1368  1368 D BluetoothMap: Proxy object connected
08-16 15:23:30.333  1368  1368 D MapProfile: Bluetooth service connected
,08-16 15:23:30.333  1368  1368 D BluetoothMap: getConnectedDevices()
08-16 15:23:30.334  4058  4058 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 15:23:30.334  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:30.334  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:30.334  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:30.334  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:30.334  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:30.334  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:30.334  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:30.334  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:30.334  4058  4058 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 15:23:30.335  1368  1393 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 15:23:30.336  4058  4058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:23:30.336  1368  1368 D BluetoothA2dp: Proxy object connected
08-16 15:23:30.337  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:30.339  4058  4058 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 15:23:30.340   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 15:23:30.343  4058  4058 D ObexServerSockets: Succeed to create listening sockets 
08-16 15:23:30.343  4058  4058 D ObexServerSockets0: startAccept()
08-16 15:23:30.343  4058  4058 D ObexServerSockets0: prepareForNewConnect()
,08-16 15:23:30.346  4058  4058 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 15:23:30.347  4058  4058 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 15:23:30.349  4058  4245 D ObexServerSockets0: Accepting socket connection...
08-16 15:23:30.350  4058  4246 D ObexServerSockets0: Accepting socket connection...
08-16 15:23:30.350  4058  4058 D BluetoothMapService: onReceive
,08-16 15:23:30.351  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:30.351  4058  4058 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:23:30.351  4058  4058 D BluetoothMapService: STATE_ON
08-16 15:23:30.352  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:30.352  3979  3979 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-16 15:23:30.353  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:30.356  3979  3979 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 15:23:30.362  3979  3979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 15:23:30.365  3979  3979 D BluetoothA2dp: Proxy object connected
,08-16 15:23:30.369  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 15:23:30.374  3979  3979 D DockEventReceiver: finishStartingService: stopping service
,08-16 15:23:30.380  3979  3979 D BluetoothPbap: Proxy object connected
08-16 15:23:30.380  1368  1368 D BluetoothPbap: Proxy object connected
08-16 15:23:30.380  1368  1368 D PbapServerProfile: Bluetooth service connected
,08-16 15:23:30.380  3979  3979 D PbapServerProfile: Bluetooth service connected
08-16 15:23:30.380  4058  4058 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 15:23:30.380  4058  4058 D ObexServerSockets0: prepareForNewConnect()
,08-16 15:23:30.389  4058  4251 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 15:23:30.411  4058  4255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 15:23:30.413  4058  4255 I BtOppRfcommListener: Accept thread started.
,08-16 15:23:30.429   871   871 D BluetoothHeadset: Proxy object connected
,08-16 15:23:30.429  1914  1932 D BluetoothHeadset: Proxy object connected
,08-16 15:23:30.430   871   871 D BluetoothHeadset: Proxy object connected
,08-16 15:23:30.430  1914  1929 D BluetoothHeadset: Proxy object connected
08-16 15:23:30.430   871   888 D BluetoothHeadset: Proxy object connected
,08-16 15:23:30.430  1368  1393 D BluetoothHeadset: Proxy object connected
,08-16 15:23:30.430   871   888 D BluetoothHeadset: Proxy object connected
08-16 15:23:30.430  1368  1368 D HeadsetProfile: Bluetooth service connected
08-16 15:23:30.430   871   871 D BluetoothHeadset: Proxy object connected
,08-16 15:23:30.430  1368  1985 D BluetoothHeadset: Proxy object connected
,08-16 15:23:30.434  1368  1368 D HeadsetProfile: Bluetooth service connected
,08-16 15:23:30.459  3979  3989 D BluetoothHeadset: Proxy object connected
,08-16 15:23:30.460  3979  3979 D HeadsetProfile: Bluetooth service connected
,08-16 15:23:33.696  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 15:23:33.697  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:23:33.698  4058  4215 D BluetoothAdapterState: Current state: ON, message: 23
08-16 15:23:33.698  4058  4215 D BluetoothAdapterProperties: Setting state to 13
08-16 15:23:33.698  4058  4215 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 15:23:33.700  4058  4215 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 15:23:33.703  4058  4215 I BluetoothAdapterState: Entering PendingCommandState
,08-16 15:23:33.705  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:33.706  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c93284 removed from the list
,08-16 15:23:33.706  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:33.706  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:33.707  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:33.710  4058  4058 D BluetoothMapService: onReceive
08-16 15:23:33.710  4058  4058 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:23:33.711  4058  4058 D BluetoothMapService: STATE_TURNING_OFF
08-16 15:23:33.711  4058  4058 D BluetoothMapService: MAP Service closeService in
08-16 15:23:33.711  4058  4058 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 15:23:33.712  4058  4058 D ObexServerSockets0: shutdown(block = true)
08-16 15:23:33.712  4058  4245 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 15:23:33.714  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:23:33.715  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4d36a2 added. We now have 4 listener(s)
08-16 15:23:33.715  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:23:33.715  4058  4058 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 15:23:33.716  4058  4231 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 15:23:33.716  4058  4246 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 15:23:33.716  4058  4058 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 15:23:33.717  4058  4058 I BtOppRfcommListener: stopping Accept Thread
08-16 15:23:33.718  4058  4255 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:23:33.719  4058  4255 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 15:23:33.726  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:33.726  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f4d36a2 removed from the list
08-16 15:23:33.726  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:33.726  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:33.726  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:33.727  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:33.727  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:33.727  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:33.727  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:33.727  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:33.727  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:33.727  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:33.727  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:33.727  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:33.727  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:23:33.727  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd1cf33 added. We now have 4 listener(s)
08-16 15:23:33.728  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:33.727  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:23:33.728  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:23:33.729  3979  3979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 15:23:33.730  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:33.730  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:33.730  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:33.730  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:33.730  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:33.730  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:23:33.730  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:33.730  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:33.730  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:33.731  4058  4219 D BluetoothAdapterProperties: Scan Mode:20
08-16 15:23:33.731  4058  4215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-16 15:23:33.732  3868  3868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:23:33.732  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:33.734  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:33.736  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:33.738  4058  4058 D HeadsetService: Received stop request...Stopping profile...
,08-16 15:23:33.744   871   871 D BluetoothHeadset: Proxy object disconnected
,08-16 15:23:33.747  1914  2157 D BluetoothHeadset: Proxy object disconnected
08-16 15:23:33.747  4058  4058 D A2dpService: Received stop request...Stopping profile...
08-16 15:23:33.747   871   871 D BluetoothHeadset: Proxy object disconnected
08-16 15:23:33.748  3979  3989 D BluetoothHeadset: Proxy object disconnected
08-16 15:23:33.748  4058  4237 D A2dpStateMachine: Exit Disconnected: -1
08-16 15:23:33.749  1368  1985 D BluetoothHeadset: Proxy object disconnected
08-16 15:23:33.749  3979  3979 D DockEventReceiver: finishStartingService: stopping service
08-16 15:23:33.749  1368  1368 D HeadsetProfile: Bluetooth service disconnected
08-16 15:23:33.749   871   871 D BluetoothHeadset: Proxy object disconnected
08-16 15:23:33.749   871   871 D BluetoothA2dp: Proxy object disconnected
08-16 15:23:33.750  1368  1368 D BluetoothA2dp: Proxy object disconnected
08-16 15:23:33.750  4058  4058 V BluetoothAdapterState: isTurningOff()=true
08-16 15:23:33.750  4058  4058 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:33.750  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:33.751  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:33.752  4058  4215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 23
,08-16 15:23:33.752  3979  3979 D HeadsetProfile: Bluetooth service disconnected
,08-16 15:23:33.754  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 15:23:33.755  3979  3979 D BluetoothA2dp: Proxy object disconnected
,08-16 15:23:33.758  4058  4058 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 15:23:33.758  4058  4219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-16 15:23:33.759  4058  4227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 15:23:33.759  4058  4227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 15:23:33.759  4058  4227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 15:23:33.758  4058  4058 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 15:23:33.759  4058  4219 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-16 15:23:33.760  4058  4058 D HidService: Received stop request...Stopping profile...
08-16 15:23:33.760  4058  4058 D HidService: Stopping Bluetooth HidService
08-16 15:23:33.760  1368  1368 D BluetoothInputDevice: Proxy object disconnected
,08-16 15:23:33.761  1368  1368 D HidProfile: Bluetooth service disconnected
08-16 15:23:33.761  3979  3979 D BluetoothInputDevice: Proxy object disconnected
08-16 15:23:33.761  3979  3979 D HidProfile: Bluetooth service disconnected
,08-16 15:23:33.761  4058  4058 V BluetoothAdapterState: isTurningOff()=true
08-16 15:23:33.761  4058  4058 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:33.761  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:33.761  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:33.762  4058  4058 D HealthService: Received stop request...Stopping profile...
,08-16 15:23:33.764  4058  4219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-16 15:23:33.764  4058  4227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 15:23:33.764  4058  4227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 15:23:33.764  4058  4227 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:23:33.765  4058  4227 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:23:33.765  4058  4227 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 15:23:33.765  4058  4227 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:23:33.765  4058  4058 D PanService: Received stop request...Stopping profile...
08-16 15:23:33.766  1368  1368 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 15:23:33.767  1368  1368 D PanProfile: Bluetooth service disconnected
,08-16 15:23:33.767  3979  3979 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 15:23:33.767  3979  3979 D PanProfile: Bluetooth service disconnected
08-16 15:23:33.768  4058  4058 D BluetoothMapService: Received stop request...Stopping profile...
08-16 15:23:33.768  4058  4058 D BluetoothMapService: stop()
,08-16 15:23:33.768  4058  4058 D BluetoothMapAppObserver: deinitObservers()
,08-16 15:23:33.768  4058  4058 D BluetoothMapAppObserver: removeReceiver()
,08-16 15:23:33.769  1368  1368 D BluetoothMap: Proxy object disconnected
08-16 15:23:33.769  1368  1368 D MapProfile: Bluetooth service disconnected
08-16 15:23:33.770  3979  3979 D BluetoothMap: Proxy object disconnected
08-16 15:23:33.770  3979  3979 D MapProfile: Bluetooth service disconnected
,08-16 15:23:33.771  1368  1368 D BluetoothPbap: Proxy object disconnected
08-16 15:23:33.771  1368  1368 D PbapServerProfile: Bluetooth service disconnected
08-16 15:23:33.771  3979  3979 D BluetoothPbap: Proxy object disconnected
08-16 15:23:33.771  3979  3979 D PbapServerProfile: Bluetooth service disconnected
08-16 15:23:33.773  4058  4058 V BluetoothAdapterState: isTurningOff()=true
,08-16 15:23:33.773  4058  4058 V BluetoothAdapterState: isTurningOn()=false
,08-16 15:23:33.773  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:33.773  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:33.774  4058  4058 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 15:23:33.774  4058  4219 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 15:23:33.774  4058  4058 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 15:23:33.774  4058  4058 V BluetoothAdapterState: isTurningOff()=true
08-16 15:23:33.774  4058  4058 V BluetoothAdapterState: isTurningOn()=false
,08-16 15:23:33.774  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 15:23:33.781  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:33.781  4058  4058 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 15:23:33.781  4058  4219 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 15:23:33.782  4058  4058 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 15:23:33.782  4058  4058 V BluetoothAdapterState: isTurningOff()=true
,08-16 15:23:33.782  4058  4058 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:33.782  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:33.782  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 15:23:33.783  4058  4058 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 15:23:33.783  4058  4058 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 15:23:33.784  4058  4058 D BluetoothMapService: MAP Service closeService in
,08-16 15:23:33.784  4058  4058 V BluetoothAdapterState: isTurningOff()=true
08-16 15:23:33.784  4058  4058 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:33.784  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:33.784  4058  4058 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:33.785  4058  4215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 15:23:33.785  4058  4215 D BluetoothAdapterProperties: Setting state to 15
08-16 15:23:33.785  4058  4215 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-16 15:23:33.786  4058  4215 I BluetoothAdapterState: Entering BleOnState
,08-16 15:23:33.786  4058  4058 D BluetoothMapService: cleanup()
,08-16 15:23:33.786  1368  1393 D BluetoothPan: onBluetoothStateChange on: false
08-16 15:23:33.786  4058  4058 D BluetoothMapService: MAP Service closeService in
08-16 15:23:33.787  3979  3990 D BluetoothMap: onBluetoothStateChange: up=false
08-16 15:23:33.787  3979  4260 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:23:33.788  3979  3989 D BluetoothPan: onBluetoothStateChange on: false
,08-16 15:23:33.788  1368  1985 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 15:23:33.789   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:23:33.789  1914  2156 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:23:33.790   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 15:23:33.790   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:23:33.790   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 15:23:33.790  3979  3990 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 15:23:33.790  1368  2018 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:23:33.791  3979  4260 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 15:23:33.791  1368  1385 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 15:23:33.792  1368  1393 D BluetoothMap: onBluetoothStateChange: up=false
08-16 15:23:33.793  3979  3989 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 15:23:33.793  1368  1985 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 15:23:33.794  4058  4215 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-16 15:23:33.794  4058  4215 D BluetoothAdapterProperties: Setting state to 16
,08-16 15:23:33.794  4058  4215 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 15:23:33.795  4058  4215 D BluetoothAdapterProperties: onBleDisable
08-16 15:23:33.795  4058  4216 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 15:23:33.796  4058  4215 I BluetoothAdapterState: Entering PendingCommandState
08-16 15:23:33.797  4058  4227 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 15:23:33.797  4058  4227 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 15:23:33.799  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:33.801  4058  4219 D BluetoothAdapterProperties: Scan Mode:20
08-16 15:23:33.801  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:33.803  3979  3979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 15:23:33.808  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:33.809  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:33.811  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 15:23:33.817  3979  3979 D DockEventReceiver: finishStartingService: stopping service
,08-16 15:23:34.004  4058  4219 I bt_hci  : shut_down
,08-16 15:23:34.004  4058  4223 D bt_hwcfg: hw_epilog_process
,08-16 15:23:34.006  4058  4223 I bt_vendor: low_power_mode_cb
,08-16 15:23:34.030  4058  4223 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-16 15:23:34.030  4058  4223 I bt_vendor: epilog_cb
08-16 15:23:34.030  4058  4223 I bt_hci  : epilog_finished_callback
,08-16 15:23:34.040  4058  4219 I bt_hci_h4: hal_close
,08-16 15:23:34.042  4058  4219 I bt_userial_vendor: device fd = 51 close
,08-16 15:23:34.167  4058  4216 D bt_stack_manager: event_shut_down_stack finished.
,08-16 15:23:34.168  4058  4215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 15:23:34.174  4058  4215 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-16 15:23:34.174  4058  4058 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 15:23:34.176  4058  4058 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 15:23:34.176  4058  4058 D BtGatt.GattService: stop()
,08-16 15:23:34.176  4058  4058 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 15:23:34.182  4058  4058 V BluetoothAdapterState: isTurningOff()=false
08-16 15:23:34.182  4058  4058 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:34.182  4058  4058 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:34.183  4058  4058 V BluetoothAdapterState: isBleTurningOff()=true
08-16 15:23:34.183  4058  4215 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-16 15:23:34.184  4058  4215 D BluetoothAdapterProperties: Setting state to 10
,08-16 15:23:34.184  4058  4215 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 15:23:34.185  4058  4215 I BluetoothAdapterState: Entering OffState
,08-16 15:23:34.189   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 15:23:34.215  4058  4058 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 15:23:34.215  4058  4058 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 15:23:34.216  4058  4216 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-16 15:23:34.218  4058  4058 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 15:23:34.228  4058  4216 D bt_stack_manager: event_clean_up_stack finished.
,08-16 15:23:34.234  4058  4058 I art     : System.exit called, status: 0
,08-16 15:23:34.235  4058  4058 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 15:23:34.301   871  1936 I ActivityManager: Process com.android.bluetooth (pid 4058) has died
,08-16 15:23:38.741  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:38.788   871   888 I ActivityManager: Start proc 4266:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 15:23:38.907  4266  4266 D AdapterServiceConfig: Adding HeadsetService
,08-16 15:23:38.908  4266  4266 D AdapterServiceConfig: Adding A2dpService
,08-16 15:23:38.908  4266  4266 D AdapterServiceConfig: Adding HidService
,08-16 15:23:38.908  4266  4266 D AdapterServiceConfig: Adding HealthService
,08-16 15:23:38.908  4266  4266 D AdapterServiceConfig: Adding PanService
,08-16 15:23:38.908  4266  4266 D AdapterServiceConfig: Adding GattService
,08-16 15:23:38.909  4266  4266 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 15:23:38.921  4266  4266 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 15:23:38.921   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4bfc3ee:true
,08-16 15:23:38.926  4266  4266 I bt_bluedroid: init
,08-16 15:23:38.927  4266  4278 I BluetoothAdapterState: Entering OffState
,08-16 15:23:38.931  4266  4279 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 15:23:38.932  4266  4279 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 15:23:38.932  4266  4279 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 15:23:38.932  4266  4279 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 15:23:38.934  4266  4266 I bt_bluedroid: get_profile_interface socket
,08-16 15:23:38.936  4266  4266 I bt_bluedroid: get_profile_interface sdp
,08-16 15:23:38.938  4266  4282 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 15:23:38.940  4266  4282 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 15:23:38.943  4266  4277 I bt_bluedroid: config_hci_snoop_log
,08-16 15:23:38.947   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 15:23:38.955  4266  4278 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 15:23:38.956  4266  4278 D BluetoothAdapterProperties: Setting state to 14
,08-16 15:23:38.956  4266  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 15:23:38.960  4266  4278 D BluetoothBondStateMachine: make
,08-16 15:23:38.965  4266  4283 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 15:23:38.973  4266  4278 I BluetoothAdapterState: Entering PendingCommandState
,08-16 15:23:38.976  4266  4266 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 15:23:38.985  4266  4266 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:38.987  4266  4266 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 15:23:38.988  4266  4266 D BtGatt.GattService: Received start request. Starting profile...
,08-16 15:23:38.989  4266  4266 D BtGatt.GattService: start()
,08-16 15:23:38.989  4266  4266 I bt_bluedroid: get_profile_interface gatt
,08-16 15:23:38.991  4266  4266 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:38.992  4266  4266 D BtGatt.AdvertiseManager: advertise manager created
,08-16 15:23:39.003  4266  4266 V BluetoothAdapterState: isTurningOff()=false
08-16 15:23:39.003  4266  4266 V BluetoothAdapterState: isTurningOn()=false
08-16 15:23:39.003  4266  4266 V BluetoothAdapterState: isBleTurningOn()=true
08-16 15:23:39.004  4266  4266 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:39.004  4266  4278 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 15:23:39.005  4266  4278 I bt_bluedroid: enable
08-16 15:23:39.005  4266  4279 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 15:23:39.006  4266  4279 I bt_hci  : start_up
,08-16 15:23:39.025  4266  4279 I bt_vendor: alloc value 0xb39c2189
08-16 15:23:39.026  4266  4279 I bt_vendor: init
08-16 15:23:39.026  4266  4279 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 15:23:39.026  4266  4279 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 15:23:39.135  4266  4279 D bt_hci  : start_up starting async portion
,08-16 15:23:39.135  4266  4286 I bt_hci  : event_finish_startup
,08-16 15:23:39.136  4266  4286 I bt_hci_h4: hal_open
,08-16 15:23:39.138  4266  4286 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 15:23:39.150  4266  4286 I bt_userial_vendor: device fd = 51 open
,08-16 15:23:39.177  4266  4286 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 15:23:39.208  4266  4286 D bt_hwcfg: Chipset BCM4354A2
08-16 15:23:39.209  4266  4286 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 15:23:39.210  4266  4286 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 15:23:39.868  4266  4286 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 15:23:39.869  4266  4286 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 15:23:39.870  4266  4286 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 15:23:39.987  4266  4286 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 15:23:39.988  4266  4286 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 15:23:40.017  4266  4286 I bt_hwcfg: vendor lib fwcfg completed
,08-16 15:23:40.017  4266  4286 I bt_vendor: firmware callback
08-16 15:23:40.017  4266  4286 I bt_hci  : firmware_config_callback
,08-16 15:23:40.030  4266  4288 I bt_btu  : btu_task pending for preload complete event
,08-16 15:23:40.030  4266  4288 I bt_btu_task: Bluetooth chip preload is complete
08-16 15:23:40.031  4266  4288 I bt_btu  : btu_task received preload complete event
,08-16 15:23:40.043  4266  4288 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 15:23:40.043  4266  4288 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 15:23:40.044  4266  4288 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-16 15:23:40.044  4266  4288 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 15:23:40.044  4266  4288 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 15:23:40.044  4266  4288 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 15:23:40.045  4266  4288 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-16 15:23:40.045  4266  4288 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 15:23:40.045  4266  4288 I         : BTE_InitTraceLevels -- TRC_GAP
,08-16 15:23:40.045  4266  4288 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 15:23:40.046  4266  4288 I         : BTE_InitTraceLevels -- TRC_SDP
,08-16 15:23:40.046  4266  4288 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 15:23:40.046  4266  4288 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 15:23:40.046  4266  4288 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 15:23:40.047  4266  4288 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 15:23:40.179  4266  4288 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393fd9d
,08-16 15:23:40.179  4266  4288 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393fd9d 
,08-16 15:23:40.203  4266  4282 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-16 15:23:40.204  4266  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 15:23:40.205  4266  4282 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 15:23:40.209  4266  4282 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 15:23:40.213  4266  4282 D BluetoothAdapterProperties: Scan Mode:20
08-16 15:23:40.214  4266  4282 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 15:23:40.214  4266  4282 D bt_hci  : do_postload posting postload work item
08-16 15:23:40.215  4266  4286 I bt_hci  : event_postload
,08-16 15:23:40.215  4266  4286 I bt_vendor: sco_config_cb
,08-16 15:23:40.215  4266  4286 I bt_hci  : sco_config_callback postload finished.
08-16 15:23:40.218  4266  4282 D bt_bte_conf: Device ID record 1 : primary
,08-16 15:23:40.218  4266  4282 D bt_bte_conf:   vendorId            = 000f
08-16 15:23:40.218  4266  4282 D bt_bte_conf:   vendorIdSource      = 0001
08-16 15:23:40.219  4266  4282 D bt_bte_conf:   product             = 1200
08-16 15:23:40.219  4266  4282 D bt_bte_conf:   version             = 1436
08-16 15:23:40.219  4266  4282 D bt_bte_conf:   clientExecutableURL = 
,08-16 15:23:40.220  4266  4282 D bt_bte_conf:   serviceDescription  = 
08-16 15:23:40.220  4266  4282 D bt_bte_conf:   documentationURL    = 
08-16 15:23:40.220  4266  4282 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 15:23:40.220  4266  4279 D bt_stack_manager: event_start_up_stack finished
08-16 15:23:40.220  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:40.221  4266  4278 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 15:23:40.221  4266  4278 D BluetoothAdapterProperties: Setting state to 15
,08-16 15:23:40.221  4266  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 15:23:40.221  4266  4278 I BluetoothAdapterState: Entering BleOnState
,08-16 15:23:40.226  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:40.228  4266  4278 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 15:23:40.228  4266  4278 D BluetoothAdapterProperties: Setting state to 11
08-16 15:23:40.228  4266  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-16 15:23:40.230  4266  4286 I bt_vendor: low_power_mode_cb
,08-16 15:23:40.233  4266  4266 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:40.234  4266  4266 D HeadsetService: Received start request. Starting profile...
08-16 15:23:40.237  4266  4266 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 15:23:40.238  4266  4266 D HeadsetStateMachine: make
,08-16 15:23:40.249  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:40.251  4266  4278 I BluetoothAdapterState: Entering PendingCommandState
,08-16 15:23:40.253  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:23:40.256  4266  4266 D HeadsetStateMachine: max_hf_connections = 1
08-16 15:23:40.256  4266  4266 I bt_bluedroid: get_profile_interface handsfree
,08-16 15:23:40.257  4266  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 15:23:40.257  4266  4282 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 15:23:40.259  4266  4266 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:40.260  4266  4266 D A2dpService: Received start request. Starting profile...
,08-16 15:23:40.260  4266  4266 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 15:23:40.261  4266  4266 I bt_bluedroid: get_profile_interface avrcp
,08-16 15:23:40.266  4266  4266 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 15:23:40.266  4266  4266 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 15:23:40.266  4266  4266 D A2dpStateMachine: make
,08-16 15:23:40.267  4266  4266 I bt_bluedroid: get_profile_interface a2dp
,08-16 15:23:40.268  4266  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 15:23:40.269  4266  4298 D A2dpStateMachine: Enter Disconnected: -2
,08-16 15:23:40.269  4266  4266 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 15:23:40.270  4266  4266 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:40.271  4266  4266 D HidService: Received start request. Starting profile...
,08-16 15:23:40.271  4266  4266 I bt_bluedroid: get_profile_interface hidhost
08-16 15:23:40.271  4266  4282 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39213e5
08-16 15:23:40.271  4266  4266 D HidService: setHidService(): set to: null
,08-16 15:23:40.271  4266  4282 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 15:23:40.271  4266  4266 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 15:23:40.272  4266  4266 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:40.273  4266  4266 D HealthService: Received start request. Starting profile...
,08-16 15:23:40.274  4266  4266 I bt_bluedroid: get_profile_interface health
,08-16 15:23:40.275  4266  4266 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 15:23:40.275  4266  4266 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:40.276  4266  4266 D PanService: Received start request. Starting profile...
08-16 15:23:40.276  4266  4266 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 15:23:40.276  4266  4266 I bt_bluedroid: get_profile_interface pan
,08-16 15:23:40.277  4266  4282 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 15:23:40.278  4266  4266 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:23:40.279  4266  4266 D BluetoothMapService: Received start request. Starting profile...
08-16 15:23:40.279  4266  4266 D BluetoothMapService: start()
,08-16 15:23:40.281  4266  4266 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 15:23:40.282  4266  4266 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 15:23:40.282  4266  4266 D BluetoothMapAppObserver: createReceiver()
,08-16 15:23:40.283  4266  4266 D BluetoothMapAppObserver: initObservers()
08-16 15:23:40.283  4266  4266 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 15:23:40.290  4266  4266 V BluetoothAdapterState: isTurningOff()=false
,08-16 15:23:40.290  4266  4266 V BluetoothAdapterState: isTurningOn()=true
08-16 15:23:40.290  4266  4266 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:40.290  4266  4266 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:40.291  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 15:23:40.292  4266  4266 V BluetoothAdapterState: isTurningOff()=false
,08-16 15:23:40.292  4266  4266 V BluetoothAdapterState: isTurningOn()=true
08-16 15:23:40.292  4266  4266 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:40.292  4266  4266 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:40.292  4266  4295 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 15:23:40.293  4266  4266 V BluetoothAdapterState: isTurningOff()=false
,08-16 15:23:40.293  4266  4266 V BluetoothAdapterState: isTurningOn()=true
08-16 15:23:40.293  4266  4266 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:40.293  4266  4266 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:40.293  4266  4266 V BluetoothAdapterState: isTurningOff()=false
08-16 15:23:40.293  4266  4266 V BluetoothAdapterState: isTurningOn()=true
08-16 15:23:40.293  4266  4266 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:40.293  4266  4266 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 15:23:40.293  4266  4266 V BluetoothAdapterState: isTurningOff()=false
08-16 15:23:40.294  4266  4266 V BluetoothAdapterState: isTurningOn()=true
08-16 15:23:40.294  4266  4266 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:40.294  4266  4266 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:40.294  4266  4266 V BluetoothAdapterState: isTurningOff()=false
08-16 15:23:40.294  4266  4266 V BluetoothAdapterState: isTurningOn()=true
08-16 15:23:40.294  4266  4266 V BluetoothAdapterState: isBleTurningOn()=false
08-16 15:23:40.294  4266  4266 V BluetoothAdapterState: isBleTurningOff()=false
08-16 15:23:40.294  4266  4278 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 15:23:40.294  4266  4278 D BluetoothAdapterProperties: ScanMode =  20
08-16 15:23:40.294  4266  4278 D BluetoothAdapterProperties: State =  11
,08-16 15:23:40.296  4266  4282 D BluetoothAdapterProperties: Scan Mode:21
08-16 15:23:40.296  4266  4282 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 15:23:40.297  4266  4278 D BluetoothAdapterProperties: Setting state to 12
08-16 15:23:40.297  4266  4278 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-16 15:23:40.297  4266  4278 I BluetoothAdapterState: Entering OnState
,08-16 15:23:40.298  1368  1393 D BluetoothPan: onBluetoothStateChange on: true
,08-16 15:23:40.299  3979  4260 D BluetoothMap: onBluetoothStateChange: up=true
08-16 15:23:40.300  1368  1368 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 15:23:40.300  1368  1368 D PanProfile: Bluetooth service connected
,08-16 15:23:40.301  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:40.301  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:40.301  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:40.301  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:40.301  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:40.301  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:40.301  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:40.301  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 15:23:40.303  3979  4260 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 15:23:40.304  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:40.304  3979  3990 D BluetoothPan: onBluetoothStateChange on: true
,08-16 15:23:40.306  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:40.306  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:40.306  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:40.306  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:40.306  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:40.306  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:40.306  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:40.306  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:23:40.307  1368  2018 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 15:23:40.307  3979  3979 D BluetoothMap: Proxy object connected
,08-16 15:23:40.307  3979  3979 D MapProfile: Bluetooth service connected
08-16 15:23:40.307  3979  3979 D BluetoothMap: getConnectedDevices()
08-16 15:23:40.308   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:23:40.308  1914  2156 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:23:40.308  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:40.308  1368  1368 D BluetoothInputDevice: Proxy object connected
,08-16 15:23:40.308  1368  1368 D HidProfile: Bluetooth service connected
08-16 15:23:40.309   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:23:40.309   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:23:40.309   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 15:23:40.309  4266  4266 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 15:23:40.309  4266  4266 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 15:23:40.309  3979  3989 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 15:23:40.310  3979  3979 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 15:23:40.310  3979  3979 D PanProfile: Bluetooth service connected
08-16 15:23:40.310  4266  4266 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:23:40.312  4266  4266 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 15:23:40.312  1368  1393 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:23:40.312  3979  3979 D BluetoothInputDevice: Proxy object connected
,08-16 15:23:40.313  3979  3979 D HidProfile: Bluetooth service connected
08-16 15:23:40.313  4266  4266 D ObexServerSockets: Succeed to create listening sockets 
08-16 15:23:40.313  4266  4266 D ObexServerSockets0: startAccept()
08-16 15:23:40.313  4266  4266 D ObexServerSockets0: prepareForNewConnect()
,08-16 15:23:40.313  3979  3990 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 15:23:40.314  4266  4266 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 15:23:40.315  4266  4266 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 15:23:40.315  4266  4303 D ObexServerSockets0: Accepting socket connection...
08-16 15:23:40.315  4266  4304 D ObexServerSockets0: Accepting socket connection...
08-16 15:23:40.315   871   871 D BluetoothA2dp: Proxy object connected
,08-16 15:23:40.317  1368  1985 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 15:23:40.318  1368  2018 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 15:23:40.320  1368  1368 D BluetoothMap: Proxy object connected
,08-16 15:23:40.320  1368  1368 D MapProfile: Bluetooth service connected
08-16 15:23:40.320  1368  1368 D BluetoothMap: getConnectedDevices()
08-16 15:23:40.320  3979  4260 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 15:23:40.322  3979  3979 D BluetoothA2dp: Proxy object connected
08-16 15:23:40.322  1368  1393 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 15:23:40.323  1368  1368 D BluetoothA2dp: Proxy object connected
,08-16 15:23:40.325  4266  4266 D BluetoothMapService: onReceive
,08-16 15:23:40.325  4266  4266 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:23:40.325  4266  4266 D BluetoothMapService: STATE_ON
08-16 15:23:40.326   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 15:23:40.327  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:40.328  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:40.330  3979  3979 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 15:23:40.337  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 15:23:40.338  3979  3979 D DockEventReceiver: finishStartingService: stopping service
,08-16 15:23:40.343  3979  3979 D BluetoothPbap: Proxy object connected
,08-16 15:23:40.344  3979  3979 D PbapServerProfile: Bluetooth service connected
,08-16 15:23:40.346  4266  4307 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 15:23:40.348  4266  4266 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 15:23:40.348  4266  4266 D ObexServerSockets0: prepareForNewConnect()
,08-16 15:23:40.350  1368  1368 D BluetoothPbap: Proxy object connected
08-16 15:23:40.350  1368  1368 D PbapServerProfile: Bluetooth service connected
,08-16 15:23:40.361  4266  4313 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 15:23:40.363  4266  4313 I BtOppRfcommListener: Accept thread started.
,08-16 15:23:40.405   871   871 D BluetoothHeadset: Proxy object connected
,08-16 15:23:40.405  1914  2172 D BluetoothHeadset: Proxy object connected
,08-16 15:23:40.405   871   871 D BluetoothHeadset: Proxy object connected
08-16 15:23:40.406  3979  3989 D BluetoothHeadset: Proxy object connected
,08-16 15:23:40.408   871   888 D BluetoothHeadset: Proxy object connected
08-16 15:23:40.408  1368  2018 D BluetoothHeadset: Proxy object connected
08-16 15:23:40.409  1914  1932 D BluetoothHeadset: Proxy object connected
08-16 15:23:40.409  3979  3979 D HeadsetProfile: Bluetooth service connected
08-16 15:23:40.409   871   871 D BluetoothHeadset: Proxy object connected
08-16 15:23:40.409  1368  1368 D HeadsetProfile: Bluetooth service connected
08-16 15:23:40.409   871   888 D BluetoothHeadset: Proxy object connected
08-16 15:23:40.409   871   888 D BluetoothHeadset: Proxy object connected
08-16 15:23:40.414  1368  1385 D BluetoothHeadset: Proxy object connected
,08-16 15:23:40.417  1368  1368 D HeadsetProfile: Bluetooth service connected
,08-16 15:23:43.761  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:43.761  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:43.761  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:43.761  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:23:43.761  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:43.761  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:43.761  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:43.761  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 15:23:43.768  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:23:43.769  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:23:43.770  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd1cf33 removed from the list
,08-16 15:23:43.770  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 15:23:43.770  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:43.771  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:43.775  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 15:23:43.775  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e8f2f0 added. We now have 4 listener(s)
08-16 15:23:43.776  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:23:43.780   871   882 D WifiService: setWifiEnabled: false pid=3868, uid=10000
,08-16 15:23:43.780   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 15:23:48.792  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:23:48.794   871  2163 D WifiService: setWifiEnabled: true pid=3868, uid=10000
,08-16 15:23:48.794   871  2163 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 15:23:48.814   871  1313 D WifiConfigStore: Loading config and enabling all networks 
,08-16 15:23:48.831  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:48.831  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:48.831  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:48.831  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:48.831  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:48.831  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:48.831  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:48.831  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 15:23:48.838  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:23:48.842   871  1313 D WifiConfigStore: loaded 0 passpoint configs
08-16 15:23:48.843   871  1313 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 15:23:48.844   871  1313 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 15:23:48.845   871  1313 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 15:23:48.845   871  1313 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 15:23:48.845   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-16 15:23:48.845   871  1313 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-16 15:23:48.849  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:48.849  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:48.849  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:48.849  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:48.849  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:48.849  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:23:48.849  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:23:48.849  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 15:23:48.852  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:23:48.859   370   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 15:23:48.859   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 15:23:48.860   370   869 D CommandListener: Setting iface cfg,
08-16 15:23:48.861   871  1312 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-16 15:23:48.861   871  1312 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 15:23:48.920   871  1313 E native  : do suspend true
08-16 15:23:48.920   871  1312 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 15:23:48.939   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 15:23:48.940   871  1312 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 15:23:50.322   871  1313 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 15:23:50.463   871  1313 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.31 rxSuccessRate=14.19 delta 1000 -> 994
,08-16 15:23:50.465   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-16 15:23:50.465   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 15:23:50.487   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 15:23:50.553   871  1313 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 15:23:50.556  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 15:23:50.985  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 15:23:51.032  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 15:23:51.033  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 15:23:51.044   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 15:23:51.061   871  1313 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 15:23:51.062   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 15:23:51.062   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 15:23:51.086   871  1313 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 15:23:51.115   370   869 D CommandListener: Setting iface cfg
,08-16 15:23:51.118   871  1313 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 15:23:51.136   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 15:23:51.158   871  4323 D DhcpClient: Receive thread started
,08-16 15:23:51.256   871  1313 E native  : do suspend false
,08-16 15:23:51.280   871  1878 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 15:23:51.294   871  4323 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172770, domain null,
08-16 15:23:51.295   871  1878 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172770 seconds
,08-16 15:23:51.300   871  1878 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1,
,08-16 15:23:51.315   871  4323 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800,
08-16 15:23:51.316   871  1878 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 15:23:51.323   370   869 D CommandListener: Setting iface cfg
,08-16 15:23:51.336   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-16 15:23:51.336   871  1878 D DhcpClient: Scheduling renewal in 86399s
,08-16 15:23:51.339   871  1313 E native  : do suspend true
,08-16 15:23:51.366   871  1313 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-16 15:23:51.370   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 15:23:51.371   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 15:23:51.375   871  1315 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 15:23:51.398   871  1313 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 15:23:51.442   871  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 15:23:51.442   871  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 15:23:51.447   871  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 15:23:51.448   871  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 15:23:51.449   871  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 15:23:51.456   871  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 15:23:51.463   871  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 15:23:51.463   871  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-16 15:23:51.463   871  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 15:23:51.463   871  1313 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 15:23:51.463   871  1315 D ConnectivityService:    accepting network in place of null
08-16 15:23:51.464   871  1313 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 15:23:51.465   871  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 15:23:51.476   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=206939, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 15:23:51.503   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 15:23:51.532   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 15:23:51.541   871  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 15:23:51.541   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:23:51.548   871  4321 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.142,2a00:1450:4001:80c::200e
,08-16 15:23:51.550   871  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 15:23:51.552   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-16 15:23:51.570  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:51.570  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:51.570  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:51.570  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:51.570  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:51.570  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:51.570  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:23:51.570  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:23:51.573  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:23:51.578  1740  1740 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 15:23:51.580  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:51.580  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:51.580  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:51.580  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:51.580  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:51.580  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:51.580  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:23:51.580  3868  3868 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:23:51.583  3868  3868 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:23:51.585  1740  1740 D SystemUpdateService: onCreate
,08-16 15:23:51.589  1740  1740 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 15:23:51.600  1740  4332 I SystemUpdateService: active receiver: enabled
,08-16 15:23:51.614  1740  1740 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 15:23:51.617  1740  2423 I iu.UploadsManager: num queued entries: 0
,08-16 15:23:51.621  1740  4332 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 15:23:51.623  1740  1740 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 15:23:51.625   871  4321 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 13:23:51 GMT], X-Android-Received-Millis=[1471353831624], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471353831595]}
,08-16 15:23:51.626   871  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 15:23:51.626   871  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 15:23:51.626   871  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 15:23:51.626  1740  1740 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 15:23:51.627   871  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 15:23:51.630  4072  4072 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:23:51.638  4072  4072 D SprintDMHelper: simOperator: 
,08-16 15:23:51.638  4072  4072 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 15:23:51.642  1740  4335 I MDM     : [183] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 15:23:51.643  1740  4335 W BaseAppContext: Using Auth Proxy for data requests.
08-16 15:23:51.643  1740  4335 V GoogleAuthProtoRequest: [183] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 15:23:51.648  1740  4332 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 15:23:51.648  1740  4332 I SystemUpdateService: now status is 0 (complete)
08-16 15:23:51.648  1740  4332 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 15:23:51.648  1740  4332 I SystemUpdateService: file has been verified
08-16 15:23:51.648  1740  4332 I SystemUpdateService: OTA package size = 12249756
08-16 15:23:51.650  1740  2423 I iu.UploadsManager: num updated entries: 0
08-16 15:23:51.650  1740  2423 I iu.SyncManager: NEXT; no task
,08-16 15:23:51.663  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:51.665  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:51.743  1740  4332 I SystemUpdateService: showing system update notification
,08-16 15:23:51.825  1520  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 15:23:51.825  1520  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 15:23:51.825  1520  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:23:51.825  1520  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:51.830  4028  4343 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 15:23:51.850  3548  4340 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 15:23:51.850  3548  4340 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at jdm.a(PG:82)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at blb.a(PG:3937)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at czp.a(PG:18188)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at czp.a(PG:9087)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:23:51.850  3548  4340 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	... 12 more
08-16 15:23:51.850  3548  4340 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at fal.a(PG:38)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:23:51.850  3548  4340 E HttpOperation: 	... 14 more
,08-16 15:23:51.870  1740  1740 D SystemUpdateService: onDestroy
,08-16 15:23:51.881  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 15:23:51.881  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 15:23:51.881  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:23:51.881  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:51.904  1740  4335 E MDM     : [183] SitrepService.a: Error sending sitrep.
,08-16 15:23:52.090  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-16 15:23:52.090  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 15:23:52.090  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:23:52.090  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:52.109  3548  4350 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 15:23:52.109  3548  4350 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at jdm.a(PG:82)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at blb.a(PG:3937)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at czp.a(PG:18188)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at czp.a(PG:9081)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:23:52.109  3548  4350 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	... 12 more
08-16 15:23:52.109  3548  4350 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at fal.a(PG:38)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:23:52.109  3548  4350 E HttpOperation: 	... 14 more
,08-16 15:23:52.148  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 15:23:52.148  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 15:23:52.148  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:23:52.148  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:52.164  3548  4350 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 15:23:52.164  3548  4350 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at jdm.a(PG:82)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at hec.a(PG:42)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at hee.a(PG:102)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at czr.a(PG:65)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at kka.a(PG:108)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at czp.a(PG:19176)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at czp.a(PG:9081)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:23:52.164  3548  4350 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	... 15 more
08-16 15:23:52.164  3548  4350 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at fal.a(PG:38)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:23:52.164  3548  4350 E HttpOperation: 	... 17 more
08-16 15:23:52.164  3548  4350 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 15:23:52.164  3548  4350 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at hec.a(PG:42)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at hee.a(PG:102)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at czr.a(PG:65)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at kka.a(PG:108)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	... 15 more
08-16 15:23:52.164  3548  4350 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at fal.a(PG:38)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 15:23:52.164  3548  4350 E ExperimentLoader: 	... 17 more
,08-16 15:23:52.396   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 160163, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:23:52.540   871  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 15:23:53.822  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:23:53.822  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:23:53.822  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:23:53.822  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:23:53.822  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:23:53.822  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:23:53.822  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:23:53.822  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:23:53.828  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:23:53.829  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:23:53.830  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e8f2f0 removed from the list
,08-16 15:23:53.830  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:23:53.830  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:23:53.830  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:23:53.842  3868  4352 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-16 15:23:53.842  3868  4352 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 15:23:54.651  1862  1975 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-16 15:23:54.651  1862  1975 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-16 15:23:54.685  1520  1520 I ConfigService: onCreate
,08-16 15:23:56.846  3868  4354 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-16 15:23:56.846  3868  4352 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-16 15:23:56.846  3868  4354 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 15:23:56.847  3868  4352 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 15:23:56.847  3868  4354 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 15:23:56.847  3868  4352 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:23:56.847  3868  4354 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:23:56.848  3868  4352 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 15:23:56.850  3868  4354 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 15:23:56.851  3868  4357 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: OutgoingSocketThread/Sender)
,08-16 15:23:56.852  3868  4352 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 15:23:56.852  3868  4356 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: IncomingSocketThread/Sender)
,08-16 15:23:56.855  3868  4358 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: IncomingSocketThread/Receiver)
,08-16 15:23:56.855  3868  4359 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: OutgoingSocketThread/Receiver)
08-16 15:23:56.856  3868  4359 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 440, thread name: OutgoingSocketThread/Receiver)
08-16 15:23:56.856  3868  4359 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,08-16 15:23:56.856  3868  4359 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 440, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 15:23:56.857  3868  4358 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: IncomingSocketThread/Receiver)
,08-16 15:23:56.857  3868  4358 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 15:23:56.857  3868  4358 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 15:23:59.471   871  1315 D ConnectivityService: handlePromptUnvalidated 102
,08-16 15:23:59.757  1520  1520 I ConfigService: onDestroy
,08-16 15:23:59.849  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 15:23:59.851  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 15:23:59.857  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f9ad6c2 Bundle[{}]
,08-16 15:23:59.857  3868  3918 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 15:23:59.857  3868  3918 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 15:23:59.858  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 15:23:59.858  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 15:23:59.859  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 15:23:59.859  3868  3918 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 15:23:59.864  3868  3918 I System.out: Running OutgoingSocketThread
,08-16 15:23:59.867  3868  4360 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-16 15:23:59.867  3868  4360 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 15:23:59.904  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:59.905  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:23:59.915  3816  4361 V GoogleAuthProtoRequest: [329] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 15:23:59.932  1520  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 15:23:59.932  1520  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 15:23:59.932  1520  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:23:59.932  1520  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:23:59.944  3816  4361 W ExperimentUpdateService: [329] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: [329] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 15:23:59.945  3816  4361 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 15:24:02.877  3868  4363 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-16 15:24:02.877  3868  4363 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 15:24:02.877  3868  4363 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:24:02.877  3868  4360 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 15:24:02.878  3868  4360 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-16 15:24:02.878  3868  4360 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:24:02.879  3868  4363 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:24:02.880  3868  4363 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 15:24:02.881  3868  4360 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 15:24:02.885  3868  4366 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 451, name: IncomingSocketThread/Receiver)
08-16 15:24:02.886  3868  4360 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 15:24:02.888  3868  4366 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 451, thread name: IncomingSocketThread/Receiver)
,08-16 15:24:02.888  3868  4366 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 15:24:02.889  3868  4366 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 451, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-16 15:24:02.894  3868  4367 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 450, name: OutgoingSocketThread/Sender)
,08-16 15:24:02.897  3868  4365 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 449, name: IncomingSocketThread/Sender)
,08-16 15:24:02.898  3868  4368 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: OutgoingSocketThread/Receiver)
08-16 15:24:02.899  3868  4368 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 452, thread name: OutgoingSocketThread/Receiver)
,08-16 15:24:02.900  3868  4368 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 15:24:02.900  3868  4368 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 15:24:05.879  3868  3918 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 461)
,08-16 15:24:05.881  3868  3918 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 15:24:05.882  3868  3918 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 462)
,08-16 15:24:05.889  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 15:24:05.889  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d4c069 added. We now have 3 listener(s)
08-16 15:24:05.891  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 15:24:05.891  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 15:24:05.891  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:24:05.891  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:24:05.891  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6c1aee added. We now have 4 listener(s)
,08-16 15:24:05.891  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:24:05.892  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 15:24:05.899  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 15:24:05.913  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:24:05.913  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:24:05.913  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:24:05.913  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:24:05.913  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:24:05.913  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:24:05.913  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:24:05.913  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:24:05.918  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:24:05.918  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:24:05.920  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:24:05.920  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 15:24:05.920  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:24:05.920  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 15:24:05.921  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:24:05.921  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:24:05.921  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 15:24:05.921  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d4c069 removed from the list
08-16 15:24:05.922  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:24:05.922  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6c1aee removed from the list
,08-16 15:24:05.928  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:24:05.936  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:24:05.936  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:24:05.937  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:24:05.938  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:24:05.938  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:24:05.944  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 15:24:05.944  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:24:05.944  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:24:05.944  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6c1aee not in the list
,08-16 15:24:05.945  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:24:05.945  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:24:05.950  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:24:05.951  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:24:05.951  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:24:05.951  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6c1aee not in the list
08-16 15:24:05.951  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:24:05.951  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:24:05.951  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:24:05.951  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d4c069 not in the list
08-16 15:24:05.953  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 15:24:05.953  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b024e1c added. We now have 3 listener(s)
,08-16 15:24:05.956  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 15:24:05.956  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:24:05.956  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 15:24:05.957  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:24:05.957  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96ffa25 added. We now have 4 listener(s)
08-16 15:24:05.957  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:24:05.958  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 15:24:05.962  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 15:24:05.977  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:24:05.977  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:24:05.977  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:24:05.977  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:24:05.977  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:24:05.977  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:24:05.977  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:24:05.977  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:24:05.983  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:24:05.984  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 15:24:05.985  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 15:24:05.985  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 15:24:05.985  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 15:24:05.986  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:24:05.986  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 15:24:05.989  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:24:05.994  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:24:05.997  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 15:24:05.997  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 15:24:06.009  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 15:24:06.011  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 15:24:06.012  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 15:24:06.020  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 15:24:06.020  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 15:24:06.020  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 15:24:06.022  3868  3918 D BluetoothAdapter: STATE_ON
,08-16 15:24:06.030  4266  4296 D BtGatt.GattService: registerClient() - UUID=7bce620e-6261-4078-9dc1-f88b7aa3ac18
08-16 15:24:06.032  4266  4282 D BtGatt.GattService: onClientRegistered() - UUID=7bce620e-6261-4078-9dc1-f88b7aa3ac18, clientIf=5
,08-16 15:24:06.034  3868  3880 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 15:24:06.037  4266  4293 D BtGatt.GattService: start scan with filters
,08-16 15:24:06.048  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 15:24:06.048  4266  4285 D BtGatt.ScanManager: handling starting scan
08-16 15:24:06.048  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 15:24:06.049  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 15:24:06.049  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 15:24:06.052  4266  4285 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4521d36
,08-16 15:24:06.061  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 15:24:06.062  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 15:24:06.062  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 15:24:06.068  4266  4282 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 15:24:06.069  4266  4282 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-16 15:24:06.070  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 15:24:06.071  4266  4285 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 15:24:06.079  3868  3918 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 15:24:06.079  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 15:24:06.080  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 15:24:06.080  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:24:06.080  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 15:24:06.080  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 15:24:06.080  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 15:24:06.080  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 15:24:06.080  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-16 15:24:06.080  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 15:24:06.081  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 15:24:06.082  3868  3918 D BluetoothAdapter: STATE_ON
,08-16 15:24:06.085  4266  4296 D BtGatt.GattService: stopScan() - queue size =1
,08-16 15:24:06.086  4266  4293 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 15:24:06.086  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:24:06.086  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 15:24:06.086  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 15:24:06.086  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 15:24:06.086  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 15:24:06.087  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 15:24:06.088  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 15:24:06.088  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 15:24:06.088  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 15:24:06.089  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 15:24:06.090  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 15:24:06.090  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 15:24:06.090  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 15:24:06.090  4266  4282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 15:24:06.090  4266  4282 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:24:06.092  4266  4285 D BtGatt.ScanManager: Starting BLE batch scan
08-16 15:24:06.092  4266  4285 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 15:24:06.123  4266  4282 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 15:24:06.123  4266  4282 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:24:06.146  4266  4282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 15:24:06.146  4266  4282 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:24:06.173  4266  4282 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16,
08-16 15:24:06.174  4266  4282 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:24:06.174  4266  4285 D BtGatt.ScanManager: stopping BLe Batch
,08-16 15:24:06.198  4266  4282 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 15:24:06.199  4266  4282 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 15:24:06.200  4266  4285 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 15:24:06.225  4266  4282 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 15:24:06.226  4266  4282 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 15:24:06.591  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 15:24:06.592  3868  3868 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:24:06.592  3868  3868 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 15:24:09.091  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:24:09.091  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 15:24:09.092  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:24:09.093  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:24:09.093  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:24:09.094  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:24:09.094  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 15:24:09.094  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b024e1c removed from the list
08-16 15:24:09.095  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:24:09.095  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96ffa25 removed from the list
08-16 15:24:09.095  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:24:09.096  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:24:09.097  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:24:09.098  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:24:09.101  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:24:09.101  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:24:09.101  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:24:09.102  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96ffa25 not in the list
08-16 15:24:09.102  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:24:09.102  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:24:09.106  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:24:09.107  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 15:24:09.107  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:24:09.108  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@96ffa25 not in the list
,08-16 15:24:09.108  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 15:24:09.108  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:24:09.109  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:24:09.109  3868  3918 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b024e1c not in the list
,08-16 15:24:09.111  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 15:24:09.112  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f899c6 added. We now have 3 listener(s)
08-16 15:24:09.114  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 15:24:09.114  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:24:09.114  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:24:09.115  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:24:09.115  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d7fd87 added. We now have 4 listener(s)
08-16 15:24:09.115  3868  3918 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:24:09.116  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 15:24:09.122  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 15:24:09.133  3868  3918 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:24:09.133  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:24:09.133  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 15:24:09.133  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:24:09.133  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:24:09.133  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:24:09.133  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:24:09.133  3868  3918 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:24:09.138  3868  3918 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:24:09.139  3868  3918 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 15:24:09.139  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 15:24:09.141  3868  3918 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 15:24:09.141  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-16 15:24:09.144  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:24:09.146  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 15:24:09.148  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-16 15:24:09.148  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 15:24:09.150  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 15:24:09.151  3868  3868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:24:09.154  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 15:24:09.155  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-16 15:24:09.155  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 15:24:09.156  3868  3868 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-16 15:24:09.157  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 15:24:09.158  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 15:24:09.158  3868  4369 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:24:09.158  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:24:09.158  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 15:24:09.162  3868  4369 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-16 15:24:09.166  3868  3918 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 15:24:09.166  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 15:24:09.175  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 15:24:09.176  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 15:24:09.176  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 15:24:09.181  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-16 15:24:09.182  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 15:24:09.183  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-16 15:24:09.186  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-16 15:24:09.186  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 15:24:09.187  3868  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,08-16 15:24:09.188  3868  3918 D BluetoothAdapter: STATE_ON
,08-16 15:24:09.195  4266  4277 D BtGatt.GattService: registerClient() - UUID=b0e89a3d-3ac3-41b2-bd8b-ba96d293b7e3
,08-16 15:24:09.196  4266  4282 D BtGatt.GattService: onClientRegistered() - UUID=b0e89a3d-3ac3-41b2-bd8b-ba96d293b7e3, clientIf=5
,08-16 15:24:09.197  3868  3879 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-16 15:24:09.202  4266  4284 D BtGatt.AdvertiseManager: message : 0
,08-16 15:24:09.209  4266  4284 D BtGatt.AdvertiseManager: starting multi advertising
,08-16 15:24:09.231  4266  4282 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-16 15:24:09.248  4266  4282 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-16 15:24:09.250  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-16 15:24:09.251  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 15:24:09.257  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 15:24:09.261  3868  3868 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 15:24:09.262  3868  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-16 15:24:09.262  3868  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-16 15:24:09.263  3868  3868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-16 15:24:09.263  3868  3868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-16 15:24:09.263  3868  3868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-16 15:24:09.272  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 15:24:09.273  3868  3868 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-16 15:24:09.273  3868  3868 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 15:24:09.774  3868  3868 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-16 15:24:09.775  3868  3868 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 15:24:09.775  3868  3868 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 15:24:12.274  3868  3918 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:24:12.274  3868  3918 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-16 15:24:12.275  3868  3918 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 15:24:12.275  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 15:24:12.275  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 15:24:12.276  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 15:24:12.278  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 15:24:12.278  3868  4369 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 15:24:12.278  3868  4369 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 15:24:12.278  3868  3918 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 15:24:12.278  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 15:24:12.279  3868  3868 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 15:24:12.279  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 15:24:12.278  3868  4369 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 15:24:12.279  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 15:24:12.279  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 15:24:12.280  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 15:24:12.282  3868  3918 D BluetoothAdapter: STATE_ON
08-16 15:24:12.283  3868  3918 D BluetoothLeScanner: could not find callback wrapper
08-16 15:24:12.283  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:24:12.284  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-16 15:24:12.286  4266  4284 D BtGatt.AdvertiseManager: message : 1
,08-16 15:24:12.287  4266  4284 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-16 15:24:12.298  4266  4282 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-16 15:24:12.298  4266  4282 D BtGatt.GattService: Client app is not null!
,08-16 15:24:12.300  4266  4276 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 15:24:12.300  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 15:24:12.300  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-16 15:24:12.301  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-16 15:24:12.301  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-16 15:24:12.301  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-16 15:24:12.302  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 15:24:12.302  3868  3918 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 15:24:12.302  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 15:24:12.303  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 15:24:12.306  3868  3868 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 15:24:12.306  3868  3918 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:24:12.306  3868  3868 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 15:24:12.306  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:24:12.307  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 15:24:12.307  3868  3868 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
,08-16 15:24:12.308  3868  3868 E AndroidRuntime: FATAL EXCEPTION: main
08-16 15:24:12.308  3868  3868 E AndroidRuntime: Process: com.test.thalitest, PID: 3868
08-16 15:24:12.308  3868  3868 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
08-16 15:24:12.308  3868  3868 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
08-16 15:24:12.308  3868  3868 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
08-16 15:24:12.308  3868  3868 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
08-16 15:24:12.308  3868  3868 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 15:24:12.308  3868  3868 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 15:24:12.308  3868  3868 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:24:12.308  3868  3868 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 15:24:12.308  3868  3868 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:24:12.308  3868  3868 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 15:24:12.308  3868  3868 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 15:24:12.307  3868  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 15:24:12.309  3868  3918 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f899c6 removed from the list
,08-16 15:24:12.309  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 15:24:12.309  3868  3918 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d7fd87 removed from the list
,08-16 15:24:12.310  3868  3918 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:24:12.310  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:24:12.311  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:24:12.311  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:24:12.313   871  2163 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
08-16 15:24:12.317  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:24:12.317  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:24:12.324  3868  3918 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:24:12.324  3868  3918 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d7fd87 not in the list
08-16 15:24:12.324  3868  3918 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:24:12.324  3868  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:24:12.327  3868  3868 I Process : Sending signal. PID: 3868 SIG: 9
,08-16 15:24:12.443   871  1386 D GraphicsStats: Buffer count: 2
,08-16 15:24:12.444   871  1398 I WindowState: WIN DEATH: Window{aca1e3c u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 15:24:12.444   871  1314 D WifiService: Client connection lost with reason: 4
,08-16 15:24:12.471   871  2162 I ActivityManager: Process com.test.thalitest (pid 3868) has died
,08-16 15:24:12.512   871  1966 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3868 uid 10000
,08-16 15:24:12.514  1862  1862 I Keyboard.Facilitator: onFinishInput()
,08-16 15:24:20.287   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=235750, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 15:24:24.591  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:24:24.594  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:24:24.632  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 15:24:24.632  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 15:24:24.633  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:24:24.633  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:24:24.667  3548  4374 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 15:24:24.667  3548  4374 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at jdm.a(PG:82)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at blb.a(PG:3937)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at czp.a(PG:18188)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at czp.a(PG:9081)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:24:24.667  3548  4374 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	... 12 more
08-16 15:24:24.667  3548  4374 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at fal.a(PG:38)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:24:24.667  3548  4374 E HttpOperation: 	... 14 more
,08-16 15:24:24.728  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 15:24:24.728  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 15:24:24.728  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 15:24:24.728  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:24:24.761  3548  4374 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 15:24:24.761  3548  4374 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:24:24.761  3548  4374 E HttpOperation: 	,at jdm.a(PG:82)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at hec.a(PG:42)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at hee.a(PG:102)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at czr.a(PG:65)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at kka.a(PG:108)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at czp.a(PG:19176)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at czp.a(PG:9081)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:24:24.761  3548  4374 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	... 15 more
08-16 15:24:24.761  3548  4374 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at fal.a(PG:38)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:24:24.761  3548  4374 E HttpOperation: 	... 17 more
08-16 15:24:24.761  3548  4374 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 15:24:24.761  3548  4374 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at hec.a(PG:42)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at hee.a(PG:102)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at czr.a(PG:65)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at kka.a(PG:108)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	... 15 more
08-16 15:24:24.761  3548  4374 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 15:24:24.761  3,548  4374 E ExperimentLoader: 	at fal.a(PG:38)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 15:24:24.761  3548  4374 E ExperimentLoader: 	... 17 more
,08-16 15:24:24.971   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 239700, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:24:51.989   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267452, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 15:24:55.120  3032  4377 V KeepSync: Connecting to GoogleApiClient
08-16 15:24:55.121   871  1933 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 15:24:55.177  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:24:55.179  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:24:55.210  1520  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 15:24:55.210  1520  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 15:24:55.210  1520  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:24:55.210  1520  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:24:55.227  1740  4378 V BaseAuthAsyncOperation: access token request failed
,08-16 15:24:55.228  3032  4377 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 15:24:55.272  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 15:24:55.272  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 15:24:55.273  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:24:55.273  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:24:55.301  3032  4377 E KeepSync: IOException
08-16 15:24:55.301  3032  4377 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 15:24:55.301  3032  4377 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 15:24:55.301  3032  4377 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 15:24:55.301  3032  4377 E KeepSync: 	... 10 more
,08-16 15:24:55.301  3032  4377 W KeepSync: Sync result 2
,08-16 15:24:55.307   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 256455, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:25:12.557  1862  1975 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-16 15:25:12.557  1862  1975 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-16 15:25:12.594  1520  1520 I ConfigService: onCreate
,08-16 15:25:17.669  1520  1520 I ConfigService: onDestroy
,08-16 15:25:20.374   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=295837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 15:25:25.498  3946  4385 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 15:25:25.530  3946  4386 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 15:25:25.541  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:25.544  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:25.571  1520  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 15:25:25.571  1520  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 15:25:25.571  1520  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:25.571  1520  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:25.606  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:25.608  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:25.636  1520  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 15:25:25.636  1520  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 15:25:25.636  1520  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:25.636  1520  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:25.653  3946  4386 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 15:25:25.655  3946  4385 E BooksSync: Soft error
08-16 15:25:25.655  3946  4385 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 15:25:25.655  3946  4385 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 15:25:25.655  3946  4385 E BooksSync: Sync error
08-16 15:25:25.655  3946  4385 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 15:25:25.655  3946  4385 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 15:25:25.656  3946  4385 I BooksSync: Finished books sync
,08-16 15:25:25.661   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 289740, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:25:53.736   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329199, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 15:25:55.916  3032  4388 V KeepSync: Connecting to GoogleApiClient
,08-16 15:25:55.917   871  1386 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 15:25:55.993  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:55.996  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:56.027  1520  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-16 15:25:56.027  1520  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 15:25:56.027  1520  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:56.027  1520  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:56.061  1740  4391 V BaseAuthAsyncOperation: access token request failed
,08-16 15:25:56.065  3032  4388 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 15:25:56.126  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 15:25:56.127  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 15:25:56.127  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 15:25:56.127  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:56.153  3548  4390 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 15:25:56.153  3548  4390 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at jdm.a(PG:82)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at blb.a(PG:3937)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at czp.a(PG:18188)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at czp.a(PG:9081)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:25:56.153  3548  4390 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	... 12 more
08-16 15:25:56.153  3548  4390 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at fal.a(PG:38)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:25:56.153  3548  4390 E HttpOperation: 	... 14 more
,08-16 15:25:56.219  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 15:25:56.219  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 15:25:56.219  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:56.220  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:56.243  3548  4390 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 15:25:56.243  3548  4390 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at jdm.a(PG:82)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at hec.a(PG:42)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at hee.a(PG:102)
,08-16 15:25:56.243  3548  4390 E HttpOperation: 	at czr.a(PG:65)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at kka.a(PG:108)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at czp.a(PG:19176)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at czp.a(PG:9081)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:25:56.243  3548  4390 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	... 15 more
08-16 15:25:56.243  3548  4390 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at fal.a(PG:38)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:25:56.243  3548  4390 E HttpOperation: 	... 17 more
08-16 15:25:56.243  3548  4390 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 15:25:56.243  3548  4390 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at hec.a(PG:42)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at hee.a(PG:102)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at czr.a(PG:65)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at kka.a(PG:108)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: ,	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	... 15 more
08-16 15:25:56.243  3548  4390 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at fal.a(PG:38)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 15:25:56.243  3548  4390 E ExperimentLoader: 	... 17 more
,08-16 15:25:56.300  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 15:25:56.300  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 15:25:56.301  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:56.301  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:56.325  3032  4388 E KeepSync: IOException
08-16 15:25:56.325  3032  4388 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 15:25:56.325  3032  4388 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 15:25:56.325  3032  4388 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 15:25:56.325  3032  4388 E KeepSync: 	... 10 more
08-16 15:25:56.325  3032  4388 W KeepSync: Sync result 2
,08-16 15:25:56.388   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 303526, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:25:56.455   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 304115, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:25:56.533   871   883 I ActivityManager: Start proc 4394:com.google.android.calendar/u0a37 for service com.google.android.calendar/com.google.android.syncadapters.calendar.CalendarSyncAdapterService
,08-16 15:25:56.584  1740  4405 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 15:25:56.605  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:56.613  4394  4394 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,08-16 15:25:56.653  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: mail
,08-16 15:25:56.653  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
08-16 15:25:56.653  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:56.653  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:56.674  1520  1531 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 15:25:56.674  1520  1531 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 15:25:56.674  1520  1531 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 15:25:56.674  1520  1531 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-16 15:25:56.674  1520  1531 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-16 15:25:56.674  1520  1531 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-16 15:25:56.674  1520  1531 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-16 15:25:56.679  1740  4405 W SubscribedFeeds: Hard error
,08-16 15:25:56.703   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 331792, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-16 15:25:56.706   871   883 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), subscribedfeeds, PERIODIC, currentRunTime 365080, reason: Periodic
,08-16 15:25:56.832  2167  4412 I GCoreUlr: Uploading GCM registration ID for account#2#
,08-16 15:25:56.860  2167  4412 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 15:25:56.874  2167  4412 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,08-16 15:25:56.886  2167  4412 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,08-16 15:25:56.911  4394  4394 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,08-16 15:25:56.913  4394  4394 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,08-16 15:25:56.960  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/userlocation.reporting
,08-16 15:25:56.960  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/userlocation.reporting without consulting the cloud.
08-16 15:25:56.961  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:56.961  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:56.983  4394  4418 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-16 15:25:56.988  2167  4412 E GCoreUlr: 
08-16 15:25:56.988  2167  4412 E GCoreUlr: com.google.android.gms.auth.ae: BadAuthentication
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.gms.auth.p.b(SourceFile:480)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:397)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.gms.auth.p.a(SourceFile:342)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.location.reporting.d.c.a(SourceFile:164)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.location.reporting.d.g.a(SourceFile:94)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	,at com.google.android.location.reporting.service.u.b(SourceFile:220)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.location.reporting.service.u.a(SourceFile:173)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.location.reporting.service.t.a(SourceFile:151)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:98)
08-16 15:25:56.988  2167  4412 E GCoreUlr: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
,08-16 15:25:57.014   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 331804, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-16 15:25:57.017   871   883 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.location.reporting, PERIODIC, currentRunTime 362826, reason: Periodic
,08-16 15:25:57.040  4394  4418 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-16 15:25:57.066  4394  4418 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 15:25:57.068  4394  4418 W AbstractGoogleClient: Application name is not set. Call Builder#setApplicationName.
,08-16 15:25:57.084   871   883 I ActivityManager: Start proc 4424:com.google.android.gm/u0a78 for service com.google.android.gm/.provider.MailSyncAdapterService
,08-16 15:25:57.147  4424  4424 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm
,08-16 15:25:57.195  4424  4438 I Gmail   : getAccountsCursor
,08-16 15:25:57.196  4424  4439 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,08-16 15:25:57.205  1520  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.calendar, service: oauth2:https://www.googleapis.com/auth/calendar
,08-16 15:25:57.205  1520  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/calendar without consulting the cloud.
08-16 15:25:57.205  1520  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:57.205  1520  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 15:25:57.205  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: Exception in onPerformLoggedSync 
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:153)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(GoogleRequestInitializer.java:90)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.api.client.http.HttpRequest.execute(HttpRequest.java:859)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:419)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(AbstractGoogleClientRequest.java:352)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(AbstractGoogleClientRequest.java:469)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.Utils.executeAndLog(Utils.java:555)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.processAccountCalendars(CalendarSyncAdapterApiary.java:2853)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.updateCalendarsFromServerFeed(CalendarSyncAdapterApiary.java:2301)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.getServerDiffsForAccount(CalendarSyncAdapterApiary.java:2182)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.performSync(CalendarSyncAdapterApiary.java:623)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.syncadapters.calendar.CalendarSyncAdapterApiary.onPerformLoggedSync(CalendarSyncAdapterApiary.java:473)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.android.emailcommon.syncadapter.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:49)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.zzb(Unknown Source)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(GoogleRequestInitializer.java:141)
08-16 15:25:57.239  4394  4418 E CalendarSyncAdapter: 	... 13 more
,08-16 15:25:57.242  4424  4424 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-16 15:25:57.278   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 331799, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-16 15:25:57.279   871   883 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.calendar, PERIODIC, currentRunTime 363346, reason: Periodic
,08-16 15:25:57.292  4424  4448 E Gmail   : Error finding the version of the Email provider.....
08-16 15:25:57.292  4424  4448 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
08-16 15:25:57.292  4424  4448 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
08-16 15:25:57.292  4424  4448 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
08-16 15:25:57.292  4424  4448 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
08-16 15:25:57.292  4424  4448 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 15:25:57.292  4424  4448 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:25:57.292  4424  4448 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
08-16 15:25:57.292  4424  4448 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 15:25:57.293  4424  4448 W EmailMigration: We do not support migrating this version of the Email provider.
,08-16 15:25:57.297  4424  4450 I Gmail   : getAccountsCursor
,08-16 15:25:57.340   871   883 I ActivityManager: Start proc 4451:com.google.process.gapps/u0a99 for service com.google.android.syncadapters.contacts/.ContactsSyncAdapterService
,08-16 15:25:57.349  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:57.359  4424  4463 W Gmail   : Sync started for account: account:61035162
,08-16 15:25:57.379   871  1398 I ActivityManager: Start proc 4466:com.google.android.gm.exchange/u0a77 for service com.google.android.gm.exchange/com.android.exchange.service.EasService
,08-16 15:25:57.379   871  1936 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,08-16 15:25:57.398  4451  4451 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm
,08-16 15:25:57.417  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:57.419  4451  4451 I GoogleHttpClient: GMS http client unavailable, use old client
,08-16 15:25:57.421  4466  4466 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm
,08-16 15:25:57.422  4424  4472 I Gmail   : Observing account changes for notifications
,08-16 15:25:57.442   871  1386 I ActivityManager: Start proc 4486:android.process.acore/u0a5 for content provider com.android.providers.contacts/.ContactsProvider2
,08-16 15:25:57.465  4466  4466 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-16 15:25:57.475  4486  4486 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 15:25:57.497  4466  4466 I Exchange: EasService.onCreate
,08-16 15:25:57.509  4466  4501 I Exchange: RestartPingTask
,08-16 15:25:57.535  4466  4466 I Exchange: RestartPingsTask did not start any pings.
,08-16 15:25:57.535  4466  4466 I Exchange: PSS stopIfIdle
08-16 15:25:57.535  4466  4466 I Exchange: PSS has no active accounts; stopping service.
,08-16 15:25:57.536  4466  4466 I Exchange: onDestroy
,08-16 15:25:57.546  4486  4486 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 15:25:57.576  4451  4485 I [@@    ] SyncAdapterProxy: Delagator disabled, using the (deprecated) GData sync adapter
,08-16 15:25:57.584  4451  4485 I GoogleHttpClient: GMS http client unavailable, use old client
,08-16 15:25:57.630  4486  4504 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,08-16 15:25:57.664  4424  4482 I Gmail   : notifyAccountChanged
,08-16 15:25:57.666  4424  4439 I Gmail   : getAccountsCursor
,08-16 15:25:57.676  4424  4482 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,08-16 15:25:57.686  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:57.690  4424  4482 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,08-16 15:25:57.721  4424  4482 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,08-16 15:25:57.722  4424  4463 I Gmail   : notifyAccountChanged
,08-16 15:25:57.726  4424  4482 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,08-16 15:25:57.953  4424  4463 I Gmail   : MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 4353, normalSync: true
,08-16 15:25:57.955  4424  4446 I Gmail   : getAccountsCursor
,08-16 15:25:57.963  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:58.002  1520  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.syncadapters.contacts, service: cp
,08-16 15:25:58.002  1520  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> cp without consulting the cloud.
,08-16 15:25:58.002  1520  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 15:25:58.002  1520  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:58.011  4486  4504 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,08-16 15:25:58.012  4486  4504 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,08-16 15:25:58.020  1520  2981 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 15:25:58.020  1520  2981 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 15:25:58.020  1520  2981 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 15:25:58.020  1520  2981 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-16 15:25:58.020  1520  2981 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-16 15:25:58.020  1520  2981 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-16 15:25:58.020  1520  2981 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: innerSync failed
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:269)
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:169)
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at com.google.android.syncadapters.contacts.delegation.SyncAdapterProxy.onPerformLoggedSync(SyncAdapterProxy.java:128)
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-16 15:25:58.022  4451  4485 D ContactsSyncAdapter: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 15:25:58.042   871  2163 I ActivityManager: Killing 1992:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-16 15:25:58.080  4486  4504 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,08-16 15:25:58.094  4486  4504 I ContactDirectoryManager: Discovered 0 contact directories in 317ms
,08-16 15:25:58.103   871  1314 D WifiService: Client connection lost with reason: 4
,08-16 15:25:58.122   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 331816, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-16 15:25:58.124   871   883 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, PERIODIC, currentRunTime 366277, reason: Periodic
,08-16 15:25:58.136   871  1400 I ActivityManager: Killing 3510:com.android.vending/u0a19 (adj 15): empty #17
,08-16 15:25:58.213  1740  1740 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,08-16 15:25:58.216  4424  4463 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-16 15:25:58.258  4424  4463 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-16 15:25:58.283  4424  4463 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 15:25:58.292  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:58.334  1520  2118 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gm, service: mail
,08-16 15:25:58.334  1520  2118 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
08-16 15:25:58.334  1520  2118 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:58.335  1520  2118 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:58.376  1520  2118 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 15:25:58.376  1520  2118 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 15:25:58.376  1520  2118 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 15:25:58.376  1520  2118 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-16 15:25:58.376  1520  2118 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-16 15:25:58.376  1520  2118 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-16 15:25:58.376  1520  2118 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 15:25:58.398  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:58.406  1520  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/reminders
,08-16 15:25:58.406  1520  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/reminders without consulting the cloud.
,08-16 15:25:58.407  1520  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 15:25:58.407  1520  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:58.456  1740  4513 E RemindersSync: AuthError [T SyncAdapterThread-1:id=190:priority=5:group=main]
,08-16 15:25:58.461  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gm, service: mail
,08-16 15:25:58.462  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mail without consulting the cloud.
08-16 15:25:58.462  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 15:25:58.462  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:58.470   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 331821, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-16 15:25:58.471   871   883 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.gms.reminders, PERIODIC, currentRunTime 365239, reason: Periodic
,08-16 15:25:58.474  1520  2313 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 15:25:58.474  1520  2313 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 15:25:58.474  1520  2313 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 15:25:58.474  1520  2313 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-16 15:25:58.474  1520  2313 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-16 15:25:58.474  1520  2313 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-16 15:25:58.474  1520  2313 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 15:25:58.489  4099  4516 I SyncAdapterService: Ignoring sync request for non-current account
,08-16 15:25:58.493  4424  4463 I Gmail   : notifyAccountChanged
,08-16 15:25:58.494  4424  4450 I Gmail   : getAccountsCursor
,08-16 15:25:58.498  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:58.535  4424  4463 I Gmail   : notifyAccountChanged
,08-16 15:25:58.538  4424  4438 I Gmail   : getAccountsCursor
,08-16 15:25:58.540  4424  4463 W Gmail   : Sync complete for account: account:61035162
,08-16 15:25:58.545  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:58.567   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 331810, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,08-16 15:25:58.568   871   883 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), gmail-ls, PERIODIC, currentRunTime 365998, reason: Periodic
,08-16 15:25:58.588  4084  4519 D DelayedSyncController: Delaying sync.
,08-16 15:25:58.594   871  2160 I ActivityManager: Killing 3979:com.android.settings/1000 (adj 15): empty #17
,08-16 15:25:58.673   871   883 I ActivityManager: Start proc 4521:com.google.android.music:main/u0a66 for service com.google.android.music/.sync.SyncAdapterService
,08-16 15:25:58.689  1740  1740 W BaseAppContext: Using Auth Proxy for data requests.
08-16 15:25:58.689  1740  1740 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 15:25:58.703  1740  1740 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 15:25:58.717  1740  1740 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 15:25:58.725  1740  1740 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 15:25:58.736  1740  1740 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 15:25:58.750  1740  1740 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 15:25:58.761  4521  4521 W System  : ClassLoader referenced unknown path: /system/app/Music2/lib/arm
,08-16 15:25:58.770  4521  4521 I MultiDex: VM with version 2.1.0 has multidex support
,08-16 15:25:58.770  4521  4521 I MultiDex: install
08-16 15:25:58.770  4521  4521 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 15:25:58.813  4521  4521 I MusicStore: Database version: 121
,08-16 15:25:58.863   871   883 I ActivityManager: Start proc 4540:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,08-16 15:25:58.889  4540  4540 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm
,08-16 15:25:58.896  4521  4521 D MusicLifecycle: com.google.android.music.MusicApplication generated event: Application created
,08-16 15:25:58.919  4521  4521 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-16 15:25:58.971  4521  4521 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-16 15:25:58.995  4521  4521 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 15:25:58.995  4521  4521 D AndroidMusic: GMSCore installation verified
,08-16 15:25:59.006  4521  4521 I ConfigStore: Config Database version: 1
,08-16 15:25:59.038   871  1965 I ActivityManager: Start proc 4554:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,08-16 15:25:59.074  4554  4554 W System  : ClassLoader referenced unknown path: /system/app/CloudPrint2/lib/arm
,08-16 15:25:59.077  4521  4521 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, iconUri=null, enabled=true, connecting=false, connectionState=0, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-16 15:25:59.078  4540  4559 I com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter: Sync request not initiated by GCP app. Dropping
,08-16 15:25:59.088   871  1965 I ActivityManager: Killing 3997:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,08-16 15:25:59.122   871  1400 I ActivityManager: Killing 4072:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,08-16 15:25:59.173  4521  4521 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,08-16 15:25:59.177  4521  4521 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory,
,08-16 15:25:59.183  4521  4521 D MusicLifecycle: com.google.android.music.net.NetworkMonitor generated event: Service created
,08-16 15:25:59.184  4521  4521 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 15:25:59.193  4521  4571 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync started
,08-16 15:25:59.199  4521  4521 D MusicLifecycle: com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder generated event: Service created
,08-16 15:25:59.201  1740  4570 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-16 15:25:59.201  4521  4521 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service created
,08-16 15:25:59.204  4521  4521 D MusicLifecycle: com.google.android.music.download.artwork.ArtDownloadService generated event: Service created
,08-16 15:25:59.212  4521  4521 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6c4ed9f and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-16 15:25:59.213  4521  4521 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 15:25:59.221  4521  4521 D MusicLifecycle: com.google.android.music.download.ArtDownloadQueueService generated event: Service created
,08-16 15:25:59.223  4521  4521 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,08-16 15:25:59.227  4521  4521 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 15:25:59.232  4521  4521 D MusicLifecycle: com.google.android.music.download.cache.ArtCacheService generated event: Service created
,08-16 15:25:59.233  3946  4575 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 15:25:59.249  4521  4521 D MusicLifecycle: com.google.android.music.download.cache.StorageMigrationService generated event: Service destroyed
,08-16 15:25:59.261  3946  4577 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 15:25:59.279  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 15:25:59.279  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 15:25:59.279  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:59.279  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:59.310  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 15:25:59.310  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 15:25:59.310  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:59.310  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:59.310  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:59.320  3946  4577 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 15:25:59.320  3946  4575 E BooksSync: Soft error
08-16 15:25:59.320  3946  4575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 15:25:59.320  3946  4575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 15:25:59.320  3946  4575 E BooksSync: Sync error
08-16 15:25:59.320  3946  4575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 15:25:59.320  3946  4575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 15:25:59.320  3946  4575 I BooksSync: Finished books sync
,08-16 15:25:59.328   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 333054, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:25:59.337  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.music, service: sj
,08-16 15:25:59.337  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> sj without consulting the cloud.
08-16 15:25:59.337  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:25:59.337  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:25:59.347  1520  1532 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 15:25:59.347  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 15:25:59.347  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 15:25:59.347  1520  1532 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-16 15:25:59.347  1520  1532 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-16 15:25:59.347  1520  1532 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-16 15:25:59.347  1520  1532 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 15:25:59.352  4521  4521 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@f9b3c9b and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,08-16 15:25:59.359  4521  4571 D MusicLifecycle: com.google.android.music.sync.google.MusicSyncAdapter generated event: Sync ended
08-16 15:25:59.359  4521  4571 W MusicSyncAdapter: Sync failed due to an authentication issue.
,08-16 15:25:59.361  4521  4521 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,08-16 15:25:59.365  4521  4521 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.ACTIVATE_AUTO_CACHE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,08-16 15:25:59.366  4521  4521 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@f9b3c9b and intent Intent { act=com.google.android.music.SYNC_COMPLETE flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
08-16 15:25:59.367   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 331838, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
08-16 15:25:59.367   871   883 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 367330, reason: Periodic
,08-16 15:25:59.371  4521  4521 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,08-16 15:25:59.375  4521  4521 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,08-16 15:25:59.383  4521  4521 D MusicLifecycle: com.google.android.music.sync.SyncAdapterService generated event: Service destroyed
,08-16 15:25:59.385  4521  4521 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service created
,08-16 15:25:59.385  4521  4521 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service started with intent Intent { act=com.google.android.music.SYNC_COMPLETE cmp=com.google.android.music/.store.KeepOnUpdater$SyncListener }
,08-16 15:25:59.387  4521  4580 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
,08-16 15:25:59.387  4521  4580 I MusicLeanback: Stop autocaching.
,08-16 15:25:59.393  4521  4521 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,08-16 15:25:59.394  4521  4521 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,08-16 15:25:59.420  4521  4521 D MusicLifecycle: com.google.android.music.download.MusicCommunicator generated event: Broadcast received with context android.app.ReceiverRestrictedContext@f9b3c9b and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.download.MusicCommunicator }
,08-16 15:25:59.424  4521  4521 D MusicLifecycle: com.google.android.music.store.KeepOnUpdater$SyncListener generated event: Service destroyed
,08-16 15:25:59.429  4521  4521 D MusicLifecycle: com.google.android.music.download.keepon.KeeponSchedulingService generated event: Service created
,08-16 15:25:59.435  4521  4521 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,08-16 15:25:59.438  4521  4521 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@f9b3c9b and intent Intent { act=com.google.android.music.NEW_SHOULDKEEPON flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,08-16 15:25:59.507   871  1933 I ActivityManager: Start proc 4587:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
08-16 15:25:59.507  4521  4521 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
,08-16 15:25:59.513  4521  4521 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,08-16 15:25:59.515  4521  4521 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,08-16 15:25:59.519  4521  4521 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
,08-16 15:25:59.525  4521  4521 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,08-16 15:25:59.577  4587  4587 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-16 15:25:59.590  4587  4587 I MultiDex: VM with version 2.1.0 has multidex support
,08-16 15:25:59.590  4587  4587 I MultiDex: install
08-16 15:25:59.590  4587  4587 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 15:25:59.649  4587  4587 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-16 15:25:59.678  4587  4587 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-16 15:25:59.686  1520  2271 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 15:25:59.691  1520  1520 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 15:25:59.703  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:25:59.706  1740  1740 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-16 15:25:59.725  4587  4587 D WearableService: callingUid 10011, callindPid: 4587
,08-16 15:25:59.766  1740  4608 D LocationInitializer: Restart initialization of location
,08-16 15:25:59.771  2167  4605 E MDM     : [158] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,08-16 15:25:59.783  4587  4604 D NativeLibraryUtils: Install completed successfully. count=13 extracted=0
,08-16 15:25:59.787  4521  4593 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
08-16 15:25:59.793  4521  4521 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
08-16 15:25:59.794  4521  4521 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,08-16 15:25:59.796   871  4371 I ActivityManager: Killing 4150:com.google.android.apps.photos/u0a71 (adj 15): empty #17
,08-16 15:25:59.870  2167  2223 W GCoreFlp: No location to return for getLastLocation()
,08-16 15:25:59.871  1520  4609 W FusedLocationProvider: location=null
,08-16 15:26:00.039  3816  4613 V GoogleAuthProtoRequest: [330] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 15:26:00.082  1520  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 15:26:00.082  1520  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 15:26:00.082  1520  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 15:26:00.082  1520  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:26:00.108  3816  4613 W ExperimentUpdateService: [330] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: [330] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 15:26:00.112  3816  4613 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 15:26:00.268  1520  1520 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 15:26:00.744  1520  4616 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-16 15:26:01.761  4394  4411 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-16 15:26:02.293  4424  4443 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-16 15:26:02.547  4466  4500 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-16 15:26:04.103  4521  4521 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService$EnablingReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@f9b3c9b and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver }
,08-16 15:26:04.124  4521  4521 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service created
,08-16 15:26:04.129  4521  4521 D MusicLifecycle: com.google.android.music.leanback.AutoCacheSchedulingService generated event: Service started with intent Intent { act=com.google.android.music.leanback.APP_IN_USE cmp=com.google.android.music/.leanback.AutoCacheSchedulingService (has extras) }
,08-16 15:26:04.129  4521  4521 D MusicLifecycle: com.google.android.music.wear.WearBroadcastReceiver generated event: Broadcast received with context android.app.ReceiverRestrictedContext@f9b3c9b and intent Intent { act=com.google.android.music.START_DOWNLOAD_SCHEDULING flg=0x10 cmp=com.google.android.music/.wear.WearBroadcastReceiver }
,08-16 15:26:04.136  4521  4521 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service created
08-16 15:26:04.142  4521  4628 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
08-16 15:26:04.142  4521  4628 I MusicLeanback: Stop autocaching.
08-16 15:26:04.142  4521  4521 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service created
,08-16 15:26:04.150  4521  4521 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service created
,08-16 15:26:04.150  4521  4521 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service started with intent Intent { cmp=com.google.android.music/.wear.WearMetadataSyncService }
,08-16 15:26:04.155  4521  4521 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,08-16 15:26:04.156  4521  4521 D MusicLifecycle: com.google.android.music.download.TrackDownloadQueueService generated event: Service destroyed
08-16 15:26:04.157  4521  4521 D MusicLifecycle: com.google.android.music.download.cache.TrackCacheService generated event: Service destroyed
,08-16 15:26:04.172  4521  4631 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,08-16 15:26:04.173  4521  4521 D MusicLifecycle: com.google.android.music.wear.WearMetadataSyncService generated event: Service destroyed
,08-16 15:26:04.780   871  1398 I ActivityManager: Killing 4028:com.google.android.talk/u0a61 (adj 15): empty #17
,08-16 15:26:06.300   871  2160 I ActivityManager: Killing 3032:com.google.android.keep/u0a79 (adj 15): empty #17
,08-16 15:26:11.331  1740  1749 W art     : Suspending all threads took: 8.009ms
,08-16 15:26:33.203   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=368665, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 15:27:02.028   871   883 I ActivityManager: Start proc 4638:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,08-16 15:27:02.098  4638  4638 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,08-16 15:27:02.375  4638  4654 V KeepSync: Connecting to GoogleApiClient
,08-16 15:27:02.376   871  1386 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 15:27:02.417  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:27:02.419  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:27:02.447  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-16 15:27:02.447  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-16 15:27:02.447  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:27:02.447  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:27:02.464  1740  4659 V BaseAuthAsyncOperation: access token request failed
,08-16 15:27:02.466  4638  4654 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 15:27:02.556  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 15:27:02.556  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 15:27:02.556  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:27:02.556  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:27:02.578  4638  4654 E KeepSync: IOException
08-16 15:27:02.578  4638  4654 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 15:27:02.578  4638  4654 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 15:27:02.578  4638  4654 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 15:27:02.578  4638  4654 E KeepSync: 	... 10 more
,08-16 15:27:02.578  4638  4654 W KeepSync: Sync result 2
,08-16 15:27:02.593   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, PERIODIC, currentRunTime 397362, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:27:02.975   871  1966 I ActivityManager: Killing 3548:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,08-16 15:27:07.140  4638  4645 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@de17d08)
,08-16 15:27:26.509   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=421972, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 15:27:32.780  3946  4663 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 15:27:32.819  3946  4664 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 15:27:32.846  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:27:32.849  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:27:32.895  1520  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 15:27:32.895  1520  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 15:27:32.895  1520  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:27:32.895  1520  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:27:32.949  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:27:32.955  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:27:33.005  1520  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 15:27:33.006  1520  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 15:27:33.006  1520  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:27:33.006  1520  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:27:33.063  3946  4664 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 15:27:33.073  3946  4663 E BooksSync: Soft error
08-16 15:27:33.073  3946  4663 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 15:27:33.073  3946  4663 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 15:27:33.074  3946  4663 E BooksSync: Sync error
08-16 15:27:33.074  3946  4663 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 15:27:33.074  3946  4663 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 15:27:33.074  3946  4663 I BooksSync: Finished books sync
,08-16 15:27:33.089   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 398647, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:27:54.827   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=450290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 15:28:00.145  1520  2187 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 15:28:04.059   871   883 I ActivityManager: Start proc 4666:com.google.android.apps.plus/u0a74 for service com.google.android.apps.plus/.service.EsSyncAdapterService
,08-16 15:28:04.606  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:28:04.608  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:28:04.660  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 15:28:04.660  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 15:28:04.660  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:28:04.660  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:28:04.702  4666  4684 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 15:28:04.702  4666  4684 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at jdm.a(PG:82)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at blb.a(PG:3937)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at czp.a(PG:18188)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at czp.a(PG:9081)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:28:04.702  4666  4684 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	... 12 more
08-16 15:28:04.702  4666  4684 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at fal.a(PG:38)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:28:04.702  4666  4684 E HttpOperation: 	... 14 more
,08-16 15:28:04.761  1520  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 15:28:04.761  1520  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 15:28:04.761  1520  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:28:04.761  1520  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:28:04.791  4666  4684 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 15:28:04.791  4666  4684 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at jdm.a(PG:82)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at jcs.o(PG:406)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at jcn.a(PG:1379)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at jcs.i(PG:143)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at hec.a(PG:42)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at hee.a(PG:102)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at czr.a(PG:65)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at kka.a(PG:108)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at czp.a(PG:19176)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at czp.a(PG:9081)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at czq.run(PG:1686)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:28:04.791  4666  4684 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at jdj.a(PG:4091)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at jdj.a(PG:1125)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at jdm.a(PG:77)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	,... 15 more
08-16 15:28:04.791  4666  4684 E HttpOperation: Caused by: faj: BadAuthentication
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at fal.a(PG:38)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	at jdj.a(PG:4089)
08-16 15:28:04.791  4666  4684 E HttpOperation: 	... 17 more
08-16 15:28:04.791  4666  4684 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 15:28:04.791  4666  4684 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at hec.a(PG:42)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at hee.a(PG:102)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at czr.a(PG:65)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at kka.a(PG:108)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	... 15 more
08-16 15:28:04.791  4666  4684 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at fal.a(PG:38)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 15:28:04.791  4666  4684 E ExperimentLoader: 	... 17 more
,08-16 15:28:04.959   871  1398 I ActivityManager: Killing 3454:com.android.providers.calendar/u0a3 (adj 15): empty #17
08-16 15:28:04.959   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 459279, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:28:56.643   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=512106, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 15:29:13.726  4638  4696 V KeepSync: Connecting to GoogleApiClient
,08-16 15:29:13.727   871  1936 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 15:29:13.801  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:29:13.804  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:29:13.836  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 15:29:13.836  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 15:29:13.836  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:29:13.836  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:29:13.859  1740  4697 V BaseAuthAsyncOperation: access token request failed
,08-16 15:29:13.860  4638  4696 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 15:29:13.924  1520  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-16 15:29:13.924  1520  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-16 15:29:13.925  1520  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:29:13.925  1520  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:29:13.950  4638  4696 E KeepSync: IOException
08-16 15:29:13.950  4638  4696 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 15:29:13.950  4638  4696 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 15:29:13.950  4638  4696 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 15:29:13.950  4638  4696 E KeepSync: 	... 10 more
,08-16 15:29:13.950  4638  4696 W KeepSync: Sync result 2
,08-16 15:29:13.961   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, PERIODIC, currentRunTime 529077, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:29:24.963   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=540426, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 15:29:44.154  3946  4699 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 15:29:44.203  3946  4700 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 15:29:44.218  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:29:44.222  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:29:44.268  1520  2981 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 15:29:44.268  1520  2981 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 15:29:44.269  1520  2981 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:29:44.269  1520  2981 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:29:44.320  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:29:44.325  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:29:44.364  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 15:29:44.365  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 15:29:44.365  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:29:44.365  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:29:44.386  3946  4700 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 15:29:44.387  3946  4699 E BooksSync: Soft error
08-16 15:29:44.387  3946  4699 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 15:29:44.387  3946  4699 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 15:29:44.389  3946  4699 E BooksSync: Sync error
08-16 15:29:44.389  3946  4699 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 15:29:44.389  3946  4699 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 15:29:44.390  3946  4699 I BooksSync: Finished books sync
,08-16 15:29:44.402   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 556261, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 15:29:58.241   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=573704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 15:30:00.310  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:30:00.316  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:30:00.345  3816  4702 V GoogleAuthProtoRequest: [331] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 15:30:00.394  1520  2979 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-16 15:30:00.394  1520  2979 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 15:30:00.394  1520  2979 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:30:00.395  1520  2979 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:30:00.431  3816  4702 W ExperimentUpdateService: [331] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: [331] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 15:30:00.432  3816  4702 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 15:30:26.616   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=602079, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 15:31:05.669   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=641132, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 15:31:34.029   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=669492, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 15:32:19.737   871   871 I ActivityManager: Start proc 4711:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-16 15:32:19.830  4711  4711 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-16 15:32:19.859  4711  4711 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-16 15:32:19.859  4711  4711 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 15:32:19.859  4711  4711 I GAv4    :   adb logcat -s GAv4
,08-16 15:32:19.877  4711  4711 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 15:32:19.886  4711  4711 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 15:32:19.901  4711  4726 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 15:32:19.999   871  4371 I ActivityManager: Killing 4394:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-16 15:38:52.231  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:38:52.233  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 15:38:52.246  3816  4743 V GoogleAuthProtoRequest: [332] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 15:38:52.307  1520  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 15:38:52.307  1520  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-16 15:38:52.307  1520  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 15:38:52.307  1520  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: [332] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: [332] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 15:38:52.321  3816  4743 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 15:38:57.231   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1112694, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 15:39:12.750   871  4322 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1128213, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 15:40:42.748   871   883 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),08-16 15:45:55.888  4763  4763 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 15:45:55.892  4763  4763 D AndroidRuntime: CheckJNI is OFF
08-16 15:45:55.927  4763  4763 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 15:45:55.968  4763  4763 I Radio-JNI: register_android_hardware_Radio DONE
08-16 15:45:55.989  4763  4763 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-16 15:45:56.001   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-16 15:45:56.118   871   894 W PackageSettings: Skipping PackageSetting{f5ff5eb com.example.hello/10273} due to missing metadata
08-16 15:45:56.151   871   894 I art     : Starting a blocking GC Explicit
08-16 15:45:56.197   871   894 I art     : Explicit concurrent mark sweep GC freed 18363(1245KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 692us total 45.570ms
08-16 15:45:56.242   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-16 15:45:56.246  4763  4763 I art     : System.exit called, status: 0
08-16 15:45:56.246  4763  4763 I AndroidRuntime: VM exiting with result code 0.
08-16 15:45:56.260   871   894 I ActivityManager: Start proc 4776:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-16 15:45:56.263   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-16 15:45:56.291  4266  4266 D BluetoothMapAppObserver: onReceive
08-16 15:45:56.292  4266  4266 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-16 15:45:56.300  2167  2285 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 15:45:56.306  1862  1862 I Keyboard.Facilitator: resetDictionaries() : en_US
08-16 15:45:56.308   871  1302 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 15:45:56.316  3702  3702 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-16 15:45:56.321  1862  4789 I Keyboard.Facilitator.DecoderInitializer: run()
08-16 15:45:56.329  1862  4789 I Decoder : createOrResetDecoder
08-16 15:45:56.358  1914  1914 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-16 15:45:56.384   871  1386 I ActivityManager: Start proc 4792:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-16 15:45:56.398   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-16 15:45:56.401  1520  1520 I ConfigService: onCreate
08-16 15:45:56.402  4486  4504 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-16 15:45:56.405  4486  4795 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-16 15:45:56.411  4792  4792 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 15:45:56.413  1520  4805 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 15:45:56.413  1520  4805 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-16 15:45:56.414  1520  4805 W SQLiteOpenHelper: Opened config.db in read-only mode
08-16 15:45:56.420  1931  2017 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-16 15:45:56.421   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-16 15:45:56.421   871   883 E PackageManager: Failed to write settings, restoring backup
08-16 15:45:56.421   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 15:45:56.421   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 15:45:56.421   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 15:45:56.421   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 15:45:56.421   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 15:45:56.421   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:45:56.421   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:45:56.421   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 15:45:56.427   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-16 15:45:56.427   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 15:45:56.427   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 15:45:56.427   871   884 E DropBoxManagerService: 	... 13 more
08-16 15:45:56.429  4486  4795 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-16 15:45:56.430  4486  4795 I Process : Sending signal. PID: 4486 SIG: 9
08-16 15:45:56.432   871   882 I ActivityManager: Start proc 4807:com.android.vending/u0a19 for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
08-16 15:45:56.448   871  1398 I ActivityManager: Start proc 4818:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-16 15:45:56.449  1931  2017 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 15:45:56.449  1931  2017 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1931
08-16 15:45:56.449  1931  2017 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 15:45:56.449  1931  2017 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 15:45:56.452   871  1933 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 15:45:56.453   871  4827 E DropBoxManagerService: Can't write: system_app_crash
08-16 15:45:56.453   871  4827 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 15:45:56.453   871  4827 E DropBoxManagerService: 	... 5 more
08-16 15:45:56.455   279   279 E lowmemorykiller: Error writing /proc/4486/oom_score_adj; errno=22
08-16 15:45:56.464   279   279 E lowmemorykiller: Error writing /proc/4486/oom_score_adj; errno=22
08-16 15:45:56.476  1931  2017 I Process : Sending signal. PID: 1931 SIG: 9
08-16 15:45:56.499  1862  4789 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-16 15:45:56.521   279   279 E lowmemorykiller: Error writing /proc/4486/oom_score_adj; errno=22
08-16 15:45:56.532  4807  4807 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
08-16 15:45:56.557  1862  4789 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-16 15:45:56.560  1862  4789 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-16 15:45:56.560  1862  4789 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-16 15:45:56.563  1862  4789 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-16 15:45:56.563  1862  4789 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-16 15:45:56.563  1862  4789 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 15:45:56.563  1862  4789 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-16 15:45:56.574   279   279 E lowmemorykiller: Error writing /proc/4486/oom_score_adj; errno=22
08-16 15:45:56.580  1862  4789 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 15:45:56.580  1862  4789 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 15:45:56.580  1862  4789 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 15:45:56.580  1862  4789 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-16 15:45:56.580  1862  4789 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 15:45:56.580  1862  4789 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-16 15:45:56.592   871  1400 I ActivityManager: Killing 4466:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
08-16 15:45:56.621   871  2162 D GraphicsStats: Buffer count: 1
08-16 15:45:56.621   871  2162 I WindowState: WIN DEATH: Window{b394f10 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-16 15:45:56.670   871  1398 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1931) has died
08-16 15:45:56.671   871  1398 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-16 15:45:56.672   871  1398 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-16 15:45:56.677   871  1936 I ActivityManager: Process android.process.acore (pid 4486) has died
08-16 15:45:56.677   871  1936 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-16 15:45:56.692   871   884 I ActivityManager: Start proc 4837:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 15:45:56.700  1740  4836 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-16 15:45:56.702  1740  4836 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-16 15:45:56.742   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
