#### Test 85009927e02c5f0_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
,09-13 13:21:39.877   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
--------- beginning of main
09-13 13:21:40.572  3905  3905 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 13:21:40.577  3905  3905 D AndroidRuntime: CheckJNI is OFF
09-13 13:21:40.620  3905  3905 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 13:21:40.673  3905  3905 I Radio-JNI: register_android_hardware_Radio DONE
09-13 13:21:40.696  3905  3905 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-13 13:21:40.701   872  1988 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 13:21:40.718  2042  3891 W SearchService: Abort, client detached.
09-13 13:21:40.735  2042  2350 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7ccfe49
09-13 13:21:40.735  2042  2042 I HotwordDetector: Closing mic
09-13 13:21:40.736  2042  2371 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-13 13:21:40.738  3905  3905 D AndroidRuntime: Shutting down VM
09-13 13:21:40.749   872  2097 I ActivityManager: Start proc 3914:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-13 13:21:40.798   374  2373 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-13 13:21:40.799   374  2373 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-13 13:21:40.802   374  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-13 13:21:40.804  2042  2370 I MicroRecognitionRnrImpl: Detection finished
09-13 13:21:40.805  2042  2363 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-13 13:21:40.840  3914  3914 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-13 13:21:40.870  3914  3914 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-13 13:21:40.879  3914  3914 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9841-9844)
09-13 13:21:40.879  3914  3914 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 13:21:40.899  3914  3914 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {771efb0}
09-13 13:21:40.900  3914  3914 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 13:21:40.900  3914  3914 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-13 13:21:40.909  3914  3914 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 13:21:40.910  3914  3914 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 13:21:40.945  3914  3914 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-13 13:21:40.964  3914  3914 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 13:21:40.964  3914  3914 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 13:21:40.964  3914  3914 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 13:21:40.964  3914  3914 I Adreno  : Build Date                       : 10/20/15
09-13 13:21:40.964  3914  3914 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 13:21:40.964  3914  3914 I Adreno  : Local Branch                     : M14
09-13 13:21:40.964  3914  3914 I Adreno  : Remote Branch                    : 
09-13 13:21:40.964  3914  3914 I Adreno  : Remote Branch                    : 
09-13 13:21:40.964  3914  3914 I Adreno  : Reconstruct Branch               : 
,09-13 13:21:41.002   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c05f411:true
09-13 13:21:41.042  3914  3914 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-13 13:21:41.054  3914  3914 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
09-13 13:21:41.093  3914  3951 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-13 13:21:41.102  3914  3938 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-13 13:21:41.134  3914  3951 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 13:21:41.205   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +464ms
09-13 13:21:41.206  1878  1878 I Keyboard.Facilitator: onFinishInput()
09-13 13:21:41.275  3914  3914 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3914
09-13 13:21:41.395  3914  3914 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-13 13:21:41.566   872  2100 I ActivityManager: Killing 3502:com.google.android.music:main/u0a66 (adj 15): empty #17
09-13 13:21:41.577  3914  3953 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1719928528
09-13 13:21:41.585  3914  3953 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 13:21:41.585  3914  3953 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 13:21:41.585  3914  3953 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 13:21:41.585  3914  3953 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 13:21:41.585  3914  3953 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-13 13:21:41.585  3914  3953 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9be3507 added. We now have 1 listener(s)
09-13 13:21:41.592  3914  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-13 13:21:41.595  3914  3953 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 13:21:41.595  3914  3953 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:21:41.596  3914  3953 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 13:21:41.601  3914  3953 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87f1aa3 added. We now have 1 listener(s)
09-13 13:21:41.601  3914  3953 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:21:41.605   872  1314 D WifiService: New client listening to asynchronous messages
09-13 13:21:41.606  3914  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:21:41.606  3914  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-13 13:21:41.606  3914  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 13:21:41.606  3914  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 13:21:41.606  3914  3953 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 13:21:41.614   872  2100 I ActivityManager: Killing 3081:com.google.android.calendar/u0a37 (adj 15): empty #18
09-13 13:21:41.646  3914  3953 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:21:41.646  3914  3953 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
09-13 13:21:41.653  3914  3953 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-13 13:21:41.653  3914  3953 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:21:41.653  3914  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:21:41.653  3914  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:21:41.653  3914  3953 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:21:41.653  3914  3953 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:21:41.653  3914  3953 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:21:41.653  3914  3953 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:21:41.653  3914  3953 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:21:41.653  3914  3953 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-13 13:21:41.653  3914  3953 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:21:41.654  3914  3953 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 13:21:41.771  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:21:41.777  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:21:41.780  3914  3914 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-13 13:21:42.485  3914  3961 W jxcore-log: Initializing JXcore engine
09-13 13:21:42.485  3914  3961 W jxcore-log: JXcore engine is ready
09-13 13:21:42.518  3961  3961 W Thread-357: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-13 13:21:42.518  3961  3961 W Thread-357: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9805]" dev="sockfs" ino=9805 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-13 13:21:42.518  3961  3961 W Thread-357: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 13:21:42.518  3961  3961 W Thread-357: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25187]" dev="sockfs" ino=25187 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 13:21:42.534  3914  3961 W jxcore-log: Starting JXcore engine
09-13 13:21:42.612  3914  3961 W jxcore-log: Platform android
09-13 13:21:42.612  3914  3961 W jxcore-log: 
09-13 13:21:42.612  3914  3961 W jxcore-log: Process ARCH arm
09-13 13:21:42.612  3914  3961 W jxcore-log: 
,09-13 13:21:42.821  3914  3961 I jxcore-log: JXcore Cordova bridge is ready!
09-13 13:21:42.821  3914  3961 I jxcore-log: 
,09-13 13:21:42.821  3914  3961 W jxcore-log: JXcore engine is started
,09-13 13:21:42.836  3914  3953 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-13 13:21:42.840  3914  3914 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-13 13:21:42.902   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:21:43.284   872  1312 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-13 13:21:44.605   872  1877 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:21:45.923   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:21:48.803  3692  3964 V KeepSync: Connecting to GoogleApiClient
,09-13 13:21:48.804   872  2100 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 13:21:48.856  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:21:48.862  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:21:48.898  1520  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 13:21:48.898  1520  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 13:21:48.898  1520  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:21:48.898  1520  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:21:48.912  1743  3965 V BaseAuthAsyncOperation: access token request failed
09-13 13:21:48.913  3692  3964 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 13:21:48.946   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:21:48.953  1520  3094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 13:21:48.953  1520  3094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 13:21:48.953  1520  3094 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:21:48.953  1520  3094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:21:48.972  3692  3964 E KeepSync: IOException
09-13 13:21:48.972  3692  3964 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 13:21:48.972  3692  3964 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:21:48.972  3692  3964 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 13:21:48.972  3692  3964 E KeepSync: 	... 10 more
,09-13 13:21:48.973  3692  3964 W KeepSync: Sync result 2
,09-13 13:21:48.984   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 127685, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:21:50.936  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:21:50.959  1520  2299 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 13:21:50.959  1520  2299 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 13:21:50.959  1520  2299 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:21:50.959  1520  2299 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:21:50.971  3606  3606 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 13:21:50.971  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 13:21:50.971  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,09-13 13:21:55.011   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:21:56.796  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 13:21:56.796  3914  3961 I jxcore-log: 
,09-13 13:21:56.799  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 13:21:56.799  3914  3961 I jxcore-log: 
,09-13 13:21:56.811  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:21:56.811  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:21:56.811  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:21:56.811  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:21:56.811  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,09-13 13:21:56.811  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:21:56.811  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:21:56.811  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:21:56.817  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:21:56.819  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 13:21:56.819  3914  3961 I jxcore-log: 
,09-13 13:21:56.821  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
09-13 13:21:56.821  3914  3961 I jxcore-log: ,
,09-13 13:21:57.173  3914  3961 I jxcore-log: Running unit tests
09-13 13:21:57.173  3914  3961 I jxcore-log: 
,09-13 13:21:57.173  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:21:57.174  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2407eb4 added. We now have 2 listener(s)
,09-13 13:21:57.175  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 13:21:57.175  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 13:21:57.175  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:21:57.175  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:21:57.175  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f48fadd added. We now have 2 listener(s)
09-13 13:21:57.175  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:21:57.176  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:21:57.182  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:21:57.191  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:21:57.191  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:21:57.191  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:21:57.191  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:21:57.191  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:21:57.191  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:21:57.191  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:21:57.191  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:21:57.196  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:21:57.197  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:21:57.199  3914  3961 D executeNativeTests: Running unit tests
09-13 13:21:57.200  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:21:57.205  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:21:57.289  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 13:21:57.290  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 added. We now have 3 listener(s)
09-13 13:21:57.291  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 13:21:57.291  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:21:57.291  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:21:57.291  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:21:57.291  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 added. We now have 3 listener(s)
09-13 13:21:57.291  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:21:57.292  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:21:57.296  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:21:57.309  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:21:57.309  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:21:57.309  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:21:57.309  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:21:57.309  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:21:57.309  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:21:57.309  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:21:57.309  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:21:57.315  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:21:57.315  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:21:57.318  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 13:21:57.318  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:21:57.318  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:21:57.318  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-13 13:21:57.319  3914  3961 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-13 13:21:57.320  3914  3961 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 13:21:57.325  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-13 13:21:57.326  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:21:57.326  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:21:57.326  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 13:21:57.326  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:21:57.327  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:21:57.328  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:21:57.328  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:21:57.328  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:21:57.328  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:21:57.329  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:21:57.329  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:21:57.329  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 removed from the list
,09-13 13:21:57.329  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:21:57.329  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 removed from the list
09-13 13:21:57.333  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:21:57.336  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:21:57.336  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:21:57.337  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:21:57.337  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:21:57.340  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:21:57.340  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:21:57.340  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:21:57.341  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
,09-13 13:21:57.346  3914  3961 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-13 13:21:57.348  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:21:57.349  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:21:57.349  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:21:57.349  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:21:57.350  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:21:57.350  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:21:57.350  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:21:57.350  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:21:57.351  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:21:57.351  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:21:57.351  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:21:57.351  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-13 13:21:57.351  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:21:57.352  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:21:57.354  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:21:57.354  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:21:57.354  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:21:57.355  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
,09-13 13:21:57.362  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-13 13:21:57.362  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 13:21:57.362  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 13:21:57.362  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-13 13:21:57.362  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 13:21:57.362  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 13:21:57.363  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 13:21:57.364  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-13 13:21:57.364  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:21:57.364  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:21:57.364  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:21:57.365  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:21:57.365  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:21:57.365  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:21:57.365  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
,09-13 13:21:57.365  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:21:57.365  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:21:57.365  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:21:57.365  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:21:57.365  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:21:57.365  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:21:57.365  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:21:57.367  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:21:57.367  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:21:57.367  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:21:57.367  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list,
09-13 13:21:57.368  3914  3961 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 13:21:57.370  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:21:57.379  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:21:57.379  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:21:57.379  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:21:57.379  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:21:57.379  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:21:57.379  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:21:57.379  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:21:57.379  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:21:57.384  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:21:57.384  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:21:57.384  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 13:21:57.384  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:21:57.385  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:21:57.385  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:21:57.385  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 13:21:57.387  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:21:57.391  3914  3961 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 13:21:57.391  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 13:21:57.392  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:21:57.399  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 13:21:57.402  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 13:21:57.402  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 13:21:57.406  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-13 13:21:57.409  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-13 13:21:57.409  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 13:21:57.410  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 13:21:57.411  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 13:21:57.412  3914  3961 D BluetoothAdapter: STATE_ON
,09-13 13:21:57.418  2672  2816 D BtGatt.GattService: registerClient() - UUID=a3cf3706-c893-4a5d-b2d8-786724ed532e
,09-13 13:21:57.419  2672  2707 D BtGatt.GattService: onClientRegistered() - UUID=a3cf3706-c893-4a5d-b2d8-786724ed532e, clientIf=5
,09-13 13:21:57.420  3914  3924 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 13:21:57.421  2672  2683 D BtGatt.GattService: start scan with filters
,09-13 13:21:57.426  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 13:21:57.426  2672  2710 D BtGatt.ScanManager: handling starting scan
,09-13 13:21:57.427  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 13:21:57.427  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 13:21:57.427  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 13:21:57.430  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 13:21:57.430  2672  2710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
09-13 13:21:57.431  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 13:21:57.431  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 13:21:57.433  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:21:57.436  3914  3961 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 13:21:57.442  2672  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 13:21:57.443  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:21:57.444  2672  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 13:21:57.454  2672  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-13 13:21:57.454  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-13 13:21:57.456  2672  2710 D BtGatt.ScanManager: Starting BLE batch scan
,09-13 13:21:57.456  2672  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 13:21:57.477  2672  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 13:21:57.478  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:21:57.492  2672  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 13:21:57.493  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:21:57.933  3914  3914 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 13:21:57.934  3914  3914 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 13:21:57.934  3914  3914 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:21:58.053   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:21:58.998  2672  2672 D BtGatt.ScanManager: awakened up at time 137964
,09-13 13:21:59.000  2672  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:21:59.035  2672  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-13 13:21:59.035  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:21:59.036  2672  2707 D BtGatt.GattService: current time is 138001768263
,09-13 13:21:59.037  2672  2707 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -84, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -94, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -84, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -99, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 13:21:59.040  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 13:21:59.042  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 13:21:59.042  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 13:21:59.043  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 13:21:59.043  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 13:22:00.541  2672  2672 D BtGatt.ScanManager: awakened up at time 139507
,09-13 13:22:00.545  2672  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:22:00.554  2672  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 13:22:00.555  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:02.057  2672  2672 D BtGatt.ScanManager: awakened up at time 141022
,09-13 13:22:02.061  2672  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:22:02.114  2672  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-13 13:22:02.114  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:02.115  2672  2707 D BtGatt.GattService: current time is 141080730989
,09-13 13:22:02.115  2672  2707 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -88, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -87, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -69, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 13:22:02.116  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 13:22:02.117  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 13:22:02.118  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 13:22:02.119  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-13 13:22:02.119  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-13 13:22:02.446  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:02.447  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:22:02.447  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 13:22:02.447  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:02.448  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 13:22:02.448  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:22:02.449  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 13:22:02.449  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 13:22:02.449  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 13:22:02.451  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:22:02.451  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 13:22:02.454  3914  3961 D BluetoothAdapter: STATE_ON
,09-13 13:22:02.460  2672  2816 D BtGatt.GattService: stopScan() - queue size =1
,09-13 13:22:02.463  2672  2683 D BtGatt.GattService: unregisterClient() - clientIf=5,
,09-13 13:22:02.464  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:22:02.465  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 13:22:02.465  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 13:22:02.465  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 13:22:02.466  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 13:22:02.470  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:22:02.472  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 13:22:02.472  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 13:22:02.473  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:22:02.475  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:22:02.478  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:22:02.478  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:22:02.479  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:02.479  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:22:02.479  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:22:02.479  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:02.480  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:02.480  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:22:02.480  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:02.480  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:02.480  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:02.483  2672  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 13:22:02.483  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:02.484  2672  2710 D BtGatt.ScanManager: stopping BLe Batch
,09-13 13:22:02.498  2672  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 13:22:02.498  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:22:02.499  2672  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:22:02.512  2672  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 13:22:02.512  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:02.981  3914  3914 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:22:04.097   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:22:07.124   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-13 13:22:07.482  3914  3961 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 13:22:07.487  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:22:07.497  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:22:07.497  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:07.497  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:07.497  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:07.497  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:22:07.497  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:22:07.497  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:22:07.497  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:22:07.502  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:22:07.503  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:22:07.503  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-13 13:22:07.503  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:22:07.503  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:22:07.504  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:22:07.504  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 13:22:07.517  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:07.520  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:07.525  3914  3961 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 13:22:07.526  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 13:22:07.530  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 13:22:07.533  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 13:22:07.533  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 13:22:07.540  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 13:22:07.540  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-13 13:22:07.541  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-13 13:22:07.541  3914  3961 D BluetoothAdapter: STATE_ON
,09-13 13:22:07.545  2672  2683 D BtGatt.GattService: registerClient() - UUID=dc371da6-dc81-44f7-97a6-fe9bc15e1385
,09-13 13:22:07.545  2672  2707 D BtGatt.GattService: onClientRegistered() - UUID=dc371da6-dc81-44f7-97a6-fe9bc15e1385, clientIf=5
,09-13 13:22:07.546  3914  3925 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 13:22:07.546  2672  2816 D BtGatt.GattService: start scan with filters
,09-13 13:22:07.549  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 13:22:07.549  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-13 13:22:07.549  2672  2710 D BtGatt.ScanManager: handling starting scan,
,09-13 13:22:07.549  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 13:22:07.549  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 13:22:07.551  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 13:22:07.551  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 13:22:07.551  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 13:22:07.552  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:22:07.554  3914  3961 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 13:22:07.556  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:22:07.556  3914  3961 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-13 13:22:07.556  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:07.556  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 13:22:07.556  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-13 13:22:07.556  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 13:22:07.556  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:22:07.556  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 13:22:07.556  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:22:07.556  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 13:22:07.556  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-13 13:22:07.556  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 13:22:07.557  3914  3961 D BluetoothAdapter: STATE_ON
09-13 13:22:07.557  2672  2683 D BtGatt.GattService: stopScan() - queue size =1
09-13 13:22:07.558  2672  2816 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 13:22:07.558  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:22:07.558  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 13:22:07.558  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 13:22:07.559  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
09-13 13:22:07.559  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 13:22:07.561  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:22:07.561  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 13:22:07.561  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 13:22:07.561  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:22:07.561  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:22:07.562  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:07.562  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:07.562  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:22:07.562  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
,09-13 13:22:07.562  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:07.562  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:07.567  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:07.567  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:22:07.574  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:22:07.574  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:07.574  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:22:07.562  2672  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 13:22:07.574  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:22:07.575  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:07.575  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:07.575  2672  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 13:22:07.575  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:07.575  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 13:22:07.576  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:07.576  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:07.576  3914  3961 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-13 13:22:07.578  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:22:07.582  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:22:07.582  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:07.582  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:07.582  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:07.582  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:22:07.582  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:22:07.582  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:22:07.582  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:22:07.583  2672  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 13:22:07.583  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:07.583  2672  2710 D BtGatt.ScanManager: Starting BLE batch scan
09-13 13:22:07.583  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:22:07.583  2672  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 13:22:07.583  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:22:07.584  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:22:07.584  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:22:07.584  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-13 13:22:07.584  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:22:07.584  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:22:07.586  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-13 13:22:07.587  3914  3961 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 13:22:07.587  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 13:22:07.588  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:07.591  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 13:22:07.591  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-13 13:22:07.591  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 13:22:07.593  2672  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 13:22:07.593  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:07.594  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-13 13:22:07.594  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 13:22:07.594  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 13:22:07.595  3914  3961 D BluetoothAdapter: STATE_ON,
,09-13 13:22:07.596  2672  2817 D BtGatt.GattService: registerClient() - UUID=ed3037a3-0cfb-40c9-832f-4059fe989a3a
09-13 13:22:07.597  2672  2707 D BtGatt.GattService: onClientRegistered() - UUID=ed3037a3-0cfb-40c9-832f-4059fe989a3a, clientIf=5
,09-13 13:22:07.597  3914  3924 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 13:22:07.597  2672  2684 D BtGatt.GattService: start scan with filters
09-13 13:22:07.598  2672  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 13:22:07.598  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:22:07.599  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-13 13:22:07.599  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 13:22:07.600  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 13:22:07.600  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 13:22:07.602  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 13:22:07.602  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 13:22:07.602  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 13:22:07.603  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:22:07.605  2672  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-13 13:22:07.605  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:22:07.605  2672  2710 D BtGatt.ScanManager: stopping BLe Batch
,09-13 13:22:07.606  3914  3961 I io.jxcore.node.ConnectionHelper: start: OK
,09-13 13:22:07.610  2672  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 13:22:07.610  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:22:07.610  2672  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:22:07.614  2672  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-13 13:22:07.614  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:07.616  2672  2710 D BtGatt.ScanManager: handling starting scan
,09-13 13:22:07.620  2672  2707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 13:22:07.621  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:07.621  2672  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 13:22:07.625  2672  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 13:22:07.626  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:07.626  2672  2710 D BtGatt.ScanManager: Starting BLE batch scan
09-13 13:22:07.626  2672  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 13:22:07.634  2672  2707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-13 13:22:07.634  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:07.640  2672  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 13:22:07.640  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:08.103  3914  3914 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 13:22:08.103  3914  3914 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:22:08.104  3914  3914 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:22:09.146  2672  2672 D BtGatt.ScanManager: awakened up at time 148111
,09-13 13:22:09.150  2672  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:22:09.198  2672  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-13 13:22:09.199  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:09.199  2672  2707 D BtGatt.GattService: current time is 148165386279
,09-13 13:22:09.200  2672  2707 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -92, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -103, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -84, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 13:22:09.201  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
09-13 13:22:09.202  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 13:22:09.214  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 13:22:09.215  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 13:22:09.216  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-13 13:22:10.703  2672  2672 D BtGatt.ScanManager: awakened up at time 149669
,09-13 13:22:10.706  2672  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:22:10.716  2672  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 13:22:10.716  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:22:10.964   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-13 13:22:10.977  1878  1878 I Keyboard.Facilitator: onFinishInput()
,09-13 13:22:10.995   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 13:22:10.995   872   892 I Adreno  : Build Date                       : 10/20/15
09-13 13:22:10.995   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 13:22:10.995   872   892 I Adreno  : Local Branch                     : M14
09-13 13:22:10.995   872   892 I Adreno  : Remote Branch                    : 
09-13 13:22:10.995   872   892 I Adreno  : Remote Branch                    : 
09-13 13:22:10.995   872   892 I Adreno  : Reconstruct Branch               : 
,09-13 13:22:11.035   281  1673 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (197 us)
,09-13 13:22:11.616  3914  3914 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 13:22:11.617  3914  3914 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-13 13:22:11.689   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-13 13:22:11.689  3914  3914 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a165c86 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@e412bbd, 16908290=android.view.AbsSavedState$1@e412bbd}, android:focusedViewId=100}]}]
09-13 13:22:11.689  3914  3914 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-13 13:22:11.690  3914  3914 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-13 13:22:11.690  3914  3914 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-13 13:22:11.698   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-13 13:22:11.701   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-13 13:22:11.704   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-13 13:22:11.704   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-13 13:22:11.955   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-13 13:22:11.959   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-13 13:22:11.964   872  1338 D SurfaceControl: Excessive delay in setPowerMode(): 263ms
,09-13 13:22:11.968   872   892 I DreamManagerService: Entering dreamland.
,09-13 13:22:11.969   872   892 I PowerManagerService: Dozing...
09-13 13:22:11.971   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-13 13:22:12.064   374  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-13 13:22:12.065   374  1322 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-13 13:22:12.085  2672  2672 D BtGatt.ScanManager: awakened up at time 151050
,09-13 13:22:12.085   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:22:12.112   872  1312 E native  : do suspend false
,09-13 13:22:12.130  2672  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:22:12.133  1936  3976 D NfcService: Discovery configuration equal, not updating.
,09-13 13:22:12.136   872  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 13:22:12.165  2672  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-13 13:22:12.165  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:22:12.165  2672  2707 D BtGatt.GattService: current time is 151131450637
09-13 13:22:12.166  2672  2707 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -87, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -87, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -86, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -94, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-13 13:22:12.166  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 13:22:12.166  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 13:22:12.166  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-13 13:22:12.166  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-13 13:22:12.166  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-13 13:22:12.167  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 13:22:12.168   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:22:12.172   872  1312 E native  : do suspend true
,09-13 13:22:12.186   374  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-13 13:22:12.186   374  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-13 13:22:12.273  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:22:12.287  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:22:12.291  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:22:12.330  1520  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 13:22:12.330  1520  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-13 13:22:12.330  1520  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:22:12.330  1520  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:22:12.358  3606  3606 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 13:22:12.358  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 13:22:12.358  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-13 13:22:12.590   872  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,09-13 13:22:12.606  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:22:12.607  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:12.608  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 13:22:12.608  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:12.608  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-13 13:22:12.608  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:22:12.609  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 13:22:12.609  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:22:12.609  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 13:22:12.610  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:22:12.611  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 13:22:12.613  3914  3961 D BluetoothAdapter: STATE_ON
09-13 13:22:12.615  2672  2817 D BtGatt.GattService: stopScan() - queue size =1
,09-13 13:22:12.617  2672  2684 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 13:22:12.618  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:22:12.619  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 13:22:12.619  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-13 13:22:12.619  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 13:22:12.620  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 13:22:12.626  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:22:12.626  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 13:22:12.626  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 13:22:12.626  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:22:12.626  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:22:12.628  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:22:12.628  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:22:12.628  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:22:12.632  2672  2707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 13:22:12.632  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:22:12.632  2672  2710 D BtGatt.ScanManager: stopping BLe Batch
,09-13 13:22:12.639  2672  2707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 13:22:12.639  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:22:12.639  2672  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:22:12.654  2672  2707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-13 13:22:12.654  2672  2707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:22:12.654  2672  2707 D BtGatt.GattService: current time is 151620392144
,09-13 13:22:12.654  2672  2707 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -86, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 13:22:12.655  2672  2707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 13:22:13.129  3914  3914 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:22:13.129  3914  3914 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:22:13.130  3914  3914 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:22:14.370  1520  2214 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 13:22:17.629  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:22:17.630  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:22:17.630  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:17.631  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:17.631  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:17.631  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:22:17.632  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
,09-13 13:22:17.632  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.633  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
,09-13 13:22:17.633  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:17.633  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.635  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.635  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:17.642  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:22:17.642  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 13:22:17.642  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:17.643  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
,09-13 13:22:17.645  3914  3961 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-13 13:22:17.647  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:22:17.647  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:17.648  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:17.649  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:17.649  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.649  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.650  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:17.650  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.650  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.652  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:17.653  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:17.653  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.653  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.653  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.655  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:17.655  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:17.655  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.655  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.656  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 13:22:17.656  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:17.656  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:17.656  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:17.657  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:22:17.657  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.657  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.657  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:17.657  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.657  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.657  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:17.658  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.658  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.658  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.658  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:17.660  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:17.660  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:17.661  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.661  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.663  3914  3961 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 13:22:17.663  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:17.664  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:17.664  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:17.664  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:22:17.664  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.665  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.665  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:17.665  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.666  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.666  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:17.666  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.666  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.667  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.667  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:17.669  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:22:17.670  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:17.670  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.670  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
,09-13 13:22:17.672  3914  3961 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-13 13:22:17.672  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:17.673  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:17.673  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:22:17.673  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:17.674  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.674  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.674  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:17.674  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:17.675  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.675  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:17.675  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.675  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.676  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:17.676  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:17.678  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:17.678  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 13:22:17.678  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.678  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.679  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 13:22:17.679  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:22:17.679  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:22:17.679  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 13:22:17.679  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:22:17.680  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-13 13:22:17.680  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 13:22:17.680  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:22:17.680  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 13:22:17.680  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:17.680  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:17.680  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:17.681  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:17.681  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.682  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:17.682  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:17.682  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.682  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.682  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:17.682  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.682  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:17.682  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.682  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.684  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:17.684  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:17.684  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.684  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.685  3914  3961 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:22:17.685  3914  3961 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 13:22:17.685  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 13:22:17.689  3914  3961 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:22:17.689  3914  3961 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 13:22:17.689  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 13:22:17.689  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 13:22:17.689  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-13 13:22:17.689  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-13 13:22:17.690  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 13:22:17.690  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 13:22:17.690  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 13:22:17.690  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-13 13:22:17.690  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 13:22:17.690  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 13:22:17.690  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 13:22:17.691  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 13:22:17.692  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 13:22:17.692  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 13:22:17.692  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 13:22:17.692  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 13:22:17.692  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 13:22:17.692  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 13:22:17.692  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 13:22:17.692  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 13:22:17.692  3914  3961 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 13:22:17.693  3914  3961 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 13:22:17.693  3914  3961 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 13:22:17.693  3914  3961 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:22:17.693  3914  3961 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 13:22:17.693  3914  3961 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 13:22:17.693  3914  3961 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 13:22:17.693  3914  3961 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 13:22:17.694  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 13:22:17.697  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 13:22:17.698  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 13:22:17.698  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-13 13:22:17.699  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 13:22:17.699  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-13 13:22:17.699  3914  3961 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 13:22:17.699  3914  3961 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-13 13:22:17.700  3914  3961 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 13:22:17.700  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:17.700  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:17.700  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:17.701  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:17.701  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:17.701  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:17.701  3914  3981 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 422)
,09-13 13:22:17.702  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 13:22:17.703  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:17.703  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:17.703  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
,09-13 13:22:17.704  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:17.704  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:17.704  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.704  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.704  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-13 13:22:17.705  3914  3982 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 422
,09-13 13:22:17.707  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:17.707  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:17.707  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:17.707  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.708  3914  3961 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 13:22:17.708  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-13 13:22:17.709  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:17.709  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:17.709  3914  3981 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:22:17.709  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:17.709  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.709  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:17.709  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:17.709  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.710  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
,09-13 13:22:17.710  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:17.710  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:17.710  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.710  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.710  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.713  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:17.713  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:17.713  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:17.714  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.715  3914  3961 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 13:22:17.715  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:17.716  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:17.716  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:17.716  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:17.716  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.716  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.716  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:17.716  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.716  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.717  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:22:17.717  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.717  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.717  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.717  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.719  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:17.719  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:17.719  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.719  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.720  3914  3961 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 13:22:17.720  3914  3961 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 13:22:17.720  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 13:22:17.722  3914  3961 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 13:22:17.722  3914  3961 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 13:22:17.723  3914  3961 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 13:22:17.723  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 13:22:17.723  3914  3961 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 13:22:17.723  3914  3961 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 13:22:17.723  3914  3961 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 13:22:17.723  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 13:22:17.723  3914  3961 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 13:22:17.723  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:17.723  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:17.724  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:17.724  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:17.724  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.724  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.724  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:17.724  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.724  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.724  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:17.724  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.724  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.724  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.725  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.725  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:17.725  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:17.726  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:17.726  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.726  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:17.726  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.726  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:17.726  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:17.727  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:17.727  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:17.727  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:17.727  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:17.727  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:18.387  2182  2771 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 13:22:19.199  3717  3983 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 13:22:19.255  3717  3986 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 13:22:19.269  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:22:19.271  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:22:19.306  1520  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:22:19.307  1520  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:22:19.307  1520  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:22:19.307  1520  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:22:19.353  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,09-13 13:22:19.355  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:22:19.391  1520  3094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:22:19.391  1520  3094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 13:22:19.391  1520  3094 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:22:19.391  1520  3094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:22:19.415  3717  3986 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 13:22:19.417  3717  3983 E BooksSync: Soft error
09-13 13:22:19.417  3717  3983 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:22:19.417  3717  3983 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 13:22:19.418  3717  3983 E BooksSync: Sync error
09-13 13:22:19.418  3717  3983 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:22:19.418  3717  3983 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 13:22:19.418  3717  3983 I BooksSync: Finished books sync
,09-13 13:22:19.426   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 130028, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
09-13 13:22:19.428  1520  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 13:22:19.428  1520  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:22:19.429  1520  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:22:19.429  1520  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:22:19.454  3643  3985 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:22:19.454  3643  3985 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:22:19.454  3643  3985 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	... 12 more
09-13 13:22:19.454  3643  3985 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at fal.a(PG:38)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:22:19.454  3643  3985 E HttpOperation: 	... 14 more
,09-13 13:22:19.506  1520  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:22:19.506  1520  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:22:19.507  1520  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:22:19.507  1520  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:22:19.531  3643  3985 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 13:22:19.531  3643  3985 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at hec.a(PG:42)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at hee.a(PG:102)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at czr.a(PG:65)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at kka.a(PG:108)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:22:19.531  3643  3985 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	... 15 more
09-13 13:22:19.531  3643  3985 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at fal.a(PG:38)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:22:19.531  3643  3985 E HttpOperation: 	... 17 more
09-13 13:22:19.531  3643  3985 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:22:19.531  3643  3985 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	... 15 more
09-13 13:22:19.531  3643  3985 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:22:19.531  3643  3985 E ExperimentLoader: 	... 17 more
,09-13 13:22:19.647   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 132763, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:22:22.728  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.728  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:22.729  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:22.729  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.729  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.730  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
,09-13 13:22:22.730  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:22.730  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:22.731  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:22.731  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:22:22.732  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.732  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:22.732  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:22.733  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.733  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:22.733  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:22.733  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:22.734  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.734  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.734  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:22.738  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:22.739  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:22.739  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.739  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
,09-13 13:22:22.744  3914  3961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-13 13:22:22.745  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:22:22.748  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-13 13:22:22.750  3914  3961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 13:22:22.750  3914  3961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 13:22:22.751  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 13:22:22.751  3914  3914 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 13:22:22.752  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-13 13:22:22.753  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:22:22.753  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-13 13:22:22.753  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-13 13:22:22.754  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-13 13:22:22.754  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.754  3914  3961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-13 13:22:22.755  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:22.755  3914  3914 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 13:22:22.755  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:22.755  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 13:22:22.755  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 13:22:22.756  3914  3988 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:22:22.756  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-13 13:22:22.756  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.756  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:22.760  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:22:22.761  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:22:22.761  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
,09-13 13:22:22.762  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:22.762  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:22:22.762  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:22.762  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:22:22.763  3914  3988 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 13:22:22.763  3914  3988 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 13:22:22.764  3914  3988 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 13:22:22.764  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:22.765  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:22.765  3914  3914 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 13:22:22.765  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.766  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.766  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:22.767  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.767  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:22.768  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:22.768  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.768  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.768  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.768  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.770  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:22.770  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:22.770  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.770  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:22.772  3914  3961 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 13:22:22.772  3914  3961 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 13:22:22.772  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 1,3:22:22.772  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:22:22.772  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 13:22:22.772  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:22.773  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:22.773  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:22.773  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:22.773  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.773  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.773  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:22.773  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.773  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:22.773  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:22.773  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.773  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.774  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.774  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.776  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:22.776  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:22.776  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.777  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:22.784  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:22.785  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:22.785  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:22.785  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:22.786  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.786  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.786  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:22.786  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.786  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:22.786  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:22.786  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.787  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.787  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.787  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.788  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:22.788  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:22.789  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.789  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:22.790  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:22:22.790  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:22:22.790  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:22:22.790  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:22:22.790  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.790  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.791  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5646513 not in the list
09-13 13:22:22.791  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.791  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:22.791  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:22.791  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.791  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.791  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:22.791  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:22.792  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:22:22.792  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:22:22.792  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:22.792  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23d0350 not in the list
09-13 13:22:22.793  3914  3961 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 13:22:22.793  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 13:22:22.794  3914  3961 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 13:22:22.794  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 13:22:22.794  3914  3961 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 13:22:22.794  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 13:22:22.797  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 13:22:22.797  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 13:22:22.798  3914  3961 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 13:22:22.798  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 13:22:22.798  3914  3961 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 13:22:22.798  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 13:22:22.798  3914  3961 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 13:22:22.798  3914  3961 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 13:22:22.799  3914  3961 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 13:22:22.799  3914  3961 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 13:22:22.800  3914  3961 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 13:22:22.800  3914  3961 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 13:22:22.800  3914  3961 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 13:22:22.800  3914  3961 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 13:22:22.801  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:22:22.801  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@880b903 added. We now have 3 listener(s)
09-13 13:22:22.801  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:22:22.803  3914  3961 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 13:22:22.804   872   882 D WifiService: setWifiEnabled: true pid=3914, uid=10000
09-13 13:22:22.804   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:22:22.845  2672  2786 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-13 13:22:22.845  2672  2805 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
09-13 13:22:22.846  3914  3981 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 422)
,09-13 13:22:23.263  3914  3914 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:22:23.298   872  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,09-13 13:22:27.810  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:22:27.811  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27fe080 added. We now have 4 listener(s)
09-13 13:22:27.811  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:22:27.827  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:27.828  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27fe080 removed from the list
09-13 13:22:27.828  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:22:27.828  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:22:27.832  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:27.836  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:22:27.836  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d9c6b9 added. We now have 4 listener(s)
09-13 13:22:27.836  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:22:27.840  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:27.840  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9d9c6b9 removed from the list
,09-13 13:22:27.840  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:27.841  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:27.841  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:22:27.843  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:22:27.843  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@85c2afe added. We now have 4 listener(s)
09-13 13:22:27.844  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:22:27.849   872  2098 D WifiService: setWifiEnabled: false pid=3914, uid=10000
09-13 13:22:27.849   872  2098 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:22:27.859  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:22:27.860  2672  2703 D BluetoothAdapterState: Current state: ON, message: 23
09-13 13:22:27.861  2672  2703 D BluetoothAdapterProperties: Setting state to 13
09-13 13:22:27.861  2672  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 13:22:27.862  2672  2703 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 13:22:27.863  2672  2703 I BluetoothAdapterState: Entering PendingCommandState
09-13 13:22:27.866  2672  2707 D BluetoothAdapterProperties: Scan Mode:20
,09-13 13:22:27.866  2672  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-13 13:22:27.867  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.867  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:22:27.867  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:27.867  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:27.867  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:27.867  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:27.867  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:22:27.867  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:22:27.867  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:22:27.868  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.868  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:22:27.868  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:22:27.871  2672  2672 D HeadsetService: Received stop request...Stopping profile...
09-13 13:22:27.873  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:27.880  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:27.884  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-13 13:22:27.885  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.886  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:27.886  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:27.886  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:27.886  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:27.886  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:27.886  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:22:27.886  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:22:27.886  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:22:27.886   872  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 13:22:27.886   872  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 13:22:27.886   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 13:22:27.887   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 13:22:27.888  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.888  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:22:27.892  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.892  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:27.892  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:27.892  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:27.892  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:27.892  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:27.892  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:22:27.892  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:22:27.892  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:22:27.893  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.893  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:22:27.894   872   885 I ActivityManager: Start proc 3992:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-13 13:22:27.895   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:27.896  1369  2062 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:27.896  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:27.897   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:27.898  1949  2154 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:27.898  2672  2672 D A2dpService: Received stop request...Stopping profile...
09-13 13:22:27.899  2672  2810 D A2dpStateMachine: Exit Disconnected: -1
,09-13 13:22:27.899   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:27.900   872  1312 E native  : do suspend true
09-13 13:22:27.901   872   872 D BluetoothA2dp: Proxy object disconnected
09-13 13:22:27.902  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:27.902  1369  1369 D HeadsetProfile: Bluetooth service disconnected
09-13 13:22:27.902  2672  2672 D BluetoothMapService: onReceive
09-13 13:22:27.903  2672  2672 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:22:27.903  2672  2672 D BluetoothMapService: STATE_TURNING_OFF
,09-13 13:22:27.903  2672  2672 V BluetoothAdapterState: isTurningOff()=true
09-13 13:22:27.903  2672  2672 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:27.903  2672  2672 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:27.903  2672  2672 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:27.903  1369  1369 D BluetoothA2dp: Proxy object disconnected
09-13 13:22:27.904  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:27.907  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:27.908  2672  2672 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 13:22:27.908  2672  2672 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-13 13:22:27.908  2672  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-13 13:22:27.908  2672  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:22:27.908  2672  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:22:27.909  2672  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:22:27.909  2672  2707 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 13:22:27.910  2672  2672 D HidService: Received stop request...Stopping profile...
09-13 13:22:27.910  2672  2672 D HidService: Stopping Bluetooth HidService
,09-13 13:22:27.912  2672  2672 V BluetoothAdapterState: isTurningOff()=true
,09-13 13:22:27.912  2672  2672 V BluetoothAdapterState: isTurningOn()=false
,09-13 13:22:27.912  2672  2672 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:27.912  2672  2672 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:27.912  1369  1369 D BluetoothInputDevice: Proxy object disconnected
09-13 13:22:27.912  1369  1369 D HidProfile: Bluetooth service disconnected
09-13 13:22:27.913  2672  2672 D HealthService: Received stop request...Stopping profile...
,09-13 13:22:27.914   872  1893 D DhcpClient: Clearing IP address
,09-13 13:22:27.914   370   871 D CommandListener: Clearing all IP addresses on wlan0
09-13 13:22:27.919  2672  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-13 13:22:27.919  2672  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:22:27.919  2672  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:22:27.919  2672  2786 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:22:27.919  2672  2786 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:22:27.919  2672  2786 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:22:27.919  2672  2786 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:22:27.920   370   871 D CommandListener: Setting iface cfg
09-13 13:22:27.920  2672  2672 D PanService: Received stop request...Stopping profile...
,09-13 13:22:27.922  2672  2672 D BluetoothMapService: Received stop request...Stopping profile...
09-13 13:22:27.922  2672  2672 D BluetoothMapService: stop()
09-13 13:22:27.922  2672  2672 D BluetoothMapAppObserver: deinitObservers()
,09-13 13:22:27.922  2672  2672 D BluetoothMapAppObserver: removeReceiver()
,09-13 13:22:27.923  1369  1369 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 13:22:27.923  1369  1369 D PanProfile: Bluetooth service disconnected
09-13 13:22:27.924  1369  1369 D BluetoothMap: Proxy object disconnected
09-13 13:22:27.924  1369  1369 D MapProfile: Bluetooth service disconnected
09-13 13:22:27.925  2672  2672 I BtOppRfcommListener: stopping Accept Thread
09-13 13:22:27.925   872  1312 D WifiStateMachine: Start Disconnecting Watchdog 1
09-13 13:22:27.925  2672  3501 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-13 13:22:27.925   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 13:22:27.925   872  1312 E native  : do suspend true
09-13 13:22:27.926  2672  3501 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-13 13:22:27.928   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-13 13:22:27.928   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-13 13:22:27.930  2672  2672 V BluetoothAdapterState: isTurningOff()=true
09-13 13:22:27.930  2672  2672 V BluetoothAdapterState: isTurningOn()=false
,09-13 13:22:27.930  2672  2672 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:27.930  2672  2672 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:27.930  2672  2672 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-13 13:22:27.930  2672  2707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 13:22:27.930  2672  2672 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-13 13:22:27.932   398   398 E Parcel  : Reading a NULL string not supported here.
09-13 13:22:27.932  2672  2672 V BluetoothAdapterState: isTurningOff()=true
09-13 13:22:27.932  2672  2672 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:27.932  2672  2672 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:27.932  2672  2672 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:27.933  2672  2672 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 13:22:27.933  2672  2707 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-13 13:22:27.933  2672  2672 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 13:22:27.934   872  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-13 13:22:27.935  2672  2672 V BluetoothAdapterState: isTurningOff()=true
09-13 13:22:27.935  2672  2672 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:27.935  2672  2672 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:27.935  2672  2672 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:27.935  2672  2672 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-13 13:22:27.935  2672  2672 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-13 13:22:27.936  2672  2672 D BluetoothMapService: MAP Service closeService in
09-13 13:22:27.937  2672  2672 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 13:22:27.937  2672  2672 D ObexServerSockets0: shutdown(block = true)
09-13 13:22:27.938  2672  2818 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-13 13:22:27.938  2672  2672 D ObexServerSockets0: shutdown called from another thread - interrupt().,
09-13 13:22:27.938  2672  2819 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-13 13:22:27.939  2672  2805 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 13:22:27.939  2672  2672 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 13:22:27.939  2672  2672 V BluetoothAdapterState: isTurningOff()=true
09-13 13:22:27.939  2672  2672 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:27.939  2672  2672 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:27.939  2672  2672 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:27.940  2672  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 13:22:27.940  2672  2703 D BluetoothAdapterProperties: Setting state to 15
09-13 13:22:27.940  2672  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-13 13:22:27.941  1949  2154 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:27.941  1369  1386 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 13:22:27.940  2672  2703 I BluetoothAdapterState: Entering BleOnState
09-13 13:22:27.941  2672  2672 D BluetoothMapService: cleanup()
09-13 13:22:27.941   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:27.942  2672  2672 D BluetoothMapService: MAP Service closeService in
09-13 13:22:27.942  1369  1381 D BluetoothMap: onBluetoothStateChange: up=false
09-13 13:22:27.942  1369  2062 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:22:27.944  1520  2466 V NativeCrypto: Read error: ssl=0x9a732000: I/O error during system call, Connection timed out
09-13 13:22:27.947  1520  2466 V NativeCrypto: SSL shutdown failed: ssl=0x9a732000: I/O error during system call, Broken pipe
09-13 13:22:27.947  1369  1386 D BluetoothPan: onBluetoothStateChange on: false
09-13 13:22:27.948  1369  1381 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:27.948   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:22:27.948   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:27.948   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:27.948  1369  2062 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 13:22:27.949   872  1894 D DhcpClient: Receive thread stopped
09-13 13:22:27.949  2672  2703 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-13 13:22:27.949  2672  2703 D BluetoothAdapterProperties: Setting state to 16
09-13 13:22:27.949  2672  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 13:22:27.950  2672  2703 D BluetoothAdapterProperties: onBleDisable
09-13 13:22:27.952  2672  2704 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 13:22:27.952  2672  2703 I BluetoothAdapterState: Entering PendingCommandState
09-13 13:22:27.953  2672  2786 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 13:22:27.953  2672  2786 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:22:27.953  2672  2707 D BluetoothAdapterProperties: Scan Mode:20
09-13 13:22:27.954  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.955  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:27.955  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:27.955  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:27.955  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:27.955  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:27.955  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:27.955  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:27.955  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:27.955  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.955  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:27.957  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.957  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:27.957  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:27.957  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:27.957  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:27.957  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:27.957  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:27.957  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:27.957  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:27.957  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.957  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:27.959  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.959  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:2,2:27.959  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:27.959  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:27.959  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:27.959  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:27.959  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:27.959  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:27.959  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:27.959  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:27.959  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:27.960  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:27.961  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:27.962  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:27.975   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:22:27.982  3992  3992 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-13 13:22:27.991  3992  3992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 13:22:27.995  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:22:27.998   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:22:27.998   370   871 D CommandListener: Clearing all IP addresses on wlan0
09-13 13:22:27.998   872  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 13:22:27.998   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:22:28.008   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15ef48:true
,09-13 13:22:28.010   872  2098 I ActivityManager: Start proc 4008:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-13 13:22:28.012   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-13 13:22:28.016   872   889 D Tethering: MasterInitialState.processMessage what=3
09-13 13:22:28.018  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:28.019  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:28.019  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:28.031   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 13:22:28.034  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:28.034  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:28.034  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:28.034  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:28.034  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:28.034  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:28.034  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:28.034  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:28.034  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:22:28.034   872  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 13:22:28.035  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:28.035  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:28.036  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:28.036  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:28.036  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:28.036  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:28.036  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:28.036  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:28.036  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:28.036  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:28.036  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:28.036  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:28.037  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:22:28.038  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:28.038  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:28.038  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:28.038  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:28.038  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:28.038  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:28.038  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:28.038  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:28.038  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:28.038  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:28.038  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:22:28.042  2182  2334 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:22:28.053  4008  4008 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-13 13:22:28.055  3992  3992 D LocalBluetoothProfileManager: Adding local MAP profile
09-13 13:22:28.057  3992  3992 D BluetoothMap: Create BluetoothMap proxy object
,09-13 13:22:28.065  3992  3992 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-13 13:22:28.081  3992  3992 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:22:28.083   370   871 E Netd    : netlink response contains error (No such file or directory)
,09-13 13:22:28.088   872  2099 I ActivityManager: Killing 2472:com.google.android.talk/u0a61 (adj 15): empty #17
,09-13 13:22:28.154  2672  2707 I bt_hci  : shut_down
,09-13 13:22:28.155  2672  2711 D bt_hwcfg: hw_epilog_process
,09-13 13:22:28.156  2672  2711 I bt_vendor: low_power_mode_cb
,09-13 13:22:28.178  2672  2711 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-13 13:22:28.179  2672  2711 I bt_vendor: epilog_cb
,09-13 13:22:28.179  2672  2711 I bt_hci  : epilog_finished_callback
,09-13 13:22:28.186  2672  2707 I bt_hci_h4: hal_close
,09-13 13:22:28.187  2672  2707 I bt_userial_vendor: device fd = 51 close
,09-13 13:22:28.266  4008  4008 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:22:28.266  4008  4008 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:22:28.266  4008  4008 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:22:28.266  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:22:28.267  4008  4008 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:22:28.267  4008  4008 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.k.d(PG:583)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.e.b(PG:170)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:22:28.267  4008  4008 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:22:28.267  4008  4008 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.File.exists(File.java:361)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:22:28.267  4008  4008 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:22:28.267  4008  4008 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-13 13:22:28.285  3992  3992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 13:22:28.292  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:22:28.299  2672  2704 D bt_stack_manager: event_shut_down_stack finished.
,09-13 13:22:28.299  2672  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 13:22:28.304  3992  3992 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:22:28.322   872  2097 I ActivityManager: Start proc 4043:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,09-13 13:22:28.327  2672  2703 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-13 13:22:28.328  2672  2672 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 13:22:28.328  2672  2672 D BtGatt.GattService: Received stop request...Stopping profile...
09-13 13:22:28.328  2672  2672 D BtGatt.GattService: stop()
09-13 13:22:28.328  2672  2672 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 13:22:28.333   872  2097 I ActivityManager: Killing 3327:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,09-13 13:22:28.387  2672  2672 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:22:28.387  2672  2672 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:28.387  2672  2672 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:28.387  2672  2672 V BluetoothAdapterState: isBleTurningOff()=true
,09-13 13:22:28.387  2672  2703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-13 13:22:28.387  2672  2703 D BluetoothAdapterProperties: Setting state to 10
09-13 13:22:28.387  2672  2703 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-13 13:22:28.388  2672  2703 I BluetoothAdapterState: Entering OffState
,09-13 13:22:28.389   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-13 13:22:28.409  2672  2672 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 13:22:28.409  2672  2672 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-13 13:22:28.412  2672  2672 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 13:22:28.412  2672  2704 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-13 13:22:28.416  2672  2704 D bt_stack_manager: event_clean_up_stack finished.
,09-13 13:22:28.430  4043  4043 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-13 13:22:28.431  2672  2672 I art     : System.exit called, status: 0
,09-13 13:22:28.431  2672  2672 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 13:22:28.530   872  1388 I ActivityManager: Process com.android.bluetooth (pid 2672) has died
,09-13 13:22:28.724  4043  4061 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-13 13:22:28.724  4043  4061 I Babel_SMS: MmsConfig.loadMmsSettings
,09-13 13:22:28.726  4043  4061 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-13 13:22:28.726  4043  4061 I Babel_SMS: MmsConfig.loadFromDatabase,
,09-13 13:22:28.768  4043  4061 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-13 13:22:28.768  4043  4061 I Babel_SMS: MmsConfig.loadFromResources
,09-13 13:22:28.769  4043  4061 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-13 13:22:28.770  4043  4061 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-13 13:22:28.804  4043  4043 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:22:28.807  4043  4043 I Babel_Crash: startup - clean
,09-13 13:22:28.846  4043  4043 I Babel_telephony: TeleModule.launchCompleted
,09-13 13:22:28.858   872  1388 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-13 13:22:28.872  4043  4043 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-13 13:22:28.880  4043  4043 W Babel   : BAM#gBA: invalid account id: -1
,09-13 13:22:28.880  4043  4043 W Babel   : BAM#gBA: invalid account id: -1
,09-13 13:22:28.880  4043  4043 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-13 13:22:28.889  4043  4066 I Babel   : deleted: false for 0
,09-13 13:22:28.900   872   883 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-13 13:22:28.917  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 13:22:28.922  1743  1743 D SystemUpdateService: onCreate
,09-13 13:22:28.926  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 13:22:28.948  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 13:22:28.969  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 13:22:28.971  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 13:22:28.989  1743  4068 I SystemUpdateService: active receiver: enabled
09-13 13:22:28.993   872   882 I ActivityManager: Start proc 4070:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-13 13:22:29.012  4043  4043 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 13:22:29.016  1743  2433 I iu.UploadsManager: num queued entries: 0
09-13 13:22:29.016  1743  2433 I iu.UploadsManager: num updated entries: 0
,09-13 13:22:29.017  1743  2433 I iu.SyncManager: NEXT; no task
,09-13 13:22:29.026  1743  4068 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 13:22:29.064  1743  4068 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-13 13:22:29.064  1743  4068 I SystemUpdateService: now status is 0 (complete)
,09-13 13:22:29.064  1743  4068 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 13:22:29.064  1743  4068 I SystemUpdateService: file has been verified
09-13 13:22:29.064  1743  4068 I SystemUpdateService: OTA package size = 12249756
,09-13 13:22:29.101  4070  4070 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-13 13:22:29.119  1743  4068 I SystemUpdateService: showing system update notification
,09-13 13:22:29.132  4070  4070 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:22:29.134  4043  4043 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-13 13:22:29.141  1743  1743 D SystemUpdateService: onDestroy
,09-13 13:22:29.151  4070  4070 D SprintDMHelper: simOperator: 
,09-13 13:22:29.151  4070  4070 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 13:22:29.158  4043  4043 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 13:22:29.159  4043  4043 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 13:22:29.166   872  1388 I ActivityManager: Start proc 4084:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-13 13:22:29.170  4043  4043 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 13:22:29.184  4043  4043 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-13 13:22:29.199   872  1913 I ActivityManager: Killing 3665:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-13 13:22:29.256  4043  4043 I vclib   : onServiceConnected
,09-13 13:22:29.342  4008  4038 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-13 13:22:29.356   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@903ddb5:true
,09-13 13:22:29.365   872  2100 I ActivityManager: Start proc 4099:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-13 13:22:29.372  4043  4098 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-13 13:22:29.375   872  1988 I ActivityManager: Killing 3549:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-13 13:22:29.457  4099  4099 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-13 13:22:29.523  4099  4099 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-13 13:22:29.523  4099  4099 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 13:22:29.523  4099  4099 I GAv4    :   adb logcat -s GAv4
,09-13 13:22:29.545  4099  4099 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 13:22:29.553  4099  4099 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 13:22:29.590  4099  4116 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 13:22:29.698  4099  4099 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-13 13:22:29.743  4099  4099 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-13 13:22:29.754  4099  4099 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 8714-8720)
,09-13 13:22:29.755  4099  4099 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 13:22:29.765  4099  4099 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9d24464}
,09-13 13:22:29.766  4099  4099 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 13:22:29.766  4099  4099 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 13:22:29.776  4099  4099 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-13 13:22:29.777  4099  4099 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-13 13:22:29.797  4099  4099 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 13:22:29.810  4099  4099 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 13:22:29.810  4099  4099 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-13 13:22:29.810  4099  4099 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-13 13:22:29.810  4099  4099 I Adreno  : Build Date                       : 10/20/15
09-13 13:22:29.810  4099  4099 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-13 13:22:29.810  4099  4099 I Adreno  : Local Branch                     : M14
09-13 13:22:29.810  4099  4099 I Adreno  : Remote Branch                    : 
09-13 13:22:29.810  4099  4099 I Adreno  : Remote Branch                    : 
09-13 13:22:29.810  4099  4099 I Adreno  : Reconstruct Branch               : 
,09-13 13:22:29.871  4099  4099 I NSApplication: Starting up...
,09-13 13:22:29.883  4099  4145 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-13 13:22:29.912   872  1989 I ActivityManager: Start proc 4150:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-13 13:22:29.913   872  1989 I ActivityManager: Killing 3589:android.process.acore/u0a5 (adj 15): empty #17
,09-13 13:22:30.008  4150  4150 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-13 13:22:30.196   872  2100 I ActivityManager: Killing 3796:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-13 13:22:30.306   872  1912 I ActivityManager: Start proc 4164:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-13 13:22:30.396  4164  4164 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-13 13:22:30.454  4164  4164 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-13 13:22:30.516   872  1913 I ActivityManager: Killing 3812:com.android.musicfx/u0a18 (adj 15): empty #17
,09-13 13:22:32.871   872  1971 D WifiService: setWifiEnabled: true pid=3914, uid=10000
,09-13 13:22:32.872   872  1971 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:22:32.886   872  1312 D WifiConfigStore: Loading config and enabling all networks 
,09-13 13:22:32.892  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:32.893  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:32.893  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:32.893  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:32.893  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:32.893  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:32.893  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:32.893  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:32.893  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:32.893  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:32.893  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:22:32.898  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:22:32.898  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:32.898  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:32.898  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:32.898  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:32.898  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:32.898  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:32.898  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:32.898  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:32.898  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:32.898  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:32.902  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:32.902  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:32.902  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:32.902  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:32.902  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:32.902  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:32.902  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:32.902  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:32.902  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:32.903  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:32.907  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:22:32.926   872  1312 D WifiConfigStore: loaded 0 passpoint configs
,09-13 13:22:32.927   872  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-13 13:22:32.928   872  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-13 13:22:32.929   872  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-13 13:22:32.929   872  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-13 13:22:32.929   872  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 13:22:32.929   872  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 13:22:32.950   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 13:22:32.951   370   871 D CommandListener: Setting iface cfg
,09-13 13:22:32.951   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-13 13:22:32.951   872  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-13 13:22:32.952   872  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 13:22:32.965   872  1310 D WifiNative-HAL: p2pGetDeviceAddress
09-13 13:22:32.966   872  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 13:22:32.967   872  1312 E native  : do suspend true
,09-13 13:22:33.002   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:22:34.161   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 13:22:34.194   872  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=3.38 rxSuccessRate=6.00 delta 1000 -> 1000
,09-13 13:22:34.196   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-13 13:22:34.197   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:22:34.208   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 13:22:34.279   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 13:22:34.281  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 13:22:34.362  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:22:34.370  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:22:34.375  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:22:34.405  1520  3094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 13:22:34.406  1520  3094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 13:22:34.406  1520  3094 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:22:34.406  1520  3094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:22:34.434  3606  3606 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 13:22:34.435  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-13 13:22:34.435  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-13 13:22:34.445   872  1679 I ActivityManager: Killing 2266:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-13 13:22:34.879  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 13:22:35.024  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 13:22:35.025  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 13:22:35.033   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:22:35.049   872  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 13:22:35.050   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-13 13:22:35.050   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:22:35.073   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:22:35.090   370   871 D CommandListener: Setting iface cfg
,09-13 13:22:35.092   872  1312 D WifiStateMachine: Start Dhcp Watchdog 2
,09-13 13:22:35.097   872  4199 D DhcpClient: Receive thread started
,09-13 13:22:35.098   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 13:22:35.181   872  1312 E native  : do suspend false
,09-13 13:22:35.190   872  1893 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 13:22:35.209   872  4199 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172648, domain null
09-13 13:22:35.210   872  1893 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172648 seconds
,09-13 13:22:35.213   872  1893 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 13:22:35.240   872  4199 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 13:22:35.241   872  1893 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 13:22:35.246   370   871 D CommandListener: Setting iface cfg
,09-13 13:22:35.256   872  1893 D DhcpClient: Scheduling renewal in 86399s
,09-13 13:22:35.257   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 13:22:35.261   872  1312 E native  : do suspend true
,09-13 13:22:35.273   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 13:22:35.274   872  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 13:22:35.276   872  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 13:22:35.277   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
,09-13 13:22:35.278   872  1315 D ConnectivityService: Adding iface wlan0 to network 101
,09-13 13:22:35.323   872  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-13 13:22:35.324   872  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-13 13:22:35.325   872  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-13 13:22:35.326   872  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-13 13:22:35.327   872  1315 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
09-13 13:22:35.336   872  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-13 13:22:35.341   872  1315 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-13 13:22:35.342   872  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-13 13:22:35.342   872  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-13 13:22:35.342   872  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 13:22:35.342   872  1315 D ConnectivityService:    accepting network in place of null
09-13 13:22:35.342   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 13:22:35.343   872  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 13:22:35.360   872  4198 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174325, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:22:35.389   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:22:35.421   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:22:35.429   872  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-13 13:22:35.430   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-13 13:22:35.437   872  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-13 13:22:35.444   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-13 13:22:35.448   872  4197 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-13 13:22:35.454  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:22:35.454  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:35.454  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:35.454  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:35.454  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:35.454  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:35.454  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:22:35.454  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:22:35.454  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:22:35.454  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:35.454  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:22:35.458  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:22:35.458  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:35.458  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:35.458  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:35.458  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:35.458  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:35.458  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:22:35.458  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:22:35.458  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 13:22:35.458  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:35.458  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:22:35.461  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:35.461  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:35.461  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:35.461  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:35.461  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:22:35.461  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:35.461  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:22:35.461  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:22:35.461  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:22:35.461  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:35.461  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:22:35.472  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 13:22:35.479  1743  1743 D SystemUpdateService: onCreate
,09-13 13:22:35.489  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 13:22:35.507  1743  4209 I SystemUpdateService: active receiver: enabled
,09-13 13:22:35.516   872  4197 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 11:22:35 GMT], X-Android-Received-Millis=[1473765755514], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473765755493]}
,09-13 13:22:35.518   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 13:22:35.519   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-13 13:22:35.519   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-13 13:22:35.521   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 13:22:35.553  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:22:35.557  1743  4209 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 13:22:35.560  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 13:22:35.595  1743  2433 I iu.UploadsManager: num queued entries: 0
,09-13 13:22:35.595  1743  2433 I iu.UploadsManager: num updated entries: 0
,09-13 13:22:35.596  1743  2433 I iu.SyncManager: NEXT; no task
,09-13 13:22:35.606  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 13:22:35.607  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 13:22:35.611  4070  4070 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:22:35.631  1743  4213 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-13 13:22:35.631  1743  4213 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 13:22:35.633  1743  4213 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-13 13:22:35.645  4070  4070 D SprintDMHelper: simOperator: 
,09-13 13:22:35.645  4070  4070 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 13:22:35.652  1743  4209 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-13 13:22:35.653  1743  4209 I SystemUpdateService: now status is 0 (complete)
09-13 13:22:35.653  1743  4209 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-13 13:22:35.653  1743  4209 I SystemUpdateService: file has been verified
09-13 13:22:35.653  1743  4209 I SystemUpdateService: OTA package size = 12249756
,09-13 13:22:35.718  1743  4209 I SystemUpdateService: showing system update notification
,09-13 13:22:35.770  1520  4221 I VacuumService: Vacuum at: now=1473765755770 tag=VacuumService
,09-13 13:22:35.829  4043  4218 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 13:22:35.896  1743  1743 D SystemUpdateService: onDestroy
,09-13 13:22:35.996  1520  2299 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-13 13:22:35.996  1520  2299 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 13:22:35.996  1520  2299 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:22:35.996  1520  2299 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:22:36.025  1520  4222 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-13 13:22:36.031  1520  4222 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-13 13:22:36.042  1743  4213 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-13 13:22:36.063  1520  4222 W Uploader:  no longer exists, so no auth token.
,09-13 13:22:36.428   872  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-13 13:22:37.534  1520  4222 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-13 13:22:37.534  1520  4222 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-13 13:22:37.534  1520  4222 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:22:37.534  1520  4222 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:22:37.551  1520  4222 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 13:22:37.551  1520  4222 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-13 13:22:37.551  1520  4222 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-13 13:22:37.878   872  2097 D WifiService: setWifiEnabled: false pid=3914, uid=10000
09-13 13:22:37.878   872  2097 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:22:37.890  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-13 13:22:37.894   872  1312 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-13 13:22:37.895   872  1312 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-13 13:22:37.895   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 13:22:37.895   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:22:37.917   872  1312 E native  : do suspend true
,09-13 13:22:37.926   872  1893 D DhcpClient: Clearing IP address
09-13 13:22:37.926   370   871 D CommandListener: Clearing all IP addresses on wlan0
,09-13 13:22:37.929   370   871 D CommandListener: Setting iface cfg
,09-13 13:22:37.932   872  4199 D DhcpClient: Receive thread stopped
,09-13 13:22:37.936  1520  4220 V NativeCrypto: Read error: ssl=0x9b0d3c00: I/O error during system call, Connection timed out
09-13 13:22:37.941  1520  4220 V NativeCrypto: SSL shutdown failed: ssl=0x9b0d3c00: I/O error during system call, Broken pipe
09-13 13:22:37.942   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 13:22:37.942   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-13 13:22:37.949   872  1312 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-13 13:22:37.953   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-13 13:22:37.953   872  1312 E native  : do suspend true
09-13 13:22:37.953   398   398 E Parcel  : Reading a NULL string not supported here.
09-13 13:22:37.964   370   871 D CommandListener: Clearing all IP addresses on wlan0
09-13 13:22:37.966   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-13 13:22:37.968   872  1315 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-13 13:22:37.984  2182  2334 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-13 13:22:37.984  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:37.985  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:37.985  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:37.985  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:37.985  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:37.985  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:37.985  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:37.985  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:37.985  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:22:37.985   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
09-13 13:22:37.985  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:37.985  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:37.987  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:37.987  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:37.987  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:37.987  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:37.987  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:37.987  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:37.987  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:37.987  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:37.987  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:37.987  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:37.987  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:37.989  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:37.989  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:37.989  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:37.989  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:37.989  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:37.989  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:37.989  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:37.989  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:37.989  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:37.990  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-13 13:22:37.990   872  1312 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 13:22:37.990  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:22:38.001   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:22:38.020  1520  4222 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/172.217.20.234 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,09-13 13:22:38.042   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:22:38.042   872  1315 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-13 13:22:38.043   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:22:38.046   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-13 13:22:38.058  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:38.059  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:38.060  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:38.071  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 13:22:38.074  1743  1743 D SystemUpdateService: onCreate
,09-13 13:22:38.076  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 13:22:38.085  1743  4244 I SystemUpdateService: active receiver: enabled
,09-13 13:22:38.094  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-13 13:22:38.099  1743  2433 I iu.UploadsManager: num queued entries: 0
,09-13 13:22:38.099  1743  2433 I iu.UploadsManager: num updated entries: 0
,09-13 13:22:38.100  1743  2433 I iu.SyncManager: NEXT; no task
09-13 13:22:38.101  1743  4244 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 13:22:38.103  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 13:22:38.105  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-13 13:22:38.107  4070  4070 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:22:38.112  4070  4070 D SprintDMHelper: simOperator: 
,09-13 13:22:38.112  4070  4070 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 13:22:38.131   370   871 E Netd    : netlink response contains error (No such file or directory)
,09-13 13:22:38.134   872  1315 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-13 13:22:38.153  1743  4244 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-13 13:22:38.153  1743  4244 I SystemUpdateService: now status is 0 (complete)
09-13 13:22:38.153  1743  4244 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 13:22:38.153  1743  4244 I SystemUpdateService: file has been verified
,09-13 13:22:38.154  1743  4244 I SystemUpdateService: OTA package size = 12249756
,09-13 13:22:38.161  4043  4248 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-13 13:22:38.170  1743  4244 I SystemUpdateService: showing system update notification
,09-13 13:22:38.178  1743  1743 D SystemUpdateService: onDestroy
,09-13 13:22:42.933   872   889 I ActivityManager: Start proc 4253:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 13:22:43.063  4253  4253 D AdapterServiceConfig: Adding HeadsetService
,09-13 13:22:43.064  4253  4253 D AdapterServiceConfig: Adding A2dpService,
,09-13 13:22:43.064  4253  4253 D AdapterServiceConfig: Adding HidService
,09-13 13:22:43.064  4253  4253 D AdapterServiceConfig: Adding HealthService
,09-13 13:22:43.065  4253  4253 D AdapterServiceConfig: Adding PanService,
,09-13 13:22:43.065  4253  4253 D AdapterServiceConfig: Adding GattService
,09-13 13:22:43.065  4253  4253 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 13:22:43.080   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@291e58:true
,09-13 13:22:43.080  4253  4253 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 13:22:43.086  4253  4253 I bt_bluedroid: init
,09-13 13:22:43.087  4253  4265 I BluetoothAdapterState: Entering OffState
,09-13 13:22:43.090  4253  4266 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 13:22:43.090  4253  4266 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 13:22:43.090  4253  4266 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-13 13:22:43.090  4253  4266 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 13:22:43.091  4253  4253 I bt_bluedroid: get_profile_interface socket
,09-13 13:22:43.093  4253  4253 I bt_bluedroid: get_profile_interface sdp
,09-13 13:22:43.096  4253  4269 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 13:22:43.098  4253  4264 I bt_bluedroid: config_hci_snoop_log
,09-13 13:22:43.104  4253  4269 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 13:22:43.105   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 13:22:43.112  4253  4265 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 13:22:43.113  4253  4265 D BluetoothAdapterProperties: Setting state to 14
09-13 13:22:43.113  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 13:22:43.117  4253  4265 D BluetoothBondStateMachine: make
,09-13 13:22:43.123  4253  4270 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 13:22:43.126  4253  4265 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:22:43.127  4253  4253 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
09-13 13:22:43.130  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:43.131  4253  4253 D BtGatt.DebugUtils: handleDebugAction() action=null
09-13 13:22:43.132  4253  4253 D BtGatt.GattService: Received start request. Starting profile...
,09-13 13:22:43.132  4253  4253 D BtGatt.GattService: start()
09-13 13:22:43.132  4253  4253 I bt_bluedroid: get_profile_interface gatt
09-13 13:22:43.133  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
09-13 13:22:43.133  4253  4253 D BtGatt.AdvertiseManager: advertise manager created
,09-13 13:22:43.138  4253  4253 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:22:43.138  4253  4253 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:43.139  4253  4253 V BluetoothAdapterState: isBleTurningOn()=true
09-13 13:22:43.139  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:43.139  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 13:22:43.139  4253  4265 I bt_bluedroid: enable
,09-13 13:22:43.139  4253  4266 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-13 13:22:43.140  4253  4266 I bt_hci  : start_up
,09-13 13:22:43.146  4253  4266 I bt_vendor: alloc value 0xb3a57189
,09-13 13:22:43.147  4253  4266 I bt_vendor: init
,09-13 13:22:43.147  4253  4266 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 13:22:43.147  4253  4266 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 13:22:43.253  4253  4266 D bt_hci  : start_up starting async portion
,09-13 13:22:43.254  4253  4273 I bt_hci  : event_finish_startup
,09-13 13:22:43.254  4253  4273 I bt_hci_h4: hal_open
,09-13 13:22:43.254  4253  4273 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 13:22:43.264  4253  4273 I bt_userial_vendor: device fd = 51 open
,09-13 13:22:43.295  4253  4273 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 13:22:43.326  4253  4273 D bt_hwcfg: Chipset BCM4354A2
09-13 13:22:43.327  4253  4273 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 13:22:43.328  4253  4273 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 13:22:43.347   872  1315 D ConnectivityService: handlePromptUnvalidated 101
,09-13 13:22:43.985  4253  4273 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 13:22:43.986  4253  4273 D bt_hwcfg: Settlement delay -- 100 ms
,09-13 13:22:43.986  4253  4273 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 13:22:44.103  4253  4273 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 13:22:44.104  4253  4273 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 13:22:44.133  4253  4273 I bt_hwcfg: vendor lib fwcfg completed
,09-13 13:22:44.133  4253  4273 I bt_vendor: firmware callback
,09-13 13:22:44.134  4253  4273 I bt_hci  : firmware_config_callback
,09-13 13:22:44.145  4253  4275 I bt_btu  : btu_task pending for preload complete event
09-13 13:22:44.146  4253  4275 I bt_btu_task: Bluetooth chip preload is complete
,09-13 13:22:44.146  4253  4275 I bt_btu  : btu_task received preload complete event
,09-13 13:22:44.155  4253  4275 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 13:22:44.156  4253  4275 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-13 13:22:44.156  4253  4275 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-13 13:22:44.156  4253  4275 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-13 13:22:44.156  4253  4275 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-13 13:22:44.157  4253  4275 I         : BTE_InitTraceLevels -- TRC_A2D
,09-13 13:22:44.157  4253  4275 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-13 13:22:44.157  4253  4275 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 13:22:44.157  4253  4275 I         : BTE_InitTraceLevels -- TRC_GAP
,09-13 13:22:44.157  4253  4275 I         : BTE_InitTraceLevels -- TRC_PAN
09-13 13:22:44.158  4253  4275 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 13:22:44.158  4253  4275 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 13:22:44.158  4253  4275 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 13:22:44.158  4253  4275 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-13 13:22:44.159  4253  4275 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 13:22:44.294  4253  4275 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d4d9d
,09-13 13:22:44.295  4253  4275 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d4d9d 
,09-13 13:22:44.302  4253  4269 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 13:22:44.304  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 13:22:44.307  4253  4269 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 13:22:44.313  4253  4269 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 13:22:44.316  4253  4269 D BluetoothAdapterProperties: Scan Mode:20
,09-13 13:22:44.316  4253  4269 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 13:22:44.317  4253  4269 D bt_hci  : do_postload posting postload work item
,09-13 13:22:44.317  4253  4273 I bt_hci  : event_postload
09-13 13:22:44.317  4253  4273 I bt_vendor: sco_config_cb
,09-13 13:22:44.317  4253  4273 I bt_hci  : sco_config_callback postload finished.
,09-13 13:22:44.323  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:44.325  4253  4273 I bt_vendor: low_power_mode_cb
09-13 13:22:44.327  4253  4269 D bt_bte_conf: Device ID record 1 : primary,
09-13 13:22:44.327  4253  4269 D bt_bte_conf:   vendorId            = 000f
,09-13 13:22:44.327  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:44.327  4253  4269 D bt_bte_conf:   vendorIdSource      = 0001
09-13 13:22:44.328  4253  4269 D bt_bte_conf:   product             = 1200
09-13 13:22:44.328  4253  4269 D bt_bte_conf:   version             = 1436
09-13 13:22:44.328  4253  4269 D bt_bte_conf:   clientExecutableURL = 
,09-13 13:22:44.328  4253  4269 D bt_bte_conf:   serviceDescription  = 
09-13 13:22:44.328  4253  4269 D bt_bte_conf:   documentationURL    = 
09-13 13:22:44.329  4253  4269 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 13:22:44.329  4253  4266 D bt_stack_manager: event_start_up_stack finished
09-13 13:22:44.331  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:44.331  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 13:22:44.332  4253  4265 D BluetoothAdapterProperties: Setting state to 15
09-13 13:22:44.332  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-13 13:22:44.333  4253  4265 I BluetoothAdapterState: Entering BleOnState
,09-13 13:22:44.337  4253  4265 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 13:22:44.337  4253  4265 D BluetoothAdapterProperties: Setting state to 11
09-13 13:22:44.337  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-13 13:22:44.342  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:44.343  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:44.345  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:44.348  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
09-13 13:22:44.350  4253  4253 D HeadsetService: Received start request. Starting profile...
,09-13 13:22:44.353  4253  4253 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-13 13:22:44.353  4253  4253 D HeadsetStateMachine: make
,09-13 13:22:44.361  4253  4265 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:22:44.364  4253  4253 D HeadsetStateMachine: max_hf_connections = 1
,09-13 13:22:44.365  4253  4253 I bt_bluedroid: get_profile_interface handsfree
,09-13 13:22:44.365  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-13 13:22:44.365  4253  4269 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-13 13:22:44.371  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:44.372  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 13:22:44.372  4253  4253 D A2dpService: Received start request. Starting profile...
09-13 13:22:44.373  4253  4253 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-13 13:22:44.373  4253  4253 I bt_bluedroid: get_profile_interface avrcp
,09-13 13:22:44.379  4253  4253 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 13:22:44.379  4253  4253 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 13:22:44.379  4253  4253 D A2dpStateMachine: make
,09-13 13:22:44.381  4253  4253 I bt_bluedroid: get_profile_interface a2dp
,09-13 13:22:44.381  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 13:22:44.383  4253  4284 D A2dpStateMachine: Enter Disconnected: -2
,09-13 13:22:44.384  4253  4253 I BluetoothHidServiceJni: classInitNative: succeeds
,09-13 13:22:44.385  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:44.386  4253  4253 D HidService: Received start request. Starting profile...
,09-13 13:22:44.386  4253  4253 I bt_bluedroid: get_profile_interface hidhost
09-13 13:22:44.386  3992  3992 D BluetoothInputDevice: Proxy object connected
09-13 13:22:44.387  4253  4253 D HidService: setHidService(): set to: null
09-13 13:22:44.387  4253  4269 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b63e5
09-13 13:22:44.387  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-13 13:22:44.387  3992  3992 D HidProfile: Bluetooth service connected
09-13 13:22:44.387  4253  4253 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 13:22:44.388  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:44.389  4253  4253 D HealthService: Received start request. Starting profile...
,09-13 13:22:44.390  4253  4253 I bt_bluedroid: get_profile_interface health
,09-13 13:22:44.390  4253  4253 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 13:22:44.391  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:44.392  3992  3992 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 13:22:44.392  4253  4253 D PanService: Received start request. Starting profile...
,09-13 13:22:44.392  4253  4253 D BluetoothPanServiceJni: initializeNative(L110): pan
09-13 13:22:44.393  4253  4253 I bt_bluedroid: get_profile_interface pan
09-13 13:22:44.393  3992  3992 D PanProfile: Bluetooth service connected
,09-13 13:22:44.393  4253  4269 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-13 13:22:44.396  4253  4253 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:44.397  3992  3992 D BluetoothMap: Proxy object connected
09-13 13:22:44.398  4253  4253 D BluetoothMapService: Received start request. Starting profile...
09-13 13:22:44.398  4253  4253 D BluetoothMapService: start()
09-13 13:22:44.399  3992  3992 D MapProfile: Bluetooth service connected
,09-13 13:22:44.399  3992  3992 D BluetoothMap: getConnectedDevices()
,09-13 13:22:44.400  3992  3992 D BluetoothMap: Bluetooth is Not enabled
,09-13 13:22:44.403  4253  4253 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 13:22:44.405  4253  4253 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-13 13:22:44.405  4253  4253 D BluetoothMapAppObserver: createReceiver()
,09-13 13:22:44.407  4253  4253 D BluetoothMapAppObserver: initObservers()
09-13 13:22:44.407  4253  4253 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 13:22:44.417  4253  4253 V BluetoothAdapterState: isTurningOff()=false
09-13 13:22:44.417  4253  4253 V BluetoothAdapterState: isTurningOn()=true
09-13 13:22:44.417  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:44.417  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:22:44.420  4253  4282 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 13:22:44.420  4253  4253 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:22:44.420  4253  4253 V BluetoothAdapterState: isTurningOn()=true
09-13 13:22:44.420  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:44.420  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:22:44.420  4253  4253 V BluetoothAdapterState: isTurningOff()=false
09-13 13:22:44.420  4253  4253 V BluetoothAdapterState: isTurningOn()=true
09-13 13:22:44.420  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:44.421  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:22:44.421  4253  4253 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:22:44.421  4253  4253 V BluetoothAdapterState: isTurningOn()=true
,09-13 13:22:44.421  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:44.421  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:22:44.421  4253  4253 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:22:44.421  4253  4253 V BluetoothAdapterState: isTurningOn()=true
09-13 13:22:44.421  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:44.421  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:22:44.422  4253  4253 V BluetoothAdapterState: isTurningOff()=false
09-13 13:22:44.422  4253  4253 V BluetoothAdapterState: isTurningOn()=true
,09-13 13:22:44.422  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:44.422  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:22:44.422  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-13 13:22:44.422  4253  4265 D BluetoothAdapterProperties: ScanMode =  20
,09-13 13:22:44.423  4253  4265 D BluetoothAdapterProperties: State =  11
09-13 13:22:44.424  4253  4265 D BluetoothAdapterProperties: Setting state to 12,
09-13 13:22:44.424  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 13:22:44.425  3992  4002 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 13:22:44.426  4253  4265 I BluetoothAdapterState: Entering OnState
,09-13 13:22:44.426  3992  4003 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 13:22:44.426  4253  4269 D BluetoothAdapterProperties: Scan Mode:21
,09-13 13:22:44.427  4253  4269 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 13:22:44.429  1949  2102 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:22:44.431  1369  1386 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 13:22:44.433  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:44.433  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:44.433  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:44.433  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:44.433  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:22:44.433  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:44.433  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:44.433  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:22:44.435  4253  4253 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 13:22:44.436  4253  4253 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 13:22:44.436  3992  4002 D BluetoothPan: onBluetoothStateChange on: true
,09-13 13:22:44.437   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:22:44.437  4253  4253 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:22:44.438  3992  4003 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-13 13:22:44.438  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:22:44.439  1369  1381 D BluetoothMap: onBluetoothStateChange: up=true
09-13 13:22:44.440  4253  4253 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 13:22:44.442  1369  1369 D BluetoothMap: Proxy object connected
09-13 13:22:44.442  1369  1369 D MapProfile: Bluetooth service connected
,09-13 13:22:44.442  1369  1369 D BluetoothMap: getConnectedDevices()
09-13 13:22:44.444  4253  4253 D ObexServerSockets: Succeed to create listening sockets 
09-13 13:22:44.444  4253  4253 D ObexServerSockets0: startAccept()
09-13 13:22:44.444  4253  4253 D ObexServerSockets0: prepareForNewConnect()
09-13 13:22:44.444  1369  1386 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 13:22:44.447  4253  4253 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 13:22:44.447  4253  4253 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 13:22:44.447  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:44.447  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:44.447  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:44.447  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:44.447  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:22:44.447  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:44.447  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:44.447  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:44.448  1369  2062 D BluetoothPan: onBluetoothStateChange on: true
09-13 13:22:44.448  4253  4289 D ObexServerSockets0: Accepting socket connection...
09-13 13:22:44.449  1369  1369 D BluetoothA2dp: Proxy object connected
,09-13 13:22:44.451  1369  1381 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:22:44.452   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 13:22:44.453   872   872 D BluetoothA2dp: Proxy object connected
09-13 13:22:44.453  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:44.454   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:22:44.455   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:22:44.455  1369  1386 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 13:22:44.457  4253  4290 D ObexServerSockets0: Accepting socket connection...
09-13 13:22:44.457  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:44.457  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:44.457  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:44.457  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:44.457  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:22:44.457  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:44.457  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:44.457  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:44.457  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 13:22:44.457  1369  1369 D PanProfile: Bluetooth service connected
,09-13 13:22:44.459  1369  1369 D BluetoothInputDevice: Proxy object connected
09-13 13:22:44.459  1369  1369 D HidProfile: Bluetooth service connected
09-13 13:22:44.459  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:44.462  4253  4253 D BluetoothMapService: onReceive
,09-13 13:22:44.462   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-13 13:22:44.462  4253  4253 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:22:44.462  4253  4253 D BluetoothMapService: STATE_ON
09-13 13:22:44.463  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:44.465  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:44.466  3992  3992 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-13 13:22:44.467  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:44.473  3992  3992 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-13 13:22:44.479  3992  3992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 13:22:44.481  3992  3992 D BluetoothA2dp: Proxy object connected
,09-13 13:22:44.483  4253  4253 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 13:22:44.483  4253  4253 D ObexServerSockets0: prepareForNewConnect()
,09-13 13:22:44.487  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:22:44.489  3992  3992 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:22:44.497  1369  1369 D BluetoothPbap: Proxy object connected
,09-13 13:22:44.497  1369  1369 D PbapServerProfile: Bluetooth service connected
09-13 13:22:44.497  3992  3992 D BluetoothPbap: Proxy object connected
09-13 13:22:44.498  3992  3992 D PbapServerProfile: Bluetooth service connected
,09-13 13:22:44.510  4253  4296 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:22:44.528  4253  4300 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:22:44.529  4253  4300 I BtOppRfcommListener: Accept thread started.
,09-13 13:22:44.532   872   872 D BluetoothHeadset: Proxy object connected
,09-13 13:22:44.532  1369  1381 D BluetoothHeadset: Proxy object connected
09-13 13:22:44.532  1369  1369 D HeadsetProfile: Bluetooth service connected
09-13 13:22:44.532   872   872 D BluetoothHeadset: Proxy object connected
,09-13 13:22:44.533  1949  2154 D BluetoothHeadset: Proxy object connected
09-13 13:22:44.533   872   872 D BluetoothHeadset: Proxy object connected
,09-13 13:22:44.537   872   889 D BluetoothHeadset: Proxy object connected
,09-13 13:22:44.552  1369  2062 D BluetoothHeadset: Proxy object connected
,09-13 13:22:44.552  1369  1369 D HeadsetProfile: Bluetooth service connected
,09-13 13:22:44.554   872   889 D BluetoothHeadset: Proxy object connected
,09-13 13:22:44.554   872   889 D BluetoothHeadset: Proxy object connected
,09-13 13:22:44.576  3992  4002 D BluetoothHeadset: Proxy object connected
,09-13 13:22:44.579  3992  3992 D HeadsetProfile: Bluetooth service connected
,09-13 13:22:47.894  4253  4265 D BluetoothAdapterState: Current state: ON, message: 23
,09-13 13:22:47.894  4253  4265 D BluetoothAdapterProperties: Setting state to 13
,09-13 13:22:47.894  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-13 13:22:47.896  4253  4265 D BluetoothAdapterProperties: onBluetoothDisable()
,09-13 13:22:47.904  4253  4265 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:22:47.909  4253  4253 D BluetoothMapService: onReceive
,09-13 13:22:47.909  4253  4253 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:22:47.909  4253  4253 D BluetoothMapService: STATE_TURNING_OFF,
,09-13 13:22:47.912  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:47.913  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:47.913  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-13 13:22:47.913  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:47.913  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:47.913  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:47.913  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:47.913  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:47.913  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:47.913  4253  4253 D BluetoothMapService: MAP Service closeService in,
09-13 13:22:47.913  4253  4253 D BluetoothMapMasInstance0: MAP Service shutdown
09-13 13:22:47.913  4253  4253 D ObexServerSockets0: shutdown(block = true),
09-13 13:22:47.915  4253  4269 D BluetoothAdapterProperties: Scan Mode:20
,09-13 13:22:47.915  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-13 13:22:47.915  4253  4289 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-13 13:22:47.916  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:47.916  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:22:47.918  4253  4253 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 13:22:47.919  4253  4290 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-13 13:22:47.920  4253  4278 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-13 13:22:47.922  4253  4253 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-13 13:22:47.922  4253  4253 I BtOppRfcommListener: stopping Accept Thread
09-13 13:22:47.923  4253  4300 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-13 13:22:47.923  4253  4300 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-13 13:22:47.924  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:47.924  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:47.924  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:47.924  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:47.924  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:47.924  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:47.924  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:47.924  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:47.924  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:47.925  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:47.926  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:47.927  3992  3992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-13 13:22:47.928  4253  4253 D HeadsetService: Received stop request...Stopping profile...
09-13 13:22:47.928  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:47.928  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:47.928  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:47.928  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:47.928  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:47.928  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-13 13:22:47.928  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:47.928  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:47.928  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:47.929  3914  3914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-13 13:22:47.929  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:47.931  3914  3914 V io.jxcore.node.ConnectivityMonitor: upd,ateConnectivityInfo: No relevant state changes
09-13 13:22:47.932   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:47.933  1369  1381 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:47.933   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:47.933  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:47.933  4253  4253 D A2dpService: Received stop request...Stopping profile...
09-13 13:22:47.933  3992  4002 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:47.934  1949  2102 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:47.934  4253  4284 D A2dpStateMachine: Exit Disconnected: -1
09-13 13:22:47.934   872   872 D BluetoothHeadset: Proxy object disconnected
09-13 13:22:47.934  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:47.936   872   872 D BluetoothA2dp: Proxy object disconnected
09-13 13:22:47.936  4253  4253 D HidService: Received stop request...Stopping profile...
09-13 13:22:47.937  4253  4253 D HidService: Stopping Bluetooth HidService
09-13 13:22:47.938  4253  4253 D HealthService: Received stop request...Stopping profile...
09-13 13:22:47.939  4253  4253 D PanService: Received stop request...Stopping profile...
09-13 13:22:47.941  4253  4253 D BluetoothMapService: Received stop request...Stopping profile...
09-13 13:22:47.941  4253  4253 D BluetoothMapService: stop()
09-13 13:22:47.943  1369  1369 D HeadsetProfile: Bluetooth service disconnected
09-13 13:22:47.944  1369  1369 D BluetoothA2dp: Proxy object disconnected
09-13 13:22:47.944  1369  1369 D BluetoothInputDevice: Proxy object disconnected
09-13 13:22:47.944  4253  4253 D BluetoothMapAppObserver: deinitObservers()
09-13 13:22:47.944  1369  1369 D HidProfile: Bluetooth service disconnected
09-13 13:22:47.944  4253  4253 D BluetoothMapAppObserver: removeReceiver()
09-13 13:22:47.944  1369  1369 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 13:22:47.944  1369  1369 D PanProfile: Bluetooth service disconnected
09-13 13:22:47.945  1369  1369 D BluetoothMap: Proxy object disconnected
09-13 13:22:47.946  1369  1369 D MapProfile: Bluetooth service disconnected
09-13 13:22:47.947  4253  4253 V BluetoothAdapterState: isTurningOff()=true
09-13 13:22:47.947  4253  4253 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:47.947  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:47.947  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false,
09-13 13:22:47.948  3992  3992 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:22:47.950  3992  3992 D HeadsetProfile: Bluetooth service disconnected,
,09-13 13:22:47.954  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
09-13 13:22:47.954  4253  4253 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-13 13:22:47.954  4253  4253 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-13 13:22:47.954  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:22:47.954  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 13:22:47.955  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:22:47.955  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-13 13:22:47.955  4253  4269 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-13 13:22:47.955  3992  3992 D BluetoothA2dp: Proxy object disconnected
09-13 13:22:47.956  3992  3992 D BluetoothInputDevice: Proxy object disconnected
09-13 13:22:47.956  3992  3992 D HidProfile: Bluetooth service disconnected
09-13 13:22:47.956  3992  3992 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-13 13:22:47.956  3992  3992 D PanProfile: Bluetooth service disconnected
09-13 13:22:47.956  4253  4253 V BluetoothAdapterState: isTurningOff()=true
,09-13 13:22:47.956  4253  4253 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:47.956  3992  3992 D BluetoothMap: Proxy object disconnected
09-13 13:22:47.956  3992  3992 D MapProfile: Bluetooth service disconnected
,09-13 13:22:47.956  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:47.957  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:47.959  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 13:22:47.959  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-13 13:22:47.960  4253  4275 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-13 13:22:47.960  4253  4275 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:22:47.960  4253  4253 V BluetoothAdapterState: isTurningOff()=true
,09-13 13:22:47.960  4253  4253 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:47.960  4253  4275 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-13 13:22:47.960  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:47.960  4253  4275 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-13 13:22:47.960  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:47.960  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-13 13:22:47.960  4253  4253 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-13 13:22:47.960  4253  4253 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-13 13:22:47.961  4253  4253 V BluetoothAdapterState: isTurningOff()=true
09-13 13:22:47.961  4253  4253 V BluetoothAdapterState: isTurningOn()=false
,09-13 13:22:47.961  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:47.961  4253  4269 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-13 13:22:47.961  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:47.961  4253  4253 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-13 13:22:47.961  4253  4269 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-13 13:22:47.961  4253  4253 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-13 13:22:47.962  4253  4253 V BluetoothAdapterState: isTurningOff()=true
09-13 13:22:47.962  4253  4253 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:47.962  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:47.962  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:47.962  4253  4253 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-13 13:22:47.962  4253  4253 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-13 13:22:47.963  4253  4253 D BluetoothMapService: MAP Service closeService in
09-13 13:22:47.963  4253  4253 V BluetoothAdapterState: isTurningOff()=true
09-13 13:22:47.963  4253  4253 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:47.963  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:47.963  4253  4253 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:22:47.964  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-13 13:22:47.964  4253  4253 D BluetoothMapService: cleanup()
09-13 13:22:47.964  4253  4253 D BluetoothMapService: MAP Service closeService in
,09-13 13:22:47.964  4253  4265 D BluetoothAdapterProperties: Setting state to 15
,09-13 13:22:47.964  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-13 13:22:47.965  1369  1369 D BluetoothPbap: Proxy object disconnected
09-13 13:22:47.965  1369  1369 D PbapServerProfile: Bluetooth service disconnected
,09-13 13:22:47.966  3992  3992 D BluetoothPbap: Proxy object disconnected
,09-13 13:22:47.966  3992  3992 D PbapServerProfile: Bluetooth service disconnected
09-13 13:22:47.966  3992  4003 D BluetoothMap: onBluetoothStateChange: up=false
09-13 13:22:47.967  4253  4265 I BluetoothAdapterState: Entering BleOnState
09-13 13:22:47.968  3992  4002 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:47.968  3992  4003 D BluetoothPbap: onBluetoothStateChange: up=false
09-13 13:22:47.969  1949  2154 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:47.970  3992  4002 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:22:47.970  1369  1386 D BluetoothPbap: onBluetoothStateChange: up=false
,09-13 13:22:47.971  3992  4003 D BluetoothPan: onBluetoothStateChange on: false
09-13 13:22:47.973   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:47.973  3992  4002 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-13 13:22:47.974  1369  1381 D BluetoothMap: onBluetoothStateChange: up=false
09-13 13:22:47.974  1369  2062 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-13 13:22:47.975  1369  1386 D BluetoothPan: onBluetoothStateChange on: false
09-13 13:22:47.976  1369  1381 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:47.976   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-13 13:22:47.976   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:47.976   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-13 13:22:47.976  1369  2062 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-13 13:22:47.977  4253  4265 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-13 13:22:47.977  4253  4265 D BluetoothAdapterProperties: Setting state to 16
09-13 13:22:47.977  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-13 13:22:47.978  4253  4265 D BluetoothAdapterProperties: onBleDisable
09-13 13:22:47.978  4253  4265 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:22:47.980  4253  4266 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-13 13:22:47.981  4253  4269 D BluetoothAdapterProperties: Scan Mode:20
09-13 13:22:47.981  4253  4275 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-13 13:22:47.982  4253  4275 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-13 13:22:47.982  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:47.983  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:47.983  3992  3992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 13:22:47.986  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:47.987  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:47.988  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:47.989  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:47.990  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:22:47.998  3992  3992 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:22:48.184  4253  4269 I bt_hci  : shut_down
,09-13 13:22:48.184  4253  4273 D bt_hwcfg: hw_epilog_process
09-13 13:22:48.186  4253  4273 I bt_vendor: low_power_mode_cb
,09-13 13:22:48.213  4253  4273 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-13 13:22:48.214  4253  4273 I bt_vendor: epilog_cb
09-13 13:22:48.214  4253  4273 I bt_hci  : epilog_finished_callback
,09-13 13:22:48.219  4253  4269 I bt_hci_h4: hal_close
,09-13 13:22:48.220  4253  4269 I bt_userial_vendor: device fd = 51 close
,09-13 13:22:48.341  4253  4266 D bt_stack_manager: event_shut_down_stack finished.
,09-13 13:22:48.342  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-13 13:22:48.348  4253  4265 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-13 13:22:48.348  4253  4253 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 13:22:48.350  4253  4253 D BtGatt.GattService: Received stop request...Stopping profile...
,09-13 13:22:48.350  4253  4253 D BtGatt.GattService: stop()
09-13 13:22:48.352  4253  4253 D BtGatt.AdvertiseManager: advertise clients cleared
,09-13 13:22:48.358  4253  4253 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:22:48.358  4253  4253 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:48.358  4253  4253 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:48.359  4253  4253 V BluetoothAdapterState: isBleTurningOff()=true
,09-13 13:22:48.359  4253  4265 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-13 13:22:48.360  4253  4265 D BluetoothAdapterProperties: Setting state to 10
09-13 13:22:48.360  4253  4265 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-13 13:22:48.362  4253  4265 I BluetoothAdapterState: Entering OffState
09-13 13:22:48.364   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-13 13:22:48.377  4253  4253 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-13 13:22:48.378  4253  4253 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-13 13:22:48.378  4253  4253 I BluetoothServiceJni: cleanupNative: return from cleanup
09-13 13:22:48.379  4253  4266 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-13 13:22:48.381  4253  4266 D bt_stack_manager: event_clean_up_stack finished.
,09-13 13:22:48.384  4253  4253 I art     : System.exit called, status: 0
09-13 13:22:48.384  4253  4253 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-13 13:22:48.461   872  2098 I ActivityManager: Process com.android.bluetooth (pid 4253) has died
,09-13 13:22:52.891  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:22:52.891  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:52.897  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:22:52.897  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@85c2afe removed from the list
,09-13 13:22:52.898  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:22:52.898  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:52.898  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:52.902  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:22:52.903  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@44284ac added. We now have 4 listener(s)
09-13 13:22:52.903  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:22:52.906  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:22:52.906  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@44284ac removed from the list
09-13 13:22:52.906  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:22:52.907  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:22:52.908  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:22:52.912  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:22:52.912  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc71575 added. We now have 4 listener(s)
09-13 13:22:52.912  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:22:57.922  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:57.972   872   889 I ActivityManager: Start proc 4311:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-13 13:22:58.135  4311  4311 D AdapterServiceConfig: Adding HeadsetService
09-13 13:22:58.136  4311  4311 D AdapterServiceConfig: Adding A2dpService
09-13 13:22:58.137  4311  4311 D AdapterServiceConfig: Adding HidService
,09-13 13:22:58.137  4311  4311 D AdapterServiceConfig: Adding HealthService
09-13 13:22:58.138  4311  4311 D AdapterServiceConfig: Adding PanService
09-13 13:22:58.138  4311  4311 D AdapterServiceConfig: Adding GattService
09-13 13:22:58.139  4311  4311 D AdapterServiceConfig: Adding BluetoothMapService
,09-13 13:22:58.157   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d1daf5:true
,09-13 13:22:58.157  4311  4311 D BluetoothAdapterState: make() - Creating AdapterState
,09-13 13:22:58.162  4311  4311 I bt_bluedroid: init
,09-13 13:22:58.163  4311  4323 I BluetoothAdapterState: Entering OffState
,09-13 13:22:58.165  4311  4324 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-13 13:22:58.166  4311  4324 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-13 13:22:58.166  4311  4324 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-13 13:22:58.166  4311  4324 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-13 13:22:58.167  4311  4311 I bt_bluedroid: get_profile_interface socket
,09-13 13:22:58.168  4311  4311 I bt_bluedroid: get_profile_interface sdp
,09-13 13:22:58.171  4311  4327 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 13:22:58.172  4311  4327 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 13:22:58.173  4311  4322 I bt_bluedroid: config_hci_snoop_log
09-13 13:22:58.174   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-13 13:22:58.182  4311  4323 D BluetoothAdapterState: Current state: OFF, message: 0
,09-13 13:22:58.183  4311  4323 D BluetoothAdapterProperties: Setting state to 14
09-13 13:22:58.183  4311  4323 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-13 13:22:58.187  4311  4323 D BluetoothBondStateMachine: make
,09-13 13:22:58.191  4311  4328 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-13 13:22:58.197  4311  4323 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:22:58.198  4311  4311 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-13 13:22:58.201  4311  4311 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:58.202  4311  4311 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-13 13:22:58.203  4311  4311 D BtGatt.GattService: Received start request. Starting profile...
09-13 13:22:58.203  4311  4311 D BtGatt.GattService: start()
,09-13 13:22:58.203  4311  4311 I bt_bluedroid: get_profile_interface gatt
09-13 13:22:58.204  4311  4311 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:58.204  4311  4311 D BtGatt.AdvertiseManager: advertise manager created
,09-13 13:22:58.214  4311  4311 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:22:58.214  4311  4311 V BluetoothAdapterState: isTurningOn()=false
09-13 13:22:58.214  4311  4311 V BluetoothAdapterState: isBleTurningOn()=true
09-13 13:22:58.214  4311  4311 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:22:58.215  4311  4323 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-13 13:22:58.216  4311  4323 I bt_bluedroid: enable
,09-13 13:22:58.216  4311  4324 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-13 13:22:58.217  4311  4324 I bt_hci  : start_up
,09-13 13:22:58.232  4311  4324 I bt_vendor: alloc value 0xb3a57189
09-13 13:22:58.232  4311  4324 I bt_vendor: init
09-13 13:22:58.232  4311  4324 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-13 13:22:58.232  4311  4324 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-13 13:22:58.342  4311  4324 D bt_hci  : start_up starting async portion
,09-13 13:22:58.342  4311  4331 I bt_hci  : event_finish_startup
,09-13 13:22:58.343  4311  4331 I bt_hci_h4: hal_open,
09-13 13:22:58.343  4311  4331 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-13 13:22:58.354  4311  4331 I bt_userial_vendor: device fd = 51 open
,09-13 13:22:58.383  4311  4331 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 13:22:58.415  4311  4331 D bt_hwcfg: Chipset BCM4354A2
09-13 13:22:58.415  4311  4331 D bt_hwcfg: Target name = [BCM4354A2]
,09-13 13:22:58.416  4311  4331 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-13 13:22:59.248  4311  4331 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-13 13:22:59.250  4311  4331 D bt_hwcfg: Settlement delay -- 100 ms
09-13 13:22:59.250  4311  4331 I bt_hwcfg: Setting fw settlement delay to 100 
,09-13 13:22:59.368  4311  4331 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-13 13:22:59.370  4311  4331 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-13 13:22:59.398  4311  4331 I bt_hwcfg: vendor lib fwcfg completed
,09-13 13:22:59.399  4311  4331 I bt_vendor: firmware callback
,09-13 13:22:59.399  4311  4331 I bt_hci  : firmware_config_callback
,09-13 13:22:59.413  4311  4333 I bt_btu  : btu_task pending for preload complete event
09-13 13:22:59.413  4311  4333 I bt_btu_task: Bluetooth chip preload is complete
09-13 13:22:59.413  4311  4333 I bt_btu  : btu_task received preload complete event
,09-13 13:22:59.421  4311  4333 I         : BTE_InitTraceLevels -- TRC_HCI
09-13 13:22:59.422  4311  4333 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-13 13:22:59.422  4311  4333 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-13 13:22:59.422  4311  4333 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-13 13:22:59.422  4311  4333 I         : BTE_InitTraceLevels -- TRC_AVRC
09-13 13:22:59.422  4311  4333 I         : BTE_InitTraceLevels -- TRC_A2D
09-13 13:22:59.423  4311  4333 I         : BTE_InitTraceLevels -- TRC_BNEP
09-13 13:22:59.423  4311  4333 I         : BTE_InitTraceLevels -- TRC_BTM
,09-13 13:22:59.423  4311  4333 I         : BTE_InitTraceLevels -- TRC_GAP
09-13 13:22:59.423  4311  4333 I         : BTE_InitTraceLevels -- TRC_PAN
,09-13 13:22:59.423  4311  4333 I         : BTE_InitTraceLevels -- TRC_SDP
,09-13 13:22:59.423  4311  4333 I         : BTE_InitTraceLevels -- TRC_GATT
09-13 13:22:59.424  4311  4333 I         : BTE_InitTraceLevels -- TRC_SMP
09-13 13:22:59.424  4311  4333 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-13 13:22:59.424  4311  4333 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-13 13:22:59.575  4311  4333 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d4d9d
,09-13 13:22:59.575  4311  4333 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d4d9d 
,09-13 13:22:59.585  4311  4327 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-13 13:22:59.589  4311  4327 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-13 13:22:59.590  4311  4327 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-13 13:22:59.595  4311  4327 D BluetoothAdapterProperties: Name is: Nexus 6
,09-13 13:22:59.601  4311  4327 D BluetoothAdapterProperties: Scan Mode:20
,09-13 13:22:59.601  4311  4327 D BluetoothAdapterProperties: Discoverable Timeout:120
09-13 13:22:59.602  4311  4327 D bt_hci  : do_postload posting postload work item
09-13 13:22:59.602  4311  4331 I bt_hci  : event_postload
09-13 13:22:59.603  4311  4331 I bt_vendor: sco_config_cb
,09-13 13:22:59.603  4311  4331 I bt_hci  : sco_config_callback postload finished.
09-13 13:22:59.606  4311  4327 D bt_bte_conf: Device ID record 1 : primary
09-13 13:22:59.606  4311  4327 D bt_bte_conf:   vendorId            = 000f
,09-13 13:22:59.606  4311  4327 D bt_bte_conf:   vendorIdSource      = 0001
09-13 13:22:59.606  4311  4327 D bt_bte_conf:   product             = 1200
09-13 13:22:59.606  4311  4327 D bt_bte_conf:   version             = 1436
,09-13 13:22:59.606  4311  4327 D bt_bte_conf:   clientExecutableURL = 
09-13 13:22:59.606  4311  4327 D bt_bte_conf:   serviceDescription  = 
09-13 13:22:59.607  4311  4327 D bt_bte_conf:   documentationURL    = 
09-13 13:22:59.607  4311  4327 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-13 13:22:59.607  4311  4324 D bt_stack_manager: event_start_up_stack finished
09-13 13:22:59.607  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:59.607  4311  4323 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-13 13:22:59.608  4311  4323 D BluetoothAdapterProperties: Setting state to 15
09-13 13:22:59.608  4311  4323 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-13 13:22:59.613  4311  4323 I BluetoothAdapterState: Entering BleOnState
,09-13 13:22:59.614  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:59.615  4311  4323 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-13 13:22:59.615  4311  4323 D BluetoothAdapterProperties: Setting state to 11
09-13 13:22:59.615  4311  4323 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-13 13:22:59.618  4311  4331 I bt_vendor: low_power_mode_cb
,09-13 13:22:59.631  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:59.633  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:22:59.633  4311  4311 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:59.635  4311  4311 D HeadsetService: Received start request. Starting profile...
,09-13 13:22:59.639  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-13 13:22:59.641  4311  4311 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-13 13:22:59.641  4311  4323 I BluetoothAdapterState: Entering PendingCommandState
,09-13 13:22:59.642  4311  4311 D HeadsetStateMachine: make
,09-13 13:22:59.651  4311  4311 D HeadsetStateMachine: max_hf_connections = 1
,09-13 13:22:59.651  4311  4311 I bt_bluedroid: get_profile_interface handsfree
09-13 13:22:59.652  4311  4327 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-13 13:22:59.652  4311  4327 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-13 13:22:59.656  4311  4311 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:59.657  4311  4311 D A2dpService: Received start request. Starting profile...
,09-13 13:22:59.658  4311  4311 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-13 13:22:59.659  4311  4311 I bt_bluedroid: get_profile_interface avrcp
,09-13 13:22:59.665  4311  4311 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-13 13:22:59.666  4311  4311 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-13 13:22:59.666  4311  4311 D A2dpStateMachine: make
,09-13 13:22:59.667  4311  4311 I bt_bluedroid: get_profile_interface a2dp
,09-13 13:22:59.668  4311  4327 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-13 13:22:59.671  4311  4311 I BluetoothHidServiceJni: classInitNative: succeeds
09-13 13:22:59.671  4311  4343 D A2dpStateMachine: Enter Disconnected: -2
09-13 13:22:59.672  4311  4311 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
09-13 13:22:59.673  4311  4311 D HidService: Received start request. Starting profile...
09-13 13:22:59.673  4311  4311 I bt_bluedroid: get_profile_interface hidhost
09-13 13:22:59.673  4311  4327 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39b63e5
09-13 13:22:59.673  4311  4311 D HidService: setHidService(): set to: null
09-13 13:22:59.673  4311  4327 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-13 13:22:59.674  4311  4311 I BluetoothHealthServiceJni: classInitNative: succeeds
09-13 13:22:59.675  4311  4311 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:59.676  4311  4311 D HealthService: Received start request. Starting profile...
,09-13 13:22:59.678  4311  4311 I bt_bluedroid: get_profile_interface health
,09-13 13:22:59.679  4311  4311 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-13 13:22:59.680  4311  4311 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
,09-13 13:22:59.681  4311  4311 D PanService: Received start request. Starting profile...
,09-13 13:22:59.681  4311  4311 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-13 13:22:59.681  4311  4311 I bt_bluedroid: get_profile_interface pan
,09-13 13:22:59.682  4311  4327 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-13 13:22:59.685  4311  4311 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba,
09-13 13:22:59.686  4311  4311 D BluetoothMapService: Received start request. Starting profile...
09-13 13:22:59.686  4311  4311 D BluetoothMapService: start()
,09-13 13:22:59.691  4311  4311 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-13 13:22:59.692  4311  4311 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-13 13:22:59.692  4311  4311 D BluetoothMapAppObserver: createReceiver()
09-13 13:22:59.693  4311  4311 D BluetoothMapAppObserver: initObservers()
09-13 13:22:59.693  4311  4311 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-13 13:22:59.701  4311  4311 V BluetoothAdapterState: isTurningOff()=false
09-13 13:22:59.701  4311  4311 V BluetoothAdapterState: isTurningOn()=true
09-13 13:22:59.701  4311  4311 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:59.702  4311  4311 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:59.702  4311  4341 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isTurningOn()=true
09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isBleTurningOn()=false
,09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isTurningOff()=false
09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isTurningOn()=true
09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isTurningOff()=false
09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isTurningOn()=true
09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isBleTurningOff()=false
,09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isTurningOff()=false
09-13 13:22:59.707  4311  4311 V BluetoothAdapterState: isTurningOn()=true
09-13 13:22:59.708  4311  4311 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:59.708  4311  4311 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:59.708  4311  4311 V BluetoothAdapterState: isTurningOff()=false
,09-13 13:22:59.708  4311  4311 V BluetoothAdapterState: isTurningOn()=true
09-13 13:22:59.708  4311  4311 V BluetoothAdapterState: isBleTurningOn()=false
09-13 13:22:59.708  4311  4311 V BluetoothAdapterState: isBleTurningOff()=false
09-13 13:22:59.708  4311  4323 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-13 13:22:59.708  4311  4323 D BluetoothAdapterProperties: ScanMode =  20
09-13 13:22:59.708  4311  4323 D BluetoothAdapterProperties: State =  11
09-13 13:22:59.708  4311  4323 D BluetoothAdapterProperties: Setting state to 12
09-13 13:22:59.709  4311  4323 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-13 13:22:59.709  4311  4323 I BluetoothAdapterState: Entering OnState
09-13 13:22:59.709  3992  4003 D BluetoothMap: onBluetoothStateChange: up=true
09-13 13:22:59.710  4311  4327 D BluetoothAdapterProperties: Scan Mode:21
09-13 13:22:59.710  4311  4327 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-13 13:22:59.712  3992  4002 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:22:59.714  3992  4003 D BluetoothPbap: onBluetoothStateChange: up=true
09-13 13:22:59.716  3992  3992 D BluetoothMap: Proxy object connected
09-13 13:22:59.716  3992  3992 D MapProfile: Bluetooth service connected
,09-13 13:22:59.716  3992  3992 D BluetoothMap: getConnectedDevices()
,09-13 13:22:59.718  1949  1960 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:22:59.719  3992  4002 D BluetoothA2dp: onBluetoothStateChange: up=true
09-13 13:22:59.719  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:59.719  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:59.719  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:59.719  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:59.719  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:22:59.719  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:59.719  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:59.719  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:59.719  4311  4311 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 13:22:59.720  4311  4311 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-13 13:22:59.721  4311  4311 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:22:59.723  1369  1381 D BluetoothPbap: onBluetoothStateChange: up=true
,09-13 13:22:59.725  3992  4003 D BluetoothPan: onBluetoothStateChange on: true
,09-13 13:22:59.726  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:22:59.726  4311  4311 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:22:59.728   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-13 13:22:59.728  3992  4348 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 13:22:59.731  1369  2062 D BluetoothMap: onBluetoothStateChange: up=true
,09-13 13:22:59.732  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:22:59.732  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:22:59.732  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:22:59.732  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:22:59.732  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:22:59.732  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:22:59.732  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:22:59.732  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-13 13:22:59.732  4311  4311 D ObexServerSockets: Succeed to create listening sockets 
,09-13 13:22:59.732  4311  4311 D ObexServerSockets0: startAccept()
,09-13 13:22:59.732  4311  4311 D ObexServerSockets0: prepareForNewConnect()
,09-13 13:22:59.732  1369  1369 D BluetoothMap: Proxy object connected
09-13 13:22:59.732  1369  1369 D MapProfile: Bluetooth service connected
09-13 13:22:59.732  1369  1369 D BluetoothMap: getConnectedDevices()
09-13 13:22:59.733  1369  1381 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 13:22:59.733  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-13 13:22:59.736  1369  1386 D BluetoothPan: onBluetoothStateChange on: true
,09-13 13:22:59.737  1369  2062 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:22:59.737   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-13 13:22:59.737   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:22:59.737   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-13 13:22:59.738  1369  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-13 13:22:59.739   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-13 13:22:59.740  4311  4311 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-13 13:22:59.740  4311  4311 D BluetoothSdpJni: SDP Create record success - handle: 0
09-13 13:22:59.742  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:59.743  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:22:59.744  4311  4351 D ObexServerSockets0: Accepting socket connection...
09-13 13:22:59.745  4311  4350 D ObexServerSockets0: Accepting socket connection...
,09-13 13:22:59.747  1369  1369 D BluetoothA2dp: Proxy object connected
09-13 13:22:59.747   872   872 D BluetoothA2dp: Proxy object connected
,09-13 13:22:59.748  3992  3992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-13 13:22:59.751  1369  1369 D BluetoothPan: BluetoothPAN Proxy object connected
09-13 13:22:59.751  1369  1369 D PanProfile: Bluetooth service connected
09-13 13:22:59.751  3992  3992 D BluetoothA2dp: Proxy object connected
09-13 13:22:59.752  4311  4311 D BluetoothMapService: onReceive
,09-13 13:22:59.752  4311  4311 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-13 13:22:59.752  4311  4311 D BluetoothMapService: STATE_ON
,09-13 13:22:59.753  1369  1369 D BluetoothInputDevice: Proxy object connected
,09-13 13:22:59.753  1369  1369 D HidProfile: Bluetooth service connected
,09-13 13:22:59.757  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-13 13:22:59.757  3992  3992 D DockEventReceiver: finishStartingService: stopping service
,09-13 13:22:59.761  3992  3992 D BluetoothPan: BluetoothPAN Proxy object connected
,09-13 13:22:59.761  3992  3992 D PanProfile: Bluetooth service connected
09-13 13:22:59.761  3992  3992 D BluetoothInputDevice: Proxy object connected
09-13 13:22:59.761  3992  3992 D HidProfile: Bluetooth service connected
,09-13 13:22:59.764  4311  4353 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:22:59.764  3992  3992 D BluetoothPbap: Proxy object connected
09-13 13:22:59.765  3992  3992 D PbapServerProfile: Bluetooth service connected
,09-13 13:22:59.776  4311  4311 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-13 13:22:59.776  4311  4311 D ObexServerSockets0: prepareForNewConnect()
09-13 13:22:59.776  1369  1369 D BluetoothPbap: Proxy object connected
09-13 13:22:59.776  1369  1369 D PbapServerProfile: Bluetooth service connected
,09-13 13:22:59.784  4311  4359 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:22:59.785  4311  4359 I BtOppRfcommListener: Accept thread started.
,09-13 13:22:59.815   872   872 D BluetoothHeadset: Proxy object connected
,09-13 13:22:59.816  1369  2062 D BluetoothHeadset: Proxy object connected
09-13 13:22:59.816   872   872 D BluetoothHeadset: Proxy object connected
,09-13 13:22:59.816  1369  1369 D HeadsetProfile: Bluetooth service connected
09-13 13:22:59.816  3992  4002 D BluetoothHeadset: Proxy object connected
09-13 13:22:59.817  3992  3992 D HeadsetProfile: Bluetooth service connected
,09-13 13:22:59.818  1949  2102 D BluetoothHeadset: Proxy object connected
,09-13 13:22:59.818   872   872 D BluetoothHeadset: Proxy object connected
,09-13 13:22:59.818  1949  2154 D BluetoothHeadset: Proxy object connected,
,09-13 13:22:59.828   872   889 D BluetoothHeadset: Proxy object connected
,09-13 13:22:59.838  1369  1381 D BluetoothHeadset: Proxy object connected
,09-13 13:22:59.838  1369  1369 D HeadsetProfile: Bluetooth service connected
09-13 13:22:59.838   872   889 D BluetoothHeadset: Proxy object connected
09-13 13:22:59.838   872   889 D BluetoothHeadset: Proxy object connected
,09-13 13:23:00.564  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:23:00.578  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:23:00.582  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:23:00.625  1520  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-13 13:23:00.625  1520  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-13 13:23:00.625  1520  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:23:00.626  1520  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:23:00.682  3606  3606 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-13 13:23:00.683  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-13 13:23:00.684  3606  3606 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-13 13:23:02.942  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:23:02.942  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:02.942  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:02.942  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-13 13:23:02.942  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:02.942  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:23:02.942  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:23:02.942  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:23:02.949  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:23:02.950  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:23:02.951  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc71575 removed from the list
09-13 13:23:02.951  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:23:02.951  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:23:02.951  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:02.954  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:23:02.955  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cbf90a added. We now have 4 listener(s)
,09-13 13:23:02.955  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:23:02.959   872  1389 D WifiService: setWifiEnabled: false pid=3914, uid=10000
09-13 13:23:02.959   872  1389 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:23:07.973  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:23:07.975   872  2098 D WifiService: setWifiEnabled: true pid=3914, uid=10000
,09-13 13:23:07.975   872  2098 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-13 13:23:07.991   872  1312 D WifiConfigStore: Loading config and enabling all networks 
,09-13 13:23:08.012  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:23:08.012  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:08.012  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:08.012  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:23:08.012  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:08.012  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:23:08.012  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:23:08.012  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:23:08.014  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:23:08.019  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:23:08.019  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:08.019  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:08.019  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:23:08.019  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:08.019  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-13 13:23:08.019  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-13 13:23:08.019  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-13 13:23:08.021  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-13 13:23:08.027   872  1312 D WifiConfigStore: loaded 0 passpoint configs
,09-13 13:23:08.028   872  1312 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-13 13:23:08.028   872  1312 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-13 13:23:08.029   872  1312 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-13 13:23:08.029   872  1312 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-13 13:23:08.030   872  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-13 13:23:08.030   872  1312 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-13 13:23:08.045   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 13:23:08.046   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-13 13:23:08.049   370   871 D CommandListener: Setting iface cfg
,09-13 13:23:08.099   872  1310 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-13 13:23:08.099   872  1310 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-13 13:23:08.105   872  1312 E native  : do suspend true
,09-13 13:23:08.110   872  1310 D WifiNative-HAL: p2pGetDeviceAddress
,09-13 13:23:08.121   872  1310 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-13 13:23:08.132   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:23:09.325   872  1312 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-13 13:23:09.473   872  1312 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.31 rxSuccessRate=8.25 delta 1000 -> 994
,09-13 13:23:09.474   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-13 13:23:09.474   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:23:09.491   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-13 13:23:09.527   872  1312 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-13 13:23:09.528  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-13 13:23:09.966  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-13 13:23:10.018  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-13 13:23:10.018  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-13 13:23:10.026   872  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,09-13 13:23:10.042   872  1312 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 13:23:10.042   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-13 13:23:10.043   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-13 13:23:10.073   872  1312 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 13:23:10.099   370   871 D CommandListener: Setting iface cfg
,09-13 13:23:10.104   872  1312 D WifiStateMachine: Start Dhcp Watchdog 3
,09-13 13:23:10.121   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-13 13:23:10.146   872  4369 D DhcpClient: Receive thread started
,09-13 13:23:10.237   872  1312 E native  : do suspend false
,09-13 13:23:10.261   872  1893 D DhcpClient: Broadcasting DHCPDISCOVER
,09-13 13:23:10.319   872  4369 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-13 13:23:10.320   872  1893 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-13 13:23:10.327   872  1893 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-13 13:23:10.354   872  4369 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-13 13:23:10.356   872  1893 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-13 13:23:10.364   370   871 D CommandListener: Setting iface cfg
,09-13 13:23:10.376   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-13 13:23:10.376   872  1893 D DhcpClient: Scheduling renewal in 86399s
09-13 13:23:10.378   872  1312 E native  : do suspend true
,09-13 13:23:10.396   872  1312 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-13 13:23:10.399   872  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,09-13 13:23:10.401   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-13 13:23:10.403   872  1315 D ConnectivityService: Adding iface wlan0 to network 102
,09-13 13:23:10.405   872  1312 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-13 13:23:10.452   872  1315 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-13 13:23:10.452   872  1315 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-13 13:23:10.454   872  1315 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-13 13:23:10.455   872  1315 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-13 13:23:10.457   872  1315 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-13 13:23:10.470   872  1315 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-13 13:23:10.476   872  1315 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-13 13:23:10.476   872  1315 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-13 13:23:10.476   872  1315 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-13 13:23:10.477   872  1315 D ConnectivityService:    accepting network in place of null
09-13 13:23:10.477   872  1312 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-13 13:23:10.477   872  1312 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-13 13:23:10.478   872  1315 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-13 13:23:10.495   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=209461, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:23:10.539   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:23:10.573   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-13 13:23:10.582   872  1315 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-13 13:23:10.583   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:23:10.591   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-13 13:23:10.596   872  1315 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-13 13:23:10.598   872  4367 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-13 13:23:10.608  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:23:10.608  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:10.608  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:10.608  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:23:10.608  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:10.608  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:10.608  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:23:10.608  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:23:10.613  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:23:10.619  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:23:10.619  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:10.619  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:10.619  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:23:10.619  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:10.619  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:10.619  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:23:10.619  3914  3914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:23:10.622  3914  3914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:23:10.622  1743  1743 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-13 13:23:10.629  1743  1743 D SystemUpdateService: onCreate
,09-13 13:23:10.633  1743  1743 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-13 13:23:10.657  1743  4378 I SystemUpdateService: active receiver: enabled
,09-13 13:23:10.660  1743  1743 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-13 13:23:10.668  1743  2433 I iu.UploadsManager: num queued entries: 0
,09-13 13:23:10.668  1743  2433 I iu.UploadsManager: num updated entries: 0
09-13 13:23:10.668  1743  2433 I iu.SyncManager: NEXT; no task
,09-13 13:23:10.672  1743  1743 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-13 13:23:10.673  1743  1743 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-13 13:23:10.675  4070  4070 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-13 13:23:10.682  1743  4380 I MDM     : [186] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-13 13:23:10.682  1743  4380 W BaseAppContext: Using Auth Proxy for data requests.
,09-13 13:23:10.685  4070  4070 D SprintDMHelper: simOperator: 
,09-13 13:23:10.685  4070  4070 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-13 13:23:10.690  1743  4380 V GoogleAuthProtoRequest: [186] a.<init>: mAccountName set to: thalitester@gmail.com
09-13 13:23:10.692   872  4367 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 11:23:10 GMT], X-Android-Received-Millis=[1473765790691], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473765790645]}
,09-13 13:23:10.691  1743  4378 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-13 13:23:10.697   872  1315 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-13 13:23:10.697   872  1315 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-13 13:23:10.698   872  1315 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-13 13:23:10.699   872  1315 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-13 13:23:10.702  1743  4378 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-13 13:23:10.702  1743  4378 I SystemUpdateService: now status is 0 (complete)
09-13 13:23:10.702  1743  4378 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-13 13:23:10.702  1743  4378 I SystemUpdateService: file has been verified
09-13 13:23:10.702  1743  4378 I SystemUpdateService: OTA package size = 12249756
,09-13 13:23:10.713  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:23:10.716  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:23:10.767  1743  4378 I SystemUpdateService: showing system update notification
,09-13 13:23:10.811  1743  1743 D SystemUpdateService: onDestroy
,09-13 13:23:10.821  1520  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-13 13:23:10.822  1520  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-13 13:23:10.822  1520  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:23:10.822  1520  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:23:10.850  1743  4380 E MDM     : [186] SitrepService.a: Error sending sitrep.
,09-13 13:23:10.879  4043  4384 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-13 13:23:11.018  1878  1981 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-13 13:23:11.018  1878  1981 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-13 13:23:11.036  1520  1520 I ConfigService: onCreate
,09-13 13:23:11.581   872  1315 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-13 13:23:13.003  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-13 13:23:13.003  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:13.003  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:13.003  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:23:13.003  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:13.003  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:13.003  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:23:13.003  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:23:13.011  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:23:13.013  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:23:13.014  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cbf90a removed from the list
09-13 13:23:13.016  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:23:13.016  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:13.017  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:23:13.030  3914  4391 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-13 13:23:13.031  3914  4391 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 13:23:16.039  3914  4392 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-13 13:23:16.040  3914  4391 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 13:23:16.040  3914  4392 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 13:23:16.040  3914  4391 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-13 13:23:16.041  3914  4391 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:23:16.044  3914  4392 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:23:16.045  3914  4391 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 13:23:16.048  3914  4391 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 13:23:16.048  3914  4394 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 453, name: OutgoingSocketThread/Sender)
,09-13 13:23:16.050  3914  4392 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:23:16.052  3914  4395 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 455, name: OutgoingSocketThread/Receiver)
09-13 13:23:16.052  3914  4396 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: IncomingSocketThread/Sender)
09-13 13:23:16.053  3914  4395 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 455, thread name: OutgoingSocketThread/Receiver)
09-13 13:23:16.053  3914  4392 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 13:23:16.054  3914  4395 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 13:23:16.054  3914  4395 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 455, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 13:23:16.055  3914  4397 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: IncomingSocketThread/Receiver)
,09-13 13:23:16.057  3914  4397 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 456, thread name: IncomingSocketThread/Receiver)
,09-13 13:23:16.057  3914  4397 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 13:23:16.057  3914  4397 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 13:23:16.107  1520  1520 I ConfigService: onDestroy
,09-13 13:23:18.485   872  1315 D ConnectivityService: handlePromptUnvalidated 102
,09-13 13:23:19.038  3914  3961 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-13 13:23:19.040  3914  3961 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-13 13:23:19.046  3914  3961 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a165c86 Bundle[{}]
,09-13 13:23:19.047  3914  3961 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 13:23:19.047  3914  3961 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 13:23:19.048  3914  3961 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 13:23:19.048  3914  3961 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 13:23:19.049  3914  3961 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 13:23:19.049  3914  3961 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-13 13:23:19.054  3914  3961 I System.out: Running OutgoingSocketThread
,09-13 13:23:19.057  3914  4399 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 13:23:19.057  3914  4399 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 13:23:22.068  3914  4399 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-13 13:23:22.068  3914  4400 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 13:23:22.068  3914  4399 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 13:23:22.068  3914  4400 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 13:23:22.069  3914  4399 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:23:22.069  3914  4400 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:23:22.071  3914  4399 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 13:23:22.072  3914  4400 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 13:23:22.075  3914  4399 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-13 13:23:22.079  3914  4400 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-13 13:23:22.081  3914  4402 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 465, name: OutgoingSocketThread/Sender)
,09-13 13:23:22.082  3914  4403 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 466, name: IncomingSocketThread/Sender)
09-13 13:23:22.082  3914  4404 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 467, name: OutgoingSocketThread/Receiver)
,09-13 13:23:22.083  3914  4404 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 467, thread name: OutgoingSocketThread/Receiver)
09-13 13:23:22.083  3914  4404 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 13:23:22.083  3914  4404 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 467, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-13 13:23:22.085  3914  4405 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 468, name: IncomingSocketThread/Receiver)
09-13 13:23:22.086  3914  4405 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 468, thread name: IncomingSocketThread/Receiver)
,09-13 13:23:22.087  3914  4405 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 13:23:22.087  3914  4405 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 468, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-13 13:23:25.069  3914  3961 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 477)
,09-13 13:23:25.071  3914  3961 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-13 13:23:25.072  3914  3961 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 478)
,09-13 13:23:25.078  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-13 13:23:25.078  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b76457b added. We now have 3 listener(s)
09-13 13:23:25.080  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 13:23:25.080  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:23:25.080  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-13 13:23:25.080  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:23:25.080  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a93f98 added. We now have 4 listener(s)
09-13 13:23:25.081  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:23:25.081  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:23:25.085  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:23:25.090  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:23:25.090  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:25.090  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:25.090  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:23:25.090  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:25.090  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:25.090  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:23:25.090  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:23:25.093  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:25.093  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 13:23:25.094  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:23:25.094  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:23:25.094  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 13:23:25.094  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:23:25.094  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:25.094  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:23:25.095  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:23:25.095  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b76457b removed from the list
,09-13 13:23:25.095  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:25.095  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a93f98 removed from the list
09-13 13:23:25.098  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:23:25.100  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:23:25.100  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:23:25.100  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:25.101  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:25.101  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:25.102  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:23:25.102  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 13:23:25.102  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:25.102  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a93f98 not in the list
09-13 13:23:25.102  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:25.102  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:25.103  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:23:25.103  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:23:25.103  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-13 13:23:25.103  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a93f98 not in the list
09-13 13:23:25.103  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:23:25.104  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:23:25.104  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:25.104  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b76457b not in the list
09-13 13:23:25.105  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:23:25.105  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b89bd6 added. We now have 3 listener(s)
,09-13 13:23:25.107  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 13:23:25.107  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:23:25.107  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:23:25.107  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:23:25.107  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99be57 added. We now have 4 listener(s)
09-13 13:23:25.107  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:23:25.108  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:23:25.113  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:23:25.121  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:23:25.121  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:25.121  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:25.121  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:23:25.121  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:25.121  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:25.121  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:23:25.121  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:23:25.124  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:25.125  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:23:25.126  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:23:25.126  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:23:25.126  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:23:25.127  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:23:25.127  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-13 13:23:25.128  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:23:25.131  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:23:25.133  3914  3961 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 13:23:25.133  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 13:23:25.138  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 13:23:25.139  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 13:23:25.139  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 13:23:25.145  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 13:23:25.145  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 13:23:25.146  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 13:23:25.146  3914  3961 D BluetoothAdapter: STATE_ON
,09-13 13:23:25.150  4311  4322 D BtGatt.GattService: registerClient() - UUID=ce939f90-319d-4782-9ab8-94f9e8ea5c39
,09-13 13:23:25.151  4311  4327 D BtGatt.GattService: onClientRegistered() - UUID=ce939f90-319d-4782-9ab8-94f9e8ea5c39, clientIf=5
,09-13 13:23:25.153  3914  3974 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-13 13:23:25.156  4311  4321 D BtGatt.GattService: start scan with filters
,09-13 13:23:25.167  4311  4330 D BtGatt.ScanManager: handling starting scan
,09-13 13:23:25.168  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 13:23:25.168  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 13:23:25.168  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-13 13:23:25.168  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-13 13:23:25.171  4311  4330 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3a60eba
09-13 13:23:25.171  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 13:23:25.172  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 13:23:25.172  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 13:23:25.175  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:23:25.182  3914  3961 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-13 13:23:25.182  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:23:25.182  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 13:23:25.182  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:25.182  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 13:23:25.182  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:23:25.183  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 13:23:25.183  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:23:25.183  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 13:23:25.183  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:23:25.184  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-13 13:23:25.184  4311  4327 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-13 13:23:25.184  3914  3961 D BluetoothAdapter: STATE_ON
09-13 13:23:25.184  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:23:25.186  4311  4330 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-13 13:23:25.186  4311  4322 D BtGatt.GattService: stopScan() - queue size =1
09-13 13:23:25.188  4311  4321 D BtGatt.GattService: unregisterClient() - clientIf=5
09-13 13:23:25.189  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:23:25.189  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-13 13:23:25.189  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 13:23:25.190  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 13:23:25.190  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-13 13:23:25.193  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:23:25.194  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-13 13:23:25.194  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 13:23:25.194  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:23:25.196  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:23:25.199  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:23:25.199  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:23:25.199  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:23:25.203  4311  4327 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 13:23:25.203  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:23:25.204  4311  4330 D BtGatt.ScanManager: Starting BLE batch scan
09-13 13:23:25.204  4311  4330 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 13:23:25.223  4311  4327 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 13:23:25.223  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:23:25.232  4311  4327 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-13 13:23:25.232  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:23:25.248  4311  4327 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 13:23:25.249  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:23:25.249  4311  4330 D BtGatt.ScanManager: stopping BLe Batch
,09-13 13:23:25.269  4311  4327 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 13:23:25.269  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:23:25.270  4311  4330 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:23:25.291  4311  4327 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-13 13:23:25.291  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:23:25.701  3914  3914 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:23:25.701  3914  3914 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:23:25.702  3914  3914 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:23:28.200  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:23:28.200  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-13 13:23:28.201  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:23:28.202  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:23:28.203  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:28.204  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:23:28.204  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-13 13:23:28.205  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b89bd6 removed from the list
09-13 13:23:28.205  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:28.206  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99be57 removed from the list
,09-13 13:23:28.206  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:23:28.207  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:28.209  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:23:28.210  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:23:28.215  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:23:28.215  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:23:28.216  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:28.216  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99be57 not in the list
,09-13 13:23:28.216  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:28.217  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:23:28.220  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:23:28.220  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:23:28.220  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:28.220  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99be57 not in the list
09-13 13:23:28.220  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:23:28.220  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:28.220  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:28.220  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9b89bd6 not in the list
,09-13 13:23:28.221  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:23:28.221  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18c69b0 added. We now have 3 listener(s)
09-13 13:23:28.223  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 13:23:28.223  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 13:23:28.223  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:23:28.223  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-13 13:23:28.224  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1cd029 added. We now have 4 listener(s)
09-13 13:23:28.224  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 13:23:28.224  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 13:23:28.228  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:23:28.236  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:23:28.236  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:28.236  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:28.236  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:23:28.236  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:28.236  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:28.236  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:23:28.236  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:23:28.239  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:23:28.240  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:23:28.241  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 13:23:28.242  3914  3961 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 13:23:28.242  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:23:28.242  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-13 13:23:28.243  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 13:23:28.243  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 13:23:28.244  3914  3961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 13:23:28.244  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:23:28.248  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 13:23:28.249  3914  3961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 13:23:28.249  3914  3961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-13 13:23:28.249  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 13:23:28.250  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-13 13:23:28.250  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 13:23:28.250  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:23:28.251  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:23:28.251  3914  3914 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 13:23:28.258  3914  4406 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 13:23:28.260  3914  4406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-13 13:23:28.262  3914  3961 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-13 13:23:28.262  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 13:23:28.268  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 13:23:28.269  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 13:23:28.269  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 13:23:28.272  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-13 13:23:28.272  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 13:23:28.273  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,09-13 13:23:28.274  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 13:23:28.274  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-13 13:23:28.274  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-13 13:23:28.275  3914  3961 D BluetoothAdapter: STATE_ON
,09-13 13:23:28.277  4311  4322 D BtGatt.GattService: registerClient() - UUID=88094ddb-a45a-42b7-b5af-275d3c02fcec
,09-13 13:23:28.278  4311  4327 D BtGatt.GattService: onClientRegistered() - UUID=88094ddb-a45a-42b7-b5af-275d3c02fcec, clientIf=5
09-13 13:23:28.278  3914  3924 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-13 13:23:28.280  4311  4329 D BtGatt.AdvertiseManager: message : 0
,09-13 13:23:28.288  4311  4329 D BtGatt.AdvertiseManager: starting multi advertising
,09-13 13:23:28.308  4311  4327 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-13 13:23:28.329  4311  4327 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-13 13:23:28.331  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-13 13:23:28.332  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-13 13:23:28.337  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:23:28.340  3914  3914 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-13 13:23:28.341  3914  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-13 13:23:28.342  3914  3914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-13 13:23:28.342  3914  3914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-13 13:23:28.342  3914  3914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-13 13:23:28.343  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-13 13:23:28.346  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-13 13:23:28.353  3914  3914 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 13:23:28.354  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-13 13:23:28.855  3914  3914 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-13 13:23:28.856  3914  3914 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 13:23:28.856  3914  3914 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:23:31.348  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:23:31.348  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything,
09-13 13:23:31.349  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-13 13:23:31.349  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 13:23:31.349  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 13:23:31.350  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 13:23:31.350  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 13:23:31.350  3914  4406 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 13:23:31.351  3914  4406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 13:23:31.351  3914  3961 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 13:23:31.351  3914  4406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 13:23:31.351  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:23:31.351  3914  3914 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 13:23:31.352  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-13 13:23:31.352  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-13 13:23:31.352  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 13:23:31.352  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:23:31.355  3914  3961 D BluetoothAdapter: STATE_ON
09-13 13:23:31.355  3914  3961 D BluetoothLeScanner: could not find callback wrapper
09-13 13:23:31.355  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 13:23:31.356  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-13 13:23:31.358  4311  4329 D BtGatt.AdvertiseManager: message : 1
09-13 13:23:31.360  4311  4329 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-13 13:23:31.370  4311  4327 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-13 13:23:31.370  4311  4327 D BtGatt.GattService: Client app is not null!
,09-13 13:23:31.372  4311  4321 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 13:23:31.373  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 13:23:31.373  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-13 13:23:31.374  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-13 13:23:31.374  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-13 13:23:31.374  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-13 13:23:31.377  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 13:23:31.377  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-13 13:23:31.378  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:23:31.379  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:23:31.382  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:23:31.382  3914  3914 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 13:23:31.382  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:23:31.382  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 13:23:31.383  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:23:31.383  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:23:31.383  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18c69b0 removed from the list
09-13 13:23:31.383  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:31.383  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:23:31.384  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1cd029 removed from the list
09-13 13:23:31.384  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:23:31.384  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
,09-13 13:23:31.384  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:31.385  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:31.385  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:31.388  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-13 13:23:31.388  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:23:31.389  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:31.389  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1cd029 not in the list
,09-13 13:23:31.389  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:31.389  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:23:31.392  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:23:31.392  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:23:31.392  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:31.392  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1cd029 not in the list
,09-13 13:23:31.392  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:23:31.393  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:31.393  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:23:31.393  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18c69b0 not in the list
09-13 13:23:31.395  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:23:31.395  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edcb8ba added. We now have 3 listener(s)
,09-13 13:23:31.401  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-13 13:23:31.401  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 13:23:31.402  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:23:31.403  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:23:31.403  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1f836b added. We now have 4 listener(s)
09-13 13:23:31.403  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:23:31.405  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:23:31.408  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:23:31.413  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:23:31.413  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:31.413  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:31.413  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:23:31.413  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:31.413  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:31.413  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:23:31.413  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:23:31.415  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-13 13:23:31.416  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:23:31.416  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:23:31.416  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 13:23:31.416  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 13:23:31.416  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:23:31.416  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 13:23:31.419  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:23:31.424  3914  3961 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-13 13:23:31.424  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-13 13:23:31.425  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 13:23:31.428  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-13 13:23:31.429  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-13 13:23:31.429  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-13 13:23:31.432  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-13 13:23:31.432  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-13 13:23:31.432  3914  3961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-13 13:23:31.433  3914  3961 D BluetoothAdapter: STATE_ON
,09-13 13:23:31.435  4311  4322 D BtGatt.GattService: registerClient() - UUID=9eca3dbc-35d6-45e5-aaf9-e023c46d6b9a
,09-13 13:23:31.436  4311  4327 D BtGatt.GattService: onClientRegistered() - UUID=9eca3dbc-35d6-45e5-aaf9-e023c46d6b9a, clientIf=5
09-13 13:23:31.436  3914  3974 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-13 13:23:31.436  4311  4340 D BtGatt.GattService: start scan with filters
,09-13 13:23:31.439  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-13 13:23:31.439  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-13 13:23:31.439  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-13 13:23:31.440  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-13 13:23:31.440  4311  4330 D BtGatt.ScanManager: handling starting scan
,09-13 13:23:31.443  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-13 13:23:31.443  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-13 13:23:31.443  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-13 13:23:31.445  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-13 13:23:31.452  4311  4327 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-13 13:23:31.453  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:23:31.453  4311  4330 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-13 13:23:31.461  4311  4327 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-13 13:23:31.462  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:23:31.462  4311  4330 D BtGatt.ScanManager: Starting BLE batch scan
09-13 13:23:31.462  4311  4330 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-13 13:23:31.477  4311  4327 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-13 13:23:31.477  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:23:31.485  4311  4327 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-13 13:23:31.486  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:23:31.885  3914  3914 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:23:31.943  3914  3914 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-13 13:23:31.944  3914  3914 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:23:31.944  3914  3914 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-13 13:23:32.993  4311  4311 D BtGatt.ScanManager: awakened up at time 231959
,09-13 13:23:32.996  4311  4330 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-13 13:23:33.032  4311  4327 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-13 13:23:33.032  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:23:33.032  4311  4327 D BtGatt.GattService: current time is 231998503798
,09-13 13:23:33.033  4311  4327 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -92, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -95, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -105, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -84, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-13 13:23:33.034  4311  4327 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-13 13:23:33.035  4311  4327 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-13 13:23:33.036  4311  4327 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-13 13:23:33.036  4311  4327 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-13 13:23:33.036  4311  4327 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-13 13:23:33.036  4311  4327 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-13 13:23:34.456  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-13 13:23:34.457  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-13 13:23:34.457  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-13 13:23:34.458  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:23:34.458  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-13 13:23:34.458  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 13:23:34.458  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 13:23:34.459  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 13:23:34.459  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-13 13:23:34.459  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 13:23:34.460  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-13 13:23:34.462  3914  3961 D BluetoothAdapter: STATE_ON
09-13 13:23:34.464  4311  4339 D BtGatt.GattService: stopScan() - queue size =1
,09-13 13:23:34.466  4311  4322 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-13 13:23:34.468  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-13 13:23:34.468  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-13 13:23:34.469  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-13 13:23:34.469  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-13 13:23:34.469  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-13 13:23:34.472  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:23:34.472  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-13 13:23:34.472  3914  3961 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 13:23:34.472  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 13:23:34.475  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:23:34.477  4311  4311 D BtGatt.ScanManager: awakened up at time 233442
,09-13 13:23:34.483  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-13 13:23:34.484  3914  3914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 13:23:34.484  3914  3914 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 13:23:34.485  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-13 13:23:34.485  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:34.485  4311  4327 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-13 13:23:34.485  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:23:34.486  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:23:34.485  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-13 13:23:34.486  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edcb8ba removed from the list
09-13 13:23:34.486  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:34.486  4311  4330 D BtGatt.ScanManager: stopping BLe Batch
09-13 13:23:34.487  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1f836b removed from the list
09-13 13:23:34.487  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:23:34.487  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:34.488  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-13 13:23:34.489  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:34.490  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:23:34.491  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 13:23:34.491  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:34.491  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1f836b not in the list
09-13 13:23:34.491  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:34.491  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:34.492  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:23:34.492  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:23:34.492  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:34.492  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1f836b not in the list
,09-13 13:23:34.492  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:23:34.492  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:34.492  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:34.492  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@edcb8ba not in the list
09-13 13:23:34.493  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 13:23:34.493  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76dff74 added. We now have 3 listener(s)
09-13 13:23:34.495  4311  4327 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-13 13:23:34.495  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-13 13:23:34.495  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:23:34.495  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 13:23:34.495  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 13:23:34.495  4311  4330 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-13 13:23:34.496  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 13:23:34.496  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5634c9d added. We now have 4 listener(s)
09-13 13:23:34.496  3914  3961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 13:23:34.496  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-13 13:23:34.499  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 13:23:34.504  3914  3961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 13:23:34.504  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 13:23:34.504  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-13 13:23:34.504  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 13:23:34.504  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 13:23:34.504  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:34.504  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 13:23:34.504  3914  3961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-13 13:23:34.506  3914  3961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 13:23:34.506  3914  3961 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 13:23:34.507  3914  3961 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-13 13:23:34.508  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:23:34.508  3914  3961 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 13:23:34.508  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:23:34.508  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:34.508  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 13:23:34.508  3914  3961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 13:23:34.508  4311  4327 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-13 13:23:34.508  4311  4327 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-13 13:23:34.509  4311  4327 D BtGatt.GattService: current time is 233474762173
09-13 13:23:34.509  4311  4327 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -88, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-13 13:23:34.509  4311  4327 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-13 13:23:34.508  3914  3961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76dff74 removed from the list
09-13 13:23:34.509  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:34.510  3914  3961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5634c9d removed from the list
09-13 13:23:34.510  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:23:34.513  3914  3914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 13:23:34.513  3914  3961 D io.jxcore.node.ConnectivityMonitor: stop
09-13 13:23:34.513  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:34.514  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:34.514  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 13:23:34.515  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:23:34.515  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-13 13:23:34.515  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:34.515  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5634c9d not in the list
09-13 13:23:34.515  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:34.515  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:34.516  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-13 13:23:34.516  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-13 13:23:34.516  3914  3961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 13:23:34.517  3914  3961 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5634c9d not in the list
09-13 13:23:34.517  3914  3961 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 13:23:34.517  3914  3961 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 13:23:34.517  3914  3961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 13:23:34.517  3914  3961 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@76dff74 not in the list
09-13 13:23:34.518  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 13:23:34.518  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 13:23:34.518  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-13 13:23:34.518  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 13:23:34.518  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,09-13 13:23:34.519  3914  3961 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 13:23:34.985  3914  3914 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 13:23:36.534  3914  4408 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 487, name: My test thread name)
,09-13 13:23:38.531  3914  3961 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 487
,09-13 13:23:38.532  3914  3961 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 487, name: My test thread name)
,09-13 13:23:38.538  3914  4409 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 488, name: My test thread name)
,09-13 13:23:38.539  3914  4409 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 488, thread name: My test thread name)
09-13 13:23:38.539  3914  4409 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 488, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-13 13:23:38.543  3914  3961 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-13 13:23:38.552  3914  4410 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 492, name: My test thread name)
,09-13 13:23:38.553  3914  4410 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 492, thread name: My test thread name): Test exception.
09-13 13:23:38.553  3914  4410 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 492, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-13 13:23:38.560  3914  3961 I jxcore-log: Total number of executed tests:  82
09-13 13:23:38.560  3914  3961 I jxcore-log: 
,09-13 13:23:38.561  3914  3961 I jxcore-log: Number of passed tests:  82
09-13 13:23:38.561  3914  3961 I jxcore-log: 
09-13 13:23:38.562  3914  3961 I jxcore-log: Number of failed tests:  0
09-13 13:23:38.562  3914  3961 I jxcore-log: 
,09-13 13:23:38.563  3914  3961 I jxcore-log: Number of ignored tests:  0
09-13 13:23:38.563  3914  3961 I jxcore-log: 
09-13 13:23:38.563  3914  3961 I jxcore-log: Total duration:  101268
09-13 13:23:38.563  3914  3961 I jxcore-log: 
,09-13 13:23:38.572  3914  3961 I jxcore-log: Unit Test app is loaded
09-13 13:23:38.572  3914  3961 I jxcore-log: 
,09-13 13:23:38.581  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.581  3914  3961 I jxcore-log: 
,09-13 13:23:38.587  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.587  3914  3961 I jxcore-log: 
,09-13 13:23:38.589  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.589  3914  3961 I jxcore-log: 
,09-13 13:23:38.590  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.590  3914  3961 I jxcore-log: 
,09-13 13:23:38.592  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 13:23:38.592  3914  3961 I jxcore-log: 
,09-13 13:23:38.593  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:23:38.593  3914  3961 I jxcore-log: 
,09-13 13:23:38.594  3914  3914 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 13:23:38.597  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.597  3914  3961 I jxcore-log: 
,09-13 13:23:38.601  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.601  3914  3961 I jxcore-log: 
,09-13 13:23:38.602  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 13:23:38.602  3914  3961 I jxcore-log: 
,09-13 13:23:38.603  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:23:38.603  3914  3961 I jxcore-log: 
,09-13 13:23:38.604  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:23:38.604  3914  3961 I jxcore-log: 
09-13 13:23:38.605  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.605  3914  3961 I jxcore-log: 
,09-13 13:23:38.606  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.606  3914  3961 I jxcore-log: 
09-13 13:23:38.606  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.606  3914  3961 I jxcore-log: 
,09-13 13:23:38.607  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:23:38.607  3914  3961 I jxcore-log: 
,09-13 13:23:38.608  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:23:38.608  3914  3961 I jxcore-log: 
09-13 13:23:38.609  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:23:38.609  3914  3961 I jxcore-log: 
,09-13 13:23:38.610  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.610  3914  3961 I jxcore-log: 
09-13 13:23:38.611  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.611  3914  3961 I jxcore-log: 
,09-13 13:23:38.612  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.612  3914  3961 I jxcore-log: 
,09-13 13:23:38.613  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:23:38.613  3914  3961 I jxcore-log: 
09-13 13:23:38.614  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:23:38.614  3914  3961 I jxcore-log: 
,09-13 13:23:38.614  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-13 13:23:38.614  3914  3961 I jxcore-log: 
09-13 13:23:38.615  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.615  3914  3961 I jxcore-log: 
,09-13 13:23:38.615  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.615  3914  3961 I jxcore-log: 
09-13 13:23:38.616  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.616  3914  3961 I jxcore-log: 
,09-13 13:23:38.616  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.616  3914  3961 I jxcore-log: 
09-13 13:23:38.617  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.617  3914  3961 I jxcore-log: 
,09-13 13:23:38.617  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.617  3914  3961 I jxcore-log: 
09-13 13:23:38.618  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.618  3914  3961 I jxcore-log: 
,09-13 13:23:38.618  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.618  3914  3961 I jxcore-log: 
,09-13 13:23:38.619  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.619  3914  3961 I jxcore-log: 
,09-13 13:23:38.619  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.619  3914  3961 I jxcore-log: 
09-13 13:23:38.620  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.620  3914  3961 I jxcore-log: 
09-13 13:23:38.620  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.620  3914  3961 I jxcore-log: 
,09-13 13:23:38.621  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.621  3914  3961 I jxcore-log: 
09-13 13:23:38.621  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.621  3914  3961 I jxcore-log: 
09-13 13:23:38.622  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-13 13:23:38.622  3914  3961 I jxcore-log: 
,09-13 13:23:38.622  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 13:23:38.622  3914  3961 I jxcore-log: 
09-13 13:23:38.623  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-13 13:23:38.623  3914  3961 I jxcore-log: 
09-13 13:23:38.623  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.623  3914  3961 I jxcore-log: 
,09-13 13:23:38.624  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.624  3914  3961 I jxcore-log: 
09-13 13:23:38.625  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.625  3914  3961 I jxcore-log: 
09-13 13:23:38.625  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.625  3914  3961 I jxcore-log: 
,09-13 13:23:38.626  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.626  3914  3961 I jxcore-log: 
09-13 13:23:38.626  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:23:38.626  3914  3961 I jxcore-log: 
,09-13 13:23:38.627  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.627  3914  3961 I jxcore-log: 
,09-13 13:23:38.627  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-13 13:23:38.627  3914  3961 I jxcore-log: 
09-13 13:23:38.628  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.628  3914  3961 I jxcore-log: 
09-13 13:23:38.628  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:23:38.628  3914  3961 I jxcore-log: 
09-13 13:23:38.629  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-13 13:23:38.629  3914  3961 I jxcore-log: 
09-13 13:23:38.629  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 13:23:38.629  3914  3961 I jxcore-log: 
09-13 13:23:38.630  3914  3961 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 13:23:38.630  3914  3961 I jxcore-log: 
,09-13 13:23:38.634  3914  3961 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-13 13:23:38.634  3914  3961 I jxcore-log:   bluetooth: 'on',
09-13 13:23:38.634  3914  3961 I jxcore-log:   wifi: 'on',
09-13 13:23:38.634  3914  3961 I jxcore-log:   cellular: 'doNotCare',
09-13 13:23:38.634  3914  3961 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-13 13:23:38.634  3914  3961 I jxcore-log: 
,09-13 13:23:38.639  3914  3961 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-13 13:23:38.639  3914  3961 I jxcore-log:   bluetooth: 'on',
09-13 13:23:38.639  3914  3961 I jxcore-log:   wifi: 'on',
09-13 13:23:38.639  3914  3961 I jxcore-log:   cellular: 'doNotCare',
09-13 13:23:38.639  3914  3961 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-13 13:23:38.639  3914  3961 I jxcore-log: 
,09-13 13:23:38.640  3914  3961 I jxcore-log: My device name is: motorola-Nexus 6
09-13 13:23:38.640  3914  3961 I jxcore-log: 
,09-13 13:23:38.641  3914  3961 I jxcore-log: Running for WIFI network type
09-13 13:23:38.641  3914  3961 I jxcore-log: 
,09-13 13:23:38.717  3914  4408 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 487, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-13 13:23:41.059  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-13 13:23:41.059  3914  3961 I jxcore-log: 
,09-13 13:23:41.503  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-13 13:23:41.503  3914  3961 I jxcore-log: 
,09-13 13:23:41.536  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-13 13:23:41.536  3914  3961 I jxcore-log: 
,09-13 13:23:42.888  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-13 13:23:42.888  3914  3961 I jxcore-log: 
,09-13 13:23:43.119  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-13 13:23:43.119  3914  3961 I jxcore-log: 
,09-13 13:23:43.124  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-13 13:23:43.124  3914  3961 I jxcore-log: 
,09-13 13:23:43.131  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-13 13:23:43.131  3914  3961 I jxcore-log: 
,09-13 13:23:43.207  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-13 13:23:43.207  3914  3961 I jxcore-log: 
,09-13 13:23:43.227  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-13 13:23:43.227  3914  3961 I jxcore-log: 
,09-13 13:23:43.232  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-13 13:23:43.232  3914  3961 I jxcore-log: 
,09-13 13:23:44.161  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-13 13:23:44.161  3914  3961 I jxcore-log: 
,09-13 13:23:44.326  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-13 13:23:44.326  3914  3961 I jxcore-log: 
,09-13 13:23:44.654  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-13 13:23:44.654  3914  3961 I jxcore-log: 
,09-13 13:23:44.665  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-13 13:23:44.665  3914  3961 I jxcore-log: 
,09-13 13:23:44.672  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-13 13:23:44.672  3914  3961 I jxcore-log: 
,09-13 13:23:44.679  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-13 13:23:44.679  3914  3961 I jxcore-log: 
,09-13 13:23:44.719  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-13 13:23:44.719  3914  3961 I jxcore-log: 
,09-13 13:23:44.766  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-13 13:23:44.766  3914  3961 I jxcore-log: 
,09-13 13:23:44.774  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-13 13:23:44.774  3914  3961 I jxcore-log: 
,09-13 13:23:44.781  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-13 13:23:44.781  3914  3961 I jxcore-log: 
,09-13 13:23:44.801  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-13 13:23:44.801  3914  3961 I jxcore-log: 
,09-13 13:23:44.806  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-13 13:23:44.806  3914  3961 I jxcore-log: 
,09-13 13:23:44.812  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-13 13:23:44.812  3914  3961 I jxcore-log: 
,09-13 13:23:44.828  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-13 13:23:44.828  3914  3961 I jxcore-log: 
,09-13 13:23:44.855  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-13 13:23:44.855  3914  3961 I jxcore-log: 
,09-13 13:23:44.866  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-13 13:23:44.866  3914  3961 I jxcore-log: 
,09-13 13:23:44.880  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-13 13:23:44.880  3914  3961 I jxcore-log: 
,09-13 13:23:44.892  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-13 13:23:44.892  3914  3961 I jxcore-log: 
,09-13 13:23:44.908  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-13 13:23:44.908  3914  3961 I jxcore-log: 
,09-13 13:23:44.919  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-13 13:23:44.919  3914  3961 I jxcore-log: 
,09-13 13:23:44.925  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-13 13:23:44.925  3914  3961 I jxcore-log: 
,09-13 13:23:44.955  3914  3961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-13 13:23:44.955  3914  3961 I jxcore-log: 
,09-13 13:23:44.966  3914  3961 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-13 13:23:44.967  3914  3961 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-13 13:23:44.967  3914  3961 I jxcore-log: 
,09-13 13:23:44.970  3914  3961 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-13 13:23:44.970  3914  3961 I jxcore-log: 
,09-13 13:23:44.970  3914  3961 I jxcore-log: ThaliTape :: Started ThaliTape
09-13 13:23:44.970  3914  3961 I jxcore-log: 
,09-13 13:23:44.975  3914  3961 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-13 13:23:44.975  3914  3961 I jxcore-log: 
,09-13 13:23:45.046  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:23:45.046  3914  3961 I jxcore-log: 
09-13 13:23:45.047  3914  3961 I jxcore-log: websocket error
09-13 13:23:45.047  3914  3961 I jxcore-log: 
09-13 13:23:45.047  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:23:45.047  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:23:45.047  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:23:45.047  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:23:45.047  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:23:45.047  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:23:45.047  3914  3961 I jxcore-log: 
,09-13 13:23:46.090  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:23:46.090  3914  3961 I jxcore-log: 
,09-13 13:23:46.092  3914  3961 I jxcore-log: websocket error
09-13 13:23:46.092  3914  3961 I jxcore-log: 
09-13 13:23:46.092  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:23:46.092  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:23:46.092  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:23:46.092  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:23:46.092  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:23:46.092  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:23:46.092  3914  3961 I jxcore-log: 
,09-13 13:23:47.689  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:23:47.689  3914  3961 I jxcore-log: 
,09-13 13:23:47.689  3914  3961 I jxcore-log: websocket error
09-13 13:23:47.689  3914  3961 I jxcore-log: 
09-13 13:23:47.689  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:23:47.689  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:23:47.689  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:23:47.689  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:23:47.689  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:23:47.689  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:23:47.689  3914  3961 I jxcore-log: 
,09-13 13:23:50.273  3692  4412 V KeepSync: Connecting to GoogleApiClient
,09-13 13:23:50.273   872  1389 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 13:23:50.336  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:23:50.341  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:23:50.382  1520  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 13:23:50.382  1520  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 13:23:50.382  1520  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:23:50.382  1520  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:23:50.409  1743  4413 V BaseAuthAsyncOperation: access token request failed
,09-13 13:23:50.412  3692  4412 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 13:23:50.486  1520  2299 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 13:23:50.486  1520  2299 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 13:23:50.486  1520  2299 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:23:50.486  1520  2299 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:23:50.514  3692  4412 E KeepSync: IOException
09-13 13:23:50.514  3692  4412 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 13:23:50.514  3692  4412 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:23:50.514  3692  4412 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 13:23:50.514  3692  4412 E KeepSync: 	... 10 more
,09-13 13:23:50.514  3692  4412 W KeepSync: Sync result 2
,09-13 13:23:50.528   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 249129, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:23:52.751  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:23:52.751  3914  3961 I jxcore-log: 
,09-13 13:23:52.752  3914  3961 I jxcore-log: websocket error
09-13 13:23:52.752  3914  3961 I jxcore-log: 
09-13 13:23:52.752  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:23:52.752  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:23:52.752  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:23:52.752  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:23:52.752  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:23:52.752  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:23:52.752  3914  3961 I jxcore-log: 
,09-13 13:23:54.385   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=253350, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:23:57.813  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:23:57.813  3914  3961 I jxcore-log: 
09-13 13:23:57.813  3914  3961 I jxcore-log: websocket error
09-13 13:23:57.813  3914  3961 I jxcore-log: 
,09-13 13:23:57.813  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:23:57.813  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:23:57.813  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:23:57.813  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:23:57.813  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:23:57.813  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:23:57.813  3914  3961 I jxcore-log: 
,09-13 13:24:02.792   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=261757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 13:24:02.872  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:02.872  3914  3961 I jxcore-log: 
,09-13 13:24:02.872  3914  3961 I jxcore-log: websocket error
09-13 13:24:02.872  3914  3961 I jxcore-log: 
09-13 13:24:02.872  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:02.872  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:02.872  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:02.872  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:02.872  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:02.872  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:02.872  3914  3961 I jxcore-log: 
,09-13 13:24:07.940  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:07.940  3914  3961 I jxcore-log: 
,09-13 13:24:07.940  3914  3961 I jxcore-log: websocket error
09-13 13:24:07.940  3914  3961 I jxcore-log: 
,09-13 13:24:07.940  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:07.940  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:07.940  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:07.940  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:07.940  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:07.940  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:07.940  3914  3961 I jxcore-log: 
,09-13 13:24:12.996  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:12.996  3914  3961 I jxcore-log: 
,09-13 13:24:12.997  3914  3961 I jxcore-log: websocket error
09-13 13:24:12.997  3914  3961 I jxcore-log: 
,09-13 13:24:12.997  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:12.997  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:12.997  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:12.997  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:12.997  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:12.997  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:12.997  3914  3961 I jxcore-log: 
,09-13 13:24:18.052  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:18.052  3914  3961 I jxcore-log: 
09-13 13:24:18.052  3914  3961 I jxcore-log: websocket error
09-13 13:24:18.052  3914  3961 I jxcore-log: 
,09-13 13:24:18.052  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:18.052  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5,
09-13 13:24:18.052  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:18.052  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:18.052  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:18.052  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:18.052  3914  3961 I jxcore-log: 
,09-13 13:24:21.403  3692  4415 V KeepSync: Connecting to GoogleApiClient
,09-13 13:24:21.404   872  1389 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 13:24:21.464  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:24:21.470  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:24:21.521  1520  2299 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 13:24:21.521  1520  2299 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 13:24:21.521  1520  2299 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:24:21.521  1520  2299 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:24:21.551  1743  4416 V BaseAuthAsyncOperation: access token request failed
,09-13 13:24:21.552  3692  4415 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 13:24:21.616  1520  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 13:24:21.616  1520  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 13:24:21.616  1520  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:24:21.616  1520  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:24:21.658  3692  4415 E KeepSync: IOException
09-13 13:24:21.658  3692  4415 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 13:24:21.658  3692  4415 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:24:21.658  3692  4415 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 13:24:21.658  3692  4415 E KeepSync: 	... 10 more
,09-13 13:24:21.658  3692  4415 W KeepSync: Sync result 2
,09-13 13:24:21.673   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 280226, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:24:23.109  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:23.109  3914  3961 I jxcore-log: 
,09-13 13:24:23.109  3914  3961 I jxcore-log: websocket error
09-13 13:24:23.109  3914  3961 I jxcore-log: 
09-13 13:24:23.109  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:23.109  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:23.109  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:23.109  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:23.109  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:23.109  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:23.109  3914  3961 I jxcore-log: 
,09-13 13:24:28.209  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:28.209  3914  3961 I jxcore-log: 
,09-13 13:24:28.210  3914  3961 I jxcore-log: websocket error
09-13 13:24:28.210  3914  3961 I jxcore-log: 
,09-13 13:24:28.210  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:28.210  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:28.210  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:28.210  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:28.210  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:28.210  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:28.210  3914  3961 I jxcore-log: 
,09-13 13:24:33.272  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:33.272  3914  3961 I jxcore-log: 
,09-13 13:24:33.272  3914  3961 I jxcore-log: websocket error
09-13 13:24:33.272  3914  3961 I jxcore-log: 
,09-13 13:24:33.273  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:33.273  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:33.273  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:33.273  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:33.273  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:33.273  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:33.273  3914  3961 I jxcore-log: 
,09-13 13:24:38.327  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:38.327  3914  3961 I jxcore-log: 
09-13 13:24:38.328  3914  3961 I jxcore-log: websocket error
09-13 13:24:38.328  3914  3961 I jxcore-log: 
09-13 13:24:38.328  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:38.328  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:38.328  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:38.328  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:38.328  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:38.328  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:38.328  3914  3961 I jxcore-log: 
,09-13 13:24:43.388  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:43.388  3914  3961 I jxcore-log: 
09-13 13:24:43.389  3914  3961 I jxcore-log: websocket error
09-13 13:24:43.389  3914  3961 I jxcore-log: 
,09-13 13:24:43.389  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:43.389  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:43.389  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:43.389  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:43.389  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:43.389  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:43.389  3914  3961 I jxcore-log: 
,09-13 13:24:46.152   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:24:48.445  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:48.445  3914  3961 I jxcore-log: 
,09-13 13:24:48.445  3914  3961 I jxcore-log: websocket error
09-13 13:24:48.445  3914  3961 I jxcore-log: 
09-13 13:24:48.445  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:48.445  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:48.445  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:48.445  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:48.445  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:48.445  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:48.445  3914  3961 I jxcore-log: 
,09-13 13:24:51.996  3717  4423 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 13:24:52.104  3717  4426 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 13:24:52.132  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:24:52.134  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:24:52.173  1520  2299 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:24:52.173  1520  2299 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 13:24:52.174  1520  2299 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:24:52.174  1520  2299 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:24:52.212  1520  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:24:52.213  1520  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:24:52.213  1520  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:24:52.213  1520  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:24:52.247  3643  4425 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:24:52.247  3643  4425 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:24:52.247  3643  4425 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	... 12 more
09-13 13:24:52.247  3643  4425 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at fal.a(PG:38)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:24:52.247  3643  4425 E HttpOperation: 	... 14 more
,09-13 13:24:52.289  1520  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-13 13:24:52.289  1520  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:24:52.289  1520  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:24:52.289  1520  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:24:52.394  3717  4426 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 13:24:52.395  1520  3094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:24:52.396  1520  3094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 13:24:52.396  1520  3094 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:24:52.396  1520  3094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-13 13:24:52.399  3717  4423 E BooksSync: Soft error
09-13 13:24:52.399  3717  4423 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:24:52.399  3717  4423 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 13:24:52.399  3717  4423 E BooksSync: Sync error
09-13 13:24:52.399  3717  4423 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:24:52.399  3717  4423 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 13:24:52.399  3717  4423 I BooksSync: Finished books sync
,09-13 13:24:52.427   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 281948, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:24:52.439  3643  4425 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 13:24:52.439  3643  4425 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at hec.a(PG:42)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at hee.a(PG:102)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at czr.a(PG:65)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at kka.a(PG:108)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423),
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:24:52.439  3643  4425 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	... 15 more
09-13 13:24:52.439  3643  4425 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at fal.a(PG:38)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:24:52.439  3643  4425 E HttpOperation: 	... 17 more
,09-13 13:24:52.439  3643  4425 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:24:52.439  3643  4425 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	... 15 more
09-13 13:24:52.439  3643  4425 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:24:52.439  3643  4425 E ExperimentLoader: 	... 17 more
,09-13 13:24:52.560   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 288398, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:24:53.432   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=312397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-13 13:24:54.500  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:54.500  3914  3961 I jxcore-log: 
09-13 13:24:54.501  3914  3961 I jxcore-log: websocket error
09-13 13:24:54.501  3914  3961 I jxcore-log: 
,09-13 13:24:54.502  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:54.502  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:54.502  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:54.502  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:54.502  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:54.502  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:54.502  3914  3961 I jxcore-log: 
,09-13 13:24:59.561  3914  3961 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-13 13:24:59.561  3914  3961 I jxcore-log: 
,09-13 13:24:59.561  3914  3961 I jxcore-log: websocket error
09-13 13:24:59.561  3914  3961 I jxcore-log: 
,09-13 13:24:59.561  3914  3961 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-13 13:24:59.561  3914  3961 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-13 13:24:59.561  3914  3961 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-13 13:24:59.561  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:59.561  3914  3961 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-13 13:24:59.561  3914  3961 I jxcore-log: emit@events.js:82:1
09-13 13:24:59.561  3914  3961 I jxcore-log: 
,09-13 13:25:04.684  3914  3961 I jxcore-log: ThaliTape :: Reconnected to the test server
09-13 13:25:04.684  3914  3961 I jxcore-log: 
,09-13 13:25:04.700  3914  3961 I jxcore-log: ThaliTape :: Connected to the test server
09-13 13:25:04.700  3914  3961 I jxcore-log: 
,09-13 13:25:23.333  3692  4438 V KeepSync: Connecting to GoogleApiClient
,09-13 13:25:23.334   872  2100 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 13:25:23.389  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:25:23.392  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:25:23.434  1520  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 13:25:23.434  1520  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-13 13:25:23.434  1520  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:25:23.434  1520  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:25:23.463  1743  4439 V BaseAuthAsyncOperation: access token request failed
,09-13 13:25:23.464  3692  4438 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 13:25:23.530  1520  3094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-13 13:25:23.530  1520  3094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-13 13:25:23.530  1520  3094 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:25:23.530  1520  3094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:25:23.553  3692  4438 E KeepSync: IOException
09-13 13:25:23.553  3692  4438 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 13:25:23.553  3692  4438 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:25:23.553  3692  4438 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 13:25:23.553  3692  4438 E KeepSync: 	... 10 more
,09-13 13:25:23.553  3692  4438 W KeepSync: Sync result 2
,09-13 13:25:23.571   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 342103, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:25:24.720  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:25:24.786  1520  2299 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
09-13 13:25:24.786  1520  2299 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-13 13:25:24.787  1520  2299 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:25:24.787  1520  2299 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:25:24.828  1520  2299 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-13 13:25:24.828  1520  2299 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-13 13:25:24.828  1520  2299 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-13 13:25:24.828  1520  2299 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-13 13:25:24.828  1520  2299 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-13 13:25:24.828  1520  2299 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-13 13:25:24.828  1520  2299 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 13:25:24.840  3606  3635 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-13 13:25:24.840  3606  3635 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-13 13:25:24.840  3606  3635 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-13 13:25:24.840  3606  3635 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-13 13:25:24.840  3606  3635 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-13 13:25:24.840  3606  3635 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-13 13:25:24.840  3606  3635 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-13 13:25:53.757  3717  4446 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 13:25:53.864  3717  4448 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 13:25:53.874  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:25:53.877  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:25:53.915  1520  2299 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:25:53.915  1520  2299 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 13:25:53.915  1520  2299 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:25:53.915  1520  2299 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:25:53.952  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:25:53.960  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:25:54.031  1520  2299 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:25:54.031  1520  2299 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:25:54.031  1520  2299 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:25:54.032  1520  2299 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:25:54.058  1520  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:25:54.059  1520  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-13 13:25:54.059  1520  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:25:54.059  1520  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:25:54.076  3717  4448 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 13:25:54.077  3717  4446 E BooksSync: Soft error
09-13 13:25:54.077  3717  4446 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:25:54.077  3717  4446 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 13:25:54.077  3717  4446 E BooksSync: Sync error
09-13 13:25:54.077  3717  4446 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:25:54.077  3717  4446 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 13:25:54.077  3717  4446 I BooksSync: Finished books sync
,09-13 13:25:54.096   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 343771, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:25:54.113  3643  4447 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:25:54.113  3643  4447 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:25:54.113  3643  4447 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	... 12 more
09-13 13:25:54.113  3643  4447 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at fal.a(PG:38)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:25:54.113  3643  4447 E HttpOperation: 	... 14 more
,09-13 13:25:54.153  1520  3094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 13:25:54.153  1520  3094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:25:54.154  1520  3094 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:25:54.154  1520  3094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:25:54.166  3643  4447 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 13:25:54.166  3643  4447 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at hec.a(PG:42)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at hee.a(PG:102)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at czr.a(PG:65)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at kka.a(PG:108)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:25:54.166  3643  4447 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	... 15 more
09-13 13:25:54.166  3643  4447 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at fal.a(PG:38)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:25:54.166  3643  4447 E HttpOperation: 	... 17 more
09-13 13:25:54.166  3643  4447 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:25:54.166  3643  4447 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	... 15 more
09-13 13:25:54.166  3643  4447 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:25:54.166  3643  4447 E ExperimentLoader: 	... 17 more
,09-13 13:25:54.344   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 343086, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:26:57.722  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:26:57.724  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:26:57.754  1520  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 13:26:57.754  1520  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:26:57.754  1520  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:26:57.754  1520  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:26:57.774  3643  4453 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:26:57.774  3643  4453 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:26:57.774  3643  4453 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	... 12 more
09-13 13:26:57.774  3643  4453 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at fal.a(PG:38)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:26:57.774  3643  4453 E HttpOperation: 	... 14 more
,09-13 13:26:57.830  1520  3094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-13 13:26:57.831  1520  3094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:26:57.831  1520  3094 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:26:57.831  1520  3094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:26:57.859  3643  4453 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 13:26:57.859  3643  4453 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at hec.a(PG:42)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at hee.a(PG:102)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at czr.a(PG:65)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at kka.a(PG:108)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:26:57.859  3643  4453 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	... 15 more
09-13 13:26:57.859  3643  4453 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at fal.a(PG:38)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:26:57.859  3643  4453 E HttpOperation: 	... 17 more
09-13 13:26:57.859  3643  4453 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:26:57.859  3643  4453 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	... 15 more
09-13 13:26:57.859  3643  4453 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:26:57.859  3643  4453 E ExperimentLoader: 	... 17 more
,09-13 13:26:57.999   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 436430, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:27:19.140  3914  3961 I jxcore-log: TAP version 13
09-13 13:27:19.140  3914  3961 I jxcore-log: 
,09-13 13:27:19.144  3914  3961 I jxcore-log: # setup
09-13 13:27:19.144  3914  3961 I jxcore-log: 
,09-13 13:27:20.206  3914  3961 I jxcore-log: # 1. calling createNativeListener directly rejects
09-13 13:27:20.206  3914  3961 I jxcore-log: 
,09-13 13:27:20.609  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:20.609  3914  3961 I jxcore-log: 
,09-13 13:27:20.617  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 49521
09-13 13:27:20.617  3914  3961 I jxcore-log: 
,09-13 13:27:20.625  3914  3961 I jxcore-log: ok 1 Should throw
09-13 13:27:20.625  3914  3961 I jxcore-log: 
,09-13 13:27:20.627  3914  3961 I jxcore-log: # teardown
09-13 13:27:20.627  3914  3961 I jxcore-log: 
,09-13 13:27:21.518  3914  3961 I jxcore-log: # setup
09-13 13:27:21.518  3914  3961 I jxcore-log: 
,09-13 13:27:21.920  3914  3961 I jxcore-log: # 2. emits incomingConnectionState
09-13 13:27:21.920  3914  3961 I jxcore-log: 
,09-13 13:27:22.727  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:22.727  3914  3961 I jxcore-log: 
,09-13 13:27:22.739  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 41839
09-13 13:27:22.739  3914  3961 I jxcore-log: 
,09-13 13:27:22.747  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:22.747  3914  3961 I jxcore-log: 
,09-13 13:27:22.750  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:22.750  3914  3961 I jxcore-log: 
,09-13 13:27:22.760  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:22.760  3914  3961 I jxcore-log: 
,09-13 13:27:22.766  3914  3961 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-13 13:27:22.766  3914  3961 I jxcore-log: 
,09-13 13:27:22.787  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:22.787  3914  3961 I jxcore-log: 
,09-13 13:27:22.788  3914  3961 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-13 13:27:22.788  3914  3961 I jxcore-log: 
,09-13 13:27:22.795  3914  3961 I jxcore-log: # teardown
09-13 13:27:22.795  3914  3961 I jxcore-log: 
,09-13 13:27:23.459  3914  3961 I jxcore-log: # setup
09-13 13:27:23.459  3914  3961 I jxcore-log: 
,09-13 13:27:24.068  3914  3961 I jxcore-log: # 3. emits routerPortConnectionFailed
09-13 13:27:24.068  3914  3961 I jxcore-log: 
,09-13 13:27:24.880  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:24.880  3914  3961 I jxcore-log: 
,09-13 13:27:24.887  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 43856
09-13 13:27:24.887  3914  3961 I jxcore-log: 
,09-13 13:27:24.900  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:24.900  3914  3961 I jxcore-log: 
,09-13 13:27:24.901  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:24.901  3914  3961 I jxcore-log: 
,09-13 13:27:24.903  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:24.903  3914  3961 I jxcore-log: 
,09-13 13:27:24.933  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:24.933  3914  3961 I jxcore-log: 
,09-13 13:27:24.936  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:24.936  3914  3961 I jxcore-log: 
,09-13 13:27:24.940  3914  3961 I jxcore-log: DEBUG createNativeListener: 
09-13 13:27:24.940  3914  3961 I jxcore-log: 
,09-13 13:27:24.942  3914  3961 I jxcore-log: ok 4 tried to connect to right port
09-13 13:27:24.942  3914  3961 I jxcore-log: 
,09-13 13:27:24.942  3914  3961 I jxcore-log: ok 5 failed due to refused connection
09-13 13:27:24.942  3914  3961 I jxcore-log: 
09-13 13:27:24.943  3914  3961 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-13 13:27:24.943  3914  3961 I jxcore-log: 
,09-13 13:27:24.946  3914  3961 I jxcore-log: # teardown
09-13 13:27:24.946  3914  3961 I jxcore-log: 
,09-13 13:27:24.947  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:24.947  3914  3961 I jxcore-log: 
,09-13 13:27:25.404  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:25.404  3914  3961 I jxcore-log: 
,09-13 13:27:25.409  3914  3961 I jxcore-log: # setup
09-13 13:27:25.409  3914  3961 I jxcore-log: 
,09-13 13:27:25.410  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:25.410  3914  3961 I jxcore-log: 
,09-13 13:27:25.620  3914  3961 I jxcore-log: # 4. native server connections all up
09-13 13:27:25.620  3914  3961 I jxcore-log: 
,09-13 13:27:26.622  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:26.622  3914  3961 I jxcore-log: 
,09-13 13:27:26.632  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 41229
09-13 13:27:26.632  3914  3961 I jxcore-log: 
,09-13 13:27:26.644  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:26.644  3914  3961 I jxcore-log: 
,09-13 13:27:26.645  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:26.645  3914  3961 I jxcore-log: 
09-13 13:27:26.647  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:26.647  3914  3961 I jxcore-log: 
,09-13 13:27:26.679  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:26.679  3914  3961 I jxcore-log: 
,09-13 13:27:26.682  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:26.682  3914  3961 I jxcore-log: 
,09-13 13:27:26.685  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:26.685  3914  3961 I jxcore-log: 
,09-13 13:27:26.687  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:26.687  3914  3961 I jxcore-log: 
,09-13 13:27:26.710  3914  3961 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-13 13:27:26.710  3914  3961 I jxcore-log: 
09-13 13:27:26.711  3914  3961 I jxcore-log: ok 8 Send/recvd #1 should be same
09-13 13:27:26.711  3914  3961 I jxcore-log: 
,09-13 13:27:26.713  3914  3961 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-13 13:27:26.713  3914  3961 I jxcore-log: 
,09-13 13:27:26.714  3914  3961 I jxcore-log: ok 10 Send/recvd #2 should be same
09-13 13:27:26.714  3914  3961 I jxcore-log: 
,09-13 13:27:26.717  3914  3961 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-13 13:27:26.717  3914  3961 I jxcore-log: 
,09-13 13:27:26.723  3914  3961 I jxcore-log: # teardown
09-13 13:27:26.723  3914  3961 I jxcore-log: 
,09-13 13:27:27.761  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:27.761  3914  3961 I jxcore-log: 
,09-13 13:27:27.763  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:27.763  3914  3961 I jxcore-log: 
,09-13 13:27:27.765  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:27.765  3914  3961 I jxcore-log: 
,09-13 13:27:27.769  3914  3961 I jxcore-log: # setup
09-13 13:27:27.769  3914  3961 I jxcore-log: 
,09-13 13:27:27.771  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:27.771  3914  3961 I jxcore-log: 
,09-13 13:27:28.022  3914  3961 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
09-13 13:27:28.022  3914  3961 I jxcore-log: 
,09-13 13:27:28.243  3717  4456 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 13:27:28.295  3717  4458 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 13:27:28.305  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:27:28.307  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:27:28.330  1520  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:27:28.331  1520  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:27:28.331  1520  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-13 13:27:28.331  1520  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:27:28.353  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:27:28.356  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:27:28.368  3692  4457 V KeepSync: Connecting to GoogleApiClient
,09-13 13:27:28.368   872  1912 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-13 13:27:28.387  1520  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-13 13:27:28.387  1520  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:27:28.387  1520  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:27:28.388  1520  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:27:28.409  3717  4458 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 13:27:28.410  3717  4456 E BooksSync: Soft error
09-13 13:27:28.410  3717  4456 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:27:28.410  3717  4456 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 13:27:28.410  3717  4456 E BooksSync: Sync error,
09-13 13:27:28.410  3717  4456 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:27:28.410  3717  4456 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 13:27:28.410  3717  4456 I BooksSync: Finished books sync
,09-13 13:27:28.422   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 437820, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:27:28.434  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:27:28.439  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:27:28.464  1520  3094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-13 13:27:28.464  1520  3094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-13 13:27:28.464  1520  3094 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:27:28.464  1520  3094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:27:28.480  1743  4459 V BaseAuthAsyncOperation: access token request failed
,09-13 13:27:28.481  3692  4457 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-13 13:27:28.525  1520  1542 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-13 13:27:28.525  1520  1542 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-13 13:27:28.525  1520  1542 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:27:28.525  1520  1542 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:27:28.541  3692  4457 E KeepSync: IOException
09-13 13:27:28.541  3692  4457 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-13 13:27:28.541  3692  4457 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-13 13:27:28.541  3692  4457 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-13 13:27:28.541  3692  4457 E KeepSync: 	... 10 more
,09-13 13:27:28.541  3692  4457 W KeepSync: Sync result 2
,09-13 13:27:28.549   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 465465, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:27:29.286  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:29.286  3914  3961 I jxcore-log: 
,09-13 13:27:29.289  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 49028
09-13 13:27:29.289  3914  3961 I jxcore-log: 
,09-13 13:27:29.295  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:29.295  3914  3961 I jxcore-log: 
,09-13 13:27:29.297  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:29.297  3914  3961 I jxcore-log: 
,09-13 13:27:29.298  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:29.298  3914  3961 I jxcore-log: 
,09-13 13:27:29.314  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:29.314  3914  3961 I jxcore-log: 
,09-13 13:27:29.317  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:29.317  3914  3961 I jxcore-log: 
,09-13 13:27:29.330  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:29.330  3914  3961 I jxcore-log: 
,09-13 13:27:29.343  3914  3961 I jxcore-log: ok 12 socket shouldn't close until after stream
09-13 13:27:29.343  3914  3961 I jxcore-log: 
,09-13 13:27:29.344  3914  3961 I jxcore-log: ok 13 incoming remains open
09-13 13:27:29.344  3914  3961 I jxcore-log: 
,09-13 13:27:29.349  3914  3961 I jxcore-log: # teardown
09-13 13:27:29.349  3914  3961 I jxcore-log: 
,09-13 13:27:29.433  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:29.433  3914  3961 I jxcore-log: 
,09-13 13:27:29.446  3914  3961 I jxcore-log: # setup
09-13 13:27:29.446  3914  3961 I jxcore-log: 
,09-13 13:27:29.447  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:29.447  3914  3961 I jxcore-log: 
,09-13 13:27:30.528  3914  3961 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
09-13 13:27:30.528  3914  3961 I jxcore-log: 
,09-13 13:27:30.743  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:30.743  3914  3961 I jxcore-log: 
,09-13 13:27:30.751  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 44502
09-13 13:27:30.751  3914  3961 I jxcore-log: 
,09-13 13:27:30.763  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:30.763  3914  3961 I jxcore-log: 
,09-13 13:27:30.766  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:30.766  3914  3961 I jxcore-log: 
,09-13 13:27:30.768  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:30.768  3914  3961 I jxcore-log: 
,09-13 13:27:30.778  3914  3961 I jxcore-log: ok 14 we should not have gotten an error
09-13 13:27:30.778  3914  3961 I jxcore-log: 
,09-13 13:27:30.787  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:30.787  3914  3961 I jxcore-log: 
,09-13 13:27:30.789  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:30.789  3914  3961 I jxcore-log: 
,09-13 13:27:30.800  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:30.800  3914  3961 I jxcore-log: 
,09-13 13:27:30.803  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:30.803  3914  3961 I jxcore-log: 
,09-13 13:27:30.812  3914  3961 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-13 13:27:30.812  3914  3961 I jxcore-log: 
,09-13 13:27:30.812  3914  3961 I jxcore-log: ok 16 incoming is cleaned up
09-13 13:27:30.812  3914  3961 I jxcore-log: 
,09-13 13:27:30.815  3914  3961 I jxcore-log: # teardown
09-13 13:27:30.815  3914  3961 I jxcore-log: 
,09-13 13:27:31.648  3914  3961 I jxcore-log: # setup
09-13 13:27:31.648  3914  3961 I jxcore-log: 
,09-13 13:27:32.468  3914  3961 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
09-13 13:27:32.468  3914  3961 I jxcore-log: 
,09-13 13:27:32.693  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:32.693  3914  3961 I jxcore-log: 
,09-13 13:27:32.703  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 40407
09-13 13:27:32.703  3914  3961 I jxcore-log: 
,09-13 13:27:32.711  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:32.711  3914  3961 I jxcore-log: 
,09-13 13:27:32.717  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:32.717  3914  3961 I jxcore-log: 
,09-13 13:27:32.720  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:32.720  3914  3961 I jxcore-log: 
,09-13 13:27:32.735  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:32.735  3914  3961 I jxcore-log: 
,09-13 13:27:32.738  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:32.738  3914  3961 I jxcore-log: 
,09-13 13:27:32.753  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:32.753  3914  3961 I jxcore-log: 
,09-13 13:27:32.762  3914  3961 I jxcore-log: ok 17 stream was closed
09-13 13:27:32.762  3914  3961 I jxcore-log: 
,09-13 13:27:32.762  3914  3961 I jxcore-log: ok 18 incoming should survive
09-13 13:27:32.762  3914  3961 I jxcore-log: 
09-13 13:27:32.762  3914  3961 I jxcore-log: ok 19 mux should have no streams
09-13 13:27:32.762  3914  3961 I jxcore-log: 
,09-13 13:27:32.778  3914  3961 I jxcore-log: # teardown
09-13 13:27:32.778  3914  3961 I jxcore-log: 
,09-13 13:27:34.097  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:34.097  3914  3961 I jxcore-log: 
,09-13 13:27:34.103  3914  3961 I jxcore-log: # setup
09-13 13:27:34.103  3914  3961 I jxcore-log: 
,09-13 13:27:34.104  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:34.104  3914  3961 I jxcore-log: 
,09-13 13:27:34.170  3914  3961 I jxcore-log: # 8. native server - closing the whole server cleans everything up
09-13 13:27:34.170  3914  3961 I jxcore-log: 
,09-13 13:27:34.302  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:34.302  3914  3961 I jxcore-log: 
,09-13 13:27:34.310  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 45561
09-13 13:27:34.310  3914  3961 I jxcore-log: 
,09-13 13:27:34.321  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.321  3914  3961 I jxcore-log: 
,09-13 13:27:34.322  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.322  3914  3961 I jxcore-log: 
,09-13 13:27:34.324  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.324  3914  3961 I jxcore-log: 
,09-13 13:27:34.333  3914  3961 I jxcore-log: ok 20 we should not have gotten an error
09-13 13:27:34.333  3914  3961 I jxcore-log: 
,09-13 13:27:34.342  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.342  3914  3961 I jxcore-log: 
,09-13 13:27:34.345  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.345  3914  3961 I jxcore-log: 
,09-13 13:27:34.355  3914  3961 I jxcore-log: ok 21 Buffers are identical
09-13 13:27:34.355  3914  3961 I jxcore-log: 
,09-13 13:27:34.358  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:34.358  3914  3961 I jxcore-log: 
,09-13 13:27:34.361  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:34.361  3914  3961 I jxcore-log: 
,09-13 13:27:34.364  3914  3961 I jxcore-log: ok 22 native server is nulled out
09-13 13:27:34.364  3914  3961 I jxcore-log: 
,09-13 13:27:34.364  3914  3961 I jxcore-log: ok 23 native server should be closed
09-13 13:27:34.364  3914  3961 I jxcore-log: 
,09-13 13:27:34.365  3914  3961 I jxcore-log: ok 24 incoming has been removed
09-13 13:27:34.365  3914  3961 I jxcore-log: 
09-13 13:27:34.365  3914  3961 I jxcore-log: ok 25 Incoming should be done
09-13 13:27:34.365  3914  3961 I jxcore-log: 
,09-13 13:27:34.365  3914  3961 I jxcore-log: ok 26 The mux object should be closed
09-13 13:27:34.365  3914  3961 I jxcore-log: 
09-13 13:27:34.366  3914  3961 I jxcore-log: ok 27 The mux stream should be closed
09-13 13:27:34.366  3914  3961 I jxcore-log: 
,09-13 13:27:34.367  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:34.367  3914  3961 I jxcore-log: 
,09-13 13:27:34.381  3914  3961 I jxcore-log: # teardown
09-13 13:27:34.381  3914  3961 I jxcore-log: 
,09-13 13:27:34.487  3914  3961 I jxcore-log: # setup
09-13 13:27:34.487  3914  3961 I jxcore-log: 
,09-13 13:27:34.576  3914  3961 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
09-13 13:27:34.576  3914  3961 I jxcore-log: 
,09-13 13:27:34.681  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:34.681  3914  3961 I jxcore-log: 
,09-13 13:27:34.696  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 40759
09-13 13:27:34.696  3914  3961 I jxcore-log: 
,09-13 13:27:34.718  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.718  3914  3961 I jxcore-log: 
,09-13 13:27:34.719  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.719  3914  3961 I jxcore-log: 
,09-13 13:27:34.721  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.721  3914  3961 I jxcore-log: 
,09-13 13:27:34.724  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.724  3914  3961 I jxcore-log: 
,09-13 13:27:34.725  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.725  3914  3961 I jxcore-log: 
,09-13 13:27:34.726  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.726  3914  3961 I jxcore-log: 
,09-13 13:27:34.729  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.729  3914  3961 I jxcore-log: 
,09-13 13:27:34.730  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.730  3914  3961 I jxcore-log: 
,09-13 13:27:34.731  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.731  3914  3961 I jxcore-log: 
,09-13 13:27:34.735  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.735  3914  3961 I jxcore-log: 
,09-13 13:27:34.736  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.736  3914  3961 I jxcore-log: 
,09-13 13:27:34.737  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.737  3914  3961 I jxcore-log: 
,09-13 13:27:34.741  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.741  3914  3961 I jxcore-log: 
,09-13 13:27:34.742  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.742  3914  3961 I jxcore-log: 
,09-13 13:27:34.743  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.743  3914  3961 I jxcore-log: 
,09-13 13:27:34.746  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.746  3914  3961 I jxcore-log: 
,09-13 13:27:34.746  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.746  3914  3961 I jxcore-log: 
,09-13 13:27:34.748  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.748  3914  3961 I jxcore-log: 
,09-13 13:27:34.757  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.757  3914  3961 I jxcore-log: 
,09-13 13:27:34.758  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.758  3914  3961 I jxcore-log: 
,09-13 13:27:34.760  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.760  3914  3961 I jxcore-log: 
,09-13 13:27:34.763  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.763  3914  3961 I jxcore-log: 
,09-13 13:27:34.764  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.764  3914  3961 I jxcore-log: 
,09-13 13:27:34.765  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.765  3914  3961 I jxcore-log: 
,09-13 13:27:34.767  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.767  3914  3961 I jxcore-log: 
09-13 13:27:34.767  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.767  3914  3961 I jxcore-log: 
,09-13 13:27:34.768  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.768  3914  3961 I jxcore-log: 
09-13 13:27:34.770  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:34.770  3914  3961 I jxcore-log: 
,09-13 13:27:34.770  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:34.770  3914  3961 I jxcore-log: 
09-13 13:27:34.771  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:34.771  3914  3961 I jxcore-log: 
,09-13 13:27:34.849  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.849  3914  3961 I jxcore-log: 
,09-13 13:27:34.854  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.854  3914  3961 I jxcore-log: 
,09-13 13:27:34.861  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.861  3914  3961 I jxcore-log: 
,09-13 13:27:34.867  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.867  3914  3961 I jxcore-log: 
,09-13 13:27:34.870  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.870  3914  3961 I jxcore-log: 
,09-13 13:27:34.873  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.873  3914  3961 I jxcore-log: 
,09-13 13:27:34.876  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.876  3914  3961 I jxcore-log: 
,09-13 13:27:34.878  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.878  3914  3961 I jxcore-log: 
,09-13 13:27:34.882  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.882  3914  3961 I jxcore-log: 
,09-13 13:27:34.884  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.884  3914  3961 I jxcore-log: 
,09-13 13:27:34.886  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.886  3914  3961 I jxcore-log: 
,09-13 13:27:34.889  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.889  3914  3961 I jxcore-log: 
,09-13 13:27:34.891  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.891  3914  3961 I jxcore-log: 
,09-13 13:27:34.893  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.893  3914  3961 I jxcore-log: 
,09-13 13:27:34.895  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.895  3914  3961 I jxcore-log: 
,09-13 13:27:34.897  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.897  3914  3961 I jxcore-log: 
,09-13 13:27:34.900  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.900  3914  3961 I jxcore-log: 
,09-13 13:27:34.903  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.903  3914  3961 I jxcore-log: 
,09-13 13:27:34.905  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.905  3914  3961 I jxcore-log: 
,09-13 13:27:34.907  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.907  3914  3961 I jxcore-log: 
,09-13 13:27:34.909  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.909  3914  3961 I jxcore-log: 
,09-13 13:27:34.911  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.911  3914  3961 I jxcore-log: 
,09-13 13:27:34.913  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.913  3914  3961 I jxcore-log: 
,09-13 13:27:34.914  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.914  3914  3961 I jxcore-log: 
,09-13 13:27:34.916  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.916  3914  3961 I jxcore-log: 
,09-13 13:27:34.918  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.918  3914  3961 I jxcore-log: 
,09-13 13:27:34.919  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.919  3914  3961 I jxcore-log: 
,09-13 13:27:34.921  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.921  3914  3961 I jxcore-log: 
,09-13 13:27:34.922  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.922  3914  3961 I jxcore-log: 
,09-13 13:27:34.924  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.924  3914  3961 I jxcore-log: 
,09-13 13:27:34.925  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.925  3914  3961 I jxcore-log: 
,09-13 13:27:34.927  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.927  3914  3961 I jxcore-log: 
,09-13 13:27:34.929  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.929  3914  3961 I jxcore-log: 
,09-13 13:27:34.931  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.931  3914  3961 I jxcore-log: 
09-13 13:27:34.932  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.932  3914  3961 I jxcore-log: 
09-13 13:27:34.934  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.934  3914  3961 I jxcore-log: 
,09-13 13:27:34.935  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.935  3914  3961 I jxcore-log: 
,09-13 13:27:34.943  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.943  3914  3961 I jxcore-log: 
,09-13 13:27:34.945  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.945  3914  3961 I jxcore-log: 
,09-13 13:27:34.946  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.946  3914  3961 I jxcore-log: 
,09-13 13:27:34.952  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.952  3914  3961 I jxcore-log: 
,09-13 13:27:34.954  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.954  3914  3961 I jxcore-log: 
,09-13 13:27:34.955  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.955  3914  3961 I jxcore-log: 
,09-13 13:27:34.957  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.957  3914  3961 I jxcore-log: 
,09-13 13:27:34.958  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.958  3914  3961 I jxcore-log: 
,09-13 13:27:34.959  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.959  3914  3961 I jxcore-log: 
,09-13 13:27:34.960  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.960  3914  3961 I jxcore-log: 
,09-13 13:27:34.962  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.962  3914  3961 I jxcore-log: 
,09-13 13:27:34.964  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.964  3914  3961 I jxcore-log: 
,09-13 13:27:34.965  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.965  3914  3961 I jxcore-log: 
,09-13 13:27:34.967  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.967  3914  3961 I jxcore-log: 
,09-13 13:27:34.968  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.968  3914  3961 I jxcore-log: 
,09-13 13:27:34.969  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.969  3914  3961 I jxcore-log: 
,09-13 13:27:34.971  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.971  3914  3961 I jxcore-log: 
,09-13 13:27:34.972  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.972  3914  3961 I jxcore-log: 
,09-13 13:27:34.973  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.973  3914  3961 I jxcore-log: 
,09-13 13:27:34.975  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.975  3914  3961 I jxcore-log: 
,09-13 13:27:34.977  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.977  3914  3961 I jxcore-log: 
,09-13 13:27:34.978  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.978  3914  3961 I jxcore-log: 
,09-13 13:27:34.980  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.980  3914  3961 I jxcore-log: 
09-13 13:27:34.981  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.981  3914  3961 I jxcore-log: 
,09-13 13:27:34.982  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.982  3914  3961 I jxcore-log: 
,09-13 13:27:34.983  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.983  3914  3961 I jxcore-log: 
,09-13 13:27:34.985  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.985  3914  3961 I jxcore-log: 
,09-13 13:27:34.987  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.987  3914  3961 I jxcore-log: 
,09-13 13:27:34.988  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.988  3914  3961 I jxcore-log: 
,09-13 13:27:34.990  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.990  3914  3961 I jxcore-log: 
09-13 13:27:34.991  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.991  3914  3961 I jxcore-log: 
,09-13 13:27:34.992  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.992  3914  3961 I jxcore-log: 
,09-13 13:27:34.994  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.994  3914  3961 I jxcore-log: 
09-13 13:27:34.995  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.995  3914  3961 I jxcore-log: 
,09-13 13:27:34.997  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:34.997  3914  3961 I jxcore-log: 
,09-13 13:27:34.999  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:34.999  3914  3961 I jxcore-log: 
,09-13 13:27:35.000  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:35.000  3914  3961 I jxcore-log: 
,09-13 13:27:35.002  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:35.002  3914  3961 I jxcore-log: 
,09-13 13:27:35.003  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:35.003  3914  3961 I jxcore-log: 
,09-13 13:27:35.004  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:35.004  3914  3961 I jxcore-log: 
,09-13 13:27:35.006  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:35.006  3914  3961 I jxcore-log: 
,09-13 13:27:35.007  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:35.007  3914  3961 I jxcore-log: 
,09-13 13:27:35.008  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:35.008  3914  3961 I jxcore-log: 
,09-13 13:27:35.094  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.094  3914  3961 I jxcore-log: 
,09-13 13:27:35.096  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.096  3914  3961 I jxcore-log: 
,09-13 13:27:35.097  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.097  3914  3961 I jxcore-log: 
,09-13 13:27:35.099  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.099  3914  3961 I jxcore-log: 
09-13 13:27:35.100  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.100  3914  3961 I jxcore-log: 
,09-13 13:27:35.102  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.102  3914  3961 I jxcore-log: 
,09-13 13:27:35.103  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.103  3914  3961 I jxcore-log: 
,09-13 13:27:35.104  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.104  3914  3961 I jxcore-log: 
09-13 13:27:35.105  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.105  3914  3961 I jxcore-log: 
,09-13 13:27:35.106  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.106  3914  3961 I jxcore-log: 
,09-13 13:27:35.107  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.107  3914  3961 I jxcore-log: 
,09-13 13:27:35.110  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.110  3914  3961 I jxcore-log: 
,09-13 13:27:35.111  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.111  3914  3961 I jxcore-log: 
,09-13 13:27:35.112  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.112  3914  3961 I jxcore-log: 
,09-13 13:27:35.114  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.114  3914  3961 I jxcore-log: 
,09-13 13:27:35.119  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.119  3914  3961 I jxcore-log: 
,09-13 13:27:35.120  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.120  3914  3961 I jxcore-log: 
,09-13 13:27:35.121  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.121  3914  3961 I jxcore-log: 
,09-13 13:27:35.122  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.122  3914  3961 I jxcore-log: 
,09-13 13:27:35.124  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.124  3914  3961 I jxcore-log: 
09-13 13:27:35.125  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.125  3914  3961 I jxcore-log: 
,09-13 13:27:35.126  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.126  3914  3961 I jxcore-log: 
,09-13 13:27:35.127  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.127  3914  3961 I jxcore-log: 
,09-13 13:27:35.128  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.128  3914  3961 I jxcore-log: 
,09-13 13:27:35.129  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.129  3914  3961 I jxcore-log: 
,09-13 13:27:35.131  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.131  3914  3961 I jxcore-log: 
09-13 13:27:35.132  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.132  3914  3961 I jxcore-log: 
,09-13 13:27:35.133  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.133  3914  3961 I jxcore-log: 
,09-13 13:27:35.134  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.134  3914  3961 I jxcore-log: 
,09-13 13:27:35.135  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.135  3914  3961 I jxcore-log: 
,09-13 13:27:35.136  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.136  3914  3961 I jxcore-log: 
,09-13 13:27:35.138  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.138  3914  3961 I jxcore-log: 
09-13 13:27:35.139  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.139  3914  3961 I jxcore-log: 
,09-13 13:27:35.140  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.140  3914  3961 I jxcore-log: 
,09-13 13:27:35.141  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.141  3914  3961 I jxcore-log: 
,09-13 13:27:35.142  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.142  3914  3961 I jxcore-log: 
09-13 13:27:35.143  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.143  3914  3961 I jxcore-log: 
,09-13 13:27:35.144  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.144  3914  3961 I jxcore-log: 
,09-13 13:27:35.148  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.148  3914  3961 I jxcore-log: 
,09-13 13:27:35.150  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.150  3914  3961 I jxcore-log: 
,09-13 13:27:35.151  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.151  3914  3961 I jxcore-log: 
,09-13 13:27:35.152  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.152  3914  3961 I jxcore-log: 
09-13 13:27:35.153  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.153  3914  3961 I jxcore-log: 
,09-13 13:27:35.154  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.154  3914  3961 I jxcore-log: 
,09-13 13:27:35.155  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.155  3914  3961 I jxcore-log: 
,09-13 13:27:35.156  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.156  3914  3961 I jxcore-log: 
09-13 13:27:35.157  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.157  3914  3961 I jxcore-log: 
,09-13 13:27:35.158  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.158  3914  3961 I jxcore-log: 
,09-13 13:27:35.159  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.159  3914  3961 I jxcore-log: 
,09-13 13:27:35.160  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.160  3914  3961 I jxcore-log: 
,09-13 13:27:35.164  3914  3961 I jxcore-log: ok 28 native server is nulled out
09-13 13:27:35.164  3914  3961 I jxcore-log: 
,09-13 13:27:35.164  3914  3961 I jxcore-log: ok 29 native server should be closed
09-13 13:27:35.164  3914  3961 I jxcore-log: 
09-13 13:27:35.165  3914  3961 I jxcore-log: ok 30 incoming has been removed
09-13 13:27:35.165  3914  3961 I jxcore-log: 
,09-13 13:27:35.166  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.166  3914  3961 I jxcore-log: 
09-13 13:27:35.167  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.167  3914  3961 I jxcore-log: 
,09-13 13:27:35.167  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.167  3914  3961 I jxcore-log: 
09-13 13:27:35.168  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.168  3914  3961 I jxcore-log: 
,09-13 13:27:35.168  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.168  3914  3961 I jxcore-log: 
09-13 13:27:35.169  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.169  3914  3961 I jxcore-log: 
,09-13 13:27:35.169  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.169  3914  3961 I jxcore-log: 
09-13 13:27:35.169  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.169  3914  3961 I jxcore-log: 
09-13 13:27:35.170  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.170  3914  3961 I jxcore-log: 
,09-13 13:27:35.170  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.170  3914  3961 I jxcore-log: 
,09-13 13:27:35.284  3914  3961 I jxcore-log: # teardown
09-13 13:27:35.284  3914  3961 I jxcore-log: 
,09-13 13:27:35.489  3914  3961 I jxcore-log: # setup
09-13 13:27:35.489  3914  3961 I jxcore-log: 
,09-13 13:27:35.685  3914  3961 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
09-13 13:27:35.685  3914  3961 I jxcore-log: 
,09-13 13:27:35.753  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:35.753  3914  3961 I jxcore-log: 
,09-13 13:27:35.759  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 44634
09-13 13:27:35.759  3914  3961 I jxcore-log: 
,09-13 13:27:35.768  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:35.768  3914  3961 I jxcore-log: 
,09-13 13:27:35.770  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:35.770  3914  3961 I jxcore-log: 
,09-13 13:27:35.771  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:35.771  3914  3961 I jxcore-log: 
,09-13 13:27:35.778  3914  3961 I jxcore-log: ok 31 we should not have gotten an error
09-13 13:27:35.778  3914  3961 I jxcore-log: 
,09-13 13:27:35.785  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:35.785  3914  3961 I jxcore-log: 
,09-13 13:27:35.788  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:35.788  3914  3961 I jxcore-log: 
,09-13 13:27:35.795  3914  3961 I jxcore-log: ok 32 Buffers are identical
09-13 13:27:35.795  3914  3961 I jxcore-log: 
,09-13 13:27:35.796  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:35.796  3914  3961 I jxcore-log: 
,09-13 13:27:35.798  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:35.798  3914  3961 I jxcore-log: 
,09-13 13:27:35.815  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:35.815  3914  3961 I jxcore-log: 
,09-13 13:27:35.816  3914  3961 I jxcore-log: ok 33 server should be fine
09-13 13:27:35.816  3914  3961 I jxcore-log: 
,09-13 13:27:35.817  3914  3961 I jxcore-log: ok 34 server should be open
09-13 13:27:35.817  3914  3961 I jxcore-log: 
09-13 13:27:35.817  3914  3961 I jxcore-log: ok 35 incoming has been removed
09-13 13:27:35.817  3914  3961 I jxcore-log: 
09-13 13:27:35.817  3914  3961 I jxcore-log: ok 36 The mux object should be closed
09-13 13:27:35.817  3914  3961 I jxcore-log: 
09-13 13:27:35.818  3914  3961 I jxcore-log: ok 37 The mux stream should be closed
09-13 13:27:35.818  3914  3961 I jxcore-log: 
,09-13 13:27:35.822  3914  3961 I jxcore-log: # teardown
09-13 13:27:35.822  3914  3961 I jxcore-log: 
,09-13 13:27:35.926  3914  3961 I jxcore-log: # setup
09-13 13:27:35.926  3914  3961 I jxcore-log: 
,09-13 13:27:36.010  3914  3961 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
09-13 13:27:36.010  3914  3961 I jxcore-log: 
,09-13 13:27:36.105  3914  3961 I jxcore-log: DEBUG createNativeListener: creating native server
09-13 13:27:36.105  3914  3961 I jxcore-log: 
,09-13 13:27:36.112  3914  3961 I jxcore-log: DEBUG createNativeListener: listening 38967
09-13 13:27:36.112  3914  3961 I jxcore-log: 
,09-13 13:27:36.123  3914  3961 I jxcore-log: DEBUG createNativeListener: new incoming socket
09-13 13:27:36.123  3914  3961 I jxcore-log: 
,09-13 13:27:36.126  3914  3961 I jxcore-log: DEBUG createNativeListener: creating incoming mux
09-13 13:27:36.126  3914  3961 I jxcore-log: 
,09-13 13:27:36.128  3914  3961 I jxcore-log: DEBUG createNativeListener: new mux
09-13 13:27:36.128  3914  3961 I jxcore-log: 
,09-13 13:27:36.134  3914  3961 I jxcore-log: ok 38 we should not have gotten an error
09-13 13:27:36.134  3914  3961 I jxcore-log: 
,09-13 13:27:36.140  3914  3961 I jxcore-log: DEBUG createNativeListener: new stream: 
09-13 13:27:36.140  3914  3961 I jxcore-log: 
,09-13 13:27:36.143  3914  3961 I jxcore-log: DEBUG createNativeListener: new outgoing socket
09-13 13:27:36.143  3914  3961 I jxcore-log: 
,09-13 13:27:36.150  3914  3961 I jxcore-log: ok 39 Buffers are identical
09-13 13:27:36.150  3914  3961 I jxcore-log: 
,09-13 13:27:36.155  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
09-13 13:27:36.155  3914  3961 I jxcore-log: 
,09-13 13:27:36.156  3914  3961 I jxcore-log: DEBUG createNativeListener: stream close:
09-13 13:27:36.156  3914  3961 I jxcore-log: 
,09-13 13:27:36.158  3914  3961 I jxcore-log: DEBUG createNativeListener: mux close
09-13 13:27:36.158  3914  3961 I jxcore-log: 
,09-13 13:27:36.163  3914  3961 I jxcore-log: DEBUG createNativeListener: incoming socket close
09-13 13:27:36.163  3914  3961 I jxcore-log: 
,09-13 13:27:36.164  3914  3961 I jxcore-log: ok 40 server should be fine
09-13 13:27:36.164  3914  3961 I jxcore-log: 
,09-13 13:27:36.165  3914  3961 I jxcore-log: ok 41 server should be open
09-13 13:27:36.165  3914  3961 I jxcore-log: 
,09-13 13:27:36.165  3914  3961 I jxcore-log: ok 42 incoming has been removed
09-13 13:27:36.165  3914  3961 I jxcore-log: 
,09-13 13:27:36.166  3914  3961 I jxcore-log: ok 43 The mux object should be closed
09-13 13:27:36.166  3914  3961 I jxcore-log: 
,09-13 13:27:36.166  3914  3961 I jxcore-log: ok 44 The mux stream should be closed
09-13 13:27:36.166  3914  3961 I jxcore-log: 
,09-13 13:27:36.173  3914  3961 I jxcore-log: # teardown
09-13 13:27:36.173  3914  3961 I jxcore-log: 
,09-13 13:27:36.268  3914  3961 I jxcore-log: # setup
09-13 13:27:36.268  3914  3961 I jxcore-log: 
,09-13 13:27:36.350  3914  3961 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
09-13 13:27:36.350  3914  3961 I jxcore-log: 
,09-13 13:27:36.507  3914  3961 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
09-13 13:27:36.507  3914  3961 I jxcore-log: 
,09-13 13:27:36.508  3914  3961 I jxcore-log: ok 45 Got right error
09-13 13:27:36.508  3914  3961 I jxcore-log: 
,09-13 13:27:36.513  3914  3961 I jxcore-log: # teardown
09-13 13:27:36.513  3914  3961 I jxcore-log: 
,09-13 13:27:36.647  3914  3961 I jxcore-log: # setup
09-13 13:27:36.647  3914  3961 I jxcore-log: 
,09-13 13:27:36.706  3914  3961 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
09-13 13:27:36.706  3914  3961 I jxcore-log: 
,09-13 13:27:36.843  3914  3961 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
09-13 13:27:36.843  3914  3961 I jxcore-log: 
,09-13 13:27:36.844  3914  3961 I jxcore-log: ok 46 Got socket hang up
09-13 13:27:36.844  3914  3961 I jxcore-log: 
,09-13 13:27:36.848  3914  3961 I jxcore-log: # teardown
09-13 13:27:36.848  3914  3961 I jxcore-log: 
,09-13 13:27:36.945  3914  3961 I jxcore-log: # setup
09-13 13:27:36.945  3914  3961 I jxcore-log: 
,09-13 13:27:37.062  3914  3961 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
09-13 13:27:37.062  3914  3961 I jxcore-log: 
,09-13 13:27:37.284  3914  3961 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq []
09-13 13:27:37.284  3914  3961 I jxcore-log: ,
09-13 13:27:37.285  3914  3961 I jxcore-log: ok 47 Got 500 as expected
09-13 13:27:37.285  3914  3961 I jxcore-log: 
,09-13 13:27:37.287  3914  3961 I jxcore-log: # teardown
09-13 13:27:37.287  3914  3961 I jxcore-log: 
,09-13 13:27:37.705  3914  3961 I jxcore-log: # setup
09-13 13:27:37.705  3914  3961 I jxcore-log: 
,09-13 13:27:37.771  3914  3961 I jxcore-log: # 15. #_doImmediateSeqUpdate - create new seq doc
09-13 13:27:37.771  3914  3961 I jxcore-log: 
,09-13 13:27:40.879  3914  3961 I jxcore-log: ok 48 should be equal
09-13 13:27:40.879  3914  3961 I jxcore-log: 
,09-13 13:27:40.880  3914  3961 I jxcore-log: ok 49 revs are equal
09-13 13:27:40.880  3914  3961 I jxcore-log: 
,09-13 13:27:40.884  3914  3961 I jxcore-log: # teardown
09-13 13:27:40.884  3914  3961 I jxcore-log: 
,09-13 13:27:54.112  1520  2214 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-13 13:29:04.496  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:29:04.498  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:29:04.523  1520  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:29:04.523  1520  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:29:04.523  1520  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:29:04.523  1520  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:29:04.538  3643  4464 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-13 13:29:04.538  3643  4464 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at blb.a(PG:3937)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at czp.a(PG:18188)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:29:04.538  3643  4464 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	... 12 more
09-13 13:29:04.538  3643  4464 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at fal.a(PG:38)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:29:04.538  3643  4464 E HttpOperation: 	... 14 more
,09-13 13:29:04.607  1520  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-13 13:29:04.607  1520  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-13 13:29:04.607  1520  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:29:04.608  1520  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:29:04.628  3643  4464 E HttpOperation: [getmobileexperiments] Unexpected exception
09-13 13:29:04.628  3643  4464 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at jdm.a(PG:82)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at jcs.o(PG:406)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at jcn.a(PG:1379)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at jcs.i(PG:143)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at hec.a(PG:42)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at hee.a(PG:102)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at czr.a(PG:65)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at kka.a(PG:108)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at czp.a(PG:19176)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at czp.a(PG:9081)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at czq.run(PG:1686)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:29:04.628  3643  4464 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at jdj.a(PG:4091)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at jdj.a(PG:1125)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at jdm.a(PG:77)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	... 15 more
09-13 13:29:04.628  3643  4464 E HttpOperation: Caused by: faj: BadAuthentication
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at fal.a(PG:38)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	at jdj.a(PG:4089)
09-13 13:29:04.628  3643  4464 E HttpOperation: 	... 17 more
,09-13 13:29:04.628  3643  4464 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-13 13:29:04.628  3643  4464 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at jdm.a(PG:82)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at jcs.o(PG:406)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at jcn.a(PG:1379)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at jcs.i(PG:143)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at hec.a(PG:42)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at hee.a(PG:102)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at czr.a(PG:65)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at kka.a(PG:108)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at czp.a(PG:19176)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at czp.a(PG:9081)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at czq.run(PG:1686)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at jdj.a(PG:4091)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at jdj.a(PG:1125)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at jdm.a(PG:77)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	... 15 more
09-13 13:29:04.628  3643  4464 E ExperimentLoader: Caused by: faj: BadAuthentication
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at fal.a(PG:38)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	at jdj.a(PG:4089)
09-13 13:29:04.628  3643  4464 E ExperimentLoader: 	... 17 more
,09-13 13:29:04.744   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 563205, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:29:38.005  3717  4468 I BooksSync: Starting books sync for 61035162, extras: ade
,09-13 13:29:38.053  3717  4469 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-13 13:29:38.080  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:29:38.086  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:29:38.122  1520  2101 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
09-13 13:29:38.123  1520  2101 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-13 13:29:38.123  1520  2101 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:29:38.123  1520  2101 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:29:38.152  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-13 13:29:38.153  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-13 13:29:38.183  1520  2299 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-13 13:29:38.183  1520  2299 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-13 13:29:38.183  1520  2299 I GLSUser : [GLSUser] Extracting token using key: Auth
09-13 13:29:38.183  1520  2299 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-13 13:29:38.204  3717  4469 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-13 13:29:38.205  3717  4468 E BooksSync: Soft error
09-13 13:29:38.205  3717  4468 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:29:38.205  3717  4468 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-13 13:29:38.205  3717  4468 E BooksSync: Sync error
09-13 13:29:38.205  3717  4468 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-13 13:29:38.205  3717  4468 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-13 13:29:38.205  3717  4468 I BooksSync: Finished books sync
,09-13 13:29:38.220   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 596904, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-13 13:31:34.460   872   872 I ActivityManager: Start proc 4485:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,09-13 13:31:34.532  4485  4485 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,09-13 13:31:34.561  4485  4485 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
09-13 13:31:34.561  4485  4485 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-13 13:31:34.561  4485  4485 I GAv4    :   adb logcat -s GAv4
,09-13 13:31:34.578  4485  4485 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-13 13:31:34.584  4485  4485 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-13 13:31:34.597  4485  4500 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-13 13:31:34.704   872  1389 I ActivityManager: Killing 3842:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-13 13:34:34.739   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=893704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:34:46.618   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=905583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:34:49.925   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=908890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:35:11.671   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=930637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:35:14.985   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=933950, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:35:36.738   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=955703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:35:40.045   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=959010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:36:01.792   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=980757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:36:05.105   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=984070, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:36:26.859   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1005824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:36:30.165   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1009131, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:36:51.925   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1030890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:36:55.231   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1034196, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:37:16.992   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1055957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:37:20.952   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1059917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:37:42.712   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1081677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:37:46.538   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1085503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:38:08.285   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1107250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:38:11.625   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1110590, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:38:33.378   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1132343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:38:36.685   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1135650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:38:58.446   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1157411, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:39:01.751   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1160717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:39:23.512   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1182477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:39:37.085   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1196050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:39:48.565   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1207531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:39:59.152   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,09-13 13:40:02.152   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1221117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:40:13.631   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1232597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:40:27.858   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1246823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:40:39.352   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1258317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:40:52.925   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1271890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:41:04.458   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1283424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:41:17.992   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1296957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:41:29.538   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1308503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:41:43.112   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1322077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:41:54.605   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1333571, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:42:08.179   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1347144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:42:19.658   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1358623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:42:33.245   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1372210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:42:44.712   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1383677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:42:58.285   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1397250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:43:09.805   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1408770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:43:23.378   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1422343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:43:34.871   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1433837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:43:48.445   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1447410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:43:51.470  1743  4537 I EventLogService: Opted in for usage reporting
,09-13 13:43:51.471  1743  4537 I EventLogService: Aggregate from 1473765231252 (log), 1473765231252 (data)
,09-13 13:43:51.528  1743  4537 W EventLogAggregator: Unknown tag: snet_gcore
09-13 13:43:51.528  1743  4537 W EventLogAggregator: Unknown tag: snet_launch_service
,09-13 13:43:51.680  1743  4537 I ServiceDumpSys: dumping service [account]
,09-13 13:43:56.432   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1455397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:44:13.512   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1472477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:44:24.992   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1483957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:44:41.698   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1500664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-13 13:44:50.058   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1509023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-13 13:45:06.792   872  4368 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1525757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),09-13 13:45:13.406  4541  4541 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-13 13:45:13.411  4541  4541 D AndroidRuntime: CheckJNI is OFF
09-13 13:45:13.453  4541  4541 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-13 13:45:13.496  4541  4541 I Radio-JNI: register_android_hardware_Radio DONE
09-13 13:45:13.520  4541  4541 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-13 13:45:13.529   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-13 13:45:13.530   872   885 I ActivityManager: Killing 3914:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-13 13:45:13.681   872  1314 D WifiService: Client connection lost with reason: 4
09-13 13:45:13.683   872  1988 D GraphicsStats: Buffer count: 2
09-13 13:45:13.684   872  1679 I WindowState: WIN DEATH: Window{f3b0381 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 13:45:13.702   872   895 W PackageSettings: Skipping PackageSetting{59aeadf com.example.hello/10273} due to missing metadata
09-13 13:45:13.751   872   885 E libprocessgroup: failed to kill 1 processes for processgroup 3914
09-13 13:45:13.756   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-13 13:45:13.757   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-13 13:45:13.757   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-13 13:45:13.757   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-13 13:45:13.757   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:45:13.757   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:13.757   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 13:45:13.757   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 13:45:13.758   872   885 I ActivityManager:   Force finishing activity ActivityRecord{5cf03ee u0 com.test.thalitest/.MainActivity t4}
09-13 13:45:13.762   872   895 I art     : Starting a blocking GC Explicit
09-13 13:45:13.769   872  1913 W ActivityManager: Spurious death for ProcessRecord{cc9bf35 0:com.test.thalitest/u0a0}, curProc for 3914: null
09-13 13:45:13.816   872   895 I art     : Explicit concurrent mark sweep GC freed 15035(1088KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.198ms total 53.862ms
09-13 13:45:13.861   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-13 13:45:13.868  4541  4541 I art     : System.exit called, status: 0
09-13 13:45:13.868  4541  4541 I AndroidRuntime: VM exiting with result code 0.
09-13 13:45:13.870   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-13 13:45:13.896   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-13 13:45:13.905   872  1303 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 13:45:13.907  1878  1878 I Keyboard.Facilitator: resetDictionaries() : en_US
09-13 13:45:13.909  4311  4311 D BluetoothMapAppObserver: onReceive
09-13 13:45:13.909  4311  4311 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-13 13:45:13.914  2182  2308 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 13:45:13.916  3782  3782 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-13 13:45:13.933  1878  4553 I Keyboard.Facilitator.DecoderInitializer: run()
09-13 13:45:13.949  1878  4553 I Decoder : createOrResetDecoder
09-13 13:45:13.970  1949  1949 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-13 13:45:13.984   872  1988 I ActivityManager: Start proc 4556:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-13 13:45:13.992  1520  1520 I ConfigService: onCreate
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-13 13:45:14.011  1520  4568 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-13 13:45:14.012  1520  4568 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-13 13:45:14.015  1520  4568 W SQLiteOpenHelper: Opened config.db in read-only mode
09-13 13:45:14.029  1878  4553 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-13 13:45:14.034   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 13:45:14.043  4556  4556 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-13 13:45:14.049   872  2097 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3914 uid 10000
09-13 13:45:14.050  1878  1878 I Keyboard.Facilitator: onFinishInput()
09-13 13:45:14.054  1965  2060 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-13 13:45:14.054   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-13 13:45:14.055   872   884 E PackageManager: Failed to write settings, restoring backup
09-13 13:45:14.055   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-13 13:45:14.055   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-13 13:45:14.055   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-13 13:45:14.055   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-13 13:45:14.055   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-13 13:45:14.055   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:45:14.055   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.055   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 13:45:14.059   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-13 13:45:14.059   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 13:45:14.059   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 13:45:14.059   872   885 E DropBoxManagerService: 	... 13 more
09-13 13:45:14.068   872  1912 I ActivityManager: Start proc 4570:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-13 13:45:14.069  1965  2060 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-13 13:45:14.069  1965  2060 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1965
09-13 13:45:14.069  1965  2060 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.069  1965  2060 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 13:45:14.070  1878  4553 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-13 13:45:14.072   872  2098 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 13:45:14.072   872  4576 E DropBoxManagerService: Can't write: system_app_crash
09-13 13:45:14.072   872  4576 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 13:45:14.072   872  4576 E DropBoxManagerService: 	... 5 more
09-13 13:45:14.076  1965  2060 I Process : Sending signal. PID: 1965 SIG: 9
09-13 13:45:14.080  1878  4553 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-13 13:45:14.080  1878  4553 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-13 13:45:14.093  1878  4553 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-13 13:45:14.093  1878  4553 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-13 13:45:14.094  1878  4553 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-13 13:45:14.094  1878  4553 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-13 13:45:14.095  1878  4553 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-13 13:45:14.095  1878  4553 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-13 13:45:14.095  1878  4553 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-13 13:45:14.095  1878  4553 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-13 13:45:14.095  1878  4553 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-13 13:45:14.095  1878  4553 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-13 13:45:14.125  4556  4556 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-13 13:45:14.138  4556  4587 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-13 13:45:14.142   872  2100 I ActivityManager: Start proc 4588:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-13 13:45:14.159   872  1389 D GraphicsStats: Buffer count: 1
09-13 13:45:14.159   872   882 I WindowState: WIN DEATH: Window{796d16a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-13 13:45:14.171   872  1679 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1965) has died
09-13 13:45:14.172   872  1679 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-13 13:45:14.173   872  1679 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.179  4556  4584 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.187  4556  4584 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 13:45:14.192   872   885 I ActivityManager: Start proc 4600:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 13:45:14.219  4588  4588 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:45:14.246  4600  4600 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 13:45:14.247  4600  4600 D AndroidRuntime: Shutting down VM
09-13 13:45:14.252  1520  1520 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-13 13:45:14.252  1520  1520 D AndroidRuntime: Shutting down VM
09-13 13:45:14.253  1520  1520 E AndroidRuntime: FATAL EXCEPTION: main
09-13 13:45:14.253  1520  1520 E AndroidRuntime: Process: com.google.process.gapps, PID: 1520
09-13 13:45:14.253  1520  1520 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-13 13:45:14.253  1520  1520 E AndroidRuntime: 	... 8 more
09-13 13:45:14.255  1743  4613 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-13 13:45:14.257  1743  4613 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-13 13:45:14.259  4600  4600 E AndroidRuntime: FATAL EXCEPTION: main
09-13 13:45:14.259  4600  4600 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4600
09-13 13:45:14.259  4600  4600 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-13 13:45:14.259  4600  4600 E AndroidRuntime: 	... 10 more
09-13 13:45:14.263  1520  1520 I Process : Sending signal. PID: 1520 SIG: 9
09-13 13:45:14.265   872   885 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2600)
09-13 13:45:14.267   872   885 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
09-13 13:45:14.267   872   885 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-13 13:45:14.267   872   885 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-13 13:45:14.267   872   885 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-13 13:45:14.267   872   885 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-13 13:45:14.267   872   885 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-13 13:45:14.267   872   885 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-13 13:45:14.267   872   885 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
09-13 13:45:14.267   872   885 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:45:14.267   872   885 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.267   872   885 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 13:45:14.267   872   885 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: Can't write: system_app_crash
09-13 13:45:14.273   872  4616 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 13:45:14.273   872  4616 E DropBoxManagerService: 	... 5 more
09-13 13:45:14.287  4556  4584 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.291  4556  4587 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-13 13:45:14.292  4556  4587 E AndroidRuntime: Process: android.process.acore, PID: 4556
09-13 13:45:14.292  4556  4587 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-13 13:45:14.292  4556  4587 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-13 13:45:14.292  4556  4584 I Process : Sending signal. PID: 4556 SIG: 9
09-13 13:45:14.295   872  1314 D WifiService: Client connection lost with reason: 4
09-13 13:45:14.301   872   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-13 13:45:14.301   872   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
09-13 13:45:14.301   872   885 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
09-13 13:45:14.313   872   885 I ActivityManager: Start proc 4618:com.google.process.gapps/u0a11 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
09-13 13:45:14.314   872   883 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-13 13:45:14.316   872  4623 E DropBoxManagerService: Can't write: system_app_crash
09-13 13:45:14.316   872  4623 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 13:45:14.316   872  4623 E DropBoxManagerService: 	... 5 more
09-13 13:45:14.317   872  2097 W ActivityManager: Spurious death for ProcessRecord{61df08 4618:com.google.process.gapps/u0a11}, curProc for 1520: null
09-13 13:45:14.318   279   279 E lowmemorykiller: Error writing /proc/4556/oom_score_adj; errno=22
09-13 13:45:14.318  4600  4600 I Process : Sending signal. PID: 4600 SIG: 9
09-13 13:45:14.321   872  4629 E DropBoxManagerService: Can't write: system_app_crash
09-13 13:45:14.321   872  4629 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-13 13:45:14.321   872  4629 E DropBoxManagerService: 	... 5 more
09-13 13:45:14.323   872  1679 I ActivityManager: Killing 2042:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
09-13 13:45:14.332  1743  1743 W RocketImpressions: ClearcutLogger connection suspended: 1
09-13 13:45:14.329  1743  4613 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-13 13:45:14.333  1743  4613 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-13 13:45:14.355   872  1314 D WifiService: Client connection lost with reason: 4
09-13 13:45:14.363   872  1989 I ActivityManager: Process android.process.acore (pid 4556) has died
09-13 13:45:14.363   872  1989 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30938ms
09-13 13:45:14.364   872  1913 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4600) has died
09-13 13:45:14.367   872  1913 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0

```
