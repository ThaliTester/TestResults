#### Test 846487400fb5c63_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-12 13:11:06.114  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:11:06.136  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:11:06.143  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:11:06.222  1502  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 13:11:06.222  1502  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 13:11:06.223  1502  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:11:06.224  1502  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 13:11:06.254  3717  3717 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 13:11:06.255  3717  3717 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 13:11:06.255  3717  3717 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-12 13:11:06.777  3996  3996 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 13:11:06.782  3996  3996 D AndroidRuntime: CheckJNI is OFF
09-12 13:11:06.824  3996  3996 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 13:11:06.881  3996  3996 I Radio-JNI: register_android_hardware_Radio DONE
09-12 13:11:06.903  3996  3996 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 13:11:06.908   874  2035 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 13:11:06.945  2068  2085 W SearchService: Abort, client detached.
09-12 13:11:06.948  3996  3996 D AndroidRuntime: Shutting down VM
09-12 13:11:06.958  2068  2356 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c9b0ea5
09-12 13:11:06.959  2068  2364 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 13:11:06.960  2068  2068 I HotwordDetector: Closing mic
09-12 13:11:06.964   874  2036 I ActivityManager: Start proc 4005:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 13:11:07.016   376  2366 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 13:11:07.017   376  2366 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 13:11:07.025   376  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 13:11:07.028  2068  2363 I MicroRecognitionRnrImpl: Detection finished
09-12 13:11:07.028  2068  2359 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 13:11:07.044  4005  4005 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 13:11:07.066  4005  4005 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 13:11:07.074  4005  4005 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9648-9652)
09-12 13:11:07.074  4005  4005 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:11:07.093  4005  4005 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c5b2dbe}
09-12 13:11:07.094  4005  4005 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:11:07.094  4005  4005 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 13:11:07.101  4005  4005 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 13:11:07.102  4005  4005 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 13:11:07.116  4005  4005 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-12 13:11:07.131  4005  4005 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:11:07.132  4005  4005 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:11:07.132  4005  4005 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 13:11:07.132  4005  4005 I Adreno  : Build Date                       : 10/20/15
09-12 13:11:07.132  4005  4005 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 13:11:07.132  4005  4005 I Adreno  : Local Branch                     : M14
09-12 13:11:07.132  4005  4005 I Adreno  : Remote Branch                    : 
09-12 13:11:07.132  4005  4005 I Adreno  : Remote Branch                    : 
09-12 13:11:07.132  4005  4005 I Adreno  : Reconstruct Branch               : 
09-12 13:11:07.187   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aece901:true
,09-12 13:11:07.243  4005  4005 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 13:11:07.257  4005  4005 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 13:11:07.323  4005  4044 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 13:11:07.333  4005  4031 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 13:11:07.375  4005  4044 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 13:11:07.444   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +497ms
09-12 13:11:07.453  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-12 13:11:07.506  4005  4005 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4005
,09-12 13:11:07.596  4005  4005 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 13:11:07.755  4005  4046 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1677526736
,09-12 13:11:07.755   874  1486 I ActivityManager: Killing 3393:com.google.android.gm/u0a78 (adj 15): empty #17
,09-12 13:11:07.761  4005  4046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 13:11:07.761  4005  4046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 13:11:07.761  4005  4046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 13:11:07.761  4005  4046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 13:11:07.761  4005  4046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 13:11:07.762  4005  4046 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@575c9ad added. We now have 1 listener(s)
,09-12 13:11:07.765  4005  4046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 13:11:07.766  4005  4046 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:11:07.767  4005  4046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:11:07.767  4005  4046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 13:11:07.775  4005  4046 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cdfcb30 added. We now have 1 listener(s)
09-12 13:11:07.775  4005  4046 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:07.778   874  1317 D WifiService: New client listening to asynchronous messages
,09-12 13:11:07.779  4005  4046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:11:07.780  4005  4046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 13:11:07.780  4005  4046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-12 13:11:07.780  4005  4046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 13:11:07.780  4005  4046 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 13:11:07.799   874  1486 I ActivityManager: Killing 3205:com.google.android.apps.fitness/u0a51 (adj 15): empty #18
,09-12 13:11:07.841  4005  4046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:07.841  4005  4046 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 13:11:07.847  4005  4046 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 13:11:07.848  4005  4046 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:07.848  4005  4046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:07.848  4005  4046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:07.848  4005  4046 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:07.848  4005  4046 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:07.848  4005  4046 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:07.848  4005  4046 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:07.848  4005  4046 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:07.849  4005  4046 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-12 13:11:07.849  4005  4046 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:07.851  4005  4046 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 13:11:07.944  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:07.949  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:07.952  4005  4005 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 13:11:08.839  4005  4056 W jxcore-log: Initializing JXcore engine
09-12 13:11:08.839  4005  4056 W jxcore-log: JXcore engine is ready
,09-12 13:11:08.905  4056  4056 W Thread-366: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8974 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 13:11:08.905  4056  4056 W Thread-366: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12047]" dev="sockfs" ino=12047 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-12 13:11:08.905  4056  4056 W Thread-366: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
09-12 13:11:08.905  4056  4056 W Thread-366: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26332]" dev="sockfs" ino=26332 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 13:11:08.924  4005  4056 W jxcore-log: Starting JXcore engine
,09-12 13:11:09.028  4005  4056 W jxcore-log: Platform android
09-12 13:11:09.028  4005  4056 W jxcore-log: 
,09-12 13:11:09.028  4005  4056 W jxcore-log: Process ARCH arm
09-12 13:11:09.028  4005  4056 W jxcore-log: 
,09-12 13:11:09.261  4005  4056 I jxcore-log: JXcore Cordova bridge is ready!
09-12 13:11:09.261  4005  4056 I jxcore-log: 
,09-12 13:11:09.262  4005  4056 W jxcore-log: JXcore engine is started
,09-12 13:11:09.271  4005  4046 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 13:11:09.274  4005  4005 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 13:11:10.660   874  1316 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 13:11:17.885  3274  4069 V KeepSync: Connecting to GoogleApiClient
,09-12 13:11:17.887   874   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 13:11:17.952  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:11:17.956  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:11:17.998  1502  2043 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-12 13:11:17.998  1502  2043 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 13:11:17.998  1502  2043 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:11:17.998  1502  2043 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:11:18.038  1694  4070 V BaseAuthAsyncOperation: access token request failed
,09-12 13:11:18.041  3274  4069 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 13:11:18.134  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 13:11:18.134  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 13:11:18.134  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 13:11:18.134  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:11:18.179  3274  4069 E KeepSync: IOException
09-12 13:11:18.179  3274  4069 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 13:11:18.179  3274  4069 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 13:11:18.179  3274  4069 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 13:11:18.179  3274  4069 E KeepSync: 	... 10 more
09-12 13:11:18.180  3274  4069 W KeepSync: Sync result 2
,09-12 13:11:18.204   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130354, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 13:11:18.987  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 13:11:18.987  4005  4056 I jxcore-log: 
,09-12 13:11:18.989  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 13:11:18.989  4005  4056 I jxcore-log: 
,09-12 13:11:18.999  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:18.999  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:18.999  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:18.999  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:18.999  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:18.999  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:18.999  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:18.999  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:19.009  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:19.012  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 13:11:19.012  4005  4056 I jxcore-log: 
,09-12 13:11:19.013  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 13:11:19.013  4005  4056 I jxcore-log: 
,09-12 13:11:19.511  4005  4056 D executeNativeTests: Running unit tests
,09-12 13:11:19.569  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:11:19.570  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 added. We now have 2 listener(s)
,09-12 13:11:19.571  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:11:19.571  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:11:19.571  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:11:19.571  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:11:19.571  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e added. We now have 2 listener(s)
,09-12 13:11:19.571  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:19.572  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:11:19.574  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:19.593  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:19.593  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:19.593  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:19.593  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:19.593  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:19.593  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:19.593  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:19.593  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:19.598  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:19.598  4005  4056 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:19.600  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:19.604  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:19.606  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 13:11:19.607  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:11:19.607  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:11:19.617  4005  4056 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 13:11:19.618  4005  4056 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-12 13:11:19.618  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-12 13:11:19.619  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 13:11:19.619  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-12 13:11:19.620  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,09-12 13:11:19.621  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:11:19.622  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:11:19.622  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:11:19.623  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:19.623  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:19.623  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:19.624  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 removed from the list
,09-12 13:11:19.624  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:19.624  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e removed from the list,
09-12 13:11:19.625  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:11:19.625  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,09-12 13:11:19.626  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:19.626  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-12 13:11:19.628  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:19.628  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:19.628  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:19.628  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.630  4005  4056 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 13:11:19.630  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:11:19.630  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.630  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:11:19.631  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.631  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.631  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.631  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.631  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:19.631  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.631  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.631  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.631  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.631  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.631  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-12 13:11:19.633  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.633  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.633  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.633  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.637  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:11:19.638  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-12 13:11:19.639  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:11:19.639  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.639  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.639  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.639  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.640  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:19.640  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.640  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.640  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.640  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.640  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:11:19.640  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.640  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.640  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.640  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:19.643  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.643  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.643  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.643  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.643  4005  4056 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:11:19.645  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:19.651  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:19.651  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:19.651  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:19.651  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:19.651  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:19.651  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:19.651  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:19.651  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:19.655  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:19.656  4005  4056 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:11:19.657  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:19.659  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:19.658  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:19.660  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:11:19.660  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:11:19.660  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:19.660  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:11:19.669  4005  4056 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted,
09-12 13:11:19.669  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:11:19.674  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,09-12 13:11:19.677  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:11:19.677  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:11:19.682  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-12 13:11:19.688  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-12 13:11:19.688  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:11:19.689  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:11:19.690  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:11:19.692  4005  4056 D BluetoothAdapter: STATE_ON
,09-12 13:11:19.704  2696  2708 D BtGatt.GattService: registerClient() - UUID=28a7e0d6-98a3-465b-8927-d6533a28a205
,09-12 13:11:19.705  2696  2732 D BtGatt.GattService: onClientRegistered() - UUID=28a7e0d6-98a3-465b-8927-d6533a28a205, clientIf=5
,09-12 13:11:19.706  4005  4052 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:11:19.709  2696  2861 D BtGatt.GattService: start scan with filters
,09-12 13:11:19.719  2696  2736 D BtGatt.ScanManager: handling starting scan
,09-12 13:11:19.725  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:11:19.726  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 13:11:19.727  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:11:19.727  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:11:19.730  2696  2736 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
09-12 13:11:19.732  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:19.733  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:11:19.734  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:11:19.737  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:11:19.742  2696  2732 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 13:11:19.743  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.744  2696  2736 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 13:11:19.747  4005  4056 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:11:19.755  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:11:19.755  4005  4056 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:11:19.755  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.755  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:11:19.755  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:19.755  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:19.756  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:11:19.756  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:11:19.756  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:11:19.756  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:11:19.757  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:11:19.757  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:11:19.758  4005  4056 D BluetoothAdapter: STATE_ON
09-12 13:11:19.758  2696  2732 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 13:11:19.758  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.759  2696  2861 D BtGatt.GattService: stopScan() - queue size =1
09-12 13:11:19.759  2696  2708 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:11:19.760  2696  2736 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:11:19.760  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:11:19.760  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:11:19.760  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:11:19.760  2696  2736 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 13:11:19.760  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:11:19.760  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:11:19.761  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:19.762  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:11:19.762  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:11:19.762  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:11:19.763  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:19.765  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:11:19.765  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:19.765  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:19.765  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.766  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.767  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:19.768  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.769  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.770  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.771  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.772  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.773  4005  4056 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 13:11:19.775  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:19.781  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:19.781  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:19.781  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:19.781  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:19.781  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:19.781  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:19.781  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:19.781  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:19.781  2696  2732 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:11:19.781  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:19.783  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:19.784  4005  4056 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:19.785  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:11:19.785  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 13:11:19.785  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 13:11:19.785  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:19.785  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:11:19.790  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:19.795  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:19.795  4005  4056 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 13:11:19.796  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:11:19.798  2696  2732 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 13:11:19.798  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:19.805  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:11:19.806  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:11:19.806  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:11:19.808  2696  2732 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 13:11:19.809  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.810  2696  2736 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:11:19.811  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:11:19.811  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 13:11:19.811  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:11:19.812  4005  4056 D BluetoothAdapter: STATE_ON
,09-12 13:11:19.816  2696  2708 D BtGatt.GattService: registerClient() - UUID=0cb90254-f8a6-4cd3-9200-278a0c90c695
,09-12 13:11:19.817  2696  2732 D BtGatt.GattService: onClientRegistered() - UUID=0cb90254-f8a6-4cd3-9200-278a0c90c695, clientIf=5
,09-12 13:11:19.817  4005  4052 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 13:11:19.818  2696  2861 D BtGatt.GattService: start scan with filters
,09-12 13:11:19.822  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:11:19.823  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:11:19.823  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:11:19.823  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:11:19.826  2696  2732 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 13:11:19.826  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:19.827  2696  2736 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 13:11:19.827  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:19.828  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:19.828  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:11:19.831  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:11:19.835  4005  4056 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:11:19.838  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:11:19.838  4005  4056 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:11:19.838  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.838  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:11:19.838  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.838  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:19.838  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 13:11:19.838  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:11:19.838  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:11:19.838  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:11:19.839  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:11:19.839  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 13:11:19.839  4005  4056 D BluetoothAdapter: STATE_ON
09-12 13:11:19.840  2696  2707 D BtGatt.GattService: stopScan() - queue size =0
,09-12 13:11:19.841  2696  2861 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:11:19.841  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:11:19.841  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 13:11:19.841  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:11:19.842  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:11:19.842  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:11:19.847  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:19.847  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:11:19.848  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-12 13:11:19.848  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:11:19.849  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:19.851  2696  2732 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
09-12 13:11:19.851  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.851  2696  2732 D BtGatt.GattService: current time is 132429737784
09-12 13:11:19.851  2696  2732 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -86, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 13:11:19.853  2696  2732 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-12 13:11:19.855  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:19.855  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:19.855  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:19.855  2696  2736 D BtGatt.ScanManager: handling starting scan
,09-12 13:11:19.855  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.855  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.855  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:19.855  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.856  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:19.856  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.856  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.856  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:19.856  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.856  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.859  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.859  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.859  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.859  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.860  4005  4056 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:11:19.863  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:19.863  2696  2732 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:11:19.863  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.863  2696  2736 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 13:11:19.868  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:19.868  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:19.868  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:19.868  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:19.868  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:19.868  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:19.868  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:19.868  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:19.870  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:19.870  4005  4056 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:19.871  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:11:19.871  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 13:11:19.871  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:11:19.871  2696  2732 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 13:11:19.871  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:19.871  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:19.872  2696  2736 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:11:19.872  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:11:19.872  2696  2736 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 13:11:19.873  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:19.876  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:19.876  4005  4056 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:11:19.876  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:11:19.882  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:11:19.883  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:11:19.883  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:11:19.886  2696  2732 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 13:11:19.886  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:19.889  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:11:19.889  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:11:19.889  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:11:19.890  4005  4056 D BluetoothAdapter: STATE_ON
09-12 13:11:19.893  2696  2708 D BtGatt.GattService: registerClient() - UUID=4fcdcb40-c11b-4fcc-9de2-53631b5ac914
09-12 13:11:19.894  2696  2732 D BtGatt.GattService: onClientRegistered() - UUID=4fcdcb40-c11b-4fcc-9de2-53631b5ac914, clientIf=5
09-12 13:11:19.894  2696  2732 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 13:11:19.894  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.894  4005  4052 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 13:11:19.894  2696  2861 D BtGatt.GattService: start scan with filters
,09-12 13:11:19.899  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:11:19.899  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:11:19.899  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:11:19.899  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:11:19.901  2696  2732 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 13:11:19.901  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:19.901  2696  2736 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:11:19.903  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:19.903  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:11:19.903  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:19.904  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:11:19.907  4005  4056 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:11:19.907  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.907  4005  4056 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 13:11:19.907  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.907  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:11:19.907  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:19.908  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:19.908  2696  2732 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:11:19.908  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 13:11:19.908  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.908  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:11:19.908  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:11:19.908  2696  2736 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 13:11:19.908  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:11:19.908  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:11:19.908  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 13:11:19.909  4005  4056 D BluetoothAdapter: STATE_ON
,09-12 13:11:19.909  2696  2707 D BtGatt.GattService: stopScan() - queue size =0
09-12 13:11:19.910  2696  2708 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 13:11:19.910  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:11:19.910  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:11:19.911  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:11:19.911  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 13:11:19.911  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:11:19.912  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:19.912  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:11:19.912  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 13:11:19.912  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:11:19.912  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:19.913  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:19.914  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:19.914  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:19.914  2696  2732 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:11:19.914  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.914  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.914  4005  4056 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:11:19.914  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.915  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.915  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.915  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.915  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:19.915  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.915  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.915  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.915  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.915  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.916  2696  2736 D BtGatt.ScanManager: handling starting scan
09-12 13:11:19.916  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.916  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.917  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.917  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.917  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.917  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
,09-12 13:11:19.917  4005  4056 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 13:11:19.918  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.918  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.918  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.918  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.918  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.919  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.919  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.919  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.919  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.919  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.919  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.919  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.919  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.919  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.920  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.920  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.920  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.921  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.921  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:11:19.922  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.922  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.922  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.922  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.922  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.922  2696  2732 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:11:19.922  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.922  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.922  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.922  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.922  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.922  2696  2736 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 13:11:19.923  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.923  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.923  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.923  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.923  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.924  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.924  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.924  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.924  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.925  4005  4056 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-12 13:11:19.925  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.925  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.925  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.925  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.925  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.925  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.925  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.925  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.926  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.926  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.926  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.926  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.926  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.926  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.927  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.927  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.927  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.927  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.928  4005  4056 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 13:11:19.928  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.928  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.928  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.928  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.928  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.928  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.928  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.928  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.929  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.929  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.929  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.929  2696  2732 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 13:11:19.929  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.929  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.929  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.929  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.929  2696  2736 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:11:19.930  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.930  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.930  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.930  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.930  2696  2736 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 13:11:19.931  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:11:19.931  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:11:19.931  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:11:19.931  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:11:19.931  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:11:19.931  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:11:19.931  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.931  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.931  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.932  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.932  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.932  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.932  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.932  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.932  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.933  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.933  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.933  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.933  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.933  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.934  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.934  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.934  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.934  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.935  4005  4056 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:11:19.935  4005  4056 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:11:19.936  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 13:11:19.941  2696  2732 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:11:19.941  4005  4056 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:11:19.941  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.942  4005  4056 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:11:19.942  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:11:19.943  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:11:19.944  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:11:19.944  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:11:19.944  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:11:19.944  4005  4056 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-12 13:11:19.944  4005  4056 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:11:19.944  4005  4056 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 13:11:19.944  4005  4056 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:11:19.944  4005  4056 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:11:19.945  4005  4056 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 13:11:19.945  4005  4056 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:11:19.945  4005  4056 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:11:19.945  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 13:11:19.947  2696  2732 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 13:11:19.947  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.951  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 13:11:19.952  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 13:11:19.952  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 13:11:19.952  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 13:11:19.952  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 13:11:19.953  4005  4056 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 13:11:19.953  4005  4056 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:11:19.953  4005  4056 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 13:11:19.953  4005  4071 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 430)
09-12 13:11:19.954  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.954  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.954  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.955  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.955  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.955  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.955  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 13:11:19.956  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.956  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.956  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.956  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.956  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.956  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.956  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.956  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.956  4005  4072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 430
09-12 13:11:19.957  2696  2732 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 13:11:19.957  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.957  2696  2736 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:11:19.958  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.958  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.958  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.958  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.959  4005  4056 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 13:11:19.959  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.959  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.959  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.960  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.960  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.960  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.960  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.960  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.960  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.960  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.960  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.960  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.960  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.960  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.961  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.961  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.961  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.961  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.962  4005  4071 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 430)
09-12 13:11:19.962  4005  4056 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 13:11:19.962  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.963  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.963  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.963  2696  2732 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:11:19.963  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.963  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.963  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.963  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.963  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.963  2696  2736 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 13:11:19.963  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.963  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.963  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.963  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.963  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.963  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.963  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.964  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.964  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.964  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.965  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.965  4005  4056 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 13:11:19.965  4005  4056 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 13:11:19.965  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:11:19.966  4005  4056 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 13:11:19.966  4005  4056 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:11:19.966  4005  4056 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 13:11:19.966  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:11:19.966  4005  4056 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 13:11:19.966  4005  4056 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:11:19.966  4005  4056 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:11:19.966  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:11:19.966  4005  4056 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 13:11:19.966  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.966  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.966  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.968  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.968  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.969  2696  2732 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:11:19.969  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.969  2696  2732 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:19.969  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.969  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.969  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.969  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.969  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.969  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.969  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.969  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.970  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.970  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.970  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.970  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.971  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.971  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.971  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.971  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.971  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.971  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.971  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.971  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.971  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.971  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.971  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.971  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.971  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.971  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.971  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.971  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.971  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.972  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.972  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.972  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.972  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.972  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.972  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.972  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.972  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.972  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.972  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.972  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.972  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.973  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.973  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.973  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.973  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.974  4005  4056 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:11:19.975  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:19.975  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 13:11:19.976  4005  4056 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:11:19.976  4005  4056 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:11:19.976  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:11:19.976  4005  4005 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:11:19.976  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:11:19.976  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.977  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:11:19.977  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:11:19.977  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:11:19.977  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.977  4005  4056 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:11:19.977  4005  4005 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:11:19.977  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.977  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.977  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:11:19.977  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:11:19.977  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:11:19.977  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.977  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.978  4005  4073 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:11:19.978  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:19.978  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.978  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.978  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:19.979  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.979  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:19.979  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.979  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:19.979  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.979  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.979  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.979  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.979  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.979  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.979  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.979  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.979  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.979  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.979  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.980  4005  4073 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 13:11:19.980  4005  4073 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:11:19.980  4005  4073 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 13:11:19.980  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.980  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.980  4005  4005 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:11:19.980  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.980  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.981  4005  4056 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 13:11:19.981  4005  4056 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:11:19.982  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:11:19.983  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:11:19.983  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.983  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.983  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.983  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.983  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.983  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.983  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.983  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.984  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.984  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.984  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.984  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.984  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.984  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.986  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.986  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.987  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.987  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.989  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.989  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.989  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.989  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.989  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.989  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.989  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.989  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.990  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.990  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.990  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.990  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.990  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.990  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.990  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:19.990  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.991  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.991  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.991  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:19.991  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:19.991  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:19.992  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:19.992  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.992  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.992  4005  4056 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c36e39 not in the list
09-12 13:11:19.992  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.992  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.992  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:19.992  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.992  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.992  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:19.992  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:19.993  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:19.993  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:19.993  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:19.993  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee17c7e not in the list
09-12 13:11:19.993  4005  4056 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 13:11:19.994  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:11:19.994  4005  4056 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 13:11:19.994  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:11:19.994  4005  4056 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 13:11:19.994  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:11:19.995  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:11:19.995  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 13:11:19.996  4005  4056 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 13:11:19.997  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:11:19.997  4005  4056 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 13:11:19.997  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:11:19.997  4005  4056 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 13:11:19.997  4005  4056 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 13:11:20.000  4005  4056 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 13:11:20.000  4005  4056 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 13:11:20.000  4005  4056 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 13:11:20.000  4005  4056 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 13:11:20.000  4005  4056 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 13:11:20.000  4005  4056 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 13:11:20.001  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:20.001  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b4e5f30 added. We now have 2 listener(s)
09-12 13:11:20.001  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:20.003  4005  4056 D BluetoothAdapter: enable(): BT is already enabled..!
09-12 13:11:20.003   874   885 D WifiService: setWifiEnabled: true pid=4005, uid=10000
09-12 13:11:20.003   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:11:20.004  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:20.004  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7f57a9 added. We now have 3 listener(s)
09-12 13:11:20.004  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:20.008  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:20.008  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8a4012e added. We now have 4 listener(s)
09-12 13:11:20.008  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:20.010  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:20.010  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc4b4cf added. We now have 5 listener(s)
09-12 13:11:20.010  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:20.011   874   884 D WifiService: setWifiEnabled: false pid=4005, uid=10000
09-12 13:11:20.011   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 13:11:20.014  2696  2728 D BluetoothAdapterState: Current state: ON, message: 23
09-12 13:11:20.014  2696  2728 D BluetoothAdapterProperties: Setting state to 13
09-12 13:11:20.014  2696  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 13:11:20.015  2696  2728 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 13:11:20.016  2696  2728 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:11:20.016  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:20.018  2696  2696 D BluetoothMapService: onReceive
09-12 13:11:20.018  2696  2696 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:20.018  2696  2696 D BluetoothMapService: STATE_TURNING_OFF
09-12 13:11:20.018  2696  2696 D BluetoothMapService: MAP Service closeService in
09-12 13:11:20.018  2696  2696 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 13:11:20.018  2696  2696 D ObexServerSockets0: shutdown(block = true)
09-12 13:11:20.019  2696  2696 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 13:11:20.019  2696  2696 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 13:11:20.019  2696  2870 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 13:11:20.019  2696  2847 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 13:11:20.019  2696  2871 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 13:11:20.019  2696  2696 I BtOppRfcommListener: stopping Accept Thread
09-12 13:11:20.019  2696  3604 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:11:20.019  2696  3604 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 13:11:20.021  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:20.021  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:20.021  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:20.021  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:20.021  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:20.021  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:20.021  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:20.021  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:20.021  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:11:20.021  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:20.021  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:20.022  4005  4056 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:11:20.023  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:20.024  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:20.026  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:20.026  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:20.026  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:20.026  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:20.026  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:20.026  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:20.026  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:20.026  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:20.026  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:11:20.027  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:20.027  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:20.028  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:20.029  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 13:11:20.030   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 13:11:20.031   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 13:11:20.031   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:11:20.031   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:11:20.037   874   887 I ActivityManager: Start proc 4078:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-12 13:11:20.038  2696  2732 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:11:20.038  2696  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 13:11:20.039  2696  2696 D HeadsetService: Received stop request...Stopping profile...
,09-12 13:11:20.042  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:20.043  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:20.046   874  2097 D DhcpClient: Clearing IP address
,09-12 13:11:20.046   874   874 D BluetoothHeadset: Proxy object disconnected
,09-12 13:11:20.046  1358  1396 D BluetoothHeadset: Proxy object disconnected
,09-12 13:11:20.046   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:11:20.046  1358  1358 D HeadsetProfile: Bluetooth service disconnected
,09-12 13:11:20.047  2696  2696 D A2dpService: Received stop request...Stopping profile...
,09-12 13:11:20.048  2696  2865 D A2dpStateMachine: Exit Disconnected: -1
,09-12 13:11:20.049  1358  1358 D BluetoothA2dp: Proxy object disconnected
,09-12 13:11:20.049  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:20.050  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:20.050  1987  2006 D BluetoothHeadset: Proxy object disconnected
09-12 13:11:20.050  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:20.050  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:20.050   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 13:11:20.050   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 13:11:20.050   372   872 D CommandListener: Setting iface cfg
09-12 13:11:20.050   874   874 D BluetoothA2dp: Proxy object disconnected
,09-12 13:11:20.051  2696  2696 D HidService: Received stop request...Stopping profile...
09-12 13:11:20.051  2696  2696 D HidService: Stopping Bluetooth HidService
09-12 13:11:20.054   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 13:11:20.054   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-12 13:11:20.054  1502  3618 V NativeCrypto: Read error: ssl=0x9a77f000: I/O error during system call, Connection timed out
09-12 13:11:20.055   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
09-12 13:11:20.055   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:11:20.055  2696  2696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 13:11:20.056  2696  2845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:11:20.056  2696  2845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:11:20.056  2696  2845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:11:20.056  2696  2732 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 13:11:20.056  2696  2732 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 13:11:20.056  2696  2696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:11:20.056   452   452 E Parcel  : Reading a NULL string not supported here.
09-12 13:11:20.057  1358  1358 D BluetoothInputDevice: Proxy object disconnected,
09-12 13:11:20.057  1358  1358 D HidProfile: Bluetooth service disconnected
09-12 13:11:20.057  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:20.057  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:20.057  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:20.057  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:20.057  1502  3618 V NativeCrypto: SSL shutdown failed: ssl=0x9a77f000: I/O error during system call, Broken pipe
09-12 13:11:20.059  2696  2696 D HealthService: Received stop request...Stopping profile...
09-12 13:11:20.062  2696  2845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:11:20.062  2696  2696 D PanService: Received stop request...Stopping profile...
,09-12 13:11:20.062  2696  2845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:11:20.062  2696  2845 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:11:20.063  2696  2845 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:11:20.062   372   872 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:11:20.063  2696  2845 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:11:20.063   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 13:11:20.063  2696  2845 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:11:20.063  2696  2732 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-12 13:11:20.063  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:11:20.063  1358  1358 D PanProfile: Bluetooth service disconnected
09-12 13:11:20.065  2696  2696 D BluetoothMapService: Received stop request...Stopping profile...
09-12 13:11:20.065  2696  2696 D BluetoothMapService: stop()
09-12 13:11:20.067  2696  2696 D BluetoothMapAppObserver: deinitObservers()
09-12 13:11:20.067  2696  2696 D BluetoothMapAppObserver: removeReceiver()
09-12 13:11:20.068  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:20.068  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:20.069  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:20.069  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:20.069  2696  2696 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 13:11:20.069  2696  2732 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 13:11:20.069  2696  2696 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 13:11:20.070  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:20.070  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:20.070  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:20.070  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:20.070  2696  2696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:11:20.070  2696  2732 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-12 13:11:20.071  2696  2696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:11:20.071  2696  2696 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:20.071  2696  2696 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:11:20.071  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:20.071  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:20.072  2696  2696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:11:20.072  2696  2696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:11:20.073  2696  2696 D BluetoothMapService: MAP Service closeService in
09-12 13:11:20.073  2696  2696 V BluetoothAdapterState: isTurningOff()=true
,09-12 13:11:20.073  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:20.073  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:20.073  2696  2696 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:20.073  2696  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 13:11:20.073  2696  2728 D BluetoothAdapterProperties: Setting state to 15
09-12 13:11:20.074  2696  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 13:11:20.074  1358  1377 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:11:20.074  2696  2696 D BluetoothMapService: cleanup()
,09-12 13:11:20.074  2696  2696 D BluetoothMapService: MAP Service closeService in
09-12 13:11:20.074  2696  2728 I BluetoothAdapterState: Entering BleOnState
09-12 13:11:20.075  1358  1381 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:11:20.075   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:11:20.075   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:11:20.075  1358  1396 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:11:20.076  1358  1377 D BluetoothMap: onBluetoothStateChange: up=false
09-12 13:11:20.076   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:11:20.076   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:11:20.077  1358  1381 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:11:20.077  1358  1396 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:11:20.077  1987  2421 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:11:20.078  2696  2728 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 13:11:20.078  2696  2728 D BluetoothAdapterProperties: Setting state to 16
09-12 13:11:20.078  2696  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 13:11:20.078  2696  2728 D BluetoothAdapterProperties: onBleDisable
09-12 13:11:20.078  2696  2728 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:11:20.079  2696  2732 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:11:20.079  2696  2729 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 13:11:20.082  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:20.082  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:20.082  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:20.082  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:20.082  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:20.082  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:20.082  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:20.082  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:20.082  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:20.083  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:20.083  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:20.084  2696  2845 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 13:11:20.084  2696  2845 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:11:20.085  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:20.085  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:20.085  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:20.085  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:20.085  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:20.085  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:20.085  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:20.085  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:20.085  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:20.086  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:20.086  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:20.087  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:20.088  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:20.088   874  2108 D DhcpClient: Receive thread stopped
,09-12 13:11:20.102   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:11:20.113  4078  4078 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 13:11:20.117   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:11:20.118   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 13:11:20.118   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:20.121   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:11:20.123   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:11:20.124   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-12 13:11:20.125  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:20.125  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:20.125  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:20.125  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:20.125  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:20.125  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:20.125  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:20.125  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:20.125  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:20.126  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:20.126  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:20.128  3595  3595 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f67c4e2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-12 13:11:20.128  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:20.128  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:20.128  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:20.128  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:20.128  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:20.128  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:20.128  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:20.128  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:20.128  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:20.129  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:20.129  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:20.130  1861  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:11:20.130  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:20.131  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:20.134  2068  2068 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-12 13:11:20.143  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:11:20.148  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:11:20.148   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d5dc608:true
,09-12 13:11:20.160   874  2035 I ActivityManager: Start proc 4099:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 13:11:20.165   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-12 13:11:20.166   874  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-12 13:11:20.190  4099  4099 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 13:11:20.192  4078  4078 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 13:11:20.194  4078  4078 D BluetoothMap: Create BluetoothMap proxy object
,09-12 13:11:20.202  4078  4078 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 13:11:20.216  4078  4078 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:11:20.221   874   884 I ActivityManager: Killing 3595:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 13:11:20.285  2696  2732 I bt_hci  : shut_down
,09-12 13:11:20.285  2696  2737 D bt_hwcfg: hw_epilog_process
,09-12 13:11:20.287  2696  2737 I bt_vendor: low_power_mode_cb
,09-12 13:11:20.309  2696  2737 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 13:11:20.310  2696  2737 I bt_vendor: epilog_cb
09-12 13:11:20.310  2696  2737 I bt_hci  : epilog_finished_callback
,09-12 13:11:20.337  2696  2732 I bt_hci_h4: hal_close
,09-12 13:11:20.338  2696  2732 I bt_userial_vendor: device fd = 51 close
,09-12 13:11:20.430  4099  4099 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:11:20.430  4099  4099 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:20.430  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:11:20.431  4099  4099 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:11:20.431  4099  4099 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:11:20.431  4099  4099 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:11:20.431  4099  4099 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:11:20.431  4099  4099 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:11:20.431  4099  4099 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 13:11:20.431  4099  4099 D StrictMode: ,	at java.io.File.lastModified(File.java:569)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48),
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
,09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 13:11:20.431  4099  4099 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 13:11:20.431  4099  4099 D StrictMode: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405),
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:20.431  4099  4099 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:11:20.443  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:11:20.455  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.,
09-12 13:11:20.456  4078  4078 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:11:20.464   874  1993 I ActivityManager: Killing 3769:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-12 13:11:20.480  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:11:20.506  2696  2729 D bt_stack_manager: event_shut_down_stack finished.,
,09-12 13:11:20.508  2696  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-12 13:11:20.510  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-12 13:11:20.512  1694  1694 D SystemUpdateService: onCreate
,09-12 13:11:20.513  2696  2728 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 13:11:20.513  2696  2696 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:11:20.515  2696  2696 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:11:20.515  2696  2696 D BtGatt.GattService: stop()
09-12 13:11:20.516  2696  2696 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 13:11:20.516  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:11:20.524  1694  4130 I SystemUpdateService: active receiver: enabled
,09-12 13:11:20.525  2696  2696 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:11:20.526  2696  2696 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:20.527  2696  2696 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:11:20.527  2696  2696 V BluetoothAdapterState: isBleTurningOff()=true
09-12 13:11:20.528  2696  2728 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 13:11:20.529  2696  2728 D BluetoothAdapterProperties: Setting state to 10
,09-12 13:11:20.529  2696  2728 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 13:11:20.529  1694  4130 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-12 13:11:20.529  2696  2728 I BluetoothAdapterState: Entering OffState
,09-12 13:11:20.539   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 13:11:20.540  1694  4130 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 13:11:20.540  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 13:11:20.542  1694  4130 I SystemUpdateService: now status is 0 (complete)
09-12 13:11:20.542  1694  4130 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 13:11:20.546  1694  2538 I iu.UploadsManager: num queued entries: 0
,09-12 13:11:20.546  1694  2538 I iu.UploadsManager: num updated entries: 0
09-12 13:11:20.547  1694  2538 I iu.SyncManager: NEXT; no task
,09-12 13:11:20.550  2696  2696 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 13:11:20.550  2696  2696 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 13:11:20.550  2696  2696 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 13:11:20.551  2696  2729 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 13:11:20.553  2696  2696 I art     : System.exit called, status: 0
,09-12 13:11:20.553  2696  2696 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:11:20.554  1694  4130 I SystemUpdateService: file has been verified
,09-12 13:11:20.555  1694  4130 I SystemUpdateService: OTA package size = 12249756
,09-12 13:11:20.571  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:11:20.572  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:11:20.579  1694  4130 I SystemUpdateService: showing system update notification
,09-12 13:11:20.619  4099  4118 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 13:11:20.628   874  2026 I ActivityManager: Start proc 4135:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 13:11:20.630   874  2036 I ActivityManager: Process com.android.bluetooth (pid 2696) has died
,09-12 13:11:20.633   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dceb6f:true
,09-12 13:11:20.694  1694  1694 D SystemUpdateService: onDestroy
,09-12 13:11:20.697  4135  4135 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 13:11:20.701  4135  4135 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:20.715  4135  4135 D SprintDMHelper: simOperator: 
,09-12 13:11:20.716  4135  4135 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:11:20.732   874  1882 I ActivityManager: Start proc 4148:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-12 13:11:20.835   874  2026 I ActivityManager: Start proc 4163:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 13:11:20.838  2887  4162 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-12 13:11:20.841   874  1983 I ActivityManager: Killing 2679:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 13:11:20.908  4163  4163 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 13:11:20.967  4163  4163 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 13:11:20.967  4163  4163 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 13:11:20.967  4163  4163 I GAv4    :   adb logcat -s GAv4
,09-12 13:11:20.982  4163  4163 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:11:20.990  4163  4163 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:11:21.016  4163  4180 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 13:11:21.134  4163  4163 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 13:11:21.175  4163  4163 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 13:11:21.183  4163  4163 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3759-3761)
,09-12 13:11:21.184  4163  4163 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 13:11:21.199  4163  4163 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4cf2a92}
,09-12 13:11:21.199  4163  4163 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:11:21.199  4163  4163 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 13:11:21.208  4163  4163 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 13:11:21.210  4163  4163 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 13:11:21.228  4163  4163 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 13:11:21.242  4163  4163 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:11:21.242  4163  4163 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 13:11:21.242  4163  4163 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 13:11:21.242  4163  4163 I Adreno  : Build Date                       : 10/20/15
09-12 13:11:21.242  4163  4163 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 13:11:21.242  4163  4163 I Adreno  : Local Branch                     : M14
09-12 13:11:21.242  4163  4163 I Adreno  : Remote Branch                    : 
09-12 13:11:21.242  4163  4163 I Adreno  : Remote Branch                    : 
09-12 13:11:21.242  4163  4163 I Adreno  : Reconstruct Branch               : 
,09-12 13:11:21.309  4163  4163 I NSApplication: Starting up...
,09-12 13:11:21.319  4163  4209 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 13:11:21.350   874  2026 I ActivityManager: Start proc 4214:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 13:11:21.353   874  2026 I ActivityManager: Killing 3699:android.process.acore/u0a5 (adj 15): empty #17
,09-12 13:11:21.432  4214  4214 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 13:11:21.617   874  1983 I ActivityManager: Killing 3856:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 13:11:21.722   874   885 I ActivityManager: Start proc 4228:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-12 13:11:21.798  4228  4228 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 13:11:21.854  4228  4228 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 13:11:21.913   874  1983 I ActivityManager: Killing 3873:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 13:11:23.024   874   885 D WifiService: setWifiEnabled: true pid=4005, uid=10000
,09-12 13:11:23.024   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:11:23.036   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:11:23.045  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:23.046  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:23.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:23.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:23.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:23.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:23.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:23.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:23.046  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:23.046  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:23.046  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:23.049  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:23.050  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:23.050  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:23.050  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:23.050  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:23.050  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:23.050  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:23.050  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:23.050  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:23.050  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:23.050  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:23.069   874  1316 D WifiConfigStore: loaded 0 passpoint configs
,09-12 13:11:23.070   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 13:11:23.071   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 13:11:23.071   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 13:11:23.072   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 13:11:23.072   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 13:11:23.072   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 13:11:23.096   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 13:11:23.097   372   872 D CommandListener: Setting iface cfg
,09-12 13:11:23.098   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-12 13:11:23.098   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 13:11:23.103   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.75 rxSuccessRate=21.88 delta 1000 -> 994
09-12 13:11:23.106   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 13:11:23.107   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 13:11:23.132   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 13:11:23.132   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:11:23.139   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 13:11:23.183   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 13:11:23.185  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 13:11:23.611  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 13:11:23.656  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 13:11:23.657  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 13:11:23.660   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:11:23.671   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:11:23.673   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 13:11:23.673   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-12 13:11:23.697   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:11:23.719   372   872 D CommandListener: Setting iface cfg
,09-12 13:11:23.721   874  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 13:11:23.737   874  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-12 13:11:23.740   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 13:11:23.752   874  4263 D DhcpClient: Receive thread started
,09-12 13:11:23.833   874  1316 E native  : do suspend false
,09-12 13:11:23.853   874  2097 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 13:11:23.867   874  4263 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172687, domain null
,09-12 13:11:23.868   874  2097 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172687 seconds
,09-12 13:11:23.875   874  2097 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 13:11:23.925   874  4263 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 13:11:23.927   874  2097 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 13:11:23.932   372   872 D CommandListener: Setting iface cfg
,09-12 13:11:23.944   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 13:11:23.944   874  2097 D DhcpClient: Scheduling renewal in 86399s
,09-12 13:11:23.958   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 13:11:23.961   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 13:11:23.962   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 13:11:23.963   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 13:11:23.967   874  1318 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 13:11:23.979   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 13:11:24.034   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 13:11:24.034   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 13:11:24.037   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 13:11:24.039   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 13:11:24.041   874  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 13:11:24.051   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 13:11:24.055   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 13:11:24.055   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-12 13:11:24.056   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-12 13:11:24.056   874  1318 D ConnectivityService:    accepting network in place of null
,09-12 13:11:24.056   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 13:11:24.057   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:11:24.057   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:11:24.098   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:11:24.129   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:11:24.137   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 13:11:24.138   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:24.149   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:11:24.154   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-12 13:11:24.158  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:24.158  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:24.158  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:24.158  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:24.158  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:24.158  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:24.158  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:24.158  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:24.158  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:11:24.158  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:24.158  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:24.161  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:24.161  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:24.161  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:24.161  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:24.161  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:24.161  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:24.161  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:24.161  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:24.161  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:11:24.161  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:24.161  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:24.172  2068  2068 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-12 13:11:24.175  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-12 13:11:24.178  1694  1694 D SystemUpdateService: onCreate
,09-12 13:11:24.182  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:11:24.186  1694  4273 I SystemUpdateService: active receiver: enabled
,09-12 13:11:24.188  1694  4273 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:11:24.191  1694  4273 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 13:11:24.191  1694  4273 I SystemUpdateService: now status is 0 (complete)
09-12 13:11:24.191  1694  4273 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 13:11:24.191  1694  4273 I SystemUpdateService: file has been verified
09-12 13:11:24.192  1694  4273 I SystemUpdateService: OTA package size = 12249756
,09-12 13:11:24.202  1694  4273 I SystemUpdateService: showing system update notification
,09-12 13:11:24.209  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 13:11:24.211  1694  2538 I iu.UploadsManager: num queued entries: 0
09-12 13:11:24.211  1694  2538 I iu.UploadsManager: num updated entries: 0
,09-12 13:11:24.214  1694  2538 I iu.SyncManager: NEXT; no task
,09-12 13:11:24.218  1694  4277 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 13:11:24.218  1694  4277 W BaseAppContext: Using Auth Proxy for data requests.
09-12 13:11:24.219  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:11:24.220  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:11:24.220  1694  4277 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 13:11:24.222  4135  4135 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:24.226  4135  4135 D SprintDMHelper: simOperator: 
,09-12 13:11:24.226  4135  4135 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-12 13:11:24.229  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:11:24.230  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 13:11:24.233  1694  1694 D SystemUpdateService: onDestroy
,09-12 13:11:24.259  1502  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-12 13:11:24.259  1502  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 13:11:24.259  1502  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:11:24.259  1502  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:11:24.280  1694  4277 E MDM     : [176] SitrepService.a: Error sending sitrep.
,09-12 13:11:25.137   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 13:11:26.030   874   885 D WifiService: setWifiEnabled: false pid=4005, uid=10000
,09-12 13:11:26.031   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:11:26.061  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 13:11:26.064   874  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 13:11:26.064   874  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 13:11:26.064   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:11:26.064   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:11:26.079   874  2097 D DhcpClient: Clearing IP address
,09-12 13:11:26.079   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:11:26.084   372   872 D CommandListener: Setting iface cfg
,09-12 13:11:26.097   874  4263 D DhcpClient: Receive thread stopped
,09-12 13:11:26.098   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 13:11:26.099   874  1316 D WifiStateMachine: Start Disconnecting Watchdog 2,
09-12 13:11:26.099   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-12 13:11:26.100   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 13:11:26.104   372   872 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:11:26.105   452   452 E Parcel  : Reading a NULL string not supported here.
,09-12 13:11:26.115   874  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-12 13:11:26.119   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:11:26.123  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:26.123  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:26.123  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:26.123  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:26.123  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:26.123  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:26.123  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:26.123  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:26.123  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:26.123  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:26.123  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:26.124  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:26.124  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:26.124  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:26.124  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:26.124  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:26.124  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:26.124  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,09-12 13:11:26.124  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:26.124  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:26.124  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:26.124  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:26.125   874  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 13:11:26.125  1861  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:11:26.147   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:11:26.176   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:11:26.176   874  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-12 13:11:26.177   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:26.178   874   891 D Tethering: MasterInitialState.processMessage what=3
,09-12 13:11:26.181  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:26.183  2068  2068 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-12 13:11:26.183  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:26.196  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:11:26.199  1694  1694 D SystemUpdateService: onCreate
,09-12 13:11:26.202  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:11:26.204  1694  4292 I SystemUpdateService: active receiver: enabled
,09-12 13:11:26.208  1694  4292 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:11:26.212  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 13:11:26.215  1694  2538 I iu.UploadsManager: num queued entries: 0
,09-12 13:11:26.215  1694  2538 I iu.UploadsManager: num updated entries: 0
,09-12 13:11:26.216  1694  2538 I iu.SyncManager: NEXT; no task
,09-12 13:11:26.221  1694  4292 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 13:11:26.221  1694  4292 I SystemUpdateService: now status is 0 (complete)
,09-12 13:11:26.222  1694  4292 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 13:11:26.222  1694  4292 I SystemUpdateService: file has been verified
,09-12 13:11:26.223  1694  4292 I SystemUpdateService: OTA package size = 12249756
,09-12 13:11:26.225  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:11:26.227  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:11:26.231  4135  4135 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:26.239  1694  4292 I SystemUpdateService: showing system update notification
,09-12 13:11:26.242  4135  4135 D SprintDMHelper: simOperator: 
,09-12 13:11:26.242  4135  4135 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:11:26.248   372   872 E Netd    : netlink response contains error (No such file or directory)
,09-12 13:11:26.288  1694  1694 D SystemUpdateService: onDestroy
,09-12 13:11:29.069   874  4261 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-12 13:11:29.071   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 13:11:29.091   874   891 I ActivityManager: Start proc 4298:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 13:11:29.248  4298  4298 D AdapterServiceConfig: Adding HeadsetService
,09-12 13:11:29.248  4298  4298 D AdapterServiceConfig: Adding A2dpService
09-12 13:11:29.248  4298  4298 D AdapterServiceConfig: Adding HidService
09-12 13:11:29.249  4298  4298 D AdapterServiceConfig: Adding HealthService
,09-12 13:11:29.249  4298  4298 D AdapterServiceConfig: Adding PanService
09-12 13:11:29.249  4298  4298 D AdapterServiceConfig: Adding GattService
09-12 13:11:29.249  4298  4298 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 13:11:29.252  2887  4279 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-12 13:11:29.252  2887  4279 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-12 13:11:29.253  2887  4279 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 13:11:29.258   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4c84b7a:true,
09-12 13:11:29.258  4298  4298 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 13:11:29.260  4298  4298 I bt_bluedroid: init
,09-12 13:11:29.260  4298  4311 I BluetoothAdapterState: Entering OffState
,09-12 13:11:29.262  4298  4312 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 13:11:29.262  4298  4312 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 13:11:29.262  4298  4312 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 13:11:29.262  4298  4312 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 13:11:29.262  4298  4298 I bt_bluedroid: get_profile_interface socket
,09-12 13:11:29.263  4298  4298 I bt_bluedroid: get_profile_interface sdp
,09-12 13:11:29.264  4298  4315 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-12 13:11:29.264  4298  4315 D BluetoothAdapterProperties: Name is: Nexus 6
09-12 13:11:29.266  4298  4309 I bt_bluedroid: config_hci_snoop_log
09-12 13:11:29.266   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-12 13:11:29.269  4298  4311 D BluetoothAdapterState: Current state: OFF, message: 0
09-12 13:11:29.269  4298  4311 D BluetoothAdapterProperties: Setting state to 14
09-12 13:11:29.269  4298  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-12 13:11:29.270  4298  4311 D BluetoothBondStateMachine: make
09-12 13:11:29.273  4298  4316 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 13:11:29.275  4298  4311 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:11:29.275  4298  4298 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 13:11:29.277  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
,09-12 13:11:29.277  4298  4298 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:11:29.278  4298  4298 D BtGatt.GattService: Received start request. Starting profile...
,09-12 13:11:29.278  4298  4298 D BtGatt.GattService: start()
09-12 13:11:29.278  4298  4298 I bt_bluedroid: get_profile_interface gatt
09-12 13:11:29.278  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
09-12 13:11:29.278  4298  4298 D BtGatt.AdvertiseManager: advertise manager created
09-12 13:11:29.282  4298  4298 V BluetoothAdapterState: isTurningOff()=false
09-12 13:11:29.282  4298  4298 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:29.282  4298  4298 V BluetoothAdapterState: isBleTurningOn()=true
,09-12 13:11:29.282  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:29.282  4298  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 13:11:29.282  4298  4311 I bt_bluedroid: enable
09-12 13:11:29.282  4298  4312 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 13:11:29.282  4298  4312 I bt_hci  : start_up
,09-12 13:11:29.286  4298  4312 I bt_vendor: alloc value 0xb3a62189
,09-12 13:11:29.286  4298  4312 I bt_vendor: init
09-12 13:11:29.286  4298  4312 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 13:11:29.286  4298  4312 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 13:11:29.334  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:11:29.343  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:11:29.345  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:11:29.362  1502  2065 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 13:11:29.362  1502  2065 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 13:11:29.362  1502  2065 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:11:29.362  1502  2065 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:11:29.374  3717  3717 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-12 13:11:29.374  3717  3717 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 13:11:29.375  3717  3717 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 13:11:29.392  4298  4312 D bt_hci  : start_up starting async portion
,09-12 13:11:29.393  4298  4319 I bt_hci  : event_finish_startup
09-12 13:11:29.393  4298  4319 I bt_hci_h4: hal_open
09-12 13:11:29.393   874   884 I ActivityManager: Killing 3625:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 13:11:29.393  4298  4319 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 13:11:29.397  4298  4319 I bt_userial_vendor: device fd = 51 open
,09-12 13:11:29.435  4298  4319 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:11:29.467  4298  4319 D bt_hwcfg: Chipset BCM4354A2
09-12 13:11:29.467  4298  4319 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 13:11:29.469  4298  4319 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 13:11:30.137  4298  4319 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 13:11:30.138  4298  4319 D bt_hwcfg: Settlement delay -- 100 ms
,09-12 13:11:30.139  4298  4319 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 13:11:30.255  4298  4319 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:11:30.257  4298  4319 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 13:11:30.286  4298  4319 I bt_hwcfg: vendor lib fwcfg completed
,09-12 13:11:30.286  4298  4319 I bt_vendor: firmware callback
,09-12 13:11:30.287  4298  4319 I bt_hci  : firmware_config_callback
,09-12 13:11:30.299  4298  4321 I bt_btu  : btu_task pending for preload complete event
,09-12 13:11:30.299  4298  4321 I bt_btu_task: Bluetooth chip preload is complete
,09-12 13:11:30.300  4298  4321 I bt_btu  : btu_task received preload complete event
,09-12 13:11:30.309  4298  4321 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 13:11:30.310  4298  4321 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 13:11:30.310  4298  4321 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 13:11:30.310  4298  4321 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 13:11:30.310  4298  4321 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 13:11:30.311  4298  4321 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 13:11:30.311  4298  4321 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 13:11:30.311  4298  4321 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:11:30.311  4298  4321 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 13:11:30.312  4298  4321 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:11:30.312  4298  4321 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:11:30.312  4298  4321 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:11:30.313  4298  4321 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:11:30.313  4298  4321 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:11:30.313  4298  4321 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 13:11:30.448  4298  4321 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39dfd9d
,09-12 13:11:30.448  4298  4321 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39dfd9d 
,09-12 13:11:30.460  4298  4315 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 13:11:30.461  4298  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 13:11:30.462  4298  4315 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-12 13:11:30.465  4298  4315 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:11:30.468  4298  4315 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:11:30.469  4298  4315 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:11:30.469  4298  4315 D bt_hci  : do_postload posting postload work item
09-12 13:11:30.469  4298  4319 I bt_hci  : event_postload
09-12 13:11:30.470  4298  4319 I bt_vendor: sco_config_cb
09-12 13:11:30.470  4298  4319 I bt_hci  : sco_config_callback postload finished.
09-12 13:11:30.472  4298  4315 D bt_bte_conf: Device ID record 1 : primary
,09-12 13:11:30.473  4298  4315 D bt_bte_conf:   vendorId            = 000f
,09-12 13:11:30.473  4298  4315 D bt_bte_conf:   vendorIdSource      = 0001
,09-12 13:11:30.473  4298  4315 D bt_bte_conf:   product             = 1200
,09-12 13:11:30.473  4298  4315 D bt_bte_conf:   version             = 1436
,09-12 13:11:30.473  4298  4315 D bt_bte_conf:   clientExecutableURL = 
,09-12 13:11:30.473  4298  4315 D bt_bte_conf:   serviceDescription  = 
09-12 13:11:30.474  4298  4315 D bt_bte_conf:   documentationURL    = 
,09-12 13:11:30.474  4298  4315 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 13:11:30.474  4298  4312 D bt_stack_manager: event_start_up_stack finished
09-12 13:11:30.477  4298  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3,
,09-12 13:11:30.477  4298  4311 D BluetoothAdapterProperties: Setting state to 15
09-12 13:11:30.476  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:30.478  4298  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-12 13:11:30.479  4298  4319 I bt_vendor: low_power_mode_cb
,09-12 13:11:30.481  4298  4311 I BluetoothAdapterState: Entering BleOnState
,09-12 13:11:30.482  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:30.486  4298  4311 D BluetoothAdapterState: Current state: BLE ON, message: 1,
09-12 13:11:30.486  4298  4311 D BluetoothAdapterProperties: Setting state to 11
09-12 13:11:30.486  4298  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-12 13:11:30.494  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:30.494  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
09-12 13:11:30.495  4298  4298 D HeadsetService: Received start request. Starting profile...
09-12 13:11:30.499  4298  4298 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 13:11:30.499  4298  4298 D HeadsetStateMachine: make
09-12 13:11:30.503  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:30.503  4298  4311 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:11:30.512  4298  4298 D HeadsetStateMachine: max_hf_connections = 1
09-12 13:11:30.512  4298  4298 I bt_bluedroid: get_profile_interface handsfree
09-12 13:11:30.513  4298  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 13:11:30.513  4298  4315 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-12 13:11:30.516  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
09-12 13:11:30.517  4298  4298 D A2dpService: Received start request. Starting profile...
09-12 13:11:30.517  4298  4298 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 13:11:30.518  4298  4298 I bt_bluedroid: get_profile_interface avrcp
,09-12 13:11:30.526  4298  4298 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:11:30.526  4298  4298 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 13:11:30.527  4298  4298 D A2dpStateMachine: make
,09-12 13:11:30.528  4298  4298 I bt_bluedroid: get_profile_interface a2dp
,09-12 13:11:30.528  4298  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 13:11:30.530  4298  4331 D A2dpStateMachine: Enter Disconnected: -2
09-12 13:11:30.530  4298  4298 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 13:11:30.531  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
09-12 13:11:30.532  4298  4298 D HidService: Received start request. Starting profile...
,09-12 13:11:30.532  4078  4078 D BluetoothInputDevice: Proxy object connected
09-12 13:11:30.532  4298  4298 I bt_bluedroid: get_profile_interface hidhost
09-12 13:11:30.532  4298  4315 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c13e5,
09-12 13:11:30.532  4298  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-12 13:11:30.533  4298  4298 D HidService: setHidService(): set to: null
,09-12 13:11:30.533  4078  4078 D HidProfile: Bluetooth service connected
09-12 13:11:30.533  4298  4298 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 13:11:30.534  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
,09-12 13:11:30.534  4298  4298 D HealthService: Received start request. Starting profile...
,09-12 13:11:30.536  4298  4298 I bt_bluedroid: get_profile_interface health
,09-12 13:11:30.536  4298  4298 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:11:30.537  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
,09-12 13:11:30.538  4298  4298 D PanService: Received start request. Starting profile...
,09-12 13:11:30.538  4298  4298 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 13:11:30.538  4298  4298 I bt_bluedroid: get_profile_interface pan
09-12 13:11:30.539  4298  4315 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 13:11:30.539  4078  4078 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:11:30.539  4078  4078 D PanProfile: Bluetooth service connected,
09-12 13:11:30.541  4298  4298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
,09-12 13:11:30.541  4298  4298 D BluetoothMapService: Received start request. Starting profile...
09-12 13:11:30.542  4298  4298 D BluetoothMapService: start()
09-12 13:11:30.542  4078  4078 D BluetoothMap: Proxy object connected
,09-12 13:11:30.542  4078  4078 D MapProfile: Bluetooth service connected
09-12 13:11:30.543  4078  4078 D BluetoothMap: getConnectedDevices()
09-12 13:11:30.543  4078  4078 D BluetoothMap: Bluetooth is Not enabled
09-12 13:11:30.543  4298  4298 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 13:11:30.544  4298  4298 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-12 13:11:30.544  4298  4298 D BluetoothMapAppObserver: createReceiver()
09-12 13:11:30.545  4298  4298 D BluetoothMapAppObserver: initObservers()
,09-12 13:11:30.545  4298  4298 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 13:11:30.553  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:11:30.555  4298  4298 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:11:30.555  4298  4298 V BluetoothAdapterState: isTurningOn()=true
09-12 13:11:30.555  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:30.555  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:30.556  4298  4298 V BluetoothAdapterState: isTurningOff()=false
09-12 13:11:30.556  4298  4298 V BluetoothAdapterState: isTurningOn()=true
09-12 13:11:30.556  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:30.556  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:30.556  4298  4298 V BluetoothAdapterState: isTurningOff()=false
09-12 13:11:30.556  4298  4298 V BluetoothAdapterState: isTurningOn()=true
09-12 13:11:30.556  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:11:30.556  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isTurningOff()=false,
09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isTurningOn()=true
09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isTurningOn()=true
09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:30.557  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:30.558  4298  4329 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:11:30.558  4298  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 13:11:30.558  4298  4311 D BluetoothAdapterProperties: ScanMode =  20
,09-12 13:11:30.558  4298  4311 D BluetoothAdapterProperties: State =  11
09-12 13:11:30.558  4298  4311 D BluetoothAdapterProperties: Setting state to 12
09-12 13:11:30.558  4298  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 13:11:30.559  1358  1377 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:11:30.560  4298  4311 I BluetoothAdapterState: Entering OnState
09-12 13:11:30.561  1358  1381 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 13:11:30.561  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:11:30.561  1358  1358 D PanProfile: Bluetooth service connected
09-12 13:11:30.561  4298  4315 D BluetoothAdapterProperties: Scan Mode:21
09-12 13:11:30.562  4298  4315 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 13:11:30.562  1358  1358 D BluetoothInputDevice: Proxy object connected
09-12 13:11:30.562  1358  1358 D HidProfile: Bluetooth service connected
09-12 13:11:30.563  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:30.563  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:30.563  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:30.563  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:30.563  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:30.563  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:30.563  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:30.563  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:30.564   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 13:11:30.564   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:11:30.565  4078  4091 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:11:30.565   874   874 D BluetoothA2dp: Proxy object connected
09-12 13:11:30.565  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:30.566  4078  4088 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:11:30.566  1358  1381 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:11:30.568  4078  4091 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:11:30.568  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:30.568  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:30.568  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:30.568  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:30.568  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:30.568  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:30.568  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:30.568  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:30.569  1358  1396 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:11:30.569  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:30.570  4298  4298 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:11:30.570  1358  1358 D BluetoothMap: Proxy object connected
09-12 13:11:30.570  1358  1358 D MapProfile: Bluetooth service connected
09-12 13:11:30.570   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:11:30.570  1358  1358 D BluetoothMap: getConnectedDevices()
09-12 13:11:30.571  4078  4088 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:11:30.571  4298  4298 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 13:11:30.571   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:11:30.571  1358  1396 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:11:30.572  4298  4298 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:11:30.572  1358  1358 D BluetoothA2dp: Proxy object connected
09-12 13:11:30.573  1358  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:11:30.573  4298  4298 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:11:30.573  1987  2073 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:11:30.574  4298  4298 D ObexServerSockets: Succeed to create listening sockets 
09-12 13:11:30.574   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 13:11:30.574  4298  4298 D ObexServerSockets0: startAccept()
09-12 13:11:30.574  4298  4298 D ObexServerSockets0: prepareForNewConnect()
09-12 13:11:30.577  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:30.577  4298  4298 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 13:11:30.577  4298  4298 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 13:11:30.577  4298  4298 D BluetoothMapService: onReceive
09-12 13:11:30.577  4298  4298 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:30.577  4298  4298 D BluetoothMapService: STATE_ON
,09-12 13:11:30.578  4298  4336 D ObexServerSockets0: Accepting socket connection...
09-12 13:11:30.578  4078  4078 D LocalBluetoothProfileManager: Adding local A2DP profile
09-12 13:11:30.578  4298  4337 D ObexServerSockets0: Accepting socket connection...
09-12 13:11:30.579  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:30.582  4078  4078 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-12 13:11:30.590  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:11:30.594  4078  4078 D BluetoothA2dp: Proxy object connected
,09-12 13:11:30.596  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:11:30.601  4078  4078 D DockEventReceiver: finishStartingService: stopping service
09-12 13:11:30.602  4298  4298 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:11:30.602  4298  4298 D ObexServerSockets0: prepareForNewConnect()
09-12 13:11:30.603  1358  1358 D BluetoothPbap: Proxy object connected
09-12 13:11:30.603  1358  1358 D PbapServerProfile: Bluetooth service connected
09-12 13:11:30.605  4078  4078 D BluetoothPbap: Proxy object connected
09-12 13:11:30.606  4078  4078 D PbapServerProfile: Bluetooth service connected
09-12 13:11:30.609  4298  4341 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:11:30.625  4298  4345 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:11:30.627  4298  4345 I BtOppRfcommListener: Accept thread started.
,09-12 13:11:30.665   874   874 D BluetoothHeadset: Proxy object connected
09-12 13:11:30.665  1358  1381 D BluetoothHeadset: Proxy object connected
09-12 13:11:30.665  1358  1358 D HeadsetProfile: Bluetooth service connected
09-12 13:11:30.666  1987  2421 D BluetoothHeadset: Proxy object connected
09-12 13:11:30.666   874   874 D BluetoothHeadset: Proxy object connected
09-12 13:11:30.666   874   874 D BluetoothHeadset: Proxy object connected
,09-12 13:11:30.672   874   891 D BluetoothHeadset: Proxy object connected
09-12 13:11:30.672   874   891 D BluetoothHeadset: Proxy object connected
,09-12 13:11:30.673  1358  1377 D BluetoothHeadset: Proxy object connected
,09-12 13:11:30.674  1358  1358 D HeadsetProfile: Bluetooth service connected
09-12 13:11:30.674  1987  2006 D BluetoothHeadset: Proxy object connected
,09-12 13:11:30.684  4078  4088 D BluetoothHeadset: Proxy object connected
,09-12 13:11:30.685  4078  4078 D HeadsetProfile: Bluetooth service connected
,09-12 13:11:32.049  4298  4311 D BluetoothAdapterState: Current state: ON, message: 23
09-12 13:11:32.049  4298  4311 D BluetoothAdapterProperties: Setting state to 13
09-12 13:11:32.049  4298  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
,09-12 13:11:32.051  4298  4311 D BluetoothAdapterProperties: onBluetoothDisable()
,09-12 13:11:32.054  4298  4311 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:11:32.060   874  1318 D ConnectivityService: handlePromptUnvalidated 101
09-12 13:11:32.063  4298  4298 D BluetoothMapService: onReceive
09-12 13:11:32.064  4298  4298 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:32.064  4298  4298 D BluetoothMapService: STATE_TURNING_OFF
,09-12 13:11:32.065  4298  4298 D BluetoothMapService: MAP Service closeService in
09-12 13:11:32.066  4298  4298 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 13:11:32.066  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:32.066  4298  4298 D ObexServerSockets0: shutdown(block = true)
,09-12 13:11:32.066  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:32.066  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:32.066  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:32.066  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:32.066  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:32.066  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:32.066  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:32.066  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:32.067  4298  4336 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 13:11:32.068  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:32.068  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:32.070  4298  4298 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 13:11:32.071  4298  4337 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 13:11:32.071  4298  4324 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 13:11:32.075  4298  4298 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 13:11:32.076  4298  4298 I BtOppRfcommListener: stopping Accept Thread
09-12 13:11:32.077  4298  4345 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:11:32.079  4298  4315 D BluetoothAdapterProperties: Scan Mode:20
09-12 13:11:32.079  4298  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 13:11:32.083  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:32.083  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:32.083  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:32.083  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:32.083  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:32.083  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:32.083  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:32.083  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:32.083  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:32.084  4298  4345 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 13:11:32.085  4005  4005 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:32.085  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:32.086  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:11:32.087  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:32.090  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:32.091  4298  4298 D HeadsetService: Received stop request...Stopping profile...
09-12 13:11:32.095   874   874 D BluetoothHeadset: Proxy object disconnected
,09-12 13:11:32.095  1358  1381 D BluetoothHeadset: Proxy object disconnected
,09-12 13:11:32.095  4298  4298 D A2dpService: Received stop request...Stopping profile...
09-12 13:11:32.096  4298  4331 D A2dpStateMachine: Exit Disconnected: -1
,09-12 13:11:32.096  1358  1358 D HeadsetProfile: Bluetooth service disconnected
09-12 13:11:32.097  1987  2000 D BluetoothHeadset: Proxy object disconnected
,09-12 13:11:32.097   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 13:11:32.099  4078  4088 D BluetoothHeadset: Proxy object disconnected
09-12 13:11:32.099   874   874 D BluetoothHeadset: Proxy object disconnected
09-12 13:11:32.099   874   874 D BluetoothA2dp: Proxy object disconnected
09-12 13:11:32.100  4298  4298 D HidService: Received stop request...Stopping profile...
09-12 13:11:32.100  4298  4298 D HidService: Stopping Bluetooth HidService
,09-12 13:11:32.102  4298  4298 D HealthService: Received stop request...Stopping profile...
09-12 13:11:32.104  4298  4298 D PanService: Received stop request...Stopping profile...
,09-12 13:11:32.105  4298  4298 D BluetoothMapService: Received stop request...Stopping profile...
09-12 13:11:32.105  4298  4298 D BluetoothMapService: stop()
09-12 13:11:32.105  4298  4298 D BluetoothMapAppObserver: deinitObservers()
09-12 13:11:32.106  4298  4298 D BluetoothMapAppObserver: removeReceiver()
,09-12 13:11:32.107  4078  4078 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:11:32.108  4078  4078 D BluetoothA2dp: Proxy object disconnected
09-12 13:11:32.108  4078  4078 D HeadsetProfile: Bluetooth service disconnected
09-12 13:11:32.108  4078  4078 D BluetoothInputDevice: Proxy object disconnected
,09-12 13:11:32.108  4078  4078 D HidProfile: Bluetooth service disconnected
09-12 13:11:32.109  4298  4298 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:32.109  4298  4298 V BluetoothAdapterState: isTurningOn()=false
,09-12 13:11:32.109  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:32.111  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:32.112  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:11:32.113  1358  1358 D BluetoothA2dp: Proxy object disconnected
09-12 13:11:32.114  1358  1358 D BluetoothInputDevice: Proxy object disconnected
09-12 13:11:32.113  4298  4298 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 13:11:32.114  1358  1358 D HidProfile: Bluetooth service disconnected
09-12 13:11:32.114  4298  4298 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:11:32.114  4298  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:11:32.114  4298  4298 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:32.114  4298  4298 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:32.114  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:32.114  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:32.114  4298  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 13:11:32.114  4298  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:11:32.115  4298  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:11:32.115  4298  4315 E bt_btif : btif_hf_upstreams_evt: Invalid index 30574
,09-12 13:11:32.115  1358  1358 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:11:32.116  1358  1358 D PanProfile: Bluetooth service disconnected
09-12 13:11:32.116  1358  1358 D BluetoothMap: Proxy object disconnected
09-12 13:11:32.116  1358  1358 D MapProfile: Bluetooth service disconnected
09-12 13:11:32.116  4298  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-12 13:11:32.116  4298  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:11:32.116  4298  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 13:11:32.116  4298  4298 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:32.116  4298  4321 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:11:32.116  4298  4298 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:32.116  4298  4321 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:11:32.116  4298  4321 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:11:32.116  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:11:32.116  4298  4321 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:11:32.116  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:32.117  4298  4298 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 13:11:32.118  4298  4315 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 13:11:32.118  4298  4298 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-12 13:11:32.118  4298  4298 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:32.118  4298  4298 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:32.119  4078  4078 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 13:11:32.119  4078  4078 D PanProfile: Bluetooth service disconnected
09-12 13:11:32.120  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:32.120  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:32.120  4078  4078 D BluetoothMap: Proxy object disconnected
09-12 13:11:32.120  4298  4298 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:11:32.120  4078  4078 D MapProfile: Bluetooth service disconnected
09-12 13:11:32.120  4298  4315 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 13:11:32.120  4298  4298 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:11:32.120  4298  4298 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:32.120  4298  4298 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:32.121  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:11:32.121  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:32.121  4298  4298 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:11:32.121  4298  4298 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:11:32.122  4298  4298 D BluetoothMapService: MAP Service closeService in
09-12 13:11:32.122  4298  4298 V BluetoothAdapterState: isTurningOff()=true
09-12 13:11:32.122  4298  4298 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:32.122  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:32.122  4298  4298 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:32.122  4298  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 13:11:32.122  4298  4311 D BluetoothAdapterProperties: Setting state to 15
09-12 13:11:32.122  4298  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 13:11:32.123  1358  1396 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:11:32.123  4298  4311 I BluetoothAdapterState: Entering BleOnState
09-12 13:11:32.123  1358  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:11:32.124   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:11:32.124   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:11:32.124  4298  4298 D BluetoothMapService: cleanup()
09-12 13:11:32.124  4298  4298 D BluetoothMapService: MAP Service closeService in
09-12 13:11:32.124  4078  4349 D BluetoothPan: onBluetoothStateChange on: false
09-12 13:11:32.125  4078  4088 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:11:32.126  1358  1358 D BluetoothPbap: Proxy object disconnected
09-12 13:11:32.126  1358  1358 D PbapServerProfile: Bluetooth service disconnected
09-12 13:11:32.127  4078  4349 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:11:32.128  1358  1381 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 13:11:32.129  4078  4091 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 13:11:32.130  1358  1396 D BluetoothMap: onBluetoothStateChange: up=false
09-12 13:11:32.130   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:11:32.130  4078  4088 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 13:11:32.131  4078  4349 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:11:32.131   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:11:32.131  1358  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:11:32.133  1358  1381 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 13:11:32.134  1987  2073 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 13:11:32.134  4298  4311 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-12 13:11:32.134  4298  4311 D BluetoothAdapterProperties: Setting state to 16
09-12 13:11:32.134  4298  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-12 13:11:32.135  4298  4311 D BluetoothAdapterProperties: onBleDisable
,09-12 13:11:32.135  4298  4311 I BluetoothAdapterState: Entering PendingCommandState
09-12 13:11:32.135  4298  4312 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-12 13:11:32.136  4298  4315 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:11:32.136  4298  4321 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 13:11:32.136  4298  4321 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 13:11:32.139  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:11:32.141  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:32.142  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:32.143  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:32.143  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:11:32.145  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:32.149  4078  4078 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:11:32.336  4298  4315 I bt_hci  : shut_down
,09-12 13:11:32.337  4298  4319 D bt_hwcfg: hw_epilog_process
,09-12 13:11:32.346  4298  4319 I bt_vendor: low_power_mode_cb
,09-12 13:11:32.369  4298  4319 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 13:11:32.369  4298  4319 I bt_vendor: epilog_cb
09-12 13:11:32.369  4298  4319 I bt_hci  : epilog_finished_callback
,09-12 13:11:32.377  4298  4315 I bt_hci_h4: hal_close
,09-12 13:11:32.379  4298  4315 I bt_userial_vendor: device fd = 51 close
,09-12 13:11:32.505  4298  4312 D bt_stack_manager: event_shut_down_stack finished.
09-12 13:11:32.506  4298  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 13:11:32.512  4298  4298 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:11:32.513  4298  4311 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 13:11:32.514  4298  4298 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:11:32.514  4298  4298 D BtGatt.GattService: stop()
09-12 13:11:32.514  4298  4298 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 13:11:32.519  4298  4298 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:11:32.519  4298  4298 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:32.519  4298  4298 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:32.520  4298  4298 V BluetoothAdapterState: isBleTurningOff()=true
09-12 13:11:32.521  4298  4311 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-12 13:11:32.521  4298  4311 D BluetoothAdapterProperties: Setting state to 10
09-12 13:11:32.522  4298  4311 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-12 13:11:32.523  4298  4311 I BluetoothAdapterState: Entering OffState
09-12 13:11:32.525   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 13:11:32.545  4298  4298 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 13:11:32.546  4298  4298 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 13:11:32.546  4298  4298 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 13:11:32.549  4298  4312 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 13:11:32.554  4298  4312 D bt_stack_manager: event_clean_up_stack finished.
,09-12 13:11:32.559  4298  4298 I art     : System.exit called, status: 0
,09-12 13:11:32.559  4298  4298 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:11:32.617   874  1983 I ActivityManager: Process com.android.bluetooth (pid 4298) has died
,09-12 13:11:35.046  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:11:35.046  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:37.535   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 13:11:37.545  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-12 13:11:37.556   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 13:11:37.556   874   894 I Adreno  : Build Date                       : 10/20/15
09-12 13:11:37.556   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 13:11:37.556   874   894 I Adreno  : Local Branch                     : M14
09-12 13:11:37.556   874   894 I Adreno  : Remote Branch                    : 
09-12 13:11:37.556   874   894 I Adreno  : Remote Branch                    : 
09-12 13:11:37.556   874   894 I Adreno  : Reconstruct Branch               : 
,09-12 13:11:37.596   279  1304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (194 us)
,09-12 13:11:38.053  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:38.054  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@74cc565 added. We now have 6 listener(s)
,09-12 13:11:38.054  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:38.058  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:11:38.058  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f3023a added. We now have 7 listener(s)
,09-12 13:11:38.059  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:38.060  4005  4056 I System.out: IsBluetoothEnabled
,09-12 13:11:38.075  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:38.119   874   891 I ActivityManager: Start proc 4359:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 13:11:38.190  4005  4005 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:11:38.190  4005  4005 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 13:11:38.240   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 13:11:38.252   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-12 13:11:38.255  4005  4005 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b39b604 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@501ceeb, 16908290=android.view.AbsSavedState$1@501ceeb}, android:focusedViewId=100}]}]
,09-12 13:11:38.255  4005  4005 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 13:11:38.255  4005  4005 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 13:11:38.255  4005  4005 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-12 13:11:38.258   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-12 13:11:38.260   279   279 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
09-12 13:11:38.260   279   279 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-12 13:11:38.301  4359  4359 D AdapterServiceConfig: Adding HeadsetService
,09-12 13:11:38.302  4359  4359 D AdapterServiceConfig: Adding A2dpService
09-12 13:11:38.302  4359  4359 D AdapterServiceConfig: Adding HidService
,09-12 13:11:38.302  4359  4359 D AdapterServiceConfig: Adding HealthService
09-12 13:11:38.302  4359  4359 D AdapterServiceConfig: Adding PanService
09-12 13:11:38.302  4359  4359 D AdapterServiceConfig: Adding GattService
,09-12 13:11:38.302  4359  4359 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 13:11:38.313   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a26fbf:true
,09-12 13:11:38.313  4359  4359 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 13:11:38.315  4359  4359 I bt_bluedroid: init
,09-12 13:11:38.315  4359  4371 I BluetoothAdapterState: Entering OffState
,09-12 13:11:38.316  4359  4372 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 13:11:38.316  4359  4372 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 13:11:38.316  4359  4372 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 13:11:38.317  4359  4372 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 13:11:38.317  4359  4359 I bt_bluedroid: get_profile_interface socket
,09-12 13:11:38.318  4359  4359 I bt_bluedroid: get_profile_interface sdp
,09-12 13:11:38.320  4359  4370 I bt_bluedroid: config_hci_snoop_log
,09-12 13:11:38.320  4359  4375 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 13:11:38.320   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 13:11:38.322  4359  4375 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 13:11:38.324  4359  4371 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 13:11:38.324  4359  4371 D BluetoothAdapterProperties: Setting state to 14
,09-12 13:11:38.324  4359  4371 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-12 13:11:38.325  4359  4371 D BluetoothBondStateMachine: make
,09-12 13:11:38.326  4359  4376 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 13:11:38.328  4359  4371 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:11:38.329  4359  4359 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 13:11:38.331  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
,09-12 13:11:38.332  4359  4359 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:11:38.332  4359  4359 D BtGatt.GattService: Received start request. Starting profile...
09-12 13:11:38.332  4359  4359 D BtGatt.GattService: start()
09-12 13:11:38.332  4359  4359 I bt_bluedroid: get_profile_interface gatt
,09-12 13:11:38.333  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
09-12 13:11:38.333  4359  4359 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:11:38.336  4359  4359 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:11:38.336  4359  4359 V BluetoothAdapterState: isTurningOn()=false
09-12 13:11:38.337  4359  4359 V BluetoothAdapterState: isBleTurningOn()=true
09-12 13:11:38.337  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:38.337  4359  4371 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 13:11:38.337  4359  4371 I bt_bluedroid: enable
09-12 13:11:38.337  4359  4372 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 13:11:38.337  4359  4372 I bt_hci  : start_up
,09-12 13:11:38.341  4359  4372 I bt_vendor: alloc value 0xb3a62189
,09-12 13:11:38.341  4359  4372 I bt_vendor: init
09-12 13:11:38.341  4359  4372 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 13:11:38.341  4359  4372 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 13:11:38.451  4359  4372 D bt_hci  : start_up starting async portion
,09-12 13:11:38.451  4359  4379 I bt_hci  : event_finish_startup
,09-12 13:11:38.452  4359  4379 I bt_hci_h4: hal_open
,09-12 13:11:38.452  4359  4379 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 13:11:38.460  4359  4379 I bt_userial_vendor: device fd = 51 open
,09-12 13:11:38.499   279   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 13:11:38.500  4359  4379 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-12 13:11:38.501   279   279 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-12 13:11:38.502   874  1340 D SurfaceControl: Excessive delay in setPowerMode(): 244ms
09-12 13:11:38.505   874   894 I DreamManagerService: Entering dreamland.
09-12 13:11:38.506   874   894 I PowerManagerService: Dozing...
,09-12 13:11:38.507   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 13:11:38.524  4359  4379 D bt_hwcfg: Chipset BCM4354A2
,09-12 13:11:38.524  4359  4379 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 13:11:38.526  4359  4379 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd,
,09-12 13:11:38.567   376  1324 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-12 13:11:38.567   376  1324 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 13:11:38.580   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:11:38.587   874  1316 E native  : do suspend false
,09-12 13:11:38.596  1970  4382 D NfcService: Discovery configuration equal, not updating.
,09-12 13:11:38.618   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:11:38.622   874  1316 E native  : do suspend true
,09-12 13:11:38.701   376  4018 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-12 13:11:38.702   376  4018 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 13:11:39.170  4359  4379 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-12 13:11:39.171  4359  4379 D bt_hwcfg: Settlement delay -- 100 ms
,09-12 13:11:39.172  4359  4379 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 13:11:39.288  4359  4379 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 13:11:39.290  4359  4379 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 13:11:39.319  4359  4379 I bt_hwcfg: vendor lib fwcfg completed
,09-12 13:11:39.319  4359  4379 I bt_vendor: firmware callback
,09-12 13:11:39.320  4359  4379 I bt_hci  : firmware_config_callback
,09-12 13:11:39.331  4359  4388 I bt_btu  : btu_task pending for preload complete event
,09-12 13:11:39.331  4359  4388 I bt_btu_task: Bluetooth chip preload is complete
,09-12 13:11:39.331  4359  4388 I bt_btu  : btu_task received preload complete event
,09-12 13:11:39.344  4359  4388 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 13:11:39.344  4359  4388 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 13:11:39.344  4359  4388 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 13:11:39.345  4359  4388 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-12 13:11:39.345  4359  4388 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 13:11:39.345  4359  4388 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 13:11:39.346  4359  4388 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 13:11:39.346  4359  4388 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 13:11:39.346  4359  4388 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 13:11:39.346  4359  4388 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:11:39.347  4359  4388 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 13:11:39.347  4359  4388 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:11:39.347  4359  4388 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:11:39.347  4359  4388 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:11:39.348  4359  4388 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 13:11:39.482  4359  4388 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39dfd9d
09-12 13:11:39.482  4359  4388 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39dfd9d 
,09-12 13:11:39.492  4359  4375 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 13:11:39.493  4359  4375 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000,
,09-12 13:11:39.494  4359  4375 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61,
,09-12 13:11:39.497  4359  4375 D BluetoothAdapterProperties: Name is: Nexus 6,
,09-12 13:11:39.504  4359  4375 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:11:39.505  4359  4375 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:11:39.507  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:39.507  4359  4375 D bt_hci  : do_postload posting postload work item
09-12 13:11:39.508  4359  4379 I bt_hci  : event_postload
09-12 13:11:39.508  4359  4379 I bt_vendor: sco_config_cb
09-12 13:11:39.508  4359  4379 I bt_hci  : sco_config_callback postload finished.
,09-12 13:11:39.513  4359  4379 I bt_vendor: low_power_mode_cb
09-12 13:11:39.513  4359  4375 D bt_bte_conf: Device ID record 1 : primary
,09-12 13:11:39.513  4359  4375 D bt_bte_conf:   vendorId            = 000f
09-12 13:11:39.514  4359  4375 D bt_bte_conf:   vendorIdSource      = 0001
09-12 13:11:39.514  4359  4375 D bt_bte_conf:   product             = 1200
09-12 13:11:39.514  4359  4375 D bt_bte_conf:   version             = 1436
,09-12 13:11:39.515  4359  4375 D bt_bte_conf:   clientExecutableURL = 
,09-12 13:11:39.515  4359  4375 D bt_bte_conf:   serviceDescription  = 
09-12 13:11:39.515  4359  4375 D bt_bte_conf:   documentationURL    = 
09-12 13:11:39.515  4359  4375 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-12 13:11:39.516  4359  4372 D bt_stack_manager: event_start_up_stack finished
09-12 13:11:39.517  4359  4371 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 13:11:39.517  4359  4371 D BluetoothAdapterProperties: Setting state to 15
09-12 13:11:39.517  4359  4371 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 13:11:39.518  4359  4371 I BluetoothAdapterState: Entering BleOnState
09-12 13:11:39.522  4359  4371 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 13:11:39.522  4359  4371 D BluetoothAdapterProperties: Setting state to 11
09-12 13:11:39.522  4359  4371 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-12 13:11:39.526  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
,09-12 13:11:39.527  4359  4359 D HeadsetService: Received start request. Starting profile...
,09-12 13:11:39.530  4359  4359 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 13:11:39.531  4359  4359 D HeadsetStateMachine: make
,09-12 13:11:39.546  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:39.548  4359  4371 I BluetoothAdapterState: Entering PendingCommandState
,09-12 13:11:39.549  4359  4359 D HeadsetStateMachine: max_hf_connections = 1
,09-12 13:11:39.549  4359  4359 I bt_bluedroid: get_profile_interface handsfree
09-12 13:11:39.550  4359  4375 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 13:11:39.550  4359  4375 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 13:11:39.553  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
09-12 13:11:39.553  4359  4359 D A2dpService: Received start request. Starting profile...
,09-12 13:11:39.554  4359  4359 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 13:11:39.554  4359  4359 I bt_bluedroid: get_profile_interface avrcp
,09-12 13:11:39.561  4359  4359 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:11:39.561  4359  4359 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 13:11:39.561  4359  4359 D A2dpStateMachine: make
,09-12 13:11:39.563  4359  4359 I bt_bluedroid: get_profile_interface a2dp
,09-12 13:11:39.564  4359  4375 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 13:11:39.565  4359  4397 D A2dpStateMachine: Enter Disconnected: -2
,09-12 13:11:39.566  4359  4359 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 13:11:39.567  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
09-12 13:11:39.568  4359  4359 D HidService: Received start request. Starting profile...
,09-12 13:11:39.568  4359  4359 I bt_bluedroid: get_profile_interface hidhost
09-12 13:11:39.568  4359  4359 D HidService: setHidService(): set to: null
09-12 13:11:39.568  4359  4375 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39c13e5
,09-12 13:11:39.568  4359  4375 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 13:11:39.570  4359  4359 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 13:11:39.570  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
,09-12 13:11:39.571  4359  4359 D HealthService: Received start request. Starting profile...
,09-12 13:11:39.572  4359  4359 I bt_bluedroid: get_profile_interface health
,09-12 13:11:39.573  4359  4359 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:11:39.574  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
,09-12 13:11:39.575  4359  4359 D PanService: Received start request. Starting profile...
,09-12 13:11:39.575  4359  4359 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 13:11:39.575  4359  4359 I bt_bluedroid: get_profile_interface pan
09-12 13:11:39.575  4359  4375 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 13:11:39.579  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 13:11:39.580  4359  4359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
09-12 13:11:39.581  4359  4359 D BluetoothMapService: Received start request. Starting profile...
,09-12 13:11:39.581  4359  4359 D BluetoothMapService: start()
,09-12 13:11:39.583  4359  4359 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 13:11:39.585  4359  4359 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-12 13:11:39.585  4359  4359 D BluetoothMapAppObserver: createReceiver()
,09-12 13:11:39.586  4359  4359 D BluetoothMapAppObserver: initObservers()
,09-12 13:11:39.586  4359  4359 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 13:11:39.592  4359  4359 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:11:39.592  4359  4359 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:11:39.592  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:39.592  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:39.594  4359  4394 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isTurningOff()=false
09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isTurningOff()=false
09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isTurningOn()=true
09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isTurningOff()=false
,09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:39.595  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:39.596  4359  4359 V BluetoothAdapterState: isTurningOff()=false
09-12 13:11:39.596  4359  4359 V BluetoothAdapterState: isTurningOn()=true
09-12 13:11:39.596  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 13:11:39.596  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
09-12 13:11:39.598  4359  4359 V BluetoothAdapterState: isTurningOff()=false
09-12 13:11:39.598  4359  4359 V BluetoothAdapterState: isTurningOn()=true
,09-12 13:11:39.598  4359  4359 V BluetoothAdapterState: isBleTurningOn()=false
09-12 13:11:39.598  4359  4359 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 13:11:39.598  4359  4371 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-12 13:11:39.598  4359  4371 D BluetoothAdapterProperties: ScanMode =  20
,09-12 13:11:39.599  4359  4371 D BluetoothAdapterProperties: State =  11
09-12 13:11:39.599  4359  4371 D BluetoothAdapterProperties: Setting state to 12
,09-12 13:11:39.599  4359  4371 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 13:11:39.600  1358  1381 D BluetoothPan: onBluetoothStateChange on: true
,09-12 13:11:39.600  4359  4371 I BluetoothAdapterState: Entering OnState
,09-12 13:11:39.601  4359  4375 D BluetoothAdapterProperties: Scan Mode:21
,09-12 13:11:39.601  4359  4375 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 13:11:39.602  1358  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:11:39.603  1358  1358 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:11:39.604  1358  1358 D PanProfile: Bluetooth service connected
09-12 13:11:39.604   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:11:39.604   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:11:39.605  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:39.605  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:39.605  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:39.605  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:39.605  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:39.605  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:39.605  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:39.605  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:39.605  1358  1358 D BluetoothInputDevice: Proxy object connected
09-12 13:11:39.605  1358  1358 D HidProfile: Bluetooth service connected
09-12 13:11:39.607   874   874 D BluetoothA2dp: Proxy object connected
09-12 13:11:39.607  4078  4349 D BluetoothPan: onBluetoothStateChange on: true
09-12 13:11:39.607  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:39.609  4078  4088 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:11:39.609  4078  4078 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:11:39.609  4078  4078 D PanProfile: Bluetooth service connected
09-12 13:11:39.610  4078  4349 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 13:11:39.611  4359  4359 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:11:39.611  4078  4078 D BluetoothA2dp: Proxy object connected
09-12 13:11:39.611  1358  1396 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:11:39.612  4359  4359 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-12 13:11:39.613  4078  4088 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 13:11:39.613  4359  4359 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:11:39.615  4359  4359 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:11:39.616  1358  1377 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:11:39.616  4078  4078 D BluetoothInputDevice: Proxy object connected
09-12 13:11:39.616  4078  4078 D HidProfile: Bluetooth service connected
09-12 13:11:39.616  4359  4359 D ObexServerSockets: Succeed to create listening sockets 
09-12 13:11:39.616  4359  4359 D ObexServerSockets0: startAccept()
09-12 13:11:39.616  4359  4359 D ObexServerSockets0: prepareForNewConnect()
09-12 13:11:39.617   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:11:39.617  4078  4091 D BluetoothMap: onBluetoothStateChange: up=true
09-12 13:11:39.618  4359  4359 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 13:11:39.619  4359  4359 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 13:11:39.619  4078  4349 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:11:39.620   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:11:39.621  4359  4404 D ObexServerSockets0: Accepting socket connection...
09-12 13:11:39.621  1358  1396 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:11:39.621  4359  4403 D ObexServerSockets0: Accepting socket connection...
09-12 13:11:39.621  1358  1358 D BluetoothMap: Proxy object connected
09-12 13:11:39.621  1358  1358 D MapProfile: Bluetooth service connected
09-12 13:11:39.621  1358  1358 D BluetoothMap: getConnectedDevices()
09-12 13:11:39.621  4078  4078 D BluetoothMap: Proxy object connected
09-12 13:11:39.621  4078  4078 D MapProfile: Bluetooth service connected
09-12 13:11:39.621  4078  4078 D BluetoothMap: getConnectedDevices()
09-12 13:11:39.623  1358  1358 D BluetoothA2dp: Proxy object connected
09-12 13:11:39.624  1358  1381 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:11:39.624  1987  2000 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 13:11:39.626   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 13:11:39.628  4359  4359 D BluetoothMapService: onReceive
09-12 13:11:39.628  4359  4359 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:39.628  4359  4359 D BluetoothMapService: STATE_ON
09-12 13:11:39.629  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:39.633  4078  4078 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:11:39.641  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 13:11:39.643  4078  4078 D DockEventReceiver: finishStartingService: stopping service
09-12 13:11:39.649  4078  4078 D BluetoothPbap: Proxy object connected
09-12 13:11:39.649  4078  4078 D PbapServerProfile: Bluetooth service connected
,09-12 13:11:39.652  1358  1358 D BluetoothPbap: Proxy object connected
09-12 13:11:39.652  1358  1358 D PbapServerProfile: Bluetooth service connected
09-12 13:11:39.656  4359  4359 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 13:11:39.656  4359  4359 D ObexServerSockets0: prepareForNewConnect()
09-12 13:11:39.658  4359  4409 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:11:39.674  4359  4413 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:11:39.675  4359  4413 I BtOppRfcommListener: Accept thread started.
,09-12 13:11:39.705   874   874 D BluetoothHeadset: Proxy object connected
,09-12 13:11:39.706  1358  1396 D BluetoothHeadset: Proxy object connected
,09-12 13:11:39.706  1358  1358 D HeadsetProfile: Bluetooth service connected
09-12 13:11:39.706  1987  2073 D BluetoothHeadset: Proxy object connected
,09-12 13:11:39.707   874   874 D BluetoothHeadset: Proxy object connected
,09-12 13:11:39.707  4078  4349 D BluetoothHeadset: Proxy object connected
,09-12 13:11:39.708  4078  4078 D HeadsetProfile: Bluetooth service connected
,09-12 13:11:39.708   874   874 D BluetoothHeadset: Proxy object connected
,09-12 13:11:39.717   874   891 D BluetoothHeadset: Proxy object connected
,09-12 13:11:39.720  4078  4088 D BluetoothHeadset: Proxy object connected
,09-12 13:11:39.720  4078  4078 D HeadsetProfile: Bluetooth service connected
09-12 13:11:39.720   874   891 D BluetoothHeadset: Proxy object connected
,09-12 13:11:39.725  1358  1377 D BluetoothHeadset: Proxy object connected
,09-12 13:11:39.726  1358  1358 D HeadsetProfile: Bluetooth service connected
,09-12 13:11:39.726  1987  2421 D BluetoothHeadset: Proxy object connected
,09-12 13:11:40.098  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:40.098  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:40.098  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:40.098  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:40.098  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:40.098  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:40.098  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:40.098  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:40.105  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:40.108  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:11:40.108  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@392e448 added. We now have 8 listener(s)
09-12 13:11:40.109  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:40.114   874   885 D WifiService: setWifiEnabled: false pid=4005, uid=10000
09-12 13:11:40.114   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:11:40.127  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:40.128   874  2019 D WifiService: setWifiEnabled: true pid=4005, uid=10000
09-12 13:11:40.128   874  2019 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 13:11:40.139   874  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:11:40.156  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:40.156  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:40.156  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:40.156  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:40.156  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:40.156  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:40.156  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:40.156  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:40.162  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:40.167   874  1316 D WifiConfigStore: loaded 0 passpoint configs
09-12 13:11:40.169   874  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-12 13:11:40.169   874  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-12 13:11:40.170   874  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 13:11:40.171   874  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 13:11:40.171   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 13:11:40.171   874  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 13:11:40.184   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 13:11:40.184   874  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.09 delta 1000 -> 1000
09-12 13:11:40.184   874  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 13:11:40.185   372   872 D CommandListener: Setting iface cfg
09-12 13:11:40.185   874  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-12 13:11:40.185   874  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-12 13:11:40.198   874  1316 E native  : do suspend true
09-12 13:11:40.198   874  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 13:11:40.199   874  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 13:11:40.213   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 13:11:40.213   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:11:40.222   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 13:11:40.279   874  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 13:11:40.284  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 13:11:40.724  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 13:11:40.769  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 13:11:40.770  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 13:11:40.778   874  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 13:11:40.797   874  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:11:40.797   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 13:11:40.797   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 13:11:40.820   874  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:11:40.829   372   872 D CommandListener: Setting iface cfg
,09-12 13:11:40.830   874  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 13:11:40.844   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 13:11:40.903   874  4421 D DhcpClient: Receive thread started
,09-12 13:11:40.992   874  1316 E native  : do suspend false
,09-12 13:11:41.012   874  2097 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 13:11:41.033   874  4421 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-12 13:11:41.034   874  2097 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-12 13:11:41.041   874  2097 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 13:11:41.054   874  4421 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 13:11:41.056   874  2097 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 13:11:41.062   372   872 D CommandListener: Setting iface cfg
,09-12 13:11:41.073   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 13:11:41.074   874  2097 D DhcpClient: Scheduling renewal in 86399s
,09-12 13:11:41.076   874  1316 E native  : do suspend true
,09-12 13:11:41.099   874  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 13:11:41.102   874  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 13:11:41.104   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 13:11:41.106   874  1318 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 13:11:41.110   874  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 13:11:41.142  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:41.142  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:41.142  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:41.142  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:41.142  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:41.142  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:41.142  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:41.142  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:41.146  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:41.149  4005  4056 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 13:11:41.150  4005  4056 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 13:11:41.152   874  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 13:11:41.152  4005  4056 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b39b604 Bundle[{}]
,09-12 13:11:41.152   874  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-12 13:11:41.152  4005  4056 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 13:11:41.153  4005  4056 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 13:11:41.153  4005  4056 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 13:11:41.154  4005  4056 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 13:11:41.154  4005  4056 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-12 13:11:41.155  4005  4056 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:11:41.155   874  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 13:11:41.157   874  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 13:11:41.160   874  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 13:11:41.162  4005  4056 I System.out: Running OutgoingSocketThread
,09-12 13:11:41.168  4005  4424 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 460)
09-12 13:11:41.169  4005  4424 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38791
09-12 13:11:41.169  4005  4424 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 13:11:41.173   874  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 13:11:41.184   874  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-12 13:11:41.184   874  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 13:11:41.184   874  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-12 13:11:41.184   874  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-12 13:11:41.184   874  1318 D ConnectivityService:    accepting network in place of null
,09-12 13:11:41.185   874  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 13:11:41.185   874  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 13:11:41.201   874  4420 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153779, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 13:11:41.213   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:11:41.260   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 13:11:41.265   874  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-12 13:11:41.265   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 13:11:41.267   874  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 13:11:41.274   874   891 D Tethering: MasterInitialState.processMessage what=3
09-12 13:11:41.278   874  4419 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 13:11:41.289  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:41.289  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:41.289  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:41.289  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:41.289  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:41.289  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:41.289  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:41.289  4005  4005 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:41.292  4005  4005 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:41.293  2068  2068 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-12 13:11:41.302  1694  1694 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 13:11:41.309  1694  1694 D SystemUpdateService: onCreate
,09-12 13:11:41.312  1694  1694 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 13:11:41.330  1694  4431 I SystemUpdateService: active receiver: enabled
,09-12 13:11:41.334  1694  1694 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 13:11:41.342  1694  2538 I iu.UploadsManager: num queued entries: 0
,09-12 13:11:41.342  1694  2538 I iu.UploadsManager: num updated entries: 0
09-12 13:11:41.343  1694  2538 I iu.SyncManager: NEXT; no task
,09-12 13:11:41.346  1694  4431 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 13:11:41.349  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 13:11:41.350  1694  1694 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 13:11:41.350   874  4419 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:11:41 GMT], X-Android-Received-Millis=[1473678701350], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473678701323]}
,09-12 13:11:41.352  4135  4135 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-12 13:11:41.353   874  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 13:11:41.353   874  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-12 13:11:41.354   874  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 13:11:41.355   874  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-12 13:11:41.360  1694  4434 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-12 13:11:41.360  1694  4434 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 13:11:41.362  4135  4135 D SprintDMHelper: simOperator: 
09-12 13:11:41.362  4135  4135 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 13:11:41.366  1694  4434 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 13:11:41.379  1694  4431 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 13:11:41.379  1694  4431 I SystemUpdateService: now status is 0 (complete)
09-12 13:11:41.379  1694  4431 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 13:11:41.379  1694  4431 I SystemUpdateService: file has been verified
09-12 13:11:41.380  1694  4431 I SystemUpdateService: OTA package size = 12249756
,09-12 13:11:41.394  1694  4431 I SystemUpdateService: showing system update notification
,09-12 13:11:41.399  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:11:41.404  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 13:11:41.433  1694  1694 D SystemUpdateService: onDestroy
,09-12 13:11:41.445  1502  2074 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 13:11:41.445  1502  2074 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 13:11:41.446  1502  2074 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 13:11:41.446  1502  2074 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 13:11:41.463  1694  4434 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-12 13:11:41.482  2887  4437 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 13:11:42.169  4005  4056 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 461)
,09-12 13:11:42.170  4005  4056 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 461)
,09-12 13:11:42.179  4005  4056 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 466)
,09-12 13:11:42.182  4005  4056 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-12 13:11:42.182  4005  4056 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 467)
,09-12 13:11:42.187  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:11:42.187  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec952e1 added. We now have 2 listener(s)
,09-12 13:11:42.189  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:11:42.189  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:11:42.189  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:11:42.190  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:42.190  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dff0806 added. We now have 9 listener(s)
,09-12 13:11:42.190  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:42.191  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:11:42.194  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:42.203  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:42.203  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:42.203  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:42.203  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:42.203  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:42.203  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:42.203  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:42.203  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:42.206  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:42.207  4005  4056 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:11:42.207  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:42.207  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c15fcf4 added. We now have 3 listener(s)
,09-12 13:11:42.209  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:11:42.209  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:42.209  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:11:42.209  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:42.209  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1273c1d added. We now have 10 listener(s)
09-12 13:11:42.209  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:42.210  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:11:42.210  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:42.210  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:42.210  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:11:42.210  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:42.210  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:42.210  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:42.210  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec952e1 removed from the list
09-12 13:11:42.210  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.210  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dff0806 removed from the list
09-12 13:11:42.213  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:42.213  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:42.213  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:42.214  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:42.214  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:42.218  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:42.218  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:42.218  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.219  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dff0806 not in the list
,09-12 13:11:42.220  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:42.220  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:42.220  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:42.223  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:42.223  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:42.223  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.223  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1273c1d removed from the list
09-12 13:11:42.224  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:11:42.224  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:42.224  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:42.224  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:11:42.225  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c15fcf4 removed from the list
,09-12 13:11:42.227  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:42.227  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d739e92 added. We now have 2 listener(s)
,09-12 13:11:42.231  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:11:42.232  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:42.232  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:42.232  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:42.233  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b773063 added. We now have 9 listener(s)
09-12 13:11:42.233  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:42.234  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:11:42.239  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:42.245  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:42.245  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:42.245  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:42.245  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:42.245  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:42.245  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:42.245  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:42.245  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:42.249  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:42.249  4005  4056 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:11:42.249  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:42.249  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f807d19 added. We now have 3 listener(s)
,09-12 13:11:42.252  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:11:42.253  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:42.253  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:42.253  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:42.253  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:42.253  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2911de added. We now have 10 listener(s)
09-12 13:11:42.253  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:42.254  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:11:42.254  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:11:42.254  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:11:42.254  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:42.254  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:11:42.258  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:42.259  4005  4056 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 13:11:42.259  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:11:42.264  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:11:42.265  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:11:42.265  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 13:11:42.266   874  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-12 13:11:42.270  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:11:42.270  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 13:11:42.270  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:11:42.271  4005  4056 D BluetoothAdapter: STATE_ON
,09-12 13:11:42.277  4359  4405 D BtGatt.GattService: registerClient() - UUID=a1f200db-3b7f-4843-b2a8-0e73acf3a308
,09-12 13:11:42.279  4359  4375 D BtGatt.GattService: onClientRegistered() - UUID=a1f200db-3b7f-4843-b2a8-0e73acf3a308, clientIf=5
,09-12 13:11:42.279  4005  4017 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:11:42.281  4359  4402 D BtGatt.GattService: start scan with filters
,09-12 13:11:42.287  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:11:42.287  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:11:42.288  4359  4378 D BtGatt.ScanManager: handling starting scan
09-12 13:11:42.288  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:11:42.288  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:11:42.293  4359  4378 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ca22c58
,09-12 13:11:42.299  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:42.299  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:42.300  4359  4375 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 13:11:42.300  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:11:42.301  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.302  4359  4378 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 13:11:42.308  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:11:42.315  4359  4375 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 13:11:42.315  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.316  4359  4378 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:11:42.316  4359  4378 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 13:11:42.319  4005  4056 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 13:11:42.320  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:11:42.320  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:11:42.321  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:42.322  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 13:11:42.322  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 13:11:42.323  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:11:42.323  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:11:42.326  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:11:42.327  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 13:11:42.327  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:11:42.329  4005  4056 D BluetoothAdapter: STATE_ON
09-12 13:11:42.330  4359  4405 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:11:42.331  4359  4405 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:11:42.332  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:11:42.332  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:11:42.332  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 13:11:42.332  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:11:42.332  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:11:42.334  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:42.335  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:11:42.335  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:11:42.335  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:11:42.337  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:42.337  4359  4375 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:11:42.337  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:42.339  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:42.339  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:42.340  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:42.344  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:11:42.344  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:42.344  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:42.345  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:11:42.345  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:42.345  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:42.346  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:42.346  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d739e92 removed from the list
09-12 13:11:42.346  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.346  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b773063 removed from the list
,09-12 13:11:42.346  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:42.346  4359  4375 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 13:11:42.346  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:42.347  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.347  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:42.348  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:42.350  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:42.350  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:42.350  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.350  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b773063 not in the list
,09-12 13:11:42.350  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:42.351  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:42.352  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:42.353  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:42.353  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.353  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2911de removed from the list
09-12 13:11:42.353  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:42.353  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:42.353  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:42.353  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:42.354  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f807d19 removed from the list
,09-12 13:11:42.356  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:42.356  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2306dea added. We now have 2 listener(s)
09-12 13:11:42.358  4359  4375 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 13:11:42.358  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.358  4359  4378 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:11:42.359  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:11:42.359  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:11:42.359  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:42.360  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:42.360  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1848db added. We now have 9 listener(s)
09-12 13:11:42.360  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:42.361  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:11:42.365  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:42.369  4359  4375 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 13:11:42.369  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.369  4359  4378 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:11:42.373  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:42.373  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:42.373  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:42.373  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:42.373  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:42.373  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:42.373  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:42.373  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:42.375  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:42.376  4005  4056 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:42.376  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:42.376  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3bb651 added. We now have 3 listener(s)
09-12 13:11:42.378  4359  4375 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:11:42.378  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:42.380  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:42.380  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:11:42.380  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:42.380  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:42.381  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:42.381  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f7eb6 added. We now have 10 listener(s)
09-12 13:11:42.381  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:42.381  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:42.382  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:42.382  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:11:42.382  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 13:11:42.383  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:42.383  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:11:42.384  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:42.387  4005  4056 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 13:11:42.387  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:11:42.391  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:11:42.392  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:11:42.392  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:11:42.397  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:11:42.397  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:11:42.397  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:11:42.398  4005  4056 D BluetoothAdapter: STATE_ON
,09-12 13:11:42.401  4359  4369 D BtGatt.GattService: registerClient() - UUID=e7499038-b50f-4982-97d1-53af16a23e66
,09-12 13:11:42.402  4359  4375 D BtGatt.GattService: onClientRegistered() - UUID=e7499038-b50f-4982-97d1-53af16a23e66, clientIf=5
,09-12 13:11:42.402  4005  4017 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:11:42.403  4359  4402 D BtGatt.GattService: start scan with filters
,09-12 13:11:42.407  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:11:42.407  4359  4378 D BtGatt.ScanManager: handling starting scan
,09-12 13:11:42.407  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 13:11:42.407  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:11:42.407  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:11:42.412  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:42.412  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:42.412  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:11:42.415  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-12 13:11:42.418  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:42.418  4005  4056 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-12 13:11:42.418  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:42.418  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:42.418  4359  4375 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 13:11:42.418  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:42.418  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.419  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:42.419  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:42.419  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:42.419  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:11:42.419  4359  4378 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 13:11:42.419  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2306dea removed from the list
09-12 13:11:42.419  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:42.419  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1848db removed from the list
,09-12 13:11:42.419  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:42.419  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:42.420  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:42.420  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-12 13:11:42.420  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:42.420  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:42.422  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:42.422  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:42.422  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:42.422  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d1848db not in the list
,09-12 13:11:42.422  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:11:42.423  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:11:42.423  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:11:42.423  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 13:11:42.424  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 13:11:42.425  4005  4056 D BluetoothAdapter: STATE_ON
,09-12 13:11:42.427  4359  4375 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 13:11:42.427  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:42.426  4359  4395 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:11:42.428  4359  4378 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:11:42.428  4359  4378 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 13:11:42.428  4359  4405 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:11:42.430  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:11:42.430  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:11:42.430  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:11:42.430  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 13:11:42.430  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:11:42.431  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:42.431  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:11:42.431  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:11:42.432  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 13:11:42.432  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:42.434  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:11:42.434  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:11:42.434  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:42.434  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:42.434  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:42.435  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.435  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19f7eb6 removed from the list,
09-12 13:11:42.435  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:11:42.435  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:42.435  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:42.435  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:11:42.435  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3bb651 removed from the list
,09-12 13:11:42.436  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:42.436  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1cd042 added. We now have 2 listener(s),
,09-12 13:11:42.438  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:11:42.438  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:11:42.438  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:42.438  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:11:42.439  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec4f853 added. We now have 9 listener(s)
,09-12 13:11:42.439  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:42.439  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:11:42.442  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:42.447  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:42.447  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:42.447  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:42.447  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:42.447  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:42.447  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:42.447  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:42.447  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:42.450  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:42.450  4005  4056 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:11:42.451  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:11:42.451  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8dde89 added. We now have 3 listener(s)
09-12 13:11:42.453  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:42.454  4359  4375 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:11:42.454  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.456  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 13:11:42.456  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:42.456  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:42.456  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:11:42.456  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:42.457  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2bae8e added. We now have 10 listener(s)
09-12 13:11:42.457  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:42.457  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:42.457  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:11:42.457  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 13:11:42.457  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:42.457  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:11:42.464  4005  4056 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 13:11:42.464  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:11:42.467  4359  4375 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 13:11:42.467  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:42.474  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:11:42.475  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 13:11:42.475  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:11:42.476  4359  4375 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 13:11:42.476  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:42.477  4359  4378 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:11:42.480  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:11:42.480  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 13:11:42.480  4005  4056 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:11:42.481  4005  4056 D BluetoothAdapter: STATE_ON
,09-12 13:11:42.485  4359  4369 D BtGatt.GattService: registerClient() - UUID=124fb7ca-5574-4797-87b4-d5e56a448d3a
,09-12 13:11:42.486  4359  4375 D BtGatt.GattService: onClientRegistered() - UUID=124fb7ca-5574-4797-87b4-d5e56a448d3a, clientIf=5
09-12 13:11:42.486  4005  4052 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 13:11:42.487  4359  4375 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 13:11:42.487  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.487  4359  4405 D BtGatt.GattService: start scan with filters
,09-12 13:11:42.487  4359  4378 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 13:11:42.493  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:11:42.493  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 13:11:42.493  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 13:11:42.493  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 13:11:42.493  4359  4375 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 13:11:42.494  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:42.495  4359  4378 D BtGatt.ScanManager: handling starting scan
,09-12 13:11:42.500  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:42.501  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:42.502  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:11:42.502  4359  4375 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 13:11:42.502  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:42.503  4359  4378 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 13:11:42.506  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:11:42.511  4359  4375 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 13:11:42.511  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:42.511  4359  4378 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:11:42.512  4359  4378 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 13:11:42.514  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:42.514  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:11:42.514  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:42.514  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:42.514  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:42.514  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:42.515  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:42.515  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e1cd042 removed from the list
,09-12 13:11:42.515  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:42.515  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec4f853 removed from the list
,09-12 13:11:42.515  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:11:42.515  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:42.516  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:42.516  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-12 13:11:42.516  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-12 13:11:42.516  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:42.517  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:42.517  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:42.517  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-12 13:11:42.518  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ec4f853 not in the list
,09-12 13:11:42.518  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:11:42.518  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
09-12 13:11:42.518  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:11:42.518  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 13:11:42.518  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
09-12 13:11:42.519  4005  4056 D BluetoothAdapter: STATE_ON,
,09-12 13:11:42.520  4359  4369 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:11:42.521  4359  4405 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 13:11:42.521  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:11:42.521  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED,
,09-12 13:11:42.521  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 13:11:42.521  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:11:42.522  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:11:42.523  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:42.523  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:11:42.523  4005  4056 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:11:42.523  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:11:42.524  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:42.527  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:42.527  4005  4005 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:42.527  4005  4005 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:42.528  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:42.528  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:42.528  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.529  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2bae8e removed from the list
09-12 13:11:42.529  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:42.529  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:42.529  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:42.530  4359  4375 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 13:11:42.531  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.532  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:42.532  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a8dde89 removed from the list
09-12 13:11:42.533  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:11:42.533  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f38259a added. We now have 2 listener(s),
,09-12 13:11:42.537  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:11:42.537  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:42.537  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:42.537  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:42.537  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5791ecb added. We now have 9 listener(s)
09-12 13:11:42.538  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:42.538  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:11:42.543  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:42.544  4359  4375 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 13:11:42.544  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 13:11:42.550  4005  4056 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:42.550  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:42.550  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:42.550  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:42.550  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:42.550  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:42.550  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:42.550  4005  4056 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:42.552  4005  4056 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:42.553  4005  4056 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:42.554  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,09-12 13:11:42.554  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@185d5c1 added. We now have 3 listener(s)
,09-12 13:11:42.556  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 13:11:42.556  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:11:42.556  4359  4375 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 13:11:42.556  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.556  4359  4378 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:11:42.556  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:42.556  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,09-12 13:11:42.557  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:11:42.557  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1630166 added. We now have 10 listener(s)
,09-12 13:11:42.557  4005  4056 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:42.557  4005  4056 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,09-12 13:11:42.558  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
,09-12 13:11:42.558  4005  4056 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:42.558  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:11:42.558  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:42.558  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,09-12 13:11:42.558  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:11:42.558  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f38259a removed from the list
,09-12 13:11:42.558  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.558  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5791ecb removed from the list
09-12 13:11:42.559  4005  4005 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:42.559  4005  4056 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:42.559  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:42.560  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:42.560  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:42.561  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:42.561  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:42.561  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.561  4005  4056 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5791ecb not in the list
,09-12 13:11:42.561  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:42.562  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:42.563  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:42.563  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:42.563  4005  4056 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:42.563  4005  4056 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1630166 removed from the list
,09-12 13:11:42.563  4005  4056 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:42.564  4005  4056 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:42.564  4005  4056 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:42.564  4005  4056 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:42.564  4005  4056 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@185d5c1 removed from the list
,09-12 13:11:42.565  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 13:11:42.565  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-12 13:11:42.565  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 13:11:42.565  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:42.566  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 13:11:42.566  4005  4056 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:11:42.566  4359  4375 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 13:11:42.567  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.567  4359  4378 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 13:11:42.572  4005  4444 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 474, name: My test thread name)
,09-12 13:11:42.572  4005  4444 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 474, thread name: My test thread name)
09-12 13:11:42.573  4005  4444 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 474, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-12 13:11:42.575  4005  4445 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 476, name: My test thread name)
09-12 13:11:42.575  4005  4445 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 476, thread name: My test thread name)
,09-12 13:11:42.575  4005  4445 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 476, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-12 13:11:42.578  4005  4056 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-12 13:11:42.578  4005  4056 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 13:11:42.578  4005  4056 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,09-12 13:11:42.578  4005  4056 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 13:11:42.578  4005  4056 D com.test.thalitest.ThaliTestRunner: Total duration: 23010 ms
09-12 13:11:42.579  4359  4375 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-12 13:11:42.579  4359  4375 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 13:11:42.580  4359  4375 D BtGatt.GattService: current time is 155158164996
09-12 13:11:42.580  4005  4056 I jxcore-log: *Native tests were executed*
09-12 13:11:42.580  4005  4056 I jxcore-log: 
,09-12 13:11:42.580  4359  4375 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -82, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 13:11:42.580  4005  4056 I jxcore-log: Total number of executed tests:  80
09-12 13:11:42.580  4005  4056 I jxcore-log: 
09-12 13:11:42.580  4005  4056 I jxcore-log: Number of passed tests:  80
09-12 13:11:42.580  4005  4056 I jxcore-log: 
,09-12 13:11:42.580  4005  4056 I jxcore-log: Number of failed tests:  0
09-12 13:11:42.580  4005  4056 I jxcore-log: 
09-12 13:11:42.581  4005  4056 I jxcore-log: Number of ignored tests:  0
09-12 13:11:42.581  4005  4056 I jxcore-log: 
09-12 13:11:42.581  4005  4056 I jxcore-log: Total duration:  23010
09-12 13:11:42.581  4005  4056 I jxcore-log: 
,09-12 13:11:42.581  4359  4375 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-12 13:11:42.581  4005  4056 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 13:11:42.581  4005  4056 I jxcore-log: 
09-12 13:11:42.589  4005  4005 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 13:11:42.590  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.590  4005  4056 I jxcore-log: 
,09-12 13:11:42.592  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.592  4005  4056 I jxcore-log: 
09-12 13:11:42.592  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.592  4005  4056 I jxcore-log: 
09-12 13:11:42.593  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.593  4005  4056 I jxcore-log: 
09-12 13:11:42.594  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.594  4005  4056 I jxcore-log: 
09-12 13:11:42.595  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.595  4005  4056 I jxcore-log: 
09-12 13:11:42.597  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.597  4005  4056 I jxcore-log: 
09-12 13:11:42.598  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:11:42.598  4005  4056 I jxcore-log: 
09-12 13:11:42.599  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:11:42.599  4005  4056 I jxcore-log: 
09-12 13:11:42.599  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:42.599  4005  4056 I jxcore-log: 
09-12 13:11:42.600  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:42.600  4005  4056 I jxcore-log: 
09-12 13:11:42.601  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:11:42.601  4005  4056 I jxcore-log: 
09-12 13:11:42.602  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:11:42.602  4005  4056 I jxcore-log: 
09-12 13:11:42.603  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:11:42.603  4005  4056 I jxcore-log: 
09-12 13:11:42.604  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.604  4005  4056 I jxcore-log: 
09-12 13:11:42.604  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.604  4005  4056 I jxcore-log: 
,09-12 13:11:42.606  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:42.606  4005  4056 I jxcore-log: 
09-12 13:11:42.607  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:42.607  4005  4056 I jxcore-log: 
09-12 13:11:42.608  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:11:42.608  4005  4056 I jxcore-log: 
09-12 13:11:42.608  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:11:42.608  4005  4056 I jxcore-log: 
09-12 13:11:42.609  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:42.609  4005  4056 I jxcore-log: 
09-12 13:11:42.609  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:42.609  4005  4056 I jxcore-log: 
09-12 13:11:42.610  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:11:42.610  4005  4056 I jxcore-log: 
09-12 13:11:42.611  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:11:42.611  4005  4056 I jxcore-log: 
09-12 13:11:42.612  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:11:42.612  4005  4056 I jxcore-log: 
09-12 13:11:42.612  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:11:42.612  4005  4056 I jxcore-log: 
09-12 13:11:42.612  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.612  4005  4056 I jxcore-log: 
,09-12 13:11:42.613  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.613  4005  4056 I jxcore-log: 
09-12 13:11:42.613  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.613  4005  4056 I jxcore-log: 
09-12 13:11:42.614  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.614  4005  4056 I jxcore-log: 
09-12 13:11:42.614  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.614  4005  4056 I jxcore-log: 
09-12 13:11:42.615  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:42.615  4005  4056 I jxcore-log: 
,09-12 13:11:42.841  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:11:42.842  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:11:42.842  4005  4056 I jxcore-log: 
,09-12 13:11:42.934  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:11:42.938  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:11:42.938  4005  4056 I jxcore-log: 
,09-12 13:11:43.029  4005  4005 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:11:43.032  4005  4056 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:11:43.032  4005  4056 I jxcore-log: 
,09-12 13:11:43.313  4446  4446 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-12 13:11:43.318  4446  4446 D AndroidRuntime: CheckJNI is OFF
,09-12 13:11:43.361  4446  4446 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-12 13:11:43.409  4446  4446 I Radio-JNI: register_android_hardware_Radio DONE
,09-12 13:11:43.431  4446  4446 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 13:11:43.448   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-12 13:11:43.450   874   887 I ActivityManager: Killing 4005:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-12 13:11:43.547   874  2026 D GraphicsStats: Buffer count: 2
,09-12 13:11:43.547   874  1486 I WindowState: WIN DEATH: Window{ef797c4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-12 13:11:43.548   874  1317 D WifiService: Client connection lost with reason: 4
,09-12 13:11:43.566   874   897 W PackageSettings: Skipping PackageSetting{34d145 com.example.hello/10273} due to missing metadata
,09-12 13:11:43.606   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-12 13:11:43.606   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-12 13:11:43.607   874   887 E ActivityManager: Failure starting process com.test.thalitest
09-12 13:11:43.607   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 13:11:43.607   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:43.607   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:43.607   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:11:43.607   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 13:11:43.608   874   887 I ActivityManager:   Force finishing activity ActivityRecord{8f0e115 u0 com.test.thalitest/.MainActivity t4}
09-12 13:11:43.608   874   897 I art     : Starting a blocking GC Explicit
09-12 13:11:43.616   874  1995 W ActivityManager: Spurious death for ProcessRecord{92ccde0 0:com.test.thalitest/u0a0}, curProc for 4005: null
,09-12 13:11:43.646   874   897 I art     : Explicit concurrent mark sweep GC freed 13669(955KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 744us total 36.964ms
09-12 13:11:43.685   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-12 13:11:43.687  4446  4446 I art     : System.exit called, status: 0
09-12 13:11:43.687  4446  4446 I AndroidRuntime: VM exiting with result code 0.
09-12 13:11:43.692   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-12 13:11:43.702   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-12 13:11:43.706  4359  4359 D BluetoothMapAppObserver: onReceive
09-12 13:11:43.706  4359  4359 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-12 13:11:43.714   874  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 13:11:43.715  1902  1902 I Keyboard.Facilitator: resetDictionaries() : en_US
09-12 13:11:43.716  1861  2198 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 13:11:43.722  3841  3841 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-12 13:11:43.732  1902  4459 I Keyboard.Facilitator.DecoderInitializer: run()
,09-12 13:11:43.746   874  1993 I ActivityManager: Start proc 4461:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-12 13:11:43.752  1987  1987 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-12 13:11:43.772  1902  4459 I Decoder : createOrResetDecoder
,09-12 13:11:43.791  1502  1502 I ConfigService: onCreate
,09-12 13:11:43.799   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 13:11:43.804  4461  4461 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-12 13:11:43.812  1902  4459 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-12 13:11:43.818   874  1995 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 4005 uid 10000
,09-12 13:11:43.819  1902  1902 I Keyboard.Facilitator: onFinishInput()
,09-12 13:11:43.819  2001  2098 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-12 13:11:43.820   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-12 13:11:43.822   874   886 E PackageManager: Failed to write settings, restoring backup
09-12 13:11:43.822   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 13:11:43.822   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 13:11:43.822   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 13:11:43.822   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 13:11:43.822   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 13:11:43.822   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:43.822   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:43.822   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:11:43.826   874   887 E DropBoxManagerService: Can't write: system_server_wtf
09-12 13:11:43.826   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 13:11:43.826   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:11:43.826   874   887 E DropBoxManagerService: 	... 13 more
,09-12 13:11:43.832   874  2026 I ActivityManager: Start proc 4474:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-12 13:11:43.832  2001  2098 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 13:11:43.832  2001  2098 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2001
09-12 13:11:43.832  2001  2098 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:43.832  2001  2098 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:11:43.834   874  2036 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:11:43.837  2001  2098 I Process : Sending signal. PID: 2001 SIG: 9
,09-12 13:11:43.838   874  4480 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:11:43.838   874  4480 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:11:43.838   874  4480 E DropBoxManagerService: 	... 5 more
,09-12 13:11:43.877  1902  4459 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-12 13:11:43.879  1902  4459 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-12 13:11:43.879  1902  4459 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-12 13:11:43.881  1902  4459 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-12 13:11:43.881  1902  4459 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-12 13:11:43.882  1902  4459 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-12 13:11:43.882  1902  4459 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-12 13:11:43.884  1902  4459 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-12 13:11:43.884  1902  4459 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-12 13:11:43.884  1902  4459 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-12 13:11:43.886  1902  4459 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-12 13:11:43.886  1902  4459 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-12 13:11:43.886  1902  4459 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-12 13:11:43.897  4461  4461 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-12 13:11:43.912   874  2026 D GraphicsStats: Buffer count: 1
,09-12 13:11:43.912   874  1995 I WindowState: WIN DEATH: Window{cf565cb u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-12 13:11:43.920   874  1882 I ActivityManager: Start proc 4494:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-12 13:11:43.921   277   277 E lowmemorykiller: Error writing /proc/2001/oom_score_adj; errno=22
09-12 13:11:43.922   874   885 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2001) has died
09-12 13:11:43.922  4461  4492 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-12 13:11:43.922   874   885 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-12 13:11:43.923   874   885 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 13:11:43.940   874   887 I ActivityManager: Start proc 4506:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:11:43.970  4494  4494 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-12 13:11:43.981  4461  4489 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:43.981  4461  4489 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:43.981  4461  4489 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 13:11:43.993  4506  4506 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.,
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:43.993  4506  4506 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:11:43.993  4506  4506 D AndroidRuntime: Shutting down VM
09-12 13:11:44.001  1502  1502 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-12 13:11:44.001  4506  4506 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:11:44.001  4506  4506 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4506
09-12 13:11:44.001  4506  4506 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 13:11:44.001  4506  4506 E AndroidRuntime: 	... 10 more
09-12 13:11:44.001  1502  1502 D AndroidRuntime: Shutting down VM
09-12 13:11:44.002  1502  1502 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:11:44.002  1502  1502 E AndroidRuntime: Process: com.google.process.gapps, PID: 1502
09-12 13:11:44.002  1502  1502 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 13:11:44.002  1502  1502 E AndroidRuntime: 	... 8 more
09-12 13:11:44.003  1694  4517 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-12 13:11:44.006   874  1995 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 13:11:44.007   874  4521 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:11:44.007   874  4521 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:11:44.007   874  4521 E DropBoxManagerService: 	... 5 more
09-12 13:11:44.008   874  4522 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:11:44.008   874  4522 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:11:44.008   874  4522 E DropBoxManagerService: 	... 5 more
09-12 13:11:44.008  4506  4506 I Process : Sending signal. PID: 4506 SIG: 9
09-12 13:11:44.008  1502  1502 I Process : Sending signal. PID: 1502 SIG: 9
09-12 13:11:44.009  1694  4517 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-12 13:11:44.019  1694  4517 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-12 13:11:44.019  1694  4517 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-12 13:11:44.027   874  2035 I ActivityManager: Killing 3894:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-12 13:11:44.036   874  1316 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-12 13:11:44.057   874  1317 D WifiService: Client connection lost with reason: 4
09-12 13:11:44.059  4461  4489 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:44.064  4461  4492 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 13:11:44.064  4461  4492 E AndroidRuntime: Process: android.process.acore, PID: 4461
09-12 13:11:44.064  4461  4492 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:44.064  4461  4492 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 13:11:44.066  4461  4489 I Process : Sending signal. PID: 4461 SIG: 9
09-12 13:11:44.079   874  2036 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4506) has died
09-12 13:11:44.081   874  2036 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 13:11:44.084   874  2022 I ActivityManager: Process com.google.process.gapps (pid 1502) has died
,09-12 13:11:44.085   874  2022 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,09-12 13:11:44.085   874  2022 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
,09-12 13:11:44.086   874  2022 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
,09-12 13:11:44.086   874  2022 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
,09-12 13:11:44.099  1694  1694 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-12 13:11:44.114   874   887 I ActivityManager: Start proc 4525:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 13:11:44.115   874   884 I ActivityManager: Process android.process.acore (pid 4461) has died
,09-12 13:11:44.115   874   884 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40970ms
,09-12 13:11:44.118   874  4530 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:11:44.118   874  4530 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:11:44.118   874  4530 E DropBoxManagerService: 	... 5 more
,09-12 13:11:44.127   874  2035 I ActivityManager: Start proc 4532:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-12 13:11:44.173  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-12 13:11:44.173  1694  1694 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-12 13:11:44.176  4532  4532 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,09-12 13:11:44.177  1694  1694 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-12 13:11:44.177  1694  1694 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:44.178  4525  4525 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 13:11:44.178  4525  4525 D AndroidRuntime: Shutting down VM
09-12 13:11:44.188  4525  4525 E AndroidRuntime: FATAL EXCEPTION: main
09-12 13:11:44.188  4525  4525 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4525
09-12 13:11:44.188  4525  4525 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 13:11:44.188  4525  4525 E Andr,oidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 13:11:44.188  4525  4525 E AndroidRuntime: 	... 10 more
09-12 13:11:44.189  4532  4532 I MultiDex: VM with version 2.1.0 has multidex support
09-12 13:11:44.189  4532  4532 I MultiDex: install
09-12 13:11:44.189  4532  4532 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-12 13:11:44.189  1694  4553 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-12 13:11:44.190   874   884 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 13:11:44.192   874  4554 E DropBoxManagerService: Can't write: system_app_crash
09-12 13:11:44.192   874  4554 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 13:11:44.192   874  4554 E DropBoxManagerService: 	... 5 more
09-12 13:11:44.192  4525  4525 I Process : Sending signal. PID: 4525 SIG: 9
,09-12 13:11:44.198  4532  4532 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm

```
