#### Test 829140730a15ac0_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-07 13:15:57.890  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:15:57.899  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 13:15:57.901  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-07 13:15:57.930  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-07 13:15:57.931  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 13:15:57.931  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:15:57.931  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-07 13:15:57.949  3449  3449 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 13:15:57.950  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 13:15:57.951  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-07 13:15:58.535  3699  3699 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 13:15:58.540  3699  3699 D AndroidRuntime: CheckJNI is OFF
09-07 13:15:58.575  3699  3699 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 13:15:58.618  3699  3699 I Radio-JNI: register_android_hardware_Radio DONE
09-07 13:15:58.638  3699  3699 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-07 13:15:58.644   873  2043 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 13:15:58.699  2071  2087 W SearchService: Abort, client detached.
09-07 13:15:58.713  2071  2305 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@e86c3a4
09-07 13:15:58.713  2071  2071 I HotwordDetector: Closing mic
09-07 13:15:58.713  2071  2315 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-07 13:15:58.715  3699  3699 D AndroidRuntime: Shutting down VM
09-07 13:15:58.734   873   884 I ActivityManager: Start proc 3708:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-07 13:15:58.776   377  2317 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-07 13:15:58.777   377  2317 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-07 13:15:58.782   377  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-07 13:15:58.783  2071  2309 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-07 13:15:58.783  2071  2314 I MicroRecognitionRnrImpl: Detection finished
09-07 13:15:58.801  3708  3708 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-07 13:15:58.805   873  2354 D NetlinkSocketObserver: NeighborEvent{elapsedMs=119410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
09-07 13:15:58.826  3708  3708 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-07 13:15:58.837  3708  3708 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 9435-9442)
09-07 13:15:58.837  3708  3708 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 13:15:58.852  3708  3708 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27edb3f}
09-07 13:15:58.853  3708  3708 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 13:15:58.854  3708  3708 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 13:15:58.859  3708  3708 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-07 13:15:58.860  3708  3708 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 13:15:58.882  3708  3708 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-07 13:15:58.907  3708  3708 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 13:15:58.907  3708  3708 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 13:15:58.907  3708  3708 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 13:15:58.907  3708  3708 I Adreno  : Build Date                       : 10/20/15
09-07 13:15:58.907  3708  3708 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 13:15:58.907  3708  3708 I Adreno  : Local Branch                     : M14
09-07 13:15:58.907  3708  3708 I Adreno  : Remote Branch                    : 
09-07 13:15:58.907  3708  3708 I Adreno  : Remote Branch                    : 
09-07 13:15:58.907  3708  3708 I Adreno  : Reconstruct Branch               : 
,09-07 13:15:59.006   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@48d4dfd:true
,09-07 13:15:59.114  3708  3708 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 13:15:59.134  3708  3708 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-07 13:15:59.221  3708  3746 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-07 13:15:59.234  3708  3733 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-07 13:15:59.277  3708  3746 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 13:15:59.360   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +645ms
,09-07 13:15:59.364  1891  1891 I Keyboard.Facilitator: onFinishInput()
,09-07 13:15:59.475  3708  3708 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3708
,09-07 13:15:59.547   873  1704 I ActivityManager: Killing 2957:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-07 13:15:59.592   873  1704 I ActivityManager: Killing 3001:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,09-07 13:15:59.668  3708  3708 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 13:15:59.842  3708  3748 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1684014800
,09-07 13:15:59.849  3708  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 13:15:59.849  3708  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 13:15:59.849  3708  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 13:15:59.849  3708  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 13:15:59.849  3708  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 13:15:59.849  3708  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2cc393 added. We now have 1 listener(s)
,09-07 13:15:59.852  3708  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-07 13:15:59.853  3708  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 13:15:59.853  3708  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:15:59.854  3708  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-07 13:15:59.857  3708  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11162ce added. We now have 1 listener(s)
09-07 13:15:59.857  3708  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:15:59.862   873  1305 D WifiService: New client listening to asynchronous messages
,09-07 13:15:59.863  3708  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 13:15:59.864  3708  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-07 13:15:59.865  3708  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-07 13:15:59.865  3708  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 13:15:59.865  3708  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 13:15:59.870  3708  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:15:59.870  3708  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-07 13:15:59.882  3708  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:15:59.882  3708  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:15:59.882  3708  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:15:59.882  3708  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 13:15:59.882  3708  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:15:59.882  3708  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:15:59.882  3708  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:15:59.882  3708  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:15:59.882  3708  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:15:59.882  3708  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-07 13:15:59.883  3708  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:15:59.886  3708  3748 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 13:15:59.986  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:15:59.989  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:15:59.991  3708  3708 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 13:16:01.176  3708  3756 W jxcore-log: Initializing JXcore engine
,09-07 13:16:01.176  3708  3756 W jxcore-log: JXcore engine is ready
,09-07 13:16:01.209  3756  3756 W Thread-313: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-07 13:16:01.209  3756  3756 W Thread-313: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10653]" dev="sockfs" ino=10653 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 13:16:01.209  3756  3756 W Thread-313: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-07 13:16:01.209  3756  3756 W Thread-313: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26145]" dev="sockfs" ino=26145 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-07 13:16:01.223  3708  3756 W jxcore-log: Starting JXcore engine
,09-07 13:16:01.304  3708  3756 W jxcore-log: Platform android
09-07 13:16:01.304  3708  3756 W jxcore-log: 
,09-07 13:16:01.304  3708  3756 W jxcore-log: Process ARCH arm
09-07 13:16:01.304  3708  3756 W jxcore-log: 
,09-07 13:16:01.496  3708  3756 I jxcore-log: JXcore Cordova bridge is ready!
09-07 13:16:01.496  3708  3756 I jxcore-log: 
,09-07 13:16:01.496  3708  3756 W jxcore-log: JXcore engine is started
,09-07 13:16:01.503  3708  3748 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 13:16:01.508  3708  3708 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 13:16:03.564   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 13:16:03.818   873  1304 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-07 13:16:04.851  2985  3763 V KeepSync: Connecting to GoogleApiClient
09-07 13:16:04.851   873  2043 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-07 13:16:04.889  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:16:04.895  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:16:04.918  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-07 13:16:04.918  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-07 13:16:04.919  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 13:16:04.919  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:16:04.941  1687  3764 V BaseAuthAsyncOperation: access token request failed
,09-07 13:16:04.942  2985  3763 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-07 13:16:04.995  1507  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-07 13:16:04.995  1507  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-07 13:16:04.995  1507  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:16:04.995  1507  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:16:05.022  2985  3763 E KeepSync: IOException
09-07 13:16:05.022  2985  3763 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-07 13:16:05.022  2985  3763 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-07 13:16:05.022  2985  3763 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-07 13:16:05.022  2985  3763 E KeepSync: 	... 10 more
09-07 13:16:05.022  2985  3763 W KeepSync: Sync result 2
,09-07 13:16:05.028   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 125033, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-07 13:16:06.597   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 13:16:09.620   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-07 13:16:11.200  3708  3756 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 13:16:11.200  3708  3756 I jxcore-log: 
,09-07 13:16:11.203  3708  3756 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 13:16:11.203  3708  3756 I jxcore-log: 
,09-07 13:16:11.207  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:11.207  3708  3756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:11.207  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:11.207  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 13:16:11.207  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:11.207  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:11.207  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:11.207  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:11.207  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:16:11.207  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:11.208  3708  3756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:11.210  3708  3756 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 13:16:11.210  3708  3756 I jxcore-log: 
09-07 13:16:11.212  3708  3756 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 13:16:11.212  3708  3756 I jxcore-log: 
,09-07 13:16:11.706  3708  3756 D executeNativeTests: Running unit tests
,09-07 13:16:11.764  3708  3756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 13:16:11.764  3708  3756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 added. We now have 2 listener(s)
,09-07 13:16:11.765  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-07 13:16:11.765  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 13:16:11.765  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 13:16:11.765  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:11.765  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 added. We now have 2 listener(s)
09-07 13:16:11.765  3708  3756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:11.766  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 13:16:11.772  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:11.777  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:11.778  3708  3756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:11.778  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:11.778  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 13:16:11.778  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:11.778  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:11.778  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:11.778  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:11.778  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:16:11.778  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:11.778  3708  3756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 13:16:11.779  3708  3756 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 13:16:11.782  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 13:16:11.783  3708  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 13:16:11.783  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:11.784  3708  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 13:16:11.785  3708  3756 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 13:16:11.785  3708  3756 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 13:16:11.785  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 13:16:11.785  3708  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 13:16:11.786  3708  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 13:16:11.786  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.786  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 13:16:11.786  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.787  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.787  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.787  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:11.787  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 13:16:11.787  3708  3756 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 removed from the list
09-07 13:16:11.787  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.787  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 removed from the list
09-07 13:16:11.793  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:11.793  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.793  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.793  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.793  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.794  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.794  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.794  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:11.794  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.797  3708  3756 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 13:16:11.797  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.797  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.797  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.798  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.798  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.798  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.798  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.798  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.798  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.798  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.798  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.798  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.798  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.798  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.799  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.799  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.799  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:11.799  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
,09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 13:16:11.805  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110],
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 13:16:11.806  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 13:16:11.807  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-07 13:16:11.807  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.807  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.807  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:16:11.807  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.807  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.807  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.807  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.808  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:11.808  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.808  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.808  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.808  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.808  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.808  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:11.808  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.809  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.809  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 13:16:11.809  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.809  3708  3756 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 13:16:11.811  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:11.812  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:11.812  3708  3756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:11.812  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:11.812  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 13:16:11.812  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:11.812  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:11.812  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:11.812  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:11.812  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:16:11.812  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:11.812  3708  3756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:11.812  3708  3756 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:16:11.812  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:16:11.813  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 13:16:11.813  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:16:11.813  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:11.813  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 13:16:11.822  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,09-07 13:16:11.823  3708  3756 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 13:16:11.822  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:11.825  3708  3756 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-07 13:16:11.825  3708  3756 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 13:16:11.826  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:11.826  3708  3756 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,09-07 13:16:11.827  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:11.827  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:11.827  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 13:16:11.827  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 13:16:11.827  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.827  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 13:16:11.827  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 13:16:11.827  3708  3708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 13:16:11.827  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 13:16:11.827  3708  3756 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 13:16:11.827  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 13:16:11.828  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 13:16:11.828  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:11.829  3708  3756 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:11.829  3708  3708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 13:16:11.829  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 13:16:11.829  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.829  3708  3708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:11.829  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:11.829  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.830  3708  3708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:11.830  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.830  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.830  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.830  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:11.830  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.830  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.831  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:16:11.831  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.831  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.831  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.832  3708  3756 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 13:16:11.834  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:11.837  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:11.837  3708  3756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:11.837  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:11.837  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 13:16:11.837  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:11.837  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:11.837  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:11.837  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:11.837  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:16:11.838  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:11.838  3708  3756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 13:16:11.838  3708  3756 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 13:16:11.838  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 13:16:11.838  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 13:16:11.838  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 13:16:11.838  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:16:11.838  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 13:16:11.840  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:11.842  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:11.842  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
09-07 13:16:11.843  3708  3756 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,09-07 13:16:11.843  3708  3756 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 13:16:11.843  3708  3708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
09-07 13:16:11.843  3708  3756 I io.jxcore.node.ConnectionHelper: start: OK
09-07 13:16:11.843  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.844  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 13:16:11.844  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 13:16:11.844  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.844  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 13:16:11.845  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 13:16:11.845  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 13:16:11.845  3708  3756 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 13:16:11.845  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 13:16:11.845  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 13:16:11.846  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 13:16:11.847  3708  3756 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:11.848  3708  3708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:11.848  3708  3708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 13:16:11.848  3708  3708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:11.848  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-07 13:16:11.848  3708  3756 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 13:16:11.848  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.848  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.848  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.849  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.849  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 13:16:11.849  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.849  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.849  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
,09-07 13:16:11.850  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.850  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.851  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.851  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.852  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:16:11.852  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.852  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.852  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
,09-07 13:16:11.853  3708  3756 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 13:16:11.855  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.855  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.855  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.855  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.856  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.856  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:11.856  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.862  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:11.863  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.863  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.863  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.863  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.863  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.863  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:11.864  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.864  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 13:16:11.865  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.865  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.866  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-07 13:16:11.866  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.866  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.866  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.866  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 13:16:11.866  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.866  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.866  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.866  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:11.867  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.867  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.867  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.867  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.867  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.867  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:11.868  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.868  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.868  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.868  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.868  3708  3756 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 13:16:11.868  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:11.869  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.869  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.869  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.869  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.869  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.869  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.869  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.869  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.869  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.869  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.869  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.869  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.869  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:11.870  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.870  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.870  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.870  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.870  3708  3756 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 13:16:11.870  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:11.871  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.871  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.871  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.871  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.871  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.871  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.871  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:11.871  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.871  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 13:16:11.871  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.871  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.871  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.871  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:11.871  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.872  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.872  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.872  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
,09-07 13:16:11.872  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 13:16:11.873  3708  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 13:16:11.873  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 13:16:11.873  3708  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 13:16:11.874  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 13:16:11.874  3708  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 13:16:11.874  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.874  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.874  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:16:11.874  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.874  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.874  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.874  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.874  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:11.874  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.875  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.875  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.875  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.875  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.875  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.875  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.875  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.875  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.875  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
,09-07 13:16:11.876  3708  3756 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:16:11.876  3708  3756 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 13:16:11.876  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 13:16:11.880  3708  3756 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 13:16:11.880  3708  3756 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-07 13:16:11.880  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 13:16:11.880  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 13:16:11.880  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 13:16:11.880  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 13:16:11.880  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-07 13:16:11.880  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 13:16:11.880  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 13:16:11.880  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 13:16:11.880  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-07 13:16:11.881  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 13:16:11.881  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 13:16:11.881  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010],
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
09-07 13:16:11.882  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 13:16:11.882  3708  3756 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 13:16:11.883  3708  3756 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-07 13:16:11.883  3708  3756 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 13:16:11.883  3708  3756 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 13:16:11.883  3708  3756 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 13:16:11.883  3708  3756 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 13:16:11.883  3708  3756 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 13:16:11.883  3708  3756 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 13:16:11.883  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 13:16:11.884  3708  3756 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
09-07 13:16:11.885  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55,
09-07 13:16:11.885  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 13:16:11.885  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-07 13:16:11.886  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 13:16:11.886  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 13:16:11.886  3708  3756 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-07 13:16:11.886  3708  3756 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 13:16:11.887  3708  3756 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 13:16:11.887  3708  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 377)
,09-07 13:16:11.887  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.887  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.887  3708  3769 E BluetoothDevice: Bluetooth is not enabled
09-07 13:16:11.887  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.887  3708  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 377)
,09-07 13:16:11.887  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.887  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.887  3708  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 377)
09-07 13:16:11.887  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.888  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-07 13:16:11.888  3708  3769 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 377)
09-07 13:16:11.888  3708  3708 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
09-07 13:16:11.889  3708  3708 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
09-07 13:16:11.889  3708  3708 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 13:16:11.889  3708  3708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 13:16:11.889  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.889  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.889  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.889  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.889  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.889  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:11.890  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.890  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.890  3708  3770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 377
09-07 13:16:11.890  3708  3769 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Failed to find a thread with ID 377
09-07 13:16:11.890  3708  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 377)
09-07 13:16:11.890  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:16:11.890  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.890  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.890  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.891  3708  3756 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-07 13:16:11.891  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.891  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.891  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.895  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 13:16:11.895  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.895  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.895  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.895  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.895  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
,09-07 13:16:11.895  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.895  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.895  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.895  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.896  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.896  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:16:11.896  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.896  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.896  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.897  3708  3756 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 13:16:11.898  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.898  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 13:16:11.898  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:16:11.898  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.899  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.899  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.899  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.899  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.899  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.899  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.899  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.899  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.900  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.900  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.900  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:16:11.900  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.900  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.901  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.902  3708  3756 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 13:16:11.902  3708  3756 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 13:16:11.903  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 13:16:11.903  3708  3756 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 13:16:11.903  3708  3756 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 13:16:11.903  3708  3756 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 13:16:11.903  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 13:16:11.903  3708  3756 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,09-07 13:16:11.903  3708  3756 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 13:16:11.904  3708  3756 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 13:16:11.904  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 13:16:11.904  3708  3756 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 13:16:11.904  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.904  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.904  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.904  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.905  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.905  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.905  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
,09-07 13:16:11.905  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.905  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.905  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.905  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.905  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.905  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.905  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.906  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.906  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.906  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.907  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
,09-07 13:16:11.907  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.908  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.908  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.908  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.908  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.908  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.908  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.908  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.908  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.909  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.909  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.909  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 13:16:11.909  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.909  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.909  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.910  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.910  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.910  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.910  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.910  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.910  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.910  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.910  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.911  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.911  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.911  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.911  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.911  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.911  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.912  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.912  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.912  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.912  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.914  3708  3756 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-07 13:16:11.914  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 13:16:11.915  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
09-07 13:16:11.915  3708  3756 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
09-07 13:16:11.915  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 13:16:11.915  3708  3708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
,09-07 13:16:11.916  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.916  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 13:16:11.916  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.916  3708  3756 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
09-07 13:16:11.916  3708  3708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 13:16:11.916  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.916  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.916  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 13:16:11.916  3708  3756 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 13:16:11.917  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 13:16:11.917  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.917  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:11.917  3708  3756 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:11.918  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.918  3708  3708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 13:16:11.918  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.918  3708  3708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 13:16:11.918  3708  3708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 13:16:11.918  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.918  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.918  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.918  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.919  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.919  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.919  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.919  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.919  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.919  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.919  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.919  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.919  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:11.920  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.920  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.920  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 13:16:11.921  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.922  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 13:16:11.924  3708  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 13:16:11.924  3708  3756 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-07 13:16:11.925  3708  3756 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-07 13:16:11.925  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 13:16:11.926  3708  3756 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 13:16:11.926  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:11.926  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 13:16:11.926  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.926  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.927  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.928  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.928  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
09-07 13:16:11.928  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.928  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.928  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.928  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.928  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.928  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.928  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.929  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.929  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.929  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.929  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
,09-07 13:16:11.931  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 13:16:11.931  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.931  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 13:16:11.931  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.931  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.931  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.931  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
,09-07 13:16:11.931  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.931  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
,09-07 13:16:11.931  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.931  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.931  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.931  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 13:16:11.931  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.932  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 13:16:11.932  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.932  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.932  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
,09-07 13:16:11.932  3708  3756 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 13:16:11.932  3708  3756 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 13:16:11.932  3708  3756 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 13:16:11.932  3708  3756 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 13:16:11.933  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.933  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.933  3708  3756 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b930fa3 not in the list
,09-07 13:16:11.933  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.933  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.933  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
09-07 13:16:11.933  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.933  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.933  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 13:16:11.933  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 13:16:11.933  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 13:16:11.933  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 13:16:11.933  3708  3756 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 13:16:11.933  3708  3756 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@77382a0 not in the list
09-07 13:16:11.934  3708  3756 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 13:16:11.934  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 13:16:11.934  3708  3756 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 13:16:11.934  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 13:16:11.934  3708  3756 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-07 13:16:11.935  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 13:16:11.936  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 13:16:11.936  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 13:16:11.936  3708  3756 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 13:16:11.937  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 13:16:11.937  3708  3756 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 13:16:11.937  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-07 13:16:11.937  3708  3756 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 13:16:11.937  3708  3756 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 13:16:11.937  3708  3756 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 13:16:11.937  3708  3756 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 13:16:11.938  3708  3756 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 13:16:11.938  3708  3756 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 13:16:11.938  3708  3756 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-07 13:16:11.938  3708  3756 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 13:16:11.938  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:11.939  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@45d8a2a added. We now have 2 listener(s)
09-07 13:16:11.939  3708  3756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:11.940   873  2044 D WifiService: setWifiEnabled: true pid=3708, uid=10000
09-07 13:16:11.940   873  2044 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-07 13:16:11.940  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:11.940  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@268d01b added. We now have 3 listener(s)
,09-07 13:16:11.940  3708  3756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:11.942  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:11.942  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:11.943  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 13:16:11.944  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5eb05b8 added. We now have 4 listener(s)
,09-07 13:16:11.944  3708  3756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:11.945  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-07 13:16:11.946  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@51faf91 added. We now have 5 listener(s)
,09-07 13:16:11.946  3708  3756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:11.947   873   884 D WifiService: setWifiEnabled: false pid=3708, uid=10000
,09-07 13:16:11.947   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 13:16:11.956   873   890 I ActivityManager: Start proc 3772:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 13:16:11.958  3708  3756 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 13:16:11.960  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:11.960  3708  3756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 13:16:11.960  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:11.960  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 13:16:11.960  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:11.960  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:11.960  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:11.960  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:11.960  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 13:16:11.960  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:11.960  3708  3756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:11.960  3708  3756 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 13:16:11.962  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:11.963  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:11.966  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 13:16:11.967   873  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 13:16:11.967   873  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 13:16:11.967   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 13:16:11.968   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 13:16:11.976   873  2358 D DhcpClient: Clearing IP address
09-07 13:16:11.977   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 13:16:11.980   373   872 D CommandListener: Setting iface cfg
,09-07 13:16:11.982  1507  2568 V NativeCrypto: Read error: ssl=0x9ade7400: I/O error during system call, Connection timed out
09-07 13:16:11.983  1507  2568 V NativeCrypto: SSL shutdown failed: ssl=0x9ade7400: I/O error during system call, Broken pipe
09-07 13:16:11.985   873   883 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
09-07 13:16:11.985   873  2353 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-07 13:16:11.987   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-07 13:16:11.987   873  2353 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-07 13:16:11.987   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-07 13:16:11.991   396   396 E Parcel  : Reading a NULL string not supported here.
09-07 13:16:11.992   873  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
09-07 13:16:11.993   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 13:16:11.995   873  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-07 13:16:11.995   373   872 D CommandListener: Clearing all IP addresses on wlan0
,09-07 13:16:12.000   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 13:16:12.001   873  2360 D DhcpClient: Receive thread stopped
09-07 13:16:12.002   873  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 13:16:12.003  3708  3708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:12.003  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:12.003  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:12.003  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 13:16:12.003  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:12.003  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:12.003  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:12.003  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:12.003  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:16:12.004  3708  3708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:12.004  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:12.004  3708  3708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:12.004  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:12.004  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:12.004  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
09-07 13:16:12.004  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:12.004  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:12.004  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:12.004  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:12.004  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:16:12.004  3708  3708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:12.004  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:12.007  1855  2279 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:16:12.032   873  2042 I ActivityManager: Start proc 3787:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-07 13:16:12.042   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 13:16:12.063  3772  3772 D AdapterServiceConfig: Adding HeadsetService
,09-07 13:16:12.063  3772  3772 D AdapterServiceConfig: Adding A2dpService
09-07 13:16:12.064  3772  3772 D AdapterServiceConfig: Adding HidService
09-07 13:16:12.064  3772  3772 D AdapterServiceConfig: Adding HealthService
,09-07 13:16:12.064  3772  3772 D AdapterServiceConfig: Adding PanService
09-07 13:16:12.064  3772  3772 D AdapterServiceConfig: Adding GattService
09-07 13:16:12.064  3772  3772 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 13:16:12.068   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 13:16:12.069   873  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-07 13:16:12.069   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:12.073   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-07 13:16:12.074  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:12.074  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:12.078  3358  3358 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b812b91 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-07 13:16:12.089  3787  3787 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-07 13:16:12.094   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c27e2c8:true
,09-07 13:16:12.094  3772  3772 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 13:16:12.097  3772  3772 I bt_bluedroid: init
09-07 13:16:12.097  3772  3804 I BluetoothAdapterState: Entering OffState
,09-07 13:16:12.099  3772  3805 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 13:16:12.100  3772  3805 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-07 13:16:12.100  3772  3805 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-07 13:16:12.100  3772  3805 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-07 13:16:12.102  3772  3772 I bt_bluedroid: get_profile_interface socket
,09-07 13:16:12.103  3772  3772 I bt_bluedroid: get_profile_interface sdp
,09-07 13:16:12.105  3772  3809 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 13:16:12.105  3772  3783 I bt_bluedroid: config_hci_snoop_log
,09-07 13:16:12.106  3772  3809 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 13:16:12.106   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,09-07 13:16:12.109  3772  3804 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 13:16:12.109  3772  3804 D BluetoothAdapterProperties: Setting state to 14
09-07 13:16:12.109  3772  3804 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-07 13:16:12.111  3772  3804 D BluetoothBondStateMachine: make
,09-07 13:16:12.112  3772  3811 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 13:16:12.116  3772  3804 I BluetoothAdapterState: Entering PendingCommandState
,09-07 13:16:12.116  3772  3772 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 13:16:12.118  3772  3772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:12.119  3772  3772 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 13:16:12.119  3772  3772 D BtGatt.GattService: Received start request. Starting profile...
09-07 13:16:12.119  3772  3772 D BtGatt.GattService: start()
09-07 13:16:12.119  3772  3772 I bt_bluedroid: get_profile_interface gatt
,09-07 13:16:12.120  3772  3772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:12.120  3772  3772 D BtGatt.AdvertiseManager: advertise manager created
,09-07 13:16:12.125  3772  3772 V BluetoothAdapterState: isTurningOff()=false
,09-07 13:16:12.125  3772  3772 V BluetoothAdapterState: isTurningOn()=false
09-07 13:16:12.125  3772  3772 V BluetoothAdapterState: isBleTurningOn()=true
,09-07 13:16:12.125  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:12.125  3772  3804 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 13:16:12.125  3772  3804 I bt_bluedroid: enable
,09-07 13:16:12.125  3772  3805 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-07 13:16:12.126  3772  3805 I bt_hci  : start_up
,09-07 13:16:12.133  3772  3805 I bt_vendor: alloc value 0xb39f9189
,09-07 13:16:12.133  3772  3805 I bt_vendor: init
,09-07 13:16:12.133  3772  3805 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 13:16:12.133  3772  3805 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 13:16:12.137   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 13:16:12.138   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-07 13:16:12.144  3787  3787 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-07 13:16:12.159  1687  1687 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-07 13:16:12.165  1687  1687 D SystemUpdateService: onCreate
,09-07 13:16:12.168  1687  1687 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 13:16:12.180  1687  1687 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 13:16:12.182  1687  2545 I iu.UploadsManager: num queued entries: 0
,09-07 13:16:12.182  1687  2545 I iu.UploadsManager: num updated entries: 0
,09-07 13:16:12.183  1687  2545 I iu.SyncManager: NEXT; no task
,09-07 13:16:12.187  1687  3826 I SystemUpdateService: active receiver: enabled
,09-07 13:16:12.190  1687  1687 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 13:16:12.191  1687  1687 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 13:16:12.193  1687  3826 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 13:16:12.195  1687  3826 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-07 13:16:12.195  1687  3826 I SystemUpdateService: now status is 0 (complete)
,09-07 13:16:12.195  1687  3826 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 13:16:12.195  1687  3826 I SystemUpdateService: file has been verified
09-07 13:16:12.195  1687  3826 I SystemUpdateService: OTA package size = 12249756
,09-07 13:16:12.200  1687  3826 I SystemUpdateService: showing system update notification
,09-07 13:16:12.205   873  2039 I ActivityManager: Start proc 3828:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-07 13:16:12.238  1687  1687 D SystemUpdateService: onDestroy
09-07 13:16:12.238  3772  3805 D bt_hci  : start_up starting async portion
,09-07 13:16:12.239  3772  3821 I bt_hci  : event_finish_startup
09-07 13:16:12.239  3772  3821 I bt_hci_h4: hal_open
09-07 13:16:12.239  3772  3821 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-07 13:16:12.240   873   884 I ActivityManager: Killing 3180:com.google.android.gm/u0a78 (adj 15): empty #17
,09-07 13:16:12.245  3772  3821 I bt_userial_vendor: device fd = 51 open
,09-07 13:16:12.258  3828  3828 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
09-07 13:16:12.263  3828  3828 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:12.271  3828  3828 D SprintDMHelper: simOperator: 
09-07 13:16:12.271  3828  3828 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 13:16:12.282  3772  3821 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 13:16:12.313  3772  3821 D bt_hwcfg: Chipset BCM4354A2
09-07 13:16:12.314  3772  3821 D bt_hwcfg: Target name = [BCM4354A2]
,09-07 13:16:12.314  3772  3821 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 13:16:12.336   873   884 I ActivityManager: Start proc 3841:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-07 13:16:12.337   873   884 I ActivityManager: Killing 3358:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-07 13:16:12.418  3708  3708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 13:16:12.488   873  2003 I ActivityManager: Start proc 3856:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-07 13:16:12.495   873  2003 I ActivityManager: Killing 2760:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-07 13:16:12.562  3856  3856 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-07 13:16:12.633  3856  3856 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 13:16:12.633  3856  3856 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 13:16:12.633  3856  3856 I GAv4    :   adb logcat -s GAv4
,09-07 13:16:12.647  3856  3856 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 13:16:12.656  3856  3856 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 13:16:12.693  3856  3873 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 13:16:12.819  3856  3856 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-07 13:16:12.846  3772  3821 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 13:16:12.847  3772  3821 D bt_hwcfg: Settlement delay -- 100 ms
09-07 13:16:12.847  3772  3821 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 13:16:12.866  3856  3856 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-07 13:16:12.874  3856  3856 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3476-3479)
,09-07 13:16:12.874  3856  3856 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 13:16:12.883  3856  3856 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35db783}
,09-07 13:16:12.884  3856  3856 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-07 13:16:12.884  3856  3856 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 13:16:12.893  3856  3856 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 13:16:12.894  3856  3856 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-07 13:16:12.913  3856  3856 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 13:16:12.929  3856  3856 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 13:16:12.929  3856  3856 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 13:16:12.929  3856  3856 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 13:16:12.929  3856  3856 I Adreno  : Build Date                       : 10/20/15
09-07 13:16:12.929  3856  3856 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 13:16:12.929  3856  3856 I Adreno  : Local Branch                     : M14
09-07 13:16:12.929  3856  3856 I Adreno  : Remote Branch                    : 
09-07 13:16:12.929  3856  3856 I Adreno  : Remote Branch                    : 
09-07 13:16:12.929  3856  3856 I Adreno  : Reconstruct Branch               : 
,09-07 13:16:12.963  3772  3821 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 13:16:12.965  3772  3821 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 13:16:12.992  3856  3856 I NSApplication: Starting up...
09-07 13:16:12.996  3772  3821 I bt_hwcfg: vendor lib fwcfg completed
09-07 13:16:12.996  3772  3821 I bt_vendor: firmware callback
09-07 13:16:12.996  3772  3821 I bt_hci  : firmware_config_callback
,09-07 13:16:13.010  3856  3902 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-07 13:16:13.046   873  2043 I ActivityManager: Start proc 3907:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-07 13:16:13.050   873  2043 I ActivityManager: Killing 3072:android.process.acore/u0a5 (adj 15): empty #17
,09-07 13:16:13.091  3772  3919 I bt_btu  : btu_task pending for preload complete event
09-07 13:16:13.091  3772  3919 I bt_btu_task: Bluetooth chip preload is complete
,09-07 13:16:13.091  3772  3919 I bt_btu  : btu_task received preload complete event
09-07 13:16:13.093  3772  3919 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 13:16:13.093  3772  3919 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 13:16:13.093  3772  3919 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 13:16:13.093  3772  3919 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 13:16:13.093  3772  3919 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 13:16:13.093  3772  3919 I         : BTE_InitTraceLevels -- TRC_A2D
,09-07 13:16:13.094  3772  3919 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 13:16:13.094  3772  3919 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 13:16:13.094  3772  3919 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 13:16:13.094  3772  3919 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 13:16:13.094  3772  3919 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 13:16:13.094  3772  3919 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 13:16:13.094  3772  3919 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 13:16:13.094  3772  3919 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-07 13:16:13.094  3772  3919 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 13:16:13.117  3907  3907 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-07 13:16:13.216  3772  3919 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,09-07 13:16:13.217  3772  3919 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,09-07 13:16:13.225  3772  3809 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 13:16:13.228  3772  3809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-07 13:16:13.228  3772  3809 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 13:16:13.232  3772  3809 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 13:16:13.236  3772  3809 D BluetoothAdapterProperties: Scan Mode:20
,09-07 13:16:13.237  3772  3809 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 13:16:13.238  3772  3809 D bt_hci  : do_postload posting postload work item
,09-07 13:16:13.238  3772  3821 I bt_hci  : event_postload
09-07 13:16:13.238  3772  3821 I bt_vendor: sco_config_cb
09-07 13:16:13.238  3772  3821 I bt_hci  : sco_config_callback postload finished.
09-07 13:16:13.239  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:13.243  3772  3821 I bt_vendor: low_power_mode_cb
,09-07 13:16:13.244  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:13.245  3772  3809 D bt_bte_conf: Device ID record 1 : primary
09-07 13:16:13.245  3772  3809 D bt_bte_conf:   vendorId            = 000f
09-07 13:16:13.245  3772  3809 D bt_bte_conf:   vendorIdSource      = 0001
09-07 13:16:13.245  3772  3809 D bt_bte_conf:   product             = 1200
09-07 13:16:13.246  3772  3809 D bt_bte_conf:   version             = 1436
09-07 13:16:13.246  3772  3809 D bt_bte_conf:   clientExecutableURL = 
09-07 13:16:13.246  3772  3809 D bt_bte_conf:   serviceDescription  = 
09-07 13:16:13.246  3772  3809 D bt_bte_conf:   documentationURL    = 
09-07 13:16:13.246  3772  3809 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-07 13:16:13.246  3772  3805 D bt_stack_manager: event_start_up_stack finished
09-07 13:16:13.247  3772  3804 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-07 13:16:13.247  3772  3804 D BluetoothAdapterProperties: Setting state to 15
09-07 13:16:13.247  3772  3804 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-07 13:16:13.248  3772  3804 I BluetoothAdapterState: Entering BleOnState
,09-07 13:16:13.250  3772  3804 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-07 13:16:13.250  3772  3804 D BluetoothAdapterProperties: Setting state to 11
09-07 13:16:13.250  3772  3804 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 13:16:13.254  3772  3772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:13.255  3772  3772 D HeadsetService: Received start request. Starting profile...
,09-07 13:16:13.257  3772  3772 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 13:16:13.258  3772  3772 D HeadsetStateMachine: make
,09-07 13:16:13.265  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:13.269  3772  3772 D HeadsetStateMachine: max_hf_connections = 1
09-07 13:16:13.269  3772  3772 I bt_bluedroid: get_profile_interface handsfree
09-07 13:16:13.269  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:13.270  3772  3809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 13:16:13.270  3772  3809 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-07 13:16:13.273  3772  3804 I BluetoothAdapterState: Entering PendingCommandState
09-07 13:16:13.275  3772  3772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:13.275   873   873 D BluetoothA2dp: Proxy object connected
09-07 13:16:13.276  3772  3772 D A2dpService: Received start request. Starting profile...
09-07 13:16:13.276  3772  3772 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-07 13:16:13.277  3772  3772 I bt_bluedroid: get_profile_interface avrcp
09-07 13:16:13.283  3772  3772 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-07 13:16:13.283  3772  3772 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 13:16:13.283  3772  3772 D A2dpStateMachine: make
,09-07 13:16:13.284  3772  3772 I bt_bluedroid: get_profile_interface a2dp
,09-07 13:16:13.285  3772  3809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 13:16:13.289  3772  3928 D A2dpStateMachine: Enter Disconnected: -2
,09-07 13:16:13.289  3772  3772 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 13:16:13.290  3772  3772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:13.291  1361  1361 D BluetoothInputDevice: Proxy object connected
,09-07 13:16:13.291  3772  3772 D HidService: Received start request. Starting profile...
09-07 13:16:13.291  3772  3772 I bt_bluedroid: get_profile_interface hidhost
,09-07 13:16:13.292  3772  3809 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
09-07 13:16:13.292  1361  1361 D HidProfile: Bluetooth service connected
09-07 13:16:13.292  3772  3809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-07 13:16:13.292  3772  3772 D HidService: setHidService(): set to: null
,09-07 13:16:13.294  3772  3772 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 13:16:13.295  3772  3772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:13.296  3772  3772 D HealthService: Received start request. Starting profile...
,09-07 13:16:13.297  3772  3772 I bt_bluedroid: get_profile_interface health
,09-07 13:16:13.298  3772  3772 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 13:16:13.298  3772  3772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:13.299   873  1704 I ActivityManager: Killing 3565:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-07 13:16:13.339  3772  3772 D PanService: Received start request. Starting profile...
,09-07 13:16:13.339  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 13:16:13.339  3772  3772 D BluetoothPanServiceJni: initializeNative(L110): pan,
,09-07 13:16:13.339  3772  3772 I bt_bluedroid: get_profile_interface pan
,09-07 13:16:13.340  3772  3809 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 13:16:13.342  1361  1361 D PanProfile: Bluetooth service connected
,09-07 13:16:13.349  3772  3772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
09-07 13:16:13.350   873  2011 I ActivityManager: Start proc 3933:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-07 13:16:13.352  1361  1361 D BluetoothMap: Proxy object connected
,09-07 13:16:13.353  1361  1361 D MapProfile: Bluetooth service connected
,09-07 13:16:13.353  1361  1361 D BluetoothMap: getConnectedDevices()
,09-07 13:16:13.355  3772  3772 D BluetoothMapService: Received start request. Starting profile...
,09-07 13:16:13.355  3772  3772 D BluetoothMapService: start()
,09-07 13:16:13.356  1361  1361 D BluetoothMap: Bluetooth is Not enabled
,09-07 13:16:13.357  3772  3772 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 13:16:13.358  3772  3772 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-07 13:16:13.359  3772  3772 D BluetoothMapAppObserver: createReceiver(),
09-07 13:16:13.360  3772  3772 D BluetoothMapAppObserver: initObservers()
,09-07 13:16:13.360  3772  3772 D BluetoothMapAppObserver: getEnabledAccountItems(),
09-07 13:16:13.365  3772  3772 V BluetoothAdapterState: isTurningOff()=false
,09-07 13:16:13.365  3772  3772 V BluetoothAdapterState: isTurningOn()=true
,09-07 13:16:13.365  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:13.365  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:13.367  3772  3925 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 13:16:13.368  3772  3772 V BluetoothAdapterState: isTurningOff()=false
09-07 13:16:13.368  3772  3772 V BluetoothAdapterState: isTurningOn()=true
,09-07 13:16:13.369  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:13.369  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:13.370  3772  3772 V BluetoothAdapterState: isTurningOff()=false
09-07 13:16:13.370  3772  3772 V BluetoothAdapterState: isTurningOn()=true
09-07 13:16:13.370  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:13.371  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:13.371  3772  3772 V BluetoothAdapterState: isTurningOff()=false
,09-07 13:16:13.371  3772  3772 V BluetoothAdapterState: isTurningOn()=true
09-07 13:16:13.371  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:13.371  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 13:16:13.372  3772  3772 V BluetoothAdapterState: isTurningOff()=false
,09-07 13:16:13.373  3772  3772 V BluetoothAdapterState: isTurningOn()=true
09-07 13:16:13.373  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:13.373  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:13.374  3772  3772 V BluetoothAdapterState: isTurningOff()=false
09-07 13:16:13.374  3772  3772 V BluetoothAdapterState: isTurningOn()=true
09-07 13:16:13.374  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:13.374  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:13.374  3772  3804 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 13:16:13.375  3772  3804 D BluetoothAdapterProperties: ScanMode =  20
09-07 13:16:13.375  3772  3804 D BluetoothAdapterProperties: State =  11
,09-07 13:16:13.377  3772  3809 D BluetoothAdapterProperties: Scan Mode:21
09-07 13:16:13.377  3772  3809 D BluetoothAdapterProperties: Discoverable Timeout:120
09-07 13:16:13.377  3772  3804 D BluetoothAdapterProperties: Setting state to 12
09-07 13:16:13.377  3772  3804 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 13:16:13.378   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 13:16:13.379  3772  3804 I BluetoothAdapterState: Entering OnState
,09-07 13:16:13.381   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 13:16:13.382  1361  1374 D BluetoothPan: onBluetoothStateChange on: true
,09-07 13:16:13.382  1361  1373 D BluetoothMap: onBluetoothStateChange: up=true
09-07 13:16:13.383  1361  1678 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 13:16:13.383  1361  2096 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 13:16:13.385  3772  3772 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-07 13:16:13.386  3772  3772 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-07 13:16:13.387  3772  3772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:16:13.387  1988  2001 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 13:16:13.388  3708  3708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage,
,09-07 13:16:13.388   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:16:13.388   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 13:16:13.390   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 13:16:13.390  3708  3708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-07 13:16:13.391  3772  3772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:16:13.393  3772  3772 D ObexServerSockets: Succeed to create listening sockets 
,09-07 13:16:13.393  3772  3772 D ObexServerSockets0: startAccept()
,09-07 13:16:13.393  3772  3772 D ObexServerSockets0: prepareForNewConnect()
09-07 13:16:13.395  3708  3708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-07 13:16:13.396  3772  3772 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-07 13:16:13.396  3772  3772 D BluetoothSdpJni: SDP Create record success - handle: 0
09-07 13:16:13.399  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:13.399  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:13.399  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:13.399  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:13.399  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:13.399  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:13.399  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:13.399  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:16:13.400  3772  3946 D ObexServerSockets0: Accepting socket connection...
09-07 13:16:13.400  3772  3772 D BluetoothMapService: onReceive
09-07 13:16:13.400  3772  3772 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:13.400  3772  3772 D BluetoothMapService: STATE_ON
09-07 13:16:13.399  3772  3947 D ObexServerSockets0: Accepting socket connection...
09-07 13:16:13.401  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:13.403  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:13.403  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:13.403  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:13.403  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:13.403  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:13.403  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:13.403  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:13.403  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:13.405  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:13.406  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:13.408  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:13.414  1361  1648 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-07 13:16:13.418  1361  1648 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-07 13:16:13.418  1361  1361 D BluetoothA2dp: Proxy object connected
,09-07 13:16:13.421  3772  3772 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 13:16:13.421  3772  3772 D ObexServerSockets0: prepareForNewConnect()
,09-07 13:16:13.423  3933  3933 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-07 13:16:13.430   873  2003 I ActivityManager: Killing 3582:com.android.musicfx/u0a18 (adj 15): empty #17
,09-07 13:16:13.470  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 13:16:13.483   873   890 D BluetoothHeadset: Proxy object connected
,09-07 13:16:13.485   873   890 D BluetoothHeadset: Proxy object connected
,09-07 13:16:13.489  1988  2091 D BluetoothHeadset: Proxy object connected
,09-07 13:16:13.492   873   890 D BluetoothHeadset: Proxy object connected
,09-07 13:16:13.497   873  2042 I ActivityManager: Start proc 3949:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-07 13:16:13.520  1361  1374 D BluetoothHeadset: Proxy object connected
,09-07 13:16:13.521  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-07 13:16:13.545  3949  3949 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-07 13:16:13.713  3949  3949 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 13:16:13.713  3949  3949 D StrictMode: 	,at java.io.File.doAccess(File.java:281)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-07 13:16:13.713  3949  3949 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 13:16:13.713  3949  3949 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 13:16:13.713  3949  3949 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 13:16:13.713  3949  3949 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.k.d(PG:583)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.e.b(PG:170)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 13:16:13.713  3949  3949 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 13:16:13.713  3949  3949 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.io.File.exists(File.java:361)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:16:13.713  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 13:16:13.714  3949  3949 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-07 13:16:13.714  3949  3949 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:16:13.714  3949  3949 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 13:16:13.742  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onRecei,ve:115 
09-07 13:16:13.754   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec15aef:true
,09-07 13:16:13.759  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:16:13.775  1361  1361 D BluetoothPbap: Proxy object connected
09-07 13:16:13.776  1361  1361 D PbapServerProfile: Bluetooth service connected
09-07 13:16:13.789  3933  3933 D LocalBluetoothProfileManager: Adding local A2DP profile
09-07 13:16:13.789  3772  3976 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:16:13.796  3933  3933 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-07 13:16:13.820  3933  3933 D LocalBluetoothProfileManager: Adding local MAP profile
,09-07 13:16:13.821  3933  3933 D BluetoothMap: Create BluetoothMap proxy object
,09-07 13:16:13.831  3933  3933 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-07 13:16:13.832  3772  3984 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:16:13.833  3772  3984 I BtOppRfcommListener: Accept thread started.
,09-07 13:16:13.841  3933  3933 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:13.842  3933  3933 D BluetoothA2dp: Proxy object connected
,09-07 13:16:13.846  3933  3933 D BluetoothInputDevice: Proxy object connected
,09-07 13:16:13.846  3933  3933 D HidProfile: Bluetooth service connected
,09-07 13:16:13.852  3933  3933 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 13:16:13.852  3933  3933 D PanProfile: Bluetooth service connected
09-07 13:16:13.853  3933  3933 D BluetoothMap: Proxy object connected
09-07 13:16:13.853  3933  3933 D MapProfile: Bluetooth service connected
09-07 13:16:13.853  3933  3933 D BluetoothMap: getConnectedDevices()
,09-07 13:16:13.858  3933  3933 D BluetoothPbap: Proxy object connected
,09-07 13:16:13.858  3933  3933 D PbapServerProfile: Bluetooth service connected
,09-07 13:16:13.875   873  1706 I ActivityManager: Killing 3409:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-07 13:16:13.898  3933  3944 D BluetoothHeadset: Proxy object connected
,09-07 13:16:13.899  3933  3933 D HeadsetProfile: Bluetooth service connected
,09-07 13:16:14.032  3949  3972 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 13:16:14.048   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c096eb:true
,09-07 13:16:14.965   873   884 D WifiService: setWifiEnabled: true pid=3708, uid=10000
,09-07 13:16:14.965   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 13:16:14.977   873  1304 D WifiConfigStore: Loading config and enabling all networks 
,09-07 13:16:14.995  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:14.995  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:14.995  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:14.995  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:14.995  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:14.995  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:14.995  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:14.995  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:15.002  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:15.013   873  1304 D WifiConfigStore: loaded 0 passpoint configs
,09-07 13:16:15.014  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:15.014  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:15.014  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:15.014  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:15.014  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:15.014  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:15.014  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:15.014  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:16:15.014   873  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-07 13:16:15.015   873  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-07 13:16:15.016   873  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-07 13:16:15.016   873  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-07 13:16:15.016   873  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-07 13:16:15.016   873  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-07 13:16:15.020  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:15.039   373   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-07 13:16:15.041   373   872 D CommandListener: Setting iface cfg
,09-07 13:16:15.041   873  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.62 rxSuccessRate=12.25 delta 1000 -> 994
09-07 13:16:15.042   873  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-07 13:16:15.042   873  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 13:16:15.051   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-07 13:16:15.051   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 13:16:15.060   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-07 13:16:15.060   873  1303 D WifiNative-HAL: p2pGetDeviceAddress
,09-07 13:16:15.061   873  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-07 13:16:15.165   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-07 13:16:15.169  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-07 13:16:15.606  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-07 13:16:15.655  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-07 13:16:15.655  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-07 13:16:15.661   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 13:16:15.673   873  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 13:16:15.674   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 13:16:15.674   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-07 13:16:15.696   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 13:16:15.714   373   872 D CommandListener: Setting iface cfg
,09-07 13:16:15.716   873  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,09-07 13:16:15.741   873  1306 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-07 13:16:15.747   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-07 13:16:15.755   873  3997 D DhcpClient: Receive thread started
,09-07 13:16:15.843   873  1304 E native  : do suspend false
,09-07 13:16:15.866   873  2358 D DhcpClient: Broadcasting DHCPDISCOVER
,09-07 13:16:15.886   873  3997 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172688, domain null
,09-07 13:16:15.887   873  2358 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172688 seconds
,09-07 13:16:15.890   873  2358 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-07 13:16:15.919   873  3997 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-07 13:16:15.921   873  2358 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-07 13:16:15.925   373   872 D CommandListener: Setting iface cfg
,09-07 13:16:15.938   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-07 13:16:15.938   873  2358 D DhcpClient: Scheduling renewal in 86399s
,09-07 13:16:15.960   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-07 13:16:15.963   873  1304 D WifiConfigStore: No blacklist allowed without epno enabled
09-07 13:16:15.963   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 13:16:15.964   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-07 13:16:15.969   873  1306 D ConnectivityService: Adding iface wlan0 to network 101
,09-07 13:16:15.980   873  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-07 13:16:16.026   873  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-07 13:16:16.026   873  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-07 13:16:16.028   873  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-07 13:16:16.029   873  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-07 13:16:16.031   873  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-07 13:16:16.041   873  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 13:16:16.046   873  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-07 13:16:16.046   873  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-07 13:16:16.047   873  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-07 13:16:16.047   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 13:16:16.047   873  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-07 13:16:16.047   873  1306 D ConnectivityService:    accepting network in place of null
09-07 13:16:16.049   873  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-07 13:16:16.093   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 13:16:16.098   873  3996 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-07 13:16:16.145   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 13:16:16.149   873  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-07 13:16:16.149   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:16.153   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-07 13:16:16.161   873  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-07 13:16:16.168  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:16.168  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:16.168  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:16.168  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:16.168  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:16.168  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:16.168  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:16.168  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:16:16.171  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:16.179  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:16.179  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:16.179  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:16.179  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 13:16:16.179  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:16.179  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:16.179  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 13:16:16.179  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 13:16:16.179   873  3995 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
09-07 13:16:16.181  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 13:16:16.184  1687  1687 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 13:16:16.186  1687  1687 D SystemUpdateService: onCreate
,09-07 13:16:16.189  1687  1687 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 13:16:16.191  1687  4008 I SystemUpdateService: active receiver: enabled
,09-07 13:16:16.194  1687  4008 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 13:16:16.196  1687  4008 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-07 13:16:16.196  1687  4008 I SystemUpdateService: now status is 0 (complete)
09-07 13:16:16.197  1687  4008 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-07 13:16:16.197  1687  4008 I SystemUpdateService: file has been verified
,09-07 13:16:16.197  1687  4008 I SystemUpdateService: OTA package size = 12249756
,09-07 13:16:16.201  1687  4008 I SystemUpdateService: showing system update notification
,09-07 13:16:16.206  1687  1687 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-07 13:16:16.207  1687  2545 I iu.UploadsManager: num queued entries: 0
09-07 13:16:16.207  1687  2545 I iu.UploadsManager: num updated entries: 0
,09-07 13:16:16.209  1687  2545 I iu.SyncManager: NEXT; no task
,09-07 13:16:16.215  1687  1687 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 13:16:16.217  1687  1687 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-07 13:16:16.217  1687  1687 D SystemUpdateService: onDestroy
,09-07 13:16:16.217  1687  4014 I MDM     : [173] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-07 13:16:16.217  1687  4014 W BaseAppContext: Using Auth Proxy for data requests.
,09-07 13:16:16.218  1687  4014 V GoogleAuthProtoRequest: [173] a.<init>: mAccountName set to: thalitester@gmail.com
09-07 13:16:16.220  3828  3828 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:16.226  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:16:16.227  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:16:16.233  3828  3828 D SprintDMHelper: simOperator: 
09-07 13:16:16.234  3828  3828 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 13:16:16.248   873  3995 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 07 Sep 2016 11:16:16 GMT], X-Android-Received-Millis=[1473246976247], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473246976224]}
,09-07 13:16:16.249   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-07 13:16:16.249   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-07 13:16:16.250   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-07 13:16:16.255   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-07 13:16:16.260  1507  2950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-07 13:16:16.260  1507  2950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-07 13:16:16.260  1507  2950 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:16:16.260  1507  2950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:16:16.284  1687  4014 E MDM     : [173] SitrepService.a: Error sending sitrep.
,09-07 13:16:16.316  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 13:16:16.316  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 13:16:16.316  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 13:16:16.316  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:16:16.328  2639  4010 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-07 13:16:16.328  2639  4010 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at jdm.a(PG:82)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at jcs.o(PG:406)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at jcn.a(PG:1379)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at jcs.i(PG:143)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at blb.a(PG:3937)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at czp.a(PG:18188)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at czp.a(PG:9081)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at czq.run(PG:1686)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 13:16:16.328  2639  4010 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at jdj.a(PG:4091)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at jdj.a(PG:1125)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at jdm.a(PG:77)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	... 12 more
09-07 13:16:16.328  2639  4010 E HttpOperation: Caused by: faj: BadAuthentication
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at fal.a(PG:38)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	at jdj.a(PG:4089)
09-07 13:16:16.328  2639  4010 E HttpOperation: 	... 14 more
,09-07 13:16:16.361  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-07 13:16:16.361  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-07 13:16:16.361  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:16:16.361  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:16:16.377  2639  4010 E HttpOperation: [getmobileexperiments] Unexpected exception
09-07 13:16:16.377  2639  4010 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at jdm.a(PG:82)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at jcs.o(PG:406)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at jcn.a(PG:1379)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at jcs.i(PG:143)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at hec.a(PG:42)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at hee.a(PG:102)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at czr.a(PG:65)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at kka.a(PG:108)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at czp.a(PG:19176)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at czp.a(PG:9081)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at czq.run(PG:1686)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-07 13:16:16.377  2639  4010 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at jdj.a(PG:4091)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at jdj.a(PG:1125)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at jdm.a(PG:77)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	... 15 more
09-07 13:16:16.377  2639  4010 E HttpOperation: Caused by: faj: BadAuthentication
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at fal.a(PG:38)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	at jdj.a(PG:4089)
09-07 13:16:16.377  2639  4010 E HttpOperation: 	... 17 more
,09-07 13:16:16.377  2639  4010 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-07 13:16:16.377  2639  4010 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at jdm.a(PG:82)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at jcs.o(PG:406)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at jcn.a(PG:1379)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at jcs.i(PG:143)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at hec.a(PG:42)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at hee.a(PG:102)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at czr.a(PG:65)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at kka.a(PG:108)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at czp.a(PG:19176)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at czp.a(PG:9081)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at czq.run(PG:1686)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at jdj.a(PG:4091)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at jdj.a(PG:1125)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at jdm.a(PG:77)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	... 15 more
09-07 13:16:16.377  2639  4010 E ExperimentLoader: Caused by: faj: BadAuthentication
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at fal.a(PG:38)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	at jdj.a(PG:4089)
09-07 13:16:16.377  2639  4010 E ExperimentLoader: 	... 17 more
,09-07 13:16:16.400  2227  4016 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-07 13:16:16.478   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 126728, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-07 13:16:17.150   873  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-07 13:16:17.994   873  2043 D WifiService: setWifiEnabled: false pid=3708, uid=10000
,09-07 13:16:17.994   873  2043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-07 13:16:18.012  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-07 13:16:18.014   873  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-07 13:16:18.014   873  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-07 13:16:18.014   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-07 13:16:18.015   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 13:16:18.027   873  2358 D DhcpClient: Clearing IP address
,09-07 13:16:18.027   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 13:16:18.029   373   872 D CommandListener: Setting iface cfg
,09-07 13:16:18.032  1507  4023 V NativeCrypto: Read error: ssl=0x9aa6fc00: I/O error during system call, Connection timed out
,09-07 13:16:18.034   873  3997 D DhcpClient: Receive thread stopped
09-07 13:16:18.035  1507  4023 V NativeCrypto: SSL shutdown failed: ssl=0x9aa6fc00: I/O error during system call, Broken pipe
,09-07 13:16:18.036   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-07 13:16:18.036   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-07 13:16:18.037   873  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-07 13:16:18.037   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-07 13:16:18.039   373   872 D CommandListener: Clearing all IP addresses on wlan0
09-07 13:16:18.042   396   396 E Parcel  : Reading a NULL string not supported here.
,09-07 13:16:18.049   873  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-07 13:16:18.066   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 13:16:18.071  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:18.071  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:18.071  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:18.071  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:18.071  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:18.071  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:18.071  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:18.071  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:18.071   873  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-07 13:16:18.073  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:18.076  1855  2279 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 13:16:18.077  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:18.077  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:18.077  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:18.077  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:18.077  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:18.077  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:18.077  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:18.077  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:18.079  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:18.081   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 13:16:18.103   373   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-07 13:16:18.104   873  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-07 13:16:18.104   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:18.106   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-07 13:16:18.108  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:18.110  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:18.113  1687  1687 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-07 13:16:18.116  1687  1687 D SystemUpdateService: onCreate
,09-07 13:16:18.119  1687  1687 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-07 13:16:18.120  1687  4034 I SystemUpdateService: active receiver: enabled
,09-07 13:16:18.123  1687  4034 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-07 13:16:18.125  1687  4034 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-07 13:16:18.125  1687  4034 I SystemUpdateService: now status is 0 (complete)
09-07 13:16:18.125  1687  4034 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-07 13:16:18.125  1687  4034 I SystemUpdateService: file has been verified
,09-07 13:16:18.125  1687  4034 I SystemUpdateService: OTA package size = 12249756
09-07 13:16:18.126  1687  1687 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-07 13:16:18.129  1687  2545 I iu.UploadsManager: num queued entries: 0
09-07 13:16:18.129  1687  2545 I iu.UploadsManager: num updated entries: 0
09-07 13:16:18.130  1687  2545 I iu.SyncManager: NEXT; no task
,09-07 13:16:18.133  1687  4034 I SystemUpdateService: showing system update notification
,09-07 13:16:18.134  1687  1687 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-07 13:16:18.135  1687  1687 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-07 13:16:18.138  3828  3828 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-07 13:16:18.143  3828  3828 D SprintDMHelper: simOperator: 
09-07 13:16:18.143  3828  3828 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-07 13:16:18.148  1687  1687 D SystemUpdateService: onDestroy
,09-07 13:16:18.155   373   872 E Netd    : netlink response contains error (No such file or directory)
,09-07 13:16:18.162  2227  4038 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-07 13:16:18.186  3907  3907 I art     : Waiting for a blocking GC DisableMovingGc
,09-07 13:16:18.188  3907  3907 I art     : Starting a blocking GC DisableMovingGc
,09-07 13:16:18.249  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:16:18.277  1507  2409 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 13:16:18.277  1507  2409 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 13:16:18.277  1507  2409 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 13:16:18.278  1507  2409 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:16:18.298  3449  3449 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 13:16:18.299  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 13:16:18.299  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 13:16:21.007  3772  3804 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 13:16:21.007  3772  3804 D BluetoothAdapterProperties: Setting state to 13
09-07 13:16:21.007  3772  3804 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 13:16:21.009  3772  3804 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 13:16:21.018  3772  3804 I BluetoothAdapterState: Entering PendingCommandState
,09-07 13:16:21.021  3772  3772 D BluetoothMapService: onReceive
,09-07 13:16:21.024  3772  3772 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:21.024  3772  3772 D BluetoothMapService: STATE_TURNING_OFF
,09-07 13:16:21.025  3772  3772 D BluetoothMapService: MAP Service closeService in
,09-07 13:16:21.025  3772  3772 D BluetoothMapMasInstance0: MAP Service shutdown
,09-07 13:16:21.026  3772  3772 D ObexServerSockets0: shutdown(block = true)
,09-07 13:16:21.027  3772  3946 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 13:16:21.030  3772  3772 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 13:16:21.031  3772  3921 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-07 13:16:21.032  3772  3947 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-07 13:16:21.032  3772  3772 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 13:16:21.034  3708  3708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:21.035  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:21.035  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:21.035  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:21.035  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:21.035  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:21.035  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:21.035  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:21.035  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:21.035  3772  3772 I BtOppRfcommListener: stopping Accept Thread
,09-07 13:16:21.035  3772  3984 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 13:16:21.036  3708  3708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:21.036  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:21.037  3772  3984 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 13:16:21.041  3772  3809 D BluetoothAdapterProperties: Scan Mode:20
,09-07 13:16:21.041  3708  3708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 13:16:21.042  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:21.042  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:21.042  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:21.042  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:21.042  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:21.042  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:21.042  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:21.042  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:21.042  3772  3804 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 13:16:21.043  3708  3708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:21.043  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:21.045  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:21.045  3772  3772 D HeadsetService: Received stop request...Stopping profile...
,09-07 13:16:21.048  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:21.048  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 13:16:21.048   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 13:16:21.049  3933  3943 D BluetoothHeadset: Proxy object disconnected
,09-07 13:16:21.049   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 13:16:21.049  3772  3772 D A2dpService: Received stop request...Stopping profile...
09-07 13:16:21.049  1988  2002 D BluetoothHeadset: Proxy object disconnected
,09-07 13:16:21.050   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 13:16:21.050  3772  3928 D A2dpStateMachine: Exit Disconnected: -1
,09-07 13:16:21.050  1361  1678 D BluetoothHeadset: Proxy object disconnected
,09-07 13:16:21.053   873   873 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:21.054  3933  3933 D HeadsetProfile: Bluetooth service disconnected
09-07 13:16:21.055  3772  3772 D HidService: Received stop request...Stopping profile...
,09-07 13:16:21.055  3772  3772 D HidService: Stopping Bluetooth HidService
09-07 13:16:21.058  3933  3933 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:21.061  1361  1361 D HeadsetProfile: Bluetooth service disconnected
,09-07 13:16:21.062  3933  3933 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:21.061  1361  1361 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:21.065  1361  1361 D BluetoothInputDevice: Proxy object disconnected
09-07 13:16:21.065  1361  1361 D HidProfile: Bluetooth service disconnected
09-07 13:16:21.065  3933  3933 D BluetoothInputDevice: Proxy object disconnected
09-07 13:16:21.065  3933  3933 D HidProfile: Bluetooth service disconnected
,09-07 13:16:21.068  3772  3772 V BluetoothAdapterState: isTurningOff()=true
,09-07 13:16:21.068  3772  3772 V BluetoothAdapterState: isTurningOn()=false
,09-07 13:16:21.068  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:21.068  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 13:16:21.072  3772  3772 D HealthService: Received stop request...Stopping profile...
,09-07 13:16:21.074  3772  3772 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-07 13:16:21.074  3772  3772 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 13:16:21.074  3772  3919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 13:16:21.075  3772  3919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 13:16:21.075  3772  3919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 13:16:21.075  3772  3809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-07 13:16:21.075  3772  3809 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-07 13:16:21.075  3772  3772 D PanService: Received stop request...Stopping profile...
09-07 13:16:21.076  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 13:16:21.076  1361  1361 D PanProfile: Bluetooth service disconnected
09-07 13:16:21.076  3933  3933 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 13:16:21.076  3933  3933 D PanProfile: Bluetooth service disconnected
09-07 13:16:21.076  3772  3772 D BluetoothMapService: Received stop request...Stopping profile...
09-07 13:16:21.076  3772  3772 D BluetoothMapService: stop()
09-07 13:16:21.077  3772  3772 D BluetoothMapAppObserver: deinitObservers()
09-07 13:16:21.077  3772  3772 D BluetoothMapAppObserver: removeReceiver()
09-07 13:16:21.078  3772  3772 V BluetoothAdapterState: isTurningOff()=true
09-07 13:16:21.079  3772  3772 V BluetoothAdapterState: isTurningOn()=false
09-07 13:16:21.079  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:21.079  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:21.080  1361  1361 D BluetoothMap: Proxy object disconnected
09-07 13:16:21.080  1361  1361 D MapProfile: Bluetooth service disconnected
09-07 13:16:21.080  3933  3933 D BluetoothMap: Proxy object disconnected
09-07 13:16:21.080  3933  3933 D MapProfile: Bluetooth service disconnected
,09-07 13:16:21.081  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:16:21.081  3772  3772 V BluetoothAdapterState: isTurningOff()=true
,09-07 13:16:21.082  3772  3772 V BluetoothAdapterState: isTurningOn()=false
09-07 13:16:21.082  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:21.082  3772  3919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 13:16:21.082  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:21.082  3772  3919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 13:16:21.082  3772  3772 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 13:16:21.082  3772  3772 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-07 13:16:21.082  3772  3919 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:16:21.082  3772  3919 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:16:21.082  3772  3919 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:16:21.082  3772  3919 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 13:16:21.082  3772  3772 V BluetoothAdapterState: isTurningOff()=true
09-07 13:16:21.082  3772  3809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 13:16:21.082  3772  3772 V BluetoothAdapterState: isTurningOn()=false
,09-07 13:16:21.082  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:21.082  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:21.082  3772  3809 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 13:16:21.082  3772  3772 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 13:16:21.083  3772  3809 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 13:16:21.083  3772  3772 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 13:16:21.083  3772  3772 V BluetoothAdapterState: isTurningOff()=true
09-07 13:16:21.083  3772  3772 V BluetoothAdapterState: isTurningOn()=false
,09-07 13:16:21.083  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:21.083  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:21.083  3772  3772 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 13:16:21.084  3772  3772 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 13:16:21.084  3772  3772 D BluetoothMapService: MAP Service closeService in
09-07 13:16:21.084  3772  3772 V BluetoothAdapterState: isTurningOff()=true
09-07 13:16:21.084  3772  3772 V BluetoothAdapterState: isTurningOn()=false
09-07 13:16:21.084  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:21.084  3772  3772 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:21.085  3772  3772 D BluetoothMapService: cleanup()
09-07 13:16:21.085  3772  3772 D BluetoothMapService: MAP Service closeService in
09-07 13:16:21.085  3772  3804 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 13:16:21.085  3772  3804 D BluetoothAdapterProperties: Setting state to 15
09-07 13:16:21.085  3772  3804 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 13:16:21.086  3933  3933 D BluetoothPbap: Proxy object disconnected
09-07 13:16:21.086  3933  3933 D PbapServerProfile: Bluetooth service disconnected
,09-07 13:16:21.086   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:16:21.086   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:16:21.086  3933  3944 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 13:16:21.087  3772  3804 I BluetoothAdapterState: Entering BleOnState
09-07 13:16:21.087  1361  1361 D BluetoothPbap: Proxy object disconnected
09-07 13:16:21.087  1361  1361 D PbapServerProfile: Bluetooth service disconnected
09-07 13:16:21.089  3933  3943 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 13:16:21.089  1361  1678 D BluetoothPan: onBluetoothStateChange on: false
,09-07 13:16:21.090  3933  3944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:16:21.090  1361  1373 D BluetoothMap: onBluetoothStateChange: up=false
09-07 13:16:21.091  1361  2096 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:16:21.092  1361  2096 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 13:16:21.094  1361  1678 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 13:16:21.094  1988  2001 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:16:21.095  3933  3943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:16:21.095  3933  3944 D BluetoothPan: onBluetoothStateChange on: false
,09-07 13:16:21.096  3933  3943 D BluetoothMap: onBluetoothStateChange: up=false
09-07 13:16:21.096   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:16:21.096  1361  1373 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 13:16:21.097   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:16:21.097  3772  3804 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 13:16:21.097  3772  3804 D BluetoothAdapterProperties: Setting state to 16
,09-07 13:16:21.097  3772  3804 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-07 13:16:21.097  3772  3804 D BluetoothAdapterProperties: onBleDisable
,09-07 13:16:21.098  3772  3804 I BluetoothAdapterState: Entering PendingCommandState
09-07 13:16:21.098  3772  3805 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 13:16:21.098  3772  3919 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 13:16:21.098  3772  3919 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 13:16:21.100  3772  3809 D BluetoothAdapterProperties: Scan Mode:20
09-07 13:16:21.101  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:21.102  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:21.102  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 13:16:21.104  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:21.105  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:21.109  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:16:21.118  3933  3933 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:21.303  3772  3809 I bt_hci  : shut_down
,09-07 13:16:21.319  3772  3821 D bt_hwcfg: hw_epilog_process
,09-07 13:16:21.319  3772  3821 I bt_vendor: low_power_mode_cb
,09-07 13:16:21.340  3772  3821 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-07 13:16:21.340  3772  3821 I bt_vendor: epilog_cb
09-07 13:16:21.341  3772  3821 I bt_hci  : epilog_finished_callback
,09-07 13:16:21.349  3772  3809 I bt_hci_h4: hal_close
,09-07 13:16:21.351  3772  3809 I bt_userial_vendor: device fd = 51 close
,09-07 13:16:21.473  3772  3805 D bt_stack_manager: event_shut_down_stack finished.
,09-07 13:16:21.473  3772  3804 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 13:16:21.483  3772  3804 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-07 13:16:21.483  3772  3772 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 13:16:21.485  3772  3772 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 13:16:21.485  3772  3772 D BtGatt.GattService: stop()
,09-07 13:16:21.486  3772  3772 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 13:16:21.492  3772  3772 V BluetoothAdapterState: isTurningOff()=false
,09-07 13:16:21.493  3772  3772 V BluetoothAdapterState: isTurningOn()=false
,09-07 13:16:21.493  3772  3772 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:21.493  3772  3772 V BluetoothAdapterState: isBleTurningOff()=true
09-07 13:16:21.496  3772  3804 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-07 13:16:21.497  3772  3804 D BluetoothAdapterProperties: Setting state to 10
09-07 13:16:21.497  3772  3804 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-07 13:16:21.500  3772  3804 I BluetoothAdapterState: Entering OffState
,09-07 13:16:21.502   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 13:16:21.523  3772  3772 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-07 13:16:21.523  3772  3772 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-07 13:16:21.523  3772  3805 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-07 13:16:21.527  3772  3805 D bt_stack_manager: event_clean_up_stack finished.
09-07 13:16:21.527  3772  3772 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 13:16:21.529  3772  3772 I art     : System.exit called, status: 0
,09-07 13:16:21.529  3772  3772 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 13:16:21.579   873  2003 I ActivityManager: Process com.android.bluetooth (pid 3772) has died
,09-07 13:16:24.051   873  1306 D ConnectivityService: handlePromptUnvalidated 101
,09-07 13:16:24.056   873   890 I ActivityManager: Start proc 4047:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-07 13:16:24.172  4047  4047 D AdapterServiceConfig: Adding HeadsetService
,09-07 13:16:24.172  4047  4047 D AdapterServiceConfig: Adding A2dpService
,09-07 13:16:24.172  4047  4047 D AdapterServiceConfig: Adding HidService
,09-07 13:16:24.172  4047  4047 D AdapterServiceConfig: Adding HealthService
,09-07 13:16:24.172  4047  4047 D AdapterServiceConfig: Adding PanService
09-07 13:16:24.173  4047  4047 D AdapterServiceConfig: Adding GattService
,09-07 13:16:24.173  4047  4047 D AdapterServiceConfig: Adding BluetoothMapService
,09-07 13:16:24.188   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32e7813:true
,09-07 13:16:24.189  4047  4047 D BluetoothAdapterState: make() - Creating AdapterState
,09-07 13:16:24.193  4047  4047 I bt_bluedroid: init
,09-07 13:16:24.193  4047  4059 I BluetoothAdapterState: Entering OffState
,09-07 13:16:24.198  4047  4060 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-07 13:16:24.199  4047  4060 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-07 13:16:24.199  4047  4060 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-07 13:16:24.199  4047  4060 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-07 13:16:24.201  4047  4047 I bt_bluedroid: get_profile_interface socket
,09-07 13:16:24.203  4047  4063 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-07 13:16:24.204  4047  4063 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 13:16:24.205  4047  4047 I bt_bluedroid: get_profile_interface sdp
,09-07 13:16:24.209  4047  4058 I bt_bluedroid: config_hci_snoop_log
,09-07 13:16:24.211   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 13:16:24.215  4047  4059 D BluetoothAdapterState: Current state: OFF, message: 0
,09-07 13:16:24.215  4047  4059 D BluetoothAdapterProperties: Setting state to 14
09-07 13:16:24.216  4047  4059 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-07 13:16:24.219  4047  4059 D BluetoothBondStateMachine: make
,09-07 13:16:24.222  4047  4064 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 13:16:24.227  4047  4059 I BluetoothAdapterState: Entering PendingCommandState
,09-07 13:16:24.227  4047  4047 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-07 13:16:24.230  4047  4047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:24.231  4047  4047 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 13:16:24.231  4047  4047 D BtGatt.GattService: Received start request. Starting profile...
09-07 13:16:24.232  4047  4047 D BtGatt.GattService: start()
09-07 13:16:24.232  4047  4047 I bt_bluedroid: get_profile_interface gatt
,09-07 13:16:24.233  4047  4047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
09-07 13:16:24.233  4047  4047 D BtGatt.AdvertiseManager: advertise manager created
,09-07 13:16:24.240  4047  4047 V BluetoothAdapterState: isTurningOff()=false
09-07 13:16:24.240  4047  4047 V BluetoothAdapterState: isTurningOn()=false
09-07 13:16:24.240  4047  4047 V BluetoothAdapterState: isBleTurningOn()=true
,09-07 13:16:24.240  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:24.240  4047  4059 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-07 13:16:24.240  4047  4059 I bt_bluedroid: enable
09-07 13:16:24.240  4047  4060 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-07 13:16:24.241  4047  4060 I bt_hci  : start_up
,09-07 13:16:24.248  4047  4060 I bt_vendor: alloc value 0xb39f9189
,09-07 13:16:24.248  4047  4060 I bt_vendor: init
09-07 13:16:24.248  4047  4060 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-07 13:16:24.248  4047  4060 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-07 13:16:24.356  4047  4060 D bt_hci  : start_up starting async portion
,09-07 13:16:24.357  4047  4067 I bt_hci  : event_finish_startup
09-07 13:16:24.357  4047  4067 I bt_hci_h4: hal_open
09-07 13:16:24.357  4047  4067 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-07 13:16:24.368  4047  4067 I bt_userial_vendor: device fd = 51 open
,09-07 13:16:24.399  4047  4067 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 13:16:24.431  4047  4067 D bt_hwcfg: Chipset BCM4354A2
09-07 13:16:24.431  4047  4067 D bt_hwcfg: Target name = [BCM4354A2]
09-07 13:16:24.432  4047  4067 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-07 13:16:25.099  4047  4067 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-07 13:16:25.101  4047  4067 D bt_hwcfg: Settlement delay -- 100 ms
,09-07 13:16:25.101  4047  4067 I bt_hwcfg: Setting fw settlement delay to 100 
,09-07 13:16:25.218  4047  4067 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-07 13:16:25.219  4047  4067 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-07 13:16:25.249  4047  4067 I bt_hwcfg: vendor lib fwcfg completed
,09-07 13:16:25.249  4047  4067 I bt_vendor: firmware callback
,09-07 13:16:25.249  4047  4067 I bt_hci  : firmware_config_callback
,09-07 13:16:25.261  4047  4069 I bt_btu  : btu_task pending for preload complete event
,09-07 13:16:25.261  4047  4069 I bt_btu_task: Bluetooth chip preload is complete
,09-07 13:16:25.261  4047  4069 I bt_btu  : btu_task received preload complete event
,09-07 13:16:25.272  4047  4069 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 13:16:25.272  4047  4069 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-07 13:16:25.272  4047  4069 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-07 13:16:25.272  4047  4069 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 13:16:25.273  4047  4069 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 13:16:25.273  4047  4069 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 13:16:25.273  4047  4069 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 13:16:25.273  4047  4069 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 13:16:25.274  4047  4069 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 13:16:25.274  4047  4069 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 13:16:25.274  4047  4069 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 13:16:25.274  4047  4069 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 13:16:25.274  4047  4069 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 13:16:25.275  4047  4069 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 13:16:25.275  4047  4069 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 13:16:25.410  4047  4069 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
09-07 13:16:25.410  4047  4069 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,09-07 13:16:25.416  4047  4063 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-07 13:16:25.418  4047  4063 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 13:16:25.419  4047  4063 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-07 13:16:25.422  4047  4063 D BluetoothAdapterProperties: Name is: Nexus 6
,09-07 13:16:25.425  4047  4063 D BluetoothAdapterProperties: Scan Mode:20
,09-07 13:16:25.425  4047  4063 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 13:16:25.426  4047  4063 D bt_hci  : do_postload posting postload work item
,09-07 13:16:25.426  4047  4067 I bt_hci  : event_postload
,09-07 13:16:25.426  4047  4067 I bt_vendor: sco_config_cb
,09-07 13:16:25.426  4047  4067 I bt_hci  : sco_config_callback postload finished.
,09-07 13:16:25.429  4047  4063 D bt_bte_conf: Device ID record 1 : primary
,09-07 13:16:25.429  4047  4063 D bt_bte_conf:   vendorId            = 000f
,09-07 13:16:25.429  4047  4063 D bt_bte_conf:   vendorIdSource      = 0001
09-07 13:16:25.430  4047  4063 D bt_bte_conf:   product             = 1200
,09-07 13:16:25.430  4047  4063 D bt_bte_conf:   version             = 1436
,09-07 13:16:25.432  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:25.430  4047  4063 D bt_bte_conf:   clientExecutableURL = 
09-07 13:16:25.435  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:25.436  4047  4063 D bt_bte_conf:   serviceDescription  = 
,09-07 13:16:25.436  4047  4063 D bt_bte_conf:   documentationURL    = 
09-07 13:16:25.438  4047  4067 I bt_vendor: low_power_mode_cb
09-07 13:16:25.439  4047  4063 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-07 13:16:25.439  4047  4060 D bt_stack_manager: event_start_up_stack finished
09-07 13:16:25.440  4047  4059 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-07 13:16:25.441  4047  4059 D BluetoothAdapterProperties: Setting state to 15
09-07 13:16:25.441  4047  4059 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-07 13:16:25.442  4047  4059 I BluetoothAdapterState: Entering BleOnState
09-07 13:16:25.448  4047  4059 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-07 13:16:25.448  4047  4059 D BluetoothAdapterProperties: Setting state to 11
,09-07 13:16:25.448  4047  4059 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-07 13:16:25.456  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:25.457  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:25.462  4047  4047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:25.468  4047  4047 D HeadsetService: Received start request. Starting profile...
,09-07 13:16:25.472  4047  4047 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-07 13:16:25.472  4047  4047 D HeadsetStateMachine: make
,09-07 13:16:25.481  4047  4059 I BluetoothAdapterState: Entering PendingCommandState
,09-07 13:16:25.483  4047  4047 D HeadsetStateMachine: max_hf_connections = 1
,09-07 13:16:25.483  4047  4047 I bt_bluedroid: get_profile_interface handsfree
,09-07 13:16:25.484  4047  4063 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-07 13:16:25.484  4047  4063 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-07 13:16:25.487  4047  4047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
09-07 13:16:25.487  4047  4047 D A2dpService: Received start request. Starting profile...
09-07 13:16:25.488  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 13:16:25.489  4047  4047 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 13:16:25.489  4047  4047 I bt_bluedroid: get_profile_interface avrcp
,09-07 13:16:25.494  4047  4047 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 13:16:25.494  4047  4047 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-07 13:16:25.494  4047  4047 D A2dpStateMachine: make
,09-07 13:16:25.495  4047  4047 I bt_bluedroid: get_profile_interface a2dp
,09-07 13:16:25.495  4047  4063 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-07 13:16:25.497  4047  4078 D A2dpStateMachine: Enter Disconnected: -2
,09-07 13:16:25.497  4047  4047 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 13:16:25.498  4047  4047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:25.499  4047  4047 D HidService: Received start request. Starting profile...
,09-07 13:16:25.499  4047  4047 I bt_bluedroid: get_profile_interface hidhost
,09-07 13:16:25.499  4047  4047 D HidService: setHidService(): set to: null
09-07 13:16:25.499  4047  4063 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
09-07 13:16:25.499  4047  4063 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-07 13:16:25.499  4047  4047 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 13:16:25.500  4047  4047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
09-07 13:16:25.501  4047  4047 D HealthService: Received start request. Starting profile...
,09-07 13:16:25.502  4047  4047 I bt_bluedroid: get_profile_interface health
,09-07 13:16:25.502  4047  4047 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 13:16:25.503  4047  4047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:25.503  4047  4047 D PanService: Received start request. Starting profile...
09-07 13:16:25.503  4047  4047 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-07 13:16:25.503  4047  4047 I bt_bluedroid: get_profile_interface pan
09-07 13:16:25.504  4047  4063 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 13:16:25.506  4047  4047 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@328c5d1
,09-07 13:16:25.506  4047  4047 D BluetoothMapService: Received start request. Starting profile...
,09-07 13:16:25.506  4047  4047 D BluetoothMapService: start()
,09-07 13:16:25.508  4047  4047 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-07 13:16:25.509  4047  4047 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-07 13:16:25.509  4047  4047 D BluetoothMapAppObserver: createReceiver()
,09-07 13:16:25.510  4047  4047 D BluetoothMapAppObserver: initObservers()
09-07 13:16:25.510  4047  4047 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-07 13:16:25.517  4047  4075 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-07 13:16:25.517  4047  4047 V BluetoothAdapterState: isTurningOff()=false
,09-07 13:16:25.517  4047  4047 V BluetoothAdapterState: isTurningOn()=true
09-07 13:16:25.517  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:25.518  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 13:16:25.519  4047  4047 V BluetoothAdapterState: isTurningOff()=false
,09-07 13:16:25.519  4047  4047 V BluetoothAdapterState: isTurningOn()=true
,09-07 13:16:25.519  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:25.519  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isTurningOff()=false
,09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isTurningOn()=true
,09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isTurningOff()=false
09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isTurningOn()=true
,09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isTurningOff()=false
09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isTurningOn()=true
09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:25.520  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:25.521  4047  4047 V BluetoothAdapterState: isTurningOff()=false
09-07 13:16:25.521  4047  4047 V BluetoothAdapterState: isTurningOn()=true
09-07 13:16:25.521  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:25.521  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 13:16:25.521  4047  4059 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-07 13:16:25.521  4047  4059 D BluetoothAdapterProperties: ScanMode =  20
09-07 13:16:25.521  4047  4059 D BluetoothAdapterProperties: State =  11
09-07 13:16:25.522  4047  4059 D BluetoothAdapterProperties: Setting state to 12
09-07 13:16:25.522  4047  4059 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-07 13:16:25.522   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:16:25.523   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:16:25.523  4047  4059 I BluetoothAdapterState: Entering OnState
,09-07 13:16:25.523  3933  3943 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 13:16:25.527  3933  3944 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 13:16:25.527  4047  4063 D BluetoothAdapterProperties: Scan Mode:21
,09-07 13:16:25.527  4047  4063 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 13:16:25.530  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:25.530  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:25.530  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:25.530  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:25.530  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:25.530  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:25.530  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:25.530  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:25.530  1361  2096 D BluetoothPan: onBluetoothStateChange on: true
,09-07 13:16:25.531  3933  3933 D BluetoothInputDevice: Proxy object connected
,09-07 13:16:25.531  3933  3933 D HidProfile: Bluetooth service connected
09-07 13:16:25.531  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:25.532  3933  3944 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 13:16:25.533  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 13:16:25.533  1361  1361 D PanProfile: Bluetooth service connected
09-07 13:16:25.534  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:25.534  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:25.534  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:25.534  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:25.534  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 13:16:25.534  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:25.534  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:25.534  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:16:25.535  1361  1373 D BluetoothMap: onBluetoothStateChange: up=true
09-07 13:16:25.536  4047  4047 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 13:16:25.536  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:25.536  4047  4047 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-07 13:16:25.536  1361  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:16:25.537  1361  2096 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-07 13:16:25.537  4047  4047 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 13:16:25.538  1361  1361 D BluetoothInputDevice: Proxy object connected
09-07 13:16:25.539  1361  1361 D HidProfile: Bluetooth service connected
,09-07 13:16:25.540  4047  4047 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:16:25.541  1361  1373 D BluetoothPbap: onBluetoothStateChange: up=true
09-07 13:16:25.541  4047  4047 D ObexServerSockets: Succeed to create listening sockets 
,09-07 13:16:25.541  4047  4047 D ObexServerSockets0: startAccept()
09-07 13:16:25.542  4047  4047 D ObexServerSockets0: prepareForNewConnect()
09-07 13:16:25.542  1988  2091 D BluetoothHeadset: onBluetoothStateChange: up=true
09-07 13:16:25.543  3933  3943 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 13:16:25.544  3933  3944 D BluetoothPan: onBluetoothStateChange on: true
,09-07 13:16:25.546  4047  4047 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-07 13:16:25.546  3933  3943 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 13:16:25.546  4047  4047 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-07 13:16:25.547  4047  4083 D ObexServerSockets0: Accepting socket connection...
09-07 13:16:25.547  4047  4085 D ObexServerSockets0: Accepting socket connection...
09-07 13:16:25.548   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-07 13:16:25.548  1361  1361 D BluetoothMap: Proxy object connected
,09-07 13:16:25.548  1361  1361 D MapProfile: Bluetooth service connected
,09-07 13:16:25.548  1361  1678 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 13:16:25.548  1361  1361 D BluetoothMap: getConnectedDevices()
,09-07 13:16:25.549  1361  1361 D BluetoothA2dp: Proxy object connected
09-07 13:16:25.549   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 13:16:25.550   873   873 D BluetoothA2dp: Proxy object connected
09-07 13:16:25.551  3933  3933 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 13:16:25.551  3933  3933 D PanProfile: Bluetooth service connected
,09-07 13:16:25.551  3933  3933 D BluetoothA2dp: Proxy object connected,
,09-07 13:16:25.552  4047  4047 D BluetoothMapService: onReceive
,09-07 13:16:25.552  4047  4047 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-07 13:16:25.552  4047  4047 D BluetoothMapService: STATE_ON
09-07 13:16:25.554  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:25.555   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-07 13:16:25.555  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:25.555  3933  3933 D BluetoothMap: Proxy object connected
,09-07 13:16:25.555  3933  3933 D MapProfile: Bluetooth service connected
09-07 13:16:25.555  3933  3933 D BluetoothMap: getConnectedDevices()
,09-07 13:16:25.561  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 13:16:25.566  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
09-07 13:16:25.568  3933  3933 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:25.573  1361  1361 D BluetoothPbap: Proxy object connected
,09-07 13:16:25.573  3933  3933 D BluetoothPbap: Proxy object connected
09-07 13:16:25.573  1361  1361 D PbapServerProfile: Bluetooth service connected
09-07 13:16:25.574  3933  3933 D PbapServerProfile: Bluetooth service connected
,09-07 13:16:25.579  4047  4047 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-07 13:16:25.579  4047  4047 D ObexServerSockets0: prepareForNewConnect()
,09-07 13:16:25.581  4047  4091 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:16:25.598  4047  4095 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 13:16:25.599  4047  4095 I BtOppRfcommListener: Accept thread started.
,09-07 13:16:25.624   873   873 D BluetoothHeadset: Proxy object connected
,09-07 13:16:25.625  3933  3944 D BluetoothHeadset: Proxy object connected
,09-07 13:16:25.625  3933  3933 D HeadsetProfile: Bluetooth service connected
,09-07 13:16:25.625   873   873 D BluetoothHeadset: Proxy object connected
09-07 13:16:25.626  1988  2278 D BluetoothHeadset: Proxy object connected
,09-07 13:16:25.626   873   873 D BluetoothHeadset: Proxy object connected
,09-07 13:16:25.628  1361  1374 D BluetoothHeadset: Proxy object connected
09-07 13:16:25.628  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-07 13:16:25.637  1361  2096 D BluetoothHeadset: Proxy object connected
09-07 13:16:25.638  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-07 13:16:25.642  1988  2002 D BluetoothHeadset: Proxy object connected
,09-07 13:16:25.644  3933  3943 D BluetoothHeadset: Proxy object connected
,09-07 13:16:25.644  3933  3933 D HeadsetProfile: Bluetooth service connected
,09-07 13:16:25.648   873   890 D BluetoothHeadset: Proxy object connected
,09-07 13:16:27.006  3708  3756 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 13:16:27.007  3708  3756 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 13:16:29.566   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-07 13:16:29.576  1891  1891 I Keyboard.Facilitator: onFinishInput()
,09-07 13:16:29.592   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-07 13:16:29.592   873   893 I Adreno  : Build Date                       : 10/20/15
09-07 13:16:29.592   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-07 13:16:29.592   873   893 I Adreno  : Local Branch                     : M14
09-07 13:16:29.592   873   893 I Adreno  : Remote Branch                    : 
09-07 13:16:29.592   873   893 I Adreno  : Remote Branch                    : 
09-07 13:16:29.592   873   893 I Adreno  : Reconstruct Branch               : 
,09-07 13:16:29.635   281   371 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (204 us)
,09-07 13:16:30.014  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 13:16:30.014  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@93a52f7 added. We now have 6 listener(s)
,09-07 13:16:30.015  3708  3756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 13:16:30.020  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 13:16:30.021  3708  3756 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@526c564 added. We now have 7 listener(s)
,09-07 13:16:30.021  3708  3756 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 13:16:30.026  3708  3756 I System.out: IsBluetoothEnabled
,09-07 13:16:30.035  4047  4059 D BluetoothAdapterState: Current state: ON, message: 23
,09-07 13:16:30.036  4047  4059 D BluetoothAdapterProperties: Setting state to 13
,09-07 13:16:30.036  4047  4059 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-07 13:16:30.038  4047  4059 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 13:16:30.045  4047  4059 I BluetoothAdapterState: Entering PendingCommandState
,09-07 13:16:30.049  4047  4047 D BluetoothMapService: onReceive
,09-07 13:16:30.049  4047  4047 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-07 13:16:30.049  4047  4047 D BluetoothMapService: STATE_TURNING_OFF
,09-07 13:16:30.049  4047  4047 D BluetoothMapService: MAP Service closeService in
09-07 13:16:30.049  4047  4047 D BluetoothMapMasInstance0: MAP Service shutdown
09-07 13:16:30.049  4047  4047 D ObexServerSockets0: shutdown(block = true)
09-07 13:16:30.050  4047  4047 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-07 13:16:30.050  4047  4047 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-07 13:16:30.051  4047  4083 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-07 13:16:30.051  4047  4085 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-07 13:16:30.052  4047  4071 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-07 13:16:30.052  4047  4047 I BtOppRfcommListener: stopping Accept Thread
09-07 13:16:30.053  4047  4095 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 13:16:30.054  4047  4095 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-07 13:16:30.054  3708  3708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:30.054  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 13:16:30.054  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:30.054  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 13:16:30.054  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:30.054  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:30.054  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:30.054  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:30.054  3708  3708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 13:16:30.055  4047  4063 D BluetoothAdapterProperties: Scan Mode:20
09-07 13:16:30.055  4047  4059 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-07 13:16:30.056  3708  3708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:30.056  3708  3708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 13:16:30.060  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:30.061  4047  4047 D HeadsetService: Received stop request...Stopping profile...
,09-07 13:16:30.063   873   873 D BluetoothHeadset: Proxy object disconnected
09-07 13:16:30.063  3933  3943 D BluetoothHeadset: Proxy object disconnected
,09-07 13:16:30.064   873   873 D BluetoothHeadset: Proxy object disconnected
,09-07 13:16:30.064  4047  4047 D A2dpService: Received stop request...Stopping profile...
09-07 13:16:30.064  1988  2278 D BluetoothHeadset: Proxy object disconnected
,09-07 13:16:30.064  4047  4078 D A2dpStateMachine: Exit Disconnected: -1
,09-07 13:16:30.065   873   873 D BluetoothHeadset: Proxy object disconnected
,09-07 13:16:30.063  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 13:16:30.065  1361  1373 D BluetoothHeadset: Proxy object disconnected
,09-07 13:16:30.065   873   873 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:30.066  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:30.066  3708  3756 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-07 13:16:30.066  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 13:16:30.066  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-07 13:16:30.066  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 13:16:30.066  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 13:16:30.066  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 13:16:30.066  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 13:16:30.066  3708  3756 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 13:16:30.068  3708  3756 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 13:16:30.068  4047  4047 D HidService: Received stop request...Stopping profile...
,09-07 13:16:30.068  3708  3756 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 13:16:30.068  4047  4047 D HidService: Stopping Bluetooth HidService
,09-07 13:16:30.070  1361  1361 D HeadsetProfile: Bluetooth service disconnected
09-07 13:16:30.070  1361  1361 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:30.070  4047  4047 D HealthService: Received stop request...Stopping profile...
09-07 13:16:30.070  1361  1361 D BluetoothInputDevice: Proxy object disconnected
09-07 13:16:30.071  1361  1361 D HidProfile: Bluetooth service disconnected
09-07 13:16:30.071  4047  4047 V BluetoothAdapterState: isTurningOff()=true
09-07 13:16:30.071  4047  4047 V BluetoothAdapterState: isTurningOn()=false
09-07 13:16:30.071  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:30.071  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:30.072  4047  4059 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-07 13:16:30.072  4047  4047 D PanService: Received stop request...Stopping profile...
09-07 13:16:30.072  4047  4059 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
09-07 13:16:30.074  3933  3933 D HeadsetProfile: Bluetooth service disconnected
,09-07 13:16:30.074  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 13:16:30.074  1361  1361 D PanProfile: Bluetooth service disconnected
,09-07 13:16:30.074  3933  3933 D BluetoothA2dp: Proxy object disconnected
09-07 13:16:30.076  4047  4047 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-07 13:16:30.076  4047  4063 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-07 13:16:30.076  4047  4047 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 13:16:30.076  4047  4069 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 13:16:30.076  4047  4069 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 13:16:30.076  4047  4069 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 13:16:30.078  4047  4063 E bt_btif : btif_hf_upstreams_evt: Invalid index 99,
09-07 13:16:30.079  4047  4047 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 13:16:30.079  4047  4047 D BluetoothMapService: stop()
09-07 13:16:30.080  4047  4047 D BluetoothMapAppObserver: deinitObservers()
,09-07 13:16:30.080  4047  4047 D BluetoothMapAppObserver: removeReceiver()
,09-07 13:16:30.082  4047  4047 V BluetoothAdapterState: isTurningOff()=true
09-07 13:16:30.083  4047  4047 V BluetoothAdapterState: isTurningOn()=false
,09-07 13:16:30.083  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:30.083  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 13:16:30.083  1361  1361 D BluetoothMap: Proxy object disconnected
,09-07 13:16:30.083  1361  1361 D MapProfile: Bluetooth service disconnected
,09-07 13:16:30.084  4047  4069 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-07 13:16:30.084  4047  4069 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 13:16:30.084  4047  4069 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 13:16:30.084  4047  4069 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-07 13:16:30.084  4047  4069 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 13:16:30.084  4047  4069 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-07 13:16:30.085  4047  4047 V BluetoothAdapterState: isTurningOff()=true,
09-07 13:16:30.085  4047  4063 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-07 13:16:30.085  4047  4047 V BluetoothAdapterState: isTurningOn()=false
,09-07 13:16:30.085  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:30.085  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 13:16:30.086  4047  4047 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 13:16:30.086  4047  4047 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-07 13:16:30.086  4047  4063 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-07 13:16:30.086  4047  4047 V BluetoothAdapterState: isTurningOff()=true
,09-07 13:16:30.086  4047  4047 V BluetoothAdapterState: isTurningOn()=false
09-07 13:16:30.086  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:30.086  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
09-07 13:16:30.087  4047  4047 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-07 13:16:30.087  4047  4063 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-07 13:16:30.087  4047  4047 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-07 13:16:30.088  4047  4047 V BluetoothAdapterState: isTurningOff()=true
,09-07 13:16:30.088  4047  4047 V BluetoothAdapterState: isTurningOn()=false
,09-07 13:16:30.088  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:30.088  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 13:16:30.088  3933  3933 D DockEventReceiver: finishStartingService: stopping service
09-07 13:16:30.089  3933  3933 D BluetoothInputDevice: Proxy object disconnected
,09-07 13:16:30.089  3933  3933 D HidProfile: Bluetooth service disconnected,
09-07 13:16:30.089  3933  3933 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 13:16:30.089  3933  3933 D PanProfile: Bluetooth service disconnected
09-07 13:16:30.090  3933  3933 D BluetoothMap: Proxy object disconnected
,09-07 13:16:30.090  3933  3933 D MapProfile: Bluetooth service disconnected
,09-07 13:16:30.092  4047  4047 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-07 13:16:30.092  4047  4047 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-07 13:16:30.092  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 13:16:30.092  4047  4047 D BluetoothMapService: MAP Service closeService in
09-07 13:16:30.092  4047  4047 V BluetoothAdapterState: isTurningOff()=true
,09-07 13:16:30.093  4047  4047 V BluetoothAdapterState: isTurningOn()=false
,09-07 13:16:30.093  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
09-07 13:16:30.093  4047  4047 V BluetoothAdapterState: isBleTurningOff()=false
,09-07 13:16:30.093  4047  4059 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-07 13:16:30.093  4047  4059 D BluetoothAdapterProperties: Setting state to 15
,09-07 13:16:30.093  4047  4059 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-07 13:16:30.093  4047  4059 I BluetoothAdapterState: Entering BleOnState
09-07 13:16:30.093  4047  4059 D BluetoothAdapterState: Current state: BLE ON, message: 0
,09-07 13:16:30.094  4047  4047 D BluetoothMapService: cleanup()
09-07 13:16:30.094  4047  4047 D BluetoothMapService: MAP Service closeService in
09-07 13:16:30.095   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 13:16:30.095   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:16:30.095  3933  3943 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 13:16:30.096  3933  4084 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 13:16:30.097  1361  1373 D BluetoothPan: onBluetoothStateChange on: false
,09-07 13:16:30.097  1361  1361 D BluetoothPbap: Proxy object disconnected
,09-07 13:16:30.097  1361  1361 D PbapServerProfile: Bluetooth service disconnected
09-07 13:16:30.097  3933  3944 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:16:30.098  1361  2096 D BluetoothMap: onBluetoothStateChange: up=false
09-07 13:16:30.100  1361  1678 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 13:16:30.100  1361  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-07 13:16:30.101  1361  1373 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 13:16:30.102  1988  2002 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-07 13:16:30.102  3933  3943 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:16:30.102  3933  4084 D BluetoothPan: onBluetoothStateChange on: false
,09-07 13:16:30.103  3933  3944 D BluetoothMap: onBluetoothStateChange: up=false
09-07 13:16:30.103   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-07 13:16:30.104  1361  2096 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:16:30.104   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 13:16:30.105  4047  4059 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-07 13:16:30.105  4047  4059 D BluetoothAdapterProperties: Setting state to 16
09-07 13:16:30.105  4047  4059 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-07 13:16:30.105  4047  4059 D BluetoothAdapterProperties: onBleDisable
09-07 13:16:30.105  4047  4059 I BluetoothAdapterState: Entering PendingCommandState
09-07 13:16:30.106  4047  4060 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-07 13:16:30.106  4047  4063 D BluetoothAdapterProperties: Scan Mode:20
09-07 13:16:30.107  4047  4069 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-07 13:16:30.107  4047  4069 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-07 13:16:30.107  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:30.109  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 13:16:30.110  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 13:16:30.115  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-07 13:16:30.122  3933  3933 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:30.230  3708  3708 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 13:16:30.230  3708  3708 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 13:16:30.304   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-07 13:16:30.305  3708  3708 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@722ee0d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@feb3cd, 16908290=android.view.AbsSavedState$1@feb3cd}, android:focusedViewId=100}]}]
,09-07 13:16:30.305  3708  3708 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-07 13:16:30.306  3708  3708 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 13:16:30.306  3708  3708 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 13:16:30.311  4047  4063 I bt_hci  : shut_down
,09-07 13:16:30.314   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-07 13:16:30.317  4047  4067 D bt_hwcfg: hw_epilog_process
,09-07 13:16:30.317  4047  4067 I bt_vendor: low_power_mode_cb
,09-07 13:16:30.318   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-07 13:16:30.318   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
09-07 13:16:30.318   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-07 13:16:30.341  4047  4067 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-07 13:16:30.341  4047  4067 I bt_vendor: epilog_cb
,09-07 13:16:30.341  4047  4067 I bt_hci  : epilog_finished_callback
,09-07 13:16:30.343  4047  4063 I bt_hci_h4: hal_close
,09-07 13:16:30.343  4047  4063 I bt_userial_vendor: device fd = 51 close
,09-07 13:16:30.459  4047  4060 D bt_stack_manager: event_shut_down_stack finished.
09-07 13:16:30.460  4047  4059 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-07 13:16:30.466  4047  4059 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-07 13:16:30.466  4047  4047 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 13:16:30.468  4047  4047 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 13:16:30.468  4047  4047 D BtGatt.GattService: stop()
,09-07 13:16:30.469  4047  4047 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 13:16:30.474  4047  4047 V BluetoothAdapterState: isTurningOff()=false
,09-07 13:16:30.474  4047  4047 V BluetoothAdapterState: isTurningOn()=false
09-07 13:16:30.475  4047  4047 V BluetoothAdapterState: isBleTurningOn()=false
,09-07 13:16:30.475  4047  4047 V BluetoothAdapterState: isBleTurningOff()=true
09-07 13:16:30.476  4047  4059 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-07 13:16:30.476  4047  4059 D BluetoothAdapterProperties: Setting state to 10
09-07 13:16:30.477  4047  4059 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-07 13:16:30.482  4047  4059 I BluetoothAdapterState: Entering OffState
,09-07 13:16:30.490  3708  3708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 13:16:30.492  3933  3933 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 13:16:30.498  3933  3933 D DockEventReceiver: finishStartingService: stopping service
,09-07 13:16:30.501  1507  1507 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-07 13:16:30.546   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-07 13:16:30.549   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-07 13:16:30.550   873  1329 D SurfaceControl: Excessive delay in setPowerMode(): 232ms
,09-07 13:16:30.556   873   893 I DreamManagerService: Entering dreamland.
,09-07 13:16:30.558   873   893 I PowerManagerService: Dozing...
,09-07 13:16:30.559   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-07 13:16:30.622   377  1312 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-07 13:16:30.622   377  1312 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-07 13:16:30.637   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 13:16:30.645  1976  4107 D NfcService: Discovery configuration equal, not updating.
,09-07 13:16:30.647   873  1304 E native  : do suspend false
,09-07 13:16:30.673   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,09-07 13:16:30.679   873  1304 E native  : do suspend true
,09-07 13:16:30.757   377  1313 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-07 13:16:30.758   377  1313 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-07 13:16:35.542  1855  2517 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 13:16:50.835  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:16:50.850  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:16:50.856  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:16:50.919  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 13:16:50.920  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 13:16:50.920  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:16:50.920  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:16:50.981  3449  3449 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 13:16:50.982  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 13:16:50.983  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-07 13:17:11.329  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:17:11.347  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:17:11.355  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:17:11.432  1507  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 13:17:11.432  1507  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 13:17:11.433  1507  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:17:11.433  1507  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:17:11.483  3449  3449 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
09-07 13:17:11.484  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 13:17:11.484  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-07 13:17:18.111   873  1306 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,09-07 13:17:29.618  1891  1963 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-07 13:17:29.619  1891  1963 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-07 13:17:29.670  1507  1507 I ConfigService: onCreate
,09-07 13:17:34.711  1507  1507 I ConfigService: onDestroy
,09-07 13:19:41.320  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:19:41.335  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:19:41.339  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:19:41.403  1507  2409 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 13:19:41.403  1507  2409 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 13:19:41.403  1507  2409 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:19:41.403  1507  2409 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:19:41.438  1507  2409 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 13:19:41.438  1507  2409 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 13:19:41.438  1507  2409 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 13:19:41.438  1507  2409 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 13:19:41.438  1507  2409 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 13:19:41.438  1507  2409 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 13:19:41.438  1507  2409 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 13:19:41.448  3449  3480 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 13:19:41.448  3449  3480 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 13:19:41.448  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 13:19:41.448  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 13:19:41.448  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 13:19:41.448  3449  3480 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 13:19:41.448  3449  3480 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 13:24:41.615  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:24:41.631  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:24:41.634  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:24:41.674  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 13:24:41.675  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-07 13:24:41.675  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:24:41.675  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:24:41.705  1507  1518 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 13:24:41.705  1507  1518 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 13:24:41.705  1507  1518 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 13:24:41.705  1507  1518 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 13:24:41.705  1507  1518 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 13:24:41.705  1507  1518 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 13:24:41.705  1507  1518 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 13:24:41.713  3449  3480 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 13:24:41.713  3449  3480 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 13:24:41.713  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 13:24:41.713  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 13:24:41.713  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 13:24:41.713  3449  3480 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 13:24:41.713  3449  3480 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 13:26:07.470  3449  3449 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,09-07 13:26:07.497  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:07.525  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:07.533  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:07.622  1507  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-07 13:26:07.622  1507  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-07 13:26:07.622  1507  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 13:26:07.623  1507  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:26:07.679  3449  3449 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 13:26:07.702  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:07.781  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-07 13:26:07.782  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-07 13:26:07.782  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:26:07.783  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:26:07.874  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:07.972  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-07 13:26:07.973  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 13:26:07.973  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:26:07.974  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:26:08.040  3449  3449 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 13:26:08.361  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:08.394  1507  1518 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 13:26:08.394  1507  1518 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 13:26:08.394  1507  1518 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:26:08.394  1507  1518 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:26:08.420  3449  3449 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,09-07 13:26:08.420  3449  3449 D Finsky  : [1] WearSupportService.startHygiene: disabled
,09-07 13:26:08.421  3449  3449 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,09-07 13:26:08.424  3449  3503 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,09-07 13:26:08.426  3449  3449 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,09-07 13:26:23.404  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:23.417  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:23.423  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:23.487  1507  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 13:26:23.488  1507  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 13:26:23.488  1507  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 13:26:23.489  1507  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:26:23.546  3449  3449 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 13:26:23.547  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 13:26:23.551  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,09-07 13:26:44.089  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:44.130  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:44.139  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:26:44.211   873   882 I art     : Background partial concurrent mark sweep GC freed 44573(3MB) AllocSpace objects, 10(336KB) LOS objects, 33% free, 29MB/43MB, paused 1.305ms total 104.633ms
,09-07 13:26:44.218  1507  2409 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 13:26:44.219  1507  2409 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 13:26:44.219  1507  2409 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 13:26:44.219  1507  2409 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:26:44.275  3449  3449 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 13:26:44.275  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 13:26:44.275  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,09-07 13:27:04.520  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:27:04.528  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:27:04.529  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:27:04.555  1507  2950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 13:27:04.555  1507  2950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 13:27:04.555  1507  2950 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:27:04.555  1507  2950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:27:04.589  3449  3449 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-07 13:27:04.589  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 13:27:04.589  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-07 13:27:24.857  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:27:24.871  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:27:24.877  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:27:24.941  1507  4163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 13:27:24.941  1507  4163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 13:27:24.942  1507  4163 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:27:24.943  1507  4163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:27:24.989  3449  3449 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 13:27:24.990  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 13:27:24.991  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-07 13:27:45.322  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:27:45.341  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:27:45.348  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:27:45.442  1507  2950 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-07 13:27:45.443  1507  2950 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-07 13:27:45.443  1507  2950 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-07 13:27:45.443  1507  2950 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:27:45.510  3449  3449 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 13:27:45.511  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-07 13:27:45.513  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-07 13:28:05.965  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:28:05.982  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:28:05.989  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:28:06.078  1507  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-07 13:28:06.079  1507  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-07 13:28:06.079  1507  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:28:06.079  1507  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:28:06.145  3449  3449 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-07 13:28:06.146  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-07 13:28:06.147  3449  3449 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-07 13:29:41.849  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:29:41.863  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:29:41.869  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:29:41.929  1507  2076 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-07 13:29:41.929  1507  2076 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 13:29:41.929  1507  2076 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:29:41.930  1507  2076 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:29:41.964  1507  2076 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 13:29:41.964  1507  2076 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 13:29:41.964  1507  2076 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 13:29:41.964  1507  2076 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 13:29:41.964  1507  2076 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 13:29:41.964  1507  2076 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 13:29:41.964  1507  2076 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 13:29:41.978  3449  3480 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 13:29:41.978  3449  3480 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 13:29:41.978  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 13:29:41.978  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 13:29:41.978  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 13:29:41.978  3449  3480 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 13:29:41.978  3449  3480 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 13:34:17.395   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,09-07 13:34:42.109  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:34:42.127  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:34:42.133  1507  1507 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-07 13:34:42.213  1507  4163 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-07 13:34:42.213  1507  4163 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-07 13:34:42.213  1507  4163 I GLSUser : [GLSUser] Extracting token using key: Auth
09-07 13:34:42.214  1507  4163 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-07 13:34:42.256  1507  4163 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-07 13:34:42.256  1507  4163 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-07 13:34:42.256  1507  4163 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-07 13:34:42.256  1507  4163 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-07 13:34:42.256  1507  4163 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-07 13:34:42.256  1507  4163 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-07 13:34:42.256  1507  4163 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-07 13:34:42.270  3449  3480 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-07 13:34:42.270  3449  3480 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-07 13:34:42.270  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-07 13:34:42.270  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-07 13:34:42.270  3449  3480 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-07 13:34:42.270  3449  3480 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-07 13:34:42.270  3449  3480 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),09-07 13:39:29.678  4200  4200 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-07 13:39:29.683  4200  4200 D AndroidRuntime: CheckJNI is OFF
09-07 13:39:29.719  4200  4200 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-07 13:39:29.759  4200  4200 I Radio-JNI: register_android_hardware_Radio DONE
09-07 13:39:29.779  4200  4200 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-07 13:39:29.794   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-07 13:39:29.795   873   886 I ActivityManager: Killing 3708:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-07 13:39:29.895   873  1704 D GraphicsStats: Buffer count: 2
09-07 13:39:29.895   873  2011 I WindowState: WIN DEATH: Window{1a3f0f0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 13:39:29.896   873  1305 D WifiService: Client connection lost with reason: 4
09-07 13:39:29.906   873   896 W PackageSettings: Skipping PackageSetting{70af03a com.example.hello/10273} due to missing metadata
09-07 13:39:29.942   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-07 13:39:29.943   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-07 13:39:29.944   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-07 13:39:29.944   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-07 13:39:29.944   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:39:29.944   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:29.944   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 13:39:29.944   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 13:39:29.945   873   886 I ActivityManager:   Force finishing activity ActivityRecord{1fa751 u0 com.test.thalitest/.MainActivity t4}
09-07 13:39:29.948   873   896 I art     : Starting a blocking GC Explicit
09-07 13:39:29.961   873  1390 W ActivityManager: Spurious death for ProcessRecord{a2c9962 0:com.test.thalitest/u0a0}, curProc for 3708: null
09-07 13:39:29.990   873   896 I art     : Explicit concurrent mark sweep GC freed 38027(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 689us total 39.864ms
09-07 13:39:30.041   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-07 13:39:30.047  4200  4200 I art     : System.exit called, status: 0
09-07 13:39:30.047  4200  4200 I AndroidRuntime: VM exiting with result code 0.
09-07 13:39:30.057   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-07 13:39:30.074   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-07 13:39:30.081  1855  2241 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 13:39:30.088   873  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 13:39:30.088  3551  3551 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-07 13:39:30.121  1891  1891 I Keyboard.Facilitator: resetDictionaries() : en_US
09-07 13:39:30.127  1988  1988 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-07 13:39:30.136  1891  4216 I Keyboard.Facilitator.DecoderInitializer: run()
09-07 13:39:30.139   873  1704 I ActivityManager: Start proc 4217:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-07 13:39:30.142  1891  4216 I Decoder : createOrResetDecoder
09-07 13:39:30.155  1507  1507 I ConfigService: onCreate
09-07 13:39:30.196   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 13:39:30.199  1891  4216 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-07 13:39:30.201   873  1705 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3708 uid 10000
09-07 13:39:30.202  1891  1891 I Keyboard.Facilitator: onFinishInput()
09-07 13:39:30.205  2005  2115 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-07 13:39:30.209   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-07 13:39:30.209   873   885 E PackageManager: Failed to write settings, restoring backup
09-07 13:39:30.209   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-07 13:39:30.209   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-07 13:39:30.209   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-07 13:39:30.209   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-07 13:39:30.209   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-07 13:39:30.209   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:39:30.209   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:30.209   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 13:39:30.210  4217  4217 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-07 13:39:30.214   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-07 13:39:30.214   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-07 13:39:30.214   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 13:39:30.214   873   886 E DropBoxManagerService: 	... 13 more
09-07 13:39:30.218   873  2042 I ActivityManager: Start proc 4231:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-07 13:39:30.219  2005  2115 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-07 13:39:30.219  2005  2115 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2005
09-07 13:39:30.219  2005  2115 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:30.219  2005  2115 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 13:39:30.221   873  2011 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 13:39:30.222   873  4236 E DropBoxManagerService: Can't write: system_app_crash
09-07 13:39:30.222   873  4236 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 13:39:30.222   873  4236 E DropBoxManagerService: 	... 5 more
09-07 13:39:30.225  2005  2115 I Process : Sending signal. PID: 2005 SIG: 9
09-07 13:39:30.249  1891  4216 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-07 13:39:30.264  1891  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-07 13:39:30.264  1891  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-07 13:39:30.291  1891  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-07 13:39:30.292  1891  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-07 13:39:30.292  1891  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-07 13:39:30.292  1891  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-07 13:39:30.293  1891  4216 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-07 13:39:30.293  1891  4216 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-07 13:39:30.293  1891  4216 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-07 13:39:30.293  1891  4216 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-07 13:39:30.293  1891  4216 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-07 13:39:30.293  1891  4216 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-07 13:39:30.330  4217  4217 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-07 13:39:30.342   873  1706 I WindowState: WIN DEATH: Window{8513870 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-07 13:39:30.342   873  2011 D GraphicsStats: Buffer count: 1
09-07 13:39:30.353   873  1704 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2005) has died
09-07 13:39:30.353   873  1704 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-07 13:39:30.356   873  1704 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:30.370  4217  4247 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:30.371  4217  4247 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 13:39:30.374   873   886 I ActivityManager: Start proc 4251:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 13:39:30.388   873  1706 I ActivityManager: Start proc 4262:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-07 13:39:30.409  1687  4250 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-07 13:39:30.411  1687  4250 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-07 13:39:30.419  4262  4262 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-07 13:39:30.421  4217  4268 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:39:30.422  4251  4251 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 13:39:30.423  4251  4251 D AndroidRuntime: Shutting down VM
09-07 13:39:30.431  4251  4251 E AndroidRuntime: FATAL EXCEPTION: main
09-07 13:39:30.431  4251  4251 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4251
09-07 13:39:30.431  4251  4251 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-07 13:39:30.431  4251  4251 E AndroidRuntime: 	... 10 more
09-07 13:39:30.432   873   884 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 13:39:30.433  4251  4251 I Process : Sending signal. PID: 4251 SIG: 9
09-07 13:39:30.433   873  4276 E DropBoxManagerService: Can't write: system_app_crash
09-07 13:39:30.433   873  4276 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 13:39:30.433   873  4276 E DropBoxManagerService: 	... 5 more
09-07 13:39:30.441  1687  4250 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-07 13:39:30.442  1687  4250 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-07 13:39:30.458  1507  1507 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-07 13:39:30.459  1507  1507 D AndroidRuntime: Shutting down VM
09-07 13:39:30.460  1507  1507 E AndroidRuntime: FATAL EXCEPTION: main
09-07 13:39:30.460  1507  1507 E AndroidRuntime: Process: com.google.process.gapps, PID: 1507
09-07 13:39:30.460  1507  1507 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-07 13:39:30.460  1507  1507 E AndroidRuntime: 	... 8 more
09-07 13:39:30.464   873  1390 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4251) has died
09-07 13:39:30.465   873  1390 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-07 13:39:30.471   873  4280 E DropBoxManagerService: Can't write: system_app_crash
09-07 13:39:30.471   873  4280 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 13:39:30.471   873  4280 E DropBoxManagerService: 	... 5 more
09-07 13:39:30.481   873   886 I ActivityManager: Start proc 4281:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-07 13:39:30.486   873  1706 I ActivityManager: Killing 3603:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-07 13:39:30.488  1507  1507 I Process : Sending signal. PID: 1507 SIG: 9
09-07 13:39:30.514  4217  4247 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:30.522  4217  4268 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 13:39:30.523   873  1305 D WifiService: Client connection lost with reason: 4
09-07 13:39:30.526  4217  4268 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-07 13:39:30.526  4217  4268 E AndroidRuntime: Process: android.process.acore, PID: 4217
09-07 13:39:30.526  4217  4268 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-07 13:39:30.526  4217  4268 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-07 13:39:30.527  4217  4247 I Process : Sending signal. PID: 4217 SIG: 9
09-07 13:39:30.547   873  2039 I ActivityManager: Process com.google.process.gapps (pid 1507) has died
09-07 13:39:30.548   873  2039 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
09-07 13:39:30.548   873  2039 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 10999ms
09-07 13:39:30.549   873  2039 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
09-07 13:39:30.551   873  4293 E DropBoxManagerService: Can't write: system_app_crash
09-07 13:39:30.551   873  4293 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-07 13:39:30.551   873  4293 E DropBoxManagerService: 	... 5 more
09-07 13:39:30.562   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
