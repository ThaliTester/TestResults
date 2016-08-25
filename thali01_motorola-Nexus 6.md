#### Test 82728424cc1b7f1_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-25 21:49:08.073  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 21:49:08.088  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 21:49:08.094  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-25 21:49:08.155  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-25 21:49:08.156  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-25 21:49:08.156  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 21:49:08.156  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 21:49:08.201  3494  3494 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-25 21:49:08.201  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 21:49:08.202  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-25 21:49:08.743  3753  3753 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-25 21:49:08.748  3753  3753 D AndroidRuntime: CheckJNI is OFF
08-25 21:49:08.791  3753  3753 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-25 21:49:08.843  3753  3753 I Radio-JNI: register_android_hardware_Radio DONE
08-25 21:49:08.866  3753  3753 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 21:49:08.870   873  1945 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 21:49:08.901  2013  3715 W SearchService: Abort, client detached.
08-25 21:49:08.910  2013  2013 I HotwordDetector: Closing mic
08-25 21:49:08.910  2013  2330 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3a002af
08-25 21:49:08.910  2013  2356 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-25 21:49:08.914  3753  3753 D AndroidRuntime: Shutting down VM
08-25 21:49:08.927   873  1985 I ActivityManager: Start proc 3762:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-25 21:49:08.972   374  2358 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-25 21:49:08.973   374  2358 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-25 21:49:08.977   374  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-25 21:49:08.979  2013  2353 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-25 21:49:08.980  2013  2355 I MicroRecognitionRnrImpl: Detection finished
08-25 21:49:08.994  3762  3762 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 21:49:09.020  3762  3762 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 21:49:09.028  3762  3762 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 10-12)
08-25 21:49:09.028  3762  3762 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 21:49:09.032  1524  3001 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.googlequicksearchbox, service: mobilepersonalfeeds
08-25 21:49:09.032  1524  3001 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> mobilepersonalfeeds without consulting the cloud.
08-25 21:49:09.032  1524  3001 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 21:49:09.032  1524  3001 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-25 21:49:09.039  3762  3762 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1140d60}
08-25 21:49:09.040  3762  3762 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 21:49:09.041  3762  3762 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: User recoverable exception for scope: mobilepersonalfeeds
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at com.google.android.gms.auth.b.b(Unknown Source)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.m.a(GoogleAuthAdapterImpl.java:29)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.k.a(FallingBackGoogleAuthAdapter.java:93)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.g.a(CachingGoogleAuthAdapter.java:72)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n.b(LoginHelper.java:829)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.Pe(LoginHelper.java:715)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.google.c.n$5.call(LoginHelper.java:712)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
08-25 21:49:09.044  2013  2155 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.concurrent.a.q$1.run(GsaThreadFactory.java:99)
08-25 21:49:09.046  2013  2128 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-25 21:49:09.048  3762  3762 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-25 21:49:09.049  3762  3762 E SysUtils: ApplicationContext is null in ApplicationStatus
08-25 21:49:09.061  3762  3762 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-25 21:49:09.072  3762  3762 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 21:49:09.072  3762  3762 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-25 21:49:09.072  3762  3762 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 21:49:09.072  3762  3762 I Adreno  : Build Date                       : 10/20/15
08-25 21:49:09.072  3762  3762 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 21:49:09.072  3762  3762 I Adreno  : Local Branch                     : M14
08-25 21:49:09.072  3762  3762 I Adreno  : Remote Branch                    : 
08-25 21:49:09.072  3762  3762 I Adreno  : Remote Branch                    : 
08-25 21:49:09.072  3762  3762 I Adreno  : Reconstruct Branch               : 
08-25 21:49:09.075  2013  2128 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-25 21:49:09.081  2013  2128 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 64-66)
08-25 21:49:09.082  2013  2128 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 21:49:09.116   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@db16b1b:true
,08-25 21:49:09.169  3762  3762 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 21:49:09.184  3762  3762 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-25 21:49:09.236  3762  3807 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-25 21:49:09.244  3762  3792 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-25 21:49:09.265  3762  3807 I OpenGLRenderer: Initialized EGL, version 1.4
,08-25 21:49:09.287  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-25 21:49:09.318   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +406ms
,08-25 21:49:09.352  3762  3762 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3762
,08-25 21:49:09.467  3762  3762 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 21:49:09.596  3762  3817 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1700923088
,08-25 21:49:09.601  3762  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 21:49:09.601  3762  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 21:49:09.601  3762  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 21:49:09.601  3762  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 21:49:09.601  3762  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-25 21:49:09.601  3762  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f77a077 added. We now have 1 listener(s)
,08-25 21:49:09.604  3762  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-25 21:49:09.605  3762  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 21:49:09.605  3762  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 21:49:09.605  3762  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-25 21:49:09.608  3762  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8b0002 added. We now have 1 listener(s)
08-25 21:49:09.609  3762  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:09.610   873  1315 D WifiService: New client listening to asynchronous messages
,08-25 21:49:09.611  3762  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:09.611  3762  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-25 21:49:09.612  3762  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 21:49:09.612  3762  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 21:49:09.612  3762  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-25 21:49:09.614  3762  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:09.614  3762  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-25 21:49:09.622  3762  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-25 21:49:09.623  3762  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:09.623  3762  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:09.623  3762  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:09.623  3762  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:09.623  3762  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:09.623  3762  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:09.623  3762  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:09.623  3762  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:49:09.623  3762  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 21:49:09.623  3762  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:09.623  3762  3817 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 21:49:09.625  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:09.626  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:09.655  3762  3762 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 21:49:09.730   873  2295 I ActivityManager: Killing 3195:com.google.android.gm/u0a78 (adj 15): empty #17
,08-25 21:49:09.773   873  2295 I ActivityManager: Killing 3086:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-25 21:49:10.578  3762  3825 W jxcore-log: Initializing JXcore engine
,08-25 21:49:10.578  3762  3825 W jxcore-log: JXcore engine is ready
,08-25 21:49:10.629  3825  3825 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-25 21:49:10.629  3825  3825 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10129]" dev="sockfs" ino=10129 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-25 21:49:10.629  3825  3825 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-25 21:49:10.629  3825  3825 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26231]" dev="sockfs" ino=26231 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-25 21:49:10.645  3762  3825 W jxcore-log: Starting JXcore engine
,08-25 21:49:10.730  3762  3825 W jxcore-log: Platform android
08-25 21:49:10.730  3762  3825 W jxcore-log: 
,08-25 21:49:10.731  3762  3825 W jxcore-log: Process ARCH arm
08-25 21:49:10.731  3762  3825 W jxcore-log: 
,08-25 21:49:10.767   873  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2412
,08-25 21:49:10.990  3762  3825 I jxcore-log: JXcore Cordova bridge is ready!
08-25 21:49:10.990  3762  3825 I jxcore-log: 
,08-25 21:49:10.990  3762  3825 W jxcore-log: JXcore engine is started
,08-25 21:49:11.000  3762  3817 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-25 21:49:11.004  3762  3762 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 21:49:15.836  3032  3840 V KeepSync: Connecting to GoogleApiClient
,08-25 21:49:15.837   873  2267 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-25 21:49:15.886  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 21:49:15.889  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 21:49:15.931  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-25 21:49:15.932  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-25 21:49:15.932  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 21:49:15.932  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 21:49:15.975  1727  3841 V BaseAuthAsyncOperation: access token request failed
,08-25 21:49:15.977  3032  3840 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-25 21:49:16.069  1524  2289 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-25 21:49:16.069  1524  2289 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-25 21:49:16.069  1524  2289 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 21:49:16.069  1524  2289 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 21:49:16.096  3032  3840 E KeepSync: IOException
08-25 21:49:16.096  3032  3840 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-25 21:49:16.096  3032  3840 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-25 21:49:16.096  3032  3840 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-25 21:49:16.096  3032  3840 E KeepSync: 	... 10 more
,08-25 21:49:16.096  3032  3840 W KeepSync: Sync result 2
,08-25 21:49:16.110   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 126709, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,08-25 21:49:21.119  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 21:49:21.119  3762  3825 I jxcore-log: 
,08-25 21:49:21.123  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 21:49:21.123  3762  3825 I jxcore-log: 
,08-25 21:49:21.135  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:21.135  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:21.135  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:21.135  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:21.135  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:21.135  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:21.135  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:21.135  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:49:21.142  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:21.148  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 21:49:21.148  3762  3825 I jxcore-log: 
,08-25 21:49:21.150  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 21:49:21.150  3762  3825 I jxcore-log: 
,08-25 21:49:21.728  3762  3825 D executeNativeTests: Running unit tests
,08-25 21:49:21.793  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 21:49:21.794  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 added. We now have 2 listener(s)
08-25 21:49:21.795  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 21:49:21.795  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:21.795  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:21.795  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:21.795  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd added. We now have 2 listener(s)
08-25 21:49:21.795  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:21.796  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:21.808  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:21.818  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:21.818  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:21.818  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:21.818  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:21.818  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:21.818  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:21.818  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:21.818  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:21.823  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:21.824  3762  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 21:49:21.830  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:21.832  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 21:49:21.838  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 21:49:21.838  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-25 21:49:21.839  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:21.847  3762  3825 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-25 21:49:21.850  3762  3825 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-25 21:49:21.851  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 21:49:21.851  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 21:49:21.851  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 21:49:21.853  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:21.855  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:21.856  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 21:49:21.857  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:49:21.858  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:21.858  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:21.858  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:21.859  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 removed from the list,
08-25 21:49:21.859  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:21.859  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd removed from the list
,08-25 21:49:21.859  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 21:49:21.860  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:21.861  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:21.861  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:21.863  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:21.864  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:21.864  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:21.864  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
,08-25 21:49:21.868  3762  3825 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-25 21:49:21.870  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:21.871  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:21.871  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:21.872  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:21.872  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:21.872  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:21.872  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:21.873  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:21.873  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:21.873  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 21:49:21.873  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:21.873  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:21.874  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:21.874  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:21.876  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:21.876  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:21.876  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:21.876  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
,08-25 21:49:21.881  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 21:49:21.881  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 21:49:21.881  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 21:49:21.881  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-25 21:49:21.881  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 21:49:21.881  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 21:49:21.881  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 21:49:21.881  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 21:49:21.882  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 21:49:21.883  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 21:49:21.883  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-25 21:49:21.883  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 21:49:21.883  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 21:49:21.883  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 21:49:21.883  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 21:49:21.883  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 21:49:21.883  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 21:49:21.883  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:21.883  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:21.883  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:21.883  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:21.883  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:21.884  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:21.884  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:21.884  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:49:21.884  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:21.884  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:21.884  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:21.884  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:21.884  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:21.884  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:21.885  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:21.885  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:21.885  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:21.885  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
,08-25 21:49:21.885  3762  3825 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 21:49:21.887  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:21.892  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:21.892  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:21.892  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:21.892  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:21.892  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:21.892  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:21.892  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:21.892  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:21.894  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:21.894  3762  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 21:49:21.896  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 21:49:21.896  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-25 21:49:21.896  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 21:49:21.896  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:21.896  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 21:49:21.896  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:21.899  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:21.899  3762  3825 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 21:49:21.899  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 21:49:21.905  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 21:49:21.907  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 21:49:21.907  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 21:49:21.910  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-25 21:49:21.913  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-25 21:49:21.913  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 21:49:21.916  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-25 21:49:21.917  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:21.919  3762  3825 D BluetoothAdapter: STATE_ON
,08-25 21:49:21.923  2695  2706 D BtGatt.GattService: registerClient() - UUID=a7205104-01b9-4d59-943f-b034fd0a845a
,08-25 21:49:21.924  2695  2749 D BtGatt.GattService: onClientRegistered() - UUID=a7205104-01b9-4d59-943f-b034fd0a845a, clientIf=5
,08-25 21:49:21.924  3762  3774 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 21:49:21.925  2695  2711 D BtGatt.GattService: start scan with filters
,08-25 21:49:21.929  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 21:49:21.929  2695  2767 D BtGatt.ScanManager: handling starting scan
,08-25 21:49:21.929  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 21:49:21.929  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:21.929  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 21:49:21.931  2695  2767 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
08-25 21:49:21.933  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 21:49:21.933  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-25 21:49:21.933  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:21.935  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-25 21:49:21.938  3762  3825 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 21:49:21.941  2695  2749 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 21:49:21.941  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:21.942  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:21.942  3762  3825 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 21:49:21.942  2695  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 21:49:21.942  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:21.942  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 21:49:21.942  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:21.942  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:21.942  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 21:49:21.942  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:21.942  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 21:49:21.942  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:21.943  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:21.943  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 21:49:21.944  3762  3825 D BluetoothAdapter: STATE_ON
08-25 21:49:21.944  2695  2711 D BtGatt.GattService: stopScan() - queue size =1
08-25 21:49:21.945  2695  2885 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 21:49:21.945  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:49:21.946  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 21:49:21.946  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 21:49:21.946  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 21:49:21.946  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 21:49:21.947  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:21.948  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 21:49:21.948  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 21:49:21.948  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 21:49:21.949  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:21.949  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 21:49:21.949  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:21.950  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:21.950  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:21.950  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:21.950  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 21:49:21.950  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:21.950  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:21.950  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:21.950  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:21.950  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:21.950  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 21:49:21.950  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:21.951  3762  3825 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-25 21:49:21.952  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:21.953  2695  2767 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:21.953  2695  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 21:49:21.957  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:21.957  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:21.957  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:21.957  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:21.957  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:21.957  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:21.957  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:21.957  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:21.959  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:21.959  3762  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 21:49:21.959  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:49:21.959  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:49:21.959  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:49:21.959  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:21.959  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 21:49:21.960  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:21.961  3762  3825 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 21:49:21.961  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 21:49:21.963  2695  2749 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 21:49:21.963  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:21.963  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:21.966  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 21:49:21.967  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 21:49:21.967  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 21:49:21.969  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 21:49:21.969  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:21.980  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 21:49:21.980  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 21:49:21.980  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:21.981  3762  3825 D BluetoothAdapter: STATE_ON
,08-25 21:49:21.983  2695  2885 D BtGatt.GattService: registerClient() - UUID=9ff1e697-8d57-46c5-94cc-baa6f3878e2e
08-25 21:49:21.984  2695  2749 D BtGatt.GattService: onClientRegistered() - UUID=9ff1e697-8d57-46c5-94cc-baa6f3878e2e, clientIf=5
,08-25 21:49:21.984  3762  3826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 21:49:21.984  2695  2893 D BtGatt.GattService: start scan with filters
08-25 21:49:21.985  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 21:49:21.985  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:21.985  2695  2767 D BtGatt.ScanManager: stopping BLe Batch
,08-25 21:49:21.988  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 21:49:21.988  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 21:49:21.988  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:21.988  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-25 21:49:21.990  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 21:49:21.990  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 21:49:21.990  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:21.991  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 21:49:21.991  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:21.991  2695  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 21:49:21.992  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 21:49:21.994  3762  3825 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 21:49:21.997  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:21.997  3762  3825 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 21:49:21.997  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:21.997  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 21:49:21.997  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:21.997  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:21.997  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-25 21:49:21.997  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:21.997  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:21.997  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:21.997  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:21.997  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 21:49:21.997  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 21:49:21.997  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:21.998  3762  3825 D BluetoothAdapter: STATE_ON
08-25 21:49:21.998  2695  2893 D BtGatt.GattService: stopScan() - queue size =0
08-25 21:49:21.999  2695  2767 D BtGatt.ScanManager: handling starting scan
08-25 21:49:21.999  2695  2711 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 21:49:21.999  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:49:21.999  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 21:49:21.999  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 21:49:21.999  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 21:49:21.999  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 21:49:22.002  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:22.002  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 21:49:22.002  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 21:49:22.002  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 21:49:22.002  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:22.004  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:22.004  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:22.004  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:22.004  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.004  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.004  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:22.004  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.004  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.004  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
,08-25 21:49:22.004  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.005  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.005  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.005  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.005  2695  2749 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
08-25 21:49:22.005  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:22.006  2695  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-25 21:49:22.006  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.006  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:22.006  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.006  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.007  3762  3825 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 21:49:22.008  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:22.013  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-25 21:49:22.013  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:22.013  2695  2767 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:22.013  2695  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 21:49:22.013  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:22.013  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:22.013  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:22.013  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:22.013  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:22.013  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:22.013  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:22.013  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:22.015  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:22.015  3762  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:22.017  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:22.019  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:22.019  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 21:49:22.020  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:49:22.020  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 21:49:22.020  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:22.020  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 21:49:22.023  3762  3825 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 21:49:22.023  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 21:49:22.024  2695  2749 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 21:49:22.024  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:22.029  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 21:49:22.030  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 21:49:22.030  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 21:49:22.032  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 21:49:22.032  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:22.036  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 21:49:22.036  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 21:49:22.036  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:22.038  3762  3825 D BluetoothAdapter: STATE_ON
,08-25 21:49:22.040  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 21:49:22.040  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:22.041  2695  2767 D BtGatt.ScanManager: stopping BLe Batch
,08-25 21:49:22.046  2695  2711 D BtGatt.GattService: registerClient() - UUID=12c7a7e1-7f42-4742-9574-603a18cd1d37
,08-25 21:49:22.046  2695  2749 D BtGatt.GattService: onClientRegistered() - UUID=12c7a7e1-7f42-4742-9574-603a18cd1d37, clientIf=5
08-25 21:49:22.046  3762  3826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 21:49:22.047  2695  2706 D BtGatt.GattService: start scan with filters
,08-25 21:49:22.051  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 21:49:22.051  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:22.051  2695  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 21:49:22.051  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 21:49:22.052  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 21:49:22.052  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:22.052  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 21:49:22.056  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:22.056  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 21:49:22.056  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 21:49:22.057  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 21:49:22.059  3762  3825 I io.jxcore.node.ConnectionHelper: start: OK
,08-25 21:49:22.060  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.060  3762  3825 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 21:49:22.060  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.060  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-25 21:49:22.060  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.060  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:22.060  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 21:49:22.060  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:22.060  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 21:49:22.060  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:22.060  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:22.060  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 21:49:22.063  3762  3825 D BluetoothAdapter: STATE_ON
,08-25 21:49:22.064  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 21:49:22.064  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:22.064  2695  2706 D BtGatt.GattService: stopScan() - queue size =0
,08-25 21:49:22.066  2695  2767 D BtGatt.ScanManager: handling starting scan
08-25 21:49:22.066  2695  2893 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 21:49:22.067  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 21:49:22.068  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 21:49:22.068  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 21:49:22.068  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 21:49:22.068  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 21:49:22.072  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:22.072  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 21:49:22.072  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 21:49:22.072  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 21:49:22.073  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:22.074  2695  2749 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-25 21:49:22.074  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:22.074  2695  2767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 21:49:22.075  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:22.075  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:22.075  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:22.075  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.076  3762  3825 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-25 21:49:22.076  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:22.076  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.076  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.076  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.076  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:22.076  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
,08-25 21:49:22.076  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.076  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.076  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.076  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.077  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:22.077  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.078  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.079  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.079  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:49:22.079  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.080  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 21:49:22.080  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:22.080  2695  2767 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:22.080  2695  2767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 21:49:22.081  3762  3825 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 21:49:22.081  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.081  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:22.081  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.081  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.081  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:22.081  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.081  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.081  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.081  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.081  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.081  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:22.081  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.081  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.081  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.084  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.084  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:22.084  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.085  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
,08-25 21:49:22.088  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-25 21:49:22.089  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.089  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.089  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.090  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:49:22.090  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.090  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.090  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
,08-25 21:49:22.091  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.091  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.091  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 21:49:22.091  2695  2749 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 21:49:22.092  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:22.091  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.092  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.092  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.092  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:22.103  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 21:49:22.104  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.104  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.104  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
,08-25 21:49:22.105  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 21:49:22.105  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:22.106  3762  3825 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 21:49:22.106  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:22.106  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:22.107  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.107  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.107  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:22.107  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.107  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.107  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:49:22.108  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.108  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.108  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.108  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-25 21:49:22.109  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.109  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:22.111  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.111  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:22.111  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.111  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
,08-25 21:49:22.113  3762  3825 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-25 21:49:22.113  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.113  2695  2749 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 21:49:22.113  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:22.113  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.114  2695  2767 D BtGatt.ScanManager: stopping BLe Batch
08-25 21:49:22.114  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.114  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.114  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.114  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:22.115  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.115  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.115  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.115  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 21:49:22.115  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.115  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.116  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.116  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:22.118  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 21:49:22.118  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.118  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.119  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
,08-25 21:49:22.119  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-25 21:49:22.119  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 21:49:22.119  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 21:49:22.120  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-25 21:49:22.120  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 21:49:22.120  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 21:49:22.120  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.120  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:22.120  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.120  2695  2749 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 21:49:22.120  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:22.120  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.120  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:22.120  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.120  2695  2767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-25 21:49:22.120  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.121  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.121  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
,08-25 21:49:22.121  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.121  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.121  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:22.121  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.121  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.122  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.122  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:22.122  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.122  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.123  3762  3825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:49:22.123  3762  3825 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 21:49:22.123  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-25 21:49:22.128  2695  2749 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 21:49:22.128  2695  2749 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:22.128  3762  3825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-25 21:49:22.129  3762  3825 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 21:49:22.129  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 21:49:22.129  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 21:49:22.129  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-25 21:49:22.130  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 21:49:22.130  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 21:49:22.130  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 21:49:22.130  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 21:49:22.130  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-25 21:49:22.131  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-25 21:49:22.131  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 21:49:22.131  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 21:49:22.131  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 21:49:22.131  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-25 21:49:22.131  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 21:49:22.131  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 21:49:22.132  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 21:49:22.132  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 21:49:22.132  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-25 21:49:22.132  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 21:49:22.132  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 21:49:22.132  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 21:49:22.132  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 21:49:22.132  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-25 21:49:22.132  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 21:49:22.132  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 21:49:22.133  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 21:49:22.133  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 21:49:22.133  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 21:49:22.133  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 21:49:22.133  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 21:49:22.133  3762  3825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 21:49:22.134  3762  3825 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 21:49:22.134  3762  3825 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-25 21:49:22.134  3762  3825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:49:22.134  3762  3825 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 21:49:22.135  3762  3825 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 21:49:22.135  3762  3825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:49:22.135  3762  3825 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 21:49:22.135  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 21:49:22.140  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 21:49:22.141  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 21:49:22.141  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 21:49:22.143  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-25 21:49:22.143  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 21:49:22.143  3762  3825 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 21:49:22.143  3762  3825 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 21:49:22.143  3762  3825 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 21:49:22.144  3762  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 386)
08-25 21:49:22.145  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.145  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.145  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.146  3762  3846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:49:22.146  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.146  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.146  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.146  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 21:49:22.147  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.147  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.147  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.147  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.147  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.148  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.148  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.148  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.149  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.149  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.149  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.149  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.149  3762  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
08-25 21:49:22.149  3762  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 386)
08-25 21:49:22.149  3762  3825 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 21:49:22.149  3762  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 386)
08-25 21:49:22.149  2695  2882 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-25 21:49:22.150  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.150  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.150  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.150  3762  3846 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
08-25 21:49:22.150  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.150  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.150  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.150  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.150  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.150  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.150  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.150  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.150  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.150  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.150  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.151  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.151  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.151  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.151  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.153  3762  3825 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 21:49:22.153  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.153  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.153  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.153  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.153  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.153  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.153  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.153  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.153  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.153  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.153  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.153  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.154  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.154  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.155  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.155  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.155  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.155  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.156  3762  3825 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 21:49:22.156  3762  3825 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 21:49:22.156  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 21:49:22.156  3762  3825 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 21:49:22.156  3762  3825 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 21:49:22.156  3762  3825 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 21:49:22.156  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 21:49:22.156  3762  3825 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 21:49:22.156  3762  3825 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 21:49:22.156  3762  3825 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 21:49:22.156  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 21:49:22.157  3762  3825 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 21:49:22.157  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.157  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.157  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.157  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.157  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.157  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.157  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.157  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.157  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.157  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.157  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.157  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.157  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.158  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.159  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.159  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.159  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.159  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.160  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.160  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.160  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.160  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.160  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.160  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.160  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.160  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.160  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.161  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.161  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.161  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.161  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.161  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.161  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.161  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.161  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.161  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.161  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.161  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:22.162  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.162  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.162  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.162  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.162  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.162  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.162  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.162  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.162  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.163  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.164  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.164  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.164  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.165  3762  3825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 21:49:22.165  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:22.166  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 21:49:22.167  3762  3825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 21:49:22.167  3762  3825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 21:49:22.167  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 21:49:22.167  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 21:49:22.167  3762  3762 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 21:49:22.168  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.168  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 21:49:22.168  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 21:49:22.168  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 21:49:22.168  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.168  3762  3825 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 21:49:22.168  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.168  3762  3762 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 21:49:22.168  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.168  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:22.168  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:22.168  3762  3848 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 21:49:22.169  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:22.169  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.169  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.169  3762  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 21:49:22.170  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:22.170  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.170  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.170  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:22.170  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.170  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.170  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:22.170  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.170  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.170  3762  3762 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 21:49:22.170  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.171  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.171  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.171  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:22.171  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.171  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.171  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.171  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.171  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.171  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.172  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.173  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.173  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.173  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.174  3762  3825 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 21:49:22.174  3762  3825 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 21:49:22.174  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 21:49:22.174  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 21:49:22.174  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.175  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.175  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.175  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.175  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.175  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.175  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.175  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.175  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.175  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.175  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.175  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.176  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.176  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.179  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.179  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.179  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.179  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.182  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.182  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.182  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.182  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.182  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.183  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.183  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.183  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.183  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.183  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.183  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.183  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.183  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.183  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.184  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.184  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.185  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.185  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.185  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:22.185  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:22.185  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:22.186  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:22.186  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.186  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.186  3762  3825 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28f9ab4 not in the list
08-25 21:49:22.186  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.186  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.186  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:22.186  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.186  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.186  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:22.186  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:22.187  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:22.187  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:22.187  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:22.187  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37fe6dd not in the list
08-25 21:49:22.188  3762  3825 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 21:49:22.188  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 21:49:22.188  3762  3825 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 21:49:22.188  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 21:49:22.188  3762  3825 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 21:49:22.188  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 21:49:22.190  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 21:49:22.190  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 21:49:22.191  3762  3825 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 21:49:22.191  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 21:49:22.191  3762  3825 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 21:49:22.191  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 21:49:22.191  3762  3825 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 21:49:22.191  3762  3825 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 21:49:22.192  3762  3825 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 21:49:22.192  3762  3825 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 21:49:22.192  3762  3825 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 21:49:22.192  3762  3825 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 21:49:22.192  3762  3825 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 21:49:22.192  3762  3825 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 21:49:22.193  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:22.193  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ecbc477 added. We now have 2 listener(s)
08-25 21:49:22.193  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:22.195  3762  3825 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 21:49:22.195   873   883 D WifiService: setWifiEnabled: true pid=3762, uid=10000
08-25 21:49:22.195   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 21:49:22.197  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:22.197  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@da918e4 added. We now have 3 listener(s)
08-25 21:49:22.197  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:22.203  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:22.203  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aed414d added. We now have 4 listener(s)
08-25 21:49:22.203  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:22.204  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:22.204  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f787402 added. We now have 5 listener(s)
08-25 21:49:22.204  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:22.207   873  1395 D WifiService: setWifiEnabled: false pid=3762, uid=10000
,08-25 21:49:22.207   873  1395 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 21:49:22.215  2695  2744 D BluetoothAdapterState: Current state: ON, message: 23
08-25 21:49:22.216  2695  2744 D BluetoothAdapterProperties: Setting state to 13
08-25 21:49:22.216  2695  2744 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 21:49:22.216  2695  2744 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 21:49:22.217  2695  2744 I BluetoothAdapterState: Entering PendingCommandState
08-25 21:49:22.223  2695  2695 D BluetoothMapService: onReceive
08-25 21:49:22.223  2695  2695 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:22.223  2695  2695 D BluetoothMapService: STATE_TURNING_OFF
08-25 21:49:22.224  2695  2695 D BluetoothMapService: MAP Service closeService in
08-25 21:49:22.224  2695  2695 D BluetoothMapMasInstance0: MAP Service shutdown
,08-25 21:49:22.224  2695  2695 D ObexServerSockets0: shutdown(block = true)
,08-25 21:49:22.224  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 21:49:22.225  2695  2695 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-25 21:49:22.225  2695  2695 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-25 21:49:22.225  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:22.226  2695  2894 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 21:49:22.226  2695  2882 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-25 21:49:22.227  2695  2895 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 21:49:22.234  2695  2695 I BtOppRfcommListener: stopping Accept Thread
08-25 21:49:22.234  2695  3424 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 21:49:22.234  2695  3424 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-25 21:49:22.237  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:22.237  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:22.237  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:22.237  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:22.237  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:22.237  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:22.237  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:22.237  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:22.237  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:49:22.239   873   886 I ActivityManager: Start proc 3851:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-25 21:49:22.239  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:22.239  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:22.239  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:22.239  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:22.239  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:22.239  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:22.239  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:22.239  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:22.239  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 21:49:22.239  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:22.239  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:22.239  2695  2749 D BluetoothAdapterProperties: Scan Mode:20
08-25 21:49:22.240  3762  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:22.240  2695  2744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 21:49:22.241  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:22.241  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:22.241  2695  2695 D HeadsetService: Received stop request...Stopping profile...
08-25 21:49:22.243   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 21:49:22.243   873   873 D BluetoothHeadset: Proxy object disconnected
,08-25 21:49:22.243   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 21:49:22.243  1359  1371 D BluetoothHeadset: Proxy object disconnected
08-25 21:49:22.244  2695  2695 D A2dpService: Received stop request...Stopping profile...
08-25 21:49:22.244  1952  1962 D BluetoothHeadset: Proxy object disconnected
08-25 21:49:22.244  2695  2888 D A2dpStateMachine: Exit Disconnected: -1
08-25 21:49:22.245   873  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 21:49:22.245   873  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 21:49:22.245   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 21:49:22.245   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 21:49:22.246  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:22.247   873   873 D BluetoothA2dp: Proxy object disconnected
,08-25 21:49:22.247  2695  2695 V BluetoothAdapterState: isTurningOff()=true
,08-25 21:49:22.248  2695  2695 V BluetoothAdapterState: isTurningOn()=false
08-25 21:49:22.248  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:22.248  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:22.248  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:22.250  1359  1359 D HeadsetProfile: Bluetooth service disconnected
08-25 21:49:22.250  1359  1359 D BluetoothA2dp: Proxy object disconnected
,08-25 21:49:22.251  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:22.254   873  1851 D DhcpClient: Clearing IP address
,08-25 21:49:22.254   370   872 D CommandListener: Clearing all IP addresses on wlan0
08-25 21:49:22.256  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:22.257   370   872 D CommandListener: Setting iface cfg
08-25 21:49:22.257  2695  2695 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-25 21:49:22.258  2695  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 21:49:22.258  2695  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 21:49:22.258  2695  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 21:49:22.258  2695  2749 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 21:49:22.258  2695  2749 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-25 21:49:22.258  2695  2695 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 21:49:22.259  2695  2695 D HidService: Received stop request...Stopping profile...
08-25 21:49:22.259  2695  2695 D HidService: Stopping Bluetooth HidService
,08-25 21:49:22.260  1524  3469 V NativeCrypto: Read error: ssl=0x9b0fb000: I/O error during system call, Connection timed out
,08-25 21:49:22.261  2695  2695 D HealthService: Received stop request...Stopping profile...
08-25 21:49:22.261  1524  3469 V NativeCrypto: SSL shutdown failed: ssl=0x9b0fb000: I/O error during system call, Broken pipe
08-25 21:49:22.262   873  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
08-25 21:49:22.263   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 21:49:22.263   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-25 21:49:22.263   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 21:49:22.266   397   397 E Parcel  : Reading a NULL string not supported here.
08-25 21:49:22.272   873  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 21:49:22.273  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-25 21:49:22.274  1359  1359 D HidProfile: Bluetooth service disconnected
08-25 21:49:22.277  2695  2695 D PanService: Received stop request...Stopping profile...
,08-25 21:49:22.278  2695  2695 V BluetoothAdapterState: isTurningOff()=true
08-25 21:49:22.278  2695  2695 V BluetoothAdapterState: isTurningOn()=false
,08-25 21:49:22.278  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:22.278  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:22.279   873  1866 D DhcpClient: Receive thread stopped
08-25 21:49:22.279  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 21:49:22.279  2695  2695 D BluetoothMapService: Received stop request...Stopping profile...
08-25 21:49:22.279  1359  1359 D PanProfile: Bluetooth service disconnected
,08-25 21:49:22.279  2695  2695 D BluetoothMapService: stop()
08-25 21:49:22.279  2695  2695 D BluetoothMapAppObserver: deinitObservers()
08-25 21:49:22.279  2695  2695 D BluetoothMapAppObserver: removeReceiver()
08-25 21:49:22.281  2695  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 21:49:22.281  1359  1359 D BluetoothMap: Proxy object disconnected
,08-25 21:49:22.281  1359  1359 D MapProfile: Bluetooth service disconnected
08-25 21:49:22.281  2695  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 21:49:22.282  2695  2876 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:49:22.282  2695  2876 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:49:22.282  2695  2876 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:49:22.282  2695  2876 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 21:49:22.282  2695  2749 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 21:49:22.285  2695  2695 V BluetoothAdapterState: isTurningOff()=true
,08-25 21:49:22.285  2695  2695 V BluetoothAdapterState: isTurningOn()=false
,08-25 21:49:22.285  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:22.285  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:22.286  2695  2695 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 21:49:22.286  2695  2695 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 21:49:22.286  2695  2695 V BluetoothAdapterState: isTurningOff()=true
,08-25 21:49:22.286  2695  2695 V BluetoothAdapterState: isTurningOn()=false
,08-25 21:49:22.286  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:22.286  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:22.286  2695  2695 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...,
,08-25 21:49:22.286  2695  2749 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 21:49:22.286  2695  2749 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 21:49:22.287  2695  2695 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 21:49:22.287  2695  2695 V BluetoothAdapterState: isTurningOff()=true
,08-25 21:49:22.287  2695  2695 V BluetoothAdapterState: isTurningOn()=false
08-25 21:49:22.287  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 21:49:22.287  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 21:49:22.288  2695  2695 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-25 21:49:22.289  2695  2695 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 21:49:22.291  2695  2695 D BluetoothMapService: MAP Service closeService in
08-25 21:49:22.291  2695  2695 V BluetoothAdapterState: isTurningOff()=true
08-25 21:49:22.291  2695  2695 V BluetoothAdapterState: isTurningOn()=false
,08-25 21:49:22.291  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:22.291  2695  2695 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:22.291  2695  2744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-25 21:49:22.291  2695  2744 D BluetoothAdapterProperties: Setting state to 15
08-25 21:49:22.291  2695  2744 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-25 21:49:22.292  1359  1371 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 21:49:22.292   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 21:49:22.292  2695  2744 I BluetoothAdapterState: Entering BleOnState
08-25 21:49:22.292  1359  1370 D BluetoothPan: onBluetoothStateChange on: false
08-25 21:49:22.293  1359  2030 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:49:22.293  1952  2112 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:49:22.293  2695  2695 D BluetoothMapService: cleanup()
,08-25 21:49:22.293  1359  1371 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 21:49:22.294  1359  1370 D BluetoothMap: onBluetoothStateChange: up=false
08-25 21:49:22.294   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:49:22.294   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 21:49:22.294  1359  2030 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 21:49:22.295   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:49:22.296  2695  2744 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-25 21:49:22.296  2695  2744 D BluetoothAdapterProperties: Setting state to 16
,08-25 21:49:22.296  2695  2744 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-25 21:49:22.296  2695  2744 D BluetoothAdapterProperties: onBleDisable
,08-25 21:49:22.296  2695  2744 I BluetoothAdapterState: Entering PendingCommandState
,08-25 21:49:22.296  2695  2746 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-25 21:49:22.297  2695  2749 D BluetoothAdapterProperties: Scan Mode:20
,08-25 21:49:22.297  2695  2876 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 21:49:22.297  2695  2876 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 21:49:22.293  2695  2695 D BluetoothMapService: MAP Service closeService in
08-25 21:49:22.304  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:22.304  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:22.304  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:22.304  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:22.304  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:22.304  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:22.304  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:22.304  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:22.304  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:22.304  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:22.305  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:22.308  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:22.308  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:22.308  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:22.308  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:22.308  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:22.308  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:22.308  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:22.308  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:22.308  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:22.309  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:22.309  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:22.310  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:22.311  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:22.317  3851  3851 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-25 21:49:22.326  3851  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 21:49:22.329   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-25 21:49:22.331  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 21:49:22.340   873   882 I art     : Backgrou,nd partial concurrent mark sweep GC freed 38166(2MB) AllocSpace objects, 8(204KB) LOS objects, 33% free, 29MB/43MB, paused 1.169ms total 122.153ms
08-25 21:49:22.340   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5fb4584:true
08-25 21:49:22.346   873  1706 I ActivityManager: Start proc 3867:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
08-25 21:49:22.355   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-25 21:49:22.356   370   872 D CommandListener: Clearing all IP addresses on wlan0
08-25 21:49:22.357   873  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 21:49:22.357   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 21:49:22.359   873   890 D Tethering: MasterInitialState.processMessage what=3
08-25 21:49:22.361  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:22.362  3373  3373 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@bddc4e4 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-25 21:49:22.362  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:22.365   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
08-25 21:49:22.368  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:22.368  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:22.368  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:22.368  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:22.368  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:22.368  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:22.368  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:22.368  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:22.368  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:22.368  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:22.368   873  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 21:49:22.368  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:22.370  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:22.370  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:22.370  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:22.370  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:22.370  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:22.370  3762  3762 V ,io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:22.370  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:22.370  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:22.370  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:22.370  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:22.370  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:22.375  2094  2315 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:49:22.372  2013  2013 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-25 21:49:22.398  3851  3851 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 21:49:22.400  3851  3851 D BluetoothMap: Create BluetoothMap proxy object
08-25 21:49:22.406  3867  3867 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
08-25 21:49:22.408  3851  3851 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-25 21:49:22.416   370   872 E Netd    : netlink response contains error (No such file or directory)
08-25 21:49:22.427  3851  3851 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:49:22.429   873  2266 I ActivityManager: Killing 2973:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-25 21:49:22.498  2695  2749 I bt_hci  : shut_down
,08-25 21:49:22.498  2695  2769 D bt_hwcfg: hw_epilog_process
,08-25 21:49:22.510  2695  2769 I bt_vendor: low_power_mode_cb
,08-25 21:49:22.536  2695  2769 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-25 21:49:22.536  2695  2769 I bt_vendor: epilog_cb
,08-25 21:49:22.536  2695  2769 I bt_hci  : epilog_finished_callback
,08-25 21:49:22.541  2695  2749 I bt_hci_h4: hal_close
,08-25 21:49:22.542  2695  2749 I bt_userial_vendor: device fd = 51 close
,08-25 21:49:22.613  3867  3867 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 21:49:22.613  3867  3867 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 21:49:22.613  3867  3867 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 21:49:22.613  3867  3867 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 21:49:22.613  3867  3867 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.k.d(PG:583)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.e.b(PG:170)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 21:49:22.613  3867  3867 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:22.613  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 21:49:22.614  3867  3867 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at java.io.File.exists(File.java:361)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 21:49:22.6,14  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 21:49:22.614  3867  3867 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:22.614  3867  3867 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 21:49:22.620  3851  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 21:49:22.631  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 21:49:22.637  3851  3851 D DockEventReceiver: finishStartingService: stopping service
08-25 21:49:22.653  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-25 21:49:22.660  1727  1727 D SystemUpdateService: onCreate
08-25 21:49:22.664  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 21:49:22.671  3762  3762 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-25 21:49:22.677  1727  3902 I SystemUpdateService: active receiver: enabled
08-25 21:49:22.686  2695  2746 D bt_stack_manager: event_shut_down_stack finished.
08-25 21:49:22.687  2695  2744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-25 21:49:22.693  2695  2744 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-25 21:49:22.693  2695  2695 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 21:49:22.695  2695  2695 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 21:49:22.695  2695  2695 D BtGatt.GattService: stop()
08-25 21:49:22.695  2695  2695 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 21:49:22.702  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-25 21:49:22.703  2695  2695 V BluetoothAdapterState: isTurningOff()=false
08-25 21:49:22.703  2695  2695 V BluetoothAdapterState: isTurningOn()=false
08-25 21:49:22.703  2695  2695 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:22.704  2695  2695 V BluetoothAdapterState: isBleTurningOff()=true
08-25 21:49:22.704  2695  2744 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 21:49:22.705  2695  2744 D BluetoothAdapterProperties: Setting state to 10
08-25 21:49:22.705  2695  2744 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 21:49:22.706  2695  2744 I BluetoothAdapterState: Entering OffState
08-25 21:49:22.708   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-25 21:49:22.708  1727  2311 I iu.UploadsManager: num queued entries: 0
,08-25 21:49:22.709  1727  3902 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 21:49:22.711  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 21:49:22.712  1727  3902 I SystemUpdateService: network: null; metered: false; mobile allowed: false
08-25 21:49:22.712  1727  2311 I iu.UploadsManager: num updated entries: 0
08-25 21:49:22.713  1727  2311 I iu.SyncManager: NEXT; no task
08-25 21:49:22.714  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 21:49:22.715  1727  3902 I SystemUpdateService: now status is 0 (complete)
,08-25 21:49:22.716  1727  3902 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 21:49:22.716  1727  3902 I SystemUpdateService: file has been verified
08-25 21:49:22.716  1727  3902 I SystemUpdateService: OTA package size = 12249756
,08-25 21:49:22.724  1727  3902 I SystemUpdateService: showing system update notification
,08-25 21:49:22.732   873  2295 I ActivityManager: Start proc 3904:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-25 21:49:22.741  2695  2695 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-25 21:49:22.741  2695  2695 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-25 21:49:22.741  2695  2695 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 21:49:22.742  2695  2746 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 21:49:22.744  2695  2746 D bt_stack_manager: event_clean_up_stack finished.
,08-25 21:49:22.763  2695  2695 I art     : System.exit called, status: 0
,08-25 21:49:22.763  2695  2695 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 21:49:22.792  1727  1727 D SystemUpdateService: onDestroy
,08-25 21:49:22.796   873  2266 I ActivityManager: Killing 3373:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-25 21:49:22.810  3904  3904 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-25 21:49:22.813  3904  3904 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:22.826  3904  3904 D SprintDMHelper: simOperator: 
08-25 21:49:22.826  3904  3904 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 21:49:22.915  3867  3893 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-25 21:49:22.916   873  1950 I ActivityManager: Process com.android.bluetooth (pid 2695) has died
,08-25 21:49:22.930   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8335577:true
,08-25 21:49:22.956   873  2266 I ActivityManager: Start proc 3919:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-25 21:49:22.957   873  2266 I ActivityManager: Killing 3447:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-25 21:49:23.133  2401  3933 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 21:49:23.139   873  1707 I ActivityManager: Start proc 3934:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-25 21:49:23.181  3934  3934 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-25 21:49:23.234  3934  3934 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-25 21:49:23.234  3934  3934 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-25 21:49:23.234  3934  3934 I GAv4    :   adb logcat -s GAv4
,08-25 21:49:23.247  3934  3934 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-25 21:49:23.253  3934  3934 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-25 21:49:23.280  3934  3951 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-25 21:49:23.383  3934  3934 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-25 21:49:23.430  3934  3934 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-25 21:49:23.439  3934  3934 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4420-4423)
,08-25 21:49:23.440  3934  3934 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 21:49:23.453  3934  3934 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9ae2f14}
,08-25 21:49:23.454  3934  3934 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 21:49:23.454  3934  3934 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 21:49:23.463  3934  3934 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-25 21:49:23.464  3934  3934 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-25 21:49:23.481  3934  3934 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-25 21:49:23.494  3934  3934 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 21:49:23.494  3934  3934 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-25 21:49:23.494  3934  3934 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 21:49:23.494  3934  3934 I Adreno  : Build Date                       : 10/20/15
08-25 21:49:23.494  3934  3934 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 21:49:23.494  3934  3934 I Adreno  : Local Branch                     : M14
08-25 21:49:23.494  3934  3934 I Adreno  : Remote Branch                    : 
08-25 21:49:23.494  3934  3934 I Adreno  : Remote Branch                    : 
08-25 21:49:23.494  3934  3934 I Adreno  : Reconstruct Branch               : 
,08-25 21:49:23.563  3934  3934 I NSApplication: Starting up...
,08-25 21:49:23.588  3934  3980 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-25 21:49:23.595   873  1395 I ActivityManager: Start proc 3985:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-25 21:49:23.597   873  1395 I ActivityManager: Killing 1712:android.process.acore/u0a5 (adj 15): empty #17
,08-25 21:49:23.671  3985  3985 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-25 21:49:23.855   873  1945 I ActivityManager: Killing 3619:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-25 21:49:23.884  3534  3543 W art     : Suspending all threads took: 5.100ms
,08-25 21:49:23.927   873  1985 I ActivityManager: Start proc 3999:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-25 21:49:24.011  3999  3999 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-25 21:49:24.058  3999  3999 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-25 21:49:24.074   873  2267 I ActivityManager: Killing 3636:com.android.musicfx/u0a18 (adj 15): empty #17
,08-25 21:49:25.242   873  1398 D WifiService: setWifiEnabled: true pid=3762, uid=10000
,08-25 21:49:25.243   873  1398 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 21:49:25.259   873  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-25 21:49:25.265  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:25.266  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:25.266  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:25.266  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:25.266  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:25.266  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:25.266  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:25.266  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:25.266  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:25.266  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:25.267  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:25.270  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:25.270  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:25.270  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:25.270  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:25.270  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:25.270  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:25.270  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:25.270  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:25.270  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:25.271  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:25.271  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:25.299   873  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-25 21:49:25.300   873  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-25 21:49:25.302   873  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-25 21:49:25.303   873  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-25 21:49:25.303   873  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-25 21:49:25.303   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 21:49:25.303   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 21:49:25.321   370   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 21:49:25.323   370   872 D CommandListener: Setting iface cfg
,08-25 21:49:25.323   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-25 21:49:25.323   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 21:49:25.325   873  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=11.12 rxSuccessRate=15.50 delta 1000 -> 994
08-25 21:49:25.327   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
08-25 21:49:25.327   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 21:49:25.347   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 21:49:25.347   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:25.355   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 21:49:25.425   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 21:49:25.428  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 21:49:25.842  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 21:49:25.886  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 21:49:25.886  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-25 21:49:25.892   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 21:49:25.903   873  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 21:49:25.904   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 21:49:25.904   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:25.930   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:25.950   370   872 D CommandListener: Setting iface cfg
08-25 21:49:25.950   873  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,08-25 21:49:25.964   873  1316 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-25 21:49:25.967   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 21:49:25.972   873  4034 D DhcpClient: Receive thread started
,08-25 21:49:26.053   873  1314 E native  : do suspend false
,08-25 21:49:26.072   873  1851 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 21:49:26.090   873  4034 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172685, domain null
,08-25 21:49:26.092   873  1851 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172685 seconds
,08-25 21:49:26.095   873  1851 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 21:49:26.108   873  4034 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 21:49:26.109   873  1851 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 21:49:26.114   370   872 D CommandListener: Setting iface cfg
,08-25 21:49:26.128   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-25 21:49:26.129   873  1851 D DhcpClient: Scheduling renewal in 86399s
,08-25 21:49:26.147   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 21:49:26.151   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 21:49:26.151   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 21:49:26.152   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 21:49:26.155   873  1316 D ConnectivityService: Adding iface wlan0 to network 101
,08-25 21:49:26.168   873  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 21:49:26.204   873  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 21:49:26.204   873  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-25 21:49:26.205   873  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-25 21:49:26.206   873  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-25 21:49:26.207   873  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-25 21:49:26.214   873  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-25 21:49:26.218   873  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-25 21:49:26.218   873  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-25 21:49:26.219   873  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 21:49:26.219   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-25 21:49:26.220   873  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-25 21:49:26.220   873  1316 D ConnectivityService:    accepting network in place of null
,08-25 21:49:26.221   873  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 21:49:26.232   873  4031 D NetlinkSocketObserver: NeighborEvent{elapsedMs=137217, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 21:49:26.253   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 21:49:26.285   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 21:49:26.292   873  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-25 21:49:26.293   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:26.301   873  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-25 21:49:26.306   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-25 21:49:26.306   873  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:814::200e
,08-25 21:49:26.318  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:26.319  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:26.319  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:26.319  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:26.319  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:26.319  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:26.319  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:26.319  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:26.319  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:26.319  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:26.320  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:26.326  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:26.326  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:26.326  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:26.326  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:26.326  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:26.326  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:26.326  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:26.326  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:26.326  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:26.326  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:26.326  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:26.333  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 21:49:26.334  2013  2013 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-25 21:49:26.337  1727  1727 D SystemUpdateService: onCreate
,08-25 21:49:26.341  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 21:49:26.347  1727  4045 I SystemUpdateService: active receiver: enabled
,08-25 21:49:26.354  1727  4045 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 21:49:26.359  1727  4045 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 21:49:26.360  1727  4045 I SystemUpdateService: now status is 0 (complete)
08-25 21:49:26.360  1727  4045 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 21:49:26.360  1727  4045 I SystemUpdateService: file has been verified
08-25 21:49:26.360  1727  4045 I SystemUpdateService: OTA package size = 12249756
,08-25 21:49:26.364  1727  4045 I SystemUpdateService: showing system update notification
,08-25 21:49:26.371  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 21:49:26.374  1727  2311 I iu.UploadsManager: num queued entries: 0
,08-25 21:49:26.374  1727  2311 I iu.UploadsManager: num updated entries: 0
08-25 21:49:26.375  1727  2311 I iu.SyncManager: NEXT; no task
,08-25 21:49:26.380  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 21:49:26.382  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 21:49:26.383  1727  4048 I MDM     : [176] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-25 21:49:26.383  1727  4048 W BaseAppContext: Using Auth Proxy for data requests.
08-25 21:49:26.384  1727  1727 D SystemUpdateService: onDestroy
,08-25 21:49:26.384  1727  4048 V GoogleAuthProtoRequest: [176] a.<init>: mAccountName set to: thalitester@gmail.com
08-25 21:49:26.386   873  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 19:49:26 GMT], X-Android-Received-Millis=[1472154566385], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472154566352]}
,08-25 21:49:26.387   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 21:49:26.387   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-25 21:49:26.387   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 21:49:26.388  3904  3904 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:26.389   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 21:49:26.393  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 21:49:26.394  3904  3904 D SprintDMHelper: simOperator: 
,08-25 21:49:26.394  3904  3904 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-25 21:49:26.394  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 21:49:26.423  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-25 21:49:26.423  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-25 21:49:26.424  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 21:49:26.424  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 21:49:26.444  1727  4048 E MDM     : [176] SitrepService.a: Error sending sitrep.
,08-25 21:49:26.517  2401  4053 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 21:49:26.549  1524  1537 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 21:49:26.549  1524  1537 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 21:49:26.549  1524  1537 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 21:49:26.549  1524  1537 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 21:49:26.569  3534  4052 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-25 21:49:26.569  3534  4052 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at jdm.a(PG:82)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at jcs.o(PG:406)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at jcn.a(PG:1379)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at jcs.i(PG:143)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at blb.a(PG:3937)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at czp.a(PG:18188)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at czp.a(PG:9081)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at czq.run(PG:1686)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 21:49:26.569  3534  4052 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at jdj.a(PG:4091)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at jdj.a(PG:1125)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at jdm.a(PG:77)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	... 12 more
08-25 21:49:26.569  3534  4052 E HttpOperation: Caused by: faj: BadAuthentication
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at fal.a(PG:38)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	at jdj.a(PG:4089)
08-25 21:49:26.569  3534  4052 E HttpOperation: 	... 14 more
,08-25 21:49:26.641  1524  2072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-25 21:49:26.641  1524  2072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-25 21:49:26.641  1524  2072 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 21:49:26.641  1524  2072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 21:49:26.653  3534  4052 E HttpOperation: [getmobileexperiments] Unexpected exception
08-25 21:49:26.653  3534  4052 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at jdm.a(PG:82)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at jcs.o(PG:406)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at jcn.a(PG:1379)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at jcs.i(PG:143)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at hec.a(PG:42)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at hee.a(PG:102)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at czr.a(PG:65)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at kka.a(PG:108)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at czp.a(PG:19176)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at czp.a(PG:9081)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at czq.run(PG:1686)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-25 21:49:26.653  3534  4052 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at jdj.a(PG:4091)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at jdj.a(PG:1125)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at jdm.a(PG:77)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	... 15 more
08-25 21:49:26.653  3534  4052 E HttpOperation: Caused by: faj: BadAuthentication
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at fal.a(PG:38)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	at jdj.a(PG:4089)
08-25 21:49:26.653  3534  4052 E HttpOperation: 	... 17 more
08-25 21:49:26.653  3534  4052 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-25 21:49:26.653  3534  4052 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at jdm.a(PG:82)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at jcs.o(PG:406)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at jcn.a(PG:1379)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at jcs.i(PG:143)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at hec.a(PG:42)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at hee.a(PG:102)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at czr.a(PG:65)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at kka.a(PG:108)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at czp.a(PG:19176)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at czp.a(PG:9081)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at czq.run(PG:1686)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at jdj.a(PG:4091)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at jdm.a(PG:77)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	... 15 more
08-25 21:49:26.653  3534  4052 E ExperimentLoader: Caused by: faj: BadAuthentication
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at fal.a(PG:38)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	at jdj.a(PG:4089)
08-25 21:49:26.653  3534  4052 E ExperimentLoader: 	... 17 more
,08-25 21:49:26.738   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 129385, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-25 21:49:27.292   873  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-25 21:49:28.193   873   883 I ActivityManager: Killing 2204:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-25 21:49:28.250   873  1985 D WifiService: setWifiEnabled: false pid=3762, uid=10000
,08-25 21:49:28.250   873  1985 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 21:49:28.291  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 21:49:28.295   873  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 21:49:28.295   873  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-25 21:49:28.295   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 21:49:28.296   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:28.301  3934  3934 I art     : Waiting for a blocking GC DisableMovingGc
,08-25 21:49:28.303  3934  3934 I art     : Starting a blocking GC DisableMovingGc
,08-25 21:49:28.309   873  1851 D DhcpClient: Clearing IP address
,08-25 21:49:28.309   370   872 D CommandListener: Clearing all IP addresses on wlan0
,08-25 21:49:28.313   370   872 D CommandListener: Setting iface cfg
,08-25 21:49:28.316  1524  4060 V NativeCrypto: Read error: ssl=0x9ae5f600: I/O error during system call, Connection timed out
,08-25 21:49:28.318  1524  4060 V NativeCrypto: SSL shutdown failed: ssl=0x9ae5f600: I/O error during system call, Broken pipe
,08-25 21:49:28.321   873  1985 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-25 21:49:28.321   873  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-25 21:49:28.322   873  4034 D DhcpClient: Receive thread stopped
08-25 21:49:28.323   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 21:49:28.323   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-25 21:49:28.323   873  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-25 21:49:28.325   873  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
08-25 21:49:28.326   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 21:49:28.327   397   397 E Parcel  : Reading a NULL string not supported here.
08-25 21:49:28.328   370   872 D CommandListener: Clearing all IP addresses on wlan0
08-25 21:49:28.330   873  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-25 21:49:28.365   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 21:49:28.388   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 21:49:28.389   873  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 21:49:28.389   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:28.396   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-25 21:49:28.407  2013  2013 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-25 21:49:28.410   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 21:49:28.409  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 21:49:28.410  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:28.410  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:28.410  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:28.410  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:28.410  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:28.410  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:28.410  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:28.410  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:28.411  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:28.411  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:28.414  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:28.414  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:28.414  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:28.414  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:28.414  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:28.414  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:28.414  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:28.414  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:28.414  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:28.414  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:28.414  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:28.415   873  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 21:49:28.417  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:28.418  2094  2315 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 21:49:28.419  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:28.420  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-25 21:49:28.424  1727  1727 D SystemUpdateService: onCreate
,08-25 21:49:28.426  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-25 21:49:28.435  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-25 21:49:28.436  1727  2311 I iu.UploadsManager: num queued entries: 0
08-25 21:49:28.437  1727  2311 I iu.UploadsManager: num updated entries: 0
08-25 21:49:28.437  1727  2311 I iu.SyncManager: NEXT; no task
08-25 21:49:28.444  1727  4071 I SystemUpdateService: active receiver: enabled
,08-25 21:49:28.447  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-25 21:49:28.447  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 21:49:28.450  3904  3904 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:28.457  1727  4071 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 21:49:28.457  3904  3904 D SprintDMHelper: simOperator: 
08-25 21:49:28.457  3904  3904 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-25 21:49:28.460  1727  4071 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-25 21:49:28.462  1727  4071 I SystemUpdateService: now status is 0 (complete),
08-25 21:49:28.462  1727  4071 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 21:49:28.462  1727  4071 I SystemUpdateService: file has been verified
08-25 21:49:28.462  1727  4071 I SystemUpdateService: OTA package size = 12249756
,08-25 21:49:28.471   370   872 E Netd    : netlink response contains error (No such file or directory)
,08-25 21:49:28.472   873  1316 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 21:49:28.472   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-25 21:49:28.498  2401  4075 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-25 21:49:28.503  1727  4071 I SystemUpdateService: showing system update notification
,08-25 21:49:28.517  1727  1727 D SystemUpdateService: onDestroy
,08-25 21:49:28.550  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 21:49:28.588  1524  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-25 21:49:28.588  1524  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-25 21:49:28.588  1524  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-25 21:49:28.588  1524  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 21:49:28.637  3494  3494 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-25 21:49:28.637  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-25 21:49:28.638  3494  3494 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-25 21:49:31.288   873   890 I ActivityManager: Start proc 4080:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 21:49:31.409  4080  4080 D AdapterServiceConfig: Adding HeadsetService
,08-25 21:49:31.409  4080  4080 D AdapterServiceConfig: Adding A2dpService
08-25 21:49:31.409  4080  4080 D AdapterServiceConfig: Adding HidService
,08-25 21:49:31.410  4080  4080 D AdapterServiceConfig: Adding HealthService
08-25 21:49:31.410  4080  4080 D AdapterServiceConfig: Adding PanService
,08-25 21:49:31.410  4080  4080 D AdapterServiceConfig: Adding GattService
08-25 21:49:31.410  4080  4080 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 21:49:31.426  4080  4080 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 21:49:31.426   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d7fdcd:true
,08-25 21:49:31.431  4080  4080 I bt_bluedroid: init
,08-25 21:49:31.432  4080  4092 I BluetoothAdapterState: Entering OffState
,08-25 21:49:31.437  4080  4093 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 21:49:31.438  4080  4093 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-25 21:49:31.438  4080  4093 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 21:49:31.438  4080  4093 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-25 21:49:31.440  4080  4080 I bt_bluedroid: get_profile_interface socket
,08-25 21:49:31.442  4080  4080 I bt_bluedroid: get_profile_interface sdp
,08-25 21:49:31.447  4080  4096 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 21:49:31.448  4080  4091 I bt_bluedroid: config_hci_snoop_log
,08-25 21:49:31.449  4080  4096 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 21:49:31.451   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 21:49:31.461  4080  4092 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 21:49:31.462  4080  4092 D BluetoothAdapterProperties: Setting state to 14
08-25 21:49:31.462  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 21:49:31.466  4080  4092 D BluetoothBondStateMachine: make
,08-25 21:49:31.470  4080  4097 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 21:49:31.477  4080  4092 I BluetoothAdapterState: Entering PendingCommandState
,08-25 21:49:31.481  4080  4080 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 21:49:31.490  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:31.493  4080  4080 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 21:49:31.494  4080  4080 D BtGatt.GattService: Received start request. Starting profile...
,08-25 21:49:31.496  4080  4080 D BtGatt.GattService: start()
,08-25 21:49:31.496  4080  4080 I bt_bluedroid: get_profile_interface gatt
,08-25 21:49:31.499  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
08-25 21:49:31.500  4080  4080 D BtGatt.AdvertiseManager: advertise manager created
,08-25 21:49:31.513  4080  4080 V BluetoothAdapterState: isTurningOff()=false
,08-25 21:49:31.513  4080  4080 V BluetoothAdapterState: isTurningOn()=false
08-25 21:49:31.514  4080  4080 V BluetoothAdapterState: isBleTurningOn()=true
,08-25 21:49:31.514  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:31.515  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 21:49:31.516  4080  4092 I bt_bluedroid: enable
08-25 21:49:31.517  4080  4093 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 21:49:31.518  4080  4093 I bt_hci  : start_up
,08-25 21:49:31.544  4080  4093 I bt_vendor: alloc value 0xb39a6189
,08-25 21:49:31.544  4080  4093 I bt_vendor: init
08-25 21:49:31.544  4080  4093 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 21:49:31.544  4080  4093 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 21:49:31.650  4080  4093 D bt_hci  : start_up starting async portion
08-25 21:49:31.651  4080  4100 I bt_hci  : event_finish_startup
,08-25 21:49:31.651  4080  4100 I bt_hci_h4: hal_open
,08-25 21:49:31.651  4080  4100 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 21:49:31.661  4080  4100 I bt_userial_vendor: device fd = 51 open
,08-25 21:49:31.692  4080  4100 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 21:49:31.724  4080  4100 D bt_hwcfg: Chipset BCM4354A2
,08-25 21:49:31.725  4080  4100 D bt_hwcfg: Target name = [BCM4354A2]
08-25 21:49:31.726  4080  4100 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 21:49:32.405  4080  4100 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 21:49:32.407  4080  4100 D bt_hwcfg: Settlement delay -- 100 ms
08-25 21:49:32.407  4080  4100 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 21:49:32.524  4080  4100 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 21:49:32.525  4080  4100 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 21:49:32.554  4080  4100 I bt_hwcfg: vendor lib fwcfg completed
,08-25 21:49:32.554  4080  4100 I bt_vendor: firmware callback
,08-25 21:49:32.555  4080  4100 I bt_hci  : firmware_config_callback
,08-25 21:49:32.567  4080  4102 I bt_btu  : btu_task pending for preload complete event
,08-25 21:49:32.567  4080  4102 I bt_btu_task: Bluetooth chip preload is complete
08-25 21:49:32.567  4080  4102 I bt_btu  : btu_task received preload complete event
,08-25 21:49:32.577  4080  4102 I         : BTE_InitTraceLevels -- TRC_HCI
,08-25 21:49:32.577  4080  4102 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 21:49:32.578  4080  4102 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 21:49:32.578  4080  4102 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 21:49:32.578  4080  4102 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 21:49:32.579  4080  4102 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 21:49:32.579  4080  4102 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 21:49:32.579  4080  4102 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 21:49:32.579  4080  4102 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 21:49:32.580  4080  4102 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 21:49:32.580  4080  4102 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 21:49:32.580  4080  4102 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 21:49:32.580  4080  4102 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 21:49:32.581  4080  4102 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-25 21:49:32.581  4080  4102 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 21:49:32.719  4080  4102 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3923d9d
,08-25 21:49:32.719  4080  4102 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3923d9d 
,08-25 21:49:32.727  4080  4096 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 21:49:32.729  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 21:49:32.730  4080  4096 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 21:49:32.735  4080  4096 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 21:49:32.740  4080  4096 D BluetoothAdapterProperties: Scan Mode:20
08-25 21:49:32.740  4080  4096 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 21:49:32.741  4080  4096 D bt_hci  : do_postload posting postload work item
08-25 21:49:32.741  4080  4100 I bt_hci  : event_postload
08-25 21:49:32.741  4080  4100 I bt_vendor: sco_config_cb
08-25 21:49:32.741  4080  4100 I bt_hci  : sco_config_callback postload finished.
,08-25 21:49:32.747  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:32.747  4080  4096 D bt_bte_conf: Device ID record 1 : primary
,08-25 21:49:32.748  4080  4096 D bt_bte_conf:   vendorId            = 000f
,08-25 21:49:32.748  4080  4096 D bt_bte_conf:   vendorIdSource      = 0001
08-25 21:49:32.748  4080  4096 D bt_bte_conf:   product             = 1200
08-25 21:49:32.749  4080  4096 D bt_bte_conf:   version             = 1436
08-25 21:49:32.749  4080  4096 D bt_bte_conf:   clientExecutableURL = 
08-25 21:49:32.749  4080  4096 D bt_bte_conf:   serviceDescription  = 
08-25 21:49:32.749  4080  4096 D bt_bte_conf:   documentationURL    = 
08-25 21:49:32.750  4080  4096 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-25 21:49:32.750  4080  4093 D bt_stack_manager: event_start_up_stack finished
08-25 21:49:32.753  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-25 21:49:32.754  4080  4092 D BluetoothAdapterProperties: Setting state to 15
08-25 21:49:32.754  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-25 21:49:32.754  4080  4100 I bt_vendor: low_power_mode_cb
08-25 21:49:32.755  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:32.756  4080  4092 I BluetoothAdapterState: Entering BleOnState
,08-25 21:49:32.759  4080  4092 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 21:49:32.759  4080  4092 D BluetoothAdapterProperties: Setting state to 11
,08-25 21:49:32.759  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 21:49:32.764  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:32.769  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:32.770  4080  4080 D HeadsetService: Received start request. Starting profile...
08-25 21:49:32.772  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:32.773  4080  4080 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 21:49:32.774  4080  4080 D HeadsetStateMachine: make
,08-25 21:49:32.784  4080  4092 I BluetoothAdapterState: Entering PendingCommandState
,08-25 21:49:32.784  4080  4080 D HeadsetStateMachine: max_hf_connections = 1
08-25 21:49:32.784  4080  4080 I bt_bluedroid: get_profile_interface handsfree
08-25 21:49:32.784  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 21:49:32.785  4080  4096 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-25 21:49:32.790  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:32.791  4080  4080 D A2dpService: Received start request. Starting profile...
08-25 21:49:32.792  4080  4080 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 21:49:32.792  4080  4080 I bt_bluedroid: get_profile_interface avrcp
,08-25 21:49:32.801  4080  4080 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 21:49:32.801  4080  4080 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 21:49:32.801  4080  4080 D A2dpStateMachine: make
,08-25 21:49:32.803  4080  4080 I bt_bluedroid: get_profile_interface a2dp
08-25 21:49:32.803  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 21:49:32.806  4080  4080 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 21:49:32.807  4080  4111 D A2dpStateMachine: Enter Disconnected: -2
08-25 21:49:32.807  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:32.808  4080  4080 D HidService: Received start request. Starting profile...
,08-25 21:49:32.809  4080  4080 I bt_bluedroid: get_profile_interface hidhost
08-25 21:49:32.809  3851  3851 D BluetoothInputDevice: Proxy object connected
08-25 21:49:32.809  4080  4096 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39053e5
08-25 21:49:32.809  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-25 21:49:32.809  4080  4080 D HidService: setHidService(): set to: null
,08-25 21:49:32.809  3851  3851 D HidProfile: Bluetooth service connected
08-25 21:49:32.810  4080  4080 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 21:49:32.811  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:32.811  4080  4080 D HealthService: Received start request. Starting profile...
,08-25 21:49:32.814  4080  4080 I bt_bluedroid: get_profile_interface health
,08-25 21:49:32.814  4080  4080 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 21:49:32.816  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:32.817  3851  3851 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 21:49:32.817  4080  4080 D PanService: Received start request. Starting profile...
,08-25 21:49:32.817  4080  4080 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-25 21:49:32.817  3851  3851 D PanProfile: Bluetooth service connected
08-25 21:49:32.817  4080  4080 I bt_bluedroid: get_profile_interface pan,
08-25 21:49:32.818  4080  4096 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 21:49:32.823  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 21:49:32.826  4080  4080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:32.827  3851  3851 D BluetoothMap: Proxy object connected
,08-25 21:49:32.828  4080  4080 D BluetoothMapService: Received start request. Starting profile...
08-25 21:49:32.828  4080  4080 D BluetoothMapService: start()
08-25 21:49:32.828  3851  3851 D MapProfile: Bluetooth service connected
,08-25 21:49:32.829  3851  3851 D BluetoothMap: getConnectedDevices()
,08-25 21:49:32.831  3851  3851 D BluetoothMap: Bluetooth is Not enabled
,08-25 21:49:32.831  4080  4080 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 21:49:32.833  4080  4080 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-25 21:49:32.833  4080  4080 D BluetoothMapAppObserver: createReceiver()
,08-25 21:49:32.834  4080  4080 D BluetoothMapAppObserver: initObservers()
,08-25 21:49:32.835  4080  4080 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 21:49:32.845  4080  4080 V BluetoothAdapterState: isTurningOff()=false
,08-25 21:49:32.846  4080  4080 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:32.846  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:32.846  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 21:49:32.848  4080  4080 V BluetoothAdapterState: isTurningOff()=false
,08-25 21:49:32.849  4080  4080 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:32.849  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:32.849  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:32.849  4080  4109 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 21:49:32.849  4080  4080 V BluetoothAdapterState: isTurningOff()=false
08-25 21:49:32.849  4080  4080 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:32.849  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:32.849  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:32.850  4080  4080 V BluetoothAdapterState: isTurningOff()=false
,08-25 21:49:32.850  4080  4080 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:32.850  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:32.850  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:32.850  4080  4080 V BluetoothAdapterState: isTurningOff()=false
,08-25 21:49:32.851  4080  4080 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:32.851  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:32.851  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 21:49:32.856  4080  4080 V BluetoothAdapterState: isTurningOff()=false
,08-25 21:49:32.856  4080  4080 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:32.856  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 21:49:32.857  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:32.857  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 21:49:32.857  4080  4092 D BluetoothAdapterProperties: ScanMode =  20
,08-25 21:49:32.857  4080  4092 D BluetoothAdapterProperties: State =  11
,08-25 21:49:32.858  4080  4092 D BluetoothAdapterProperties: Setting state to 12
,08-25 21:49:32.858  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-25 21:49:32.859  4080  4096 D BluetoothAdapterProperties: Scan Mode:21
,08-25 21:49:32.859  3851  3862 D BluetoothPan: onBluetoothStateChange on: true
,08-25 21:49:32.859  4080  4096 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 21:49:32.859  4080  4092 I BluetoothAdapterState: Entering OnState
08-25 21:49:32.859  1359  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 21:49:32.861  1359  1359 D BluetoothInputDevice: Proxy object connected
08-25 21:49:32.861  1359  1359 D HidProfile: Bluetooth service connected
08-25 21:49:32.862  3851  3863 D BluetoothMap: onBluetoothStateChange: up=true
08-25 21:49:32.863   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 21:49:32.864  1359  2030 D BluetoothPan: onBluetoothStateChange on: true
08-25 21:49:32.864  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:32.864  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:32.864  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:32.864  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:32.864  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:32.864  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:32.864  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:32.864  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:32.864   873   873 D BluetoothA2dp: Proxy object connected
08-25 21:49:32.865  4080  4080 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 21:49:32.867  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:32.867  4080  4080 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-25 21:49:32.870  4080  4080 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:49:32.870  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 21:49:32.870  1359  1370 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 21:49:32.870  1359  1359 D PanProfile: Bluetooth service connected
08-25 21:49:32.871  1952  1964 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:49:32.871  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:32.871  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:32.871  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:32.871  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:32.871  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:32.871  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:32.871  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:32.871  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:32.872  1359  1371 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 21:49:32.873  4080  4080 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:49:32.873  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:32.874  1359  1359 D BluetoothA2dp: Proxy object connected
08-25 21:49:32.875  1359  1370 D BluetoothMap: onBluetoothStateChange: up=true
08-25 21:49:32.875  4080  4080 D ObexServerSockets: Succeed to create listening sockets 
,08-25 21:49:32.875  4080  4080 D ObexServerSockets0: startAccept()
,08-25 21:49:32.875  4080  4080 D ObexServerSockets0: prepareForNewConnect()
08-25 21:49:32.877  1359  1359 D BluetoothMap: Proxy object connected
08-25 21:49:32.877  1359  1359 D MapProfile: Bluetooth service connected
,08-25 21:49:32.877  4080  4080 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 21:49:32.877  1359  1359 D BluetoothMap: getConnectedDevices()
08-25 21:49:32.877  4080  4080 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 21:49:32.877   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:49:32.878  3851  3862 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 21:49:32.878   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:49:32.878  3851  3863 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 21:49:32.880  4080  4117 D ObexServerSockets0: Accepting socket connection...
08-25 21:49:32.881  4080  4118 D ObexServerSockets0: Accepting socket connection...
08-25 21:49:32.881  1359  2030 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 21:49:32.882   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 21:49:32.884   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-25 21:49:32.885  4080  4080 D BluetoothMapService: onReceive
,08-25 21:49:32.885  4080  4080 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:32.885  4080  4080 D BluetoothMapService: STATE_ON
08-25 21:49:32.887  3851  3851 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 21:49:32.887  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:32.889  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:32.893  3851  3851 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-25 21:49:32.899  3851  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 21:49:32.902  3851  3851 D BluetoothA2dp: Proxy object connected
,08-25 21:49:32.905  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 21:49:32.909  3851  3851 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:49:32.913  1359  1359 D BluetoothPbap: Proxy object connected
,08-25 21:49:32.913  3851  3851 D BluetoothPbap: Proxy object connected
08-25 21:49:32.913  1359  1359 D PbapServerProfile: Bluetooth service connected
08-25 21:49:32.914  3851  3851 D PbapServerProfile: Bluetooth service connected
,08-25 21:49:32.914  4080  4080 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 21:49:32.914  4080  4080 D ObexServerSockets0: prepareForNewConnect()
,08-25 21:49:32.924  4080  4122 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:49:32.937  4080  4126 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:49:32.938  4080  4126 I BtOppRfcommListener: Accept thread started.
,08-25 21:49:32.972   873   873 D BluetoothHeadset: Proxy object connected
,08-25 21:49:32.972   873   873 D BluetoothHeadset: Proxy object connected
08-25 21:49:32.972   873   873 D BluetoothHeadset: Proxy object connected
08-25 21:49:32.972  1359  1370 D BluetoothHeadset: Proxy object connected
08-25 21:49:32.972  1359  1359 D HeadsetProfile: Bluetooth service connected,
08-25 21:49:32.973  1952  2112 D BluetoothHeadset: Proxy object connected
,08-25 21:49:32.977   873   890 D BluetoothHeadset: Proxy object connected
,08-25 21:49:32.978   873   890 D BluetoothHeadset: Proxy object connected
,08-25 21:49:32.983   873   890 D BluetoothHeadset: Proxy object connected
,08-25 21:49:32.997  3851  3862 D BluetoothHeadset: Proxy object connected
,08-25 21:49:32.998  3851  3851 D HeadsetProfile: Bluetooth service connected
,08-25 21:49:34.224   873  1316 D ConnectivityService: handlePromptUnvalidated 101
,08-25 21:49:34.272  4080  4092 D BluetoothAdapterState: Current state: ON, message: 23
,08-25 21:49:34.273  4080  4092 D BluetoothAdapterProperties: Setting state to 13
08-25 21:49:34.273  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-25 21:49:34.276  4080  4092 D BluetoothAdapterProperties: onBluetoothDisable()
,08-25 21:49:34.280  4080  4092 I BluetoothAdapterState: Entering PendingCommandState
,08-25 21:49:34.291  4080  4080 D BluetoothMapService: onReceive
,08-25 21:49:34.291  4080  4080 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:34.292  4080  4080 D BluetoothMapService: STATE_TURNING_OFF
,08-25 21:49:34.292  4080  4080 D BluetoothMapService: MAP Service closeService in
,08-25 21:49:34.293  4080  4080 D BluetoothMapMasInstance0: MAP Service shutdown
,08-25 21:49:34.293  4080  4080 D ObexServerSockets0: shutdown(block = true)
,08-25 21:49:34.294  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:34.294  4080  4117 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-25 21:49:34.295  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:34.295  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:34.295  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:34.295  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:34.295  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:34.295  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:34.295  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:34.295  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:34.297  4080  4080 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 21:49:34.297  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:34.298  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:34.298  4080  4080 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-25 21:49:34.298  4080  4118 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-25 21:49:34.299  4080  4104 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-25 21:49:34.300  4080  4080 I BtOppRfcommListener: stopping Accept Thread
,08-25 21:49:34.301  4080  4126 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 21:49:34.302  4080  4126 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 21:49:34.303  4080  4096 D BluetoothAdapterProperties: Scan Mode:20
,08-25 21:49:34.303  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-25 21:49:34.303  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:34.303  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:34.303  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:34.303  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:34.303  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:34.303  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 21:49:34.303  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:34.303  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:34.303  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 21:49:34.305  3762  3762 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 21:49:34.305  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 21:49:34.308  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:34.306  4080  4080 D HeadsetService: Received stop request...Stopping profile...
08-25 21:49:34.310   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 21:49:34.311  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:34.311  3851  3863 D BluetoothHeadset: Proxy object disconnected
08-25 21:49:34.311   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 21:49:34.311   873   873 D BluetoothHeadset: Proxy object disconnected
08-25 21:49:34.312  1359  1370 D BluetoothHeadset: Proxy object disconnected
,08-25 21:49:34.312  1359  1359 D HeadsetProfile: Bluetooth service disconnected
08-25 21:49:34.312  1952  2112 D BluetoothHeadset: Proxy object disconnected
08-25 21:49:34.313  4080  4080 D A2dpService: Received stop request...Stopping profile...
,08-25 21:49:34.313  4080  4111 D A2dpStateMachine: Exit Disconnected: -1
08-25 21:49:34.314  3851  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 21:49:34.315   873   873 D BluetoothA2dp: Proxy object disconnected
08-25 21:49:34.316  1359  1359 D BluetoothA2dp: Proxy object disconnected
,08-25 21:49:34.317  4080  4080 D HidService: Received stop request...Stopping profile...
,08-25 21:49:34.317  4080  4080 D HidService: Stopping Bluetooth HidService
08-25 21:49:34.318  1359  1359 D BluetoothInputDevice: Proxy object disconnected
08-25 21:49:34.318  1359  1359 D HidProfile: Bluetooth service disconnected
,08-25 21:49:34.319  4080  4080 D HealthService: Received stop request...Stopping profile...
,08-25 21:49:34.321  4080  4080 V BluetoothAdapterState: isTurningOff()=true
,08-25 21:49:34.321  4080  4080 V BluetoothAdapterState: isTurningOn()=false
,08-25 21:49:34.321  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:34.321  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 21:49:34.322  4080  4080 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 21:49:34.323  4080  4080 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-25 21:49:34.323  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-25 21:49:34.323  4080  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 21:49:34.323  4080  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 21:49:34.323  4080  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 21:49:34.323  4080  4096 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
08-25 21:49:34.323  4080  4080 D PanService: Received stop request...Stopping profile...
,08-25 21:49:34.326  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 21:49:34.326  1359  1359 D PanProfile: Bluetooth service disconnected
,08-25 21:49:34.327  3851  3851 D HeadsetProfile: Bluetooth service disconnected
,08-25 21:49:34.327  3851  3851 D BluetoothA2dp: Proxy object disconnected
08-25 21:49:34.328  3851  3851 D BluetoothInputDevice: Proxy object disconnected
08-25 21:49:34.328  3851  3851 D HidProfile: Bluetooth service disconnected
,08-25 21:49:34.329  4080  4080 D BluetoothMapService: Received stop request...Stopping profile...
,08-25 21:49:34.329  4080  4080 D BluetoothMapService: stop()
08-25 21:49:34.330  4080  4080 D BluetoothMapAppObserver: deinitObservers()
,08-25 21:49:34.330  4080  4080 D BluetoothMapAppObserver: removeReceiver()
08-25 21:49:34.331  1359  1359 D BluetoothMap: Proxy object disconnected
,08-25 21:49:34.331  1359  1359 D MapProfile: Bluetooth service disconnected
,08-25 21:49:34.331  4080  4080 V BluetoothAdapterState: isTurningOff()=true
08-25 21:49:34.331  4080  4080 V BluetoothAdapterState: isTurningOn()=false
08-25 21:49:34.332  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false,
08-25 21:49:34.332  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 21:49:34.333  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-25 21:49:34.333  4080  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-25 21:49:34.333  4080  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 21:49:34.333  4080  4102 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 21:49:34.333  4080  4102 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 21:49:34.334  4080  4102 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 21:49:34.334  4080  4102 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-25 21:49:34.334  4080  4080 V BluetoothAdapterState: isTurningOff()=true
08-25 21:49:34.334  4080  4080 V BluetoothAdapterState: isTurningOn()=false
08-25 21:49:34.335  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:34.335  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:34.335  4080  4080 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-25 21:49:34.335  4080  4096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-25 21:49:34.335  4080  4080 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 21:49:34.336  4080  4080 V BluetoothAdapterState: isTurningOff()=true
08-25 21:49:34.336  4080  4080 V BluetoothAdapterState: isTurningOn()=false
08-25 21:49:34.336  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:34.336  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:34.337  4080  4080 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-25 21:49:34.337  4080  4096 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-25 21:49:34.337  4080  4080 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 21:49:34.337  4080  4080 V BluetoothAdapterState: isTurningOff()=true
08-25 21:49:34.337  4080  4080 V BluetoothAdapterState: isTurningOn()=false
,08-25 21:49:34.337  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:34.338  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:34.339  4080  4080 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 21:49:34.339  3851  3851 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:49:34.339  4080  4080 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 21:49:34.340  4080  4080 D BluetoothMapService: MAP Service closeService in
08-25 21:49:34.340  4080  4080 V BluetoothAdapterState: isTurningOff()=true
08-25 21:49:34.340  4080  4080 V BluetoothAdapterState: isTurningOn()=false
08-25 21:49:34.340  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:34.340  4080  4080 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:34.341  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-25 21:49:34.341  4080  4080 D BluetoothMapService: cleanup()
08-25 21:49:34.341  4080  4080 D BluetoothMapService: MAP Service closeService in
08-25 21:49:34.341  4080  4092 D BluetoothAdapterProperties: Setting state to 15
08-25 21:49:34.341  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-25 21:49:34.341  4080  4092 I BluetoothAdapterState: Entering BleOnState
08-25 21:49:34.341  3851  3851 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 21:49:34.342  3851  3851 D PanProfile: Bluetooth service disconnected
08-25 21:49:34.343  3851  3851 D BluetoothMap: Proxy object disconnected
,08-25 21:49:34.343  3851  3851 D MapProfile: Bluetooth service disconnected
08-25 21:49:34.343  3851  3862 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 21:49:34.343  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 21:49:34.343  3851  3851 D BluetoothPbap: Proxy object disconnected
,08-25 21:49:34.343  3851  3851 D PbapServerProfile: Bluetooth service disconnected
08-25 21:49:34.344  1359  1359 D BluetoothPbap: Proxy object disconnected
08-25 21:49:34.344  1359  1359 D PbapServerProfile: Bluetooth service disconnected
08-25 21:49:34.344  3851  3863 D BluetoothPan: onBluetoothStateChange on: false
08-25 21:49:34.347  1359  2030 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 21:49:34.348  3851  3863 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 21:49:34.349   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 21:49:34.349  1359  1370 D BluetoothPan: onBluetoothStateChange on: false
08-25 21:49:34.350  1359  1371 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:49:34.350  1952  1962 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 21:49:34.350  1359  2030 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 21:49:34.351  1359  1370 D BluetoothMap: onBluetoothStateChange: up=false
,08-25 21:49:34.354   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 21:49:34.354  3851  4129 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:49:34.354  3851  3862 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 21:49:34.355   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 21:49:34.355  3851  3863 D BluetoothPbap: onBluetoothStateChange: up=false
,08-25 21:49:34.355  1359  1371 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 21:49:34.356   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-25 21:49:34.356  4080  4092 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-25 21:49:34.356  4080  4092 D BluetoothAdapterProperties: Setting state to 16
08-25 21:49:34.356  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-25 21:49:34.357  4080  4092 D BluetoothAdapterProperties: onBleDisable
08-25 21:49:34.357  4080  4092 I BluetoothAdapterState: Entering PendingCommandState
,08-25 21:49:34.357  4080  4093 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-25 21:49:34.358  4080  4102 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-25 21:49:34.358  4080  4102 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-25 21:49:34.362  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:34.363  4080  4096 D BluetoothAdapterProperties: Scan Mode:20
,08-25 21:49:34.363  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:34.364  3851  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-25 21:49:34.365  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:34.366  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:34.367  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 21:49:34.373  3851  3851 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:49:34.560  4080  4096 I bt_hci  : shut_down
,08-25 21:49:34.560  4080  4100 I bt_vendor: low_power_mode_cb
08-25 21:49:34.560  4080  4100 D bt_hwcfg: hw_epilog_process
,08-25 21:49:34.585  4080  4100 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-25 21:49:34.585  4080  4100 I bt_vendor: epilog_cb
08-25 21:49:34.585  4080  4100 I bt_hci  : epilog_finished_callback
,08-25 21:49:34.598  4080  4096 I bt_hci_h4: hal_close
,08-25 21:49:34.600  4080  4096 I bt_userial_vendor: device fd = 51 close
,08-25 21:49:34.726  4080  4093 D bt_stack_manager: event_shut_down_stack finished.
,08-25 21:49:34.727  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-25 21:49:34.732  4080  4080 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 21:49:34.732  4080  4092 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-25 21:49:34.734  4080  4080 D BtGatt.GattService: Received stop request...Stopping profile...
,08-25 21:49:34.734  4080  4080 D BtGatt.GattService: stop()
,08-25 21:49:34.735  4080  4080 D BtGatt.AdvertiseManager: advertise clients cleared
,08-25 21:49:34.740  4080  4080 V BluetoothAdapterState: isTurningOff()=false
,08-25 21:49:34.740  4080  4080 V BluetoothAdapterState: isTurningOn()=false
08-25 21:49:34.740  4080  4080 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 21:49:34.741  4080  4080 V BluetoothAdapterState: isBleTurningOff()=true
08-25 21:49:34.741  4080  4092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-25 21:49:34.742  4080  4092 D BluetoothAdapterProperties: Setting state to 10
08-25 21:49:34.742  4080  4092 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-25 21:49:34.744  4080  4092 I BluetoothAdapterState: Entering OffState
08-25 21:49:34.748   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-25 21:49:34.777  4080  4080 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-25 21:49:34.777  4080  4080 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-25 21:49:34.778  4080  4093 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-25 21:49:34.788  4080  4093 D bt_stack_manager: event_clean_up_stack finished.
,08-25 21:49:34.790  4080  4080 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-25 21:49:34.793  4080  4080 I art     : System.exit called, status: 0
,08-25 21:49:34.793  4080  4080 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-25 21:49:34.843   873  2265 I ActivityManager: Process com.android.bluetooth (pid 4080) has died
,08-25 21:49:37.269  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 21:49:37.270  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:39.233   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-25 21:49:39.246  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-25 21:49:39.249   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-25 21:49:39.249   873   893 I Adreno  : Build Date                       : 10/20/15
08-25 21:49:39.249   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-25 21:49:39.249   873   893 I Adreno  : Local Branch                     : M14
08-25 21:49:39.249   873   893 I Adreno  : Remote Branch                    : 
08-25 21:49:39.249   873   893 I Adreno  : Remote Branch                    : 
08-25 21:49:39.249   873   893 I Adreno  : Reconstruct Branch               : 
,08-25 21:49:39.288   280   302 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (165 us)
,08-25 21:49:39.923  3762  3762 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 21:49:39.923  3762  3762 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-25 21:49:39.959  3762  3762 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7fedfb6 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f50df50, 16908290=android.view.AbsSavedState$1@f50df50}, android:focusedViewId=100}]}]
,08-25 21:49:39.960  3762  3762 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-25 21:49:39.960  3762  3762 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-25 21:49:39.960  3762  3762 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-25 21:49:39.964   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-25 21:49:39.981   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-25 21:49:39.986   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-25 21:49:39.986   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
08-25 21:49:39.986   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-25 21:49:40.007   873   882 I art     : Background partial concurrent mark sweep GC freed 20551(1774KB) AllocSpace objects, 15(596KB) LOS objects, 33% free, 29MB/43MB, paused 1.138ms total 103.546ms
,08-25 21:49:40.212   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-25 21:49:40.217   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-25 21:49:40.217   873  1339 D SurfaceControl: Excessive delay in setPowerMode(): 231ms
,08-25 21:49:40.219   873   893 I DreamManagerService: Entering dreamland.
,08-25 21:49:40.220   873   893 I PowerManagerService: Dozing...
,08-25 21:49:40.221   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-25 21:49:40.274  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:40.274  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@159a549 added. We now have 6 listener(s)
,08-25 21:49:40.274  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:40.277  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:40.277  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2fdce4e added. We now have 7 listener(s)
08-25 21:49:40.277  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:40.278  3762  3825 I System.out: IsBluetoothEnabled
,08-25 21:49:40.284  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:40.309   873   890 I ActivityManager: Start proc 4141:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-25 21:49:40.311   374  1323 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-25 21:49:40.311   374  1323 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-25 21:49:40.318   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 21:49:40.323  1930  4147 D NfcService: Discovery configuration equal, not updating.
,08-25 21:49:40.328   873  1314 E native  : do suspend false
,08-25 21:49:40.349   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 21:49:40.352   873  1314 E native  : do suspend true
,08-25 21:49:40.394  4141  4141 D AdapterServiceConfig: Adding HeadsetService
,08-25 21:49:40.394  4141  4141 D AdapterServiceConfig: Adding A2dpService
,08-25 21:49:40.394  4141  4141 D AdapterServiceConfig: Adding HidService
,08-25 21:49:40.394  4141  4141 D AdapterServiceConfig: Adding HealthService
,08-25 21:49:40.395  4141  4141 D AdapterServiceConfig: Adding PanService
,08-25 21:49:40.395  4141  4141 D AdapterServiceConfig: Adding GattService
08-25 21:49:40.395  4141  4141 D AdapterServiceConfig: Adding BluetoothMapService
,08-25 21:49:40.409  4141  4141 D BluetoothAdapterState: make() - Creating AdapterState
,08-25 21:49:40.409   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b15345:true
,08-25 21:49:40.414  4141  4141 I bt_bluedroid: init
,08-25 21:49:40.415  4141  4155 I BluetoothAdapterState: Entering OffState
,08-25 21:49:40.418  4141  4156 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-25 21:49:40.418  4141  4156 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 21:49:40.418  4141  4156 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-25 21:49:40.418  4141  4156 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 21:49:40.419  4141  4141 I bt_bluedroid: get_profile_interface socket
,08-25 21:49:40.421  4141  4141 I bt_bluedroid: get_profile_interface sdp
,08-25 21:49:40.425  4141  4159 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-25 21:49:40.426   374  1322 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-25 21:49:40.427   374  1322 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-25 21:49:40.428  4141  4159 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 21:49:40.433  4141  4154 I bt_bluedroid: config_hci_snoop_log
,08-25 21:49:40.435   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-25 21:49:40.443  4141  4155 D BluetoothAdapterState: Current state: OFF, message: 0
,08-25 21:49:40.443  4141  4155 D BluetoothAdapterProperties: Setting state to 14
,08-25 21:49:40.443  4141  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-25 21:49:40.449  4141  4155 D BluetoothBondStateMachine: make
,08-25 21:49:40.453  4141  4160 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-25 21:49:40.466  4141  4155 I BluetoothAdapterState: Entering PendingCommandState
,08-25 21:49:40.469  4141  4141 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-25 21:49:40.473  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:40.474  4141  4141 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-25 21:49:40.475  4141  4141 D BtGatt.GattService: Received start request. Starting profile...
08-25 21:49:40.475  4141  4141 D BtGatt.GattService: start()
08-25 21:49:40.476  4141  4141 I bt_bluedroid: get_profile_interface gatt
,08-25 21:49:40.477  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
08-25 21:49:40.477  4141  4141 D BtGatt.AdvertiseManager: advertise manager created
,08-25 21:49:40.486  4141  4141 V BluetoothAdapterState: isTurningOff()=false
,08-25 21:49:40.486  4141  4141 V BluetoothAdapterState: isTurningOn()=false
08-25 21:49:40.486  4141  4141 V BluetoothAdapterState: isBleTurningOn()=true
08-25 21:49:40.486  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:40.486  4141  4155 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-25 21:49:40.487  4141  4155 I bt_bluedroid: enable
08-25 21:49:40.487  4141  4156 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-25 21:49:40.487  4141  4156 I bt_hci  : start_up
,08-25 21:49:40.495  4141  4156 I bt_vendor: alloc value 0xb39a6189
,08-25 21:49:40.495  4141  4156 I bt_vendor: init
08-25 21:49:40.495  4141  4156 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-25 21:49:40.495  4141  4156 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-25 21:49:40.603  4141  4156 D bt_hci  : start_up starting async portion
,08-25 21:49:40.603  4141  4165 I bt_hci  : event_finish_startup
08-25 21:49:40.604  4141  4165 I bt_hci_h4: hal_open
08-25 21:49:40.604  4141  4165 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-25 21:49:40.612  4141  4165 I bt_userial_vendor: device fd = 51 open
,08-25 21:49:40.646  4141  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 21:49:40.678  4141  4165 D bt_hwcfg: Chipset BCM4354A2
08-25 21:49:40.678  4141  4165 D bt_hwcfg: Target name = [BCM4354A2]
,08-25 21:49:40.679  4141  4165 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-25 21:49:41.347  4141  4165 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-25 21:49:41.348  4141  4165 D bt_hwcfg: Settlement delay -- 100 ms
08-25 21:49:41.348  4141  4165 I bt_hwcfg: Setting fw settlement delay to 100 
,08-25 21:49:41.465  4141  4165 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-25 21:49:41.466  4141  4165 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-25 21:49:41.496  4141  4165 I bt_hwcfg: vendor lib fwcfg completed
08-25 21:49:41.496  4141  4165 I bt_vendor: firmware callback
,08-25 21:49:41.496  4141  4165 I bt_hci  : firmware_config_callback
,08-25 21:49:41.509  4141  4169 I bt_btu  : btu_task pending for preload complete event
08-25 21:49:41.509  4141  4169 I bt_btu_task: Bluetooth chip preload is complete
08-25 21:49:41.509  4141  4169 I bt_btu  : btu_task received preload complete event
,08-25 21:49:41.519  4141  4169 I         : BTE_InitTraceLevels -- TRC_HCI,
08-25 21:49:41.519  4141  4169 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 21:49:41.519  4141  4169 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 21:49:41.519  4141  4169 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-25 21:49:41.520  4141  4169 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-25 21:49:41.520  4141  4169 I         : BTE_InitTraceLevels -- TRC_A2D
,08-25 21:49:41.520  4141  4169 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 21:49:41.521  4141  4169 I         : BTE_InitTraceLevels -- TRC_BTM
,08-25 21:49:41.521  4141  4169 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 21:49:41.521  4141  4169 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 21:49:41.521  4141  4169 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 21:49:41.522  4141  4169 I         : BTE_InitTraceLevels -- TRC_GATT
,08-25 21:49:41.522  4141  4169 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 21:49:41.522  4141  4169 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 21:49:41.522  4141  4169 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 21:49:41.655  4141  4169 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3923d9d
,08-25 21:49:41.655  4141  4169 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3923d9d 
,08-25 21:49:41.667  4141  4159 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-25 21:49:41.670  4141  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-25 21:49:41.670  4141  4159 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-25 21:49:41.673  4141  4159 D BluetoothAdapterProperties: Name is: Nexus 6
,08-25 21:49:41.677  4141  4159 D BluetoothAdapterProperties: Scan Mode:20
,08-25 21:49:41.678  4141  4159 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-25 21:49:41.682  4141  4159 D bt_hci  : do_postload posting postload work item
,08-25 21:49:41.683  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:41.684  4141  4165 I bt_hci  : event_postload
08-25 21:49:41.684  4141  4165 I bt_vendor: sco_config_cb
,08-25 21:49:41.684  4141  4165 I bt_hci  : sco_config_callback postload finished.
,08-25 21:49:41.688  4141  4159 D bt_bte_conf: Device ID record 1 : primary
,08-25 21:49:41.688  4141  4159 D bt_bte_conf:   vendorId            = 000f
,08-25 21:49:41.688  4141  4159 D bt_bte_conf:   vendorIdSource      = 0001
08-25 21:49:41.689  4141  4159 D bt_bte_conf:   product             = 1200
,08-25 21:49:41.689  4141  4159 D bt_bte_conf:   version             = 1436
08-25 21:49:41.689  4141  4159 D bt_bte_conf:   clientExecutableURL = 
,08-25 21:49:41.689  4141  4159 D bt_bte_conf:   serviceDescription  = 
08-25 21:49:41.690  4141  4159 D bt_bte_conf:   documentationURL    = 
08-25 21:49:41.690  4141  4159 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-25 21:49:41.690  4141  4156 D bt_stack_manager: event_start_up_stack finished
08-25 21:49:41.691  4141  4155 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-25 21:49:41.692  4141  4165 I bt_vendor: low_power_mode_cb
08-25 21:49:41.692  4141  4155 D BluetoothAdapterProperties: Setting state to 15
08-25 21:49:41.692  4141  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-25 21:49:41.693  4141  4155 I BluetoothAdapterState: Entering BleOnState
,08-25 21:49:41.699  4141  4155 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-25 21:49:41.699  4141  4155 D BluetoothAdapterProperties: Setting state to 11
,08-25 21:49:41.699  4141  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-25 21:49:41.709  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:41.713  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:41.715  4141  4141 D HeadsetService: Received start request. Starting profile...
,08-25 21:49:41.722  4141  4141 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 21:49:41.722  4141  4141 D HeadsetStateMachine: make
,08-25 21:49:41.729  4141  4141 D HeadsetStateMachine: max_hf_connections = 1
,08-25 21:49:41.729  4141  4155 I BluetoothAdapterState: Entering PendingCommandState
08-25 21:49:41.730  4141  4141 I bt_bluedroid: get_profile_interface handsfree
08-25 21:49:41.730  4141  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-25 21:49:41.730  4141  4159 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-25 21:49:41.735  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:41.736  4141  4141 D A2dpService: Received start request. Starting profile...
,08-25 21:49:41.738  4141  4141 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-25 21:49:41.739  4141  4141 I bt_bluedroid: get_profile_interface avrcp
,08-25 21:49:41.751  4141  4141 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-25 21:49:41.752  4141  4141 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 21:49:41.752  4141  4141 D A2dpStateMachine: make
,08-25 21:49:41.754  4141  4141 I bt_bluedroid: get_profile_interface a2dp
,08-25 21:49:41.757  4141  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-25 21:49:41.761  4141  4177 D A2dpStateMachine: Enter Disconnected: -2
,08-25 21:49:41.763  4141  4141 I BluetoothHidServiceJni: classInitNative: succeeds
,08-25 21:49:41.765  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:41.767  4141  4141 D HidService: Received start request. Starting profile...
,08-25 21:49:41.767  4141  4141 I bt_bluedroid: get_profile_interface hidhost
,08-25 21:49:41.768  4141  4159 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39053e5
,08-25 21:49:41.768  4141  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-25 21:49:41.769  4141  4141 D HidService: setHidService(): set to: null
,08-25 21:49:41.770  4141  4141 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 21:49:41.771  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:41.771  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 21:49:41.772  4141  4141 D HealthService: Received start request. Starting profile...
,08-25 21:49:41.774  4141  4141 I bt_bluedroid: get_profile_interface health,
,08-25 21:49:41.775  4141  4141 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-25 21:49:41.776  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
08-25 21:49:41.776  4141  4141 D PanService: Received start request. Starting profile...
08-25 21:49:41.777  4141  4141 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 21:49:41.777  4141  4141 I bt_bluedroid: get_profile_interface pan
08-25 21:49:41.778  4141  4159 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-25 21:49:41.783  4141  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
08-25 21:49:41.784  4141  4141 D BluetoothMapService: Received start request. Starting profile...
08-25 21:49:41.784  4141  4141 D BluetoothMapService: start()
,08-25 21:49:41.788  4141  4141 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-25 21:49:41.789  4141  4141 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-25 21:49:41.789  4141  4141 D BluetoothMapAppObserver: createReceiver()
,08-25 21:49:41.792  4141  4141 D BluetoothMapAppObserver: initObservers()
,08-25 21:49:41.792  4141  4141 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-25 21:49:41.816  4141  4175 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-25 21:49:41.816  4141  4141 V BluetoothAdapterState: isTurningOff()=false
08-25 21:49:41.816  4141  4141 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:41.816  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:41.816  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 21:49:41.822  4141  4141 V BluetoothAdapterState: isTurningOff()=false
08-25 21:49:41.822  4141  4141 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:41.823  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:41.823  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 21:49:41.823  4141  4141 V BluetoothAdapterState: isTurningOff()=false
08-25 21:49:41.823  4141  4141 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:41.823  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 21:49:41.823  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:41.824  4141  4141 V BluetoothAdapterState: isTurningOff()=false
08-25 21:49:41.824  4141  4141 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:41.824  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:41.824  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:41.825  4141  4141 V BluetoothAdapterState: isTurningOff()=false
08-25 21:49:41.825  4141  4141 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:41.825  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
08-25 21:49:41.826  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
,08-25 21:49:41.826  4141  4141 V BluetoothAdapterState: isTurningOff()=false
,08-25 21:49:41.826  4141  4141 V BluetoothAdapterState: isTurningOn()=true
08-25 21:49:41.826  4141  4141 V BluetoothAdapterState: isBleTurningOn()=false
,08-25 21:49:41.826  4141  4141 V BluetoothAdapterState: isBleTurningOff()=false
08-25 21:49:41.826  4141  4155 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-25 21:49:41.827  4141  4155 D BluetoothAdapterProperties: ScanMode =  20
08-25 21:49:41.827  4141  4155 D BluetoothAdapterProperties: State =  11
08-25 21:49:41.829  4141  4155 D BluetoothAdapterProperties: Setting state to 12
08-25 21:49:41.829  4141  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 21:49:41.830  4141  4159 D BluetoothAdapterProperties: Scan Mode:21
08-25 21:49:41.829  4141  4155 I BluetoothAdapterState: Entering OnState
08-25 21:49:41.830  4141  4159 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 21:49:41.833  4141  4141 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-25 21:49:41.833  4141  4141 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-25 21:49:41.835  4141  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:49:41.835  3851  4129 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 21:49:41.839  4141  4141 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:49:41.841  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:41.841  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:41.841  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:41.841  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:41.841  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:41.841  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:41.841  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:41.841  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:41.841  3851  3862 D BluetoothPan: onBluetoothStateChange on: true
08-25 21:49:41.841  4141  4141 D ObexServerSockets: Succeed to create listening sockets 
,08-25 21:49:41.841  4141  4141 D ObexServerSockets0: startAccept()
08-25 21:49:41.841  4141  4141 D ObexServerSockets0: prepareForNewConnect()
08-25 21:49:41.844  1359  1371 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 21:49:41.845  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:41.848  3851  3863 D BluetoothMap: onBluetoothStateChange: up=true
,08-25 21:49:41.849   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-25 21:49:41.850  4141  4141 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-25 21:49:41.850  1359  2030 D BluetoothPan: onBluetoothStateChange on: true
08-25 21:49:41.850  4141  4141 D BluetoothSdpJni: SDP Create record success - handle: 0
08-25 21:49:41.852  4141  4184 D ObexServerSockets0: Accepting socket connection...
08-25 21:49:41.852  1359  1370 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:49:41.853  4141  4185 D ObexServerSockets0: Accepting socket connection...
08-25 21:49:41.853  1952  2075 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:49:41.854  1359  1371 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 21:49:41.855   873   873 D BluetoothA2dp: Proxy object connected
08-25 21:49:41.856  3851  3851 D BluetoothA2dp: Proxy object connected
08-25 21:49:41.857  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 21:49:41.857  1359  1359 D PanProfile: Bluetooth service connected
08-25 21:49:41.857  1359  1359 D BluetoothA2dp: Proxy object connected
08-25 21:49:41.858  1359  2030 D BluetoothMap: onBluetoothStateChange: up=true
08-25 21:49:41.859  1359  1359 D BluetoothInputDevice: Proxy object connected
08-25 21:49:41.859  1359  1359 D HidProfile: Bluetooth service connected
08-25 21:49:41.860   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:49:41.860  3851  4129 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:49:41.860  3851  3862 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 21:49:41.862  1359  1359 D BluetoothMap: Proxy object connected
,08-25 21:49:41.862  1359  1359 D MapProfile: Bluetooth service connected
08-25 21:49:41.862   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 21:49:41.862  1359  1359 D BluetoothMap: getConnectedDevices()
08-25 21:49:41.862  3851  4129 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 21:49:41.864  1359  2030 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 21:49:41.864  3851  3851 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 21:49:41.864  3851  3851 D PanProfile: Bluetooth service connected
08-25 21:49:41.864  3851  3851 D BluetoothMap: Proxy object connected
08-25 21:49:41.864  3851  3851 D MapProfile: Bluetooth service connected
08-25 21:49:41.864  3851  3851 D BluetoothMap: getConnectedDevices()
08-25 21:49:41.865   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 21:49:41.867   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-25 21:49:41.869  4141  4141 D BluetoothMapService: onReceive
08-25 21:49:41.870  4141  4141 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 21:49:41.870  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:41.870  4141  4141 D BluetoothMapService: STATE_ON
08-25 21:49:41.872  3851  3851 D BluetoothInputDevice: Proxy object connected
08-25 21:49:41.872  3851  3851 D HidProfile: Bluetooth service connected
,08-25 21:49:41.885  3851  3851 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-25 21:49:41.893  4141  4141 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-25 21:49:41.893  4141  4141 D ObexServerSockets0: prepareForNewConnect()
08-25 21:49:41.894  1524  1524 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 21:49:41.894  3851  3851 D DockEventReceiver: finishStartingService: stopping service
,08-25 21:49:41.916  3851  3851 D BluetoothPbap: Proxy object connected
,08-25 21:49:41.916  1359  1359 D BluetoothPbap: Proxy object connected
08-25 21:49:41.916  3851  3851 D PbapServerProfile: Bluetooth service connected
08-25 21:49:41.916  1359  1359 D PbapServerProfile: Bluetooth service connected
,08-25 21:49:41.925  4141  4190 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 21:49:41.955   873   873 D BluetoothHeadset: Proxy object connected
08-25 21:49:41.955  3851  3862 D BluetoothHeadset: Proxy object connected
,08-25 21:49:41.955   873   873 D BluetoothHeadset: Proxy object connected
08-25 21:49:41.955  3851  3851 D HeadsetProfile: Bluetooth service connected
08-25 21:49:41.955   873   873 D BluetoothHeadset: Proxy object connected
08-25 21:49:41.955  4141  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 21:49:41.956  1359  1370 D BluetoothHeadset: Proxy object connected
08-25 21:49:41.956  1359  1359 D HeadsetProfile: Bluetooth service connected
08-25 21:49:41.956  1952  1964 D BluetoothHeadset: Proxy object connected
08-25 21:49:41.957  4141  4194 I BtOppRfcommListener: Accept thread started.
08-25 21:49:41.959   873   890 D BluetoothHeadset: Proxy object connected
,08-25 21:49:41.961  3851  4129 D BluetoothHeadset: Proxy object connected
08-25 21:49:41.961  3851  3851 D HeadsetProfile: Bluetooth service connected
,08-25 21:49:41.963   873   890 D BluetoothHeadset: Proxy object connected
,08-25 21:49:41.965   873   890 D BluetoothHeadset: Proxy object connected
,08-25 21:49:42.305  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:42.305  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:42.305  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:42.305  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 21:49:42.305  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:42.305  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:42.305  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:42.305  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:42.312  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:42.316  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:42.316  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@940cb6f added. We now have 8 listener(s)
,08-25 21:49:42.317  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:42.322   873   883 D WifiService: setWifiEnabled: false pid=3762, uid=10000
,08-25 21:49:42.322   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 21:49:42.336  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:42.337   873  1950 D WifiService: setWifiEnabled: true pid=3762, uid=10000
,08-25 21:49:42.337   873  1950 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 21:49:42.352   873  1314 D WifiConfigStore: Loading config and enabling all networks 
,08-25 21:49:42.371  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:42.371  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:42.371  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:42.371  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:42.371  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:42.371  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:42.371  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:42.371  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:42.377  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:42.388   873  1314 D WifiConfigStore: loaded 0 passpoint configs
,08-25 21:49:42.389   873  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-25 21:49:42.389   873  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-25 21:49:42.390   873  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-25 21:49:42.390   873  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-25 21:49:42.390   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-25 21:49:42.391   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-25 21:49:42.404   370   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-25 21:49:42.405   873  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.06 rxSuccessRate=0.07 delta 1000 -> 1000
08-25 21:49:42.405   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-25 21:49:42.408   370   872 D CommandListener: Setting iface cfg
,08-25 21:49:42.414   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-25 21:49:42.414   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 21:49:42.415   873  1314 E native  : do suspend true
,08-25 21:49:42.424   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-25 21:49:42.430   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-25 21:49:42.434   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-25 21:49:42.434   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:42.463   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-25 21:49:42.571   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-25 21:49:42.573  1461  1461 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-25 21:49:42.999  1461  1461 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 21:49:43.036  1461  1461 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 21:49:43.036  1461  1461 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=],
,08-25 21:49:43.052   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,08-25 21:49:43.060   873  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-25 21:49:43.060   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 21:49:43.061   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-25 21:49:43.074   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-25 21:49:43.083   370   872 D CommandListener: Setting iface cfg
,08-25 21:49:43.083   873  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,08-25 21:49:43.089   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-25 21:49:43.114   873  4202 D DhcpClient: Receive thread started
,08-25 21:49:43.198   873  1314 E native  : do suspend false
,08-25 21:49:43.219   873  1851 D DhcpClient: Broadcasting DHCPDISCOVER
,08-25 21:49:43.233   873  4202 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.104, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-25 21:49:43.234   873  1851 D DhcpClient: Got pending lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-25 21:49:43.238   873  1851 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.104 serverid=192.168.1.1
,08-25 21:49:43.253   873  4202 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.104, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-25 21:49:43.254   873  1851 D DhcpClient: Confirmed lease: IP address 192.168.1.104/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-25 21:49:43.261   370   872 D CommandListener: Setting iface cfg
,08-25 21:49:43.271   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-25 21:49:43.273   873  1851 D DhcpClient: Scheduling renewal in 86399s
,08-25 21:49:43.275   873  1314 E native  : do suspend true
,08-25 21:49:43.303   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-25 21:49:43.308   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,08-25 21:49:43.310   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 21:49:43.313   873  1316 D ConnectivityService: Adding iface wlan0 to network 102
,08-25 21:49:43.331   873  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-25 21:49:43.361  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:43.361  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:43.361  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:43.361  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:43.361  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:43.361  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 21:49:43.361  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 21:49:43.361  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 21:49:43.365  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 21:49:43.371   873  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-25 21:49:43.372   873  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-25 21:49:43.373   873  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-25 21:49:43.374   873  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-25 21:49:43.375   873  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-25 21:49:43.377  3762  3825 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 21:49:43.379  3762  3825 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-25 21:49:43.383  3762  3825 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7fedfb6 Bundle[{}]
08-25 21:49:43.384  3762  3825 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 21:49:43.384  3762  3825 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 21:49:43.385  3762  3825 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 21:49:43.386  3762  3825 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 21:49:43.386   873  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 21:49:43.386  3762  3825 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
08-25 21:49:43.387  3762  3825 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-25 21:49:43.395   873  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-25 21:49:43.395   873  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-25 21:49:43.396   873  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-25 21:49:43.396   873  1316 D ConnectivityService:    accepting network in place of null
08-25 21:49:43.396  3762  3825 I System.out: Running OutgoingSocketThread
,08-25 21:49:43.396   873  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-25 21:49:43.397   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-25 21:49:43.397  3762  4206 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
,08-25 21:49:43.398   873  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.104/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-25 21:49:43.398  3762  4206 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42879
,08-25 21:49:43.399  3762  4206 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 21:49:43.424   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 21:49:43.442   873  4201 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154426, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-25 21:49:43.451   370   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-25 21:49:43.456   873  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-25 21:49:43.456   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:43.459   873  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-25 21:49:43.460   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-25 21:49:43.481  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 21:49:43.481  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:43.481  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:43.481  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:43.481  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:43.481  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:43.481  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:43.481  3762  3762 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:43.487  3762  3762 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:43.489  2013  2013 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-25 21:49:43.492  1727  1727 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-25 21:49:43.499  1727  1727 D SystemUpdateService: onCreate
,08-25 21:49:43.502  1727  1727 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-25 21:49:43.523  1727  4213 I SystemUpdateService: active receiver: enabled
,08-25 21:49:43.526  1727  1727 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-25 21:49:43.532  1727  2311 I iu.UploadsManager: num queued entries: 0
,08-25 21:49:43.532  1727  2311 I iu.UploadsManager: num updated entries: 0
,08-25 21:49:43.534  1727  4213 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-25 21:49:43.536  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-25 21:49:43.538  1727  1727 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-25 21:49:43.541  3904  3904 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-25 21:49:43.545  1727  4216 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-25 21:49:43.546  1727  4216 W BaseAppContext: Using Auth Proxy for data requests.
,08-25 21:49:43.547  3904  3904 D SprintDMHelper: simOperator: 
,08-25 21:49:43.547  3904  3904 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-25 21:49:43.548  1727  4216 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
08-25 21:49:43.549  1727  2311 I iu.SyncManager: NEXT; no task
,08-25 21:49:43.559  1727  4213 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-25 21:49:43.559  1727  4213 I SystemUpdateService: now status is 0 (complete)
08-25 21:49:43.559  1727  4213 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-25 21:49:43.559  1727  4213 I SystemUpdateService: file has been verified
,08-25 21:49:43.563  1727  4213 I SystemUpdateService: OTA package size = 12249756
,08-25 21:49:43.565  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 21:49:43.569  1524  1524 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-25 21:49:43.589  1727  4213 I SystemUpdateService: showing system update notification
,08-25 21:49:43.608  1727  1727 D SystemUpdateService: onDestroy
,08-25 21:49:43.622  1524  2072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-25 21:49:43.622  1524  2072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-25 21:49:43.622  1524  2072 I GLSUser : [GLSUser] Extracting token using key: Auth
08-25 21:49:43.622  1524  2072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-25 21:49:43.642  1727  4216 E MDM     : [181] SitrepService.a: Error sending sitrep.
,08-25 21:49:44.110   873  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:814::200e
,08-25 21:49:44.254  2401  4218 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-25 21:49:44.399  3762  3825 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
,08-25 21:49:44.400  3762  3825 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
,08-25 21:49:44.409  3762  3825 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,08-25 21:49:44.411  3762  3825 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-25 21:49:44.412  3762  3825 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 423)
,08-25 21:49:44.420  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 21:49:44.421  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56ca07c added. We now have 2 listener(s)
,08-25 21:49:44.427  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 21:49:44.428  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:44.428  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 21:49:44.429  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:44.429  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e4d05 added. We now have 9 listener(s)
08-25 21:49:44.430  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:44.431  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:44.437  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:44.444  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:44.444  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:44.444  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:44.444  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:44.444  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:44.444  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:44.444  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:44.444  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:44.449  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:44.449  3762  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:44.450  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 21:49:44.450  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f38af8b added. We now have 3 listener(s)
08-25 21:49:44.452  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:44.456  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 21:49:44.456  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:44.456  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:44.457  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:44.457  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:44.457  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1214868 added. We now have 10 listener(s)
08-25 21:49:44.457   873  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
08-25 21:49:44.458  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:44.458  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:44.459  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:44.459  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:44.459  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:44.459  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:44.460  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:44.460  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:44.460  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56ca07c removed from the list
08-25 21:49:44.460  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.461  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e4d05 removed from the list
08-25 21:49:44.461  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:44.461  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:44.463  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.463  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:44.464  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:44.464  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:44.465  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:49:44.465  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@40e4d05 not in the list
,08-25 21:49:44.465  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.465  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:44.466  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:44.466  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 21:49:44.466  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.466  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1214868 removed from the list
08-25 21:49:44.466  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:44.466  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.466  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:44.466  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:44.466  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f38af8b removed from the list
08-25 21:49:44.467  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 21:49:44.467  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7abb481 added. We now have 2 listener(s)
,08-25 21:49:44.469  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 21:49:44.469  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:44.469  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 21:49:44.470  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:44.470  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e15926 added. We now have 9 listener(s)
,08-25 21:49:44.470  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:44.470  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:44.473  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:44.478  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:44.478  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:44.478  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:44.478  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:44.478  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:44.478  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:44.478  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:44.478  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:44.480  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:44.481  3762  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 21:49:44.481  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:44.481  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef68314 added. We now have 3 listener(s)
,08-25 21:49:44.483  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 21:49:44.483  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 21:49:44.483  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:44.483  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:44.483  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e17bd added. We now have 10 listener(s)
08-25 21:49:44.483  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:44.483  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:49:44.483  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:49:44.484  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 21:49:44.484  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:44.484  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 21:49:44.485  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:44.487  3762  3825 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-25 21:49:44.487  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 21:49:44.490  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:44.493  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 21:49:44.493  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 21:49:44.494  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 21:49:44.497  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 21:49:44.497  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 21:49:44.498  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:44.499  3762  3825 D BluetoothAdapter: STATE_ON
,08-25 21:49:44.502  4141  4154 D BtGatt.GattService: registerClient() - UUID=6dc92e45-bd41-46d0-8836-71788fae923f
,08-25 21:49:44.503  4141  4159 D BtGatt.GattService: onClientRegistered() - UUID=6dc92e45-bd41-46d0-8836-71788fae923f, clientIf=5
,08-25 21:49:44.504  3762  3826 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-25 21:49:44.506  4141  4183 D BtGatt.GattService: start scan with filters
,08-25 21:49:44.510  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 21:49:44.510  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 21:49:44.510  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:44.510  4141  4164 D BtGatt.ScanManager: handling starting scan
08-25 21:49:44.510  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 21:49:44.514  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-25 21:49:44.514  4141  4164 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dabbeea
,08-25 21:49:44.514  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 21:49:44.514  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:44.516  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 21:49:44.520  4141  4159 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 21:49:44.520  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.521  3762  3825 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-25 21:49:44.521  4141  4164 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 21:49:44.521  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:44.522  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 21:49:44.522  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.522  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:44.522  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 21:49:44.522  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-25 21:49:44.522  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:44.522  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:44.522  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:44.522  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-25 21:49:44.526  3762  3825 D BluetoothAdapter: STATE_ON
,08-25 21:49:44.528  4141  4153 D BtGatt.GattService: stopScan() - queue size =1
,08-25 21:49:44.530  4141  4182 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-25 21:49:44.530  4141  4159 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 21:49:44.530  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-25 21:49:44.531  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 21:49:44.531  4141  4164 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:44.531  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-25 21:49:44.531  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 21:49:44.531  4141  4164 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 21:49:44.532  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 21:49:44.532  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-25 21:49:44.535  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:44.535  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 21:49:44.535  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 21:49:44.536  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 21:49:44.537  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:44.540  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 21:49:44.540  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 21:49:44.540  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:44.546  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:44.546  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:44.546  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 21:49:44.547  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:49:44.547  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:44.547  4141  4159 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 21:49:44.547  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:44.547  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:44.549  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-25 21:49:44.549  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7abb481 removed from the list
,08-25 21:49:44.549  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.549  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e15926 removed from the list
08-25 21:49:44.549  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 21:49:44.549  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:44.551  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:44.551  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:44.553  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 21:49:44.553  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:44.553  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:49:44.553  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e15926 not in the list
08-25 21:49:44.553  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:44.553  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:44.555  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:44.555  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 21:49:44.555  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.556  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5e17bd removed from the list
,08-25 21:49:44.556  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:44.556  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:44.556  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:44.556  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:44.557  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef68314 removed from the list
,08-25 21:49:44.558  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:44.558  4141  4159 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 21:49:44.559  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.559  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed972b9 added. We now have 2 listener(s)
,08-25 21:49:44.567  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 21:49:44.567  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 21:49:44.568  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 21:49:44.568  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:44.569  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a066fe added. We now have 9 listener(s)
08-25 21:49:44.569  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:44.570  4141  4159 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 21:49:44.570  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:44.570  4141  4164 D BtGatt.ScanManager: stopping BLe Batch
,08-25 21:49:44.570  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:44.576  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:44.578  4141  4159 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 21:49:44.578  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:44.578  4141  4164 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 21:49:44.582  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:44.582  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:44.582  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:44.582  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:44.582  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:44.582  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:44.582  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:44.582  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:44.585  4141  4159 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-25 21:49:44.585  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:44.586  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:44.586  3762  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:44.586  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-25 21:49:44.586  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5720ac added. We now have 3 listener(s)
,08-25 21:49:44.588  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:44.589  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 21:49:44.590  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 21:49:44.590  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-25 21:49:44.590  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:44.590  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1158175 added. We now have 10 listener(s)
08-25 21:49:44.590  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:44.591  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:44.591  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 21:49:44.592  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 21:49:44.592  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:49:44.592  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 21:49:44.592  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:44.592  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 21:49:44.596  3762  3825 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 21:49:44.596  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 21:49:44.603  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 21:49:44.604  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-25 21:49:44.604  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 21:49:44.608  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-25 21:49:44.608  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 21:49:44.608  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-25 21:49:44.609  3762  3825 D BluetoothAdapter: STATE_ON
08-25 21:49:44.612  4141  4183 D BtGatt.GattService: registerClient() - UUID=71f85d2f-f85f-4c2d-ac7e-015b056dd07e
08-25 21:49:44.613  4141  4159 D BtGatt.GattService: onClientRegistered() - UUID=71f85d2f-f85f-4c2d-ac7e-015b056dd07e, clientIf=5
08-25 21:49:44.613  3762  3773 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 21:49:44.614  4141  4154 D BtGatt.GattService: start scan with filters
08-25 21:49:44.617  4141  4164 D BtGatt.ScanManager: handling starting scan
08-25 21:49:44.618  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-25 21:49:44.618  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-25 21:49:44.618  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-25 21:49:44.618  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 21:49:44.622  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:44.622  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-25 21:49:44.622  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:44.624  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 21:49:44.627  4141  4159 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 21:49:44.627  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:44.627  4141  4164 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 21:49:44.629  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-25 21:49:44.629  3762  3825 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-25 21:49:44.630  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:44.630  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:44.630  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 21:49:44.630  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:49:44.630  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:44.630  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:44.630  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
08-25 21:49:44.631  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ed972b9 removed from the list
,08-25 21:49:44.631  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.631  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a066fe removed from the list
,08-25 21:49:44.631  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:44.631  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:44.632  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.632  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-25 21:49:44.632  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.632  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 21:49:44.634  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:44.634  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:44.634  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.634  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a066fe not in the list
08-25 21:49:44.634  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:44.634  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 21:49:44.634  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 21:49:44.634  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:44.634  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 21:49:44.635  3762  3825 D BluetoothAdapter: STATE_ON
08-25 21:49:44.636  4141  4154 D BtGatt.GattService: stopScan() - queue size =1
08-25 21:49:44.636  4141  4159 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 21:49:44.637  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.637  4141  4164 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:44.637  4141  4164 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-25 21:49:44.638  4141  4182 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 21:49:44.638  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 21:49:44.638  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 21:49:44.639  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-25 21:49:44.639  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-25 21:49:44.639  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 21:49:44.640  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:44.640  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-25 21:49:44.641  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 21:49:44.641  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 21:49:44.641  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:44.644  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 21:49:44.644  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:44.644  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.645  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:44.645  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1158175 removed from the list
,08-25 21:49:44.645  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:44.645  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:44.645  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:44.645  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.645  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:44.645  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:44.645  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5720ac removed from the list
,08-25 21:49:44.647  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:44.647  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9bff1 added. We now have 2 listener(s)
,08-25 21:49:44.650  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 21:49:44.651  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:44.651  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:44.651  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-25 21:49:44.651  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc857d6 added. We now have 9 listener(s)
08-25 21:49:44.651  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 21:49:44.654  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:44.655  4141  4159 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 21:49:44.655  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:44.657   873  4200 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 19:49:44 GMT], X-Android-Received-Millis=[1472154584656], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472154584252]}
,08-25 21:49:44.658  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-25 21:49:44.658   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-25 21:49:44.658   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-25 21:49:44.659   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-25 21:49:44.663   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-25 21:49:44.667  4141  4159 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-25 21:49:44.667  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.670  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:44.670  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:44.670  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:44.670  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:44.670  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:44.670  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:44.670  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:44.670  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:44.673  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-25 21:49:44.673  3762  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:44.673  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:44.673  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14ad944 added. We now have 3 listener(s)
,08-25 21:49:44.676  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-25 21:49:44.676  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 21:49:44.676  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:44.677  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:44.677  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:44.677  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a96a2d added. We now have 10 listener(s)
,08-25 21:49:44.677  4141  4159 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-25 21:49:44.677  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:44.677  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:44.677  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:49:44.677  4141  4164 D BtGatt.ScanManager: stopping BLe Batch
08-25 21:49:44.677  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 21:49:44.677  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-25 21:49:44.678  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 21:49:44.678  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 21:49:44.679  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:44.682  3762  3825 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-25 21:49:44.682  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-25 21:49:44.684  4141  4159 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-25 21:49:44.684  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.685  4141  4164 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 21:49:44.686  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 21:49:44.687  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-25 21:49:44.687  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-25 21:49:44.690  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-25 21:49:44.690  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-25 21:49:44.691  3762  3825 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-25 21:49:44.691  4141  4159 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 21:49:44.691  3762  3825 D BluetoothAdapter: STATE_ON
08-25 21:49:44.691  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:44.694  4141  4153 D BtGatt.GattService: registerClient() - UUID=d29ff96b-ba1d-44f0-b71f-d0381653ec48
,08-25 21:49:44.694  4141  4159 D BtGatt.GattService: onClientRegistered() - UUID=d29ff96b-ba1d-44f0-b71f-d0381653ec48, clientIf=5
08-25 21:49:44.694  3762  3773 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-25 21:49:44.695  4141  4154 D BtGatt.GattService: start scan with filters
,08-25 21:49:44.697  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-25 21:49:44.697  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-25 21:49:44.697  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-25 21:49:44.697  4141  4164 D BtGatt.ScanManager: handling starting scan
,08-25 21:49:44.697  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-25 21:49:44.701  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:44.701  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-25 21:49:44.701  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-25 21:49:44.703  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-25 21:49:44.703  4141  4159 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-25 21:49:44.704  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-25 21:49:44.704  4141  4164 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-25 21:49:44.708  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 21:49:44.708  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:44.708  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 21:49:44.708  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:49:44.709  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:44.709  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 21:49:44.709  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 21:49:44.709  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c9bff1 removed from the list
,08-25 21:49:44.709  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:49:44.709  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc857d6 removed from the list
08-25 21:49:44.709  4141  4159 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-25 21:49:44.709  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:44.709  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.709  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:44.709  4141  4164 D BtGatt.ScanManager: Starting BLE batch scan
08-25 21:49:44.710  4141  4164 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-25 21:49:44.710  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.710  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-25 21:49:44.710  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.710  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:44.711  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 21:49:44.711  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:44.711  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 21:49:44.711  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dc857d6 not in the list
08-25 21:49:44.711  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 21:49:44.711  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-25 21:49:44.711  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-25 21:49:44.714  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-25 21:49:44.715  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-25 21:49:44.715  3762  3825 D BluetoothAdapter: STATE_ON
,08-25 21:49:44.716  4141  4153 D BtGatt.GattService: stopScan() - queue size =1
08-25 21:49:44.716  4141  4154 D BtGatt.GattService: unregisterClient() - clientIf=5
08-25 21:49:44.717  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-25 21:49:44.717  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-25 21:49:44.717  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-25 21:49:44.717  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-25 21:49:44.717  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-25 21:49:44.718  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-25 21:49:44.718  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-25 21:49:44.719  3762  3825 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-25 21:49:44.719  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 21:49:44.720  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:44.720  4141  4159 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-25 21:49:44.720  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.722  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:44.722  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 21:49:44.723  3762  3762 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-25 21:49:44.723  3762  3762 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 21:49:44.723  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:44.723  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.723  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a96a2d removed from the list
08-25 21:49:44.723  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:49:44.723  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.723  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:44.723  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 21:49:44.723  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14ad944 removed from the list
08-25 21:49:44.724  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-25 21:49:44.724  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95f7c29 added. We now have 2 listener(s)
08-25 21:49:44.725  4141  4159 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-25 21:49:44.725  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.727  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 21:49:44.727  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-25 21:49:44.727  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:44.727  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:44.727  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6328bae added. We now have 9 listener(s)
,08-25 21:49:44.728  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:44.728  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 21:49:44.734  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 21:49:44.737  4141  4159 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-25 21:49:44.737  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.737  4141  4164 D BtGatt.ScanManager: stopping BLe Batch
,08-25 21:49:44.742  3762  3825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 21:49:44.742  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 21:49:44.742  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-25 21:49:44.742  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 21:49:44.742  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 21:49:44.742  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:44.742  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 21:49:44.742  3762  3825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 21:49:44.743  4141  4159 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-25 21:49:44.743  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.743  4141  4164 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-25 21:49:44.746  3762  3825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 21:49:44.746  3762  3825 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 21:49:44.747  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 21:49:44.747  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ba0cdc added. We now have 3 listener(s)
08-25 21:49:44.749  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:44.751  3762  3762 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 21:49:44.751  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-25 21:49:44.751  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 21:49:44.751  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 21:49:44.751  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 21:49:44.752  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4ab1e5 added. We now have 10 listener(s)
,08-25 21:49:44.752  3762  3825 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 21:49:44.752  3762  3825 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 21:49:44.752  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 21:49:44.752  3762  3825 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 21:49:44.752  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 21:49:44.752  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.752  4141  4159 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-25 21:49:44.753  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 21:49:44.753  4141  4159 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-25 21:49:44.753  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 21:49:44.753  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95f7c29 removed from the list
08-25 21:49:44.753  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.753  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6328bae removed from the list
08-25 21:49:44.753  3762  3825 D io.jxcore.node.ConnectivityMonitor: stop
08-25 21:49:44.753  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:44.754  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.754  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-25 21:49:44.755  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:44.755  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:44.755  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.756  3762  3825 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6328bae not in the list
08-25 21:49:44.756  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 21:49:44.756  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:44.757  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 21:49:44.757  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 21:49:44.757  3762  3825 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 21:49:44.757  3762  3825 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4ab1e5 removed from the list
,08-25 21:49:44.758  3762  3825 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 21:49:44.758  3762  3825 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 21:49:44.758  3762  3825 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-25 21:49:44.758  3762  3825 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-25 21:49:44.758  3762  3825 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6ba0cdc removed from the list
08-25 21:49:44.760  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 21:49:44.760  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 21:49:44.760  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-25 21:49:44.761  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 21:49:44.761  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 21:49:44.761  3762  3825 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-25 21:49:44.771  3762  4226 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: My test thread name)
,08-25 21:49:44.772  3762  4226 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: My test thread name)
08-25 21:49:44.772  3762  4226 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-25 21:49:44.775  3762  4227 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 432, name: My test thread name)
,08-25 21:49:44.775  3762  4227 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 432, thread name: My test thread name)
08-25 21:49:44.775  3762  4227 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 432, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-25 21:49:44.777  3762  3825 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-25 21:49:44.777  3762  3825 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-25 21:49:44.778  3762  3825 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-25 21:49:44.778  3762  3825 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-25 21:49:44.778  3762  3825 D com.test.thalitest.ThaliTestRunner: Total duration: 22987 ms
,08-25 21:49:44.780  3762  3825 I jxcore-log: *Native tests were executed*
08-25 21:49:44.780  3762  3825 I jxcore-log: 
,08-25 21:49:44.780  3762  3825 I jxcore-log: Total number of executed tests:  80
08-25 21:49:44.780  3762  3825 I jxcore-log: 
08-25 21:49:44.781  3762  3825 I jxcore-log: Number of passed tests:  80
08-25 21:49:44.781  3762  3825 I jxcore-log: 
,08-25 21:49:44.781  3762  3825 I jxcore-log: Number of failed tests:  0
08-25 21:49:44.781  3762  3825 I jxcore-log: 
08-25 21:49:44.781  3762  3825 I jxcore-log: Number of ignored tests:  0
08-25 21:49:44.781  3762  3825 I jxcore-log: 
,08-25 21:49:44.782  2094  2642 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-25 21:49:44.782  3762  3825 I jxcore-log: Total duration:  22987
08-25 21:49:44.782  3762  3825 I jxcore-log: 
08-25 21:49:44.783  3762  3825 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-25 21:49:44.783  3762  3825 I jxcore-log: 
,08-25 21:49:44.787  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.787  3762  3825 I jxcore-log: 
08-25 21:49:44.791  3762  3762 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-25 21:49:44.795  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.795  3762  3825 I jxcore-log: 
08-25 21:49:44.796  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.796  3762  3825 I jxcore-log: 
08-25 21:49:44.797  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.797  3762  3825 I jxcore-log: 
08-25 21:49:44.797  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.797  3762  3825 I jxcore-log: 
08-25 21:49:44.799  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.799  3762  3825 I jxcore-log: 
08-25 21:49:44.801  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.801  3762  3825 I jxcore-log: 
08-25 21:49:44.802  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 21:49:44.802  3762  3825 I jxcore-log: 
08-25 21:49:44.802  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 21:49:44.802  3762  3825 I jxcore-log: 
08-25 21:49:44.803  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:44.803  3762  3825 I jxcore-log: 
,08-25 21:49:44.804  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:44.804  3762  3825 I jxcore-log: 
,08-25 21:49:44.805  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 21:49:44.805  3762  3825 I jxcore-log: 
,08-25 21:49:44.806  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 21:49:44.806  3762  3825 I jxcore-log: 
,08-25 21:49:44.807  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 21:49:44.807  3762  3825 I jxcore-log: 
,08-25 21:49:44.807  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.807  3762  3825 I jxcore-log: 
,08-25 21:49:44.808  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.808  3762  3825 I jxcore-log: 
,08-25 21:49:44.809  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:44.809  3762  3825 I jxcore-log: 
,08-25 21:49:44.810  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:44.810  3762  3825 I jxcore-log: 
,08-25 21:49:44.811  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:49:44.811  3762  3825 I jxcore-log: 
,08-25 21:49:44.811  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:49:44.811  3762  3825 I jxcore-log: 
,08-25 21:49:44.812  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:44.812  3762  3825 I jxcore-log: 
,08-25 21:49:44.813  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 21:49:44.813  3762  3825 I jxcore-log: 
,08-25 21:49:44.814  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:49:44.814  3762  3825 I jxcore-log: 
,08-25 21:49:44.815  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 21:49:44.815  3762  3825 I jxcore-log: 
,08-25 21:49:44.816  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 21:49:44.816  3762  3825 I jxcore-log: 
,08-25 21:49:44.817  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 21:49:44.817  3762  3825 I jxcore-log: 
,08-25 21:49:44.817  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.817  3762  3825 I jxcore-log: 
,08-25 21:49:44.818  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.818  3762  3825 I jxcore-log: 
,08-25 21:49:44.819  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.819  3762  3825 I jxcore-log: 
,08-25 21:49:44.820  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.820  3762  3825 I jxcore-log: 
,08-25 21:49:44.821  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.821  3762  3825 I jxcore-log: 
,08-25 21:49:44.822  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 21:49:44.822  3762  3825 I jxcore-log: 
,08-25 21:49:45.041  3762  3762 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 21:49:45.042  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 21:49:45.042  3762  3825 I jxcore-log: 
,08-25 21:49:45.146  3762  3762 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 21:49:45.147  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 21:49:45.147  3762  3825 I jxcore-log: 
,08-25 21:49:45.222  3762  3762 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 21:49:45.225  3762  3825 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 21:49:45.225  3762  3825 I jxcore-log: 
,08-25 21:49:45.469  4228  4228 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-25 21:49:45.474  4228  4228 D AndroidRuntime: CheckJNI is OFF
,08-25 21:49:45.517  4228  4228 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-25 21:49:45.563  4228  4228 I Radio-JNI: register_android_hardware_Radio DONE
,08-25 21:49:45.586  4228  4228 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 21:49:45.595   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-25 21:49:45.596   873   886 I ActivityManager: Killing 3762:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-25 21:49:45.677   873   896 W PackageSettings: Skipping PackageSetting{228c4f com.example.hello/10273} due to missing metadata
,08-25 21:49:45.711   873   896 I art     : Starting a blocking GC Explicit
,08-25 21:49:45.734   873  2265 D GraphicsStats: Buffer count: 2
,08-25 21:49:45.735   873  1315 D WifiService: Client connection lost with reason: 4
08-25 21:49:45.735   873  1395 I WindowState: WIN DEATH: Window{4bf510b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 21:49:45.767   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-25 21:49:45.767   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-25 21:49:45.767   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-25 21:49:45.767   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-25 21:49:45.767   873   886 E ActivityManager: ,	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-25 21:49:45.767   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:45.767   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:45.767   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 21:49:45.767   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-25 21:49:45.768   873   886 I ActivityManager:   Force finishing activity ActivityRecord{111b33b u0 com.test.thalitest/.MainActivity t2}
,08-25 21:49:45.782   873  1706 W ActivityManager: Spurious death for ProcessRecord{7707936 0:com.test.thalitest/u0a0}, curProc for 3762: null
,08-25 21:49:45.793   873   896 I art     : Explicit concurrent mark sweep GC freed 13990(969KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.002ms total 80.841ms
,08-25 21:49:45.820   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-25 21:49:45.823  4228  4228 I art     : System.exit called, status: 0
,08-25 21:49:45.823  4228  4228 I AndroidRuntime: VM exiting with result code 0.
,08-25 21:49:45.826   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-25 21:49:45.845   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-25 21:49:45.852  1874  1874 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-25 21:49:45.856  4141  4141 D BluetoothMapAppObserver: onReceive
,08-25 21:49:45.856  4141  4141 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-25 21:49:45.860  3605  3605 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-25 21:49:45.861  2094  2261 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.,
08-25 21:49:45.862   873  1304 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 21:49:45.869  1874  4239 I Keyboard.Facilitator.DecoderInitializer: run()
,08-25 21:49:45.872  1874  4239 I Decoder : createOrResetDecoder
,08-25 21:49:45.919  1952  1952 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-25 21:49:45.922   873  1985 I ActivityManager: Start proc 4242:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-25 21:49:45.936  1524  1524 I ConfigService: onCreate
,08-25 21:49:45.954   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-25 21:49:45.958  1874  4239 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-25 21:49:45.975  4242  4242 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-25 21:49:45.982  1965  2041 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-25 21:49:45.983   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-25 21:49:45.984   873   885 E PackageManager: Failed to write settings, restoring backup
08-25 21:49:45.984   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-25 21:49:45.984   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-25 21:49:45.984   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-25 21:49:45.984   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-25 21:49:45.984   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-25 21:49:45.984   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:45.984   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:45.984   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 21:49:45.988   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-25 21:49:45.988   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-25 21:49:45.988   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 21:49:45.988   873   886 E DropBoxManagerService: 	... 13 more
,08-25 21:49:45.989   873  1706 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3762 uid 10000
,08-25 21:49:45.990  1874  1874 I Keyboard.Facilitator: onFinishInput()
,08-25 21:49:45.990  1874  4239 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-25 21:49:45.993  1874  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-25 21:49:45.993  1874  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-25 21:49:45.995   873  2267 I ActivityManager: Start proc 4256:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-25 21:49:45.995  1965  2041 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-25 21:49:45.995  1965  2041 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1965
08-25 21:49:45.995  1965  2041 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:45.995  1965  2041 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 21:49:45.996  1874  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-25 21:49:45.996  1874  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-25 21:49:45.996  1874  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-25 21:49:45.996  1874  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-25 21:49:45.997  1874  4239 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-25 21:49:45.997  1874  4239 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-25 21:49:45.997  1874  4239 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-25 21:49:45.997   873  1395 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 21:49:45.997   873  4262 E DropBoxManagerService: Can't write: system_app_crash
08-25 21:49:45.997   873  4262 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: 	at li,bcore.io.Posix.open(Native Method)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 21:49:45.997   873  4262 E DropBoxManagerService: 	... 5 more
08-25 21:49:45.997  1874  4239 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-25 21:49:45.997  1874  4239 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-25 21:49:45.997  1874  4239 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-25 21:49:45.999  1965  2041 I Process : Sending signal. PID: 1965 SIG: 9
,08-25 21:49:46.034  4242  4242 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-25 21:49:46.043   873   883 D GraphicsStats: Buffer count: 1
08-25 21:49:46.043   873   884 I WindowState: WIN DEATH: Window{2f9b4fd u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-25 21:49:46.068   873  1985 I ActivityManager: Start proc 4275:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-25 21:49:46.068   873  1950 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1965) has died
08-25 21:49:46.069   873  1950 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-25 21:49:46.070   873  1950 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 21:49:46.090   873   886 I ActivityManager: Start proc 4287:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 21:49:46.114  4242  4272 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-25 21:49:46.119  4275  4275 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-25 21:49:46.137  4287  4287 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:46.137  4287  4287 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 21:49:46.138  4287  4287 D AndroidRuntime: Shutting down VM
,08-25 21:49:46.142  1524  1524 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-25 21:49:46.143  1524  1524 D AndroidRuntime: Shutting down VM
08-25 21:49:46.143  1524  1524 E AndroidRuntime: FATAL EXCEPTION: main
08-25 21:49:46.143  1524  1524 E AndroidRuntime: Process: com.google.process.gapps, PID: 1524
08-25 21:49:46.143  1524  1524 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-25 21:49:46.143  1524  1524 E AndroidRuntime: 	... 8 more
,08-25 21:49:46.144  4287  4287 E AndroidRuntime: FATAL EXCEPTION: main
08-25 21:49:46.144  4287  4287 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4287
08-25 21:49:46.144  4287  4287 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 21:49:46.144  4287  4287 E AndroidRuntime: 	... 10 more
,08-25 21:49:46.146  1524  1524 I Process : Sending signal. PID: 1524 SIG: 9
08-25 21:49:46.147   873  1398 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-25 21:49:46.146   873  4301 E DropBoxManagerService: Can't write: system_app_crash
08-25 21:49:46.146   873  4301 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 21:49:46.146   873  4301 E DropBoxManagerService: 	... 5 more
08-25 21:49:46.148  4287  4287 I Process : Sending signal. PID: 4287 SIG: 9
08-25 21:49:46.155   873  4303 E DropBoxManagerService: Can't write: system_app_crash
08-25 21:49:46.155   873  4303 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 21:49:46.155   873  4303 E DropBoxManagerService: 	... 5 more
,08-25 21:49:46.159  4242  4272 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.159  4242  4272 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-25 21:49:46.159  4242  4272 E AndroidRuntime: Process: android.process.acore, PID: 4242
08-25 21:49:46.159  4242  4272 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 21:49:46.159  4242  4272 E Andr,oidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.159  4242  4272 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 21:49:46.172  4242  4270 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.172  4242  4270 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.172  4242  4270 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-25 21:49:46.186   873  1315 D WifiService: Client connection lost with reason: 4
,08-25 21:49:46.192   873  2265 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4287) has died
,08-25 21:49:46.193   873  2265 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-25 21:49:46.194  4242  4270 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-25 21:49:46.197   873  1950 I ActivityManager: Process com.google.process.gapps (pid 1524) has died
,08-25 21:49:46.197   873  1950 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-25 21:49:46.197   873  1950 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-25 21:49:46.197   873  1950 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
08-25 21:49:46.197   873  1950 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 31000ms
,08-25 21:49:46.202  1727  1727 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-25 21:49:46.205   873  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,08-25 21:49:46.206  4242  4270 I Process : Sending signal. PID: 4242 SIG: 9
,08-25 21:49:46.210   873   886 I ActivityManager: Start proc 4306:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 21:49:46.210   278   278 E lowmemorykiller: Error writing /proc/4242/oom_score_adj; errno=22
,08-25 21:49:46.214   873  4312 E DropBoxManagerService: Can't write: system_app_crash
08-25 21:49:46.214   873  4312 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 21:49:46.214   873  4312 E DropBoxManagerService: 	... 5 more
,08-25 21:49:46.232   873   883 I ActivityManager: Start proc 4320:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,08-25 21:49:46.239   873  1945 I ActivityManager: Killing 3658:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-25 21:49:46.270  4306  4306 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:46.270  4306  4306 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-25 21:49:46.271  4306  4306 D AndroidRuntime: Shutting down VM
,08-25 21:49:46.301   873  1395 I ActivityManager: Process android.process.acore (pid 4242) has died
,08-25 21:49:46.301   873  1395 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-25 21:49:46.308  4320  4320 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,08-25 21:49:46.309  4306  4306 E AndroidRuntime: FATAL EXCEPTION: main
08-25 21:49:46.309  4306  4306 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4306
08-25 21:49:46.309  4306  4306 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 21:49:46.309  4306  4306 E AndroidRuntime: 	... 10 more
08-25 21:49:46.310  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-25 21:49:46.310  1727  1727 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-25 21:49:46.313   873  1395 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-25 21:49:46.314   873  4333 E DropBoxManagerService: Can't write: system_app_crash
08-25 21:49:46.314   873  4333 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 21:49:46.314   873  4333 E DropBoxManagerService: 	... 5 more
,08-25 21:49:46.317  4306  4306 I Process : Sending signal. PID: 4306 SIG: 9
,08-25 21:49:46.318  4320  4320 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-25 21:49:46.318  1727  1727 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-25 21:49:46.318  1727  1727 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:46.321  4320  4320 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 21:49,:46.321  1727  4334 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-25 21:49:46.321  4320  4320 D AndroidRuntime: Shutting down VM
08-25 21:49:46.322  4320  4320 E AndroidRuntime: FATAL EXCEPTION: main
08-25 21:49:46.322  4320  4320 E AndroidRuntime: Process: com.google.process.gapps, PID: 4320
08-25 21:49:46.322  4320  4320 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
08-25 21:49:46.322  4320  4,320 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-25 21:49:46.322  4320  4320 E AndroidRuntime: 	... 10 more
08-25 21:49:46.326   873  4336 E DropBoxManagerService: Can't write: system_app_crash
08-25 21:49:46.326   873  4336 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-25 21:49:46.326   873  4336 E DropBoxManagerService: 	... 5 more
08-25 21:49:46.327  4320  4320 I Process : Sending signal. PID: 4320 SIG: 9
08-25 21:49:46.332   873  2266 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4306) has died
08-25 21:49:46.334   873  2266 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0

```
