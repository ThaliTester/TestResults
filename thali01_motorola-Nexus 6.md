#### Test 7975101513b55b4_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-12 11:25:38.743   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
08-12 11:25:39.580  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 11:25:39.593  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 11:25:39.599  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-12 11:25:39.651  1513  2346 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 11:25:39.652  1513  2346 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 11:25:39.652  1513  2346 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:25:39.653  1513  2346 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 11:25:39.694  3498  3498 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-12 11:25:39.695  3498  3498 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 11:25:39.696  3498  3498 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-12 11:25:40.399  3760  3760 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 11:25:40.406  3760  3760 D AndroidRuntime: CheckJNI is OFF
08-12 11:25:40.443  3760  3760 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 11:25:40.483  3760  3760 I Radio-JNI: register_android_hardware_Radio DONE
08-12 11:25:40.503  3760  3760 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 11:25:40.507   871   882 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 11:25:40.551  1985  2393 W SearchService: Abort, client detached.
08-12 11:25:40.561  1985  1985 I HotwordDetector: Closing mic
08-12 11:25:40.562  1985  2345 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@f21cca8
08-12 11:25:40.562  1985  2355 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 11:25:40.568  3760  3760 D AndroidRuntime: Shutting down VM
08-12 11:25:40.588   871   881 I ActivityManager: Start proc 3769:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 11:25:40.616   375  2357 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 11:25:40.618   375  2357 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 11:25:40.634   375  1283 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 11:25:40.637  1985  2354 I MicroRecognitionRnrImpl: Detection finished
08-12 11:25:40.638  1985  2349 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 11:25:40.674  3769  3769 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 11:25:40.697  3769  3769 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 11:25:40.713  3769  3769 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 3720-3728)
08-12 11:25:40.713  3769  3769 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 11:25:40.747  3769  3769 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d66d98c}
08-12 11:25:40.751  3769  3769 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 11:25:40.751  3769  3769 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 11:25:40.762  3769  3769 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 11:25:40.765  3769  3769 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 11:25:40.793  3769  3769 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-12 11:25:40.802  3769  3769 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 11:25:40.803  3769  3769 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-12 11:25:40.803  3769  3769 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 11:25:40.803  3769  3769 I Adreno  : Build Date                       : 10/20/15
08-12 11:25:40.803  3769  3769 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 11:25:40.803  3769  3769 I Adreno  : Local Branch                     : M14
08-12 11:25:40.803  3769  3769 I Adreno  : Remote Branch                    : 
08-12 11:25:40.803  3769  3769 I Adreno  : Remote Branch                    : 
08-12 11:25:40.803  3769  3769 I Adreno  : Reconstruct Branch               : 
,08-12 11:25:40.886   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cc94fb:true
,08-12 11:25:40.914  3769  3769 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 11:25:40.929  3769  3769 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-12 11:25:40.967   871  1313 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 11:25:40.986  3769  3807 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 11:25:40.995  3769  3794 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-12 11:25:41.039  3769  3807 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 11:25:41.120   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +550ms
,08-12 11:25:41.122  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-12 11:25:41.186  3769  3769 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3769
,08-12 11:25:41.301  3769  3769 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 11:25:41.414   871  1971 I ActivityManager: Killing 3198:com.google.android.gm/u0a78 (adj 15): empty #17
,08-12 11:25:41.462   871  1971 I ActivityManager: Killing 3089:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-12 11:25:41.559  3769  3810 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1696728784
,08-12 11:25:41.579  3769  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 11:25:41.579  3769  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 11:25:41.579  3769  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 11:25:41.579  3769  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 11:25:41.579  3769  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 11:25:41.580  3769  3810 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2636550 added. We now have 1 listener(s)
,08-12 11:25:41.592  3769  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-12 11:25:41.595  3769  3810 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 11:25:41.596  3769  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 11:25:41.596  3769  3810 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 11:25:41.606  3769  3810 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc1896f added. We now have 1 listener(s)
,08-12 11:25:41.606  3769  3810 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 11:25:41.609   871  1314 D WifiService: New client listening to asynchronous messages
,08-12 11:25:41.610  3769  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 11:25:41.611  3769  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 11:25:41.611  3769  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-12 11:25:41.611  3769  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-12 11:25:41.611  3769  3810 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 11:25:41.614  3769  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 11:25:41.614  3769  3810 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-12 11:25:41.619  3769  3810 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 11:25:41.619  3769  3810 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:25:41.619  3769  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:25:41.619  3769  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 11:25:41.619  3769  3810 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:25:41.619  3769  3810 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:25:41.619  3769  3810 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:25:41.619  3769  3810 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:25:41.619  3769  3810 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 11:25:41.620  3769  3810 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-12 11:25:41.620  3769  3810 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 11:25:41.620  3769  3810 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 11:25:41.725  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:25:41.730  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:25:41.731  3769  3769 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 11:25:42.700  3769  3819 W jxcore-log: Initializing JXcore engine
,08-12 11:25:42.701  3769  3819 W jxcore-log: JXcore engine is ready
,08-12 11:25:42.757  3819  3819 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8941 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 11:25:42.760  3819  3819 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11943]" dev="sockfs" ino=11943 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 11:25:42.779  3769  3819 W jxcore-log: Starting JXcore engine
,08-12 11:25:42.760  3819  3819 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 11:25:42.760  3819  3819 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26751]" dev="sockfs" ino=26751 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 11:25:42.888  3769  3819 W jxcore-log: Platform android
08-12 11:25:42.888  3769  3819 W jxcore-log: 
,08-12 11:25:42.889  3769  3819 W jxcore-log: Process ARCH arm
08-12 11:25:42.889  3769  3819 W jxcore-log: 
,08-12 11:25:43.113  3769  3819 I jxcore-log: JXcore Cordova bridge is ready!
08-12 11:25:43.113  3769  3819 I jxcore-log: 
,08-12 11:25:43.113  3769  3819 W jxcore-log: JXcore engine is started
,08-12 11:25:43.120  3769  3810 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 11:25:43.125  3769  3769 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 11:25:44.073  3043  3821 V KeepSync: Connecting to GoogleApiClient
08-12 11:25:44.073   871   881 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 11:25:44.167  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 11:25:44.168  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 11:25:44.168  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 11:25:44.169  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:25:44.187  1728  3822 V BaseAuthAsyncOperation: access token request failed
,08-12 11:25:44.188  3043  3821 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 11:25:44.257  1513  2346 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 11:25:44.258  1513  2346 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-12 11:25:44.258  1513  2346 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 11:25:44.258  1513  2346 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:25:44.290  3043  3821 E KeepSync: IOException
08-12 11:25:44.290  3043  3821 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 11:25:44.290  3043  3821 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 11:25:44.290  3043  3821 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 11:25:44.290  3043  3821 E KeepSync: 	... 10 more
,08-12 11:25:44.290  3043  3821 W KeepSync: Sync result 2
,08-12 11:25:44.302   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126979, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:25:59.080  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 11:25:59.080  3769  3819 I jxcore-log: 
,08-12 11:25:59.083  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 11:25:59.083  3769  3819 I jxcore-log: 
,08-12 11:25:59.093  3769  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:25:59.093  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:25:59.093  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 11:25:59.093  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:25:59.093  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:25:59.093  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:25:59.093  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:25:59.093  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 11:25:59.097  3769  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 11:25:59.099  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 11:25:59.099  3769  3819 I jxcore-log: 
,08-12 11:25:59.101  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 11:25:59.101  3769  3819 I jxcore-log: 
,08-12 11:25:59.438  3769  3819 I jxcore-log: Unit Test app is loaded
08-12 11:25:59.438  3769  3819 I jxcore-log: 
,08-12 11:25:59.445  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 11:25:59.445  3769  3819 I jxcore-log: 
,08-12 11:25:59.448  3769  3819 I jxcore-log: My device name is: motorola-Nexus 6
08-12 11:25:59.448  3769  3819 I jxcore-log: 
,08-12 11:25:59.450  3769  3819 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 11:25:59.450  3769  3819 I jxcore-log: 
,08-12 11:25:59.465  3769  3769 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 11:26:01.763  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 11:26:01.763  3769  3819 I jxcore-log: 
,08-12 11:26:02.356  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 11:26:02.356  3769  3819 I jxcore-log: 
,08-12 11:26:02.380  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 11:26:02.380  3769  3819 I jxcore-log: 
,08-12 11:26:03.728  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 11:26:03.728  3769  3819 I jxcore-log: 
,08-12 11:26:03.950  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 11:26:03.950  3769  3819 I jxcore-log: 
,08-12 11:26:03.956  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 11:26:03.956  3769  3819 I jxcore-log: 
,08-12 11:26:03.962  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 11:26:03.962  3769  3819 I jxcore-log: 
,08-12 11:26:03.978  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 11:26:03.978  3769  3819 I jxcore-log: 
,08-12 11:26:03.982  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 11:26:03.982  3769  3819 I jxcore-log: 
,08-12 11:26:04.645  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 11:26:04.645  3769  3819 I jxcore-log: 
,08-12 11:26:04.657  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 11:26:04.657  3769  3819 I jxcore-log: 
,08-12 11:26:04.666  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 11:26:04.666  3769  3819 I jxcore-log: 
,08-12 11:26:04.673  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 11:26:04.673  3769  3819 I jxcore-log: 
,08-12 11:26:04.722  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 11:26:04.722  3769  3819 I jxcore-log: 
,08-12 11:26:04.777  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 11:26:04.777  3769  3819 I jxcore-log: 
,08-12 11:26:04.784  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 11:26:04.784  3769  3819 I jxcore-log: 
,08-12 11:26:04.949  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 11:26:04.949  3769  3819 I jxcore-log: 
,08-12 11:26:04.977  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 11:26:04.977  3769  3819 I jxcore-log: 
,08-12 11:26:04.982  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 11:26:04.982  3769  3819 I jxcore-log: 
,08-12 11:26:04.988  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 11:26:04.988  3769  3819 I jxcore-log: 
,08-12 11:26:05.006  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 11:26:05.006  3769  3819 I jxcore-log: 
,08-12 11:26:05.089  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 11:26:05.089  3769  3819 I jxcore-log: 
,08-12 11:26:05.102  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 11:26:05.102  3769  3819 I jxcore-log: 
,08-12 11:26:05.130  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 11:26:05.130  3769  3819 I jxcore-log: 
,08-12 11:26:05.142  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 11:26:05.142  3769  3819 I jxcore-log: 
,08-12 11:26:05.161  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 11:26:05.161  3769  3819 I jxcore-log: 
,08-12 11:26:05.197  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 11:26:05.197  3769  3819 I jxcore-log: 
,08-12 11:26:05.203  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 11:26:05.203  3769  3819 I jxcore-log: 
,08-12 11:26:05.407  3769  3819 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 11:26:05.407  3769  3819 I jxcore-log: 
,08-12 11:26:05.419  3769  3819 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 11:26:05.420  3769  3819 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 11:26:05.420  3769  3819 I jxcore-log: 
,08-12 11:26:07.071   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-12 11:26:07.084  1863  1863 I Keyboard.Facilitator: onFinishInput()
,08-12 11:26:07.088   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 11:26:07.088   871   891 I Adreno  : Build Date                       : 10/20/15
08-12 11:26:07.088   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 11:26:07.088   871   891 I Adreno  : Local Branch                     : M14
08-12 11:26:07.088   871   891 I Adreno  : Remote Branch                    : 
08-12 11:26:07.088   871   891 I Adreno  : Remote Branch                    : 
08-12 11:26:07.088   871   891 I Adreno  : Reconstruct Branch               : 
,08-12 11:26:07.117   281  1980 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (186 us)
,08-12 11:26:07.779  3769  3769 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-12 11:26:07.779  3769  3769 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-12 11:26:07.818   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-12 11:26:07.819  3769  3769 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@164b42 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@4b36699, 16908290=android.view.AbsSavedState$1@4b36699}, android:focusedViewId=100}]}]
08-12 11:26:07.819  3769  3769 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-12 11:26:07.821  3769  3769 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-12 11:26:07.822  3769  3769 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-12 11:26:07.826   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-12 11:26:07.830   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-12 11:26:07.895   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
08-12 11:26:07.895   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-12 11:26:08.158   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 11:26:08.162   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-12 11:26:08.167   871  1340 D SurfaceControl: Excessive delay in setPowerMode(): 337ms
,08-12 11:26:08.173   871   891 I DreamManagerService: Entering dreamland.
,08-12 11:26:08.175   871   891 I PowerManagerService: Dozing...
,08-12 11:26:08.177   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-12 11:26:08.230   375  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-12 11:26:08.230   375  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-12 11:26:08.247   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 11:26:08.250  1904  3837 D NfcService: Discovery configuration equal, not updating.
,08-12 11:26:08.264   871  1313 E native  : do suspend false
,08-12 11:26:08.284   871  1313 D WifiConfigStore: No blacklist allowed without epno enabled
,08-12 11:26:08.299   871  1313 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 11:26:08.304   871  1313 E native  : do suspend true
,08-12 11:26:08.361   375  1284 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-12 11:26:08.361   375  1284 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-12 11:26:08.755   871  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-12 11:26:10.476   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 11:26:12.470  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:12.490  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:12.498  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:12.589  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 11:26:12.590  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 11:26:12.590  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:26:12.591  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:26:12.654  3498  3498 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 11:26:12.656  3498  3498 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 11:26:12.658  3498  3498 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-12 11:26:13.383  2039  2658 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 11:26:14.719  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-12 11:26:14.720  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 11:26:14.720  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:26:14.720  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:26:14.767  3537  3843 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 11:26:14.767  3537  3843 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at jdm.a(PG:82)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at jcs.o(PG:406)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at jcn.a(PG:1379)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at jcs.i(PG:143)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at blb.a(PG:3937)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at czp.a(PG:18188)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at czp.a(PG:9081)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at czq.run(PG:1686)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:26:14.767  3537  3843 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at jdj.a(PG:4091)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at jdj.a(PG:1125)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at jdm.a(PG:77)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	... 12 more
08-12 11:26:14.767  3537  3843 E HttpOperation: Caused by: faj: BadAuthentication
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at fal.a(PG:38)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	at jdj.a(PG:4089)
08-12 11:26:14.767  3537  3843 E HttpOperation: 	... 14 more
,08-12 11:26:14.870  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 11:26:14.870  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 11:26:14.870  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:26:14.871  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:26:14.941  3537  3843 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 11:26:14.941  3537  3843 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at jdm.a(PG:82)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at jcs.o(PG:406)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at jcn.a(PG:1379)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at jcs.i(PG:143)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at hec.a(PG:42)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at hee.a(PG:102)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at czr.a(PG:65)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at kka.a(PG:108)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at czp.a(PG:19176)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at czp.a(PG:9081)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at czq.run(PG:1686)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:26:14.941  3537  3843 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at jdj.a(PG:4091)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at jdj.a(PG:1125)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at jdm.a(PG:77)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	... 15 more
08-12 11:26:14.941  3537  3843 E HttpOperation: Caused by: faj: BadAuthentication
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at fal.a(PG:38)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	at jdj.a(PG:4089)
08-12 11:26:14.941  3537  3843 E HttpOperation: 	... 17 more
08-12 11:26:14.943  3537  3843 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 11:26:14.943  3537  3843 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at hec.a(PG:42)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at hee.a(PG:102)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at czr.a(PG:65)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at kka.a(PG:108)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	... 15 more
08-12 11:26:14.943  3537  3843 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at fal.a(PG:38)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 11:26:14.943  3537  3843 E ExperimentLoader: 	... 17 more
,08-12 11:26:15.136   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 128083, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:26:20.984   871  1313 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-12 11:26:38.533  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:38.738  1513  1513 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 11:26:38.802  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:38.823  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:38.825  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:38.928  1513  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 11:26:38.928  1513  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 11:26:38.928  1513  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:26:38.929  1513  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:26:38.957  3498  3498 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-12 11:26:38.958  3498  3498 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 11:26:38.958  3498  3498 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-12 11:26:39.263  1513  3854 I VacuumService: Vacuum at: now=1470993999262 tag=VacuumService
,08-12 11:26:39.332  1513  3846 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-12 11:26:40.554  1513  2147 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 11:26:45.219  3722  3856 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 11:26:45.263  3722  3857 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 11:26:45.284  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:45.288  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:45.326  1513  2346 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 11:26:45.326  1513  2346 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 11:26:45.326  1513  2346 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 11:26:45.326  1513  2346 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:26:45.366  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:45.368  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:45.401  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 11:26:45.402  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 11:26:45.402  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 11:26:45.402  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:26:45.423  3722  3857 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 11:26:45.424  3722  3856 E BooksSync: Soft error
08-12 11:26:45.424  3722  3856 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 11:26:45.424  3722  3856 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 11:26:45.424  3722  3856 E BooksSync: Sync error
08-12 11:26:45.424  3722  3856 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 11:26:45.424  3722  3856 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 11:26:45.426  3722  3856 I BooksSync: Finished books sync
,08-12 11:26:45.439   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 162880, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:26:59.256  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:59.270  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:59.276  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:26:59.356  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 11:26:59.357  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 11:26:59.358  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 11:26:59.358  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:26:59.432  3498  3498 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 11:26:59.434  3498  3498 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 11:26:59.435  3498  3498 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-12 11:27:07.125  1863  1953 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-12 11:27:07.125  1863  1953 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-12 11:27:07.160  1513  1513 I ConfigService: onCreate
,08-12 11:27:12.209  1513  1513 I ConfigService: onDestroy
,08-12 11:27:18.263   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=221277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:27:23.516   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=226530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 11:27:46.782  3043  3861 V KeepSync: Connecting to GoogleApiClient
,08-12 11:27:46.782   871   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 11:27:46.844  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:27:46.847  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:27:46.879  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-12 11:27:46.880  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-12 11:27:46.880  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:27:46.880  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:27:46.909  1728  3862 V BaseAuthAsyncOperation: access token request failed
08-12 11:27:46.910  3043  3861 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 11:27:46.989  1513  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 11:27:46.989  1513  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-12 11:27:46.989  1513  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 11:27:46.989  1513  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:27:47.020  3043  3861 E KeepSync: IOException
08-12 11:27:47.020  3043  3861 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 11:27:47.020  3043  3861 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 11:27:47.020  3043  3861 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 11:27:47.020  3043  3861 E KeepSync: 	... 10 more
,08-12 11:27:47.020  3043  3861 W KeepSync: Sync result 2
,08-12 11:27:47.025   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 249602, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:28:02.636   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=265650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:28:08.983   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=271997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 11:28:19.618  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:28:19.623  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:28:19.657  1513  3752 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 11:28:19.658  1513  3752 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 11:28:19.658  1513  3752 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 11:28:19.658  1513  3752 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:28:19.681  3537  3865 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 11:28:19.681  3537  3865 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at jdm.a(PG:82)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at jcs.o(PG:406)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at jcn.a(PG:1379)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at jcs.i(PG:143)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at blb.a(PG:3937)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at czp.a(PG:18188)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at czp.a(PG:9081)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at czq.run(PG:1686)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:28:19.681  3537  3865 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at jdj.a(PG:4091)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at jdj.a(PG:1125)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at jdm.a(PG:77)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	... 12 more
08-12 11:28:19.681  3537  3865 E HttpOperation: Caused by: faj: BadAuthentication
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at fal.a(PG:38)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	at jdj.a(PG:4089)
08-12 11:28:19.681  3537  3865 E HttpOperation: 	... 14 more
,08-12 11:28:19.735  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 11:28:19.735  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 11:28:19.735  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 11:28:19.735  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:28:19.775  3537  3865 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 11:28:19.775  3537  3865 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at jdm.a(PG:82)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at jcs.o(PG:406)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at jcn.a(PG:1379)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at jcs.i(PG:143)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at hec.a(PG:42)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at hee.a(PG:102)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at czr.a(PG:65)
08-12 11:28:19.775  3537  3865 E HttpOperation: ,	at kka.a(PG:108)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at czp.a(PG:19176)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at czp.a(PG:9081)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at czq.run(PG:1686)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:28:19.775  3537  3865 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at jdj.a(PG:4091)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at jdj.a(PG:1125)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at jdm.a(PG:77)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	... 15 more
08-12 11:28:19.775  3537  3865 E HttpOperation: Caused by: faj: BadAuthentication
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at fal.a(PG:38)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	at jdj.a(PG:4089)
08-12 11:28:19.775  3537  3865 E HttpOperation: 	... 17 more
08-12 11:28:19.776  3537  3865 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 11:28:19.776  3537  3865 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at hec.a(PG:42)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at hee.a(PG:102)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at czr.a(PG:65)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at kka.a(PG:108)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	... 15 more
08-12 11:28:19.776  3537  3865 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at fal.a(PG:38)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 11:28:19.776  3537  3865 E ExperimentLoader: 	... 17 more
,08-12 11:28:19.916   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 282303, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:28:48.076   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=311090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:28:54.502   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=317517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 11:28:57.478  3722  3880 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 11:28:57.509  3722  3881 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 11:28:57.533  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:28:57.535  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:28:57.563  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-12 11:28:57.563  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 11:28:57.563  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:28:57.563  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:28:57.591  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:28:57.593  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:28:57.620  1513  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 11:28:57.620  1513  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 11:28:57.620  1513  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 11:28:57.620  1513  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:28:57.639  3722  3881 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 11:28:57.640  3722  3880 E BooksSync: Soft error
08-12 11:28:57.640  3722  3880 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 11:28:57.640  3722  3880 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 11:28:57.640  3722  3880 E BooksSync: Sync error
08-12 11:28:57.640  3722  3880 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 11:28:57.640  3722  3880 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 11:28:57.640  3722  3880 I BooksSync: Finished books sync
,08-12 11:28:57.649   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 320419, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:29:19.847  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:29:19.862  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:29:19.863  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:29:19.927  1513  1524 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-12 11:29:19.928  1513  1524 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 11:29:19.928  1513  1524 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:29:19.929  1513  1524 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:29:19.972  1513  1524 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 11:29:19.972  1513  1524 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 11:29:19.972  1513  1524 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 11:29:19.972  1513  1524 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-12 11:29:19.972  1513  1524 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-12 11:29:19.972  1513  1524 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-12 11:29:19.972  1513  1524 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 11:29:19.988  3498  3529 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 11:29:19.988  3498  3529 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-12 11:29:19.988  3498  3529 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-12 11:29:19.988  3498  3529 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-12 11:29:19.988  3498  3529 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-12 11:29:19.988  3498  3529 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-12 11:29:19.988  3498  3529 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 11:29:25.648  3769  3819 I jxcore-log: TAP version 13
08-12 11:29:25.648  3769  3819 I jxcore-log: 
,08-12 11:29:25.659  3769  3819 I jxcore-log: # setup
08-12 11:29:25.659  3769  3819 I jxcore-log: 
,08-12 11:29:25.758  3769  3819 I jxcore-log: # 1. calling createNativeListener directly rejects
08-12 11:29:25.758  3769  3819 I jxcore-log: 
,08-12 11:29:25.856  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:25.856  3769  3819 I jxcore-log: 
,08-12 11:29:25.859  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 46762
08-12 11:29:25.859  3769  3819 I jxcore-log: 
,08-12 11:29:25.866  3769  3819 I jxcore-log: ok 1 Should throw
08-12 11:29:25.866  3769  3819 I jxcore-log: 
,08-12 11:29:25.868  3769  3819 I jxcore-log: # teardown
08-12 11:29:25.868  3769  3819 I jxcore-log: 
,08-12 11:29:25.935  3769  3819 I jxcore-log: # setup
08-12 11:29:25.935  3769  3819 I jxcore-log: 
,08-12 11:29:25.987  3769  3819 I jxcore-log: # 2. emits incomingConnectionState
08-12 11:29:25.987  3769  3819 I jxcore-log: 
,08-12 11:29:26.034  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:26.034  3769  3819 I jxcore-log: 
,08-12 11:29:26.043  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 38911
08-12 11:29:26.043  3769  3819 I jxcore-log: 
,08-12 11:29:26.056  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:26.056  3769  3819 I jxcore-log: 
,08-12 11:29:26.059  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:26.059  3769  3819 I jxcore-log: 
,08-12 11:29:26.069  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:26.069  3769  3819 I jxcore-log: 
,08-12 11:29:26.075  3769  3819 I jxcore-log: ok 2 initial connection state should be CONNECTED
08-12 11:29:26.075  3769  3819 I jxcore-log: 
,08-12 11:29:26.097  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:26.097  3769  3819 I jxcore-log: 
,08-12 11:29:26.099  3769  3819 I jxcore-log: ok 3 final connection state should be DISCONNECTED
08-12 11:29:26.099  3769  3819 I jxcore-log: 
,08-12 11:29:26.105  3769  3819 I jxcore-log: # teardown
08-12 11:29:26.105  3769  3819 I jxcore-log: 
,08-12 11:29:26.150  3769  3819 I jxcore-log: # setup
08-12 11:29:26.150  3769  3819 I jxcore-log: 
,08-12 11:29:26.215  3769  3819 I jxcore-log: # 3. emits routerPortConnectionFailed
08-12 11:29:26.215  3769  3819 I jxcore-log: 
,08-12 11:29:26.273  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:26.273  3769  3819 I jxcore-log: 
,08-12 11:29:26.276  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 48242
08-12 11:29:26.276  3769  3819 I jxcore-log: 
,08-12 11:29:26.282  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:26.282  3769  3819 I jxcore-log: 
,08-12 11:29:26.284  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:26.284  3769  3819 I jxcore-log: 
,08-12 11:29:26.286  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:26.286  3769  3819 I jxcore-log: 
,08-12 11:29:26.316  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:26.316  3769  3819 I jxcore-log: 
,08-12 11:29:26.319  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:26.319  3769  3819 I jxcore-log: 
,08-12 11:29:26.323  3769  3819 I jxcore-log: DEBUG createNativeListener: 
08-12 11:29:26.323  3769  3819 I jxcore-log: 
,08-12 11:29:26.324  3769  3819 I jxcore-log: ok 4 tried to connect to right port
08-12 11:29:26.324  3769  3819 I jxcore-log: 
08-12 11:29:26.325  3769  3819 I jxcore-log: ok 5 failed due to refused connection
08-12 11:29:26.325  3769  3819 I jxcore-log: 
,08-12 11:29:26.325  3769  3819 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
08-12 11:29:26.325  3769  3819 I jxcore-log: 
,08-12 11:29:26.328  3769  3819 I jxcore-log: # teardown
08-12 11:29:26.328  3769  3819 I jxcore-log: 
,08-12 11:29:26.329  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:26.329  3769  3819 I jxcore-log: 
,08-12 11:29:26.399  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:26.399  3769  3819 I jxcore-log: 
,08-12 11:29:26.406  3769  3819 I jxcore-log: # setup
08-12 11:29:26.406  3769  3819 I jxcore-log: 
,08-12 11:29:26.408  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:26.408  3769  3819 I jxcore-log: 
,08-12 11:29:26.471  3769  3819 I jxcore-log: # 4. native server connections all up
08-12 11:29:26.471  3769  3819 I jxcore-log: 
,08-12 11:29:26.553  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:26.553  3769  3819 I jxcore-log: 
,08-12 11:29:26.563  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 46540
08-12 11:29:26.563  3769  3819 I jxcore-log: 
,08-12 11:29:26.570  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:26.570  3769  3819 I jxcore-log: 
,08-12 11:29:26.571  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:26.571  3769  3819 I jxcore-log: 
,08-12 11:29:26.573  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:26.573  3769  3819 I jxcore-log: 
,08-12 11:29:26.612  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:26.612  3769  3819 I jxcore-log: 
,08-12 11:29:26.615  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:26.615  3769  3819 I jxcore-log: 
,08-12 11:29:26.617  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:26.617  3769  3819 I jxcore-log: 
,08-12 11:29:26.619  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:26.619  3769  3819 I jxcore-log: 
,08-12 11:29:26.638  3769  3819 I jxcore-log: ok 7 Send/recvd #1 should be equal length
08-12 11:29:26.638  3769  3819 I jxcore-log: 
,08-12 11:29:26.639  3769  3819 I jxcore-log: ok 8 Send/recvd #1 should be same
08-12 11:29:26.639  3769  3819 I jxcore-log: 
,08-12 11:29:26.641  3769  3819 I jxcore-log: ok 9 Send/recvd #2 should be equal length
08-12 11:29:26.641  3769  3819 I jxcore-log: 
08-12 11:29:26.641  3769  3819 I jxcore-log: ok 10 Send/recvd #2 should be same
08-12 11:29:26.641  3769  3819 I jxcore-log: 
,08-12 11:29:26.644  3769  3819 I jxcore-log: ok 11 Should be exactly 2 client sockets
08-12 11:29:26.644  3769  3819 I jxcore-log: 
,08-12 11:29:26.649  3769  3819 I jxcore-log: # teardown
08-12 11:29:26.649  3769  3819 I jxcore-log: 
,08-12 11:29:26.716  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:26.716  3769  3819 I jxcore-log: 
,08-12 11:29:26.718  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:26.718  3769  3819 I jxcore-log: 
,08-12 11:29:26.720  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:26.720  3769  3819 I jxcore-log: 
,08-12 11:29:26.722  3769  3819 I jxcore-log: # setup
08-12 11:29:26.722  3769  3819 I jxcore-log: 
,08-12 11:29:26.723  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:26.723  3769  3819 I jxcore-log: 
,08-12 11:29:26.769  3769  3819 I jxcore-log: # 5. native server - closing incoming stream cleans outgoing socket
08-12 11:29:26.769  3769  3819 I jxcore-log: 
,08-12 11:29:26.820  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:26.820  3769  3819 I jxcore-log: 
,08-12 11:29:26.822  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 37859
08-12 11:29:26.822  3769  3819 I jxcore-log: 
,08-12 11:29:26.827  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:26.827  3769  3819 I jxcore-log: 
,08-12 11:29:26.828  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:26.828  3769  3819 I jxcore-log: 
,08-12 11:29:26.829  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:26.829  3769  3819 I jxcore-log: 
,08-12 11:29:26.840  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:26.840  3769  3819 I jxcore-log: 
,08-12 11:29:26.842  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:26.842  3769  3819 I jxcore-log: 
,08-12 11:29:26.851  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:,
08-12 11:29:26.851  3769  3819 I jxcore-log: 
,08-12 11:29:26.862  3769  3819 I jxcore-log: ok 12 socket shouldn't close until after stream,
08-12 11:29:26.862  3769  3819 I jxcore-log: 
08-12 11:29:26.862  3769  3819 I jxcore-log: ok 13 incoming remains open
08-12 11:29:26.862  3769  3819 I jxcore-log: 
,08-12 11:29:26.864  3769  3819 I jxcore-log: # teardown
08-12 11:29:26.864  3769  3819 I jxcore-log: 
,08-12 11:29:27.012  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:27.012  3769  3819 I jxcore-log: 
,08-12 11:29:27.020  3769  3819 I jxcore-log: # setup
08-12 11:29:27.020  3769  3819 I jxcore-log: 
,08-12 11:29:27.022  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:27.022  3769  3819 I jxcore-log: 
,08-12 11:29:27.075  3769  3819 I jxcore-log: # 6. native server - closing incoming connection cleans outgoing socket
08-12 11:29:27.075  3769  3819 I jxcore-log: 
,08-12 11:29:27.124  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:27.124  3769  3819 I jxcore-log: 
,08-12 11:29:27.127  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 37564
08-12 11:29:27.127  3769  3819 I jxcore-log: 
,08-12 11:29:27.134  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:27.134  3769  3819 I jxcore-log: 
,08-12 11:29:27.136  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:27.136  3769  3819 I jxcore-log: 
,08-12 11:29:27.138  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:27.138  3769  3819 I jxcore-log: 
,08-12 11:29:27.151  3769  3819 I jxcore-log: ok 14 we should not have gotten an error
08-12 11:29:27.151  3769  3819 I jxcore-log: 
,08-12 11:29:27.160  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:27.160  3769  3819 I jxcore-log: 
,08-12 11:29:27.163  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:27.163  3769  3819 I jxcore-log: 
,08-12 11:29:27.173  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:27.173  3769  3819 I jxcore-log: 
,08-12 11:29:27.176  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:27.176  3769  3819 I jxcore-log: 
,08-12 11:29:27.185  3769  3819 I jxcore-log: ok 15 socket shouldn't close until after incoming
08-12 11:29:27.185  3769  3819 I jxcore-log: 
,08-12 11:29:27.186  3769  3819 I jxcore-log: ok 16 incoming is cleaned up
08-12 11:29:27.186  3769  3819 I jxcore-log: 
,08-12 11:29:27.189  3769  3819 I jxcore-log: # teardown
08-12 11:29:27.189  3769  3819 I jxcore-log: 
,08-12 11:29:27.267  3769  3819 I jxcore-log: # setup
08-12 11:29:27.267  3769  3819 I jxcore-log: 
,08-12 11:29:27.340  3769  3819 I jxcore-log: # 7. native server - closing outgoing socket cleans associated mux stream
08-12 11:29:27.340  3769  3819 I jxcore-log: 
,08-12 11:29:27.384  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:27.384  3769  3819 I jxcore-log: 
,08-12 11:29:27.391  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 46481
08-12 11:29:27.391  3769  3819 I jxcore-log: 
,08-12 11:29:27.400  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:27.400  3769  3819 I jxcore-log: 
,08-12 11:29:27.402  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:27.402  3769  3819 I jxcore-log: 
,08-12 11:29:27.404  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:27.404  3769  3819 I jxcore-log: 
,08-12 11:29:27.419  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:27.419  3769  3819 I jxcore-log: 
,08-12 11:29:27.422  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:27.422  3769  3819 I jxcore-log: 
,08-12 11:29:27.439  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:27.439  3769  3819 I jxcore-log: 
,08-12 11:29:27.448  3769  3819 I jxcore-log: ok 17 stream was closed
08-12 11:29:27.448  3769  3819 I jxcore-log: 
,08-12 11:29:27.449  3769  3819 I jxcore-log: ok 18 incoming should survive
08-12 11:29:27.449  3769  3819 I jxcore-log: 
,08-12 11:29:27.449  3769  3819 I jxcore-log: ok 19 mux should have no streams
08-12 11:29:27.449  3769  3819 I jxcore-log: 
,08-12 11:29:27.454  3769  3819 I jxcore-log: # teardown
08-12 11:29:27.454  3769  3819 I jxcore-log: 
,08-12 11:29:27.547  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:27.547  3769  3819 I jxcore-log: 
,08-12 11:29:27.560  3769  3819 I jxcore-log: # setup
08-12 11:29:27.560  3769  3819 I jxcore-log: 
,08-12 11:29:27.561  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:27.561  3769  3819 I jxcore-log: 
,08-12 11:29:27.628  3769  3819 I jxcore-log: # 8. native server - closing the whole server cleans everything up
08-12 11:29:27.628  3769  3819 I jxcore-log: 
,08-12 11:29:27.723  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:27.723  3769  3819 I jxcore-log: 
,08-12 11:29:27.733  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 48058
08-12 11:29:27.733  3769  3819 I jxcore-log: 
,08-12 11:29:27.742  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:27.742  3769  3819 I jxcore-log: 
,08-12 11:29:27.743  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:27.743  3769  3819 I jxcore-log: 
,08-12 11:29:27.745  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:27.745  3769  3819 I jxcore-log: 
,08-12 11:29:27.755  3769  3819 I jxcore-log: ok 20 we should not have gotten an error
08-12 11:29:27.755  3769  3819 I jxcore-log: 
,08-12 11:29:27.764  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:27.764  3769  3819 I jxcore-log: 
,08-12 11:29:27.767  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:27.767  3769  3819 I jxcore-log: 
,08-12 11:29:27.777  3769  3819 I jxcore-log: ok 21 Buffers are identical
08-12 11:29:27.777  3769  3819 I jxcore-log: 
,08-12 11:29:27.779  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:27.779  3769  3819 I jxcore-log: 
,08-12 11:29:27.782  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:27.782  3769  3819 I jxcore-log: 
,08-12 11:29:27.784  3769  3819 I jxcore-log: ok 22 native server is nulled out
08-12 11:29:27.784  3769  3819 I jxcore-log: 
,08-12 11:29:27.785  3769  3819 I jxcore-log: ok 23 native server should be closed
08-12 11:29:27.785  3769  3819 I jxcore-log: 
08-12 11:29:27.785  3769  3819 I jxcore-log: ok 24 incoming has been removed
08-12 11:29:27.785  3769  3819 I jxcore-log: 
08-12 11:29:27.785  3769  3819 I jxcore-log: ok 25 Incoming should be done
08-12 11:29:27.785  3769  3819 I jxcore-log: 
08-12 11:29:27.786  3769  3819 I jxcore-log: ok 26 The mux object should be closed
08-12 11:29:27.786  3769  3819 I jxcore-log: 
08-12 11:29:27.786  3769  3819 I jxcore-log: ok 27 The mux stream should be closed
08-12 11:29:27.786  3769  3819 I jxcore-log: 
08-12 11:29:27.787  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:27.787  3769  3819 I jxcore-log: 
,08-12 11:29:27.800  3769  3819 I jxcore-log: # teardown
08-12 11:29:27.800  3769  3819 I jxcore-log: 
,08-12 11:29:27.904  3769  3819 I jxcore-log: # setup
08-12 11:29:27.904  3769  3819 I jxcore-log: ,
,08-12 11:29:27.953  3769  3819 I jxcore-log: # 9. native server - we can get a ton of connections and data through and still clean up the server completely
08-12 11:29:27.953  3769  3819 I jxcore-log: 
,08-12 11:29:28.061  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:28.061  3769  3819 I jxcore-log: 
,08-12 11:29:28.069  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 39657
08-12 11:29:28.069  3769  3819 I jxcore-log: 
,08-12 11:29:28.096  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:28.096  3769  3819 I jxcore-log: 
,08-12 11:29:28.097  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:28.097  3769  3819 I jxcore-log: 
,08-12 11:29:28.098  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:28.098  3769  3819 I jxcore-log: 
,08-12 11:29:28.102  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:28.102  3769  3819 I jxcore-log: 
,08-12 11:29:28.103  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:28.103  3769  3819 I jxcore-log: 
,08-12 11:29:28.104  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:28.104  3769  3819 I jxcore-log: 
,08-12 11:29:28.107  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:28.107  3769  3819 I jxcore-log: 
,08-12 11:29:28.107  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:28.107  3769  3819 I jxcore-log: 
,08-12 11:29:28.109  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:28.109  3769  3819 I jxcore-log: 
,08-12 11:29:28.112  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:28.112  3769  3819 I jxcore-log: 
,08-12 11:29:28.113  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:28.113  3769  3819 I jxcore-log: 
08-12 11:29:28.115  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:28.115  3769  3819 I jxcore-log: 
,08-12 11:29:28.118  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:28.118  3769  3819 I jxcore-log: 
,08-12 11:29:28.119  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:28.119  3769  3819 I jxcore-log: 
,08-12 11:29:28.120  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:28.120  3769  3819 I jxcore-log: 
,08-12 11:29:28.122  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:28.122  3769  3819 I jxcore-log: 
,08-12 11:29:28.122  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:28.122  3769  3819 I jxcore-log: 
08-12 11:29:28.123  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:28.123  3769  3819 I jxcore-log: 
,08-12 11:29:28.129  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:28.129  3769  3819 I jxcore-log: 
,08-12 11:29:28.130  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:28.130  3769  3819 I jxcore-log: 
,08-12 11:29:28.132  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:28.132  3769  3819 I jxcore-log: 
,08-12 11:29:28.136  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:28.136  3769  3819 I jxcore-log: 
,08-12 11:29:28.136  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:28.136  3769  3819 I jxcore-log: 
08-12 11:29:28.137  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:28.137  3769  3819 I jxcore-log: 
,08-12 11:29:28.139  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:28.139  3769  3819 I jxcore-log: 
,08-12 11:29:28.139  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:28.139  3769  3819 I jxcore-log: 
,08-12 11:29:28.140  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:28.140  3769  3819 I jxcore-log: 
,08-12 11:29:28.142  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:28.142  3769  3819 I jxcore-log: 
,08-12 11:29:28.142  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:28.142  3769  3819 I jxcore-log: 
08-12 11:29:28.143  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:28.143  3769  3819 I jxcore-log: 
,08-12 11:29:28.231  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.231  3769  3819 I jxcore-log: 
,08-12 11:29:28.233  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.233  3769  3819 I jxcore-log: 
,08-12 11:29:28.235  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.235  3769  3819 I jxcore-log: 
,08-12 11:29:28.237  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.237  3769  3819 I jxcore-log: 
,08-12 11:29:28.238  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.238  3769  3819 I jxcore-log: 
,08-12 11:29:28.240  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.240  3769  3819 I jxcore-log: 
,08-12 11:29:28.242  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.242  3769  3819 I jxcore-log: 
,08-12 11:29:28.244  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.244  3769  3819 I jxcore-log: 
08-12 11:29:28.246  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.246  3769  3819 I jxcore-log: 
,08-12 11:29:28.248  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.248  3769  3819 I jxcore-log: 
,08-12 11:29:28.249  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.249  3769  3819 I jxcore-log: 
,08-12 11:29:28.251  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.251  3769  3819 I jxcore-log: 
08-12 11:29:28.252  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.252  3769  3819 I jxcore-log: 
08-12 11:29:28.254  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.254  3769  3819 I jxcore-log: 
,08-12 11:29:28.255  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.255  3769  3819 I jxcore-log: 
08-12 11:29:28.256  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.256  3769  3819 I jxcore-log: 
,08-12 11:29:28.261  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.261  3769  3819 I jxcore-log: 
,08-12 11:29:28.263  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.263  3769  3819 I jxcore-log: 
,08-12 11:29:28.265  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.265  3769  3819 I jxcore-log: 
,08-12 11:29:28.266  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.266  3769  3819 I jxcore-log: 
,08-12 11:29:28.268  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.268  3769  3819 I jxcore-log: 
,08-12 11:29:28.269  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.269  3769  3819 I jxcore-log: 
,08-12 11:29:28.270  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.270  3769  3819 I jxcore-log: 
,08-12 11:29:28.272  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.272  3769  3819 I jxcore-log: 
,08-12 11:29:28.274  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.274  3769  3819 I jxcore-log: 
,08-12 11:29:28.278  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.278  3769  3819 I jxcore-log: 
,08-12 11:29:28.279  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.279  3769  3819 I jxcore-log: 
,08-12 11:29:28.281  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.281  3769  3819 I jxcore-log: 
08-12 11:29:28.282  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.282  3769  3819 I jxcore-log: 
,08-12 11:29:28.284  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.284  3769  3819 I jxcore-log: 
,08-12 11:29:28.286  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.286  3769  3819 I jxcore-log: 
,08-12 11:29:28.287  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.287  3769  3819 I jxcore-log: 
,08-12 11:29:28.289  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.289  3769  3819 I jxcore-log: 
,08-12 11:29:28.291  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.291  3769  3819 I jxcore-log: 
,08-12 11:29:28.292  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.292  3769  3819 I jxcore-log: 
,08-12 11:29:28.294  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.294  3769  3819 I jxcore-log: 
08-12 11:29:28.295  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.295  3769  3819 I jxcore-log: 
,08-12 11:29:28.297  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.297  3769  3819 I jxcore-log: 
,08-12 11:29:28.304  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.304  3769  3819 I jxcore-log: 
,08-12 11:29:28.306  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.306  3769  3819 I jxcore-log: 
,08-12 11:29:28.308  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.308  3769  3819 I jxcore-log: 
,08-12 11:29:28.309  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.309  3769  3819 I jxcore-log: 
08-12 11:29:28.310  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.310  3769  3819 I jxcore-log: 
,08-12 11:29:28.312  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.312  3769  3819 I jxcore-log: 
08-12 11:29:28.313  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.313  3769  3819 I jxcore-log: 
,08-12 11:29:28.314  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.314  3769  3819 I jxcore-log: 
,08-12 11:29:28.315  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.315  3769  3819 I jxcore-log: 
,08-12 11:29:28.317  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.317  3769  3819 I jxcore-log: 
,08-12 11:29:28.319  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.319  3769  3819 I jxcore-log: 
,08-12 11:29:28.320  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.320  3769  3819 I jxcore-log: 
08-12 11:29:28.321  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.321  3769  3819 I jxcore-log: 
,08-12 11:29:28.323  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.323  3769  3819 I jxcore-log: 
08-12 11:29:28.324  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.324  3769  3819 I jxcore-log: 
,08-12 11:29:28.325  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.325  3769  3819 I jxcore-log: 
,08-12 11:29:28.326  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.326  3769  3819 I jxcore-log: 
,08-12 11:29:28.328  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.328  3769  3819 I jxcore-log: 
,08-12 11:29:28.334  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
,08-12 11:29:28.334  3769  3819 I jxcore-log: 
,08-12 11:29:28.335  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.335  3769  3819 I jxcore-log: 
,08-12 11:29:28.336  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.336  3769  3819 I jxcore-log: 
,08-12 11:29:28.338  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.338  3769  3819 I jxcore-log: 
,08-12 11:29:28.339  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.339  3769  3819 I jxcore-log: 
,08-12 11:29:28.340  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.340  3769  3819 I jxcore-log: 
08-12 11:29:28.341  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.341  3769  3819 I jxcore-log: 
,08-12 11:29:28.343  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.343  3769  3819 I jxcore-log: 
,08-12 11:29:28.344  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.344  3769  3819 I jxcore-log: 
,08-12 11:29:28.346  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.346  3769  3819 I jxcore-log: 
,08-12 11:29:28.347  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.347  3769  3819 I jxcore-log: 
,08-12 11:29:28.348  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.348  3769  3819 I jxcore-log: 
08-12 11:29:28.349  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.349  3769  3819 I jxcore-log: 
,08-12 11:29:28.351  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.351  3769  3819 I jxcore-log: 
,08-12 11:29:28.352  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.352  3769  3819 I jxcore-log: 
,08-12 11:29:28.353  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.353  3769  3819 I jxcore-log: 
,08-12 11:29:28.355  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.355  3769  3819 I jxcore-log: 
,08-12 11:29:28.357  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.357  3769  3819 I jxcore-log: 
08-12 11:29:28.358  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.358  3769  3819 I jxcore-log: 
,08-12 11:29:28.359  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.359  3769  3819 I jxcore-log: 
,08-12 11:29:28.360  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.360  3769  3819 I jxcore-log: 
,08-12 11:29:28.362  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.362  3769  3819 I jxcore-log: 
08-12 11:29:28.363  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:28.363  3769  3819 I jxcore-log: 
08-12 11:29:28.364  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:28.364  3769  3819 I jxcore-log: 
,08-12 11:29:28.437  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.437  3769  3819 I jxcore-log: 
,08-12 11:29:28.440  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.440  3769  3819 I jxcore-log: 
,08-12 11:29:28.441  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.441  3769  3819 I jxcore-log: 
,08-12 11:29:28.443  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.443  3769  3819 I jxcore-log: 
,08-12 11:29:28.444  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:28.444  3769  3819 I jxcore-log: 
,08-12 11:29:28.446  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.446  3769  3819 I jxcore-log: 
,08-12 11:29:28.447  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.447  3769  3819 I jxcore-log: 
08-12 11:29:28.448  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.448  3769  3819 I jxcore-log: 
08-12 11:29:28.449  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.449  3769  3819 I jxcore-log: 
,08-12 11:29:28.450  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:28.450  3769  3819 I jxcore-log: 
08-12 11:29:28.451  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.451  3769  3819 I jxcore-log: 
,08-12 11:29:28.454  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.454  3769  3819 I jxcore-log: 
,08-12 11:29:28.455  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.455  3769  3819 I jxcore-log: 
,08-12 11:29:28.457  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.457  3769  3819 I jxcore-log: 
08-12 11:29:28.458  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:28.458  3769  3819 I jxcore-log: 
,08-12 11:29:28.463  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.463  3769  3819 I jxcore-log: 
,08-12 11:29:28.464  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.464  3769  3819 I jxcore-log: 
,08-12 11:29:28.465  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.465  3769  3819 I jxcore-log: 
,08-12 11:29:28.467  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.467  3769  3819 I jxcore-log: 
08-12 11:29:28.468  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:28.468  3769  3819 I jxcore-log: 
08-12 11:29:28.469  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.469  3769  3819 I jxcore-log: 
,08-12 11:29:28.470  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.470  3769  3819 I jxcore-log: 
,08-12 11:29:28.471  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.471  3769  3819 I jxcore-log: 
,08-12 11:29:28.472  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.472  3769  3819 I jxcore-log: 
,08-12 11:29:28.474  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:28.474  3769  3819 I jxcore-log: 
08-12 11:29:28.475  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.475  3769  3819 I jxcore-log: 
08-12 11:29:28.476  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.476  3769  3819 I jxcore-log: 
,08-12 11:29:28.477  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.477  3769  3819 I jxcore-log: 
08-12 11:29:28.478  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.478  3769  3819 I jxcore-log: 
08-12 11:29:28.479  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:28.479  3769  3819 I jxcore-log: 
,08-12 11:29:28.481  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.481  3769  3819 I jxcore-log: 
08-12 11:29:28.482  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.482  3769  3819 I jxcore-log: 
,08-12 11:29:28.483  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.483  3769  3819 I jxcore-log: 
,08-12 11:29:28.484  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.484  3769  3819 I jxcore-log: 
08-12 11:29:28.485  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:28.485  3769  3819 I jxcore-log: 
,08-12 11:29:28.486  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.486  3769  3819 I jxcore-log: 
,08-12 11:29:28.487  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.487  3769  3819 I jxcore-log: 
,08-12 11:29:28.488  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.488  3769  3819 I jxcore-log: 
,08-12 11:29:28.493  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.493  3769  3819 I jxcore-log: 
08-12 11:29:28.494  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:28.494  3769  3819 I jxcore-log: 
,08-12 11:29:28.495  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.495  3769  3819 I jxcore-log: 
,08-12 11:29:28.496  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.496  3769  3819 I jxcore-log: 
08-12 11:29:28.497  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.497  3769  3819 I jxcore-log: 
,08-12 11:29:28.498  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.498  3769  3819 I jxcore-log: 
,08-12 11:29:28.499  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:28.499  3769  3819 I jxcore-log: 
08-12 11:29:28.501  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.501  3769  3819 I jxcore-log: 
08-12 11:29:28.502  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.502  3769  3819 I jxcore-log: 
,08-12 11:29:28.503  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.503  3769  3819 I jxcore-log: 
08-12 11:29:28.504  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:28.504  3769  3819 I jxcore-log: 
,08-12 11:29:28.505  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:28.505  3769  3819 I jxcore-log: 
,08-12 11:29:28.508  3769  3819 I jxcore-log: ok 28 native server is nulled out
08-12 11:29:28.508  3769  3819 I jxcore-log: 
08-12 11:29:28.509  3769  3819 I jxcore-log: ok 29 native server should be closed
08-12 11:29:28.509  3769  3819 I jxcore-log: 
08-12 11:29:28.509  3769  3819 I jxcore-log: ok 30 incoming has been removed
08-12 11:29:28.509  3769  3819 I jxcore-log: 
,08-12 11:29:28.510  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:28.510  3769  3819 I jxcore-log: 
08-12 11:29:28.511  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:28.511  3769  3819 I jxcore-log: 
,08-12 11:29:28.512  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:28.512  3769  3819 I jxcore-log: 
08-12 11:29:28.512  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:28.512  3769  3819 I jxcore-log: 
08-12 11:29:28.513  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:28.513  3769  3819 I jxcore-log: 
,08-12 11:29:28.513  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:28.513  3769  3819 I jxcore-log: 
08-12 11:29:28.514  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:28.514  3769  3819 I jxcore-log: 
08-12 11:29:28.514  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:28.514  3769  3819 I jxcore-log: 
,08-12 11:29:28.514  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:28.514  3769  3819 I jxcore-log: 
08-12 11:29:28.515  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:28.515  3769  3819 I jxcore-log: 
,08-12 11:29:28.629  3769  3819 I jxcore-log: # teardown
08-12 11:29:28.629  3769  3819 I jxcore-log: 
,08-12 11:29:28.774  3769  3819 I jxcore-log: # setup
08-12 11:29:28.774  3769  3819 I jxcore-log: 
,08-12 11:29:30.190  3769  3819 I jxcore-log: # 10. native server - simulate mux failure, make sure everything is cleaned up
08-12 11:29:30.190  3769  3819 I jxcore-log: 
,08-12 11:29:30.256  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:30.256  3769  3819 I jxcore-log: 
,08-12 11:29:30.259  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 48409
08-12 11:29:30.259  3769  3819 I jxcore-log: 
,08-12 11:29:30.265  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:30.265  3769  3819 I jxcore-log: 
,08-12 11:29:30.267  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:30.267  3769  3819 I jxcore-log: 
,08-12 11:29:30.268  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:30.268  3769  3819 I jxcore-log: 
,08-12 11:29:30.275  3769  3819 I jxcore-log: ok 31 we should not have gotten an error
08-12 11:29:30.275  3769  3819 I jxcore-log: 
,08-12 11:29:30.282  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:30.282  3769  3819 I jxcore-log: 
,08-12 11:29:30.285  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:30.285  3769  3819 I jxcore-log: 
,08-12 11:29:30.292  3769  3819 I jxcore-log: ok 32 Buffers are identical
08-12 11:29:30.292  3769  3819 I jxcore-log: 
,08-12 11:29:30.294  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
08-12 11:29:30.294  3769  3819 I jxcore-log: 
,08-12 11:29:30.296  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:30.296  3769  3819 I jxcore-log: 
,08-12 11:29:30.313  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:30.313  3769  3819 I jxcore-log: 
,08-12 11:29:30.314  3769  3819 I jxcore-log: ok 33 server should be fine
08-12 11:29:30.314  3769  3819 I jxcore-log: 
,08-12 11:29:30.314  3769  3819 I jxcore-log: ok 34 server should be open
08-12 11:29:30.314  3769  3819 I jxcore-log: 
08-12 11:29:30.315  3769  3819 I jxcore-log: ok 35 incoming has been removed
08-12 11:29:30.315  3769  3819 I jxcore-log: 
08-12 11:29:30.315  3769  3819 I jxcore-log: ok 36 The mux object should be closed
08-12 11:29:30.315  3769  3819 I jxcore-log: 
,08-12 11:29:30.316  3769  3819 I jxcore-log: ok 37 The mux stream should be closed
08-12 11:29:30.316  3769  3819 I jxcore-log: 
,08-12 11:29:30.320  3769  3819 I jxcore-log: # teardown,
08-12 11:29:30.320  3769  3819 I jxcore-log: 
,08-12 11:29:31.320  3769  3819 I jxcore-log: # setup
08-12 11:29:31.320  3769  3819 I jxcore-log: 
,08-12 11:29:31.370  3769  3819 I jxcore-log: # 11. native server - timing out the incoming connection cleans everything up
08-12 11:29:31.370  3769  3819 I jxcore-log: 
,08-12 11:29:31.472  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:31.472  3769  3819 I jxcore-log: 
,08-12 11:29:31.475  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 44116
08-12 11:29:31.475  3769  3819 I jxcore-log: 
,08-12 11:29:31.481  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:29:31.481  3769  3819 I jxcore-log: 
,08-12 11:29:31.482  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:29:31.482  3769  3819 I jxcore-log: 
,08-12 11:29:31.484  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:29:31.484  3769  3819 I jxcore-log: 
,08-12 11:29:31.490  3769  3819 I jxcore-log: ok 38 we should not have gotten an error
08-12 11:29:31.490  3769  3819 I jxcore-log: 
,08-12 11:29:31.497  3769  3819 I jxcore-log: DEBUG createNativeListener: new stream: 
08-12 11:29:31.497  3769  3819 I jxcore-log: 
,08-12 11:29:31.499  3769  3819 I jxcore-log: DEBUG createNativeListener: new outgoing socket
08-12 11:29:31.499  3769  3819 I jxcore-log: 
,08-12 11:29:31.506  3769  3819 I jxcore-log: ok 39 Buffers are identical
08-12 11:29:31.506  3769  3819 I jxcore-log: 
,08-12 11:29:31.511  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket timeout
08-12 11:29:31.511  3769  3819 I jxcore-log: 
,08-12 11:29:31.512  3769  3819 I jxcore-log: DEBUG createNativeListener: stream close:
,08-12 11:29:31.512  3769  3819 I jxcore-log: 
08-12 11:29:31.514  3769  3819 I jxcore-log: DEBUG createNativeListener: mux close
08-12 11:29:31.514  3769  3819 I jxcore-log: 
,08-12 11:29:31.520  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:29:31.520  3769  3819 I jxcore-log: 
,08-12 11:29:31.520  3769  3819 I jxcore-log: ok 40 server should be fine
08-12 11:29:31.520  3769  3819 I jxcore-log: 
08-12 11:29:31.521  3769  3819 I jxcore-log: ok 41 server should be open
08-12 11:29:31.521  3769  3819 I jxcore-log: 
,08-12 11:29:31.521  3769  3819 I jxcore-log: ok 42 incoming has been removed
08-12 11:29:31.521  3769  3819 I jxcore-log: 
08-12 11:29:31.522  3769  3819 I jxcore-log: ok 43 The mux object should be closed
08-12 11:29:31.522  3769  3819 I jxcore-log: 
08-12 11:29:31.522  3769  3819 I jxcore-log: ok 44 The mux stream should be closed
08-12 11:29:31.522  3769  3819 I jxcore-log: 
,08-12 11:29:31.529  3769  3819 I jxcore-log: # teardown
08-12 11:29:31.529  3769  3819 I jxcore-log: 
,08-12 11:29:31.650  3769  3819 I jxcore-log: # setup
08-12 11:29:31.650  3769  3819 I jxcore-log: 
,08-12 11:29:31.687  3769  3819 I jxcore-log: # 12. #_doImmediateSeqUpdate - server is not there
08-12 11:29:31.687  3769  3819 I jxcore-log: 
,08-12 11:29:31.863  3769  3819 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}
08-12 11:29:31.863  3769  3819 I jxcore-log: 
,08-12 11:29:31.865  3769  3819 I jxcore-log: ok 45 Got right error
08-12 11:29:31.865  3769  3819 I jxcore-log: 
,08-12 11:29:31.869  3769  3819 I jxcore-log: # teardown
08-12 11:29:31.869  3769  3819 I jxcore-log: 
,08-12 11:29:32.031  3769  3819 I jxcore-log: # setup
08-12 11:29:32.031  3769  3819 I jxcore-log: 
,08-12 11:29:32.072  3769  3819 I jxcore-log: # 13. #_doImmediateSeqUpdate - server accepts & closes connection
08-12 11:29:32.072  3769  3819 I jxcore-log: 
,08-12 11:29:32.163  3769  3819 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"code":"ECONNRESET","status":500}
08-12 11:29:32.163  3769  3819 I jxcore-log: 
,08-12 11:29:32.164  3769  3819 I jxcore-log: ok 46 Got socket hang up
08-12 11:29:32.164  3769  3819 I jxcore-log: 
,08-12 11:29:32.169  3769  3819 I jxcore-log: # teardown
08-12 11:29:32.169  3769  3819 I jxcore-log: 
,08-12 11:29:32.268  3769  3819 I jxcore-log: # setup
08-12 11:29:32.268  3769  3819 I jxcore-log: 
,08-12 11:29:32.309  3769  3819 I jxcore-log: # 14. #_doImmediateSeqUpdate - server always returns 500
08-12 11:29:32.309  3769  3819 I jxcore-log: 
,08-12 11:29:32.480  3769  3819 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq []
08-12 11:29:32.480  3769  3819 I jxcore-log: 
,08-12 11:29:32.481  3769  3819 I jxcore-log: ok 47 Got 500 as expected
08-12 11:29:32.481  3769  3819 I jxcore-log: 
,08-12 11:29:32.484  3769  3819 I jxcore-log: # teardown
08-12 11:29:32.484  3769  3819 I jxcore-log: 
,08-12 11:29:32.579  3769  3819 I jxcore-log: # setup
08-12 11:29:32.579  3769  3819 I jxcore-log: 
,08-12 11:29:32.656  3769  3819 I jxcore-log: # 15. #_doImmediateSeqUpdate - create new seq doc
08-12 11:29:32.656  3769  3819 I jxcore-log: 
,08-12 11:29:34.562  3769  3819 I jxcore-log: ok 48 should be equal
08-12 11:29:34.562  3769  3819 I jxcore-log: 
,08-12 11:29:34.563  3769  3819 I jxcore-log: ok 49 revs are equal
08-12 11:29:34.563  3769  3819 I jxcore-log: 
,08-12 11:29:34.568  3769  3819 I jxcore-log: # teardown
08-12 11:29:34.568  3769  3819 I jxcore-log: 
,08-12 11:29:34.602  3769  3819 I jxcore-log: # setup
08-12 11:29:34.602  3769  3819 I jxcore-log: 
,08-12 11:29:34.647  3769  3819 I jxcore-log: # 16. #_doImmediateSeqUpdate - doc exists, need to get rev and update
08-12 11:29:34.647  3769  3819 I jxcore-log: 
,08-12 11:29:35.394  3769  3819 I jxcore-log: ok 50 should be equal
08-12 11:29:35.394  3769  3819 I jxcore-log: 
,08-12 11:29:35.395  3769  3819 I jxcore-log: ok 51 revs are equal
08-12 11:29:35.395  3769  3819 I jxcore-log: 
,08-12 11:29:35.399  3769  3819 I jxcore-log: # teardown
08-12 11:29:35.399  3769  3819 I jxcore-log: 
,08-12 11:29:35.438  3769  3819 I jxcore-log: # setup
08-12 11:29:35.438  3769  3819 I jxcore-log: 
,08-12 11:29:35.495  3769  3819 I jxcore-log: # 17. #_doImmediateSeqUpdate - update seq three times
08-12 11:29:35.495  3769  3819 I jxcore-log: 
,08-12 11:29:35.975  3769  3819 I jxcore-log: ok 52 should be equal
08-12 11:29:35.975  3769  3819 I jxcore-log: 
,08-12 11:29:35.975  3769  3819 I jxcore-log: ok 53 revs are equal
08-12 11:29:35.975  3769  3819 I jxcore-log: 
,08-12 11:29:36.110  3769  3819 I jxcore-log: ok 54 should be equal
08-12 11:29:36.110  3769  3819 I jxcore-log: 
,08-12 11:29:36.110  3769  3819 I jxcore-log: ok 55 revs are equal
08-12 11:29:36.110  3769  3819 I jxcore-log: 
08-12 11:29:36.252  3769  3819 I jxcore-log: ok 56 should be equal
08-12 11:29:36.252  3769  3819 I jxcore-log: 
08-12 11:29:36.253  3769  3819 I jxcore-log: ok 57 revs are equal
08-12 11:29:36.253  3769  3819 I jxcore-log: 
,08-12 11:29:36.257  3769  3819 I jxcore-log: # teardown
08-12 11:29:36.257  3769  3819 I jxcore-log: 
,08-12 11:29:36.659  3769  3819 I jxcore-log: # setup
08-12 11:29:36.659  3769  3819 I jxcore-log: 
,08-12 11:29:36.722  3769  3819 I jxcore-log: # 18. #_doImmediateSeqUpdate - rev got changed under us
08-12 11:29:36.722  3769  3819 I jxcore-log: 
,08-12 11:29:37.400  3769  3819 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}
08-12 11:29:37.400  3769  3819 I jxcore-log: 
,08-12 11:29:37.402  3769  3819 I jxcore-log: ok 58 Our rev is old so we should fail
08-12 11:29:37.402  3769  3819 I jxcore-log: 
,08-12 11:29:37.404  3769  3819 I jxcore-log: # teardown
08-12 11:29:37.404  3769  3819 I jxcore-log: 
,08-12 11:29:37.535  3769  3819 I jxcore-log: # setup
08-12 11:29:37.535  3769  3819 I jxcore-log: 
,08-12 11:29:37.603  3769  3819 I jxcore-log: # 19. #_doImmediateSeqUpdate - fail if stop is called
08-12 11:29:37.603  3769  3819 I jxcore-log: 
,08-12 11:29:37.756  3769  3819 I jxcore-log: ok 59 confirm stop caused failure
08-12 11:29:37.756  3769  3819 I jxcore-log: 
,08-12 11:29:37.763  3769  3819 I jxcore-log: # teardown
08-12 11:29:37.763  3769  3819 I jxcore-log: 
,08-12 11:29:37.818  3769  3819 I jxcore-log: # setup
08-12 11:29:37.818  3769  3819 I jxcore-log: 
,08-12 11:29:37.862  3769  3819 I jxcore-log: # 20. #_doImmediateSeqUpdate - stop after get but before put fails right
08-12 11:29:37.862  3769  3819 I jxcore-log: 
,08-12 11:29:38.238  3769  3819 I jxcore-log: DEBUG localSeqManager: Got an error trying to update seq {"onPut":true}
08-12 11:29:38.238  3769  3819 I jxcore-log: 
,08-12 11:29:38.239  3769  3819 I jxcore-log: ok 60 stop caused us to fail
08-12 11:29:38.239  3769  3819 I jxcore-log: 
08-12 11:29:38.240  3769  3819 I jxcore-log: ok 61 We specifically failed on a stop before put
08-12 11:29:38.240  3769  3819 I jxcore-log: 
,08-12 11:29:38.246  3769  3819 I jxcore-log: # teardown
08-12 11:29:38.246  3769  3819 I jxcore-log: 
,08-12 11:29:38.292  3769  3819 I jxcore-log: # setup
08-12 11:29:38.292  3769  3819 I jxcore-log: 
,08-12 11:29:38.364  3769  3819 I jxcore-log: # 21. #update - fail if stop is called
08-12 11:29:38.364  3769  3819 I jxcore-log: 
,08-12 11:29:38.459  3769  3819 I jxcore-log: ok 62 failed due to stop
08-12 11:29:38.459  3769  3819 I jxcore-log: 
,08-12 11:29:38.462  3769  3819 I jxcore-log: ok 63 failed due to stop
08-12 11:29:38.462  3769  3819 I jxcore-log: 
,08-12 11:29:38.470  3769  3819 I jxcore-log: # teardown
08-12 11:29:38.470  3769  3819 I jxcore-log: 
,08-12 11:29:38.593  3769  3819 I jxcore-log: # setup
08-12 11:29:38.593  3769  3819 I jxcore-log: 
,08-12 11:29:38.633  3769  3819 I jxcore-log: # 22. #update - set seq for first time
08-12 11:29:38.633  3769  3819 I jxcore-log: 
,08-12 11:29:39.138  3769  3819 I jxcore-log: ok 64 should be equal
08-12 11:29:39.138  3769  3819 I jxcore-log: 
,08-12 11:29:39.142  3769  3819 I jxcore-log: # teardown
08-12 11:29:39.142  3769  3819 I jxcore-log: 
,08-12 11:29:39.238  3769  3819 I jxcore-log: # setup
08-12 11:29:39.238  3769  3819 I jxcore-log: 
,08-12 11:29:39.303  3769  3819 I jxcore-log: # 23. #update - Fail on bad seq value
08-12 11:29:39.303  3769  3819 I jxcore-log: 
,08-12 11:29:39.744  3769  3819 I jxcore-log: DEBUG localSeqManager: Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10
08-12 11:29:39.744  3769  3819 I jxcore-log: 
,08-12 11:29:39.746  3769  3819 I jxcore-log: ok 65 Expected bad seq error
08-12 11:29:39.746  3769  3819 I jxcore-log: 
,08-12 11:29:39.750  3769  3819 I jxcore-log: # teardown
08-12 11:29:39.750  3769  3819 I jxcore-log: 
,08-12 11:29:39.821  3769  3819 I jxcore-log: # setup
08-12 11:29:39.821  3769  3819 I jxcore-log: 
,08-12 11:29:39.884  3769  3819 I jxcore-log: # 24. #update - do we cancel timer properly on an immediate?
08-12 11:29:39.884  3769  3819 I jxcore-log: 
,08-12 11:29:40.393  3769  3819 I jxcore-log: ok 66 Different promises
08-12 11:29:40.393  3769  3819 I jxcore-log: 
,08-12 11:29:40.396  3769  3819 I jxcore-log: ok 67 Timer was cancelled
08-12 11:29:40.396  3769  3819 I jxcore-log: 
,08-12 11:29:40.570  3769  3819 I jxcore-log: ok 68 should be equal
08-12 11:29:40.570  3769  3819 I jxcore-log: 
,08-12 11:29:40.575  3769  3819 I jxcore-log: # teardown
08-12 11:29:40.575  3769  3819 I jxcore-log: 
,08-12 11:29:40.645  3769  3819 I jxcore-log: # setup
08-12 11:29:40.645  3769  3819 I jxcore-log: 
,08-12 11:29:40.832  3769  3819 I jxcore-log: # 25. #update - do we wait for blocked update
08-12 11:29:40.832  3769  3819 I jxcore-log: 
,08-12 11:29:40.932  3769  3819 I jxcore-log: ok 69 One go and one blocked
08-12 11:29:40.932  3769  3819 I jxcore-log: 
08-12 11:29:40.932  3769  3819 I jxcore-log: ok 70 All blocked
08-12 11:29:40.932  3769  3819 I jxcore-log: 
,08-12 11:29:40.933  3769  3819 I jxcore-log: ok 71 Still blocked
08-12 11:29:40.933  3769  3819 I jxcore-log: 
,08-12 11:29:41.377  3769  3819 I jxcore-log: ok 72 should be equal
08-12 11:29:41.377  3769  3819 I jxcore-log: 
,08-12 11:29:41.383  3769  3819 I jxcore-log: # teardown
08-12 11:29:41.383  3769  3819 I jxcore-log: 
,08-12 11:29:41.430  3769  3819 I jxcore-log: # setup
08-12 11:29:41.430  3769  3819 I jxcore-log: 
,08-12 11:29:41.503  3769  3819 I jxcore-log: # 26. #update - test that we wait long enough
08-12 11:29:41.503  3769  3819 I jxcore-log: 
,08-12 11:29:42.699  3769  3819 I jxcore-log: ok 73 We waited long enough
08-12 11:29:42.699  3769  3819 I jxcore-log: 
,08-12 11:29:42.845  3769  3819 I jxcore-log: ok 74 should be equal
08-12 11:29:42.845  3769  3819 I jxcore-log: 
,08-12 11:29:42.849  3769  3819 I jxcore-log: # teardown
08-12 11:29:42.849  3769  3819 I jxcore-log: 
,08-12 11:29:43.302  3769  3819 I jxcore-log: # setup
08-12 11:29:43.302  3769  3819 I jxcore-log: 
,08-12 11:29:43.376  3769  3819 I jxcore-log: # 27. #update - test that we pick up new sequences while we wait
08-12 11:29:43.376  3769  3819 I jxcore-log: 
,08-12 11:29:44.361  3769  3819 I jxcore-log: ok 75 Should have gotten same timer promise
08-12 11:29:44.361  3769  3819 I jxcore-log: 
,08-12 11:29:44.361  3769  3819 I jxcore-log: ok 76 Still same timer promise
08-12 11:29:44.361  3769  3819 I jxcore-log: 
,08-12 11:29:45.174  3769  3819 I jxcore-log: ok 77 We waited long enough
08-12 11:29:45.174  3769  3819 I jxcore-log: 
,08-12 11:29:45.274  3769  3819 I jxcore-log: ok 78 should be equal
08-12 11:29:45.274  3769  3819 I jxcore-log: 
,08-12 11:29:45.279  3769  3819 I jxcore-log: # teardown
08-12 11:29:45.279  3769  3819 I jxcore-log: 
,08-12 11:29:45.351  3769  3819 I jxcore-log: # setup
08-12 11:29:45.351  3769  3819 I jxcore-log: 
,08-12 11:29:45.603  3769  3819 I jxcore-log: # 28. Coordinated seq test
08-12 11:29:45.603  3769  3819 I jxcore-log: 
,08-12 11:29:45.825  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:29:45.825  3769  3819 I jxcore-log: 
,08-12 11:29:45.827  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 49883
08-12 11:29:45.827  3769  3819 I jxcore-log: 
,08-12 11:29:45.832  3769  3819 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 11:29:45.836  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 0, start advertisements: false
,08-12 11:29:45.836  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 11:29:45.836  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 11:29:45.837  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-12 11:29:45.837  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 11:29:45.837  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 11:29:45.837  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-12 11:29:45.841  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 11:29:45.842  3769  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 11:29:45.847  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 11:29:45.849  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 11:29:45.849  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 11:29:45.851  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-12 11:29:45.853  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-12 11:29:45.853  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 11:29:45.853  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-12 11:29:45.853  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 11:29:45.854  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:29:45.858  2638  2649 D BtGatt.GattService: registerClient() - UUID=d2324f9f-d666-4942-bc6e-fe3b39bc54ca
,08-12 11:29:45.858  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=d2324f9f-d666-4942-bc6e-fe3b39bc54ca, clientIf=5
,08-12 11:29:45.859  3769  3779 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 11:29:45.860  2638  2651 D BtGatt.GattService: start scan with filters
08-12 11:29:45.863  2638  2679 D BtGatt.ScanManager: handling starting scan
,08-12 11:29:45.863  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 11:29:45.864  2638  2679 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@76749b6
08-12 11:29:45.864  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-12 11:29:45.865  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 11:29:45.865  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 11:29:45.871  2638  2676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-12 11:29:45.871  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:29:45.872  2638  2679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-12 11:29:45.874  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 11:29:45.879  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 11:29:45.880  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 11:29:45.880  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:29:45.880  2638  2679 D BtGatt.ScanManager: Starting BLE batch scan
,08-12 11:29:45.880  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-12 11:29:45.881  2638  2679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-12 11:29:45.887  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-12 11:29:45.890  2638  2676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 11:29:45.890  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:29:45.894  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 11:29:45.894  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:29:45.896  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:29:46.381  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-12 11:29:46.382  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 11:29:46.382  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:29:46.413  3769  3819 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 11:29:46.417  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 49883, start advertisements: true
,08-12 11:29:46.417  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 11:29:46.418  3769  3819 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-12 11:29:46.418  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-12 11:29:46.420  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-12 11:29:46.420  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-12 11:29:46.420  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-12 11:29:46.420  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 1
08-12 11:29:46.420  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-12 11:29:46.420  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-12 11:29:46.420  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-12 11:29:46.420  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-12 11:29:46.420  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
08-12 11:29:46.421  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 11:29:46.421  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 11:29:46.422  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:29:46.424  2638  2651 D BtGatt.GattService: stopScan() - queue size =1
,08-12 11:29:46.426  2638  2761 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:29:46.426  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 11:29:46.427  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 11:29:46.427  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-12 11:29:46.427  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-12 11:29:46.428  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-12 11:29:46.428  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-12 11:29:46.430  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:29:46.434  2638  2651 D BtGatt.GattService: registerClient() - UUID=82b25cf8-7df2-44f9-80cd-f04ede659e41
,08-12 11:29:46.435  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=82b25cf8-7df2-44f9-80cd-f04ede659e41, clientIf=5
,08-12 11:29:46.436  3769  3780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 11:29:46.437  2638  2649 D BtGatt.GattService: start scan with filters
,08-12 11:29:46.442  2638  2638 D BtGatt.ScanManager: awakened up at time 369457
,08-12 11:29:46.446  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 11:29:46.447  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-12 11:29:46.447  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-12 11:29:46.447  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-12 11:29:46.448  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-12 11:29:46.449  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 11:29:46.452  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-12 11:29:46.454  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 11:29:46.454  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:29:46.455  2638  2679 D BtGatt.ScanManager: stopping BLe Batch
,08-12 11:29:46.455  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-12 11:29:46.456  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-12 11:29:46.457  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-12 11:29:46.464  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-12 11:29:46.464  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-12 11:29:46.464  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 11:29:46.464  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 11:29:46.465  3769  3889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-12 11:29:46.465  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:29:46.465  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 11:29:46.465  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:29:46.466  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
08-12 11:29:46.466  2638  2651 D BtGatt.GattService: stopScan() - queue size =0
08-12 11:29:46.467  2638  2761 D BtGatt.GattService: unregisterClient() - clientIf=5,
,08-12 11:29:46.467  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 11:29:46.467  3769  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-12 11:29:46.467  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-12 11:29:46.467  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-12 11:29:46.467  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 11:29:46.467  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-12 11:29:46.468  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:29:46.469  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 11:29:46.472  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-12 11:29:46.472  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 11:29:46.473  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-12 11:29:46.475  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 11:29:46.475  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 11:29:46.475  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-12 11:29:46.476  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:29:46.483  2638  2651 D BtGatt.GattService: registerClient() - UUID=23ebb7fc-7366-49dc-b875-125fe9164918
08-12 11:29:46.483  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=23ebb7fc-7366-49dc-b875-125fe9164918, clientIf=5
,08-12 11:29:46.483  3769  3779 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-12 11:29:46.484  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 11:29:46.484  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:29:46.485  2638  2676 D BtGatt.GattService: current time is 369500187546
08-12 11:29:46.485  2638  2678 D BtGatt.AdvertiseManager: message : 0
08-12 11:29:46.485  2638  2676 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 53, 33, -121, 80, 73, -44, 1, 0, -107, 2, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -28, -15, -42, 2, 2, -29, 21, 63, 38, -30, -93, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:29:46.486  2638  2679 D BtGatt.ScanManager: handling starting scan
08-12 11:29:46.486  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:29:46.487  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:29:46.487  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, -28, -15, -42, 2, 2, -29, 21, 63, 38, -30, -93, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,08-12 11:29:46.487  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 11:29:46.487  2638  2678 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 11:29:46.487  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:29:46.493  2638  2676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-12 11:29:46.493  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:29:46.493  2638  2679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 11:29:46.503  2638  2676 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 11:29:46.507  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 11:29:46.507  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:29:46.507  2638  2679 D BtGatt.ScanManager: Starting BLE batch scan
08-12 11:29:46.507  2638  2679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 11:29:46.512  2638  2676 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-12 11:29:46.513  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-12 11:29:46.514  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 11:29:46.515  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 11:29:46.518  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:29:46.518  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-12 11:29:46.518  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 11:29:46.518  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-12 11:29:46.518  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-12 11:29:46.519  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-12 11:29:46.519  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-12 11:29:46.519  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-12 11:29:46.521  3769  3769 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-12 11:29:46.521  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
08-12 11:29:46.522  2638  2676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 11:29:46.522  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:29:46.525  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 11:29:46.525  3769  3819 I jxcore-log: 
08-12 11:29:46.527  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 11:29:46.528  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:29:46.534  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 11:29:46.534  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:29:46.534  2638  2679 D BtGatt.ScanManager: stopping BLe Batch
,08-12 11:29:46.539  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 11:29:46.539  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:29:46.539  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:29:46.544  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:29:46.544  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:29:47.022  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-12 11:29:47.023  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-12 11:29:47.023  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:29:47.032  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-12 11:29:47.032  3769  3819 I jxcore-log: 
,08-12 11:31:51.868  3043  3898 V KeepSync: Connecting to GoogleApiClient
,08-12 11:31:51.869   871   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 11:31:51.941  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:31:51.944  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:31:52.001  1513  2346 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 11:31:52.001  1513  2346 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 11:31:52.001  1513  2346 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:31:52.002  1513  2346 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:31:52.041  1728  3899 V BaseAuthAsyncOperation: access token request failed
,08-12 11:31:52.044  3043  3898 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 11:31:52.126  1513  3752 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-12 11:31:52.126  1513  3752 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-12 11:31:52.126  1513  3752 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:31:52.127  1513  3752 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:31:52.143  3043  3898 E KeepSync: IOException
08-12 11:31:52.143  3043  3898 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 11:31:52.143  3043  3898 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 11:31:52.143  3043  3898 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 11:31:52.143  3043  3898 E KeepSync: 	... 10 more
,08-12 11:31:52.144  3043  3898 W KeepSync: Sync result 2
,08-12 11:31:52.161   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 494608, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:32:28.574  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:32:28.579  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:32:28.636  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 11:32:28.637  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 11:32:28.637  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:32:28.637  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:32:28.675  3537  3904 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 11:32:28.675  3537  3904 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at jdm.a(PG:82)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at jcs.o(PG:406)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at jcn.a(PG:1379)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at jcs.i(PG:143)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at blb.a(PG:3937)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at czp.a(PG:18188)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at czp.a(PG:9081)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at czq.run(PG:1686)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:32:28.675  3537  3904 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at jdj.a(PG:4091)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at jdj.a(PG:1125)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at jdm.a(PG:77)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	... 12 more
08-12 11:32:28.675  3537  3904 E HttpOperation: Caused by: faj: BadAuthentication
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at fal.a(PG:38)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	at jdj.a(PG:4089)
08-12 11:32:28.675  3537  3904 E HttpOperation: 	... 14 more
,08-12 11:32:28.745  1513  3752 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 11:32:28.745  1513  3752 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 11:32:28.745  1513  3752 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:32:28.745  1513  3752 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:32:28.764  3537  3904 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 11:32:28.764  3537  3904 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at jdm.a(PG:82)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at jcs.o(PG:406)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at jcn.a(PG:1379)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at jcs.i(PG:143)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at hec.a(PG:42)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at hee.a(PG:102)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at czr.a(PG:65)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at kka.a(PG:108)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at czp.a(PG:19176)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at czp.a(PG:9081)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at czq.run(PG:1686)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:32:28.764  3537  3904 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at jdj.a(PG:4091)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at jdj.a(PG:1125)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at jdm.a(PG:77)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	... 15 more
08-12 11:32:28.764  3537  3904 E HttpOperation: Caused by: faj: BadAuthentication
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at fal.a(PG:38)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	at jdj.a(PG:4089)
08-12 11:32:28.764  3537  3904 E HttpOperation: 	... 17 more
,08-12 11:32:28.765  3537  3904 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 11:32:28.765  3537  3904 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at hec.a(PG:42)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at hee.a(PG:102)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at czr.a(PG:65)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at kka.a(PG:108)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	... 15 more
08-12 11:32:28.765  3537  3904 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at fal.a(PG:38)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 11:32:28.765  3537  3904 E ExperimentLoader: 	... 17 more
,08-12 11:32:28.900   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 531236, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:33:21.667  3722  3909 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 11:33:21.690  3722  3910 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 11:33:21.707  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:33:21.711  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:33:21.743  1513  2346 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 11:33:21.743  1513  2346 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 11:33:21.743  1513  2346 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:33:21.744  1513  2346 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:33:21.776  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:33:21.778  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:33:21.800  1513  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 11:33:21.800  1513  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 11:33:21.800  1513  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:33:21.800  1513  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:33:21.827  3722  3910 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 11:33:21.828  3722  3909 E BooksSync: Soft error
08-12 11:33:21.828  3722  3909 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 11:33:21.828  3722  3909 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 11:33:21.828  3722  3909 E BooksSync: Sync error
08-12 11:33:21.828  3722  3909 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 11:33:21.828  3722  3909 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 11:33:21.828  3722  3909 I BooksSync: Finished books sync
,08-12 11:33:21.839   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 584592, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 11:33:52.077  1513  2147 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 11:34:45.743  3769  3819 I jxcore-log: not ok 79 We failed - Error: Test timed out
08-12 11:34:45.743  3769  3819 I jxcore-log: 
08-12 11:34:45.743  3769  3819 I jxcore-log:   ---
08-12 11:34:45.743  3769  3819 I jxcore-log: 
,08-12 11:34:45.744  3769  3819 I jxcore-log:     operator: fail
08-12 11:34:45.744  3769  3819 I jxcore-log: 
08-12 11:34:45.744  3769  3819 I jxcore-log:   ...
08-12 11:34:45.744  3769  3819 I jxcore-log: 
,08-12 11:34:45.759  3769  3819 I jxcore-log: # teardown
08-12 11:34:45.759  3769  3819 I jxcore-log: 
,08-12 11:34:45.804  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:34:45.805  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:34:45.805  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-12 11:34:45.805  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-12 11:34:45.805  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-12 11:34:45.805  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-12 11:34:45.805  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-12 11:34:45.806  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-12 11:34:45.806  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-12 11:34:45.806  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-12 11:34:45.806  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 11:34:45.806  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-12 11:34:45.806  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-12 11:34:45.806  3769  3889 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-12 11:34:45.806  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-12 11:34:45.806  3769  3889 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-12 11:34:45.807  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-12 11:34:45.807  3769  3889 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-12 11:34:45.808  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:34:45.808  3769  3819 D BluetoothLeScanner: could not find callback wrapper
08-12 11:34:45.808  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 11:34:45.808  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-12 11:34:45.809  2638  2678 D BtGatt.AdvertiseManager: message : 1
08-12 11:34:45.810  2638  2678 D BtGatt.AdvertiseManager: stop advertise for client 5
08-12 11:34:45.824  2638  2676 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-12 11:34:45.824  2638  2676 D BtGatt.GattService: Client app is not null!
08-12 11:34:45.825  2638  2761 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 11:34:45.825  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-12 11:34:45.826  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-12 11:34:45.826  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-12 11:34:45.826  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-12 11:34:45.826  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-12 11:34:45.827  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 11:34:45.827  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-12 11:34:45.828  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-12 11:34:45.828  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-12 11:34:45.832  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 11:34:45.833  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-12 11:34:45.833  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 11:34:45.833  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 11:34:45.833  3769  3769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-12 11:34:45.833  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:34:45.846  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:34:45.846  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:34:45.847  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:34:45.847  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:45.850  3769  3819 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 11:34:45.850  3769  3819 I jxcore-log: 
,08-12 11:34:45.855  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 11:34:45.856  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:34:45.856  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:34:45.856  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:45.867  3769  3819 I jxcore-log: # setup
08-12 11:34:45.867  3769  3819 I jxcore-log: 
,08-12 11:34:46.033  3769  3819 I jxcore-log: # 29. closeAll can close even when connections open
08-12 11:34:46.033  3769  3819 I jxcore-log: 
,08-12 11:34:46.224  3769  3819 I jxcore-log: ok 80 not possible to connect to the server anymore
08-12 11:34:46.224  3769  3819 I jxcore-log: 
,08-12 11:34:46.234  3769  3819 I jxcore-log: # teardown
08-12 11:34:46.234  3769  3819 I jxcore-log: 
,08-12 11:34:46.311  3769  3819 I jxcore-log: # setup
08-12 11:34:46.311  3769  3819 I jxcore-log: 
,08-12 11:34:46.333  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 11:34:46.340  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 11:34:46.340  3769  3819 I jxcore-log: 
,08-12 11:34:46.373  3769  3819 I jxcore-log: # 30. closeAll with promise
08-12 11:34:46.373  3769  3819 I jxcore-log: 
,08-12 11:34:46.573  3769  3819 I jxcore-log: ok 81 not possible to connect to the server anymore
08-12 11:34:46.573  3769  3819 I jxcore-log: 
,08-12 11:34:46.576  3769  3819 I jxcore-log: # teardown
08-12 11:34:46.576  3769  3819 I jxcore-log: 
,08-12 11:34:46.650  3769  3819 I jxcore-log: # setup
08-12 11:34:46.650  3769  3819 I jxcore-log: 
,08-12 11:34:46.725  3769  3819 I jxcore-log: # 31. closeAll properly throws when closing a non open server with eatNotRunning set to false
08-12 11:34:46.725  3769  3819 I jxcore-log: 
,08-12 11:34:46.903  3769  3819 I jxcore-log: ok 82 Got the right error
08-12 11:34:46.903  3769  3819 I jxcore-log: 
,08-12 11:34:46.916  3769  3819 I jxcore-log: # teardown
08-12 11:34:46.916  3769  3819 I jxcore-log: 
,08-12 11:34:46.967  3769  3819 I jxcore-log: # setup
08-12 11:34:46.967  3769  3819 I jxcore-log: 
,08-12 11:34:47.056  3769  3819 I jxcore-log: # 32. closeAll works even with a server that is not listening yet witheatNotRunning set to true
08-12 11:34:47.056  3769  3819 I jxcore-log: 
,08-12 11:34:47.225  3769  3819 I jxcore-log: # teardown
08-12 11:34:47.225  3769  3819 I jxcore-log: 
,08-12 11:34:47.324  3769  3819 I jxcore-log: # setup
08-12 11:34:47.324  3769  3819 I jxcore-log: 
,08-12 11:34:47.405  3769  3819 I jxcore-log: # 33. onPeerLost calls jxcore
08-12 11:34:47.405  3769  3819 I jxcore-log: 
,08-12 11:34:47.475  3769  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-12 11:34:47.475  3769  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bcad355 added. We now have 2 listener(s)
,08-12 11:34:47.477  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 11:34:47.477  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 11:34:47.477  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 11:34:47.477  3769  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-12 11:34:47.477  3769  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7e116a added. We now have 2 listener(s)
08-12 11:34:47.477  3769  3819 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 11:34:47.478  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 11:34:47.482  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 11:34:47.493  3769  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:34:47.493  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:34:47.493  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 11:34:47.493  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:34:47.493  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:34:47.493  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:34:47.493  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:34:47.493  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 11:34:47.498  3769  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 11:34:47.500  3769  3819 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-12 11:34:47.505  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 11:34:47.505  3769  3819 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
,08-12 11:34:47.505  3769  3819 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,08-12 11:34:47.508  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:34:49.510  3769  3819 I jxcore-log: onPeerLost
08-12 11:34:49.510  3769  3819 I jxcore-log: 
,08-12 11:34:49.516  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 11:34:49.516  3769  3819 I jxcore-log: 
,08-12 11:34:49.528  3769  3819 I jxcore-log: # teardown
08-12 11:34:49.528  3769  3819 I jxcore-log: 
,08-12 11:34:49.534  3769  3819 I jxcore-log: ok 83 check if callback was fired by onPeerLost
08-12 11:34:49.534  3769  3819 I jxcore-log: 
,08-12 11:34:49.535  3769  3819 I jxcore-log: ok 84 check if peerAvailable is false
08-12 11:34:49.535  3769  3819 I jxcore-log: 
,08-12 11:34:49.648  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 11:34:49.648  3769  3819 I jxcore-log: 
,08-12 11:34:49.650  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 11:34:49.650  3769  3819 I jxcore-log: 
,08-12 11:34:49.660  3769  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:34:49.660  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:34:49.660  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 11:34:49.660  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:34:49.660  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:34:49.660  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:34:49.660  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:34:49.660  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 11:34:49.664  3769  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 11:34:49.666  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 11:34:49.666  3769  3819 I jxcore-log: 
,08-12 11:34:49.669  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 11:34:49.669  3769  3819 I jxcore-log: 
,08-12 11:34:49.672  3769  3819 I jxcore-log: # setup
08-12 11:34:49.672  3769  3819 I jxcore-log: 
,08-12 11:34:49.674  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 11:34:49.674  3769  3819 I jxcore-log: 
,08-12 11:34:49.717  3769  3819 I jxcore-log: # 34. onPeerDiscovered calls jxcore
08-12 11:34:49.717  3769  3819 I jxcore-log: 
,08-12 11:34:49.756  3769  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-12 11:34:49.756  3769  3819 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11efef8 added. We now have 3 listener(s)
,08-12 11:34:49.759  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 11:34:49.759  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 11:34:49.759  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 11:34:49.759  3769  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-12 11:34:49.759  3769  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b24fd1 added. We now have 3 listener(s)
08-12 11:34:49.760  3769  3819 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 11:34:49.761  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 11:34:49.765  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 11:34:49.774  3769  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:34:49.774  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:34:49.774  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 11:34:49.774  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:34:49.774  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:34:49.774  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:34:49.774  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:34:49.774  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 11:34:49.779  3769  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 11:34:49.779  3769  3819 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 11:34:49.780  3769  3819 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,08-12 11:34:49.785  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:34:49.789  3769  3769 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:34:51.783  3769  3819 I jxcore-log: onPeerDiscovered
08-12 11:34:51.783  3769  3819 I jxcore-log: 
,08-12 11:34:51.787  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 11:34:51.787  3769  3819 I jxcore-log: 
,08-12 11:34:51.799  3769  3819 I jxcore-log: # teardown
08-12 11:34:51.799  3769  3819 I jxcore-log: 
,08-12 11:34:51.806  3769  3819 I jxcore-log: ok 85 check if callback was fired by onPeerDiscovered
08-12 11:34:51.806  3769  3819 I jxcore-log: 
,08-12 11:34:51.807  3769  3819 I jxcore-log: ok 86 check if peerAvailable is true
08-12 11:34:51.807  3769  3819 I jxcore-log: 
,08-12 11:34:51.933  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 11:34:51.933  3769  3819 I jxcore-log: 
,08-12 11:34:51.939  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 11:34:51.939  3769  3819 I jxcore-log: 
,08-12 11:34:51.947  3769  3819 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:34:51.947  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:34:51.947  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 11:34:51.947  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:34:51.947  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:34:51.947  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:34:51.947  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:34:51.947  3769  3819 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 11:34:51.950  3769  3819 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 11:34:51.952  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 11:34:51.952  3769  3819 I jxcore-log: 
,08-12 11:34:51.954  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 11:34:51.954  3769  3819 I jxcore-log: 
,08-12 11:34:51.956  3769  3819 I jxcore-log: # setup
08-12 11:34:51.956  3769  3819 I jxcore-log: 
08-12 11:34:51.958  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 11:34:51.958  3769  3819 I jxcore-log: 
,08-12 11:34:52.013  3769  3819 I jxcore-log: # 35. enqueue and run in order
08-12 11:34:52.013  3769  3819 I jxcore-log: 
,08-12 11:34:52.180  3769  3819 I jxcore-log: ok 87 firstPromise setTimeout
08-12 11:34:52.180  3769  3819 I jxcore-log: 
,08-12 11:34:52.184  3769  3819 I jxcore-log: ok 88 firstPromise result
08-12 11:34:52.184  3769  3819 I jxcore-log: 
,08-12 11:34:52.186  3769  3819 I jxcore-log: ok 89 firstPromise testValue
08-12 11:34:52.186  3769  3819 I jxcore-log: 
,08-12 11:34:52.291  3769  3819 I jxcore-log: ok 90 secondPromise setTimeout
08-12 11:34:52.291  3769  3819 I jxcore-log: 
,08-12 11:34:52.294  3769  3819 I jxcore-log: ok 91 secondPromise result
08-12 11:34:52.294  3769  3819 I jxcore-log: 
,08-12 11:34:52.296  3769  3819 I jxcore-log: ok 92 secondPromise testValue
08-12 11:34:52.296  3769  3819 I jxcore-log: 
,08-12 11:34:52.299  3769  3819 I jxcore-log: ok 93 thirdPromise in promise
08-12 11:34:52.299  3769  3819 I jxcore-log: 
,08-12 11:34:52.302  3769  3819 I jxcore-log: ok 94 thirdPromise result
08-12 11:34:52.302  3769  3819 I jxcore-log: 
,08-12 11:34:52.305  3769  3819 I jxcore-log: ok 95 thirdPromise testValue
08-12 11:34:52.305  3769  3819 I jxcore-log: 
,08-12 11:34:52.314  3769  3819 I jxcore-log: # teardown
08-12 11:34:52.314  3769  3819 I jxcore-log: 
,08-12 11:34:52.395  3769  3819 I jxcore-log: # setup
08-12 11:34:52.395  3769  3819 I jxcore-log: 
,08-12 11:34:52.461  3769  3819 I jxcore-log: # 36. enqueueAtTop and run backwards
08-12 11:34:52.461  3769  3819 I jxcore-log: 
,08-12 11:34:52.507  3769  3819 I jxcore-log: ok 96 thirdPromise - first to run,
08-12 11:34:52.507  3769  3819 I jxcore-log: 
08-12 11:34:52.508  3769  3819 I jxcore-log: ok 97 thirdPromise - in resolve
08-12 11:34:52.508  3769  3819 I jxcore-log: 
08-12 11:34:52.509  3769  3819 I jxcore-log: ok 98 secondPromise - second to run
08-12 11:34:52.509  3769  3819 I jxcore-log: 
,08-12 11:34:52.510  3769  3819 I jxcore-log: ok 99 secondPromise - in catch
08-12 11:34:52.510  3769  3819 I jxcore-log: 
08-12 11:34:52.510  3769  3819 I jxcore-log: ok 100 firstPromise - third to run
08-12 11:34:52.510  3769  3819 I jxcore-log: 
,08-12 11:34:52.511  3769  3819 I jxcore-log: ok 101 firstPromise - in then
08-12 11:34:52.511  3769  3819 I jxcore-log: 
,08-12 11:34:52.512  3769  3819 I jxcore-log: ok 102 testing promises
08-12 11:34:52.512  3769  3819 I jxcore-log: 
08-12 11:34:52.514  3769  3819 I jxcore-log: # teardown
08-12 11:34:52.514  3769  3819 I jxcore-log: 
,08-12 11:34:52.615  3769  3819 I jxcore-log: # setup
08-12 11:34:52.615  3769  3819 I jxcore-log: 
,08-12 11:34:52.666  3769  3819 I jxcore-log: # 37. mix enqueue and enqueueAtTop
08-12 11:34:52.666  3769  3819 I jxcore-log: 
,08-12 11:34:52.716  3769  3819 I jxcore-log: ok 103 fourth
08-12 11:34:52.716  3769  3819 I jxcore-log: 
,08-12 11:34:52.718  3769  3819 I jxcore-log: ok 104 fourth
08-12 11:34:52.718  3769  3819 I jxcore-log: 
,08-12 11:34:52.720  3769  3819 I jxcore-log: ok 105 second
08-12 11:34:52.720  3769  3819 I jxcore-log: 
08-12 11:34:52.722  3769  3819 I jxcore-log: ok 106 secondPromise - in then
08-12 11:34:52.722  3769  3819 I jxcore-log: 
,08-12 11:34:52.826  3769  3819 I jxcore-log: ok 107 first
08-12 11:34:52.826  3769  3819 I jxcore-log: 
,08-12 11:34:52.842  3769  3819 I jxcore-log: ok 108 firstPromise - in catch
08-12 11:34:52.842  3769  3819 I jxcore-log: 
,08-12 11:34:52.845  3769  3819 I jxcore-log: ok 109 third
08-12 11:34:52.845  3769  3819 I jxcore-log: 
,08-12 11:34:52.849  3769  3819 I jxcore-log: ok 110 thirdPromise - in then
08-12 11:34:52.849  3769  3819 I jxcore-log: 
,08-12 11:34:52.852  3769  3819 I jxcore-log: ok 111 testingPromises
08-12 11:34:52.852  3769  3819 I jxcore-log: 
,08-12 11:34:52.857  3769  3819 I jxcore-log: # teardown,
08-12 11:34:52.857  3769  3819 I jxcore-log: 
,08-12 11:34:52.932  3769  3819 I jxcore-log: # setup,
08-12 11:34:52.932  3769  3819 I jxcore-log: 
,08-12 11:34:53.022  3769  3819 I jxcore-log: # 38. queues handled independently,
08-12 11:34:53.022  3769  3819 I jxcore-log: 
,08-12 11:34:53.105  3769  3819 I jxcore-log: ok 112 all short operations completed before the long resolves,
08-12 11:34:53.105  3769  3819 I jxcore-log: 
,08-12 11:34:53.112  3769  3819 I jxcore-log: # teardown,
08-12 11:34:53.112  3769  3819 I jxcore-log: 
,08-12 11:34:53.175  3769  3819 I jxcore-log: # setup,
08-12 11:34:53.175  3769  3819 I jxcore-log: 
,08-12 11:34:53.236  3769  3819 I jxcore-log: # 39. basic,
08-12 11:34:53.236  3769  3819 I jxcore-log: 
,08-12 11:34:53.285  3769  3819 I jxcore-log: ok 113 sane,
08-12 11:34:53.285  3769  3819 I jxcore-log: 
,08-12 11:34:53.289  3769  3819 I jxcore-log: # teardown
08-12 11:34:53.289  3769  3819 I jxcore-log: 
,08-12 11:34:53.352  3769  3819 I jxcore-log: # setup,
08-12 11:34:53.352  3769  3819 I jxcore-log: 
,08-12 11:34:53.410  3769  3819 I jxcore-log: # 40. another,
08-12 11:34:53.410  3769  3819 I jxcore-log: 
,08-12 11:34:53.454  3769  3819 I jxcore-log: ok 114 sane,
08-12 11:34:53.454  3769  3819 I jxcore-log: 
,08-12 11:34:53.457  3769  3819 I jxcore-log: # teardown
08-12 11:34:53.457  3769  3819 I jxcore-log: 
,08-12 11:34:53.504  3769  3819 I jxcore-log: # setup
08-12 11:34:53.504  3769  3819 I jxcore-log: 
,08-12 11:34:53.552  3769  3819 I jxcore-log: # 41. can pass data in setup
08-12 11:34:53.552  3769  3819 I jxcore-log: 
,08-12 11:34:53.618  3769  3819 I jxcore-log: [{"uuid":"4fbc60b0-f8bb-4e77-b7f5-add5fd7c8258","data":"custom data"},{"uuid":"7a27e459-0201-4316-b4ea-84061707e357","data":"custom data"}]
08-12 11:34:53.618  3769  3819 I jxcore-log: 
,08-12 11:34:53.620  3769  3819 I jxcore-log: ok 115 test participant has uuid
08-12 11:34:53.620  3769  3819 I jxcore-log: 
08-12 11:34:53.620  3769  3819 I jxcore-log: ok 116 participant data matches
08-12 11:34:53.620  3769  3819 I jxcore-log: 
,08-12 11:34:53.621  3769  3819 I jxcore-log: ok 117 test participant has uuid
08-12 11:34:53.621  3769  3819 I jxcore-log: 
08-12 11:34:53.621  3769  3819 I jxcore-log: ok 118 participant data matches
08-12 11:34:53.621  3769  3819 I jxcore-log: 
,08-12 11:34:53.622  3769  3819 I jxcore-log: ok 119 own UUID is found from the participants list
08-12 11:34:53.622  3769  3819 I jxcore-log: 
08-12 11:34:53.625  3769  3819 I jxcore-log: # teardown
08-12 11:34:53.625  3769  3819 I jxcore-log: 
,08-12 11:34:53.682  3769  3819 I jxcore-log: # setup
08-12 11:34:53.682  3769  3819 I jxcore-log: 
,08-12 11:34:53.726  3769  3819 I jxcore-log: # 42. #startListeningForAdvertisements should fail if start not called
08-12 11:34:53.726  3769  3819 I jxcore-log: 
,08-12 11:34:53.782  3769  3819 I jxcore-log: ok 120 specific error should be returned
08-12 11:34:53.782  3769  3819 I jxcore-log: 
,08-12 11:34:53.785  3769  3819 I jxcore-log: # teardown
08-12 11:34:53.785  3769  3819 I jxcore-log: 
,08-12 11:34:53.839  3769  3819 I jxcore-log: ok 121 error should be null
08-12 11:34:53.839  3769  3819 I jxcore-log: 
,08-12 11:34:53.840  3769  3819 I jxcore-log: ok 122 error should be null
08-12 11:34:53.840  3769  3819 I jxcore-log: 
,08-12 11:34:53.843  3769  3819 I jxcore-log: # setup
08-12 11:34:53.843  3769  3819 I jxcore-log: 
,08-12 11:34:53.914  3769  3819 I jxcore-log: # 43. #startUpdateAdvertisingAndListening should fail if start not called
08-12 11:34:53.914  3769  3819 I jxcore-log: 
,08-12 11:34:53.973  3769  3819 I jxcore-log: ok 123 specific error should be returned
08-12 11:34:53.973  3769  3819 I jxcore-log: 
,08-12 11:34:53.978  3769  3819 I jxcore-log: # teardown
08-12 11:34:53.978  3769  3819 I jxcore-log: 
,08-12 11:34:54.091  3769  3819 I jxcore-log: ok 124 error should be null
08-12 11:34:54.091  3769  3819 I jxcore-log: 
,08-12 11:34:54.092  3769  3819 I jxcore-log: ok 125 error should be null
08-12 11:34:54.092  3769  3819 I jxcore-log: 
,08-12 11:34:54.094  3769  3819 I jxcore-log: # setup
08-12 11:34:54.094  3769  3819 I jxcore-log: 
,08-12 11:34:54.132  3769  3819 I jxcore-log: # 44. should be able to call #stopListeningForAdvertisements many times
08-12 11:34:54.132  3769  3819 I jxcore-log: 
,08-12 11:34:54.241  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:34:54.241  3769  3819 I jxcore-log: 
,08-12 11:34:54.244  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 39837
08-12 11:34:54.244  3769  3819 I jxcore-log: 
,08-12 11:34:54.248  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 11:34:54.248  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:34:54.248  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:34:54.248  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:54.252  3769  3819 I jxcore-log: ok 126 error should be null
,08-12 11:34:54.252  3769  3819 I jxcore-log: 
08-12 11:34:54.252  3769  3819 I jxcore-log: ok 127 error should be null
08-12 11:34:54.252  3769  3819 I jxcore-log: 
08-12 11:34:54.254  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 11:34:54.254  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:34:54.254  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-12 11:34:54.254  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 11:34:54.257  3769  3819 I jxcore-log: ok 128 error should be null
08-12 11:34:54.257  3769  3819 I jxcore-log: 
08-12 11:34:54.258  3769  3819 I jxcore-log: ok 129 error should be null
08-12 11:34:54.258  3769  3819 I jxcore-log: 
,08-12 11:34:54.262  3769  3819 I jxcore-log: # teardown
08-12 11:34:54.262  3769  3819 I jxcore-log: 
,08-12 11:34:54.362  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening,
08-12 11:34:54.363  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:34:54.363  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:34:54.363  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:54.368  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 11:34:54.369  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:34:54.369  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:34:54.369  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:54.376  3769  3819 I jxcore-log: ok 130 error should be null
08-12 11:34:54.376  3769  3819 I jxcore-log: 
,08-12 11:34:54.377  3769  3819 I jxcore-log: ok 131 error should be null
08-12 11:34:54.377  3769  3819 I jxcore-log: 
,08-12 11:34:54.383  3769  3819 I jxcore-log: # setup
08-12 11:34:54.383  3769  3819 I jxcore-log: 
,08-12 11:34:54.413  3769  3819 I jxcore-log: # 45. should be able to call #startListeningForAdvertisements many times
08-12 11:34:54.413  3769  3819 I jxcore-log: 
,08-12 11:34:54.498  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:34:54.498  3769  3819 I jxcore-log: 
,08-12 11:34:54.501  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 44746
08-12 11:34:54.501  3769  3819 I jxcore-log: 
,08-12 11:34:54.506  3769  3819 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 11:34:54.510  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 49883, start advertisements: false
,08-12 11:34:54.510  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 11:34:54.510  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 11:34:54.510  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-12 11:34:54.510  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-12 11:34:54.510  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 11:34:54.510  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-12 11:34:54.513  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-12 11:34:54.513  3769  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 11:34:54.518  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 11:34:54.519  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 11:34:54.519  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 11:34:54.523  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 11:34:54.523  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 11:34:54.523  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 11:34:54.524  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:34:54.527  2638  2651 D BtGatt.GattService: registerClient() - UUID=a6e42b8b-b46a-4fa5-ab89-609c318b621e
,08-12 11:34:54.527  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=a6e42b8b-b46a-4fa5-ab89-609c318b621e, clientIf=5
08-12 11:34:54.528  3769  3779 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-12 11:34:54.529  2638  2649 D BtGatt.GattService: start scan with filters
,08-12 11:34:54.533  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 11:34:54.533  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-12 11:34:54.533  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 11:34:54.533  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 11:34:54.534  2638  2679 D BtGatt.ScanManager: handling starting scan
,08-12 11:34:54.539  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 11:34:54.540  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-12 11:34:54.540  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 11:34:54.541  2638  2676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-12 11:34:54.541  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:54.542  2638  2679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-12 11:34:54.542  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 11:34:54.545  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:34:54.559  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 11:34:54.559  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:34:54.560  2638  2679 D BtGatt.ScanManager: Starting BLE batch scan
08-12 11:34:54.560  2638  2679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 11:34:54.579  2638  2676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-12 11:34:54.579  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:54.587  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 11:34:54.587  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:55.041  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-12 11:34:55.042  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 11:34:55.042  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:34:55.048  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 11:34:55.048  3769  3819 I jxcore-log: 
,08-12 11:34:55.052  3769  3819 I jxcore-log: ok 132 error should be null
08-12 11:34:55.052  3769  3819 I jxcore-log: 
,08-12 11:34:55.054  3769  3819 I jxcore-log: ok 133 error should be null
08-12 11:34:55.054  3769  3819 I jxcore-log: 
,08-12 11:34:55.063  3769  3819 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 11:34:55.070  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 49883, start advertisements: false
,08-12 11:34:55.070  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 11:34:55.071  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 11:34:55.071  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:55.072  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:34:55.078  3769  3819 I jxcore-log: ok 134 error should be null
08-12 11:34:55.078  3769  3819 I jxcore-log: 
,08-12 11:34:55.080  3769  3819 I jxcore-log: ok 135 error should be null
08-12 11:34:55.080  3769  3819 I jxcore-log: 
,08-12 11:34:55.088  3769  3819 I jxcore-log: # teardown
08-12 11:34:55.088  3769  3819 I jxcore-log: 
,08-12 11:34:55.330  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:34:55.331  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 11:34:55.331  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-12 11:34:55.331  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-12 11:34:55.332  3769  3819 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-12 11:34:55.332  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-12 11:34:55.332  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-12 11:34:55.332  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 11:34:55.333  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-12 11:34:55.333  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 11:34:55.333  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-12 11:34:55.333  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 11:34:55.336  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:34:55.338  2638  2761 D BtGatt.GattService: stopScan() - queue size =1
,08-12 11:34:55.340  2638  2651 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:34:55.341  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 11:34:55.342  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 11:34:55.342  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 11:34:55.343  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 11:34:55.343  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-12 11:34:55.346  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 11:34:55.347  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-12 11:34:55.348  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-12 11:34:55.348  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-12 11:34:55.350  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-12 11:34:55.355  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-12 11:34:55.356  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 11:34:55.357  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 11:34:55.358  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 11:34:55.359  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:34:55.359  2638  2679 D BtGatt.ScanManager: stopping BLe Batch
08-12 11:34:55.360  3769  3819 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 11:34:55.360  3769  3819 I jxcore-log: 
,08-12 11:34:55.368  2638  2638 D BtGatt.ScanManager: awakened up at time 678383
,08-12 11:34:55.374  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 11:34:55.374  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:34:55.374  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:34:55.387  1728  3918 I EventLogService: Opted in for usage reporting
,08-12 11:34:55.388  1728  3918 I EventLogService: Aggregate from 1470992520330 (log), 1470992520330 (data)
,08-12 11:34:55.391  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 11:34:55.391  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:34:55.391  2638  2676 D BtGatt.GattService: current time is 678406366965
08-12 11:34:55.391  2638  2676 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -64, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 53, 33, -121, 80, 73, -44, 1, 0, -104, 11, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 24, -13, -42, 2, 2, -29, 21, 63, 108, -49, -23, 28, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,08-12 11:34:55.391  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-12 11:34:55.391  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 24, -13, -42, 2, 2, -29, 21, 63, 108, -49, -23, 6, 8, 116, 105, 115, 54, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,08-12 11:34:55.429  1728  3918 W EventLogAggregator: Unknown tag: snet_gcore
,08-12 11:34:55.429  1728  3918 W EventLogAggregator: Unknown tag: snet_launch_service
,08-12 11:34:55.564  1728  3918 I ServiceDumpSys: dumping service [account]
,08-12 11:34:55.858  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 11:34:55.859  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:34:55.859  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-12 11:34:55.862  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 11:34:55.862  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:34:55.863  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-12 11:34:55.863  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:55.867  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 11:34:55.867  3769  3819 I jxcore-log: 
,08-12 11:34:55.883  3769  3819 I jxcore-log: ok 136 error should be null
08-12 11:34:55.883  3769  3819 I jxcore-log: 
,08-12 11:34:55.885  3769  3819 I jxcore-log: ok 137 error should be null
08-12 11:34:55.885  3769  3819 I jxcore-log: 
,08-12 11:34:55.893  3769  3819 I jxcore-log: # setup
08-12 11:34:55.893  3769  3819 I jxcore-log: 
,08-12 11:34:56.034  3769  3819 I jxcore-log: # 46. should be able to call #startUpdateAdvertisingAndListening many times
08-12 11:34:56.034  3769  3819 I jxcore-log: 
,08-12 11:34:56.119  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:34:56.119  3769  3819 I jxcore-log: 
,08-12 11:34:56.121  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 38247
08-12 11:34:56.121  3769  3819 I jxcore-log: 
,08-12 11:34:56.133  3769  3819 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 11:34:56.137  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 38247, start advertisements: true
,08-12 11:34:56.137  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 11:34:56.137  3769  3819 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,08-12 11:34:56.137  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
08-12 11:34:56.138  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-12 11:34:56.138  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-12 11:34:56.138  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-12 11:34:56.138  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 11:34:56.139  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-12 11:34:56.139  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-12 11:34:56.139  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-12 11:34:56.140  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-12 11:34:56.140  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-12 11:34:56.140  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 11:34:56.140  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
08-12 11:34:56.140  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-12 11:34:56.144  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 11:34:56.144  3769  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 11:34:56.149  3769  3920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-12 11:34:56.153  3769  3920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-12 11:34:56.154  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-12 11:34:56.157  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 11:34:56.157  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-12 11:34:56.160  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-12 11:34:56.160  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 11:34:56.160  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 F8 CF C5 D9 E5 61
,08-12 11:34:56.161  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 11:34:56.161  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 11:34:56.161  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-12 11:34:56.162  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:34:56.166  2638  2651 D BtGatt.GattService: registerClient() - UUID=7170d140-cf69-4d4e-a7c8-4e8c79833360
,08-12 11:34:56.166  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=7170d140-cf69-4d4e-a7c8-4e8c79833360, clientIf=5
08-12 11:34:56.167  3769  3779 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-12 11:34:56.168  2638  2678 D BtGatt.AdvertiseManager: message : 0
,08-12 11:34:56.174  2638  2678 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 11:34:56.190  2638  2676 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 11:34:56.200  2638  2676 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-12 11:34:56.202  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-12 11:34:56.202  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 11:34:56.207  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 11:34:56.210  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-12 11:34:56.210  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-12 11:34:56.210  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-12 11:34:56.211  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-12 11:34:56.211  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-12 11:34:56.211  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-12 11:34:56.211  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:34:56.215  3769  3769 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-12 11:34:56.215  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-12 11:34:56.715  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-12 11:34:56.716  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-12 11:34:56.716  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:34:56.722  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-12 11:34:56.722  3769  3819 I jxcore-log: 
,08-12 11:34:56.728  3769  3819 I jxcore-log: ok 138 error should be null
08-12 11:34:56.728  3769  3819 I jxcore-log: 
,08-12 11:34:56.730  3769  3819 I jxcore-log: ok 139 error should be null
08-12 11:34:56.730  3769  3819 I jxcore-log: 
,08-12 11:34:56.742  3769  3819 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 11:34:56.749  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 38247, start advertisements: true
,08-12 11:34:56.750  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-12 11:34:56.750  3769  3819 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
,08-12 11:34:56.750  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,08-12 11:34:56.752  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-12 11:34:56.752  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-12 11:34:56.752  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-12 11:34:56.752  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
08-12 11:34:56.752  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-12 11:34:56.752  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-12 11:34:56.752  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-12 11:34:56.752  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-12 11:34:56.752  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-12 11:34:56.755  2638  2678 D BtGatt.AdvertiseManager: message : 1
,08-12 11:34:56.756  2638  2678 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-12 11:34:56.782  2638  2676 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-12 11:34:56.782  2638  2676 D BtGatt.GattService: Client app is not null!
08-12 11:34:56.784  2638  2649 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:34:56.785  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-12 11:34:56.786  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-12 11:34:56.786  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 11:34:56.786  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...,
,08-12 11:34:56.787  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 11:34:56.787  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 F8 CF C5 D9 E5 61
,08-12 11:34:56.788  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-12 11:34:56.788  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 11:34:56.789  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-12 11:34:56.790  3769  3819 D BluetoothAdapter: STATE_ON,
08-12 11:34:56.799  2638  2761 D BtGatt.GattService: registerClient() - UUID=5b7d5e43-7670-4e1c-b34d-34399c0e5785
08-12 11:34:56.800  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=5b7d5e43-7670-4e1c-b34d-34399c0e5785, clientIf=5
08-12 11:34:56.801  3769  3780 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-12 11:34:56.804  2638  2678 D BtGatt.AdvertiseManager: message : 0
,08-12 11:34:56.810  2638  2678 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 11:34:56.829  2638  2676 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 11:34:56.838  2638  2676 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-12 11:34:56.839  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-12 11:34:56.839  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-12 11:34:56.839  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-12 11:34:56.839  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-12 11:34:56.839  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 11:34:56.840  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-12 11:34:56.840  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-12 11:34:56.840  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 11:34:56.840  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:34:56.857  3769  3819 I jxcore-log: ok 140 error should be null
08-12 11:34:56.857  3769  3819 I jxcore-log: 
,08-12 11:34:56.859  3769  3819 I jxcore-log: ok 141 error should be null
08-12 11:34:56.859  3769  3819 I jxcore-log: 
,08-12 11:34:56.866  3769  3819 I jxcore-log: # teardown
08-12 11:34:56.866  3769  3819 I jxcore-log: 
,08-12 11:34:57.267  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:34:57.267  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 11:34:57.268  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-12 11:34:57.268  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-12 11:34:57.268  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-12 11:34:57.268  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-12 11:34:57.269  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-12 11:34:57.269  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-12 11:34:57.269  3769  3920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-12 11:34:57.269  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-12 11:34:57.269  3769  3920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-12 11:34:57.270  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-12 11:34:57.270  3769  3920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-12 11:34:57.270  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 11:34:57.270  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-12 11:34:57.270  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-12 11:34:57.270  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 11:34:57.270  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-12 11:34:57.273  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:34:57.273  3769  3819 D BluetoothLeScanner: could not find callback wrapper
,08-12 11:34:57.274  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 11:34:57.274  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-12 11:34:57.276  2638  2678 D BtGatt.AdvertiseManager: message : 1
08-12 11:34:57.277  2638  2678 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-12 11:34:57.295  2638  2676 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-12 11:34:57.295  2638  2676 D BtGatt.GattService: Client app is not null!
,08-12 11:34:57.297  2638  2649 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:34:57.298  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-12 11:34:57.298  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-12 11:34:57.298  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-12 11:34:57.299  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-12 11:34:57.299  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-12 11:34:57.301  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:34:57.302  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-12 11:34:57.302  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-12 11:34:57.303  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-12 11:34:57.306  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 11:34:57.306  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:34:57.307  3769  3769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-12 11:34:57.308  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 11:34:57.308  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 11:34:57.308  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 11:34:57.309  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 11:34:57.309  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:34:57.309  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:34:57.310  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:57.317  3769  3819 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 11:34:57.317  3769  3819 I jxcore-log: 
,08-12 11:34:57.331  3769  3819 I jxcore-log: ok 142 error should be null
08-12 11:34:57.331  3769  3819 I jxcore-log: 
,08-12 11:34:57.331  3769  3819 I jxcore-log: ok 143 error should be null
08-12 11:34:57.331  3769  3819 I jxcore-log: 
,08-12 11:34:57.337  3769  3819 I jxcore-log: # setup
08-12 11:34:57.337  3769  3819 I jxcore-log: 
,08-12 11:34:57.399  3769  3819 I jxcore-log: # 47. should be able to call #stopAdvertisingAndListening many times
08-12 11:34:57.399  3769  3819 I jxcore-log: 
,08-12 11:34:57.493  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:34:57.493  3769  3819 I jxcore-log: 
,08-12 11:34:57.495  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 40281
08-12 11:34:57.495  3769  3819 I jxcore-log: 
,08-12 11:34:57.499  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:34:57.499  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:34:57.499  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:34:57.499  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:57.502  3769  3819 I jxcore-log: ok 144 error should be null
08-12 11:34:57.502  3769  3819 I jxcore-log: 
,08-12 11:34:57.503  3769  3819 I jxcore-log: ok 145 error should be null
08-12 11:34:57.503  3769  3819 I jxcore-log: 
,08-12 11:34:57.505  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:34:57.505  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:34:57.505  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:34:57.505  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:57.509  3769  3819 I jxcore-log: ok 146 error should be null
08-12 11:34:57.509  3769  3819 I jxcore-log: 
,08-12 11:34:57.509  3769  3819 I jxcore-log: ok 147 error should be null
08-12 11:34:57.509  3769  3819 I jxcore-log: 
,08-12 11:34:57.515  3769  3819 I jxcore-log: # teardown
08-12 11:34:57.515  3769  3819 I jxcore-log: 
,08-12 11:34:57.581  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:34:57.581  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:34:57.581  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:34:57.581  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:57.585  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 11:34:57.585  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-12 11:34:57.586  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:34:57.586  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:57.591  3769  3819 I jxcore-log: ok 148 error should be null
08-12 11:34:57.591  3769  3819 I jxcore-log: 
,08-12 11:34:57.592  3769  3819 I jxcore-log: ok 149 error should be null
08-12 11:34:57.592  3769  3819 I jxcore-log: 
,08-12 11:34:57.599  3769  3819 I jxcore-log: # setup
08-12 11:34:57.599  3769  3819 I jxcore-log: 
,08-12 11:34:57.657  3769  3819 I jxcore-log: # 48. #start should fail if called twice in a row
08-12 11:34:57.657  3769  3819 I jxcore-log: 
,08-12 11:34:57.740  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:34:57.740  3769  3819 I jxcore-log: 
,08-12 11:34:57.743  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 43603
08-12 11:34:57.743  3769  3819 I jxcore-log: 
,08-12 11:34:57.746  3769  3819 I jxcore-log: ok 150 first call should succeed
08-12 11:34:57.746  3769  3819 I jxcore-log: 
,08-12 11:34:57.747  3769  3819 I jxcore-log: ok 151 first call should succeed
08-12 11:34:57.747  3769  3819 I jxcore-log: 
,08-12 11:34:57.749  3769  3819 I jxcore-log: ok 152 specific error should be returned
08-12 11:34:57.749  3769  3819 I jxcore-log: 
,08-12 11:34:57.752  3769  3819 I jxcore-log: # teardown
08-12 11:34:57.752  3769  3819 I jxcore-log: 
,08-12 11:34:57.808  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:34:57.808  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:34:57.808  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:34:57.808  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:57.809  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-12 11:34:57.810  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 11:34:57.810  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-12 11:34:57.810  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:34:57.810  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:57.813  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 11:34:57.813  3769  3819 I jxcore-log: 
,08-12 11:34:57.817  3769  3819 I jxcore-log: ok 153 error should be null
08-12 11:34:57.817  3769  3819 I jxcore-log: 
,08-12 11:34:57.818  3769  3819 I jxcore-log: ok 154 error should be null
08-12 11:34:57.818  3769  3819 I jxcore-log: 
,08-12 11:34:57.823  3769  3819 I jxcore-log: # setup
08-12 11:34:57.823  3769  3819 I jxcore-log: 
,08-12 11:34:57.869  3769  3819 I jxcore-log: # 49. does not emit duplicate discoveryAdvertisingStateUpdate
08-12 11:34:57.869  3769  3819 I jxcore-log: 
,08-12 11:34:57.944  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:34:57.944  3769  3819 I jxcore-log: 
,08-12 11:34:57.949  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 44661
08-12 11:34:57.949  3769  3819 I jxcore-log: 
,08-12 11:34:57.953  3769  3819 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 11:34:57.957  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 38247, start advertisements: false
,08-12 11:34:57.957  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-12 11:34:57.957  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 11:34:57.957  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-12 11:34:57.957  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-12 11:34:57.957  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 11:34:57.957  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-12 11:34:57.964  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 11:34:57.964  3769  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 11:34:57.971  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 11:34:57.972  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 11:34:57.973  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 11:34:57.979  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 11:34:57.980  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-12 11:34:57.980  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 11:34:57.981  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:34:57.984  2638  2761 D BtGatt.GattService: registerClient() - UUID=8c18561f-8eef-4ec1-b7a3-0e7a17bccd9c
08-12 11:34:57.985  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=8c18561f-8eef-4ec1-b7a3-0e7a17bccd9c, clientIf=5
,08-12 11:34:57.986  3769  3780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-12 11:34:57.987  2638  2649 D BtGatt.GattService: start scan with filters
,08-12 11:34:57.991  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 11:34:57.991  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 11:34:57.991  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 11:34:57.991  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-12 11:34:57.991  2638  2679 D BtGatt.ScanManager: handling starting scan
08-12 11:34:57.994  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 11:34:57.994  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-12 11:34:57.994  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 11:34:57.996  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 11:34:58.000  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:34:58.010  2638  2676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-12 11:34:58.010  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:58.011  2638  2679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 11:34:58.027  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 11:34:58.027  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:58.028  2638  2679 D BtGatt.ScanManager: Starting BLE batch scan
08-12 11:34:58.028  2638  2679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 11:34:58.044  2638  2676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
08-12 11:34:58.044  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:58.055  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 11:34:58.055  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:58.496  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-12 11:34:58.496  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 11:34:58.497  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:34:58.502  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 11:34:58.502  3769  3819 I jxcore-log: 
,08-12 11:34:58.532  3769  3819 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 11:34:58.536  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 44661, start advertisements: true
,08-12 11:34:58.536  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 11:34:58.536  3769  3819 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
08-12 11:34:58.536  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
08-12 11:34:58.536  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-12 11:34:58.536  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-12 11:34:58.536  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-12 11:34:58.536  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 4
08-12 11:34:58.536  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-12 11:34:58.536  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-12 11:34:58.536  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-12 11:34:58.536  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-12 11:34:58.536  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-12 11:34:58.537  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-12 11:34:58.537  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 11:34:58.537  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:34:58.538  2638  2651 D BtGatt.GattService: stopScan() - queue size =1
08-12 11:34:58.539  2638  2761 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:34:58.539  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 11:34:58.539  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-12 11:34:58.539  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 11:34:58.539  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 11:34:58.539  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 11:34:58.539  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-12 11:34:58.540  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:34:58.547  2638  2649 D BtGatt.GattService: registerClient() - UUID=dd06a777-8264-42fb-a94c-7bcbbebee3cc
08-12 11:34:58.548  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=dd06a777-8264-42fb-a94c-7bcbbebee3cc, clientIf=5
08-12 11:34:58.549  3769  3779 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-12 11:34:58.551  2638  2651 D BtGatt.GattService: start scan with filters
,08-12 11:34:58.558  2638  2638 D BtGatt.ScanManager: awakened up at time 681573
,08-12 11:34:58.560  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 11:34:58.560  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 11:34:58.560  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-12 11:34:58.560  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-12 11:34:58.560  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-12 11:34:58.561  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 11:34:58.562  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-12 11:34:58.563  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-12 11:34:58.563  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-12 11:34:58.564  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-12 11:34:58.564  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-12 11:34:58.564  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-12 11:34:58.564  3769  3923 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-12 11:34:58.564  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-12 11:34:58.564  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-12 11:34:58.569  3769  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-12 11:34:58.569  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:34:58.569  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 11:34:58.569  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:34:58.570  2638  2679 D BtGatt.ScanManager: stopping BLe Batch
08-12 11:34:58.570  2638  2649 D BtGatt.GattService: stopScan() - queue size =0
08-12 11:34:58.570  2638  2761 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 11:34:58.571  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 11:34:58.571  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 11:34:58.571  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 11:34:58.571  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 11:34:58.571  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-12 11:34:58.572  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:34:58.573  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 11:34:58.576  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-12 11:34:58.576  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 11:34:58.576  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 F8 CF C5 D9 E5 61
,08-12 11:34:58.576  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 11:34:58.576  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 11:34:58.577  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-12 11:34:58.577  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:34:58.578  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-12 11:34:58.578  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:34:58.578  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:34:58.580  2638  2761 D BtGatt.GattService: registerClient() - UUID=a634e817-5f51-47e0-abb7-6bb8eecee78c
08-12 11:34:58.580  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=a634e817-5f51-47e0-abb7-6bb8eecee78c, clientIf=5
,08-12 11:34:58.583  3769  3780 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-12 11:34:58.585  2638  2678 D BtGatt.AdvertiseManager: message : 0
,08-12 11:34:58.587  2638  2678 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 11:34:58.589  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 11:34:58.589  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:34:58.589  2638  2676 D BtGatt.GattService: current time is 681604948012
,08-12 11:34:58.590  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -82, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -80, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:34:58.590  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:34:58.590  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:34:58.590  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 11:34:58.591  2638  2679 D BtGatt.ScanManager: handling starting scan
,08-12 11:34:58.598  2638  2676 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 11:34:58.602  2638  2676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 11:34:58.602  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:34:58.603  2638  2679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 11:34:58.607  2638  2676 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-12 11:34:58.607  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-12 11:34:58.607  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-12 11:34:58.609  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 11:34:58.610  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:34:58.610  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-12 11:34:58.610  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 11:34:58.610  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess,
08-12 11:34:58.610  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-12 11:34:58.610  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-12 11:34:58.610  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-12 11:34:58.610  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING],
08-12 11:34:58.612  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-12 11:34:58.612  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:58.612  2638  2679 D BtGatt.ScanManager: Starting BLE batch scan
08-12 11:34:58.612  2638  2679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 11:34:58.614  3769  3769 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-12 11:34:58.614  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-12 11:34:58.622  2638  2676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-12 11:34:58.622  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:58.627  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 11:34:58.627  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:58.635  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 11:34:58.635  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:34:58.635  2638  2679 D BtGatt.ScanManager: stopping BLe Batch
,08-12 11:34:58.641  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 11:34:58.641  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:34:58.642  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:34:58.648  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:34:58.648  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:34:59.115  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-12 11:34:59.115  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-12 11:34:59.116  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:34:59.121  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-12 11:34:59.121  3769  3819 I jxcore-log: 
,08-12 11:34:59.141  3769  3819 I jxcore-log: ok 155 called only once
08-12 11:34:59.141  3769  3819 I jxcore-log: 
,08-12 11:34:59.143  3769  3819 I jxcore-log: ok 156 discovery state matches
08-12 11:34:59.143  3769  3819 I jxcore-log: 
,08-12 11:34:59.143  3769  3819 I jxcore-log: ok 157 advertising state matches
08-12 11:34:59.143  3769  3819 I jxcore-log: 
,08-12 11:34:59.149  3769  3819 I jxcore-log: # teardown
08-12 11:34:59.149  3769  3819 I jxcore-log: 
,08-12 11:34:59.616  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:34:59.616  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:34:59.617  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-12 11:34:59.617  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-12 11:34:59.617  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-12 11:34:59.618  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-12 11:34:59.618  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-12 11:34:59.620  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-12 11:34:59.620  3769  3923 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-12 11:34:59.620  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-12 11:34:59.620  3769  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-12 11:34:59.620  3769  3923 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-12 11:34:59.620  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-12 11:34:59.621  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-12 11:34:59.621  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 11:34:59.621  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-12 11:34:59.622  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 11:34:59.622  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-12 11:34:59.625  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:34:59.625  3769  3819 D BluetoothLeScanner: could not find callback wrapper
08-12 11:34:59.625  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 11:34:59.625  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-12 11:34:59.628  2638  2678 D BtGatt.AdvertiseManager: message : 1
,08-12 11:34:59.629  2638  2678 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-12 11:34:59.643  2638  2676 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-12 11:34:59.644  2638  2676 D BtGatt.GattService: Client app is not null!
,08-12 11:34:59.646  2638  2761 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:34:59.647  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-12 11:34:59.647  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-12 11:34:59.647  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-12 11:34:59.648  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-12 11:34:59.648  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-12 11:34:59.652  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 11:34:59.652  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-12 11:34:59.652  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-12 11:34:59.654  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-12 11:34:59.657  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:34:59.657  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:34:59.657  3769  3769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-12 11:34:59.658  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 11:34:59.658  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 11:34:59.658  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:34:59.659  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 11:34:59.659  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:34:59.659  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-12 11:34:59.659  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:34:59.664  3769  3819 I jxcore-log: INFO thaliMobile: Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
08-12 11:34:59.664  3769  3819 I jxcore-log: 
,08-12 11:34:59.665  3769  3819 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 11:34:59.665  3769  3819 I jxcore-log: 
08-12 11:34:59.666  3769  3819 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 11:34:59.666  3769  3819 I jxcore-log: 
,08-12 11:34:59.673  3769  3819 I jxcore-log: ok 158 error should be null
08-12 11:34:59.673  3769  3819 I jxcore-log: 
,08-12 11:34:59.673  3769  3819 I jxcore-log: ok 159 error should be null
08-12 11:34:59.673  3769  3819 I jxcore-log: 
,08-12 11:34:59.679  3769  3819 I jxcore-log: # setup
08-12 11:34:59.679  3769  3819 I jxcore-log: 
,08-12 11:34:59.732  3769  3819 I jxcore-log: # 50. does not send duplicate availability changes
08-12 11:34:59.732  3769  3819 I jxcore-log: 
,08-12 11:34:59.808  3769  3819 I jxcore-log: ok 160 should be called once
08-12 11:34:59.808  3769  3819 I jxcore-log: 
,08-12 11:34:59.809  3769  3819 I jxcore-log: ok 161 should not have been called more than once
08-12 11:34:59.809  3769  3819 I jxcore-log: 
,08-12 11:34:59.812  3769  3819 I jxcore-log: # teardown
08-12 11:34:59.812  3769  3819 I jxcore-log: 
,08-12 11:34:59.854  3769  3819 I jxcore-log: ok 162 error should be null
08-12 11:34:59.854  3769  3819 I jxcore-log: 
,08-12 11:34:59.854  3769  3819 I jxcore-log: ok 163 error should be null
08-12 11:34:59.854  3769  3819 I jxcore-log: 
,08-12 11:34:59.856  3769  3819 I jxcore-log: # setup
08-12 11:34:59.856  3769  3819 I jxcore-log: 
,08-12 11:34:59.914  3769  3819 I jxcore-log: # 51. can get the network status
08-12 11:34:59.914  3769  3819 I jxcore-log: 
,08-12 11:34:59.972  3769  3819 I jxcore-log: ok 164 network status should have certain non-empty properties
08-12 11:34:59.972  3769  3819 I jxcore-log: 
,08-12 11:34:59.974  3769  3819 I jxcore-log: # teardown
08-12 11:34:59.974  3769  3819 I jxcore-log: 
,08-12 11:35:00.045  3769  3819 I jxcore-log: ok 165 error should be null
08-12 11:35:00.045  3769  3819 I jxcore-log: 
,08-12 11:35:00.047  3769  3819 I jxcore-log: ok 166 error should be null
08-12 11:35:00.047  3769  3819 I jxcore-log: 
,08-12 11:35:00.052  3769  3819 I jxcore-log: # setup
08-12 11:35:00.052  3769  3819 I jxcore-log: 
,08-12 11:35:00.134  3769  3819 I jxcore-log: # 52. wifi peer is marked unavailable if announcements stop
08-12 11:35:00.134  3769  3819 I jxcore-log: 
,08-12 11:35:00.159  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 11:35:00.163  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 11:35:00.163  3769  3819 I jxcore-log: 
,08-12 11:35:00.238  3769  3819 I jxcore-log: ERROR thaliMobileNativeWrapper: Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined
08-12 11:35:00.238  3769  3819 I jxcore-log: 
,08-12 11:35:00.266  3769  3819 I jxcore-log: ok 167 host address should match
08-12 11:35:00.266  3769  3819 I jxcore-log: 
,08-12 11:35:00.266  3769  3819 I jxcore-log: ok 168 port should match
08-12 11:35:00.266  3769  3819 I jxcore-log: 
,08-12 11:35:02.229  3769  3819 I jxcore-log: ok 169 host address should be null
08-12 11:35:02.229  3769  3819 I jxcore-log: 
,08-12 11:35:02.231  3769  3819 I jxcore-log: ok 170 port should should be null
08-12 11:35:02.231  3769  3819 I jxcore-log: 
,08-12 11:35:02.250  3769  3819 I jxcore-log: # teardown
08-12 11:35:02.250  3769  3819 I jxcore-log: 
,08-12 11:35:02.395  3769  3819 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 11:35:02.395  3769  3819 I jxcore-log: 
,08-12 11:35:02.397  3769  3819 I jxcore-log: ok 171 error should be null
08-12 11:35:02.397  3769  3819 I jxcore-log: 
,08-12 11:35:02.397  3769  3819 I jxcore-log: ok 172 error should be null
08-12 11:35:02.397  3769  3819 I jxcore-log: 
,08-12 11:35:02.400  3769  3819 I jxcore-log: # setup
08-12 11:35:02.400  3769  3819 I jxcore-log: 
,08-12 11:35:02.444  3769  3819 I jxcore-log: # 53. Can call start/stopListeningForAdvertisements
08-12 11:35:02.444  3769  3819 I jxcore-log: 
,08-12 11:35:02.491  3769  3819 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 11:35:02.495  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 44661, start advertisements: false
,08-12 11:35:02.495  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 11:35:02.496  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 11:35:02.496  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-12 11:35:02.496  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 11:35:02.496  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 11:35:02.496  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-12 11:35:02.502  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 11:35:02.502  3769  3819 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-12 11:35:02.512  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 11:35:02.514  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 11:35:02.514  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-12 11:35:02.523  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 11:35:02.523  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-12 11:35:02.523  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 11:35:02.525  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:35:02.531  2638  2761 D BtGatt.GattService: registerClient() - UUID=dbc193b0-928d-4c5e-a9ff-c6eaa7dde6e3
,08-12 11:35:02.532  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=dbc193b0-928d-4c5e-a9ff-c6eaa7dde6e3, clientIf=5
,08-12 11:35:02.534  3769  3779 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-12 11:35:02.535  2638  2651 D BtGatt.GattService: start scan with filters
,08-12 11:35:02.542  2638  2679 D BtGatt.ScanManager: handling starting scan
,08-12 11:35:02.542  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-12 11:35:02.543  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 11:35:02.543  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 11:35:02.543  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 11:35:02.550  2638  2676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 11:35:02.551  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:02.551  2638  2679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 11:35:02.552  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 11:35:02.553  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 11:35:02.553  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 11:35:02.558  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 11:35:02.565  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:35:02.567  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 11:35:02.568  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:02.568  2638  2679 D BtGatt.ScanManager: Starting BLE batch scan
08-12 11:35:02.568  2638  2679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 11:35:02.582  2638  2676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-12 11:35:02.582  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:02.590  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 11:35:02.590  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:03.055  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-12 11:35:03.055  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 11:35:03.056  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:35:03.060  3769  3819 I jxcore-log: ok 173 Can call startListeningForAdvertisements without error
08-12 11:35:03.060  3769  3819 I jxcore-log: 
,08-12 11:35:03.062  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 11:35:03.063  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:35:03.063  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:35:03.064  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
,08-12 11:35:03.064  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 11:35:03.064  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 11:35:03.067  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:35:03.070  2638  2649 D BtGatt.GattService: stopScan() - queue size =1
,08-12 11:35:03.073  2638  2761 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:35:03.075  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 11:35:03.075  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 11:35:03.075  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 11:35:03.076  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-12 11:35:03.076  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-12 11:35:03.078  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:35:03.079  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:35:03.082  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 11:35:03.082  3769  3819 I jxcore-log: 
,08-12 11:35:03.091  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 11:35:03.091  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:03.091  2638  2679 D BtGatt.ScanManager: stopping BLe Batch
,08-12 11:35:03.096  2638  2638 D BtGatt.ScanManager: awakened up at time 686111
,08-12 11:35:03.108  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 11:35:03.108  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:03.108  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:03.135  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-12 11:35:03.135  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:03.136  2638  2676 D BtGatt.GattService: current time is 686151231486
08-12 11:35:03.136  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:35:03.137  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:35:03.580  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 11:35:03.580  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:35:03.581  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:35:03.585  3769  3819 I jxcore-log: ok 174 Can call stopListeningForAdvertisements without error
08-12 11:35:03.585  3769  3819 I jxcore-log: 
,08-12 11:35:03.596  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 11:35:03.596  3769  3819 I jxcore-log: 
,08-12 11:35:03.602  3769  3819 I jxcore-log: # teardown
08-12 11:35:03.602  3769  3819 I jxcore-log: 
,08-12 11:35:04.034  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 11:35:04.034  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:35:04.034  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:35:04.034  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 11:35:04.036  3769  3819 I jxcore-log: ok 175 Should be able to call stopListeningForAdvertisements in teardown
08-12 11:35:04.036  3769  3819 I jxcore-log: 
,08-12 11:35:04.037  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-12 11:35:04.037  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:35:04.037  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:35:04.037  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:35:04.043  3769  3819 I jxcore-log: ok 176 Should be able to call stopAdvertisingAndListening in teardown
08-12 11:35:04.043  3769  3819 I jxcore-log: 
,08-12 11:35:04.049  3769  3819 I jxcore-log: # setup
08-12 11:35:04.049  3769  3819 I jxcore-log: 
,08-12 11:35:04.113  3769  3819 I jxcore-log: # 54. Client to server request coordinated
08-12 11:35:04.113  3769  3819 I jxcore-log: 
,08-12 11:35:04.171  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:35:04.171  3769  3819 I jxcore-log: 
,08-12 11:35:04.175  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 41325
08-12 11:35:04.175  3769  3819 I jxcore-log: 
,08-12 11:35:04.178  3769  3819 I jxcore-log: ok 177 error should be null
08-12 11:35:04.178  3769  3819 I jxcore-log: 
,08-12 11:35:04.179  3769  3819 I jxcore-log: ok 178 error should be null
08-12 11:35:04.179  3769  3819 I jxcore-log: 
,08-12 11:35:04.232  3769  3819 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 11:35:04.235  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 41325, start advertisements: true
,08-12 11:35:04.235  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
,08-12 11:35:04.235  3769  3819 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
,08-12 11:35:04.235  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 5
08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-12 11:35:04.236  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-12 11:35:04.236  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-12 11:35:04.236  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-12 11:35:04.236  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 11:35:04.236  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-12 11:35:04.237  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-12 11:35:04.237  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-12 11:35:04.237  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-12 11:35:04.237  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,08-12 11:35:04.237  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-12 11:35:04.238  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 11:35:04.253  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-12 11:35:04.253  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 11:35:04.253  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 F8 CF C5 D9 E5 61
,08-12 11:35:04.253  3769  3924 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-12 11:35:04.253  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-12 11:35:04.253  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 11:35:04.253  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-12 11:35:04.263  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:35:04.263  3769  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-12 11:35:04.273  2638  2651 D BtGatt.GattService: registerClient() - UUID=5fc6f8c0-2613-4cb4-99bd-53bf13cf7155
,08-12 11:35:04.273  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=5fc6f8c0-2613-4cb4-99bd-53bf13cf7155, clientIf=5
08-12 11:35:04.273  3769  3780 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-12 11:35:04.274  2638  2678 D BtGatt.AdvertiseManager: message : 0
,08-12 11:35:04.276  2638  2678 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 11:35:04.285  2638  2676 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 11:35:04.290  2638  2676 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-12 11:35:04.291  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
08-12 11:35:04.291  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 11:35:04.292  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 11:35:04.293  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
08-12 11:35:04.294  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-12 11:35:04.294  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-12 11:35:04.294  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-12 11:35:04.294  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true,
08-12 11:35:04.294  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-12 11:35:04.294  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-12 11:35:04.296  3769  3769 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-12 11:35:04.297  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-12 11:35:04.798  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-12 11:35:04.798  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-12 11:35:04.799  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:35:04.807  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-12 11:35:04.807  3769  3819 I jxcore-log: 
,08-12 11:35:04.820  3769  3819 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 11:35:04.828  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 41325, start advertisements: false
08-12 11:35:04.828  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 11:35:04.829  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should affect listening to advertisements only
,08-12 11:35:04.829  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-12 11:35:04.830  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-12 11:35:04.830  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-12 11:35:04.830  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-12 11:35:04.833  2638  2678 D BtGatt.AdvertiseManager: message : 1
08-12 11:35:04.834  2638  2678 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-12 11:35:04.857  2638  2676 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-12 11:35:04.857  2638  2676 D BtGatt.GattService: Client app is not null!
,08-12 11:35:04.860  2638  2651 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:35:04.862  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-12 11:35:04.862  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-12 11:35:04.862  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,08-12 11:35:04.863  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-12 11:35:04.863  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-12 11:35:04.866  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:35:04.867  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:35:04.871  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 11:35:04.884  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 11:35:04.885  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-12 11:35:04.885  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 11:35:04.887  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:35:04.894  2638  3925 D BtGatt.GattService: registerClient() - UUID=4d65d1e8-2df2-4a8a-8665-2ecf0dd5eb1e
,08-12 11:35:04.895  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=4d65d1e8-2df2-4a8a-8665-2ecf0dd5eb1e, clientIf=5
,08-12 11:35:04.895  3769  3779 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-12 11:35:04.896  2638  2649 D BtGatt.GattService: start scan with filters
,08-12 11:35:04.901  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 11:35:04.902  2638  2679 D BtGatt.ScanManager: handling starting scan
,08-12 11:35:04.902  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 11:35:04.902  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-12 11:35:04.902  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-12 11:35:04.909  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 11:35:04.909  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 11:35:04.909  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-12 11:35:04.913  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 11:35:04.917  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:35:04.921  2638  2676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 11:35:04.921  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:04.922  2638  2679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 11:35:04.937  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 11:35:04.937  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:04.937  2638  2679 D BtGatt.ScanManager: Starting BLE batch scan
,08-12 11:35:04.938  2638  2679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 11:35:04.962  2638  2676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-12 11:35:04.962  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:04.978  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 11:35:04.978  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:05.410  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-12 11:35:05.411  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 11:35:05.411  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:35:05.420  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 11:35:05.420  3769  3819 I jxcore-log: 
,08-12 11:35:05.425  3769  3819 I jxcore-log: INFO testThaliNotification: startListeningForAdvertisements
08-12 11:35:05.425  3769  3819 I jxcore-log: 
,08-12 11:35:06.483  2638  2638 D BtGatt.ScanManager: awakened up at time 689497
,08-12 11:35:06.486  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:06.520  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 11:35:06.520  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:06.520  2638  2676 D BtGatt.GattService: current time is 689535669688
,08-12 11:35:06.520  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -65, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -64, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -61, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -64, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:35:06.521  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:06.521  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 11:35:06.521  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 11:35:06.522  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:35:06.522  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:35:08.027  2638  2638 D BtGatt.ScanManager: awakened up at time 691042
08-12 11:35:08.030  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:08.077  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 11:35:08.078  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:08.079  2638  2676 D BtGatt.GattService: current time is 691093934479
,08-12 11:35:08.079  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -80, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -89, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -61, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:35:08.080  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:08.081  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:35:08.082  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:35:08.083  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 11:35:08.084  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:35:09.580  2638  2638 D BtGatt.ScanManager: awakened up at time 692595
,08-12 11:35:09.583  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:09.630  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 11:35:09.630  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:09.631  2638  2676 D BtGatt.GattService: current time is 692646317758
08-12 11:35:09.631  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -80, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:35:09.632  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:35:09.633  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:35:11.135  2638  2638 D BtGatt.ScanManager: awakened up at time 694150
,08-12 11:35:11.137  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:11.147  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:11.147  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:12.652  2638  2638 D BtGatt.ScanManager: awakened up at time 695667
,08-12 11:35:12.654  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:12.722  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:35:12.723  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:12.723  2638  2676 D BtGatt.GattService: current time is 695738723275
08-12 11:35:12.724  2638  2676 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -91, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -66, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -91, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -90, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:35:12.726  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:35:12.727  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:35:12.728  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 11:35:12.729  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:35:12.730  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:12.730  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:35:14.228  2638  2638 D BtGatt.ScanManager: awakened up at time 697243
08-12 11:35:14.231  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:14.268  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
08-12 11:35:14.268  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:14.269  2638  2676 D BtGatt.GattService: current time is 697283947439
,08-12 11:35:14.269  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -66, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:14.270  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 11:35:14.271  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:35:15.765  2638  2638 D BtGatt.ScanManager: awakened up at time 698780
,08-12 11:35:15.770  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:15.780  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:15.780  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:17.289  2638  2638 D BtGatt.ScanManager: awakened up at time 700304
,08-12 11:35:17.292  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:17.321  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 11:35:17.321  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:17.322  2638  2676 D BtGatt.GattService: current time is 700337411024
08-12 11:35:17.322  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -65, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -63, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
08-12 11:35:17.323  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-12 11:35:17.324  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 11:35:18.824  2638  2638 D BtGatt.ScanManager: awakened up at time 701839
08-12 11:35:18.829  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:18.880  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:35:18.880  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:18.881  2638  2676 D BtGatt.GattService: current time is 701896168836
08-12 11:35:18.882  2638  2676 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -80, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -64, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -65, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 53, 33, -121, 80, 73, -44, 1, -128, -105, 13, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 48, -13, -42, 2, 2, -29, 21, 63, -55, 84, -11, 0]
,08-12 11:35:18.883  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 11:35:18.884  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-12 11:35:18.885  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:35:18.886  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 11:35:18.886  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:18.887  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -59, -60, 94, 117, -73, -4, -67, 70, 48, -13, -42, 2, 2, -29, 21, 63, -55, 84, -11]
,08-12 11:35:20.384  2638  2638 D BtGatt.ScanManager: awakened up at time 703399
,08-12 11:35:20.387  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:20.397  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 11:35:20.398  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:21.902  2638  2638 D BtGatt.ScanManager: awakened up at time 704917
,08-12 11:35:21.906  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:21.936  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-12 11:35:21.936  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:21.937  2638  2676 D BtGatt.GattService: current time is 704952310547
08-12 11:35:21.937  2638  2676 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:35:21.938  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:35:23.441  2638  2638 D BtGatt.ScanManager: awakened up at time 706456
08-12 11:35:23.444  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:23.494  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:35:23.494  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:23.495  2638  2676 D BtGatt.GattService: current time is 706509930337
08-12 11:35:23.496  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -63, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -69, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -63, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -78, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:35:23.496  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:35:23.499  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:35:23.500  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:23.501  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 11:35:23.502  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-12 11:35:23.503  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:35:24.999  2638  2638 D BtGatt.ScanManager: awakened up at time 708014
,08-12 11:35:25.002  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:25.013  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 11:35:25.014  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:26.516  2638  2638 D BtGatt.ScanManager: awakened up at time 709531
,08-12 11:35:26.521  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:26.531  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:26.531  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:28.034  2638  2638 D BtGatt.ScanManager: awakened up at time 711049
,08-12 11:35:28.037  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:28.077  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 11:35:28.078  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-12 11:35:28.078  2638  2676 D BtGatt.GattService: current time is 711093721367
,08-12 11:35:28.079  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -66, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -71, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -82, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -92, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:35:28.080  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 11:35:28.081  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 11:35:28.082  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:28.082  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:35:28.083  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:35:29.582  2638  2638 D BtGatt.ScanManager: awakened up at time 712597
,08-12 11:35:29.586  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:29.607  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 11:35:29.607  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:29.607  2638  2676 D BtGatt.GattService: current time is 712622868186
08-12 11:35:29.608  2638  2676 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -71, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:35:29.609  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 11:35:29.609  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:35:31.115  2638  2638 D BtGatt.ScanManager: awakened up at time 714130
,08-12 11:35:31.118  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:31.126  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:31.127  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:32.630  2638  2638 D BtGatt.ScanManager: awakened up at time 715645
,08-12 11:35:32.633  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:32.664  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-12 11:35:32.664  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:32.665  2638  2676 D BtGatt.GattService: current time is 715680508907
,08-12 11:35:32.666  2638  2676 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -63, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 11:35:32.667  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:35:32.668  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:32.669  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 11:35:32.669  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 11:35:34.168  2638  2638 D BtGatt.ScanManager: awakened up at time 717183
,08-12 11:35:34.170  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:34.222  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-12 11:35:34.222  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:34.222  2638  2676 D BtGatt.GattService: current time is 717237860000
08-12 11:35:34.223  2638  2676 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -62, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -82, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 50, -35, 86, -77, -92, -11, 1, -128, -103, 27, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 33, -82, -42, 2, 2, -37, 21, 61, 48, -34, -3, 0, 116, -43, -111, -91, -20, -29, 1, -128, -65, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -82, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -64, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -63, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-12 11:35:34.224  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 11:35:34.225  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:35:34.226  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 33, -82, -42, 2, 2, -37, 21, 61, 48, -34, -3]
08-12 11:35:34.227  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 11:35:34.228  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:35:34.230  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 11:35:34.233  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 11:35:35.724  2638  2638 D BtGatt.ScanManager: awakened up at time 718739
,08-12 11:35:35.730  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:35.741  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:35.742  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:37.242  2638  2638 D BtGatt.ScanManager: awakened up at time 720257
08-12 11:35:37.245  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:37.277  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 11:35:37.277  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:37.278  2638  2676 D BtGatt.GattService: current time is 720293109002
08-12 11:35:37.278  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -63, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:37.279  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:35:37.280  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:35:38.781  2638  2638 D BtGatt.ScanManager: awakened up at time 721796
,08-12 11:35:38.784  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:38.835  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:35:38.835  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:38.835  2638  2676 D BtGatt.GattService: current time is 721850902907
,08-12 11:35:38.836  2638  2676 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -90, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -64, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -62, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -79, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:35:38.839  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:35:38.842  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:35:38.844  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:35:38.846  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-12 11:35:38.848  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:35:38.850  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:35:40.337  2638  2638 D BtGatt.ScanManager: awakened up at time 723352
,08-12 11:35:40.342  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:40.352  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:40.352  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:41.854  2638  2638 D BtGatt.ScanManager: awakened up at time 724869
,08-12 11:35:41.861  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:41.869  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:41.870  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:43.371  2638  2638 D BtGatt.ScanManager: awakened up at time 726386
,08-12 11:35:43.376  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:43.418  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:35:43.418  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:43.419  2638  2676 D BtGatt.GattService: current time is 726434176176
08-12 11:35:43.420  2638  2676 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -71, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -64, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -85, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -90, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -69, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
08-12 11:35:43.420  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:35:43.421  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:43.422  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:35:43.423  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:35:43.424  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:35:43.426  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-12 11:35:44.927  2638  2638 D BtGatt.ScanManager: awakened up at time 727942
,08-12 11:35:44.932  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:44.942  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:44.942  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:46.444  2638  2638 D BtGatt.ScanManager: awakened up at time 729459
,08-12 11:35:46.447  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:46.458  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:46.459  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:47.963  2638  2638 D BtGatt.ScanManager: awakened up at time 730978
,08-12 11:35:47.968  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:48.020  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:35:48.020  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:48.023  2638  2676 D BtGatt.GattService: current time is 731037703822
,08-12 11:35:48.024  2638  2676 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -63, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -63, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -64, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -81, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:35:48.026  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:35:48.028  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:35:48.029  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 11:35:48.030  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 11:35:48.031  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:35:48.032  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:35:49.522  2638  2638 D BtGatt.ScanManager: awakened up at time 732537
,08-12 11:35:49.525  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:49.555  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
08-12 11:35:49.555  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:49.556  2638  2676 D BtGatt.GattService: current time is 732571119965
08-12 11:35:49.556  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -83, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -81, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-12 11:35:49.557  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:35:49.558  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:35:49.559  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 11:35:51.059  2638  2638 D BtGatt.ScanManager: awakened up at time 734074
,08-12 11:35:51.063  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:51.074  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:51.074  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:52.577  2638  2638 D BtGatt.ScanManager: awakened up at time 735592
,08-12 11:35:52.579  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:52.615  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 11:35:52.615  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:52.616  2638  2676 D BtGatt.GattService: current time is 735631082509
,08-12 11:35:52.616  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -89, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -78, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:35:52.617  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:35:52.618  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 11:35:52.619  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:35:54.118  2638  2638 D BtGatt.ScanManager: awakened up at time 737133
,08-12 11:35:54.120  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:54.152  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 11:35:54.153  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:54.155  2638  2676 D BtGatt.GattService: current time is 737170479485
,08-12 11:35:54.156  2638  2676 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -62, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
08-12 11:35:54.157  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113],
08-12 11:35:54.158  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:35:54.159  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 11:35:55.655  2638  2638 D BtGatt.ScanManager: awakened up at time 738670
,08-12 11:35:55.658  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:55.672  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:35:55.672  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:57.171  2638  2638 D BtGatt.ScanManager: awakened up at time 740186
,08-12 11:35:57.173  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:57.209  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 11:35:57.210  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:35:57.210  2638  2676 D BtGatt.GattService: current time is 740225742915
08-12 11:35:57.211  2638  2676 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -70, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:35:57.213  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 11:35:57.214  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:35:57.215  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:35:58.712  2638  2638 D BtGatt.ScanManager: awakened up at time 741727
,08-12 11:35:58.715  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:35:58.770  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:35:58.770  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:35:58.773  2638  2676 D BtGatt.GattService: current time is 741787955883
,08-12 11:35:58.776  2638  2676 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -91, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -83, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -90, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -90, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -63, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:35:58.777  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:35:58.778  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:35:58.779  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:35:58.780  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:35:58.781  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 11:35:58.782  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:36:00.276  2638  2638 D BtGatt.ScanManager: awakened up at time 743291
,08-12 11:36:00.279  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:00.294  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:00.294  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:01.796  2638  2638 D BtGatt.ScanManager: awakened up at time 744811
,08-12 11:36:01.799  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:01.810  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 11:36:01.811  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:03.317  2638  2638 D BtGatt.ScanManager: awakened up at time 746331
,08-12 11:36:03.319  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:03.348  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-12 11:36:03.348  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:03.349  2638  2676 D BtGatt.GattService: current time is 746364250037
08-12 11:36:03.350  2638  2676 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -81, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -81, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -81, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:36:03.351  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:36:03.352  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:03.352  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:36:03.353  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 11:36:03.354  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:36:03.355  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:36:04.854  2638  2638 D BtGatt.ScanManager: awakened up at time 747869
,08-12 11:36:04.856  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:04.867  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:04.867  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:06.370  2638  2638 D BtGatt.ScanManager: awakened up at time 749385
,08-12 11:36:06.373  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:06.386  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:06.386  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:07.890  2638  2638 D BtGatt.ScanManager: awakened up at time 750905
,08-12 11:36:07.893  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:07.943  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 11:36:07.943  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:36:07.944  2638  2676 D BtGatt.GattService: current time is 750959073515
,08-12 11:36:07.945  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -62, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -89, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -79, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:36:07.945  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:36:07.946  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:36:07.947  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:36:07.948  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:36:07.949  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:36:09.451  2638  2638 D BtGatt.ScanManager: awakened up at time 752466
,08-12 11:36:09.454  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:09.487  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 11:36:09.488  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:36:09.488  2638  2676 D BtGatt.GattService: current time is 752503887315
,08-12 11:36:09.489  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -62, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -90, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -81, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:36:09.490  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 11:36:09.491  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:36:09.492  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:36:10.990  2638  2638 D BtGatt.ScanManager: awakened up at time 754005
08-12 11:36:10.993  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:11.005  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:11.005  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:12.507  2638  2638 D BtGatt.ScanManager: awakened up at time 755521
,08-12 11:36:12.509  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:12.557  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-12 11:36:12.557  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:12.558  2638  2676 D BtGatt.GattService: current time is 755573244496
,08-12 11:36:12.559  2638  2676 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -89, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -64, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -67, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -71, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -89, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:36:12.559  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:36:12.560  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:36:12.561  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 11:36:12.562  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 11:36:12.562  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:36:14.062  2638  2638 D BtGatt.ScanManager: awakened up at time 757077
08-12 11:36:14.065  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:14.110  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-12 11:36:14.110  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:14.112  2638  2676 D BtGatt.GattService: current time is 757127156994
,08-12 11:36:14.113  2638  2676 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -64, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -89, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -64, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -86, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -92, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-12 11:36:14.113  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
,08-12 11:36:14.114  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:36:14.115  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:36:14.116  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:14.117  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 11:36:15.613  2638  2638 D BtGatt.ScanManager: awakened up at time 758628
,08-12 11:36:15.616  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:15.625  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:15.625  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:17.133  2638  2638 D BtGatt.ScanManager: awakened up at time 760148
,08-12 11:36:17.137  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:17.166  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 11:36:17.166  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:17.166  2638  2676 D BtGatt.GattService: current time is 760181795163
,08-12 11:36:17.167  2638  2676 D BtGatt.GattService: Batch record : [50, -35, 86, -77, -92, -11, 1, 0, -107, 6, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 77, -82, -42, 2, 2, -37, 21, 61, 11, 22, -20, 28, 6, 8, 116, 105, 115, 55, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:17.168  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, 77, -82, -42, 2, 2, -37, 21, 61, 11, 22, -20, 6, 8, 116, 105, 115, 55, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,08-12 11:36:17.169  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:36:18.670  2638  2638 D BtGatt.ScanManager: awakened up at time 761685
,08-12 11:36:18.673  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:18.728  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:36:18.729  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:18.729  2638  2676 D BtGatt.GattService: current time is 761744586569
,08-12 11:36:18.730  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -65, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -64, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -80, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:36:18.733  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:36:18.734  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 11:36:18.735  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:36:18.736  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:36:18.737  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:18.737  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:36:20.232  2638  2638 D BtGatt.ScanManager: awakened up at time 763247
,08-12 11:36:20.234  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:20.246  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:20.247  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:21.748  2638  2638 D BtGatt.ScanManager: awakened up at time 764763
08-12 11:36:21.750  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:21.763  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:21.763  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:23.266  2638  2638 D BtGatt.ScanManager: awakened up at time 766281
,08-12 11:36:23.269  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:23.316  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:36:23.317  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:36:23.317  2638  2676 D BtGatt.GattService: current time is 766332686453
,08-12 11:36:23.318  2638  2676 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -80, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -62, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -70, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -61, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:36:23.319  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:36:23.320  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:36:23.321  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-12 11:36:23.322  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 11:36:23.322  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 11:36:23.323  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:36:24.821  2638  2638 D BtGatt.ScanManager: awakened up at time 767836
,08-12 11:36:24.823  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:24.857  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-12 11:36:24.858  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:24.858  2638  2676 D BtGatt.GattService: current time is 767873710929
08-12 11:36:24.859  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -80, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:36:24.860  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:36:26.360  2638  2638 D BtGatt.ScanManager: awakened up at time 769375
,08-12 11:36:26.363  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:26.375  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:26.375  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:27.876  2638  2638 D BtGatt.ScanManager: awakened up at time 770891
,08-12 11:36:27.881  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:27.934  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-12 11:36:27.935  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:36:27.935  2638  2676 D BtGatt.GattService: current time is 770950880246
08-12 11:36:27.936  2638  2676 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -83, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -82, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -66, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -90, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -71, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
08-12 11:36:27.937  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:36:27.938  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:36:27.939  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 11:36:27.940  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:36:27.943  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-12 11:36:29.438  2638  2638 D BtGatt.ScanManager: awakened up at time 772453
,08-12 11:36:29.442  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:29.476  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 11:36:29.477  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:36:29.477  2638  2676 D BtGatt.GattService: current time is 772492633629
08-12 11:36:29.478  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -64, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -66, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
,08-12 11:36:29.479  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 11:36:29.479  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-12 11:36:30.980  2638  2638 D BtGatt.ScanManager: awakened up at time 773995
,08-12 11:36:30.982  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:30.995  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:30.995  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:32.498  2638  2638 D BtGatt.ScanManager: awakened up at time 775513
,08-12 11:36:32.501  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:32.544  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 11:36:32.544  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:32.544  2638  2676 D BtGatt.GattService: current time is 775559793726
,08-12 11:36:32.545  2638  2676 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -66, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-12 11:36:32.545  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:36:32.545  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:32.545  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 11:36:34.052  2638  2638 D BtGatt.ScanManager: awakened up at time 777067
,08-12 11:36:34.055  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:34.109  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:36:34.109  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:36:34.110  2638  2676 D BtGatt.GattService: current time is 777125082841
08-12 11:36:34.111  2638  2676 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -64, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -65, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -81, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -66, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-12 11:36:34.112  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 11:36:34.113  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:36:34.114  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:36:34.114  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 11:36:34.115  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:34.116  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 11:36:35.613  2638  2638 D BtGatt.ScanManager: awakened up at time 778628
,08-12 11:36:35.618  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:35.625  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 11:36:35.626  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:37.130  2638  2638 D BtGatt.ScanManager: awakened up at time 780145
,08-12 11:36:37.133  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:37.167  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-12 11:36:37.167  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-12 11:36:37.168  2638  2676 D BtGatt.GattService: current time is 780183067885
,08-12 11:36:37.168  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:36:37.169  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:36:38.670  2638  2638 D BtGatt.ScanManager: awakened up at time 781685
,08-12 11:36:38.672  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:38.734  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-12 11:36:38.735  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:36:38.735  2638  2676 D BtGatt.GattService: current time is 781750506218
08-12 11:36:38.736  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -90, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -63, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -78, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -80, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -63, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:36:38.737  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:38.738  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 11:36:38.739  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 11:36:38.740  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:36:38.742  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:36:38.743  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:36:40.238  2638  2638 D BtGatt.ScanManager: awakened up at time 783253
,08-12 11:36:40.244  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:40.254  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:40.254  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:41.756  2638  2638 D BtGatt.ScanManager: awakened up at time 784771
08-12 11:36:41.759  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:41.771  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 11:36:41.771  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:43.271  2638  2638 D BtGatt.ScanManager: awakened up at time 786286
,08-12 11:36:43.273  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:43.326  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:36:43.326  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:36:43.327  2638  2676 D BtGatt.GattService: current time is 786342341571
,08-12 11:36:43.328  2638  2676 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -70, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -67, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -69, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -89, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:36:43.329  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:36:43.330  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:36:43.331  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:43.332  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:36:43.332  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-12 11:36:43.333  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:36:44.830  2638  2638 D BtGatt.ScanManager: awakened up at time 787845
,08-12 11:36:44.834  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:44.844  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:44.844  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:46.347  2638  2638 D BtGatt.ScanManager: awakened up at time 789362
,08-12 11:36:46.351  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:46.360  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:46.361  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:47.863  2638  2638 D BtGatt.ScanManager: awakened up at time 790878
,08-12 11:36:47.865  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:47.925  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:36:47.926  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:47.926  2638  2676 D BtGatt.GattService: current time is 790941545102
,08-12 11:36:47.927  2638  2676 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -81, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -65, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -64, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:36:47.928  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:47.929  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-12 11:36:47.930  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:36:47.931  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:36:47.932  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:36:47.933  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:36:49.429  2638  2638 D BtGatt.ScanManager: awakened up at time 792444
,08-12 11:36:49.436  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:49.470  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 11:36:49.470  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:36:49.471  2638  2676 D BtGatt.GattService: current time is 792486277756
,08-12 11:36:49.472  2638  2676 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -81, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -65, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
08-12 11:36:49.473  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:36:49.474  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:36:49.475  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,08-12 11:36:50.973  2638  2638 D BtGatt.ScanManager: awakened up at time 793988
,08-12 11:36:50.976  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:50.986  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 11:36:50.987  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:52.490  2638  2638 D BtGatt.ScanManager: awakened up at time 795505
,08-12 11:36:52.493  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:52.539  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-12 11:36:52.539  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:52.540  2638  2676 D BtGatt.GattService: current time is 795554993218
,08-12 11:36:52.540  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -90, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -63, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:36:52.541  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:36:52.542  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:36:52.543  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:52.544  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:36:54.042  2638  2638 D BtGatt.ScanManager: awakened up at time 797057
,08-12 11:36:54.046  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:54.096  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:36:54.096  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:54.096  2638  2676 D BtGatt.GattService: current time is 797111866186
,08-12 11:36:54.097  2638  2676 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -89, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -81, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -79, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -64, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -80, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -80, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:54.098  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-12 11:36:54.099  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:36:54.100  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:36:54.101  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-12 11:36:54.102  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:36:54.102  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:36:55.600  2638  2638 D BtGatt.ScanManager: awakened up at time 798615
,08-12 11:36:55.603  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:55.613  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:36:55.613  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:57.116  2638  2638 D BtGatt.ScanManager: awakened up at time 800131
,08-12 11:36:57.121  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:57.151  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 11:36:57.152  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:36:57.152  2638  2676 D BtGatt.GattService: current time is 800167634355
08-12 11:36:57.153  2638  2676 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -71, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -66, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:57.154  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-12 11:36:57.155  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:36:58.654  2638  2638 D BtGatt.ScanManager: awakened up at time 801669
,08-12 11:36:58.657  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:36:58.709  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:36:58.710  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:36:58.710  2638  2676 D BtGatt.GattService: current time is 801725713260
,08-12 11:36:58.711  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -90, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -84, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -88, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -71, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -86, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-12 11:36:58.712  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:36:58.713  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:36:58.714  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:36:58.715  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:36:58.716  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
08-12 11:36:58.717  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:37:00.220  2638  2638 D BtGatt.ScanManager: awakened up at time 803235
,08-12 11:37:00.222  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:37:00.231  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:37:00.232  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:37:01.736  2638  2638 D BtGatt.ScanManager: awakened up at time 804751
,08-12 11:37:01.738  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:37:01.749  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-12 11:37:01.750  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:37:03.254  2638  2638 D BtGatt.ScanManager: awakened up at time 806269
,08-12 11:37:03.256  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:37:03.292  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:37:03.292  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:37:03.292  2638  2676 D BtGatt.GattService: current time is 806307717675
08-12 11:37:03.292  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -81, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -64, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -81, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-12 11:37:03.293  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:37:03.293  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:37:03.293  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
08-12 11:37:03.293  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:37:03.294  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-12 11:37:03.294  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:37:04.800  2638  2638 D BtGatt.ScanManager: awakened up at time 807815
,08-12 11:37:04.802  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:37:04.837  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-12 11:37:04.837  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:37:04.838  2638  2676 D BtGatt.GattService: current time is 807853000381
08-12 11:37:04.838  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -82, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:37:04.839  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-12 11:37:06.341  2638  2638 D BtGatt.ScanManager: awakened up at time 809356
08-12 11:37:06.344  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:37:06.355  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 11:37:06.355  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:37:07.859  2638  2638 D BtGatt.ScanManager: awakened up at time 810874
,08-12 11:37:07.863  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:37:07.916  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-12 11:37:07.917  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:37:07.917  2638  2676 D BtGatt.GattService: current time is 810932490323
08-12 11:37:07.918  2638  2676 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -63, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -78, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -80, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -90, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -80, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -80, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:37:07.919  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:37:07.920  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-12 11:37:07.921  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:37:07.922  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:37:07.923  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:37:07.924  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-12 11:37:09.213  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
,08-12 11:37:09.214  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:37:09.214  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:37:09.216  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should affect listening to advertisements only
,08-12 11:37:09.216  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 11:37:09.216  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-12 11:37:09.221  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:37:09.223  2638  3925 D BtGatt.GattService: stopScan() - queue size =1
,08-12 11:37:09.225  2638  2649 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:37:09.226  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 11:37:09.226  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 11:37:09.226  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-12 11:37:09.227  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-12 11:37:09.227  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-12 11:37:09.230  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:37:09.230  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:37:09.235  2638  2638 D BtGatt.ScanManager: awakened up at time 812250
,08-12 11:37:09.243  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-12 11:37:09.243  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:37:09.244  2638  2679 D BtGatt.ScanManager: stopping BLe Batch
,08-12 11:37:09.259  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 11:37:09.259  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:37:09.259  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:37:09.290  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-12 11:37:09.290  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:37:09.291  2638  2676 D BtGatt.GattService: current time is 812306362960
08-12 11:37:09.292  2638  2676 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -63, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -91, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -80, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:37:09.292  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-12 11:37:09.293  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-12 11:37:09.294  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-12 11:37:09.732  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 11:37:09.733  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:37:09.733  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:37:09.748  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:37:09.749  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:37:09.749  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:37:09.749  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-12 11:37:09.750  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-12 11:37:09.750  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-12 11:37:09.750  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-12 11:37:09.752  3769  3924 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-12 11:37:09.752  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-12 11:37:09.752  3769  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-12 11:37:09.753  3769  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-12 11:37:09.753  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-12 11:37:09.754  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-12 11:37:09.754  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-12 11:37:09.755  3769  3769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-12 11:37:09.756  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-12 11:37:09.756  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-12 11:37:09.760  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:37:09.761  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:37:09.771  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 11:37:09.771  3769  3819 I jxcore-log: 
,08-12 11:37:09.778  3769  3819 I jxcore-log: not ok 179 Peer made successful https requests to all peers
08-12 11:37:09.778  3769  3819 I jxcore-log: 
,08-12 11:37:09.778  3769  3819 I jxcore-log:   ---
08-12 11:37:09.778  3769  3819 I jxcore-log: 
08-12 11:37:09.778  3769  3819 I jxcore-log:     operator: ok
08-12 11:37:09.778  3769  3819 I jxcore-log: 
08-12 11:37:09.778  3769  3819 I jxcore-log:     expected: true
08-12 11:37:09.778  3769  3819 I jxcore-log: 
08-12 11:37:09.779  3769  3819 I jxcore-log:     actual:   false
08-12 11:37:09.779  3769  3819 I jxcore-log: 
,08-12 11:37:09.779  3769  3819 I jxcore-log:   ...
08-12 11:37:09.779  3769  3819 I jxcore-log: 
08-12 11:37:09.779  3769  3819 I jxcore-log: ok 180 Peer received right amount of https requests
08-12 11:37:09.779  3769  3819 I jxcore-log: 
08-12 11:37:09.780  3769  3819 I jxcore-log: ok 181 HTTPS server received zero PSK Identities. Count:0
08-12 11:37:09.780  3769  3819 I jxcore-log: 
,08-12 11:37:09.784  3769  3819 I jxcore-log: # teardown
08-12 11:37:09.784  3769  3819 I jxcore-log: 
,08-12 11:37:10.274  3769  3819 I jxcore-log: INFO testThaliNotification: Participants:2 Peers Replied to us:0 Peers requested to:1
08-12 11:37:10.274  3769  3819 I jxcore-log: 
,08-12 11:37:10.297  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-12 11:37:10.298  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 11:37:10.298  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:37:10.298  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 11:37:10.300  3769  3819 I jxcore-log: # setup
08-12 11:37:10.300  3769  3819 I jxcore-log: 
,08-12 11:37:10.301  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 11:37:10.301  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
08-12 11:37:10.302  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:37:10.302  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:37:10.469  3769  3819 I jxcore-log: # 55. Test BEACONS_RETRIEVED_AND_PARSED locally
08-12 11:37:10.469  3769  3819 I jxcore-log: 
,08-12 11:37:10.718  3769  3819 I jxcore-log: ok 182 peerIdentifier should be identifier
08-12 11:37:10.718  3769  3819 I jxcore-log: 
,08-12 11:37:10.719  3769  3819 I jxcore-log: ok 183 Response should be BEACONS_RETRIEVED_AND_PARSED
08-12 11:37:10.719  3769  3819 I jxcore-log: 
08-12 11:37:10.719  3769  3819 I jxcore-log: ok 184 good beacon
08-12 11:37:10.719  3769  3819 I jxcore-log: 
08-12 11:37:10.720  3769  3819 I jxcore-log: ok 185 good preAmble
08-12 11:37:10.720  3769  3819 I jxcore-log: 
08-12 11:37:10.721  3769  3819 I jxcore-log: ok 186 public keys match!
08-12 11:37:10.721  3769  3819 I jxcore-log: 
,08-12 11:37:10.724  3769  3819 I jxcore-log: ok 187 must return null after successful call
08-12 11:37:10.724  3769  3819 I jxcore-log: 
08-12 11:37:10.724  3769  3819 I jxcore-log: ok 188 Once start returns the action should be in KILLED state
08-12 11:37:10.724  3769  3819 I jxcore-log: 
,08-12 11:37:10.737  3769  3819 I jxcore-log: # teardown
08-12 11:37:10.737  3769  3819 I jxcore-log: 
,08-12 11:37:10.814  3769  3819 I jxcore-log: # setup
08-12 11:37:10.814  3769  3819 I jxcore-log: 
,08-12 11:37:10.966  3769  3819 I jxcore-log: # 56. Test HTTP_BAD_RESPONSE locally
08-12 11:37:10.966  3769  3819 I jxcore-log: 
,08-12 11:37:11.220  3769  3819 I jxcore-log: ok 189 Response should be HTTP_BAD_RESPONSE
08-12 11:37:11.220  3769  3819 I jxcore-log: 
,08-12 11:37:11.223  3769  3819 I jxcore-log: ok 190 must return null after successful call
08-12 11:37:11.223  3769  3819 I jxcore-log: 
,08-12 11:37:11.238  3769  3819 I jxcore-log: # teardown
08-12 11:37:11.238  3769  3819 I jxcore-log: 
,08-12 11:37:11.609  3769  3819 I jxcore-log: # setup
08-12 11:37:11.609  3769  3819 I jxcore-log: 
,08-12 11:37:11.780  3769  3819 I jxcore-log: # 57. Test NETWORK_PROBLEM locally
08-12 11:37:11.780  3769  3819 I jxcore-log: 
,08-12 11:37:12.017  3769  3819 I jxcore-log: ok 191 Response should be NETWORK_PROBLEM
08-12 11:37:12.017  3769  3819 I jxcore-log: 
,08-12 11:37:12.028  3769  3819 I jxcore-log: ok 192 reject reason should be: Could not establish TCP connection
08-12 11:37:12.028  3769  3819 I jxcore-log: 
,08-12 11:37:12.042  3769  3819 I jxcore-log: # teardown
08-12 11:37:12.042  3769  3819 I jxcore-log: 
,08-12 11:37:12.425  3769  3819 I jxcore-log: # setup
08-12 11:37:12.425  3769  3819 I jxcore-log: 
,08-12 11:37:12.574  3769  3819 I jxcore-log: # 58. Call the start two times
08-12 11:37:12.574  3769  3819 I jxcore-log: 
,08-12 11:37:12.742  3769  3819 I jxcore-log: ok 193 Call start once
08-12 11:37:12.742  3769  3819 I jxcore-log: 
,08-12 11:37:12.876  3769  3819 I jxcore-log: ok 194 Response should be BEACONS_RETRIEVED_AND_PARSED
08-12 11:37:12.876  3769  3819 I jxcore-log: 
,08-12 11:37:12.879  3769  3819 I jxcore-log: ok 195 must return null after successful call.
08-12 11:37:12.879  3769  3819 I jxcore-log: 
,08-12 11:37:12.891  3769  3819 I jxcore-log: # teardown
08-12 11:37:12.891  3769  3819 I jxcore-log: 
,08-12 11:37:12.936  3769  3819 I jxcore-log: # setup
08-12 11:37:12.936  3769  3819 I jxcore-log: 
,08-12 11:37:13.112  3769  3819 I jxcore-log: # 59. Call the kill before calling the start
08-12 11:37:13.112  3769  3819 I jxcore-log: 
,08-12 11:37:13.550  3769  3819 I jxcore-log: ok 196 Should be Killed
08-12 11:37:13.550  3769  3819 I jxcore-log: 
,08-12 11:37:13.557  3769  3819 I jxcore-log: ok 197 Start after killed
08-12 11:37:13.557  3769  3819 I jxcore-log: 
,08-12 11:37:13.566  3769  3819 I jxcore-log: # teardown
08-12 11:37:13.566  3769  3819 I jxcore-log: 
,08-12 11:37:13.655  3769  3819 I jxcore-log: # setup
08-12 11:37:13.655  3769  3819 I jxcore-log: 
,08-12 11:37:13.810  3769  3819 I jxcore-log: # 60. Call the kill immediately after the start
08-12 11:37:13.810  3769  3819 I jxcore-log: 
,08-12 11:37:20.212  3769  3819 I jxcore-log: ok 198 Should be KILLED
08-12 11:37:20.212  3769  3819 I jxcore-log: 
,08-12 11:37:20.216  3769  3819 I jxcore-log: ok 199 must return null after successful kill
08-12 11:37:20.216  3769  3819 I jxcore-log: 
,08-12 11:37:20.228  3769  3819 I jxcore-log: # teardown
08-12 11:37:20.228  3769  3819 I jxcore-log: 
,08-12 11:37:20.265  3769  3819 I jxcore-log: # setup
08-12 11:37:20.265  3769  3819 I jxcore-log: 
,08-12 11:37:20.446  3769  3819 I jxcore-log: # 61. Call the kill while waiting a response from the server
08-12 11:37:20.446  3769  3819 I jxcore-log: 
,08-12 11:37:22.558  3769  3819 I jxcore-log: ok 200 Should be KILLED
08-12 11:37:22.558  3769  3819 I jxcore-log: 
,08-12 11:37:22.572  3769  3819 I jxcore-log: ok 201 must return null after successful kill
08-12 11:37:22.572  3769  3819 I jxcore-log: 
,08-12 11:37:22.601  3769  3819 I jxcore-log: # teardown
08-12 11:37:22.601  3769  3819 I jxcore-log: 
,08-12 11:37:22.673  3769  3819 I jxcore-log: # setup
08-12 11:37:22.673  3769  3819 I jxcore-log: 
,08-12 11:37:22.817  3769  3819 I jxcore-log: # 62. Test to exceed the max content size locally
08-12 11:37:22.817  3769  3819 I jxcore-log: 
,08-12 11:37:23.052  3769  3819 I jxcore-log: ok 202 HTTP_BAD_RESPONSE should be response when content size is exceeded
08-12 11:37:23.052  3769  3819 I jxcore-log: 
,08-12 11:37:23.066  3769  3819 I jxcore-log: ok 203 must return null after successful call
08-12 11:37:23.066  3769  3819 I jxcore-log: 
,08-12 11:37:23.085  3769  3819 I jxcore-log: # teardown
08-12 11:37:23.085  3769  3819 I jxcore-log: 
,08-12 11:37:23.115  3769  3819 I jxcore-log: # setup
08-12 11:37:23.115  3769  3819 I jxcore-log: 
,08-12 11:37:23.267  3769  3819 I jxcore-log: # 63. Close the server socket while the client is waiting a response from the server. Local test.
08-12 11:37:23.267  3769  3819 I jxcore-log: 
,08-12 11:37:25.373  3769  3819 I jxcore-log: ok 204 Should be NETWORK_PROBLEM caused closing server socket
08-12 11:37:25.373  3769  3819 I jxcore-log: 
,08-12 11:37:25.375  3769  3819 I jxcore-log: ok 205 Should be Could not establish TCP connection
08-12 11:37:25.375  3769  3819 I jxcore-log: 
,08-12 11:37:25.393  3769  3819 I jxcore-log: # teardown
08-12 11:37:25.393  3769  3819 I jxcore-log: 
,08-12 11:37:25.504  3769  3819 I jxcore-log: # setup
08-12 11:37:25.504  3769  3819 I jxcore-log: 
,08-12 11:37:25.625  3769  3819 I jxcore-log: # 64. Close the client socket while the client is waiting a response from the server. Local test.
08-12 11:37:25.625  3769  3819 I jxcore-log: 
,08-12 11:37:27.764  3769  3819 I jxcore-log: ok 206 Should be NETWORK_PROBLEM caused closing client socket
08-12 11:37:27.764  3769  3819 I jxcore-log: 
,08-12 11:37:27.778  3769  3819 I jxcore-log: ok 207 Should be Could not establish TCP connection
08-12 11:37:27.778  3769  3819 I jxcore-log: 
,08-12 11:37:27.789  3769  3819 I jxcore-log: # teardown
08-12 11:37:27.789  3769  3819 I jxcore-log: 
,08-12 11:37:27.858  3769  3819 I jxcore-log: # setup
08-12 11:37:27.858  3769  3819 I jxcore-log: 
,08-12 11:37:27.922  3769  3819 I jxcore-log: # 65. #generatePreambleAndBeacons bad args
08-12 11:37:27.922  3769  3819 I jxcore-log: 
,08-12 11:37:28.047  3769  3819 I jxcore-log: ok 208 publicKeysToNotify cannot be null
08-12 11:37:28.047  3769  3819 I jxcore-log: 
,08-12 11:37:28.050  3769  3819 I jxcore-log: ok 209 ecdh for local device cannot be null
08-12 11:37:28.050  3769  3819 I jxcore-log: 
,08-12 11:37:28.052  3769  3819 I jxcore-log: ok 210 milliseconds cannot be less than 0
08-12 11:37:28.052  3769  3819 I jxcore-log: 
,08-12 11:37:28.054  3769  3819 I jxcore-log: ok 211 milliseconds cannot be 0
08-12 11:37:28.054  3769  3819 I jxcore-log: 
,08-12 11:37:28.056  3769  3819 I jxcore-log: ok 212 milliseconds cannot be greater than one_day
08-12 11:37:28.056  3769  3819 I jxcore-log: 
,08-12 11:37:28.059  3769  3819 I jxcore-log: # teardown
08-12 11:37:28.059  3769  3819 I jxcore-log: 
,08-12 11:37:28.115  3769  3819 I jxcore-log: # setup
08-12 11:37:28.115  3769  3819 I jxcore-log: 
,08-12 11:37:28.157  3769  3819 I jxcore-log: # 66. #generatePreambleAndBeacons empty keys to notify
08-12 11:37:28.157  3769  3819 I jxcore-log: 
,08-12 11:37:28.266  3769  3819 I jxcore-log: ok 213 should be equal
08-12 11:37:28.266  3769  3819 I jxcore-log: 
,08-12 11:37:28.269  3769  3819 I jxcore-log: # teardown
08-12 11:37:28.269  3769  3819 I jxcore-log: 
,08-12 11:37:28.368  3769  3819 I jxcore-log: # setup
08-12 11:37:28.368  3769  3819 I jxcore-log: 
,08-12 11:37:28.414  3769  3819 I jxcore-log: # 67. #generatePreambleAndBeacons multiple keys to notify
08-12 11:37:28.414  3769  3819 I jxcore-log: 
,08-12 11:37:28.610  3769  3819 I jxcore-log: ok 214 should be equal
08-12 11:37:28.610  3769  3819 I jxcore-log: 
08-12 11:37:28.610  3769  3819 I jxcore-log: ok 215 should be equal
08-12 11:37:28.610  3769  3819 I jxcore-log: 
08-12 11:37:28.611  3769  3819 I jxcore-log: ok 216 (unnamed assert)
08-12 11:37:28.611  3769  3819 I jxcore-log: 
08-12 11:37:28.611  3769  3819 I jxcore-log: ok 217 should be equal
08-12 11:37:28.611  3769  3819 I jxcore-log: 
,08-12 11:37:28.618  3769  3819 I jxcore-log: # teardown
08-12 11:37:28.618  3769  3819 I jxcore-log: 
,08-12 11:37:28.716  3769  3819 I jxcore-log: # setup
08-12 11:37:28.716  3769  3819 I jxcore-log: 
,08-12 11:37:28.778  3769  3819 I jxcore-log: # 68. #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
08-12 11:37:28.778  3769  3819 I jxcore-log: 
,08-12 11:37:28.842  3769  3819 I jxcore-log: ok 218 should throw
08-12 11:37:28.842  3769  3819 I jxcore-log: 
,08-12 11:37:28.845  3769  3819 I jxcore-log: # teardown
08-12 11:37:28.845  3769  3819 I jxcore-log: 
,08-12 11:37:28.915  3769  3819 I jxcore-log: # setup
08-12 11:37:28.915  3769  3819 I jxcore-log: 
,08-12 11:37:28.964  3769  3819 I jxcore-log: # 69. #parseBeacons invalid expiration in beaconStreamWithPreAmble
08-12 11:37:28.964  3769  3819 I jxcore-log: 
,08-12 11:37:29.037  3769  3819 I jxcore-log: ok 219 Preamble expiration must be a 64 bit integer
08-12 11:37:29.037  3769  3819 I jxcore-log: 
,08-12 11:37:29.040  3769  3819 I jxcore-log: # teardown
08-12 11:37:29.040  3769  3819 I jxcore-log: 
,08-12 11:37:29.086  3769  3819 I jxcore-log: # setup
08-12 11:37:29.086  3769  3819 I jxcore-log: 
,08-12 11:37:29.136  3769  3819 I jxcore-log: # 70. #parseBeacons expiration out of range lower
08-12 11:37:29.136  3769  3819 I jxcore-log: 
,08-12 11:37:29.220  3769  3819 I jxcore-log: ok 220 Expiration out of range
08-12 11:37:29.220  3769  3819 I jxcore-log: 
,08-12 11:37:29.223  3769  3819 I jxcore-log: # teardown
08-12 11:37:29.223  3769  3819 I jxcore-log: 
,08-12 11:37:29.359  3769  3819 I jxcore-log: # setup
08-12 11:37:29.359  3769  3819 I jxcore-log: 
,08-12 11:37:29.432  3769  3819 I jxcore-log: # 71. #parseBeacons expiration out of range lower
08-12 11:37:29.432  3769  3819 I jxcore-log: 
,08-12 11:37:29.539  3769  3819 I jxcore-log: ok 221 Expiration out of range
08-12 11:37:29.539  3769  3819 I jxcore-log: 
08-12 11:37:29.541  3769  3819 I jxcore-log: # teardown
08-12 11:37:29.541  3769  3819 I jxcore-log: 
,08-12 11:37:29.632  3769  3819 I jxcore-log: # setup
08-12 11:37:29.632  3769  3819 I jxcore-log: 
,08-12 11:37:29.672  3769  3819 I jxcore-log: # 72. #parseBeacons no beacons returns null
08-12 11:37:29.672  3769  3819 I jxcore-log: 
,08-12 11:37:29.766  3769  3819 I jxcore-log: ok 222 should be equal
08-12 11:37:29.766  3769  3819 I jxcore-log: 
,08-12 11:37:29.768  3769  3819 I jxcore-log: # teardown
08-12 11:37:29.768  3769  3819 I jxcore-log: 
,08-12 11:37:29.833  3769  3819 I jxcore-log: # setup
08-12 11:37:29.833  3769  3819 I jxcore-log: 
,08-12 11:37:29.875  3769  3819 I jxcore-log: # 73. #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
08-12 11:37:29.875  3769  3819 I jxcore-log: 
,08-12 11:37:29.969  3769  3819 I jxcore-log: ok 223 Malformed encrypted beacon key ID
08-12 11:37:29.969  3769  3819 I jxcore-log: 
08-12 11:37:29.971  3769  3819 I jxcore-log: # teardown
08-12 11:37:29.971  3769  3819 I jxcore-log: 
,08-12 11:37:30.007  3769  3819 I jxcore-log: # setup
08-12 11:37:30.007  3769  3819 I jxcore-log: 
,08-12 11:37:30.085  3769  3819 I jxcore-log: # 74. #parseBeacons addressBookCallback fails decrypt
08-12 11:37:30.085  3769  3819 I jxcore-log: 
,08-12 11:37:30.228  3769  3819 I jxcore-log: ok 224 should be equal
08-12 11:37:30.228  3769  3819 I jxcore-log: 
,08-12 11:37:30.230  3769  3819 I jxcore-log: # teardown
08-12 11:37:30.230  3769  3819 I jxcore-log: 
,08-12 11:37:30.376  3769  3819 I jxcore-log: # setup
08-12 11:37:30.376  3769  3819 I jxcore-log: 
,08-12 11:37:30.440  3769  3819 I jxcore-log: # 75. #parseBeacons addressBookCallback returns no matches
08-12 11:37:30.440  3769  3819 I jxcore-log: 
,08-12 11:37:30.625  3769  3819 I jxcore-log: ok 225 should be equal
08-12 11:37:30.625  3769  3819 I jxcore-log: 
,08-12 11:37:30.626  3769  3819 I jxcore-log: ok 226 should be equal
08-12 11:37:30.626  3769  3819 I jxcore-log: 
,08-12 11:37:30.628  3769  3819 I jxcore-log: # teardown
08-12 11:37:30.628  3769  3819 I jxcore-log: 
,08-12 11:37:30.778  3769  3819 I jxcore-log: # setup
08-12 11:37:30.778  3769  3819 I jxcore-log: 
,08-12 11:37:30.838  3769  3819 I jxcore-log: # 76. #parseBeacons addressBookCallback returns spurious match
08-12 11:37:30.838  3769  3819 I jxcore-log: 
,08-12 11:37:31.037  3769  3819 I jxcore-log: ok 227 should be equal
08-12 11:37:31.037  3769  3819 I jxcore-log: 
,08-12 11:37:31.039  3769  3819 I jxcore-log: ok 228 should be equal
08-12 11:37:31.039  3769  3819 I jxcore-log: 
,08-12 11:37:31.041  3769  3819 I jxcore-log: # teardown
08-12 11:37:31.041  3769  3819 I jxcore-log: 
,08-12 11:37:31.172  3769  3819 I jxcore-log: # setup
08-12 11:37:31.172  3769  3819 I jxcore-log: 
,08-12 11:37:31.220  3769  3819 I jxcore-log: # 77. #parseBeacons addressBookCallback returns public key
08-12 11:37:31.220  3769  3819 I jxcore-log: 
,08-12 11:37:31.383  3769  3819 I jxcore-log: ok 229 right number of calls to address book
08-12 11:37:31.383  3769  3819 I jxcore-log: 
,08-12 11:37:31.384  3769  3819 I jxcore-log: ok 230 good preAmble
08-12 11:37:31.384  3769  3819 I jxcore-log: 
08-12 11:37:31.384  3769  3819 I jxcore-log: ok 231 good unencryptedKeyId
08-12 11:37:31.384  3769  3819 I jxcore-log: 
08-12 11:37:31.384  3769  3819 I jxcore-log: ok 232 good beacon
08-12 11:37:31.384  3769  3819 I jxcore-log: 
,08-12 11:37:31.387  3769  3819 I jxcore-log: # teardown
08-12 11:37:31.387  3769  3819 I jxcore-log: 
,08-12 11:37:31.522  3769  3819 I jxcore-log: # setup
08-12 11:37:31.522  3769  3819 I jxcore-log: 
,08-12 11:37:31.562  3769  3819 I jxcore-log: # 78. validate generatePskIdentityField
08-12 11:37:31.562  3769  3819 I jxcore-log: 
,08-12 11:37:31.614  3769  3819 I jxcore-log: ok 233 decoded buffers match
08-12 11:37:31.614  3769  3819 I jxcore-log: 
,08-12 11:37:31.618  3769  3819 I jxcore-log: # teardown
08-12 11:37:31.618  3769  3819 I jxcore-log: 
,08-12 11:37:31.670  3769  3819 I jxcore-log: # setup
08-12 11:37:31.670  3769  3819 I jxcore-log: 
,08-12 11:37:31.719  3769  3819 I jxcore-log: # 79. validate generatePskSecret
08-12 11:37:31.719  3769  3819 I jxcore-log: 
,08-12 11:37:31.884  3769  3819 I jxcore-log: ok 234 secrets match
08-12 11:37:31.884  3769  3819 I jxcore-log: 
,08-12 11:37:31.887  3769  3819 I jxcore-log: # teardown
08-12 11:37:31.887  3769  3819 I jxcore-log: 
,08-12 11:37:31.923  3769  3819 I jxcore-log: # setup
08-12 11:37:31.923  3769  3819 I jxcore-log: 
,08-12 11:37:31.968  3769  3819 I jxcore-log: # 80. validate generatePskSecrets
08-12 11:37:31.968  3769  3819 I jxcore-log: 
,08-12 11:37:32.135  3769  3819 I jxcore-log: ok 235 Matching numbers
08-12 11:37:32.135  3769  3819 I jxcore-log: 
,08-12 11:37:32.142  3769  3819 I jxcore-log: ok 236 We have an entry!
08-12 11:37:32.142  3769  3819 I jxcore-log: 
,08-12 11:37:32.143  3769  3819 I jxcore-log: ok 237 keys match
08-12 11:37:32.143  3769  3819 I jxcore-log: 
,08-12 11:37:32.143  3769  3819 I jxcore-log: ok 238 secrets match
08-12 11:37:32.143  3769  3819 I jxcore-log: 
,08-12 11:37:32.150  3769  3819 I jxcore-log: ok 239 We have an entry!
08-12 11:37:32.150  3769  3819 I jxcore-log: 
,08-12 11:37:32.151  3769  3819 I jxcore-log: ok 240 keys match
08-12 11:37:32.151  3769  3819 I jxcore-log: 
,08-12 11:37:32.151  3769  3819 I jxcore-log: ok 241 secrets match
08-12 11:37:32.151  3769  3819 I jxcore-log: 
,08-12 11:37:32.158  3769  3819 I jxcore-log: ok 242 We have an entry!
08-12 11:37:32.158  3769  3819 I jxcore-log: 
,08-12 11:37:32.159  3769  3819 I jxcore-log: ok 243 keys match
08-12 11:37:32.159  3769  3819 I jxcore-log: 
,08-12 11:37:32.159  3769  3819 I jxcore-log: ok 244 secrets match
08-12 11:37:32.159  3769  3819 I jxcore-log: 
08-12 11:37:32.161  3769  3819 I jxcore-log: # teardown
08-12 11:37:32.161  3769  3819 I jxcore-log: 
,08-12 11:37:32.306  3769  3819 I jxcore-log: # setup
08-12 11:37:32.306  3769  3819 I jxcore-log: 
,08-12 11:37:32.362  3769  3819 I jxcore-log: # 81. validate generateBeaconStreamAndSecrets
08-12 11:37:32.362  3769  3819 I jxcore-log: 
,08-12 11:37:32.516  3769  3819 I jxcore-log: ok 245 Streams have same length
08-12 11:37:32.516  3769  3819 I jxcore-log: 
,08-12 11:37:32.523  3769  3819 I jxcore-log: ok 246 matching size
08-12 11:37:32.523  3769  3819 I jxcore-log: 
,08-12 11:37:32.524  3769  3819 I jxcore-log: ok 247 keys match
08-12 11:37:32.524  3769  3819 I jxcore-log: 
,08-12 11:37:32.524  3769  3819 I jxcore-log: ok 248 secrets match
08-12 11:37:32.524  3769  3819 I jxcore-log: 
08-12 11:37:32.526  3769  3819 I jxcore-log: # teardown
08-12 11:37:32.526  3769  3819 I jxcore-log: 
,08-12 11:37:32.602  3769  3819 I jxcore-log: # setup
08-12 11:37:32.602  3769  3819 I jxcore-log: 
,08-12 11:37:32.731  3769  3819 I jxcore-log: # 82. Add two Peers.
08-12 11:37:32.731  3769  3819 I jxcore-log: 
,08-12 11:37:32.816  3769  3819 I jxcore-log: ok 249 should be equal
08-12 11:37:32.816  3769  3819 I jxcore-log: 
,08-12 11:37:32.817  3769  3819 I jxcore-log: ok 250 should be equal
08-12 11:37:32.817  3769  3819 I jxcore-log: 
08-12 11:37:32.817  3769  3819 I jxcore-log: ok 251 should be equal
08-12 11:37:32.817  3769  3819 I jxcore-log: 
08-12 11:37:32.817  3769  3819 I jxcore-log: ok 252 should be equal
08-12 11:37:32.817  3769  3819 I jxcore-log: 
08-12 11:37:32.818  3769  3819 I jxcore-log: ok 253 should be equal
08-12 11:37:32.818  3769  3819 I jxcore-log: 
,08-12 11:37:32.823  3769  3819 I jxcore-log: # teardown
08-12 11:37:32.823  3769  3819 I jxcore-log: 
,08-12 11:37:32.857  3769  3819 I jxcore-log: # setup
08-12 11:37:32.857  3769  3819 I jxcore-log: 
,08-12 11:37:32.953  3769  3819 I jxcore-log: # 83. TCP_NATIVE peer loses DNS
08-12 11:37:32.953  3769  3819 I jxcore-log: 
,08-12 11:37:33.096  3769  3819 I jxcore-log: ok 254 should be equal
08-12 11:37:33.096  3769  3819 I jxcore-log: 
,08-12 11:37:33.099  3769  3819 I jxcore-log: ok 255 should be equal
08-12 11:37:33.099  3769  3819 I jxcore-log: 
,08-12 11:37:33.109  3769  3819 I jxcore-log: # teardown
08-12 11:37:33.109  3769  3819 I jxcore-log: 
,08-12 11:37:33.152  3769  3819 I jxcore-log: # setup
08-12 11:37:33.152  3769  3819 I jxcore-log: 
,08-12 11:37:33.276  3769  3819 I jxcore-log: # 84. Received beacons with no values for us
08-12 11:37:33.276  3769  3819 I jxcore-log: 
,08-12 11:37:33.473  3769  3819 I jxcore-log: ok 256 entry exists
08-12 11:37:33.473  3769  3819 I jxcore-log: 
,08-12 11:37:33.473  3769  3819 I jxcore-log: ok 257 entry is resolved
08-12 11:37:33.473  3769  3819 I jxcore-log: 
08-12 11:37:33.482  3769  3819 I jxcore-log: # teardown
08-12 11:37:33.482  3769  3819 I jxcore-log: 
,08-12 11:37:33.550  3769  3819 I jxcore-log: # setup
08-12 11:37:33.550  3769  3819 I jxcore-log: 
,08-12 11:37:33.660  3769  3819 I jxcore-log: # 85. Resolves an action locally
08-12 11:37:33.660  3769  3819 I jxcore-log: 
,08-12 11:37:33.935  3769  3819 I jxcore-log: ok 258 Host address must match
08-12 11:37:33.935  3769  3819 I jxcore-log: 
,08-12 11:37:33.936  3769  3819 I jxcore-log: ok 259 suggestedTCPTimeout must match
08-12 11:37:33.936  3769  3819 I jxcore-log: 
,08-12 11:37:33.936  3769  3819 I jxcore-log: ok 260 connectionType must match
08-12 11:37:33.936  3769  3819 I jxcore-log: 
,08-12 11:37:33.937  3769  3819 I jxcore-log: ok 261 portNumber must match
08-12 11:37:33.937  3769  3819 I jxcore-log: 
,08-12 11:37:33.945  3769  3819 I jxcore-log: # teardown
08-12 11:37:33.945  3769  3819 I jxcore-log: 
,08-12 11:37:33.975  3769  3819 I jxcore-log: # setup
08-12 11:37:33.975  3769  3819 I jxcore-log: 
,08-12 11:37:34.121  3769  3819 I jxcore-log: # 86. Resolves an action locally using ThaliPeerPoolDefault
08-12 11:37:34.121  3769  3819 I jxcore-log: 
,08-12 11:37:34.294  3769  3819 I jxcore-log: ok 262 Host address must match
08-12 11:37:34.294  3769  3819 I jxcore-log: 
,08-12 11:37:34.294  3769  3819 I jxcore-log: ok 263 suggestedTCPTimeout must match
08-12 11:37:34.294  3769  3819 I jxcore-log: 
08-12 11:37:34.295  3769  3819 I jxcore-log: ok 264 connectionType must match
08-12 11:37:34.295  3769  3819 I jxcore-log: 
,08-12 11:37:34.295  3769  3819 I jxcore-log: ok 265 portNumber must match
08-12 11:37:34.295  3769  3819 I jxcore-log: 
,08-12 11:37:34.302  3769  3819 I jxcore-log: # teardown
08-12 11:37:34.302  3769  3819 I jxcore-log: 
,08-12 11:37:34.392  3769  3819 I jxcore-log: # setup
08-12 11:37:34.392  3769  3819 I jxcore-log: 
,08-12 11:37:34.488  3769  3819 I jxcore-log: # 87. Action fails because of a bad hostname.
08-12 11:37:34.488  3769  3819 I jxcore-log: 
,08-12 11:37:39.652  3769  3819 I jxcore-log: ok 266 should be equal
08-12 11:37:39.652  3769  3819 I jxcore-log: 
08-12 11:37:39.654  3769  3819 I jxcore-log: ok 267 should be equal
08-12 11:37:39.654  3769  3819 I jxcore-log: 
,08-12 11:37:39.656  3769  3819 I jxcore-log: ok 268 should be equal
08-12 11:37:39.656  3769  3819 I jxcore-log: 
,08-12 11:37:39.674  3769  3819 I jxcore-log: # teardown
08-12 11:37:39.674  3769  3819 I jxcore-log: 
,08-12 11:37:39.771  3769  3819 I jxcore-log: # setup
08-12 11:37:39.771  3769  3819 I jxcore-log: 
,08-12 11:37:39.984  3769  3819 I jxcore-log: # 88. hostaddress is removed when the action is running. 
08-12 11:37:39.984  3769  3819 I jxcore-log: 
,08-12 11:37:42.200  3769  3819 I jxcore-log: ok 269 should be equal
08-12 11:37:42.200  3769  3819 I jxcore-log: 
,08-12 11:37:42.238  3769  3819 I jxcore-log: # teardown
08-12 11:37:42.238  3769  3819 I jxcore-log: 
,08-12 11:37:44.992  3769  3819 I jxcore-log: # setup
08-12 11:37:44.992  3769  3819 I jxcore-log: 
,08-12 11:37:45.100  3769  3819 I jxcore-log: # 89. Client to server request locally
08-12 11:37:45.100  3769  3819 I jxcore-log: 
,08-12 11:37:45.369  3769  3819 I jxcore-log: ok 270 secrets are equal
08-12 11:37:45.369  3769  3819 I jxcore-log: 
,08-12 11:37:45.369  3769  3819 I jxcore-log: ok 271 Public key matches with the server key
08-12 11:37:45.369  3769  3819 I jxcore-log: 
08-12 11:37:45.369  3769  3819 I jxcore-log: ok 272 Host address must match
08-12 11:37:45.369  3769  3819 I jxcore-log: 
,08-12 11:37:45.370  3769  3819 I jxcore-log: ok 273 suggestedTCPTimeout must match
08-12 11:37:45.370  3769  3819 I jxcore-log: 
08-12 11:37:45.370  3769  3819 I jxcore-log: ok 274 connectionType must match
08-12 11:37:45.370  3769  3819 I jxcore-log: 
08-12 11:37:45.370  3769  3819 I jxcore-log: ok 275 portNumber must match
08-12 11:37:45.370  3769  3819 I jxcore-log: 
,08-12 11:37:45.377  3769  3819 I jxcore-log: # teardown
08-12 11:37:45.377  3769  3819 I jxcore-log: 
,08-12 11:37:45.439  3769  3819 I jxcore-log: # setup
08-12 11:37:45.439  3769  3819 I jxcore-log: 
,08-12 11:37:45.513  3769  3819 I jxcore-log: # 90. Test ThaliPskMapCache clean and expiration
08-12 11:37:45.513  3769  3819 I jxcore-log: 
,08-12 11:37:45.601  3769  3819 I jxcore-log: ok 276 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
08-12 11:37:45.601  3769  3819 I jxcore-log: 
08-12 11:37:45.602  3769  3819 I jxcore-log: ok 277 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
08-12 11:37:45.602  3769  3819 I jxcore-log: 
,08-12 11:37:46.605  3769  3819 I jxcore-log: ok 278 All entries should be expired after 1 second
08-12 11:37:46.605  3769  3819 I jxcore-log: 
,08-12 11:37:46.619  3769  3819 I jxcore-log: # teardown
08-12 11:37:46.619  3769  3819 I jxcore-log: 
,08-12 11:37:46.694  3769  3819 I jxcore-log: # setup
08-12 11:37:46.694  3769  3819 I jxcore-log: 
,08-12 11:37:46.821  3769  3819 I jxcore-log: # 91. Test ThaliPskMapCache getSecret and getPublic
08-12 11:37:46.821  3769  3819 I jxcore-log: 
,08-12 11:37:46.967  3769  3819 I jxcore-log: ok 279 All keys need to be available in the cache
08-12 11:37:46.967  3769  3819 I jxcore-log: 
,08-12 11:37:47.971  3769  3819 I jxcore-log: ok 280 All entries should be expired after 1 second
08-12 11:37:47.971  3769  3819 I jxcore-log: 
,08-12 11:37:47.983  3769  3819 I jxcore-log: # teardown
08-12 11:37:47.983  3769  3819 I jxcore-log: 
,08-12 11:37:48.088  3769  3819 I jxcore-log: # setup
08-12 11:37:48.088  3769  3819 I jxcore-log: 
,08-12 11:37:48.197  3769  3819 I jxcore-log: # 92. Test ThaliPskMapCache multiple entries
08-12 11:37:48.197  3769  3819 I jxcore-log: 
,08-12 11:37:49.639  3769  3819 I jxcore-log: ok 281 Size of the cache should be 2
08-12 11:37:49.639  3769  3819 I jxcore-log: 
,08-12 11:37:49.643  3769  3819 I jxcore-log: ok 282 Cache doesn't contain dictionary1
08-12 11:37:49.643  3769  3819 I jxcore-log: 
,08-12 11:37:50.856  3769  3819 I jxcore-log: ok 283 Size of the cache should be 1
08-12 11:37:50.856  3769  3819 I jxcore-log: 
,08-12 11:37:50.859  3769  3819 I jxcore-log: ok 284 Cache doesn't contain beaconStreamAndSecretDictionary2
08-12 11:37:50.859  3769  3819 I jxcore-log: 
,08-12 11:37:50.871  3769  3819 I jxcore-log: # teardown
08-12 11:37:50.871  3769  3819 I jxcore-log: 
,08-12 11:37:51.017  3769  3819 I jxcore-log: # setup
08-12 11:37:51.017  3769  3819 I jxcore-log: 
,08-12 11:37:51.088  3769  3819 I jxcore-log: # 93. Start and stop ThaliNotificationServer
08-12 11:37:51.088  3769  3819 I jxcore-log: 
,08-12 11:37:51.279  3769  3819 I jxcore-log: ok 285 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
08-12 11:37:51.279  3769  3819 I jxcore-log: 
08-12 11:37:51.279  3769  3819 I jxcore-log: ok 286 ThaliMobile.StopAdvertisingAndListeningshould be called once
08-12 11:37:51.279  3769  3819 I jxcore-log: 
,08-12 11:37:51.281  3769  3819 I jxcore-log: # teardown
08-12 11:37:51.281  3769  3819 I jxcore-log: 
,08-12 11:37:51.337  3769  3819 I jxcore-log: # setup
08-12 11:37:51.337  3769  3819 I jxcore-log: 
,08-12 11:37:51.412  3769  3819 I jxcore-log: # 94. Pass an empty array to ThaliNotificationServer.start
08-12 11:37:51.412  3769  3819 I jxcore-log: 
,08-12 11:37:51.461  3769  3819 I jxcore-log: ok 287 StartUpdateAdvertisingAndListening should not be called
08-12 11:37:51.461  3769  3819 I jxcore-log: 
,08-12 11:37:51.475  3769  3819 I jxcore-log: ok 288 ThaliMobile.StopAdvertisingAndListening should be called once
08-12 11:37:51.475  3769  3819 I jxcore-log: 
,08-12 11:37:51.522  3769  3819 I jxcore-log: ok 289 no error
08-12 11:37:51.522  3769  3819 I jxcore-log: 
,08-12 11:37:51.522  3769  3819 I jxcore-log: ok 290 should be 204
08-12 11:37:51.522  3769  3819 I jxcore-log: 
,08-12 11:37:51.527  3769  3819 I jxcore-log: # teardown
08-12 11:37:51.527  3769  3819 I jxcore-log: 
,08-12 11:37:51.572  3769  3819 I jxcore-log: # setup
08-12 11:37:51.572  3769  3819 I jxcore-log: 
,08-12 11:37:51.654  3769  3819 I jxcore-log: # 95. Pass a string to ThaliNotificationServer.start
08-12 11:37:51.654  3769  3819 I jxcore-log: 
,08-12 11:37:51.705  3769  3819 I jxcore-log: ok 291 StartUpdateAdvertisingAndListening should not be called
08-12 11:37:51.705  3769  3819 I jxcore-log: 
,08-12 11:37:51.709  3769  3819 I jxcore-log: # teardown
08-12 11:37:51.709  3769  3819 I jxcore-log: 
,08-12 11:37:51.760  3769  3819 I jxcore-log: # setup
08-12 11:37:51.760  3769  3819 I jxcore-log: 
,08-12 11:37:51.854  3769  3819 I jxcore-log: # 96. Pass an empty parameter to ThaliNotificationServer.start
08-12 11:37:51.854  3769  3819 I jxcore-log: 
,08-12 11:37:51.959  3769  3819 I jxcore-log: ok 292 StartUpdateAdvertisingAndListening should not be called
08-12 11:37:51.959  3769  3819 I jxcore-log: 
,08-12 11:37:51.965  3769  3819 I jxcore-log: # teardown
08-12 11:37:51.965  3769  3819 I jxcore-log: 
,08-12 11:37:52.004  3769  3819 I jxcore-log: # setup
08-12 11:37:52.004  3769  3819 I jxcore-log: 
,08-12 11:37:52.092  3769  3819 I jxcore-log: # 97. Make an HTTP request to /NotificationBeacons
08-12 11:37:52.092  3769  3819 I jxcore-log: 
,08-12 11:37:52.271  3769  3819 I jxcore-log: ok 293 no error
08-12 11:37:52.271  3769  3819 I jxcore-log: 
08-12 11:37:52.271  3769  3819 I jxcore-log: ok 294 should be 200
08-12 11:37:52.271  3769  3819 I jxcore-log: 
,08-12 11:37:52.271  3769  3819 I jxcore-log: ok 295 should be equal
08-12 11:37:52.271  3769  3819 I jxcore-log: 
,08-12 11:37:52.278  3769  3819 I jxcore-log: ok 296 should be equal
08-12 11:37:52.278  3769  3819 I jxcore-log: 
,08-12 11:37:52.295  3769  3819 I jxcore-log: ok 297 (unnamed assert)
08-12 11:37:52.295  3769  3819 I jxcore-log: 
,08-12 11:37:52.329  3769  3819 I jxcore-log: ok 298 no error
08-12 11:37:52.329  3769  3819 I jxcore-log: 
08-12 11:37:52.329  3769  3819 I jxcore-log: ok 299 should be 204
08-12 11:37:52.329  3769  3819 I jxcore-log: 
,08-12 11:37:52.333  3769  3819 I jxcore-log: # teardown
08-12 11:37:52.333  3769  3819 I jxcore-log: 
,08-12 11:37:52.430  3769  3819 I jxcore-log: # setup
08-12 11:37:52.430  3769  3819 I jxcore-log: 
,08-12 11:37:52.583  3769  3819 I jxcore-log: # 98. Make an HTTP request to /NotificationBeacons (no keys)
08-12 11:37:52.583  3769  3819 I jxcore-log: 
,08-12 11:37:52.646  3769  3819 I jxcore-log: ok 300 error should be null
08-12 11:37:52.646  3769  3819 I jxcore-log: 
08-12 11:37:52.646  3769  3819 I jxcore-log: ok 301 should be 204
08-12 11:37:52.646  3769  3819 I jxcore-log: 
,08-12 11:37:52.650  3769  3819 I jxcore-log: # teardown
08-12 11:37:52.650  3769  3819 I jxcore-log: 
,08-12 11:37:52.779  3769  3819 I jxcore-log: # setup
08-12 11:37:52.779  3769  3819 I jxcore-log: 
,08-12 11:37:52.877  3769  3819 I jxcore-log: # 99. Make an HTTP request to /NotificationBeaconsbefore calling start
08-12 11:37:52.877  3769  3819 I jxcore-log: 
,08-12 11:37:53.027  3769  3819 I jxcore-log: ok 302 should be 404
08-12 11:37:53.027  3769  3819 I jxcore-log: 
,08-12 11:37:53.031  3769  3819 I jxcore-log: # teardown
08-12 11:37:53.031  3769  3819 I jxcore-log: 
,08-12 11:37:53.067  3769  3819 I jxcore-log: # setup
08-12 11:37:53.067  3769  3819 I jxcore-log: 
,08-12 11:37:53.123  3769  3819 I jxcore-log: # 100. #testThaliPeerAction - test getters
08-12 11:37:53.123  3769  3819 I jxcore-log: 
,08-12 11:37:53.219  3769  3819 I jxcore-log: ok 303 getPeerIdentifier
08-12 11:37:53.219  3769  3819 I jxcore-log: 
,08-12 11:37:53.221  3769  3819 I jxcore-log: ok 304 getConnectionType
08-12 11:37:53.221  3769  3819 I jxcore-log: 
,08-12 11:37:53.223  3769  3819 I jxcore-log: ok 305 getActionType
08-12 11:37:53.223  3769  3819 I jxcore-log: 
,08-12 11:37:53.225  3769  3819 I jxcore-log: ok 306 getActionState
08-12 11:37:53.225  3769  3819 I jxcore-log: 
,08-12 11:37:53.227  3769  3819 I jxcore-log: ok 307 getPskIdentity
08-12 11:37:53.227  3769  3819 I jxcore-log: 
,08-12 11:37:53.229  3769  3819 I jxcore-log: ok 308 getPskKey
08-12 11:37:53.229  3769  3819 I jxcore-log: 
,08-12 11:37:53.236  3769  3819 I jxcore-log: # teardown
08-12 11:37:53.236  3769  3819 I jxcore-log: 
,08-12 11:37:53.275  3769  3819 I jxcore-log: # setup
08-12 11:37:53.275  3769  3819 I jxcore-log: 
,08-12 11:37:53.339  3769  3819 I jxcore-log: # 101. #testThaliPeerAction - start and kill
08-12 11:37:53.339  3769  3819 I jxcore-log: 
,08-12 11:37:53.421  3769  3819 I jxcore-log: ok 309 initial state
08-12 11:37:53.421  3769  3819 I jxcore-log: 
,08-12 11:37:53.422  3769  3819 I jxcore-log: ok 310 after start
08-12 11:37:53.422  3769  3819 I jxcore-log: 
,08-12 11:37:53.423  3769  3819 I jxcore-log: ok 311 after kill
08-12 11:37:53.423  3769  3819 I jxcore-log: 
,08-12 11:37:53.425  3769  3819 I jxcore-log: # teardown
08-12 11:37:53.425  3769  3819 I jxcore-log: 
,08-12 11:37:53.484  3769  3819 I jxcore-log: # setup
08-12 11:37:53.484  3769  3819 I jxcore-log: 
,08-12 11:37:53.520  3769  3819 I jxcore-log: # 102. #testThaliPeerAction - double start
08-12 11:37:53.520  3769  3819 I jxcore-log: 
,08-12 11:37:53.617  3769  3819 I jxcore-log: ok 312 should be equal
08-12 11:37:53.617  3769  3819 I jxcore-log: 
,08-12 11:37:53.619  3769  3819 I jxcore-log: # teardown
08-12 11:37:53.619  3769  3819 I jxcore-log: 
,08-12 11:37:53.684  3769  3819 I jxcore-log: # setup
08-12 11:37:53.684  3769  3819 I jxcore-log: 
,08-12 11:37:53.746  3769  3819 I jxcore-log: # 103. #testThaliPeerAction - start after kill
08-12 11:37:53.746  3769  3819 I jxcore-log: 
,08-12 11:37:53.814  3769  3819 I jxcore-log: ok 313 clean kill
08-12 11:37:53.814  3769  3819 I jxcore-log: 
,08-12 11:37:53.816  3769  3819 I jxcore-log: ok 314 should be equal
08-12 11:37:53.816  3769  3819 I jxcore-log: 
,08-12 11:37:53.819  3769  3819 I jxcore-log: # teardown
08-12 11:37:53.819  3769  3819 I jxcore-log: 
,08-12 11:37:53.904  3769  3819 I jxcore-log: # setup
08-12 11:37:53.904  3769  3819 I jxcore-log: 
,08-12 11:37:53.969  3769  3819 I jxcore-log: # 104. #testThaliPeerAction - make sure ids are unique
08-12 11:37:53.969  3769  3819 I jxcore-log: 
,08-12 11:37:54.018  3769  3819 I jxcore-log: ok 315 should not be equal
08-12 11:37:54.018  3769  3819 I jxcore-log: 
,08-12 11:37:54.022  3769  3819 I jxcore-log: # teardown
08-12 11:37:54.022  3769  3819 I jxcore-log: 
,08-12 11:37:54.084  3769  3819 I jxcore-log: # setup
08-12 11:37:54.084  3769  3819 I jxcore-log: 
,08-12 11:37:54.143  3769  3819 I jxcore-log: # 105. Test PeerConnectionInformation basics
08-12 11:37:54.143  3769  3819 I jxcore-log: 
,08-12 11:37:54.238  3769  3819 I jxcore-log: ok 316 connection type works
08-12 11:37:54.238  3769  3819 I jxcore-log: 
,08-12 11:37:54.240  3769  3819 I jxcore-log: ok 317 getHostAddress works
08-12 11:37:54.240  3769  3819 I jxcore-log: 
,08-12 11:37:54.242  3769  3819 I jxcore-log: ok 318 getPortNumber works
08-12 11:37:54.242  3769  3819 I jxcore-log: 
,08-12 11:37:54.244  3769  3819 I jxcore-log: ok 319 getSuggestedTCPTimeout works
08-12 11:37:54.244  3769  3819 I jxcore-log: 
,08-12 11:37:54.248  3769  3819 I jxcore-log: # teardown
08-12 11:37:54.248  3769  3819 I jxcore-log: 
,08-12 11:37:54.331  3769  3819 I jxcore-log: # setup
08-12 11:37:54.331  3769  3819 I jxcore-log: 
,08-12 11:37:54.378  3769  3819 I jxcore-log: # 106. Test PeerDictionary basic functionality
08-12 11:37:54.378  3769  3819 I jxcore-log: 
,08-12 11:37:54.476  3769  3819 I jxcore-log: ok 320 Entry counter must be 1
08-12 11:37:54.476  3769  3819 I jxcore-log: 
,08-12 11:37:54.477  3769  3819 I jxcore-log: ok 321 Size must be 1
08-12 11:37:54.477  3769  3819 I jxcore-log: 
,08-12 11:37:54.478  3769  3819 I jxcore-log: ok 322 Entry counter must be 2
08-12 11:37:54.478  3769  3819 I jxcore-log: 
,08-12 11:37:54.479  3769  3819 I jxcore-log: ok 323 Size must be 2
08-12 11:37:54.479  3769  3819 I jxcore-log: 
08-12 11:37:54.479  3769  3819 I jxcore-log: ok 324 Entry2 should not be found
08-12 11:37:54.479  3769  3819 I jxcore-log: 
08-12 11:37:54.480  3769  3819 I jxcore-log: ok 325 Size must be 1
08-12 11:37:54.480  3769  3819 I jxcore-log: 
08-12 11:37:54.481  3769  3819 I jxcore-log: ok 326 Size must be 0
08-12 11:37:54.481  3769  3819 I jxcore-log: 
08-12 11:37:54.483  3769  3819 I jxcore-log: # teardown
08-12 11:37:54.483  3769  3819 I jxcore-log: 
,08-12 11:37:54.588  3769  3819 I jxcore-log: # setup
08-12 11:37:54.588  3769  3819 I jxcore-log: 
,08-12 11:37:54.632  3769  3819 I jxcore-log: # 107. Test PeerDictionary with multiple entries.
08-12 11:37:54.632  3769  3819 I jxcore-log: 
,08-12 11:37:55.439  3769  3819 I jxcore-log: ok 327 Size must be100
08-12 11:37:55.439  3769  3819 I jxcore-log: 
,08-12 11:37:55.443  3769  3819 I jxcore-log: ok 328 Entries between 20 and MAXSIZE + 20 should exist
08-12 11:37:55.443  3769  3819 I jxcore-log: 
,08-12 11:37:56.157  3769  3819 I jxcore-log: ok 329 WAITING state entry should not be removed
08-12 11:37:56.157  3769  3819 I jxcore-log: 
,08-12 11:37:56.159  3769  3819 I jxcore-log: # teardown
08-12 11:37:56.159  3769  3819 I jxcore-log: 
,08-12 11:37:56.556  3769  3819 I jxcore-log: # setup
08-12 11:37:56.556  3769  3819 I jxcore-log: 
,08-12 11:37:56.619  3769  3819 I jxcore-log: # 108. RESOLVED entries are removed before WAITING state entry.
08-12 11:37:56.619  3769  3819 I jxcore-log: 
,08-12 11:37:57.310  3769  3819 I jxcore-log: ok 330 Entries between 6 and MAXSIZE + 4 should exist
08-12 11:37:57.310  3769  3819 I jxcore-log: 
,08-12 11:37:57.310  3769  3819 I jxcore-log: ok 331 Size should be MAXSIZE
08-12 11:37:57.310  3769  3819 I jxcore-log: 
08-12 11:37:57.311  3769  3819 I jxcore-log: ok 332 Size should be MAXSIZE+6
08-12 11:37:57.311  3769  3819 I jxcore-log: 
,08-12 11:37:57.317  3769  3819 I jxcore-log: # teardown
08-12 11:37:57.317  3769  3819 I jxcore-log: 
,08-12 11:37:57.480  3769  3819 I jxcore-log: # setup
08-12 11:37:57.480  3769  3819 I jxcore-log: 
,08-12 11:37:57.524  3769  3819 I jxcore-log: # 109. WAITING entries are removed before CONTROLLED_BY_POOL state entry.
08-12 11:37:57.524  3769  3819 I jxcore-log: 
,08-12 11:37:58.213  3769  3819 I jxcore-log: ok 333 WAITING state entry should not be removed
08-12 11:37:58.213  3769  3819 I jxcore-log: 
,08-12 11:37:58.215  3769  3819 I jxcore-log: ok 334 Waiting entries between 6 and MAXSIZE + 4 should exist
08-12 11:37:58.215  3769  3819 I jxcore-log: 
08-12 11:37:58.215  3769  3819 I jxcore-log: ok 335 Size should be MAXSIZE
08-12 11:37:58.215  3769  3819 I jxcore-log: 
,08-12 11:37:58.215  3769  3819 I jxcore-log: ok 336 entryCounter should be MAXSIZE+6
08-12 11:37:58.215  3769  3819 I jxcore-log: 
08-12 11:37:58.217  3769  3819 I jxcore-log: # teardown
08-12 11:37:58.217  3769  3819 I jxcore-log: 
,08-12 11:37:58.268  3769  3819 I jxcore-log: # setup
08-12 11:37:58.268  3769  3819 I jxcore-log: 
,08-12 11:37:58.300  3769  3819 I jxcore-log: # 110. When CONTROLLED_BY_POOL entry is removed and kill is called.
08-12 11:37:58.300  3769  3819 I jxcore-log: 
,08-12 11:37:58.988  3769  3819 I jxcore-log: ok 337 Kill should be called once
08-12 11:37:58.988  3769  3819 I jxcore-log: 
,08-12 11:37:58.988  3769  3819 I jxcore-log: ok 338 Size should be 100
08-12 11:37:58.988  3769  3819 I jxcore-log: 
08-12 11:37:58.990  3769  3819 I jxcore-log: # teardown
08-12 11:37:58.990  3769  3819 I jxcore-log: 
,08-12 11:37:59.073  3769  3819 I jxcore-log: # setup
08-12 11:37:59.073  3769  3819 I jxcore-log: 
,08-12 11:37:59.105  3769  3819 I jxcore-log: # 111. #ThaliPeerPoolInterface - bad enqueues
08-12 11:37:59.105  3769  3819 I jxcore-log: 
,08-12 11:37:59.146  3769  3819 I jxcore-log: ok 339 null arg
08-12 11:37:59.146  3769  3819 I jxcore-log: 
,08-12 11:37:59.147  3769  3819 I jxcore-log: ok 340 wrong arg type
08-12 11:37:59.147  3769  3819 I jxcore-log: 
,08-12 11:37:59.149  3769  3819 I jxcore-log: ok 341 wrong state
08-12 11:37:59.149  3769  3819 I jxcore-log: 
,08-12 11:37:59.151  3769  3819 I jxcore-log: # teardown
08-12 11:37:59.151  3769  3819 I jxcore-log: 
,08-12 11:37:59.190  3769  3819 I jxcore-log: # setup
08-12 11:37:59.190  3769  3819 I jxcore-log: 
,08-12 11:37:59.245  3769  3819 I jxcore-log: # 112. #ThaliPeerPoolInterface - do not allow same object type
08-12 11:37:59.245  3769  3819 I jxcore-log: 
,08-12 11:37:59.281  3769  3819 I jxcore-log: ok 342 good enqueue
08-12 11:37:59.281  3769  3819 I jxcore-log: 
,08-12 11:37:59.283  3769  3819 I jxcore-log: ok 343 should be equal
08-12 11:37:59.283  3769  3819 I jxcore-log: 
,08-12 11:37:59.284  3769  3819 I jxcore-log: # teardown
08-12 11:37:59.284  3769  3819 I jxcore-log: 
,08-12 11:37:59.330  3769  3819 I jxcore-log: # setup
08-12 11:37:59.330  3769  3819 I jxcore-log: 
,08-12 11:37:59.377  3769  3819 I jxcore-log: # 113. #ThaliPeerPoolInterface - make sure we catch kill and dequeue
08-12 11:37:59.377  3769  3819 I jxcore-log: 
,08-12 11:37:59.420  3769  3819 I jxcore-log: ok 344 good enqueue
08-12 11:37:59.420  3769  3819 I jxcore-log: 
,08-12 11:37:59.422  3769  3819 I jxcore-log: ok 345 2nd good enqueue
08-12 11:37:59.422  3769  3819 I jxcore-log: 
,08-12 11:37:59.423  3769  3819 I jxcore-log: ok 346 we are in the pool
08-12 11:37:59.423  3769  3819 I jxcore-log: 
,08-12 11:37:59.427  3769  3819 I jxcore-log: ok 347 We are out of the pool
08-12 11:37:59.427  3769  3819 I jxcore-log: 
,08-12 11:37:59.428  3769  3819 I jxcore-log: ok 348 Action was killed
08-12 11:37:59.428  3769  3819 I jxcore-log: 
08-12 11:37:59.429  3769  3819 I jxcore-log: ok 349 The original kill was called too
08-12 11:37:59.429  3769  3819 I jxcore-log: 
,08-12 11:37:59.430  3769  3819 I jxcore-log: ok 350 second item is still in queue
08-12 11:37:59.430  3769  3819 I jxcore-log: 
,08-12 11:37:59.433  3769  3819 I jxcore-log: # teardown
08-12 11:37:59.433  3769  3819 I jxcore-log: 
,08-12 11:37:59.473  3769  3819 I jxcore-log: # setup
08-12 11:37:59.473  3769  3819 I jxcore-log: 
,08-12 11:37:59.516  3769  3819 I jxcore-log: # 114. #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
08-12 11:37:59.516  3769  3819 I jxcore-log: 
,08-12 11:37:59.559  3769  3819 I jxcore-log: ok 351 good enqueue
08-12 11:37:59.559  3769  3819 I jxcore-log: 
,08-12 11:37:59.560  3769  3819 I jxcore-log: ok 352 first kill
08-12 11:37:59.560  3769  3819 I jxcore-log: 
08-12 11:37:59.561  3769  3819 I jxcore-log: ok 353 second NOOP kill
08-12 11:37:59.561  3769  3819 I jxcore-log: 
,08-12 11:37:59.564  3769  3819 I jxcore-log: # teardown
08-12 11:37:59.564  3769  3819 I jxcore-log: 
,08-12 11:37:59.610  3769  3819 I jxcore-log: # setup
08-12 11:37:59.610  3769  3819 I jxcore-log: 
,08-12 11:37:59.658  3769  3819 I jxcore-log: # 115. Make sure peerDictionaryKey is reasonable
08-12 11:37:59.658  3769  3819 I jxcore-log: 
,08-12 11:37:59.703  3769  3819 I jxcore-log: ok 354 equal keys
08-12 11:37:59.703  3769  3819 I jxcore-log: 
,08-12 11:37:59.704  3769  3819 I jxcore-log: ok 355 not equal connection type
08-12 11:37:59.704  3769  3819 I jxcore-log: 
,08-12 11:37:59.705  3769  3819 I jxcore-log: ok 356 same connection type, different buffer
08-12 11:37:59.705  3769  3819 I jxcore-log: 
,08-12 11:37:59.708  3769  3819 I jxcore-log: # teardown
08-12 11:37:59.708  3769  3819 I jxcore-log: 
,08-12 11:37:59.761  3769  3819 I jxcore-log: # setup
08-12 11:37:59.761  3769  3819 I jxcore-log: 
,08-12 11:37:59.805  3769  3819 I jxcore-log: # 116. Make sure start works
08-12 11:37:59.805  3769  3819 I jxcore-log: 
,08-12 11:37:59.883  3769  3819 I jxcore-log: ok 357 First start and on called correctly
08-12 11:37:59.883  3769  3819 I jxcore-log: 
,08-12 11:37:59.885  3769  3819 I jxcore-log: # teardown
08-12 11:37:59.885  3769  3819 I jxcore-log: 
,08-12 11:37:59.951  3769  3819 I jxcore-log: # setup
08-12 11:37:59.951  3769  3819 I jxcore-log: 
,08-12 11:37:59.996  3769  3819 I jxcore-log: # 117. Make sure stop works
08-12 11:37:59.996  3769  3819 I jxcore-log: 
,08-12 11:38:00.052  3769  3819 I jxcore-log: ok 358 second cleared dictionary
08-12 11:38:00.052  3769  3819 I jxcore-log: 
,08-12 11:38:00.070  3769  3819 I jxcore-log: ok 359 First start and on called correctly
08-12 11:38:00.070  3769  3819 I jxcore-log: 
,08-12 11:38:00.085  3769  3819 I jxcore-log: ok 360 First stop and removeListener called correctly
08-12 11:38:00.085  3769  3819 I jxcore-log: 
,08-12 11:38:00.086  3769  3819 I jxcore-log: ok 361 first action kill called
08-12 11:38:00.086  3769  3819 I jxcore-log: 
08-12 11:38:00.086  3769  3819 I jxcore-log: ok 362 second action kill called
08-12 11:38:00.086  3769  3819 I jxcore-log: 
,08-12 11:38:00.086  3769  3819 I jxcore-log: ok 363 first cleared dictionary
08-12 11:38:00.086  3769  3819 I jxcore-log: 
08-12 11:38:00.087  3769  3819 I jxcore-log: ok 364 second cleared dictionary
08-12 11:38:00.087  3769  3819 I jxcore-log: 
,08-12 11:38:00.090  3769  3819 I jxcore-log: # teardown
08-12 11:38:00.090  3769  3819 I jxcore-log: 
,08-12 11:38:00.231  3769  3819 I jxcore-log: # setup
08-12 11:38:00.231  3769  3819 I jxcore-log: 
,08-12 11:38:00.286  3769  3819 I jxcore-log: # 118. Simple peer event
08-12 11:38:00.286  3769  3819 I jxcore-log: 
,08-12 11:38:01.282  3769  3819 I jxcore-log: ok 365 listener has been set
08-12 11:38:01.282  3769  3819 I jxcore-log: 
,08-12 11:38:01.288  3769  3819 I jxcore-log: ok 366 peer dictionary has expected number of entries
08-12 11:38:01.288  3769  3819 I jxcore-log: 
,08-12 11:38:01.288  3769  3819 I jxcore-log: ok 367 Dictionary and pool have same action
08-12 11:38:01.288  3769  3819 I jxcore-log: 
08-12 11:38:01.289  3769  3819 I jxcore-log: ok 368 ads match
08-12 11:38:01.289  3769  3819 I jxcore-log: 
,08-12 11:38:01.289  3769  3819 I jxcore-log: ok 369 PouchDB matches
08-12 11:38:01.289  3769  3819 I jxcore-log: 
08-12 11:38:01.290  3769  3819 I jxcore-log: ok 370 DB Names match
08-12 11:38:01.290  3769  3819 I jxcore-log: 
,08-12 11:38:01.291  3769  3819 I jxcore-log: ok 371 public keys match
08-12 11:38:01.291  3769  3819 I jxcore-log: 
,08-12 11:38:01.295  3769  3819 I jxcore-log: ok 372 peer dictionary has expected number of entries
08-12 11:38:01.295  3769  3819 I jxcore-log: 
,08-12 11:38:01.296  3769  3819 I jxcore-log: ok 373 Dictionary and pool have same action
08-12 11:38:01.296  3769  3819 I jxcore-log: 
08-12 11:38:01.296  3769  3819 I jxcore-log: ok 374 ads match
08-12 11:38:01.296  3769  3819 I jxcore-log: 
,08-12 11:38:01.297  3769  3819 I jxcore-log: ok 375 PouchDB matches
08-12 11:38:01.297  3769  3819 I jxcore-log: 
08-12 11:38:01.297  3769  3819 I jxcore-log: ok 376 DB Names match
08-12 11:38:01.297  3769  3819 I jxcore-log: 
08-12 11:38:01.298  3769  3819 I jxcore-log: ok 377 public keys match
08-12 11:38:01.298  3769  3819 I jxcore-log: 
,08-12 11:38:01.301  3769  3819 I jxcore-log: ok 378 start called once
08-12 11:38:01.301  3769  3819 I jxcore-log: 
,08-12 11:38:01.301  3769  3819 I jxcore-log: ok 379 kill never called
08-12 11:38:01.301  3769  3819 I jxcore-log: 
08-12 11:38:01.302  3769  3819 I jxcore-log: ok 380 One entry left
08-12 11:38:01.302  3769  3819 I jxcore-log: 
08-12 11:38:01.302  3769  3819 I jxcore-log: ok 381 Dictionary and pool have same action
08-12 11:38:01.302  3769  3819 I jxcore-log: 
,08-12 11:38:01.304  3769  3819 I jxcore-log: ok 382 Start never called
08-12 11:38:01.304  3769  3819 I jxcore-log: 
,08-12 11:38:01.305  3769  3819 I jxcore-log: ok 383 Kill called once
08-12 11:38:01.305  3769  3819 I jxcore-log: 
08-12 11:38:01.305  3769  3819 I jxcore-log: ok 384 no entries left
08-12 11:38:01.305  3769  3819 I jxcore-log: 
,08-12 11:38:01.317  3769  3819 I jxcore-log: ok 385 Third action is dead
08-12 11:38:01.317  3769  3819 I jxcore-log: 
,08-12 11:38:01.317  3769  3819 I jxcore-log: ok 386 peer dictionary has expected number of entries
08-12 11:38:01.317  3769  3819 I jxcore-log: 
08-12 11:38:01.318  3769  3819 I jxcore-log: ok 387 Dictionary and pool have same action
08-12 11:38:01.318  3769  3819 I jxcore-log: 
08-12 11:38:01.318  3769  3819 I jxcore-log: ok 388 ads match
08-12 11:38:01.318  3769  3819 I jxcore-log: 
,08-12 11:38:01.318  3769  3819 I jxcore-log: ok 389 PouchDB matches
08-12 11:38:01.318  3769  3819 I jxcore-log: 
08-12 11:38:01.319  3769  3819 I jxcore-log: ok 390 DB Names match
08-12 11:38:01.319  3769  3819 I jxcore-log: 
08-12 11:38:01.319  3769  3819 I jxcore-log: ok 391 public keys match
08-12 11:38:01.319  3769  3819 I jxcore-log: 
08-12 11:38:01.321  3769  3819 I jxcore-log: # teardown
08-12 11:38:01.321  3769  3819 I jxcore-log: 
,08-12 11:38:01.389  3769  3819 I jxcore-log: # setup
08-12 11:38:01.389  3769  3819 I jxcore-log: 
,08-12 11:38:01.455  3769  3819 I jxcore-log: # 119. Coordinated pull replication from notification test
08-12 11:38:01.455  3769  3819 I jxcore-log: 
,08-12 11:38:01.717  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:38:01.717  3769  3819 I jxcore-log: 
,08-12 11:38:01.719  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 46699
08-12 11:38:01.719  3769  3819 I jxcore-log: 
,08-12 11:38:01.723  3769  3819 D io.jxcore.node.JXcoreExtension: startListeningForAdvertisements
,08-12 11:38:01.725  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 41325, start advertisements: false
,08-12 11:38:01.725  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started
08-12 11:38:01.725  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-12 11:38:01.725  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-12 11:38:01.725  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-12 11:38:01.726  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 11:38:01.726  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-12 11:38:01.728  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 11:38:01.731  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-12 11:38:01.731  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 11:38:01.731  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 11:38:01.731  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:38:01.733  2638  3925 D BtGatt.GattService: registerClient() - UUID=06c806fc-3e1f-443e-bd75-71e6171cb1d9
,08-12 11:38:01.733  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=06c806fc-3e1f-443e-bd75-71e6171cb1d9, clientIf=5
,08-12 11:38:01.734  3769  3780 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 11:38:01.735  2638  2649 D BtGatt.GattService: start scan with filters
,08-12 11:38:01.737  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-12 11:38:01.737  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 11:38:01.738  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-12 11:38:01.738  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-12 11:38:01.738  2638  2679 D BtGatt.ScanManager: handling starting scan
08-12 11:38:01.739  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 11:38:01.740  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-12 11:38:01.740  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-12 11:38:01.740  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 11:38:01.742  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:38:01.751  2638  2676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 11:38:01.751  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:38:01.752  2638  2679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 11:38:01.768  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 11:38:01.768  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:38:01.769  2638  2679 D BtGatt.ScanManager: Starting BLE batch scan
,08-12 11:38:01.769  2638  2679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 11:38:01.784  2638  2676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-12 11:38:01.785  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:38:01.790  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-12 11:38:01.790  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:38:02.241  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-12 11:38:02.241  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-12 11:38:02.242  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:38:02.247  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-12 11:38:02.247  3769  3819 I jxcore-log: 
,08-12 11:38:02.278  3769  3819 D io.jxcore.node.JXcoreExtension: startUpdateAdvertisingAndListening
,08-12 11:38:02.282  3769  3819 I io.jxcore.node.ConnectionHelper: start: Port number: 46699, start advertisements: true
,08-12 11:38:02.282  3769  3819 V io.jxcore.node.ConnectivityMonitor: start: Already started,
08-12 11:38:02.283  3769  3819 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
08-12 11:38:02.283  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
08-12 11:38:02.285  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
08-12 11:38:02.285  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
08-12 11:38:02.285  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
08-12 11:38:02.285  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
08-12 11:38:02.285  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
08-12 11:38:02.285  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
08-12 11:38:02.285  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
08-12 11:38:02.285  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
08-12 11:38:02.285  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
08-12 11:38:02.285  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-12 11:38:02.285  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-12 11:38:02.287  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:38:02.288  2638  3925 D BtGatt.GattService: stopScan() - queue size =1
,08-12 11:38:02.290  2638  2649 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:38:02.291  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-12 11:38:02.297  2638  2638 D BtGatt.ScanManager: awakened up at time 865312
,08-12 11:38:02.299  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-12 11:38:02.304  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-12 11:38:02.304  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-12 11:38:02.304  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-12 11:38:02.305  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-12 11:38:02.306  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 11:38:02.307  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:38:02.307  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:38:02.309  2638  2679 D BtGatt.ScanManager: stopping BLe Batch
,08-12 11:38:02.316  2638  2761 D BtGatt.GattService: registerClient() - UUID=80a84e03-7d09-4b49-bda3-6e052c1425f6
,08-12 11:38:02.317  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=80a84e03-7d09-4b49-bda3-6e052c1425f6, clientIf=5
,08-12 11:38:02.318  3769  3779 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-12 11:38:02.319  2638  3925 D BtGatt.GattService: start scan with filters
,08-12 11:38:02.322  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-12 11:38:02.322  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-12 11:38:02.322  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-12 11:38:02.322  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-12 11:38:02.322  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-12 11:38:02.322  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 11:38:02.323  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-12 11:38:02.324  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-12 11:38:02.324  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-12 11:38:02.324  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-12 11:38:02.324  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-12 11:38:02.324  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-12 11:38:02.324  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-12 11:38:02.324  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-12 11:38:02.325  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-12 11:38:02.325  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:38:02.325  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:38:02.325  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-12 11:38:02.326  2638  2761 D BtGatt.GattService: stopScan() - queue size =0
,08-12 11:38:02.327  2638  3925 D BtGatt.GattService: unregisterClient() - clientIf=5
08-12 11:38:02.327  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 11:38:02.327  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-12 11:38:02.328  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-12 11:38:02.328  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-12 11:38:02.328  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-12 11:38:02.329  3769  3938 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-12 11:38:02.333  3769  3938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-12 11:38:02.333  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:38:02.335  3769  3819 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-12 11:38:02.338  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-12 11:38:02.338  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-12 11:38:02.339  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 F8 CF C5 D9 E5 61
08-12 11:38:02.339  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-12 11:38:02.340  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-12 11:38:02.340  3769  3819 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-12 11:38:02.341  3769  3819 D BluetoothAdapter: STATE_ON
,08-12 11:38:02.345  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=2
,08-12 11:38:02.345  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:38:02.345  2638  2676 D BtGatt.GattService: current time is 865360741787
08-12 11:38:02.346  2638  2676 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -62, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:38:02.346  2638  2761 D BtGatt.GattService: registerClient() - UUID=88631824-fd55-44b1-bbe7-74c7b5070337
,08-12 11:38:02.346  2638  2679 D BtGatt.ScanManager: handling starting scan
08-12 11:38:02.346  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-12 11:38:02.347  2638  2676 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-12 11:38:02.348  2638  2676 E BtGatt.ContextMap: Context not found for ID 5
,08-12 11:38:02.348  2638  2676 D BtGatt.GattService: onClientRegistered() - UUID=88631824-fd55-44b1-bbe7-74c7b5070337, clientIf=5
,08-12 11:38:02.349  3769  3780 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-12 11:38:02.350  2638  2678 D BtGatt.AdvertiseManager: message : 0
,08-12 11:38:02.352  2638  2678 D BtGatt.AdvertiseManager: starting multi advertising
,08-12 11:38:02.355  2638  2676 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-12 11:38:02.355  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:38:02.356  2638  2679 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-12 11:38:02.365  2638  2676 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-12 11:38:02.370  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-12 11:38:02.371  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:38:02.371  2638  2679 D BtGatt.ScanManager: Starting BLE batch scan
08-12 11:38:02.371  2638  2679 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-12 11:38:02.376  2638  2676 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-12 11:38:02.376  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-12 11:38:02.377  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-12 11:38:02.382  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-12 11:38:02.383  3769  3819 I io.jxcore.node.ConnectionHelper: start: OK
,08-12 11:38:02.383  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-12 11:38:02.383  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-12 11:38:02.384  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-12 11:38:02.384  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-12 11:38:02.384  3769  3769 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-12 11:38:02.384  3769  3769 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-12 11:38:02.384  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
08-12 11:38:02.389  3769  3769 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
08-12 11:38:02.390  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
08-12 11:38:02.390  2638  2676 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-12 11:38:02.390  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:38:02.397  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-12 11:38:02.397  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:38:02.404  2638  2676 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-12 11:38:02.404  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:38:02.404  2638  2679 D BtGatt.ScanManager: stopping BLe Batch
,08-12 11:38:02.411  2638  2676 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-12 11:38:02.411  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-12 11:38:02.411  2638  2679 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-12 11:38:02.417  2638  2676 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-12 11:38:02.417  2638  2676 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-12 11:38:02.891  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-12 11:38:02.892  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-12 11:38:02.892  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-12 11:38:02.915  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-12 11:38:02.915  3769  3819 I jxcore-log: 
,08-12 11:38:52.610   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=915624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:39:04.368   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=927383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 11:39:04.528  1513  3941 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-12 11:39:04.530  1513  3941 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 11:39:04.568  1513  3941 W Uploader:  no longer exists, so no auth token.
,08-12 11:39:05.583  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:39:05.585  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 11:39:05.619  1513  3941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 11:39:05.619  1513  3941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 11:39:05.619  1513  3941 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 11:39:05.619  1513  3941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:39:05.635  1513  3941 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 11:39:05.635  1513  3941 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 11:39:05.635  1513  3941 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 11:39:05.800  1513  3941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 11:39:05.801  1513  3941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 11:39:05.801  1513  3941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:39:05.801  1513  3941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:39:05.824  1513  3941 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 11:39:05.824  1513  3941 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68),
08-12 11:39:05.824  1513  3941 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 11:39:06.003  1513  3941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 11:39:06.003  1513  3941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 11:39:06.003  1513  3941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 11:39:06.003  1513  3941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 11:39:06.028  1513  3941 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 11:39:06.028  1513  3941 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 11:39:06.028  1513  3941 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 11:39:42.742   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=965757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:39:54.529   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=977544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 11:40:07.862   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=990877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:40:19.582   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1002597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 11:40:32.903   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1015917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:40:44.636   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1027650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 11:40:57.942   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1040957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:41:09.676   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1052690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 11:41:23.009   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1066024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:41:34.729   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1077744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 11:41:48.076   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1091090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:41:59.796   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1102810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 11:42:13.089   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1116104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:42:24.836   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1127850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 11:42:38.156   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1141170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 11:42:49.889   871  2137 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1152903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 11:43:01.550  3769  3819 I jxcore-log: not ok 392 failed with Error: We ran out of time
08-12 11:43:01.550  3769  3819 I jxcore-log: 
08-12 11:43:01.551  3769  3819 I jxcore-log:   ---
08-12 11:43:01.551  3769  3819 I jxcore-log: 
08-12 11:43:01.551  3769  3819 I jxcore-log:     operator: fail
08-12 11:43:01.551  3769  3819 I jxcore-log: 
08-12 11:43:01.552  3769  3819 I jxcore-log:   ...
08-12 11:43:01.552  3769  3819 I jxcore-log: 
,08-12 11:43:01.564  3769  3819 I jxcore-log: # teardown
08-12 11:43:01.564  3769  3819 I jxcore-log: 
,08-12 11:43:01.602  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,08-12 11:43:01.602  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-12 11:43:01.602  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-12 11:43:01.603  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-12 11:43:01.603  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-12 11:43:01.603  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-12 11:43:01.603  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-12 11:43:01.603  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-12 11:43:01.603  3769  3819 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-12 11:43:01.603  3769  3819 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-12 11:43:01.604  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-12 11:43:01.603  3769  3938 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-12 11:43:01.604  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-12 11:43:01.604  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-12 11:43:01.604  3769  3938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-12 11:43:01.604  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-12 11:43:01.603  3769  3769 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-12 11:43:01.604  3769  3938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-12 11:43:01.606  3769  3819 D BluetoothAdapter: STATE_ON
08-12 11:43:01.606  3769  3819 D BluetoothLeScanner: could not find callback wrapper
08-12 11:43:01.606  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-12 11:43:01.606  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,08-12 11:43:01.608  2638  2678 D BtGatt.AdvertiseManager: message : 1
08-12 11:43:01.609  2638  2678 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-12 11:43:01.630  2638  2676 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-12 11:43:01.630  2638  2676 D BtGatt.GattService: Client app is not null!
,08-12 11:43:01.633  2638  2651 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-12 11:43:01.634  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-12 11:43:01.639  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-12 11:43:01.639  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-12 11:43:01.640  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-12 11:43:01.640  3769  3819 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-12 11:43:01.646  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:43:01.647  3769  3819 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-12 11:43:01.647  3769  3819 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-12 11:43:01.649  3769  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-12 11:43:01.653  3769  3769 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-12 11:43:01.654  3769  3769 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-12 11:43:01.654  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-12 11:43:01.655  3769  3769 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-12 11:43:01.655  3769  3769 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-12 11:43:01.655  3769  3769 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-12 11:43:01.669  3769  3819 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
08-12 11:43:01.670  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-12 11:43:01.670  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-12 11:43:01.670  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-12 11:43:01.673  3769  3819 I jxcore-log: INFO thaliMobile: Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
08-12 11:43:01.673  3769  3819 I jxcore-log: 
,08-12 11:43:01.675  3769  3819 D io.jxcore.node.JXcoreExtension: stopListeningForAdvertisements
08-12 11:43:01.675  3769  3819 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
,08-12 11:43:01.676  3769  3819 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
08-12 11:43:01.676  3769  3819 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-12 11:43:01.687  3769  3819 I jxcore-log: # setup
08-12 11:43:01.687  3769  3819 I jxcore-log: 
,08-12 11:43:01.868  3769  3819 I jxcore-log: # 120. Server is not there
08-12 11:43:01.868  3769  3819 I jxcore-log: 
,08-12 11:43:02.132  3769  3819 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - Error: connect ECONNREFUSED
08-12 11:43:02.132  3769  3819 I jxcore-log: 
,08-12 11:43:02.134  3769  3819 I jxcore-log: ok 393 right error
08-12 11:43:02.134  3769  3819 I jxcore-log: 
,08-12 11:43:02.138  3769  3819 I jxcore-log: # teardown
08-12 11:43:02.138  3769  3819 I jxcore-log: 
,08-12 11:43:02.157  3769  3769 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-12 11:43:02.159  3769  3819 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-12 11:43:02.159  3769  3819 I jxcore-log: 
,08-12 11:43:02.184  3769  3819 I jxcore-log: # setup
08-12 11:43:02.184  3769  3819 I jxcore-log: 
,08-12 11:43:02.269  3769  3819 I jxcore-log: # 121. Server accepts & closes connection
08-12 11:43:02.269  3769  3819 I jxcore-log: 
,08-12 11:43:02.436  3769  3819 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - Error: socket hang up
08-12 11:43:02.436  3769  3819 I jxcore-log: 
,08-12 11:43:02.438  3769  3819 I jxcore-log: ok 394 right error
08-12 11:43:02.438  3769  3819 I jxcore-log: 
,08-12 11:43:02.443  3769  3819 I jxcore-log: # teardown
08-12 11:43:02.443  3769  3819 I jxcore-log: 
,08-12 11:43:02.536  3769  3819 I jxcore-log: # setup
08-12 11:43:02.536  3769  3819 I jxcore-log: 
,08-12 11:43:02.597  3769  3819 I jxcore-log: # 122. Server always returns 500
08-12 11:43:02.597  3769  3819 I jxcore-log: 
,08-12 11:43:02.760  3769  3819 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - 
08-12 11:43:02.760  3769  3819 I jxcore-log: 
,08-12 11:43:02.764  3769  3819 I jxcore-log: ok 395 Got error as expected
08-12 11:43:02.764  3769  3819 I jxcore-log: 
,08-12 11:43:02.768  3769  3819 I jxcore-log: # teardown
08-12 11:43:02.768  3769  3819 I jxcore-log: 
,08-12 11:43:02.902  3769  3819 I jxcore-log: # setup
08-12 11:43:02.902  3769  3819 I jxcore-log: 
,08-12 11:43:02.955  3769  3819 I jxcore-log: # 123. Server always returns 401
08-12 11:43:02.955  3769  3819 I jxcore-log: 
,08-12 11:43:03.163  3769  3819 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - 
08-12 11:43:03.163  3769  3819 I jxcore-log: 
,08-12 11:43:03.165  3769  3819 I jxcore-log: ok 396 Got error as expected
08-12 11:43:03.165  3769  3819 I jxcore-log: 
,08-12 11:43:03.168  3769  3819 I jxcore-log: # teardown
08-12 11:43:03.168  3769  3819 I jxcore-log: 
,08-12 11:43:03.198  3769  3819 I jxcore-log: # setup
08-12 11:43:03.198  3769  3819 I jxcore-log: 
,08-12 11:43:03.254  3769  3819 I jxcore-log: # 124. Server always returns 403
08-12 11:43:03.254  3769  3819 I jxcore-log: 
,08-12 11:43:03.467  3769  3819 I jxcore-log: DEBUG thaliReplicationPeerAction: Got error on replication - 
08-12 11:43:03.467  3769  3819 I jxcore-log: 
,08-12 11:43:03.469  3769  3819 I jxcore-log: ok 397 Got error as expected
08-12 11:43:03.469  3769  3819 I jxcore-log: 
,08-12 11:43:03.472  3769  3819 I jxcore-log: # teardown
08-12 11:43:03.472  3769  3819 I jxcore-log: 
,08-12 11:43:03.516  3769  3819 I jxcore-log: # setup
08-12 11:43:03.516  3769  3819 I jxcore-log: 
,08-12 11:43:03.564  3769  3819 I jxcore-log: # 125. Make sure docs replicate
08-12 11:43:03.564  3769  3819 I jxcore-log: 
,08-12 11:43:04.732  3769  3819 I jxcore-log: DEBUG thaliReplicationPeerAction: Replication resumed
08-12 11:43:04.732  3769  3819 I jxcore-log: 
,08-12 11:43:05.420  3769  3819 I jxcore-log: ok 398 should be equal
08-12 11:43:05.420  3769  3819 I jxcore-log: 
,08-12 11:43:05.421  3769  3819 I jxcore-log: ok 399 All tests passed!
08-12 11:43:05.421  3769  3819 I jxcore-log: 
,08-12 11:43:05.426  3769  3819 I jxcore-log: # teardown
08-12 11:43:05.426  3769  3819 I jxcore-log: 
,08-12 11:43:05.483  3769  3819 I jxcore-log: # setup
08-12 11:43:05.483  3769  3819 I jxcore-log: 
,08-12 11:43:05.559  3769  3819 I jxcore-log: # 126. Do nothing and make sure we time out
08-12 11:43:05.559  3769  3819 I jxcore-log: 
,08-12 11:43:05.987  3769  3819 I jxcore-log: DEBUG thaliReplicationPeerAction: Got paused with undefined
08-12 11:43:05.987  3769  3819 I jxcore-log: 
,08-12 11:43:07.685  3769  3819 I jxcore-log: ok 400 action should be killed
08-12 11:43:07.685  3769  3819 I jxcore-log: 
,08-12 11:43:07.688  3769  3819 I jxcore-log: ok 401 Error should be timed out
08-12 11:43:07.688  3769  3819 I jxcore-log: 
,08-12 11:43:07.808  3769  3819 I jxcore-log: ok 402 No doc found
08-12 11:43:07.808  3769  3819 I jxcore-log: 
,08-12 11:43:07.815  3769  3819 I jxcore-log: # teardown
08-12 11:43:07.815  3769  3819 I jxcore-log: 
,08-12 11:43:07.953  3769  3819 I jxcore-log: # setup
08-12 11:43:07.953  3769  3819 I jxcore-log: 
,08-12 11:43:07.999  3769  3819 I jxcore-log: # 127. Do something and make sure we time out
08-12 11:43:07.999  3769  3819 I jxcore-log: 
,08-12 11:43:09.066  3769  3819 I jxcore-log: DEBUG thaliReplicationPeerAction: Replication resumed
08-12 11:43:09.066  3769  3819 I jxcore-log: 
,08-12 11:43:09.616  3769  3819 I jxcore-log: DEBUG thaliReplicationPeerAction: Got paused with undefined
08-12 11:43:09.616  3769  3819 I jxcore-log: 
,08-12 11:43:09.734  3769  3819 I jxcore-log: ok 403 should be equal
08-12 11:43:09.734  3769  3819 I jxcore-log: 
,08-12 11:43:11.284  3769  3819 I jxcore-log: ok 404 action should be killed
08-12 11:43:11.284  3769  3819 I jxcore-log: 
,08-12 11:43:11.286  3769  3819 I jxcore-log: ok 405 Error should be timed out
08-12 11:43:11.286  3769  3819 I jxcore-log: 
,08-12 11:43:11.305  3769  3819 I jxcore-log: # teardown
08-12 11:43:11.305  3769  3819 I jxcore-log: 
,08-12 11:43:11.342  3769  3819 I jxcore-log: # setup
08-12 11:43:11.342  3769  3819 I jxcore-log: 
,08-12 11:43:11.848  3769  3819 I jxcore-log: # 128. Start replicating and then catch error when server goes
08-12 11:43:11.848  3769  3819 I jxcore-log: 
,08-12 11:43:12.420  3769  3819 I jxcore-log: ok 406 socket hung up
08-12 11:43:12.420  3769  3819 I jxcore-log: 
,08-12 11:43:12.455  3769  3819 I jxcore-log: # teardown
08-12 11:43:12.455  3769  3819 I jxcore-log: 
,08-12 11:43:12.586  3769  3819 I jxcore-log: # setup
08-12 11:43:12.586  3769  3819 I jxcore-log: 
,08-12 11:43:12.645  3769  3819 I jxcore-log: # 129. compareBufferArrays
08-12 11:43:12.645  3769  3819 I jxcore-log: 
,08-12 11:43:12.682  3769  3819 I jxcore-log: ok 407 should throw
08-12 11:43:12.682  3769  3819 I jxcore-log: 
,08-12 11:43:12.683  3769  3819 I jxcore-log: ok 408 should throw
08-12 11:43:12.683  3769  3819 I jxcore-log: 
08-12 11:43:12.683  3769  3819 I jxcore-log: ok 409 (unnamed assert)
08-12 11:43:12.683  3769  3819 I jxcore-log: 
08-12 11:43:12.684  3769  3819 I jxcore-log: ok 410 (unnamed assert)
08-12 11:43:12.684  3769  3819 I jxcore-log: 
,08-12 11:43:12.684  3769  3819 I jxcore-log: ok 411 (unnamed assert)
08-12 11:43:12.684  3769  3819 I jxcore-log: 
08-12 11:43:12.685  3769  3819 I jxcore-log: ok 412 (unnamed assert)
08-12 11:43:12.685  3769  3819 I jxcore-log: 
08-12 11:43:12.685  3769  3819 I jxcore-log: ok 413 (unnamed assert)
08-12 11:43:12.685  3769  3819 I jxcore-log: 
,08-12 11:43:12.687  3769  3819 I jxcore-log: # teardown
08-12 11:43:12.687  3769  3819 I jxcore-log: 
,08-12 11:43:12.722  3769  3819 I jxcore-log: # setup
08-12 11:43:12.722  3769  3819 I jxcore-log: 
,08-12 11:43:12.762  3769  3819 I jxcore-log: # 130. Call start twice and get error
08-12 11:43:12.762  3769  3819 I jxcore-log: 
,08-12 11:43:12.811  3769  3819 I jxcore-log: ok 414 should throw
08-12 11:43:12.811  3769  3819 I jxcore-log: 
,08-12 11:43:12.814  3769  3819 I jxcore-log: # teardown
08-12 11:43:12.814  3769  3819 I jxcore-log: 
,08-12 11:43:12.858  3769  3819 I jxcore-log: # setup
08-12 11:43:12.858  3769  3819 I jxcore-log: 
,08-12 11:43:12.952  3769  3819 I jxcore-log: # 131. Start and make sure it runs
08-12 11:43:12.952  3769  3819 I jxcore-log: 
,08-12 11:43:13.029  3769  3819 I jxcore-log: # teardown
08-12 11:43:13.029  3769  3819 I jxcore-log: 
,08-12 11:43:13.103  3769  3819 I jxcore-log: # setup
08-12 11:43:13.103  3769  3819 I jxcore-log: 
,08-12 11:43:13.141  3769  3819 I jxcore-log: # 132. Make sure getTimeWhenRun is right after start
08-12 11:43:13.141  3769  3819 I jxcore-log: 
,08-12 11:43:13.196  3769  3819 I jxcore-log: ok 415 (unnamed assert)
08-12 11:43:13.196  3769  3819 I jxcore-log: 
,08-12 11:43:13.200  3769  3819 I jxcore-log: # teardown
08-12 11:43:13.200  3769  3819 I jxcore-log: 
,08-12 11:43:13.250  3769  3819 I jxcore-log: # setup
08-12 11:43:13.250  3769  3819 I jxcore-log: 
,08-12 11:43:13.310  3769  3819 I jxcore-log: # 133. Make sure getTimeWhenRun is -1 after function is called
08-12 11:43:13.310  3769  3819 I jxcore-log: 
,08-12 11:43:13.352  3769  3819 I jxcore-log: ok 416 should be equal
08-12 11:43:13.352  3769  3819 I jxcore-log: 
,08-12 11:43:13.358  3769  3819 I jxcore-log: # teardown
08-12 11:43:13.358  3769  3819 I jxcore-log: 
,08-12 11:43:13.406  3769  3819 I jxcore-log: # setup
08-12 11:43:13.406  3769  3819 I jxcore-log: 
,08-12 11:43:13.453  3769  3819 I jxcore-log: # 134. Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
08-12 11:43:13.453  3769  3819 I jxcore-log: 
,08-12 11:43:13.532  3769  3819 I jxcore-log: ok 417 should be equal
08-12 11:43:13.532  3769  3819 I jxcore-log: 
,08-12 11:43:13.533  3769  3819 I jxcore-log: ok 418 should be equal
08-12 11:43:13.533  3769  3819 I jxcore-log: 
08-12 11:43:13.535  3769  3819 I jxcore-log: ok 419 should throw
08-12 11:43:13.535  3769  3819 I jxcore-log: 
,08-12 11:43:13.537  3769  3819 I jxcore-log: # teardown
08-12 11:43:13.537  3769  3819 I jxcore-log: 
,08-12 11:43:13.584  3769  3819 I jxcore-log: # setup
08-12 11:43:13.584  3769  3819 I jxcore-log: 
,08-12 11:43:13.639  3769  3819 I jxcore-log: # 135. Test TransientState
08-12 11:43:13.639  3769  3819 I jxcore-log: 
,08-12 11:43:13.717  3769  3819 I jxcore-log: ok 420 should throw
08-12 11:43:13.717  3769  3819 I jxcore-log: 
,08-12 11:43:13.721  3769  3819 I jxcore-log: ok 421 should throw
08-12 11:43:13.721  3769  3819 I jxcore-log: 
,08-12 11:43:13.723  3769  3819 I jxcore-log: ok 422 should be equal
08-12 11:43:13.723  3769  3819 I jxcore-log: 
08-12 11:43:13.724  3769  3819 I jxcore-log: ok 423 should be equal
08-12 11:43:13.724  3769  3819 I jxcore-log: 
,08-12 11:43:13.726  3769  3819 I jxcore-log: ok 424 should be equal
08-12 11:43:13.726  3769  3819 I jxcore-log: 
08-12 11:43:13.727  3769  3819 I jxcore-log: ok 425 should be equal
08-12 11:43:13.727  3769  3819 I jxcore-log: 
,08-12 11:43:13.727  3769  3819 I jxcore-log: ok 426 (unnamed assert)
08-12 11:43:13.727  3769  3819 I jxcore-log: 
08-12 11:43:13.728  3769  3819 I jxcore-log: ok 427 (unnamed assert)
08-12 11:43:13.728  3769  3819 I jxcore-log: 
08-12 11:43:13.730  3769  3819 I jxcore-log: # teardown
08-12 11:43:13.730  3769  3819 I jxcore-log: 
,08-12 11:43:13.807  3769  3819 I jxcore-log: # setup
08-12 11:43:13.807  3769  3819 I jxcore-log: 
,08-12 11:43:13.876  3769  3819 I jxcore-log: # 136. No peers and empty database
08-12 11:43:13.876  3769  3819 I jxcore-log: 
,08-12 11:43:14.077  3769  3819 I jxcore-log: ok 428 verify failed
08-12 11:43:14.077  3769  3819 I jxcore-log: 
08-12 11:43:14.078  3769  3819 I jxcore-log: ok 429 constructor called once
08-12 11:43:14.078  3769  3819 I jxcore-log: 
,08-12 11:43:14.079  3769  3819 I jxcore-log: ok 430 constructor called with right args
08-12 11:43:14.079  3769  3819 I jxcore-log: 
08-12 11:43:14.079  3769  3819 I jxcore-log: ok 431 match start arg
08-12 11:43:14.079  3769  3819 I jxcore-log: 
08-12 11:43:14.080  3769  3819 I jxcore-log: ok 432 start called once
08-12 11:43:14.080  3769  3819 I jxcore-log: 
08-12 11:43:14.080  3769  3819 I jxcore-log: ok 433 stop called once
08-12 11:43:14.080  3769  3819 I jxcore-log: 
08-12 11:43:14.080  3769  3819 I jxcore-log: ok 434 stop after start
08-12 11:43:14.080  3769  3819 I jxcore-log: 
,08-12 11:43:14.085  3769  3819 I jxcore-log: # teardown
08-12 11:43:14.085  3769  3819 I jxcore-log: 
,08-12 11:43:14.135  3769  3819 I jxcore-log: # setup
08-12 11:43:14.135  3769  3819 I jxcore-log: 
,08-12 11:43:14.169  3769  3819 I jxcore-log: # 137. One peer and empty DB
08-12 11:43:14.169  3769  3819 I jxcore-log: 
,08-12 11:43:14.344  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:14.344  3769  3819 I jxcore-log: 
,08-12 11:43:14.346  3769  3819 I jxcore-log: ok 435 verify failed
08-12 11:43:14.346  3769  3819 I jxcore-log: 
08-12 11:43:14.347  3769  3819 I jxcore-log: ok 436 constructor called once
08-12 11:43:14.347  3769  3819 I jxcore-log: 
,08-12 11:43:14.347  3769  3819 I jxcore-log: ok 437 constructor called with right args
08-12 11:43:14.347  3769  3819 I jxcore-log: 
,08-12 11:43:14.348  3769  3819 I jxcore-log: ok 438 match start arg
08-12 11:43:14.348  3769  3819 I jxcore-log: 
08-12 11:43:14.348  3769  3819 I jxcore-log: ok 439 start called once
08-12 11:43:14.348  3769  3819 I jxcore-log: 
08-12 11:43:14.349  3769  3819 I jxcore-log: ok 440 stop called once
08-12 11:43:14.349  3769  3819 I jxcore-log: 
,08-12 11:43:14.349  3769  3819 I jxcore-log: ok 441 stop after start
08-12 11:43:14.349  3769  3819 I jxcore-log: 
,08-12 11:43:14.356  3769  3819 I jxcore-log: # teardown
08-12 11:43:14.356  3769  3819 I jxcore-log: 
,08-12 11:43:14.433  3769  3819 I jxcore-log: # setup
08-12 11:43:14.433  3769  3819 I jxcore-log: 
,08-12 11:43:14.468  3769  3819 I jxcore-log: # 138. One peer with _Local set behind current seq
08-12 11:43:14.468  3769  3819 I jxcore-log: 
,08-12 11:43:14.719  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:14.719  3769  3819 I jxcore-log: 
,08-12 11:43:14.721  3769  3819 I jxcore-log: ok 442 verify failed
08-12 11:43:14.721  3769  3819 I jxcore-log: 
,08-12 11:43:14.722  3769  3819 I jxcore-log: ok 443 constructor called once
08-12 11:43:14.722  3769  3819 I jxcore-log: 
08-12 11:43:14.722  3769  3819 I jxcore-log: ok 444 constructor called with right args
08-12 11:43:14.722  3769  3819 I jxcore-log: 
,08-12 11:43:14.723  3769  3819 I jxcore-log: ok 445 match start arg
08-12 11:43:14.723  3769  3819 I jxcore-log: 
08-12 11:43:14.723  3769  3819 I jxcore-log: ok 446 start called once
08-12 11:43:14.723  3769  3819 I jxcore-log: 
08-12 11:43:14.723  3769  3819 I jxcore-log: ok 447 stop called once
08-12 11:43:14.723  3769  3819 I jxcore-log: 
,08-12 11:43:14.724  3769  3819 I jxcore-log: ok 448 stop after start
08-12 11:43:14.724  3769  3819 I jxcore-log: 
08-12 11:43:14.726  3769  3819 I jxcore-log: # teardown
08-12 11:43:14.726  3769  3819 I jxcore-log: 
,08-12 11:43:14.789  3769  3819 I jxcore-log: # setup
08-12 11:43:14.789  3769  3819 I jxcore-log: 
,08-12 11:43:14.820  3769  3819 I jxcore-log: # 139. One peer with _Local set equal to current seq
08-12 11:43:14.820  3769  3819 I jxcore-log: 
,08-12 11:43:15.098  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:15.098  3769  3819 I jxcore-log: 
,08-12 11:43:15.100  3769  3819 I jxcore-log: ok 449 verify failed
08-12 11:43:15.100  3769  3819 I jxcore-log: 
,08-12 11:43:15.101  3769  3819 I jxcore-log: ok 450 constructor called once
08-12 11:43:15.101  3769  3819 I jxcore-log: 
,08-12 11:43:15.102  3769  3819 I jxcore-log: ok 451 constructor called with right args
08-12 11:43:15.102  3769  3819 I jxcore-log: 
,08-12 11:43:15.103  3769  3819 I jxcore-log: ok 452 match start arg
08-12 11:43:15.103  3769  3819 I jxcore-log: 
08-12 11:43:15.104  3769  3819 I jxcore-log: ok 453 start called once
08-12 11:43:15.104  3769  3819 I jxcore-log: 
,08-12 11:43:15.104  3769  3819 I jxcore-log: ok 454 stop called once
08-12 11:43:15.104  3769  3819 I jxcore-log: 
08-12 11:43:15.106  3769  3819 I jxcore-log: ok 455 stop after start
08-12 11:43:15.106  3769  3819 I jxcore-log: 
,08-12 11:43:15.109  3769  3819 I jxcore-log: # teardown,
08-12 11:43:15.109  3769  3819 I jxcore-log: 
,08-12 11:43:15.188  3769  3819 I jxcore-log: # setup,
08-12 11:43:15.188  3769  3819 I jxcore-log: 
,08-12 11:43:15.242  3769  3819 I jxcore-log: # 140. One peer with _Local set ahead of current seq (and no this should not happen),
08-12 11:43:15.242  3769  3819 I jxcore-log: 
,08-12 11:43:15.533  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:15.533  3769  3819 I jxcore-log: 
,08-12 11:43:15.534  3769  3819 I jxcore-log: ok 456 verify failed
08-12 11:43:15.534  3769  3819 I jxcore-log: 
08-12 11:43:15.535  3769  3819 I jxcore-log: ok 457 constructor called once
08-12 11:43:15.535  3769  3819 I jxcore-log: 
,08-12 11:43:15.536  3769  3819 I jxcore-log: ok 458 constructor called with right args
08-12 11:43:15.536  3769  3819 I jxcore-log: 
08-12 11:43:15.536  3769  3819 I jxcore-log: ok 459 match start arg
08-12 11:43:15.536  3769  3819 I jxcore-log: 
,08-12 11:43:15.536  3769  3819 I jxcore-log: ok 460 start called once
08-12 11:43:15.536  3769  3819 I jxcore-log: 
08-12 11:43:15.537  3769  3819 I jxcore-log: ok 461 stop called once
08-12 11:43:15.537  3769  3819 I jxcore-log: 
08-12 11:43:15.537  3769  3819 I jxcore-log: ok 462 stop after start
08-12 11:43:15.537  3769  3819 I jxcore-log: 
,08-12 11:43:15.540  3769  3819 I jxcore-log: # teardown
08-12 11:43:15.540  3769  3819 I jxcore-log: ,
,08-12 11:43:15.570  3769  3819 I jxcore-log: # setup
08-12 11:43:15.570  3769  3819 I jxcore-log: 
,08-12 11:43:15.616  3769  3819 I jxcore-log: # 141. Three peers, one not in DB, one behind and one ahead
,08-12 11:43:15.616  3769  3819 I jxcore-log: 
,08-12 11:43:15.909  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:15.909  3769  3819 I jxcore-log: 
,08-12 11:43:15.911  3769  3819 I jxcore-log: ok 463 verify failed
08-12 11:43:15.911  3769  3819 I jxcore-log: 
08-12 11:43:15.911  3769  3819 I jxcore-log: ok 464 constructor called once
08-12 11:43:15.911  3769  3819 I jxcore-log: 
,08-12 11:43:15.912  3769  3819 I jxcore-log: ok 465 constructor called with right args
08-12 11:43:15.912  3769  3819 I jxcore-log: 
08-12 11:43:15.913  3769  3819 I jxcore-log: ok 466 match start arg
08-12 11:43:15.913  3769  3819 I jxcore-log: 
,08-12 11:43:15.913  3769  3819 I jxcore-log: ok 467 start called once
08-12 11:43:15.913  3769  3819 I jxcore-log: 
08-12 11:43:15.913  3769  3819 I jxcore-log: ok 468 stop called once
08-12 11:43:15.913  3769  3819 I jxcore-log: 
08-12 11:43:15.914  3769  3819 I jxcore-log: ok 469 stop after start
08-12 11:43:15.914  3769  3819 I jxcore-log: 
,08-12 11:43:15.917  3769  3819 I jxcore-log: # teardown
08-12 11:43:15.917  3769  3819 I jxcore-log: 
,08-12 11:43:16.043  3769  3819 I jxcore-log: # setup
08-12 11:43:16.043  3769  3819 I jxcore-log: 
,08-12 11:43:16.091  3769  3819 I jxcore-log: # 142. More than maximum peers, make sure we only send maximum allowed
08-12 11:43:16.091  3769  3819 I jxcore-log: 
,08-12 11:43:16.787  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:16.787  3769  3819 I jxcore-log: 
,08-12 11:43:16.790  3769  3819 I jxcore-log: ok 470 verify failed
08-12 11:43:16.790  3769  3819 I jxcore-log: 
,08-12 11:43:16.790  3769  3819 I jxcore-log: ok 471 constructor called once
08-12 11:43:16.790  3769  3819 I jxcore-log: 
,08-12 11:43:16.791  3769  3819 I jxcore-log: ok 472 constructor called with right args
08-12 11:43:16.791  3769  3819 I jxcore-log: 
,08-12 11:43:16.792  3769  3819 I jxcore-log: ok 473 match start arg
08-12 11:43:16.792  3769  3819 I jxcore-log: 
08-12 11:43:16.792  3769  3819 I jxcore-log: ok 474 start called once
08-12 11:43:16.792  3769  3819 I jxcore-log: 
,08-12 11:43:16.793  3769  3819 I jxcore-log: ok 475 stop called once
08-12 11:43:16.793  3769  3819 I jxcore-log: 
08-12 11:43:16.794  3769  3819 I jxcore-log: ok 476 stop after start
08-12 11:43:16.794  3769  3819 I jxcore-log: 
,08-12 11:43:16.800  3769  3819 I jxcore-log: # teardown
08-12 11:43:16.800  3769  3819 I jxcore-log: 
,08-12 11:43:16.955  3769  3819 I jxcore-log: # setup
08-12 11:43:16.955  3769  3819 I jxcore-log: 
,08-12 11:43:16.993  3769  3819 I jxcore-log: # 143. two peers with empty DB, update the doc
08-12 11:43:16.993  3769  3819 I jxcore-log: 
,08-12 11:43:17.264  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:17.264  3769  3819 I jxcore-log: 
,08-12 11:43:17.296  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:17.296  3769  3819 I jxcore-log: 
,08-12 11:43:17.299  3769  3819 I jxcore-log: ok 477 verify failed
08-12 11:43:17.299  3769  3819 I jxcore-log: 
,08-12 11:43:17.300  3769  3819 I jxcore-log: ok 478 constructor called once
08-12 11:43:17.300  3769  3819 I jxcore-log: 
08-12 11:43:17.300  3769  3819 I jxcore-log: ok 479 constructor called with right args
08-12 11:43:17.300  3769  3819 I jxcore-log: 
,08-12 11:43:17.301  3769  3819 I jxcore-log: ok 480 last start before stop
08-12 11:43:17.301  3769  3819 I jxcore-log: 
08-12 11:43:17.302  3769  3819 I jxcore-log: ok 481 empty first start
08-12 11:43:17.302  3769  3819 I jxcore-log: 
,08-12 11:43:17.304  3769  3819 I jxcore-log: ok 482 full second start
08-12 11:43:17.304  3769  3819 I jxcore-log: 
,08-12 11:43:17.304  3769  3819 I jxcore-log: ok 483 only 2 timers
08-12 11:43:17.304  3769  3819 I jxcore-log: 
,08-12 11:43:17.308  3769  3819 I jxcore-log: # teardown
08-12 11:43:17.308  3769  3819 I jxcore-log: 
,08-12 11:43:17.340  3769  3819 I jxcore-log: # setup
08-12 11:43:17.340  3769  3819 I jxcore-log: 
,08-12 11:43:17.387  3769  3819 I jxcore-log: # 144. add doc and make sure tokens refresh when they expire
08-12 11:43:17.387  3769  3819 I jxcore-log: 
,08-12 11:43:17.763  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:17.763  3769  3819 I jxcore-log: 
,08-12 11:43:17.894  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:17.894  3769  3819 I jxcore-log: 
,08-12 11:43:17.964  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:17.964  3769  3819 I jxcore-log: 
,08-12 11:43:17.966  3769  3819 I jxcore-log: ok 484 verify failed
08-12 11:43:17.966  3769  3819 I jxcore-log: 
,08-12 11:43:17.967  3769  3819 I jxcore-log: ok 485 constructor called once
08-12 11:43:17.967  3769  3819 I jxcore-log: 
,08-12 11:43:17.968  3769  3819 I jxcore-log: ok 486 constructor called with right args
08-12 11:43:17.968  3769  3819 I jxcore-log: 
,08-12 11:43:17.968  3769  3819 I jxcore-log: ok 487 start before stop
08-12 11:43:17.968  3769  3819 I jxcore-log: 
,08-12 11:43:17.969  3769  3819 I jxcore-log: ok 488 We got at least 3 calls to start
08-12 11:43:17.969  3769  3819 I jxcore-log: 
,08-12 11:43:17.969  3769  3819 I jxcore-log: ok 489 at least 3
08-12 11:43:17.969  3769  3819 I jxcore-log: 
,08-12 11:43:17.970  3769  3819 I jxcore-log: ok 490 default 1
08-12 11:43:17.970  3769  3819 I jxcore-log: 
,08-12 11:43:17.970  3769  3819 I jxcore-log: ok 491 1 run
08-12 11:43:17.970  3769  3819 I jxcore-log: 
08-12 11:43:17.971  3769  3819 I jxcore-log: ok 492 default 2
08-12 11:43:17.971  3769  3819 I jxcore-log: 
08-12 11:43:17.971  3769  3819 I jxcore-log: ok 493 2 run
08-12 11:43:17.971  3769  3819 I jxcore-log: 
08-12 11:43:17.972  3769  3819 I jxcore-log: ok 494 default 3
08-12 11:43:17.972  3769  3819 I jxcore-log: 
08-12 11:43:17.976  3769  3819 I jxcore-log: # teardown
08-12 11:43:17.976  3769  3819 I jxcore-log: 
,08-12 11:43:18.008  3769  3819 I jxcore-log: # setup
08-12 11:43:18.008  3769  3819 I jxcore-log: 
,08-12 11:43:18.066  3769  3819 I jxcore-log: # 145. start and stop and start and stop
08-12 11:43:18.066  3769  3819 I jxcore-log: 
,08-12 11:43:18.291  3769  3819 I jxcore-log: ok 495 start out null
08-12 11:43:18.291  3769  3819 I jxcore-log: 
,08-12 11:43:18.322  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:18.322  3769  3819 I jxcore-log: 
,08-12 11:43:18.323  3769  3819 I jxcore-log: ok 496 back to null
08-12 11:43:18.323  3769  3819 I jxcore-log: 
,08-12 11:43:18.347  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:18.347  3769  3819 I jxcore-log: 
,08-12 11:43:18.348  3769  3819 I jxcore-log: ok 497 still null
08-12 11:43:18.348  3769  3819 I jxcore-log: 
,08-12 11:43:18.350  3769  3819 I jxcore-log: ok 498 verify failed
08-12 11:43:18.350  3769  3819 I jxcore-log: 
08-12 11:43:18.350  3769  3819 I jxcore-log: ok 499 constructor called once
08-12 11:43:18.350  3769  3819 I jxcore-log: 
08-12 11:43:18.350  3769  3819 I jxcore-log: ok 500 constructor called with right args
08-12 11:43:18.350  3769  3819 I jxcore-log: 
,08-12 11:43:18.351  3769  3819 I jxcore-log: ok 501 first start before first stop
08-12 11:43:18.351  3769  3819 I jxcore-log: 
08-12 11:43:18.351  3769  3819 I jxcore-log: ok 502 first stop before second start
08-12 11:43:18.351  3769  3819 I jxcore-log: 
08-12 11:43:18.352  3769  3819 I jxcore-log: ok 503 second start before second stop
08-12 11:43:18.352  3769  3819 I jxcore-log: 
,08-12 11:43:18.359  3769  3819 I jxcore-log: # teardown
08-12 11:43:18.359  3769  3819 I jxcore-log: 
,08-12 11:43:18.395  3769  3819 I jxcore-log: # setup
08-12 11:43:18.395  3769  3819 I jxcore-log: 
,08-12 11:43:18.429  3769  3819 I jxcore-log: # 146. two identical starts in a row
08-12 11:43:18.429  3769  3819 I jxcore-log: 
,08-12 11:43:18.664  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:18.664  3769  3819 I jxcore-log: 
,08-12 11:43:18.666  3769  3819 I jxcore-log: ok 504 verify failed
08-12 11:43:18.666  3769  3819 I jxcore-log: 
08-12 11:43:18.666  3769  3819 I jxcore-log: ok 505 constructor called once
08-12 11:43:18.666  3769  3819 I jxcore-log: 
,08-12 11:43:18.667  3769  3819 I jxcore-log: ok 506 constructor called with right args
08-12 11:43:18.667  3769  3819 I jxcore-log: 
08-12 11:43:18.667  3769  3819 I jxcore-log: ok 507 (unnamed assert)
08-12 11:43:18.667  3769  3819 I jxcore-log: 
,08-12 11:43:18.682  3769  3819 I jxcore-log: # teardown
08-12 11:43:18.682  3769  3819 I jxcore-log: 
,08-12 11:43:18.715  3769  3819 I jxcore-log: # setup
08-12 11:43:18.715  3769  3819 I jxcore-log: 
,08-12 11:43:18.747  3769  3819 I jxcore-log: # 147. two different starts in a row
08-12 11:43:18.747  3769  3819 I jxcore-log: 
,08-12 11:43:18.947  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:18.947  3769  3819 I jxcore-log: 
,08-12 11:43:18.953  3769  3819 I jxcore-log: ok 508 verify failed
08-12 11:43:18.953  3769  3819 I jxcore-log: 
08-12 11:43:18.953  3769  3819 I jxcore-log: ok 509 constructor called once
08-12 11:43:18.953  3769  3819 I jxcore-log: 
,08-12 11:43:18.954  3769  3819 I jxcore-log: ok 510 constructor called with right args
08-12 11:43:18.954  3769  3819 I jxcore-log: 
08-12 11:43:18.954  3769  3819 I jxcore-log: ok 511 (unnamed assert)
08-12 11:43:18.954  3769  3819 I jxcore-log: 
08-12 11:43:18.954  3769  3819 I jxcore-log: ok 512 (unnamed assert)
08-12 11:43:18.954  3769  3819 I jxcore-log: 
,08-12 11:43:18.960  3769  3819 I jxcore-log: # teardown
08-12 11:43:18.960  3769  3819 I jxcore-log: 
,08-12 11:43:19.080  3769  3819 I jxcore-log: # setup
08-12 11:43:19.080  3769  3819 I jxcore-log: 
,08-12 11:43:19.115  3769  3819 I jxcore-log: # 148. two stops and a start and two stops
08-12 11:43:19.115  3769  3819 I jxcore-log: 
,08-12 11:43:19.368  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:19.368  3769  3819 I jxcore-log: 
,08-12 11:43:19.371  3769  3819 I jxcore-log: ok 513 verify failed
08-12 11:43:19.371  3769  3819 I jxcore-log: 
,08-12 11:43:19.371  3769  3819 I jxcore-log: ok 514 constructor called once
08-12 11:43:19.371  3769  3819 I jxcore-log: 
,08-12 11:43:19.372  3769  3819 I jxcore-log: ok 515 constructor called with right args
08-12 11:43:19.372  3769  3819 I jxcore-log: 
08-12 11:43:19.372  3769  3819 I jxcore-log: ok 516 start before stop
08-12 11:43:19.372  3769  3819 I jxcore-log: 
08-12 11:43:19.378  3769  3819 I jxcore-log: # teardown
08-12 11:43:19.378  3769  3819 I jxcore-log: 
,08-12 11:43:19.479  3769  3819 I jxcore-log: # setup
08-12 11:43:19.479  3769  3819 I jxcore-log: 
,08-12 11:43:19.532  3769  3819 I jxcore-log: # 149. we properly enqueue requests so no then needed
08-12 11:43:19.532  3769  3819 I jxcore-log: 
,08-12 11:43:19.812  3769  3819 I jxcore-log: DEBUG thaliSendNotificationBasedOnReplication: We must have stopped because we are complete -{"status":"cancelled"}
08-12 11:43:19.812  3769  3819 I jxcore-log: 
08-12 11:43:19.814  3769  3819 I jxcore-log: ok 517 verify failed
08-12 11:43:19.814  3769  3819 I jxcore-log: 
,08-12 11:43:19.816  3769  3819 I jxcore-log: ok 518 constructor called once
08-12 11:43:19.816  3769  3819 I jxcore-log: 
,08-12 11:43:19.819  3769  3819 I jxcore-log: ok 519 constructor called with right args
08-12 11:43:19.819  3769  3819 I jxcore-log: 
,08-12 11:43:19.820  3769  3819 I jxcore-log: ok 520 start before stop
08-12 11:43:19.820  3769  3819 I jxcore-log: 
,08-12 11:43:19.835  3769  3819 I jxcore-log: # teardown
08-12 11:43:19.835  3769  3819 I jxcore-log: 
,08-12 11:43:19.874  3769  3819 I jxcore-log: # setup
08-12 11:43:19.874  3769  3819 I jxcore-log: 
,08-12 11:43:19.920  3769  3819 I jxcore-log: # 150. test calculateSeqPointKeyId
08-12 11:43:19.920  3769  3819 I jxcore-log: 
,08-12 11:43:20.011  3769  3819 I jxcore-log: ok 521 should be equal
08-12 11:43:20.011  3769  3819 I jxcore-log: 
,08-12 11:43:20.012  3769  3819 I jxcore-log: ok 522 should be equal
08-12 11:43:20.012  3769  3819 I jxcore-log: 
,08-12 11:43:20.014  3769  3819 I jxcore-log: # teardown
08-12 11:43:20.014  3769  3819 I jxcore-log: 
,08-12 11:43:20.114  3769  3819 I jxcore-log: # setup
08-12 11:43:20.114  3769  3819 I jxcore-log: 
,08-12 11:43:20.162  3769  3819 I jxcore-log: # 151. can create servers manager
08-12 11:43:20.162  3769  3819 I jxcore-log: 
,08-12 11:43:20.205  3769  3819 I jxcore-log: ok 523 serversManager must not be null
08-12 11:43:20.205  3769  3819 I jxcore-log: 
,08-12 11:43:20.206  3769  3819 I jxcore-log: ok 524 serversManager must be an object
08-12 11:43:20.206  3769  3819 I jxcore-log: 
,08-12 11:43:20.209  3769  3819 I jxcore-log: # teardown
08-12 11:43:20.209  3769  3819 I jxcore-log: 
,08-12 11:43:20.257  3769  3819 I jxcore-log: # setup
08-12 11:43:20.257  3769  3819 I jxcore-log: 
,08-12 11:43:20.323  3769  3819 I jxcore-log: # 152. calling stop without start causes error
08-12 11:43:20.323  3769  3819 I jxcore-log: 
,08-12 11:43:20.359  3769  3819 I jxcore-log: ok 525 We need to call start first
08-12 11:43:20.359  3769  3819 I jxcore-log: 
,08-12 11:43:20.361  3769  3819 I jxcore-log: # teardown
08-12 11:43:20.361  3769  3819 I jxcore-log: 
,08-12 11:43:20.424  3769  3819 I jxcore-log: # setup
08-12 11:43:20.424  3769  3819 I jxcore-log: 
,08-12 11:43:20.475  3769  3819 I jxcore-log: # 153. can start/stop servers manager
08-12 11:43:20.475  3769  3819 I jxcore-log: 
,08-12 11:43:20.519  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:43:20.519  3769  3819 I jxcore-log: 
,08-12 11:43:20.524  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 42147
08-12 11:43:20.524  3769  3819 I jxcore-log: 
,08-12 11:43:20.526  3769  3819 I jxcore-log: ok 526 port must be in range
08-12 11:43:20.526  3769  3819 I jxcore-log: 
,08-12 11:43:20.529  3769  3819 I jxcore-log: # teardown
08-12 11:43:20.529  3769  3819 I jxcore-log: 
,08-12 11:43:20.577  3769  3819 I jxcore-log: # setup
08-12 11:43:20.577  3769  3819 I jxcore-log: 
,08-12 11:43:20.628  3769  3819 I jxcore-log: # 154. starting twice resolves with listening port
08-12 11:43:20.628  3769  3819 I jxcore-log: 
,08-12 11:43:20.674  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:43:20.674  3769  3819 I jxcore-log: 
,08-12 11:43:20.680  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 42957
08-12 11:43:20.680  3769  3819 I jxcore-log: 
,08-12 11:43:20.683  3769  3819 I jxcore-log: ok 527 second start should return same port
08-12 11:43:20.683  3769  3819 I jxcore-log: 
,08-12 11:43:20.686  3769  3819 I jxcore-log: # teardown
08-12 11:43:20.686  3769  3819 I jxcore-log: 
,08-12 11:43:20.742  3769  3819 I jxcore-log: # setup
08-12 11:43:20.742  3769  3819 I jxcore-log: 
,08-12 11:43:20.791  3769  3819 I jxcore-log: # 155. terminateIncomingConnection will terminate a connection
08-12 11:43:20.791  3769  3819 I jxcore-log: 
,08-12 11:43:20.859  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:43:20.859  3769  3819 I jxcore-log: 
,08-12 11:43:20.865  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 38980
08-12 11:43:20.865  3769  3819 I jxcore-log: 
,08-12 11:43:20.872  3769  3819 I jxcore-log: DEBUG createNativeListener: new incoming socket
08-12 11:43:20.872  3769  3819 I jxcore-log: 
,08-12 11:43:20.874  3769  3819 I jxcore-log: DEBUG createNativeListener: creating incoming mux
08-12 11:43:20.874  3769  3819 I jxcore-log: 
,08-12 11:43:20.876  3769  3819 I jxcore-log: DEBUG createNativeListener: new mux
08-12 11:43:20.876  3769  3819 I jxcore-log: 
,08-12 11:43:20.878  3769  3819 I jxcore-log: ok 528 we should be connected
08-12 11:43:20.878  3769  3819 I jxcore-log: 
,08-12 11:43:20.882  3769  3819 I jxcore-log: DEBUG createNativeListener: incoming socket close
08-12 11:43:20.882  3769  3819 I jxcore-log: 
08-12 11:43:20.883  3769  3819 I jxcore-log: ok 529 now we are disconnected
08-12 11:43:20.883  3769  3819 I jxcore-log: 
,08-12 11:43:20.897  3769  3819 I jxcore-log: # teardown
08-12 11:43:20.897  3769  3819 I jxcore-log: 
,08-12 11:43:20.966  3769  3819 I jxcore-log: # setup
08-12 11:43:20.966  3769  3819 I jxcore-log: 
,08-12 11:43:21.002  3769  3819 I jxcore-log: # 156. terminate an Outgoing connection will terminate the server
08-12 11:43:21.002  3769  3819 I jxcore-log: 
,08-12 11:43:21.058  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:43:21.058  3769  3819 I jxcore-log: 
,08-12 11:43:21.063  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 47854
08-12 11:43:21.063  3769  3819 I jxcore-log: 
,08-12 11:43:21.066  3769  3819 I jxcore-log: # teardown
08-12 11:43:21.066  3769  3819 I jxcore-log: 
,08-12 11:43:21.122  3769  3819 I jxcore-log: # setup
08-12 11:43:21.122  3769  3819 I jxcore-log: 
,08-12 11:43:21.176  3769  3819 I jxcore-log: # 157. terminate an Outgoing connection with wrong arguments is not harmful
08-12 11:43:21.176  3769  3819 I jxcore-log: 
,08-12 11:43:21.257  3769  3819 I jxcore-log: DEBUG createNativeListener: creating native server
08-12 11:43:21.257  3769  3819 I jxcore-log: 
,08-12 11:43:21.266  3769  3819 I jxcore-log: DEBUG createNativeListener: listening 49651
08-12 11:43:21.266  3769  3819 I jxcore-log: 
,08-12 11:43:21.270  3769  3819 I jxcore-log: # teardown
08-12 11:43:21.270  3769  3819 I jxcore-log: 
,08-12 11:43:21.329  3769  3819 I jxcore-log: # setup
08-12 11:43:21.329  3769  3819 I jxcore-log: 
,08-12 11:43:21.382  3769  3819 I jxcore-log: ok 530 should be in started state
08-12 11:43:21.382  3769  3819 I jxcore-log: 
,08-12 11:43:21.384  3769  3819 I jxcore-log: # 158. After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
08-12 11:43:21.384  3769  3819 I jxcore-log: 
,08-12 11:43:21.497  3769  3819 I jxcore-log: ok 531 peer identifier should match
08-12 11:43:21.497  3769  3819 I jxcore-log: 
,08-12 11:43:21.498  3769  3819 I jxcore-log: ok 532 host address should match
08-12 11:43:21.498  3769  3819 I jxcore-log: 
08-12 11:43:21.498  3769  3819 I jxcore-log: ok 533 port should match
08-12 11:43:21.498  3769  3819 I jxcore-log: 
,08-12 11:43:21.504  3769  3819 I jxcore-log: ok 534 host address should be null
08-12 11:43:21.504  3769  3819 I jxcore-log: 
,08-12 11:43:21.504  3769  3819 I jxcore-log: ok 535 port should should be null
08-12 11:43:21.504  3769  3819 I jxcore-log: 
,08-12 11:43:21.508  3769  3819 I jxcore-log: # teardown
08-12 11:43:21.508  3769  3819 I jxcore-log: 
,08-12 11:43:21.559  3769  3819 I jxcore-log: ok 536 should not be in started state
08-12 11:43:21.559  3769  3819 I jxcore-log: 
,08-12 11:43:21.564  3769  3819 I jxcore-log: # setup
,08-12 11:43:21.564  3769  3819 I jxcore-log: 
,08-12 11:43:21.612  3769  3819 I jxcore-log: ok 537 should be in started state
08-12 11:43:21.612  3769  3819 I jxcore-log: 
,08-12 11:43:21.614  3769  3819 I jxcore-log: # 159. #startUpdateAdvertisingAndListening should use different USN after every invocation
08-12 11:43:21.614  3769  3819 I jxcore-log: 
,08-12 11:43:21.703  3769  3819 I jxcore-log: ok 538 USN should have changed from the first one
08-12 11:43:21.703  3769  3819 I jxcore-log: 
,08-12 11:43:21.710  3769  3819 I jxcore-log: ok 539 when receiving the second byebye, the first USN should be already set
08-12 11:43:21.710  3769  3819 I jxcore-log: 
,08-12 11:43:21.714  3769  3819 I jxcore-log: # teardown
08-12 11:43:21.714  3769  3819 I jxcore-log: 
,08-12 11:43:21.806  3769  3819 I jxcore-log: ok 540 should not be in started state
08-12 11:43:21.806  3769  3819 I jxcore-log: 
,08-12 11:43:21.811  3769  3819 I jxcore-log: # setup
08-12 11:43:21.811  3769  3819 I jxcore-log: 
,08-12 11:43:21.868  3769  3819 I jxcore-log: ok 541 should be in started state
08-12 11:43:21.868  3769  3819 I jxcore-log: 
,08-12 11:43:21.872  3769  3819 I jxcore-log: # 160. messages with invalid location or USN should be ignored
08-12 11:43:21.872  3769  3819 I jxcore-log: 
,08-12 11:43:21.925  3769  3819 I jxcore-log: WARN thaliWifiInfrastructure: Failed to parse a valid port number from location: http://foo.bar:90000
08-12 11:43:21.925  3769  3819 I jxcore-log: 
,08-12 11:43:21.927  3769  3819 I jxcore-log: ok 542 should not have emitted with invalid port
08-12 11:43:21.927  3769  3819 I jxcore-log: 
,08-12 11:43:21.930  3769  3819 I jxcore-log: WARN thaliWifiInfrastructure: Received an invalid USN value: 
08-12 11:43:21.930  3769  3819 I jxcore-log: ,
,08-12 11:43:21.931  3769  3819 I jxcore-log: ok 543 should not have emitted with invalid USN
08-12 11:43:21.931  3769  3819 I jxcore-log: 
,08-12 11:43:21.934  3769  3819 I jxcore-log: # teardown
08-12 11:43:21.934  3769  3819 I jxcore-log: 
,08-12 11:43:21.986  3769  3819 I jxcore-log: ok 544 should not be in started state,
08-12 11:43:21.986  3769  3819 I jxcore-log: 
,08-12 11:43:21.989  3769  3819 I jxcore-log: # setup
08-12 11:43:21.989  3769  3819 I jxcore-log: 
,08-12 11:43:22.051  3769  3819 I jxcore-log: ok 545 should be in started state
08-12 11:43:22.051  3769  3819 I jxcore-log: 
,08-12 11:43:22.054  3769  3819 I jxcore-log: # 161. verify that Thali-specific messages are filtered correctly
08-12 11:43:22.054  3769  3819 I jxcore-log: 
,08-12 11:43:22.232  3769  3819 I jxcore-log: ok 546 irrelevant messages should be ignored
08-12 11:43:22.232  3769  3819 I jxcore-log: 
,08-12 11:43:22.235  3769  3819 I jxcore-log: ok 547 relevant messages should not be ignored
08-12 11:43:22.235  3769  3819 I jxcore-log: 
,08-12 11:43:22.237  3769  3819 I jxcore-log: ok 548 messages from this device should be ignored
08-12 11:43:22.237  3769  3819 I jxcore-log: 
,08-12 11:43:22.243  3769  3819 I jxcore-log: # teardown
08-12 11:43:22.243  3769  3819 I jxcore-log: 
,08-12 11:43:22.281  3769  3819 I jxcore-log: ok 549 should not be in started state
08-12 11:43:22.281  3769  3819 I jxcore-log: 
,08-12 11:43:22.283  3769  3819 I jxcore-log: # setup
08-12 11:43:22.283  3769  3819 I jxcore-log: 
,08-12 11:43:22.327  3769  3819 I jxcore-log: ok 550 should be in started state
08-12 11:43:22.327  3769  3819 I jxcore-log: 
,08-12 11:43:22.330  3769  3819 I jxcore-log: # 162. #startListeningForAdvertisements should fail if start not called
08-12 11:43:22.330  3769  3819 I jxcore-log: 
,08-12 11:43:22.408  3769  3819 I jxcore-log: ok 551 specific error should be returned
08-12 11:43:22.408  3769  3819 I jxcore-log: 
,08-12 11:43:22.410  3769  3819 I jxcore-log: # teardown
08-12 11:43:22.410  3769  3819 I jxcore-log: 
,08-12 11:43:22.484  3769  3819 I jxcore-log: ok 552 should not be in started state
08-12 11:43:22.484  3769  3819 I jxcore-log: 
,08-12 11:43:22.492  3769  3819 I jxcore-log: # setup
08-12 11:43:22.492  3769  3819 I jxcore-log: 
,08-12 11:43:22.536  3769  3819 I jxcore-log: ok 553 should be in started state
08-12 11:43:22.536  3769  3819 I jxcore-log: 
,08-12 11:43:22.539  3769  3819 I jxcore-log: # 163. #startUpdateAdvertisingAndListening should fail if start not called
08-12 11:43:22.539  3769  3819 I jxcore-log: 
,08-12 11:43:22.617  3769  3819 I jxcore-log: ok 554 specific error should be returned
08-12 11:43:22.617  3769  3819 I jxcore-log: 
,08-12 11:43:22.621  3769  3819 I jxcore-log: # teardown
08-12 11:43:22.621  3769  3819 I jxcore-log: 
,08-12 11:43:22.680  3769  3819 I jxcore-log: ok 555 should not be in started state
08-12 11:43:22.680  3769  3819 I jxcore-log: 
,08-12 11:43:22.684  3769  3819 I jxcore-log: # setup
08-12 11:43:22.684  3769  3819 I jxcore-log: 
,08-12 11:43:22.750  3769  3819 I jxcore-log: ok 556 should be in started state
08-12 11:43:22.750  3769  3819 I jxcore-log: 
,08-12 11:43:22.754  3769  3819 I jxcore-log: # 164. #start should fail if called twice in a row
08-12 11:43:22.754  3769  3819 I jxcore-log: 
,08-12 11:43:22.804  3769  3819 I jxcore-log: ok 557 specific error should be received
08-12 11:43:22.804  3769  3819 I jxcore-log: 
,08-12 11:43:22.808  3769  3819 I jxcore-log: # teardown
08-12 11:43:22.808  3769  3819 I jxcore-log: 
,08-12 11:43:22.851  3769  3819 I jxcore-log: ok 558 should not be in started state
08-12 11:43:22.851  3769  3819 I jxcore-log: 
,08-12 11:43:22.854  3769  3819 I jxcore-log: # setup
08-12 11:43:22.854  3769  3819 I jxcore-log: 
,08-12 11:43:22.908  3769  3819 I jxcore-log: ok 559 should be in started state
08-12 11:43:22.908  3769  3819 I jxcore-log: 
,08-12 11:43:22.913  3769  3819 I jxcore-log: # 165. should not be started after stop is called
08-12 11:43:22.913  3769  3819 I jxcore-log: 
,08-12 11:43:22.958  3769  3819 I jxcore-log: ok 560 should not be started
08-12 11:43:22.958  3769  3819 I jxcore-log: 
,08-12 11:43:22.959  3769  3819 I jxcore-log: ok 561 should not be listening
08-12 11:43:22.959  3769  3819 I jxcore-log: 
08-12 11:43:22.959  3769  3819 I jxcore-log: ok 562 should not target listening
08-12 11:43:22.959  3769  3819 I jxcore-log: 
,08-12 11:43:22.960  3769  3819 I jxcore-log: ok 563 should not be advertising
08-12 11:43:22.960  3769  3819 I jxcore-log: 
08-12 11:43:22.961  3769  3819 I jxcore-log: ok 564 should not target advertising
08-12 11:43:22.961  3769  3819 I jxcore-log: 
,08-12 11:43:22.964  3769  3819 I jxcore-log: # teardown
08-12 11:43:22.964  3769  3819 I jxcore-log: 
,08-12 11:43:23.017  3769  3819 I jxcore-log: ok 565 should not be in started state
08-12 11:43:23.017  3769  3819 I jxcore-log: 
,08-12 11:43:23.020  3769  3819 I jxcore-log: # setup
08-12 11:43:23.020  3769  3819 I jxcore-log: 
,08-12 11:43:23.073  3769  3819 I jxcore-log: ok 566 should be in started state
08-12 11:43:23.073  3769  3819 I jxcore-log: 
,08-12 11:43:23.077  3769  3819 I jxcore-log: # 166. #startUpdateAdvertisingAndListening should fail invalid router has been passed
08-12 11:43:23.077  3769  3819 I jxcore-log: 
,08-12 11:43:23.141  3769  3819 I jxcore-log: ERROR thaliWifiInfrastructure: Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
08-12 11:43:23.141  3769  3819 I jxcore-log: 
,08-12 11:43:23.145  3769  3819 I jxcore-log: ok 567 specific error should be received
08-12 11:43:23.145  3769  3819 I jxcore-log: 
,08-12 11:43:23.148  3769  3819 I jxcore-log: # teardown
08-12 11:43:23.148  3769  3819 I jxcore-log: 
,08-12 11:43:23.221  3769  3819 I jxcore-log: ok 568 should not be in started state
08-12 11:43:23.221  3769  3819 I jxcore-log: 
,08-12 11:43:23.247  3769  3819 I jxcore-log: # setup
08-12 11:43:23.247  3769  3819 I jxcore-log: 
,08-12 11:43:23.287  3769  3819 I jxcore-log: ok 569 should be in started state
08-12 11:43:23.287  3769  3819 I jxcore-log: 
,08-12 11:43:23.291  3769  3819 I jxcore-log: # 167. #startUpdateAdvertisingAndListening should fail if router server starting fails
08-12 11:43:23.291  3769  3819 I jxcore-log: 
,08-12 11:43:23.362  3769  3819 I jxcore-log: ERROR thaliWifiInfrastructure: Router server emitted an error: Error: listen EADDRINUSE
08-12 11:43:23.362  3769  3819 I jxcore-log: 
,08-12 11:43:23.364  3769  3819 I jxcore-log: ok 570 specific error expected
08-12 11:43:23.364  3769  3819 I jxcore-log: 
,08-12 11:43:23.367  3769  3819 I jxcore-log: # teardown
08-12 11:43:23.367  3769  3819 I jxcore-log: 
,08-12 11:43:23.407  3769  3819 I jxcore-log: ok 571 should not be in started state
08-12 11:43:23.407  3769  3819 I jxcore-log: 
,08-12 11:43:23.409  3769  3819 I jxcore-log: # setup
08-12 11:43:23.409  3769  3819 I jxcore-log: 
,08-12 11:43:23.456  3769  3819 I jxcore-log: ok 572 should be in started state
08-12 11:43:23.456  3769  3819 I jxcore-log: 
,08-12 11:43:23.461  3769  3819 I jxcore-log: # 168. #startUpdateAdvertisingAndListening should start hosting given router object
08-12 11:43:23.461  3769  3819 I jxcore-log: 
,08-12 11:43:23.580  3769  3819 I jxcore-log: ok 573 server should respond with code 200
08-12 11:43:23.580  3769  3819 I jxcore-log: 
,08-12 11:43:23.587  3769  3819 I jxcore-log: # teardown
08-12 11:43:23.587  3769  3819 I jxcore-log: 
,08-12 11:43:23.714  3769  3819 I jxcore-log: ok 574 should not be in started state
08-12 11:43:23.714  3769  3819 I jxcore-log: 
,08-12 11:43:23.720  3769  3819 I jxcore-log: # setup
08-12 11:43:23.720  3769  3819 I jxcore-log: 
,08-12 11:43:23.761  3769  3819 I jxcore-log: ok 575 should be in started state
08-12 11:43:23.761  3769  3819 I jxcore-log: 
,08-12 11:43:23.763  3769  3819 I jxcore-log: # 169. #startUpdateAdvertisingAndListening bad psk should be rejected object
08-12 11:43:23.763  3769  3819 I jxcore-log: 
,08-12 11:43:23.858  3769  3819 I jxcore-log: ok 576 Connection should be rejected
08-12 11:43:23.858  3769  3819 I jxcore-log: 
,08-12 11:43:23.863  3769  3819 I jxcore-log: # teardown
08-12 11:43:23.863  3769  3819 I jxcore-log: 
,08-12 11:43:23.896  3769  3819 I jxcore-log: ok 577 should not be in started state
08-12 11:43:23.896  3769  3819 I jxcore-log: 
,08-12 11:43:23.900  3769  3819 I jxcore-log: # setup
08-12 11:43:23.900  3769  3819 I jxcore-log: 
,08-12 11:43:23.971  3769  3819 I jxcore-log: ok 578 should be in started state
08-12 11:43:23.971  3769  3819 I jxcore-log: 
,08-12 11:43:23.980  3769  3819 I jxcore-log: # 170. #stop can be called multiple times in a row
08-12 11:43:23.980  3769  3819 I jxcore-log: 
,08-12 11:43:24.020  3769  3819 I jxcore-log: ok 579 should be in stopped state
08-12 11:43:24.020  3769  3819 I jxcore-log: 
,08-12 11:43:24.021  3769  3819 I jxcore-log: ok 580 should still be in stopped state
08-12 11:43:24.021  3769  3819 I jxcore-log: 
,08-12 11:43:24.024  3769  3819 I jxcore-log: # teardown
08-12 11:43:24.024  3769  3819 I jxcore-log: 
,08-12 11:43:24.079  3769  3819 I jxcore-log: ok 581 should not be in started state
08-12 11:43:24.079  3769  3819 I jxcore-log: 
,08-12 11:43:24.081  3769  3819 I jxcore-log: # setup
08-12 11:43:24.081  3769  3819 I jxcore-log: 
,08-12 11:43:24.136  3769  3819 I jxcore-log: ok 582 should be in started state
08-12 11:43:24.136  3769  3819 I jxcore-log: 
,08-12 11:43:24.139  3769  3819 I jxcore-log: # 171. #startListeningForAdvertisements can be called multiple times in a row
08-12 11:43:24.139  3769  3819 I jxcore-log: 
,08-12 11:43:24.193  3769  3819 I jxcore-log: ok 583 should be in listening state
08-12 11:43:24.193  3769  3819 I jxcore-log: 
,08-12 11:43:24.197  3769  3819 I jxcore-log: ok 584 should still be in listening state
08-12 11:43:24.197  3769  3819 I jxcore-log: 
,08-12 11:43:24.200  3769  3819 I jxcore-log: # teardown
08-12 11:43:24.200  3769  3819 I jxcore-log: 
,08-12 11:43:24.266  3769  3819 I jxcore-log: ok 585 should not be in started state
08-12 11:43:24.266  3769  3819 I jxcore-log: 
,08-12 11:43:24.273  3769  3819 I jxcore-log: # setup
08-12 11:43:24.273  3769  3819 I jxcore-log: 
,08-12 11:43:24.313  3769  3819 I jxcore-log: ok 586 should be in started state
08-12 11:43:24.313  3769  3819 I jxcore-log: 
,08-12 11:43:24.315  3769  3819 I jxcore-log: # 172. #stopListeningForAdvertisements can be called multiple times in a row
08-12 11:43:24.315  3769  3819 I jxcore-log: 
,08-12 11:43:24.385  3769  3819 I jxcore-log: ok 587 should not be in listening state
08-12 11:43:24.385  3769  3819 I jxcore-log: 
,08-12 11:43:24.387  3769  3819 I jxcore-log: ok 588 should still not be in listening state
08-12 11:43:24.387  3769  3819 I jxcore-log: 
,08-12 11:43:24.388  3769  3819 I jxcore-log: # teardown
08-12 11:43:24.388  3769  3819 I jxcore-log: 
,08-12 11:43:24.428  3769  3819 I jxcore-log: ok 589 should not be in started state
08-12 11:43:24.428  3769  3819 I jxcore-log: 
,08-12 11:43:24.430  3769  3819 I jxcore-log: # setup
08-12 11:43:24.430  3769  3819 I jxcore-log: 
,08-12 11:43:24.517  3769  3819 I jxcore-log: ok 590 should be in started state
08-12 11:43:24.517  3769  3819 I jxcore-log: 
,08-12 11:43:24.521  3769  3819 I jxcore-log: # 173. #stopAdvertisingAndListening can be called multiple times in a row
08-12 11:43:24.521  3769  3819 I jxcore-log: 
,08-12 11:43:24.564  3769  3819 I jxcore-log: ok 591 should not be in advertising state
08-12 11:43:24.564  3769  3819 I jxcore-log: 
,08-12 11:43:24.565  3769  3819 I jxcore-log: ok 592 should still not be in advertising state
08-12 11:43:24.565  3769  3819 I jxcore-log: 
,08-12 11:43:24.567  3769  3819 I jxcore-log: # teardown
08-12 11:43:24.567  3769  3819 I jxcore-log: 
,08-12 11:43:24.621  3769  3819 I jxcore-log: ok 593 should not be in started state
08-12 11:43:24.621  3769  3819 I jxcore-log: 
,08-12 11:43:24.625  3769  3819 I jxcore-log: # setup
08-12 11:43:24.625  3769  3819 I jxcore-log: 
,08-12 11:43:24.671  3769  3819 I jxcore-log: ok 594 should be in started state
08-12 11:43:24.671  3769  3819 I jxcore-log: 
,08-12 11:43:24.674  3769  3819 I jxcore-log: # 174. functions are run from a queue in the right order
08-12 11:43:24.674  3769  3819 I jxcore-log: 
,08-12 11:43:24.759  3769  3819 I jxcore-log: ok 595 call order must match
08-12 11:43:24.759  3769  3819 I jxcore-log: 
,08-12 11:43:24.762  3769  3819 I jxcore-log: # teardown
08-12 11:43:24.762  3769  3819 I jxcore-log: 
,08-12 11:43:24.840  3769  3819 I jxcore-log: ok 596 should not be in started state
08-12 11:43:24.840  3769  3819 I jxcore-log: 
,08-12 11:43:24.849  3769  3819 I jxcore-log: # setup
08-12 11:43:24.849  3769  3819 I jxcore-log: 
,08-12 11:43:24.889  3769  3819 I jxcore-log: ok 597 should be in started state
08-12 11:43:24.889  3769  3819 I jxcore-log: 
08-12 11:43:24.891  3769  3819 I jxcore-log: # 175. does not get peer changes from self
08-12 11:43:24.891  3769  3819 I jxcore-log: 
,08-12 11:43:25.980  3769  3819 I jxcore-log: ok 598 USN must have changed again
08-12 11:43:25.980  3769  3819 I jxcore-log: 
,08-12 11:43:26.978  3769  3819 I jxcore-log: # teardown
08-12 11:43:26.978  3769  3819 I jxcore-log: 
,08-12 11:43:27.057  3769  3819 I jxcore-log: ok 599 should not be in started state
08-12 11:43:27.057  3769  3819 I jxcore-log: 
,08-12 11:43:27.062  3769  3819 I jxcore-log: # setup
08-12 11:43:27.062  3769  3819 I jxcore-log: 
,08-12 11:43:27.130  3769  3819 I jxcore-log: # 176. #ThaliPeerPoolDefault - single action
08-12 11:43:27.130  3769  3819 I jxcore-log: 
,08-12 11:43:27.172  3769  3819 I jxcore-log: ok 600 is an agent
08-12 11:43:27.172  3769  3819 I jxcore-log: 
,08-12 11:43:27.173  3769  3819 I jxcore-log: ok 601 enqueue is fine
08-12 11:43:27.173  3769  3819 I jxcore-log: 
,08-12 11:43:27.174  3769  3819 I jxcore-log: ok 602 Everything should be off the queue
08-12 11:43:27.174  3769  3819 I jxcore-log: 
08-12 11:43:27.176  3769  3819 I jxcore-log: # teardown
08-12 11:43:27.176  3769  3819 I jxcore-log: 
,08-12 11:43:27.253  3769  3819 I jxcore-log: # setup
08-12 11:43:27.253  3769  3819 I jxcore-log: 
,08-12 11:43:27.303  3769  3819 I jxcore-log: # 177. #ThaliPeerPoolDefault - multiple actions
08-12 11:43:27.303  3769  3819 I jxcore-log: 
,08-12 11:43:27.353  3769  3819 I jxcore-log: ok 603 is an agent
08-12 11:43:27.353  3769  3819 I jxcore-log: 
,08-12 11:43:27.354  3769  3819 I jxcore-log: ok 604 first enqueue is fine
08-12 11:43:27.354  3769  3819 I jxcore-log: 
,08-12 11:43:27.356  3769  3819 I jxcore-log: ok 605 is an agent
08-12 11:43:27.356  3769  3819 I jxcore-log: 
,08-12 11:43:27.356  3769  3819 I jxcore-log: ok 606 second enqueue is fine
08-12 11:43:27.356  3769  3819 I jxcore-log: 
08-12 11:43:27.359  3769  3819 I jxcore-log: ok 607 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
08-12 11:43:27.359  3769  3819 I jxcore-log: 
,08-12 11:43:27.360  3769  3819 I jxcore-log: ok 608 Queue is empty
08-12 11:43:27.360  3769  3819 I jxcore-log: 
,08-12 11:43:27.363  3769  3819 I jxcore-log: # teardown
08-12 11:43:27.363  3769  3819 I jxcore-log: 
,08-12 11:43:27.429  3769  3819 I jxcore-log: # setup
08-12 11:43:27.429  3769  3819 I jxcore-log: 
,08-12 11:43:27.472  3769  3819 I jxcore-log: # 178. #ThaliPeerPoolDefault - PSK Pool works
08-12 11:43:27.472  3769  3819 I jxcore-log: 
,08-12 11:43:27.526  3769  3819 I jxcore-log: ok 609 is an agent
08-12 11:43:27.526  3769  3819 I jxcore-log: 
,08-12 11:43:27.528  3769  3819 I jxcore-log: ok 610 good enqueue
08-12 11:43:27.528  3769  3819 I jxcore-log: 
,08-12 11:43:27.565  3769  3819 I jxcore-log: ok 611 Identity should match
08-12 11:43:27.565  3769  3819 I jxcore-log: 
,08-12 11:43:27.589  3769  3819 I jxcore-log: ok 612 Got expected response
08-12 11:43:27.589  3769  3819 I jxcore-log: 
,08-12 11:43:27.590  3769  3819 I jxcore-log: ok 613 Got psk call back
08-12 11:43:27.590  3769  3819 I jxcore-log: 
,08-12 11:43:27.593  3769  3819 I jxcore-log: # teardown
08-12 11:43:27.593  3769  3819 I jxcore-log: 
,08-12 11:43:27.746  3769  3819 I jxcore-log: # setup
08-12 11:43:27.746  3769  3819 I jxcore-log: 
,08-12 11:43:27.794  3769  3819 I jxcore-log: # 179. #ThaliPeerPoolDefault - stop
08-12 11:43:27.794  3769  3819 I jxcore-log: 
,08-12 11:43:27.838  3769  3819 I jxcore-log: ok 614 is an agent
08-12 11:43:27.838  3769  3819 I jxcore-log: 
,08-12 11:43:27.839  3769  3819 I jxcore-log: ok 615 enqueue worked
08-12 11:43:27.839  3769  3819 I jxcore-log: 
08-12 11:43:27.839  3769  3819 I jxcore-log: ok 616 is an agent
08-12 11:43:27.839  3769  3819 I jxcore-log: 
,08-12 11:43:27.840  3769  3819 I jxcore-log: ok 617 enqueue 2 worked
08-12 11:43:27.840  3769  3819 I jxcore-log: 
08-12 11:43:27.841  3769  3819 I jxcore-log: ok 618 start action is killed
08-12 11:43:27.841  3769  3819 I jxcore-log: 
08-12 11:43:27.842  3769  3819 I jxcore-log: ok 619 killed action is still killed
08-12 11:43:27.842  3769  3819 I jxcore-log: 
,08-12 11:43:27.842  3769  3819 I jxcore-log: ok 620 inQueue is empty
08-12 11:43:27.842  3769  3819 I jxcore-log: 
,08-12 11:43:27.845  3769  3819 I jxcore-log: ok 621 Make sure we won enqueue after stopping
08-12 11:43:27.845  3769  3819 I jxcore-log: 
08-12 11:43:27.848  3769  3819 I jxcore-log: # teardown
08-12 11:43:27.848  3769  3819 I jxcore-log: 
,08-12 11:43:27.992  3769  3819 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 11:43:27.992  3769  3819 I jxcore-log: 
,08-12 11:43:28.627  3965  3965 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-12 11:43:28.635  3965  3965 D AndroidRuntime: CheckJNI is OFF
,08-12 11:43:28.677  3965  3965 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-12 11:43:28.724  3965  3965 I Radio-JNI: register_android_hardware_Radio DONE
,08-12 11:43:28.746  3965  3965 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 11:43:28.759   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-12 11:43:28.760   871   884 I ActivityManager: Killing 3769:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-12 11:43:28.913   871   894 W PackageSettings: Skipping PackageSetting{60206b com.example.hello/10273} due to missing metadata
,08-12 11:43:28.916   871  1958 I WindowState: WIN DEATH: Window{568b2eb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 11:43:28.917   871   882 D GraphicsStats: Buffer count: 2
08-12 11:43:28.917   871  1314 D WifiService: Client connection lost with reason: 4
,08-12 11:43:28.957   871   894 I art     : Starting a blocking GC Explicit
,08-12 11:43:28.980   871   884 E libprocessgroup: failed to kill 1 processes for processgroup 3769
,08-12 11:43:28.981   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-12 11:43:28.982   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-12 11:43:28.983   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-12 11:43:28.983   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-12 11:43:28.983   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:43:28.983   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:28.983   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:43:28.983   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-12 11:43:28.983   871   884 I ActivityManager:   Force finishing activity ActivityRecord{ea4ccd0 u0 com.test.thalitest/.MainActivity t2}
,08-12 11:43:29.001   871  1944 W ActivityManager: Spurious death for ProcessRecord{51f9947 0:com.test.thalitest/u0a0}, curProc for 3769: null
,08-12 11:43:29.001   871   894 I art     : Explicit concurrent mark sweep GC freed 17197(1375KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.127ms total 43.271ms
,08-12 11:43:29.033   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-12 11:43:29.036  3965  3965 I art     : System.exit called, status: 0
08-12 11:43:29.036  3965  3965 I AndroidRuntime: VM exiting with result code 0.
,08-12 11:43:29.040   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-12 11:43:29.055   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-12 11:43:29.060  2638  2638 D BluetoothMapAppObserver: onReceive
08-12 11:43:29.060  2638  2638 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-12 11:43:29.060  2039  2276 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 11:43:29.068   871  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 11:43:29.070  3611  3611 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-12 11:43:29.072  1863  1863 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-12 11:43:29.076  1863  3976 I Keyboard.Facilitator.DecoderInitializer: run()
,08-12 11:43:29.079  1863  3976 I Decoder : createOrResetDecoder
,08-12 11:43:29.104  1916  1916 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-12 11:43:29.123  1701  3980 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-12 11:43:29.141  1513  1513 I ConfigService: onCreate
,08-12 11:43:29.158  1513  1513 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-12 11:43:29.158   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 11:43:29.159  1513  1513 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-12 11:43:29.161  1863  3976 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-12 11:43:29.192  1728  3983 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-12 11:43:29.192  1728  3983 D AccountUtils: Clearing selected account for com.test.thalitest
,08-12 11:43:29.203  1863  3976 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-12 11:43:29.205  1863  3976 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-12 11:43:29.205  1863  3976 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-12 11:43:29.206  1863  3976 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-12 11:43:29.206  1863  3976 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-12 11:43:29.207  1863  3976 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict,
,08-12 11:43:29.207  1863  3976 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-12 11:43:29.207  1863  3976 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-12 11:43:29.207  1863  3976 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-12 11:43:29.207  1863  3976 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-12 11:43:29.208  1863  3976 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-12 11:43:29.208  1863  3976 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-12 11:43:29.208  1863  3976 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-12 11:43:29.216  1728  3983 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-12 11:43:29.220  1701  3980 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-12 11:43:29.225  1701  3980 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-12 11:43:29.225  1701  3980 E AndroidRuntime: Process: android.process.acore, PID: 1701
08-12 11:43:29.225  1701  3980 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.225  1701  3980 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 11:43:29.232   871  3988 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:43:29.232   871  3988 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:43:29.232   871  3988 E DropBoxManagerService: 	... 5 more
,08-12 11:43:29.233  1701  3980 I Process : Sending signal. PID: 1701 SIG: 9
,08-12 11:43:29.236  1728  3983 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.236  1728  3983 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.236  1728  3983 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 11:43:29.237  1728  3983 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-12 11:43:29.257  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 11:43:29.257  1728  1728 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 11:43:29.267  1728  1728 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-12 11:43:29.267  1728  1728 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-12 11:43:29.270  1728  3990 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 11:43:29.271  1728  3990 E DriveAsyncService: disk I/O error (code 3850)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:43:29.271  1728  3990 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,08-12 11:43:29.281   279   279 E lowmemorykiller: Error writing /proc/1701/oom_score_adj; errno=22
,08-12 11:43:29.282   279   279 E lowmemorykiller: Error writing /proc/1701/oom_score_adj; errno=22
,08-12 11:43:29.288  1932  2489 E ReflectionEngine: Failed to save models
08-12 11:43:29.288  1932  2489 E ReflectionEngine: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/files/engine_16: open failed: EROFS (Read-only file system)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.BT(ReflectionEngine.java:123)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:240)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at libcore.io.Posix.open(Native Method)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:43:29.288  1932  2489 E ReflectionEngine: 	... 16 more
,08-12 11:43:29.297   871  1956 I ActivityManager: Start proc 3997:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-12 11:43:29.298  1985  3993 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-12 11:43:29.304  1728  3994 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-12 11:43:29.306  1932  2489 E ObservedEventLogger: Failed to write the stream file
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2431: open failed: EROFS (Read-only file system)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:43:29.306  1932  2489 E ObservedEventLogger: 	... 16 more
,08-12 11:43:29.307  1932  2489 E ObservedEventLogger: Failed to write the stream file
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: java.io.FileNotFoundException: /data/user/0/com.google.android.googlequicksearchbox/app_prediction/events_2432: open failed: EROFS (Read-only file system)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.U(ObservedEventLogger.java:206)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.i.a(ObservedEventLogger.java:104)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.s.x(ReflectionEngine.java:247)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.b(ReflectionServiceHandler.java:117)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t.a(ReflectionServiceHandler.java:33)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.extradex.reflection.t$1.run(ReflectionServiceHandler.java:101)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at libcore.io.Posix.open(Native Method)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:43:29.307  1932  2489 E ObservedEventLogger: 	... 16 more
,08-12 11:43:29.299  1728  3991 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.299  1728  3991 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.320  1728  3991 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-12 11:43:29.341  1728  3994 E AndroidRuntime: Process: com.google.android.gms, PID: 1728
08-12 11:43:29.341  1728  3994 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 11:43:29.341  1728  3994 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-12 11:43:29.342  1728  3991 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-12 11:43:29.342  1728  3991 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-12 11:43:29.344  1728  3991 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
,08-12 11:43:29.350  1728  3991 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-12 11:43:29.350   871  4010 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:43:29.350   871  4010 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:43:29.350   871  4010 E DropBoxManagerService: 	... 5 more
08-12 11:43:29.350  1728  3991 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
08-12 11:43:29.350  1728  3991 I Process : Sending signal. PID: 1728 SIG: 9
08-12 11:43:29.355  1932  2016 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-12 11:43:29.360   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-12 11:43:29.361   871   883 E PackageManager: Failed to write settings, restoring backup
08-12 11:43:29.361   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 11:43:29.361   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 11:43:29.361   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 11:43:29.361   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 11:43:29.361   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 11:43:29.361   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:43:29.361   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.361   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:43:29.363   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-12 11:43:29.363   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 11:43:29.363   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:43:29.363   871   884 E DropBoxManagerService: 	... 13 more
08-12 11:43:29.371   871   881 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3769 uid 10000
08-12 11:43:29.372   871  1958 I ActivityManager: Start proc 4011:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-12 11:43:29.372  1932  2016 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 11:43:29.372  1932  2016 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1932
08-12 11:43:29.372  1932  2016 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.372  1932  2016 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:43:29.373   871  1379 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-12 11:43:29.374   871  4016 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:43:29.374   871  4016 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:43:29.374   871  4016 E DropBoxManagerService: 	... 5 more
,08-12 11:43:29.376   279   279 E lowmemorykiller: Error writing /proc/1701/oom_score_adj; errno=22
08-12 11:43:29.377  1863  1863 I Keyboard.Facilitator: onFinishInput()
08-12 11:43:29.378  1932  2016 I Process : Sending signal. PID: 1932 SIG: 9
08-12 11:43:29.392  1985  3993 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-12 11:43:29.404  3997  3997 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm
08-12 11:43:29.413  3997  3997 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
08-12 11:43:29.416  1985  3993 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-12 11:43:29.417  1985  3993 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 11:43:29.417  1985  3993 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1985
08-12 11:43:29.417  1985  3993 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.417  1985  3993 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:43:29.419   871  1971 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-12 11:43:29.419   871  1971 I ActivityManager: Killing 1985:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
08-12 11:43:29.419   871  4024 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:43:29.419   871  4024 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:43:29.419   871  4024 E DropBoxManagerService: 	... 5 more
,08-12 11:43:29.450  3997  4025 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.keychain/databases/grants.db'.
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.450  3997  4025 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-12 11:43:29.450  3997  4025 E AndroidRuntime: Process: com.android.keychain, PID: 3997
08-12 11:43:29.450  3997  4025 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.j,ava:791)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 11:43:29.450  3997  4025 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-12 11:43:29.467   871   882 D GraphicsStats: Buffer count: 1
08-12 11:43:29.467   871  1956 I WindowState: WIN DEATH: Window{3c8cae2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-12 11:43:29.472   871  1314 D WifiService: Client connection lost with reason: 4
,08-12 11:43:29.480   279   279 E lowmemorykiller: Error writing /proc/1701/oom_score_adj; errno=22
,08-12 11:43:29.481   871  1971 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@fb10be8)
,08-12 11:43:29.483   871  1315 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-12 11:43:29.484   871  1315 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-12 11:43:29.485   871   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1932) has died
,08-12 11:43:29.485   871  4026 E DropBoxManagerService: Can't write: system_app_crash
08-12 11:43:29.485   871  4026 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 11:43:29.485   871  4026 E DropBoxManagerService: 	... 5 more
,08-12 11:43:29.486   871   882 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-12 11:43:29.487   871   882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-12 11:43:29.492   871  1969 W ActivityManager: Spurious death for ProcessRecord{5ff870c 0:com.google.android.googlequicksearchbox:search/u0a28}, curProc for 1985: null
,08-12 11:43:29.492   871  1944 I ActivityManager: Process com.google.android.gms (pid 1728) has died
08-12 11:43:29.493   871  1944 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
08-12 11:43:29.493   871  1944 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
,08-12 11:43:29.493   871  1944 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
08-12 11:43:29.494   871  1944 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
,08-12 11:43:29.494   871  1944 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 1000ms
,08-12 11:43:29.498   871  1400 I ActivityManager: Process android.process.acore (pid 1701) has died
,08-12 11:43:29.499   871  1400 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-12 11:43:29.515   871   884 I ActivityManager: Start proc 4028:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-12 11:43:29.520  3997  4025 I Process : Sending signal. PID: 3997 SIG: 9
,08-12 11:43:29.542   871   871 I ActivityManager: Start proc 4043:com.android.documentsui/u0a45 for broadcast com.android.documentsui/.PackageReceiver

```
