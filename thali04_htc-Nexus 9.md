#### Test 757892686f45c73_thali04_htc-Nexus 9 Logs


```
--------- beginning of main
07-26 15:20:45.762  2070  2857 V KeepSync: Connecting to GoogleApiClient
--------- beginning of system
07-26 15:20:45.762   569  1049 W AppOps  : Bad call: specified package com.google.android.gms under uid 10072 but it is really 10007
,07-26 15:20:45.780  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-26 15:20:45.781  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-26 15:20:45.791  1097  1258 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-26 15:20:45.791  1097  1258 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-26 15:20:45.791  1097  1258 I GLSUser : [GLSUser] Extracting token using key: Auth
07-26 15:20:45.791  1097  1258 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-26 15:20:45.798  1218  2858 V BaseAuthAsyncOperation: access token request failed
07-26 15:20:45.799  2070  2857 V KeepSync: GoogleApiClient failed to connect with error code: 4
07-26 15:20:45.823  1097  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-26 15:20:45.823  1097  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-26 15:20:45.823  1097  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
07-26 15:20:45.823  1097  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-26 15:20:45.831  2070  2857 E KeepSync: IOException
07-26 15:20:45.831  2070  2857 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-26 15:20:45.831  2070  2857 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-26 15:20:45.831  2070  2857 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-26 15:20:45.831  2070  2857 E KeepSync: 	... 10 more
07-26 15:20:45.832  2070  2857 W KeepSync: Sync result 2
07-26 15:20:45.837   569   604 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 136649, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
07-26 15:20:46.068  2859  2859 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-26 15:20:46.072  2859  2859 D AndroidRuntime: CheckJNI is OFF
07-26 15:20:46.103  2859  2859 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-26 15:20:46.138  2859  2859 I Radio-JNI: register_android_hardware_Radio DONE
07-26 15:20:46.160  2859  2859 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-26 15:20:46.166   569   734 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-26 15:20:46.185  2859  2859 D AndroidRuntime: Shutting down VM
07-26 15:20:46.194  1080  1304 W SearchService: Abort, client detached.
07-26 15:20:46.207  1080  1080 I HotwordDetector: Closing mic
07-26 15:20:46.208  1080  1315 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@6299f9c
07-26 15:20:46.212   569   591 I ActivityManager: Start proc 2868:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-26 15:20:46.219   222   644 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-26 15:20:46.227  1080  1323 I MicroRecognitionRnrImpl: Detection finished
07-26 15:20:46.230  1080  1317 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-26 15:20:46.323  2868  2868 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,07-26 15:20:46.445  2868  2868 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-26 15:20:46.469  2868  2868 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 7565-7579)
07-26 15:20:46.469  2868  2868 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-26 15:20:46.511  2868  2868 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fbf93dc}
,07-26 15:20:46.512  2868  2868 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:20:46.512  2868  2868 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-26 15:20:46.516  2868  2868 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-26 15:20:46.517  2868  2868 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-26 15:20:46.553  2868  2868 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-26 15:20:46.569  2868  2868 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:20:46.570  2868  2868 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-26 15:20:46.800   569   616 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3084d0d:true
,07-26 15:20:46.871  2868  2868 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-26 15:20:46.888  2868  2868 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
,07-26 15:20:46.947  2868  2910 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-26 15:20:46.954  2868  2896 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-26 15:20:46.998  2868  2910 I OpenGLRenderer: Initialized EGL, version 1.4
,07-26 15:20:47.082   569   618 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +880ms
,07-26 15:20:47.088   990   990 I Keyboard.Facilitator: onFinishInput()
,07-26 15:20:47.153   569   958 I ActivityManager: Killing 2514:com.google.android.gm.exchange/u0a70 (adj 15): empty #17
,07-26 15:20:47.170  2868  2868 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2868
,07-26 15:20:47.180   569   958 I ActivityManager: Killing 1956:com.google.android.talk/u0a56 (adj 15): empty #18
,07-26 15:20:47.288  2868  2868 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-26 15:20:47.452  2868  2911 D jxcore_app_log: JniHelper::setJavaVM(0xaae5e7b8), pthread_self() = -571479760
,07-26 15:20:47.459  2868  2911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-26 15:20:47.459  2868  2911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 15:20:47.459  2868  2911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 15:20:47.459  2868  2911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 15:20:47.459  2868  2911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-26 15:20:47.459  2868  2911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd75ba3 added. We now have 1 listener(s)
,07-26 15:20:47.501  2868  2911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
07-26 15:20:47.502  2868  2911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
,07-26 15:20:47.502  2868  2911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:20:47.503  2868  2911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-26 15:20:47.508  2868  2911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62aa61e added. We now have 1 listener(s)
07-26 15:20:47.508  2868  2911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:20:47.514   569   664 D WifiService: New client listening to asynchronous messages
,07-26 15:20:47.515  2868  2911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:20:47.515  2868  2911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-26 15:20:47.515  2868  2911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-26 15:20:47.515  2868  2911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-26 15:20:47.518  2868  2911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:20:47.519  2868  2911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
,07-26 15:20:47.524  2868  2911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
07-26 15:20:47.525  2868  2911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:20:47.525  2868  2911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:20:47.525  2868  2911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:20:47.525  2868  2911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:20:47.525  2868  2911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:20:47.525  2868  2911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:20:47.525  2868  2911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:20:47.525  2868  2911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:20:47.525  2868  2911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-26 15:20:47.525  2868  2911 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:20:47.526  2868  2868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:47.527  2868  2868 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:20:47.531  2868  2911 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-26 15:20:47.564  2868  2868 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-26 15:20:48.079  2868  2919 W jxcore-log: Initializing JXcore engine
07-26 15:20:48.079  2868  2919 W jxcore-log: JXcore engine is ready
,07-26 15:20:48.128  2919  2919 W Thread-61: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=7626 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-26 15:20:48.128  2919  2919 W Thread-61: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10357]" dev="sockfs" ino=10357 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-26 15:20:48.128  2919  2919 W Thread-61: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=1032 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-26 15:20:48.128  2919  2919 W Thread-61: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[20986]" dev="sockfs" ino=20986 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-26 15:20:48.142  2868  2919 W jxcore-log: Starting JXcore engine
,07-26 15:20:48.221  2868  2919 W jxcore-log: Platform android
07-26 15:20:48.221  2868  2919 W jxcore-log: 
07-26 15:20:48.221  2868  2919 W jxcore-log: Process ARCH arm
07-26 15:20:48.221  2868  2919 W jxcore-log: 
,07-26 15:20:48.343  2868  2919 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:20:48.343  2868  2919 I jxcore-log: 
07-26 15:20:48.343  2868  2919 W jxcore-log: JXcore engine is started
,07-26 15:20:48.346  2868  2911 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 15:20:48.348  2868  2868 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
07-26 15:20:48.354  2868  2919 E jxcore  : Error!: No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js
07-26 15:20:48.354  2868  2919 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-26 15:20:48.359  2868  2868 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/user/0/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,07-26 15:20:48.359  2868  2868 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-26 15:20:48.361   169   176 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (94 us)
,07-26 15:20:48.425  2868  2911 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 65ms. Plugin should use CordovaInterface.getThreadPool().
,07-26 15:20:48.426  2868  2868 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-26 15:20:48.426  2868  2868 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-26 15:20:48.437   569   605 I ActivityManager: Killing 2540:com.google.process.gapps/u0a85 (adj 15): empty #17
,07-26 15:20:48.476  2868  2868 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-26 15:20:48.476  2868  2868 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
07-26 15:20:48.476  2868  2868 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-26 15:20:48.476  2868  2868 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-26 15:20:48.476  2868  2868 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:20:48.476  2868  2868 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:20:48.477  2868  2868 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:20:48.477  2868  2868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:20:48.478  2868  2868 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd75ba3 removed from the list
07-26 15:20:48.478  2868  2868 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:20:48.478  2868  2868 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62aa61e removed from the list
,07-26 15:20:48.478  2868  2868 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:20:48.483  2868  2868 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-26 15:20:48.488  2868  2868 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-26 15:20:48.537   990   990 I Keyboard.Facilitator: onFinishInput()
,07-26 15:20:48.651  1080  1080 W LocationOracleImpl: Best location was null
,07-26 15:20:48.683  1080  2931 I MicroRecognitionRnrImpl: Starting detection.
07-26 15:20:48.686  1080  2932 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@572b7c8
07-26 15:20:48.689   222   644 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-26 15:20:48.695   222  2934 I AudioFlinger: AudioFlinger's thread 0xabc7aa30 ready to run
07-26 15:20:48.698  1080  2932 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@572b7c8
,07-26 15:20:48.749  1007  1229 W GCoreFlp: No location to return for getLastLocation()
,07-26 15:20:48.822  1007  1229 W GCoreFlp: No location to return for getLastLocation()
,07-26 15:20:48.866  1007  1229 W GCoreFlp: No location to return for getLastLocation()
,07-26 15:20:48.879  1080  1080 I HotwordWorkerImpl: onReady
,07-26 15:20:48.881  1007  1229 W GCoreFlp: No location to return for getLastLocation()
,07-26 15:20:48.950  2923  2923 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,07-26 15:20:48.956  2923  2923 D AndroidRuntime: CheckJNI is OFF
07-26 15:20:48.978  2728  2936 V GoogleAuthProtoRequest: [263] a.<init>: mAccountName set to: thalitester@gmail.com
07-26 15:20:49.011  2923  2923 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-26 15:20:49.019  1097  1109 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-26 15:20:49.019  1097  1109 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-26 15:20:49.021  1097  1109 I GLSUser : [GLSUser] Extracting token using key: Auth
07-26 15:20:49.021  1097  1109 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-26 15:20:49.027  1051  1259 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: [263] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: [263] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-26 15:20:49.051  2728  2936 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-26 15:20:49.062  2923  2923 I Radio-JNI: register_android_hardware_Radio DONE
,07-26 15:20:49.092  1097  1097 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-26 15:20:49.097  2923  2923 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-26 15:20:49.108  1097  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-26 15:20:49.108  1097  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-26 15:20:49.108  1097  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
07-26 15:20:49.108  1097  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-26 15:20:49.110   569   605 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,07-26 15:20:49.110   569   605 I ActivityManager: Killing 2868:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,07-26 15:20:49.143   569   734 D GraphicsStats: Buffer count: 2
07-26 15:20:49.144   569   664 D WifiService: Client connection lost with reason: 4
,07-26 15:20:49.154   569   633 W PackageSettings: Skipping PackageSetting{ab4d384 com.example.hello/10095} due to missing metadata
,07-26 15:20:49.180   569   633 I art     : Starting a blocking GC Explicit
,07-26 15:20:49.180   569   590 W ActivityManager: Spurious death for ProcessRecord{5bbfe73 0:com.test.thalitest/u0a0}, curProc for 2868: null
,07-26 15:20:49.198  2490  2490 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-26 15:20:49.198  2490  2490 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-26 15:20:49.198  2490  2490 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-26 15:20:49.253   569   633 I art     : Explicit concurrent mark sweep GC freed 19755(1287KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 17MB/26MB, paused 647us total 71.600ms
,07-26 15:20:49.262   569   633 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,07-26 15:20:49.265  2923  2923 I art     : System.exit called, status: 0
07-26 15:20:49.265  2923  2923 I AndroidRuntime: VM exiting with result code 0.
,07-26 15:20:49.270   569   633 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-26 15:20:49.312  1030  1030 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-26 15:20:49.312  1007  1255 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-26 15:20:49.317   990   990 I Keyboard.Facilitator: resetDictionaries() : en_US
07-26 15:20:49.324   569   654 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-26 15:20:49.348   990  2953 I Keyboard.Facilitator.DecoderInitializer: run()
,07-26 15:20:49.371  2474  2954 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-26 15:20:49.389   990  2953 I Decoder : createOrResetDecoder
,07-26 15:20:49.402   569   569 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-26 15:20:49.494  1097  1097 I ConfigService: onCreate
,07-26 15:20:49.506  1097  1097 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,07-26 15:20:49.506  1097  1097 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,07-26 15:20:49.513   990  2953 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-26 15:20:49.522  1218  2958 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,07-26 15:20:49.523  1218  2958 D AccountUtils: Clearing selected account for com.test.thalitest
07-26 15:20:49.529   569   686 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
07-26 15:20:49.529   569   686 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
07-26 15:20:49.529   569   686 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
07-26 15:20:49.529   569   686 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
07-26 15:20:49.529   569   686 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
07-26 15:20:49.529   569   686 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
07-26 15:20:49.532   569   686 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
,07-26 15:20:49.538   569   590 I ActivityManager: Start proc 2961:com.google.android.googlequicksearchbox:crash_report/u0a22 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
07-26 15:20:49.539  1051  1123 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-26 15:20:49.539  1051  1123 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1051
07-26 15:20:49.539  1051  1123 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:49.539  1051  1123 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.547   569   686 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
07-26 15:20:49.547   569   686 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
07-26 15:20:49.547   569   686 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
07-26 15:20:49.547   569   686 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
07-26 15:20:49.547   569   686 W System.err: 	... 4 more
,07-26 15:20:49.548   569   958 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-26 15:20:49.552  1080  1094 W SearchService: Abort, client detached.
,07-26 15:20:49.557  1080  1080 I HotwordDetector: Closing mic
,07-26 15:20:49.558  1080  1315 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@572b7c8
,07-26 15:20:49.575  2474  2954 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,07-26 15:20:49.577   569   686 D skia    : ------- write threw an exception
,07-26 15:20:49.580   569  2975 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-26 15:20:49.589  1218  1218 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
07-26 15:20:49.590  1218  1218 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
07-26 15:20:49.594   222   644 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-26 15:20:49.602  1080  1317 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-26 15:20:49.603  1080  2931 I MicroRecognitionRnrImpl: Detection finished
07-26 15:20:49.604  2474  2954 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-26 15:20:49.604  2474  2954 E AndroidRuntime: Process: android.process.acore, PID: 2474
07-26 15:20:49.604  2474  2954 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:49.604  2474  2954 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.617  1218  2976 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-26 15:20:49.624  1218  2958 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-26 15:20:49.631   569  2977 E DropBoxManagerService: Can't write: system_app_crash
07-26 15:20:49.631   569  2977 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop103.tmp: open failed: EROFS (Read-only file system)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-26 15:20:49.631   569  2977 E DropBoxManagerService: 	... 5 more
,07-26 15:20:49.632   569  2975 I OpenGLRenderer: Initialized EGL, version 1.4
,07-26 15:20:49.647  1218  2976 E DriveAsyncService: disk I/O error (code 3850)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-26 15:20:49.647  1218  2976 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,07-26 15:20:49.652  1218  1218 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,07-26 15:20:49.653  1218  1218 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,07-26 15:20:49.697  1218  2958 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:49.697  1218  2958 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:20:49.698  1218  2958 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:20:49.699  1218  2958 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,07-26 15:20:49.708  1080  2980 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-26 15:20:49.719  1080  2980 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-26 15:20:49.736  1218  2985 W BaseAppContext: Using Auth Proxy for data requests.
,07-26 15:20:49.737  1218  2987 I GMPM-SVC: App measurement is starting up
,07-26 15:20:49.739  1218  2987 E GMPM-SVC: AppMeasurementService not registered/enabled
,07-26 15:20:49.743  1218  2987 E GMPM-SVC: Uploading is not possible. App measurement disabled
07-26 15:20:49.743  1218  2985 W BaseAppContext: Using Auth Proxy for data requests.

```
