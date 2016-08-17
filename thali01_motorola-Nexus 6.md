#### Test 8135127732cb2b8_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-17 14:23:07.286   872  1303 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-17 14:23:08.146  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 14:23:08.155  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 14:23:08.159  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 14:23:08.188  1479  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-17 14:23:08.189  1479  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-17 14:23:08.189  1479  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 14:23:08.189  1479  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-17 14:23:08.207  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 14:23:08.208  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 14:23:08.208  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-17 14:23:08.644  3756  3756 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-17 14:23:08.648  3756  3756 D AndroidRuntime: CheckJNI is OFF
08-17 14:23:08.685  3756  3756 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-17 14:23:08.728  3756  3756 I Radio-JNI: register_android_hardware_Radio DONE
08-17 14:23:08.749  3756  3756 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 14:23:08.756   872  1990 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 14:23:08.806  2047  2399 W SearchService: Abort, client detached.
08-17 14:23:08.811  2047  2047 I HotwordDetector: Closing mic
08-17 14:23:08.812  2047  2324 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@24a6727
08-17 14:23:08.812  2047  2335 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-17 14:23:08.815  3756  3756 D AndroidRuntime: Shutting down VM
08-17 14:23:08.850   872   883 I ActivityManager: Start proc 3765:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-17 14:23:08.876   375  2337 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-17 14:23:08.878   375  2337 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-17 14:23:08.889   375  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-17 14:23:08.890  2047  2334 I MicroRecognitionRnrImpl: Detection finished
08-17 14:23:08.890  2047  2327 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-17 14:23:08.937  3765  3765 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-17 14:23:08.966  3765  3765 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-17 14:23:08.979  3765  3765 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 5071-5080)
08-17 14:23:08.979  3765  3765 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 14:23:09.003  3765  3765 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a3a7917}
08-17 14:23:09.004  3765  3765 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 14:23:09.004  3765  3765 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 14:23:09.010  3765  3765 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-17 14:23:09.011  3765  3765 E SysUtils: ApplicationContext is null in ApplicationStatus
08-17 14:23:09.032  3765  3765 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-17 14:23:09.043  3765  3765 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 14:23:09.043  3765  3765 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-17 14:23:09.043  3765  3765 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 14:23:09.043  3765  3765 I Adreno  : Build Date                       : 10/20/15
08-17 14:23:09.043  3765  3765 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 14:23:09.043  3765  3765 I Adreno  : Local Branch                     : M14
08-17 14:23:09.043  3765  3765 I Adreno  : Remote Branch                    : 
08-17 14:23:09.043  3765  3765 I Adreno  : Remote Branch                    : 
08-17 14:23:09.043  3765  3765 I Adreno  : Reconstruct Branch               : 
,08-17 14:23:09.106   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e085140:true
,08-17 14:23:09.155  3765  3765 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 14:23:09.166  3765  3765 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-17 14:23:09.228  3765  3803 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-17 14:23:09.238  3765  3790 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-17 14:23:09.270  3765  3803 I OpenGLRenderer: Initialized EGL, version 1.4
,08-17 14:23:09.330  1877  1877 I Keyboard.Facilitator: onFinishInput()
,08-17 14:23:09.331   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +514ms
,08-17 14:23:09.418  3765  3765 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3765
,08-17 14:23:09.585  3765  3765 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 14:23:09.653   872  1670 I ActivityManager: Killing 2966:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-17 14:23:09.695   872  1670 I ActivityManager: Killing 3126:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-17 14:23:09.715  3765  3805 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1698498256
,08-17 14:23:09.721  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 14:23:09.721  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 14:23:09.721  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 14:23:09.721  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 14:23:09.721  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 14:23:09.721  3765  3805 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bf6f13a added. We now have 1 listener(s)
,08-17 14:23:09.724  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-17 14:23:09.725  3765  3805 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:23:09.726  3765  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:23:09.726  3765  3805 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-17 14:23:09.732  3765  3805 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d2e706 added. We now have 1 listener(s)
08-17 14:23:09.732  3765  3805 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:09.735   872  1304 D WifiService: New client listening to asynchronous messages
08-17 14:23:09.736  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:23:09.736  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 14:23:09.736  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-17 14:23:09.736  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 14:23:09.736  3765  3805 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-17 14:23:09.754  3765  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:09.754  3765  3805 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-17 14:23:09.759  3765  3805 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage,
08-17 14:23:09.759  3765  3805 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-17 14:23:09.759  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:09.759  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:09.759  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:09.759  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:09.759  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:09.759  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:09.759  3765  3805 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:09.759  3765  3805 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 14:23:09.759  3765  3805 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:09.759  3765  3805 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 14:23:09.924  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:09.928  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:09.931  3765  3765 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 14:23:10.290  3765  3775 I art     : Background sticky concurrent mark sweep GC freed 73175(6MB) AllocSpace objects, 17(1116KB) LOS objects, 28% free, 23MB/32MB, paused 639us total 135.712ms
,08-17 14:23:10.819  3009  3817 V KeepSync: Connecting to GoogleApiClient
08-17 14:23:10.820   872  1993 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-17 14:23:10.914  1479  1493 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-17 14:23:10.914  1479  1493 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-17 14:23:10.914  1479  1493 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:23:10.915  1479  1493 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:23:10.939  1677  3818 V BaseAuthAsyncOperation: access token request failed
,08-17 14:23:10.941  3009  3817 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-17 14:23:11.014  1479  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-17 14:23:11.014  1479  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-17 14:23:11.014  1479  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:23:11.014  1479  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:23:11.030  3009  3817 E KeepSync: IOException
08-17 14:23:11.030  3009  3817 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-17 14:23:11.030  3009  3817 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-17 14:23:11.030  3009  3817 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-17 14:23:11.030  3009  3817 E KeepSync: 	... 10 more
,08-17 14:23:11.031  3009  3817 W KeepSync: Sync result 2
,08-17 14:23:11.035   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126722, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 14:23:11.182  3765  3816 W jxcore-log: Initializing JXcore engine
08-17 14:23:11.182  3765  3816 W jxcore-log: JXcore engine is ready
,08-17 14:23:11.216  3816  3816 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8949 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-17 14:23:11.216  3816  3816 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10564]" dev="sockfs" ino=10564 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-17 14:23:11.216  3816  3816 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-17 14:23:11.231  3765  3816 W jxcore-log: Starting JXcore engine
08-17 14:23:11.216  3816  3816 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25153]" dev="sockfs" ino=25153 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-17 14:23:11.320  3765  3816 W jxcore-log: Platform android
08-17 14:23:11.320  3765  3816 W jxcore-log: 
,08-17 14:23:11.321  3765  3816 W jxcore-log: Process ARCH arm
08-17 14:23:11.321  3765  3816 W jxcore-log: 
,08-17 14:23:11.581  3765  3816 I jxcore-log: JXcore Cordova bridge is ready!
08-17 14:23:11.581  3765  3816 I jxcore-log: 
,08-17 14:23:11.581  3765  3816 W jxcore-log: JXcore engine is started
,08-17 14:23:11.600  3765  3805 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-17 14:23:11.608  3765  3765 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-17 14:23:17.403   872  2085 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-17 14:23:27.725  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 14:23:27.725  3765  3816 I jxcore-log: 
,08-17 14:23:27.728  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 14:23:27.728  3765  3816 I jxcore-log: 
,08-17 14:23:27.741  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:27.741  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:27.741  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:27.741  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:27.741  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:27.741  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:27.741  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:27.741  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:27.748  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:27.751  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 14:23:27.751  3765  3816 I jxcore-log: 
,08-17 14:23:27.753  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 14:23:27.753  3765  3816 I jxcore-log: 
,08-17 14:23:28.107  3765  3816 D ExecuteNativeTests: Running unit tests
,08-17 14:23:28.166  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:28.166  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 added. We now have 2 listener(s)
,08-17 14:23:28.168  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:23:28.168  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:28.168  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:28.168  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:28.169  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd added. We now have 2 listener(s)
08-17 14:23:28.169  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:28.170  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:23:28.174  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:28.187  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:28.187  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:28.187  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:28.187  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:28.187  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:28.187  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:28.187  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:28.187  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:28.193  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:28.194  3765  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:28.201  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 14:23:28.201  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:28.205  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 14:23:28.206  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-17 14:23:28.208  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:28.212  3765  3816 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-17 14:23:28.213  3765  3816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-17 14:23:28.214  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-17 14:23:28.214  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:23:28.214  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-17 14:23:28.216  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:28.217  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-17 14:23:28.217  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:23:28.218  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.218  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:28.219  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:28.219  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 14:23:28.219  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 removed from the list
08-17 14:23:28.220  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.220  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd removed from the list
,08-17 14:23:28.220  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.220  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:28.222  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.222  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:28.225  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:28.225  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.225  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:28.226  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
,08-17 14:23:28.228  3765  3816 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-17 14:23:28.228  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:28.228  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.228  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.229  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:23:28.229  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:28.229  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.229  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.229  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.229  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
,08-17 14:23:28.229  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.229  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.229  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:28.229  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.230  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.231  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.231  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-17 14:23:28.231  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.231  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
,08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210],
08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-17 14:23:28.237  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 14:23:28.238  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 14:23:28.239  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 14:23:28.239  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 14:23:28.239  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 14:23:28.239  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-17 14:23:28.239  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 14:23:28.239  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.239  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.239  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:23:28.239  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.239  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.239  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.240  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.240  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.240  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
,08-17 14:23:28.240  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.240  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.240  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.240  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.240  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:28.242  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.242  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.242  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.242  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.243  3765  3816 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 14:23:28.245  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:28.257  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:28.257  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:28.257  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:28.257  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:28.257  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:28.257  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:28.257  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:28.257  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:28.260  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:28.261  3765  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:28.261  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:28.261  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:23:28.261  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:23:28.261  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:28.261  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:23:28.270  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:28.271  3765  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 14:23:28.271  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 14:23:28.272  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:28.280  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:28.282  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 14:23:28.283  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:28.286  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-17 14:23:28.289  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-17 14:23:28.289  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 14:23:28.290  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:23:28.290  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 14:23:28.291  3765  3816 D BluetoothAdapter: STATE_ON
,08-17 14:23:28.297  2656  2668 D BtGatt.GattService: registerClient() - UUID=a532e2d3-37de-4745-805b-97e598fe6da1
,08-17 14:23:28.297  2656  2674 D BtGatt.GattService: onClientRegistered() - UUID=a532e2d3-37de-4745-805b-97e598fe6da1, clientIf=5
,08-17 14:23:28.298  3765  3777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 14:23:28.299  2656  2666 D BtGatt.GattService: start scan with filters
,08-17 14:23:28.304  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:23:28.304  2656  2677 D BtGatt.ScanManager: handling starting scan
,08-17 14:23:28.304  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-17 14:23:28.304  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-17 14:23:28.304  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:28.306  2656  2677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:28.308  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:28.308  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 14:23:28.308  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:23:28.310  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:28.314  3765  3816 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 14:23:28.320  2656  2674 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 14:23:28.321  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.322  2656  2677 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 14:23:28.322  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.322  3765  3816 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 14:23:28.323  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.323  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 14:23:28.323  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.323  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:28.323  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:23:28.323  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 14:23:28.323  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:28.323  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:23:28.324  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:23:28.324  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 14:23:28.325  3765  3816 D BluetoothAdapter: STATE_ON
,08-17 14:23:28.327  2656  2666 D BtGatt.GattService: stopScan() - queue size =1
,08-17 14:23:28.328  2656  2668 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 14:23:28.328  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 14:23:28.328  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 14:23:28.328  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:23:28.328  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:23:28.328  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 14:23:28.329  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:28.330  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 14:23:28.330  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:23:28.330  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:23:28.331  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:28.331  2656  2674 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 14:23:28.331  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:28.332  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.332  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:28.332  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:28.332  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.332  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.332  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.332  2656  2677 D BtGatt.ScanManager: Starting BLE batch scan,
08-17 14:23:28.332  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:23:28.332  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.332  2656  2677 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 14:23:28.333  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:23:28.333  3765  3816 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-17 14:23:28.333  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:28.334  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:28.335  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:28.340  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:28.340  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:28.340  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:28.340  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:28.340  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:28.340  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:28.340  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:28.340  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:28.342  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:28.342  3765  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:23:28.342  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:23:28.342  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:23:28.342  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 14:23:28.342  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:28.342  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:23:28.343  2656  2674 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 14:23:28.344  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:28.346  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:28.347  3765  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 14:23:28.347  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:28.348  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:28.350  2656  2674 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 14:23:28.351  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.352  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:28.352  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 14:23:28.352  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:28.356  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 14:23:28.356  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:23:28.356  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 14:23:28.356  3765  3816 D BluetoothAdapter: STATE_ON
08-17 14:23:28.358  2656  2674 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 14:23:28.358  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:28.359  2656  2677 D BtGatt.ScanManager: stopping BLe Batch
08-17 14:23:28.359  2656  2760 D BtGatt.GattService: registerClient() - UUID=e36c1e33-cf25-4ac9-8824-c17df051b117
,08-17 14:23:28.359  2656  2674 D BtGatt.GattService: onClientRegistered() - UUID=e36c1e33-cf25-4ac9-8824-c17df051b117, clientIf=5
08-17 14:23:28.360  3765  3776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 14:23:28.360  2656  2668 D BtGatt.GattService: start scan with filters
,08-17 14:23:28.364  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:23:28.364  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:23:28.364  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:23:28.364  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:28.366  2656  2674 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 14:23:28.366  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:28.367  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:23:28.367  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 14:23:28.368  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:23:28.369  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:28.369  2656  2677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 14:23:28.372  3765  3816 I io.jxcore.node.ConnectionHelper: start: OK
,08-17 14:23:28.374  2656  2674 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 14:23:28.374  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.375  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:28.375  3765  3816 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 14:23:28.375  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.375  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-17 14:23:28.375  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.375  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:28.375  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:23:28.375  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:23:28.375  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:28.376  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-17 14:23:28.376  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 14:23:28.376  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:23:28.376  3765  3816 D BluetoothAdapter: STATE_ON
08-17 14:23:28.377  2656  2677 D BtGatt.ScanManager: handling starting scan
08-17 14:23:28.377  2656  2668 D BtGatt.GattService: stopScan() - queue size =0
08-17 14:23:28.377  2656  2760 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 14:23:28.378  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:23:28.378  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:23:28.378  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:23:28.378  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-17 14:23:28.378  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 14:23:28.379  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:23:28.379  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 14:23:28.379  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-17 14:23:28.379  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:23:28.380  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:28.382  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:28.382  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:28.382  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.382  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:23:28.382  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:28.382  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:28.382  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
,08-17 14:23:28.382  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.382  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.382  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.383  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.383  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:28.383  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.383  2656  2674 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 14:23:28.383  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:28.384  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.384  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.384  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.384  2656  2677 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 14:23:28.384  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.385  3765  3816 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 14:23:28.386  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:28.390  2656  2674 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 14:23:28.391  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.391  2656  2677 D BtGatt.ScanManager: Starting BLE batch scan
,08-17 14:23:28.391  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:28.391  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:28.391  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:28.391  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:28.391  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:28.391  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:28.391  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:28.391  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:23:28.391  2656  2677 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 14:23:28.394  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:28.394  3765  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:28.394  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:28.394  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-17 14:23:28.395  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 14:23:28.395  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:28.395  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:23:28.398  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:28.401  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:28.401  3765  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 14:23:28.401  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:28.406  2656  2674 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 14:23:28.406  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:28.410  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:28.411  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 14:23:28.411  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:28.414  2656  2674 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 14:23:28.414  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:28.415  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 14:23:28.415  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-17 14:23:28.415  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 14:23:28.416  3765  3816 D BluetoothAdapter: STATE_ON
,08-17 14:23:28.421  2656  2668 D BtGatt.GattService: registerClient() - UUID=c96760a5-7741-446e-abf4-0c72fa3bdf34
,08-17 14:23:28.421  2656  2674 D BtGatt.GattService: onClientRegistered() - UUID=c96760a5-7741-446e-abf4-0c72fa3bdf34, clientIf=5
08-17 14:23:28.422  3765  3777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-17 14:23:28.422  2656  2666 D BtGatt.GattService: start scan with filters
,08-17 14:23:28.425  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-17 14:23:28.425  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:23:28.425  2656  2674 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 14:23:28.426  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.426  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:23:28.426  2656  2677 D BtGatt.ScanManager: stopping BLe Batch
08-17 14:23:28.426  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:28.428  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:28.428  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 14:23:28.429  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:23:28.430  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:28.432  2656  2674 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 14:23:28.432  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.432  2656  2677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 14:23:28.433  3765  3816 I io.jxcore.node.ConnectionHelper: start: OK
08-17 14:23:28.433  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.433  3765  3816 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-17 14:23:28.433  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.433  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 14:23:28.433  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.433  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:28.433  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:23:28.433  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:23:28.433  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:28.434  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:23:28.434  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-17 14:23:28.434  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:23:28.434  3765  3816 D BluetoothAdapter: STATE_ON
08-17 14:23:28.435  2656  2760 D BtGatt.GattService: stopScan() - queue size =0
,08-17 14:23:28.436  2656  2668 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 14:23:28.437  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 14:23:28.437  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:23:28.437  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 14:23:28.437  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:23:28.437  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 14:23:28.438  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:23:28.438  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 14:23:28.438  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:23:28.438  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:23:28.439  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:28.442  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:23:28.442  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:28.443  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:23:28.443  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.443  3765  3816 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 14:23:28.443  2656  2674 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 14:23:28.443  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.443  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.443  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:28.444  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.444  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.444  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:28.444  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
,08-17 14:23:28.444  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.444  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.444  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.444  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.445  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:28.445  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.447  2656  2677 D BtGatt.ScanManager: handling starting scan
08-17 14:23:28.447  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.447  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.447  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.447  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
,08-17 14:23:28.448  3765  3816 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 14:23:28.449  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.449  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:28.450  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.450  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:23:28.450  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.453  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:28.453  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.453  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.453  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.453  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.454  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:28.454  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.454  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.454  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.455  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.455  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.455  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:28.455  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
,08-17 14:23:28.457  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 14:23:28.457  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.457  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.457  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:23:28.457  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.457  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.457  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.457  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.457  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.458  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.458  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.458  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.458  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:28.458  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.458  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.459  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.459  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.459  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.460  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
,08-17 14:23:28.460  3765  3816 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 14:23:28.460  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:28.461  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.461  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.461  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.461  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:28.461  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.461  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.461  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.461  2656  2674 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 14:23:28.461  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.461  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:28.461  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.461  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.461  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.461  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.462  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:28.462  2656  2677 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-17 14:23:28.463  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:28.463  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.463  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.463  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.464  3765  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-17 14:23:28.464  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.464  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.464  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.464  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.464  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.464  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.464  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
,08-17 14:23:28.465  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.465  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.465  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.465  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.465  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.465  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:28.465  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:28.466  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.466  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.466  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.467  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
,08-17 14:23:28.468  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:23:28.470  2656  2674 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 14:23:28.470  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.470  2656  2677 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:23:28.470  2656  2677 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 14:23:28.472  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:23:28.472  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:23:28.472  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:23:28.472  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 14:23:28.473  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 14:23:28.473  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.473  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.473  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.473  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.474  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.474  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.474  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.474  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.474  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.474  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.474  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.475  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.475  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:28.475  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.476  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.476  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.476  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.476  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.477  3765  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:23:28.477  3765  3816 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 14:23:28.477  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 14:23:28.481  3765  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:23:28.481  3765  3816 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 14:23:28.481  2656  2674 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 14:23:28.481  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 14:23:28.481  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 14:23:28.482  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 14:23:28.482  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 14:23:28.482  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 14:23:28.482  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 14:23:28.482  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 14:23:28.482  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 14:23:28.482  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 14:23:28.483  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 14:23:28.483  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 14:23:28.483  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 14:23:28.483  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 14:23:28.483  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 14:23:28.483  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 14:23:28.483  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 14:23:28.483  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 14:23:28.483  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 14:23:28.483  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 14:23:28.484  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 14:23:28.484  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 14:23:28.484  3765  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 14:23:28.485  3765  3816 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:23:28.487  3765  3816 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 14:23:28.487  3765  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:23:28.487  3765  3816 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:23:28.487  3765  3816 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 14:23:28.487  2656  2674 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 14:23:28.487  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.487  3765  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:23:28.487  3765  3816 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 14:23:28.487  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 14:23:28.492  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 14:23:28.492  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 14:23:28.492  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 14:23:28.493  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 14:23:28.493  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 14:23:28.493  3765  3816 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 14:23:28.493  3765  3816 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 14:23:28.493  3765  3816 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 14:23:28.493  3765  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 385)
08-17 14:23:28.494  2656  2674 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 14:23:28.494  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.494  2656  2677 D BtGatt.ScanManager: stopping BLe Batch
08-17 14:23:28.494  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.494  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.494  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.494  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.494  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.494  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.494  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 14:23:28.495  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.495  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.495  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.495  3765  3829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:23:28.495  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.495  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.495  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.495  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.495  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.496  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.496  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.496  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.496  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.497  3765  3816 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 14:23:28.497  3765  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 385
08-17 14:23:28.497  3765  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 385)
08-17 14:23:28.497  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.497  3765  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 385)
08-17 14:23:28.497  2656  2757 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-17 14:23:28.497  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.498  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.498  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.498  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.498  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.498  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.498  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.498  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.498  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.498  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.498  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.498  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.498  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.499  3765  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 385)
08-17 14:23:28.499  3765  3816 I org.thaliproject.p2p.btconn,ectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.499  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.499  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.500  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.501  2656  2674 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 14:23:28.501  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.502  2656  2677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 14:23:28.503  3765  3816 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 14:23:28.504  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.504  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.504  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.504  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.504  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.504  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.504  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.504  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.504  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.504  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.504  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.504  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.504  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.504  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.508  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.508  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.508  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.508  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.508  3765  3816 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 14:23:28.509  3765  3816 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 14:23:28.509  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:23:28.509  3765  3816 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 14:23:28.509  3765  3816 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 14:23:28.509  3765  3816 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 14:23:28.509  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:23:28.509  3765  3816 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 14:23:28.509  3765  3816 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 14:23:28.509  3765  3816 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 14:23:28.509  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:23:28.509  3765  3816 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 14:23:28.509  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.509  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.509  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.510  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.510  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.510  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.510  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.510  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.511  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.511  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.511  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.511  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.511  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.511  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.511  2656  2674 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 14:23:28.511  2656  2674 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:28.513  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.513  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.513  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.513  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.513  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.513  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.514  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.514  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.514  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.514  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.514  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.514  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.514  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.514  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.514  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.514  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.514  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.514  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.514  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.514  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.514  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.515  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.515  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.515  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.515  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.515  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.515  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.515  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.515  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.515  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.515  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.515  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.515  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.516  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.516  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.516  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.516  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.518  3765  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 14:23:28.518  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:28.518  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 14:23:28.519  3765  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 14:23:28.519  3765  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 14:23:28.519  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 14:23:28.519  3765  3765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 14:23:28.519  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 14:23:28.520  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.520  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 14:23:28.520  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 14:23:28.520  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 14:23:28.520  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.520  3765  3816 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 14:23:28.520  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.520  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.520  3765  3765 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 14:23:28.520  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:23:28.520  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:28.520  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:23:28.520  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.521  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.521  3765  3831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:23:28.521  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:23:28.522  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:28.522  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.522  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:28.522  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.522  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:23:28.522  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.522  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.522  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.522  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.522  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.522  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.522  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.522  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.522  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.522  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.522  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.522  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.522  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.523  3765  3831 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 14:23:28.523  3765  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 14:23:28.523  3765  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 14:23:28.523  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.523  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.523  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.523  3765  3765 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 14:23:28.523  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.524  3765  3816 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 14:23:28.525  3765  3816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 14:23:28.525  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 14:23:28.525  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 14:23:28.525  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.525  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.525  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.525  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.525  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.525  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.525  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.525  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.526  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.526  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.526  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.526  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.526  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.526  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.527  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.527  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.527  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.527  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.530  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.530  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.530  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.530  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.530  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.530  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.530  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.530  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.530  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.530  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.530  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.530  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.531  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.531  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.531  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.531  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.531  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.531  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.532  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:28.532  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:28.532  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:28.532  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:28.532  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.533  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.533  3765  3816 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8a7154 not in the list
08-17 14:23:28.533  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.533  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.533  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:28.533  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.533  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.533  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:28.533  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:28.534  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:28.534  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:28.534  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:28.534  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7208fd not in the list
08-17 14:23:28.535  3765  3816 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 14:23:28.535  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:23:28.535  3765  3816 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 14:23:28.535  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 14:23:28.535  3765  3816 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 14:23:28.535  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 14:23:28.537  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 14:23:28.537  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 14:23:28.537  3765  3816 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 14:23:28.538  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 14:23:28.538  3765  3816 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 14:23:28.538  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 14:23:28.538  3765  3816 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 14:23:28.538  3765  3816 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 14:23:28.538  3765  3816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 14:23:28.538  3765  3816 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-17 14:23:28.539  3765  3816 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 14:23:28.539  3765  3816 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 14:23:28.539  3765  3816 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 14:23:28.539  3765  3816 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 14:23:28.540  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:28.540  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@274d997 added. We now have 2 listener(s)
08-17 14:23:28.540  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:28.542  3765  3816 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 14:23:28.542   872  2001 D WifiService: setWifiEnabled: true pid=3765, uid=10000
08-17 14:23:28.542   872  2001 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 14:23:28.543  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:28.543  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7d6d784 added. We now have 3 listener(s)
08-17 14:23:28.543  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:28.548  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:28.548  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c2b6d added. We now have 4 listener(s)
08-17 14:23:28.548  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:28.549  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:28.549  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@227e3a2 added. We now have 5 listener(s)
08-17 14:23:28.549  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:28.551   872  1670 D WifiService: setWifiEnabled: false pid=3765, uid=10000
08-17 14:23:28.551   872  1670 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 14:23:28.557  2656  2670 D BluetoothAdapterState: Current state: ON, message: 23
08-17 14:23:28.557  2656  2670 D BluetoothAdapterProperties: Setting state to 13
08-17 14:23:28.557  2656  2670 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 14:23:28.557  2656  2670 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 14:23:28.559  2656  2670 I BluetoothAdapterState: Entering PendingCommandState
08-17 14:23:28.561  2656  2656 D BluetoothMapService: onReceive
08-17 14:23:28.561  2656  2656 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:28.561  2656  2656 D BluetoothMapService: STATE_TURNING_OFF
08-17 14:23:28.561  2656  2656 D BluetoothMapService: MAP Service closeService in
08-17 14:23:28.561  2656  2656 D BluetoothMapMasInstance0: MAP Service shutdown
08-17 14:23:28.561  2656  2656 D ObexServerSockets0: shutdown(block = true)
08-17 14:23:28.562  2656  2656 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 14:23:28.562  2656  2656 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 14:23:28.562  2656  2779 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 14:23:28.564  2656  2757 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 14:23:28.564  2656  2780 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 14:23:28.566  1439  1439 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 14:23:28.568   872  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 14:23:28.568   872  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-17 14:23:28.568   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 14:23:28.568   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 14:23:28.568  2656  2656 I BtOppRfcommListener: stopping Accept Thread
08-17 14:23:28.568  2656  3420 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:23:28.569  2656  3420 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 14:23:28.569  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:28.569  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:28.569  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:28.569  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:28.569  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:28.569  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:28.569  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:28.569  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:28.569  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:23:28.570  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:28.570  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:28.579   872  2087 D DhcpClient: Clearing IP address
08-17 14:23:28.579   371   870 D CommandListener: Clearing all IP addresses on wlan0
08-17 14:23:28.581   872   885 I ActivityManager: Start proc 3835:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-17 14:23:28.582  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:28.583  2656  2674 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:23:28.583  2656  2670 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-17 14:23:28.583  1479  3487 V NativeCrypto: Read error: ssl=0x9ad97200: I/O error during system call, Connection timed out
08-17 14:23:28.586  2656  2656 D HeadsetService: Received stop request...Stopping profile...
08-17 14:23:28.587  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:28.587   371   870 D CommandListener: Setting iface cfg
,08-17 14:23:28.587  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:28.587  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:28.587  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:28.587  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:28.587  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:28.587  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:28.587  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:28.587  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:28.588   872   872 D BluetoothHeadset: Proxy object disconnected
,08-17 14:23:28.588   872   872 D BluetoothHeadset: Proxy object disconnected
,08-17 14:23:28.588  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:28.588  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:28.588   872   872 D BluetoothHeadset: Proxy object disconnected
,08-17 14:23:28.588  3765  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:23:28.588  1976  2277 D BluetoothHeadset: Proxy object disconnected
,08-17 14:23:28.589  1362  2091 D BluetoothHeadset: Proxy object disconnected
,08-17 14:23:28.589  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-17 14:23:28.590  1479  3487 V NativeCrypto: SSL shutdown failed: ssl=0x9ad97200: I/O error during system call, Broken pipe
,08-17 14:23:28.591  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:28.593   872  1671 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-17 14:23:28.593   872  2082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,08-17 14:23:28.594  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:28.594   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 14:23:28.594   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-17 14:23:28.594   872  1303 D WifiStateMachine: Start Disconnecting Watchdog 1
08-17 14:23:28.595   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 14:23:28.595  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:28.595  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:28.595  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:28.595  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:28.595  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:28.595  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:28.595  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:28.595  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:28.595  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:23:28.596  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:28.596  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:28.596  2656  2656 D A2dpService: Received stop request...Stopping profile...
08-17 14:23:28.597  2656  2763 D A2dpStateMachine: Exit Disconnected: -1
,08-17 14:23:28.599   394   394 E Parcel  : Reading a NULL string not supported here.
,08-17 14:23:28.601   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:23:28.602  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:28.602  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:28.602  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:28.602  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-17 14:23:28.602  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:28.602  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:28.602  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:28.602  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:28.602  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:23:28.604  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:28.604  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:28.604   872   872 D BluetoothA2dp: Proxy object disconnected
08-17 14:23:28.605  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-17 14:23:28.606  2656  2656 D HidService: Received stop request...Stopping profile...
,08-17 14:23:28.606  2656  2656 D HidService: Stopping Bluetooth HidService
,08-17 14:23:28.606   872  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-17 14:23:28.607  1362  1362 D BluetoothInputDevice: Proxy object disconnected
,08-17 14:23:28.607  1362  1362 D HidProfile: Bluetooth service disconnected
08-17 14:23:28.608  2656  2656 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:28.608  2656  2656 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:23:28.608  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 14:23:28.608  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:28.610  2656  2656 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 14:23:28.610  2656  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 14:23:28.610  2656  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:23:28.610  2656  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:23:28.610  2656  2674 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-17 14:23:28.610  2656  2674 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-17 14:23:28.611  2656  2656 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:23:28.612  2656  2656 D HealthService: Received stop request...Stopping profile...
08-17 14:23:28.612   872  2082 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-17 14:23:28.612   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 14:23:28.614  2656  2656 D PanService: Received stop request...Stopping profile...
08-17 14:23:28.618  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:28.618  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:28.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:28.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:28.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:28.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:28.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:28.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:28.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:28.619  2656  2656 D BluetoothMapService: Received stop request...Stopping profile...
,08-17 14:23:28.619  2656  2656 D BluetoothMapService: stop()
08-17 14:23:28.619  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:28.619  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:28.621  2656  2656 D BluetoothMapAppObserver: deinitObservers()
08-17 14:23:28.621  2656  2656 D BluetoothMapAppObserver: removeReceiver()
08-17 14:23:28.622  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:28.622  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:28.622  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:28.622  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:28.622  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:28.622  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:28.622  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:28.622  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:28.622  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:28.622  2656  2656 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:28.622  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-17 14:23:28.622  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:28.622  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:28.623  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:28.623  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:28.624  2656  2656 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:28.624  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-17 14:23:28.624  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 14:23:28.624  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:28.624  2656  2674 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 14:23:28.624  2656  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:23:28.624  2656  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:23:28.624  2656  2717 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:23:28.624  2656  2717 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:23:28.624  2656  2717 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:23:28.624  2656  2717 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-17 14:23:28.625  2656  2656 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 14:23:28.625  2656  2656 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 14:23:28.625  2656  2674 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 14:23:28.625  2656  2656 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:28.626  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-17 14:23:28.626  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:28.626  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:28.626  2656  2656 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 14:23:28.626  2656  2674 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-17 14:23:28.626  2656  2656 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:23:28.626  2656  2656 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:28.626  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-17 14:23:28.626  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:28.626  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:28.627  2656  2656 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 14:23:28.627  2656  2656 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 14:23:28.628  2656  2656 D BluetoothMapService: MAP Service closeService in
08-17 14:23:28.628  2656  2656 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:28.628  2656  2656 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:23:28.628  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:28.628  2656  2656 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:28.628  2656  2670 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 14:23:28.628  2656  2670 D BluetoothAdapterProperties: Setting state to 15
08-17 14:23:28.628  2656  2656 D BluetoothMapService: cleanup()
08-17 14:23:28.628  2656  2656 D BluetoothMapService: MAP Service closeService in
08-17 14:23:28.628  2656  2670 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 14:23:28.629  2656  2670 I BluetoothAdapterState: Entering BleOnState
,08-17 14:23:28.629  1841  2285 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:23:28.631   872  2092 D DhcpClient: Receive thread stopped
08-17 14:23:28.635   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:23:28.635   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:23:28.635   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-17 14:23:28.636  1362  1375 D BluetoothPan: onBluetoothStateChange on: false
08-17 14:23:28.637  1362  1374 D BluetoothMap: onBluetoothStateChange: up=false
08-17 14:23:28.637  1362  2091 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 14:23:28.638  1362  1375 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:23:28.638   872  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 14:23:28.638   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:23:28.638  1976  1989 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:23:28.639  1362  1374 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 14:23:28.639  1362  2091 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:23:28.639   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:23:28.640  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 14:23:28.640  1362  1362 D PanProfile: Bluetooth service disconnected
08-17 14:23:28.640  2656  2670 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-17 14:23:28.640  2656  2670 D BluetoothAdapterProperties: Setting state to 16
08-17 14:23:28.640  2656  2670 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-17 14:23:28.641  2656  2670 D BluetoothAdapterProperties: onBleDisable
08-17 14:23:28.641  2656  2671 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-17 14:23:28.641  2656  2674 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:23:28.642  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:28.643  2656  2717 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 14:23:28.643  2656  2717 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:23:28.641  2656  2670 I BluetoothAdapterState: Entering PendingCommandState
08-17 14:23:28.651  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:28.653  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:28.660  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:28.669   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:23:28.670   872  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-17 14:23:28.670   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:28.671   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:23:28.674  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:28.674  3409  3409 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@28091eb and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-17 14:23:28.675  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:28.682  3835  3835 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-17 14:23:28.693  3835  3835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:23:28.698  1479  1479 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:28.704   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@453d6c7:true
,08-17 14:23:28.710   872  2064 I ActivityManager: Start proc 3855:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-17 14:23:28.723   371   870 E Netd    : netlink response contains error (No such file or directory)
08-17 14:23:28.724   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 14:23:28.735  3835  3835 D LocalBluetoothProfileManager: Adding local MAP profile
,08-17 14:23:28.737  3835  3835 D BluetoothMap: Create BluetoothMap proxy object
,08-17 14:23:28.743  3855  3855 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-17 14:23:28.747  3835  3835 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-17 14:23:28.764  3835  3835 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:28.767   872  2015 I ActivityManager: Killing 3216:com.google.android.gm/u0a78 (adj 15): empty #17
,08-17 14:23:28.845  2656  2674 I bt_hci  : shut_down
,08-17 14:23:28.846  2656  2678 D bt_hwcfg: hw_epilog_process
,08-17 14:23:28.847  2656  2678 I bt_vendor: low_power_mode_cb
,08-17 14:23:28.870  2656  2678 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 14:23:28.870  2656  2678 I bt_vendor: epilog_cb
,08-17 14:23:28.870  2656  2678 I bt_hci  : epilog_finished_callback
,08-17 14:23:28.873  2656  2674 I bt_hci_h4: hal_close
,08-17 14:23:28.873  2656  2674 I bt_userial_vendor: device fd = 51 close
,08-17 14:23:28.952  3855  3855 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:23:28.952  3855  3855 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:23:28.952  3855  3855 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:23:28.952  3855  3855 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:23:28.952  3855  3855 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.k.d(PG:583)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.e.b(PG:170)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:23:28.952  3855  3855 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:23:28.952  3855  3855 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.File.exists(File.java:361)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-17 14:23:28.952  3855  3855 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-17 14:23:28.952  3855  3855 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-17 14:23:29.016   872  1670 I ActivityManager: Start proc 3886:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-17 14:23:29.017   872  1670 I ActivityManager: Killing 3409:com.google.android.music:main/u0a66 (adj 15): empty #17
08-17 14:23:29.023  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:23:29.091  2656  2671 D bt_stack_manager: event_shut_down_stack finished.
,08-17 14:23:29.091  2656  2670 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 14:23:29.093  2656  2656 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:23:29.093  2656  2656 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 14:23:29.093  2656  2656 D BtGatt.GattService: stop()
08-17 14:23:29.093  2656  2656 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 14:23:29.094  2656  2670 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 14:23:29.095  2656  2656 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:23:29.095  2656  2656 V BluetoothAdapterState: isTurningOn()=false
08-17 14:23:29.095  2656  2656 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 14:23:29.095  2656  2656 V BluetoothAdapterState: isBleTurningOff()=true
08-17 14:23:29.095  2656  2670 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-17 14:23:29.095  2656  2670 D BluetoothAdapterProperties: Setting state to 10
,08-17 14:23:29.096  2656  2670 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 14:23:29.096  2656  2670 I BluetoothAdapterState: Entering OffState
,08-17 14:23:29.097   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-17 14:23:29.106  2656  2656 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-17 14:23:29.106  2656  2656 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-17 14:23:29.106  2656  2656 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 14:23:29.108  3855  3882 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-17 14:23:29.109  2656  2671 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 14:23:29.112  3886  3886 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-17 14:23:29.115  2656  2671 D bt_stack_manager: event_clean_up_stack finished.
,08-17 14:23:29.121  2656  2656 I art     : System.exit called, status: 0
08-17 14:23:29.121  2656  2656 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 14:23:29.173  3886  3886 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-17 14:23:29.175   872  2001 I ActivityManager: Process com.android.bluetooth (pid 2656) has died
,08-17 14:23:29.197   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@58b0966:true
08-17 14:23:29.197  3835  3835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:23:29.214   872  1992 I ActivityManager: Start proc 3914:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-17 14:23:29.220  3835  3835 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:29.287  3914  3914 D AdapterServiceConfig: Adding HeadsetService
08-17 14:23:29.287  3914  3914 D AdapterServiceConfig: Adding A2dpService
08-17 14:23:29.288  3914  3914 D AdapterServiceConfig: Adding HidService
08-17 14:23:29.288  3914  3914 D AdapterServiceConfig: Adding HealthService
08-17 14:23:29.288  3914  3914 D AdapterServiceConfig: Adding PanService
08-17 14:23:29.288  3914  3914 D AdapterServiceConfig: Adding GattService
08-17 14:23:29.288  3914  3914 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 14:23:29.292   872  2064 I ActivityManager: Killing 2787:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-17 14:23:29.358  1479  1479 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:29.384  1677  1677 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 14:23:29.389  1677  1677 D SystemUpdateService: onCreate
,08-17 14:23:29.396  1677  1677 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 14:23:29.405  1677  3926 I SystemUpdateService: active receiver: enabled
,08-17 14:23:29.414  1677  3926 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 14:23:29.416  1677  3926 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 14:23:29.416  1677  3926 I SystemUpdateService: now status is 0 (complete)
08-17 14:23:29.416  1677  3926 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 14:23:29.416  1677  3926 I SystemUpdateService: file has been verified
08-17 14:23:29.416  1677  3926 I SystemUpdateService: OTA package size = 12249756
,08-17 14:23:29.421  1677  1677 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 14:23:29.425  1677  3926 I SystemUpdateService: showing system update notification
,08-17 14:23:29.424  1677  2507 I iu.UploadsManager: num queued entries: 0
,08-17 14:23:29.427  1677  2507 I iu.UploadsManager: num updated entries: 0
,08-17 14:23:29.427  1677  2507 I iu.SyncManager: NEXT; no task
,08-17 14:23:29.442  1677  1677 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 14:23:29.443  1677  1677 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 14:23:29.460   872  1990 I ActivityManager: Start proc 3928:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-17 14:23:29.464  1677  1677 D SystemUpdateService: onDestroy
,08-17 14:23:29.528  3928  3928 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-17 14:23:29.531  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:29.541  3928  3928 D SprintDMHelper: simOperator: 
,08-17 14:23:29.541  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 14:23:29.556   872  1982 I ActivityManager: Start proc 3940:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher,
,08-17 14:23:29.558   872  1982 I ActivityManager: Killing 1700:android.process.acore/u0a5 (adj 15): empty #17
,08-17 14:23:29.696   872  1992 I ActivityManager: Start proc 3955:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-17 14:23:29.698  3083  3954 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-17 14:23:29.702   872  1990 I ActivityManager: Killing 3586:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-17 14:23:29.751  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-17 14:23:29.794  3955  3955 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-17 14:23:29.794  3955  3955 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-17 14:23:29.794  3955  3955 I GAv4    :   adb logcat -s GAv4
,08-17 14:23:29.804  3955  3955 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-17 14:23:29.809  3955  3955 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-17 14:23:29.834  3955  3972 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-17 14:23:29.921  3955  3955 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-17 14:23:29.953  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-17 14:23:29.964  3955  3955 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 6059-6065)
,08-17 14:23:29.964  3955  3955 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 14:23:29.973  3955  3955 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {54dcbdb}
,08-17 14:23:29.973  3955  3955 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 14:23:29.973  3955  3955 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 14:23:29.980  3955  3955 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-17 14:23:29.981  3955  3955 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-17 14:23:29.994  3955  3955 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-17 14:23:30.008  3955  3955 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 14:23:30.008  3955  3955 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-17 14:23:30.008  3955  3955 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 14:23:30.008  3955  3955 I Adreno  : Build Date                       : 10/20/15
08-17 14:23:30.008  3955  3955 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 14:23:30.008  3955  3955 I Adreno  : Local Branch                     : M14
08-17 14:23:30.008  3955  3955 I Adreno  : Remote Branch                    : 
08-17 14:23:30.008  3955  3955 I Adreno  : Remote Branch                    : 
08-17 14:23:30.008  3955  3955 I Adreno  : Reconstruct Branch               : 
,08-17 14:23:30.069  3955  3955 I NSApplication: Starting up...
,08-17 14:23:30.079  3955  4001 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-17 14:23:30.111   872  1369 I ActivityManager: Start proc 4006:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-17 14:23:30.112   872  1369 I ActivityManager: Killing 3620:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-17 14:23:30.189  4006  4006 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-17 14:23:30.348   872  2058 I ActivityManager: Killing 3636:com.android.musicfx/u0a18 (adj 15): empty #17
,08-17 14:23:31.591   872  1990 D WifiService: setWifiEnabled: true pid=3765, uid=10000
,08-17 14:23:31.591   872  1990 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:23:31.603   872  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-17 14:23:31.614  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:31.614  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:31.614  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:31.614  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:31.614  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:31.614  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:31.614  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:31.614  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:31.614  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:31.614  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:31.615  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:31.618  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:31.618  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:31.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:31.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:31.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:31.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:31.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:31.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:31.618  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:31.618  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:31.619  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:31.638   872  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-17 14:23:31.639   872  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-17 14:23:31.640   872  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-17 14:23:31.641   872  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 14:23:31.641   872  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-17 14:23:31.641   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-17 14:23:31.641   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 14:23:31.659   872  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.94 rxSuccessRate=7.75 delta 1000 -> 1000
,08-17 14:23:31.660   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 14:23:31.662   371   870 D CommandListener: Setting iface cfg
,08-17 14:23:31.663   872  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-17 14:23:31.664   872  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 14:23:31.667   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-17 14:23:31.667   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:31.669   872  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 14:23:31.669   872  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 14:23:31.680   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 14:23:31.772   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 14:23:31.777  1439  1439 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 14:23:32.190  1439  1439 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 14:23:32.238  1439  1439 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 14:23:32.239  1439  1439 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 14:23:32.241   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 14:23:32.251   872  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 14:23:32.251   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:32.252   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 14:23:32.273   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:32.285   371   870 D CommandListener: Setting iface cfg
,08-17 14:23:32.289   872  1303 D WifiStateMachine: Start Dhcp Watchdog 2
,08-17 14:23:32.299   872  1305 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-17 14:23:32.301   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 14:23:32.321   872  4029 D DhcpClient: Receive thread started
,08-17 14:23:32.404   872  1303 E native  : do suspend false
,08-17 14:23:32.424   872  2087 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 14:23:32.437   872  4029 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172674, domain null
,08-17 14:23:32.438   872  2087 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172674 seconds
,08-17 14:23:32.441   872  2087 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 14:23:32.453   872  4029 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 14:23:32.455   872  2087 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 14:23:32.459   371   870 D CommandListener: Setting iface cfg
,08-17 14:23:32.470   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 14:23:32.473   872  2087 D DhcpClient: Scheduling renewal in 86399s
,08-17 14:23:32.489   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-17 14:23:32.494   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 14:23:32.494   872  1303 D WifiConfigStore: No blacklist allowed without epno enabled
,08-17 14:23:32.496   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 14:23:32.499   872  1305 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 14:23:32.505   872  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 14:23:32.557   872  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 14:23:32.558   872  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-17 14:23:32.559   872  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-17 14:23:32.560   872  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-17 14:23:32.561   872  1305 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-17 14:23:32.570   872  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-17 14:23:32.574   872  1305 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-17 14:23:32.575   872  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-17 14:23:32.576   872  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 14:23:32.576   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 14:23:32.576   872  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-17 14:23:32.576   872  1305 D ConnectivityService:    accepting network in place of null
,08-17 14:23:32.578   872  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 14:23:32.586   872  4028 D NetlinkSocketObserver: NeighborEvent{elapsedMs=148686, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 14:23:32.607   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:23:32.641   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:23:32.648   872  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 14:23:32.648   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:32.657   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:23:32.664   872  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-17 14:23:32.670   872  4027 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:817::200e
,08-17 14:23:32.677  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:32.677  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:32.677  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:32.677  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:32.677  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:32.677  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:32.677  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:32.677  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:32.677  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:32.677  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:32.677  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:32.679  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:32.680  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:32.680  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:32.680  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:32.680  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:32.680  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:32.680  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:32.680  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:32.680  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:23:32.680  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:32.680  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:32.690  1677  1677 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 14:23:32.694  1677  1677 D SystemUpdateService: onCreate
,08-17 14:23:32.697  1677  1677 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 14:23:32.700  1677  4039 I SystemUpdateService: active receiver: enabled
,08-17 14:23:32.712  1677  4039 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 14:23:32.714  1677  4039 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-17 14:23:32.714  1677  4039 I SystemUpdateService: now status is 0 (complete)
,08-17 14:23:32.714  1677  4039 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-17 14:23:32.714  1677  4039 I SystemUpdateService: file has been verified
,08-17 14:23:32.714  1677  4039 I SystemUpdateService: OTA package size = 12249756
08-17 14:23:32.717  1677  4039 I SystemUpdateService: showing system update notification
,08-17 14:23:32.724  1677  1677 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 14:23:32.725  1677  2507 I iu.UploadsManager: num queued entries: 0
,08-17 14:23:32.726  1677  2507 I iu.UploadsManager: num updated entries: 0
08-17 14:23:32.727  1677  2507 I iu.SyncManager: NEXT; no task
,08-17 14:23:32.732  1677  1677 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 14:23:32.733  1677  4044 I MDM     : [172] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-17 14:23:32.733  1677  4044 W BaseAppContext: Using Auth Proxy for data requests.
08-17 14:23:32.734  1677  1677 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-17 14:23:32.734  1677  4044 V GoogleAuthProtoRequest: [172] a.<init>: mAccountName set to: thalitester@gmail.com
,08-17 14:23:32.736  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-17 14:23:32.738  1677  1677 D SystemUpdateService: onDestroy
08-17 14:23:32.741  3928  3928 D SprintDMHelper: simOperator: 
08-17 14:23:32.741  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-17 14:23:32.741  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-17 14:23:32.743  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:23:32.752   872  4027 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 12:23:32 GMT], X-Android-Received-Millis=[1471436612751], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471436612721]}
,08-17 14:23:32.753   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-17 14:23:32.754   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-17 14:23:32.754   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 14:23:32.755   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 14:23:32.791  1479  1491 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 14:23:32.792  1479  1491 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-17 14:23:32.792  1479  1491 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:23:32.793  1479  1491 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:23:32.809  1677  4044 E MDM     : [172] SitrepService.a: Error sending sitrep.
,08-17 14:23:32.860  1479  3157 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-17 14:23:32.860  1479  3157 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-17 14:23:32.860  1479  3157 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 14:23:32.861  1479  3157 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:23:32.875  3083  4049 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 14:23:32.880  2981  4048 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-17 14:23:32.880  2981  4048 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at jdm.a(PG:82)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at jcs.o(PG:406)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at jcn.a(PG:1379)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at jcs.i(PG:143)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at blb.a(PG:3937)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at czp.a(PG:18188)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at czp.a(PG:9081)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at czq.run(PG:1686)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 14:23:32.880  2981  4048 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at jdj.a(PG:4091)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at jdj.a(PG:1125)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at jdm.a(PG:77)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	... 12 more
08-17 14:23:32.880  2981  4048 E HttpOperation: Caused by: faj: BadAuthentication
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at fal.a(PG:38)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	at jdj.a(PG:4089)
08-17 14:23:32.880  2981  4048 E HttpOperation: 	... 14 more
,08-17 14:23:32.912  1479  1493 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-17 14:23:32.912  1479  1493 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-17 14:23:32.912  1479  1493 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:23:32.912  1479  1493 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:23:32.924  2981  4048 E HttpOperation: [getmobileexperiments] Unexpected exception
08-17 14:23:32.924  2981  4048 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at jdm.a(PG:82)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at jcs.o(PG:406)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at jcn.a(PG:1379)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at jcs.i(PG:143)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at hec.a(PG:42)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at hee.a(PG:102)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at czr.a(PG:65)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at kka.a(PG:108)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at czp.a(PG:19176)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at czp.a(PG:9081)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at czq.run(PG:1686)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-17 14:23:32.924  2981  4048 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at jdj.a(PG:4091)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at jdj.a(PG:1125)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at jdm.a(PG:77)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	... 15 more
08-17 14:23:32.924  2981  4048 E HttpOperation: Caused by: faj: BadAuthentication
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at fal.a(PG:38)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	at jdj.a(PG:4089)
08-17 14:23:32.924  2981  4048 E HttpOperation: 	... 17 more
,08-17 14:23:32.924  2981  4048 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-17 14:23:32.924  2981  4048 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at jdm.a(PG:82)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at jcs.o(PG:406)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at jcn.a(PG:1379)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at jcs.i(PG:143)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at hec.a(PG:42)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at hee.a(PG:102)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at czr.a(PG:65)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at kka.a(PG:108)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at czp.a(PG:19176)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at czp.a(PG:9081)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at czq.run(PG:1686)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	,at java.lang.Thread.run(Thread.java:818)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at jdj.a(PG:4091)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at jdj.a(PG:1125)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at jdm.a(PG:77)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	... 15 more
08-17 14:23:32.924  2981  4048 E ExperimentLoader: Caused by: faj: BadAuthentication
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at fal.a(PG:38)
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	at jdj.a(PG:4089),
08-17 14:23:32.924  2981  4048 E ExperimentLoader: 	... 17 more
,08-17 14:23:33.017   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 128076, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 14:23:33.647   872  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 14:23:34.061   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-17 14:23:34.071  1877  1877 I Keyboard.Facilitator: onFinishInput()
,08-17 14:23:34.080   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-17 14:23:34.080   872   892 I Adreno  : Build Date                       : 10/20/15
08-17 14:23:34.080   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-17 14:23:34.080   872   892 I Adreno  : Local Branch                     : M14
08-17 14:23:34.080   872   892 I Adreno  : Remote Branch                    : 
08-17 14:23:34.080   872   892 I Adreno  : Remote Branch                    : 
08-17 14:23:34.080   872   892 I Adreno  : Reconstruct Branch               : 
,08-17 14:23:34.129   282   307 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (187 us)
,08-17 14:23:34.227   872  1992 I ActivityManager: Killing 3442:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-17 14:23:34.597   872  2001 D WifiService: setWifiEnabled: false pid=3765, uid=10000
08-17 14:23:34.598   872  2001 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:23:34.627  1439  1439 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 14:23:34.630   872  1303 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 14:23:34.631   872  1303 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-17 14:23:34.631   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 14:23:34.631   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:34.650   872  2087 D DhcpClient: Clearing IP address
08-17 14:23:34.650   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:23:34.654   371   870 D CommandListener: Setting iface cfg
,08-17 14:23:34.661  1479  4055 V NativeCrypto: Read error: ssl=0x9ac90800: I/O error during system call, Connection timed out
,08-17 14:23:34.664  1479  4055 V NativeCrypto: SSL shutdown failed: ssl=0x9ac90800: I/O error during system call, Broken pipe
,08-17 14:23:34.664   872  4029 D DhcpClient: Receive thread stopped
,08-17 14:23:34.675   394   394 E Parcel  : Reading a NULL string not supported here.
,08-17 14:23:34.675   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 14:23:34.675   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-17 14:23:34.676   872  1303 D WifiStateMachine: Start Disconnecting Watchdog 2
08-17 14:23:34.682   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-17 14:23:34.684   371   870 D CommandListener: Clearing all IP addresses on wlan0
,08-17 14:23:34.688   872  1305 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-17 14:23:34.714  3765  3765 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-17 14:23:34.714  3765  3765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-17 14:23:34.724   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-17 14:23:34.736   872   892 W ProcessCpuTracker: Skipping unknown process pid 4065
08-17 14:23:34.740  3765  3765 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a1fb6a5 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5abe7f0, 16908290=android.view.AbsSavedState$1@5abe7f0}, android:focusedViewId=100}]}]
08-17 14:23:34.740  3765  3765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-17 14:23:34.741  3765  3765 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 14:23:34.741  3765  3765 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-17 14:23:34.743   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
08-17 14:23:34.749   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-17 14:23:34.754   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-17 14:23:34.756   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-17 14:23:34.756   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-17 14:23:34.762   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:23:34.764   872  1305 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-17 14:23:34.764   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 14:23:34.766   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:23:34.776  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:34.777   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
08-17 14:23:34.777  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:34.777  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:34.777  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:34.777  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:34.777  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:34.777  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:34.777  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:34.777  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:34.777  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:34.777  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:34.778  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:34.778  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:34.778  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:34.778  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:34.778  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:34.778  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:34.778  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:34.778  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:34.778  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:34.778  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-17 14:23:34.778  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:34.779  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:34.780  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:34.781  1841  2285 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 14:23:34.781   872  1303 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 14:23:34.785  1677  1677 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-17 14:23:34.791  1677  1677 D SystemUpdateService: onCreate
,08-17 14:23:34.795  1677  1677 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-17 14:23:34.808  1677  1677 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-17 14:23:34.810  1677  2507 I iu.UploadsManager: num queued entries: 0
,08-17 14:23:34.810  1677  2507 I iu.UploadsManager: num updated entries: 0
,08-17 14:23:34.821  1677  1677 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-17 14:23:34.821  1677  1677 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-17 14:23:34.823  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-17 14:23:34.826  3928  3928 D SprintDMHelper: simOperator: 
08-17 14:23:34.826  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-17 14:23:34.831   371   870 E Netd    : netlink response contains error (No such file or directory)
08-17 14:23:34.832   872  1305 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-17 14:23:34.840  1677  4070 I SystemUpdateService: active receiver: enabled
,08-17 14:23:34.842  1677  2507 I iu.SyncManager: NEXT; no task
,08-17 14:23:34.842  3083  4074 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-17 14:23:34.849  1677  4070 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-17 14:23:34.856  1677  4070 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-17 14:23:34.856  1677  4070 I SystemUpdateService: now status is 0 (complete)
08-17 14:23:34.856  1677  4070 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 14:23:34.856  1677  4070 I SystemUpdateService: file has been verified
08-17 14:23:34.856  1677  4070 I SystemUpdateService: OTA package size = 12249756
,08-17 14:23:34.858  3955  3955 I art     : Waiting for a blocking GC DisableMovingGc
,08-17 14:23:34.860  3955  3955 I art     : Starting a blocking GC DisableMovingGc
,08-17 14:23:34.877  1677  4070 I SystemUpdateService: showing system update notification
,08-17 14:23:34.894  1677  1677 D SystemUpdateService: onDestroy
,08-17 14:23:34.981   282   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-17 14:23:34.982   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-17 14:23:34.982   872  1330 D SurfaceControl: Excessive delay in setPowerMode(): 228ms
,08-17 14:23:34.988   872   892 I DreamManagerService: Entering dreamland.
,08-17 14:23:34.988   872   892 I PowerManagerService: Dozing...
08-17 14:23:34.988   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-17 14:23:35.025   375  1311 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-17 14:23:35.025   375  1311 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-17 14:23:35.030   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 14:23:35.033   872  1303 E native  : do suspend false
,08-17 14:23:35.034  1965  4078 D NfcService: Discovery configuration equal, not updating.
,08-17 14:23:35.050   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 14:23:35.053   872  1303 E native  : do suspend true
,08-17 14:23:35.169   375  1312 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-17 14:23:35.169   375  1312 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-17 14:23:37.649  3914  3914 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 14:23:37.649   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@34ccee6:true
,08-17 14:23:37.654  3914  3914 I bt_bluedroid: init
,08-17 14:23:37.655  3914  4082 I BluetoothAdapterState: Entering OffState
,08-17 14:23:37.661  3914  4083 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 14:23:37.661  3914  4083 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 14:23:37.661  3914  4083 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 14:23:37.662  3914  4083 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 14:23:37.663  3914  3914 I bt_bluedroid: get_profile_interface socket
08-17 14:23:37.666  3914  4086 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 14:23:37.668  3914  3914 I bt_bluedroid: get_profile_interface sdp
08-17 14:23:37.668  3914  4086 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 14:23:37.676  3914  3924 I bt_bluedroid: config_hci_snoop_log
,08-17 14:23:37.680   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 14:23:37.687  3914  4082 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 14:23:37.688  3914  4082 D BluetoothAdapterProperties: Setting state to 14
08-17 14:23:37.688  3914  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 14:23:37.693  3914  4082 D BluetoothBondStateMachine: make
,08-17 14:23:37.698  3914  4087 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 14:23:37.706  3914  4082 I BluetoothAdapterState: Entering PendingCommandState
,08-17 14:23:37.706  3914  3914 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!,
,08-17 14:23:37.711  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:37.712  3914  3914 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:23:37.713  3914  3914 D BtGatt.GattService: Received start request. Starting profile...
,08-17 14:23:37.713  3914  3914 D BtGatt.GattService: start()
08-17 14:23:37.713  3914  3914 I bt_bluedroid: get_profile_interface gatt
,08-17 14:23:37.714  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
08-17 14:23:37.715  3914  3914 D BtGatt.AdvertiseManager: advertise manager created
,08-17 14:23:37.723  3914  3914 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:23:37.723  3914  3914 V BluetoothAdapterState: isTurningOn()=false
08-17 14:23:37.723  3914  3914 V BluetoothAdapterState: isBleTurningOn()=true
08-17 14:23:37.723  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:37.724  3914  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-17 14:23:37.725  3914  4082 I bt_bluedroid: enable
08-17 14:23:37.725  3914  4083 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 14:23:37.726  3914  4083 I bt_hci  : start_up
,08-17 14:23:37.747  3914  4083 I bt_vendor: alloc value 0xb39f9189
,08-17 14:23:37.748  3914  4083 I bt_vendor: init
,08-17 14:23:37.748  3914  4083 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-17 14:23:37.748  3914  4083 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 14:23:37.856  3914  4083 D bt_hci  : start_up starting async portion
,08-17 14:23:37.856  3914  4090 I bt_hci  : event_finish_startup
,08-17 14:23:37.856  3914  4090 I bt_hci_h4: hal_open
,08-17 14:23:37.856  3914  4090 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 14:23:37.863  3914  4090 I bt_userial_vendor: device fd = 51 open
,08-17 14:23:37.899  3914  4090 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 14:23:37.931  3914  4090 D bt_hwcfg: Chipset BCM4354A2
08-17 14:23:37.931  3914  4090 D bt_hwcfg: Target name = [BCM4354A2]
08-17 14:23:37.932  3914  4090 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 14:23:38.591  3914  4090 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 14:23:38.592  3914  4090 D bt_hwcfg: Settlement delay -- 100 ms
,08-17 14:23:38.592  3914  4090 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 14:23:38.709  3914  4090 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 14:23:38.710  3914  4090 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 14:23:38.740  3914  4090 I bt_hwcfg: vendor lib fwcfg completed
,08-17 14:23:38.740  3914  4090 I bt_vendor: firmware callback
,08-17 14:23:38.740  3914  4090 I bt_hci  : firmware_config_callback
,08-17 14:23:38.752  3914  4092 I bt_btu  : btu_task pending for preload complete event
,08-17 14:23:38.752  3914  4092 I bt_btu_task: Bluetooth chip preload is complete
08-17 14:23:38.752  3914  4092 I bt_btu  : btu_task received preload complete event
,08-17 14:23:38.762  3914  4092 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 14:23:38.762  3914  4092 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 14:23:38.763  3914  4092 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-17 14:23:38.763  3914  4092 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 14:23:38.763  3914  4092 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 14:23:38.764  3914  4092 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 14:23:38.764  3914  4092 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 14:23:38.764  3914  4092 I         : BTE_InitTraceLevels -- TRC_BTM
,08-17 14:23:38.764  3914  4092 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 14:23:38.765  3914  4092 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 14:23:38.765  3914  4092 I         : BTE_InitTraceLevels -- TRC_SDP
,08-17 14:23:38.765  3914  4092 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 14:23:38.765  3914  4092 I         : BTE_InitTraceLevels -- TRC_SMP
,08-17 14:23:38.766  3914  4092 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 14:23:38.766  3914  4092 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 14:23:38.899  3914  4092 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,08-17 14:23:38.899  3914  4092 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,08-17 14:23:38.910  3914  4086 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 14:23:38.912  3914  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 14:23:38.913  3914  4086 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-17 14:23:38.917  3914  4086 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 14:23:38.920  3914  4086 D BluetoothAdapterProperties: Scan Mode:20
,08-17 14:23:38.920  3914  4086 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-17 14:23:38.922  3914  4086 D bt_hci  : do_postload posting postload work item
,08-17 14:23:38.922  3914  4090 I bt_hci  : event_postload
08-17 14:23:38.922  3914  4090 I bt_vendor: sco_config_cb
08-17 14:23:38.922  3914  4090 I bt_hci  : sco_config_callback postload finished.
08-17 14:23:38.927  3914  4086 D bt_bte_conf: Device ID record 1 : primary
,08-17 14:23:38.927  3914  4086 D bt_bte_conf:   vendorId            = 000f
08-17 14:23:38.927  3914  4086 D bt_bte_conf:   vendorIdSource      = 0001
08-17 14:23:38.927  3914  4086 D bt_bte_conf:   product             = 1200
08-17 14:23:38.927  3914  4086 D bt_bte_conf:   version             = 1436
,08-17 14:23:38.928  3914  4086 D bt_bte_conf:   clientExecutableURL = 
,08-17 14:23:38.927  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:38.928  3914  4086 D bt_bte_conf:   serviceDescription  = 
,08-17 14:23:38.928  3914  4086 D bt_bte_conf:   documentationURL    = 
,08-17 14:23:38.928  3914  4086 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-17 14:23:38.929  3914  4083 D bt_stack_manager: event_start_up_stack finished
,08-17 14:23:38.932  3914  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-17 14:23:38.933  3914  4082 D BluetoothAdapterProperties: Setting state to 15
,08-17 14:23:38.933  3914  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-17 14:23:38.933  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:38.934  3914  4090 I bt_vendor: low_power_mode_cb
08-17 14:23:38.934  3914  4082 I BluetoothAdapterState: Entering BleOnState
,08-17 14:23:38.942  3914  4082 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-17 14:23:38.944  3914  4082 D BluetoothAdapterProperties: Setting state to 11
08-17 14:23:38.945  3914  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-17 14:23:38.953  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:38.955  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:38.958  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:38.959  3914  3914 D HeadsetService: Received start request. Starting profile...
,08-17 14:23:38.962  3914  3914 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 14:23:38.962  3914  3914 D HeadsetStateMachine: make
,08-17 14:23:38.969  3914  4082 I BluetoothAdapterState: Entering PendingCommandState
,08-17 14:23:38.972  3914  3914 D HeadsetStateMachine: max_hf_connections = 1
,08-17 14:23:38.972  3914  3914 I bt_bluedroid: get_profile_interface handsfree
08-17 14:23:38.972  3914  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 14:23:38.972  3914  4086 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-17 14:23:38.977  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:38.977  3914  3914 D A2dpService: Received start request. Starting profile...
,08-17 14:23:38.978  3914  3914 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 14:23:38.978  3914  3914 I bt_bluedroid: get_profile_interface avrcp
,08-17 14:23:38.984  3914  3914 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 14:23:38.984  3914  3914 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:23:38.984  3914  3914 D A2dpStateMachine: make
,08-17 14:23:38.986  3914  3914 I bt_bluedroid: get_profile_interface a2dp
,08-17 14:23:38.986  3914  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 14:23:38.988  3914  4101 D A2dpStateMachine: Enter Disconnected: -2
,08-17 14:23:38.990  1479  1479 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:38.990  3914  3914 I BluetoothHidServiceJni: classInitNative: succeeds
08-17 14:23:38.991  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:38.992  3914  3914 D HidService: Received start request. Starting profile...
,08-17 14:23:38.993  3914  3914 I bt_bluedroid: get_profile_interface hidhost
08-17 14:23:38.993  3835  3835 D BluetoothInputDevice: Proxy object connected
08-17 14:23:38.993  3914  4086 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
08-17 14:23:38.993  3914  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-17 14:23:38.993  3914  3914 D HidService: setHidService(): set to: null
08-17 14:23:38.993  3835  3835 D HidProfile: Bluetooth service connected
08-17 14:23:38.994  3914  3914 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:23:38.995  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
08-17 14:23:38.995  3914  3914 D HealthService: Received start request. Starting profile...
,08-17 14:23:38.996  3914  3914 I bt_bluedroid: get_profile_interface health
,08-17 14:23:38.997  3914  3914 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 14:23:38.998  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:38.999  3914  3914 D PanService: Received start request. Starting profile...
08-17 14:23:38.999  3914  3914 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 14:23:38.999  3914  3914 I bt_bluedroid: get_profile_interface pan
08-17 14:23:38.999  3835  3835 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:23:38.999  3914  4086 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 14:23:39.000  3835  3835 D PanProfile: Bluetooth service connected
,08-17 14:23:39.002  3914  3914 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:39.003  3914  3914 D BluetoothMapService: Received start request. Starting profile...
,08-17 14:23:39.003  3914  3914 D BluetoothMapService: start()
08-17 14:23:39.003  3835  3835 D BluetoothMap: Proxy object connected
08-17 14:23:39.003  3835  3835 D MapProfile: Bluetooth service connected
08-17 14:23:39.003  3835  3835 D BluetoothMap: getConnectedDevices()
08-17 14:23:39.004  3835  3835 D BluetoothMap: Bluetooth is Not enabled
08-17 14:23:39.005  3914  3914 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 14:23:39.005  3914  3914 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-17 14:23:39.005  3914  3914 D BluetoothMapAppObserver: createReceiver()
,08-17 14:23:39.006  3914  3914 D BluetoothMapAppObserver: initObservers()
08-17 14:23:39.006  3914  3914 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 14:23:39.014  3914  4099 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 14:23:39.014  3914  3914 V BluetoothAdapterState: isTurningOff()=false
08-17 14:23:39.014  3914  3914 V BluetoothAdapterState: isTurningOn()=true
08-17 14:23:39.014  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:39.014  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:23:39.016  3914  3914 V BluetoothAdapterState: isTurningOff()=false
08-17 14:23:39.016  3914  3914 V BluetoothAdapterState: isTurningOn()=true
,08-17 14:23:39.016  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:39.016  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:23:39.018  3914  3914 V BluetoothAdapterState: isTurningOff()=false
08-17 14:23:39.018  3914  3914 V BluetoothAdapterState: isTurningOn()=true
08-17 14:23:39.018  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:39.018  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:39.018  3914  3914 V BluetoothAdapterState: isTurningOff()=false
08-17 14:23:39.018  3914  3914 V BluetoothAdapterState: isTurningOn()=true
08-17 14:23:39.018  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:39.018  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:39.018  3914  3914 V BluetoothAdapterState: isTurningOff()=false
08-17 14:23:39.018  3914  3914 V BluetoothAdapterState: isTurningOn()=true
08-17 14:23:39.019  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:39.019  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:39.019  3914  3914 V BluetoothAdapterState: isTurningOff()=false
08-17 14:23:39.019  3914  3914 V BluetoothAdapterState: isTurningOn()=true
08-17 14:23:39.019  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 14:23:39.019  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:39.019  3914  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 14:23:39.019  3914  4082 D BluetoothAdapterProperties: ScanMode =  20
08-17 14:23:39.019  3914  4082 D BluetoothAdapterProperties: State =  11
,08-17 14:23:39.022  3914  4086 D BluetoothAdapterProperties: Scan Mode:21
,08-17 14:23:39.022  3914  4082 D BluetoothAdapterProperties: Setting state to 12
,08-17 14:23:39.022  3914  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 14:23:39.022  3914  4086 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:23:39.022  3914  4082 I BluetoothAdapterState: Entering OnState
,08-17 14:23:39.022  3835  3846 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 14:23:39.024   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:23:39.024  3835  3849 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 14:23:39.024   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:23:39.025  1362  2091 D BluetoothPan: onBluetoothStateChange on: true
,08-17 14:23:39.025  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:39.025  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:39.025  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:39.025  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:39.025  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:39.025  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:39.025  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:39.025  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:39.025   872   872 D BluetoothA2dp: Proxy object connected
,08-17 14:23:39.026  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:23:39.026  1362  1362 D PanProfile: Bluetooth service connected
08-17 14:23:39.027  1362  1375 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 14:23:39.027  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:39.028  1362  1362 D BluetoothMap: Proxy object connected
08-17 14:23:39.028  1362  1362 D MapProfile: Bluetooth service connected
08-17 14:23:39.028  1362  1362 D BluetoothMap: getConnectedDevices(),
,08-17 14:23:39.028  3835  3846 D BluetoothMap: onBluetoothStateChange: up=true
08-17 14:23:39.029  1362  2091 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 14:23:39.030  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:39.030  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:39.030  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:39.030  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:39.030  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:39.030  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:39.030  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:39.030  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 14:23:39.030  1362  1362 D BluetoothInputDevice: Proxy object connected
08-17 14:23:39.030  1362  1362 D HidProfile: Bluetooth service connected
,08-17 14:23:39.030  3835  3849 D BluetoothPan: onBluetoothStateChange on: true
08-17 14:23:39.031  1362  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:23:39.032  1362  1362 D BluetoothA2dp: Proxy object connected
08-17 14:23:39.032   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:23:39.032  1976  2277 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:23:39.032  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:39.032  1362  2091 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 14:23:39.033  3914  3914 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 14:23:39.034  1362  1375 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:23:39.034  3914  3914 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 14:23:39.034   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:23:39.035   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 14:23:39.038  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:39.038  3914  3914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:23:39.039  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:39.040  3835  3835 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-17 14:23:39.041  3914  3914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:39.042  3914  3914 D ObexServerSockets: Succeed to create listening sockets 
08-17 14:23:39.042  3914  3914 D ObexServerSockets0: startAccept()
,08-17 14:23:39.042  3914  3914 D ObexServerSockets0: prepareForNewConnect()
,08-17 14:23:39.043  3835  3835 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-17 14:23:39.044  3914  3914 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-17 14:23:39.044  3914  3914 D BluetoothSdpJni: SDP Create record success - handle: 0
08-17 14:23:39.044  3914  3914 D BluetoothMapService: onReceive
08-17 14:23:39.044  3914  3914 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:39.044  3914  3914 D BluetoothMapService: STATE_ON
08-17 14:23:39.045  3914  4108 D ObexServerSockets0: Accepting socket connection...
,08-17 14:23:39.045  3914  4107 D ObexServerSockets0: Accepting socket connection...
,08-17 14:23:39.049  3835  3835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:23:39.053  3835  3835 D BluetoothA2dp: Proxy object connected
,08-17 14:23:39.056  1479  1479 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:39.059  3835  3835 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:39.063  1362  1362 D BluetoothPbap: Proxy object connected
,08-17 14:23:39.063  3835  3835 D BluetoothPbap: Proxy object connected
08-17 14:23:39.063  1362  1362 D PbapServerProfile: Bluetooth service connected
08-17 14:23:39.063  3835  3835 D PbapServerProfile: Bluetooth service connected
,08-17 14:23:39.068  3914  3914 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 14:23:39.068  3914  3914 D ObexServerSockets0: prepareForNewConnect()
08-17 14:23:39.070  3914  4112 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:39.100  3914  4116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:39.101  3914  4116 I BtOppRfcommListener: Accept thread started.
,08-17 14:23:39.126   872   872 D BluetoothHeadset: Proxy object connected
08-17 14:23:39.126   872   872 D BluetoothHeadset: Proxy object connected
,08-17 14:23:39.126   872   872 D BluetoothHeadset: Proxy object connected
08-17 14:23:39.127  1976  1988 D BluetoothHeadset: Proxy object connected
08-17 14:23:39.127  1362  2091 D BluetoothHeadset: Proxy object connected
08-17 14:23:39.127  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-17 14:23:39.132   872   889 D BluetoothHeadset: Proxy object connected
,08-17 14:23:39.132  1976  2081 D BluetoothHeadset: Proxy object connected
,08-17 14:23:39.135  1362  1375 D BluetoothHeadset: Proxy object connected
,08-17 14:23:39.135  1362  1362 D HeadsetProfile: Bluetooth service connected
,08-17 14:23:39.135   872   889 D BluetoothHeadset: Proxy object connected
,08-17 14:23:39.147  3835  3846 D BluetoothHeadset: Proxy object connected
,08-17 14:23:39.148  3835  3835 D HeadsetProfile: Bluetooth service connected
,08-17 14:23:39.252  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:23:39.266  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:23:39.272  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:23:39.338  1479  1491 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-17 14:23:39.338  1479  1491 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-17 14:23:39.338  1479  1491 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:23:39.339  1479  1491 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:23:39.366  3506  3506 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-17 14:23:39.366  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-17 14:23:39.366  3506  3506 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-17 14:23:40.581   872  1305 D ConnectivityService: handlePromptUnvalidated 101
,08-17 14:23:40.614  3914  4082 D BluetoothAdapterState: Current state: ON, message: 23
,08-17 14:23:40.615  3914  4082 D BluetoothAdapterProperties: Setting state to 13
,08-17 14:23:40.615  3914  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-17 14:23:40.617  3914  4082 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 14:23:40.621  3914  4082 I BluetoothAdapterState: Entering PendingCommandState
08-17 14:23:40.631  3914  3914 D BluetoothMapService: onReceive
08-17 14:23:40.631  3914  3914 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 14:23:40.632  3914  3914 D BluetoothMapService: STATE_TURNING_OFF
08-17 14:23:40.633  3914  3914 D BluetoothMapService: MAP Service closeService in
08-17 14:23:40.633  3914  3914 D BluetoothMapMasInstance0: MAP Service shutdown
08-17 14:23:40.634  3914  3914 D ObexServerSockets0: shutdown(block = true)
08-17 14:23:40.634  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:40.634  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:40.634  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:40.634  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:40.634  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:40.634  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:40.634  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:40.634  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:40.634  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:40.634  3914  4107 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-17 14:23:40.637  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:40.637  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:40.643  3914  3914 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 14:23:40.643  3914  4108 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-17 14:23:40.643  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:40.643  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:40.643  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:40.643  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:40.643  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:40.643  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 14:23:40.643  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:40.643  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:40.643  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:40.643  3914  4095 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-17 14:23:40.644  3914  3914 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-17 14:23:40.644  3914  3914 I BtOppRfcommListener: stopping Accept Thread
08-17 14:23:40.644  3765  3765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 14:23:40.644  3914  4086 D BluetoothAdapterProperties: Scan Mode:20
,08-17 14:23:40.644  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:40.644  3914  4116 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 14:23:40.645  3914  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-17 14:23:40.646  3914  4116 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 14:23:40.646  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:40.648  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:40.648  3914  3914 D HeadsetService: Received stop request...Stopping profile...
,08-17 14:23:40.650  3835  3835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 14:23:40.651   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 14:23:40.651   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 14:23:40.651   872   872 D BluetoothHeadset: Proxy object disconnected
08-17 14:23:40.652  1976  1989 D BluetoothHeadset: Proxy object disconnected
08-17 14:23:40.653  1362  2091 D BluetoothHeadset: Proxy object disconnected
,08-17 14:23:40.654  3835  3849 D BluetoothHeadset: Proxy object disconnected
,08-17 14:23:40.655  1362  1362 D HeadsetProfile: Bluetooth service disconnected
,08-17 14:23:40.658  3914  3914 D A2dpService: Received stop request...Stopping profile...
,08-17 14:23:40.659  3914  4101 D A2dpStateMachine: Exit Disconnected: -1
,08-17 14:23:40.661  3835  3835 D HeadsetProfile: Bluetooth service disconnected
,08-17 14:23:40.661   872   872 D BluetoothA2dp: Proxy object disconnected
08-17 14:23:40.662  1362  1362 D BluetoothA2dp: Proxy object disconnected
08-17 14:23:40.662  3914  3914 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:40.662  3914  3914 V BluetoothAdapterState: isTurningOn()=false
08-17 14:23:40.662  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:40.662  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:23:40.663  3914  3914 D HidService: Received stop request...Stopping profile...
08-17 14:23:40.663  3914  3914 D HidService: Stopping Bluetooth HidService
08-17 14:23:40.664  1362  1362 D BluetoothInputDevice: Proxy object disconnected
,08-17 14:23:40.664  1362  1362 D HidProfile: Bluetooth service disconnected
,08-17 14:23:40.666  3914  3914 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-17 14:23:40.666  3914  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:23:40.666  3914  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:23:40.666  3914  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-17 14:23:40.666  3914  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-17 14:23:40.666  3914  4086 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-17 14:23:40.666  3914  3914 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 14:23:40.667  3914  3914 D HealthService: Received stop request...Stopping profile...
,08-17 14:23:40.670  3914  3914 D PanService: Received stop request...Stopping profile...
,08-17 14:23:40.670  3835  3835 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:40.671  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 14:23:40.671  1362  1362 D PanProfile: Bluetooth service disconnected
,08-17 14:23:40.673  3835  3835 D BluetoothA2dp: Proxy object disconnected
,08-17 14:23:40.673  3835  3835 D BluetoothInputDevice: Proxy object disconnected
08-17 14:23:40.673  3835  3835 D HidProfile: Bluetooth service disconnected
08-17 14:23:40.673  3914  3914 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:40.673  3914  3914 V BluetoothAdapterState: isTurningOn()=false
08-17 14:23:40.673  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:40.674  1479  1479 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:40.674  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:40.674  3914  3914 D BluetoothMapService: Received stop request...Stopping profile...
08-17 14:23:40.674  3914  3914 D BluetoothMapService: stop()
08-17 14:23:40.676  3914  3914 D BluetoothMapAppObserver: deinitObservers()
08-17 14:23:40.676  3835  3835 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 14:23:40.676  3835  3835 D PanProfile: Bluetooth service disconnected
08-17 14:23:40.676  3914  3914 D BluetoothMapAppObserver: removeReceiver()
08-17 14:23:40.678  3835  3835 D BluetoothMap: Proxy object disconnected
08-17 14:23:40.678  3835  3835 D MapProfile: Bluetooth service disconnected
08-17 14:23:40.678  1362  1362 D BluetoothMap: Proxy object disconnected
08-17 14:23:40.678  1362  1362 D MapProfile: Bluetooth service disconnected
08-17 14:23:40.679  3914  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:23:40.679  3914  3914 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:40.679  3914  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:23:40.679  3914  3914 V BluetoothAdapterState: isTurningOn()=false
08-17 14:23:40.680  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:40.680  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:40.680  3914  4092 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:23:40.680  3914  4092 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:23:40.680  3914  4092 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 14:23:40.680  3914  4092 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 14:23:40.680  3914  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-17 14:23:40.680  3914  3914 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 14:23:40.680  3914  3914 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 14:23:40.680  3914  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-17 14:23:40.680  3914  3914 V BluetoothAdapterState: isTurningOff()=true
,08-17 14:23:40.680  3914  3914 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:23:40.681  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:40.681  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:40.681  3914  3914 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 14:23:40.681  3914  4086 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-17 14:23:40.681  3914  3914 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 14:23:40.682  3914  3914 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:40.682  3914  3914 V BluetoothAdapterState: isTurningOn()=false
08-17 14:23:40.682  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:40.682  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:40.682  3914  3914 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-17 14:23:40.682  3914  3914 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 14:23:40.684  3835  3835 D BluetoothPbap: Proxy object disconnected
08-17 14:23:40.684  3835  3835 D PbapServerProfile: Bluetooth service disconnected
08-17 14:23:40.685  1362  1362 D BluetoothPbap: Proxy object disconnected
08-17 14:23:40.685  1362  1362 D PbapServerProfile: Bluetooth service disconnected
08-17 14:23:40.687  3914  3914 D BluetoothMapService: MAP Service closeService in
08-17 14:23:40.687  3914  3914 V BluetoothAdapterState: isTurningOff()=true
08-17 14:23:40.687  3914  3914 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:23:40.687  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:40.687  3914  3914 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:40.687  3914  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-17 14:23:40.687  3914  4082 D BluetoothAdapterProperties: Setting state to 15
08-17 14:23:40.687  3914  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-17 14:23:40.688  3914  3914 D BluetoothMapService: cleanup()
08-17 14:23:40.688  3914  3914 D BluetoothMapService: MAP Service closeService in
,08-17 14:23:40.688  3914  4082 I BluetoothAdapterState: Entering BleOnState
08-17 14:23:40.690  3835  3846 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 14:23:40.690   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:23:40.690  3835  3849 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 14:23:40.691   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:23:40.691  1362  1374 D BluetoothPan: onBluetoothStateChange on: false
08-17 14:23:40.692  3835  3846 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:23:40.692  3835  3846 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 14:23:40.693  1362  2091 D BluetoothMap: onBluetoothStateChange: up=false
,08-17 14:23:40.693  3835  3849 D BluetoothMap: onBluetoothStateChange: up=false
08-17 14:23:40.695  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-17 14:23:40.696  3835  3846 D BluetoothPan: onBluetoothStateChange on: false
08-17 14:23:40.696  1362  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 14:23:40.696   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 14:23:40.697  1976  2277 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:23:40.697  1362  2091 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 14:23:40.697  1362  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 14:23:40.698   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 14:23:40.698  3914  4082 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-17 14:23:40.698  3914  4082 D BluetoothAdapterProperties: Setting state to 16
,08-17 14:23:40.698  3914  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-17 14:23:40.699  3914  4082 D BluetoothAdapterProperties: onBleDisable
,08-17 14:23:40.700  3914  4082 I BluetoothAdapterState: Entering PendingCommandState
,08-17 14:23:40.700  3914  4083 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-17 14:23:40.702  3914  4092 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-17 14:23:40.702  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:40.702  3914  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-17 14:23:40.703  3914  4086 D BluetoothAdapterProperties: Scan Mode:20
08-17 14:23:40.704  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:40.704  3835  3835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-17 14:23:40.705  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:40.707  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:40.712  1479  1479 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:40.714  3835  3835 D DockEventReceiver: finishStartingService: stopping service,
,08-17 14:23:40.902  3914  4086 I bt_hci  : shut_down
,08-17 14:23:40.903  3914  4090 D bt_hwcfg: hw_epilog_process
08-17 14:23:40.904  3914  4090 I bt_vendor: low_power_mode_cb
,08-17 14:23:40.933  3914  4090 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-17 14:23:40.933  3914  4090 I bt_vendor: epilog_cb
08-17 14:23:40.933  3914  4090 I bt_hci  : epilog_finished_callback
,08-17 14:23:40.943  3914  4086 I bt_hci_h4: hal_close
,08-17 14:23:40.945  3914  4086 I bt_userial_vendor: device fd = 51 close
,08-17 14:23:41.058  3914  4083 D bt_stack_manager: event_shut_down_stack finished.
,08-17 14:23:41.060  3914  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-17 14:23:41.066  3914  3914 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:23:41.067  3914  4082 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-17 14:23:41.068  3914  3914 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 14:23:41.068  3914  3914 D BtGatt.GattService: stop()
,08-17 14:23:41.068  3914  3914 D BtGatt.AdvertiseManager: advertise clients cleared
,08-17 14:23:41.076  3914  3914 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:23:41.077  3914  3914 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:23:41.077  3914  3914 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:41.077  3914  3914 V BluetoothAdapterState: isBleTurningOff()=true
,08-17 14:23:41.078  3914  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-17 14:23:41.079  3914  4082 D BluetoothAdapterProperties: Setting state to 10
08-17 14:23:41.079  3914  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-17 14:23:41.082  3914  4082 I BluetoothAdapterState: Entering OffState
08-17 14:23:41.084   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-17 14:23:41.107  3914  3914 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-17 14:23:41.107  3914  3914 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-17 14:23:41.108  3914  3914 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-17 14:23:41.112  3914  4083 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-17 14:23:41.118  3914  4083 D bt_stack_manager: event_clean_up_stack finished.
,08-17 14:23:41.123  3914  3914 I art     : System.exit called, status: 0
,08-17 14:23:41.123  3914  3914 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-17 14:23:41.179   872  1990 I ActivityManager: Process com.android.bluetooth (pid 3914) has died
,08-17 14:23:41.203  1841  2639 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 14:23:43.613  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:23:43.613  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:46.621  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:46.621  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e7d1169 added. We now have 6 listener(s)
,08-17 14:23:46.621  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:46.625  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:46.626  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c497ee added. We now have 7 listener(s)
,08-17 14:23:46.626  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:46.627  3765  3816 I System.out: IsBluetoothEnabled
,08-17 14:23:46.637  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:46.674   872   889 I ActivityManager: Start proc 4128:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-17 14:23:46.772  4128  4128 D AdapterServiceConfig: Adding HeadsetService
,08-17 14:23:46.772  4128  4128 D AdapterServiceConfig: Adding A2dpService
08-17 14:23:46.772  4128  4128 D AdapterServiceConfig: Adding HidService
,08-17 14:23:46.772  4128  4128 D AdapterServiceConfig: Adding HealthService
08-17 14:23:46.773  4128  4128 D AdapterServiceConfig: Adding PanService
08-17 14:23:46.773  4128  4128 D AdapterServiceConfig: Adding GattService
,08-17 14:23:46.773  4128  4128 D AdapterServiceConfig: Adding BluetoothMapService
,08-17 14:23:46.788   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6cd83f5:true
,08-17 14:23:46.788  4128  4128 D BluetoothAdapterState: make() - Creating AdapterState
,08-17 14:23:46.793  4128  4128 I bt_bluedroid: init
,08-17 14:23:46.794  4128  4140 I BluetoothAdapterState: Entering OffState
,08-17 14:23:46.800  4128  4141 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-17 14:23:46.800  4128  4141 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-17 14:23:46.800  4128  4141 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 14:23:46.801  4128  4141 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-17 14:23:46.803  4128  4128 I bt_bluedroid: get_profile_interface socket
,08-17 14:23:46.806  4128  4128 I bt_bluedroid: get_profile_interface sdp
,08-17 14:23:46.808  4128  4144 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 14:23:46.811  4128  4139 I bt_bluedroid: config_hci_snoop_log
,08-17 14:23:46.812  4128  4144 D BluetoothAdapterProperties: Name is: Nexus 6
,08-17 14:23:46.814   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-17 14:23:46.823  4128  4140 D BluetoothAdapterState: Current state: OFF, message: 0
,08-17 14:23:46.824  4128  4140 D BluetoothAdapterProperties: Setting state to 14
,08-17 14:23:46.825  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-17 14:23:46.829  4128  4140 D BluetoothBondStateMachine: make
,08-17 14:23:46.834  4128  4145 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 14:23:46.840  4128  4140 I BluetoothAdapterState: Entering PendingCommandState
,08-17 14:23:46.841  4128  4128 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-17 14:23:46.846  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:46.848  4128  4128 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-17 14:23:46.850  4128  4128 D BtGatt.GattService: Received start request. Starting profile...
,08-17 14:23:46.850  4128  4128 D BtGatt.GattService: start()
,08-17 14:23:46.851  4128  4128 I bt_bluedroid: get_profile_interface gatt
,08-17 14:23:46.853  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:46.853  4128  4128 D BtGatt.AdvertiseManager: advertise manager created
,08-17 14:23:46.866  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:23:46.867  4128  4128 V BluetoothAdapterState: isTurningOn()=false
,08-17 14:23:46.867  4128  4128 V BluetoothAdapterState: isBleTurningOn()=true
,08-17 14:23:46.867  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:46.868  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4,
08-17 14:23:46.869  4128  4140 I bt_bluedroid: enable
,08-17 14:23:46.869  4128  4141 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-17 14:23:46.870  4128  4141 I bt_hci  : start_up
,08-17 14:23:46.891  4128  4141 I bt_vendor: alloc value 0xb3a4a189
08-17 14:23:46.891  4128  4141 I bt_vendor: init
,08-17 14:23:46.892  4128  4141 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-17 14:23:46.892  4128  4141 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-17 14:23:47.001  4128  4141 D bt_hci  : start_up starting async portion
,08-17 14:23:47.001  4128  4148 I bt_hci  : event_finish_startup
08-17 14:23:47.001  4128  4148 I bt_hci_h4: hal_open
,08-17 14:23:47.005  4128  4148 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-17 14:23:47.016  4128  4148 I bt_userial_vendor: device fd = 51 open
,08-17 14:23:47.043  4128  4148 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 14:23:47.075  4128  4148 D bt_hwcfg: Chipset BCM4354A2
,08-17 14:23:47.075  4128  4148 D bt_hwcfg: Target name = [BCM4354A2]
08-17 14:23:47.076  4128  4148 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-17 14:23:47.735  4128  4148 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-17 14:23:47.737  4128  4148 D bt_hwcfg: Settlement delay -- 100 ms
08-17 14:23:47.737  4128  4148 I bt_hwcfg: Setting fw settlement delay to 100 
,08-17 14:23:47.854  4128  4148 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-17 14:23:47.855  4128  4148 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-17 14:23:47.884  4128  4148 I bt_hwcfg: vendor lib fwcfg completed
,08-17 14:23:47.885  4128  4148 I bt_vendor: firmware callback
08-17 14:23:47.885  4128  4148 I bt_hci  : firmware_config_callback
,08-17 14:23:47.896  4128  4150 I bt_btu  : btu_task pending for preload complete event
,08-17 14:23:47.896  4128  4150 I bt_btu_task: Bluetooth chip preload is complete
08-17 14:23:47.896  4128  4150 I bt_btu  : btu_task received preload complete event
,08-17 14:23:47.906  4128  4150 I         : BTE_InitTraceLevels -- TRC_HCI
,08-17 14:23:47.906  4128  4150 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-17 14:23:47.907  4128  4150 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 14:23:47.907  4128  4150 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 14:23:47.907  4128  4150 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-17 14:23:47.908  4128  4150 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 14:23:47.908  4128  4150 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 14:23:47.908  4128  4150 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 14:23:47.908  4128  4150 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 14:23:47.909  4128  4150 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 14:23:47.909  4128  4150 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 14:23:47.909  4128  4150 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 14:23:47.910  4128  4150 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 14:23:47.910  4128  4150 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 14:23:47.910  4128  4150 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 14:23:48.050  4128  4150 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c7d9d
,08-17 14:23:48.050  4128  4150 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c7d9d 
,08-17 14:23:48.059  4128  4144 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-17 14:23:48.060  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-17 14:23:48.061  4128  4144 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-17 14:23:48.065  4128  4144 D BluetoothAdapterProperties: Name is: Nexus 6
08-17 14:23:48.069  4128  4144 D BluetoothAdapterProperties: Scan Mode:20
,08-17 14:23:48.070  4128  4144 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:23:48.070  4128  4144 D bt_hci  : do_postload posting postload work item
08-17 14:23:48.070  4128  4148 I bt_hci  : event_postload
08-17 14:23:48.070  4128  4148 I bt_vendor: sco_config_cb
08-17 14:23:48.070  4128  4148 I bt_hci  : sco_config_callback postload finished.
08-17 14:23:48.073  4128  4144 D bt_bte_conf: Device ID record 1 : primary
08-17 14:23:48.074  4128  4144 D bt_bte_conf:   vendorId            = 000f
08-17 14:23:48.074  4128  4144 D bt_bte_conf:   vendorIdSource      = 0001
08-17 14:23:48.074  4128  4144 D bt_bte_conf:   product             = 1200
08-17 14:23:48.074  4128  4144 D bt_bte_conf:   version             = 1436
08-17 14:23:48.074  4128  4144 D bt_bte_conf:   clientExecutableURL = 
,08-17 14:23:48.075  4128  4144 D bt_bte_conf:   serviceDescription  = 
08-17 14:23:48.075  4128  4144 D bt_bte_conf:   documentationURL    = 
08-17 14:23:48.075  4128  4144 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-17 14:23:48.076  4128  4141 D bt_stack_manager: event_start_up_stack finished
08-17 14:23:48.075  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:48.078  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-17 14:23:48.078  4128  4140 D BluetoothAdapterProperties: Setting state to 15
08-17 14:23:48.079  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-17 14:23:48.079  4128  4148 I bt_vendor: low_power_mode_cb
,08-17 14:23:48.080  4128  4140 I BluetoothAdapterState: Entering BleOnState
,08-17 14:23:48.084  4128  4140 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-17 14:23:48.085  4128  4140 D BluetoothAdapterProperties: Setting state to 11
,08-17 14:23:48.086  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-17 14:23:48.093  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:48.098  1479  2227 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-17 14:23:48.103  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:48.106  4128  4128 D HeadsetService: Received start request. Starting profile...
,08-17 14:23:48.108  4128  4140 I BluetoothAdapterState: Entering PendingCommandState
,08-17 14:23:48.110  4128  4128 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-17 14:23:48.110  4128  4128 D HeadsetStateMachine: make
,08-17 14:23:48.120  4128  4128 D HeadsetStateMachine: max_hf_connections = 1
,08-17 14:23:48.120  4128  4128 I bt_bluedroid: get_profile_interface handsfree
,08-17 14:23:48.120  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-17 14:23:48.121  4128  4144 E bt_btif : btif_hf_upstreams_evt: Invalid index 3,
,08-17 14:23:48.125  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
08-17 14:23:48.126  4128  4128 D A2dpService: Received start request. Starting profile...,
,08-17 14:23:48.127  4128  4128 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 14:23:48.127  4128  4128 I bt_bluedroid: get_profile_interface avrcp
,08-17 14:23:48.135  4128  4128 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-17 14:23:48.135  4128  4128 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 14:23:48.135  4128  4128 D A2dpStateMachine: make
,08-17 14:23:48.137  4128  4128 I bt_bluedroid: get_profile_interface a2dp
,08-17 14:23:48.137  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-17 14:23:48.140  4128  4159 D A2dpStateMachine: Enter Disconnected: -2
,08-17 14:23:48.141  4128  4128 I BluetoothHidServiceJni: classInitNative: succeeds
,08-17 14:23:48.142  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
08-17 14:23:48.143  4128  4128 D HidService: Received start request. Starting profile...
,08-17 14:23:48.144  4128  4128 I bt_bluedroid: get_profile_interface hidhost
,08-17 14:23:48.144  4128  4128 D HidService: setHidService(): set to: null
08-17 14:23:48.144  4128  4144 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a93e5
08-17 14:23:48.144  4128  4144 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-17 14:23:48.146  4128  4128 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 14:23:48.147  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
08-17 14:23:48.148  4128  4128 D HealthService: Received start request. Starting profile...
,08-17 14:23:48.149  1479  1479 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:48.151  4128  4128 I bt_bluedroid: get_profile_interface health
,08-17 14:23:48.153  4128  4128 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-17 14:23:48.154  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:48.155  4128  4128 D PanService: Received start request. Starting profile...
,08-17 14:23:48.156  4128  4128 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 14:23:48.156  4128  4128 I bt_bluedroid: get_profile_interface pan
,08-17 14:23:48.157  4128  4144 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-17 14:23:48.162  4128  4128 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:48.164  4128  4128 D BluetoothMapService: Received start request. Starting profile...
,08-17 14:23:48.164  4128  4128 D BluetoothMapService: start()
,08-17 14:23:48.168  4128  4128 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-17 14:23:48.169  4128  4128 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-17 14:23:48.170  4128  4128 D BluetoothMapAppObserver: createReceiver()
,08-17 14:23:48.171  4128  4128 D BluetoothMapAppObserver: initObservers()
,08-17 14:23:48.172  4128  4128 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-17 14:23:48.183  4128  4157 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 14:23:48.184  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:23:48.184  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-17 14:23:48.184  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:48.184  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:23:48.186  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:23:48.186  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-17 14:23:48.187  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:48.187  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:23:48.187  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-17 14:23:48.187  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-17 14:23:48.187  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:48.187  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:23:48.187  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-17 14:23:48.187  4128  4128 V BluetoothAdapterState: isTurningOn()=true
,08-17 14:23:48.187  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
,08-17 14:23:48.188  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:23:48.193  4128  4128 V BluetoothAdapterState: isTurningOff()=false
08-17 14:23:48.193  4128  4128 V BluetoothAdapterState: isTurningOn()=true
,08-17 14:23:48.193  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:48.193  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
08-17 14:23:48.193  4128  4128 V BluetoothAdapterState: isTurningOff()=false
,08-17 14:23:48.193  4128  4128 V BluetoothAdapterState: isTurningOn()=true
08-17 14:23:48.193  4128  4128 V BluetoothAdapterState: isBleTurningOn()=false
08-17 14:23:48.193  4128  4128 V BluetoothAdapterState: isBleTurningOff()=false
,08-17 14:23:48.194  4128  4140 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-17 14:23:48.194  4128  4140 D BluetoothAdapterProperties: ScanMode =  20
08-17 14:23:48.194  4128  4140 D BluetoothAdapterProperties: State =  11
,08-17 14:23:48.195  4128  4140 D BluetoothAdapterProperties: Setting state to 12
08-17 14:23:48.196  4128  4140 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 14:23:48.197  4128  4144 D BluetoothAdapterProperties: Scan Mode:21
,08-17 14:23:48.198  4128  4144 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 14:23:48.197  3835  3846 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 14:23:48.198  4128  4140 I BluetoothAdapterState: Entering OnState
,08-17 14:23:48.199  4128  4128 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-17 14:23:48.201   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:23:48.201  4128  4128 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-17 14:23:48.201  3835  3849 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 14:23:48.203  4128  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:48.205  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:48.205  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:48.205  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:48.205  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:48.205  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:48.205  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:48.205  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:48.205  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:48.206   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:23:48.208  1362  1374 D BluetoothPan: onBluetoothStateChange on: true
,08-17 14:23:48.209  4128  4128 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 14:23:48.210  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 14:23:48.211  3835  3846 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 14:23:48.212  4128  4128 D ObexServerSockets: Succeed to create listening sockets 
,08-17 14:23:48.212  4128  4128 D ObexServerSockets0: startAccept()
08-17 14:23:48.212  4128  4128 D ObexServerSockets0: prepareForNewConnect()
,08-17 14:23:48.214  3835  3849 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:23:48.215  1362  1375 D BluetoothMap: onBluetoothStateChange: up=true
,08-17 14:23:48.216  4128  4128 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-17 14:23:48.216  4128  4128 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-17 14:23:48.217  3835  3835 D BluetoothInputDevice: Proxy object connected
08-17 14:23:48.218  3835  3835 D HidProfile: Bluetooth service connected
08-17 14:23:48.218  4128  4165 D ObexServerSockets0: Accepting socket connection...
,08-17 14:23:48.218  3835  3849 D BluetoothMap: onBluetoothStateChange: up=true
08-17 14:23:48.219   872   872 D BluetoothA2dp: Proxy object connected
08-17 14:23:48.219  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:23:48.220  1362  1362 D PanProfile: Bluetooth service connected
08-17 14:23:48.220  1362  1362 D BluetoothMap: Proxy object connected
,08-17 14:23:48.220  1362  1362 D MapProfile: Bluetooth service connected
,08-17 14:23:48.220  1362  1362 D BluetoothMap: getConnectedDevices()
08-17 14:23:48.220  4128  4166 D ObexServerSockets0: Accepting socket connection...
,08-17 14:23:48.223  1362  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 14:23:48.225  1362  1362 D BluetoothInputDevice: Proxy object connected
08-17 14:23:48.225  3835  4164 D BluetoothPan: onBluetoothStateChange on: true
08-17 14:23:48.225  1362  1362 D HidProfile: Bluetooth service connected
,08-17 14:23:48.227  1362  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 14:23:48.229   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:23:48.229  3835  3835 D BluetoothA2dp: Proxy object connected
08-17 14:23:48.229  1362  1362 D BluetoothA2dp: Proxy object connected
,08-17 14:23:48.229  1976  2277 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 14:23:48.230  3835  3835 D BluetoothMap: Proxy object connected
08-17 14:23:48.231  3835  3835 D MapProfile: Bluetooth service connected
,08-17 14:23:48.231  3835  3835 D BluetoothMap: getConnectedDevices()
08-17 14:23:48.231  1362  2091 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 14:23:48.232  3835  3835 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 14:23:48.232  3835  3835 D PanProfile: Bluetooth service connected
,08-17 14:23:48.232  1362  1375 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:23:48.233   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 14:23:48.234   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,08-17 14:23:48.236  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:48.237  4128  4128 D BluetoothMapService: onReceive
08-17 14:23:48.237  4128  4128 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 14:23:48.237  4128  4128 D BluetoothMapService: STATE_ON
,08-17 14:23:48.244  3835  3835 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-17 14:23:48.250  1479  1479 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 14:23:48.251  3835  3835 D DockEventReceiver: finishStartingService: stopping service
,08-17 14:23:48.260  3835  3835 D BluetoothPbap: Proxy object connected
,08-17 14:23:48.260  3835  3835 D PbapServerProfile: Bluetooth service connected
,08-17 14:23:48.262  1362  1362 D BluetoothPbap: Proxy object connected
,08-17 14:23:48.262  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-17 14:23:48.272  4128  4128 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-17 14:23:48.272  4128  4128 D ObexServerSockets0: prepareForNewConnect()
,08-17 14:23:48.277  4128  4172 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:48.301  4128  4176 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 14:23:48.304  4128  4176 I BtOppRfcommListener: Accept thread started.
,08-17 14:23:48.304   872   872 D BluetoothHeadset: Proxy object connected
,08-17 14:23:48.304   872   872 D BluetoothHeadset: Proxy object connected
,08-17 14:23:48.304   872   872 D BluetoothHeadset: Proxy object connected
08-17 14:23:48.305  1976  2081 D BluetoothHeadset: Proxy object connected
,08-17 14:23:48.306  1362  2091 D BluetoothHeadset: Proxy object connected
,08-17 14:23:48.307  1362  1362 D HeadsetProfile: Bluetooth service connected
08-17 14:23:48.307  3835  3846 D BluetoothHeadset: Proxy object connected
08-17 14:23:48.308  3835  3835 D HeadsetProfile: Bluetooth service connected
,08-17 14:23:48.315  3835  4164 D BluetoothHeadset: Proxy object connected
,08-17 14:23:48.315  3835  3835 D HeadsetProfile: Bluetooth service connected
,08-17 14:23:48.329   872   889 D BluetoothHeadset: Proxy object connected
,08-17 14:23:48.330  1976  1989 D BluetoothHeadset: Proxy object connected
,08-17 14:23:48.332  1362  1375 D BluetoothHeadset: Proxy object connected
,08-17 14:23:48.333  1362  1362 D HeadsetProfile: Bluetooth service connected
08-17 14:23:48.333   872   889 D BluetoothHeadset: Proxy object connected
,08-17 14:23:48.658  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:48.658  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:48.658  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:48.658  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 14:23:48.658  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:48.658  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:48.658  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:48.658  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:48.665  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:48.670  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:23:48.671  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@813648f added. We now have 8 listener(s)
08-17 14:23:48.671  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:48.677   872  1982 D WifiService: setWifiEnabled: false pid=3765, uid=10000
,08-17 14:23:48.677   872  1982 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:23:48.690  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:48.691   872  1671 D WifiService: setWifiEnabled: true pid=3765, uid=10000
,08-17 14:23:48.692   872  1671 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 14:23:48.704   872  1303 D WifiConfigStore: Loading config and enabling all networks 
,08-17 14:23:48.719  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:48.719  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:48.719  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:48.719  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:48.719  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:48.719  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:48.719  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:48.719  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:48.725  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:48.728  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 14:23:48.728  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:48.728  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:48.728  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:48.728  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:48.728  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 14:23:48.728  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 14:23:48.728  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 14:23:48.731  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-17 14:23:48.735  3765  3816 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-17 14:23:48.735  3765  3816 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-17 14:23:48.738   872  1303 D WifiConfigStore: loaded 0 passpoint configs
,08-17 14:23:48.737  3765  3816 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a1fb6a5 Bundle[{}]
08-17 14:23:48.738  3765  3816 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-17 14:23:48.738  3765  3816 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 14:23:48.738   872  1303 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-17 14:23:48.739  3765  3816 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 14:23:48.740   872  1303 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-17 14:23:48.740  3765  3816 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 14:23:48.740  3765  3816 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-17 14:23:48.740   872  1303 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-17 14:23:48.741   872  1303 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-17 14:23:48.741   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-17 14:23:48.741  3765  3816 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-17 14:23:48.741   872  1303 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-17 14:23:48.745  3765  3816 I System.out: Running OutgoingSocketThread
,08-17 14:23:48.747  3765  4181 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 415)
,08-17 14:23:48.747  3765  4181 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39532
08-17 14:23:48.748  3765  4181 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-17 14:23:48.753   371   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-17 14:23:48.754   872  1303 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.21 rxSuccessRate=0.29 delta 1000 -> 1000
08-17 14:23:48.754   872  1303 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-17 14:23:48.754   371   870 D CommandListener: Setting iface cfg
08-17 14:23:48.755   872  1302 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-17 14:23:48.755   872  1302 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-17 14:23:48.763   872  1303 E native  : do suspend true
,08-17 14:23:48.764   872  1302 D WifiNative-HAL: p2pGetDeviceAddress
,08-17 14:23:48.771   872  1302 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-17 14:23:48.779   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-17 14:23:48.779   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:48.800   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-17 14:23:48.857   872  1303 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-17 14:23:48.860  1439  1439 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-17 14:23:49.308  1439  1439 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 14:23:49.349  1439  1439 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-17 14:23:49.350  1439  1439 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-17 14:23:49.355   872  1303 D WifiConfigStore: Retrieve network priorities after PNO.
,08-17 14:23:49.364   872  1303 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 14:23:49.365   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:49.365   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-17 14:23:49.385   872  1303 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-17 14:23:49.397   371   870 D CommandListener: Setting iface cfg
,08-17 14:23:49.398   872  1303 D WifiStateMachine: Start Dhcp Watchdog 3
,08-17 14:23:49.408   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-17 14:23:49.446   872  4185 D DhcpClient: Receive thread started
,08-17 14:23:49.532   872  1303 E native  : do suspend false
,08-17 14:23:49.542   872  2087 D DhcpClient: Broadcasting DHCPDISCOVER
,08-17 14:23:49.554   872  4185 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
08-17 14:23:49.555   872  2087 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-17 14:23:49.556   872  2087 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-17 14:23:49.584   872  4185 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-17 14:23:49.585   872  2087 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-17 14:23:49.588   371   870 D CommandListener: Setting iface cfg
,08-17 14:23:49.595   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-17 14:23:49.600   872  1303 E native  : do suspend true
,08-17 14:23:49.601   872  2087 D DhcpClient: Scheduling renewal in 86399s
,08-17 14:23:49.616   872  1303 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-17 14:23:49.617   872  1303 D WifiConfigStore: No blacklist allowed without epno enabled
08-17 14:23:49.618   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-17 14:23:49.622   872  1303 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-17 14:23:49.624   872  1305 D ConnectivityService: Adding iface wlan0 to network 102
,08-17 14:23:49.678   872  1305 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-17 14:23:49.678   872  1305 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-17 14:23:49.680   872  1305 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-17 14:23:49.682   872  1305 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-17 14:23:49.683   872  1305 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-17 14:23:49.691   872  1305 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 14:23:49.696   872  1305 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-17 14:23:49.697   872  1305 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-17 14:23:49.697   872  1305 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-17 14:23:49.697   872  1305 D ConnectivityService:    accepting network in place of null
,08-17 14:23:49.697   872  1303 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-17 14:23:49.698   872  1303 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-17 14:23:49.698   872  1305 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-17 14:23:49.721   872  4184 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165822, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-17 14:23:49.744   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-17 14:23:49.747  3765  3816 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 416)
,08-17 14:23:49.747  3765  3816 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 416)
,08-17 14:23:49.750  3765  3816 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 421)
,08-17 14:23:49.751  3765  3816 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-17 14:23:49.751  3765  3816 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,08-17 14:23:49.753  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 14:23:49.754  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7f931c added. We now have 2 listener(s)
,08-17 14:23:49.756  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 14:23:49.756  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:49.757  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:49.757  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:49.757  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc5b25 added. We now have 9 listener(s)
08-17 14:23:49.757  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:49.758  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:23:49.761  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:49.768  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:49.768  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:49.768  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:49.768  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:49.768  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:49.768  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:49.768  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:49.768  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:49.772  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:49.773  3765  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:49.774  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:49.774  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bebbaab added. We now have 3 listener(s)
,08-17 14:23:49.777  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:49.777   371   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-17 14:23:49.778  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:23:49.779  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:49.779  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:49.779  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:49.779  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180c508 added. We now have 10 listener(s)
08-17 14:23:49.779  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:49.780  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:49.780  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:49.780  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:49.780  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:49.780  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.780  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:49.780  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:49.780  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e7f931c removed from the list
08-17 14:23:49.780  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:49.780  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc5b25 removed from the list
08-17 14:23:49.780  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:49.781   872  1305 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-17 14:23:49.781   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 14:23:49.781  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:49.781  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:49.784   872  1305 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-17 14:23:49.785   872   889 D Tethering: MasterInitialState.processMessage what=3
,08-17 14:23:49.787   872  4183 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.46,2a00:1450:4001:80b::200e
,08-17 14:23:49.790  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:49.790  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:49.794  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:49.794  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:23:49.794  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:49.794  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecc5b25 not in the list
08-17 14:23:49.794  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:49.794  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:49.797  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-17 14:23:49.797  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:49.797  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:49.797  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:49.797  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:49.797  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:49.797  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:49.797  3765  3765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:49.798  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:49.798  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:49.798  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:49.798  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180c508 removed from the list
,08-17 14:23:49.798  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:49.798  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.798  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:49.798  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:49.798  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bebbaab removed from the list
,08-17 14:23:49.799  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 14:23:49.799  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0c84a1 added. We now have 2 listener(s)
08-17 14:23:49.800  3765  3765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:49.801  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:23:49.801  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:23:49.801  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:49.801  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:49.801  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@743b6c6 added. We now have 9 listener(s)
,08-17 14:23:49.801  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:49.802  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:23:49.804  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:49.808  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:49.808  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:49.808  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:49.808  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:49.808  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:49.808  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:49.808  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:49.808  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:49.810  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:49.810  3765  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:23:49.811  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:49.811  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe129b4 added. We now have 3 listener(s)
08-17 14:23:49.813  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:49.813  1677  1677 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-17 14:23:49.815  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:49.816  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:23:49.816  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:49.816  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:49.816  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:49.816  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cbc9dd added. We now have 10 listener(s)
08-17 14:23:49.816  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:49.817  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:49.817  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:23:49.817  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:23:49.817  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:49.817  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:23:49.820  1677  1677 D SystemUpdateService: onCreate
,08-17 14:23:49.821  3765  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 14:23:49.821  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:49.824  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:49.825  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-17 14:23:49.825  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:49.828  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 14:23:49.828  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:23:49.828  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-17 14:23:49.829  3765  3816 D BluetoothAdapter: STATE_ON
,08-17 14:23:49.831  4128  4168 D BtGatt.GattService: registerClient() - UUID=efb94d2e-9986-43ba-8bdc-469691d3de5c
08-17 14:23:49.831  1677  1677 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-17 14:23:49.831  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=efb94d2e-9986-43ba-8bdc-469691d3de5c, clientIf=5,
,08-17 14:23:49.832  3765  3777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 14:23:49.833  4128  4156 D BtGatt.GattService: start scan with filters
08-17 14:23:49.834  3721  4197 I BooksSync: Starting books sync for 61035162, extras: ade
,08-17 14:23:49.837  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:23:49.837  4128  4147 D BtGatt.ScanManager: handling starting scan
,08-17 14:23:49.837  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:23:49.837  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:23:49.837  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:49.838  4128  4147 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@8e9b4e9
,08-17 14:23:49.840  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:23:49.840  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 14:23:49.840  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:49.841  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:49.841  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 14:23:49.842  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:49.842  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 14:23:49.843  3765  3816 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-17 14:23:49.843  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:49.843  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-17 14:23:49.843  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.843  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:49.843  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-17 14:23:49.843  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:23:49.843  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:49.844  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:23:49.844  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-17 14:23:49.844  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:23:49.844  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-17 14:23:49.844  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.844  3765  3816 D BluetoothAdapter: STATE_ON
,08-17 14:23:49.844  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:23:49.845  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 14:23:49.845  4128  4168 D BtGatt.GattService: stopScan() - queue size =1
08-17 14:23:49.845  4128  4156 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 14:23:49.845  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 14:23:49.845  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:23:49.846  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:23:49.846  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:23:49.846  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 14:23:49.846  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 14:23:49.846  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.846  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:49.847  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 14:23:49.847  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:23:49.847  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 14:23:49.847  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:49.847  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 14:23:49.847  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.848  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:49.848  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:49.848  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:49.851  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 14:23:49.851  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.851  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:49.851  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
08-17 14:23:49.851  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:49.851  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:49.852  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:49.852  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:49.852  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:49.852  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:49.852  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c0c84a1 removed from the list
08-17 14:23:49.852  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:49.852  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@743b6c6 removed from the list
08-17 14:23:49.852  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:49.852  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:49.853  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.853  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:49.853  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 14:23:49.853  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:49.853  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-17 14:23:49.853  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:49.853  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:23:49.853  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:49.853  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@743b6c6 not in the list
,08-17 14:23:49.854  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.854  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:49.854   872  4183 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 12:23:49 GMT], X-Android-Received-Millis=[1471436629853], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471436629825]}
08-17 14:23:49.855   872  1305 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-17 14:23:49.855   872  1305 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-17 14:23:49.855   872  1305 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 14:23:49.855  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 14:23:49.855  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:49.855  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:49.855  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:49.855  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:49.856  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cbc9dd removed from the list
,08-17 14:23:49.856  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:49.856  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.856  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:49.856  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 14:23:49.856  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe129b4 removed from the list
08-17 14:23:49.856   872  1305 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 14:23:49.856  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:49.857  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4026d9 added. We now have 2 listener(s)
08-17 14:23:49.858  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:23:49.858  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:23:49.858  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:49.858  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:49.859  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfcd89e added. We now have 9 listener(s)
08-17 14:23:49.859  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:49.859  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-17 14:23:49.861  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:49.864  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:49.864  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:49.864  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:49.864  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:49.864  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:49.864  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:49.864  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:49.864  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:49.865  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:49.866  3765  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:23:49.866  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:49.866  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dbfb4c added. We now have 3 listener(s)
08-17 14:23:49.867  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:23:49.867  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:49.867  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:49.867  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:49.867  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5035795 added. We now have 10 listener(s)
,08-17 14:23:49.867  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:49.867  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:49.867  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:49.868  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:23:49.868  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:23:49.868  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 14:23:49.868  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:49.868  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 14:23:49.869  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:49.870  3765  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-17 14:23:49.871  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:49.874  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:49.874  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 14:23:49.874  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:49.874  1677  4196 I SystemUpdateService: active receiver: enabled
,08-17 14:23:49.877  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-17 14:23:49.877  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:23:49.877  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 14:23:49.878  3765  3816 D BluetoothAdapter: STATE_ON
,08-17 14:23:49.880  4128  4139 D BtGatt.GattService: registerClient() - UUID=4c450dc0-c43c-419a-be04-11368ad7eac4
,08-17 14:23:49.880  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=4c450dc0-c43c-419a-be04-11368ad7eac4, clientIf=5
08-17 14:23:49.880  3765  3777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 14:23:49.881  4128  4138 D BtGatt.GattService: start scan with filters
,08-17 14:23:49.884  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:23:49.884  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:23:49.884  4128  4147 D BtGatt.ScanManager: handling starting scan
,08-17 14:23:49.884  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:23:49.884  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:49.886  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-17 14:23:49.886  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.886  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 14:23:49.887  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:23:49.887  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-17 14:23:49.887  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-17 14:23:49.887  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 14:23:49.888  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.888  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:23:49.888  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-17 14:23:49.888  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:49.890  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-17 14:23:49.890  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:49.891  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 14:23:49.891  3765  3816 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-17 14:23:49.891  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-17 14:23:49.891  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.891  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 14:23:49.891  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-17 14:23:49.891  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:49.891  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:49.891  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.892  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:49.892  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-17 14:23:49.892  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4026d9 removed from the list
,08-17 14:23:49.892  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:49.892  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfcd89e removed from the list
08-17 14:23:49.892  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:49.892  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:49.892  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:49.892  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-17 14:23:49.893  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.893  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 14:23:49.893  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:49.893  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:49.894  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:49.894  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bfcd89e not in the list
08-17 14:23:49.894  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-17 14:23:49.894  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 14:23:49.894  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:23:49.894  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:23:49.894  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-17 14:23:49.895  3765  3816 D BluetoothAdapter: STATE_ON
08-17 14:23:49.895  4128  4138 D BtGatt.GattService: stopScan() - queue size =1
08-17 14:23:49.896  4128  4168 D BtGatt.GattService: unregisterClient() - clientIf=5
08-17 14:23:49.896  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 14:23:49.896  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-17 14:23:49.896  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-17 14:23:49.896  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:23:49.896  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-17 14:23:49.897  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:49.897  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 14:23:49.897  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:23:49.898  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:23:49.898  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 14:23:49.898  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.898  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
08-17 14:23:49.899  1677  1677 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-17 14:23:49.902  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:49.903  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:23:49.903  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:49.903  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:49.903  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5035795 removed from the list
08-17 14:23:49.903  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:23:49.903  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.903  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:49.903  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:49.904  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8dbfb4c removed from the list
08-17 14:23:49.904  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:49.904  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78ed811 added. We now have 2 listener(s)
,08-17 14:23:49.905  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:49.905  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-17 14:23:49.906  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:49.906  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:23:49.906  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:23:49.906  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:49.906  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:49.906  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 14:23:49.906  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcd5d76 added. We now have 9 listener(s)
08-17 14:23:49.907  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:49.908  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-17 14:23:49.908  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.908  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 14:23:49.909  1677  2507 I iu.UploadsManager: num queued entries: 0
08-17 14:23:49.909  1677  2507 I iu.UploadsManager: num updated entries: 0
08-17 14:23:49.910  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-17 14:23:49.913  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 14:23:49.916  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-17 14:23:49.917  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:49.918  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:49.918  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:49.918  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:49.918  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:49.918  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:49.918  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:49.918  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:49.918  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 14:23:49.920  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 14:23:49.920  3765  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 14:23:49.920  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-17 14:23:49.920  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fc67e4 added. We now have 3 listener(s)
,08-17 14:23:49.922  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-17 14:23:49.922  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:49.922  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-17 14:23:49.922  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:49.923  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277e44d added. We now have 10 listener(s)
08-17 14:23:49.923  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:49.923  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:23:49.923  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 14:23:49.923  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-17 14:23:49.923  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:49.923  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-17 14:23:49.925  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:49.927  3765  3816 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-17 14:23:49.927  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 14:23:49.927  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 14:23:49.931  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 14:23:49.931  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-17 14:23:49.932  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 14:23:49.935  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-17 14:23:49.935  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-17 14:23:49.935  3765  3816 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-17 14:23:49.936  3765  3816 D BluetoothAdapter: STATE_ON
,08-17 14:23:49.938  4128  4167 D BtGatt.GattService: registerClient() - UUID=7657f85a-f344-4486-ac47-5cf4c3a27068
,08-17 14:23:49.938  4128  4144 D BtGatt.GattService: onClientRegistered() - UUID=7657f85a-f344-4486-ac47-5cf4c3a27068, clientIf=5
08-17 14:23:49.938  3765  3777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-17 14:23:49.939  4128  4139 D BtGatt.GattService: start scan with filters
,08-17 14:23:49.941  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-17 14:23:49.941  4128  4147 D BtGatt.ScanManager: handling starting scan
08-17 14:23:49.941  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-17 14:23:49.941  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-17 14:23:49.941  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-17 14:23:49.944  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:49.944  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-17 14:23:49.944  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-17 14:23:49.947  4128  4144 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-17 14:23:49.947  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-17 14:23:49.947  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.947  4128  4147 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-17 14:23:49.952  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-17 14:23:49.953  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-17 14:23:49.953  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:49.953  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.953  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 14:23:49.953  4128  4147 D BtGatt.ScanManager: Starting BLE batch scan
08-17 14:23:49.953  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:49.953  4128  4147 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-17 14:23:49.953  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-17 14:23:49.953  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-17 14:23:49.953  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:49.953  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78ed811 removed from the list
08-17 14:23:49.953  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:49.953  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcd5d76 removed from the list
08-17 14:23:49.953  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 14:23:49.953  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:49.954  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.954  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-17 14:23:49.954  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.954  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:49.955  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:49.955  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:49.955  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:49.955  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcd5d76 not in the list
,08-17 14:23:49.956  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 14:23:49.956  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-17 14:23:49.956  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 14:23:49.956  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 14:23:49.956  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-17 14:23:49.957  3765  3816 D BluetoothAdapter: STATE_ON,
08-17 14:23:49.958  4128  4156 D BtGatt.GattService: stopScan() - queue size =1
,08-17 14:23:49.962  4128  4167 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-17 14:23:49.962  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-17 14:23:49.962  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-17 14:23:49.963  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-17 14:23:49.963  4128  4144 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-17 14:23:49.963  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.963  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-17 14:23:49.964  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-17 14:23:49.965  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-17 14:23:49.965  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-17 14:23:49.965  3765  3816 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 14:23:49.965  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 14:23:49.965  1677  1677 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-17 14:23:49.966  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:49.966  1677  1677 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-17 14:23:49.967  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:23:49.967  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:49.967  3765  3765 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 14:23:49.967  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:49.967  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:49.967  3765  3765 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 14:23:49.967  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@277e44d removed from the list
08-17 14:23:49.967  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 14:23:49.968  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.968  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:49.968  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 14:23:49.968  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fc67e4 removed from the list
,08-17 14:23:49.968  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-17 14:23:49.968  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:49.968  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6b7849 added. We now have 2 listener(s)
,08-17 14:23:49.968  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-17 14:23:49.969  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:49.969  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:23:49.970  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-17 14:23:49.970  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:49.970  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:49.970  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fdea54e added. We now have 9 listener(s)
08-17 14:23:49.970  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 14:23:49.970  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 14:23:49.972  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 14:23:49.976  3928  3928 D SprintDMHelper: simOperator: 
08-17 14:23:49.976  4128  4144 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-17 14:23:49.976  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-17 14:23:49.976  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-17 14:23:49.976  4128  4147 D BtGatt.ScanManager: stopping BLe Batch
,08-17 14:23:49.976  3765  3816 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 14:23:49.976  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 14:23:49.976  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-17 14:23:49.976  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 14:23:49.976  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 14:23:49.976  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:49.976  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 14:23:49.976  3765  3816 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 14:23:49.980  3765  3816 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 14:23:49.980  3765  3816 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 14:23:49.982  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:49.982  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 14:23:49.982  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfacf7c added. We now have 3 listener(s)
,08-17 14:23:49.984  4128  4144 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-17 14:23:49.984  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-17 14:23:49.984  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:49.984  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 14:23:49.984  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 14:23:49.984  4128  4147 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-17 14:23:49.984  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 14:23:49.984  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ea5005 added. We now have 10 listener(s)
08-17 14:23:49.984  3765  3816 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 14:23:49.984  3765  3816 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-17 14:23:49.984  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:49.985  3765  3816 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 14:23:49.985  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:23:49.985  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.985  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 14:23:49.985  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-17 14:23:49.985  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6b7849 removed from the list
08-17 14:23:49.985  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:49.985  3765  3765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 14:23:49.985  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fdea54e removed from the list
08-17 14:23:49.985  3765  3816 D io.jxcore.node.ConnectivityMonitor: stop
08-17 14:23:49.985  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:49.985  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.986  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 14:23:49.987  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 14:23:49.987  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 14:23:49.987  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 14:23:49.987  3765  3816 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fdea54e not in the list
08-17 14:23:49.987  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.987  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:49.988  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 14:23:49.988  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 14:23:49.988  3765  3816 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 14:23:49.988  3765  3816 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ea5005 removed from the list
08-17 14:23:49.988  3765  3816 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 14:23:49.988  3765  3816 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 14:23:49.988  3765  3816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 14:23:49.988  3765  3816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 14:23:49.988  3765  3816 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cfacf7c removed from the list
,08-17 14:23:49.990  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 14:23:49.991  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 14:23:49.991  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 14:23:49.991  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-17 14:23:49.991  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 14:23:49.991  3765  3816 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 14:23:49.992  4128  4144 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-17 14:23:49.992  4128  4144 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-17 14:23:50.000  3765  4205 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: My test thread name)
,08-17 14:23:50.000  3765  4205 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 429, thread name: My test thread name)
08-17 14:23:50.000  3765  4205 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 429, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 14:23:50.002  3765  4206 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: My test thread name)
,08-17 14:23:50.002  3765  4206 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: My test thread name)
08-17 14:23:50.002  3765  4206 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-17 14:23:50.004  3765  3816 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-17 14:23:50.004  3765  3816 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 14:23:50.004  3765  3816 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 14:23:50.004  3765  3816 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 14:23:50.005  3765  3816 D com.test.thalitest.ThaliTestRunner: Total duration: 21840 ms
,08-17 14:23:50.006  1677  4200 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-17 14:23:50.006  1677  4200 W BaseAppContext: Using Auth Proxy for data requests.
08-17 14:23:50.006  3765  3816 I jxcore-log: Total number of executed tests:  80
08-17 14:23:50.006  3765  3816 I jxcore-log: 
,08-17 14:23:50.007  3765  3816 I jxcore-log: Number of passed tests:  80
08-17 14:23:50.007  3765  3816 I jxcore-log: 
08-17 14:23:50.007  3765  3816 I jxcore-log: Number of failed tests:  0
08-17 14:23:50.007  3765  3816 I jxcore-log: 
08-17 14:23:50.007  3765  3816 I jxcore-log: Number of ignored tests:  0
08-17 14:23:50.007  3765  3816 I jxcore-log: 
,08-17 14:23:50.007  3765  3816 I jxcore-log: Total duration:  21840
08-17 14:23:50.007  3765  3816 I jxcore-log: 
,08-17 14:23:50.008  1677  4200 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
08-17 14:23:50.008  3765  3816 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 14:23:50.008  3765  3816 I jxcore-log: 
,08-17 14:23:50.011  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.011  3765  3816 I jxcore-log: 
08-17 14:23:50.014  3765  3765 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 14:23:50.016  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.016  3765  3816 I jxcore-log: 
08-17 14:23:50.017  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.017  3765  3816 I jxcore-log: 
08-17 14:23:50.018  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.018  3765  3816 I jxcore-log: 
08-17 14:23:50.018  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.018  3765  3816 I jxcore-log: 
08-17 14:23:50.019  1677  4196 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-17 14:23:50.020  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.020  3765  3816 I jxcore-log: 
,08-17 14:23:50.022  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:23:50.022  3765  3816 I jxcore-log: 
08-17 14:23:50.024  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:23:50.024  3765  3816 I jxcore-log: 
08-17 14:23:50.024  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.024  3765  3816 I jxcore-log: 
08-17 14:23:50.025  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:50.025  3765  3816 I jxcore-log: 
08-17 14:23:50.026  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:50.026  3765  3816 I jxcore-log: 
08-17 14:23:50.027  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:23:50.027  3765  3816 I jxcore-log: 
,08-17 14:23:50.028  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:23:50.028  3765  3816 I jxcore-log: 
,08-17 14:23:50.029  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 14:23:50.029  3765  3816 I jxcore-log: 
08-17 14:23:50.029  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.029  3765  3816 I jxcore-log: 
,08-17 14:23:50.030  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.030  3765  3816 I jxcore-log: 
,08-17 14:23:50.031  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:50.031  3765  3816 I jxcore-log: 
,08-17 14:23:50.032  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:50.032  3765  3816 I jxcore-log: 
,08-17 14:23:50.032  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:23:50.032  3765  3816 I jxcore-log: 
08-17 14:23:50.033  1677  2507 I iu.SyncManager: NEXT; no task
,08-17 14:23:50.033  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:23:50.033  3765  3816 I jxcore-log: 
,08-17 14:23:50.034  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:50.034  3765  3816 I jxcore-log: 
08-17 14:23:50.035  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 14:23:50.035  3765  3816 I jxcore-log: 
,08-17 14:23:50.035  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:23:50.035  3765  3816 I jxcore-log: 
,08-17 14:23:50.036  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 14:23:50.036  3765  3816 I jxcore-log: 
08-17 14:23:50.037  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:23:50.037  3765  3816 I jxcore-log: 
,08-17 14:23:50.037  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 14:23:50.037  3765  3816 I jxcore-log: 
08-17 14:23:50.038  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.038  3765  3816 I jxcore-log: 
,08-17 14:23:50.038  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.038  3765  3816 I jxcore-log: 
08-17 14:23:50.039  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.039  3765  3816 I jxcore-log: 
,08-17 14:23:50.040  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.040  3765  3816 I jxcore-log: 
,08-17 14:23:50.040  1677  4196 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-17 14:23:50.040  1677  4196 I SystemUpdateService: now status is 0 (complete)
08-17 14:23:50.040  1677  4196 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-17 14:23:50.040  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.040  3765  3816 I jxcore-log: 
08-17 14:23:50.040  1677  4196 I SystemUpdateService: file has been verified
,08-17 14:23:50.041  1677  4196 I SystemUpdateService: OTA package size = 12249756
08-17 14:23:50.041  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 14:23:50.041  3765  3816 I jxcore-log: 
,08-17 14:23:50.090  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:23:50.092  1479  1479 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-17 14:23:50.122  1479  4212 I VacuumService: Vacuum at: now=1471436630122 tag=VacuumService
08-17 14:23:50.118  1677  4196 I SystemUpdateService: showing system update notification
,08-17 14:23:50.125  3721  4213 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-17 14:23:50.142  3083  4204 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-17 14:23:50.171  1479  1491 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 14:23:50.171  1479  1491 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 14:23:50.171  1479  1491 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:23:50.171  1479  1491 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:23:50.222  1479  2409 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-17 14:23:50.222  1479  2409 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-17 14:23:50.222  1479  2409 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-17 14:23:50.222  1479  2409 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:23:50.237  3721  4213 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-17 14:23:50.238  3721  4197 E BooksSync: Soft error
08-17 14:23:50.238  3721  4197 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 14:23:50.238  3721  4197 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 14:23:50.238  3721  4197 E BooksSync: Sync error
08-17 14:23:50.238  3721  4197 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-17 14:23:50.238  3721  4197 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-17 14:23:50.238  3721  4197 I BooksSync: Finished books sync
,08-17 14:23:50.252   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 157962, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-17 14:23:50.303  1479  1963 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-17 14:23:50.303  1479  1963 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-17 14:23:50.303  1479  1963 I GLSUser : [GLSUser] Extracting token using key: Auth
08-17 14:23:50.303  1479  1963 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-17 14:23:50.310  1677  1677 D SystemUpdateService: onDestroy
,08-17 14:23:50.349  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:23:50.350  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:23:50.350  3765  3816 I jxcore-log: 
,08-17 14:23:50.368  1677  4200 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-17 14:23:50.375  1479  4214 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-17 14:23:50.383  1479  4214 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-17 14:23:50.406  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:23:50.407  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:23:50.407  3765  3816 I jxcore-log: 
,08-17 14:23:50.425  1479  4214 W Uploader:  no longer exists, so no auth token.
,08-17 14:23:50.468  3765  3765 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-17 14:23:50.469  3765  3816 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 14:23:50.469  3765  3816 I jxcore-log: 
,08-17 14:23:50.687  4208  4208 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-17 14:23:50.692  4208  4208 D AndroidRuntime: CheckJNI is OFF
,08-17 14:23:50.734  4208  4208 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-17 14:23:50.782  4208  4208 I Radio-JNI: register_android_hardware_Radio DONE
,08-17 14:23:50.782   872  1305 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-17 14:23:50.803  4208  4208 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 14:23:50.812   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-17 14:23:50.812   872   885 I ActivityManager: Killing 3765:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-17 14:23:50.901   872   895 W PackageSettings: Skipping PackageSetting{6df1bf2 com.example.hello/10273} due to missing metadata
,08-17 14:23:50.930   872   895 I art     : Starting a blocking GC Explicit
,08-17 14:23:50.934   872  1304 D WifiService: Client connection lost with reason: 4
08-17 14:23:50.934   872  1982 D GraphicsStats: Buffer count: 2
,08-17 14:23:50.935   872  1671 I WindowState: WIN DEATH: Window{f728a70 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 14:23:50.954   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-17 14:23:50.954   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-17 14:23:50.954   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-17 14:23:50.954   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-17 14:23:50.954   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:50.954   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:50.954   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:23:50.954   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 14:23:50.956   872   885 I ActivityManager:   Force finishing activity ActivityRecord{4ae52d1 u0 com.test.thalitest/.MainActivity t2}
,08-17 14:23:50.961   872   883 W ActivityManager: Spurious death for ProcessRecord{b9cbf12 0:com.test.thalitest/u0a0}, curProc for 3765: null
,08-17 14:23:50.991   872   895 I art     : Explicit concurrent mark sweep GC freed 54870(3MB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 29MB/43MB, paused 1.048ms total 60.266ms
08-17 14:23:51.011   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-17 14:23:51.013  4208  4208 I art     : System.exit called, status: 0
08-17 14:23:51.013  4208  4208 I AndroidRuntime: VM exiting with result code 0.
,08-17 14:23:51.066   872   895 I ActivityManager: Start proc 4232:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-17 14:23:51.066   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-17 14:23:51.081   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-17 14:23:51.096   872  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 14:23:51.100  4128  4128 D BluetoothMapAppObserver: onReceive
,08-17 14:23:51.100  4128  4128 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-17 14:23:51.104  1841  2248 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 14:23:51.109  3606  3606 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-17 14:23:51.142  1877  1877 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-17 14:23:51.156   872  1301 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-17 14:23:51.161  1877  4246 I Keyboard.Facilitator.DecoderInitializer: run()
,08-17 14:23:51.166  1877  4246 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,08-17 14:23:51.166  1877  4246 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-17 14:23:51.166  1976  1976 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-17 14:23:51.167   872  2058 I ActivityManager: Start proc 4248:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-17 14:23:51.174  1877  4246 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-17 14:23:51.174  1877  4246 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,08-17 14:23:51.175  1877  4246 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-17 14:23:51.175  1877  4246 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,08-17 14:23:51.177  1877  4246 I Decoder : createOrResetDecoder
,08-17 14:23:51.184   872  1671 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3765 uid 10000
,08-17 14:23:51.186  1877  1877 I Keyboard.Facilitator: onFinishInput()
,08-17 14:23:51.197  1479  1479 I ConfigService: onCreate
,08-17 14:23:51.200   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 14:23:51.210  1479  4257 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-17 14:23:51.210  1479  4257 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-17 14:23:51.210  1479  4257 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-17 14:23:51.212  1479  4257 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-17 14:23:51.233  1994  2110 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-17 14:23:51.233   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-17 14:23:51.233   872   884 E PackageManager: Failed to write settings, restoring backup,
08-17 14:23:51.233   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml,
08-17 14:23:51.233   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-17 14:23:51.233   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-17 14:23:51.233   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-17 14:23:51.233   872   884 E PackageManager: 	,at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-17 14:23:51.233   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 14:23:51.233   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:51.233   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-17 14:23:51.238   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-17 14:23:51.238   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-17 14:23:51.238   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 14:23:51.238   872   885 E DropBoxManagerService: 	... 13 more
,08-17 14:23:51.245   872  1671 I ActivityManager: Start proc 4261:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash,
08-17 14:23:51.246  1994  2110 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-17 14:23:51.246  1994  2110 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1994
08-17 14:23:51.246  1994  2110 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-17 14:23:51.246  1994  2110 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61),
,08-17 14:23:51.248   872  2001 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 14:23:51.248   872  4271 E DropBoxManagerService: Can't write: system_app_crash
08-17 14:23:51.248   872  4271 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-17 14:23:51.248   872  4271 E DropBoxManagerService: 	... 5 more
,08-17 14:23:51.279  1994  2110 I Process : Sending signal. PID: 1994 SIG: 9
,08-17 14:23:51.303  4248  4248 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-17 14:23:51.311  1877  4246 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-17 14:23:51.364  1877  4246 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-17 14:23:51.367  1877  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-17 14:23:51.367  1877  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-17 14:23:51.379  1877  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-17 14:23:51.380  1877  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-17 14:23:51.380  1877  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-17 14:23:51.380  1877  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-17 14:23:51.381  1877  4246 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-17 14:23:51.381  1877  4246 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-17 14:23:51.381  1877  4246 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-17 14:23:51.381  1877  4246 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-17 14:23:51.381  1877  4246 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-17 14:23:51.381  1877  4246 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-17 14:23:51.434  1677  4278 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-17 14:23:51.436  1677  4278 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-17 14:23:51.461   872  1670 D GraphicsStats: Buffer count: 1
,08-17 14:23:51.461   872  1992 I WindowState: WIN DEATH: Window{828f273 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-17 14:23:51.480   872  2058 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1994) has died
,08-17 14:23:51.482   872  2058 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-17 14:23:51.487   872  2058 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-17 14:23:51.500  4248  4248 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-17 14:23:51.513   872   885 I ActivityManager: Start proc 4282:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-17 14:23:51.530   872  2064 I ActivityManager: Start proc 4295:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver

```
