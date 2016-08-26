#### Test 82914073856d1c8_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-26 19:45:17.311   873  1885 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-26 19:45:18.206  3961  3961 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-26 19:45:18.211  3961  3961 D AndroidRuntime: CheckJNI is OFF
08-26 19:45:18.255  3961  3961 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-26 19:45:18.307  3961  3961 I Radio-JNI: register_android_hardware_Radio DONE
08-26 19:45:18.328  3961  3961 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-26 19:45:18.333   873   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 19:45:18.358  2005  3904 W SearchService: Abort, client detached.
08-26 19:45:18.375  3961  3961 D AndroidRuntime: Shutting down VM
08-26 19:45:18.376  2005  2346 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@1e65339
08-26 19:45:18.377  2005  2005 I HotwordDetector: Closing mic
08-26 19:45:18.394   873  3241 I ActivityManager: Start proc 3971:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-26 19:45:18.443   375  2364 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-26 19:45:18.444   375  2364 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-26 19:45:18.447   375  1285 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-26 19:45:18.450  2005  2350 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-26 19:45:18.450  2005  2361 I MicroRecognitionRnrImpl: Detection finished
08-26 19:45:18.469  3971  3971 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-26 19:45:18.491  3971  3971 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-26 19:45:18.497  3971  3971 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9982-9984)
08-26 19:45:18.498  3971  3971 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:45:18.518  3971  3971 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6005d2}
08-26 19:45:18.518  3971  3971 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:45:18.518  3971  3971 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 19:45:18.525  3971  3971 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 19:45:18.526  3971  3971 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 19:45:18.544  3971  3971 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-26 19:45:18.555  3971  3971 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 19:45:18.555  3971  3971 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 19:45:18.555  3971  3971 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 19:45:18.555  3971  3971 I Adreno  : Build Date                       : 10/20/15
08-26 19:45:18.555  3971  3971 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 19:45:18.555  3971  3971 I Adreno  : Local Branch                     : M14
08-26 19:45:18.555  3971  3971 I Adreno  : Remote Branch                    : 
08-26 19:45:18.555  3971  3971 I Adreno  : Remote Branch                    : 
08-26 19:45:18.555  3971  3971 I Adreno  : Reconstruct Branch               : 
,08-26 19:45:18.621   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7a8db7e:true
,08-26 19:45:18.652  3971  3971 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 19:45:18.666  3971  3971 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-26 19:45:18.711  3971  4009 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-26 19:45:18.721  3971  3996 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-26 19:45:18.770  3971  4009 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 19:45:18.841   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +466ms
,08-26 19:45:18.847  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-26 19:45:18.918  3971  3971 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3971
,08-26 19:45:19.062  3971  3971 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 19:45:19.186   873   883 I ActivityManager: Killing 2464:com.google.android.talk/u0a61 (adj 15): empty #17
,08-26 19:45:19.229  3971  4011 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1697777360
,08-26 19:45:19.232   873   883 I ActivityManager: Killing 3336:com.google.android.gm/u0a78 (adj 15): empty #18
,08-26 19:45:19.240  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 19:45:19.240  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 19:45:19.240  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 19:45:19.240  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 19:45:19.240  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 19:45:19.240  3971  4011 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30aa451 added. We now have 1 listener(s)
08-26 19:45:19.244  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-26 19:45:19.245  3971  4011 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:45:19.245  3971  4011 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:19.246  3971  4011 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 19:45:19.249  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 19:45:19.251  3971  4011 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9c2d124 added. We now have 1 listener(s)
,08-26 19:45:19.251  3971  4011 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:19.254   873  1316 D WifiService: New client listening to asynchronous messages
,08-26 19:45:19.257  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:45:19.257  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 19:45:19.257  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 19:45:19.257  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 19:45:19.257  3971  4011 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 19:45:19.304  3971  4011 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:19.305  3971  4011 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-26 19:45:19.308  3971  4011 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 19:45:19.309  3971  4011 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:19.309  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:19.309  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:19.309  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:19.309  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:19.309  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:19.309  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:19.309  3971  4011 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:19.309  3971  4011 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 19:45:19.309  3971  4011 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:19.309  3971  4011 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 19:45:19.407  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:19.410  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:19.413  3971  3971 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 19:45:20.121  3971  4021 W jxcore-log: Initializing JXcore engine
08-26 19:45:20.121  3971  4021 W jxcore-log: JXcore engine is ready
,08-26 19:45:20.153  4021  4021 W Thread-366: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8951 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-26 19:45:20.156  4021  4021 W Thread-366: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11466]" dev="sockfs" ino=11466 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-26 19:45:20.156  4021  4021 W Thread-366: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-26 19:45:20.156  4021  4021 W Thread-366: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25961]" dev="sockfs" ino=25961 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-26 19:45:20.171  3971  4021 W jxcore-log: Starting JXcore engine
,08-26 19:45:20.250  3971  4021 W jxcore-log: Platform android
08-26 19:45:20.250  3971  4021 W jxcore-log: 
,08-26 19:45:20.250  3971  4021 W jxcore-log: Process ARCH arm
08-26 19:45:20.250  3971  4021 W jxcore-log: 
,08-26 19:45:20.454  3971  4021 I jxcore-log: JXcore Cordova bridge is ready!
08-26 19:45:20.454  3971  4021 I jxcore-log: 
,08-26 19:45:20.454  3971  4021 W jxcore-log: JXcore engine is started
,08-26 19:45:20.465  3971  4011 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 19:45:20.471  3971  3971 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 19:45:22.115   873  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,08-26 19:45:29.251  3730  4029 V KeepSync: Connecting to GoogleApiClient
,08-26 19:45:29.252   873  1389 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-26 19:45:29.316  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:45:29.320  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:45:29.383  1521  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-26 19:45:29.384  1521  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-26 19:45:29.384  1521  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:45:29.384  1521  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:45:29.425  1731  4030 V BaseAuthAsyncOperation: access token request failed
,08-26 19:45:29.430  3730  4029 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-26 19:45:29.600  3758  4033 V GoogleAuthProtoRequest: [326] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 19:45:29.616  1521  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-26 19:45:29.616  1521  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-26 19:45:29.616  1521  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:45:29.616  1521  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:45:29.620  1521  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-26 19:45:29.620  1521  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-26 19:45:29.622  1521  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:45:29.624  1521  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:45:29.638  3730  4029 E KeepSync: IOException
08-26 19:45:29.638  3730  4029 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-26 19:45:29.638  3730  4029 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-26 19:45:29.638  3730  4029 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-26 19:45:29.638  3730  4029 E KeepSync: 	... 10 more
,08-26 19:45:29.638  3730  4029 W KeepSync: Sync result 2
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-26 19:45:29.640  3758  4033 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
08-26 19:45:29.659   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 129963, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-26 19:45:29.733  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:45:29.758  1521  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 19:45:29.758  1521  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 19:45:29.758  1521  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 19:45:29.758  1521  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:45:29.770  1521  4035 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-26 19:45:29.772  1521  4035 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 19:45:29.777  3646  3646 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-26 19:45:29.777  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-26 19:45:29.777  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-26 19:45:30.261  1521  4035 W Uploader:  no longer exists, so no auth token.
,08-26 19:45:30.555  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 19:45:30.555  3971  4021 I jxcore-log: 
,08-26 19:45:30.558  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 19:45:30.558  3971  4021 I jxcore-log: 
,08-26 19:45:30.564  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:30.564  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:30.564  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:30.564  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:30.564  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:30.564  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:30.564  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:30.564  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:30.568  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:30.571  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 19:45:30.571  3971  4021 I jxcore-log: 
,08-26 19:45:30.573  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 19:45:30.573  3971  4021 I jxcore-log: 
,08-26 19:45:31.106  3971  4021 D executeNativeTests: Running unit tests
,08-26 19:45:31.167  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:45:31.167  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 added. We now have 2 listener(s)
08-26 19:45:31.168  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:45:31.168  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:31.168  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:45:31.168  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:31.168  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 added. We now have 2 listener(s)
08-26 19:45:31.169  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:31.170  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:31.173  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:31.195  1521  4035 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-26 19:45:31.195  1521  4035 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-26 19:45:31.195  1521  4035 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 19:45:31.195  1521  4035 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:45:31.197  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:31.197  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.197  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.197  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:31.197  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:31.197  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:31.197  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:31.197  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:31.210  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:31.210  3971  4021 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:31.212  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:45:31.214  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:45:31.214  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 19:45:31.215  3971  4021 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 19:45:31.215  3971  4021 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-26 19:45:31.215  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:31.216  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:45:31.216  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:31.216  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:31.216  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:31.217  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.217  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.217  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.217  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:31.217  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:31.217  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 19:45:31.217  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 removed from the list
08-26 19:45:31.217  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.217  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 removed from the list
,08-26 19:45:31.219  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:31.220  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:45:31.220  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.221  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.221  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:31.222  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.222  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.222  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.222  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.224  3971  4021 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
08-26 19:45:31.224  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.224  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.224  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.225  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:31.225  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.225  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.225  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.225  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.225  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.225  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.225  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.225  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.225  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.225  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:31.227  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:45:31.227  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.227  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.228  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
,08-26 19:45:31.230  1521  4035 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-26 19:45:31.230  1521  4035 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-26 19:45:31.230  1521  4035 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-26 19:45:31.233  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-26 19:45:31.234  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 19:45:31.235  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-26 19:45:31.235  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:45:31.235  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-26 19:45:31.235  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:45:31.235  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 19:45:31.235  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-26 19:45:31.235  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:45:31.235  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-26 19:45:31.235  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:45:31.235  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-26 19:45:31.236  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 19:45:31.236  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-26 19:45:31.236  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-26 19:45:31.236  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-26 19:45:31.236  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:45:31.236  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-26 19:45:31.237  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 19:45:31.237  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-26 19:45:31.237  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.237  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-26 19:45:31.237  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.237  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:31.237  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:31.237  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.237  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
,08-26 19:45:31.237  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.237  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
,08-26 19:45:31.238  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.238  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.238  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.238  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.238  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.239  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:45:31.239  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.239  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.239  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.240  3971  4021 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 19:45:31.242  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:31.247  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:31.247  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.247  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.247  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:31.247  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:31.247  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:31.247  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:31.247  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:31.248  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:31.248  3971  4021 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:31.249  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:31.250  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:31.250  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:31.250  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:31.250  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:31.250  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:31.251  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:31.254  3971  4021 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 19:45:31.254  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:45:31.258  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:45:31.259  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 19:45:31.259  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:45:31.260  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 19:45:31.262  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 19:45:31.262  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:45:31.262  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:45:31.263  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:45:31.263  3971  4021 D BluetoothAdapter: STATE_ON
08-26 19:45:31.266  2827  2838 D BtGatt.GattService: registerClient() - UUID=fc001360-53fb-4178-af95-4bf8ae98f648
08-26 19:45:31.267  2827  2852 D BtGatt.GattService: onClientRegistered() - UUID=fc001360-53fb-4178-af95-4bf8ae98f648, clientIf=5
,08-26 19:45:31.267  3971  4017 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 19:45:31.268  2827  2840 D BtGatt.GattService: start scan with filters
,08-26 19:45:31.270  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:45:31.270  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:45:31.270  2827  2856 D BtGatt.ScanManager: handling starting scan
08-26 19:45:31.271  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:45:31.271  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 19:45:31.271  2827  2856 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:31.273  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:31.273  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:45:31.273  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:31.274  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:45:31.277  3971  4021 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:45:31.277  2827  2852 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 19:45:31.277  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:31.278  2827  2856 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 19:45:31.279  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:31.279  3971  4021 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 19:45:31.279  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:45:31.279  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:45:31.279  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.279  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:31.279  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 19:45:31.279  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:31.279  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:31.280  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 19:45:31.280  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:31.281  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 19:45:31.281  3971  4021 D BluetoothAdapter: STATE_ON
08-26 19:45:31.282  2827  2852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 19:45:31.282  2827  2966 D BtGatt.GattService: stopScan() - queue size =1
,08-26 19:45:31.282  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.282  2827  2856 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:45:31.282  2827  2856 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 19:45:31.282  2827  2838 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-26 19:45:31.283  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:31.283  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 19:45:31.283  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:31.283  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:45:31.283  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 19:45:31.284  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:31.284  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 19:45:31.284  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:45:31.284  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:31.285  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:31.286  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:31.286  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:45:31.286  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:31.286  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.286  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:31.287  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:31.287  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.287  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.287  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.287  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop,
08-26 19:45:31.287  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.287  3971  4021 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 19:45:31.289  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:31.290  2827  2852 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 19:45:31.290  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:31.292  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:31.292  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.292  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.292  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:31.292  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:31.292  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:31.292  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:31.292  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:31.293  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:31.293  3971  4021 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:45:31.294  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:31.294  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:31.294  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-26 19:45:31.294  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:31.294  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:45:31.296  2827  2852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 19:45:31.297  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:31.298  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:31.299  3971  4021 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 19:45:31.299  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:45:31.301  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:31.302  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:45:31.303  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 19:45:31.303  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:45:31.303  2827  2852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 19:45:31.303  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.304  2827  2856 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:45:31.306  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:45:31.306  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:45:31.306  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:45:31.307  3971  4021 D BluetoothAdapter: STATE_ON
,08-26 19:45:31.308  2827  2840 D BtGatt.GattService: registerClient() - UUID=f37e5890-ae0b-4400-9bfc-f900ff4da184
,08-26 19:45:31.309  2827  2852 D BtGatt.GattService: onClientRegistered() - UUID=f37e5890-ae0b-4400-9bfc-f900ff4da184, clientIf=5
,08-26 19:45:31.309  3971  4017 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 19:45:31.309  2827  2966 D BtGatt.GattService: start scan with filters
,08-26 19:45:31.310  2827  2852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-26 19:45:31.310  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.310  2827  2856 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 19:45:31.313  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:45:31.313  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:45:31.313  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
08-26 19:45:31.313  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:45:31.315  2827  2852 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 19:45:31.315  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
,08-26 19:45:31.315  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:45:31.315  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:45:31.315  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:31.316  2827  2856 D BtGatt.ScanManager: handling starting scan
08-26 19:45:31.317  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:45:31.320  3971  4021 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:45:31.321  2827  2852 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 19:45:31.321  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:31.321  2827  2856 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 19:45:31.322  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.322  3971  4021 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 19:45:31.322  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.322  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 19:45:31.322  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.322  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:31.322  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:45:31.322  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:31.322  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 19:45:31.322  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:31.323  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:31.323  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:45:31.323  3971  4021 D BluetoothAdapter: STATE_ON
08-26 19:45:31.324  2827  2838 D BtGatt.GattService: stopScan() - queue size =1
08-26 19:45:31.324  2827  2840 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 19:45:31.325  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:45:31.325  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:45:31.325  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:31.325  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:45:31.325  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 19:45:31.326  2827  2852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 19:45:31.326  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.326  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:31.326  2827  2856 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:45:31.326  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:45:31.326  2827  2856 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 19:45:31.326  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:45:31.326  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:31.326  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:31.327  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:31.327  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.327  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.327  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:31.327  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:31.327  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:31.327  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.328  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.328  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.328  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:45:31.328  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.328  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:31.328  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.329  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.329  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.329  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:31.329  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.330  3971  4021 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 19:45:31.332  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:31.335  2827  2852 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 19:45:31.335  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.338  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:31.338  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.338  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.338  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:31.338  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:31.338  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:31.338  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:31.338  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:31.339  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:31.339  3971  4021 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:31.339  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:31.339  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only,
08-26 19:45:31.339  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:31.339  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:31.339  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:31.341  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 19:45:31.342  3971  4021 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 19:45:31.342  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:45:31.342  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:31.344  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:45:31.345  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 19:45:31.345  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:45:31.345  2827  2852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 19:45:31.345  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:31.347  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:45:31.347  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 19:45:31.347  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 19:45:31.347  3971  4021 D BluetoothAdapter: STATE_ON
08-26 19:45:31.349  2827  2840 D BtGatt.GattService: registerClient() - UUID=ab46c358-f198-447f-bcc8-7b8d6de550d0
08-26 19:45:31.349  2827  2852 D BtGatt.GattService: onClientRegistered() - UUID=ab46c358-f198-447f-bcc8-7b8d6de550d0, clientIf=5
,08-26 19:45:31.349  3971  3981 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 19:45:31.350  2827  2966 D BtGatt.GattService: start scan with filters
08-26 19:45:31.351  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-26 19:45:31.351  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 19:45:31.351  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:45:31.352  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:45:31.352  2827  2852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 19:45:31.352  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.352  2827  2856 D BtGatt.ScanManager: stopping BLe Batch
08-26 19:45:31.354  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:31.354  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:45:31.354  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:31.355  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:45:31.357  3971  4021 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:45:31.357  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.357  3971  4021 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 19:45:31.357  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.357  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-26 19:45:31.357  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:31.357  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:31.357  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:45:31.357  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 19:45:31.357  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:31.357  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 19:45:31.357  2827  2852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 19:45:31.357  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:31.357  2827  2856 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 19:45:31.357  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 19:45:31.358  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 19:45:31.358  3971  4021 D BluetoothAdapter: STATE_ON
08-26 19:45:31.358  2827  2838 D BtGatt.GattService: stopScan() - queue size =0,
08-26 19:45:31.359  2827  2840 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 19:45:31.359  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:45:31.359  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:45:31.359  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 19:45:31.359  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:45:31.359  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 19:45:31.360  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:31.360  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:45:31.360  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 19:45:31.360  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:31.360  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:31.361  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:31.361  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:31.361  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:31.361  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:31.361  3971  4021 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 19:45:31.361  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.361  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:45:31.361  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:31.361  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.361  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:31.361  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.361  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.361  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.361  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:45:31.362  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.362  2827  2852 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 19:45:31.362  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.362  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.364  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:31.364  2827  2856 D BtGatt.ScanManager: handling starting scan
08-26 19:45:31.364  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.364  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.364  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:31.364  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.365  3971  4021 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 19:45:31.365  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.365  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.365  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.365  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.365  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.365  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.365  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.365  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.365  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.365  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.366  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.366  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.366  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:31.366  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.366  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.366  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.366  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.367  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.368  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-26 19:45:31.368  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.368  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.368  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.368  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.368  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:31.368  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.368  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.368  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:31.368  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.368  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.368  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.368  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.368  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:31.368  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.369  2827  2852 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 19:45:31.369  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.369  2827  2856 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 19:45:31.369  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.369  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.369  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.369  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.370  3971  4021 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 19:45:31.370  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.370  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.370  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.370  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.370  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.370  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.370  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.370  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:31.370  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.370  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.370  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.370  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.370  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:31.370  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.371  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.371  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.371  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:31.371  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
,08-26 19:45:31.371  3971  4021 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 19:45:31.371  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.372  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.372  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:45:31.372  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:31.372  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.372  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:31.372  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.372  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.372  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.372  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.372  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.372  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.372  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.372  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.373  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.373  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.373  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.373  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.373  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:45:31.373  2827  2852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 19:45:31.373  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:45:31.373  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.373  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:45:31.374  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 19:45:31.374  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:45:31.374  2827  2856 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:45:31.374  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:45:31.374  2827  2856 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 19:45:31.374  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.374  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.374  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.374  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.374  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.374  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.374  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.374  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.374  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.374  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.374  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.374  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.374  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.374  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.376  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.376  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.376  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.376  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.376  3971  4021 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:31.376  3971  4021 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 19:45:31.377  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 19:45:31.379  3971  4021 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:31.379  3971  4021 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 19:45:31.379  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 19:45:31.380  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 19:45:31.381  3971  4021 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 19:45:31.381  3971  4021 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:45:31.381  3971  4021 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 19:45:31.381  3971  4021 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:31.381  3971  4021 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:45:31.381  3971  4021 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 19:45:31.381  3971  4021 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:31.381  3971  4021 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:45:31.381  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 19:45:31.385  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 19:45:31.385  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 19:45:31.386  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 19:45:31.386  2827  2852 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 19:45:31.386  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.386  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 19:45:31.386  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 19:45:31.386  3971  4021 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 19:45:31.387  3971  4021 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:31.387  3971  4045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 430)
08-26 19:45:31.387  3971  4021 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 19:45:31.387  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.387  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.387  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.387  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.387  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.387  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.388  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 19:45:31.388  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.388  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.388  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.388  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.388  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.388  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.388  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.388  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.389  3971  4045 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:31.389  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.389  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.389  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.389  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.390  3971  4021 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 19:45:31.390  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.390  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.390  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.390  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.390  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.390  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.391  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.391  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.391  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.391  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.391  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.391  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.391  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.391  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.391  2827  2852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 19:45:31.391  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.392  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.392  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.392  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.392  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.392  3971  4021 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 19:45:31.392  3971  4046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 430
08-26 19:45:31.392  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.392  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.392  3971  4046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 430)
08-26 19:45:31.393  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.393  2827  2951 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-26 19:45:31.393  3971  4045 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 430)
08-26 19:45:31.393  3971  4046 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 430)
08-26 19:45:31.393  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.393  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.393  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.394  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.394  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.394  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.394  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.394  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.394  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.394  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.394  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.395  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.395  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.395  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.395  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.395  3971  4021 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 19:45:31.395  3971  4021 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 19:45:31.395  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:45:31.395  3971  4021 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 19:45:31.395  3971  4021 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:45:31.395  3971  4021 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 19:45:31.396  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:45:31.396  3971  4021 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 19:45:31.396  3971  4021 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:45:31.396  3971  4021 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 19:45:31.396  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:45:31.396  3971  4021 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 19:45:31.396  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.396  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.396  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.396  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.396  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.396  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.396  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.396  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.396  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.396  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.397  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.397  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.397  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.397  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.397  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.397  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.397  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.397  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.398  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.398  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.398  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.398  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.398  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.398  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.398  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.398  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.398  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.398  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.398  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.398  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.398  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.398  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.398  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.398  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.399  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.399  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.399  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.399  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.399  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.399  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.399  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.399  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.399  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.399  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.399  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.399  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.399  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.400  2827  2852 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 19:45:31.400  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.400  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.400  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.400  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.400  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.401  3971  4021 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 19:45:31.401  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:31.401  2827  2856 D BtGatt.ScanManager: stopping BLe Batch
08-26 19:45:31.402  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 19:45:31.402  3971  4021 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 19:45:31.402  3971  4021 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 19:45:31.402  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 19:45:31.403  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:45:31.403  3971  3971 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 19:45:31.403  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.403  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 19:45:31.403  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 19:45:31.403  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 19:45:31.403  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.403  3971  4021 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 19:45:31.403  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.403  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.403  3971  3971 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 19:45:31.403  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:31.403  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:31.403  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:31.403  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.403  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.403  3971  4047 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 19:45:31.404  3971  4047 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 19:45:31.404  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:31.405  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:31.405  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:31.405  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:31.405  3971  3971 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 19:45:31.405  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.405  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.405  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.405  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.405  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.405  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.405  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.405  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.405  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.405  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.405  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.405  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.406  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.406  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.406  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.406  2827  2852 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 19:45:31.406  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.406  2827  2856 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 19:45:31.406  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.406  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.406  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.407  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.407  3971  4021 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 19:45:31.408  3971  4021 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:45:31.408  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:45:31.408  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:31.408  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.408  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.408  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.409  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.409  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.409  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.409  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.409  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.409  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.409  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.409  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.409  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.409  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.409  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.411  2827  2852 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 19:45:31.411  2827  2852 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:31.410  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.412  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.412  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.412  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.412  1521  4035 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-26 19:45:31.412  1521  4035 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-26 19:45:31.412  1521  4035 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 19:45:31.412  1521  4035 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-26 19:45:31.414  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.414  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.414  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.414  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.414  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.414  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.414  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.414  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.415  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.415  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.415  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.415  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.415  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.415  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.415  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.415  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.415  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.415  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.416  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:31.416  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:31.416  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:31.416  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:31.416  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.416  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.416  3971  4021 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e621206 not in the list
08-26 19:45:31.416  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.416  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.416  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:31.416  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.416  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.417  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:31.417  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:31.417  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:31.417  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:31.417  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:31.417  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e3b0c7 not in the list
08-26 19:45:31.418  3971  4021 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 19:45:31.418  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:45:31.418  3971  4021 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 19:45:31.418  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:45:31.418  3971  4021 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 19:45:31.418  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:45:31.420  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:45:31.420  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 19:45:31.420  3971  4021 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-26 19:45:31.420  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 19:45:31.420  3971  4021 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 19:45:31.420  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 19:45:31.420  3971  4021 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 19:45:31.420  3971  4021 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 19:45:31.421  3971  4021 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 19:45:31.421  3971  4021 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 19:45:31.421  3971  4021 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 19:45:31.421  3971  4021 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 19:45:31.421  3971  4021 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 19:45:31.422  3971  4021 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 19:45:31.422  1521  4035 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-26 19:45:31.422  1521  4035 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-26 19:45:31.422  1521  4035 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-26 19:45:31.423  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:31.423  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d9d2851 added. We now have 2 listener(s)
,08-26 19:45:31.423  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:31.424  3971  4021 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 19:45:31.424   873  1709 D WifiService: setWifiEnabled: true pid=3971, uid=10000
08-26 19:45:31.424   873  1709 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:45:31.425  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:31.425  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd908b6 added. We now have 3 listener(s)
08-26 19:45:31.425  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:31.428  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:31.429  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8d459b7 added. We now have 4 listener(s),
,08-26 19:45:31.429  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:31.430  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:31.430  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4a2524 added. We now have 5 listener(s)
08-26 19:45:31.430  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:31.431   873  1709 D WifiService: setWifiEnabled: false pid=3971, uid=10000
08-26 19:45:31.431   873  1709 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:45:31.434  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:31.435  2827  2848 D BluetoothAdapterState: Current state: ON, message: 23
08-26 19:45:31.435  2827  2848 D BluetoothAdapterProperties: Setting state to 13
08-26 19:45:31.435  2827  2848 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 19:45:31.435  2827  2848 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 19:45:31.436  2827  2848 I BluetoothAdapterState: Entering PendingCommandState
08-26 19:45:31.437  2827  2827 D BluetoothMapService: onReceive
08-26 19:45:31.437  2827  2827 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:31.437  2827  2827 D BluetoothMapService: STATE_TURNING_OFF
08-26 19:45:31.437  2827  2827 D BluetoothMapService: MAP Service closeService in
08-26 19:45:31.437  2827  2827 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 19:45:31.437  2827  2827 D ObexServerSockets0: shutdown(block = true)
08-26 19:45:31.437  2827  2827 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 19:45:31.438  2827  2974 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 19:45:31.438  2827  2827 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 19:45:31.438  2827  2951 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 19:45:31.438  2827  2975 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-26 19:45:31.438  2827  2827 I BtOppRfcommListener: stopping Accept Thread
08-26 19:45:31.439  2827  3613 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:31.439  2827  3613 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 19:45:31.439  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:45:31.440   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 19:45:31.440   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-26 19:45:31.440   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 19:45:31.440  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.440   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:45:31.440  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:31.440  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.440  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.440  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:31.440  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:31.440  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:31.440  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:31.440  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active, network type is Wi-Fi: true
08-26 19:45:31.441  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:31.441  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:31.441  3971  4021 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:31.446  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:31.448  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:31.449   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:31.449   873  1887 D DhcpClient: Clearing IP address
08-26 19:45:31.450  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.450  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:31.450  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.450  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.450  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:31.450  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:31.450  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:31.450  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:31.450  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:31.451   371   871 D CommandListener: Setting iface cfg
08-26 19:45:31.451  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.451  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:31.451  1521  2461 V NativeCrypto: Read error: ssl=0x9b1d0e00: I/O error during system call, Connection timed out
08-26 19:45:31.452  1521  2461 V NativeCrypto: SSL shutdown failed: ssl=0x9b1d0e00: I/O error during system call, Broken pipe
08-26 19:45:31.453  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:31.454   873   884 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-26 19:45:31.455   873  1883 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-26 19:45:31.456   873  1883 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-26 19:45:31.456   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-26 19:45:31.457   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-26 19:45:31.457   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 19:45:31.458   873   886 I ActivityManager: Start proc 4050:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-26 19:45:31.460  2827  2852 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:31.460  2827  2848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 19:45:31.461   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
08-26 19:45:31.462   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 19:45:31.464   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:31.465   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100], EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 19:45:31.465   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-26 19:45:31.466   479   479 E Parcel  : Reading a NULL string not supported here.
08-26 19:45:31.467  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.467  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:31.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:31.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:31.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:31.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:31.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:31.468  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.468  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:31.470  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.471  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:31.471  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.471  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.471  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:31.471  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:31.471  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:31.471  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:31.471  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:31.471  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.471  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:31.471  2827  2827 D HeadsetService: Received stop request...Stopping profile...
08-26 19:45:31.472   873  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 19:45:31.474  1372  1392 D BluetoothHeadset: Proxy object disconnected
,08-26 19:45:31.474   873   873 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:31.474   873   873 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:31.474  1931  2215 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:31.474   873   873 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:31.474  1372  1372 D HeadsetProfile: Bluetooth service disconnected
08-26 19:45:31.475  2827  2827 D A2dpService: Received stop request...Stopping profile...
08-26 19:45:31.475  2827  2969 D A2dpStateMachine: Exit Disconnected: -1
08-26 19:45:31.477  1521  4035 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/172.217.21.106 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,08-26 19:45:31.478   873   873 D BluetoothA2dp: Proxy object disconnected
08-26 19:45:31.478   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 19:45:31.478  2827  2827 D HidService: Received stop request...Stopping profile...
08-26 19:45:31.479  2827  2827 D HidService: Stopping Bluetooth HidService
08-26 19:45:31.483   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:45:31.484  2827  2827 V BluetoothAdapterState: isTurningOff()=true
08-26 19:45:31.484  2827  2827 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:31.484  2827  2827 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:45:31.484  2827  2827 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:31.485  2139  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:31.485  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.485  2827  2827 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 19:45:31.485  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:31.485  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.485  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.485  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:31.485  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:31.485  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:31.485  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:31.485  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:31.485  2827  2827 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:45:31.486  2827  2852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-26 19:45:31.486  2827  2935 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:31.486  2827  2935 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:31.486  2827  2935 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:31.486  2827  2852 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-26 19:45:31.486  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.486  2827  2827 D HealthService: Received stop request...Stopping profile...
08-26 19:45:31.486  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:31.487  2827  2827 D PanService: Received stop request...Stopping profile...
,08-26 19:45:31.488  2827  2827 V BluetoothAdapterState: isTurningOff()=true
08-26 19:45:31.488  2827  2827 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:31.488  2827  2827 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:31.488  2827  2827 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:31.488  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.488  2827  2827 D BluetoothMapService: Received stop request...Stopping profile...
08-26 19:45:31.488  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:31.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:31.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:31.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:31.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:31.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:31.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:31.488  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:31.488  2827  2827 D BluetoothMapService: stop()
,08-26 19:45:31.489  2827  2827 D BluetoothMapAppObserver: deinitObservers()
08-26 19:45:31.489  2827  2827 D BluetoothMapAppObserver: removeReceiver()
08-26 19:45:31.489  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:31.489  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:31.493  2827  2827 V BluetoothAdapterState: isTurningOff()=true
08-26 19:45:31.493  2827  2827 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:31.493  2827  2827 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:31.493  2827  2827 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:31.493  2827  2827 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:45:31.493  2827  2827 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 19:45:31.493   873  1889 D DhcpClient: Receive thread stopped
08-26 19:45:31.493  2827  2827 V BluetoothAdapterState: isTurningOff()=true
08-26 19:45:31.493  2827  2827 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:31.493  2827  2827 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:31.493  2827  2827 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:31.494  2827  2827 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 19:45:31.494  2827  2852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 19:45:31.494  2827  2852 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 19:45:31.494  2827  2852 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 19:45:31.494  2827  2935 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-26 19:45:31.494  2827  2935 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:31.495  2827  2935 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:31.495  2827  2935 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:31.495  2827  2935 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:31.495  2827  2935 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:31.495  2827  2827 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:45:31.495  2827  2827 V BluetoothAdapterState: isTurningOff()=true
08-26 19:45:31.495  2827  2827 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:31.495  2827  2827 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:45:31.495  2827  2827 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:31.496  2827  2827 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:45:31.497  2827  2827 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 19:45:31.497  2827  2827 D BluetoothMapService: MAP Service closeService in
08-26 19:45:31.497  2827  2827 V BluetoothAdapterState: isTurningOff()=true
08-26 19:45:31.497  2827  2827 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:31.497  2827  2827 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:31.498  2827  2827 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:31.498  2827  2848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-26 19:45:31.498  2827  2848 D BluetoothAdapterProperties: Setting state to 15
08-26 19:45:31.498  2827  2848 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-26 19:45:31.498  1372  2028 D BluetoothPan: onBluetoothStateChange on: false
08-26 19:45:31.499  2827  2848 I BluetoothAdapterState: Entering BleOnState
08-26 19:45:31.499  1372  1388 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 19:45:31.500   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:31.500  1372  1392 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:45:31.501  1372  2000 D BluetoothMap: onBluetoothStateChange: up=false
08-26 19:45:31.501  1372  2028 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 19:45:31.501   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:31.501   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:31.501   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:45:31.502  1372  1388 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:31.502  1931  1948 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:31.502  2827  2848 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 19:45:31.502  2827  2848 D BluetoothAdapterProperties: Setting state to 16
08-26 19:45:31.502  2827  2848 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 19:45:31.503  2827  2848 D BluetoothAdapterProperties: onBleDisable
,08-26 19:45:31.503  2827  2848 I BluetoothAdapterState: Entering PendingCommandState
08-26 19:45:31.503  2827  2849 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-26 19:45:31.503  2827  2827 D BluetoothMapService: cleanup()
08-26 19:45:31.504  2827  2827 D BluetoothMapService: MAP Service closeService in
08-26 19:45:31.504  2827  2935 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 19:45:31.504  2827  2935 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:31.506  2827  2852 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:31.509  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:31.509  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:31.512  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:31.512  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:31.523   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:45:31.537  4050  4050 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-26 19:45:31.539   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:45:31.540   873  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-26 19:45:31.540   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:31.541   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:45:31.544  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:31.545  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:31.545  3557  3557 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@13ed4b6 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,08-26 19:45:31.555  4050  4050 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:31.558   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec63598:true
,08-26 19:45:31.560  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:31.572   873  1709 I ActivityManager: Start proc 4071:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-26 19:45:31.577  4050  4050 D LocalBluetoothProfileManager: Adding local MAP profile
,08-26 19:45:31.580  4050  4050 D BluetoothMap: Create BluetoothMap proxy object
,08-26 19:45:31.582   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-26 19:45:31.583   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 19:45:31.586  4050  4050 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-26 19:45:31.597  4050  4050 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:31.601   873   883 I ActivityManager: Killing 3557:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-26 19:45:31.616  4071  4071 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-26 19:45:31.706  2827  2852 I bt_hci  : shut_down
,08-26 19:45:31.718  2827  2857 D bt_hwcfg: hw_epilog_process
08-26 19:45:31.718  2827  2857 I bt_vendor: low_power_mode_cb
,08-26 19:45:31.743  2827  2857 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 19:45:31.743  2827  2857 I bt_vendor: epilog_cb
08-26 19:45:31.743  2827  2857 I bt_hci  : epilog_finished_callback
,08-26 19:45:31.748  2827  2852 I bt_hci_h4: hal_close
,08-26 19:45:31.750  2827  2852 I bt_userial_vendor: device fd = 51 close
,08-26 19:45:31.832  4071  4071 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:45:31.832  4071  4071 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:45:31.832  4071  4071 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:45:31.832  4071  4071 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 19:45:31.832  4071  4071 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream,.java:290)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.k.d(PG:583)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:31.832  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 19:45:31.833  4071  4071 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
0,8-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 19:45:31.833  4071  4071 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at java.io.File.exists(File.java:361)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 19:45:31.833  4071  4071 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:31.833  4071  4071 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 19:45:31.862   873  1729 I ActivityManager: Start proc 4101:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-26 19:45:31.863   873  1729 I ActivityManager: Killing 3441:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-26 19:45:31.905  3971  3971 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:45:31.928  2827  2849 D bt_stack_manager: event_shut_down_stack finished.
,08-26 19:45:31.929  2827  2848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 19:45:31.934  2827  2848 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-26 19:45:31.934  2827  2827 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 19:45:31.935  2827  2827 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 19:45:31.935  2827  2827 D BtGatt.GattService: stop()
08-26 19:45:31.935  2827  2827 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 19:45:31.937  2827  2827 V BluetoothAdapterState: isTurningOff()=false
08-26 19:45:31.937  2827  2827 V BluetoothAdapterState: isTurningOn()=false
,08-26 19:45:31.937  2827  2827 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:31.937  2827  2827 V BluetoothAdapterState: isBleTurningOff()=true
08-26 19:45:31.937  2827  2848 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 19:45:31.937  2827  2848 D BluetoothAdapterProperties: Setting state to 10
08-26 19:45:31.937  2827  2848 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 19:45:31.937  2827  2848 I BluetoothAdapterState: Entering OffState
,08-26 19:45:31.940   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-26 19:45:31.948  2827  2827 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 19:45:31.948  2827  2827 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 19:45:31.948  2827  2827 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 19:45:31.948  2827  2849 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 19:45:31.952  2827  2849 D bt_stack_manager: event_clean_up_stack finished.
,08-26 19:45:31.960  2827  2827 I art     : System.exit called, status: 0
,08-26 19:45:31.960  2827  2827 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 19:45:31.978  4101  4101 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-26 19:45:32.028   873   884 I ActivityManager: Process com.android.bluetooth (pid 2827) has died
,08-26 19:45:32.196  4101  4120 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 19:45:32.196  4101  4120 I Babel_SMS: MmsConfig.loadMmsSettings
08-26 19:45:32.197  4101  4120 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-26 19:45:32.200  4101  4120 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 19:45:32.247  4101  4120 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-26 19:45:32.247  4101  4120 I Babel_SMS: MmsConfig.loadFromResources
,08-26 19:45:32.250  4101  4120 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 19:45:32.250  4101  4120 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-26 19:45:32.283  4101  4101 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:45:32.287  4101  4101 I Babel_Crash: startup - clean
,08-26 19:45:32.318  4101  4101 I Babel_telephony: TeleModule.launchCompleted
,08-26 19:45:32.325   873  3315 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-26 19:45:32.341  4101  4101 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-26 19:45:32.349  4101  4101 W Babel   : BAM#gBA: invalid account id: -1
,08-26 19:45:32.349  4101  4101 W Babel   : BAM#gBA: invalid account id: -1
08-26 19:45:32.349  4101  4101 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-26 19:45:32.358   873  2271 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-26 19:45:32.362  4101  4125 I Babel   : deleted: false for 0
,08-26 19:45:32.394  4050  4050 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:32.456   873  3315 I ActivityManager: Start proc 4130:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-26 19:45:32.464  4050  4050 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:32.523  4101  4101 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:45:32.622  4130  4130 D AdapterServiceConfig: Adding HeadsetService
,08-26 19:45:32.622  4130  4130 D AdapterServiceConfig: Adding A2dpService
,08-26 19:45:32.622  4130  4130 D AdapterServiceConfig: Adding HidService
08-26 19:45:32.622  4130  4130 D AdapterServiceConfig: Adding HealthService
,08-26 19:45:32.622  4130  4130 D AdapterServiceConfig: Adding PanService
,08-26 19:45:32.623  4130  4130 D AdapterServiceConfig: Adding GattService
08-26 19:45:32.623  4130  4130 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 19:45:32.637  4101  4101 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 19:45:32.642  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:32.648  4101  4101 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:45:32.657  4101  4101 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:45:32.667  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 19:45:32.670  4101  4101 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 19:45:32.677  1731  1731 D SystemUpdateService: onCreate
,08-26 19:45:32.684  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 19:45:32.690  1731  4143 I SystemUpdateService: active receiver: enabled
,08-26 19:45:32.693  4101  4101 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 19:45:32.697   873  1709 I ActivityManager: Killing 3302:android.process.acore/u0a5 (adj 15): empty #17
,08-26 19:45:32.698  1731  4143 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 19:45:32.699  1731  4143 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 19:45:32.699  1731  4143 I SystemUpdateService: now status is 0 (complete)
,08-26 19:45:32.699  1731  4143 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 19:45:32.699  1731  4143 I SystemUpdateService: file has been verified
,08-26 19:45:32.700  1731  4143 I SystemUpdateService: OTA package size = 12249756
,08-26 19:45:32.702  1731  4143 I SystemUpdateService: showing system update notification
,08-26 19:45:32.782  4071  4097 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 19:45:32.811   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff1a33c:true
,08-26 19:45:32.831  4101  4101 I vclib   : onServiceConnected
,08-26 19:45:32.841  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 19:45:32.842  1731  2425 I iu.UploadsManager: num queued entries: 0
08-26 19:45:32.843  1731  2425 I iu.UploadsManager: num updated entries: 0
,08-26 19:45:32.845  1731  2425 I iu.SyncManager: NEXT; no task
,08-26 19:45:32.849  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-26 19:45:32.850  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 19:45:32.865   873  3437 I ActivityManager: Start proc 4145:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-26 19:45:32.868  1731  1731 D SystemUpdateService: onDestroy
,08-26 19:45:32.897  4145  4145 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-26 19:45:32.899  4145  4145 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:32.903  4145  4145 D SprintDMHelper: simOperator: 
,08-26 19:45:32.904  4145  4145 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 19:45:32.922   873  3439 I ActivityManager: Start proc 4157:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-26 19:45:32.923   873  3439 I ActivityManager: Killing 3808:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-26 19:45:33.088   873  3439 I ActivityManager: Start proc 4172:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-26 19:45:33.092  4101  4171 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 19:45:33.096   873  1729 I ActivityManager: Killing 3825:com.android.musicfx/u0a18 (adj 15): empty #17
,08-26 19:45:33.151  4172  4172 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-26 19:45:33.213  4172  4172 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 19:45:33.213  4172  4172 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 19:45:33.213  4172  4172 I GAv4    :   adb logcat -s GAv4
,08-26 19:45:33.232  4172  4172 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:45:33.241  4172  4172 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:45:33.270  4172  4190 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 19:45:33.378  4172  4172 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-26 19:45:33.424  4172  4172 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-26 19:45:33.437  4172  4172 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4916-4919)
,08-26 19:45:33.437  4172  4172 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 19:45:33.446  4172  4172 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a83d766}
,08-26 19:45:33.447  4172  4172 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 19:45:33.447  4172  4172 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 19:45:33.460  4172  4172 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 19:45:33.463  4172  4172 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 19:45:33.482  4172  4172 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-26 19:45:33.498  4172  4172 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 19:45:33.498  4172  4172 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-26 19:45:33.498  4172  4172 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 19:45:33.498  4172  4172 I Adreno  : Build Date                       : 10/20/15
08-26 19:45:33.498  4172  4172 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 19:45:33.498  4172  4172 I Adreno  : Local Branch                     : M14
08-26 19:45:33.498  4172  4172 I Adreno  : Remote Branch                    : 
08-26 19:45:33.498  4172  4172 I Adreno  : Remote Branch                    : 
08-26 19:45:33.498  4172  4172 I Adreno  : Reconstruct Branch               : 
,08-26 19:45:33.558  4172  4172 I NSApplication: Starting up...
,08-26 19:45:33.569  4172  4218 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 19:45:33.605   873  2271 I ActivityManager: Start proc 4223:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-26 19:45:33.607   873  2271 I ActivityManager: Killing 2245:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-26 19:45:33.688  4223  4223 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-26 19:45:33.889   873  3241 I ActivityManager: Killing 3853:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-26 19:45:34.443   873  1709 D WifiService: setWifiEnabled: true pid=3971, uid=10000
,08-26 19:45:34.444   873  1709 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:45:34.459   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-26 19:45:34.466  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:34.467  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:34.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:34.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:34.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:34.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:34.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:34.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:34.467  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:34.467  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:34.467  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:34.470  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:34.470  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:34.470  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:34.470  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:34.470  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:34.470  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:34.470  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:34.470  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:34.470  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:34.471  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:34.471  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:34.485   873  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-26 19:45:34.487   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 19:45:34.488   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 19:45:34.490   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 19:45:34.490   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-26 19:45:34.490   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-26 19:45:34.490   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 19:45:34.514   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-26 19:45:34.518   371   871 D CommandListener: Setting iface cfg
,08-26 19:45:34.519   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
,08-26 19:45:34.520   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 19:45:34.519   873  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.75 rxSuccessRate=14.00 delta 1000 -> 994
08-26 19:45:34.525   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 19:45:34.526   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 19:45:34.530   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-26 19:45:34.530   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:34.538   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 19:45:34.582   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 19:45:34.584  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 19:45:35.010  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 19:45:35.057  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 19:45:35.057  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 19:45:35.066   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 19:45:35.078   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 19:45:35.078   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:35.078   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 19:45:35.100   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:35.111   371   871 D CommandListener: Setting iface cfg
,08-26 19:45:35.112   873  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,08-26 19:45:35.126   873  1317 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-26 19:45:35.128   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 19:45:35.153   873  4248 D DhcpClient: Receive thread started
,08-26 19:45:35.238   873  1315 E native  : do suspend false
,08-26 19:45:35.258   873  1887 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 19:45:35.272   873  4248 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,08-26 19:45:35.273   873  1887 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,08-26 19:45:35.277   873  1887 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 19:45:35.292   873  4248 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 19:45:35.293   873  1887 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 19:45:35.299   371   871 D CommandListener: Setting iface cfg
,08-26 19:45:35.310   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 19:45:35.312   873  1887 D DhcpClient: Scheduling renewal in 86399s
,08-26 19:45:35.330   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 19:45:35.333   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
08-26 19:45:35.333   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 19:45:35.335   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 19:45:35.338   873  1317 D ConnectivityService: Adding iface wlan0 to network 101
,08-26 19:45:35.353   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 19:45:35.396   873  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 19:45:35.397   873  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-26 19:45:35.399   873  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-26 19:45:35.401   873  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-26 19:45:35.403   873  1317 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-26 19:45:35.418   873  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 19:45:35.423   873  1317 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-26 19:45:35.423   873  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-26 19:45:35.423   873  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-26 19:45:35.423   873  1317 D ConnectivityService:    accepting network in place of null
,08-26 19:45:35.423   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 19:45:35.425   873  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-26 19:45:35.425   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 19:45:35.439   873  4247 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136925, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 19:45:35.471   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:45:35.505   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:45:35.515   873  4246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.18.14,2a00:1450:4001:816::200e
,08-26 19:45:35.516   873  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 19:45:35.517   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:35.526   873  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-26 19:45:35.527   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:45:35.552  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.552  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:35.552  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.552  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:35.552  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:35.552  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:35.552  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.552  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:35.552  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:35.552  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:35.552  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:35.555  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:35.556  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:35.556  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.556  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:35.556  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:35.556  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:35.556  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.556  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:35.556  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:35.556  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.556  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:35.563  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 19:45:35.566  1731  1731 D SystemUpdateService: onCreate
,08-26 19:45:35.571  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-26 19:45:35.574  1731  4257 I SystemUpdateService: active receiver: enabled
,08-26 19:45:35.580  1731  4257 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 19:45:35.584  1731  4257 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-26 19:45:35.585  1731  4257 I SystemUpdateService: now status is 0 (complete)
08-26 19:45:35.585  1731  4257 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 19:45:35.585  1731  4257 I SystemUpdateService: file has been verified
,08-26 19:45:35.585  1731  4257 I SystemUpdateService: OTA package size = 12249756
,08-26 19:45:35.588  1731  4257 I SystemUpdateService: showing system update notification
,08-26 19:45:35.595   873  4246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 17:45:35 GMT], X-Android-Received-Millis=[1472233535594], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472233535562]}
,08-26 19:45:35.596   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 19:45:35.597   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-26 19:45:35.597   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 19:45:35.598   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 19:45:35.599  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 19:45:35.608  1731  4260 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 19:45:35.608  1731  4260 W BaseAppContext: Using Auth Proxy for data requests.
08-26 19:45:35.608  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-26 19:45:35.609  1731  4260 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 19:45:35.610  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 19:45:35.614  1731  1731 D SystemUpdateService: onDestroy
,08-26 19:45:35.615  4145  4145 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:35.609  1731  2425 I iu.UploadsManager: num queued entries: 0
,08-26 19:45:35.618  4145  4145 D SprintDMHelper: simOperator: 
,08-26 19:45:35.618  4145  4145 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 19:45:35.622  1731  2425 I iu.UploadsManager: num updated entries: 0
,08-26 19:45:35.623  1731  2425 I iu.SyncManager: NEXT; no task
,08-26 19:45:35.654  1521  3036 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 19:45:35.654  1521  3036 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 19:45:35.654  1521  3036 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:45:35.654  1521  3036 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:45:35.670  1731  4260 E MDM     : [180] SitrepService.a: Error sending sitrep.
,08-26 19:45:35.763  4101  4263 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 19:45:36.515   873  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-26 19:45:37.453   873  1709 D WifiService: setWifiEnabled: false pid=3971, uid=10000
,08-26 19:45:37.453   873  1709 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:45:37.491  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 19:45:37.498   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 19:45:37.499   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-26 19:45:37.499   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-26 19:45:37.500   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:37.529   873  1887 D DhcpClient: Clearing IP address
,08-26 19:45:37.530   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-26 19:45:37.536   371   871 D CommandListener: Setting iface cfg
,08-26 19:45:37.540  1521  4268 V NativeCrypto: Read error: ssl=0x9b1d0e00: I/O error during system call, Connection timed out
,08-26 19:45:37.544  1521  4268 V NativeCrypto: SSL shutdown failed: ssl=0x9b1d0e00: I/O error during system call, Broken pipe
,08-26 19:45:37.552   873  4248 D DhcpClient: Receive thread stopped
,08-26 19:45:37.554   873  3439 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-26 19:45:37.555   873  4246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-26 19:45:37.561   873  4246 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-26 19:45:37.561   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-26 19:45:37.561   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-26 19:45:37.563   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 19:45:37.564   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 19:45:37.564   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
08-26 19:45:37.568   479   479 E Parcel  : Reading a NULL string not supported here.
08-26 19:45:37.570   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-26 19:45:37.571   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 19:45:37.574   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:37.577   873  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 19:45:37.581   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 19:45:37.583  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:37.583  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:37.583  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:37.583  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:37.583  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:37.583  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:37.583  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:37.583  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:37.583  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:37.584  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:37.584  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:37.584  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:37.585  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:37.585  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:37.585  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:37.585  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:37.585  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:37.585  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:37.585  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:37.585  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:37.585  2139  2326 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:37.585  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:37.585  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:37.591   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 19:45:37.615   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:45:37.640   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:45:37.641   873  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-26 19:45:37.641   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:37.643   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:45:37.646  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:37.647  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:37.651  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 19:45:37.653  1731  1731 D SystemUpdateService: onCreate
,08-26 19:45:37.655  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 19:45:37.657  1731  4279 I SystemUpdateService: active receiver: enabled
,08-26 19:45:37.659  1731  4279 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 19:45:37.661  1731  4279 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-26 19:45:37.661  1731  4279 I SystemUpdateService: now status is 0 (complete)
,08-26 19:45:37.661  1731  4279 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-26 19:45:37.662  1731  4279 I SystemUpdateService: file has been verified
08-26 19:45:37.662  1731  4279 I SystemUpdateService: OTA package size = 12249756
08-26 19:45:37.663  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 19:45:37.664  1731  4279 I SystemUpdateService: showing system update notification
,08-26 19:45:37.668  1731  2425 I iu.UploadsManager: num queued entries: 0
,08-26 19:45:37.670  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-26 19:45:37.671  1731  2425 I iu.UploadsManager: num updated entries: 0
,08-26 19:45:37.671  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 19:45:37.673  4145  4145 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:37.674  1731  2425 I iu.SyncManager: NEXT; no task
,08-26 19:45:37.676  4145  4145 D SprintDMHelper: simOperator: 
,08-26 19:45:37.676  4145  4145 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 19:45:37.684  1731  1731 D SystemUpdateService: onDestroy
,08-26 19:45:37.694   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-26 19:45:37.695   873  1317 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-26 19:45:37.695   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-26 19:45:37.696  4101  4284 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-26 19:45:37.869   873  1709 I ActivityManager: Killing 3717:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-26 19:45:40.493   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8869930:true
,08-26 19:45:40.497  4130  4130 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 19:45:40.505  4130  4287 I BluetoothAdapterState: Entering OffState
,08-26 19:45:40.505  4130  4130 I bt_bluedroid: init
,08-26 19:45:40.511  4130  4288 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 19:45:40.512  4130  4288 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 19:45:40.512  4130  4288 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 19:45:40.512  4130  4288 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 19:45:40.514  4130  4130 I bt_bluedroid: get_profile_interface socket
,08-26 19:45:40.519  4130  4291 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 19:45:40.520  4130  4130 I bt_bluedroid: get_profile_interface sdp
,08-26 19:45:40.521  4130  4291 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 19:45:40.527  4130  4142 I bt_bluedroid: config_hci_snoop_log
,08-26 19:45:40.530   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 19:45:40.539  4130  4287 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 19:45:40.539  4130  4287 D BluetoothAdapterProperties: Setting state to 14
08-26 19:45:40.539  4130  4287 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 19:45:40.544  4130  4287 D BluetoothBondStateMachine: make
,08-26 19:45:40.548  4130  4292 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 19:45:40.556  4130  4287 I BluetoothAdapterState: Entering PendingCommandState
,08-26 19:45:40.557  4130  4130 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 19:45:40.560  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc,
,08-26 19:45:40.561  4130  4130 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 19:45:40.562  4130  4130 D BtGatt.GattService: Received start request. Starting profile...
,08-26 19:45:40.562  4130  4130 D BtGatt.GattService: start()
,08-26 19:45:40.562  4130  4130 I bt_bluedroid: get_profile_interface gatt
08-26 19:45:40.563  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:40.563  4130  4130 D BtGatt.AdvertiseManager: advertise manager created
,08-26 19:45:40.572  4130  4130 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:45:40.572  4130  4130 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:40.572  4130  4130 V BluetoothAdapterState: isBleTurningOn()=true
,08-26 19:45:40.572  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:40.573  4130  4287 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 19:45:40.574  4130  4287 I bt_bluedroid: enable
08-26 19:45:40.574  4130  4288 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-26 19:45:40.575  4130  4288 I bt_hci  : start_up
,08-26 19:45:40.594  4130  4288 I bt_vendor: alloc value 0xb3939189
,08-26 19:45:40.594  4130  4288 I bt_vendor: init
08-26 19:45:40.594  4130  4288 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-26 19:45:40.595  4130  4288 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 19:45:40.702  4130  4288 D bt_hci  : start_up starting async portion
,08-26 19:45:40.702  4130  4295 I bt_hci  : event_finish_startup
08-26 19:45:40.702  4130  4295 I bt_hci_h4: hal_open
08-26 19:45:40.703  4130  4295 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 19:45:40.712  4130  4295 I bt_userial_vendor: device fd = 51 open
,08-26 19:45:40.744  4130  4295 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 19:45:40.776  4130  4295 D bt_hwcfg: Chipset BCM4354A2
,08-26 19:45:40.776  4130  4295 D bt_hwcfg: Target name = [BCM4354A2]
08-26 19:45:40.777  4130  4295 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 19:45:41.474  4130  4295 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 19:45:41.476  4130  4295 D bt_hwcfg: Settlement delay -- 100 ms
08-26 19:45:41.476  4130  4295 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 19:45:41.593  4130  4295 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 19:45:41.594  4130  4295 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 19:45:41.623  4130  4295 I bt_hwcfg: vendor lib fwcfg completed
,08-26 19:45:41.624  4130  4295 I bt_vendor: firmware callback
08-26 19:45:41.624  4130  4295 I bt_hci  : firmware_config_callback
,08-26 19:45:41.635  4130  4297 I bt_btu  : btu_task pending for preload complete event
,08-26 19:45:41.635  4130  4297 I bt_btu_task: Bluetooth chip preload is complete
08-26 19:45:41.636  4130  4297 I bt_btu  : btu_task received preload complete event
,08-26 19:45:41.646  4130  4297 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 19:45:41.647  4130  4297 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 19:45:41.647  4130  4297 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 19:45:41.648  4130  4297 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 19:45:41.648  4130  4297 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 19:45:41.648  4130  4297 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 19:45:41.649  4130  4297 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-26 19:45:41.649  4130  4297 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 19:45:41.650  4130  4297 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 19:45:41.651  4130  4297 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 19:45:41.652  4130  4297 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 19:45:41.652  4130  4297 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 19:45:41.653  4130  4297 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 19:45:41.653  4130  4297 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 19:45:41.654  4130  4297 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 19:45:41.787  4130  4297 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb38b6d9d
,08-26 19:45:41.788  4130  4297 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb38b6d9d 
,08-26 19:45:41.799  4130  4291 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 19:45:41.800  4130  4291 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 19:45:41.801  4130  4291 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 19:45:41.804  4130  4291 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 19:45:41.810  4130  4291 D BluetoothAdapterProperties: Scan Mode:20
,08-26 19:45:41.811  4130  4291 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:45:41.812  4130  4291 D bt_hci  : do_postload posting postload work item
08-26 19:45:41.812  4130  4295 I bt_hci  : event_postload
08-26 19:45:41.812  4130  4295 I bt_vendor: sco_config_cb
08-26 19:45:41.812  4130  4295 I bt_hci  : sco_config_callback postload finished.
,08-26 19:45:41.815  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:41.817  4130  4291 D bt_bte_conf: Device ID record 1 : primary
08-26 19:45:41.817  4130  4291 D bt_bte_conf:   vendorId            = 000f
08-26 19:45:41.818  4130  4291 D bt_bte_conf:   vendorIdSource      = 0001
08-26 19:45:41.818  4130  4291 D bt_bte_conf:   product             = 1200
,08-26 19:45:41.818  4130  4291 D bt_bte_conf:   version             = 1436
08-26 19:45:41.818  4130  4291 D bt_bte_conf:   clientExecutableURL = 
08-26 19:45:41.818  4130  4291 D bt_bte_conf:   serviceDescription  = 
08-26 19:45:41.819  4130  4291 D bt_bte_conf:   documentationURL    = 
08-26 19:45:41.819  4130  4291 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 19:45:41.819  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:41.820  4130  4288 D bt_stack_manager: event_start_up_stack finished
,08-26 19:45:41.821  4130  4287 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 19:45:41.822  4130  4287 D BluetoothAdapterProperties: Setting state to 15
08-26 19:45:41.822  4130  4287 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 19:45:41.823  4130  4287 I BluetoothAdapterState: Entering BleOnState
08-26 19:45:41.826  4130  4295 I bt_vendor: low_power_mode_cb
,08-26 19:45:41.830  4130  4287 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 19:45:41.831  4130  4287 D BluetoothAdapterProperties: Setting state to 11
08-26 19:45:41.831  4130  4287 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-26 19:45:41.836  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
08-26 19:45:41.838  4130  4130 D HeadsetService: Received start request. Starting profile...
08-26 19:45:41.841  4130  4130 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 19:45:41.841  4130  4130 D HeadsetStateMachine: make
,08-26 19:45:41.845  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:41.850  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:41.858  4130  4130 D HeadsetStateMachine: max_hf_connections = 1
08-26 19:45:41.858  4130  4130 I bt_bluedroid: get_profile_interface handsfree
,08-26 19:45:41.859  4130  4291 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 19:45:41.859  4130  4291 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-26 19:45:41.872  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:41.873  4130  4287 I BluetoothAdapterState: Entering PendingCommandState
,08-26 19:45:41.874  4130  4130 D A2dpService: Received start request. Starting profile...
08-26 19:45:41.875  4130  4130 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 19:45:41.875  4130  4130 I bt_bluedroid: get_profile_interface avrcp
,08-26 19:45:41.884  4130  4130 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 19:45:41.884  4130  4130 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:45:41.884  4130  4130 D A2dpStateMachine: make
,08-26 19:45:41.886  4130  4130 I bt_bluedroid: get_profile_interface a2dp
08-26 19:45:41.886  4130  4291 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 19:45:41.892  4130  4130 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 19:45:41.894  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:41.895  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:41.896  4130  4306 D A2dpStateMachine: Enter Disconnected: -2
,08-26 19:45:41.896  4130  4130 V BluetoothAdapterState: isTurningOff()=false
08-26 19:45:41.897  4130  4130 V BluetoothAdapterState: isTurningOn()=true
08-26 19:45:41.897  4050  4050 D BluetoothInputDevice: Proxy object connected
08-26 19:45:41.897  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:41.897  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:45:41.897  4050  4050 D HidProfile: Bluetooth service connected
,08-26 19:45:41.901  4130  4130 D HidService: Received start request. Starting profile...
,08-26 19:45:41.902  4130  4130 I bt_bluedroid: get_profile_interface hidhost
08-26 19:45:41.902  4130  4291 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb38983e5
,08-26 19:45:41.903  4130  4291 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-26 19:45:41.903  4130  4130 D HidService: setHidService(): set to: null
,08-26 19:45:41.904  4130  4303 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 19:45:41.906  4130  4130 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 19:45:41.908  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:41.909  4130  4130 D HealthService: Received start request. Starting profile...
,08-26 19:45:41.912  4130  4130 I bt_bluedroid: get_profile_interface health
,08-26 19:45:41.912  4130  4130 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 19:45:41.913  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:41.914  4130  4130 D PanService: Received start request. Starting profile...
,08-26 19:45:41.914  4050  4050 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:45:41.915  4130  4130 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-26 19:45:41.915  4130  4130 I bt_bluedroid: get_profile_interface pan
,08-26 19:45:41.916  4130  4291 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 19:45:41.916  4050  4050 D PanProfile: Bluetooth service connected
08-26 19:45:41.918  4130  4130 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:41.919  4130  4130 D BluetoothMapService: Received start request. Starting profile...
,08-26 19:45:41.919  4130  4130 D BluetoothMapService: start()
,08-26 19:45:41.920  4050  4050 D BluetoothMap: Proxy object connected
08-26 19:45:41.920  4050  4050 D MapProfile: Bluetooth service connected
,08-26 19:45:41.920  4050  4050 D BluetoothMap: getConnectedDevices()
08-26 19:45:41.921  4050  4050 D BluetoothMap: Bluetooth is Not enabled
08-26 19:45:41.922  4130  4130 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER,
08-26 19:45:41.922  4130  4130 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 19:45:41.923  4130  4130 D BluetoothMapAppObserver: createReceiver()
,08-26 19:45:41.924  4130  4130 D BluetoothMapAppObserver: initObservers()
,08-26 19:45:41.924  4130  4130 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 19:45:41.930  4130  4130 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:45:41.930  4130  4130 V BluetoothAdapterState: isTurningOn()=true
08-26 19:45:41.930  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:45:41.930  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:45:41.932  4130  4130 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:45:41.932  4130  4130 V BluetoothAdapterState: isTurningOn()=true
,08-26 19:45:41.932  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:45:41.932  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:45:41.932  4130  4130 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:45:41.932  4130  4130 V BluetoothAdapterState: isTurningOn()=true
08-26 19:45:41.933  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:45:41.933  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:41.933  4130  4130 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:45:41.933  4130  4130 V BluetoothAdapterState: isTurningOn()=true
08-26 19:45:41.933  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:45:41.933  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:45:41.933  4130  4130 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:45:41.933  4130  4130 V BluetoothAdapterState: isTurningOn()=true
08-26 19:45:41.933  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:45:41.934  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:45:41.934  4130  4287 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-26 19:45:41.934  4130  4287 D BluetoothAdapterProperties: ScanMode =  20
08-26 19:45:41.934  4130  4287 D BluetoothAdapterProperties: State =  11
08-26 19:45:41.936  4130  4287 D BluetoothAdapterProperties: Setting state to 12
08-26 19:45:41.936  4130  4287 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 19:45:41.937  4130  4287 I BluetoothAdapterState: Entering OnState
08-26 19:45:41.938  4050  4061 D BluetoothMap: onBluetoothStateChange: up=true
08-26 19:45:41.938  1372  2000 D BluetoothPan: onBluetoothStateChange on: true
08-26 19:45:41.939  4130  4291 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:45:41.939  4130  4291 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:45:41.940  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:45:41.940  1372  1372 D PanProfile: Bluetooth service connected
08-26 19:45:41.941  1372  2028 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:45:41.942   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:41.943  1372  2000 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:45:41.945  4050  4063 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:45:41.945  1372  1372 D BluetoothA2dp: Proxy object connected
08-26 19:45:41.947  1372  1388 D BluetoothMap: onBluetoothStateChange: up=true
08-26 19:45:41.949  1372  2000 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 19:45:41.949  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:41.949  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:41.949  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:41.949  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:41.949  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:41.949  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:41.949  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:41.949  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:41.949  1372  1372 D BluetoothMap: Proxy object connected
08-26 19:45:41.949  1372  1372 D MapProfile: Bluetooth service connected
08-26 19:45:41.949  1372  1372 D BluetoothMap: getConnectedDevices()
08-26 19:45:41.951  4050  4061 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 19:45:41.952   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:41.951  4130  4130 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 19:45:41.952  4050  4063 D BluetoothPan: onBluetoothStateChange on: true
08-26 19:45:41.952  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:41.952   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:41.952   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:45:41.953  4130  4130 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-26 19:45:41.953   873   873 D BluetoothA2dp: Proxy object connected
08-26 19:45:41.955  4130  4130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:41.955  1372  1372 D BluetoothInputDevice: Proxy object connected
08-26 19:45:41.955  1372  1372 D HidProfile: Bluetooth service connected
08-26 19:45:41.956  1372  1388 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:41.957  1931  1946 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:41.957  4130  4130 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:41.958  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:41.958  3971  3971 V io.jxcore.nod,e.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:41.958  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:41.958  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:41.958  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:41.958  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:41.958  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:41.958  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:41.960  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:41.962  4130  4130 D ObexServerSockets: Succeed to create listening sockets 
08-26 19:45:41.962  4130  4130 D ObexServerSockets0: startAccept()
08-26 19:45:41.962   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-26 19:45:41.963  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:41.963  4130  4130 D ObexServerSockets0: prepareForNewConnect()
08-26 19:45:41.964  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:41.965  4050  4050 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 19:45:41.969  4130  4130 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-26 19:45:41.969  4130  4130 D BluetoothSdpJni: SDP Create record success - handle: 0
08-26 19:45:41.969  4130  4130 D BluetoothMapService: onReceive
08-26 19:45:41.969  4130  4130 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:41.969  4130  4130 D BluetoothMapService: STATE_ON
08-26 19:45:41.970  4050  4050 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 19:45:41.971  4130  4313 D ObexServerSockets0: Accepting socket connection...
08-26 19:45:41.971  4130  4314 D ObexServerSockets0: Accepting socket connection...
,08-26 19:45:41.978  4050  4050 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:41.982  4050  4050 D BluetoothA2dp: Proxy object connected
,08-26 19:45:41.986  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:41.990  4050  4050 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:41.994  1372  1372 D BluetoothPbap: Proxy object connected
,08-26 19:45:41.994  4050  4050 D BluetoothPbap: Proxy object connected
08-26 19:45:41.994  1372  1372 D PbapServerProfile: Bluetooth service connected
08-26 19:45:41.994  4050  4050 D PbapServerProfile: Bluetooth service connected
,08-26 19:45:41.999  4130  4130 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 19:45:41.999  4130  4130 D ObexServerSockets0: prepareForNewConnect()
,08-26 19:45:42.003  4130  4318 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:45:42.017  4130  4322 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:45:42.018  4130  4322 I BtOppRfcommListener: Accept thread started.
,08-26 19:45:42.044  1372  2028 D BluetoothHeadset: Proxy object connected
,08-26 19:45:42.044  1372  1372 D HeadsetProfile: Bluetooth service connected
08-26 19:45:42.044   873   873 D BluetoothHeadset: Proxy object connected
08-26 19:45:42.044   873   873 D BluetoothHeadset: Proxy object connected
08-26 19:45:42.045  1931  1948 D BluetoothHeadset: Proxy object connected
,08-26 19:45:42.045   873   873 D BluetoothHeadset: Proxy object connected
,08-26 19:45:42.052   873   890 D BluetoothHeadset: Proxy object connected
,08-26 19:45:42.053   873   890 D BluetoothHeadset: Proxy object connected
,08-26 19:45:42.057  1372  1392 D BluetoothHeadset: Proxy object connected
,08-26 19:45:42.057  1372  1372 D HeadsetProfile: Bluetooth service connected
08-26 19:45:42.058  1931  2215 D BluetoothHeadset: Proxy object connected
,08-26 19:45:42.075  4050  4063 D BluetoothHeadset: Proxy object connected
,08-26 19:45:42.076  4050  4050 D HeadsetProfile: Bluetooth service connected
,08-26 19:45:43.429   873  1317 D ConnectivityService: handlePromptUnvalidated 101
,08-26 19:45:43.473  4130  4287 D BluetoothAdapterState: Current state: ON, message: 23
08-26 19:45:43.474  4130  4287 D BluetoothAdapterProperties: Setting state to 13
,08-26 19:45:43.475  4130  4287 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 19:45:43.476  4130  4287 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 19:45:43.480  4130  4291 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:43.480  4130  4287 I BluetoothAdapterState: Entering PendingCommandState
08-26 19:45:43.480  4130  4287 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-26 19:45:43.486  4130  4130 D HeadsetService: Received stop request...Stopping profile...
,08-26 19:45:43.490  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:43.490  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:43.490  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:43.490  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:43.490  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:43.490  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:43.490  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:43.490  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:43.490  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:43.490  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:43.490  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:43.493  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 19:45:43.493  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:43.493  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:43.493  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:43.493  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:43.493  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:43.493  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:43.493  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:43.493  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:43.495  1372  2000 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:43.495  1372  1372 D HeadsetProfile: Bluetooth service disconnected
08-26 19:45:43.496  3971  3971 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:43.496  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:43.497  4050  4061 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:43.497  4130  4130 V BluetoothAdapterState: isTurningOff()=true
08-26 19:45:43.497   873   873 D BluetoothHeadset: Proxy object disconnected
,08-26 19:45:43.497   873   873 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:43.497  4130  4130 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:43.497  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:43.497  4050  4050 D HeadsetProfile: Bluetooth service disconnected
08-26 19:45:43.497  1931  2215 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:43.497  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:43.498   873   873 D BluetoothHeadset: Proxy object disconnected
,08-26 19:45:43.499  4130  4130 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 19:45:43.499  4130  4291 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-26 19:45:43.500  4130  4130 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object,
08-26 19:45:43.500  4130  4297 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:43.500  4130  4297 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:43.500  4130  4297 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:43.501  4130  4291 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
08-26 19:45:43.501  4130  4130 D A2dpService: Received stop request...Stopping profile...
08-26 19:45:43.501  4130  4306 D A2dpStateMachine: Exit Disconnected: -1
,08-26 19:45:43.503  1372  1372 D BluetoothA2dp: Proxy object disconnected
08-26 19:45:43.503   873   873 D BluetoothA2dp: Proxy object disconnected
08-26 19:45:43.504  4130  4130 V BluetoothAdapterState: isTurningOff()=true
08-26 19:45:43.504  4130  4130 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:43.504  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:43.504  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:45:43.505  4130  4130 D HidService: Received stop request...Stopping profile...
08-26 19:45:43.505  4130  4130 D HidService: Stopping Bluetooth HidService
08-26 19:45:43.506  4050  4050 D BluetoothA2dp: Proxy object disconnected
,08-26 19:45:43.506  1372  1372 D BluetoothInputDevice: Proxy object disconnected
08-26 19:45:43.506  1372  1372 D HidProfile: Bluetooth service disconnected
,08-26 19:45:43.506  4050  4050 D BluetoothInputDevice: Proxy object disconnected
08-26 19:45:43.506  4050  4050 D HidProfile: Bluetooth service disconnected
,08-26 19:45:43.507  4130  4291 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-26 19:45:43.507  4130  4297 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:43.508  4130  4297 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:43.508  4130  4297 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
08-26 19:45:43.508  4130  4297 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:43.508  4130  4297 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 19:45:43.508  4130  4297 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 19:45:43.510  4130  4130 D HealthService: Received stop request...Stopping profile...
,08-26 19:45:43.511  4130  4130 V BluetoothAdapterState: isTurningOff()=true
,08-26 19:45:43.511  4130  4130 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:43.511  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:43.511  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:43.511  4130  4130 D PanService: Received stop request...Stopping profile...
,08-26 19:45:43.513  1372  1372 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 19:45:43.513  1372  1372 D PanProfile: Bluetooth service disconnected
08-26 19:45:43.514  4050  4050 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 19:45:43.514  4050  4050 D PanProfile: Bluetooth service disconnected
,08-26 19:45:43.514  4130  4130 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-26 19:45:43.514  4130  4291 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-26 19:45:43.514  4130  4130 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-26 19:45:43.516  4130  4130 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 19:45:43.516  4130  4130 D BluetoothMapService: stop()
,08-26 19:45:43.517  4130  4130 D BluetoothMapAppObserver: deinitObservers()
08-26 19:45:43.517  4130  4130 D BluetoothMapAppObserver: removeReceiver()
,08-26 19:45:43.518  1372  1372 D BluetoothMap: Proxy object disconnected
,08-26 19:45:43.518  1372  1372 D MapProfile: Bluetooth service disconnected
,08-26 19:45:43.518  4130  4130 V BluetoothAdapterState: isTurningOff()=true
08-26 19:45:43.518  4130  4130 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:43.518  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:45:43.518  4050  4050 D BluetoothMap: Proxy object disconnected
08-26 19:45:43.518  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:43.519  4130  4130 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 19:45:43.519  4130  4291 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-26 19:45:43.518  4050  4050 D MapProfile: Bluetooth service disconnected
08-26 19:45:43.519  4130  4130 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 19:45:43.519  4130  4130 V BluetoothAdapterState: isTurningOff()=true
,08-26 19:45:43.519  4130  4130 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:43.520  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:43.520  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:43.520  4130  4130 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:45:43.520  4130  4130 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 19:45:43.521  4130  4130 D BluetoothMapService: MAP Service closeService in
,08-26 19:45:43.521  4130  4130 D BluetoothMapMasInstance0: MAP Service shutdown
08-26 19:45:43.521  4130  4130 D ObexServerSockets0: shutdown(block = true)
08-26 19:45:43.521  4130  4313 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-26 19:45:43.522  4130  4130 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 19:45:43.523  4130  4130 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-26 19:45:43.523  4130  4299 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-26 19:45:43.523  4130  4314 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-26 19:45:43.524  4130  4130 V BluetoothAdapterState: isTurningOff()=true
08-26 19:45:43.524  4130  4130 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:43.524  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:43.524  4130  4130 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:43.524  4130  4287 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-26 19:45:43.524  4130  4287 D BluetoothAdapterProperties: Setting state to 15
08-26 19:45:43.524  4130  4287 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,08-26 19:45:43.525  4130  4287 I BluetoothAdapterState: Entering BleOnState
08-26 19:45:43.525  4130  4130 D BluetoothMapService: cleanup()
08-26 19:45:43.525  4130  4130 D BluetoothMapService: MAP Service closeService in
08-26 19:45:43.528  4130  4130 I BtOppRfcommListener: stopping Accept Thread
08-26 19:45:43.528  4130  4322 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:43.528  4130  4322 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 19:45:43.529  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:43.531  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:43.531  4050  4063 D BluetoothMap: onBluetoothStateChange: up=false
08-26 19:45:43.532  1372  2000 D BluetoothPan: onBluetoothStateChange on: false
08-26 19:45:43.532  4050  4050 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 19:45:43.533  1372  2028 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 19:45:43.533   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:43.534  1372  1388 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:45:43.535  4050  4061 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 19:45:43.537  1372  1392 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 19:45:43.539  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:45:43.540  1372  2000 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 19:45:43.544  4050  4063 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 19:45:43.547   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:43.547  4050  4050 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:43.547  4050  4061 D BluetoothPan: onBluetoothStateChange on: false
,08-26 19:45:43.549   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:43.549  4050  4063 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 19:45:43.549   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:45:43.549  4050  4326 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 19:45:43.550  1372  2028 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:43.550  1931  2213 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:43.550  4130  4287 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-26 19:45:43.551  4130  4287 D BluetoothAdapterProperties: Setting state to 16
08-26 19:45:43.551  4130  4287 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-26 19:45:43.551  4130  4287 D BluetoothAdapterProperties: onBleDisable
08-26 19:45:43.551  4130  4287 I BluetoothAdapterState: Entering PendingCommandState
08-26 19:45:43.551  4130  4288 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-26 19:45:43.553  4130  4297 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 19:45:43.553  4130  4297 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-26 19:45:43.555  4130  4291 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:43.556  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:43.558  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:43.559  4050  4050 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:43.560  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:43.561  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:43.565  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:45:43.569  4050  4050 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:43.754  4130  4291 I bt_hci  : shut_down
,08-26 19:45:43.754  4130  4295 D bt_hwcfg: hw_epilog_process
,08-26 19:45:43.755  4130  4295 I bt_vendor: low_power_mode_cb
,08-26 19:45:43.779  4130  4295 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-26 19:45:43.780  4130  4295 I bt_vendor: epilog_cb
08-26 19:45:43.780  4130  4295 I bt_hci  : epilog_finished_callback
,08-26 19:45:43.790  4130  4291 I bt_hci_h4: hal_close
,08-26 19:45:43.792  4130  4291 I bt_userial_vendor: device fd = 51 close
,08-26 19:45:43.912  4130  4288 D bt_stack_manager: event_shut_down_stack finished.
,08-26 19:45:43.914  4130  4287 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-26 19:45:43.920  4130  4130 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 19:45:43.921  4130  4287 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-26 19:45:43.922  4130  4130 D BtGatt.GattService: Received stop request...Stopping profile...
,08-26 19:45:43.922  4130  4130 D BtGatt.GattService: stop()
08-26 19:45:43.923  4130  4130 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 19:45:43.927  4130  4130 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:45:43.928  4130  4130 V BluetoothAdapterState: isTurningOn()=false
,08-26 19:45:43.928  4130  4130 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:43.928  4130  4130 V BluetoothAdapterState: isBleTurningOff()=true
08-26 19:45:43.929  4130  4287 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-26 19:45:43.930  4130  4287 D BluetoothAdapterProperties: Setting state to 10
,08-26 19:45:43.930  4130  4287 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-26 19:45:43.931  4130  4287 I BluetoothAdapterState: Entering OffState
08-26 19:45:43.934   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 19:45:43.964  4130  4130 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-26 19:45:43.964  4130  4130 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-26 19:45:43.965  4130  4288 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-26 19:45:43.972  4130  4288 D bt_stack_manager: event_clean_up_stack finished.
,08-26 19:45:43.974  4130  4130 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 19:45:43.977  4130  4130 I art     : System.exit called, status: 0
,08-26 19:45:43.977  4130  4130 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 19:45:44.038   873  3315 I ActivityManager: Process com.android.bluetooth (pid 4130) has died
,08-26 19:45:46.470  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:45:46.470  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:49.478  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:49.478  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@564fa42 added. We now have 6 listener(s)
08-26 19:45:49.479  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:49.485  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:49.485  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14ada53 added. We now have 7 listener(s)
,08-26 19:45:49.485  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:49.490  3971  4021 I System.out: IsBluetoothEnabled
,08-26 19:45:49.502  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:49.557   873   890 I ActivityManager: Start proc 4334:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-26 19:45:49.685  4334  4334 D AdapterServiceConfig: Adding HeadsetService
,08-26 19:45:49.685  4334  4334 D AdapterServiceConfig: Adding A2dpService
08-26 19:45:49.685  4334  4334 D AdapterServiceConfig: Adding HidService
08-26 19:45:49.686  4334  4334 D AdapterServiceConfig: Adding HealthService
08-26 19:45:49.686  4334  4334 D AdapterServiceConfig: Adding PanService
,08-26 19:45:49.686  4334  4334 D AdapterServiceConfig: Adding GattService
08-26 19:45:49.686  4334  4334 D AdapterServiceConfig: Adding BluetoothMapService
,08-26 19:45:49.702  4334  4334 D BluetoothAdapterState: make() - Creating AdapterState
,08-26 19:45:49.702   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a23c16d:true
,08-26 19:45:49.708  4334  4334 I bt_bluedroid: init
,08-26 19:45:49.709  4334  4346 I BluetoothAdapterState: Entering OffState
,08-26 19:45:49.714  4334  4347 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 19:45:49.715  4334  4347 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 19:45:49.715  4334  4347 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 19:45:49.716  4334  4347 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 19:45:49.718  4334  4334 I bt_bluedroid: get_profile_interface socket
,08-26 19:45:49.720  4334  4334 I bt_bluedroid: get_profile_interface sdp
,08-26 19:45:49.727  4334  4350 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-26 19:45:49.728  4334  4345 I bt_bluedroid: config_hci_snoop_log
,08-26 19:45:49.731  4334  4350 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 19:45:49.734   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 19:45:49.745  4334  4346 D BluetoothAdapterState: Current state: OFF, message: 0
,08-26 19:45:49.746  4334  4346 D BluetoothAdapterProperties: Setting state to 14
,08-26 19:45:49.747  4334  4346 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-26 19:45:49.752  4334  4346 D BluetoothBondStateMachine: make
,08-26 19:45:49.758  4334  4351 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 19:45:49.767  4334  4346 I BluetoothAdapterState: Entering PendingCommandState
,08-26 19:45:49.769  4334  4334 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-26 19:45:49.778  4334  4334 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:49.780  4334  4334 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 19:45:49.782  4334  4334 D BtGatt.GattService: Received start request. Starting profile...
,08-26 19:45:49.784  4334  4334 D BtGatt.GattService: start()
,08-26 19:45:49.784  4334  4334 I bt_bluedroid: get_profile_interface gatt
08-26 19:45:49.785  4334  4334 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
08-26 19:45:49.786  4334  4334 D BtGatt.AdvertiseManager: advertise manager created
,08-26 19:45:49.819  4334  4334 V BluetoothAdapterState: isTurningOff()=false
08-26 19:45:49.819  4334  4334 V BluetoothAdapterState: isTurningOn()=false
08-26 19:45:49.819  4334  4334 V BluetoothAdapterState: isBleTurningOn()=true
08-26 19:45:49.820  4334  4334 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:49.820  4334  4346 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-26 19:45:49.821  4334  4346 I bt_bluedroid: enable
08-26 19:45:49.821  4334  4347 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-26 19:45:49.822  4334  4347 I bt_hci  : start_up
,08-26 19:45:49.831  4334  4347 I bt_vendor: alloc value 0xb39a9189
08-26 19:45:49.831  4334  4347 I bt_vendor: init
08-26 19:45:49.831  4334  4347 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-26 19:45:49.831  4334  4347 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-26 19:45:49.937  4334  4347 D bt_hci  : start_up starting async portion
08-26 19:45:49.937  4334  4354 I bt_hci  : event_finish_startup
08-26 19:45:49.938  4334  4354 I bt_hci_h4: hal_open
08-26 19:45:49.938  4334  4354 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-26 19:45:49.943  4334  4354 I bt_userial_vendor: device fd = 51 open
,08-26 19:45:49.980  4334  4354 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 19:45:50.012  4334  4354 D bt_hwcfg: Chipset BCM4354A2
,08-26 19:45:50.012  4334  4354 D bt_hwcfg: Target name = [BCM4354A2]
,08-26 19:45:50.014  4334  4354 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-26 19:45:50.081  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:45:50.097  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:45:50.102  1521  1521 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-26 19:45:50.174  1521  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-26 19:45:50.175  1521  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-26 19:45:50.175  1521  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-26 19:45:50.175  1521  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:45:50.225  3646  3646 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-26 19:45:50.226  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-26 19:45:50.227  3646  3646 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-26 19:45:50.678  4334  4354 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-26 19:45:50.679  4334  4354 D bt_hwcfg: Settlement delay -- 100 ms
08-26 19:45:50.679  4334  4354 I bt_hwcfg: Setting fw settlement delay to 100 
,08-26 19:45:50.796  4334  4354 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-26 19:45:50.798  4334  4354 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-26 19:45:50.827  4334  4354 I bt_hwcfg: vendor lib fwcfg completed
08-26 19:45:50.827  4334  4354 I bt_vendor: firmware callback
,08-26 19:45:50.827  4334  4354 I bt_hci  : firmware_config_callback
,08-26 19:45:50.839  4334  4356 I bt_btu  : btu_task pending for preload complete event
,08-26 19:45:50.839  4334  4356 I bt_btu_task: Bluetooth chip preload is complete
,08-26 19:45:50.839  4334  4356 I bt_btu  : btu_task received preload complete event
,08-26 19:45:50.852  4334  4356 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 19:45:50.852  4334  4356 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 19:45:50.852  4334  4356 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 19:45:50.853  4334  4356 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 19:45:50.853  4334  4356 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-26 19:45:50.853  4334  4356 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 19:45:50.854  4334  4356 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 19:45:50.854  4334  4356 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 19:45:50.854  4334  4356 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 19:45:50.854  4334  4356 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 19:45:50.855  4334  4356 I         : BTE_InitTraceLevels -- TRC_SDP
,08-26 19:45:50.855  4334  4356 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 19:45:50.855  4334  4356 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 19:45:50.855  4334  4356 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 19:45:50.856  4334  4356 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-26 19:45:50.995  4334  4356 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3926d9d
,08-26 19:45:50.995  4334  4356 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3926d9d 
,08-26 19:45:51.004  4334  4350 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-26 19:45:51.005  4334  4350 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-26 19:45:51.006  4334  4350 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-26 19:45:51.011  4334  4350 D BluetoothAdapterProperties: Name is: Nexus 6
,08-26 19:45:51.016  4334  4350 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:51.016  4334  4350 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 19:45:51.016  4334  4350 D bt_hci  : do_postload posting postload work item
08-26 19:45:51.017  4334  4354 I bt_hci  : event_postload
08-26 19:45:51.017  4334  4354 I bt_vendor: sco_config_cb
08-26 19:45:51.017  4334  4354 I bt_hci  : sco_config_callback postload finished.
08-26 19:45:51.021  4334  4350 D bt_bte_conf: Device ID record 1 : primary
,08-26 19:45:51.021  4334  4350 D bt_bte_conf:   vendorId            = 000f
08-26 19:45:51.021  4334  4350 D bt_bte_conf:   vendorIdSource      = 0001
08-26 19:45:51.022  4334  4350 D bt_bte_conf:   product             = 1200
08-26 19:45:51.022  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:51.022  4334  4350 D bt_bte_conf:   version             = 1436
,08-26 19:45:51.022  4334  4350 D bt_bte_conf:   clientExecutableURL = 
08-26 19:45:51.022  4334  4350 D bt_bte_conf:   serviceDescription  = 
,08-26 19:45:51.022  4334  4350 D bt_bte_conf:   documentationURL    = 
08-26 19:45:51.023  4334  4350 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-26 19:45:51.023  4334  4347 D bt_stack_manager: event_start_up_stack finished
08-26 19:45:51.024  4334  4354 I bt_vendor: low_power_mode_cb
08-26 19:45:51.024  4334  4346 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-26 19:45:51.025  4334  4346 D BluetoothAdapterProperties: Setting state to 15
,08-26 19:45:51.025  4334  4346 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-26 19:45:51.027  4334  4346 I BluetoothAdapterState: Entering BleOnState
08-26 19:45:51.034  4334  4346 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-26 19:45:51.034  4334  4346 D BluetoothAdapterProperties: Setting state to 11
08-26 19:45:51.034  4334  4346 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-26 19:45:51.043  4334  4334 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:51.046  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:51.046  4334  4334 D HeadsetService: Received start request. Starting profile...
08-26 19:45:51.052  4334  4334 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 19:45:51.052  4334  4334 D HeadsetStateMachine: make
,08-26 19:45:51.056  4334  4346 I BluetoothAdapterState: Entering PendingCommandState
,08-26 19:45:51.066  4334  4334 D HeadsetStateMachine: max_hf_connections = 1
,08-26 19:45:51.066  4334  4334 I bt_bluedroid: get_profile_interface handsfree
08-26 19:45:51.066  4334  4350 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-26 19:45:51.067  4334  4350 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-26 19:45:51.072  4334  4334 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:51.073  4334  4334 D A2dpService: Received start request. Starting profile...
,08-26 19:45:51.074  4334  4334 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 19:45:51.074  4334  4334 I bt_bluedroid: get_profile_interface avrcp
,08-26 19:45:51.081  4334  4334 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 19:45:51.081  4334  4334 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 19:45:51.081  4334  4334 D A2dpStateMachine: make
,08-26 19:45:51.083  4334  4334 I bt_bluedroid: get_profile_interface a2dp
,08-26 19:45:51.084  4334  4350 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-26 19:45:51.087  4334  4365 D A2dpStateMachine: Enter Disconnected: -2
,08-26 19:45:51.089  4334  4334 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 19:45:51.090  4334  4334 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:51.091  4334  4334 D HidService: Received start request. Starting profile...
08-26 19:45:51.091  4334  4334 I bt_bluedroid: get_profile_interface hidhost
,08-26 19:45:51.092  4334  4350 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39083e5
08-26 19:45:51.092  4334  4350 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-26 19:45:51.092  4334  4334 D HidService: setHidService(): set to: null
08-26 19:45:51.093  4334  4334 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 19:45:51.094  4334  4334 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
08-26 19:45:51.095  4334  4334 D HealthService: Received start request. Starting profile...
,08-26 19:45:51.097  4334  4334 I bt_bluedroid: get_profile_interface health
,08-26 19:45:51.097  4334  4334 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 19:45:51.099  4334  4334 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:51.099  4334  4334 D PanService: Received start request. Starting profile...
,08-26 19:45:51.100  4334  4334 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 19:45:51.100  4334  4334 I bt_bluedroid: get_profile_interface pan
08-26 19:45:51.101  4334  4350 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 19:45:51.108  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:51.108  4334  4334 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
08-26 19:45:51.109  4334  4334 D BluetoothMapService: Received start request. Starting profile...
08-26 19:45:51.109  4334  4334 D BluetoothMapService: start()
,08-26 19:45:51.113  4334  4334 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-26 19:45:51.115  4334  4334 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-26 19:45:51.115  4334  4334 D BluetoothMapAppObserver: createReceiver()
,08-26 19:45:51.116  4334  4334 D BluetoothMapAppObserver: initObservers()
,08-26 19:45:51.116  4334  4334 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-26 19:45:51.124  4334  4334 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:45:51.124  4334  4334 V BluetoothAdapterState: isTurningOn()=true
08-26 19:45:51.124  4334  4334 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:51.124  4334  4363 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 19:45:51.124  4334  4334 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:45:51.126  4334  4334 V BluetoothAdapterState: isTurningOff()=false
08-26 19:45:51.126  4334  4334 V BluetoothAdapterState: isTurningOn()=true
,08-26 19:45:51.126  4334  4334 V BluetoothAdapterState: isBleTurningOn()=false
,08-26 19:45:51.126  4334  4334 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:45:51.126  4334  4334 V BluetoothAdapterState: isTurningOff()=false
08-26 19:45:51.126  4334  4334 V BluetoothAdapterState: isTurningOn()=true
08-26 19:45:51.126  4334  4334 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:51.126  4334  4334 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:51.127  4334  4334 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:45:51.127  4334  4334 V BluetoothAdapterState: isTurningOn()=true
08-26 19:45:51.127  4334  4334 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:51.127  4334  4334 V BluetoothAdapterState: isBleTurningOff()=false
,08-26 19:45:51.127  4334  4334 V BluetoothAdapterState: isTurningOff()=false
08-26 19:45:51.127  4334  4334 V BluetoothAdapterState: isTurningOn()=true
,08-26 19:45:51.127  4334  4334 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:51.127  4334  4334 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:51.128  4334  4334 V BluetoothAdapterState: isTurningOff()=false
,08-26 19:45:51.128  4334  4334 V BluetoothAdapterState: isTurningOn()=true
08-26 19:45:51.128  4334  4334 V BluetoothAdapterState: isBleTurningOn()=false
08-26 19:45:51.128  4334  4334 V BluetoothAdapterState: isBleTurningOff()=false
08-26 19:45:51.128  4334  4346 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-26 19:45:51.129  4334  4346 D BluetoothAdapterProperties: ScanMode =  20
08-26 19:45:51.129  4334  4346 D BluetoothAdapterProperties: State =  11
,08-26 19:45:51.131  4334  4350 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:45:51.131  4334  4350 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:45:51.132  4334  4346 D BluetoothAdapterProperties: Setting state to 12
08-26 19:45:51.132  4334  4346 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 19:45:51.132  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:51.133  4050  4061 D BluetoothMap: onBluetoothStateChange: up=true
08-26 19:45:51.133  4334  4346 I BluetoothAdapterState: Entering OnState
,08-26 19:45:51.135  1372  1388 D BluetoothPan: onBluetoothStateChange on: true
08-26 19:45:51.136  4050  4050 D BluetoothMap: Proxy object connected
08-26 19:45:51.136  4050  4050 D MapProfile: Bluetooth service connected
08-26 19:45:51.137  4050  4050 D BluetoothMap: getConnectedDevices()
08-26 19:45:51.138  1372  2028 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:45:51.138  1372  1372 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:45:51.138  1372  1372 D PanProfile: Bluetooth service connected
,08-26 19:45:51.142   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:45:51.142  1372  1388 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:45:51.143  4334  4334 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-26 19:45:51.144  4334  4334 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-26 19:45:51.144  4050  4326 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:45:51.145  4334  4334 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:51.146  1372  2000 D BluetoothMap: onBluetoothStateChange: up=true
08-26 19:45:51.147  1372  1372 D BluetoothMap: Proxy object connected
08-26 19:45:51.147  1372  2028 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 19:45:51.147  1372  1372 D MapProfile: Bluetooth service connected
,08-26 19:45:51.147  1372  1372 D BluetoothMap: getConnectedDevices()
08-26 19:45:51.148  4334  4334 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:51.149  4050  4061 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 19:45:51.150  4334  4334 D ObexServerSockets: Succeed to create listening sockets 
08-26 19:45:51.150  4334  4334 D ObexServerSockets0: startAccept()
08-26 19:45:51.150  4334  4334 D ObexServerSockets0: prepareForNewConnect()
,08-26 19:45:51.152  4334  4334 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-26 19:45:51.152  4334  4334 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-26 19:45:51.153  4334  4370 D ObexServerSockets0: Accepting socket connection...
08-26 19:45:51.153   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:51.154  4050  4063 D BluetoothPan: onBluetoothStateChange on: true
,08-26 19:45:51.154  1372  1372 D BluetoothA2dp: Proxy object connected
08-26 19:45:51.154  4334  4371 D ObexServerSockets0: Accepting socket connection...
,08-26 19:45:51.156  1372  1372 D BluetoothInputDevice: Proxy object connected
08-26 19:45:51.156  1372  1372 D HidProfile: Bluetooth service connected
,08-26 19:45:51.158   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:45:51.158  4050  4326 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:45:51.160   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:45:51.161   873   873 D BluetoothA2dp: Proxy object connected
,08-26 19:45:51.162  4050  4063 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:45:51.162  1372  1392 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:51.163  1931  2085 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:45:51.164  4050  4050 D BluetoothInputDevice: Proxy object connected
,08-26 19:45:51.164  4050  4050 D HidProfile: Bluetooth service connected
,08-26 19:45:51.165   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 19:45:51.166  4334  4334 D BluetoothMapService: onReceive
08-26 19:45:51.166  4334  4334 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:51.166  4334  4334 D BluetoothMapService: STATE_ON
08-26 19:45:51.169  4050  4050 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:45:51.169  4050  4050 D PanProfile: Bluetooth service connected
08-26 19:45:51.169  4050  4050 D BluetoothA2dp: Proxy object connected
,08-26 19:45:51.171  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:51.171  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:51.171  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:51.171  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:51.171  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:51.171  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:51.171  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:51.171  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:51.173  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:51.175  4050  4050 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 19:45:51.184  1521  1521 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:51.185  4050  4050 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:51.195  4050  4050 D BluetoothPbap: Proxy object connected
,08-26 19:45:51.195  1372  1372 D BluetoothPbap: Proxy object connected
08-26 19:45:51.195  4050  4050 D PbapServerProfile: Bluetooth service connected
08-26 19:45:51.195  1372  1372 D PbapServerProfile: Bluetooth service connected
08-26 19:45:51.195  4334  4334 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-26 19:45:51.196  4334  4334 D ObexServerSockets0: prepareForNewConnect()
,08-26 19:45:51.207  4334  4376 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:45:51.228  4334  4380 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:45:51.229  4334  4380 I BtOppRfcommListener: Accept thread started.
,08-26 19:45:51.244  1372  2028 D BluetoothHeadset: Proxy object connected
,08-26 19:45:51.244  1372  1372 D HeadsetProfile: Bluetooth service connected
,08-26 19:45:51.245  4050  4061 D BluetoothHeadset: Proxy object connected
08-26 19:45:51.246   873   873 D BluetoothHeadset: Proxy object connected
,08-26 19:45:51.246   873   873 D BluetoothHeadset: Proxy object connected
08-26 19:45:51.246  1931  1946 D BluetoothHeadset: Proxy object connected
08-26 19:45:51.246   873   873 D BluetoothHeadset: Proxy object connected
08-26 19:45:51.247  4050  4050 D HeadsetProfile: Bluetooth service connected
,08-26 19:45:51.253   873   890 D BluetoothHeadset: Proxy object connected
,08-26 19:45:51.259   873   890 D BluetoothHeadset: Proxy object connected
,08-26 19:45:51.263  4050  4326 D BluetoothHeadset: Proxy object connected
,08-26 19:45:51.264  1372  1388 D BluetoothHeadset: Proxy object connected
08-26 19:45:51.264  1372  1372 D HeadsetProfile: Bluetooth service connected
08-26 19:45:51.264  1931  1948 D BluetoothHeadset: Proxy object connected
08-26 19:45:51.265  4050  4050 D HeadsetProfile: Bluetooth service connected
,08-26 19:45:51.525  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:51.525  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:51.525  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:51.525  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:51.525  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:51.525  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:51.525  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:51.525  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:51.533  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:51.537  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:51.538  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a966f90 added. We now have 8 listener(s)
,08-26 19:45:51.538  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:51.547   873  1402 D WifiService: setWifiEnabled: false pid=3971, uid=10000
,08-26 19:45:51.547   873  1402 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:45:51.560  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:51.561   873  2272 D WifiService: setWifiEnabled: true pid=3971, uid=10000
08-26 19:45:51.561   873  2272 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:45:51.574   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-26 19:45:51.575   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
08-26 19:45:51.589   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-26 19:45:51.589   873   893 I Adreno  : Build Date                       : 10/20/15
08-26 19:45:51.589   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-26 19:45:51.589   873   893 I Adreno  : Local Branch                     : M14
08-26 19:45:51.589   873   893 I Adreno  : Remote Branch                    : 
08-26 19:45:51.589   873   893 I Adreno  : Remote Branch                    : 
08-26 19:45:51.589   873   893 I Adreno  : Reconstruct Branch               : 
08-26 19:45:51.593  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:51.593  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:51.593  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:51.593  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:51.593  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:51.593  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:51.593  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:51.593  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:51.597  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:51.604  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-26 19:45:51.612   873  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-26 19:45:51.615   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-26 19:45:51.617   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-26 19:45:51.620   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-26 19:45:51.621   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-26 19:45:51.623   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-26 19:45:51.623   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-26 19:45:51.635   281   300 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (229 us)
,08-26 19:45:51.637   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-26 19:45:51.637   873  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.23 rxSuccessRate=0.27 delta 1000 -> 1000
08-26 19:45:51.638   371   871 D CommandListener: Setting iface cfg
08-26 19:45:51.638   873  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '154 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 154 Failed to set address (No such device)'
08-26 19:45:51.638   873  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 19:45:51.641   873  1314 D WifiNative-HAL: p2pGetDeviceAddress
,08-26 19:45:51.647   873  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-26 19:45:51.647   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-26 19:45:51.647   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:51.654   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-26 19:45:51.715   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-26 19:45:51.725  1469  1469 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-26 19:45:52.150  1469  1469 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-26 19:45:52.188  1469  1469 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-26 19:45:52.188  1469  1469 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-26 19:45:52.192  3971  3971 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 19:45:52.193  3971  3971 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 19:45:52.229   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-26 19:45:52.229   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 19:45:52.230  3971  3971 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@758b0b8 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@16b9089, 16908290=android.view.AbsSavedState$1@16b9089}, android:focusedViewId=100}]}]
08-26 19:45:52.230  3971  3971 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 19:45:52.231  3971  3971 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 19:45:52.231  3971  3971 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 19:45:52.239   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 19:45:52.240   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:45:52.240   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 19:45:52.240   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-26 19:45:52.243   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-26 19:45:52.243   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
08-26 19:45:52.243   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-26 19:45:52.256   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 19:45:52.267   371   871 D CommandListener: Setting iface cfg
,08-26 19:45:52.268   873  1315 D WifiStateMachine: Start Dhcp Watchdog 3
,08-26 19:45:52.279   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 19:45:52.279   873  1317 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 19:45:52.280   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-26 19:45:52.291   873  4390 D DhcpClient: Receive thread started
,08-26 19:45:52.372   873  1315 E native  : do suspend false
,08-26 19:45:52.394   873  1887 D DhcpClient: Broadcasting DHCPDISCOVER
,08-26 19:45:52.410   873  4390 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-26 19:45:52.411   873  1887 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-26 19:45:52.415   873  1887 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,08-26 19:45:52.427   873  4390 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-26 19:45:52.428   873  1887 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-26 19:45:52.434   371   871 D CommandListener: Setting iface cfg
,08-26 19:45:52.445   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-26 19:45:52.446   873  1887 D DhcpClient: Scheduling renewal in 86399s
,08-26 19:45:52.461   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-26 19:45:52.464   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 19:45:52.466   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-26 19:45:52.469   873  1317 D ConnectivityService: Adding iface wlan0 to network 102
,08-26 19:45:52.477   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-26 19:45:52.480   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
08-26 19:45:52.485   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 19:45:52.485   873  1340 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
,08-26 19:45:52.487   873   893 I DreamManagerService: Entering dreamland.
,08-26 19:45:52.488   873   893 I PowerManagerService: Dozing...
,08-26 19:45:52.490   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-26 19:45:52.526   873  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-26 19:45:52.526   873  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-26 19:45:52.527   873  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 19:45:52.528   873  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-26 19:45:52.529   873  1317 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-26 19:45:52.535   873  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 19:45:52.539   873  1317 D ConnectivityService: scheduleUnvalidatedPrompt 102
08-26 19:45:52.540   873  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-26 19:45:52.540   873  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-26 19:45:52.540   873  1317 D ConnectivityService:    accepting network in place of null
08-26 19:45:52.540   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-26 19:45:52.540   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-26 19:45:52.541   873  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-26 19:45:52.555   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-26 19:45:52.555   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-26 19:45:52.557   873  4389 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154044, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-26 19:45:52.558   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-26 19:45:52.564   873  1315 E native  : do suspend false
,08-26 19:45:52.569   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:45:52.572   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-26 19:45:52.576  1919  4398 D NfcService: Discovery configuration equal, not updating.
,08-26 19:45:52.579  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:52.579  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:52.579  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:52.579  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:52.579  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:52.579  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:52.579  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:52.579  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:52.582  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:52.586  3971  4021 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 19:45:52.586  3971  4021 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 19:45:52.588  3971  4021 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@758b0b8 Bundle[{}]
08-26 19:45:52.588  3971  4021 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 19:45:52.589  3971  4021 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 19:45:52.589  3971  4021 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 19:45:52.590  3971  4021 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 19:45:52.591  3971  4021 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 19:45:52.592   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
08-26 19:45:52.592  3971  4021 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 19:45:52.595   873  1315 E native  : do suspend true
,08-26 19:45:52.597  3971  4021 I System.out: Running OutgoingSocketThread
,08-26 19:45:52.599  3971  4401 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 460)
,08-26 19:45:52.600  3971  4401 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 38255
,08-26 19:45:52.600  3971  4401 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 19:45:52.604   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-26 19:45:52.606   873  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-26 19:45:52.606   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:52.607   873  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-26 19:45:52.616  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:52.616  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:52.616  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:52.616  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:52.616  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:52.616  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:52.616  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:52.616  3971  3971 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:52.618  3971  3971 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:52.621  1731  1731 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-26 19:45:52.627  1731  1731 D SystemUpdateService: onCreate
,08-26 19:45:52.630  1731  1731 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-26 19:45:52.639   873  4388 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:4001:805::200e
,08-26 19:45:52.645  1731  4403 I SystemUpdateService: active receiver: enabled
,08-26 19:45:52.651  1731  1731 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-26 19:45:52.659  1731  2425 I iu.UploadsManager: num queued entries: 0
,08-26 19:45:52.659  1731  2425 I iu.UploadsManager: num updated entries: 0
,08-26 19:45:52.660  1731  2425 I iu.SyncManager: NEXT; no task
,08-26 19:45:52.660  1731  4403 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-26 19:45:52.661  1731  1731 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-26 19:45:52.662  1731  1731 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-26 19:45:52.664  4145  4145 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:52.669  1731  4406 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-26 19:45:52.669  1731  4406 W BaseAppContext: Using Auth Proxy for data requests.
,08-26 19:45:52.671  4145  4145 D SprintDMHelper: simOperator: 
08-26 19:45:52.671  4145  4145 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-26 19:45:52.672  1731  4406 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,08-26 19:45:52.674  1731  4403 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-26 19:45:52.674  1731  4403 I SystemUpdateService: now status is 0 (complete)
08-26 19:45:52.674  1731  4403 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-26 19:45:52.674  1731  4403 I SystemUpdateService: file has been verified
,08-26 19:45:52.675  1731  4403 I SystemUpdateService: OTA package size = 12249756
,08-26 19:45:52.683  1731  4403 I SystemUpdateService: showing system update notification
,08-26 19:45:52.687   375  1286 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-26 19:45:52.687   375  1286 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
08-26 19:45:52.689   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:45:52.699   873  4388 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 17:45:52 GMT], X-Android-Received-Millis=[1472233552698], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472233552677]}
,08-26 19:45:52.700   873  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-26 19:45:52.700   873  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-26 19:45:52.700   873  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-26 19:45:52.702   873  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 19:45:52.725  1731  1731 D SystemUpdateService: onDestroy
,08-26 19:45:52.739  1521  2091 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-26 19:45:52.739  1521  2091 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-26 19:45:52.739  1521  2091 I GLSUser : [GLSUser] Extracting token using key: Auth
08-26 19:45:52.739  1521  2091 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-26 19:45:52.756  1731  4406 E MDM     : [185] SitrepService.a: Error sending sitrep.,
,08-26 19:45:52.798  4101  4408 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-26 19:45:53.062   873  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,08-26 19:45:53.600  3971  4021 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 461)
,08-26 19:45:53.601  3971  4021 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 461)
,08-26 19:45:53.608   873  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-26 19:45:53.613  3971  4021 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 466)
,08-26 19:45:53.616  3971  4021 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-26 19:45:53.617  3971  4021 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 467)
,08-26 19:45:53.626  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:45:53.626  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cc788e added. We now have 2 listener(s)
,08-26 19:45:53.634  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:45:53.634  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:53.634  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:53.634  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:53.634  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69ec8af added. We now have 9 listener(s)
08-26 19:45:53.635  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:53.635  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:53.638  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:53.646  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:53.646  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:53.646  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:53.646  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:53.646  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:53.646  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:53.646  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:53.646  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:53.649  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:53.649  3971  4021 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:53.649  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:53.649  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c73ac45 added. We now have 3 listener(s)
,08-26 19:45:53.651  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:45:53.651  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:53.651  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:53.651  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:53.652  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1b8f9a added. We now have 10 listener(s)
,08-26 19:45:53.652  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:53.652  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:53.652  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:45:53.652  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:53.652  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:53.652  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:53.652  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:53.652  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:53.653  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3cc788e removed from the list
,08-26 19:45:53.653  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:53.653  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69ec8af removed from the list
08-26 19:45:53.654  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:53.655  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:53.655  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.655  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:53.656  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.657  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:53.657  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:45:53.657  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:53.657  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69ec8af not in the list
08-26 19:45:53.657  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.657  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.658  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:53.658  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:53.658  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:53.659  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1b8f9a removed from the list
,08-26 19:45:53.659  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:53.659  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.659  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.659  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:53.659  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c73ac45 removed from the list
,08-26 19:45:53.660  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:53.660  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29940cb added. We now have 2 listener(s)
08-26 19:45:53.661  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:53.662  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:45:53.662  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:45:53.663  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:53.663  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:53.663  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@500a0a8 added. We now have 9 listener(s)
08-26 19:45:53.663  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:53.664  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:45:53.668  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:53.676  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:53.676  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:53.676  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:53.676  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:53.676  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:53.676  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:53.676  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:53.676  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:53.678  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:53.678  3971  4021 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:45:53.678  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:53.679  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c130b66 added. We now have 3 listener(s)
,08-26 19:45:53.682  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:45:53.682  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:53.682  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:53.682  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:53.682  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8791ea7 added. We now have 10 listener(s)
08-26 19:45:53.682  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:53.683  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 19:45:53.683  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 19:45:53.683  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:53.683  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:53.683  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:53.683  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:45:53.687  3971  4021 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 19:45:53.687  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:45:53.689  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:53.693  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:45:53.695  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-26 19:45:53.695  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:45:53.699  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 19:45:53.700  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:45:53.700  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:45:53.700  3971  4021 D BluetoothAdapter: STATE_ON
,08-26 19:45:53.704  4334  4344 D BtGatt.GattService: registerClient() - UUID=6b2ae55b-162d-45b0-b1e9-63ac1b728395
08-26 19:45:53.705  4334  4350 D BtGatt.GattService: onClientRegistered() - UUID=6b2ae55b-162d-45b0-b1e9-63ac1b728395, clientIf=5
08-26 19:45:53.706  3971  4017 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-26 19:45:53.707  4334  4372 D BtGatt.GattService: start scan with filters
,08-26 19:45:53.712  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 19:45:53.712  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 19:45:53.712  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:45:53.712  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 19:45:53.712  4334  4353 D BtGatt.ScanManager: handling starting scan
,08-26 19:45:53.715  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:53.716  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:45:53.716  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:53.717  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-26 19:45:53.718  4334  4353 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7f723cc
,08-26 19:45:53.722  3971  4021 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-26 19:45:53.722  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 19:45:53.722  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 19:45:53.723  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.723  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:53.723  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 19:45:53.723  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:53.723  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:53.723  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 19:45:53.724  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:53.724  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 19:45:53.725  3971  4021 D BluetoothAdapter: STATE_ON
,08-26 19:45:53.725  4334  4362 D BtGatt.GattService: stopScan() - queue size =1
08-26 19:45:53.726  4334  4345 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 19:45:53.727  4334  4350 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 19:45:53.727  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.727  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:45:53.727  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:45:53.728  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:53.728  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 19:45:53.728  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 19:45:53.728  4334  4353 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-26 19:45:53.731  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:53.731  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:45:53.731  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:45:53.731  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:53.732  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:53.733  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:53.733  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:53.734  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 19:45:53.739  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:53.739  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:53.739  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:53.740  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:53.740  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:53.740  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:53.740  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:53.740  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29940cb removed from the list
08-26 19:45:53.741  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:53.741  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@500a0a8 removed from the list
08-26 19:45:53.741  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:53.741  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.742  4334  4350 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-26 19:45:53.742  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.742  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:53.742  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.743  4334  4353 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:45:53.743  4334  4353 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 19:45:53.746  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:45:53.746  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:53.747  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:53.747  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@500a0a8 not in the list
,08-26 19:45:53.748  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.748  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:53.751  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:53.751  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:53.751  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:53.751  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8791ea7 removed from the list
08-26 19:45:53.751  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:53.752  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.752  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:53.752  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:53.752  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c130b66 removed from the list
08-26 19:45:53.754  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:53.755  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68efe43 added. We now have 2 listener(s)
,08-26 19:45:53.757  4334  4350 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-26 19:45:53.758  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:53.762  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:45:53.762  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:53.762  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:53.763  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:53.764  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72cdcc0 added. We now have 9 listener(s)
08-26 19:45:53.764  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:53.765  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:53.767  4334  4350 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 19:45:53.767  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:53.771  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:53.776  4334  4350 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-26 19:45:53.776  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.776  4334  4353 D BtGatt.ScanManager: stopping BLe Batch
08-26 19:45:53.776  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:53.776  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:53.776  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:53.776  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:53.776  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:53.776  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:53.776  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:53.776  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:53.778  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:53.779  3971  4021 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:45:53.780  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 19:45:53.780  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38e213e added. We now have 3 listener(s)
,08-26 19:45:53.781  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:53.782  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-26 19:45:53.782  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:53.782  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:53.782  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:53.782  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5993b9f added. We now have 10 listener(s)
08-26 19:45:53.783  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:53.783  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:53.783  4334  4350 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 19:45:53.783  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.783  4334  4353 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 19:45:53.784  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:53.784  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:53.784  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-26 19:45:53.784  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:53.784  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:53.785  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:53.787  3971  4021 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-26 19:45:53.787  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:45:53.791  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:45:53.791  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 19:45:53.791  4334  4350 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-26 19:45:53.791  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.791  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:45:53.794  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:45:53.794  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 19:45:53.794  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:45:53.795  3971  4021 D BluetoothAdapter: STATE_ON
,08-26 19:45:53.797  4334  4344 D BtGatt.GattService: registerClient() - UUID=0b49c765-d968-4731-8bbf-a046df8046b2
,08-26 19:45:53.797  4334  4350 D BtGatt.GattService: onClientRegistered() - UUID=0b49c765-d968-4731-8bbf-a046df8046b2, clientIf=5
08-26 19:45:53.797  3971  3982 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 19:45:53.798  4334  4372 D BtGatt.GattService: start scan with filters
,08-26 19:45:53.800  4334  4353 D BtGatt.ScanManager: handling starting scan
,08-26 19:45:53.800  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 19:45:53.800  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 19:45:53.800  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:45:53.800  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 19:45:53.804  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:53.804  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:45:53.804  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 19:45:53.806  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:45:53.807  4334  4350 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-26 19:45:53.807  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.807  4334  4353 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 19:45:53.809  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:53.809  3971  4021 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 19:45:53.810  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:53.810  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:53.810  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:45:53.810  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:53.810  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.810  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:53.811  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:53.811  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@68efe43 removed from the list
08-26 19:45:53.811  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:53.811  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72cdcc0 removed from the list
08-26 19:45:53.811  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:53.811  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:53.811  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.811  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 19:45:53.812  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 19:45:53.812  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:53.813  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:53.813  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:53.813  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:53.813  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@72cdcc0 not in the list
,08-26 19:45:53.813  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:53.813  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:53.813  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:53.813  4334  4350 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 19:45:53.814  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.814  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:53.814  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-26 19:45:53.814  4334  4353 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:45:53.814  4334  4353 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-26 19:45:53.815  3971  4021 D BluetoothAdapter: STATE_ON
,08-26 19:45:53.815  4334  4362 D BtGatt.GattService: stopScan() - queue size =1
08-26 19:45:53.816  4334  4344 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 19:45:53.816  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:53.816  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 19:45:53.817  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:53.817  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 19:45:53.817  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 19:45:53.818  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:53.818  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:45:53.818  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:45:53.818  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:53.818  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.820  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:45:53.820  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 19:45:53.820  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:53.820  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:53.820  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:53.820  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5993b9f removed from the list
08-26 19:45:53.820  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:53.820  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:53.820  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.821  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.821  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:53.821  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38e213e removed from the list,
08-26 19:45:53.822  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:53.822  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dff2bb added. We now have 2 listener(s)
08-26 19:45:53.824  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:45:53.825  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:53.825  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:53.825  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:53.825  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff183d8 added. We now have 9 listener(s)
08-26 19:45:53.825  4334  4350 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 19:45:53.825  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.825  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:53.826  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:53.829  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:53.832  4334  4350 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-26 19:45:53.832  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:53.834  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:53.834  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:53.834  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:53.834  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:53.834  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:53.834  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:53.834  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:53.834  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:53.836  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:53.836  3971  4021 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:53.837  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:53.837  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eb1a16 added. We now have 3 listener(s)
08-26 19:45:53.839  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:53.839  4334  4350 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 19:45:53.839  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.840  4334  4353 D BtGatt.ScanManager: stopping BLe Batch
08-26 19:45:53.842  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:53.842  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:45:53.843  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:45:53.843  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 19:45:53.844  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:53.845  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a10ff97 added. We now have 10 listener(s)
,08-26 19:45:53.845  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:53.845  4334  4350 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 19:45:53.846  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.846  4334  4353 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-26 19:45:53.846  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 19:45:53.846  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:53.847  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:53.847  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:53.847  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 19:45:53.852  3971  4021 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-26 19:45:53.852  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:45:53.855  4334  4350 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
08-26 19:45:53.855  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:53.856  4334  4350 D BtGatt.GattService: current time is 155342727410
08-26 19:45:53.856  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:45:53.856  4334  4350 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -88, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-26 19:45:53.856  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-26 19:45:53.856  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:45:53.857  4334  4350 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-26 19:45:53.859  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 19:45:53.859  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 19:45:53.859  3971  4021 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 19:45:53.860  3971  4021 D BluetoothAdapter: STATE_ON
,08-26 19:45:53.862  4334  4344 D BtGatt.GattService: registerClient() - UUID=ccf9e3c6-c6d4-4b92-ac98-ef94e6a972ab
,08-26 19:45:53.862  4334  4350 D BtGatt.GattService: onClientRegistered() - UUID=ccf9e3c6-c6d4-4b92-ac98-ef94e6a972ab, clientIf=5
08-26 19:45:53.862  3971  4017 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-26 19:45:53.863  4334  4345 D BtGatt.GattService: start scan with filters
,08-26 19:45:53.864  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 19:45:53.865  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 19:45:53.865  4334  4353 D BtGatt.ScanManager: handling starting scan
08-26 19:45:53.865  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 19:45:53.865  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 19:45:53.867  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 19:45:53.867  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 19:45:53.867  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 19:45:53.868  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 19:45:53.872  4334  4350 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-26 19:45:53.872  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.872  4334  4353 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-26 19:45:53.874  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 19:45:53.874  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:53.874  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:53.874  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:53.874  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.874  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 19:45:53.874  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:53.875  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dff2bb removed from the list
,08-26 19:45:53.875  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:53.875  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff183d8 removed from the list
08-26 19:45:53.875  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:53.875  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:53.875  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.876  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 19:45:53.876  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.876  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:53.877  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:53.877  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:53.877  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:53.877  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff183d8 not in the list
,08-26 19:45:53.877  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:53.877  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:53.877  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 19:45:53.878  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:53.878  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 19:45:53.878  3971  4021 D BluetoothAdapter: STATE_ON
08-26 19:45:53.879  4334  4345 D BtGatt.GattService: stopScan() - queue size =1
08-26 19:45:53.879  4334  4350 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-26 19:45:53.879  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.879  4334  4353 D BtGatt.ScanManager: Starting BLE batch scan
08-26 19:45:53.879  4334  4353 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-26 19:45:53.879  4334  4362 D BtGatt.GattService: unregisterClient() - clientIf=5
08-26 19:45:53.880  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:53.880  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 19:45:53.880  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 19:45:53.880  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-26 19:45:53.880  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 19:45:53.881  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:53.881  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 19:45:53.881  3971  4021 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:45:53.881  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:53.881  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.882  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:53.882  3971  3971 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:53.882  3971  3971 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:53.882  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:53.883  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:53.883  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:53.883  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a10ff97 removed from the list
08-26 19:45:53.883  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:53.883  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.883  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.883  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:53.883  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5eb1a16 removed from the list
08-26 19:45:53.884  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:53.884  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdbfe33 added. We now have 2 listener(s)
,08-26 19:45:53.885  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:45:53.885  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:53.885  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:53.886  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:53.886  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@690f5f0 added. We now have 9 listener(s)
,08-26 19:45:53.886  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:53.886  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:53.888  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:53.892  3971  4021 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:53.892  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:53.892  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 19:45:53.892  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:53.892  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:53.892  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:53.892  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:53.892  3971  4021 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:53.893  4334  4350 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-26 19:45:53.893  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:53.895  3971  4021 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:53.895  3971  4021 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:45:53.896  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:53.896  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2355ee added. We now have 3 listener(s)
,08-26 19:45:53.897  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:53.898  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-26 19:45:53.898  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:53.898  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:53.898  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:53.898  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64e4a8f added. We now have 10 listener(s)
08-26 19:45:53.898  3971  4021 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:53.899  3971  4021 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:53.899  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:53.899  3971  4021 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:53.899  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:53.899  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.899  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:53.899  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:53.899  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fdbfe33 removed from the list
,08-26 19:45:53.899  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:53.899  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@690f5f0 removed from the list
08-26 19:45:53.900  3971  3971 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:53.900  3971  4021 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:53.900  4334  4350 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-26 19:45:53.900  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.900  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.901  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.901  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:53.903  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:53.903  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:53.903  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:53.903  3971  4021 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@690f5f0 not in the list
08-26 19:45:53.903  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.903  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.904  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:53.904  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:53.904  3971  4021 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:53.904  3971  4021 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@64e4a8f removed from the list
,08-26 19:45:53.904  3971  4021 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:53.904  3971  4021 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:53.904  3971  4021 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:53.904  3971  4021 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:53.904  3971  4021 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2355ee removed from the list
08-26 19:45:53.905  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 19:45:53.906  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 19:45:53.906  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 19:45:53.906  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:53.906  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 19:45:53.906  3971  4021 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:53.906  4334  4350 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-26 19:45:53.906  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.906  4334  4353 D BtGatt.ScanManager: stopping BLe Batch
,08-26 19:45:53.912  4334  4350 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-26 19:45:53.912  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-26 19:45:53.912  4334  4353 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-26 19:45:53.913  3971  4417 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 474, name: My test thread name)
08-26 19:45:53.913  3971  4417 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 474, thread name: My test thread name)
08-26 19:45:53.913  3971  4417 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 474, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 19:45:53.916  3971  4418 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 476, name: My test thread name)
,08-26 19:45:53.916  3971  4418 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 476, thread name: My test thread name)
08-26 19:45:53.916  3971  4418 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 476, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 19:45:53.917  4334  4350 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-26 19:45:53.917  4334  4350 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-26 19:45:53.918  3971  4021 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-26 19:45:53.918  3971  4021 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-26 19:45:53.918  3971  4021 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 19:45:53.918  3971  4021 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 19:45:53.918  3971  4021 D com.test.thalitest.ThaliTestRunner: Total duration: 22753 ms
08-26 19:45:53.921  3971  4021 I jxcore-log: *Native tests were executed*
08-26 19:45:53.921  3971  4021 I jxcore-log: 
,08-26 19:45:53.921  3971  4021 I jxcore-log: Total number of executed tests:  80
08-26 19:45:53.921  3971  4021 I jxcore-log: 
,08-26 19:45:53.921  3971  4021 I jxcore-log: Number of passed tests:  80
08-26 19:45:53.921  3971  4021 I jxcore-log: 
08-26 19:45:53.921  3971  4021 I jxcore-log: Number of failed tests:  0
08-26 19:45:53.921  3971  4021 I jxcore-log: 
08-26 19:45:53.921  3971  4021 I jxcore-log: Number of ignored tests:  0
08-26 19:45:53.921  3971  4021 I jxcore-log: 
08-26 19:45:53.922  3971  4021 I jxcore-log: Total duration:  22753
08-26 19:45:53.922  3971  4021 I jxcore-log: 
08-26 19:45:53.922  3971  4021 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 19:45:53.922  3971  4021 I jxcore-log: 
,08-26 19:45:53.925  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.925  3971  4021 I jxcore-log: 
08-26 19:45:53.927  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.927  3971  4021 I jxcore-log: 
08-26 19:45:53.929  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.929  3971  4021 I jxcore-log: 
08-26 19:45:53.930  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.930  3971  4021 I jxcore-log: 
08-26 19:45:53.931  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.931  3971  4021 I jxcore-log: 
08-26 19:45:53.932  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.932  3971  4021 I jxcore-log: 
08-26 19:45:53.934  3971  3971 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 19:45:53.938  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.938  3971  4021 I jxcore-log: 
08-26 19:45:53.940  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:45:53.940  3971  4021 I jxcore-log: 
08-26 19:45:53.940  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:45:53.940  3971  4021 I jxcore-log: 
08-26 19:45:53.941  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:53.941  3971  4021 I jxcore-log: 
,08-26 19:45:53.942  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:53.942  3971  4021 I jxcore-log: 
08-26 19:45:53.943  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:45:53.943  3971  4021 I jxcore-log: 
,08-26 19:45:53.943  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:45:53.943  3971  4021 I jxcore-log: 
08-26 19:45:53.944  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:45:53.944  3971  4021 I jxcore-log: 
,08-26 19:45:53.945  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.945  3971  4021 I jxcore-log: 
08-26 19:45:53.945  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.945  3971  4021 I jxcore-log: 
08-26 19:45:53.946  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:53.946  3971  4021 I jxcore-log: 
,08-26 19:45:53.946  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:53.946  3971  4021 I jxcore-log: 
08-26 19:45:53.947  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:45:53.947  3971  4021 I jxcore-log: 
08-26 19:45:53.948  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:45:53.948  3971  4021 I jxcore-log: 
,08-26 19:45:53.948  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:53.948  3971  4021 I jxcore-log: 
08-26 19:45:53.949  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:53.949  3971  4021 I jxcore-log: 
,08-26 19:45:53.949  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:45:53.949  3971  4021 I jxcore-log: 
08-26 19:45:53.950  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:45:53.950  3971  4021 I jxcore-log: 
,08-26 19:45:53.951  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:45:53.951  3971  4021 I jxcore-log: 
08-26 19:45:53.951  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.951  3971  4021 I jxcore-log: 
,08-26 19:45:53.952  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.952  3971  4021 I jxcore-log: 
08-26 19:45:53.953  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.953  3971  4021 I jxcore-log: 
,08-26 19:45:53.953  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.953  3971  4021 I jxcore-log: 
08-26 19:45:53.954  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.954  3971  4021 I jxcore-log: 
,08-26 19:45:53.954  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.954  3971  4021 I jxcore-log: 
08-26 19:45:53.955  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:53.955  3971  4021 I jxcore-log: 
,08-26 19:45:54.234  3971  3971 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:45:54.237  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:45:54.237  3971  4021 I jxcore-log: 
,08-26 19:45:54.320  3971  3971 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:45:54.323  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:45:54.323  3971  4021 I jxcore-log: 
,08-26 19:45:54.382  3971  3971 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 19:45:54.385  3971  4021 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:45:54.385  3971  4021 I jxcore-log: 
,08-26 19:45:54.618  4419  4419 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-26 19:45:54.623  4419  4419 D AndroidRuntime: CheckJNI is OFF
,08-26 19:45:54.666  4419  4419 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-26 19:45:54.714  4419  4419 I Radio-JNI: register_android_hardware_Radio DONE
,08-26 19:45:54.736  4419  4419 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 19:45:54.754   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-26 19:45:54.755   873   886 I ActivityManager: Killing 3971:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-26 19:45:54.846   873  1709 D GraphicsStats: Buffer count: 2
,08-26 19:45:54.846   873  2272 I WindowState: WIN DEATH: Window{d81202e u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-26 19:45:54.847   873  1316 D WifiService: Client connection lost with reason: 4
,08-26 19:45:54.910   873   896 W PackageSettings: Skipping PackageSetting{60e69 com.example.hello/10273} due to missing metadata
,08-26 19:45:54.936   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-26 19:45:54.936   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-26 19:45:54.937   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-26 19:45:54.937   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-26 19:45:54.937   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:54.937   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:54.937   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 19:45:54.937   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-26 19:45:54.938   873   886 I ActivityManager:   Force finishing activity ActivityRecord{7a5eef7 u0 com.test.thalitest/.MainActivity t2}
,08-26 19:45:54.941   873   896 I art     : Starting a blocking GC Explicit
,08-26 19:45:54.947   873  3241 W ActivityManager: Spurious death for ProcessRecord{9b2ba46 0:com.test.thalitest/u0a0}, curProc for 3971: null
,08-26 19:45:54.995   873   896 I art     : Explicit concurrent mark sweep GC freed 38564(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 29MB/43MB, paused 746us total 53.639ms
,08-26 19:45:55.026   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-26 19:45:55.030  4419  4419 I art     : System.exit called, status: 0
,08-26 19:45:55.030  4419  4419 I AndroidRuntime: VM exiting with result code 0.
,08-26 19:45:55.044   873   896 I ActivityManager: Start proc 4431:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-26 19:45:55.044   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-26 19:45:55.078   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-26 19:45:55.083  4334  4334 D BluetoothMapAppObserver: onReceive
,08-26 19:45:55.083  4334  4334 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-26 19:45:55.084  1871  1871 I Keyboard.Facilitator: resetDictionaries() : en_US
08-26 19:45:55.087  2139  2299 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 19:45:55.088   873  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 19:45:55.091  1871  4444 I Keyboard.Facilitator.DecoderInitializer: run()
,08-26 19:45:55.097  3794  3794 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-26 19:45:55.109  1871  4444 I Decoder : createOrResetDecoder
,08-26 19:45:55.110   873  2272 I ActivityManager: Start proc 4447:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-26 19:45:55.145  1931  1931 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-26 19:45:55.153  1521  1521 I ConfigService: onCreate
,08-26 19:45:55.156  1521  4459 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 19:45:55.156  1521  4459 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-26 19:45:55.156  1521  4459 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-26 19:45:55.157   873  1313 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-26 19:45:55.158  1521  4459 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-26 19:45:55.167  1871  4444 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-26 19:45:55.179   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 19:45:55.188   873   884 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3971 uid 10000
,08-26 19:45:55.189  1871  1871 I Keyboard.Facilitator: onFinishInput()
,08-26 19:45:55.211  4447  4447 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-26 19:45:55.215  1949  2029 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-26 19:45:55.216   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-26 19:45:55.216   873   885 E PackageManager: Failed to write settings, restoring backup
08-26 19:45:55.216   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-26 19:45:55.216   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-26 19:45:55.216   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-26 19:45:55.216   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-26 19:45:55.216   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-26 19:45:55.216   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:55.216   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:55.216   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 19:45:55.220   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-26 19:45:55.220   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 19:45:55.220   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:45:55.220   873   886 E DropBoxManagerService: 	... 13 more
,08-26 19:45:55.222  1871  4444 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-26 19:45:55.223  1871  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-26 19:45:55.224  1871  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-26 19:45:55.225   873  1341 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,08-26 19:45:55.225   873  1341 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-26 19:45:55.225   873  1341 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-26 19:45:55.225   873  1341 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
08-26 19:45:55.226   873  1341 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
08-26 19:45:55.226   873  1341 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
,08-26 19:45:55.226   873  1341 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
08-26 19:45:55.226   873  1341 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
08-26 19:45:55.226   873  1341 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
,08-26 19:45:55.226   873  1341 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-26 19:45:55.227   873  1341 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-26 19:45:55.227   873  1341 W System.err: 	... 4 more
08-26 19:45:55.227   873  1341 D skia    : ------- write threw an exception
,08-26 19:45:55.227  1871  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-26 19:45:55.227   873  1709 I ActivityManager: Start proc 4461:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-26 19:45:55.227  1871  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,--------- beginning of crash
08-26 19:45:55.228  1949  2029 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-26 19:45:55.228  1949  2029 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1949
08-26 19:45:55.228  1949  2029 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:55.228  1949  2029 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 19:45:55.231   873  3437 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-26 19:45:55.232   873  4470 E DropBoxManagerService: Can't write: system_app_crash
08-26 19:45:55.232   873  4470 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:45:55.232   873  4470 E DropBoxManagerService: 	... 5 more
08-26 19:45:55.237  1949  2029 I Process : Sending signal. PID: 1949 SIG: 9
08-26 19:45:55.239  1871  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-26 19:45:55.240  1871  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,08-26 19:45:55.243  1871  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-26 19:45:55.244  1871  4444 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-26 19:45:55.245  1871  4444 I Keyboard.Facilitator.Delight2FileSweeper: run()
,08-26 19:45:55.246  1871  4444 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-26 19:45:55.246  1871  4444 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-26 19:45:55.247  1871  4444 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-26 19:45:55.282  4447  4447 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-26 19:45:55.295   873  2271 D GraphicsStats: Buffer count: 1
,08-26 19:45:55.295   873  1958 I WindowState: WIN DEATH: Window{8664993 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-26 19:45:55.301  4447  4479 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-26 19:45:55.316  4447  4476 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:55.316  4447  4476 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:55.317  4447  4476 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 19:45:55.322   873  1729 I ActivityManager: Start proc 4481:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-26 19:45:55.325   873  2271 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1949) has died
,08-26 19:45:55.326   873  2271 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-26 19:45:55.328   873  2271 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 19:45:55.343   873   886 I ActivityManager: Start proc 4494:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 19:45:55.370  4481  4481 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-26 19:45:55.389  4494  4494 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:55.389  4494  4494 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-26 19:45:55.389  4494  4494 D AndroidRuntime: Shutting down VM
,08-26 19:45:55.395  1521  1521 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-26 19:45:55.396  1521  1521 D AndroidRuntime: Shutting down VM
08-26 19:45:55.396  1521  1521 E AndroidRuntime: FATAL EXCEPTION: main
08-26 19:45:55.396  1521  1521 E AndroidRuntime: Process: com.google.process.gapps, PID: 1521
08-26 19:45:55.396  1521  1521 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-26 19:45:55.396  1521  1521 E AndroidRuntime: 	... 8 more
,08-26 19:45:55.397   873  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 16 -> obsolete
08-26 19:45:55.398  4494  4494 E AndroidRuntime: FATAL EXCEPTION: main
08-26 19:45:55.398  4494  4494 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4494
08-26 19:45:55.398  4494  4494 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:174,8)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-26 19:45:55.398  4494  4494 E AndroidRuntime: 	... 10 more
,08-26 19:45:55.402   873  4510 E DropBoxManagerService: Can't write: system_app_crash
08-26 19:45:55.402   873  4510 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:45:55.402   873  4510 E DropBoxManagerService: 	... 5 more
,08-26 19:45:55.403   873  4509 E DropBoxManagerService: Can't write: system_app_crash
08-26 19:45:55.403   873  4509 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:45:55.403   873  4509 E DropBoxManagerService: 	... 5 more
08-26 19:45:55.403   873  2271 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 19:45:55.404  1521  1521 I Process : Sending signal. PID: 1521 SIG: 9
08-26 19:45:55.405  4494  4494 I Process : Sending signal. PID: 4494 SIG: 9
,08-26 19:45:55.421   873  1389 I ActivityManager: Killing 3908:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-26 19:45:55.445  4447  4476 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-26 19:45:55.450  4447  4479 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:55.450  4447  4479 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 19:45:55.450  4447  4479 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-26 19:45:55.450  4447  4479 E AndroidRuntime: Process: android.process.acore, PID: 4447
08-26 19:45:55.450  4447  4479 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-26 19:45:55.450  4447  4479 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 19:45:55.451  4447  4476 I Process : Sending signal. PID: 4447 SIG: 9
,08-26 19:45:55.458   873  1316 D WifiService: Client connection lost with reason: 4
,08-26 19:45:55.459  1731  4506 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@4e53ab5
,08-26 19:45:55.485   873   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4494) has died
,08-26 19:45:55.486   873   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-26 19:45:55.489   873  1729 I ActivityManager: Process com.google.process.gapps (pid 1521) has died
,08-26 19:45:55.489   873  1729 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
,08-26 19:45:55.489   873  1729 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
08-26 19:45:55.489   873  1729 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-26 19:45:55.490   873  1729 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 31000ms
,08-26 19:45:55.502   873   886 I ActivityManager: Start proc 4512:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-26 19:45:55.504   873  2271 I ActivityManager: Process android.process.acore (pid 4447) has died
,08-26 19:45:55.504   873  2271 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 40985ms
,08-26 19:45:55.517  1731  1731 W RocketImpressions: ClearcutLogger connection suspended: 1
08-26 19:45:55.518   873  3241 I ActivityManager: Start proc 4524:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
08-26 19:45:55.521   873  4530 E DropBoxManagerService: Can't write: system_app_crash
08-26 19:45:55.521   873  4530 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-26 19:45:55.521   873  4530 E DropBoxManagerService: 	... 5 more

```
