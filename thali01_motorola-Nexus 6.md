#### Test 79763830cfa9ed9_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-26 15:42:38.511   875  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 15:42:39.180  3835  3835 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 15:42:39.185  3835  3835 D AndroidRuntime: CheckJNI is OFF
08-26 15:42:39.228  3835  3835 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 15:42:39.278  3835  3835 I Radio-JNI: register_android_hardware_Radio DONE
08-26 15:42:39.299  3835  3835 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 15:42:39.304   875  2114 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 15:42:39.326  2028  2043 W SearchService: Abort, client detached.
08-26 15:42:39.339  2028  2028 I HotwordDetector: Closing mic
08-26 15:42:39.339  2028  2333 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@58f2f92
08-26 15:42:39.340  2028  2347 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-26 15:42:39.345  3835  3835 D AndroidRuntime: Shutting down VM
08-26 15:42:39.381   875  1700 I ActivityManager: Start proc 3844:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 15:42:39.401   375  2353 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 15:42:39.402   375  2353 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 15:42:39.408   375  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 15:42:39.414  2028  2342 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 15:42:39.414  2028  2346 I MicroRecognitionRnrImpl: Detection finished
08-26 15:42:39.461  3844  3844 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 15:42:39.483  3844  3844 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 15:42:39.490  3844  3844 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3476-3479)
08-26 15:42:39.490  3844  3844 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 15:42:39.507  3844  3844 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34b8b18}
08-26 15:42:39.507  3844  3844 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 15:42:39.507  3844  3844 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 15:42:39.514  3844  3844 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 15:42:39.515  3844  3844 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 15:42:39.537  3844  3844 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 15:42:39.548  3844  3844 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 15:42:39.548  3844  3844 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 15:42:39.548  3844  3844 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 15:42:39.548  3844  3844 I Adreno  : Build Date                       : 10/20/15
08-26 15:42:39.548  3844  3844 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 15:42:39.548  3844  3844 I Adreno  : Local Branch                     : M14
08-26 15:42:39.548  3844  3844 I Adreno  : Remote Branch                    : 
08-26 15:42:39.548  3844  3844 I Adreno  : Remote Branch                    : 
08-26 15:42:39.548  3844  3844 I Adreno  : Reconstruct Branch               : 
,08-26 15:42:39.625   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aafae32:true
,08-26 15:42:39.671  3844  3844 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 15:42:39.685  3844  3844 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 15:42:39.766  3844  3882 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 15:42:39.781  3844  3869 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 15:42:39.836  3844  3882 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 15:42:39.903   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +551ms
,08-26 15:42:39.910  1862  1862 I Keyboard.Facilitator: onFinishInput()
,08-26 15:42:40.012  3844  3844 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3844
,08-26 15:42:40.182   875  1385 I ActivityManager: Killing 3059:com.google.android.talk/u0a61 (adj 15): empty #17
,08-26 15:42:40.193  3844  3844 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 15:42:40.240   875  1385 I ActivityManager: Killing 2978:com.google.android.calendar/u0a37 (adj 15): empty #18
,08-26 15:42:40.404  3844  3885 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1699284688
,08-26 15:42:40.413  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 15:42:40.413  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 15:42:40.413  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 15:42:40.413  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 15:42:40.413  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 15:42:40.413  3844  3885 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@930c68f added. We now have 1 listener(s)
,08-26 15:42:40.416  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-26 15:42:40.418  3844  3885 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 15:42:40.418  3844  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:40.419  3844  3885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 15:42:40.422  3844  3885 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c248efa added. We now have 1 listener(s)
08-26 15:42:40.423  3844  3885 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:40.427   875  1309 D WifiService: New client listening to asynchronous messages
,08-26 15:42:40.431  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:42:40.431  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-26 15:42:40.431  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2,
,08-26 15:42:40.431  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 15:42:40.431  3844  3885 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 15:42:40.437  3844  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:40.437  3844  3885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-26 15:42:40.447  3844  3885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 15:42:40.447  3844  3885 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:40.447  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:40.447  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:40.447  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:40.447  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:40.447  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:40.447  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:40.447  3844  3885 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:40.447  3844  3885 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-26 15:42:40.447  3844  3885 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:40.450  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:40.449  3844  3885 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 15:42:40.452  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:40.480  3844  3844 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 15:42:41.433  3844  3895 W jxcore-log: Initializing JXcore engine
,08-26 15:42:41.433  3844  3895 W jxcore-log: JXcore engine is ready
,08-26 15:42:41.489  3895  3895 W Thread-334: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 15:42:41.492  3895  3895 W Thread-334: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12060]" dev="sockfs" ino=12060 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-26 15:42:41.492  3895  3895 W Thread-334: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 15:42:41.492  3895  3895 W Thread-334: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[28967]" dev="sockfs" ino=28967 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,08-26 15:42:41.508  3844  3895 W jxcore-log: Starting JXcore engine
,08-26 15:42:41.615  3844  3895 W jxcore-log: Platform android
08-26 15:42:41.615  3844  3895 W jxcore-log: 
08-26 15:42:41.615  3844  3895 W jxcore-log: Process ARCH arm
08-26 15:42:41.615  3844  3895 W jxcore-log: 
,08-26 15:42:41.860  3844  3895 I jxcore-log: JXcore Cordova bridge is ready!
08-26 15:42:41.860  3844  3895 I jxcore-log: 
08-26 15:42:41.860  3844  3895 W jxcore-log: JXcore engine is started
,08-26 15:42:41.872  3844  3885 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 15:42:41.878  3844  3844 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 15:42:42.637   875  1863 D NetlinkSocketObserver: NeighborEvent{elapsedMs=126626, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-26 15:42:43.703  3036  3897 V KeepSync: Connecting to GoogleApiClient
,08-26 15:42:43.704   875  1384 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 15:42:43.777  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:42:43.781  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:42:43.818  1501  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-26 15:42:43.818  1501  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-26 15:42:43.818  1501  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 15:42:43.819  1501  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 15:42:43.845  1730  3898 V BaseAuthAsyncOperation: access token request failed
,08-26 15:42:43.847  3036  3897 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 15:42:43.920  1501  3633 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-26 15:42:43.921  1501  3633 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 15:42:43.921  1501  3633 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 15:42:43.921  1501  3633 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 15:42:43.968  3036  3897 E KeepSync: IOException
08-26 15:42:43.968  3036  3897 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 15:42:43.968  3036  3897 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 15:42:43.968  3036  3897 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 15:42:43.968  3036  3897 E KeepSync: 	... 10 more
,08-26 15:42:43.968  3036  3897 W KeepSync: Sync result 2
,08-26 15:42:43.975   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, SERVER, currentRunTime 127554, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-26 15:42:44.679  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:42:44.723  1501  2403 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 15:42:44.723  1501  2403 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 15:42:44.723  1501  2403 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 15:42:44.723  1501  2403 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 15:42:44.760  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 15:42:44.761  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-26 15:42:44.761  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-26 15:42:49.521  3784  3906 V GoogleAuthProtoRequest: [318] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 15:42:49.556  1501  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-26 15:42:49.556  1501  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-26 15:42:49.556  1501  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 15:42:49.556  1501  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: [318] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: [318] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-26 15:42:49.569  3784  3906 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-26 15:42:51.726  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 15:42:51.726  3844  3895 I jxcore-log: 
,08-26 15:42:51.729  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 15:42:51.729  3844  3895 I jxcore-log: 
,08-26 15:42:51.740  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:51.740  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:51.740  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:51.740  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:51.740  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:51.740  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:51.740  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:51.740  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:51.747  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:51.750  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 15:42:51.750  3844  3895 I jxcore-log: 
,08-26 15:42:51.752  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 15:42:51.752  3844  3895 I jxcore-log: 
,08-26 15:42:52.251  3844  3895 D executeNativeTests: Running unit tests
,08-26 15:42:52.310  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:42:52.310  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec added. We now have 2 listener(s)
,08-26 15:42:52.311  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 15:42:52.311  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:42:52.311  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:42:52.312  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:52.312  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 added. We now have 2 listener(s)
08-26 15:42:52.312  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:42:52.312  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:42:52.315  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:52.345  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:52.345  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.345  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.345  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:52.345  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:52.345  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.345  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:52.345  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:42:52.350  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:42:52.350  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:52.352  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 15:42:52.354  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 15:42:52.354  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 15:42:52.356  3844  3895 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 15:42:52.356  3844  3895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-26 15:42:52.356  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:52.356  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 15:42:52.356  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:52.356  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:52.357  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.357  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:52.357  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:52.357  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.357  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:42:52.357  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:42:52.358  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec removed from the list
,08-26 15:42:52.358  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.358  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 removed from the list
,08-26 15:42:52.359  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.360  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:42:52.360  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:52.362  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:52.362  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.363  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:42:52.363  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.363  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:52.364  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
,08-26 15:42:52.368  3844  3895 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 15:42:52.368  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:52.368  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:42:52.369  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:52.369  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.369  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:52.369  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.369  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
,08-26 15:42:52.369  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.369  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
,08-26 15:42:52.370  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.371  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.371  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:52.371  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.371  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.371  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:52.373  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.373  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.373  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.373  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.377  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:52.377  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 15:42:52.377  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 15:42:52.377  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 15:42:52.377  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 15:42:52.377  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 15:42:52.377  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 15:42:52.377  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 15:42:52.378  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 15:42:52.379  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 15:42:52.379  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.379  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.379  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.379  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.379  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.379  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.379  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.379  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.379  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.379  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.379  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.379  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.379  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.379  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.380  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.380  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.380  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.380  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.381  3844  3895 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 15:42:52.382  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:52.386  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:52.386  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.386  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.386  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:52.386  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:52.386  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.386  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:52.386  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:52.389  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.389  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:52.389  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:52.389  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:52.389  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:52.389  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:52.389  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:42:52.391  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.392  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 15:42:52.392  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 15:42:52.393  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.397  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 15:42:52.399  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 15:42:52.399  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 15:42:52.401  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 15:42:52.405  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 15:42:52.405  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 15:42:52.405  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:42:52.406  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 15:42:52.406  3844  3895 D BluetoothAdapter: STATE_ON
08-26 15:42:52.411  2637  2769 D BtGatt.GattService: registerClient() - UUID=401aa00d-f34c-4a41-b00e-61158453bc08
08-26 15:42:52.411  2637  2675 D BtGatt.GattService: onClientRegistered() - UUID=401aa00d-f34c-4a41-b00e-61158453bc08, clientIf=5
08-26 15:42:52.412  3844  3855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 15:42:52.413  2637  2777 D BtGatt.GattService: start scan with filters
08-26 15:42:52.415  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:42:52.415  2637  2678 D BtGatt.ScanManager: handling starting scan
08-26 15:42:52.416  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:42:52.416  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:42:52.416  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 15:42:52.417  2637  2678 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
08-26 15:42:52.418  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:42:52.418  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:42:52.418  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:42:52.419  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:52.421  3844  3895 I io.jxcore.node.ConnectionHelper: start: OK
08-26 15:42:52.424  2637  2675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 15:42:52.424  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.424  2637  2678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 15:42:52.424  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.424  3844  3895 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:52.425  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.425  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:42:52.425  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.425  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:42:52.425  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:52.425  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:52.425  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:52.425  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:52.425  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:52.425  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 15:42:52.426  3844  3895 D BluetoothAdapter: STATE_ON
08-26 15:42:52.426  2637  2769 D BtGatt.GattService: stopScan() - queue size =1
08-26 15:42:52.427  2637  2648 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 15:42:52.428  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:52.428  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:52.428  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:42:52.428  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:42:52.428  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 15:42:52.429  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:52.429  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:42:52.429  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:52.430  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:42:52.430  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:52.430  2637  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 15:42:52.430  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.431  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:52.431  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:52.431  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:52.431  2637  2678 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:42:52.431  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.431  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.431  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:52.431  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.431  2637  2678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 15:42:52.431  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.431  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.431  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.431  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.431  3844  3895 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 15:42:52.433  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:52.436  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:52.436  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.436  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.436  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:52.436  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:52.436  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.436  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:52.436  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:52.437  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.437  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:52.438  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:52.438  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:52.438  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:52.438  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:52.438  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:42:52.439  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.442  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.442  2637  2675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 15:42:52.442  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.445  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 15:42:52.445  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 15:42:52.448  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 15:42:52.449  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 15:42:52.449  2637  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 15:42:52.449  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 15:42:52.449  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.451  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 15:42:52.452  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:42:52.452  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 15:42:52.452  3844  3895 D BluetoothAdapter: STATE_ON
08-26 15:42:52.454  2637  2648 D BtGatt.GattService: registerClient() - UUID=690fb695-c64c-4999-a086-ad4c635c3c06
08-26 15:42:52.455  2637  2675 D BtGatt.GattService: onClientRegistered() - UUID=690fb695-c64c-4999-a086-ad4c635c3c06, clientIf=5
08-26 15:42:52.455  3844  3856 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 15:42:52.455  2637  2650 D BtGatt.GattService: start scan with filters
08-26 15:42:52.456  2637  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 15:42:52.456  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.457  2637  2678 D BtGatt.ScanManager: stopping BLe Batch
08-26 15:42:52.457  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:42:52.457  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:42:52.458  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:42:52.458  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 15:42:52.459  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:42:52.460  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:42:52.460  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:42:52.461  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 15:42:52.462  3844  3895 I io.jxcore.node.ConnectionHelper: start: OK
08-26 15:42:52.464  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.464  3844  3895 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:52.464  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.464  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:42:52.464  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.465  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:42:52.465  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:52.465  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:52.465  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:52.465  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:52.465  2637  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 15:42:52.465  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:52.465  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 15:42:52.465  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.465  2637  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 15:42:52.466  3844  3895 D BluetoothAdapter: STATE_ON
08-26 15:42:52.466  2637  2648 D BtGatt.GattService: stopScan() - queue size =0
08-26 15:42:52.466  2637  2650 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 15:42:52.466  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:52.467  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:52.467  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:42:52.467  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:42:52.467  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 15:42:52.468  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:52.468  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:42:52.468  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:52.468  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:42:52.468  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:52.469  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:52.469  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:52.469  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:52.469  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.469  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.469  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:52.469  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.469  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.470  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.470  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.470  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.470  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.470  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.471  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.471  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.471  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.471  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.471  2637  2675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 15:42:52.471  3844  3895 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 15:42:52.471  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.472  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:52.473  2637  2678 D BtGatt.ScanManager: handling starting scan
08-26 15:42:52.475  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:52.475  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.475  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.475  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:52.475  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:42:52.475  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.475  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:52.475  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:52.477  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.477  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 15:42:52.478  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:42:52.478  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:42:52.478  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:42:52.478  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:42:52.478  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:42:52.479  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.480  2637  2675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 15:42:52.480  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.480  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.480  2637  2678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 15:42:52.482  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 15:42:52.482  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 15:42:52.485  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 15:42:52.485  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 15:42:52.485  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 15:42:52.486  2637  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 15:42:52.486  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.487  2637  2678 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:42:52.487  2637  2678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 15:42:52.487  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 15:42:52.487  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:42:52.487  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 15:42:52.488  3844  3895 D BluetoothAdapter: STATE_ON
08-26 15:42:52.489  2637  2648 D BtGatt.GattService: registerClient() - UUID=87cdaa43-ce3b-486c-a9e2-af52c0104fd7
08-26 15:42:52.489  2637  2675 D BtGatt.GattService: onClientRegistered() - UUID=87cdaa43-ce3b-486c-a9e2-af52c0104fd7, clientIf=5
08-26 15:42:52.490  3844  3855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 15:42:52.490  2637  2777 D BtGatt.GattService: start scan with filters
08-26 15:42:52.492  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:42:52.493  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:42:52.493  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:42:52.493  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 15:42:52.497  2637  2675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 15:42:52.497  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.498  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:42:52.498  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:42:52.499  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:42:52.500  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:42:52.501  2637  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 15:42:52.501  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.503  3844  3895 I io.jxcore.node.ConnectionHelper: start: OK
08-26 15:42:52.503  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.503  3844  3895 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:52.503  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.503  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 15:42:52.503  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.503  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:42:52.503  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:52.503  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:52.503  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:52.503  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:42:52.504  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:42:52.504  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 15:42:52.504  3844  3895 D BluetoothAdapter: STATE_ON
08-26 15:42:52.505  2637  2777 D BtGatt.GattService: stopScan() - queue size =0
08-26 15:42:52.505  2637  2769 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 15:42:52.506  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:42:52.506  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:42:52.506  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:42:52.506  2637  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 15:42:52.506  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:42:52.506  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.506  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 15:42:52.506  2637  2678 D BtGatt.ScanManager: stopping BLe Batch
08-26 15:42:52.507  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:52.507  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:42:52.507  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:42:52.507  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:42:52.508  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:52.509  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.509  3844  3895 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 15:42:52.509  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.509  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.509  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.510  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.510  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:42:52.510  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.510  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.510  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.510  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.510  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.510  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:52.510  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:52.510  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:52.511  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.511  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.512  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.512  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.512  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.512  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.512  2637  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 15:42:52.512  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.513  3844  3895 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 15:42:52.513  2637  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 15:42:52.513  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.513  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.513  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.514  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.514  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.514  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.514  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.514  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.514  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.514  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.514  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.514  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.514  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.514  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.515  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.515  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.515  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.515  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.516  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 15:42:52.516  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.517  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.517  2637  2675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 15:42:52.517  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.517  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.517  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.518  2637  2678 D BtGatt.ScanManager: handling starting scan
08-26 15:42:52.518  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.518  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.518  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.518  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.519  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.519  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.519  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.519  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.519  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.519  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.520  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.520  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.520  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.520  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.520  3844  3895 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 15:42:52.521  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.521  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.521  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.521  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.521  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.521  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.521  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.521  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.521  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.521  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.521  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.521  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.521  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.522  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.522  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.522  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.522  2637  2675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 15:42:52.522  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.522  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.522  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.523  2637  2678 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 15:42:52.523  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 15:42:52.523  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.523  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.523  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.523  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.524  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.524  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.524  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.524  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.524  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.524  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.524  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.524  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.524  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.524  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.525  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.525  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.525  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.525  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.526  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 15:42:52.527  2637  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 15:42:52.527  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.527  2637  2678 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:42:52.527  2637  2678 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 15:42:52.527  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:52.527  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:52.528  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 15:42:52.528  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 15:42:52.528  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 15:42:52.528  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.529  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.529  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.532  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.532  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.533  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.533  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.534  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.534  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.534  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.534  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.534  2637  2675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 15:42:52.534  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.534  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.534  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.534  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:52.535  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.536  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.536  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.536  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.536  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:52.537  3844  3895 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 15:42:52.537  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:52.539  2637  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 15:42:52.539  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.542  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:52.542  3844  3895 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 15:42:52.542  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 15:42:52.542  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 15:42:52.542  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 15:42:52.542  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 15:42:52.542  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 15:42:52.542  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 15:42:52.542  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 15:42:52.542  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 15:42:52.543  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 15:42:52.543  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 15:42:52.543  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 15:42:52.543  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 15:42:52.543  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 15:42:52.543  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 15:42:52.543  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 15:42:52.544  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 15:42:52.544  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 15:42:52.544  3844  3895 D io.jxcore.node.ConnectionModel: closeAndR,emoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 15:42:52.544  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 15:42:52.544  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 15:42:52.544  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 15:42:52.544  2637  2675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 15:42:52.544  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 15:42:52.544  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.544  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 15:42:52.544  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 15:42:52.544  2637  2678 D BtGatt.ScanManager: stopping BLe Batch
08-26 15:42:52.545  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 15:42:52.545  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 15:42:52.545  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 15:42:52.545  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 15:42:52.545  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 15:42:52.545  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 15:42:52.545  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 15:42:52.546  3844  3895 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:52.546  3844  3895 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 15:42:52.546  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:52.546  3844  3895 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:52.546  3844  3895 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 15:42:52.546  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:52.546  3844  3895 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 15:42:52.546  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 15:42:52.550  2637  2675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 15:42:52.550  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.550  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 15:42:52.550  2637  2678 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 15:42:52.550  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 15:42:52.551  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 15:42:52.551  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 15:42:52.551  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 15:42:52.551  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 15:42:52.551  3844  3895 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 15:42:52.551  3844  3895 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 15:42:52.552  3844  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 398)
08-26 15:42:52.552  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.552  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.552  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.552  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.552  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.552  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.553  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 15:42:52.553  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.553  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.553  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.553  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.553  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.553  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.553  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.554  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.554  3844  3909 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:42:52.554  2637  2675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 15:42:52.554  2637  2675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:42:52.555  3844  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 398
08-26 15:42:52.555  3844  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 398)
08-26 15:42:52.555  3844  3910 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 398)
08-26 15:42:52.555  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.555  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.555  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.555  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.556  3844  3895 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 15:42:52.556  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.556  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.556  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.556  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.556  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.556  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.556  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.557  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.557  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.557  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.557  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.557  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.557  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.557  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.558  3844  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 398)
08-26 15:42:52.559  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.559  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.559  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.559  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.560  3844  3895 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 15:42:52.560  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.560  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.560  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.560  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.560  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.560  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.561  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.561  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.561  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.561  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.561  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.561  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.561  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.561  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.562  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.562  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.562  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.562  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.563  3844  3895 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 15:42:52.563  3844  3895 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 15:42:52.563  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:52.563  3844  3895 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 15:42:52.563  3844  3895 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 15:42:52.563  3844  3895 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 15:42:52.563  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:52.563  3844  3895 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 15:42:52.563  3844  3895 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 15:42:52.563  3844  3895 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 15:42:52.564  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:52.564  3844  3895 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 15:42:52.564  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.564  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:42:52.564  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.564  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.564  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.564  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.564  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.564  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-26 15:42:52.564  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list,
08-26 15:42:52.564  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.564  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.564  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.564  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.564  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.565  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.565  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.566  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:52.566  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.566  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.566  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:52.566  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.566  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.566  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:52.566  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.566  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:42:52.566  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.566  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.567  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:52.567  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.567  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:52.567  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:52.567  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.567  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
,08-26 15:42:52.567  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.567  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 15:42:52.567  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:52.567  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.567  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.567  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:52.567  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.567  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:52.568  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.568  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:42:52.568  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.568  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:52.568  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.568  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:52.569  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.569  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.569  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:52.569  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.570  3844  3895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 15:42:52.570  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:52.571  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-26 15:42:52.572  3844  3895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 15:42:52.572  3844  3895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 15:42:52.572  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-26 15:42:52.572  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 15:42:52.572  3844  3844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 15:42:52.572  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.572  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 15:42:52.572  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-26 15:42:52.572  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 15:42:52.573  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.573  3844  3911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:42:52.573  3844  3895 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-26 15:42:52.573  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.573  3844  3844 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 15:42:52.573  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:52.573  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:42:52.573  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:42:52.573  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 15:42:52.573  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.573  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:42:52.574  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:52.574  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.574  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.574  3844  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 15:42:52.574  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:42:52.574  3844  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 15:42:52.574  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.574  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:42:52.574  3844  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 15:42:52.574  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-26 15:42:52.574  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:42:52.574  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.574  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:52.574  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.574  3844  3844 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 15:42:52.574  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.575  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 15:42:52.575  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.575  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.575  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.575  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.575  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.575  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.576  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.576  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:42:52.576  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.576  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
,08-26 15:42:52.577  3844  3895 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-26 15:42:52.577  3844  3895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 15:42:52.578  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 15:42:52.578  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 15:42:52.578  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:42:52.578  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.578  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:42:52.578  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:42:52.578  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:42:52.578  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.578  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.578  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.578  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.578  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.578  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.578  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.578  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.579  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.580  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.580  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:42:52.580  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.580  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.582  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.582  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.582  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.582  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.582  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.582  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.582  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.582  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.582  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.582  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:42:52.582  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.582  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.583  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.583  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.584  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.584  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:42:52.584  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.584  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.584  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:42:52.584  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:42:52.584  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:42:52.584  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:42:52.584  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.585  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.585  3844  3895 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac9a4ec not in the list
08-26 15:42:52.585  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.585  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.585  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:42:52.585  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.585  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.585  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:42:52.585  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:42:52.585  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:42:52.585  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:42:52.585  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:42:52.586  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a350b5 not in the list
08-26 15:42:52.586  3844  3895 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 15:42:52.586  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:52.586  3844  3895 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 15:42:52.586  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 15:42:52.586  3844  3895 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 15:42:52.586  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 15:42:52.588  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-26 15:42:52.588  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 15:42:52.588  3844  3895 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-26 15:42:52.588  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 15:42:52.588  3844  3895 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-26 15:42:52.588  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-26 15:42:52.588  3844  3895 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 15:42:52.588  3844  3895 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 15:42:52.589  3844  3895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 15:42:52.589  3844  3895 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 15:42:52.589  3844  3895 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 15:42:52.589  3844  3895 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-26 15:42:52.589  3844  3895 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 15:42:52.589  3844  3895 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 15:42:52.590  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:42:52.590  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1336a8f added. We now have 2 listener(s)
08-26 15:42:52.590  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:42:52.591  3844  3895 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 15:42:52.592   875   886 D WifiService: setWifiEnabled: true pid=3844, uid=10000
08-26 15:42:52.592   875   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 15:42:52.593  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:52.593  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6f6211c added. We now have 3 listener(s)
,08-26 15:42:52.593  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:52.596  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:42:52.596  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c8ad125 added. We now have 4 listener(s)
08-26 15:42:52.596  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:42:52.597  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:42:52.597  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a7282fa added. We now have 5 listener(s)
08-26 15:42:52.597  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:42:52.599   875  1988 D WifiService: setWifiEnabled: false pid=3844, uid=10000
08-26 15:42:52.599   875  1988 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 15:42:52.603  2637  2671 D BluetoothAdapterState: Current state: ON, message: 23
08-26 15:42:52.603  2637  2671 D BluetoothAdapterProperties: Setting state to 13
08-26 15:42:52.603  2637  2671 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 15:42:52.603  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:42:52.603  2637  2671 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 15:42:52.604  2637  2671 I BluetoothAdapterState: Entering PendingCommandState
08-26 15:42:52.606  2637  2637 D BluetoothMapService: onReceive
08-26 15:42:52.606  2637  2637 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:42:52.606  2637  2637 D BluetoothMapService: STATE_TURNING_OFF
08-26 15:42:52.606  2637  2637 D BluetoothMapService: MAP Service closeService in
,08-26 15:42:52.606  2637  2637 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 15:42:52.606  2637  2637 D ObexServerSockets0: shutdown(block = true)
08-26 15:42:52.607  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.607  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:42:52.607  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.607  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.607  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:52.607  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.607  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.607  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:52.607  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:52.607  2637  2637 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-26 15:42:52.607  2637  2637 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 15:42:52.607  2637  2779 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 15:42:52.607  2637  2778 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 15:42:52.607  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.607  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.608  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:42:52.608  2637  2764 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 15:42:52.608  2637  2637 I BtOppRfcommListener: stopping Accept Thread
08-26 15:42:52.608  2637  3418 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 15:42:52.609  2637  3418 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 15:42:52.610  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.613  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.616  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.616  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:52.616  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.616  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.616  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:52.616  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.616  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.616  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:52.616  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:52.617  1450  1450 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 15:42:52.617  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:52.617  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:52.618   875  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 15:42:52.618   875  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 15:42:52.619   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 15:42:52.619   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:42:52.620  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.622   875   888 I ActivityManager: Start proc 3914:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-26 15:42:52.622  2637  2675 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:42:52.626  2637  2671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 15:42:52.630  2637  2637 D HeadsetService: Received stop request...Stopping profile...
08-26 15:42:52.630   875  1877 D DhcpClient: Clearing IP address
08-26 15:42:52.631   371   873 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:52.631  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.632  1354  1365 D BluetoothHeadset: Proxy object disconnected
08-26 15:42:52.632   875   875 D BluetoothHeadset: Proxy object disconnected
08-26 15:42:52.632   875   875 D BluetoothHeadset: Proxy object disconnected
08-26 15:42:52.632   875   875 D BluetoothHeadset: Proxy object disconnected
08-26 15:42:52.633  1922  1936 D BluetoothHeadset: Proxy object disconnected
08-26 15:42:52.633  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.634  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-26 15:42:52.634  2637  2637 D A2dpService: Received stop request...Stopping profile...
,08-26 15:42:52.635  2637  2771 D A2dpStateMachine: Exit Disconnected: -1
08-26 15:42:52.636  1501  2147 V NativeCrypto: Read error: ssl=0xaec90c00: I/O error during system call, Connection timed out
08-26 15:42:52.636   875   875 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:52.637  2637  2637 D HidService: Received stop request...Stopping profile...
08-26 15:42:52.637  2637  2637 D HidService: Stopping Bluetooth HidService
,08-26 15:42:52.637  1501  2147 V NativeCrypto: SSL shutdown failed: ssl=0xaec90c00: I/O error during system call, Broken pipe
,08-26 15:42:52.639  2637  2637 D HealthService: Received stop request...Stopping profile...
08-26 15:42:52.639   875  1384 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-26 15:42:52.640   875  1860 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-26 15:42:52.641   371   873 D CommandListener: Setting iface cfg
08-26 15:42:52.642  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-26 15:42:52.642  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-26 15:42:52.642  1354  1354 D HidProfile: Bluetooth service disconnected
08-26 15:42:52.642   875  1878 D DhcpClient: Receive thread stopped
,08-26 15:42:52.643   875  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-26 15:42:52.643  2637  2637 D PanService: Received stop request...Stopping profile...
08-26 15:42:52.644   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 15:42:52.644   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 15:42:52.644   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-26 15:42:52.644   875  1860 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-26 15:42:52.646   400   400 E Parcel  : Reading a NULL string not supported here.
08-26 15:42:52.647   875  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-26 15:42:52.649  2637  2637 V BluetoothAdapterState: isTurningOff()=true
08-26 15:42:52.650  2637  2637 V BluetoothAdapterState: isTurningOn()=false
08-26 15:42:52.650  2637  2637 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:42:52.650  2637  2637 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:42:52.651  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:42:52.651  1354  1354 D PanProfile: Bluetooth service disconnected
,08-26 15:42:52.653  2637  2637 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 15:42:52.653  2637  2637 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 15:42:52.653  2637  2675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 15:42:52.654  2637  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 15:42:52.654  2637  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 15:42:52.654  2637  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 15:42:52.654  2637  2675 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-26 15:42:52.654  2637  2637 D BluetoothMapService: Received stop request...Stopping profile...
08-26 15:42:52.658  2637  2637 D BluetoothMapService: stop()
,08-26 15:42:52.659  2637  2637 D BluetoothMapAppObserver: deinitObservers()
08-26 15:42:52.659  2637  2637 D BluetoothMapAppObserver: removeReceiver()
08-26 15:42:52.660  2637  2637 V BluetoothAdapterState: isTurningOff()=true
08-26 15:42:52.660  2637  2637 V BluetoothAdapterState: isTurningOn()=false
08-26 15:42:52.660  2637  2637 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 15:42:52.660  2637  2637 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:42:52.662  2637  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 15:42:52.662  2637  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 15:42:52.662  2637  2722 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:52.662  2637  2722 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:42:52.662  2637  2722 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:42:52.662  2637  2722 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 15:42:52.662  2637  2675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 15:42:52.662  2637  2637 V BluetoothAdapterState: isTurningOff()=true
08-26 15:42:52.662  2637  2637 V BluetoothAdapterState: isTurningOn()=false
08-26 15:42:52.662  2637  2637 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:42:52.662  2637  2637 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:42:52.662  2637  2637 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-26 15:42:52.663  2637  2637 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 15:42:52.663  2637  2675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 15:42:52.663  2637  2637 V BluetoothAdapterState: isTurningOff()=true
08-26 15:42:52.663  2637  2637 V BluetoothAdapterState: isTurningOn()=false
08-26 15:42:52.663  2637  2637 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 15:42:52.663  2637  2637 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:42:52.663  2637  2637 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 15:42:52.663  2637  2675 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 15:42:52.664  2637  2637 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 15:42:52.664  2637  2637 V BluetoothAdapterState: isTurningOff()=true
,08-26 15:42:52.664  2637  2637 V BluetoothAdapterState: isTurningOn()=false
08-26 15:42:52.664  2637  2637 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 15:42:52.664  2637  2637 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:42:52.664  2637  2637 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 15:42:52.664  2637  2637 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 15:42:52.665  2637  2637 D BluetoothMapService: MAP Service closeService in
,08-26 15:42:52.665  2637  2637 V BluetoothAdapterState: isTurningOff()=true
08-26 15:42:52.665  2637  2637 V BluetoothAdapterState: isTurningOn()=false
08-26 15:42:52.666  2637  2637 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:42:52.666  2637  2637 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:42:52.666  2637  2637 D BluetoothMapService: cleanup()
08-26 15:42:52.666  2637  2637 D BluetoothMapService: MAP Service closeService in
,08-26 15:42:52.666  2637  2671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 15:42:52.666  2637  2671 D BluetoothAdapterProperties: Setting state to 15
08-26 15:42:52.666  2637  2671 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 15:42:52.667   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:42:52.667  1354  2000 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 15:42:52.668  2637  2671 I BluetoothAdapterState: Entering BleOnState
,08-26 15:42:52.668   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:42:52.668  1354  1365 D BluetoothPan: onBluetoothStateChange on: false
08-26 15:42:52.668  1354  1371 D BluetoothMap: onBluetoothStateChange: up=false
08-26 15:42:52.669  1354  2000 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 15:42:52.669   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:42:52.669  1354  1365 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:42:52.669  1922  1938 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 15:42:52.670  1354  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:42:52.670   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:42:52.670  2637  2671 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 15:42:52.670  2637  2671 D BluetoothAdapterProperties: Setting state to 16
08-26 15:42:52.671  2637  2671 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 15:42:52.672  2637  2671 D BluetoothAdapterProperties: onBleDisable
08-26 15:42:52.672  2637  2671 I BluetoothAdapterState: Entering PendingCommandState
08-26 15:42:52.672  2637  2672 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-26 15:42:52.673  2637  2675 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:42:52.673  2637  2722 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 15:42:52.673  2637  2722 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 15:42:52.677  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.677  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:52.677  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.677  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.677  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:52.677  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.677  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:52.677  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:52.677  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:52.678  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.678  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:52.679  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.680  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:52.680  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.680  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.680  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:52.680  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.680  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:52.680  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:52.680  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:52.680  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.680  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:52.681  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.682  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:52.686   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-26 15:42:52.691  3914  3914 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 15:42:52.701  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:42:52.705   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ca45950:true
,08-26 15:42:52.707  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:42:52.709   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 15:42:52.709   371   873 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:52.710   875  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 15:42:52.710   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:52.721   875  2114 I ActivityManager: Start proc 3931:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 15:42:52.724   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 15:42:52.727  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:52.727   875  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 15:42:52.728  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:52.728  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.728  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.728  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:52.728  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.728  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:52.728  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:52.728  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:52.728  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.728  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:52.732   875   892 D Tethering: MasterInitialState.processMessage what=3
08-26 15:42:52.734  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.734  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:52.734  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:52.734  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:52.734  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:52.734  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:52.734  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:52.734  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:52.734  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:52.735  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:52.735  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:42:52.736  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.737  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:52.737  3409  3409 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7de4d1c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-26 15:42:52.740  2133  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:52.760  3914  3914 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 15:42:52.762  3914  3914 D BluetoothMap: Create BluetoothMap proxy object
,08-26 15:42:52.767  3931  3931 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 15:42:52.773  3914  3914 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 15:42:52.789  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:52.790   371   873 E Netd    : netlink response contains error (No such file or directory)
,08-26 15:42:52.791   875  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 15:42:52.796   875  2115 I ActivityManager: Killing 3567:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-26 15:42:52.875  2637  2675 I bt_hci  : shut_down
,08-26 15:42:52.875  2637  2679 D bt_hwcfg: hw_epilog_process
,08-26 15:42:52.880  2637  2679 I bt_vendor: low_power_mode_cb
,08-26 15:42:52.910  2637  2679 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 15:42:52.910  2637  2679 I bt_vendor: epilog_cb
08-26 15:42:52.910  2637  2679 I bt_hci  : epilog_finished_callback
,08-26 15:42:52.918  2637  2675 I bt_hci_h4: hal_close
,08-26 15:42:52.918  2637  2675 I bt_userial_vendor: device fd = 51 close
,08-26 15:42:52.992  3931  3931 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 15:42:52.992  3931  3931 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 15:42:52.992  3931  3931 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 15:42:52.992  3931  3931 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 15:42:52.992  3931  3931 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 15:42:52.992  3931  3931 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 15:42:52.992  3931  3931 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 15:42:52.992  3931  3931 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:42:52.992  3931  3931 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 15:42:53.020   875  1994 I ActivityManager: Start proc 3965:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-26 15:42:53.021   875  1994 I ActivityManager: Killing 3409:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 15:42:53.075  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:42:53.086  3931  3954 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 15:42:53.100   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8721375:true
,08-26 15:42:53.156  3965  3965 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-26 15:42:53.219  2637  2672 D bt_stack_manager: event_shut_down_stack finished.
,08-26 15:42:53.222  2637  2671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 15:42:53.226  2637  2637 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 15:42:53.225  2637  2671 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 15:42:53.226  2637  2637 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 15:42:53.226  2637  2637 D BtGatt.GattService: stop()
,08-26 15:42:53.226  2637  2637 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 15:42:53.228  2637  2637 V BluetoothAdapterState: isTurningOff()=false
,08-26 15:42:53.228  2637  2637 V BluetoothAdapterState: isTurningOn()=false
,08-26 15:42:53.228  2637  2637 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:42:53.228  2637  2637 V BluetoothAdapterState: isBleTurningOff()=true
,08-26 15:42:53.229  2637  2671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 15:42:53.229  2637  2671 D BluetoothAdapterProperties: Setting state to 10
,08-26 15:42:53.229  2637  2671 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 15:42:53.231   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-26 15:42:53.232  2637  2671 I BluetoothAdapterState: Entering OffState
,08-26 15:42:53.244  2637  2637 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-26 15:42:53.244  2637  2637 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 15:42:53.244  2637  2637 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 15:42:53.245  2637  2672 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-26 15:42:53.247  2637  2672 D bt_stack_manager: event_clean_up_stack finished.
,08-26 15:42:53.254  2637  2637 I art     : System.exit called, status: 0
,08-26 15:42:53.254  2637  2637 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 15:42:53.318   875  2115 I ActivityManager: Process com.android.bluetooth (pid 2637) has died
,08-26 15:42:53.432  3965  3985 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 15:42:53.432  3965  3985 I Babel_SMS: MmsConfig.loadMmsSettings
,08-26 15:42:53.436  3965  3985 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
08-26 15:42:53.436  3965  3985 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 15:42:53.486  3965  3985 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-26 15:42:53.486  3965  3985 I Babel_SMS: MmsConfig.loadFromResources
08-26 15:42:53.487  3965  3985 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 15:42:53.488  3965  3985 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-26 15:42:53.530  3965  3965 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:53.534  3965  3965 I Babel_Crash: startup - clean
,08-26 15:42:53.550  3965  3965 I Babel_telephony: TeleModule.launchCompleted
,08-26 15:42:53.566   875  1700 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-26 15:42:53.581  3965  3965 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-26 15:42:53.588  3965  3965 W Babel   : BAM#gBA: invalid account id: -1
,08-26 15:42:53.588  3965  3965 W Babel   : BAM#gBA: invalid account id: -1
08-26 15:42:53.588  3965  3965 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-26 15:42:53.594   875  2114 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-26 15:42:53.595  3965  3990 I Babel   : deleted: false for 0
,08-26 15:42:53.632  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:42:53.669   875   885 I ActivityManager: Start proc 3993:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-26 15:42:53.671  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:42:53.690  3965  3965 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:53.754  3965  3965 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 15:42:53.775  3965  3965 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:53.777  3965  3965 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:53.782  3965  3965 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:53.801  3965  3965 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 15:42:53.810  3965  3965 I vclib   : onServiceConnected
,08-26 15:42:53.836  3993  3993 D AdapterServiceConfig: Adding HeadsetService
,08-26 15:42:53.836  3993  3993 D AdapterServiceConfig: Adding A2dpService
08-26 15:42:53.836  3993  3993 D AdapterServiceConfig: Adding HidService
08-26 15:42:53.836  3993  3993 D AdapterServiceConfig: Adding HealthService
,08-26 15:42:53.837  3993  3993 D AdapterServiceConfig: Adding PanService
08-26 15:42:53.837  3993  3993 D AdapterServiceConfig: Adding GattService
,08-26 15:42:53.837  3993  3993 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 15:42:53.841   875  1700 I ActivityManager: Killing 3461:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 15:42:53.890  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:42:53.924  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 15:42:53.928  1730  1730 D SystemUpdateService: onCreate
,08-26 15:42:53.933  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 15:42:53.940  1730  4006 I SystemUpdateService: active receiver: enabled
,08-26 15:42:53.948  1730  4006 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 15:42:53.954  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-26 15:42:53.954  1730  4006 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 15:42:53.955  1730  4006 I SystemUpdateService: now status is 0 (complete)
,08-26 15:42:53.955  1730  4006 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 15:42:53.955  1730  4006 I SystemUpdateService: file has been verified
08-26 15:42:53.956  1730  4006 I SystemUpdateService: OTA package size = 12249756
,08-26 15:42:53.967  1730  2425 I iu.UploadsManager: num queued entries: 0
08-26 15:42:53.968  1730  2425 I iu.UploadsManager: num updated entries: 0
08-26 15:42:53.968  1730  2425 I iu.SyncManager: NEXT; no task
,08-26 15:42:53.971  1730  4006 I SystemUpdateService: showing system update notification
,08-26 15:42:53.978  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 15:42:53.979  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 15:42:54.009   875  1990 I ActivityManager: Start proc 4008:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 15:42:54.010  1730  1730 D SystemUpdateService: onDestroy
,08-26 15:42:54.057  4008  4008 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 15:42:54.060  4008  4008 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:54.065  4008  4008 D SprintDMHelper: simOperator: 
08-26 15:42:54.066  4008  4008 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 15:42:54.084   875  1385 I ActivityManager: Start proc 4020:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-26 15:42:54.085   875  1385 I ActivityManager: Killing 3497:android.process.acore/u0a5 (adj 15): empty #17
,08-26 15:42:54.244   875  2115 I ActivityManager: Start proc 4035:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 15:42:54.249  3965  4034 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 15:42:54.252   875   885 I ActivityManager: Killing 3655:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 15:42:54.298  4035  4035 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 15:42:54.349  4035  4035 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 15:42:54.349  4035  4035 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 15:42:54.349  4035  4035 I GAv4    :   adb logcat -s GAv4
,08-26 15:42:54.373  4035  4035 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 15:42:54.380  4035  4035 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 15:42:54.414  4035  4052 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 15:42:54.530  4035  4035 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 15:42:54.574  4035  4035 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 15:42:54.583  4035  4035 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8569-8572)
,08-26 15:42:54.583  4035  4035 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 15:42:54.598  4035  4035 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c5d354c}
,08-26 15:42:54.599  4035  4035 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 15:42:54.599  4035  4035 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 15:42:54.612  4035  4035 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 15:42:54.614  4035  4035 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 15:42:54.633  4035  4035 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 15:42:54.646  4035  4035 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 15:42:54.646  4035  4035 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 15:42:54.646  4035  4035 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 15:42:54.646  4035  4035 I Adreno  : Build Date                       : 10/20/15
08-26 15:42:54.646  4035  4035 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 15:42:54.646  4035  4035 I Adreno  : Local Branch                     : M14
08-26 15:42:54.646  4035  4035 I Adreno  : Remote Branch                    : 
08-26 15:42:54.646  4035  4035 I Adreno  : Remote Branch                    : 
08-26 15:42:54.646  4035  4035 I Adreno  : Reconstruct Branch               : 
,08-26 15:42:54.719  4035  4035 I NSApplication: Starting up...
,08-26 15:42:54.728  4035  4081 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 15:42:54.763   875  1994 I ActivityManager: Start proc 4086:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 15:42:54.764   875  1994 I ActivityManager: Killing 3672:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 15:42:54.861  4086  4086 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 15:42:55.056   875  1700 I ActivityManager: Killing 2229:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 15:42:55.077  3554  3563 W art     : Suspending all threads took: 9.727ms
,08-26 15:42:55.610   875  1700 D WifiService: setWifiEnabled: true pid=3844, uid=10000
,08-26 15:42:55.610   875  1700 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 15:42:55.626   875  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-26 15:42:55.631  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:55.631  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:55.631  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:55.631  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:55.631  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:55.631  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:55.631  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:55.631  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:55.631  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:55.632  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:55.632  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:55.635  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:55.635  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:55.635  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:55.635  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:55.635  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:55.635  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:55.635  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:55.635  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:55.635  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:55.636  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:55.636  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:55.668   875  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-26 15:42:55.671   875  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 15:42:55.673   875  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 15:42:55.676   875  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 15:42:55.676   875  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-26 15:42:55.677   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 15:42:55.677   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 15:42:55.699   371   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 15:42:55.701   371   873 D CommandListener: Setting iface cfg
,08-26 15:42:55.701   875  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.88 rxSuccessRate=14.50 delta 1000 -> 994
,08-26 15:42:55.702   875  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-26 15:42:55.702   875  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 15:42:55.707   875  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 15:42:55.707   875  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 15:42:55.741   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 15:42:55.741   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:42:55.748   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 15:42:55.806   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 15:42:55.809  1450  1450 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 15:42:56.239  1450  1450 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 15:42:56.282  1450  1450 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 15:42:56.283  1450  1450 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 15:42:56.285   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 15:42:56.297   875  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-26 15:42:56.297   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:42:56.297   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 15:42:56.322   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:42:56.342   371   873 D CommandListener: Setting iface cfg
,08-26 15:42:56.343   875  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 15:42:56.366   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 15:42:56.366   875  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 15:42:56.369   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 15:42:56.381   875  4112 D DhcpClient: Receive thread started
,08-26 15:42:56.464   875  1308 E native  : do suspend false
,08-26 15:42:56.483   875  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 15:42:56.518   875  4112 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172682, domain null
,08-26 15:42:56.519   875  1877 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172682 seconds
,08-26 15:42:56.524   875  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 15:42:56.608   875  4112 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 15:42:56.609   875  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 15:42:56.618   371   873 D CommandListener: Setting iface cfg
,08-26 15:42:56.629   875  1877 D DhcpClient: Scheduling renewal in 86399s
,08-26 15:42:56.630   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 15:42:56.644   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 15:42:56.648   875  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 15:42:56.654   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 15:42:56.657   875  1310 D ConnectivityService: Adding iface wlan0 to network 101
08-26 15:42:56.669   875  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 15:42:56.728   875  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 15:42:56.729   875  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 15:42:56.730   875  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 15:42:56.731   875  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 15:42:56.732   875  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 15:42:56.744   875  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 15:42:56.751   875  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 15:42:56.752   875  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-26 15:42:56.752   875  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 15:42:56.752   875  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-26 15:42:56.752   875  1310 D ConnectivityService:    accepting network in place of null
08-26 15:42:56.752   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 15:42:56.754   875  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -62]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 15:42:56.784   875  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=140774, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 15:42:56.785   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0,
,08-26 15:42:56.829   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 15:42:56.836   875  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 15:42:56.836   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:42:56.838   875  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 15:42:56.842   875   892 D Tethering: MasterInitialState.processMessage what=3
08-26 15:42:56.850  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:56.850  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:56.850  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:56.850  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:56.850  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:56.850  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:56.850  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:56.850  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:56.850  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:56.850  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:56.850  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:56.856  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:56.856  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:56.856  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:56.856  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:56.856  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:42:56.856  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:56.856  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:56.856  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:42:56.856  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:42:56.856  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:56.856  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:42:56.863   875  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:816::200e
,08-26 15:42:56.870  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 15:42:56.873  1730  1730 D SystemUpdateService: onCreate
,08-26 15:42:56.875  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 15:42:56.878  1730  4122 I SystemUpdateService: active receiver: enabled
,08-26 15:42:56.884  1730  4122 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 15:42:56.886  1730  4122 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 15:42:56.886  1730  4122 I SystemUpdateService: now status is 0 (complete)
08-26 15:42:56.886  1730  4122 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 15:42:56.886  1730  4122 I SystemUpdateService: file has been verified
,08-26 15:42:56.887  1730  4122 I SystemUpdateService: OTA package size = 12249756
,08-26 15:42:56.890  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 15:42:56.892  1730  4122 I SystemUpdateService: showing system update notification
,08-26 15:42:56.894  1730  2425 I iu.UploadsManager: num queued entries: 0
08-26 15:42:56.894  1730  2425 I iu.UploadsManager: num updated entries: 0
08-26 15:42:56.896  1730  2425 I iu.SyncManager: NEXT; no task
,08-26 15:42:56.898  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 15:42:56.899  1730  4127 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 15:42:56.899  1730  4127 W BaseAppContext: Using Auth Proxy for data requests.
08-26 15:42:56.899  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-26 15:42:56.900  1730  4127 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
08-26 15:42:56.901  4008  4008 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:56.905  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:42:56.906  4008  4008 D SprintDMHelper: simOperator: 
08-26 15:42:56.906  4008  4008 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-26 15:42:56.906  1730  1730 D SystemUpdateService: onDestroy
08-26 15:42:56.907  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:42:56.937  1501  2255 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 15:42:56.937  1501  2255 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 15:42:56.937  1501  2255 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 15:42:56.937  1501  2255 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 15:42:56.953  1730  4127 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-26 15:42:56.978   875  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 13:42:56 GMT], X-Android-Received-Millis=[1472218976977], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472218976918]}
,08-26 15:42:56.978   875  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 15:42:56.979   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-26 15:42:56.979   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 15:42:56.981   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 15:42:57.090  3965  4129 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 15:42:57.837   875  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 15:42:58.414   875  1992 I ActivityManager: Killing 3694:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 15:42:58.511   875  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 9, 11 -> obsolete
,08-26 15:42:58.619   875  1988 D WifiService: setWifiEnabled: false pid=3844, uid=10000
,08-26 15:42:58.619   875  1988 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 15:42:58.656  1450  1450 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 15:42:58.662   875  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 15:42:58.662   875  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 15:42:58.663   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 15:42:58.663   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:42:58.681   875  1877 D DhcpClient: Clearing IP address
,08-26 15:42:58.682   371   873 D CommandListener: Clearing all IP addresses on wlan0
,08-26 15:42:58.687   371   873 D CommandListener: Setting iface cfg
,08-26 15:42:58.691  1501  4136 V NativeCrypto: Read error: ssl=0x99571600: I/O error during system call, Connection timed out
,08-26 15:42:58.693  1501  4136 V NativeCrypto: SSL shutdown failed: ssl=0x99571600: I/O error during system call, Broken pipe
,08-26 15:42:58.696   875  1384 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-26 15:42:58.697   875  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-26 15:42:58.698   875  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:816::200e
,08-26 15:42:58.707   875  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-26 15:42:58.708   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 15:42:58.709   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 15:42:58.709   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-26 15:42:58.715   371   873 D CommandListener: Clearing all IP addresses on wlan0
08-26 15:42:58.715   875  4112 D DhcpClient: Receive thread stopped
,08-26 15:42:58.717   400   400 E Parcel  : Reading a NULL string not supported here.
,08-26 15:42:58.724   875  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:816::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-26 15:42:58.725   875  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-26 15:42:58.726   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 15:42:58.729  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:58.729  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:58.729  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:58.729  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:58.729  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:58.729  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:58.729  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:58.729  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:58.729  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:42:58.729  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:58.729  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:58.730  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:42:58.730  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:42:58.730  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:42:58.730  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:42:58.730  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:42:58.730  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:42:58.730  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:42:58.730  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:42:58.730  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:42:58.731  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:42:58.731  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:42:58.731   875  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 15:42:58.736  2133  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 15:42:58.766   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 15:42:58.791   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 15:42:58.792   875  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 15:42:58.793   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:58.797  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:42:58.797  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:42:58.798   875   892 D Tethering: MasterInitialState.processMessage what=3,
,08-26 15:42:58.801  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 15:42:58.804  1730  1730 D SystemUpdateService: onCreate
,08-26 15:42:58.808  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 15:42:58.814  1730  4145 I SystemUpdateService: active receiver: enabled
,08-26 15:42:58.817  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 15:42:58.822  1730  2425 I iu.UploadsManager: num queued entries: 0
,08-26 15:42:58.823  1730  2425 I iu.UploadsManager: num updated entries: 0
08-26 15:42:58.823  1730  2425 I iu.SyncManager: NEXT; no task
,08-26 15:42:58.826  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 15:42:58.828  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 15:42:58.827  1730  4145 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 15:42:58.830  4008  4008 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:42:58.833  4008  4008 D SprintDMHelper: simOperator: 
08-26 15:42:58.833  4008  4008 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 15:42:58.853   371   873 E Netd    : netlink response contains error (No such file or directory)
,08-26 15:42:58.854  3965  4149 I Babel   : connection state changed from CONNECTED to DISCONNECTED
08-26 15:42:58.854   875  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 15:42:58.859  1730  4145 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-26 15:42:58.860  1730  4145 I SystemUpdateService: now status is 0 (complete)
,08-26 15:42:58.860  1730  4145 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 15:42:58.860  1730  4145 I SystemUpdateService: file has been verified
08-26 15:42:58.860  1730  4145 I SystemUpdateService: OTA package size = 12249756
,08-26 15:42:58.866  1730  4145 I SystemUpdateService: showing system update notification
,08-26 15:42:58.874  1730  1730 D SystemUpdateService: onDestroy
,08-26 15:43:01.661   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1fbd201:true
08-26 15:43:01.661  3993  3993 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 15:43:01.666  3993  3993 I bt_bluedroid: init
,08-26 15:43:01.667  3993  4152 I BluetoothAdapterState: Entering OffState
,08-26 15:43:01.670  3993  4153 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 15:43:01.670  3993  4153 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 15:43:01.671  3993  4153 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 15:43:01.671  3993  4153 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 15:43:01.672  3993  3993 I bt_bluedroid: get_profile_interface socket
,08-26 15:43:01.676  3993  3993 I bt_bluedroid: get_profile_interface sdp
,08-26 15:43:01.677  3993  4156 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 15:43:01.680  3993  4004 I bt_bluedroid: config_hci_snoop_log
,08-26 15:43:01.680  3993  4156 D BluetoothAdapterProperties: Name is: Nexus 6
08-26 15:43:01.682   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 15:43:01.689  3993  4152 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 15:43:01.690  3993  4152 D BluetoothAdapterProperties: Setting state to 14
08-26 15:43:01.690  3993  4152 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 15:43:01.694  3993  4152 D BluetoothBondStateMachine: make
,08-26 15:43:01.698  3993  4157 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 15:43:01.703  3993  4152 I BluetoothAdapterState: Entering PendingCommandState
,08-26 15:43:01.704  3993  3993 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 15:43:01.708  3993  3993 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:01.709  3993  3993 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:43:01.710  3993  3993 D BtGatt.GattService: Received start request. Starting profile...
,08-26 15:43:01.710  3993  3993 D BtGatt.GattService: start()
,08-26 15:43:01.710  3993  3993 I bt_bluedroid: get_profile_interface gatt
08-26 15:43:01.711  3993  3993 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:01.711  3993  3993 D BtGatt.AdvertiseManager: advertise manager created
,08-26 15:43:01.723  3993  3993 V BluetoothAdapterState: isTurningOff()=false
,08-26 15:43:01.723  3993  3993 V BluetoothAdapterState: isTurningOn()=false
08-26 15:43:01.723  3993  3993 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 15:43:01.724  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 15:43:01.725  3993  4152 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 15:43:01.726  3993  4152 I bt_bluedroid: enable
,08-26 15:43:01.726  3993  4153 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 15:43:01.727  3993  4153 I bt_hci  : start_up
,08-26 15:43:01.735  3993  4153 I bt_vendor: alloc value 0xb3979189
,08-26 15:43:01.735  3993  4153 I bt_vendor: init
08-26 15:43:01.735  3993  4153 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-26 15:43:01.735  3993  4153 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 15:43:01.842  3993  4153 D bt_hci  : start_up starting async portion
,08-26 15:43:01.843  3993  4160 I bt_hci  : event_finish_startup
,08-26 15:43:01.843  3993  4160 I bt_hci_h4: hal_open
08-26 15:43:01.843  3993  4160 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 15:43:01.850  3993  4160 I bt_userial_vendor: device fd = 51 open
,08-26 15:43:01.884  3993  4160 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 15:43:01.916  3993  4160 D bt_hwcfg: Chipset BCM4354A2
,08-26 15:43:01.917  3993  4160 D bt_hwcfg: Target name = [BCM4354A2]
08-26 15:43:01.917  3993  4160 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 15:43:02.605  3993  4160 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-26 15:43:02.607  3993  4160 D bt_hwcfg: Settlement delay -- 100 ms
,08-26 15:43:02.607  3993  4160 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 15:43:02.724  3993  4160 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 15:43:02.725  3993  4160 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 15:43:02.754  3993  4160 I bt_hwcfg: vendor lib fwcfg completed
,08-26 15:43:02.754  3993  4160 I bt_vendor: firmware callback
,08-26 15:43:02.755  3993  4160 I bt_hci  : firmware_config_callback
,08-26 15:43:02.770  3993  4164 I bt_btu  : btu_task pending for preload complete event
08-26 15:43:02.771  3993  4164 I bt_btu_task: Bluetooth chip preload is complete
08-26 15:43:02.771  3993  4164 I bt_btu  : btu_task received preload complete event
,08-26 15:43:02.780  3993  4164 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 15:43:02.780  3993  4164 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 15:43:02.781  3993  4164 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 15:43:02.781  3993  4164 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 15:43:02.781  3993  4164 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 15:43:02.781  3993  4164 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 15:43:02.782  3993  4164 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 15:43:02.782  3993  4164 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 15:43:02.782  3993  4164 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 15:43:02.782  3993  4164 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 15:43:02.783  3993  4164 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 15:43:02.783  3993  4164 I         : BTE_InitTraceLevels -- TRC_GATT
,08-26 15:43:02.783  3993  4164 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 15:43:02.783  3993  4164 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 15:43:02.784  3993  4164 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 15:43:02.911  3993  4164 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38f6d9d
,08-26 15:43:02.911  3993  4164 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38f6d9d 
,08-26 15:43:02.938  3993  4156 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 15:43:02.939  3993  4156 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 15:43:02.940  3993  4156 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 15:43:02.943  3993  4156 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 15:43:02.946  3993  4156 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:43:02.947  3993  4156 D BluetoothAdapterProperties: Discoverable Timeout:120,
08-26 15:43:02.948  3993  4156 D bt_hci  : do_postload posting postload work item
,08-26 15:43:02.948  3993  4160 I bt_hci  : event_postload
,08-26 15:43:02.948  3993  4160 I bt_vendor: sco_config_cb
08-26 15:43:02.948  3993  4160 I bt_hci  : sco_config_callback postload finished.
,08-26 15:43:02.951  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:02.952  3993  4156 D bt_bte_conf: Device ID record 1 : primary
08-26 15:43:02.952  3993  4156 D bt_bte_conf:   vendorId            = 000f
08-26 15:43:02.952  3993  4156 D bt_bte_conf:   vendorIdSource      = 0001
08-26 15:43:02.952  3993  4156 D bt_bte_conf:   product             = 1200
08-26 15:43:02.952  3993  4156 D bt_bte_conf:   version             = 1436
,08-26 15:43:02.952  3993  4156 D bt_bte_conf:   clientExecutableURL = 
,08-26 15:43:02.952  3993  4156 D bt_bte_conf:   serviceDescription  = 
08-26 15:43:02.952  3993  4156 D bt_bte_conf:   documentationURL    = 
08-26 15:43:02.952  3993  4156 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-26 15:43:02.953  3993  4153 D bt_stack_manager: event_start_up_stack finished
08-26 15:43:02.953  3993  4160 I bt_vendor: low_power_mode_cb
08-26 15:43:02.954  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:02.954  3993  4152 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 15:43:02.954  3993  4152 D BluetoothAdapterProperties: Setting state to 15
08-26 15:43:02.955  3993  4152 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 15:43:02.956  3993  4152 I BluetoothAdapterState: Entering BleOnState
08-26 15:43:02.960  3993  4152 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-26 15:43:02.960  3993  4152 D BluetoothAdapterProperties: Setting state to 11
08-26 15:43:02.960  3993  4152 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 15:43:02.973  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:02.975  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:02.986  3993  3993 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:02.988  3993  3993 D HeadsetService: Received start request. Starting profile...
,08-26 15:43:02.993  3993  3993 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 15:43:02.993  3993  3993 D HeadsetStateMachine: make
08-26 15:43:02.996  3993  4152 I BluetoothAdapterState: Entering PendingCommandState
,08-26 15:43:03.001  3993  3993 D HeadsetStateMachine: max_hf_connections = 1
,08-26 15:43:03.001  3993  3993 I bt_bluedroid: get_profile_interface handsfree
08-26 15:43:03.002  3993  4156 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-26 15:43:03.002  3993  4156 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 15:43:03.005  3993  3993 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:03.005  3993  3993 D A2dpService: Received start request. Starting profile...
08-26 15:43:03.006  3993  3993 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 15:43:03.006  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 15:43:03.006  3993  3993 I bt_bluedroid: get_profile_interface avrcp
,08-26 15:43:03.013  3993  3993 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 15:43:03.013  3993  3993 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 15:43:03.013  3993  3993 D A2dpStateMachine: make
,08-26 15:43:03.015  3993  3993 I bt_bluedroid: get_profile_interface a2dp
,08-26 15:43:03.015  3993  4156 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 15:43:03.017  3993  4172 D A2dpStateMachine: Enter Disconnected: -2
,08-26 15:43:03.018  3993  3993 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 15:43:03.018  3993  3993 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:03.019  3993  3993 D HidService: Received start request. Starting profile...
08-26 15:43:03.020  3993  3993 I bt_bluedroid: get_profile_interface hidhost
08-26 15:43:03.020  3914  3914 D BluetoothInputDevice: Proxy object connected
08-26 15:43:03.020  3993  3993 D HidService: setHidService(): set to: null
,08-26 15:43:03.020  3993  3993 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 15:43:03.020  3993  4156 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38d83e5
08-26 15:43:03.020  3993  4156 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 15:43:03.021  3993  3993 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
08-26 15:43:03.021  3993  3993 D HealthService: Received start request. Starting profile...
,08-26 15:43:03.021  3914  3914 D HidProfile: Bluetooth service connected
,08-26 15:43:03.023  3993  3993 I bt_bluedroid: get_profile_interface health
08-26 15:43:03.023  3993  3993 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 15:43:03.024  3993  3993 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:03.025  3993  3993 D PanService: Received start request. Starting profile...
,08-26 15:43:03.025  3993  3993 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 15:43:03.025  3993  3993 I bt_bluedroid: get_profile_interface pan
,08-26 15:43:03.025  3914  3914 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 15:43:03.025  3993  4156 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 15:43:03.026  3914  3914 D PanProfile: Bluetooth service connected
08-26 15:43:03.029  3993  3993 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
08-26 15:43:03.030  3914  3914 D BluetoothMap: Proxy object connected
,08-26 15:43:03.030  3993  3993 D BluetoothMapService: Received start request. Starting profile...
08-26 15:43:03.030  3993  3993 D BluetoothMapService: start()
08-26 15:43:03.030  3914  3914 D MapProfile: Bluetooth service connected
,08-26 15:43:03.030  3914  3914 D BluetoothMap: getConnectedDevices()
08-26 15:43:03.031  3914  3914 D BluetoothMap: Bluetooth is Not enabled
,08-26 15:43:03.032  3993  3993 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 15:43:03.033  3993  3993 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-26 15:43:03.033  3993  3993 D BluetoothMapAppObserver: createReceiver()
08-26 15:43:03.034  3993  3993 D BluetoothMapAppObserver: initObservers()
,08-26 15:43:03.034  3993  3993 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 15:43:03.042  3993  3993 V BluetoothAdapterState: isTurningOff()=false
,08-26 15:43:03.042  3993  3993 V BluetoothAdapterState: isTurningOn()=true
08-26 15:43:03.042  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 15:43:03.042  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:03.044  3993  4170 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 15:43:03.044  3993  3993 V BluetoothAdapterState: isTurningOff()=false
08-26 15:43:03.044  3993  3993 V BluetoothAdapterState: isTurningOn()=true
08-26 15:43:03.044  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 15:43:03.044  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:03.044  3993  3993 V BluetoothAdapterState: isTurningOff()=false
08-26 15:43:03.044  3993  3993 V BluetoothAdapterState: isTurningOn()=true
08-26 15:43:03.044  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:03.044  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 15:43:03.045  3993  3993 V BluetoothAdapterState: isTurningOff()=false
08-26 15:43:03.045  3993  3993 V BluetoothAdapterState: isTurningOn()=true
08-26 15:43:03.045  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:03.045  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 15:43:03.045  3993  3993 V BluetoothAdapterState: isTurningOff()=false
,08-26 15:43:03.045  3993  3993 V BluetoothAdapterState: isTurningOn()=true
08-26 15:43:03.045  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:03.045  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 15:43:03.046  3993  3993 V BluetoothAdapterState: isTurningOff()=false
08-26 15:43:03.046  3993  3993 V BluetoothAdapterState: isTurningOn()=true
08-26 15:43:03.046  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:03.046  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:03.046  3993  4152 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 15:43:03.046  3993  4152 D BluetoothAdapterProperties: ScanMode =  20
08-26 15:43:03.046  3993  4152 D BluetoothAdapterProperties: State =  11
08-26 15:43:03.047  3993  4152 D BluetoothAdapterProperties: Setting state to 12
,08-26 15:43:03.047  3993  4152 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 15:43:03.047   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:03.048  3993  4152 I BluetoothAdapterState: Entering OnState
08-26 15:43:03.048  3914  3925 D BluetoothPan: onBluetoothStateChange on: true
08-26 15:43:03.048  1354  1371 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 15:43:03.049  3993  4156 D BluetoothAdapterProperties: Scan Mode:21
08-26 15:43:03.049  3993  4156 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 15:43:03.050   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:03.051  1354  1365 D BluetoothPan: onBluetoothStateChange on: true
,08-26 15:43:03.052  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:03.052  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:03.052  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:03.052  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:03.052  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:03.052  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:03.052  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:03.052  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:03.054  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:03.055  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 15:43:03.055  1354  1354 D PanProfile: Bluetooth service connected
,08-26 15:43:03.056  1354  1371 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 15:43:03.057  1354  1354 D BluetoothMap: Proxy object connected
,08-26 15:43:03.057  1354  1354 D MapProfile: Bluetooth service connected
,08-26 15:43:03.058  1354  1354 D BluetoothMap: getConnectedDevices()
,08-26 15:43:03.058  3914  3926 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 15:43:03.058  1354  1365 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 15:43:03.059  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:03.059  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:03.059  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:03.059  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:03.059  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:03.059  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:03.059  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:03.059  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:03.060  1354  1354 D BluetoothInputDevice: Proxy object connected
08-26 15:43:03.060   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:03.060  1354  1354 D HidProfile: Bluetooth service connected
08-26 15:43:03.060  1354  1371 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:03.061  1922  2088 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:03.061  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:03.061  3914  3925 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 15:43:03.062  3993  3993 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 15:43:03.062  3993  3993 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 15:43:03.063  3914  3926 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 15:43:03.063  1354  2000 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 15:43:03.064  3993  3993 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:03.064   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:03.066   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 15:43:03.068  3993  3993 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:03.068  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:03.069  3993  3993 D ObexServerSockets: Succeed to create listening sockets 
08-26 15:43:03.069  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:03.069  3993  3993 D ObexServerSockets0: startAccept()
08-26 15:43:03.069  3993  3993 D ObexServerSockets0: prepareForNewConnect()
08-26 15:43:03.071  3914  3914 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-26 15:43:03.073  3993  3993 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 15:43:03.073  3993  3993 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 15:43:03.074  3993  4182 D ObexServerSockets0: Accepting socket connection...
08-26 15:43:03.075  3993  3993 D BluetoothMapService: onReceive
08-26 15:43:03.075  3993  3993 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:03.075  3993  3993 D BluetoothMapService: STATE_ON
,08-26 15:43:03.075  3993  4181 D ObexServerSockets0: Accepting socket connection...
08-26 15:43:03.075   875   875 D BluetoothA2dp: Proxy object connected
08-26 15:43:03.075  1354  1354 D BluetoothA2dp: Proxy object connected
,08-26 15:43:03.077  3914  3914 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-26 15:43:03.083  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:43:03.086  3914  3914 D BluetoothA2dp: Proxy object connected
,08-26 15:43:03.090  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:03.095  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:03.099  3914  3914 D BluetoothPbap: Proxy object connected
,08-26 15:43:03.100  3914  3914 D PbapServerProfile: Bluetooth service connected
,08-26 15:43:03.101  1354  1354 D BluetoothPbap: Proxy object connected
08-26 15:43:03.101  1354  1354 D PbapServerProfile: Bluetooth service connected
,08-26 15:43:03.109  3993  3993 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 15:43:03.109  3993  3993 D ObexServerSockets0: prepareForNewConnect()
,08-26 15:43:03.113  3993  4186 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:03.131  3993  4190 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:03.133  3993  4190 I BtOppRfcommListener: Accept thread started.
,08-26 15:43:03.150  1354  2000 D BluetoothHeadset: Proxy object connected
08-26 15:43:03.150  1354  1354 D HeadsetProfile: Bluetooth service connected
08-26 15:43:03.150   875   875 D BluetoothHeadset: Proxy object connected
08-26 15:43:03.150   875   875 D BluetoothHeadset: Proxy object connected
08-26 15:43:03.150   875   875 D BluetoothHeadset: Proxy object connected
,08-26 15:43:03.151  1922  1938 D BluetoothHeadset: Proxy object connected
08-26 15:43:03.151   875   892 D BluetoothHeadset: Proxy object connected
,08-26 15:43:03.162  1354  1371 D BluetoothHeadset: Proxy object connected
,08-26 15:43:03.162  1354  1354 D HeadsetProfile: Bluetooth service connected
08-26 15:43:03.162  1922  1936 D BluetoothHeadset: Proxy object connected
,08-26 15:43:03.165   875   892 D BluetoothHeadset: Proxy object connected
,08-26 15:43:03.182  3914  3926 D BluetoothHeadset: Proxy object connected
,08-26 15:43:03.185  3914  3914 D HeadsetProfile: Bluetooth service connected
,08-26 15:43:04.637  3993  4152 D BluetoothAdapterState: Current state: ON, message: 23
,08-26 15:43:04.638  3993  4152 D BluetoothAdapterProperties: Setting state to 13
,08-26 15:43:04.638  3993  4152 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-26 15:43:04.640  3993  4152 D BluetoothAdapterProperties: onBluetoothDisable()
,08-26 15:43:04.643  3993  4152 I BluetoothAdapterState: Entering PendingCommandState
,08-26 15:43:04.649  3993  3993 D BluetoothMapService: onReceive
,08-26 15:43:04.649  3993  3993 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:04.650  3993  3993 D BluetoothMapService: STATE_TURNING_OFF
,08-26 15:43:04.650  3993  3993 D BluetoothMapService: MAP Service closeService in
08-26 15:43:04.651  3993  3993 D BluetoothMapMasInstance0: MAP Service shutdown,
,08-26 15:43:04.651  3993  3993 D ObexServerSockets0: shutdown(block = true)
,08-26 15:43:04.652  3993  4181 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-26 15:43:04.653  3993  3993 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 15:43:04.653  3993  4182 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 15:43:04.653  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:43:04.654  3993  3993 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 15:43:04.654  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:04.654  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:04.654  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:04.654  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:04.654  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:43:04.654  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:04.654  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:04.654  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:04.654  3993  4166 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 15:43:04.654  3993  3993 I BtOppRfcommListener: stopping Accept Thread
,08-26 15:43:04.655  3993  4190 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 15:43:04.655  3993  4190 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 15:43:04.657  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 15:43:04.658  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:04.661  3993  4156 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:43:04.661  3993  4152 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-26 15:43:04.670  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:43:04.670  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 15:43:04.670  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:04.670  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:04.670  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:04.670  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:04.670  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 15:43:04.670  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:04.670  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:04.670  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 15:43:04.670  3993  3993 D HeadsetService: Received stop request...Stopping profile...
08-26 15:43:04.671  3844  3844 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 15:43:04.671  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:04.672  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:04.673  3914  3925 D BluetoothHeadset: Proxy object disconnected
08-26 15:43:04.674  1354  1365 D BluetoothHeadset: Proxy object disconnected
,08-26 15:43:04.674  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:04.674   875   875 D BluetoothHeadset: Proxy object disconnected
08-26 15:43:04.674   875   875 D BluetoothHeadset: Proxy object disconnected
08-26 15:43:04.675   875   875 D BluetoothHeadset: Proxy object disconnected
08-26 15:43:04.675  3993  3993 D A2dpService: Received stop request...Stopping profile...
,08-26 15:43:04.675  3993  4172 D A2dpStateMachine: Exit Disconnected: -1
,08-26 15:43:04.675  1922  2088 D BluetoothHeadset: Proxy object disconnected
08-26 15:43:04.677   875   875 D BluetoothA2dp: Proxy object disconnected
08-26 15:43:04.677  3993  3993 V BluetoothAdapterState: isTurningOff()=true
,08-26 15:43:04.678  3993  3993 V BluetoothAdapterState: isTurningOn()=false
08-26 15:43:04.678  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:04.678  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 15:43:04.680  3993  3993 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 15:43:04.680  3993  3993 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 15:43:04.680  3993  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 15:43:04.680  3993  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 15:43:04.680  3993  4156 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 15:43:04.680  3993  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 15:43:04.681  3993  3993 D HidService: Received stop request...Stopping profile...
08-26 15:43:04.681  3993  3993 D HidService: Stopping Bluetooth HidService
,08-26 15:43:04.681  3993  4156 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-26 15:43:04.683  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-26 15:43:04.684  1354  1354 D BluetoothA2dp: Proxy object disconnected
,08-26 15:43:04.684  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-26 15:43:04.684  1354  1354 D HidProfile: Bluetooth service disconnected
08-26 15:43:04.686  3993  3993 D HealthService: Received stop request...Stopping profile...
,08-26 15:43:04.688  3993  3993 V BluetoothAdapterState: isTurningOff()=true
,08-26 15:43:04.688  3993  3993 V BluetoothAdapterState: isTurningOn()=false
,08-26 15:43:04.688  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:04.688  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:04.688  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:04.690  3993  4156 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-26 15:43:04.690  3993  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 15:43:04.690  3993  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 15:43:04.690  3993  4164 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:43:04.690  3993  4164 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 15:43:04.690  3993  4164 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 15:43:04.690  3993  4164 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 15:43:04.691  3993  3993 D PanService: Received stop request...Stopping profile...
08-26 15:43:04.692  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:43:04.692  1354  1354 D PanProfile: Bluetooth service disconnected
08-26 15:43:04.693  3993  3993 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 15:43:04.693  3993  3993 D BluetoothMapService: stop()
08-26 15:43:04.693  3993  3993 D BluetoothMapAppObserver: deinitObservers()
08-26 15:43:04.693  3993  3993 D BluetoothMapAppObserver: removeReceiver()
08-26 15:43:04.695  1354  1354 D BluetoothMap: Proxy object disconnected
08-26 15:43:04.696  1354  1354 D MapProfile: Bluetooth service disconnected
08-26 15:43:04.697  3993  3993 V BluetoothAdapterState: isTurningOff()=true
08-26 15:43:04.697  3993  3993 V BluetoothAdapterState: isTurningOn()=false
,08-26 15:43:04.697  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:04.697  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:04.698  3993  3993 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 15:43:04.698  3993  3993 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 15:43:04.698  3993  4156 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 15:43:04.699  1354  1354 D BluetoothPbap: Proxy object disconnected
08-26 15:43:04.699  1354  1354 D PbapServerProfile: Bluetooth service disconnected
,08-26 15:43:04.699  3993  3993 V BluetoothAdapterState: isTurningOff()=true
08-26 15:43:04.700  3993  3993 V BluetoothAdapterState: isTurningOn()=false
08-26 15:43:04.700  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:04.700  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:04.700  3993  3993 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 15:43:04.700  3993  4156 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-26 15:43:04.700  3914  3914 D DockEventReceiver: finishStartingService: stopping service
08-26 15:43:04.700  3993  3993 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 15:43:04.701  3993  3993 V BluetoothAdapterState: isTurningOff()=true
08-26 15:43:04.701  3993  3993 V BluetoothAdapterState: isTurningOn()=false
08-26 15:43:04.701  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:04.701  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:04.701  3914  3914 D HeadsetProfile: Bluetooth service disconnected
,08-26 15:43:04.701  3993  3993 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 15:43:04.701  3914  3914 D BluetoothA2dp: Proxy object disconnected
08-26 15:43:04.702  3914  3914 D BluetoothInputDevice: Proxy object disconnected
08-26 15:43:04.702  3914  3914 D HidProfile: Bluetooth service disconnected
08-26 15:43:04.703  3993  3993 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 15:43:04.703  3914  3914 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 15:43:04.703  3914  3914 D PanProfile: Bluetooth service disconnected
,08-26 15:43:04.704  3993  3993 D BluetoothMapService: MAP Service closeService in
08-26 15:43:04.705  3993  3993 V BluetoothAdapterState: isTurningOff()=true
08-26 15:43:04.705  3993  3993 V BluetoothAdapterState: isTurningOn()=false
08-26 15:43:04.705  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:04.705  3993  3993 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:04.705  3914  3914 D BluetoothMap: Proxy object disconnected
08-26 15:43:04.705  3914  3914 D MapProfile: Bluetooth service disconnected
,08-26 15:43:04.705  3914  3914 D BluetoothPbap: Proxy object disconnected
08-26 15:43:04.705  3914  3914 D PbapServerProfile: Bluetooth service disconnected
08-26 15:43:04.706  3993  4152 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 15:43:04.706  3993  4152 D BluetoothAdapterProperties: Setting state to 15
08-26 15:43:04.706  3993  4152 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 15:43:04.706   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 15:43:04.707  3914  3926 D BluetoothPan: onBluetoothStateChange on: false
08-26 15:43:04.707  3993  3993 D BluetoothMapService: cleanup()
08-26 15:43:04.707  3993  3993 D BluetoothMapService: MAP Service closeService in
,08-26 15:43:04.707  1354  1365 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 15:43:04.707  3993  4152 I BluetoothAdapterState: Entering BleOnState
,08-26 15:43:04.708   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:43:04.708  1354  2000 D BluetoothPan: onBluetoothStateChange on: false
08-26 15:43:04.708  1354  1371 D BluetoothMap: onBluetoothStateChange: up=false
08-26 15:43:04.709  3914  3925 D BluetoothMap: onBluetoothStateChange: up=false
08-26 15:43:04.709  1354  1365 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 15:43:04.710  3914  3926 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:43:04.710  3914  3925 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:43:04.710   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 15:43:04.710  1354  2000 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:43:04.711  1922  1938 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:43:04.711  3914  3926 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 15:43:04.711  3914  3926 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 15:43:04.712  1354  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 15:43:04.712   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 15:43:04.713  3993  4152 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 15:43:04.713  3993  4152 D BluetoothAdapterProperties: Setting state to 16
08-26 15:43:04.713  3993  4152 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-26 15:43:04.713  3993  4152 D BluetoothAdapterProperties: onBleDisable
08-26 15:43:04.714  3993  4152 I BluetoothAdapterState: Entering PendingCommandState
08-26 15:43:04.714  3993  4153 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 15:43:04.716  3993  4164 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 15:43:04.716  3993  4164 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 15:43:04.716  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:04.717  3993  4156 D BluetoothAdapterProperties: Scan Mode:20
08-26 15:43:04.718  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:04.719  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:04.720  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 15:43:04.721  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:04.726  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 15:43:04.732  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:04.757   875  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-26 15:43:04.916  3993  4156 I bt_hci  : shut_down
,08-26 15:43:04.917  3993  4160 D bt_hwcfg: hw_epilog_process
,08-26 15:43:04.929  3993  4160 I bt_vendor: low_power_mode_cb
,08-26 15:43:04.960  3993  4160 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 15:43:04.960  3993  4160 I bt_vendor: epilog_cb
08-26 15:43:04.960  3993  4160 I bt_hci  : epilog_finished_callback
,08-26 15:43:04.968  3993  4156 I bt_hci_h4: hal_close
,08-26 15:43:04.969  3993  4156 I bt_userial_vendor: device fd = 51 close
,08-26 15:43:05.083  3993  4153 D bt_stack_manager: event_shut_down_stack finished.
,08-26 15:43:05.084  3993  4152 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 15:43:05.092  3993  3993 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:43:05.092  3993  4152 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 15:43:05.094  3993  3993 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 15:43:05.094  3993  3993 D BtGatt.GattService: stop()
,08-26 15:43:05.095  3993  3993 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 15:43:05.100  3993  3993 V BluetoothAdapterState: isTurningOff()=false
,08-26 15:43:05.100  3993  3993 V BluetoothAdapterState: isTurningOn()=false
08-26 15:43:05.101  3993  3993 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 15:43:05.101  3993  3993 V BluetoothAdapterState: isBleTurningOff()=true
08-26 15:43:05.102  3993  4152 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-26 15:43:05.103  3993  4152 D BluetoothAdapterProperties: Setting state to 10
08-26 15:43:05.104  3993  4152 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-26 15:43:05.106  3993  4152 I BluetoothAdapterState: Entering OffState
,08-26 15:43:05.107   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 15:43:05.138  3993  3993 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 15:43:05.138  3993  3993 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 15:43:05.139  3993  4153 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 15:43:05.149  3993  4153 D bt_stack_manager: event_clean_up_stack finished.
,08-26 15:43:05.149  3993  3993 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 15:43:05.159  3993  3993 I art     : System.exit called, status: 0
,08-26 15:43:05.159  3993  3993 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 15:43:05.220   875  1939 I ActivityManager: Process com.android.bluetooth (pid 3993) has died
,08-26 15:43:05.891   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-26 15:43:05.901  1862  1862 I Keyboard.Facilitator: onFinishInput()
,08-26 15:43:05.919   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 15:43:05.919   875   895 I Adreno  : Build Date                       : 10/20/15
08-26 15:43:05.919   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 15:43:05.919   875   895 I Adreno  : Local Branch                     : M14
08-26 15:43:05.919   875   895 I Adreno  : Remote Branch                    : 
08-26 15:43:05.919   875   895 I Adreno  : Remote Branch                    : 
08-26 15:43:05.919   875   895 I Adreno  : Reconstruct Branch               : 
,08-26 15:43:05.953   281   303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (197 us)
,08-26 15:43:06.578  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 15:43:06.579  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 15:43:06.617   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 15:43:06.619  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ffab72e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5d23308, 16908290=android.view.AbsSavedState$1@5d23308}, android:focusedViewId=100}]}]
08-26 15:43:06.619  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 15:43:06.619  3844  3844 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 15:43:06.619  3844  3844 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 15:43:06.641   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-26 15:43:06.647   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-26 15:43:06.649   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-26 15:43:06.649   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-26 15:43:06.881   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-26 15:43:06.885   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-26 15:43:06.886   875  1333 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,08-26 15:43:06.895   875   895 I DreamManagerService: Entering dreamland.
,08-26 15:43:06.896   875   895 I PowerManagerService: Dozing...
,08-26 15:43:06.898   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 15:43:06.943   375  1316 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 15:43:06.943   375  1316 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 15:43:06.954   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 15:43:06.958   875  1308 E native  : do suspend false
,08-26 15:43:06.962  1909  4203 D NfcService: Discovery configuration equal, not updating.
,08-26 15:43:06.988   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 15:43:06.991   875  1308 E native  : do suspend true
,08-26 15:43:07.086   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-26 15:43:07.086   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-26 15:43:07.633  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:43:07.634  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:09.647  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:43:09.663  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:43:09.668  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 15:43:09.732  1501  3633 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-26 15:43:09.732  1501  3633 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-26 15:43:09.732  1501  3633 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 15:43:09.733  1501  3633 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 15:43:09.762  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 15:43:09.763  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-26 15:43:09.763  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-26 15:43:10.641  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:10.642  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@63c5aa1 added. We now have 6 listener(s)
08-26 15:43:10.642  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:10.646  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:10.646  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4d5d4c6 added. We now have 7 listener(s)
08-26 15:43:10.646  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:10.648  3844  3895 I System.out: IsBluetoothEnabled
,08-26 15:43:10.659  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:10.701   875   892 I ActivityManager: Start proc 4211:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 15:43:10.811  4211  4211 D AdapterServiceConfig: Adding HeadsetService
,08-26 15:43:10.812  4211  4211 D AdapterServiceConfig: Adding A2dpService
08-26 15:43:10.812  4211  4211 D AdapterServiceConfig: Adding HidService
,08-26 15:43:10.812  4211  4211 D AdapterServiceConfig: Adding HealthService
,08-26 15:43:10.812  4211  4211 D AdapterServiceConfig: Adding PanService
08-26 15:43:10.813  4211  4211 D AdapterServiceConfig: Adding GattService
,08-26 15:43:10.813  4211  4211 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 15:43:10.828   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@af1e33:true
,08-26 15:43:10.828  4211  4211 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 15:43:10.834  4211  4211 I bt_bluedroid: init
,08-26 15:43:10.835  4211  4223 I BluetoothAdapterState: Entering OffState
,08-26 15:43:10.839  4211  4224 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 15:43:10.840  4211  4224 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory,
,08-26 15:43:10.840  4211  4224 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 15:43:10.840  4211  4224 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 15:43:10.842  4211  4211 I bt_bluedroid: get_profile_interface socket
,08-26 15:43:10.844  4211  4227 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 15:43:10.846  4211  4227 D BluetoothAdapterProperties: Name is: Nexus 6
08-26 15:43:10.847  4211  4211 I bt_bluedroid: get_profile_interface sdp
,08-26 15:43:10.853  4211  4222 I bt_bluedroid: config_hci_snoop_log
,08-26 15:43:10.856   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 15:43:10.867  4211  4223 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 15:43:10.867  4211  4223 D BluetoothAdapterProperties: Setting state to 14
,08-26 15:43:10.868  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 15:43:10.874  4211  4223 D BluetoothBondStateMachine: make
,08-26 15:43:10.878  4211  4228 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 15:43:10.889  4211  4223 I BluetoothAdapterState: Entering PendingCommandState
08-26 15:43:10.889  4211  4211 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 15:43:10.894  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:10.894  4211  4211 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 15:43:10.895  4211  4211 D BtGatt.GattService: Received start request. Starting profile...
08-26 15:43:10.895  4211  4211 D BtGatt.GattService: start()
08-26 15:43:10.895  4211  4211 I bt_bluedroid: get_profile_interface gatt
,08-26 15:43:10.896  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
08-26 15:43:10.896  4211  4211 D BtGatt.AdvertiseManager: advertise manager created
,08-26 15:43:10.903  4211  4211 V BluetoothAdapterState: isTurningOff()=false
,08-26 15:43:10.904  4211  4211 V BluetoothAdapterState: isTurningOn()=false
08-26 15:43:10.904  4211  4211 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 15:43:10.904  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:10.905  4211  4223 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-26 15:43:10.905  4211  4223 I bt_bluedroid: enable
,08-26 15:43:10.906  4211  4224 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 15:43:10.906  4211  4224 I bt_hci  : start_up
,08-26 15:43:10.914  4211  4224 I bt_vendor: alloc value 0xb39ea189
08-26 15:43:10.915  4211  4224 I bt_vendor: init
,08-26 15:43:10.915  4211  4224 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 15:43:10.915  4211  4224 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 15:43:11.023  4211  4224 D bt_hci  : start_up starting async portion
,08-26 15:43:11.023  4211  4231 I bt_hci  : event_finish_startup
,08-26 15:43:11.024  4211  4231 I bt_hci_h4: hal_open
08-26 15:43:11.024  4211  4231 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 15:43:11.036  4211  4231 I bt_userial_vendor: device fd = 51 open
,08-26 15:43:11.065  4211  4231 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 15:43:11.096  4211  4231 D bt_hwcfg: Chipset BCM4354A2
,08-26 15:43:11.097  4211  4231 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 15:43:11.098  4211  4231 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 15:43:11.768  4211  4231 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 15:43:11.770  4211  4231 D bt_hwcfg: Settlement delay -- 100 ms
08-26 15:43:11.770  4211  4231 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 15:43:11.886  4211  4231 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 15:43:11.888  4211  4231 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 15:43:11.917  4211  4231 I bt_hwcfg: vendor lib fwcfg completed
,08-26 15:43:11.918  4211  4231 I bt_vendor: firmware callback
08-26 15:43:11.918  4211  4231 I bt_hci  : firmware_config_callback
,08-26 15:43:11.929  4211  4234 I bt_btu  : btu_task pending for preload complete event
,08-26 15:43:11.929  4211  4234 I bt_btu_task: Bluetooth chip preload is complete
08-26 15:43:11.929  4211  4234 I bt_btu  : btu_task received preload complete event
,08-26 15:43:11.939  4211  4234 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 15:43:11.939  4211  4234 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 15:43:11.939  4211  4234 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 15:43:11.940  4211  4234 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 15:43:11.940  4211  4234 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 15:43:11.940  4211  4234 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 15:43:11.940  4211  4234 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 15:43:11.941  4211  4234 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 15:43:11.941  4211  4234 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 15:43:11.941  4211  4234 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 15:43:11.941  4211  4234 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 15:43:11.942  4211  4234 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 15:43:11.942  4211  4234 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 15:43:11.942  4211  4234 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 15:43:11.942  4211  4234 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 15:43:12.076  4211  4234 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3967d9d
,08-26 15:43:12.076  4211  4234 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3967d9d 
,08-26 15:43:12.088  4211  4227 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 15:43:12.089  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 15:43:12.090  4211  4227 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 15:43:12.094  4211  4227 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 15:43:12.101  4211  4227 D BluetoothAdapterProperties: Scan Mode:20
,08-26 15:43:12.101  4211  4227 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 15:43:12.101  4211  4227 D bt_hci  : do_postload posting postload work item
,08-26 15:43:12.102  4211  4231 I bt_hci  : event_postload
08-26 15:43:12.102  4211  4231 I bt_vendor: sco_config_cb
08-26 15:43:12.102  4211  4231 I bt_hci  : sco_config_callback postload finished.
08-26 15:43:12.104  4211  4227 D bt_bte_conf: Device ID record 1 : primary
08-26 15:43:12.104  4211  4227 D bt_bte_conf:   vendorId            = 000f
08-26 15:43:12.105  4211  4227 D bt_bte_conf:   vendorIdSource      = 0001
08-26 15:43:12.105  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:12.105  4211  4227 D bt_bte_conf:   product             = 1200
08-26 15:43:12.105  4211  4227 D bt_bte_conf:   version             = 1436
08-26 15:43:12.105  4211  4227 D bt_bte_conf:   clientExecutableURL = 
08-26 15:43:12.105  4211  4227 D bt_bte_conf:   serviceDescription  = 
08-26 15:43:12.106  4211  4227 D bt_bte_conf:   documentationURL    = 
,08-26 15:43:12.106  4211  4227 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-26 15:43:12.106  4211  4224 D bt_stack_manager: event_start_up_stack finished
08-26 15:43:12.107  4211  4223 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 15:43:12.108  4211  4223 D BluetoothAdapterProperties: Setting state to 15
08-26 15:43:12.108  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 15:43:12.110  4211  4231 I bt_vendor: low_power_mode_cb
08-26 15:43:12.111  4211  4223 I BluetoothAdapterState: Entering BleOnState
08-26 15:43:12.114  4211  4223 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 15:43:12.115  4211  4223 D BluetoothAdapterProperties: Setting state to 11
08-26 15:43:12.115  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 15:43:12.127  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:12.135  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:12.136  4211  4211 D HeadsetService: Received start request. Starting profile...
,08-26 15:43:12.143  4211  4211 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 15:43:12.143  4211  4211 D HeadsetStateMachine: make
08-26 15:43:12.145  4211  4223 I BluetoothAdapterState: Entering PendingCommandState
,08-26 15:43:12.152  4211  4211 D HeadsetStateMachine: max_hf_connections = 1
,08-26 15:43:12.152  4211  4211 I bt_bluedroid: get_profile_interface handsfree
08-26 15:43:12.152  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 15:43:12.153  4211  4227 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 15:43:12.157  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
08-26 15:43:12.158  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:12.158  4211  4211 D A2dpService: Received start request. Starting profile...
08-26 15:43:12.159  4211  4211 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 15:43:12.160  4211  4211 I bt_bluedroid: get_profile_interface avrcp
,08-26 15:43:12.167  4211  4211 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 15:43:12.167  4211  4211 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 15:43:12.167  4211  4211 D A2dpStateMachine: make
,08-26 15:43:12.169  4211  4211 I bt_bluedroid: get_profile_interface a2dp
,08-26 15:43:12.171  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-26 15:43:12.172  4211  4244 D A2dpStateMachine: Enter Disconnected: -2
08-26 15:43:12.173  4211  4211 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 15:43:12.173  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
08-26 15:43:12.174  4211  4211 D HidService: Received start request. Starting profile...
08-26 15:43:12.175  4211  4211 I bt_bluedroid: get_profile_interface hidhost
08-26 15:43:12.175  4211  4211 D HidService: setHidService(): set to: null
08-26 15:43:12.175  4211  4227 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39493e5
08-26 15:43:12.176  4211  4211 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 15:43:12.175  4211  4227 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 15:43:12.176  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
08-26 15:43:12.177  4211  4211 D HealthService: Received start request. Starting profile...
,08-26 15:43:12.180  4211  4211 I bt_bluedroid: get_profile_interface health
,08-26 15:43:12.180  4211  4211 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 15:43:12.182  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:12.183  4211  4211 D PanService: Received start request. Starting profile...
,08-26 15:43:12.183  4211  4211 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 15:43:12.183  4211  4211 I bt_bluedroid: get_profile_interface pan
08-26 15:43:12.185  4211  4227 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 15:43:12.187  4211  4211 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:12.188  4211  4211 D BluetoothMapService: Received start request. Starting profile...
08-26 15:43:12.188  4211  4211 D BluetoothMapService: start()
,08-26 15:43:12.194  4211  4211 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 15:43:12.196  4211  4211 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 15:43:12.196  4211  4211 D BluetoothMapAppObserver: createReceiver()
,08-26 15:43:12.199  4211  4211 D BluetoothMapAppObserver: initObservers()
,08-26 15:43:12.200  4211  4211 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 15:43:12.219  4211  4211 V BluetoothAdapterState: isTurningOff()=false
08-26 15:43:12.219  4211  4211 V BluetoothAdapterState: isTurningOn()=true
,08-26 15:43:12.219  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:12.219  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 15:43:12.221  4211  4242 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 15:43:12.222  4211  4211 V BluetoothAdapterState: isTurningOff()=false
08-26 15:43:12.222  4211  4211 V BluetoothAdapterState: isTurningOn()=true
,08-26 15:43:12.222  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:12.222  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:12.223  4211  4211 V BluetoothAdapterState: isTurningOff()=false
08-26 15:43:12.223  4211  4211 V BluetoothAdapterState: isTurningOn()=true
08-26 15:43:12.223  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:12.223  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:12.223  4211  4211 V BluetoothAdapterState: isTurningOff()=false
,08-26 15:43:12.223  4211  4211 V BluetoothAdapterState: isTurningOn()=true
,08-26 15:43:12.223  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 15:43:12.223  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 15:43:12.223  4211  4211 V BluetoothAdapterState: isTurningOff()=false
08-26 15:43:12.224  4211  4211 V BluetoothAdapterState: isTurningOn()=true
08-26 15:43:12.224  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:12.224  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 15:43:12.224  4211  4211 V BluetoothAdapterState: isTurningOff()=false
08-26 15:43:12.224  4211  4211 V BluetoothAdapterState: isTurningOn()=true
08-26 15:43:12.224  4211  4211 V BluetoothAdapterState: isBleTurningOn()=false
08-26 15:43:12.224  4211  4211 V BluetoothAdapterState: isBleTurningOff()=false
08-26 15:43:12.225  4211  4223 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 15:43:12.225  4211  4223 D BluetoothAdapterProperties: ScanMode =  20
08-26 15:43:12.225  4211  4223 D BluetoothAdapterProperties: State =  11
08-26 15:43:12.225  4211  4223 D BluetoothAdapterProperties: Setting state to 12
08-26 15:43:12.225  4211  4223 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 15:43:12.226   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:12.226  3914  3925 D BluetoothPan: onBluetoothStateChange on: true
,08-26 15:43:12.227  4211  4223 I BluetoothAdapterState: Entering OnState
08-26 15:43:12.234  4211  4227 D BluetoothAdapterProperties: Scan Mode:21
08-26 15:43:12.234  1354  4199 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 15:43:12.234  4211  4227 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 15:43:12.237   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:12.237  1354  2000 D BluetoothPan: onBluetoothStateChange on: true
08-26 15:43:12.238  4211  4211 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 15:43:12.238  4211  4211 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 15:43:12.240  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 15:43:12.240  1354  1354 D PanProfile: Bluetooth service connected
08-26 15:43:12.240  1354  1371 D BluetoothMap: onBluetoothStateChange: up=true
08-26 15:43:12.242  3914  3925 D BluetoothMap: onBluetoothStateChange: up=true
08-26 15:43:12.242  4211  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:12.242  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:12.242  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:12.242  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:12.242  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:12.242  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:12.242  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:12.242  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:12.242  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:12.243  3914  3914 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 15:43:12.243  3914  3914 D PanProfile: Bluetooth service connected
08-26 15:43:12.243  1354  4199 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 15:43:12.244  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 15:43:12.245  3914  3926 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:12.245  4211  4211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 15:43:12.247  3914  3925 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 15:43:12.247   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:12.247  4211  4211 D ObexServerSockets: Succeed to create listening sockets 
08-26 15:43:12.248  4211  4211 D ObexServerSockets0: startAccept()
08-26 15:43:12.248  4211  4211 D ObexServerSockets0: prepareForNewConnect()
08-26 15:43:12.248  1354  1365 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:12.248  1922  1936 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 15:43:12.249  3914  3926 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 15:43:12.251  3914  3925 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 15:43:12.252  1354  2000 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 15:43:12.253  4211  4211 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 15:43:12.253  4211  4211 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-26 15:43:12.253   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 15:43:12.253  4211  4249 D ObexServerSockets0: Accepting socket connection...
,08-26 15:43:12.254  4211  4250 D ObexServerSockets0: Accepting socket connection...
08-26 15:43:12.255   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 15:43:12.259  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:12.260  1354  1354 D BluetoothMap: Proxy object connected
08-26 15:43:12.260  1354  1354 D MapProfile: Bluetooth service connected
08-26 15:43:12.260  1354  1354 D BluetoothMap: getConnectedDevices()
08-26 15:43:12.262   875   875 D BluetoothA2dp: Proxy object connected
,08-26 15:43:12.262  4211  4211 D BluetoothMapService: onReceive
08-26 15:43:12.262  4211  4211 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 15:43:12.262  4211  4211 D BluetoothMapService: STATE_ON
08-26 15:43:12.265  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 15:43:12.265  1354  1354 D BluetoothInputDevice: Proxy object connected
,08-26 15:43:12.265  1354  1354 D HidProfile: Bluetooth service connected
08-26 15:43:12.267  3914  3914 D BluetoothMap: Proxy object connected
08-26 15:43:12.267  3914  3914 D MapProfile: Bluetooth service connected
08-26 15:43:12.267  3914  3914 D BluetoothMap: getConnectedDevices()
08-26 15:43:12.267  1354  1354 D BluetoothA2dp: Proxy object connected
08-26 15:43:12.271  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 15:43:12.275  3914  3914 D BluetoothInputDevice: Proxy object connected
08-26 15:43:12.275  3914  3914 D HidProfile: Bluetooth service connected
08-26 15:43:12.277  3914  3914 D BluetoothA2dp: Proxy object connected
,08-26 15:43:12.283  3914  3914 D DockEventReceiver: finishStartingService: stopping service
,08-26 15:43:12.284  3914  3914 D BluetoothPbap: Proxy object connected
08-26 15:43:12.284  3914  3914 D PbapServerProfile: Bluetooth service connected
,08-26 15:43:12.287  4211  4255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:12.291  1354  1354 D BluetoothPbap: Proxy object connected
,08-26 15:43:12.291  1354  1354 D PbapServerProfile: Bluetooth service connected
,08-26 15:43:12.298  4211  4211 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 15:43:12.298  4211  4211 D ObexServerSockets0: prepareForNewConnect()
,08-26 15:43:12.302  4211  4259 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 15:43:12.304  4211  4259 I BtOppRfcommListener: Accept thread started.
,08-26 15:43:12.328  3914  3925 D BluetoothHeadset: Proxy object connected
08-26 15:43:12.328  3914  3914 D HeadsetProfile: Bluetooth service connected
,08-26 15:43:12.329  1354  1365 D BluetoothHeadset: Proxy object connected
,08-26 15:43:12.329  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-26 15:43:12.329   875   875 D BluetoothHeadset: Proxy object connected
,08-26 15:43:12.330   875   875 D BluetoothHeadset: Proxy object connected
,08-26 15:43:12.330   875   875 D BluetoothHeadset: Proxy object connected
,08-26 15:43:12.330  1922  2088 D BluetoothHeadset: Proxy object connected
08-26 15:43:12.337   875   892 D BluetoothHeadset: Proxy object connected
,08-26 15:43:12.347  3914  3926 D BluetoothHeadset: Proxy object connected
08-26 15:43:12.347  1354  2000 D BluetoothHeadset: Proxy object connected
,08-26 15:43:12.348  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-26 15:43:12.348  3914  3914 D HeadsetProfile: Bluetooth service connected
08-26 15:43:12.349  1922  1938 D BluetoothHeadset: Proxy object connected
,08-26 15:43:12.354   875   892 D BluetoothHeadset: Proxy object connected
,08-26 15:43:12.682  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:12.682  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:12.682  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:12.682  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 15:43:12.682  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:12.682  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:12.682  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:12.682  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:12.689  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:12.692  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:12.693  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d041c87 added. We now have 8 listener(s)
,08-26 15:43:12.693  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:12.698   875  1939 D WifiService: setWifiEnabled: false pid=3844, uid=10000
,08-26 15:43:12.699   875  1939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 15:43:12.711  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:12.712   875  2114 D WifiService: setWifiEnabled: true pid=3844, uid=10000
,08-26 15:43:12.712   875  2114 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 15:43:12.726   875  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-26 15:43:12.739  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:12.739  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:12.739  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:12.739  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:12.739  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:12.739  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:12.739  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:12.739  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:12.743  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:12.754   875  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-26 15:43:12.756   875  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 15:43:12.756   875  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 15:43:12.757   875  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 15:43:12.758   875  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 15:43:12.758   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 15:43:12.758   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 15:43:12.771   371   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 15:43:12.772   875  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.22 rxSuccessRate=0.28 delta 1000 -> 1000
08-26 15:43:12.772   371   873 D CommandListener: Setting iface cfg
08-26 15:43:12.773   875  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-26 15:43:12.773   875  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-26 15:43:12.773   875  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 15:43:12.783   875  1308 E native  : do suspend true
,08-26 15:43:12.784   875  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 15:43:12.790   875  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 15:43:12.797   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-26 15:43:12.797   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:43:12.816   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 15:43:12.900   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 15:43:12.904  1450  1450 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 15:43:13.141  2133  2657 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-26 15:43:13.498  1450  1450 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 15:43:13.620  1450  1450 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 15:43:13.624  1450  1450 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 15:43:13.632   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 15:43:13.651   875  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 15:43:13.652   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 15:43:13.652   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 15:43:13.675   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 15:43:13.691   371   873 D CommandListener: Setting iface cfg
,08-26 15:43:13.692   875  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 15:43:13.709   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 15:43:13.736   875  4267 D DhcpClient: Receive thread started
,08-26 15:43:13.742  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:13.742  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:13.742  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:13.742  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:13.742  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:13.742  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 15:43:13.742  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 15:43:13.742  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 15:43:13.749  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 15:43:13.761  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 15:43:13.763  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 15:43:13.770  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ffab72e Bundle[{}]
,08-26 15:43:13.772  3844  3895 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 15:43:13.772  3844  3895 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 15:43:13.772  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 15:43:13.773  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 15:43:13.773  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 15:43:13.774  3844  3895 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 15:43:13.778  3844  3895 I System.out: Running OutgoingSocketThread
,08-26 15:43:13.781  3844  4268 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 428)
,08-26 15:43:13.784  3844  4268 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42026
,08-26 15:43:13.784  3844  4268 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 15:43:13.825   875  1308 E native  : do suspend false
,08-26 15:43:13.844   875  1877 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 15:43:13.876   875  4267 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-26 15:43:13.877   875  1877 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-26 15:43:13.881   875  1877 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 15:43:13.906   875  4267 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 15:43:13.907   875  1877 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 15:43:13.912   371   873 D CommandListener: Setting iface cfg
,08-26 15:43:13.923   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 15:43:13.924   875  1877 D DhcpClient: Scheduling renewal in 86399s
,08-26 15:43:13.926   875  1308 E native  : do suspend true
,08-26 15:43:13.946   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 15:43:13.950   875  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 15:43:13.952   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 15:43:13.954   875  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 15:43:13.963   875  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 15:43:14.005   875  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 15:43:14.005   875  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-26 15:43:14.008   875  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-26 15:43:14.011   875  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 15:43:14.013   875  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 15:43:14.023   875  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 15:43:14.029   875  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-26 15:43:14.029   875  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-26 15:43:14.029   875  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-26 15:43:14.030   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 15:43:14.030   875  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-26 15:43:14.030   875  1310 D ConnectivityService:    accepting network in place of null
08-26 15:43:14.032   875  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 15:43:14.051   875  4266 D NetlinkSocketObserver: NeighborEvent{elapsedMs=158040, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 15:43:14.082   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 15:43:14.138   371   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 15:43:14.144   875  4265 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:807::200e
,08-26 15:43:14.145   875  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-26 15:43:14.145   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 15:43:14.146   875  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 15:43:14.148   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-26 15:43:14.171  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 15:43:14.171  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.171  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.171  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.171  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.171  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:14.171  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:14.171  3844  3844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:43:14.173  3844  3844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:43:14.178  1730  1730 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 15:43:14.183  1730  1730 D SystemUpdateService: onCreate
,08-26 15:43:14.187  1730  1730 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 15:43:14.197  1730  4277 I SystemUpdateService: active receiver: enabled
,08-26 15:43:14.206  1730  4277 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 15:43:14.209  1730  1730 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 15:43:14.211  1730  2425 I iu.UploadsManager: num queued entries: 0
,08-26 15:43:14.211  1730  2425 I iu.UploadsManager: num updated entries: 0
08-26 15:43:14.212  1730  2425 I iu.SyncManager: NEXT; no task
,08-26 15:43:14.217  1730  4277 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 15:43:14.218  1730  4277 I SystemUpdateService: now status is 0 (complete)
08-26 15:43:14.218  1730  4277 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 15:43:14.218  1730  4277 I SystemUpdateService: file has been verified
,08-26 15:43:14.218  1730  4277 I SystemUpdateService: OTA package size = 12249756
,08-26 15:43:14.222  1730  1730 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 15:43:14.223  1730  1730 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 15:43:14.225  4008  4008 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 15:43:14.231  1730  4280 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 15:43:14.231  1730  4280 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 15:43:14.232  4008  4008 D SprintDMHelper: simOperator: 
08-26 15:43:14.232  4008  4008 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 15:43:14.234   875  4265 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 13:43:14 GMT], X-Android-Received-Millis=[1472218994233], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472218994202]}
,08-26 15:43:14.235  1730  4280 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 15:43:14.237   875  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 15:43:14.238   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 15:43:14.238   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 15:43:14.239   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 15:43:14.259  1730  4277 I SystemUpdateService: showing system update notification
,08-26 15:43:14.304  1501  2138 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 15:43:14.304  1501  2138 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-26 15:43:14.304  1501  2138 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 15:43:14.304  1501  2138 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 15:43:14.307  1730  1730 D SystemUpdateService: onDestroy
,08-26 15:43:14.331  1730  4280 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-26 15:43:14.417  3965  4283 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 15:43:14.781  3844  3895 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 429)
,08-26 15:43:14.782  3844  3895 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 429)
,08-26 15:43:14.791  3844  3895 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 434)
,08-26 15:43:14.793  3844  3895 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 15:43:14.794  3844  3895 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 435)
,08-26 15:43:14.799  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:14.799  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db77b4 added. We now have 2 listener(s)
,08-26 15:43:14.801  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 15:43:14.801  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.801  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:14.802  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.802  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f22ffdd added. We now have 9 listener(s)
08-26 15:43:14.802  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.802  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.806  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.813  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.813  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.813  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.813  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.813  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.813  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:14.813  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:14.813  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:43:14.816  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:43:14.816  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:14.817  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:14.818  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afbfa23 added. We now have 3 listener(s)
,08-26 15:43:14.819  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.822  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 15:43:14.824  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 15:43:14.824  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.824  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.825  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.825  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d925b20 added. We now have 10 listener(s)
08-26 15:43:14.825  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.826  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:14.826  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.826  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:14.827  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.827  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.827  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.827  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.828  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db77b4 removed from the list
08-26 15:43:14.828  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.828  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f22ffdd removed from the list
08-26 15:43:14.828  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:14.828  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.830  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.830  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.831  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:14.832  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.832  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.832  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f22ffdd not in the list
08-26 15:43:14.832  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.832  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.833  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.833  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.833  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.833  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d925b20 removed from the list
,08-26 15:43:14.833  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:14.833  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.833  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.833  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:14.833  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@afbfa23 removed from the list
,08-26 15:43:14.834  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.834  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d4bcd9 added. We now have 2 listener(s)
,08-26 15:43:14.836  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 15:43:14.836  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 15:43:14.836  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:14.837  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.837  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f4b69e added. We now have 9 listener(s)
,08-26 15:43:14.837  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.837  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.841  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.848  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.848  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.848  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.848  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.848  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.848  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:14.848  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:14.848  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:43:14.850  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:14.850  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:14.851  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.851  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b12094c added. We now have 3 listener(s)
,08-26 15:43:14.852  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 15:43:14.853  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.853  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:14.853  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.853  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b4d95 added. We now have 10 listener(s)
,08-26 15:43:14.853  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.853  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 15:43:14.853  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 15:43:14.853  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:14.853  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.854  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:43:14.861  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.864  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.866  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 15:43:14.866  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:14.871  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:14.872  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 15:43:14.872  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:14.875  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:43:14.876  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:43:14.876  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 15:43:14.877  3844  3895 D BluetoothAdapter: STATE_ON
,08-26 15:43:14.880  4211  4241 D BtGatt.GattService: registerClient() - UUID=19365a92-6bd8-4606-9447-5dc523b14e1e
,08-26 15:43:14.881  4211  4227 D BtGatt.GattService: onClientRegistered() - UUID=19365a92-6bd8-4606-9447-5dc523b14e1e, clientIf=5
,08-26 15:43:14.883  3844  3856 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 15:43:14.884  4211  4240 D BtGatt.GattService: start scan with filters
,08-26 15:43:14.889  4211  4230 D BtGatt.ScanManager: handling starting scan
,08-26 15:43:14.890  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:43:14.890  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 15:43:14.890  4211  4230 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@37e8ee2
,08-26 15:43:14.891  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 15:43:14.891  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 15:43:14.894  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:14.895  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:14.895  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 15:43:14.897  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 15:43:14.898  4211  4227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 15:43:14.898  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:14.900  3844  3895 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 15:43:14.900  4211  4230 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 15:43:14.900  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:14.900  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 15:43:14.900  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.900  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 15:43:14.900  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 15:43:14.901  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 15:43:14.901  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:43:14.901  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:43:14.901  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 15:43:14.901  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 15:43:14.902  3844  3895 D BluetoothAdapter: STATE_ON,
08-26 15:43:14.902  4211  4241 D BtGatt.GattService: stopScan() - queue size =1
08-26 15:43:14.903  4211  4240 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 15:43:14.903  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:14.903  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 15:43:14.903  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:43:14.904  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
08-26 15:43:14.904  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 15:43:14.909  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:43:14.909  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:43:14.909  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:43:14.909  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:43:14.910  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.911  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.911  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.912  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:14.914  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:14.914  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.914  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:14.914  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.914  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 15:43:14.914  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.914  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.914  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9d4bcd9 removed from the list
08-26 15:43:14.914  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.915  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f4b69e removed from the list
,08-26 15:43:14.915  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:14.915  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.915  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.915  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.917  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:14.917  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.918  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.918  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f4b69e not in the list
08-26 15:43:14.918  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.918  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.918  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 15:43:14.919  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.919  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 15:43:14.919  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.919  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:14.919  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b4d95 removed from the list
08-26 15:43:14.919  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.919  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.919  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 15:43:14.920  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.920  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b12094c removed from the list
08-26 15:43:14.920  4211  4230 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:14.921  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:14.921  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@602e11 added. We now have 2 listener(s)
08-26 15:43:14.921  4211  4230 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 15:43:14.922  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 15:43:14.923  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.923  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.923  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.923  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@922fb76 added. We now have 9 listener(s)
08-26 15:43:14.923  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:14.924  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:14.926  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:14.933  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:14.933  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:14.933  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:14.933  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:14.933  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:14.933  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:14.933  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:14.933  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:43:14.935  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:43:14.935  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:14.936  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:14.936  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2635e4 added. We now have 3 listener(s)
,08-26 15:43:14.938  4211  4227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 15:43:14.938  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-26 15:43:14.939  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 15:43:14.939  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 15:43:14.939  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:14.939  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:14.940  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6089a4d added. We now have 10 listener(s)
,08-26 15:43:14.940  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 15:43:14.940  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 15:43:14.941  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 15:43:14.941  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 15:43:14.941  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:14.941  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-26 15:43:14.941  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 15:43:14.944  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.946  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 15:43:14.946  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:14.947  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:14.953  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 15:43:14.953  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:14.954  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:14.954  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 15:43:14.955  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:14.961  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:43:14.961  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:43:14.961  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 15:43:14.962  3844  3895 D BluetoothAdapter: STATE_ON
,08-26 15:43:14.964  4211  4221 D BtGatt.GattService: registerClient() - UUID=e451dd2f-75bb-430f-8e54-f6005ead5537
,08-26 15:43:14.965  4211  4227 D BtGatt.GattService: onClientRegistered() - UUID=e451dd2f-75bb-430f-8e54-f6005ead5537, clientIf=5
08-26 15:43:14.965  3844  3856 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 15:43:14.965  4211  4240 D BtGatt.GattService: start scan with filters
,08-26 15:43:14.967  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 15:43:14.967  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 15:43:14.967  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 15:43:14.967  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:43:14.972  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 15:43:14.972  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:14.972  4211  4230 D BtGatt.ScanManager: stopping BLe Batch
08-26 15:43:14.972  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:14.973  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:43:14.973  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 15:43:14.974  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:14.976  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 15:43:14.976  3844  3895 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-26 15:43:14.976  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:14.977  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:14.977  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 15:43:14.977  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.977  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.977  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:43:14.977  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.977  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@602e11 removed from the list
08-26 15:43:14.977  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.977  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@922fb76 removed from the list
08-26 15:43:14.977  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:14.977  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:14.978  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.978  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 15:43:14.978  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.978  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:14.979  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.979  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.979  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.979  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@922fb76 not in the list
08-26 15:43:14.980  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 15:43:14.980  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:43:14.980  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:43:14.980  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:43:14.980  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 15:43:14.981  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 15:43:14.981  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:14.981  3844  3895 D BluetoothAdapter: STATE_ON
08-26 15:43:14.981  4211  4230 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 15:43:14.981  4211  4240 D BtGatt.GattService: stopScan() - queue size =0
08-26 15:43:14.982  4211  4222 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 15:43:14.982  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 15:43:14.982  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:43:14.982  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:43:14.983  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:43:14.983  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 15:43:14.983  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:43:14.984  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:43:14.984  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:43:14.984  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 15:43:14.984  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 15:43:14.987  4211  4227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 15:43:14.987  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 15:43:14.987  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:14.988  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:14.988  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:14.988  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.988  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 15:43:14.988  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:43:14.988  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6089a4d removed from the list
,08-26 15:43:14.989  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:14.989  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:14.989  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:14.989  4211  4230 D BtGatt.ScanManager: handling starting scan
08-26 15:43:14.989  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:14.989  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2635e4 removed from the list
,08-26 15:43:14.990  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 15:43:14.990  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5518e49 added. We now have 2 listener(s)
,08-26 15:43:14.994  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 15:43:14.994  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:14.994  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:14.995  4211  4227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 15:43:14.995  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:14.995  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:14.995  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a034e added. We now have 9 listener(s)
,08-26 15:43:14.995  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:14.995  4211  4230 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 15:43:14.995  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:43:14.999  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:43:15.003  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 15:43:15.003  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 15:43:15.003  4211  4230 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:15.003  4211  4230 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 15:43:15.004  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:15.004  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:15.004  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:15.004  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:15.004  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:15.004  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:15.004  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:15.004  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:43:15.006  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:15.007  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:15.010  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:15.011  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:15.011  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d05d7c added. We now have 3 listener(s)
08-26 15:43:15.013  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:15.015  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 15:43:15.015  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:15.016  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:43:15.016  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:15.016  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1bc605 added. We now have 10 listener(s)
08-26 15:43:15.016  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:15.017  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:15.017  4211  4227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 15:43:15.017  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:15.018  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 15:43:15.018  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 15:43:15.018  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:15.018  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 15:43:15.025  3844  3895 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 15:43:15.026  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 15:43:15.029  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 15:43:15.029  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 15:43:15.036  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 15:43:15.038  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 15:43:15.038  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 15:43:15.038  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 15:43:15.038  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:15.039  4211  4230 D BtGatt.ScanManager: stopping BLe Batch
,08-26 15:43:15.043  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 15:43:15.043  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 15:43:15.043  3844  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 15:43:15.044  3844  3895 D BluetoothAdapter: STATE_ON
,08-26 15:43:15.046  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 15:43:15.046  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:15.047  4211  4230 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 15:43:15.049  4211  4251 D BtGatt.GattService: registerClient() - UUID=137600fd-f5b5-4e46-be62-abf797e6acca
08-26 15:43:15.049  4211  4227 D BtGatt.GattService: onClientRegistered() - UUID=137600fd-f5b5-4e46-be62-abf797e6acca, clientIf=5
,08-26 15:43:15.050  3844  3856 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 15:43:15.051  4211  4240 D BtGatt.GattService: start scan with filters
,08-26 15:43:15.054  4211  4227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 15:43:15.054  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 15:43:15.055  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 15:43:15.055  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 15:43:15.055  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 15:43:15.055  4211  4230 D BtGatt.ScanManager: handling starting scan
08-26 15:43:15.055  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 15:43:15.063  4211  4227 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 15:43:15.063  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:15.063  4211  4230 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 15:43:15.063  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:15.063  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 15:43:15.063  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 15:43:15.065  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 15:43:15.069  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 15:43:15.069  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:15.069  4211  4230 D BtGatt.ScanManager: Starting BLE batch scan
08-26 15:43:15.069  4211  4230 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 15:43:15.071  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 15:43:15.071  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:15.071  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:15.072  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:15.072  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:15.072  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 15:43:15.072  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:15.072  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5518e49 removed from the list
08-26 15:43:15.072  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:15.072  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a034e removed from the list
08-26 15:43:15.072  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
08-26 15:43:15.072  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:15.072  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:15.072  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 15:43:15.072  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:15.073  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 15:43:15.077  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:15.077  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:15.077  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:15.078  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a034e not in the list
08-26 15:43:15.078  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 15:43:15.078  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 15:43:15.078  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 15:43:15.078  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 15:43:15.078  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 15:43:15.079  3844  3895 D BluetoothAdapter: STATE_ON
08-26 15:43:15.079  4211  4251 D BtGatt.GattService: stopScan() - queue size =1
,08-26 15:43:15.080  4211  4240 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 15:43:15.080  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 15:43:15.081  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 15:43:15.081  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 15:43:15.081  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 15:43:15.081  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 15:43:15.081  4211  4227 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 15:43:15.081  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 15:43:15.083  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 15:43:15.083  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 15:43:15.083  3844  3895 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 15:43:15.083  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 15:43:15.084  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:15.085  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:15.085  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:15.085  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:15.085  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1bc605 removed from the list
08-26 15:43:15.085  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:15.085  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:15.085  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:15.085  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 15:43:15.085  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7d05d7c removed from the list
08-26 15:43:15.086  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:15.086  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@397bd81 added. We now have 2 listener(s)
,08-26 15:43:15.086  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 15:43:15.086  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 15:43:15.087  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:43:15.087  3844  3844 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 15:43:15.087  3844  3844 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 15:43:15.087  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 15:43:15.087  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:15.088  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:15.088  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 15:43:15.088  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61f2e26 added. We now have 9 listener(s)
,08-26 15:43:15.088  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:15.088  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 15:43:15.090  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 15:43:15.091  4211  4227 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 15:43:15.092  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:15.092  4211  4230 D BtGatt.ScanManager: stopping BLe Batch
08-26 15:43:15.095  3844  3895 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:43:15.095  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:43:15.095  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:43:15.095  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:43:15.095  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:43:15.095  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:15.095  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:43:15.095  3844  3895 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:43:15.096  3844  3895 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 15:43:15.096  3844  3895 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:43:15.096  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 15:43:15.097  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@874e014 added. We now have 3 listener(s)
08-26 15:43:15.097  4211  4227 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 15:43:15.097  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 15:43:15.097  4211  4230 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 15:43:15.098  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:15.100  3844  3844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:43:15.100  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 15:43:15.101  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:43:15.101  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 15:43:15.101  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 15:43:15.101  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@981b0bd added. We now have 10 listener(s)
08-26 15:43:15.101  3844  3895 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:43:15.101  3844  3895 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 15:43:15.101  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 15:43:15.101  3844  3895 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 15:43:15.101  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 15:43:15.101  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:15.101  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 15:43:15.101  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:15.102  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@397bd81 removed from the list
08-26 15:43:15.102  4211  4227 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 15:43:15.102  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:15.102  4211  4227 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 15:43:15.102  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61f2e26 removed from the list
08-26 15:43:15.102  3844  3895 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 15:43:15.102  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:15.103  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:15.103  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:15.103  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:15.103  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 15:43:15.103  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:15.103  3844  3895 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61f2e26 not in the list
08-26 15:43:15.104  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:15.104  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:15.104  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 15:43:15.104  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 15:43:15.104  3844  3895 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 15:43:15.104  3844  3895 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@981b0bd removed from the list
08-26 15:43:15.104  3844  3895 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 15:43:15.104  3844  3895 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 15:43:15.104  3844  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 15:43:15.104  3844  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 15:43:15.105  3844  3895 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@874e014 removed from the list
08-26 15:43:15.105  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 15:43:15.105  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 15:43:15.105  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 15:43:15.105  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 15:43:15.105  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 15:43:15.105  3844  3895 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 15:43:15.109  3844  4289 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: My test thread name)
,08-26 15:43:15.109  3844  4289 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: My test thread name)
08-26 15:43:15.109  3844  4289 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 15:43:15.111  3844  4290 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 444, name: My test thread name)
,08-26 15:43:15.111  3844  4290 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 444, thread name: My test thread name)
08-26 15:43:15.111  3844  4290 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 444, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 15:43:15.112  3844  3895 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 15:43:15.112  3844  3895 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-26 15:43:15.112  3844  3895 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 15:43:15.112  3844  3895 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 15:43:15.112  3844  3895 D com.test.thalitest.ThaliTestRunner: Total duration: 22804 ms
,08-26 15:43:15.113  3844  3895 I jxcore-log: *Native tests were executed*
08-26 15:43:15.113  3844  3895 I jxcore-log: 
08-26 15:43:15.113  3844  3895 I jxcore-log: Total number of executed tests:  80
08-26 15:43:15.113  3844  3895 I jxcore-log: 
08-26 15:43:15.113  3844  3895 I jxcore-log: Number of passed tests:  80
08-26 15:43:15.113  3844  3895 I jxcore-log: 
08-26 15:43:15.113  3844  3895 I jxcore-log: Number of failed tests:  0
08-26 15:43:15.113  3844  3895 I jxcore-log: 
08-26 15:43:15.114  3844  3895 I jxcore-log: Number of ignored tests:  0
08-26 15:43:15.114  3844  3895 I jxcore-log: 
,08-26 15:43:15.114  3844  3895 I jxcore-log: Total duration:  22804
08-26 15:43:15.114  3844  3895 I jxcore-log: 
08-26 15:43:15.114  3844  3895 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 15:43:15.114  3844  3895 I jxcore-log: 
,08-26 15:43:15.116  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.116  3844  3895 I jxcore-log: 
08-26 15:43:15.117  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.117  3844  3895 I jxcore-log: 
08-26 15:43:15.118  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.118  3844  3895 I jxcore-log: 
08-26 15:43:15.119  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.119  3844  3895 I jxcore-log: 
08-26 15:43:15.119  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.119  3844  3895 I jxcore-log: 
08-26 15:43:15.120  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.120  3844  3895 I jxcore-log: 
08-26 15:43:15.121  3844  3844 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 15:43:15.122  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.122  3844  3895 I jxcore-log: 
08-26 15:43:15.123  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:15.123  3844  3895 I jxcore-log: 
08-26 15:43:15.124  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:15.124  3844  3895 I jxcore-log: 
08-26 15:43:15.124  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:15.124  3844  3895 I jxcore-log: 
08-26 15:43:15.125  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:15.125  3844  3895 I jxcore-log: 
08-26 15:43:15.126  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:15.126  3844  3895 I jxcore-log: 
08-26 15:43:15.126  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:15.126  3844  3895 I jxcore-log: 
08-26 15:43:15.127  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 15:43:15.127  3844  3895 I jxcore-log: 
08-26 15:43:15.127  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.127  3844  3895 I jxcore-log: 
08-26 15:43:15.128  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.128  3844  3895 I jxcore-log: 
08-26 15:43:15.128  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:15.128  3844  3895 I jxcore-log: 
08-26 15:43:15.129  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:15.129  3844  3895 I jxcore-log: 
08-26 15:43:15.129  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:15.129  3844  3895 I jxcore-log: 
08-26 15:43:15.129  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:15.129  3844  3895 I jxcore-log: 
08-26 15:43:15.130  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:15.130  3844  3895 I jxcore-log: 
08-26 15:43:15.130  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 15:43:15.130  3844  3895 I jxcore-log: 
08-26 15:43:15.131  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:15.131  3844  3895 I jxcore-log: 
08-26 15:43:15.131  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 15:43:15.131  3844  3895 I jxcore-log: 
08-26 15:43:15.132  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:15.132  3844  3895 I jxcore-log: 
08-26 15:43:15.132  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 15:43:15.132  3844  3895 I jxcore-log: 
08-26 15:43:15.133  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.133  3844  3895 I jxcore-log: 
08-26 15:43:15.133  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.133  3844  3895 I jxcore-log: 
08-26 15:43:15.133  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.133  3844  3895 I jxcore-log: 
08-26 15:43:15.134  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.134  3844  3895 I jxcore-log: 
08-26 15:43:15.134  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.134  3844  3895 I jxcore-log: 
,08-26 15:43:15.135  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:43:15.135  3844  3895 I jxcore-log: 
,08-26 15:43:15.145   875  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-26 15:43:15.413  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:43:15.416  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:15.416  3844  3895 I jxcore-log: 
,08-26 15:43:15.489  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:43:15.492  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:15.492  3844  3895 I jxcore-log: 
,08-26 15:43:15.587  3844  3844 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 15:43:15.590  3844  3895 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 15:43:15.590  3844  3895 I jxcore-log: 
,08-26 15:43:15.770  4292  4292 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 15:43:15.775  4292  4292 D AndroidRuntime: CheckJNI is OFF
,08-26 15:43:15.818  4292  4292 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 15:43:15.863  4292  4292 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 15:43:15.886  4292  4292 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 15:43:15.896   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-26 15:43:15.898   875   888 I ActivityManager: Killing 3844:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 15:43:15.999   875  1309 D WifiService: Client connection lost with reason: 4
,08-26 15:43:16.000   875   885 D GraphicsStats: Buffer count: 2
,08-26 15:43:16.000   875  1994 I WindowState: WIN DEATH: Window{ecc07e2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 15:43:16.017   875   898 W PackageSettings: Skipping PackageSetting{b49a967 com.example.hello/10273} due to missing metadata
,08-26 15:43:16.054   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-26 15:43:16.054   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-26 15:43:16.055   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-26 15:43:16.055   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 15:43:16.055   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.055   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.055   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 15:43:16.055   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 15:43:16.056   875   888 I ActivityManager:   Force finishing activity ActivityRecord{971cc1b u0 com.test.thalitest/.MainActivity t2}
,08-26 15:43:16.059   875   898 I art     : Starting a blocking GC Explicit
,08-26 15:43:16.068   875  1992 W ActivityManager: Spurious death for ProcessRecord{af3e31f 0:com.test.thalitest/u0a0}, curProc for 3844: null
,08-26 15:43:16.113   875   898 I art     : Explicit concurrent mark sweep GC freed 14528(998KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 810us total 54.580ms
,08-26 15:43:16.138   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 15:43:16.140  4292  4292 I art     : System.exit called, status: 0
08-26 15:43:16.140  4292  4292 I AndroidRuntime: VM exiting with result code 0.
,08-26 15:43:16.144   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 15:43:16.154   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 15:43:16.159  4211  4211 D BluetoothMapAppObserver: onReceive
08-26 15:43:16.159  4211  4211 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-26 15:43:16.168   875  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-26 15:43:16.169  2133  2275 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 15:43:16.170  3640  3640 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-26 15:43:16.171  1862  1862 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-26 15:43:16.181  1862  4303 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 15:43:16.184  1862  4303 I Decoder : createOrResetDecoder
,08-26 15:43:16.198   875  2114 I ActivityManager: Start proc 4306:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 15:43:16.237  1501  1501 I ConfigService: onCreate
08-26 15:43:16.241  1922  1922 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 15:43:16.266  1862  4303 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 15:43:16.278   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 15:43:16.286   875  2115 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3844 uid 10000
,08-26 15:43:16.288  1862  1862 I Keyboard.Facilitator: onFinishInput()
,08-26 15:43:16.291  4306  4306 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 15:43:16.319  1862  4303 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-26 15:43:16.322  1862  4303 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-26 15:43:16.322  1862  4303 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 15:43:16.323  1940  2060 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-26 15:43:16.324   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-26 15:43:16.325   875   887 E PackageManager: Failed to write settings, restoring backup
08-26 15:43:16.325   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 15:43:16.325   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 15:43:16.325   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 15:43:16.325   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 15:43:16.325   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 15:43:16.325   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.325   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.325   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 15:43:16.326  1862  4303 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-26 15:43:16.326  1862  4303 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-26 15:43:16.326  1862  4303 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-26 15:43:16.326  1862  4303 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-26 15:43:16.329  1862  4303 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-26 15:43:16.329  1862  4303 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-26 15:43:16.329  1862  4303 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-26 15:43:16.329  1862  4303 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 15:43:16.329  1862  4303 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-26 15:43:16.329   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-26 15:43:16.329   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 15:43:16.329   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 15:43:16.329   875   888 E DropBoxManagerService: 	... 13 more
,08-26 15:43:16.329  1862  4303 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 15:43:16.336   875  2104 I ActivityManager: Start proc 4322:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-26 15:43:16.336  1940  2060 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 15:43:16.336  1940  2060 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1940
08-26 15:43:16.336  1940  2060 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.336  1940  2060 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 15:43:16.339   875  1385 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 15:43:16.340   875  4328 E DropBoxManagerService: Can't write: system_app_crash
08-26 15:43:16.340   875  4328 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 15:43:16.340   875  4328 E DropBoxManagerService: 	... 5 more
,08-26 15:43:16.345  1940  2060 I Process : Sending signal. PID: 1940 SIG: 9
,08-26 15:43:16.353  4306  4306 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 15:43:16.376  4306  4336 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 15:43:16.381   875   885 I ActivityManager: Start proc 4337:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 15:43:16.386  4306  4321 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.386  4306  4321 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.387  4306  4321 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 15:43:16.392   875  1990 D GraphicsStats: Buffer count: 1
08-26 15:43:16.392   875  1384 I WindowState: WIN DEATH: Window{8225963 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-26 15:43:16.424   875  1988 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1940) has died
08-26 15:43:16.425   875  1988 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-26 15:43:16.427   875  1988 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-26 15:43:16.446   875  2114 I ActivityManager: Start proc 4349:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 15:43:16.477  4337  4337 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 15:43:16.502  4349  4349 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:43:16.502  4349  4349 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 15:43:16.502  4349  4349 D AndroidRuntime: Shutting down VM
08-26 15:43:16.502  1501  1501 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-26 15:43:16.503  1501  1501 D AndroidRuntime: Shutting down VM
,08-26 15:43:16.504  1501  1501 E AndroidRuntime: FATAL EXCEPTION: main
08-26 15:43:16.504  1501  1501 E AndroidRuntime: Process: com.google.process.gapps, PID: 1501
08-26 15:43:16.504  1501  1501 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 15:43:16.504  1501  1501 E AndroidRuntime: 	... 8 more
08-26 15:43:16.510  4349  4349 E AndroidRuntime: FATAL EXCEPTION: main
08-26 15:43:16.510  4349  4349 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4349
08-26 15:43:16.510  4349  4349 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.510  4349  4,349 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 15:43:16.510  4349  4349 E AndroidRuntime: 	... 10 more
08-26 15:43:16.511   875  4365 E DropBoxManagerService: Can't write: system_app_crash
08-26 15:43:16.511   875  4365 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: Caused by: andr,oid.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 15:43:16.511   875  4365 E DropBoxManagerService: 	... 5 more
08-26 15:43:16.513   875  2115 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 15:43:16.514   875  4366 E DropBoxManagerService: Can't write: system_app_crash
08-26 15:43:16.514   875  4366 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 15:43:16.514   875  4366 E DropBoxManagerService: 	... 5 more
08-26 15:43:16.514  1501  1501 I Process : Sending signal. PID: 1501 SIG: 9
08-26 15:43:16.514  4349  4349 I Process : Sending signal. PID: 4349 SIG: 9
08-26 15:43:16.539  1730  4367 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
08-26 15:43:16.540  1730  4367 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@93d8f7f
08-26 15:43:16.540   875  1939 I ActivityManager: Process com.google.process.gapps (pid 1501) early provider death
08-26 15:43:16.546  4306  4321 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-26 15:43:16.550  4306  4336 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.550  4306  4336 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 15:43:16.551  4306  4336 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 15:43:16.551  4306  4336 E AndroidRuntime: Process: android.process.acore, PID: 4306
08-26 15:43:16.551  4306  4336 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 15:43:16.551  4306  4336 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 15:43:16.551  4306  4321 I Process : Sending signal. PID: 4306 SIG: 9
,08-26 15:43:16.561   875  1309 D WifiService: Client connection lost with reason: 4
,08-26 15:43:16.567   875  1939 I ActivityManager: Process com.google.process.gapps (pid 1501) has died
,08-26 15:43:16.567   875  1939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 1000ms
08-26 15:43:16.567   875  1939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-26 15:43:16.567   875  1939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-26 15:43:16.568   875  1939 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
08-26 15:43:16.569   875  1992 W ActivityManager: Spurious death for ProcessRecord{f888191 0:com.google.process.gapps/u0a11}, curProc for 1501: null
,08-26 15:43:16.571   875  4369 E DropBoxManagerService: Can't write: system_app_crash
08-26 15:43:16.571   875  4369 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 15:43:16.571   875  4369 E DropBoxManagerService: 	... 5 more
,08-26 15:43:16.592   875  1937 I ActivityManager: Start proc 4371:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-26 15:43:16.594   875  1384 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4349) has died
,08-26 15:43:16.595   875  1384 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 15:43:16.599   875   885 I ActivityManager: Process android.process.acore (pid 4306) has died
,08-26 15:43:16.599   875   885 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40969ms
,08-26 15:43:16.604  1730  1730 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-26 15:43:16.612   875   888 I ActivityManager: Start proc 4382:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 15:43:16.628  4371  4371 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm

```
