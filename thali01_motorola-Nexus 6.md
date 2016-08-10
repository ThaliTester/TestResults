#### Test 807613747027f2d_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-10 11:45:34.114  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:45:34.125  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 11:45:34.130  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 11:45:34.168  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 11:45:34.168  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 11:45:34.168  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:45:34.168  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 11:45:34.186  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 11:45:34.187  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 11:45:34.189  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-10 11:45:34.750  3678  3678 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 11:45:34.755  3678  3678 D AndroidRuntime: CheckJNI is OFF
08-10 11:45:34.798  3678  3678 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 11:45:34.850  3678  3678 I Radio-JNI: register_android_hardware_Radio DONE
08-10 11:45:34.872  3678  3678 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 11:45:34.876   871  1899 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 11:45:34.918   871  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
08-10 11:45:34.928  1801  1820 W SearchService: Abort, client detached.
08-10 11:45:34.940  1801  1801 I HotwordDetector: Closing mic
08-10 11:45:34.940  1801  2111 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@2c98036
08-10 11:45:34.940  1801  2118 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-10 11:45:34.946  3678  3678 D AndroidRuntime: Shutting down VM
08-10 11:45:34.995   871   881 I ActivityManager: Start proc 3687:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-10 11:45:35.015   375  2120 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-10 11:45:35.017   375  2120 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-10 11:45:35.023   375  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 11:45:35.025  1801  2114 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 11:45:35.025  1801  2117 I MicroRecognitionRnrImpl: Detection finished
08-10 11:45:35.091  3687  3687 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-10 11:45:35.126  3687  3687 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-10 11:45:35.138  3687  3687 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2929-2934)
08-10 11:45:35.138  3687  3687 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 11:45:35.180  3687  3687 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {661f6c8}
08-10 11:45:35.181  3687  3687 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 11:45:35.183  3687  3687 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 11:45:35.198  3687  3687 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 11:45:35.200  3687  3687 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 11:45:35.217  3687  3687 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 11:45:35.234  3687  3687 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 11:45:35.234  3687  3687 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 11:45:35.234  3687  3687 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 11:45:35.234  3687  3687 I Adreno  : Build Date                       : 10/20/15
08-10 11:45:35.234  3687  3687 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 11:45:35.234  3687  3687 I Adreno  : Local Branch                     : M14
08-10 11:45:35.234  3687  3687 I Adreno  : Remote Branch                    : 
08-10 11:45:35.234  3687  3687 I Adreno  : Remote Branch                    : 
08-10 11:45:35.234  3687  3687 I Adreno  : Reconstruct Branch               : 
,08-10 11:45:35.315   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@549d612:true
,08-10 11:45:35.356  3687  3687 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 11:45:35.374  3687  3687 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-10 11:45:35.445  3687  3726 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 11:45:35.457  3687  3712 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-10 11:45:35.494  3687  3726 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 11:45:35.584   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +620ms
,08-10 11:45:35.588  1648  1648 I Keyboard.Facilitator: onFinishInput()
,08-10 11:45:35.654  3687  3687 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3687
,08-10 11:45:35.772  3687  3687 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 11:45:35.834   871  1888 I ActivityManager: Killing 2380:com.google.android.talk/u0a61 (adj 15): empty #17
,08-10 11:45:35.834   280   280 E lowmemorykiller: Error writing /proc/2380/oom_score_adj; errno=22
,08-10 11:45:35.886   871  1888 I ActivityManager: Killing 3261:com.google.android.music:main/u0a66 (adj 15): empty #18
,08-10 11:45:36.013  3687  3729 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1668085456
,08-10 11:45:36.019  3687  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 11:45:36.019  3687  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 11:45:36.019  3687  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 11:45:36.019  3687  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 11:45:36.019  3687  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-10 11:45:36.019  3687  3729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14217ff added. We now have 1 listener(s)
,08-10 11:45:36.024  3687  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-10 11:45:36.025  3687  3729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 11:45:36.025  3687  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 11:45:36.026  3687  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 11:45:36.035  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-10 11:45:36.036  3687  3729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be1632a added. We now have 1 listener(s)
08-10 11:45:36.037  3687  3729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 11:45:36.042   871  1303 D WifiService: New client listening to asynchronous messages
,08-10 11:45:36.046  3687  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 11:45:36.046  3687  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-10 11:45:36.050  3687  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-10 11:45:36.050  3687  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-10 11:45:36.050  3687  3729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-10 11:45:36.055  3687  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 11:45:36.056  3687  3729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-10 11:45:36.061  3687  3729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-10 11:45:36.062  3687  3729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:45:36.062  3687  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:45:36.062  3687  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:45:36.062  3687  3729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:45:36.062  3687  3729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:45:36.062  3687  3729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:45:36.062  3687  3729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:45:36.062  3687  3729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 11:45:36.062  3687  3729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-10 11:45:36.062  3687  3729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 11:45:36.063  3687  3729 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 11:45:36.064  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:45:36.065  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:45:36.209  3687  3687 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 11:45:36.962  3687  3738 E filemap : mmap(27197440,0) failed: Invalid argument
,08-10 11:45:36.963  3687  3738 W asset   : create map from entry failed
,08-10 11:45:36.963  3687  3738 W jxcore-FileManager: aproxFileSize failed
,08-10 11:45:36.963  3687  3738 W System.err: java.io.FileNotFoundException: www/jxcore/node_modules/tar-fs/test/fixtures/e/file
,08-10 11:45:36.963  3687  3738 W System.err: 	at android.content.res.AssetManager.openAsset(Native Method)
,08-10 11:45:36.963  3687  3738 W System.err: 	at android.content.res.AssetManager.open(AssetManager.java:313)
,08-10 11:45:36.963  3687  3738 W System.err: 	at io.jxcore.node.FileManager.aproxFileSize(FileManager.java:48)
,08-10 11:45:36.963  3687  3738 W System.err: 	at io.jxcore.node.jxcore.Initialize(jxcore.java:281)
,08-10 11:45:36.964  3687  3738 W System.err: 	at io.jxcore.node.jxcore.access$200(jxcore.java:25)
08-10 11:45:36.964  3687  3738 W System.err: 	at io.jxcore.node.jxcore$6.run(jxcore.java:343)
,08-10 11:45:36.964  3687  3738 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 11:45:36.964  3687  3738 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 11:45:36.964  3687  3738 W System.err: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:45:36.964  3687  3738 W System.err: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,08-10 11:45:37.019  3687  3738 W jxcore-log: Initializing JXcore engine
,08-10 11:45:37.019  3687  3738 W jxcore-log: JXcore engine is ready
,08-10 11:45:37.054  3738  3738 W Thread-334: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-10 11:45:37.058  3738  3738 W Thread-334: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9887]" dev="sockfs" ino=9887 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-10 11:45:37.058  3738  3738 W Thread-334: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-10 11:45:37.058  3738  3738 W Thread-334: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25495]" dev="sockfs" ino=25495 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-10 11:45:37.072  3687  3738 W jxcore-log: Starting JXcore engine
,08-10 11:45:37.175  3687  3738 W jxcore-log: Platform android
08-10 11:45:37.175  3687  3738 W jxcore-log: 
,08-10 11:45:37.175  3687  3738 W jxcore-log: Process ARCH arm
08-10 11:45:37.175  3687  3738 W jxcore-log: 
,08-10 11:45:37.441  3687  3738 I jxcore-log: JXcore Cordova bridge is ready!
08-10 11:45:37.441  3687  3738 I jxcore-log: 
,08-10 11:45:37.442  3687  3738 W jxcore-log: JXcore engine is started
,08-10 11:45:37.453  3687  3729 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 11:45:37.459  3687  3687 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 11:45:39.248  2902  3740 V KeepSync: Connecting to GoogleApiClient
,08-10 11:45:39.249   871   881 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 11:45:39.288  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:45:39.290  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:45:39.313  1502  2840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 11:45:39.313  1502  2840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 11:45:39.313  1502  2840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:45:39.313  1502  2840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:45:39.334  1870  3741 V BaseAuthAsyncOperation: access token request failed
08-10 11:45:39.336  2902  3740 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 11:45:39.412  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 11:45:39.412  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 11:45:39.412  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:45:39.413  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:45:39.425  2902  3740 E KeepSync: IOException
08-10 11:45:39.425  2902  3740 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 11:45:39.425  2902  3740 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:45:39.425  2902  3740 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 11:45:39.425  2902  3740 E KeepSync: 	... 10 more
,08-10 11:45:39.425  2902  3740 W KeepSync: Sync result 2
,08-10 11:45:39.431   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126902, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:45:39.612  1502  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 11:45:39.613  1502  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 11:45:39.613  1502  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 11:45:39.613  1502  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:45:39.633  2862  3743 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 11:45:39.633  2862  3743 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at blb.a(PG:3937)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at czp.a(PG:18188)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:45:39.633  2862  3743 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	... 12 more
08-10 11:45:39.633  2862  3743 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at fal.a(PG:38)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:45:39.633  2862  3743 E HttpOperation: 	... 14 more
,08-10 11:45:39.684  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 11:45:39.685  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 11:45:39.685  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:45:39.685  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:45:39.706  2862  3743 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 11:45:39.706  2862  3743 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at hec.a(PG:42)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at hee.a(PG:102)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at czr.a(PG:65)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at kka.a(PG:108)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at czp.a(PG:19176)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:45:39.706  2862  3743 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	... 15 more
08-10 11:45:39.706  2862  3743 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at fal.a(PG:38)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:45:39.706  2862  3743 E HttpOperation: 	... 17 more
,08-10 11:45:39.706  2862  3743 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 11:45:39.706  2862  3743 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at hec.a(PG:42)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at hee.a(PG:102)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at czr.a(PG:65)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at kka.a(PG:108)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	... 15 more
08-10 11:45:39.706  2862  3743 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at fal.a(PG:38)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 11:45:39.706  2862  3743 E ExperimentLoader: 	... 17 more
,08-10 11:45:39.847   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127064, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:45:53.577  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 11:45:53.577  3687  3738 I jxcore-log: 
,08-10 11:45:53.579  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 11:45:53.579  3687  3738 I jxcore-log: 
,08-10 11:45:53.589  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:45:53.589  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:45:53.589  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:45:53.589  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:45:53.589  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:45:53.589  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:45:53.589  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:45:53.589  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:45:53.594  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:45:53.596  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 11:45:53.596  3687  3738 I jxcore-log: 
,08-10 11:45:53.598  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 11:45:53.598  3687  3738 I jxcore-log: 
,08-10 11:45:53.934  3687  3738 I jxcore-log: Running unit tests
08-10 11:45:53.934  3687  3738 I jxcore-log: 
,08-10 11:45:53.935  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 11:45:53.935  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c063d5c added. We now have 2 listener(s)
,08-10 11:45:53.936  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 11:45:53.936  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 11:45:53.936  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 11:45:53.936  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:45:53.936  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6825865 added. We now have 2 listener(s)
08-10 11:45:53.936  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 11:45:53.937  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 11:45:53.941  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 11:45:53.954  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:45:53.954  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:45:53.954  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:45:53.954  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:45:53.954  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:45:53.954  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:45:53.954  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:45:53.954  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:45:53.957  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:45:53.957  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 11:45:53.958  3687  3738 D ExecuteNativeTests: Running unit tests
,08-10 11:45:53.963  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:45:53.975  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:45:54.047  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 11:45:54.047  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db added. We now have 3 listener(s)
08-10 11:45:54.048  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 11:45:54.048  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 11:45:54.048  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 11:45:54.048  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:45:54.048  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 added. We now have 3 listener(s)
08-10 11:45:54.048  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 11:45:54.050  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 11:45:54.054  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 11:45:54.064  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:45:54.064  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:45:54.064  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:45:54.064  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:45:54.064  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:45:54.064  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:45:54.064  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:45:54.064  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:45:54.070  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:45:54.071  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 11:45:54.076  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:45:54.078  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-10 11:45:54.081  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 11:45:54.081  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 11:45:54.081  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 11:45:54.082  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:45:54.084  3687  3738 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-10 11:45:54.084  3687  3738 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 11:45:54.084  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-10 11:45:54.085  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-10 11:45:54.085  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 11:45:54.085  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-10 11:45:54.085  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:45:54.085  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:45:54.086  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 11:45:54.086  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:45:54.086  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:45:54.086  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 11:45:54.086  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 11:45:54.086  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db removed from the list
08-10 11:45:54.086  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:45:54.086  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 removed from the list
08-10 11:45:54.086  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:45:54.086  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:45:54.087  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:45:54.087  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:45:54.088  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:45:54.088  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:45:54.088  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:45:54.088  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:45:54.090  3687  3738 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-10 11:45:54.090  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:45:54.091  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:45:54.091  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:45:54.091  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:45:54.091  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:45:54.091  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:45:54.091  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:45:54.091  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:45:54.091  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:45:54.091  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:45:54.091  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:45:54.091  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:45:54.091  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:45:54.091  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:45:54.094  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:45:54.094  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:45:54.095  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:45:54.095  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
,08-10 11:45:54.107  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 11:45:54.108  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-10 11:45:54.109  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 11:45:54.110  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:45:54.110  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:45:54.110  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:45:54.110  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:45:54.110  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:45:54.110  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:45:54.110  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
,08-10 11:45:54.110  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:45:54.110  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:45:54.110  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:45:54.110  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:45:54.110  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:45:54.110  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:45:54.111  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:45:54.113  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:45:54.113  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:45:54.113  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:45:54.113  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
,08-10 11:45:54.115  3687  3738 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 11:45:54.117  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 11:45:54.124  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:45:54.124  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:45:54.124  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:45:54.124  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:45:54.124  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:45:54.124  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:45:54.124  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:45:54.124  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:45:54.128  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 11:45:54.128  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 11:45:54.128  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 11:45:54.128  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 11:45:54.129  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-10 11:45:54.129  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-10 11:45:54.129  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 11:45:54.132  3687  3738 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 11:45:54.132  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 11:45:54.134  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:45:54.147  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 11:45:54.149  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:45:54.151  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 11:45:54.152  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 11:45:54.158  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-10 11:45:54.163  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-10 11:45:54.165  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 11:45:54.165  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-10 11:45:54.165  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 11:45:54.167  3687  3738 D BluetoothAdapter: STATE_ON
,08-10 11:45:54.171  2556  2567 D BtGatt.GattService: registerClient() - UUID=c8d5a247-0225-4941-ac48-ee4ebcd4a040
,08-10 11:45:54.172  2556  2609 D BtGatt.GattService: onClientRegistered() - UUID=c8d5a247-0225-4941-ac48-ee4ebcd4a040, clientIf=5
,08-10 11:45:54.174  3687  3698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 11:45:54.176  2556  2770 D BtGatt.GattService: start scan with filters
,08-10 11:45:54.183  2556  2614 D BtGatt.ScanManager: handling starting scan
,08-10 11:45:54.183  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 11:45:54.184  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-10 11:45:54.184  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-10 11:45:54.184  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 11:45:54.187  2556  2614 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:45:54.187  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 11:45:54.188  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 11:45:54.188  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 11:45:54.189  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 11:45:54.191  3687  3738 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 11:45:54.200  2556  2609 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 11:45:54.200  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:45:54.200  2556  2614 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 11:45:54.223  2556  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-10 11:45:54.223  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:45:54.224  2556  2614 D BtGatt.ScanManager: Starting BLE batch scan,
08-10 11:45:54.224  2556  2614 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-10 11:45:54.243  2556  2609 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 11:45:54.243  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:45:54.250  2556  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-10 11:45:54.250  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:45:54.406  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:45:54.421  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:45:54.429  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:45:54.520  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 11:45:54.521  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 11:45:54.521  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:45:54.521  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:45:54.580  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 11:45:54.582  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 11:45:54.585  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-10 11:45:54.693  3687  3687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-10 11:45:54.694  3687  3687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 11:45:54.694  3687  3687 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-10 11:45:55.757  2556  2556 D BtGatt.ScanManager: awakened up at time 143553
,08-10 11:45:55.759  2556  2614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:45:55.805  2556  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-10 11:45:55.805  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:45:55.807  2556  2609 D BtGatt.GattService: current time is 143603740617
,08-10 11:45:55.808  2556  2609 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -94, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -106, -15, -31, -128, 20, -7, 1, 0, -104, 24, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 17, 10, -44, 2, 2, -25, 21, 62, -103, 39, 95, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 71, -122, -77, 84, 69, -12, 1, -128, -85, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -92, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -67, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,08-10 11:45:55.812  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-10 11:45:55.814  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-10 11:45:55.815  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-10 11:45:55.816  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 17, 10, -44, 2, 2, -25, 21, 62, -103, 39, 95, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,08-10 11:45:55.817  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-10 11:45:55.817  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-10 11:45:55.818  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-10 11:45:57.311  2556  2556 D BtGatt.ScanManager: awakened up at time 145107
,08-10 11:45:57.313  2556  2614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:45:57.345  2556  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-10 11:45:57.345  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:45:57.346  2556  2609 D BtGatt.GattService: current time is 145143028680
08-10 11:45:57.347  2556  2609 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-10 11:45:57.347  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-10 11:45:58.848  2556  2556 D BtGatt.ScanManager: awakened up at time 146644
,08-10 11:45:58.851  2556  2614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:45:58.899  2556  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-10 11:45:58.899  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:45:58.900  2556  2609 D BtGatt.GattService: current time is 146697083112
08-10 11:45:58.901  2556  2609 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -78, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -71, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 22, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -65, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-10 11:45:58.902  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-10 11:45:58.903  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-10 11:45:58.904  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
08-10 11:45:58.905  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,08-10 11:45:58.906  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-10 11:45:58.907  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-10 11:45:59.201  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 11:45:59.201  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:45:59.202  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-10 11:45:59.202  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:45:59.202  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-10 11:45:59.203  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 11:45:59.203  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 11:45:59.203  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 11:45:59.204  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 11:45:59.207  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 11:45:59.208  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 11:45:59.210  3687  3738 D BluetoothAdapter: STATE_ON
08-10 11:45:59.212  2556  2569 D BtGatt.GattService: stopScan() - queue size =1
,08-10 11:45:59.215  2556  2773 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 11:45:59.216  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 11:45:59.220  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 11:45:59.221  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 11:45:59.221  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 11:45:59.221  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 11:45:59.224  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 11:45:59.235  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-10 11:45:59.235  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-10 11:45:59.236  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 11:45:59.238  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 11:45:59.241  2556  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-10 11:45:59.241  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 11:45:59.241  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:45:59.241  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 11:45:59.242  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 11:45:59.242  2556  2614 D BtGatt.ScanManager: stopping BLe Batch
08-10 11:45:59.242  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:45:59.242  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:45:59.242  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 11:45:59.243  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:45:59.243  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:45:59.244  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:45:59.244  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 11:45:59.244  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:45:59.252  2556  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 11:45:59.252  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:45:59.253  2556  2614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:45:59.260  2556  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-10 11:45:59.260  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:45:59.743  3687  3687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 11:46:02.251   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-10 11:46:02.260  1648  1648 I Keyboard.Facilitator: onFinishInput()
,08-10 11:46:02.270   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 11:46:02.270   871   891 I Adreno  : Build Date                       : 10/20/15
08-10 11:46:02.270   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 11:46:02.270   871   891 I Adreno  : Local Branch                     : M14
08-10 11:46:02.270   871   891 I Adreno  : Remote Branch                    : 
08-10 11:46:02.270   871   891 I Adreno  : Remote Branch                    : 
08-10 11:46:02.270   871   891 I Adreno  : Reconstruct Branch               : 
,08-10 11:46:02.307   282  1766 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (196 us)
,08-10 11:46:02.909  3687  3687 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 11:46:02.909  3687  3687 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-10 11:46:02.966   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-10 11:46:02.970  3687  3687 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9c4f85e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d3e0742, 16908290=android.view.AbsSavedState$1@d3e0742}, android:focusedViewId=100}]}]
,08-10 11:46:02.970  3687  3687 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-10 11:46:02.970  3687  3687 D io.jxcore.node.LifeCycleMonitor: onActivityStopped,
08-10 11:46:02.970  3687  3687 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-10 11:46:02.977   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-10 11:46:02.979   871   880 I art     : Background partial concurrent mark sweep GC freed 11910(866KB) AllocSpace objects, 5(136KB) LOS objects, 33% free, 28MB/43MB, paused 5.621ms total 98.123ms
,08-10 11:46:02.982   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-10 11:46:02.982   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-10 11:46:02.982   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-10 11:46:03.206   282   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-10 11:46:03.211   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-10 11:46:03.211   871  1329 D SurfaceControl: Excessive delay in setPowerMode(): 229ms
08-10 11:46:03.215   871   891 I DreamManagerService: Entering dreamland.
08-10 11:46:03.217   871   891 I PowerManagerService: Dozing...
08-10 11:46:03.219   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-10 11:46:03.273   375  1277 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-10 11:46:03.273   375  1277 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-10 11:46:03.284   871  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 11:46:03.288  1698  3759 D NfcService: Discovery configuration equal, not updating.
,08-10 11:46:03.297   871  1302 E native  : do suspend false
,08-10 11:46:03.316   871  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-10 11:46:03.328   871  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 11:46:03.332   871  1302 E native  : do suspend true
,08-10 11:46:03.416   375  1310 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-10 11:46:03.416   375  1310 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-10 11:46:03.789   871  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-10 11:46:04.246  3687  3738 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 11:46:04.254  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 11:46:04.268  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:46:04.268  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:04.268  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:04.268  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:04.268  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:04.268  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:04.268  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:46:04.268  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:46:04.274  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:46:04.275  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 11:46:04.276  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 11:46:04.277  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 11:46:04.277  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-10 11:46:04.277  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 11:46:04.278  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 11:46:04.283  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:04.288  3687  3738 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 11:46:04.288  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 11:46:04.291  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:04.305  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 11:46:04.307  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 11:46:04.307  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 11:46:04.316  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 11:46:04.316  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-10 11:46:04.316  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 11:46:04.318  3687  3738 D BluetoothAdapter: STATE_ON
,08-10 11:46:04.324  2556  2567 D BtGatt.GattService: registerClient() - UUID=a114725e-ce69-493f-a899-fd948368532d
,08-10 11:46:04.325  2556  2609 D BtGatt.GattService: onClientRegistered() - UUID=a114725e-ce69-493f-a899-fd948368532d, clientIf=5
08-10 11:46:04.326  3687  3699 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 11:46:04.327  2556  2770 D BtGatt.GattService: start scan with filters
,08-10 11:46:04.334  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 11:46:04.335  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 11:46:04.335  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-10 11:46:04.335  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-10 11:46:04.337  2556  2614 D BtGatt.ScanManager: handling starting scan
,08-10 11:46:04.345  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 11:46:04.346  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 11:46:04.347  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 11:46:04.351  2556  2609 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 11:46:04.351  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:46:04.352  2556  2614 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 11:46:04.354  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 11:46:04.366  3687  3738 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 11:46:04.372  2556  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 11:46:04.372  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:46:04.372  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:46:04.372  2556  2614 D BtGatt.ScanManager: Starting BLE batch scan
08-10 11:46:04.372  3687  3738 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-10 11:46:04.373  2556  2614 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 11:46:04.373  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:46:04.373  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-10 11:46:04.375  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:04.375  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-10 11:46:04.376  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-10 11:46:04.376  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-10 11:46:04.376  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 11:46:04.376  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 11:46:04.377  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 11:46:04.377  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 11:46:04.378  3687  3738 D BluetoothAdapter: STATE_ON
08-10 11:46:04.379  2556  2567 D BtGatt.GattService: stopScan() - queue size =1
08-10 11:46:04.380  2556  2770 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 11:46:04.381  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 11:46:04.382  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 11:46:04.382  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 11:46:04.382  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 11:46:04.382  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-10 11:46:04.385  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 11:46:04.385  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 11:46:04.385  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-10 11:46:04.386  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 11:46:04.388  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 11:46:04.388  2556  2609 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0,
08-10 11:46:04.388  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:46:04.390  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 11:46:04.390  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 11:46:04.391  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 11:46:04.391  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:04.391  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:04.391  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 11:46:04.392  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
,08-10 11:46:04.392  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:04.392  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:04.392  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:04.392  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:04.393  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:04.394  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:04.397  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:04.397  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 11:46:04.397  2556  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 11:46:04.397  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:04.398  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:04.398  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:46:04.399  3687  3738 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 11:46:04.404  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 11:46:04.407  2556  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 11:46:04.407  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:46:04.407  2556  2614 D BtGatt.ScanManager: stopping BLe Batch
,08-10 11:46:04.411  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:46:04.411  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:04.411  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:04.411  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:04.411  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:04.411  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:04.411  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:46:04.411  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:46:04.413  2556  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 11:46:04.413  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:46:04.413  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:04.413  2556  2614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:46:04.413  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 11:46:04.418  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:04.418  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 11:46:04.419  2556  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-10 11:46:04.419  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:46:04.419  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 11:46:04.420  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-10 11:46:04.421  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 11:46:04.421  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 11:46:04.421  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:04.424  3687  3738 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 11:46:04.424  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 11:46:04.427  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 11:46:04.428  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 11:46:04.428  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 11:46:04.431  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 11:46:04.431  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-10 11:46:04.431  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 11:46:04.432  3687  3738 D BluetoothAdapter: STATE_ON
,08-10 11:46:04.434  2556  2770 D BtGatt.GattService: registerClient() - UUID=458d06d7-d96c-4c62-b37d-3fc2cf3d6b0a
,08-10 11:46:04.434  2556  2609 D BtGatt.GattService: onClientRegistered() - UUID=458d06d7-d96c-4c62-b37d-3fc2cf3d6b0a, clientIf=5
08-10 11:46:04.434  3687  3698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 11:46:04.435  2556  2773 D BtGatt.GattService: start scan with filters
,08-10 11:46:04.437  2556  2614 D BtGatt.ScanManager: handling starting scan
,08-10 11:46:04.438  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 11:46:04.438  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-10 11:46:04.438  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 11:46:04.438  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 11:46:04.441  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 11:46:04.441  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-10 11:46:04.441  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 11:46:04.443  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-10 11:46:04.444  2556  2609 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 11:46:04.444  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:46:04.444  2556  2614 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 11:46:04.445  3687  3738 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 11:46:04.450  2556  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-10 11:46:04.450  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:46:04.450  2556  2614 D BtGatt.ScanManager: Starting BLE batch scan
,08-10 11:46:04.450  2556  2614 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-10 11:46:04.462  2556  2609 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 11:46:04.462  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:46:04.468  2556  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-10 11:46:04.468  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-10 11:46:04.942  3687  3687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-10 11:46:04.943  3687  3687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 11:46:04.943  3687  3687 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-10 11:46:05.974  2556  2556 D BtGatt.ScanManager: awakened up at time 153771
,08-10 11:46:05.976  2556  2614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:46:06.015  2556  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-10 11:46:06.015  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:46:06.016  2556  2609 D BtGatt.GattService: current time is 153812776850
,08-10 11:46:06.017  2556  2609 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -86, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -84, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -92, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -106, -15, -31, -128, 20, -7, 1, 0, -102, 20, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 28, 10, -44, 2, 2, -25, 21, 62, -74, 44, -105, 28, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, -46, -4, -117, 6, 105, -37, 1, -128, -92, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -79, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-10 11:46:06.018  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-10 11:46:06.019  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-10 11:46:06.019  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-10 11:46:06.020  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-10 11:46:06.021  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 28, 10, -44, 2, 2, -25, 21, 62, -74, 44, -105, 6, 8, 116, 105, 115, 54, 67, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
08-10 11:46:06.022  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-10 11:46:06.022  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-10 11:46:07.280  1768  2324 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 11:46:07.522  2556  2556 D BtGatt.ScanManager: awakened up at time 155318
,08-10 11:46:07.527  2556  2614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:46:07.574  2556  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,08-10 11:46:07.575  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:46:07.576  2556  2609 D BtGatt.GattService: current time is 155373255903
,08-10 11:46:07.577  2556  2609 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -98, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -90, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-10 11:46:07.578  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-10 11:46:07.579  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-10 11:46:07.580  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-10 11:46:07.581  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-10 11:46:09.078  2556  2556 D BtGatt.ScanManager: awakened up at time 156875
,08-10 11:46:09.081  2556  2614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:46:09.134  2556  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-10 11:46:09.135  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:46:09.135  2556  2609 D BtGatt.GattService: current time is 156932322768
,08-10 11:46:09.137  2556  2609 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -86, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -83, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -82, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -99, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -90, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-10 11:46:09.138  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-10 11:46:09.140  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-10 11:46:09.141  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-10 11:46:09.142  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-10 11:46:09.143  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-10 11:46:09.143  2556  2609 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-10 11:46:09.446  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 11:46:09.446  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:09.447  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 11:46:09.447  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:09.447  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-10 11:46:09.448  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-10 11:46:09.448  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 11:46:09.448  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 11:46:09.448  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 11:46:09.449  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 11:46:09.449  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-10 11:46:09.451  3687  3738 D BluetoothAdapter: STATE_ON
08-10 11:46:09.453  2556  2773 D BtGatt.GattService: stopScan() - queue size =1
08-10 11:46:09.457  2556  2567 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 11:46:09.458  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 11:46:09.458  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-10 11:46:09.458  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 11:46:09.459  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 11:46:09.459  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 11:46:09.464  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 11:46:09.464  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-10 11:46:09.464  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 11:46:09.464  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 11:46:09.465  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 11:46:09.470  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 11:46:09.470  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 11:46:09.470  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 11:46:09.476  2556  2609 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-10 11:46:09.476  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:46:09.477  2556  2614 D BtGatt.ScanManager: stopping BLe Batch
,08-10 11:46:09.492  2556  2609 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 11:46:09.492  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:46:09.492  2556  2614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:46:09.507  2556  2609 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-10 11:46:09.507  2556  2609 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:46:09.957  3628  3764 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 11:46:09.971  3687  3687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 11:46:09.972  3687  3687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:46:09.972  3687  3687 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-10 11:46:10.004  3628  3765 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 11:46:10.021  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:10.027  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:10.062  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 11:46:10.062  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 11:46:10.063  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:46:10.063  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:46:10.118  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:10.124  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:10.193  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 11:46:10.194  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 11:46:10.194  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 11:46:10.195  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:46:10.249  3628  3765 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 11:46:10.256  3628  3764 E BooksSync: Soft error
08-10 11:46:10.256  3628  3764 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:46:10.256  3628  3764 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 11:46:10.257  3628  3764 E BooksSync: Sync error
08-10 11:46:10.257  3628  3764 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:46:10.257  3628  3764 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 11:46:10.258  3628  3764 I BooksSync: Finished books sync
,08-10 11:46:10.272   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 156330, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:46:14.472  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 11:46:14.472  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:46:14.473  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 11:46:14.474  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 11:46:14.475  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:14.475  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 11:46:14.476  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
,08-10 11:46:14.476  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:14.476  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.476  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:14.477  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.479  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:14.480  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.483  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:14.483  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 11:46:14.484  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.484  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.487  3687  3738 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-10 11:46:14.489  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:46:14.491  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:46:14.492  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:46:14.492  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:14.493  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:14.493  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.494  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:14.494  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.494  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.494  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 11:46:14.495  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.495  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.495  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.495  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:14.497  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:14.497  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:14.498  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.498  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
,08-10 11:46:14.499  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 11:46:14.499  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:46:14.499  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:14.499  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 11:46:14.500  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:14.500  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:14.500  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.500  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:14.500  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.500  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.501  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:14.501  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:14.501  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.501  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.501  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:14.503  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:14.503  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 11:46:14.503  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.503  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.504  3687  3738 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 11:46:14.504  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:46:14.504  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:14.504  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:46:14.505  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 11:46:14.505  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.505  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.505  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:14.505  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.505  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.505  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:14.505  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:14.505  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.505  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.505  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.506  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:14.507  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 11:46:14.507  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.507  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.508  3687  3738 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-10 11:46:14.508  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:46:14.508  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:14.508  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:46:14.509  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:14.509  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.509  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.509  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:14.509  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:14.509  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.509  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:14.509  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.510  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.510  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.510  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.512  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 11:46:14.512  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:14.512  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.512  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.513  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 11:46:14.513  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 11:46:14.513  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 11:46:14.514  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-10 11:46:14.514  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 11:46:14.514  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 11:46:14.514  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 11:46:14.514  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 11:46:14.514  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 11:46:14.515  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 11:46:14.515  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:14.515  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:46:14.515  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:14.515  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.515  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.516  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:14.516  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.516  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.516  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 11:46:14.516  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.516  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.516  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.516  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:14.518  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:14.518  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:14.519  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.519  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
,08-10 11:46:14.521  3687  3738 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-10 11:46:14.522  3687  3738 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 11:46:14.522  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-10 11:46:14.529  3687  3738 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-10 11:46:14.529  3687  3738 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-10 11:46:14.529  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-10 11:46:14.529  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 11:46:14.529  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-10 11:46:14.530  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 11:46:14.530  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 11:46:14.530  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-10 11:46:14.530  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 11:46:14.530  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 11:46:14.531  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 11:46:14.532  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 11:46:14.532  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 11:46:14.532  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-10 11:46:14.532  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 11:46:14.532  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 11:46:14.533  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 11:46:14.533  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 11:46:14.533  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 11:46:14.533  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 11:46:14.533  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 11:46:14.533  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 11:46:14.534  3687  3738 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 11:46:14.534  3687  3738 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 11:46:14.534  3687  3738 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 11:46:14.535  3687  3738 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 11:46:14.535  3687  3738 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-10 11:46:14.535  3687  3738 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 11:46:14.535  3687  3738 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 11:46:14.535  3687  3738 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 11:46:14.535  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 11:46:14.539  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-10 11:46:14.541  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 11:46:14.541  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 11:46:14.543  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-10 11:46:14.543  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-10 11:46:14.543  3687  3738 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-10 11:46:14.544  3687  3738 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 11:46:14.544  3687  3738 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-10 11:46:14.545  3687  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 398)
,08-10 11:46:14.547  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 11:46:14.547  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:14.547  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:46:14.547  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 11:46:14.548  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.548  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.548  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-10 11:46:14.549  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:14.550  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:14.550  3687  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 398
08-10 11:46:14.550  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.550  3687  3766 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 11:46:14.550  3687  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 398)
08-10 11:46:14.550  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:14.550  3687  3767 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 398)
08-10 11:46:14.550  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.550  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.551  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.551  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:14.553  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 11:46:14.554  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 11:46:14.554  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:14.554  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.554  3687  3766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 398)
,08-10 11:46:14.555  3687  3738 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 11:46:14.555  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 11:46:14.555  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:14.555  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 11:46:14.556  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:14.556  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:14.556  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:14.556  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:14.556  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:14.556  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.556  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 11:46:14.556  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.556  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.556  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-10 11:46:14.556  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:14.557  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:14.557  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:14.557  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.558  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.558  3687  3738 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 11:46:14.558  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:46:14.559  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:14.559  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:46:14.559  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:14.559  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.559  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.559  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:14.559  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.560  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.560  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:14.560  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.560  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.560  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.560  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.561  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:14.561  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:14.561  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.561  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.562  3687  3738 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 11:46:14.562  3687  3738 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-10 11:46:14.562  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 11:46:14.562  3687  3738 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 11:46:14.562  3687  3738 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Tryi,ng to close connection to peer with ID 00:11:22:33:44:55
08-10 11:46:14.562  3687  3738 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 11:46:14.562  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 11:46:14.563  3687  3738 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 11:46:14.563  3687  3738 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 11:46:14.563  3687  3738 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 11:46:14.563  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 11:46:14.563  3687  3738 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 11:46:14.563  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:46:14.563  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:14.563  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:46:14.563  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:14.563  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.564  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.564  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:14.564  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.564  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.564  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:14.564  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.564  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.564  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.564  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.565  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:14.565  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:14.565  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.565  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.566  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:14.566  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.566  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:14.566  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:14.566  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:14.567  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:14.567  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:14.567  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:14.567  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:14.779  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:14.781  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:14.803  3461  3769 V GoogleAuthProtoRequest: [295] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 11:46:14.843  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 11:46:14.843  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-10 11:46:14.843  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:46:14.843  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: [295] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: [295] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 11:46:14.863  3461  3769 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 11:46:14.932   871  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-10 11:46:14.948  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:14.972  1502  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 11:46:14.972  1502  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 11:46:14.972  1502  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:46:14.972  1502  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:46:15.000  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 11:46:15.000  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 11:46:15.000  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-10 11:46:18.014   871  2102 D NetlinkSocketObserver: NeighborEvent{elapsedMs=165810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:46:19.568  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:19.568  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:19.569  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:19.569  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:19.569  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:19.569  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:19.570  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:46:19.571  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:19.571  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 11:46:19.571  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:19.571  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.572  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:19.572  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:19.572  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:19.573  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
,08-10 11:46:19.573  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:19.573  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.574  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.574  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:19.574  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:19.580  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 11:46:19.580  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:19.581  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:19.582  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
,08-10 11:46:19.590  3687  3738 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 11:46:19.591  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 11:46:19.592  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-10 11:46:19.593  3687  3738 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-10 11:46:19.594  3687  3738 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-10 11:46:19.595  3687  3687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-10 11:46:19.595  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-10 11:46:19.595  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-10 11:46:19.596  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:19.596  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 11:46:19.596  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-10 11:46:19.596  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-10 11:46:19.596  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.596  3687  3738 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-10 11:46:19.597  3687  3687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 11:46:19.597  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
,08-10 11:46:19.597  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:19.597  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 11:46:19.597  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 11:46:19.597  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 11:46:19.598  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:19.598  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.598  3687  3770 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 11:46:19.600  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 11:46:19.601  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 11:46:19.601  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 11:46:19.602  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 11:46:19.601  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
,08-10 11:46:19.602  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:46:19.603  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:46:19.603  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:46:19.603  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 11:46:19.604  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.604  3687  3770 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-10 11:46:19.604  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:19.604  3687  3770 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-10 11:46:19.604  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
,08-10 11:46:19.604  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:19.604  3687  3770 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-10 11:46:19.605  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:19.605  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 11:46:19.605  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.605  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:19.605  3687  3687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-10 11:46:19.606  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:19.607  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:19.609  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 11:46:19.609  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:19.610  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:19.610  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:19.613  3687  3738 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-10 11:46:19.614  3687  3738 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 11:46:19.614  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-10 11:46:19.615  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 11:46:19.615  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 11:46:19.616  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 11:46:19.616  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:19.616  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 11:46:19.617  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:19.617  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.617  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:19.618  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:19.618  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:19.618  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:19.618  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:19.619  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.619  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.620  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.621  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:19.624  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:19.625  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:19.625  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:19.625  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
,08-10 11:46:19.631  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 11:46:19.631  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:46:19.631  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:46:19.632  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:19.632  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.632  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.632  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
08-10 11:46:19.632  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:19.632  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:19.632  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:19.632  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.632  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.632  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.633  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.634  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 11:46:19.634  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:19.634  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:19.634  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:19.635  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 11:46:19.635  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:46:19.635  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 11:46:19.636  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:46:19.636  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:19.636  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.636  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46853db not in the list
,08-10 11:46:19.636  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:19.636  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
,08-10 11:46:19.636  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:19.636  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:19.636  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.636  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:19.637  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.638  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:46:19.638  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:46:19.638  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-10 11:46:19.638  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5a9e78 not in the list
08-10 11:46:19.639  3687  3738 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-10 11:46:19.639  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 11:46:19.640  3687  3738 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 11:46:19.640  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-10 11:46:19.641  3687  3738 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 11:46:19.641  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 11:46:19.643  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 11:46:19.643  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 11:46:19.644  3687  3738 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 11:46:19.644  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 11:46:19.644  3687  3738 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 11:46:19.644  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 11:46:19.644  3687  3738 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-10 11:46:19.644  3687  3738 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,08-10 11:46:19.645  3687  3738 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 11:46:19.645  3687  3738 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-10 11:46:19.646  3687  3738 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 11:46:19.646  3687  3738 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 11:46:19.646  3687  3738 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 11:46:19.646  3687  3738 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-10 11:46:19.647  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 11:46:19.647  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@261e9cb added. We now have 3 listener(s)
08-10 11:46:19.648  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 11:46:19.649  3687  3738 D BluetoothAdapter: enable(): BT is already enabled..!
,08-10 11:46:19.650   871  1725 D WifiService: setWifiEnabled: true pid=3687, uid=10000
08-10 11:46:19.650   871  1725 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 11:46:19.651  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:46:19.651  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ee95a8 added. We now have 4 listener(s)
,08-10 11:46:19.651  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 11:46:19.656  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:19.656  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ee95a8 removed from the list
08-10 11:46:19.656  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:19.656  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:19.656  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:19.657  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:46:19.657  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d1f18c1 added. We now have 4 listener(s)
,08-10 11:46:19.657  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 11:46:19.658  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:19.658  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d1f18c1 removed from the list
,08-10 11:46:19.659  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:19.659  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:19.659  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:19.659  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:46:19.659  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60e8866 added. We now have 4 listener(s)
08-10 11:46:19.660  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 11:46:19.662   871  1680 D WifiService: setWifiEnabled: false pid=3687, uid=10000
,08-10 11:46:19.662   871  1680 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 11:46:19.669  2556  2605 D BluetoothAdapterState: Current state: ON, message: 23
08-10 11:46:19.669  2556  2605 D BluetoothAdapterProperties: Setting state to 13
08-10 11:46:19.669  2556  2605 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 11:46:19.670  2556  2605 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 11:46:19.671  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 11:46:19.671  2556  2605 I BluetoothAdapterState: Entering PendingCommandState
08-10 11:46:19.672  2556  2609 D BluetoothAdapterProperties: Scan Mode:20
08-10 11:46:19.672  2556  2605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-10 11:46:19.677  2556  2556 D HeadsetService: Received stop request...Stopping profile...
,08-10 11:46:19.680  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:19.681  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:46:19.681  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:19.681  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:19.681  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:19.681  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:19.681  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:19.681  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:46:19.681  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 11:46:19.681  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:19.681  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:19.682  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 11:46:19.684  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 11:46:19.685  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:19.688  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:19.689   871  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 11:46:19.689   871  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-10 11:46:19.690   871  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 11:46:19.690   871  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 11:46:19.693  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:19.693  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:19.693  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:19.693  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:19.693  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:19.693  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:19.693  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:19.693  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:46:19.693  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:46:19.695  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:19.695  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:46:19.699   871  1302 E native  : do suspend true
,08-10 11:46:19.699  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:19.699  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:19.699  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:19.699  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:19.699  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:19.699  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:19.699  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:19.699  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:46:19.699  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:46:19.700  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:19.700  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:46:19.702   871   884 I ActivityManager: Start proc 3773:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-10 11:46:19.704  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:19.707  2556  2556 D BluetoothMapService: onReceive
,08-10 11:46:19.707  2556  2556 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-10 11:46:19.707  2556  2556 D BluetoothMapService: STATE_TURNING_OFF
08-10 11:46:19.707  2556  2556 V BluetoothAdapterState: isTurningOff()=true
08-10 11:46:19.708  2556  2556 V BluetoothAdapterState: isTurningOn()=false
,08-10 11:46:19.708  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:19.708  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:19.708  1711  1864 D BluetoothHeadset: Proxy object disconnected
08-10 11:46:19.708   871   871 D BluetoothHeadset: Proxy object disconnected
08-10 11:46:19.708   871   871 D BluetoothHeadset: Proxy object disconnected
,08-10 11:46:19.708  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:19.708   871   871 D BluetoothHeadset: Proxy object disconnected
08-10 11:46:19.709  1361  1378 D BluetoothHeadset: Proxy object disconnected
,08-10 11:46:19.709  2556  2556 D A2dpService: Received stop request...Stopping profile...
08-10 11:46:19.710  2556  2757 D A2dpStateMachine: Exit Disconnected: -1
,08-10 11:46:19.711  2556  2747 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-10 11:46:19.711  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:19.711  2556  2752 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-10 11:46:19.712   871   871 D BluetoothA2dp: Proxy object disconnected
,08-10 11:46:19.712   871  2103 D DhcpClient: Clearing IP address
08-10 11:46:19.713   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-10 11:46:19.713  2556  2556 D HidService: Received stop request...Stopping profile...
,08-10 11:46:19.713  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:19.713  2556  2556 D HidService: Stopping Bluetooth HidService
08-10 11:46:19.714  2556  2556 D HealthService: Received stop request...Stopping profile...
08-10 11:46:19.716  2556  2556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 11:46:19.716  2556  2556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 11:46:19.716  2556  2609 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-10 11:46:19.717  2556  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 11:46:19.717  2556  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 11:46:19.717  2556  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 11:46:19.720   371   869 D CommandListener: Setting iface cfg
08-10 11:46:19.721  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-10 11:46:19.721  2556  2609 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-10 11:46:19.721  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-10 11:46:19.721  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-10 11:46:19.721  1361  1361 D HidProfile: Bluetooth service disconnected
08-10 11:46:19.722  2556  2556 D BluetoothMapService: MAP Service closeService in
08-10 11:46:19.722  2556  2556 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 11:46:19.722  2556  2556 D ObexServerSockets0: shutdown(block = true)
08-10 11:46:19.722  1502  2275 V NativeCrypto: Read error: ssl=0x9b810800: I/O error during system call, Connection timed out
08-10 11:46:19.722  2556  2775 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-10 11:46:19.724  2556  2556 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 11:46:19.724  2556  2777 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-10 11:46:19.724  2556  2752 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 11:46:19.724  2556  2556 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 11:46:19.724   871  1302 D WifiStateMachine: Start Disconnecting Watchdog 1
08-10 11:46:19.724  2556  2556 I BtOppRfcommListener: stopping Accept Thread
08-10 11:46:19.725  2556  3291 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 11:46:19.725  2556  3291 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 11:46:19.726   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 11:46:19.727   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-10 11:46:19.728   871  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 11:46:19.728   871  1302 E native  : do suspend true
,08-10 11:46:19.729   394   394 E Parcel  : Reading a NULL string not supported here.
08-10 11:46:19.730  2556  2556 D PanService: Received stop request...Stopping profile...
08-10 11:46:19.731  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 11:46:19.731  1361  1361 D PanProfile: Bluetooth service disconnected
08-10 11:46:19.731  2556  2556 D BluetoothMapService: Received stop request...Stopping profile...
08-10 11:46:19.731  2556  2556 D BluetoothMapService: stop()
08-10 11:46:19.732  1502  2275 V NativeCrypto: SSL shutdown failed: ssl=0x9b810800: I/O error during system call, Broken pipe
,08-10 11:46:19.732  2556  2556 D BluetoothMapAppObserver: deinitObservers()
08-10 11:46:19.732  2556  2556 D BluetoothMapAppObserver: removeReceiver()
,08-10 11:46:19.734  2556  2556 V BluetoothAdapterState: isTurningOff()=true
08-10 11:46:19.734  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:19.734   871  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-10 11:46:19.734  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 11:46:19.734  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:19.734  1361  1361 D BluetoothMap: Proxy object disconnected
08-10 11:46:19.734  1361  1361 D MapProfile: Bluetooth service disconnected
08-10 11:46:19.736  2556  2556 V BluetoothAdapterState: isTurningOff()=true
08-10 11:46:19.736  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:19.736  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:19.736  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:19.736  2556  2556 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 11:46:19.736  2556  2556 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 11:46:19.736  2556  2556 V BluetoothAdapterState: isTurningOff()=true
08-10 11:46:19.737  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:19.737  2556  2609 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 11:46:19.737  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:19.737  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:19.737  2556  2609 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 11:46:19.737  2556  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 11:46:19.737  2556  2556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 11:46:19.737  2556  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 11:46:19.737  2556  2747 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 11:46:19.737  2556  2747 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 11:46:19.737  2556  2747 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 11:46:19.737  2556  2747 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 11:46:19.737  2556  2609 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-10 11:46:19.738  2556  2556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 11:46:19.739  2556  2556 V BluetoothAdapterState: isTurningOff()=true
,08-10 11:46:19.739  2556  2556 V BluetoothAdapterState: isTurningOn()=false
,08-10 11:46:19.739  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:19.740  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:19.740  2556  2556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 11:46:19.740  2556  2556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 11:46:19.741  2556  2556 D BluetoothMapService: MAP Service closeService in
08-10 11:46:19.742  2556  2556 V BluetoothAdapterState: isTurningOff()=true
,08-10 11:46:19.742  2556  2556 V BluetoothAdapterState: isTurningOn()=false
,08-10 11:46:19.742  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 11:46:19.742  2556  2556 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:19.742  2556  2605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 11:46:19.742  2556  2605 D BluetoothAdapterProperties: Setting state to 15
08-10 11:46:19.742  2556  2556 D BluetoothMapService: cleanup()
08-10 11:46:19.742  2556  2605 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15,
08-10 11:46:19.742  2556  2556 D BluetoothMapService: MAP Service closeService in
08-10 11:46:19.743  2556  2605 I BluetoothAdapterState: Entering BleOnState
,08-10 11:46:19.743  1361  1373 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 11:46:19.744  1361  1814 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-10 11:46:19.744   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 11:46:19.744   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 11:46:19.745  1361  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 11:46:19.745  1711  1864 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 11:46:19.745  1361  1373 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 11:46:19.746  1361  1814 D BluetoothPan: onBluetoothStateChange on: false
,08-10 11:46:19.746   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 11:46:19.746   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 11:46:19.747  1361  1378 D BluetoothMap: onBluetoothStateChange: up=false
08-10 11:46:19.747  2556  2605 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-10 11:46:19.747  2556  2605 D BluetoothAdapterProperties: Setting state to 16
08-10 11:46:19.747  2556  2605 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-10 11:46:19.748  2556  2605 D BluetoothAdapterProperties: onBleDisable
08-10 11:46:19.748  2556  2605 I BluetoothAdapterState: Entering PendingCommandState
08-10 11:46:19.748  2556  2606 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-10 11:46:19.749  2556  2747 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 11:46:19.749  2556  2747 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 11:46:19.750  2556  2609 D BluetoothAdapterProperties: Scan Mode:20
,08-10 11:46:19.753  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:19.753   871  2104 D DhcpClient: Receive thread stopped
08-10 11:46:19.754  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:19.754  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:19.754  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:19.754  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:19.754  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:19.754  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:19.754  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:19.754  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:19.755  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:19.755  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:19.758  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:19.758  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:19.758  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:19.758  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:19.758  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:19.758  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:19.758  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:19.758  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:19.758  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:19.759  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:19.759  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:19.763  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:19.763  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:19.763  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:19.763  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:19.763  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:19.763  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:19.763  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:19.763  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:19.763  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:19.764  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:19.764  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:19.765  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:19.767  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:19.768  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:19.774   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 11:46:19.784  3773  3773 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-10 11:46:19.790   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 11:46:19.790   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-10 11:46:19.791   871  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-10 11:46:19.791   871  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 11:46:19.792   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-10 11:46:19.795  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:19.797  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:19.798  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:19.799  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 11:46:19.803  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 11:46:19.805   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ab801a1:true
,08-10 11:46:19.814   871  1725 I ActivityManager: Start proc 3791:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-10 11:46:19.824  3773  3773 D LocalBluetoothProfileManager: Adding local MAP profile
,08-10 11:46:19.826  3773  3773 D BluetoothMap: Create BluetoothMap proxy object
,08-10 11:46:19.838  3773  3773 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-10 11:46:19.840   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-10 11:46:19.842   871  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 11:46:19.849  3791  3791 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-10 11:46:19.854  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-10 11:46:19.858   871  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 11:46:19.860  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:19.860  1768  2054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 11:46:19.860  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:19.860  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:19.860  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:19.860  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:19.860  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:19.860  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:19.860  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:19.860  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:19.860  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:19.860  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:19.861  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:19.862  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:19.862  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:19.862  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:19.862  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:19.862  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:19.862  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:19.862  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:19.862  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:19.862  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:19.862  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:19.863   871  1929 I ActivityManager: Killing 3427:com.google.process.gapps/u0a99 (adj 15): empty #17
08-10 11:46:19.863   871  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-10 11:46:19.864  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:19.864  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:19.864  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:19.864  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:19.864  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:19.864  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:19.864  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:19.864  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:19.864  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:19.864  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:19.864  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:19.950  2556  2609 I bt_hci  : shut_down
,08-10 11:46:19.954  2556  2615 I bt_vendor: low_power_mode_cb
,08-10 11:46:19.963  2556  2615 D bt_hwcfg: hw_epilog_process
,08-10 11:46:19.977  2556  2615 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-10 11:46:19.977  2556  2615 I bt_vendor: epilog_cb
,08-10 11:46:19.977  2556  2615 I bt_hci  : epilog_finished_callback
,08-10 11:46:19.979  2556  2609 I bt_hci_h4: hal_close
,08-10 11:46:19.979  2556  2609 I bt_userial_vendor: device fd = 51 close
,08-10 11:46:20.100  2556  2606 D bt_stack_manager: event_shut_down_stack finished.
08-10 11:46:20.101  2556  2605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 11:46:20.103  3687  3687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 11:46:20.105  2556  2605 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-10 11:46:20.105  2556  2556 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 11:46:20.106  2556  2556 D BtGatt.GattService: Received stop request...Stopping profile...
,08-10 11:46:20.106  2556  2556 D BtGatt.GattService: stop()
,08-10 11:46:20.106  2556  2556 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 11:46:20.109  2556  2556 V BluetoothAdapterState: isTurningOff()=false
08-10 11:46:20.110  2556  2556 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:20.110  2556  2556 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:20.110  2556  2556 V BluetoothAdapterState: isBleTurningOff()=true
08-10 11:46:20.110  3791  3791 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 11:46:20.110  3791  3791 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:46:20.110  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 11:46:20.111  3791  3791 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 11:46:20.111  3791  3791 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 11:46:20.111  3791  3791 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.k.d(PG:583)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 11:46:20.111  3791  3791 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 11:46:20.111  3791  3791 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 11:46:20.111  3791  3791 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 11:46:20.111  3791  3791 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 11:46:20.111  2556  2605 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-10 11:46:20.112  2556  2605 D BluetoothAdapterProperties: Setting state to 10
08-10 11:46:20.112  2556  2605 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-10 11:46:20.113  2556  2605 I BluetoothAdapterState: Entering OffState
08-10 11:46:20.115   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-10 11:46:20.143   871  1724 I ActivityManager: Start proc 3823:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-10 11:46:20.144   871  1724 I ActivityManager: Killing 2630:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-10 11:46:20.213  2556  2556 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-10 11:46:20.213  2556  2556 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-10 11:46:20.213  2556  2556 I BluetoothServiceJni: cleanupNative: return from cleanup
08-10 11:46:20.214  2556  2606 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-10 11:46:20.217  2556  2606 D bt_stack_manager: event_clean_up_stack finished.
,08-10 11:46:20.235  3823  3823 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-10 11:46:20.237  2556  2556 I art     : System.exit called, status: 0
,08-10 11:46:20.237  2556  2556 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 11:46:20.292   871  1724 I ActivityManager: Process com.android.bluetooth (pid 2556) has died
,08-10 11:46:20.438  3823  3841 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-10 11:46:20.438  3823  3841 I Babel_SMS: MmsConfig.loadMmsSettings
,08-10 11:46:20.454  3823  3841 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-10 11:46:20.454  3823  3841 I Babel_SMS: MmsConfig.loadFromDatabase
,08-10 11:46:20.494  3823  3841 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-10 11:46:20.495  3823  3841 I Babel_SMS: MmsConfig.loadFromResources
,08-10 11:46:20.498  3823  3841 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-10 11:46:20.499  3823  3841 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-10 11:46:20.531  3823  3823 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 11:46:20.535  3823  3823 I Babel_Crash: startup - clean
,08-10 11:46:20.562  3823  3823 I Babel_telephony: TeleModule.launchCompleted
,08-10 11:46:20.573   871  1899 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-10 11:46:20.577  3823  3823 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-10 11:46:20.586  3823  3823 W Babel   : BAM#gBA: invalid account id: -1
,08-10 11:46:20.586  3823  3823 W Babel   : BAM#gBA: invalid account id: -1
08-10 11:46:20.586  3823  3823 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-10 11:46:20.594  3823  3847 I Babel   : deleted: false for 0
,08-10 11:46:20.596   871  1680 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-10 11:46:20.608  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 11:46:20.649   871  1680 I ActivityManager: Start proc 3850:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-10 11:46:20.660  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-10 11:46:20.669  3823  3823 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 11:46:20.786  3823  3823 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-10 11:46:20.802  3823  3823 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 11:46:20.804  3823  3823 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 11:46:20.813  3850  3850 D AdapterServiceConfig: Adding HeadsetService
08-10 11:46:20.813  3850  3850 D AdapterServiceConfig: Adding A2dpService
08-10 11:46:20.813  3850  3850 D AdapterServiceConfig: Adding HidService
,08-10 11:46:20.813  3850  3850 D AdapterServiceConfig: Adding HealthService
,08-10 11:46:20.817  3823  3823 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 11:46:20.820  3850  3850 D AdapterServiceConfig: Adding PanService
,08-10 11:46:20.820  3850  3850 D AdapterServiceConfig: Adding GattService
,08-10 11:46:20.820  3850  3850 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 11:46:20.832  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 11:46:20.837  3823  3823 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-10 11:46:20.847  3823  3823 I vclib   : onServiceConnected
,08-10 11:46:20.851   871  1724 I ActivityManager: Killing 3369:android.process.acore/u0a5 (adj 15): empty #17
,08-10 11:46:20.912  1870  1870 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 11:46:20.920  1870  1870 D SystemUpdateService: onCreate
,08-10 11:46:20.932  1870  1870 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 11:46:20.941  1870  3863 I SystemUpdateService: active receiver: enabled
,08-10 11:46:20.953  1870  3863 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 11:46:20.963  1870  3863 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-10 11:46:20.963  1870  3863 I SystemUpdateService: now status is 0 (complete)
08-10 11:46:20.963  1870  3863 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-10 11:46:20.963  1870  3863 I SystemUpdateService: file has been verified
08-10 11:46:20.964  1870  3863 I SystemUpdateService: OTA package size = 12249756
,08-10 11:46:20.965  1870  1870 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 11:46:20.966  1870  2355 I iu.UploadsManager: num queued entries: 0
08-10 11:46:20.966  1870  3863 I SystemUpdateService: showing system update notification
,08-10 11:46:20.966  1870  2355 I iu.UploadsManager: num updated entries: 0
,08-10 11:46:20.968  1870  2355 I iu.SyncManager: NEXT; no task
,08-10 11:46:20.977  1870  1870 D SystemUpdateService: onDestroy
,08-10 11:46:20.987  1870  1870 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 11:46:20.989  1870  1870 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 11:46:21.002  3791  3810 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-10 11:46:21.005   871   882 I ActivityManager: Start proc 3865:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-10 11:46:21.023   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b5b175:true
,08-10 11:46:21.039  3865  3865 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-10 11:46:21.042  3865  3865 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 11:46:21.047  3865  3865 D SprintDMHelper: simOperator: 
08-10 11:46:21.048  3865  3865 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 11:46:21.063   871  1680 I ActivityManager: Start proc 3877:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-10 11:46:21.064   871  1680 I ActivityManager: Killing 3532:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-10 11:46:21.242   871   882 I ActivityManager: Start proc 3892:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-10 11:46:21.246  3823  3891 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-10 11:46:21.250   871  1899 I ActivityManager: Killing 3549:com.android.musicfx/u0a18 (adj 15): empty #17
,08-10 11:46:21.311  3892  3892 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-10 11:46:21.369  3892  3892 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-10 11:46:21.369  3892  3892 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 11:46:21.369  3892  3892 I GAv4    :   adb logcat -s GAv4
,08-10 11:46:21.384  3892  3892 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 11:46:21.391  3892  3892 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 11:46:21.420  3892  3909 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 11:46:21.530  3892  3892 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-10 11:46:21.574  3892  3892 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-10 11:46:21.586  3892  3892 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 9376-9383)
,08-10 11:46:21.586  3892  3892 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 11:46:21.596  3892  3892 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8d18dfc}
,08-10 11:46:21.597  3892  3892 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 11:46:21.597  3892  3892 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 11:46:21.605  3892  3892 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 11:46:21.608  3892  3892 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 11:46:21.625  3892  3892 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 11:46:21.638  3892  3892 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 11:46:21.638  3892  3892 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 11:46:21.638  3892  3892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 11:46:21.638  3892  3892 I Adreno  : Build Date                       : 10/20/15
08-10 11:46:21.638  3892  3892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 11:46:21.638  3892  3892 I Adreno  : Local Branch                     : M14
08-10 11:46:21.638  3892  3892 I Adreno  : Remote Branch                    : 
08-10 11:46:21.638  3892  3892 I Adreno  : Remote Branch                    : 
08-10 11:46:21.638  3892  3892 I Adreno  : Reconstruct Branch               : 
,08-10 11:46:21.708  3892  3892 I NSApplication: Starting up...
,08-10 11:46:21.717  3892  3938 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-10 11:46:21.753   871  1725 I ActivityManager: Start proc 3943:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-10 11:46:21.754   871  1725 I ActivityManager: Killing 3311:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-10 11:46:21.838  3943  3943 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-10 11:46:22.027   871  1714 I ActivityManager: Killing 3498:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-10 11:46:24.685   871  1899 D WifiService: setWifiEnabled: true pid=3687, uid=10000
08-10 11:46:24.685   871  1899 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 11:46:24.703   871  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-10 11:46:24.714  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:24.714  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:24.714  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:24.714  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:24.714  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:24.714  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:24.714  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:24.714  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:24.714  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:24.714  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:24.715  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:24.718  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:24.719  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:24.719  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:24.719  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:24.719  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:24.719  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:24.719  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:24.719  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:24.719  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:24.719  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:24.719  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:24.722  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:24.723  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:24.723  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:24.723  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:24.723  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:24.723  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:24.723  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:24.723  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:24.723  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:24.723  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:24.724  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:24.735   871  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-10 11:46:24.736   871  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 11:46:24.737   871  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 11:46:24.739   871  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-10 11:46:24.739   871  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-10 11:46:24.739   871  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-10 11:46:24.739   871  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-10 11:46:24.755   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-10 11:46:24.756   371   869 D CommandListener: Setting iface cfg
08-10 11:46:24.756   871  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 11:46:24.756   871  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
08-10 11:46:24.757   871  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 11:46:24.768   871  1302 E native  : do suspend true
,08-10 11:46:24.776   871  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 11:46:24.782   871  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-10 11:46:24.783   871  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 11:46:26.044   871  1899 I ActivityManager: Killing 3575:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-10 11:46:26.163   871  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 11:46:26.237   871  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.19 rxSuccessRate=4.88 delta 1000 -> 994
,08-10 11:46:26.239   871  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-10 11:46:26.239   871  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 11:46:26.256   871  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-10 11:46:26.290   871  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-10 11:46:26.293  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-10 11:46:26.710  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 11:46:26.747  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 11:46:26.748  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 11:46:26.753   871  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 11:46:26.767   871  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 11:46:26.768   871  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 11:46:26.768   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-10 11:46:26.790   871  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 11:46:26.800   371   869 D CommandListener: Setting iface cfg
,08-10 11:46:26.801   871  1302 D WifiStateMachine: Start Dhcp Watchdog 2
,08-10 11:46:26.812   871  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 11:46:26.844   871  3969 D DhcpClient: Receive thread started
,08-10 11:46:26.930   871  1302 E native  : do suspend false
,08-10 11:46:26.940   871  2103 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 11:46:26.952   871  3969 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172648, domain null
,08-10 11:46:26.952   871  2103 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172648 seconds
,08-10 11:46:26.953   871  2103 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 11:46:26.963   871  3969 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 11:46:26.964   871  2103 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 11:46:26.965   371   869 D CommandListener: Setting iface cfg
,08-10 11:46:26.969   871  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-10 11:46:26.973   871  1302 E native  : do suspend true
,08-10 11:46:26.974   871  2103 D DhcpClient: Scheduling renewal in 86399s
,08-10 11:46:26.987   871  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 11:46:26.988   871  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-10 11:46:26.990   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-10 11:46:26.994   871  1304 D ConnectivityService: Adding iface wlan0 to network 101
,08-10 11:46:26.999   871  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 11:46:27.041   871  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-10 11:46:27.041   871  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-10 11:46:27.045   871  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-10 11:46:27.047   871  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-10 11:46:27.051   871  1304 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-10 11:46:27.072   871  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-10 11:46:27.081   871  1304 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-10 11:46:27.081   871  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-10 11:46:27.081   871  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-10 11:46:27.081   871  1304 D ConnectivityService:    accepting network in place of null
08-10 11:46:27.081   871  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-10 11:46:27.083   871  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 11:46:27.083   871  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 11:46:27.091   871  3968 D NetlinkSocketObserver: NeighborEvent{elapsedMs=174888, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:46:27.158   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 11:46:27.193   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 11:46:27.202   871  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-10 11:46:27.202   871  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 11:46:27.206   871  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-10 11:46:27.208   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-10 11:46:27.222  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:27.223  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:27.223  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:27.223  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:27.223  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:27.223  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:27.223  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:27.223  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:46:27.223  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 11:46:27.223  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:27.223  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:46:27.228  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:27.228  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:27.228  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:27.228  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:27.228  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:27.228  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:27.228  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:27.228  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:46:27.228  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 11:46:27.228  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:27.228  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:46:27.232  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:27.232  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:27.232  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:27.232  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:27.232  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:27.232  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:27.232  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:27.232  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:46:27.232  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 11:46:27.233  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:27.233  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:46:27.244  1870  1870 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 11:46:27.250  1870  1870 D SystemUpdateService: onCreate
,08-10 11:46:27.256  1870  1870 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 11:46:27.275  1870  3978 I SystemUpdateService: active receiver: enabled
,08-10 11:46:27.279  1870  1870 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-10 11:46:27.281  1870  2355 I iu.UploadsManager: num queued entries: 0
,08-10 11:46:27.282  1870  2355 I iu.UploadsManager: num updated entries: 0
,08-10 11:46:27.288  1870  3978 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 11:46:27.292  1870  2355 I iu.SyncManager: NEXT; no task
,08-10 11:46:27.293  1870  3978 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-10 11:46:27.293  1870  3978 I SystemUpdateService: now status is 0 (complete)
,08-10 11:46:27.293  1870  3978 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 11:46:27.294  1870  3978 I SystemUpdateService: file has been verified
,08-10 11:46:27.297  1870  1870 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 11:46:27.298  1870  1870 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 11:46:27.299  1870  3978 I SystemUpdateService: OTA package size = 12249756
,08-10 11:46:27.302  3865  3865 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 11:46:27.309  1870  3980 I MDM     : [214] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-10 11:46:27.309  1870  3980 W BaseAppContext: Using Auth Proxy for data requests.
,08-10 11:46:27.314  3865  3865 D SprintDMHelper: simOperator: 
,08-10 11:46:27.314  3865  3865 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 11:46:27.320  1870  3980 V GoogleAuthProtoRequest: [214] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 11:46:27.323  1870  3978 I SystemUpdateService: showing system update notification
,08-10 11:46:27.338  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:27.344  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:27.397  1870  1870 D SystemUpdateService: onDestroy
,08-10 11:46:27.413  1502  2840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-10 11:46:27.413  1502  2840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-10 11:46:27.413  1502  2840 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 11:46:27.413  1502  2840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:46:27.431  1870  3980 E MDM     : [214] SitrepService.a: Error sending sitrep.
,08-10 11:46:27.442  3823  3983 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-10 11:46:27.593   871  1370 D ConnectivityService: reportNetworkConnectivity(101, true) by 10011
,08-10 11:46:27.612   871  1725 D ConnectivityService: reportNetworkConnectivity(101, true) by 10011
,08-10 11:46:27.614   871  1899 D ConnectivityService: reportNetworkConnectivity(101, true) by 10011
,08-10 11:46:27.616   871  3967 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:812::200e
,08-10 11:46:27.696   871  3967 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 09:46:27 GMT], X-Android-Received-Millis=[1470822387693], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470822387664]}
,08-10 11:46:27.700   871  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 11:46:27.700   871  3967 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
08-10 11:46:27.701   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-10 11:46:27.702   871  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-10 11:46:27.704   871  3967 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:812::200e
08-10 11:46:27.708   871  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-10 11:46:27.739   871  3967 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 09:46:27 GMT], X-Android-Received-Millis=[1470822387739], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470822387711]}
,08-10 11:46:27.741   871  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 11:46:27.742   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-10 11:46:28.201   871  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-10 11:46:29.692   871  1680 D WifiService: setWifiEnabled: false pid=3687, uid=10000
,08-10 11:46:29.693   871  1680 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 11:46:29.733  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-10 11:46:29.741   871  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-10 11:46:29.741   871  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-10 11:46:29.741   871  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 11:46:29.742   871  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 11:46:29.765   871  1302 E native  : do suspend true
,08-10 11:46:29.784   871  2103 D DhcpClient: Clearing IP address
,08-10 11:46:29.785   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-10 11:46:29.803  1502  3987 V NativeCrypto: Read error: ssl=0x99f05e00: I/O error during system call, Connection timed out
,08-10 11:46:29.805   371   869 D CommandListener: Setting iface cfg
,08-10 11:46:29.809   871  3969 D DhcpClient: Receive thread stopped
,08-10 11:46:29.818   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-10 11:46:29.819   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-10 11:46:29.827   394   394 E Parcel  : Reading a NULL string not supported here.
,08-10 11:46:29.827   871  1302 D WifiStateMachine: Start Disconnecting Watchdog 2
08-10 11:46:29.828   871  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-10 11:46:29.833   871  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 11:46:29.833   871  1302 E native  : do suspend true
08-10 11:46:29.838  1502  3987 V NativeCrypto: SSL shutdown failed: ssl=0x99f05e00: I/O error during system call, Broken pipe
,08-10 11:46:29.863   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 11:46:29.897   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 11:46:29.898   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-10 11:46:29.899   871  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-10 11:46:29.899   871  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 11:46:29.907   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-10 11:46:29.910  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:29.910  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:29.910  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:29.910  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:29.910  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:29.910  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:29.910  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:29.910  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:29.910  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:29.910  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:29.911  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:29.912   871  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-10 11:46:29.915  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:29.915  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:29.915  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:29.915  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:29.915  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:29.915  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:29.915  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:29.915  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:29.915  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:29.915  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:29.915  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:29.918  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:29.918  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:29.918  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:29.918  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:29.918  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:29.918  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:29.918  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:29.918  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:29.918  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:29.918  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:29.918  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:29.928  1870  1870 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 11:46:29.933  1870  1870 D SystemUpdateService: onCreate
,08-10 11:46:29.935   871  1302 D WifiConfigStore: Retrieve network priorities after PNO.
08-10 11:46:29.937  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:29.937  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:29.937  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:29.937  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:29.937  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:29.937  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:29.937  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:29.937  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:29.937  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:29.937  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:29.937  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:29.938  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:29.938  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:29.938  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:29.938  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:29.938  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:29.938  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:29.938  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:29.938  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:29.938  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:29.938  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:29.938  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:29.939   871  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 11:46:29.939  1870  1870 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-10 11:46:29.939  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:29.939  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:29.939  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:29.939  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:29.939  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:29.939  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:29.939  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:29.939  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:29.939  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:29.939  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:29.939  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:29.947  1768  2054 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 11:46:29.956  1870  1870 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 11:46:29.961  1870  2355 I iu.UploadsManager: num queued entries: 0
,08-10 11:46:29.961  1870  2355 I iu.UploadsManager: num updated entries: 0
,08-10 11:46:29.963  1870  3999 I SystemUpdateService: active receiver: enabled
,08-10 11:46:29.964  1870  1870 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 11:46:29.966  1870  1870 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 11:46:29.968  3865  3865 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 11:46:29.973  3865  3865 D SprintDMHelper: simOperator: 
,08-10 11:46:29.973  3865  3865 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-10 11:46:29.975  1870  2355 I iu.SyncManager: NEXT; no task
08-10 11:46:29.976  1870  3999 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 11:46:29.978   371   869 E Netd    : netlink response contains error (No such file or directory)
08-10 11:46:29.978   871  1304 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-10 11:46:29.991  3823  4003 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-10 11:46:29.995  1870  3999 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-10 11:46:29.995  1870  3999 I SystemUpdateService: now status is 0 (complete)
,08-10 11:46:29.995  1870  3999 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-10 11:46:29.995  1870  3999 I SystemUpdateService: file has been verified
,08-10 11:46:29.996  1870  3999 I SystemUpdateService: OTA package size = 12249756
,08-10 11:46:30.014  1870  3999 I SystemUpdateService: showing system update notification
,08-10 11:46:30.023  1870  1870 D SystemUpdateService: onDestroy
,08-10 11:46:34.751   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f7ce71e:true
,08-10 11:46:34.752  3850  3850 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 11:46:34.757  3850  3850 I bt_bluedroid: init
,08-10 11:46:34.758  3850  4006 I BluetoothAdapterState: Entering OffState
,08-10 11:46:34.763  3850  4007 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 11:46:34.764  3850  4007 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 11:46:34.764  3850  4007 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 11:46:34.764  3850  4007 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 11:46:34.766  3850  3850 I bt_bluedroid: get_profile_interface socket
08-10 11:46:34.768  3850  3850 I bt_bluedroid: get_profile_interface sdp
,08-10 11:46:34.773  3850  4010 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 11:46:34.774  3850  3861 I bt_bluedroid: config_hci_snoop_log
08-10 11:46:34.776   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-10 11:46:34.777  3850  4010 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 11:46:34.786  3850  4006 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 11:46:34.787  3850  4006 D BluetoothAdapterProperties: Setting state to 14
,08-10 11:46:34.787  3850  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 11:46:34.791  3850  4006 D BluetoothBondStateMachine: make
,08-10 11:46:34.797  3850  4011 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 11:46:34.805  3850  4006 I BluetoothAdapterState: Entering PendingCommandState
,08-10 11:46:34.806  3850  3850 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 11:46:34.815  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:34.817  3850  3850 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 11:46:34.820  3850  3850 D BtGatt.GattService: Received start request. Starting profile...
,08-10 11:46:34.820  3850  3850 D BtGatt.GattService: start()
08-10 11:46:34.821  3850  3850 I bt_bluedroid: get_profile_interface gatt
,08-10 11:46:34.823  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:34.823  3850  3850 D BtGatt.AdvertiseManager: advertise manager created
,08-10 11:46:34.842  3850  3850 V BluetoothAdapterState: isTurningOff()=false
,08-10 11:46:34.843  3850  3850 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:34.843  3850  3850 V BluetoothAdapterState: isBleTurningOn()=true
08-10 11:46:34.843  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:34.844  3850  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-10 11:46:34.845  3850  4006 I bt_bluedroid: enable
08-10 11:46:34.846  3850  4007 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-10 11:46:34.847  3850  4007 I bt_hci  : start_up
,08-10 11:46:34.870  3850  4007 I bt_vendor: alloc value 0xb39a9189
,08-10 11:46:34.870  3850  4007 I bt_vendor: init
08-10 11:46:34.870  3850  4007 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-10 11:46:34.871  3850  4007 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 11:46:34.979  3850  4007 D bt_hci  : start_up starting async portion
,08-10 11:46:34.980  3850  4014 I bt_hci  : event_finish_startup
08-10 11:46:34.981  3850  4014 I bt_hci_h4: hal_open
,08-10 11:46:34.981  3850  4014 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 11:46:34.994  3850  4014 I bt_userial_vendor: device fd = 51 open
,08-10 11:46:35.020  3850  4014 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 11:46:35.052  3850  4014 D bt_hwcfg: Chipset BCM4354A2
,08-10 11:46:35.053  3850  4014 D bt_hwcfg: Target name = [BCM4354A2]
,08-10 11:46:35.054  3850  4014 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 11:46:35.087   871  1304 D ConnectivityService: handlePromptUnvalidated 101
,08-10 11:46:35.716  3850  4014 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 11:46:35.717  3850  4014 D bt_hwcfg: Settlement delay -- 100 ms
,08-10 11:46:35.717  3850  4014 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 11:46:35.834  3850  4014 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 11:46:35.835  3850  4014 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 11:46:35.865  3850  4014 I bt_hwcfg: vendor lib fwcfg completed
08-10 11:46:35.865  3850  4014 I bt_vendor: firmware callback
08-10 11:46:35.865  3850  4014 I bt_hci  : firmware_config_callback
,08-10 11:46:35.876  3850  4016 I bt_btu  : btu_task pending for preload complete event
,08-10 11:46:35.877  3850  4016 I bt_btu_task: Bluetooth chip preload is complete
,08-10 11:46:35.877  3850  4016 I bt_btu  : btu_task received preload complete event
,08-10 11:46:35.887  3850  4016 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 11:46:35.888  3850  4016 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 11:46:35.888  3850  4016 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-10 11:46:35.888  3850  4016 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 11:46:35.889  3850  4016 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-10 11:46:35.889  3850  4016 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 11:46:35.889  3850  4016 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-10 11:46:35.889  3850  4016 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 11:46:35.890  3850  4016 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 11:46:35.890  3850  4016 I         : BTE_InitTraceLevels -- TRC_PAN
,08-10 11:46:35.890  3850  4016 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 11:46:35.890  3850  4016 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 11:46:35.891  3850  4016 I         : BTE_InitTraceLevels -- TRC_SMP
,08-10 11:46:35.891  3850  4016 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 11:46:35.891  3850  4016 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 11:46:36.024  3850  4016 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3926d9d
,08-10 11:46:36.024  3850  4016 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3926d9d 
,08-10 11:46:36.037  3850  4010 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 11:46:36.038  3850  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 11:46:36.039  3850  4010 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 11:46:36.042  3850  4010 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 11:46:36.047  3850  4010 D BluetoothAdapterProperties: Scan Mode:20
,08-10 11:46:36.047  3850  4010 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 11:46:36.051  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:36.047  3850  4010 D bt_hci  : do_postload posting postload work item
,08-10 11:46:36.052  3850  4014 I bt_hci  : event_postload
,08-10 11:46:36.052  3850  4014 I bt_vendor: sco_config_cb
,08-10 11:46:36.052  3850  4014 I bt_hci  : sco_config_callback postload finished.
08-10 11:46:36.055  3850  4010 D bt_bte_conf: Device ID record 1 : primary
08-10 11:46:36.055  3850  4010 D bt_bte_conf:   vendorId            = 000f
08-10 11:46:36.055  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:36.055  3850  4010 D bt_bte_conf:   vendorIdSource      = 0001
08-10 11:46:36.055  3850  4010 D bt_bte_conf:   product             = 1200
,08-10 11:46:36.055  3850  4010 D bt_bte_conf:   version             = 1436
,08-10 11:46:36.055  3850  4010 D bt_bte_conf:   clientExecutableURL = 
08-10 11:46:36.056  3850  4010 D bt_bte_conf:   serviceDescription  = 
,08-10 11:46:36.056  3850  4010 D bt_bte_conf:   documentationURL    = 
08-10 11:46:36.056  3850  4010 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-10 11:46:36.057  3850  4007 D bt_stack_manager: event_start_up_stack finished
08-10 11:46:36.058  3850  4014 I bt_vendor: low_power_mode_cb
,08-10 11:46:36.058  3850  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-10 11:46:36.058  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:36.059  3850  4006 D BluetoothAdapterProperties: Setting state to 15
,08-10 11:46:36.059  3850  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-10 11:46:36.060  3850  4006 I BluetoothAdapterState: Entering BleOnState
,08-10 11:46:36.068  3850  4006 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-10 11:46:36.068  3850  4006 D BluetoothAdapterProperties: Setting state to 11
,08-10 11:46:36.068  3850  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 11:46:36.084  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:36.085  3850  3850 D HeadsetService: Received start request. Starting profile...
,08-10 11:46:36.085  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:36.087  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:36.088  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:36.090  3850  3850 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 11:46:36.090  3850  3850 D HeadsetStateMachine: make
,08-10 11:46:36.096  3850  4006 I BluetoothAdapterState: Entering PendingCommandState
,08-10 11:46:36.098  3850  3850 D HeadsetStateMachine: max_hf_connections = 1
,08-10 11:46:36.098  3850  3850 I bt_bluedroid: get_profile_interface handsfree
,08-10 11:46:36.099  3850  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-10 11:46:36.099  3850  4010 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-10 11:46:36.104  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:36.104  3850  3850 D A2dpService: Received start request. Starting profile...
,08-10 11:46:36.105  3850  3850 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-10 11:46:36.105  3850  3850 I bt_bluedroid: get_profile_interface avrcp
,08-10 11:46:36.111  3850  3850 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 11:46:36.111  3850  3850 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-10 11:46:36.111  3850  3850 D A2dpStateMachine: make
,08-10 11:46:36.112  3850  3850 I bt_bluedroid: get_profile_interface a2dp
,08-10 11:46:36.113  3850  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-10 11:46:36.115  3850  4026 D A2dpStateMachine: Enter Disconnected: -2
,08-10 11:46:36.116  3850  3850 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 11:46:36.117  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
08-10 11:46:36.118  3850  3850 D HidService: Received start request. Starting profile...
08-10 11:46:36.118  3850  3850 I bt_bluedroid: get_profile_interface hidhost
08-10 11:46:36.118  3850  4010 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39083e5
08-10 11:46:36.118  3850  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-10 11:46:36.118  3850  3850 D HidService: setHidService(): set to: null
,08-10 11:46:36.119  3773  3773 D BluetoothInputDevice: Proxy object connected
,08-10 11:46:36.121  3850  3850 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 11:46:36.121  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 11:46:36.121  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
08-10 11:46:36.122  3850  3850 D HealthService: Received start request. Starting profile...
,08-10 11:46:36.122  3773  3773 D HidProfile: Bluetooth service connected
08-10 11:46:36.124  3850  3850 I bt_bluedroid: get_profile_interface health
,08-10 11:46:36.124  3850  3850 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 11:46:36.125  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:36.127  3773  3773 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 11:46:36.127  3850  3850 D PanService: Received start request. Starting profile...
,08-10 11:46:36.127  3773  3773 D PanProfile: Bluetooth service connected
08-10 11:46:36.127  3850  3850 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-10 11:46:36.127  3850  3850 I bt_bluedroid: get_profile_interface pan
,08-10 11:46:36.128  3850  4010 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 11:46:36.131  3850  3850 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:36.132  3850  3850 D BluetoothMapService: Received start request. Starting profile...
,08-10 11:46:36.132  3850  3850 D BluetoothMapService: start()
,08-10 11:46:36.133  3773  3773 D BluetoothMap: Proxy object connected
,08-10 11:46:36.133  3773  3773 D MapProfile: Bluetooth service connected
,08-10 11:46:36.133  3773  3773 D BluetoothMap: getConnectedDevices()
,08-10 11:46:36.134  3850  3850 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 11:46:36.135  3850  3850 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-10 11:46:36.135  3850  3850 D BluetoothMapAppObserver: createReceiver()
,08-10 11:46:36.135  3773  3773 D BluetoothMap: Bluetooth is Not enabled
,08-10 11:46:36.137  3850  3850 D BluetoothMapAppObserver: initObservers()
,08-10 11:46:36.137  3850  3850 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 11:46:36.146  3850  4024 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-10 11:46:36.146  3850  3850 V BluetoothAdapterState: isTurningOff()=false
,08-10 11:46:36.146  3850  3850 V BluetoothAdapterState: isTurningOn()=true
08-10 11:46:36.146  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 11:46:36.146  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:36.148  3850  3850 V BluetoothAdapterState: isTurningOff()=false
,08-10 11:46:36.148  3850  3850 V BluetoothAdapterState: isTurningOn()=true
,08-10 11:46:36.148  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 11:46:36.148  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:36.148  3850  3850 V BluetoothAdapterState: isTurningOff()=false
08-10 11:46:36.148  3850  3850 V BluetoothAdapterState: isTurningOn()=true
08-10 11:46:36.148  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:36.149  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:36.150  3850  3850 V BluetoothAdapterState: isTurningOff()=false
08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isTurningOn()=true
08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isTurningOff()=false
08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isTurningOn()=true
08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isTurningOff()=false
,08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isTurningOn()=true
,08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 11:46:36.151  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:36.152  3850  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-10 11:46:36.152  3850  4006 D BluetoothAdapterProperties: ScanMode =  20
08-10 11:46:36.152  3850  4006 D BluetoothAdapterProperties: State =  11
,08-10 11:46:36.154  3850  4010 D BluetoothAdapterProperties: Scan Mode:21
,08-10 11:46:36.155  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:36.155  3850  4010 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 11:46:36.155  3850  4006 D BluetoothAdapterProperties: Setting state to 12
08-10 11:46:36.156  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:36.156  3850  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 11:46:36.156  3850  4006 I BluetoothAdapterState: Entering OnState
08-10 11:46:36.157  1361  1814 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 11:46:36.159  1361  1378 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 11:46:36.159  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:36.159  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:36.159  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:36.159  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:36.159  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:36.159  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:36.159  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:36.159  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:36.161   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 11:46:36.161  1361  1361 D BluetoothInputDevice: Proxy object connected
08-10 11:46:36.161  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:36.161  1361  1361 D HidProfile: Bluetooth service connected
,08-10 11:46:36.162  3773  3785 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 11:46:36.163  3850  3850 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 11:46:36.164  3850  3850 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-10 11:46:36.164  3773  3784 D BluetoothMap: onBluetoothStateChange: up=true
,08-10 11:46:36.165   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 11:46:36.165  3850  3850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 11:46:36.165  1361  1814 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 11:46:36.167  3850  3850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 11:46:36.168  1711  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 11:46:36.168  3850  3850 D ObexServerSockets: Succeed to create listening sockets 
,08-10 11:46:36.168  3850  3850 D ObexServerSockets0: startAccept()
,08-10 11:46:36.168  3850  3850 D ObexServerSockets0: prepareForNewConnect()
08-10 11:46:36.169  1361  1378 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 11:46:36.169  1361  1373 D BluetoothPan: onBluetoothStateChange on: true
08-10 11:46:36.170  3850  3850 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-10 11:46:36.170  3850  3850 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-10 11:46:36.171   871   871 D BluetoothA2dp: Proxy object connected
08-10 11:46:36.172  1361  1361 D BluetoothA2dp: Proxy object connected
08-10 11:46:36.172  3850  4031 D ObexServerSockets0: Accepting socket connection...
08-10 11:46:36.173   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 11:46:36.173  3773  3785 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 11:46:36.173   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 11:46:36.174  1361  1373 D BluetoothMap: onBluetoothStateChange: up=true
08-10 11:46:36.174  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 11:46:36.174  1361  1361 D PanProfile: Bluetooth service connected
,08-10 11:46:36.175  1361  1361 D BluetoothMap: Proxy object connected
08-10 11:46:36.175  1361  1361 D MapProfile: Bluetooth service connected
08-10 11:46:36.175  1361  1361 D BluetoothMap: getConnectedDevices()
08-10 11:46:36.175  3773  3784 D BluetoothPan: onBluetoothStateChange on: true
,08-10 11:46:36.177  3850  4032 D ObexServerSockets0: Accepting socket connection...
,08-10 11:46:36.179   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-10 11:46:36.179  3850  3850 D BluetoothMapService: onReceive
08-10 11:46:36.179  3850  3850 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-10 11:46:36.179  3850  3850 D BluetoothMapService: STATE_ON
08-10 11:46:36.182  3773  3773 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 11:46:36.182  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:36.182  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:36.182  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:36.182  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:36.182  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:36.182  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:36.182  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:36.182  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:36.184  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:36.187  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:36.187  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:36.187  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:36.187  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:36.187  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:36.187  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:36.187  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:36.187  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:36.189  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:36.190  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:36.191  3773  3773 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-10 11:46:36.199  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 11:46:36.200  3850  3850 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 11:46:36.200  3850  3850 D ObexServerSockets0: prepareForNewConnect()
,08-10 11:46:36.202  3773  3773 D BluetoothA2dp: Proxy object connected
,08-10 11:46:36.206  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 11:46:36.211  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-10 11:46:36.215  1361  1361 D BluetoothPbap: Proxy object connected
08-10 11:46:36.215  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-10 11:46:36.216  3773  3773 D BluetoothPbap: Proxy object connected
08-10 11:46:36.216  3773  3773 D PbapServerProfile: Bluetooth service connected
,08-10 11:46:36.224  3850  4037 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 11:46:36.235  3850  4041 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 11:46:36.236  3850  4041 I BtOppRfcommListener: Accept thread started.
,08-10 11:46:36.268  1711  1722 D BluetoothHeadset: Proxy object connected
,08-10 11:46:36.268   871   871 D BluetoothHeadset: Proxy object connected
08-10 11:46:36.268   871   871 D BluetoothHeadset: Proxy object connected
08-10 11:46:36.268   871   871 D BluetoothHeadset: Proxy object connected
,08-10 11:46:36.268  1361  1814 D BluetoothHeadset: Proxy object connected
08-10 11:46:36.268  1361  1361 D HeadsetProfile: Bluetooth service connected
08-10 11:46:36.269  1711  1723 D BluetoothHeadset: Proxy object connected
,08-10 11:46:36.270  1361  1373 D BluetoothHeadset: Proxy object connected
,08-10 11:46:36.271  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-10 11:46:36.274   871   888 D BluetoothHeadset: Proxy object connected
,08-10 11:46:36.274   871   888 D BluetoothHeadset: Proxy object connected
,08-10 11:46:36.294  3773  3785 D BluetoothHeadset: Proxy object connected
,08-10 11:46:36.295  3773  3773 D HeadsetProfile: Bluetooth service connected
,08-10 11:46:37.018  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:37.034  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:37.041  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:37.115  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 11:46:37.116  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 11:46:37.116  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:46:37.117  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:46:37.179  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 11:46:37.181  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 11:46:37.184  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-10 11:46:39.716  3850  4006 D BluetoothAdapterState: Current state: ON, message: 23
,08-10 11:46:39.716  3850  4006 D BluetoothAdapterProperties: Setting state to 13
,08-10 11:46:39.717  3850  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-10 11:46:39.718  3850  4006 D BluetoothAdapterProperties: onBluetoothDisable()
,08-10 11:46:39.727  3850  4006 I BluetoothAdapterState: Entering PendingCommandState
,08-10 11:46:39.735  3850  3850 D BluetoothMapService: onReceive
,08-10 11:46:39.735  3850  3850 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 11:46:39.736  3850  3850 D BluetoothMapService: STATE_TURNING_OFF
,08-10 11:46:39.736  3850  3850 D BluetoothMapService: MAP Service closeService in
08-10 11:46:39.737  3850  3850 D BluetoothMapMasInstance0: MAP Service shutdown
,08-10 11:46:39.737  3850  3850 D ObexServerSockets0: shutdown(block = true)
,08-10 11:46:39.738  3850  4031 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-10 11:46:39.741  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 11:46:39.741  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:39.741  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:39.741  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:39.741  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:39.741  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:39.741  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:39.741  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:39.741  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:39.742  3850  3850 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 11:46:39.742  3850  4032 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 11:46:39.743  3850  4019 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 11:46:39.743  3850  3850 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-10 11:46:39.743  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:39.744  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:39.744  3850  3850 I BtOppRfcommListener: stopping Accept Thread
08-10 11:46:39.744  3850  4041 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 11:46:39.744  3850  4010 D BluetoothAdapterProperties: Scan Mode:20
08-10 11:46:39.745  3850  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-10 11:46:39.746  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 11:46:39.747  3850  4041 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 11:46:39.751  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:39.752  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:39.752  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:39.752  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:39.752  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:39.752  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:39.752  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:39.752  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:39.752  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:39.754  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:39.754  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:39.755  3850  3850 D HeadsetService: Received stop request...Stopping profile...
,08-10 11:46:39.759  1711  1722 D BluetoothHeadset: Proxy object disconnected
,08-10 11:46:39.760  3850  3850 D A2dpService: Received stop request...Stopping profile...
08-10 11:46:39.760  3773  3784 D BluetoothHeadset: Proxy object disconnected
08-10 11:46:39.760  3850  4026 D A2dpStateMachine: Exit Disconnected: -1
,08-10 11:46:39.760  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:39.761   871   871 D BluetoothHeadset: Proxy object disconnected
08-10 11:46:39.761   871   871 D BluetoothHeadset: Proxy object disconnected
08-10 11:46:39.761  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:39.761  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:39.761  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:39.761  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:39.761  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 11:46:39.761  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:39.761  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:39.761  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:39.761   871   871 D BluetoothHeadset: Proxy object disconnected
08-10 11:46:39.761  1361  1814 D BluetoothHeadset: Proxy object disconnected
08-10 11:46:39.762   871   871 D BluetoothA2dp: Proxy object disconnected
,08-10 11:46:39.762  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-10 11:46:39.762  3687  3687 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 11:46:39.762  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:39.763  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-10 11:46:39.764  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:39.763  3850  3850 V BluetoothAdapterState: isTurningOff()=true
08-10 11:46:39.764  3850  3850 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:39.764  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:39.764  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:39.765  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 11:46:39.765  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:39.766  3850  3850 D HidService: Received stop request...Stopping profile...
08-10 11:46:39.766  3850  3850 D HidService: Stopping Bluetooth HidService
08-10 11:46:39.767  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-10 11:46:39.767  1361  1361 D HidProfile: Bluetooth service disconnected
08-10 11:46:39.768  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:39.768  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-10 11:46:39.769  3773  3773 D HeadsetProfile: Bluetooth service disconnected
,08-10 11:46:39.770  3773  3773 D BluetoothA2dp: Proxy object disconnected
08-10 11:46:39.770  3850  3850 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 11:46:39.770  3773  3773 D BluetoothInputDevice: Proxy object disconnected
08-10 11:46:39.770  3773  3773 D HidProfile: Bluetooth service disconnected
08-10 11:46:39.770  3850  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-10 11:46:39.770  3850  4016 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 11:46:39.771  3850  3850 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 11:46:39.771  3850  4016 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 11:46:39.771  3850  4016 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 11:46:39.771  3850  4010 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-10 11:46:39.771  3850  3850 D HealthService: Received stop request...Stopping profile...
08-10 11:46:39.774  1361  1361 D BluetoothPbap: Proxy object disconnected
08-10 11:46:39.774  1361  1361 D PbapServerProfile: Bluetooth service disconnected
08-10 11:46:39.775  3850  3850 V BluetoothAdapterState: isTurningOff()=true
08-10 11:46:39.775  3850  3850 V BluetoothAdapterState: isTurningOn()=false
,08-10 11:46:39.775  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:39.775  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:39.775  3773  3773 D BluetoothPbap: Proxy object disconnected
08-10 11:46:39.775  3773  3773 D PbapServerProfile: Bluetooth service disconnected
08-10 11:46:39.776  3850  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-10 11:46:39.776  3850  4016 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 11:46:39.776  3850  4016 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 11:46:39.776  3850  4016 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 11:46:39.776  3850  4016 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 11:46:39.776  3850  4016 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 11:46:39.776  3850  4016 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 11:46:39.777  3850  3850 D PanService: Received stop request...Stopping profile...
,08-10 11:46:39.777  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 11:46:39.778  1361  1361 D PanProfile: Bluetooth service disconnected
08-10 11:46:39.778  3773  3773 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 11:46:39.778  3773  3773 D PanProfile: Bluetooth service disconnected
08-10 11:46:39.779  3850  3850 D BluetoothMapService: Received stop request...Stopping profile...
,08-10 11:46:39.779  3850  3850 D BluetoothMapService: stop()
08-10 11:46:39.779  3850  3850 D BluetoothMapAppObserver: deinitObservers()
08-10 11:46:39.779  3850  3850 D BluetoothMapAppObserver: removeReceiver()
08-10 11:46:39.781  1361  1361 D BluetoothMap: Proxy object disconnected
08-10 11:46:39.781  1361  1361 D MapProfile: Bluetooth service disconnected
08-10 11:46:39.781  3773  3773 D BluetoothMap: Proxy object disconnected
08-10 11:46:39.781  3773  3773 D MapProfile: Bluetooth service disconnected
,08-10 11:46:39.782  3850  3850 V BluetoothAdapterState: isTurningOff()=true
08-10 11:46:39.782  3850  3850 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:39.782  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:39.782  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:39.782  3850  3850 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 11:46:39.782  3850  4010 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 11:46:39.782  3850  3850 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 11:46:39.783  3850  3850 V BluetoothAdapterState: isTurningOff()=true
08-10 11:46:39.783  3850  3850 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:39.783  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 11:46:39.783  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:39.783  3850  3850 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 11:46:39.784  3850  4010 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-10 11:46:39.784  3850  3850 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 11:46:39.785  3850  3850 V BluetoothAdapterState: isTurningOff()=true
,08-10 11:46:39.785  3850  3850 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:39.785  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:39.785  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:39.785  3850  3850 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 11:46:39.785  3850  3850 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-10 11:46:39.787  3850  3850 D BluetoothMapService: MAP Service closeService in
08-10 11:46:39.787  3850  3850 V BluetoothAdapterState: isTurningOff()=true
08-10 11:46:39.787  3850  3850 V BluetoothAdapterState: isTurningOn()=false
,08-10 11:46:39.787  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:39.787  3850  3850 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:39.787  3850  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 11:46:39.787  3850  4006 D BluetoothAdapterProperties: Setting state to 15
08-10 11:46:39.787  3850  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-10 11:46:39.788  3850  4006 I BluetoothAdapterState: Entering BleOnState
08-10 11:46:39.788  3850  3850 D BluetoothMapService: cleanup()
08-10 11:46:39.788  3850  3850 D BluetoothMapService: MAP Service closeService in
,08-10 11:46:39.790  1361  1373 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 11:46:39.790  3773  3785 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 11:46:39.791  3773  3784 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 11:46:39.791  1361  1814 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 11:46:39.792   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 11:46:39.792  3773  3785 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 11:46:39.792  3773  3784 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 11:46:39.793   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 11:46:39.793  1361  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 11:46:39.794  1711  1723 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 11:46:39.794  1361  1373 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 11:46:39.795  1361  1814 D BluetoothPan: onBluetoothStateChange on: false
,08-10 11:46:39.795   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 11:46:39.795  3773  3785 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 11:46:39.796   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 11:46:39.796  1361  1378 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 11:46:39.796  3773  3784 D BluetoothPan: onBluetoothStateChange on: false
,08-10 11:46:39.797  3850  4006 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-10 11:46:39.797  3850  4006 D BluetoothAdapterProperties: Setting state to 16
08-10 11:46:39.797  3850  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-10 11:46:39.798  3850  4006 D BluetoothAdapterProperties: onBleDisable
08-10 11:46:39.798  3850  4006 I BluetoothAdapterState: Entering PendingCommandState
08-10 11:46:39.799  3850  4007 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-10 11:46:39.799  3850  4016 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 11:46:39.799  3850  4016 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 11:46:39.800  3850  4010 D BluetoothAdapterProperties: Scan Mode:20
,08-10 11:46:39.802  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:39.803  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 11:46:39.803  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:39.804  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:39.805  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:39.806  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:39.807  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:39.809  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 11:46:39.816  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-10 11:46:40.001  3850  4010 I bt_hci  : shut_down
,08-10 11:46:40.011  3850  4014 I bt_vendor: low_power_mode_cb
,08-10 11:46:40.016  3850  4014 D bt_hwcfg: hw_epilog_process
,08-10 11:46:40.033  3850  4014 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-10 11:46:40.034  3850  4014 I bt_vendor: epilog_cb
08-10 11:46:40.034  3850  4014 I bt_hci  : epilog_finished_callback
,08-10 11:46:40.042  3850  4010 I bt_hci_h4: hal_close
,08-10 11:46:40.044  3850  4010 I bt_userial_vendor: device fd = 51 close
,08-10 11:46:40.166  3850  4007 D bt_stack_manager: event_shut_down_stack finished.
,08-10 11:46:40.167  3850  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 11:46:40.174  3850  4006 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-10 11:46:40.175  3850  3850 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 11:46:40.176  3850  3850 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 11:46:40.176  3850  3850 D BtGatt.GattService: stop()
,08-10 11:46:40.177  3850  3850 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 11:46:40.184  3850  3850 V BluetoothAdapterState: isTurningOff()=false
,08-10 11:46:40.184  3850  3850 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:40.185  3850  3850 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:40.185  3850  3850 V BluetoothAdapterState: isBleTurningOff()=true
,08-10 11:46:40.186  3850  4006 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-10 11:46:40.187  3850  4006 D BluetoothAdapterProperties: Setting state to 10
,08-10 11:46:40.188  3850  4006 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-10 11:46:40.190  3850  4006 I BluetoothAdapterState: Entering OffState
08-10 11:46:40.191   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-10 11:46:40.219  3850  3850 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-10 11:46:40.220  3850  3850 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-10 11:46:40.220  3850  4007 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-10 11:46:40.228  3850  4007 D bt_stack_manager: event_clean_up_stack finished.
,08-10 11:46:40.229  3850  3850 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-10 11:46:40.235  3850  3850 I art     : System.exit called, status: 0
,08-10 11:46:40.235  3850  3850 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 11:46:40.302   871  1680 I ActivityManager: Process com.android.bluetooth (pid 3850) has died
,08-10 11:46:44.713  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 11:46:44.714  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:49.719  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:49.720  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@60e8866 removed from the list
08-10 11:46:49.720  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:49.721  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:49.721  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:49.725  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:46:49.725  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a6b6454 added. We now have 4 listener(s)
08-10 11:46:49.726  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 11:46:49.728  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:46:49.729  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a6b6454 removed from the list
08-10 11:46:49.729  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:49.729  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:49.730  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:46:49.732  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:46:49.732  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5437ffd added. We now have 4 listener(s)
08-10 11:46:49.733  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 11:46:49.734  3687  3738 I System.out: IsBluetoothEnabled
08-10 11:46:49.744  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:49.773   871   888 I ActivityManager: Start proc 4052:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 11:46:49.918  4052  4052 D AdapterServiceConfig: Adding HeadsetService
08-10 11:46:49.918  4052  4052 D AdapterServiceConfig: Adding A2dpService
08-10 11:46:49.918  4052  4052 D AdapterServiceConfig: Adding HidService
08-10 11:46:49.919  4052  4052 D AdapterServiceConfig: Adding HealthService
08-10 11:46:49.919  4052  4052 D AdapterServiceConfig: Adding PanService
,08-10 11:46:49.919  4052  4052 D AdapterServiceConfig: Adding GattService
08-10 11:46:49.919  4052  4052 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 11:46:49.932   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d768d:true
,08-10 11:46:49.932  4052  4052 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 11:46:49.935  4052  4052 I bt_bluedroid: init
08-10 11:46:49.935  4052  4064 I BluetoothAdapterState: Entering OffState
,08-10 11:46:49.938  4052  4065 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-10 11:46:49.938  4052  4065 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-10 11:46:49.938  4052  4065 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 11:46:49.938  4052  4065 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 11:46:49.939  4052  4052 I bt_bluedroid: get_profile_interface socket
,08-10 11:46:49.940  4052  4052 I bt_bluedroid: get_profile_interface sdp
,08-10 11:46:49.942  4052  4068 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 11:46:49.944  4052  4068 D BluetoothAdapterProperties: Name is: Nexus 6
08-10 11:46:49.944  4052  4063 I bt_bluedroid: config_hci_snoop_log
,08-10 11:46:49.945   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-10 11:46:49.950  4052  4064 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 11:46:49.950  4052  4064 D BluetoothAdapterProperties: Setting state to 14
08-10 11:46:49.950  4052  4064 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 11:46:49.952  4052  4064 D BluetoothBondStateMachine: make
,08-10 11:46:49.954  4052  4069 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 11:46:49.957  4052  4064 I BluetoothAdapterState: Entering PendingCommandState
,08-10 11:46:49.958  4052  4052 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 11:46:49.960  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:49.961  4052  4052 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 11:46:49.961  4052  4052 D BtGatt.GattService: Received start request. Starting profile...
08-10 11:46:49.961  4052  4052 D BtGatt.GattService: start()
08-10 11:46:49.962  4052  4052 I bt_bluedroid: get_profile_interface gatt
08-10 11:46:49.962  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
08-10 11:46:49.962  4052  4052 D BtGatt.AdvertiseManager: advertise manager created
,08-10 11:46:49.967  4052  4052 V BluetoothAdapterState: isTurningOff()=false
08-10 11:46:49.967  4052  4052 V BluetoothAdapterState: isTurningOn()=false
08-10 11:46:49.967  4052  4052 V BluetoothAdapterState: isBleTurningOn()=true
08-10 11:46:49.967  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:49.968  4052  4064 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-10 11:46:49.970  4052  4064 I bt_bluedroid: enable
,08-10 11:46:49.970  4052  4065 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-10 11:46:49.971  4052  4065 I bt_hci  : start_up
08-10 11:46:49.976  4052  4065 I bt_vendor: alloc value 0xb3a06189
08-10 11:46:49.976  4052  4065 I bt_vendor: init
,08-10 11:46:49.976  4052  4065 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-10 11:46:49.976  4052  4065 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 11:46:50.086  4052  4065 D bt_hci  : start_up starting async portion
,08-10 11:46:50.087  4052  4072 I bt_hci  : event_finish_startup
08-10 11:46:50.087  4052  4072 I bt_hci_h4: hal_open
,08-10 11:46:50.087  4052  4072 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 11:46:50.098  4052  4072 I bt_userial_vendor: device fd = 51 open
,08-10 11:46:50.129  4052  4072 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 11:46:50.161  4052  4072 D bt_hwcfg: Chipset BCM4354A2
,08-10 11:46:50.161  4052  4072 D bt_hwcfg: Target name = [BCM4354A2]
08-10 11:46:50.162  4052  4072 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 11:46:50.962  4052  4072 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 11:46:50.964  4052  4072 D bt_hwcfg: Settlement delay -- 100 ms
08-10 11:46:50.964  4052  4072 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 11:46:51.081  4052  4072 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 11:46:51.082  4052  4072 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 11:46:51.111  4052  4072 I bt_hwcfg: vendor lib fwcfg completed
,08-10 11:46:51.112  4052  4072 I bt_vendor: firmware callback
,08-10 11:46:51.112  4052  4072 I bt_hci  : firmware_config_callback
,08-10 11:46:51.123  4052  4076 I bt_btu  : btu_task pending for preload complete event
,08-10 11:46:51.124  4052  4076 I bt_btu_task: Bluetooth chip preload is complete
,08-10 11:46:51.124  4052  4076 I bt_btu  : btu_task received preload complete event
,08-10 11:46:51.137  4052  4076 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 11:46:51.137  4052  4076 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 11:46:51.137  4052  4076 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-10 11:46:51.138  4052  4076 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 11:46:51.138  4052  4076 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-10 11:46:51.138  4052  4076 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 11:46:51.138  4052  4076 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-10 11:46:51.140  4052  4076 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 11:46:51.140  4052  4076 I         : BTE_InitTraceLevels -- TRC_GAP
,08-10 11:46:51.141  4052  4076 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 11:46:51.142  4052  4076 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 11:46:51.143  4052  4076 I         : BTE_InitTraceLevels -- TRC_GATT
,08-10 11:46:51.143  4052  4076 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 11:46:51.143  4052  4076 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 11:46:51.144  4052  4076 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 11:46:51.277  4052  4076 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3983d9d,
08-10 11:46:51.278  4052  4076 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3983d9d 
,08-10 11:46:51.288  4052  4068 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 11:46:51.289  4052  4068 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 11:46:51.291  4052  4068 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 11:46:51.297  4052  4068 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 11:46:51.301  4052  4068 D BluetoothAdapterProperties: Scan Mode:20
,08-10 11:46:51.301  4052  4068 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 11:46:51.302  4052  4068 D bt_hci  : do_postload posting postload work item
,08-10 11:46:51.302  4052  4072 I bt_hci  : event_postload
,08-10 11:46:51.302  4052  4072 I bt_vendor: sco_config_cb
08-10 11:46:51.302  4052  4072 I bt_hci  : sco_config_callback postload finished.
08-10 11:46:51.306  4052  4068 D bt_bte_conf: Device ID record 1 : primary
08-10 11:46:51.306  4052  4068 D bt_bte_conf:   vendorId            = 000f
08-10 11:46:51.307  4052  4068 D bt_bte_conf:   vendorIdSource      = 0001
08-10 11:46:51.307  4052  4068 D bt_bte_conf:   product             = 1200
,08-10 11:46:51.307  4052  4068 D bt_bte_conf:   version             = 1436
08-10 11:46:51.307  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:51.307  4052  4068 D bt_bte_conf:   clientExecutableURL = 
08-10 11:46:51.308  4052  4068 D bt_bte_conf:   serviceDescription  = 
08-10 11:46:51.308  4052  4068 D bt_bte_conf:   documentationURL    = 
08-10 11:46:51.308  4052  4072 I bt_vendor: low_power_mode_cb
08-10 11:46:51.309  4052  4068 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-10 11:46:51.309  4052  4065 D bt_stack_manager: event_start_up_stack finished
08-10 11:46:51.310  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:51.312  4052  4064 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-10 11:46:51.314  4052  4064 D BluetoothAdapterProperties: Setting state to 15
,08-10 11:46:51.315  4052  4064 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-10 11:46:51.317  4052  4064 I BluetoothAdapterState: Entering BleOnState
,08-10 11:46:51.321  4052  4064 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-10 11:46:51.321  4052  4064 D BluetoothAdapterProperties: Setting state to 11
,08-10 11:46:51.321  4052  4064 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 11:46:51.331  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:51.334  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:46:51.340  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:51.341  4052  4052 D HeadsetService: Received start request. Starting profile...
,08-10 11:46:51.344  4052  4052 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-10 11:46:51.344  4052  4052 D HeadsetStateMachine: make
,08-10 11:46:51.352  4052  4064 I BluetoothAdapterState: Entering PendingCommandState
,08-10 11:46:51.355  4052  4052 D HeadsetStateMachine: max_hf_connections = 1
,08-10 11:46:51.355  4052  4052 I bt_bluedroid: get_profile_interface handsfree
,08-10 11:46:51.355  4052  4068 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-10 11:46:51.356  4052  4068 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-10 11:46:51.360  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:51.360  4052  4052 D A2dpService: Received start request. Starting profile...
,08-10 11:46:51.361  4052  4052 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 11:46:51.362  4052  4052 I bt_bluedroid: get_profile_interface avrcp
,08-10 11:46:51.368  4052  4052 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 11:46:51.369  4052  4052 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 11:46:51.369  4052  4052 D A2dpStateMachine: make
,08-10 11:46:51.370  4052  4052 I bt_bluedroid: get_profile_interface a2dp
,08-10 11:46:51.371  4052  4068 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-10 11:46:51.372  4052  4084 D A2dpStateMachine: Enter Disconnected: -2
,08-10 11:46:51.374  4052  4052 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 11:46:51.375  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:51.376  4052  4052 D HidService: Received start request. Starting profile...
08-10 11:46:51.376  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 11:46:51.376  4052  4052 I bt_bluedroid: get_profile_interface hidhost
08-10 11:46:51.376  4052  4052 D HidService: setHidService(): set to: null
08-10 11:46:51.377  4052  4068 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39653e5
,08-10 11:46:51.377  4052  4068 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-10 11:46:51.377  4052  4052 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 11:46:51.378  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
08-10 11:46:51.379  4052  4052 D HealthService: Received start request. Starting profile...
,08-10 11:46:51.381  4052  4052 I bt_bluedroid: get_profile_interface health
,08-10 11:46:51.382  4052  4052 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 11:46:51.382  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:51.383  4052  4052 D PanService: Received start request. Starting profile...
,08-10 11:46:51.383  4052  4052 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-10 11:46:51.383  4052  4052 I bt_bluedroid: get_profile_interface pan
08-10 11:46:51.384  4052  4068 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 11:46:51.386  4052  4052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:46:51.389  4052  4052 D BluetoothMapService: Received start request. Starting profile...
,08-10 11:46:51.389  4052  4052 D BluetoothMapService: start()
,08-10 11:46:51.391  4052  4052 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-10 11:46:51.392  4052  4052 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-10 11:46:51.392  4052  4052 D BluetoothMapAppObserver: createReceiver()
08-10 11:46:51.393  4052  4052 D BluetoothMapAppObserver: initObservers()
08-10 11:46:51.393  4052  4052 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 11:46:51.401  4052  4082 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-10 11:46:51.401  4052  4052 V BluetoothAdapterState: isTurningOff()=false
08-10 11:46:51.401  4052  4052 V BluetoothAdapterState: isTurningOn()=true
08-10 11:46:51.401  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 11:46:51.401  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:51.402  4052  4052 V BluetoothAdapterState: isTurningOff()=false
08-10 11:46:51.402  4052  4052 V BluetoothAdapterState: isTurningOn()=true
,08-10 11:46:51.403  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:51.403  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:51.403  4052  4052 V BluetoothAdapterState: isTurningOff()=false
,08-10 11:46:51.403  4052  4052 V BluetoothAdapterState: isTurningOn()=true
08-10 11:46:51.403  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:51.403  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:51.405  4052  4052 V BluetoothAdapterState: isTurningOff()=false
,08-10 11:46:51.405  4052  4052 V BluetoothAdapterState: isTurningOn()=true
08-10 11:46:51.405  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 11:46:51.405  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:51.405  4052  4052 V BluetoothAdapterState: isTurningOff()=false
08-10 11:46:51.406  4052  4052 V BluetoothAdapterState: isTurningOn()=true
,08-10 11:46:51.406  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:51.406  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 11:46:51.406  4052  4052 V BluetoothAdapterState: isTurningOff()=false
08-10 11:46:51.406  4052  4052 V BluetoothAdapterState: isTurningOn()=true
08-10 11:46:51.406  4052  4052 V BluetoothAdapterState: isBleTurningOn()=false
08-10 11:46:51.406  4052  4052 V BluetoothAdapterState: isBleTurningOff()=false
08-10 11:46:51.406  4052  4064 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-10 11:46:51.406  4052  4064 D BluetoothAdapterProperties: ScanMode =  20
08-10 11:46:51.406  4052  4064 D BluetoothAdapterProperties: State =  11
08-10 11:46:51.407  4052  4064 D BluetoothAdapterProperties: Setting state to 12
08-10 11:46:51.407  4052  4064 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 11:46:51.408  1361  1814 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 11:46:51.408  4052  4064 I BluetoothAdapterState: Entering OnState
08-10 11:46:51.410  4052  4068 D BluetoothAdapterProperties: Scan Mode:21
08-10 11:46:51.410  3773  3784 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 11:46:51.410  4052  4068 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 11:46:51.412  3773  3785 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 11:46:51.412  1361  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 11:46:51.413  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:51.413  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:51.413  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:51.413  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:51.413  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:51.413  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:51.413  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:51.413  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:51.415   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 11:46:51.415  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:51.416  1361  1361 D BluetoothInputDevice: Proxy object connected
08-10 11:46:51.416  1361  1361 D HidProfile: Bluetooth service connected
,08-10 11:46:51.418   871   871 D BluetoothA2dp: Proxy object connected
,08-10 11:46:51.418  3773  3785 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 11:46:51.419  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:51.419  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:51.419  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:51.419  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:51.419  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:51.419  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:51.419  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:51.419  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 11:46:51.419  4052  4052 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 11:46:51.420  4052  4052 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-10 11:46:51.420  3773  3784 D BluetoothMap: onBluetoothStateChange: up=true
08-10 11:46:51.421  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:51.421  4052  4052 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 11:46:51.421  3773  3773 D BluetoothA2dp: Proxy object connected
08-10 11:46:51.422   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 11:46:51.422  1361  1814 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 11:46:51.423  4052  4052 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 11:46:51.424  1361  1361 D BluetoothA2dp: Proxy object connected
08-10 11:46:51.424  4052  4052 D ObexServerSockets: Succeed to create listening sockets 
08-10 11:46:51.424  4052  4052 D ObexServerSockets0: startAccept()
08-10 11:46:51.424  1711  1865 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 11:46:51.424  4052  4052 D ObexServerSockets0: prepareForNewConnect()
08-10 11:46:51.425  1361  1378 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 11:46:51.425  1361  1373 D BluetoothPan: onBluetoothStateChange on: true
08-10 11:46:51.426  4052  4052 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-10 11:46:51.426  4052  4052 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-10 11:46:51.427   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 11:46:51.427  4052  4091 D ObexServerSockets0: Accepting socket connection...
,08-10 11:46:51.427  4052  4092 D ObexServerSockets0: Accepting socket connection...
08-10 11:46:51.427  3773  3785 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 11:46:51.428  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 11:46:51.428  1361  1361 D PanProfile: Bluetooth service connected
,08-10 11:46:51.429   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 11:46:51.430  1361  1378 D BluetoothMap: onBluetoothStateChange: up=true,
,08-10 11:46:51.431  1361  1361 D BluetoothMap: Proxy object connected
,08-10 11:46:51.431  1361  1361 D MapProfile: Bluetooth service connected
08-10 11:46:51.431  1361  1361 D BluetoothMap: getConnectedDevices(),
08-10 11:46:51.431  3773  3784 D BluetoothPan: onBluetoothStateChange on: true
,08-10 11:46:51.435   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-10 11:46:51.435  4052  4052 D BluetoothMapService: onReceive
,08-10 11:46:51.435  4052  4052 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 11:46:51.435  4052  4052 D BluetoothMapService: STATE_ON
,08-10 11:46:51.437  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:51.438  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:51.439  3773  3773 D BluetoothMap: Proxy object connected
,08-10 11:46:51.439  3773  3773 D MapProfile: Bluetooth service connected
08-10 11:46:51.439  3773  3773 D BluetoothMap: getConnectedDevices(),
08-10 11:46:51.440  3773  3773 D BluetoothInputDevice: Proxy object connected
,08-10 11:46:51.440  3773  3773 D HidProfile: Bluetooth service connected
08-10 11:46:51.442  3773  3773 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 11:46:51.442  3773  3773 D PanProfile: Bluetooth service connected
08-10 11:46:51.446  3773  3773 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
,08-10 11:46:51.451  1502  1502 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 11:46:51.455  3773  3773 D DockEventReceiver: finishStartingService: stopping service
,08-10 11:46:51.461  1361  1361 D BluetoothPbap: Proxy object connected
,08-10 11:46:51.461  3773  3773 D BluetoothPbap: Proxy object connected
08-10 11:46:51.461  1361  1361 D PbapServerProfile: Bluetooth service connected
08-10 11:46:51.461  3773  3773 D PbapServerProfile: Bluetooth service connected
,08-10 11:46:51.466  4052  4052 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 11:46:51.466  4052  4052 D ObexServerSockets0: prepareForNewConnect()
,08-10 11:46:51.470  4052  4097 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 11:46:51.484  4052  4101 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 11:46:51.485  4052  4101 I BtOppRfcommListener: Accept thread started.
,08-10 11:46:51.514  1711  1722 D BluetoothHeadset: Proxy object connected
,08-10 11:46:51.515  3773  4093 D BluetoothHeadset: Proxy object connected
08-10 11:46:51.515  3773  3773 D HeadsetProfile: Bluetooth service connected
08-10 11:46:51.515   871   871 D BluetoothHeadset: Proxy object connected
,08-10 11:46:51.515   871   871 D BluetoothHeadset: Proxy object connected
08-10 11:46:51.515   871   871 D BluetoothHeadset: Proxy object connected
08-10 11:46:51.516  1361  1814 D BluetoothHeadset: Proxy object connected
,08-10 11:46:51.516  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-10 11:46:51.522   871   888 D BluetoothHeadset: Proxy object connected
,08-10 11:46:51.525  1711  1723 D BluetoothHeadset: Proxy object connected
,08-10 11:46:51.526  1361  1373 D BluetoothHeadset: Proxy object connected
,08-10 11:46:51.526  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-10 11:46:51.527   871   888 D BluetoothHeadset: Proxy object connected,
,08-10 11:46:51.530   871   888 D BluetoothHeadset: Proxy object connected
,08-10 11:46:51.761  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:51.761  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:51.761  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:51.761  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 11:46:51.761  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:51.761  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:51.761  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:51.761  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:51.768  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:51.768  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:51.769  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5437ffd removed from the list
,08-10 11:46:51.769  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:46:51.769  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:46:51.770  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:51.772  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 11:46:51.773  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@96ac4f2 added. We now have 4 listener(s)
08-10 11:46:51.773  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 11:46:51.779   871  1725 D WifiService: setWifiEnabled: false pid=3687, uid=10000
,08-10 11:46:51.780   871  1725 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 11:46:51.792  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:46:51.793   871  1899 D WifiService: setWifiEnabled: true pid=3687, uid=10000
08-10 11:46:51.793   871  1899 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 11:46:51.805   871  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-10 11:46:51.818  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:51.818  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:51.818  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:51.818  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:51.818  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:51.818  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:51.818  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:51.818  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:51.823  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:51.823  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:51.823  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:51.823  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:51.823  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:51.823  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:51.823  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:51.823  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:51.826  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:51.827  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:46:51.827  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@96ac4f2 removed from the list
,08-10 11:46:51.827  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 11:46:51.827  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:46:51.827  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:46:51.830  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 11:46:51.831  3687  4105 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-10 11:46:51.832  3687  4105 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-10 11:46:51.834   871  1302 D WifiConfigStore: loaded 0 passpoint configs
08-10 11:46:51.834  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:51.834  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:51.834  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:51.834  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:51.834  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:51.834  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 11:46:51.834  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 11:46:51.834  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 11:46:51.836   871  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-10 11:46:51.836  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 11:46:51.837   871  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-10 11:46:51.839   871  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-10 11:46:51.839   871  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-10 11:46:51.839   871  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-10 11:46:51.839   871  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-10 11:46:51.855   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-10 11:46:51.855   871  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-10 11:46:51.861   371   869 D CommandListener: Setting iface cfg
,08-10 11:46:51.906   871  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
08-10 11:46:51.906   871  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 11:46:51.910   871  1302 E native  : do suspend true
,08-10 11:46:51.923   871  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 11:46:51.933   871  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 11:46:51.935   871  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 11:46:53.336   871  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 11:46:53.473   871  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.06 rxSuccessRate=6.38 delta 1000 -> 994
,08-10 11:46:53.476   871  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-10 11:46:53.476   871  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 11:46:53.497   871  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-10 11:46:53.574   871  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-10 11:46:53.576  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-10 11:46:54.019  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 11:46:54.066  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 11:46:54.069  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 11:46:54.073   871  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 11:46:54.087   871  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 11:46:54.087   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-10 11:46:54.087   871  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 11:46:54.110   871  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 11:46:54.131   371   869 D CommandListener: Setting iface cfg
,08-10 11:46:54.132   871  1302 D WifiStateMachine: Start Dhcp Watchdog 3
,08-10 11:46:54.149   871  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 11:46:54.163   871  4110 D DhcpClient: Receive thread started
,08-10 11:46:54.249   871  1302 E native  : do suspend false
,08-10 11:46:54.271   871  2103 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 11:46:54.285   871  4110 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172773, domain null
,08-10 11:46:54.287   871  2103 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172773 seconds
,08-10 11:46:54.290   871  2103 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 11:46:54.303   871  4110 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 11:46:54.304   871  2103 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 11:46:54.309   371   869 D CommandListener: Setting iface cfg
,08-10 11:46:54.321   871  2103 D DhcpClient: Scheduling renewal in 86399s
,08-10 11:46:54.321   871  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-10 11:46:54.324   871  1302 E native  : do suspend true
,08-10 11:46:54.350   871  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 11:46:54.353   871  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-10 11:46:54.355   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-10 11:46:54.359   871  1304 D ConnectivityService: Adding iface wlan0 to network 102
,08-10 11:46:54.373   871  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 11:46:54.426   871  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-10 11:46:54.426   871  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-10 11:46:54.430   871  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-10 11:46:54.433   871  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-10 11:46:54.434   871  1304 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-10 11:46:54.445   871  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-10 11:46:54.451   871  1304 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-10 11:46:54.451   871  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-10 11:46:54.451   871  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-10 11:46:54.451   871  1304 D ConnectivityService:    accepting network in place of null
08-10 11:46:54.452   871  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-10 11:46:54.452   871  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-10 11:46:54.453   871  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 11:46:54.500   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=202296, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 11:46:54.500   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 11:46:54.548   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 11:46:54.557   871  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-10 11:46:54.558   871  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 11:46:54.561   871  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-10 11:46:54.567   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-10 11:46:54.571   871  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.210.14,2a00:1450:4001:812::200e
,08-10 11:46:54.585  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:54.585  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:54.585  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:54.585  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:54.585  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:54.585  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:54.585  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:46:54.585  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:46:54.588  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:46:54.594  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 11:46:54.594  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:46:54.594  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:46:54.594  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:46:54.594  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:46:54.594  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:46:54.594  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:46:54.594  3687  3687 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:46:54.596  3687  3687 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:46:54.600  1870  1870 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 11:46:54.606  1870  1870 D SystemUpdateService: onCreate
,08-10 11:46:54.609  1870  1870 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 11:46:54.625  1870  4119 I SystemUpdateService: active receiver: enabled
,08-10 11:46:54.630  1870  1870 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-10 11:46:54.631  1870  2355 I iu.UploadsManager: num queued entries: 0
08-10 11:46:54.631  1870  2355 I iu.UploadsManager: num updated entries: 0
,08-10 11:46:54.637  1870  4119 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 11:46:54.638  1870  1870 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 11:46:54.640  1870  1870 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 11:46:54.644  3865  3865 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 11:46:54.645   871  4108 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 09:46:54 GMT], X-Android-Received-Millis=[1470822414644], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470822414616]}
,08-10 11:46:54.647   871  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 11:46:54.648   871  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-10 11:46:54.648   871  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-10 11:46:54.650  1870  4121 I MDM     : [219] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-10 11:46:54.651   871  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-10 11:46:54.654  1870  4121 W BaseAppContext: Using Auth Proxy for data requests.
,08-10 11:46:54.654  3865  3865 D SprintDMHelper: simOperator: 
,08-10 11:46:54.654  3865  3865 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-10 11:46:54.655  1870  4121 V GoogleAuthProtoRequest: [219] a.<init>: mAccountName set to: thalitester@gmail.com
08-10 11:46:54.657  1870  2355 I iu.SyncManager: NEXT; no task
,08-10 11:46:54.657  1870  4119 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-10 11:46:54.657  1870  4119 I SystemUpdateService: now status is 0 (complete)
08-10 11:46:54.657  1870  4119 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 11:46:54.657  1870  4119 I SystemUpdateService: file has been verified
,08-10 11:46:54.657  1870  4119 I SystemUpdateService: OTA package size = 12249756
,08-10 11:46:54.679  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:54.704  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:46:54.710  1870  4119 I SystemUpdateService: showing system update notification
,08-10 11:46:54.741  1870  1870 D SystemUpdateService: onDestroy
,08-10 11:46:54.760  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-10 11:46:54.760  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-10 11:46:54.760  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:46:54.760  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:46:54.782  1870  4121 E MDM     : [219] SitrepService.a: Error sending sitrep.
,08-10 11:46:54.813  3823  4125 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-10 11:46:54.832  3687  4131 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-10 11:46:54.833  3687  4131 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-10 11:46:54.833  3687  4105 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-10 11:46:54.833  3687  4105 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-10 11:46:54.833  3687  4105 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 11:46:54.833  3687  4105 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 11:46:54.833  3687  4105 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-10 11:46:54.833  3687  4131 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-10 11:46:54.834  3687  4131 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 11:46:54.835  3687  4134 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: OutgoingSocketThread/Receiver)
08-10 11:46:54.835  3687  4134 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: OutgoingSocketThread/Receiver)
08-10 11:46:54.835  3687  4134 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-10 11:46:54.835  3687  4134 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-10 11:46:54.837  3687  4131 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-10 11:46:54.837  3687  4133 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: OutgoingSocketThread/Sender)
,08-10 11:46:54.837  3687  4135 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: IncomingSocketThread/Sender)
08-10 11:46:54.838  3687  4136 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: IncomingSocketThread/Receiver)
,08-10 11:46:54.838  3687  4136 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: IncomingSocketThread/Receiver)
08-10 11:46:54.838  3687  4136 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-10 11:46:54.838  3687  4136 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-10 11:46:55.555   871  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-10 11:46:57.840  3687  3738 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-10 11:46:57.842  3687  3738 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-10 11:46:57.848  3687  3738 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9c4f85e Bundle[{}]
,08-10 11:46:57.848  3687  3738 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 11:46:57.849  3687  3738 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-10 11:46:57.849  3687  3738 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-10 11:46:57.850  3687  3738 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-10 11:46:57.850  3687  3738 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-10 11:46:57.851  3687  3738 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 11:46:57.855  3687  3738 I System.out: Running OutgoingSocketThread
,08-10 11:46:57.858  3687  4137 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-10 11:46:57.859  3687  4137 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-10 11:47:00.868  3687  4138 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-10 11:47:00.868  3687  4138 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-10 11:47:00.868  3687  4137 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-10 11:47:00.869  3687  4138 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-10 11:47:00.869  3687  4137 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-10 11:47:00.869  3687  4137 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 11:47:00.870  3687  4138 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-10 11:47:00.870  3687  4137 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-10 11:47:00.872  3687  4138 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-10 11:47:00.873  3687  4137 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-10 11:47:00.880  3687  4140 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: IncomingSocketThread/Sender)
,08-10 11:47:00.881  3687  4141 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: OutgoingSocketThread/Sender)
,08-10 11:47:00.884  3687  4142 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: IncomingSocketThread/Receiver)
,08-10 11:47:00.887  3687  4142 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: IncomingSocketThread/Receiver)
,08-10 11:47:00.887  3687  4142 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-10 11:47:00.887  3687  4142 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-10 11:47:00.888  3687  4143 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: OutgoingSocketThread/Receiver)
08-10 11:47:00.889  3687  4143 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 443, thread name: OutgoingSocketThread/Receiver)
,08-10 11:47:00.890  3687  4143 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-10 11:47:00.890  3687  4143 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 443, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-10 11:47:02.301  1648  1767 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-10 11:47:02.302  1648  1767 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-10 11:47:02.333  1502  1502 I ConfigService: onCreate
,08-10 11:47:02.457   871  1304 D ConnectivityService: handlePromptUnvalidated 102
,08-10 11:47:03.871  3687  3738 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 452)
,08-10 11:47:03.873  3687  3738 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-10 11:47:03.873  3687  3738 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 453)
,08-10 11:47:03.879  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 11:47:03.880  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa3c743 added. We now have 3 listener(s)
,08-10 11:47:03.881  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 11:47:03.881  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 11:47:03.882  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 11:47:03.882  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:47:03.882  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4471c0 added. We now have 4 listener(s)
08-10 11:47:03.882  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 11:47:03.882  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 11:47:03.888  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 11:47:03.902  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:47:03.902  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:47:03.902  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:47:03.902  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:47:03.902  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:47:03.902  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:47:03.902  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:47:03.902  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:47:03.907  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:47:03.907  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 11:47:03.908  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:47:03.908  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:47:03.908  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:47:03.908  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 11:47:03.908  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:03.908  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 11:47:03.908  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 11:47:03.908  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa3c743 removed from the list
08-10 11:47:03.908  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:03.908  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4471c0 removed from the list
,08-10 11:47:03.915  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:47:03.925  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:47:03.925  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:47:03.926  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:47:03.928  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:03.929  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:47:03.933  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 11:47:03.934  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:47:03.934  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:03.934  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4471c0 not in the list
,08-10 11:47:03.935  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:03.935  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:47:03.939  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:47:03.939  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:47:03.939  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 11:47:03.939  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4471c0 not in the list
08-10 11:47:03.940  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 11:47:03.940  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:03.941  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:03.941  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa3c743 not in the list
08-10 11:47:03.943  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 11:47:03.944  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dc3e3e added. We now have 3 listener(s)
,08-10 11:47:03.951  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 11:47:03.951  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 11:47:03.952  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 11:47:03.952  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:47:03.953  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b1949f added. We now have 4 listener(s)
08-10 11:47:03.953  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 11:47:03.954  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 11:47:03.960  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 11:47:03.969  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:47:03.969  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:47:03.969  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:47:03.969  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:47:03.969  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:47:03.969  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:47:03.969  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:47:03.969  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:47:03.974  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:47:03.974  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 11:47:03.974  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 11:47:03.974  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-10 11:47:03.974  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 11:47:03.974  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 11:47:03.974  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 11:47:03.985  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:47:03.985  3687  3738 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 11:47:03.986  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 11:47:03.991  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:47:03.999  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 11:47:04.001  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 11:47:04.002  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 11:47:04.009  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 11:47:04.010  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 11:47:04.010  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 11:47:04.012  3687  3738 D BluetoothAdapter: STATE_ON
,08-10 11:47:04.016  4052  4062 D BtGatt.GattService: registerClient() - UUID=639694b9-8c96-4ea4-9a45-7bb38c89ff96
,08-10 11:47:04.018  4052  4068 D BtGatt.GattService: onClientRegistered() - UUID=639694b9-8c96-4ea4-9a45-7bb38c89ff96, clientIf=5
,08-10 11:47:04.020  3687  3698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 11:47:04.021  4052  4090 D BtGatt.GattService: start scan with filters
,08-10 11:47:04.026  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 11:47:04.026  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 11:47:04.026  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 11:47:04.026  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 11:47:04.027  4052  4071 D BtGatt.ScanManager: handling starting scan
08-10 11:47:04.029  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 11:47:04.030  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 11:47:04.030  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 11:47:04.030  4052  4071 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e261d12
,08-10 11:47:04.032  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 11:47:04.035  3687  3738 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-10 11:47:04.036  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:47:04.036  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-10 11:47:04.036  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:47:04.036  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-10 11:47:04.036  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 11:47:04.036  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 11:47:04.036  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 11:47:04.036  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 11:47:04.036  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 11:47:04.037  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 11:47:04.037  3687  3738 D BluetoothAdapter: STATE_ON
08-10 11:47:04.038  4052  4063 D BtGatt.GattService: stopScan() - queue size =1
08-10 11:47:04.040  4052  4090 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 11:47:04.041  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 11:47:04.041  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 11:47:04.041  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 11:47:04.042  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 11:47:04.042  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-10 11:47:04.044  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 11:47:04.044  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 11:47:04.044  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 11:47:04.044  4052  4068 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 11:47:04.044  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 11:47:04.044  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:47:04.045  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 11:47:04.046  4052  4071 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 11:47:04.047  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 11:47:04.047  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 11:47:04.047  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 11:47:04.051  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:47:04.051  3687  3738 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 11:47:04.051  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:47:04.051  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:47:04.051  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:47:04.052  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:04.052  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 11:47:04.052  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 11:47:04.052  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dc3e3e removed from the list
08-10 11:47:04.052  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:04.052  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b1949f removed from the list
08-10 11:47:04.052  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:47:04.052  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:04.053  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:04.054  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:04.057  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:47:04.057  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:47:04.057  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:04.057  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b1949f not in the list
08-10 11:47:04.057  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:04.057  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:04.058  4052  4068 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 11:47:04.058  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:47:04.058  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:47:04.058  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:47:04.058  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:04.058  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5b1949f not in the list
08-10 11:47:04.059  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:47:04.059  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:04.059  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:04.059  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7dc3e3e not in the list
08-10 11:47:04.059  4052  4071 D BtGatt.ScanManager: Starting BLE batch scan
08-10 11:47:04.060  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 11:47:04.060  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c6b8d8 added. We now have 3 listener(s)
08-10 11:47:04.060  4052  4071 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 11:47:04.062  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 11:47:04.062  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 11:47:04.062  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 11:47:04.062  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:47:04.062  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afeb431 added. We now have 4 listener(s)
08-10 11:47:04.063  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 11:47:04.063  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 11:47:04.066  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 11:47:04.073  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:47:04.073  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:47:04.073  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:47:04.073  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:47:04.073  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:47:04.073  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:47:04.073  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:47:04.073  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 11:47:04.076  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 11:47:04.076  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 11:47:04.079  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-10 11:47:04.079  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:47:04.081  3687  3738 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-10 11:47:04.081  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-10 11:47:04.081  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-10 11:47:04.081  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-10 11:47:04.081  3687  3738 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 11:47:04.082  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 11:47:04.082  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-10 11:47:04.083  3687  3738 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-10 11:47:04.083  3687  3738 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-10 11:47:04.083  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-10 11:47:04.083  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-10 11:47:04.083  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 11:47:04.083  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 11:47:04.086  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:47:04.086  4052  4068 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 11:47:04.087  3687  3687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-10 11:47:04.087  3687  3738 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 11:47:04.087  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 11:47:04.087  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:47:04.092  3687  4145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 11:47:04.092  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-10 11:47:04.093  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 11:47:04.093  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-10 11:47:04.094  3687  4145 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-10 11:47:04.096  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
08-10 11:47:04.096  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 11:47:04.097  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-10 11:47:04.098  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-10 11:47:04.098  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-10 11:47:04.098  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-10 11:47:04.098  4052  4068 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 11:47:04.098  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:47:04.099  3687  3738 D BluetoothAdapter: STATE_ON
08-10 11:47:04.102  4052  4090 D BtGatt.GattService: registerClient() - UUID=3c7d14db-3b49-4c2a-9b27-f3da14ae72c4
08-10 11:47:04.103  4052  4068 D BtGatt.GattService: onClientRegistered() - UUID=3c7d14db-3b49-4c2a-9b27-f3da14ae72c4, clientIf=5
08-10 11:47:04.103  3687  3698 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
08-10 11:47:04.105  4052  4070 D BtGatt.AdvertiseManager: message : 0
08-10 11:47:04.109  4052  4068 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 11:47:04.109  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:47:04.109  4052  4070 D BtGatt.AdvertiseManager: starting multi advertising
08-10 11:47:04.109  4052  4071 D BtGatt.ScanManager: stopping BLe Batch
08-10 11:47:04.127  4052  4068 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 11:47:04.127  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:47:04.127  4052  4071 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:47:04.139  4052  4068 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-10 11:47:04.144  4052  4068 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 11:47:04.144  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:47:04.151  4052  4068 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-10 11:47:04.153  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-10 11:47:04.153  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 11:47:04.157  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 11:47:04.160  3687  3687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-10 11:47:04.161  3687  3687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-10 11:47:04.162  3687  3687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-10 11:47:04.162  3687  3687 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,08-10 11:47:04.162  3687  3687 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-10 11:47:04.162  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-10 11:47:04.170  3687  3687 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-10 11:47:04.170  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-10 11:47:04.548  3687  3687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 11:47:04.671  3687  3687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-10 11:47:04.671  3687  3687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-10 11:47:04.671  3687  3687 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-10 11:47:07.403  1502  1502 I ConfigService: onDestroy
,08-10 11:47:09.161  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:47:09.161  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-10 11:47:09.162  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 11:47:09.162  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-10 11:47:09.162  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-10 11:47:09.163  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-10 11:47:09.165  3687  4145 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-10 11:47:09.165  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-10 11:47:09.165  3687  4145 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-10 11:47:09.165  3687  3738 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-10 11:47:09.165  3687  4145 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-10 11:47:09.166  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 11:47:09.167  3687  3687 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 11:47:09.166  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 11:47:09.167  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 11:47:09.167  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 11:47:09.168  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 11:47:09.170  3687  3738 D BluetoothAdapter: STATE_ON
08-10 11:47:09.170  3687  3738 D BluetoothLeScanner: could not find callback wrapper
08-10 11:47:09.171  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 11:47:09.171  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-10 11:47:09.174  4052  4070 D BtGatt.AdvertiseManager: message : 1
08-10 11:47:09.175  4052  4070 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-10 11:47:09.185  4052  4068 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
08-10 11:47:09.185  4052  4068 D BtGatt.GattService: Client app is not null!
,08-10 11:47:09.187  4052  4089 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 11:47:09.189  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 11:47:09.189  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-10 11:47:09.189  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-10 11:47:09.189  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-10 11:47:09.189  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-10 11:47:09.191  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 11:47:09.191  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 11:47:09.191  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 11:47:09.192  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 11:47:09.196  3687  3687 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:47:09.196  3687  3687 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-10 11:47:09.197  3687  3687 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-10 11:47:09.197  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:47:09.197  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 11:47:09.197  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:47:09.197  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 11:47:09.197  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 11:47:09.198  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 11:47:09.198  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 11:47:09.198  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c6b8d8 removed from the list
08-10 11:47:09.198  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:09.198  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afeb431 removed from the list
,08-10 11:47:09.199  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:47:09.199  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:09.200  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:47:09.201  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:47:09.203  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:47:09.203  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:47:09.203  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:09.203  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afeb431 not in the list
08-10 11:47:09.203  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:09.203  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:47:09.205  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:47:09.205  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:47:09.205  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:09.205  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afeb431 not in the list
08-10 11:47:09.205  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:47:09.205  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:47:09.205  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:09.205  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c6b8d8 not in the list
08-10 11:47:09.206  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 11:47:09.206  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cda4ea2 added. We now have 3 listener(s)
,08-10 11:47:09.208  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 11:47:09.208  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 11:47:09.208  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 11:47:09.208  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 11:47:09.208  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350733 added. We now have 4 listener(s)
08-10 11:47:09.208  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 11:47:09.209  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 11:47:09.213  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 11:47:09.220  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:47:09.220  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:47:09.220  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:47:09.220  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:47:09.220  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:47:09.220  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:47:09.220  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:47:09.220  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:47:09.223  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:47:09.224  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 11:47:09.224  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 11:47:09.225  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 11:47:09.225  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-10 11:47:09.225  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 11:47:09.225  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 11:47:09.226  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:47:09.229  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:47:09.231  3687  3738 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 11:47:09.231  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 11:47:09.235  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 11:47:09.236  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 11:47:09.236  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 11:47:09.240  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 11:47:09.240  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 11:47:09.240  3687  3738 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 11:47:09.241  3687  3738 D BluetoothAdapter: STATE_ON
,08-10 11:47:09.243  4052  4062 D BtGatt.GattService: registerClient() - UUID=23d5c1ab-93b2-470c-bfdf-30dc8386a5d8
,08-10 11:47:09.244  4052  4068 D BtGatt.GattService: onClientRegistered() - UUID=23d5c1ab-93b2-470c-bfdf-30dc8386a5d8, clientIf=5
,08-10 11:47:09.245  3687  3699 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 11:47:09.245  4052  4063 D BtGatt.GattService: start scan with filters
,08-10 11:47:09.248  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 11:47:09.249  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 11:47:09.249  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 11:47:09.249  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 11:47:09.249  4052  4071 D BtGatt.ScanManager: handling starting scan
,08-10 11:47:09.256  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 11:47:09.257  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 11:47:09.256  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 11:47:09.263  4052  4068 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 11:47:09.263  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:47:09.264  4052  4071 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-10 11:47:09.265  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 11:47:09.276  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 11:47:09.276  3687  3738 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 11:47:09.276  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-10 11:47:09.276  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 11:47:09.276  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 11:47:09.276  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-10 11:47:09.277  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 11:47:09.277  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 11:47:09.277  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 11:47:09.277  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-10 11:47:09.277  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 11:47:09.277  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 11:47:09.278  3687  3738 D BluetoothAdapter: STATE_ON
08-10 11:47:09.279  4052  4068 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 11:47:09.279  4052  4063 D BtGatt.GattService: stopScan() - queue size =1
08-10 11:47:09.279  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:47:09.279  4052  4071 D BtGatt.ScanManager: Starting BLE batch scan
08-10 11:47:09.279  4052  4071 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 11:47:09.279  4052  4089 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 11:47:09.280  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 11:47:09.280  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-10 11:47:09.280  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 11:47:09.280  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 11:47:09.280  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-10 11:47:09.281  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 11:47:09.282  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 11:47:09.282  3687  3738 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 11:47:09.282  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 11:47:09.282  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 11:47:09.285  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:47:09.285  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:09.285  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 11:47:09.285  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 11:47:09.285  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 11:47:09.285  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cda4ea2 removed from the list
08-10 11:47:09.285  3687  3687 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 11:47:09.285  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:09.286  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350733 removed from the list
08-10 11:47:09.286  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:47:09.286  3687  3687 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 11:47:09.286  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:09.286  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:09.286  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:47:09.287  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:47:09.288  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:47:09.288  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:09.288  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350733 not in the list
08-10 11:47:09.288  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:09.288  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:47:09.289  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:47:09.289  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:47:09.289  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:09.289  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@350733 not in the list
,08-10 11:47:09.289  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:47:09.290  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:09.290  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:09.290  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cda4ea2 not in the list
08-10 11:47:09.291  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 11:47:09.291  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c66a61c added. We now have 3 listener(s)
,08-10 11:47:09.293  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 11:47:09.293  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 11:47:09.294  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 11:47:09.294  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 11:47:09.294  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f97225 added. We now have 4 listener(s)
08-10 11:47:09.294  3687  3738 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 11:47:09.295  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 11:47:09.300  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 11:47:09.303  4052  4068 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 11:47:09.303  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:47:09.305  3687  3738 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 11:47:09.305  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 11:47:09.305  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 11:47:09.305  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 11:47:09.305  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 11:47:09.305  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 11:47:09.305  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 11:47:09.305  3687  3738 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 11:47:09.307  3687  3738 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 11:47:09.308  3687  3738 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 11:47:09.308  3687  3738 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 11:47:09.308  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 11:47:09.308  3687  3738 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 11:47:09.308  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:47:09.308  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:09.309  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 11:47:09.309  3687  3738 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 11:47:09.309  3687  3738 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c66a61c removed from the list
08-10 11:47:09.309  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:09.309  3687  3738 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f97225 removed from the list
08-10 11:47:09.311  4052  4068 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 11:47:09.311  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:47:09.312  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 11:47:09.313  3687  3738 D io.jxcore.node.ConnectivityMonitor: stop
08-10 11:47:09.313  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:47:09.314  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:09.314  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 11:47:09.316  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:47:09.316  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 11:47:09.316  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:09.316  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f97225 not in the list
08-10 11:47:09.316  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:09.316  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:09.316  3687  3687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 11:47:09.317  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 11:47:09.317  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 11:47:09.317  3687  3738 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 11:47:09.317  3687  3738 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f97225 not in the list
08-10 11:47:09.318  3687  3738 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 11:47:09.318  3687  3738 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 11:47:09.318  3687  3738 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 11:47:09.318  3687  3738 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c66a61c not in the list
,08-10 11:47:09.319  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-10 11:47:09.319  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-10 11:47:09.319  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-10 11:47:09.320  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 11:47:09.320  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-10 11:47:09.320  3687  3738 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 11:47:09.321  4052  4068 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 11:47:09.321  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:47:09.321  4052  4071 D BtGatt.ScanManager: stopping BLe Batch
,08-10 11:47:09.328  4052  4068 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 11:47:09.328  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 11:47:09.328  4052  4071 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 11:47:09.330  3687  4147 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: My test thread name)
,08-10 11:47:09.334  4052  4068 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-10 11:47:09.335  4052  4068 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 11:47:09.698  3687  3687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 11:47:09.786  3687  3687 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 11:47:11.328  3687  3738 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 462
08-10 11:47:11.329  3687  3738 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 462, name: My test thread name)
,08-10 11:47:11.335  3687  4148 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
,08-10 11:47:11.335  3687  4148 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 463, thread name: My test thread name)
08-10 11:47:11.336  3687  4148 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-10 11:47:11.341  3687  3738 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-10 11:47:11.349  3687  4149 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 467, name: My test thread name)
,08-10 11:47:11.350  3687  4149 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 467, thread name: My test thread name): Test exception.
08-10 11:47:11.350  3687  4149 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 467, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-10 11:47:11.358  3687  3738 I jxcore-log: Total number of executed tests:  82
08-10 11:47:11.358  3687  3738 I jxcore-log: 
,08-10 11:47:11.359  3687  3738 I jxcore-log: Number of passed tests:  82
08-10 11:47:11.359  3687  3738 I jxcore-log: 
,08-10 11:47:11.360  3687  3738 I jxcore-log: Number of failed tests:  0
08-10 11:47:11.360  3687  3738 I jxcore-log: 
,08-10 11:47:11.361  3687  3738 I jxcore-log: Number of ignored tests:  0,
08-10 11:47:11.361  3687  3738 I jxcore-log: 
,08-10 11:47:11.363  3687  3738 I jxcore-log: Total duration:  77307
08-10 11:47:11.363  3687  3738 I jxcore-log: 
,08-10 11:47:11.370  3687  3738 I jxcore-log: Unit Test app is loaded
08-10 11:47:11.370  3687  3738 I jxcore-log: 
,08-10 11:47:11.402  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.402  3687  3738 I jxcore-log: 
,08-10 11:47:11.402  3687  3687 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-10 11:47:11.415  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.415  3687  3738 I jxcore-log: 
,08-10 11:47:11.417  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.417  3687  3738 I jxcore-log: 
,08-10 11:47:11.419  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.419  3687  3738 I jxcore-log: 
,08-10 11:47:11.422  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-10 11:47:11.422  3687  3738 I jxcore-log: 
,08-10 11:47:11.425  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 11:47:11.425  3687  3738 I jxcore-log: 
,08-10 11:47:11.429  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.429  3687  3738 I jxcore-log: 
,08-10 11:47:11.430  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.430  3687  3738 I jxcore-log: 
,08-10 11:47:11.431  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-10 11:47:11.431  3687  3738 I jxcore-log: 
,08-10 11:47:11.432  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 11:47:11.432  3687  3738 I jxcore-log: 
08-10 11:47:11.433  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.433  3687  3738 I jxcore-log: 
,08-10 11:47:11.434  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.434  3687  3738 I jxcore-log: 
,08-10 11:47:11.434  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.434  3687  3738 I jxcore-log: 
08-10 11:47:11.435  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.435  3687  3738 I jxcore-log: 
,08-10 11:47:11.436  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.436  3687  3738 I jxcore-log: 
,08-10 11:47:11.437  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.437  3687  3738 I jxcore-log: 
,08-10 11:47:11.438  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.438  3687  3738 I jxcore-log: 
08-10 11:47:11.439  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.439  3687  3738 I jxcore-log: 
08-10 11:47:11.439  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.439  3687  3738 I jxcore-log: 
,08-10 11:47:11.440  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 11:47:11.440  3687  3738 I jxcore-log: 
,08-10 11:47:11.441  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.441  3687  3738 I jxcore-log: 
08-10 11:47:11.442  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.442  3687  3738 I jxcore-log: 
08-10 11:47:11.443  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.443  3687  3738 I jxcore-log: 
08-10 11:47:11.444  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.444  3687  3738 I jxcore-log: 
08-10 11:47:11.444  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.444  3687  3738 I jxcore-log: 
08-10 11:47:11.445  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.445  3687  3738 I jxcore-log: 
,08-10 11:47:11.446  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.446  3687  3738 I jxcore-log: 
,08-10 11:47:11.447  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.447  3687  3738 I jxcore-log: 
08-10 11:47:11.447  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.447  3687  3738 I jxcore-log: 
08-10 11:47:11.448  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.448  3687  3738 I jxcore-log: 
,08-10 11:47:11.449  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.449  3687  3738 I jxcore-log: 
08-10 11:47:11.450  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.450  3687  3738 I jxcore-log: 
08-10 11:47:11.450  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.450  3687  3738 I jxcore-log: 
08-10 11:47:11.451  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.451  3687  3738 I jxcore-log: 
,08-10 11:47:11.452  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.452  3687  3738 I jxcore-log: 
,08-10 11:47:11.453  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.453  3687  3738 I jxcore-log: 
08-10 11:47:11.454  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.454  3687  3738 I jxcore-log: 
,08-10 11:47:11.455  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.455  3687  3738 I jxcore-log: 
,08-10 11:47:11.455  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.455  3687  3738 I jxcore-log: 
08-10 11:47:11.456  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.456  3687  3738 I jxcore-log: 
,08-10 11:47:11.457  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 11:47:11.457  3687  3738 I jxcore-log: 
,08-10 11:47:11.457  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.457  3687  3738 I jxcore-log: 
08-10 11:47:11.458  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.458  3687  3738 I jxcore-log: 
08-10 11:47:11.459  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 11:47:11.459  3687  3738 I jxcore-log: 
08-10 11:47:11.460  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.460  3687  3738 I jxcore-log: 
08-10 11:47:11.460  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.460  3687  3738 I jxcore-log: 
08-10 11:47:11.461  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.461  3687  3738 I jxcore-log: 
,08-10 11:47:11.462  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.462  3687  3738 I jxcore-log: 
08-10 11:47:11.463  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.463  3687  3738 I jxcore-log: 
08-10 11:47:11.464  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 11:47:11.464  3687  3738 I jxcore-log: 
08-10 11:47:11.465  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-10 11:47:11.465  3687  3738 I jxcore-log: 
,08-10 11:47:11.465  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.465  3687  3738 I jxcore-log: 
08-10 11:47:11.466  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 11:47:11.466  3687  3738 I jxcore-log: 
,08-10 11:47:11.468  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 11:47:11.468  3687  3738 I jxcore-log: 
08-10 11:47:11.468  3687  3738 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 11:47:11.468  3687  3738 I jxcore-log: 
,08-10 11:47:11.471  3687  3738 I jxcore-log: My device name is: motorola-Nexus 6
08-10 11:47:11.471  3687  3738 I jxcore-log: 
,08-10 11:47:11.507  3687  4147 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-10 11:47:13.773  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-10 11:47:13.773  3687  3738 I jxcore-log: 
,08-10 11:47:14.393  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-10 11:47:14.393  3687  3738 I jxcore-log: 
,08-10 11:47:14.418  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-10 11:47:14.418  3687  3738 I jxcore-log: 
,08-10 11:47:15.781  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-10 11:47:15.781  3687  3738 I jxcore-log: 
,08-10 11:47:16.011  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-10 11:47:16.011  3687  3738 I jxcore-log: 
,08-10 11:47:16.017  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-10 11:47:16.017  3687  3738 I jxcore-log: 
,08-10 11:47:16.022  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-10 11:47:16.022  3687  3738 I jxcore-log: 
,08-10 11:47:16.039  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-10 11:47:16.039  3687  3738 I jxcore-log: 
,08-10 11:47:16.044  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-10 11:47:16.044  3687  3738 I jxcore-log: 
,08-10 11:47:16.723  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-10 11:47:16.723  3687  3738 I jxcore-log: 
,08-10 11:47:16.737  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-10 11:47:16.737  3687  3738 I jxcore-log: 
,08-10 11:47:16.747  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-10 11:47:16.747  3687  3738 I jxcore-log: 
,08-10 11:47:16.754  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-10 11:47:16.754  3687  3738 I jxcore-log: 
,08-10 11:47:16.804  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-10 11:47:16.804  3687  3738 I jxcore-log: 
,08-10 11:47:16.860  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-10 11:47:16.860  3687  3738 I jxcore-log: 
,08-10 11:47:16.868  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-10 11:47:16.868  3687  3738 I jxcore-log: 
,08-10 11:47:17.032  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-10 11:47:17.032  3687  3738 I jxcore-log: 
,08-10 11:47:17.059  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-10 11:47:17.059  3687  3738 I jxcore-log: 
,08-10 11:47:17.064  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-10 11:47:17.064  3687  3738 I jxcore-log: 
,08-10 11:47:17.070  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-10 11:47:17.070  3687  3738 I jxcore-log: 
,08-10 11:47:17.089  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-10 11:47:17.089  3687  3738 I jxcore-log: 
,08-10 11:47:17.172  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-10 11:47:17.172  3687  3738 I jxcore-log: 
,08-10 11:47:17.184  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-10 11:47:17.184  3687  3738 I jxcore-log: 
,08-10 11:47:17.212  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-10 11:47:17.212  3687  3738 I jxcore-log: 
,08-10 11:47:17.224  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-10 11:47:17.224  3687  3738 I jxcore-log: 
,08-10 11:47:17.243  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-10 11:47:17.243  3687  3738 I jxcore-log: 
,08-10 11:47:17.461  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-10 11:47:17.461  3687  3738 I jxcore-log: 
,08-10 11:47:17.468  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-10 11:47:17.468  3687  3738 I jxcore-log: 
,08-10 11:47:17.492  3687  3738 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-10 11:47:17.492  3687  3738 I jxcore-log: 
,08-10 11:47:17.503  3687  3738 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-10 11:47:17.507  3687  3738 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-10 11:47:17.507  3687  3738 I jxcore-log: 
,08-10 11:47:37.128   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=244924, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:47:44.630  2902  4151 V KeepSync: Connecting to GoogleApiClient
,08-10 11:47:44.630   871  1680 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 11:47:44.680  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:47:44.682  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:47:44.722  1502  2840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-10 11:47:44.722  1502  2840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 11:47:44.722  1502  2840 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 11:47:44.723  1502  2840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:47:44.753  1870  4152 V BaseAuthAsyncOperation: access token request failed
,08-10 11:47:44.755  2902  4151 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 11:47:44.828  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 11:47:44.828  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 11:47:44.828  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:47:44.828  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:47:44.858  2902  4151 E KeepSync: IOException
08-10 11:47:44.858  2902  4151 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 11:47:44.858  2902  4151 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:47:44.858  2902  4151 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 11:47:44.858  2902  4151 E KeepSync: 	... 10 more
,08-10 11:47:44.858  2902  4151 W KeepSync: Sync result 2
,08-10 11:47:44.875   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 252156, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:47:44.894   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=252690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:48:15.059  3628  4158 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 11:48:15.065  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:48:15.069  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:48:15.141  3461  4156 V GoogleAuthProtoRequest: [297] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 11:48:15.195  3628  4160 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 11:48:15.214  1502  2840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 11:48:15.214  1502  2840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 11:48:15.214  1502  2840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:48:15.214  1502  2840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:48:15.259  2862  4159 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 11:48:15.259  2862  4159 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at blb.a(PG:3937)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at czp.a(PG:18188)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:48:15.259  2862  4159 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	... 12 more
08-10 11:48:15.259  2862  4159 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at fal.a(PG:38)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:48:15.259  2862  4159 E HttpOperation: 	... 14 more
,08-10 11:48:15.308  1502  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 11:48:15.308  1502  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 11:48:15.308  1502  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:48:15.309  1502  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:48:15.322  1502  2840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 11:48:15.322  1502  2840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 11:48:15.322  1502  2840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:48:15.322  1502  2840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:48:15.348  2862  4159 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 11:48:15.348  2862  4159 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at hec.a(PG:42)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at hee.a(PG:102)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at czr.a(PG:65)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at kka.a(PG:108)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at czp.a(PG:19176)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:48:15.348  2862  4159 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	... 15 more
08-10 11:48:15.348  2862  4159 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at fal.a(PG:38)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:48:15.348  2862  4159 E HttpOperation: 	... 17 more
,08-10 11:48:15.348  2862  4159 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 11:48:15.348  2862  4159 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at hec.a(PG:42)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at hee.a(PG:102)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at czr.a(PG:65)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at kka.a(PG:108)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	... 15 more
08-10 11:48:15.348  2862  4159 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at fal.a(PG:38)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 11:48:15.348  2862  4159 E ExperimentLoader: 	... 17 more
,08-10 11:48:15.377  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 11:48:15.377  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 11:48:15.377  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 11:48:15.377  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:48:15.377  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:48:15.377  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-10 11:48:15.384  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 11:48:15.389  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:48:15.407  3628  4160 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 11:48:15.408  3628  4158 E BooksSync: Soft error
08-10 11:48:15.408  3628  4158 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:48:15.408  3628  4158 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 11:48:15.408  3628  4158 E BooksSync: Sync error
08-10 11:48:15.408  3628  4158 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:48:15.408  3628  4158 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 11:48:15.408  3628  4158 I BooksSync: Finished books sync
,08-10 11:48:15.427   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 280017, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:48:15.436  3461  4156 W ExperimentUpdateService: [297] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: [297] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: 	,at com.a.a.a.g.a(SourceFile:79)
08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 11:48:15.437  3461  4156 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 11:48:15.474   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 252780, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:48:27.081   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=294877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:48:35.441   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=303237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:48:45.693  2902  4167 V KeepSync: Connecting to GoogleApiClient
,08-10 11:48:45.693   871  1930 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 11:48:45.743  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:48:45.745  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:48:45.781  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 11:48:45.781  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-10 11:48:45.781  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:48:45.781  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:48:45.801  1870  4168 V BaseAuthAsyncOperation: access token request failed
,08-10 11:48:45.802  2902  4167 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 11:48:45.868  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 11:48:45.868  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 11:48:45.868  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:48:45.868  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:48:45.879  2902  4167 E KeepSync: IOException
08-10 11:48:45.879  2902  4167 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 11:48:45.879  2902  4167 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:48:45.879  2902  4167 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 11:48:45.879  2902  4167 E KeepSync: 	... 10 more
,08-10 11:48:45.879  2902  4167 W KeepSync: Sync result 2
,08-10 11:48:45.883   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 284628, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:49:13.928  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:49:13.939  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:49:13.940  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:49:13.973  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-10 11:49:13.973  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 11:49:13.973  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:49:13.973  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:49:13.997  1502  1515 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 11:49:13.997  1502  1515 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 11:49:13.997  1502  1515 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 11:49:13.997  1502  1515 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 11:49:13.997  1502  1515 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 11:49:13.997  1502  1515 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 11:49:13.997  1502  1515 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 11:49:14.003  3385  3415 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 11:49:14.003  3385  3415 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 11:49:14.003  3385  3415 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 11:49:14.003  3385  3415 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 11:49:14.003  3385  3415 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 11:49:14.003  3385  3415 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 11:49:14.003  3385  3415 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 11:49:16.136  3628  4175 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 11:49:16.240  3628  4177 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 11:49:16.313  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 11:49:16.313  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 11:49:16.313  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:49:16.313  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:49:16.353  1502  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 11:49:16.353  1502  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 11:49:16.354  1502  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 11:49:16.354  1502  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:49:16.378  2862  4176 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 11:49:16.378  2862  4176 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at blb.a(PG:3937)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at czp.a(PG:18188)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:49:16.378  2862  4176 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	... 12 more
08-10 11:49:16.378  2862  4176 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at fal.a(PG:38)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:49:16.378  2862  4176 E HttpOperation: 	... 14 more
,08-10 11:49:16.443  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 11:49:16.444  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 11:49:16.444  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:49:16.444  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:49:16.444  1502  2840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 11:49:16.444  1502  2840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 11:49:16.444  1502  2840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:49:16.444  1502  2840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:49:16.508  2862  4176 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 11:49:16.508  2862  4176 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at hec.a(PG:42)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at hee.a(PG:102)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at czr.a(PG:65)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at kka.a(PG:108)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at czp.a(PG:19176)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:49:16.508  2862  4176 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	... 15 more
08-10 11:49:16.508  2862  4176 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at fal.a(PG:38)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:49:16.508  2862  4176 E HttpOperation: 	... 17 more
08-10 11:49:16.508  2862  4176 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 11:49:16.508  2862  4176 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at hec.a(PG:42)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at hee.a(PG:102)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at czr.a(PG:65)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at kka.a(PG:108)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	... 15 more
08-10 11:49:16.508  2862  4176 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at fal.a(PG:38)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 11:49:16.508  2862  4176 E ExperimentLoader: 	... 17 more
,08-10 11:49:16.514  3628  4177 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 11:49:16.522  3628  4175 E BooksSync: Soft error
08-10 11:49:16.522  3628  4175 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:49:16.522  3628  4175 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 11:49:16.523  3628  4175 E BooksSync: Sync error
08-10 11:49:16.523  3628  4175 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:49:16.523  3628  4175 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 11:49:16.523  3628  4175 I BooksSync: Finished books sync
,08-10 11:49:16.544   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 314998, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:49:16.671   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 314194, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:49:49.972  2902  4180 V KeepSync: Connecting to GoogleApiClient
,08-10 11:49:49.973   871   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 11:49:50.027  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:49:50.029  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:49:50.061  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 11:49:50.061  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 11:49:50.061  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:49:50.061  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:49:50.088  1870  4181 V BaseAuthAsyncOperation: access token request failed
,08-10 11:49:50.089  2902  4180 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 11:49:50.155  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 11:49:50.155  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 11:49:50.155  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:49:50.155  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:49:50.180  2902  4180 E KeepSync: IOException
08-10 11:49:50.180  2902  4180 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 11:49:50.180  2902  4180 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:49:50.180  2902  4180 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 11:49:50.180  2902  4180 E KeepSync: 	... 10 more
,08-10 11:49:50.181  2902  4180 W KeepSync: Sync result 2
,08-10 11:49:50.193   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 377592, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:49:56.467   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=384263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:50:06.388   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=394184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:50:20.490  3628  4185 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 11:50:20.571  3628  4186 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 11:50:20.585  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:50:20.587  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:50:20.638  1502  2840 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 11:50:20.638  1502  2840 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 11:50:20.638  1502  2840 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:50:20.638  1502  2840 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:50:20.661  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 11:50:20.661  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 11:50:20.661  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:50:20.661  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:50:20.675  2862  4184 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 11:50:20.675  2862  4184 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at blb.a(PG:3937)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at czp.a(PG:18188)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:50:20.675  2862  4184 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	... 12 more
08-10 11:50:20.675  2862  4184 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at fal.a(PG:38)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:50:20.675  2862  4184 E HttpOperation: 	... 14 more
,08-10 11:50:20.764  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 11:50:20.764  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 11:50:20.764  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:50:20.764  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 11:50:20.765  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 11:50:20.765  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 11:50:20.765  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 11:50:20.766  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:50:20.791  2862  4184 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 11:50:20.791  2862  4184 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at hec.a(PG:42)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at hee.a(PG:102)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at czr.a(PG:65)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at kka.a(PG:108)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at czp.a(PG:19176)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:50:20.791  2862  4184 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	... 15 more
08-10 11:50:20.791  2862  4184 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at fal.a(PG:38)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:50:20.791  2862  4184 E HttpOperation: 	... 17 more
,08-10 11:50:20.792  2862  4184 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 11:50:20.792  2862  4184 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at hec.a(PG:42)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at hee.a(PG:102)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at czr.a(PG:65)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at kka.a(PG:108)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	... 15 more
08-10 11:50:20.792  2862  4184 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at fal.a(PG:38)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 11:50:20.792  2862  4184 E ExperimentLoader: 	... 17 more
,08-10 11:50:20.797  3628  4186 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 11:50:20.798  3628  4185 E BooksSync: Soft error
08-10 11:50:20.798  3628  4185 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:50:20.798  3628  4185 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 11:50:20.798  3628  4185 E BooksSync: Sync error
08-10 11:50:20.798  3628  4185 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:50:20.798  3628  4185 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 11:50:20.798  3628  4185 I BooksSync: Finished books sync
,08-10 11:50:20.812   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 407887, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:50:20.943   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 406314, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:50:48.521   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=436317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:50:56.921   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=444717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:51:16.546  1502  2018 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 11:51:39.081   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=486877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:51:47.441   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=495237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:51:58.255  2902  4192 V KeepSync: Connecting to GoogleApiClient
,08-10 11:51:58.256   871   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 11:51:58.325  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:51:58.329  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:51:58.391  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata,
08-10 11:51:58.391  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 11:51:58.391  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:51:58.391  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:51:58.427  1870  4193 V BaseAuthAsyncOperation: access token request failed
,08-10 11:51:58.429  2902  4192 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 11:51:58.514  1502  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-10 11:51:58.514  1502  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 11:51:58.514  1502  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:51:58.514  1502  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:51:58.537  2902  4192 E KeepSync: IOException
08-10 11:51:58.537  2902  4192 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 11:51:58.537  2902  4192 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:51:58.537  2902  4192 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 11:51:58.537  2902  4192 E KeepSync: 	... 10 more
08-10 11:51:58.537  2902  4192 W KeepSync: Sync result 2
,08-10 11:51:58.553   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 505814, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:52:28.761  3628  4197 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 11:52:28.875  3628  4199 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 11:52:28.895  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:52:28.897  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:52:28.951  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 11:52:28.951  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 11:52:28.951  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:52:28.951  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:52:28.974  2862  4198 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 11:52:28.974  2862  4198 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at blb.a(PG:3937)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at czp.a(PG:18188)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:52:28.974  2862  4198 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	... 12 more
08-10 11:52:28.974  2862  4198 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at fal.a(PG:38)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:52:28.974  2862  4198 E HttpOperation: 	... 14 more
,08-10 11:52:28.987  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 11:52:28.988  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 11:52:28.988  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:52:28.988  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:52:29.068  1502  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 11:52:29.069  1502  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 11:52:29.069  1502  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 11:52:29.069  1502  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:52:29.097  2862  4198 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 11:52:29.097  2862  4198 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at hec.a(PG:42)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at hee.a(PG:102)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at czr.a(PG:65)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at kka.a(PG:108)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at czp.a(PG:19176)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:52:29.097  2862  4198 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	... 15 more
08-10 11:52:29.097  2862  4198 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at fal.a(PG:38)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:52:29.097  2862  4198 E HttpOperation: 	... 17 more
,08-10 11:52:29.097  2862  4198 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 11:52:29.097  2862  4198 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at hec.a(PG:42)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at hee.a(PG:102)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at czr.a(PG:65)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at kka.a(PG:108)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	... 15 more
08-10 11:52:29.097  2862  4198 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at fal.a(PG:38)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 11:52:29.097  2862  4198 E ExperimentLoader: 	... 17 more
,08-10 11:52:29.110  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 11:52:29.111  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 11:52:29.111  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:52:29.111  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:52:29.132  3628  4199 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 11:52:29.133  3628  4197 E BooksSync: Soft error
08-10 11:52:29.133  3628  4197 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:52:29.133  3628  4197 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 11:52:29.133  3628  4197 E BooksSync: Sync error
08-10 11:52:29.133  3628  4197 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:52:29.133  3628  4197 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 11:52:29.133  3628  4197 I BooksSync: Finished books sync
,08-10 11:52:29.146   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 535701, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:52:29.247   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 532432, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:52:29.641   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=537437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:52:37.987   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=545783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:52:45.256  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:52:45.258  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:52:45.277  3461  4202 V GoogleAuthProtoRequest: [298] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 11:52:45.315  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 11:52:45.316  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 11:52:45.316  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:52:45.316  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: [298] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: [298] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 11:52:45.338  3461  4202 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 11:53:20.201   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:53:28.467   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=596263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:54:10.547   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=638343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:54:18.961   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=646757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:55:01.108   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=688904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:55:07.401   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=695197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:55:49.534   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=737330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:55:57.881   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=745677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:56:14.511  2902  4217 V KeepSync: Connecting to GoogleApiClient
08-10 11:56:14.512   871  1930 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 11:56:14.577  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:56:14.578  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:56:14.612  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 11:56:14.612  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 11:56:14.612  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:56:14.613  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:56:14.631  1870  4218 V BaseAuthAsyncOperation: access token request failed
,08-10 11:56:14.632  2902  4217 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 11:56:14.673  1502  1927 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 11:56:14.673  1502  1927 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 11:56:14.673  1502  1927 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 11:56:14.673  1502  1927 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:56:14.688  2902  4217 E KeepSync: IOException
08-10 11:56:14.688  2902  4217 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 11:56:14.688  2902  4217 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 11:56:14.688  2902  4217 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 11:56:14.688  2902  4217 E KeepSync: 	... 10 more
,08-10 11:56:14.688  2902  4217 W KeepSync: Sync result 2
,08-10 11:56:14.703   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 761998, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:56:40.094   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=787891, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:56:44.821  3628  4222 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 11:56:44.929  3628  4224 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 11:56:44.941  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:56:44.943  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:56:44.972  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 11:56:44.972  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 11:56:44.973  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 11:56:44.973  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:56:45.003  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:56:45.006  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 11:56:45.043  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 11:56:45.043  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 11:56:45.043  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:56:45.043  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:56:45.075  3628  4224 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 11:56:45.078  3628  4222 E BooksSync: Soft error
08-10 11:56:45.078  3628  4222 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:56:45.078  3628  4222 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 11:56:45.078  3628  4222 E BooksSync: Sync error
08-10 11:56:45.078  3628  4222 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 11:56:45.078  3628  4222 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 11:56:45.081  3628  4222 I BooksSync: Finished books sync,
,08-10 11:56:45.086  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 11:56:45.086  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 11:56:45.086  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:56:45.086  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:56:45.098   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 791127, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:56:45.110  2862  4223 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 11:56:45.110  2862  4223 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at blb.a(PG:3937)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at czp.a(PG:18188)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at czp.a(PG:9081)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:56:45.110  2862  4223 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	... 12 more
08-10 11:56:45.110  2862  4223 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at fal.a(PG:38)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:56:45.110  2862  4223 E HttpOperation: 	... 14 more
,08-10 11:56:45.162  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 11:56:45.162  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 11:56:45.162  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 11:56:45.162  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 11:56:45.184  2862  4223 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 11:56:45.184  2862  4223 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at jdm.a(PG:82)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at jcs.o(PG:406)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at jcn.a(PG:1379)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at jcs.i(PG:143)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at hec.a(PG:42)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at hee.a(PG:102)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at czr.a(PG:65)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at kka.a(PG:108)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at czp.a(PG:19176)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at czp.a(PG:9081)
,08-10 11:56:45.184  2862  4223 E HttpOperation: 	at czq.run(PG:1686)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:56:45.184  2862  4223 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at jdj.a(PG:4091)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at jdj.a(PG:1125)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at jdm.a(PG:77)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	... 15 more
08-10 11:56:45.184  2862  4223 E HttpOperation: Caused by: faj: BadAuthentication
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at fal.a(PG:38)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	at jdj.a(PG:4089)
08-10 11:56:45.184  2862  4223 E HttpOperation: 	... 17 more
08-10 11:56:45.184  2862  4223 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 11:56:45.184  2862  4223 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at hec.a(PG:42)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at hee.a(PG:102)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at czr.a(PG:65)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at kka.a(PG:108)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	... 15 more
08-10 11:56:45.184  2862  4223 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at fal.a(PG:38)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 11:56:45.184  2862  4223 E ExperimentLoader: 	... 17 more
,08-10 11:56:45.313   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 784427, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 11:56:48.361   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=796157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:57:30.441   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=838237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:57:38.841   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=846637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:58:21.001   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=888797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:58:29.387   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=897183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:58:42.041   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=909837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:58:49.574   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=917370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:59:02.227   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=930023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:59:09.774   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=937570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:59:22.441   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=950237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:59:29.975   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=957771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 11:59:42.628   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=970424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 11:59:50.174   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=977971, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:00:02.814   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=990610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:00:10.374   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=998170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:00:23.028   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1010824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:00:30.574   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1018370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:00:43.241   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1031037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:00:50.761   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1038557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:01:03.401   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1051197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:01:10.974   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1058770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:01:23.614   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1071410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:01:31.214   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1079010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:01:43.881   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1091677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:01:51.427   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1099223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:01:55.211  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:01:55.214  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:01:55.229  3461  4238 V GoogleAuthProtoRequest: [299] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 12:01:55.306  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-10 12:01:55.306  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 12:01:55.306  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:01:55.306  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:01:55.335  3461  4238 W ExperimentUpdateService: [299] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: [299] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 12:01:55.336  3461  4238 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 12:02:07.867   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1115663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:02:16.654   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1124450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:02:29.321   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1137117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:02:36.868   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1144664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:02:49.534   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1157330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:02:57.081   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1164877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:03:09.748   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1177544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:03:17.268   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1185064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:03:35.348   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1203144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:03:42.494   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1210290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:03:49.983   871   883 I UsageStatsService: User[0] Flushing usage stats to disk
,08-10 12:04:00.575   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1228371, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:04:07.734   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1235530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:04:25.801   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1253597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:04:32.975   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1260771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:04:46.290  2902  4249 V KeepSync: Connecting to GoogleApiClient
08-10 12:04:46.290   871  1714 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 12:04:46.340  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:04:46.345  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:04:46.382  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-10 12:04:46.383  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-10 12:04:46.383  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:04:46.383  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:04:46.404  1870  4250 V BaseAuthAsyncOperation: access token request failed
,08-10 12:04:46.406  2902  4249 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 12:04:46.470  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-10 12:04:46.470  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 12:04:46.470  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:04:46.470  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:04:46.495  2902  4249 E KeepSync: IOException
08-10 12:04:46.495  2902  4249 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 12:04:46.495  2902  4249 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 12:04:46.495  2902  4249 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 12:04:46.495  2902  4249 E KeepSync: 	... 10 more
08-10 12:04:46.495  2902  4249 W KeepSync: Sync result 2
,08-10 12:04:46.508   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1273796, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:04:51.081   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1278877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:04:59.241   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1287037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:05:16.804  3628  4254 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 12:05:16.897  3628  4255 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 12:05:16.915  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:05:16.922  1502  1502 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 12:05:17.010  1502  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:05:17.010  1502  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 12:05:17.010  1502  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:05:17.010  1502  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 12:05:17.011  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 12:05:17.011  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 12:05:17.011  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:05:17.011  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:05:17.062  2862  4253 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 12:05:17.062  2862  4253 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at blb.a(PG:3937)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at czp.a(PG:18188)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:05:17.062  2862  4253 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	... 12 more
08-10 12:05:17.062  2862  4253 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at fal.a(PG:38)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:05:17.062  2862  4253 E HttpOperation: 	... 14 more
,08-10 12:05:17.138  1502  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 12:05:17.138  1502  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 12:05:17.138  1502  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 12:05:17.138  1502  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:05:17.159  1502  1926 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 12:05:17.159  1502  1926 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 12:05:17.159  1502  1926 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 12:05:17.159  1502  1926 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 12:05:17.170  3628  4255 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 12:05:17.174  3628  4254 E BooksSync: Soft error
08-10 12:05:17.174  3628  4254 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:05:17.174  3628  4254 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 12:05:17.175  3628  4254 E BooksSync: Sync error
08-10 12:05:17.175  3628  4254 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 12:05:17.175  3628  4254 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 12:05:17.175  3628  4254 I BooksSync: Finished books sync
,08-10 12:05:17.186  2862  4253 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 12:05:17.186  2862  4253 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at jdm.a(PG:82)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at jcs.o(PG:406)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at jcn.a(PG:1379)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at jcs.i(PG:143)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at hec.a(PG:42)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at hee.a(PG:102)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at czr.a(PG:65)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at kka.a(PG:108)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at czp.a(PG:19176)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at czp.a(PG:9081)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at czq.run(PG:1686)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:05:17.186  2862  4253 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at jdj.a(PG:4091)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at jdj.a(PG:1125)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at jdm.a(PG:77)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	... 15 more
08-10 12:05:17.186  2862  4253 E HttpOperation: Caused by: faj: BadAuthentication
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at fal.a(PG:38)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	at jdj.a(PG:4089)
08-10 12:05:17.186  2862  4253 E HttpOperation: 	... 17 more
,08-10 12:05:17.187  2862  4253 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 12:05:17.187  2862  4253 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at hec.a(PG:42)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at hee.a(PG:102)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at czr.a(PG:65)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at kka.a(PG:108)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	... 15 more
08-10 12:05:17.187  2862  4253 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at fal.a(PG:38)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 12:05:17.187  2862  4253 E ExperimentLoader: 	... 17 more
,08-10 12:05:17.192   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1301263, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:05:17.304   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1287878, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 12:05:17.320   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1305116, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:05:24.481   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1312277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:05:42.601   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1330397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:05:49.721   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1337517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:06:07.828   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1355624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:06:14.960   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1362756, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:06:33.054   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1380850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:06:40.214   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1388010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:06:58.334   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1406130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:07:05.467   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1413263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:07:23.561   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1431357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:07:30.708   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1438504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:07:48.788   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1456584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:07:55.947   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1463743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:08:18.387   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1486183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:08:26.334   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1494130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 12:08:48.841   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1516637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 12:08:56.641   871  4109 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1524437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,TIME-OUT KILL (timeout was 1400000ms),08-10 12:09:05.843  4267  4267 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 12:09:05.848  4267  4267 D AndroidRuntime: CheckJNI is OFF
08-10 12:09:05.884  4267  4267 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 12:09:05.924  4267  4267 I Radio-JNI: register_android_hardware_Radio DONE
08-10 12:09:05.944  4267  4267 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-10 12:09:05.956   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-10 12:09:05.957   871   884 I ActivityManager: Killing 3687:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-10 12:09:06.062   871  1714 D GraphicsStats: Buffer count: 2
08-10 12:09:06.062   871  1724 I WindowState: WIN DEATH: Window{9afe7c2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 12:09:06.063   871  1303 D WifiService: Client connection lost with reason: 4
08-10 12:09:06.080   871   894 W PackageSettings: Skipping PackageSetting{f42f0d7 com.example.hello/10273} due to missing metadata
08-10 12:09:06.123   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-10 12:09:06.123   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-10 12:09:06.124   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-10 12:09:06.124   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-10 12:09:06.124   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:09:06.124   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:09:06.124   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 12:09:06.124   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 12:09:06.124   871   894 I art     : Starting a blocking GC Explicit
08-10 12:09:06.125   871   884 I ActivityManager:   Force finishing activity ActivityRecord{a21427b u0 com.test.thalitest/.MainActivity t8}
08-10 12:09:06.132   871  1682 W ActivityManager: Spurious death for ProcessRecord{8b1f667 0:com.test.thalitest/u0a0}, curProc for 3687: null
08-10 12:09:06.182   871   894 I art     : Explicit concurrent mark sweep GC freed 39457(2MB) AllocSpace objects, 10(200KB) LOS objects, 33% free, 29MB/43MB, paused 985us total 56.922ms
08-10 12:09:06.216   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-10 12:09:06.220  4267  4267 I art     : System.exit called, status: 0
08-10 12:09:06.220  4267  4267 I AndroidRuntime: VM exiting with result code 0.
08-10 12:09:06.274   871   894 I ActivityManager: Start proc 4278:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-10 12:09:06.275   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-10 12:09:06.307   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-10 12:09:06.311  4052  4052 D BluetoothMapAppObserver: onReceive
08-10 12:09:06.311  4052  4052 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-10 12:09:06.312   871  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-10 12:09:06.316  1768  2016 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-10 12:09:06.335  3518  3518 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-10 12:09:06.337  1648  1648 I Keyboard.Facilitator: resetDictionaries() : en_US
08-10 12:09:06.353  1711  1711 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-10 12:09:06.370   871  1899 I ActivityManager: Start proc 4294:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-10 12:09:06.371  1648  4297 I Keyboard.Facilitator.DecoderInitializer: run()
08-10 12:09:06.375   871  1300 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-10 12:09:06.380  1648  4297 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-10 12:09:06.380  1648  4297 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-10 12:09:06.381  1648  4297 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-10 12:09:06.381  1648  4297 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-10 12:09:06.381  1648  4297 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-10 12:09:06.381  1648  4297 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-10 12:09:06.384  1648  4297 I Decoder : createOrResetDecoder
08-10 12:09:06.401   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 12:09:06.402   871  1370 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3687 uid 10000
08-10 12:09:06.403  1648  1648 I Keyboard.Facilitator: onFinishInput()
08-10 12:09:06.416  1502  1502 I ConfigService: onCreate
08-10 12:09:06.433  1726  1835 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-10 12:09:06.433   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-10 12:09:06.434   871   883 E PackageManager: Failed to write settings, restoring backup
08-10 12:09:06.434   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-10 12:09:06.434   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-10 12:09:06.434   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-10 12:09:06.434   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-10 12:09:06.434   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-10 12:09:06.434   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:09:06.434   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:09:06.434   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 12:09:06.438   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-10 12:09:06.438   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 12:09:06.438   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 12:09:06.438   871   884 E DropBoxManagerService: 	... 13 more
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 12:09:06.441  1502  4307 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 12:09:06.442  1502  4307 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-10 12:09:06.443  1502  4307 W SQLiteOpenHelper: Opened config.db in read-only mode
08-10 12:09:06.446   871  1370 I ActivityManager: Start proc 4308:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-10 12:09:06.447  1726  1835 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-10 12:09:06.447  1726  1835 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1726
08-10 12:09:06.447  1726  1835 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:09:06.447  1726  1835 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 12:09:06.449   871  3009 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 12:09:06.452   871  4316 E DropBoxManagerService: Can't write: system_app_crash
08-10 12:09:06.452   871  4316 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 12:09:06.452   871  4316 E DropBoxManagerService: 	... 5 more
08-10 12:09:06.453  1726  1835 I Process : Sending signal. PID: 1726 SIG: 9
08-10 12:09:06.468  4294  4294 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-10 12:09:06.486  1648  4297 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-10 12:09:06.522  1648  4297 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-10 12:09:06.524  1648  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-10 12:09:06.524  1648  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-10 12:09:06.526  1648  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-10 12:09:06.526  1648  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-10 12:09:06.527  1648  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-10 12:09:06.527  1648  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-10 12:09:06.527  1648  4297 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-10 12:09:06.527  1648  4297 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-10 12:09:06.527  1648  4297 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-10 12:09:06.528  1648  4297 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-10 12:09:06.528  1648  4297 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-10 12:09:06.528  1648  4297 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-10 12:09:06.541   871  1929 D GraphicsStats: Buffer count: 1
08-10 12:09:06.541   871  1682 I WindowState: WIN DEATH: Window{4d1b4b2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-10 12:09:06.558   871  3009 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1726) has died
08-10 12:09:06.558   871  3009 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-10 12:09:06.559   871  3009 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:09:06.582  4294  4325 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:09:06.582  4294  4325 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 12:09:06.586   871   884 I ActivityManager: Start proc 4328:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 12:09:06.596  4294  4294 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-10 12:09:06.619  1870  4326 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-10 12:09:06.619  1870  4326 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 12:09:06.632  4328  4328 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 12:09:06.632  4328  4328 D AndroidRuntime: Shutting down VM
08-10 12:09:06.633   871  1370 I ActivityManager: Start proc 4340:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-10 12:09:06.635  4294  4345 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-10 12:09:06.647  4328  4328 E AndroidRuntime: FATAL EXCEPTION: main
08-10 12:09:06.647  4328  4328 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4328
08-10 12:09:06.647  4328  4328 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-10 12:09:06.647  4328  4328 E AndroidRuntime: 	... 10 more
08-10 12:09:06.651   871  3009 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 12:09:06.651   871  4353 E DropBoxManagerService: Can't write: system_app_crash
08-10 12:09:06.651   871  4353 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 12:09:06.651   871  4353 E DropBoxManagerService: 	... 5 more
08-10 12:09:06.652  4328  4328 I Process : Sending signal. PID: 4328 SIG: 9
08-10 12:09:06.668  1870  4326 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-10 12:09:06.669  1870  4326 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-10 12:09:06.679   871  1370 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4328) has died
08-10 12:09:06.680   871  1370 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-10 12:09:06.685  4340  4340 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-10 12:09:06.696   871   884 I ActivityManager: Start proc 4354:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 12:09:06.712   282   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
