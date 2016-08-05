#### Test 79751015abe04ee_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-05 11:23:31.832   871  2013 D NetlinkSocketObserver: NeighborEvent{elapsedMs=124904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:23:32.709  3831  3831 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 11:23:32.714  3831  3831 D AndroidRuntime: CheckJNI is OFF
08-05 11:23:32.750  3831  3831 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-05 11:23:32.792  3831  3831 I Radio-JNI: register_android_hardware_Radio DONE
08-05 11:23:32.813  3831  3831 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 11:23:32.818   871  1690 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 11:23:32.865  1802  2200 W SearchService: Abort, client detached.
08-05 11:23:32.870  1802  1802 I HotwordDetector: Closing mic
08-05 11:23:32.870  1802  2129 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@caad7fc
08-05 11:23:32.871  1802  2134 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-05 11:23:32.874  3831  3831 D AndroidRuntime: Shutting down VM
08-05 11:23:32.889   871  1521 I ActivityManager: Start proc 3843:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-05 11:23:32.931   375  2136 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-05 11:23:32.931   375  2136 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-05 11:23:32.936   375  1273 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-05 11:23:32.938  1802  2132 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-05 11:23:32.938  1802  2133 I MicroRecognitionRnrImpl: Detection finished
08-05 11:23:32.960  3843  3843 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-05 11:23:32.988  3843  3843 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-05 11:23:32.995  3843  3843 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6065-6067)
08-05 11:23:32.995  3843  3843 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 11:23:33.011  3843  3843 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f524df}
08-05 11:23:33.011  3843  3843 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 11:23:33.011  3843  3843 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 11:23:33.018  3843  3843 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-05 11:23:33.020  3843  3843 E SysUtils: ApplicationContext is null in ApplicationStatus
08-05 11:23:33.025  3078  3856 V KeepSync: Connecting to GoogleApiClient
08-05 11:23:33.026   871  1889 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
08-05 11:23:33.034  3843  3843 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-05 11:23:33.044  3843  3843 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 11:23:33.044  3843  3843 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 11:23:33.044  3843  3843 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-05 11:23:33.044  3843  3843 I Adreno  : Build Date                       : 10/20/15
08-05 11:23:33.044  3843  3843 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-05 11:23:33.044  3843  3843 I Adreno  : Local Branch                     : M14
08-05 11:23:33.044  3843  3843 I Adreno  : Remote Branch                    : 
08-05 11:23:33.044  3843  3843 I Adreno  : Remote Branch                    : 
08-05 11:23:33.044  3843  3843 I Adreno  : Reconstruct Branch               : 
08-05 11:23:33.050  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-05 11:23:33.052  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-05 11:23:33.066  1508  2012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-05 11:23:33.066  1508  2012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-05 11:23:33.066  1508  2012 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:23:33.066  1508  2012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-05 11:23:33.076  1865  3867 V BaseAuthAsyncOperation: access token request failed
08-05 11:23:33.078  3078  3856 V KeepSync: GoogleApiClient failed to connect with error code: 4
08-05 11:23:33.081   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e30033:true
,08-05 11:23:33.122  3843  3843 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 11:23:33.127  1508  3822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-05 11:23:33.127  1508  3822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-05 11:23:33.128  1508  3822 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:23:33.128  1508  3822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:23:33.135  3843  3843 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-05 11:23:33.141  3078  3856 E KeepSync: IOException
08-05 11:23:33.141  3078  3856 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 11:23:33.141  3078  3856 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:23:33.141  3078  3856 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 11:23:33.141  3078  3856 E KeepSync: 	... 10 more
,08-05 11:23:33.141  3078  3856 W KeepSync: Sync result 2
,08-05 11:23:33.144   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 124895, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1],
,08-05 11:23:33.181  3843  3886 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-05 11:23:33.188  3843  3873 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-05 11:23:33.215  3843  3886 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 11:23:33.293  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-05 11:23:33.294   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +419ms
,08-05 11:23:33.356  3843  3843 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3843
,08-05 11:23:33.525  3843  3843 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 11:23:33.711   871   881 I ActivityManager: Killing 3159:com.google.android.gm.exchange/u0a77 (adj 15): empty #17
,08-05 11:23:33.737  3843  3888 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1702168272
,08-05 11:23:33.749  3843  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 11:23:33.749  3843  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 11:23:33.749  3843  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 11:23:33.749  3843  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 11:23:33.749  3843  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-05 11:23:33.749  3843  3888 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2612a2 added. We now have 1 listener(s)
,08-05 11:23:33.754  3843  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-05 11:23:33.755  3843  3888 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 11:23:33.757  3843  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 11:23:33.759  3843  3888 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 11:23:33.760   871   881 I ActivityManager: Killing 2401:com.google.android.talk/u0a61 (adj 15): empty #18
,08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-05 11:23:33.772  3843  3888 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb84c69 added. We now have 1 listener(s)
08-05 11:23:33.773  3843  3888 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:23:33.777   871  1305 D WifiService: New client listening to asynchronous messages
,08-05 11:23:33.778  3843  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 11:23:33.778  3843  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-05 11:23:33.778  3843  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 11:23:33.778  3843  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3,
08-05 11:23:33.779  3843  3888 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-05 11:23:33.829  3843  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:23:33.829  3843  3888 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-05 11:23:33.835  3843  3888 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-05 11:23:33.836  3843  3888 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:23:33.836  3843  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:33.836  3843  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:33.836  3843  3888 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:33.836  3843  3888 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:23:33.836  3843  3888 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:33.836  3843  3888 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:23:33.836  3843  3888 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:23:33.836  3843  3888 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 11:23:33.836  3843  3888 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:23:33.836  3843  3888 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 11:23:33.935  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:23:33.940  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:23:33.943  3843  3843 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 11:23:35.000  3843  3898 W jxcore-log: Initializing JXcore engine
,08-05 11:23:35.000  3843  3898 W jxcore-log: JXcore engine is ready
,08-05 11:23:35.040  3898  3898 W Thread-342: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-05 11:23:35.040  3898  3898 W Thread-342: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10786]" dev="sockfs" ino=10786 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-05 11:23:35.040  3898  3898 W Thread-342: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-05 11:23:35.040  3898  3898 W Thread-342: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[25468]" dev="sockfs" ino=25468 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-05 11:23:35.055  3843  3898 W jxcore-log: Starting JXcore engine
,08-05 11:23:35.156  3843  3898 W jxcore-log: Platform android
08-05 11:23:35.156  3843  3898 W jxcore-log: 
,08-05 11:23:35.156  3843  3898 W jxcore-log: Process ARCH arm
08-05 11:23:35.156  3843  3898 W jxcore-log: 
,08-05 11:23:35.374  3843  3898 I jxcore-log: JXcore Cordova bridge is ready!
08-05 11:23:35.374  3843  3898 I jxcore-log: 
,08-05 11:23:35.375  3843  3898 W jxcore-log: JXcore engine is started
08-05 11:23:35.381  3843  3888 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-05 11:23:35.387  3843  3843 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 11:23:38.015  3534  3905 V GoogleAuthProtoRequest: [299] a.<init>: mAccountName set to: thalitester@gmail.com
,08-05 11:23:38.103  1508  1968 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-05 11:23:38.103  1508  1968 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-05 11:23:38.103  1508  1968 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:23:38.104  1508  1968 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:23:38.111  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:23:38.134  1508  3907 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-05 11:23:38.136  1508  3907 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-05 11:23:38.142  1508  2353 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-05 11:23:38.142  1508  2353 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-05 11:23:38.142  1508  2353 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:23:38.142  1508  2353 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: [299] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: [299] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-05 11:23:38.157  3534  3905 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-05 11:23:38.161  3443  3443 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-05 11:23:38.161  3443  3443 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-05 11:23:38.161  3443  3443 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-05 11:23:38.164  1508  3907 W Uploader:  no longer exists, so no auth token.
,08-05 11:23:38.590  1508  3907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-05 11:23:38.591  1508  3907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-05 11:23:38.592  1508  3907 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:23:38.592  1508  3907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:23:38.623  1508  3907 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-05 11:23:38.623  1508  3907 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-05 11:23:38.623  1508  3907 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-05 11:23:38.831   871  2013 D NetlinkSocketObserver: NeighborEvent{elapsedMs=131903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:23:39.280  1508  3907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
08-05 11:23:39.280  1508  3907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-05 11:23:39.280  1508  3907 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:23:39.280  1508  3907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:23:39.300  1508  3907 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-05 11:23:39.300  1508  3907 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-05 11:23:39.300  1508  3907 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-05 11:23:39.488  1508  3907 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-05 11:23:39.488  1508  3907 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-05 11:23:39.489  1508  3907 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:23:39.489  1508  3907 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:23:39.530  1508  3907 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-05 11:23:39.530  1508  3907 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-05 11:23:39.530  1508  3907 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-05 11:23:51.558  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 11:23:51.558  3843  3898 I jxcore-log: 
,08-05 11:23:51.560  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 11:23:51.560  3843  3898 I jxcore-log: 
,08-05 11:23:51.575  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:23:51.575  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:51.575  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:51.575  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:51.575  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:23:51.575  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:51.575  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:23:51.575  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:23:51.581  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:23:51.583  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 11:23:51.583  3843  3898 I jxcore-log: 
,08-05 11:23:51.585  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 11:23:51.585  3843  3898 I jxcore-log: 
,08-05 11:23:51.924  3843  3898 D ExecuteNativeTests: Running unit tests
,08-05 11:23:51.982  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:23:51.982  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 added. We now have 2 listener(s)
08-05 11:23:51.983  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 11:23:51.983  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:23:51.983  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:23:51.983  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 11:23:51.983  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 added. We now have 2 listener(s)
08-05 11:23:51.983  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:23:51.984  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 11:23:51.992  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:23:52.003  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:23:52.003  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:52.003  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:52.003  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:52.003  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:23:52.003  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:52.003  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:23:52.003  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:23:52.006  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:23:52.007  3843  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:23:52.009  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-05 11:23:52.011  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 11:23:52.011  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-05 11:23:52.012  3843  3898 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-05 11:23:52.012  3843  3898 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-05 11:23:52.012  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 11:23:52.013  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:23:52.013  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:23:52.013  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.013  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.014  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 11:23:52.014  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.014  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.014  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:23:52.014  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:23:52.014  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 removed from the list
08-05 11:23:52.014  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.014  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 removed from the list
08-05 11:23:52.016  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:23:52.016  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.016  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.017  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.017  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:23:52.022  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 11:23:52.022  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.022  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.022  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
,08-05 11:23:52.024  3843  3898 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-05 11:23:52.024  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.025  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.025  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.025  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.025  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.025  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:23:52.025  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.025  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.025  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.025  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.025  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.025  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:23:52.025  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.026  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.026  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.026  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 11:23:52.027  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.027  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.027  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
,08-05 11:23:52.031  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-05 11:23:52.031  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 11:23:52.031  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 11:23:52.031  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510],
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-05 11:23:52.032  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 11:23:52.033  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 11:23:52.033  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-05 11:23:52.033  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 11:23:52.033  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 11:23:52.033  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-05 11:23:52.033  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 11:23:52.033  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 11:23:52.033  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 11:23:52.033  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.033  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 11:23:52.033  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.033  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:23:52.033  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.033  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.033  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.033  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
,08-05 11:23:52.033  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.033  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.033  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.033  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.034  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.035  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 11:23:52.035  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.035  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.035  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.036  3843  3898 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-05 11:23:52.037  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:23:52.042  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:23:52.042  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:52.042  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:52.042  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:52.042  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:23:52.042  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:52.042  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:23:52.042  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:23:52.044  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:23:52.044  3843  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:23:52.044  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:23:52.044  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:23:52.044  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:23:52.044  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:23:52.045  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:23:52.046  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:23:52.050  3843  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 11:23:52.051  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:23:52.051  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.058  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 11:23:52.060  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 11:23:52.060  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 11:23:52.063  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-05 11:23:52.064  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-05 11:23:52.064  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-05 11:23:52.065  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 11:23:52.065  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 11:23:52.066  3843  3898 D BluetoothAdapter: STATE_ON
,08-05 11:23:52.070  2591  2603 D BtGatt.GattService: registerClient() - UUID=60973ab8-7c70-4e1a-98be-aa71ee09cccd
08-05 11:23:52.071  2591  2625 D BtGatt.GattService: onClientRegistered() - UUID=60973ab8-7c70-4e1a-98be-aa71ee09cccd, clientIf=5
08-05 11:23:52.072  3843  3853 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-05 11:23:52.073  2591  2728 D BtGatt.GattService: start scan with filters
,08-05 11:23:52.078  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-05 11:23:52.079  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 11:23:52.079  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 11:23:52.079  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-05 11:23:52.079  2591  2628 D BtGatt.ScanManager: handling starting scan
,08-05 11:23:52.081  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 11:23:52.082  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 11:23:52.082  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 11:23:52.083  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-05 11:23:52.083  2591  2628 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:23:52.087  3843  3898 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 11:23:52.090  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 11:23:52.090  3843  3898 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-05 11:23:52.090  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.090  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-05 11:23:52.090  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.090  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-05 11:23:52.091  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 11:23:52.091  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-05 11:23:52.092  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 11:23:52.092  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-05 11:23:52.092  2591  2625 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-05 11:23:52.092  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.093  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-05 11:23:52.093  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 11:23:52.094  2591  2628 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 11:23:52.094  3843  3898 D BluetoothAdapter: STATE_ON
08-05 11:23:52.094  2591  2603 D BtGatt.GattService: stopScan() - queue size =1
08-05 11:23:52.095  2591  2728 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 11:23:52.096  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:23:52.096  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 11:23:52.096  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-05 11:23:52.096  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 11:23:52.097  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-05 11:23:52.098  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 11:23:52.098  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 11:23:52.098  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 11:23:52.098  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 11:23:52.099  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 11:23:52.099  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:23:52.099  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:23:52.099  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 11:23:52.100  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.100  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.100  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:23:52.100  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.100  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:23:52.100  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.100  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop,
08-05 11:23:52.100  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:23:52.104  3843  3898 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-05 11:23:52.108  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:23:52.116  2591  2625 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-05 11:23:52.116  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:23:52.117  2591  2628 D BtGatt.ScanManager: Starting BLE batch scan
,08-05 11:23:52.117  2591  2628 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 11:23:52.118  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:23:52.118  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:52.118  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:52.118  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:52.118  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:23:52.118  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:52.118  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:23:52.118  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:23:52.120  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:52.120  3843  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:23:52.120  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 11:23:52.120  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:23:52.120  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:23:52.120  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:23:52.121  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 11:23:52.123  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:23:52.124  3843  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 11:23:52.124  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:23:52.125  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:23:52.128  2591  2625 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-05 11:23:52.128  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 11:23:52.128  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.130  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 11:23:52.130  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 11:23:52.133  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-05 11:23:52.133  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-05 11:23:52.133  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 11:23:52.133  3843  3898 D BluetoothAdapter: STATE_ON
08-05 11:23:52.135  2591  2728 D BtGatt.GattService: registerClient() - UUID=cd33f04c-c078-45ea-a1e3-81ffb740710a
08-05 11:23:52.135  2591  2625 D BtGatt.GattService: onClientRegistered() - UUID=cd33f04c-c078-45ea-a1e3-81ffb740710a, clientIf=5
08-05 11:23:52.136  3843  3855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-05 11:23:52.136  2591  2603 D BtGatt.GattService: start scan with filters
,08-05 11:23:52.137  2591  2625 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-05 11:23:52.137  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:23:52.139  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-05 11:23:52.139  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 11:23:52.139  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-05 11:23:52.139  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 11:23:52.141  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 11:23:52.141  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 11:23:52.141  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 11:23:52.142  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 11:23:52.144  3843  3898 I io.jxcore.node.ConnectionHelper: start: OK
08-05 11:23:52.144  2591  2625 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 11:23:52.144  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:23:52.145  2591  2628 D BtGatt.ScanManager: stopping BLe Batch
08-05 11:23:52.145  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 11:23:52.145  3843  3898 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-05 11:23:52.146  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.146  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-05 11:23:52.146  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.146  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-05 11:23:52.146  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 11:23:52.146  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 11:23:52.146  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-05 11:23:52.146  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 11:23:52.146  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 11:23:52.146  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 11:23:52.147  3843  3898 D BluetoothAdapter: STATE_ON
,08-05 11:23:52.147  2591  2603 D BtGatt.GattService: stopScan() - queue size =0
08-05 11:23:52.148  2591  2750 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 11:23:52.149  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:23:52.149  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-05 11:23:52.149  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-05 11:23:52.149  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-05 11:23:52.149  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 11:23:52.150  2591  2625 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-05 11:23:52.150  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.150  2591  2628 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 11:23:52.150  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 11:23:52.151  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-05 11:23:52.151  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-05 11:23:52.151  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 11:23:52.152  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:23:52.153  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.153  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.153  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 11:23:52.153  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
,08-05 11:23:52.153  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:23:52.153  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:23:52.153  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
,08-05 11:23:52.153  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:23:52.153  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 11:23:52.153  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.153  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 11:23:52.154  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.154  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:23:52.155  2591  2625 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-05 11:23:52.155  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:23:52.155  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 11:23:52.155  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.155  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:23:52.155  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.156  3843  3898 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-05 11:23:52.157  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:23:52.159  2591  2628 D BtGatt.ScanManager: handling starting scan
,08-05 11:23:52.166  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:23:52.166  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:52.166  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:52.166  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:52.166  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:23:52.166  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:52.166  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:23:52.166  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:23:52.168  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:23:52.168  3843  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:23:52.168  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:23:52.168  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:23:52.168  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-05 11:23:52.168  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:23:52.168  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:23:52.171  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.171  2591  2625 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-05 11:23:52.171  3843  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 11:23:52.171  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.172  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:23:52.172  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.172  2591  2628 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 11:23:52.179  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 11:23:52.179  2591  2625 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-05 11:23:52.179  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:23:52.180  2591  2628 D BtGatt.ScanManager: Starting BLE batch scan
08-05 11:23:52.180  2591  2628 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 11:23:52.180  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 11:23:52.180  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 11:23:52.184  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-05 11:23:52.184  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 11:23:52.184  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 11:23:52.192  3843  3898 D BluetoothAdapter: STATE_ON
,08-05 11:23:52.194  2591  2625 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-05 11:23:52.194  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:23:52.195  2591  2750 D BtGatt.GattService: registerClient() - UUID=12f1f10e-6bf9-417c-ac53-43dfe23fca28
,08-05 11:23:52.197  2591  2625 D BtGatt.GattService: onClientRegistered() - UUID=12f1f10e-6bf9-417c-ac53-43dfe23fca28, clientIf=5
,08-05 11:23:52.198  3843  3855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-05 11:23:52.198  2591  2728 D BtGatt.GattService: start scan with filters
,08-05 11:23:52.202  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-05 11:23:52.202  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-05 11:23:52.202  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 11:23:52.202  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 11:23:52.203  2591  2625 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-05 11:23:52.203  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:23:52.206  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 11:23:52.207  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 11:23:52.207  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 11:23:52.211  2591  2625 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 11:23:52.211  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.212  2591  2628 D BtGatt.ScanManager: stopping BLe Batch
08-05 11:23:52.214  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 11:23:52.218  2591  2625 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-05 11:23:52.219  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.219  2591  2628 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
,08-05 11:23:52.222  3843  3898 I io.jxcore.node.ConnectionHelper: start: OK
08-05 11:23:52.222  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-05 11:23:52.222  3843  3898 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-05 11:23:52.222  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-05 11:23:52.222  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-05 11:23:52.223  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.223  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-05 11:23:52.223  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 11:23:52.223  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-05 11:23:52.223  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 11:23:52.223  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-05 11:23:52.224  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 11:23:52.224  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-05 11:23:52.234  3843  3898 D BluetoothAdapter: STATE_ON
,08-05 11:23:52.235  2591  2625 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-05 11:23:52.235  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-05 11:23:52.235  2591  2603 D BtGatt.GattService: stopScan() - queue size =0
08-05 11:23:52.236  2591  2628 D BtGatt.ScanManager: handling starting scan
,08-05 11:23:52.237  2591  2602 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 11:23:52.237  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:23:52.237  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-05 11:23:52.237  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 11:23:52.238  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 11:23:52.238  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 11:23:52.240  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 11:23:52.241  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-05 11:23:52.241  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 11:23:52.241  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 11:23:52.242  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:23:52.242  2591  2625 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-05 11:23:52.242  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.242  2591  2628 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 11:23:52.244  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-05 11:23:52.244  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:23:52.245  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 11:23:52.245  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.245  3843  3898 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-05 11:23:52.245  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.245  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.246  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.246  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:23:52.246  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:23:52.246  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.246  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.246  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.247  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.247  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:23:52.247  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.247  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:23:52.249  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.249  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.249  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.249  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.249  3843  3898 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-05 11:23:52.250  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 11:23:52.250  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.250  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 11:23:52.250  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.250  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.250  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.250  2591  2625 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-05 11:23:52.250  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.250  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.250  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.250  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.250  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 11:23:52.250  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.250  2591  2628 D BtGatt.ScanManager: Starting BLE batch scan
08-05 11:23:52.250  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.250  2591  2628 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-05 11:23:52.250  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.251  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.251  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.251  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.252  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:23:52.252  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.252  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 11:23:52.252  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.253  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.253  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.253  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.253  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.253  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.253  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.253  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:23:52.253  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.253  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.253  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.253  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.253  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.253  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:23:52.254  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.254  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.254  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.254  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.255  3843  3898 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-05 11:23:52.255  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.255  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.255  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.255  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.255  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.255  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.255  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
,08-05 11:23:52.255  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.255  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.255  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.255  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.255  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.256  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.256  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.256  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 11:23:52.256  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.256  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.257  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.258  3843  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-05 11:23:52.258  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.258  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 11:23:52.258  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.259  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.259  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.259  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:23:52.259  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.259  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.259  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.259  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.259  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.259  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.260  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.260  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.261  2591  2625 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 11:23:52.261  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.262  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 11:23:52.262  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.262  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.262  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
,08-05 11:23:52.263  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-05 11:23:52.266  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 11:23:52.266  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 11:23:52.266  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-05 11:23:52.266  2591  2625 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-05 11:23:52.267  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:23:52.267  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-05 11:23:52.268  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 11:23:52.268  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 11:23:52.268  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.268  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 11:23:52.268  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.268  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:23:52.268  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.269  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
,08-05 11:23:52.269  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.269  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
,08-05 11:23:52.269  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 11:23:52.269  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.269  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.269  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.269  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:23:52.270  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.270  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.270  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.270  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.271  3843  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:23:52.272  3843  3898 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 11:23:52.272  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-05 11:23:52.273  2591  2625 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 11:23:52.273  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.273  2591  2628 D BtGatt.ScanManager: stopping BLe Batch
08-05 11:23:52.276  3843  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:23:52.276  3843  3898 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-05 11:23:52.276  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 11:23:52.277  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 11:23:52.277  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 11:23:52.277  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-05 11:23:52.277  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 11:23:52.277  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 11:23:52.277  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 11:23:52.278  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 11:23:52.279  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 11:23:52.279  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-05 11:23:52.279  2591  2625 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-05 11:23:52.279  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 11:23:52.279  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:23:52.279  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 11:23:52.279  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 11:23:52.279  2591  2628 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-05 11:23:52.279  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 11:23:52.279  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 11:23:52.279  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-05 11:23:52.279  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 11:23:52.279  3843  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-05 11:23:52.280  3843  3898 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 11:23:52.280  3843  3898 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-05 11:23:52.280  3843  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:23:52.280  3843  3898 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-05 11:23:52.280  3843  3898 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-05 11:23:52.280  3843  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:23:52.280  3843  3898 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 11:23:52.281  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-05 11:23:52.283  2591  2625 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-05 11:23:52.283  2591  2625 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:23:52.286  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-05 11:23:52.287  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-05 11:23:52.287  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-05 11:23:52.287  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-05 11:23:52.287  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-05 11:23:52.287  3843  3898 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-05 11:23:52.287  3843  3898 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 11:23:52.287  3843  3898 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-05 11:23:52.288  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.288  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 11:23:52.288  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.288  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.288  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.288  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.288  3843  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 406)
08-05 11:23:52.288  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-05 11:23:52.289  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.289  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:23:52.289  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.289  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.289  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.289  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.289  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:23:52.289  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.290  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.290  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.290  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.290  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.290  3843  3898 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-05 11:23:52.290  3843  3922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:23:52.291  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.291  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.291  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 11:23:52.291  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.291  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.291  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.291  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.291  3843  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 406
08-05 11:23:52.291  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.291  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.291  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.291  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.291  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.292  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:23:52.291  3843  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 406)
08-05 11:23:52.292  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.292  3843  3923 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 406)
08-05 11:23:52.292  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.293  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.293  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.293  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.293  3843  3922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 406)
08-05 11:23:52.293  3843  3898 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-05 11:23:52.293  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.293  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.293  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.294  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.294  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.294  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.294  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.294  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.294  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.294  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.294  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:23:52.294  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.294  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.294  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.295  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.295  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.295  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.295  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.296  3843  3898 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-05 11:23:52.296  3843  3898 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-05 11:23:52.296  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 11:23:52.296  3843  3898 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-05 11:23:52.296  3843  3898 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 11:23:52.296  3843  3898 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-05 11:23:52.296  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 11:23:52.296  3843  3898 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-05 11:23:52.296  3843  3898 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 11:23:52.296  3843  3898 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 11:23:52.296  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 11:23:52.296  3843  3898 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-05 11:23:52.296  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.296  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.297  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.297  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 11:23:52.297  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.297  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.297  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.297  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.297  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.297  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.297  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.297  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.297  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:23:52.297  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.298  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.298  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.298  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.298  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.298  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.298  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.298  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.298  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.298  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:23:52.299  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.299  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.299  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.299  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.299  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.299  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.299  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.299  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.299  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.299  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.299  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.299  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.299  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.299  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.299  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.299  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.299  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.299  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.299  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
,08-05 11:23:52.299  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.299  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.300  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.300  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.300  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.300  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.300  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.300  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.300  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.301  3843  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 11:23:52.301  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:23:52.302  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 11:23:52.302  3843  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 11:23:52.303  3843  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 11:23:52.303  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 11:23:52.303  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 11:23:52.303  3843  3843 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 11:23:52.303  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.303  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 11:23:52.303  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 11:23:52.303  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 11:23:52.303  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.303  3843  3898 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 11:23:52.303  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.303  3843  3843 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 11:23:52.303  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.303  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 11:23:52.303  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 11:23:52.304  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 11:23:52.304  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.304  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.304  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 11:23:52.304  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.304  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.305  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.305  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.305  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.305  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:23:52.305  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.305  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.305  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.305  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.305  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.305  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:23:52.305  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.305  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 11:23:52.305  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.305  3843  3924 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 11:23:52.306  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.306  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.306  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.306  3843  3924 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 11:23:52.306  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.306  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.306  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.307  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.307  3843  3843 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 11:23:52.307  3843  3898 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-05 11:23:52.308  3843  3898 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 11:23:52.308  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 11:23:52.308  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 11:23:52.308  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.308  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.308  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.308  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.308  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.308  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.308  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.308  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.309  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.309  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.309  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.309  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.309  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.309  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.309  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.309  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.309  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.310  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.322  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.322  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.323  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.323  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.323  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.323  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.323  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.323  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.323  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.323  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.323  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.323  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.323  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.323  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.324  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.324  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.324  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.324  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.325  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:23:52.325  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:23:52.325  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:23:52.325  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:23:52.325  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.325  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.325  3843  3898 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@788d1f3 not in the list
08-05 11:23:52.325  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.325  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.325  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:23:52.325  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.325  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.325  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:23:52.325  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:23:52.327  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:23:52.327  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:23:52.327  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:23:52.327  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2b9eb0 not in the list
08-05 11:23:52.328  3843  3898 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-05 11:23:52.328  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 11:23:52.328  3843  3898 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-05 11:23:52.328  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 11:23:52.328  3843  3898 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-05 11:23:52.328  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 11:23:52.329  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 11:23:52.330  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-05 11:23:52.330  3843  3898 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-05 11:23:52.330  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 11:23:52.337  3843  3898 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-05 11:23:52.337  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 11:23:52.337  3843  3898 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-05 11:23:52.337  3843  3898 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-05 11:23:52.338  3843  3898 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-05 11:23:52.338  3843  3898 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-05 11:23:52.338  3843  3898 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-05 11:23:52.338  3843  3898 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-05 11:23:52.338  3843  3898 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-05 11:23:52.338  3843  3898 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-05 11:23:52.339  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:23:52.339  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@76fd212 added. We now have 2 listener(s)
08-05 11:23:52.339  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:23:52.341  3843  3898 D BluetoothAdapter: enable(): BT is already enabled..!
08-05 11:23:52.342   871  1687 D WifiService: setWifiEnabled: true pid=3843, uid=10000
08-05 11:23:52.342   871  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 11:23:52.343  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:23:52.343  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@88a1de3 added. We now have 3 listener(s)
08-05 11:23:52.343  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:23:52.349  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:23:52.349  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@87c13e0 added. We now have 4 listener(s)
08-05 11:23:52.349  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:23:52.350  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:23:52.350  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a22e699 added. We now have 5 listener(s)
08-05 11:23:52.350  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:23:52.351   871  1753 D WifiService: setWifiEnabled: false pid=3843, uid=10000
08-05 11:23:52.351   871  1753 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-05 11:23:52.355  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:23:52.356  2591  2621 D BluetoothAdapterState: Current state: ON, message: 23
08-05 11:23:52.356  2591  2621 D BluetoothAdapterProperties: Setting state to 13
08-05 11:23:52.356  2591  2621 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 11:23:52.356  2591  2621 D BluetoothAdapterProperties: onBluetoothDisable()
08-05 11:23:52.358  2591  2621 I BluetoothAdapterState: Entering PendingCommandState
08-05 11:23:52.358  2591  2591 D BluetoothMapService: onReceive
08-05 11:23:52.358  2591  2591 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:23:52.358  2591  2591 D BluetoothMapService: STATE_TURNING_OFF
08-05 11:23:52.359  2591  2591 D BluetoothMapService: MAP Service closeService in
08-05 11:23:52.359  2591  2591 D BluetoothMapMasInstance0: MAP Service shutdown
08-05 11:23:52.359  2591  2591 D ObexServerSockets0: shutdown(block = true)
08-05 11:23:52.359  2591  2591 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-05 11:23:52.359  2591  2591 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-05 11:23:52.359  2591  2751 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-05 11:23:52.359  2591  2724 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-05 11:23:52.360  2591  2752 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-05 11:23:52.357  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:52.360  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:23:52.360  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:52.360  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:52.360  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:52.360  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:52.360  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:52.360  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:23:52.360  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:23:52.360  2591  2591 I BtOppRfcommListener: stopping Accept Thread
08-05 11:23:52.360  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:52.360  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:52.360  3843  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:23:52.360  2591  3342 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-05 11:23:52.363  2591  3342 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-05 11:23:52.364  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.366  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.368  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:52.368  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:23:52.368  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:52.368  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:52.368  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:52.368  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:52.368  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:52.368  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:23:52.368  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:23:52.369  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-05 11:23:52.369  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:52.369  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:52.371  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.371   871  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 11:23:52.371   871  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-05 11:23:52.371   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-05 11:23:52.371   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 11:23:52.375  2591  2724 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-05 11:23:52.377   871  2014 D DhcpClient: Clearing IP address
,08-05 11:23:52.377   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-05 11:23:52.378   871   884 I ActivityManager: Start proc 3927:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-05 11:23:52.379  2591  2625 D BluetoothAdapterProperties: Scan Mode:20
08-05 11:23:52.379  2591  2621 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-05 11:23:52.379   371   869 D CommandListener: Setting iface cfg
,08-05 11:23:52.381  1508  2301 V NativeCrypto: Read error: ssl=0xaa234e00: I/O error during system call, Connection timed out
,08-05 11:23:52.383  2591  2591 D HeadsetService: Received stop request...Stopping profile...
,08-05 11:23:52.383  1508  2301 V NativeCrypto: SSL shutdown failed: ssl=0xaa234e00: I/O error during system call, Broken pipe
08-05 11:23:52.383  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.385   871   871 D BluetoothHeadset: Proxy object disconnected
08-05 11:23:52.386  2591  2591 D A2dpService: Received stop request...Stopping profile...
08-05 11:23:52.386  2591  2744 D A2dpStateMachine: Exit Disconnected: -1
,08-05 11:23:52.386  1360  1384 D BluetoothHeadset: Proxy object disconnected
08-05 11:23:52.387  1740  1751 D BluetoothHeadset: Proxy object disconnected
08-05 11:23:52.387   871   871 D BluetoothHeadset: Proxy object disconnected
08-05 11:23:52.387   871   871 D BluetoothHeadset: Proxy object disconnected
08-05 11:23:52.387   871   871 D BluetoothA2dp: Proxy object disconnected
,08-05 11:23:52.388  2591  2591 V BluetoothAdapterState: isTurningOff()=true
08-05 11:23:52.388  2591  2591 V BluetoothAdapterState: isTurningOn()=false
08-05 11:23:52.388  2591  2591 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:23:52.388  2591  2591 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:23:52.388  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.388  2591  2591 D HidService: Received stop request...Stopping profile...
08-05 11:23:52.388  2591  2591 D HidService: Stopping Bluetooth HidService
08-05 11:23:52.389   871  1753 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-05 11:23:52.390   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-05 11:23:52.390   871  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-05 11:23:52.390   871  2011 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-05 11:23:52.390   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-05 11:23:52.390  1360  1360 D HeadsetProfile: Bluetooth service disconnected
,08-05 11:23:52.390   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-05 11:23:52.390  1360  1360 D BluetoothA2dp: Proxy object disconnected
08-05 11:23:52.392  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-05 11:23:52.392  1360  1360 D HidProfile: Bluetooth service disconnected
08-05 11:23:52.393   398   398 E Parcel  : Reading a NULL string not supported here.
08-05 11:23:52.395  2591  2591 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 11:23:52.395  2591  2591 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 11:23:52.396  2591  2708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 11:23:52.396  2591  2708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 11:23:52.396  2591  2708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-05 11:23:52.396  2591  2591 D HealthService: Received stop request...Stopping profile...
08-05 11:23:52.396   371   869 D CommandListener: Clearing all IP addresses on wlan0
08-05 11:23:52.397  2591  2625 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-05 11:23:52.397  2591  2625 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-05 11:23:52.398  2591  2591 V BluetoothAdapterState: isTurningOff()=true
,08-05 11:23:52.398  2591  2591 V BluetoothAdapterState: isTurningOn()=false
08-05 11:23:52.398  2591  2591 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:23:52.398  2591  2591 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:23:52.398  2591  2591 D PanService: Received stop request...Stopping profile...
08-05 11:23:52.400  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 11:23:52.400  1360  1360 D PanProfile: Bluetooth service disconnected
08-05 11:23:52.400   871  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-05 11:23:52.402  2591  2591 V BluetoothAdapterState: isTurningOff()=true
,08-05 11:23:52.402  2591  2591 V BluetoothAdapterState: isTurningOn()=false
08-05 11:23:52.402  2591  2591 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:23:52.402  2591  2591 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:23:52.402  2591  2591 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 11:23:52.403  2591  2591 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 11:23:52.403   871  2011 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-05 11:23:52.403  2591  2708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-05 11:23:52.403  2591  2708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-05 11:23:52.403  2591  2708 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:23:52.403  2591  2708 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:23:52.403  2591  2708 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:23:52.403  2591  2708 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 11:23:52.403  2591  2625 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-05 11:23:52.403  2591  2625 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-05 11:23:52.404  2591  2591 D BluetoothMapService: Received stop request...Stopping profile...
08-05 11:23:52.404  2591  2591 D BluetoothMapService: stop()
08-05 11:23:52.404  2591  2591 D BluetoothMapAppObserver: deinitObservers()
,08-05 11:23:52.404  2591  2591 D BluetoothMapAppObserver: removeReceiver()
08-05 11:23:52.406  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:52.406  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:23:52.406  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:52.406  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:52.406  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:23:52.406  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:52.406  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:23:52.406  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:23:52.406  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:23:52.406  2591  2591 V BluetoothAdapterState: isTurningOff()=true
08-05 11:23:52.406  2591  2591 V BluetoothAdapterState: isTurningOn()=false
08-05 11:23:52.406  2591  2591 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:23:52.406  2591  2591 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:23:52.406  2591  2591 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-05 11:23:52.406   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
08-05 11:23:52.407  2591  2625 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-05 11:23:52.407  2591  2591 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 11:23:52.407  2591  2591 V BluetoothAdapterState: isTurningOff()=true
08-05 11:23:52.407  2591  2591 V BluetoothAdapterState: isTurningOn()=false
08-05 11:23:52.407  2591  2591 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:23:52.407  2591  2591 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:23:52.407  2591  2591 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 11:23:52.407  2591  2591 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 11:23:52.408  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:23:52.408  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:23:52.408  1847  2070 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:23:52.409  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:52.409  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:23:52.409  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:52.409  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:52.409  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:23:52.409  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:52.409  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:23:52.409  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:23:52.409  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:23:52.410  2591  2591 D BluetoothMapService: MAP Service closeService in
08-05 11:23:52.410  2591  2591 V BluetoothAdapterState: isTurningOff()=true
08-05 11:23:52.410  2591  2591 V BluetoothAdapterState: isTurningOn()=false
08-05 11:23:52.410  2591  2591 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 11:23:52.410  2591  2591 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:23:52.410  2591  2621 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-05 11:23:52.410  2591  2621 D BluetoothAdapterProperties: Setting state to 15
08-05 11:23:52.411  2591  2621 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-05 11:23:52.411   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:23:52.411  1740  1759 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:23:52.411  1360  1824 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 11:23:52.412  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:52.412  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:23:52.412  1360  1384 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 11:23:52.412  2591  2621 I BluetoothAdapterState: Entering BleOnState
08-05 11:23:52.413   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:23:52.413   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 11:23:52.413  1360  3842 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 11:23:52.413  2591  2591 D BluetoothMapService: cleanup()
08-05 11:23:52.413  2591  2591 D BluetoothMapService: MAP Service closeService in
08-05 11:23:52.415   871  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 11:23:52.415  1360  1373 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 11:23:52.415  1360  1824 D BluetoothPan: onBluetoothStateChange on: false
08-05 11:23:52.415   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:23:52.415  1360  1384 D BluetoothMap: onBluetoothStateChange: up=false
08-05 11:23:52.416  2591  2621 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-05 11:23:52.416  2591  2621 D BluetoothAdapterProperties: Setting state to 16
08-05 11:23:52.416  2591  2621 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-05 11:23:52.417  2591  2621 D BluetoothAdapterProperties: onBleDisable
08-05 11:23:52.417  2591  2621 I BluetoothAdapterState: Entering PendingCommandState
08-05 11:23:52.417  2591  2622 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-05 11:23:52.418  2591  2625 D BluetoothAdapterProperties: Scan Mode:20
08-05 11:23:52.419  2591  2708 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-05 11:23:52.419  2591  2708 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 11:23:52.422  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:52.422  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:23:52.422  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:52.422  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:52.422  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:23:52.422  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:52.422  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:23:52.422  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:23:52.422  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:23:52.423  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.424  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.425  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.427   871  2018 D DhcpClient: Receive thread stopped
,08-05 11:23:52.453  3927  3927 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-05 11:23:52.454   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 11:23:52.463  3927  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 11:23:52.468  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:23:52.471   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a6d917:true
,08-05 11:23:52.472   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 11:23:52.473   871  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-05 11:23:52.473   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:23:52.482   871  1521 I ActivityManager: Start proc 3944:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-05 11:23:52.485   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-05 11:23:52.486  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.486  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:23:52.499  3927  3927 D LocalBluetoothProfileManager: Adding local MAP profile
,08-05 11:23:52.509  3927  3927 D BluetoothMap: Create BluetoothMap proxy object
,08-05 11:23:52.515  3927  3927 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-05 11:23:52.519  3944  3944 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-05 11:23:52.525   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-05 11:23:52.525   871  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-05 11:23:52.529  3927  3927 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:23:52.540   871  1753 I ActivityManager: Killing 3504:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-05 11:23:52.623  2591  2625 I bt_hci  : shut_down
,08-05 11:23:52.624  2591  2629 D bt_hwcfg: hw_epilog_process
,08-05 11:23:52.625  2591  2629 I bt_vendor: low_power_mode_cb
,08-05 11:23:52.651  2591  2629 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-05 11:23:52.651  2591  2629 I bt_vendor: epilog_cb
08-05 11:23:52.651  2591  2629 I bt_hci  : epilog_finished_callback
,08-05 11:23:52.656  3944  3944 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.io.File.exists(File.java:361)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-05 11:23:52.656  3944  3944 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:23:52.656  3944  3944 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:23:52.656  3944  3944 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.r.e.b(PG:170)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:23:52.656  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:23:52.657  3944  3944 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.r.k.d(PG:583)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.r.e.b(PG:170)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:23:52.657  3944  3944 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.io.File.exists(File.java:361)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:23:52.657  3944  3944 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.io.File.exists(File.java:361)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:23:52.657  3944  3944 D StrictMode: StrictMode policy violation; ~duration=50 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:23:52.657  3944  3944 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:23:52.658  2591  2625 I bt_hci_h4: hal_close
08-05 11:23:52.659  2591  2625 I bt_userial_vendor: device fd = 51 close
08-05 11:23:52.676   871  1888 I ActivityManager: Start proc 3977:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-05 11:23:52.677   871  1888 I ActivityManager: Killing 3374:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-05 11:23:52.748  3977  3977 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-05 11:23:52.780  2591  2622 D bt_stack_manager: event_shut_down_stack finished.
,08-05 11:23:52.781  2591  2621 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-05 11:23:52.785  2591  2621 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-05 11:23:52.785  2591  2591 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 11:23:52.786  2591  2591 D BtGatt.GattService: Received stop request...Stopping profile...
,08-05 11:23:52.786  2591  2591 D BtGatt.GattService: stop()
08-05 11:23:52.787  2591  2591 D BtGatt.AdvertiseManager: advertise clients cleared
,08-05 11:23:52.790  2591  2591 V BluetoothAdapterState: isTurningOff()=false
,08-05 11:23:52.790  2591  2591 V BluetoothAdapterState: isTurningOn()=false
08-05 11:23:52.791  2591  2591 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 11:23:52.791  2591  2591 V BluetoothAdapterState: isBleTurningOff()=true
,08-05 11:23:52.792  2591  2621 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-05 11:23:52.792  2591  2621 D BluetoothAdapterProperties: Setting state to 10
08-05 11:23:52.792  2591  2621 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-05 11:23:52.793  2591  2621 I BluetoothAdapterState: Entering OffState
,08-05 11:23:52.794   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-05 11:23:52.805  3843  3843 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 11:23:52.806  2591  2591 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-05 11:23:52.806  2591  2591 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-05 11:23:52.806  2591  2591 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-05 11:23:52.806  2591  2622 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-05 11:23:52.809  2591  2622 D bt_stack_manager: event_clean_up_stack finished.
,08-05 11:23:52.821  2591  2591 I art     : System.exit called, status: 0
,08-05 11:23:52.822  2591  2591 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-05 11:23:52.881   871  1888 I ActivityManager: Process com.android.bluetooth (pid 2591) has died
,08-05 11:23:52.935  3977  3996 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-05 11:23:52.935  3977  3996 I Babel_SMS: MmsConfig.loadMmsSettings
08-05 11:23:52.936  3977  3996 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-05 11:23:52.936  3977  3996 I Babel_SMS: MmsConfig.loadFromDatabase
,08-05 11:23:52.981  3977  3996 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-05 11:23:52.982  3977  3996 I Babel_SMS: MmsConfig.loadFromResources
08-05 11:23:52.982  3977  3996 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-05 11:23:52.983  3977  3996 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-05 11:23:53.068  3977  3977 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 11:23:53.076  3977  3977 I Babel_Crash: startup - clean
,08-05 11:23:53.114  3977  3977 I Babel_telephony: TeleModule.launchCompleted
,08-05 11:23:53.128   871   881 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-05 11:23:53.171  3977  3977 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-05 11:23:53.182  3977  3977 W Babel   : BAM#gBA: invalid account id: -1
,08-05 11:23:53.183  3977  3977 W Babel   : BAM#gBA: invalid account id: -1
08-05 11:23:53.183  3977  3977 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-05 11:23:53.196  3977  4003 I Babel   : deleted: false for 0
,08-05 11:23:53.226   871  1752 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-05 11:23:53.313  3927  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 11:23:53.331   871   882 I ActivityManager: Start proc 4007:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-05 11:23:53.373  3927  3927 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:23:53.410  3977  3977 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 11:23:53.468  4007  4007 D AdapterServiceConfig: Adding HeadsetService
08-05 11:23:53.469  4007  4007 D AdapterServiceConfig: Adding A2dpService
,08-05 11:23:53.469  4007  4007 D AdapterServiceConfig: Adding HidService
08-05 11:23:53.469  4007  4007 D AdapterServiceConfig: Adding HealthService
,08-05 11:23:53.469  4007  4007 D AdapterServiceConfig: Adding PanService
08-05 11:23:53.469  4007  4007 D AdapterServiceConfig: Adding GattService
08-05 11:23:53.469  4007  4007 D AdapterServiceConfig: Adding BluetoothMapService
,08-05 11:23:53.473  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:23:53.371  3944  3965 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.,
,08-05 11:23:53.503  1865  1865 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-05 11:23:53.521  1865  1865 D SystemUpdateService: onCreate
,08-05 11:23:53.536  1865  1865 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-05 11:23:53.556  1865  4019 I SystemUpdateService: active receiver: enabled
,08-05 11:23:53.559  3977  3977 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 11:23:53.560  1865  4019 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-05 11:23:53.561  1865  4019 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-05 11:23:53.561  1865  1865 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-05 11:23:53.565  1865  4019 I SystemUpdateService: now status is 0 (complete)
,08-05 11:23:53.566  1865  4019 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-05 11:23:53.566  1865  4019 I SystemUpdateService: file has been verified
08-05 11:23:53.566  1865  4019 I SystemUpdateService: OTA package size = 12249756
,08-05 11:23:53.567  1865  1865 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-05 11:23:53.569  1865  1865 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-05 11:23:53.570  1865  2354 I iu.UploadsManager: num queued entries: 0
,08-05 11:23:53.572  1865  2354 I iu.UploadsManager: num updated entries: 0
,08-05 11:23:53.573  1865  4019 I SystemUpdateService: showing system update notification
,08-05 11:23:53.575  1865  2354 I iu.SyncManager: NEXT; no task
,08-05 11:23:53.578  3977  3977 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 11:23:53.580  3977  3977 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 11:23:53.592  3977  3977 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 11:23:53.596   871  1521 I ActivityManager: Start proc 4021:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-05 11:23:53.598  1865  1865 D SystemUpdateService: onDestroy
,08-05 11:23:53.601  3977  3977 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 11:23:53.608   871  1887 I ActivityManager: Killing 3426:android.process.acore/u0a5 (adj 15): empty #17
,08-05 11:23:53.627   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7ab8e8:true
,08-05 11:23:53.649  3977  3977 I vclib   : onServiceConnected
,08-05 11:23:53.660  4021  4021 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-05 11:23:53.662  4021  4021 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:23:53.675  4021  4021 D SprintDMHelper: simOperator: 
,08-05 11:23:53.675  4021  4021 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-05 11:23:53.712   871  1687 I ActivityManager: Start proc 4033:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-05 11:23:53.713   871  1687 I ActivityManager: Killing 3689:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-05 11:23:53.863   871  1367 I ActivityManager: Start proc 4048:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-05 11:23:53.866  3977  4047 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-05 11:23:53.872   871  1889 I ActivityManager: Killing 3704:com.android.musicfx/u0a18 (adj 15): empty #17
,08-05 11:23:53.954  4048  4048 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-05 11:23:54.023  4048  4048 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-05 11:23:54.023  4048  4048 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-05 11:23:54.023  4048  4048 I GAv4    :   adb logcat -s GAv4
,08-05 11:23:54.036  4048  4048 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-05 11:23:54.041  4048  4048 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-05 11:23:54.069  4048  4067 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-05 11:23:54.174  4048  4048 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-05 11:23:54.214  4048  4048 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-05 11:23:54.223  4048  4048 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7292-7295)
,08-05 11:23:54.223  4048  4048 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 11:23:54.236  4048  4048 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5cd9723}
,08-05 11:23:54.237  4048  4048 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 11:23:54.237  4048  4048 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 11:23:54.246  4048  4048 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-05 11:23:54.251  4048  4048 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-05 11:23:54.267  4048  4048 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-05 11:23:54.283  4048  4048 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-05 11:23:54.284  4048  4048 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-05 11:23:54.284  4048  4048 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-05 11:23:54.284  4048  4048 I Adreno  : Build Date                       : 10/20/15
08-05 11:23:54.284  4048  4048 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-05 11:23:54.284  4048  4048 I Adreno  : Local Branch                     : M14
08-05 11:23:54.284  4048  4048 I Adreno  : Remote Branch                    : 
08-05 11:23:54.284  4048  4048 I Adreno  : Remote Branch                    : 
08-05 11:23:54.284  4048  4048 I Adreno  : Reconstruct Branch               : 
,08-05 11:23:54.345  4048  4048 I NSApplication: Starting up...
,08-05 11:23:54.355  4048  4096 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-05 11:23:54.385   871  1690 I ActivityManager: Start proc 4101:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-05 11:23:54.388   871  1690 I ActivityManager: Killing 2035:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-05 11:23:54.491  4101  4101 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-05 11:23:54.680   871   882 I ActivityManager: Killing 3655:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-05 11:23:55.363   871  1521 D WifiService: setWifiEnabled: true pid=3843, uid=10000
08-05 11:23:55.363   871  1521 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:23:55.380   871  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-05 11:23:55.389  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:23:55.390  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:23:55.390  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:55.390  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:55.390  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:55.390  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:55.390  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:23:55.390  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:23:55.390  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:23:55.390  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:55.390  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:23:55.396  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:23:55.396  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:23:55.396  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:55.396  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:55.396  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:55.396  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:55.396  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:23:55.396  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:23:55.396  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:23:55.396  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:55.397  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:23:55.413   871  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-05 11:23:55.413   871  1304 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-05 11:23:55.414   871  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-05 11:23:55.415   871  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-05 11:23:55.416   871  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-05 11:23:55.416   871  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-05 11:23:55.416   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-05 11:23:55.416   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-05 11:23:55.433   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-05 11:23:55.434   371   869 D CommandListener: Setting iface cfg
,08-05 11:23:55.435   871  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
08-05 11:23:55.435   871  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-05 11:23:55.435   871  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=15.00 rxSuccessRate=19.75 delta 1000 -> 994
,08-05 11:23:55.437   871  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-05 11:23:55.438   871  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-05 11:23:55.457   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-05 11:23:55.457   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 11:23:55.464   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-05 11:23:55.519   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-05 11:23:55.525  1454  1454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-05 11:23:55.947  1454  1454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 11:23:55.987  1454  1454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-05 11:23:55.988  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-05 11:23:55.997   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-05 11:23:56.013   871  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-05 11:23:56.015   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-05 11:23:56.015   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 11:23:56.043   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 11:23:56.062   371   869 D CommandListener: Setting iface cfg
08-05 11:23:56.064   871  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,08-05 11:23:56.082   871  1306 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-05 11:23:56.083   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-05 11:23:56.095   871  4124 D DhcpClient: Receive thread started
,08-05 11:23:56.177   871  1304 E native  : do suspend false
,08-05 11:23:56.196   871  2014 D DhcpClient: Broadcasting DHCPDISCOVER
,08-05 11:23:56.209   871  4124 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172674, domain null
,08-05 11:23:56.210   871  2014 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172674 seconds
,08-05 11:23:56.214   871  2014 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-05 11:23:56.227   871  4124 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-05 11:23:56.228   871  2014 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-05 11:23:56.232   371   869 D CommandListener: Setting iface cfg
,08-05 11:23:56.245   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-05 11:23:56.245   871  2014 D DhcpClient: Scheduling renewal in 86399s
,08-05 11:23:56.263   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-05 11:23:56.266   871  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,08-05 11:23:56.267   871  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-05 11:23:56.268   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-05 11:23:56.275   871  1306 D ConnectivityService: Adding iface wlan0 to network 101
,08-05 11:23:56.290   871  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-05 11:23:56.330   871  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-05 11:23:56.330   871  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-05 11:23:56.334   871  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-05 11:23:56.337   871  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-05 11:23:56.341   871  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-05 11:23:56.360   871  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-05 11:23:56.373   871  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-05 11:23:56.373   871  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-05 11:23:56.373   871  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-05 11:23:56.373   871  1306 D ConnectivityService:    accepting network in place of null
,08-05 11:23:56.373   871  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-05 11:23:56.374   871  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-05 11:23:56.374   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-05 11:23:56.385   871  4123 D NetlinkSocketObserver: NeighborEvent{elapsedMs=149457, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:23:56.422   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 11:23:56.460   871  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-05 11:23:56.491   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 11:23:56.496   871  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-05 11:23:56.496   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:23:56.503   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-05 11:23:56.513   871  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-05 11:23:56.513  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:23:56.514  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:23:56.514  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:56.514  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:56.514  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:56.514  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:56.514  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:56.514  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:23:56.514  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:23:56.514  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:56.514  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:23:56.523  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:56.523  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:23:56.523  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:56.523  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:56.523  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:23:56.523  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:56.523  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:23:56.523  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:23:56.523  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:23:56.523  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:56.523  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:23:56.534  1865  1865 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-05 11:23:56.537  1865  1865 D SystemUpdateService: onCreate
,08-05 11:23:56.541  1865  1865 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-05 11:23:56.543  1865  4136 I SystemUpdateService: active receiver: enabled
,08-05 11:23:56.546  1865  4136 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-05 11:23:56.549  1865  4136 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
,08-05 11:23:56.551  1865  4136 I SystemUpdateService: now status is 0 (complete)
,08-05 11:23:56.552  1865  4136 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-05 11:23:56.552  1865  4136 I SystemUpdateService: file has been verified
08-05 11:23:56.553  1865  4136 I SystemUpdateService: OTA package size = 12249756
,08-05 11:23:56.558   871  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 09:23:56 GMT], X-Android-Received-Millis=[1470389036557], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470389036518]}
,08-05 11:23:56.559   871  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-05 11:23:56.559   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-05 11:23:56.559   871  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-05 11:23:56.560   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 11:23:56.561  1865  4136 I SystemUpdateService: showing system update notification
,08-05 11:23:56.563  1865  1865 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-05 11:23:56.568  1865  2354 I iu.UploadsManager: num queued entries: 0
,08-05 11:23:56.571  1865  1865 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-05 11:23:56.571  1865  2354 I iu.UploadsManager: num updated entries: 0
,08-05 11:23:56.572  1865  1865 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-05 11:23:56.573  1865  4140 I MDM     : [213] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-05 11:23:56.574  1865  4140 W BaseAppContext: Using Auth Proxy for data requests.
08-05 11:23:56.574  4021  4021 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:23:56.575  1865  2354 I iu.SyncManager: NEXT; no task
,08-05 11:23:56.575  1865  4140 V GoogleAuthProtoRequest: [213] a.<init>: mAccountName set to: thalitester@gmail.com
,08-05 11:23:56.579  4021  4021 D SprintDMHelper: simOperator: 
,08-05 11:23:56.579  4021  4021 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-05 11:23:56.585  1865  1865 D SystemUpdateService: onDestroy
,08-05 11:23:56.588  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:23:56.591  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:23:56.627  1508  2353 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-05 11:23:56.627  1508  2353 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-05 11:23:56.627  1508  2353 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:23:56.627  1508  2353 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:23:56.644  1865  4140 E MDM     : [213] SitrepService.a: Error sending sitrep.
,08-05 11:23:56.744  3977  4143 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-05 11:23:56.869   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-05 11:23:56.884  1655  1655 I Keyboard.Facilitator: onFinishInput()
,08-05 11:23:56.891   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-05 11:23:56.891   871   891 I Adreno  : Build Date                       : 10/20/15
08-05 11:23:56.891   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-05 11:23:56.891   871   891 I Adreno  : Local Branch                     : M14
08-05 11:23:56.891   871   891 I Adreno  : Remote Branch                    : 
08-05 11:23:56.891   871   891 I Adreno  : Remote Branch                    : 
08-05 11:23:56.891   871   891 I Adreno  : Reconstruct Branch               : 
,08-05 11:23:56.924   281   390 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (164 us)
,08-05 11:23:57.497   871  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-05 11:23:57.518  3843  3843 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-05 11:23:57.518  3843  3843 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-05 11:23:57.553   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-05 11:23:57.555  3843  3843 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bf914ad Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9b6b53f, 16908290=android.view.AbsSavedState$1@9b6b53f}, android:focusedViewId=100}]}]
08-05 11:23:57.555  3843  3843 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-05 11:23:57.555  3843  3843 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-05 11:23:57.555  3843  3843 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-05 11:23:57.556   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
08-05 11:23:57.559   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-05 11:23:57.560   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-05 11:23:57.560   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-05 11:23:57.608   871   880 I art     : Background partial concurrent mark sweep GC freed 36037(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 834us total 109.939ms
,08-05 11:23:57.787   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-05 11:23:57.790   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-05 11:23:57.794   871  1328 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
,08-05 11:23:57.798   871   891 I DreamManagerService: Entering dreamland.
,08-05 11:23:57.799   871   891 I PowerManagerService: Dozing...
08-05 11:23:57.800   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-05 11:23:57.847   375  1677 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-05 11:23:57.848   375  1677 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-05 11:23:57.857   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-05 11:23:57.858  1722  4155 D NfcService: Discovery configuration equal, not updating.
,08-05 11:23:57.869   871  1304 E native  : do suspend false
,08-05 11:23:57.884   871  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,08-05 11:23:57.894   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-05 11:23:57.896   871  1304 E native  : do suspend true
,08-05 11:23:57.988   375  1274 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-05 11:23:57.988   375  1274 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-05 11:23:58.372   871  1521 D WifiService: setWifiEnabled: false pid=3843, uid=10000
,08-05 11:23:58.373   871  1521 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:23:58.390   871  1753 I ActivityManager: Killing 3733:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-05 11:23:58.392  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-05 11:23:58.395   871  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-05 11:23:58.396   871  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-05 11:23:58.396   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-05 11:23:58.396   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 11:23:58.413   871  1304 E native  : do suspend true
,08-05 11:23:58.423   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-05 11:23:58.423   871  2014 D DhcpClient: Clearing IP address
,08-05 11:23:58.426   371   869 D CommandListener: Setting iface cfg
,08-05 11:23:58.428  1508  4149 V NativeCrypto: Read error: ssl=0x9ae0d400: I/O error during system call, Connection timed out
,08-05 11:23:58.431  1508  4149 V NativeCrypto: SSL shutdown failed: ssl=0x9ae0d400: I/O error during system call, Broken pipe
,08-05 11:23:58.435   871  1887 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-05 11:23:58.435   871  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-05 11:23:58.436   871  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-05 11:23:58.440   871  4122 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:401b:801::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-05 11:23:58.440   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,08-05 11:23:58.441   871  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-05 11:23:58.442   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-05 11:23:58.454   871  4124 D DhcpClient: Receive thread stopped
,08-05 11:23:58.490   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-05 11:23:58.490   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-05 11:23:58.490   871  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-05 11:23:58.494   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-05 11:23:58.494   871  1304 E native  : do suspend true
,08-05 11:23:58.500   398   398 E Parcel  : Reading a NULL string not supported here.
,08-05 11:23:58.506   371   869 D CommandListener: Clearing all IP addresses on wlan0
,08-05 11:23:58.513   871  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-05 11:23:58.513   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-05 11:23:58.530   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-05 11:23:58.532  1847  2070 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 11:23:58.533  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:58.533  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:23:58.533  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:58.533  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:58.533  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:23:58.533  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:58.533  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:23:58.533  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:23:58.533  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:23:58.533  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:23:58.533  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:23:58.534   871  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-05 11:23:58.535  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:23:58.535  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:23:58.535  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:23:58.535  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:23:58.535  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:23:58.535  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:23:58.535  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:23:58.535  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:23:58.535  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:23:58.535  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:23:58.535  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:23:58.561   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 11:23:58.582   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 11:23:58.583   871  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-05 11:23:58.583   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:23:58.586   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-05 11:23:58.593  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:23:58.593  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:23:58.607  1865  1865 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-05 11:23:58.610  1865  1865 D SystemUpdateService: onCreate
,08-05 11:23:58.618  1865  1865 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-05 11:23:58.637  1865  4168 I SystemUpdateService: active receiver: enabled
,08-05 11:23:58.638  1865  1865 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-05 11:23:58.640  1865  2354 I iu.UploadsManager: num queued entries: 0
08-05 11:23:58.640  1865  2354 I iu.UploadsManager: num updated entries: 0
08-05 11:23:58.641  1865  2354 I iu.SyncManager: NEXT; no task
08-05 11:23:58.644  1865  4168 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-05 11:23:58.646  1865  1865 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-05 11:23:58.648  1865  1865 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-05 11:23:58.650  4021  4021 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:23:58.654  4021  4021 D SprintDMHelper: simOperator: 
,08-05 11:23:58.654  4021  4021 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-05 11:23:58.660  1865  4168 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,08-05 11:23:58.669  1865  4168 I SystemUpdateService: now status is 0 (complete)
,08-05 11:23:58.675   371   869 E Netd    : netlink response contains error (No such file or directory)
,08-05 11:23:58.676   871  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-05 11:23:58.679  1865  4168 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-05 11:23:58.679  1865  4168 I SystemUpdateService: file has been verified
08-05 11:23:58.679  1865  4168 I SystemUpdateService: OTA package size = 12249756
,08-05 11:23:58.682  3977  4171 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-05 11:23:58.721  1865  4168 I SystemUpdateService: showing system update notification
,08-05 11:23:58.744  1865  1865 D SystemUpdateService: onDestroy
,08-05 11:24:01.409   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@efefb23:true
,08-05 11:24:01.410  4007  4007 D BluetoothAdapterState: make() - Creating AdapterState
,08-05 11:24:01.419  4007  4173 I BluetoothAdapterState: Entering OffState
,08-05 11:24:01.419  4007  4007 I bt_bluedroid: init
,08-05 11:24:01.422  4007  4174 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-05 11:24:01.422  4007  4174 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-05 11:24:01.422  4007  4174 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-05 11:24:01.422  4007  4174 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-05 11:24:01.423  4007  4007 I bt_bluedroid: get_profile_interface socket
,08-05 11:24:01.429  4007  4177 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-05 11:24:01.429  4007  4007 I bt_bluedroid: get_profile_interface sdp
,08-05 11:24:01.432  4007  4177 D BluetoothAdapterProperties: Name is: Nexus 6
,08-05 11:24:01.440  4007  4017 I bt_bluedroid: config_hci_snoop_log
,08-05 11:24:01.441   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-05 11:24:01.447  4007  4173 D BluetoothAdapterState: Current state: OFF, message: 0
,08-05 11:24:01.447  4007  4173 D BluetoothAdapterProperties: Setting state to 14
08-05 11:24:01.448  4007  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-05 11:24:01.449  4007  4173 D BluetoothBondStateMachine: make
,08-05 11:24:01.451  4007  4178 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-05 11:24:01.455  4007  4173 I BluetoothAdapterState: Entering PendingCommandState
,08-05 11:24:01.458  4007  4007 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-05 11:24:01.465  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:01.467  4007  4007 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 11:24:01.468  4007  4007 D BtGatt.GattService: Received start request. Starting profile...
,08-05 11:24:01.469  4007  4007 D BtGatt.GattService: start()
08-05 11:24:01.469  4007  4007 I bt_bluedroid: get_profile_interface gatt
,08-05 11:24:01.471  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:01.471  4007  4007 D BtGatt.AdvertiseManager: advertise manager created
,08-05 11:24:01.483  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,08-05 11:24:01.483  4007  4007 V BluetoothAdapterState: isTurningOn()=false
,08-05 11:24:01.483  4007  4007 V BluetoothAdapterState: isBleTurningOn()=true
,08-05 11:24:01.483  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false,
,08-05 11:24:01.484  4007  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-05 11:24:01.485  4007  4173 I bt_bluedroid: enable
08-05 11:24:01.485  4007  4174 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-05 11:24:01.486  4007  4174 I bt_hci  : start_up
,08-05 11:24:01.503  4007  4174 I bt_vendor: alloc value 0xb39cb189
08-05 11:24:01.503  4007  4174 I bt_vendor: init
08-05 11:24:01.503  4007  4174 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-05 11:24:01.503  4007  4174 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-05 11:24:01.611  4007  4174 D bt_hci  : start_up starting async portion
,08-05 11:24:01.612  4007  4181 I bt_hci  : event_finish_startup
,08-05 11:24:01.612  4007  4181 I bt_hci_h4: hal_open
,08-05 11:24:01.612  4007  4181 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-05 11:24:01.625  4007  4181 I bt_userial_vendor: device fd = 51 open
,08-05 11:24:01.652  4007  4181 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 11:24:01.684  4007  4181 D bt_hwcfg: Chipset BCM4354A2
,08-05 11:24:01.684  4007  4181 D bt_hwcfg: Target name = [BCM4354A2]
,08-05 11:24:01.685  4007  4181 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-05 11:24:02.367  4007  4181 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-05 11:24:02.369  4007  4181 D bt_hwcfg: Settlement delay -- 100 ms
,08-05 11:24:02.369  4007  4181 I bt_hwcfg: Setting fw settlement delay to 100 
,08-05 11:24:02.486  4007  4181 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 11:24:02.487  4007  4181 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-05 11:24:02.517  4007  4181 I bt_hwcfg: vendor lib fwcfg completed
,08-05 11:24:02.517  4007  4181 I bt_vendor: firmware callback
08-05 11:24:02.517  4007  4181 I bt_hci  : firmware_config_callback
,08-05 11:24:02.529  4007  4183 I bt_btu  : btu_task pending for preload complete event
,08-05 11:24:02.529  4007  4183 I bt_btu_task: Bluetooth chip preload is complete
08-05 11:24:02.529  4007  4183 I bt_btu  : btu_task received preload complete event
,08-05 11:24:02.540  4007  4183 I         : BTE_InitTraceLevels -- TRC_HCI
,08-05 11:24:02.540  4007  4183 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 11:24:02.540  4007  4183 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-05 11:24:02.541  4007  4183 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 11:24:02.541  4007  4183 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-05 11:24:02.541  4007  4183 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 11:24:02.542  4007  4183 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 11:24:02.542  4007  4183 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 11:24:02.542  4007  4183 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 11:24:02.542  4007  4183 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 11:24:02.543  4007  4183 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 11:24:02.543  4007  4183 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 11:24:02.543  4007  4183 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 11:24:02.543  4007  4183 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 11:24:02.544  4007  4183 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-05 11:24:02.648  1847  2575 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-05 11:24:02.678  4007  4183 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3948d9d,
,08-05 11:24:02.679  4007  4183 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3948d9d 
,08-05 11:24:02.687  4007  4177 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-05 11:24:02.691  4007  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-05 11:24:02.692  4007  4177 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-05 11:24:02.699  4007  4177 D BluetoothAdapterProperties: Name is: Nexus 6
,08-05 11:24:02.704  4007  4177 D BluetoothAdapterProperties: Scan Mode:20
,08-05 11:24:02.705  4007  4177 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-05 11:24:02.706  4007  4177 D bt_hci  : do_postload posting postload work item
,08-05 11:24:02.706  4007  4181 I bt_hci  : event_postload
,08-05 11:24:02.707  4007  4181 I bt_vendor: sco_config_cb
08-05 11:24:02.707  4007  4181 I bt_hci  : sco_config_callback postload finished.
08-05 11:24:02.708  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:24:02.709  4007  4181 I bt_vendor: low_power_mode_cb
08-05 11:24:02.710  4007  4177 D bt_bte_conf: Device ID record 1 : primary
,08-05 11:24:02.711  4007  4177 D bt_bte_conf:   vendorId            = 000f
08-05 11:24:02.711  4007  4177 D bt_bte_conf:   vendorIdSource      = 0001
08-05 11:24:02.711  4007  4177 D bt_bte_conf:   product             = 1200
,08-05 11:24:02.711  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:24:02.711  4007  4177 D bt_bte_conf:   version             = 1436
08-05 11:24:02.711  4007  4177 D bt_bte_conf:   clientExecutableURL = 
08-05 11:24:02.712  4007  4177 D bt_bte_conf:   serviceDescription  = 
,08-05 11:24:02.712  4007  4177 D bt_bte_conf:   documentationURL    = 
08-05 11:24:02.712  4007  4177 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-05 11:24:02.712  4007  4174 D bt_stack_manager: event_start_up_stack finished
08-05 11:24:02.713  4007  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-05 11:24:02.714  4007  4173 D BluetoothAdapterProperties: Setting state to 15
,08-05 11:24:02.714  4007  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-05 11:24:02.715  4007  4173 I BluetoothAdapterState: Entering BleOnState
,08-05 11:24:02.722  4007  4173 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-05 11:24:02.722  4007  4173 D BluetoothAdapterProperties: Setting state to 11
08-05 11:24:02.722  4007  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-05 11:24:02.732  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:02.733  4007  4007 D HeadsetService: Received start request. Starting profile...
,08-05 11:24:02.737  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:02.738  4007  4007 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-05 11:24:02.738  4007  4007 D HeadsetStateMachine: make
,08-05 11:24:02.742  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:02.758  4007  4007 D HeadsetStateMachine: max_hf_connections = 1
,08-05 11:24:02.758  4007  4007 I bt_bluedroid: get_profile_interface handsfree
,08-05 11:24:02.758  4007  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-05 11:24:02.759  4007  4177 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-05 11:24:02.763  4007  4173 I BluetoothAdapterState: Entering PendingCommandState
,08-05 11:24:02.764  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:02.765  4007  4007 D A2dpService: Received start request. Starting profile...
,08-05 11:24:02.766  4007  4007 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-05 11:24:02.766  4007  4007 I bt_bluedroid: get_profile_interface avrcp,
,08-05 11:24:02.774  4007  4007 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-05 11:24:02.774  4007  4007 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 11:24:02.774  4007  4007 D A2dpStateMachine: make
,08-05 11:24:02.777  4007  4007 I bt_bluedroid: get_profile_interface a2dp
,08-05 11:24:02.778  4007  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-05 11:24:02.780  4007  4193 D A2dpStateMachine: Enter Disconnected: -2
,08-05 11:24:02.782  4007  4007 I BluetoothHidServiceJni: classInitNative: succeeds
,08-05 11:24:02.783  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:02.785  3927  3927 D BluetoothInputDevice: Proxy object connected
,08-05 11:24:02.785  4007  4007 D HidService: Received start request. Starting profile...
,08-05 11:24:02.785  4007  4007 I bt_bluedroid: get_profile_interface hidhost
,08-05 11:24:02.785  4007  4177 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb392a3e5
,08-05 11:24:02.785  3927  3927 D HidProfile: Bluetooth service connected
,08-05 11:24:02.786  4007  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-05 11:24:02.786  4007  4007 D HidService: setHidService(): set to: null
,08-05 11:24:02.787  4007  4007 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-05 11:24:02.789  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:24:02.789  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:02.789  4007  4007 D HealthService: Received start request. Starting profile...
,08-05 11:24:02.791  4007  4007 I bt_bluedroid: get_profile_interface health
,08-05 11:24:02.793  4007  4007 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-05 11:24:02.793  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
08-05 11:24:02.795  4007  4007 D PanService: Received start request. Starting profile...
08-05 11:24:02.795  3927  3927 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 11:24:02.795  4007  4007 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 11:24:02.795  4007  4007 I bt_bluedroid: get_profile_interface pan
,08-05 11:24:02.796  3927  3927 D PanProfile: Bluetooth service connected
08-05 11:24:02.796  4007  4177 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-05 11:24:02.799  4007  4007 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:02.801  4007  4007 D BluetoothMapService: Received start request. Starting profile...
08-05 11:24:02.801  4007  4007 D BluetoothMapService: start()
08-05 11:24:02.801  3927  3927 D BluetoothMap: Proxy object connected
08-05 11:24:02.802  3927  3927 D MapProfile: Bluetooth service connected
,08-05 11:24:02.802  3927  3927 D BluetoothMap: getConnectedDevices()
08-05 11:24:02.803  3927  3927 D BluetoothMap: Bluetooth is Not enabled
08-05 11:24:02.804  4007  4007 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-05 11:24:02.805  4007  4007 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-05 11:24:02.805  4007  4007 D BluetoothMapAppObserver: createReceiver()
08-05 11:24:02.806  4007  4007 D BluetoothMapAppObserver: initObservers()
,08-05 11:24:02.806  4007  4007 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-05 11:24:02.813  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,08-05 11:24:02.813  4007  4007 V BluetoothAdapterState: isTurningOn()=true
08-05 11:24:02.813  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:02.813  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:02.815  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,08-05 11:24:02.815  4007  4007 V BluetoothAdapterState: isTurningOn()=true
08-05 11:24:02.815  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:02.816  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:24:02.816  4007  4191 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-05 11:24:02.816  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,08-05 11:24:02.816  4007  4007 V BluetoothAdapterState: isTurningOn()=true
,08-05 11:24:02.816  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:02.816  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:24:02.818  4007  4007 V BluetoothAdapterState: isTurningOff()=false
08-05 11:24:02.819  4007  4007 V BluetoothAdapterState: isTurningOn()=true
08-05 11:24:02.819  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:02.819  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:24:02.820  4007  4007 V BluetoothAdapterState: isTurningOff()=false
08-05 11:24:02.820  4007  4007 V BluetoothAdapterState: isTurningOn()=true
08-05 11:24:02.820  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:02.820  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:02.821  4007  4007 V BluetoothAdapterState: isTurningOff()=false
08-05 11:24:02.822  4007  4007 V BluetoothAdapterState: isTurningOn()=true
08-05 11:24:02.822  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:02.822  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:02.823  4007  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-05 11:24:02.823  4007  4173 D BluetoothAdapterProperties: ScanMode =  20
,08-05 11:24:02.824  4007  4173 D BluetoothAdapterProperties: State =  11
,08-05 11:24:02.825  4007  4177 D BluetoothAdapterProperties: Scan Mode:21
08-05 11:24:02.826  4007  4173 D BluetoothAdapterProperties: Setting state to 12
08-05 11:24:02.826  4007  4177 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 11:24:02.826  4007  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 11:24:02.827   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:24:02.828  3927  3938 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 11:24:02.828  4007  4173 I BluetoothAdapterState: Entering OnState
,08-05 11:24:02.829  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:24:02.829  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:02.829  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:02.829  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:24:02.829  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:02.829  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:24:02.829  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:24:02.829  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:24:02.831  1740  1917 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:24:02.832  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:24:02.832  1360  3842 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 11:24:02.835  3927  3939 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 11:24:02.835  3927  3938 D BluetoothMap: onBluetoothStateChange: up=true
08-05 11:24:02.835  4007  4007 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-05 11:24:02.836  1360  1373 D BluetoothPbap: onBluetoothStateChange: up=true
,08-05 11:24:02.836  4007  4007 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-05 11:24:02.837   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:24:02.837  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:24:02.837  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:02.837  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:02.837  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:24:02.837  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:02.837  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:24:02.837  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:24:02.837  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:24:02.838  3927  3939 D BluetoothPan: onBluetoothStateChange on: true
08-05 11:24:02.838   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 11:24:02.839  1360  1384 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 11:24:02.840  4007  4007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:24:02.841  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:24:02.842  1360  3842 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:24:02.842  1360  1360 D BluetoothInputDevice: Proxy object connected
08-05 11:24:02.842  1360  1360 D HidProfile: Bluetooth service connected
,08-05 11:24:02.843  1360  1373 D BluetoothPan: onBluetoothStateChange on: true
08-05 11:24:02.843  4007  4007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:24:02.845  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 11:24:02.845  1360  1360 D PanProfile: Bluetooth service connected
,08-05 11:24:02.848   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:24:02.848  1360  3842 D BluetoothMap: onBluetoothStateChange: up=true
,08-05 11:24:02.848  4007  4007 D ObexServerSockets: Succeed to create listening sockets 
,08-05 11:24:02.849  4007  4007 D ObexServerSockets0: startAccept()
,08-05 11:24:02.849  4007  4007 D ObexServerSockets0: prepareForNewConnect()
,08-05 11:24:02.851  4007  4007 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-05 11:24:02.851  4007  4007 D BluetoothSdpJni: SDP Create record success - handle: 0,
,08-05 11:24:02.851  1360  1360 D BluetoothMap: Proxy object connected
,08-05 11:24:02.851  1360  1360 D MapProfile: Bluetooth service connected
,08-05 11:24:02.852  1360  1360 D BluetoothMap: getConnectedDevices()
,08-05 11:24:02.853   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
08-05 11:24:02.854  4007  4199 D ObexServerSockets0: Accepting socket connection...
,08-05 11:24:02.855  4007  4198 D ObexServerSockets0: Accepting socket connection...
08-05 11:24:02.856   871   871 D BluetoothA2dp: Proxy object connected
,08-05 11:24:02.856  4007  4007 D BluetoothMapService: onReceive
08-05 11:24:02.856  4007  4007 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:24:02.856  4007  4007 D BluetoothMapService: STATE_ON
08-05 11:24:02.857  1360  1360 D BluetoothA2dp: Proxy object connected
08-05 11:24:02.858  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:24:02.861  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:24:02.861  3927  3927 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-05 11:24:02.865  3927  3927 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-05 11:24:02.874  3927  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 ,
,08-05 11:24:02.877  4007  4007 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-05 11:24:02.877  4007  4007 D ObexServerSockets0: prepareForNewConnect()
,08-05 11:24:02.878  3927  3927 D BluetoothA2dp: Proxy object connected
,08-05 11:24:02.882  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:24:02.884  3927  3927 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:24:02.893  1360  1360 D BluetoothPbap: Proxy object connected
,08-05 11:24:02.893  3927  3927 D BluetoothPbap: Proxy object connected
08-05 11:24:02.893  1360  1360 D PbapServerProfile: Bluetooth service connected
08-05 11:24:02.893  3927  3927 D PbapServerProfile: Bluetooth service connected
,08-05 11:24:02.908  4007  4206 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 11:24:02.923  4007  4210 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 11:24:02.924  4007  4210 I BtOppRfcommListener: Accept thread started.
,08-05 11:24:02.929   871   871 D BluetoothHeadset: Proxy object connected
,08-05 11:24:02.929  1360  1373 D BluetoothHeadset: Proxy object connected
08-05 11:24:02.929  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-05 11:24:02.930  1740  1759 D BluetoothHeadset: Proxy object connected
08-05 11:24:02.930   871   871 D BluetoothHeadset: Proxy object connected,
08-05 11:24:02.930   871   871 D BluetoothHeadset: Proxy object connected
08-05 11:24:02.932  1740  1951 D BluetoothHeadset: Proxy object connected
,08-05 11:24:02.937   871   888 D BluetoothHeadset: Proxy object connected
,08-05 11:24:02.944  1360  3842 D BluetoothHeadset: Proxy object connected
,08-05 11:24:02.944  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-05 11:24:02.948   871   888 D BluetoothHeadset: Proxy object connected
,08-05 11:24:02.969  3927  3939 D BluetoothHeadset: Proxy object connected
,08-05 11:24:02.970  3927  3927 D HeadsetProfile: Bluetooth service connected
,08-05 11:24:04.379   871  1306 D ConnectivityService: handlePromptUnvalidated 101
,08-05 11:24:04.389  4007  4173 D BluetoothAdapterState: Current state: ON, message: 23
,08-05 11:24:04.389  4007  4173 D BluetoothAdapterProperties: Setting state to 13
08-05 11:24:04.389  4007  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 11:24:04.392  4007  4173 D BluetoothAdapterProperties: onBluetoothDisable()
,08-05 11:24:04.398  4007  4007 D BluetoothMapService: onReceive
08-05 11:24:04.399  4007  4007 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-05 11:24:04.399  4007  4007 D BluetoothMapService: STATE_TURNING_OFF
,08-05 11:24:04.400  4007  4007 D BluetoothMapService: MAP Service closeService in
,08-05 11:24:04.400  4007  4007 D BluetoothMapMasInstance0: MAP Service shutdown
,08-05 11:24:04.400  4007  4007 D ObexServerSockets0: shutdown(block = true)
,08-05 11:24:04.400  4007  4173 I BluetoothAdapterState: Entering PendingCommandState
08-05 11:24:04.402  4007  4007 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-05 11:24:04.403  4007  4007 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-05 11:24:04.403  4007  4199 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-05 11:24:04.404  4007  4198 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-05 11:24:04.407  4007  4187 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-05 11:24:04.409  4007  4007 I BtOppRfcommListener: stopping Accept Thread
08-05 11:24:04.410  4007  4210 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-05 11:24:04.410  4007  4210 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-05 11:24:04.411  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:24:04.411  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:24:04.411  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:04.411  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:04.411  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:24:04.411  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:24:04.411  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:24:04.411  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:24:04.411  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:24:04.413  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:24:04.413  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:24:04.415  4007  4177 D BluetoothAdapterProperties: Scan Mode:20,
08-05 11:24:04.415  4007  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-05 11:24:04.417  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 11:24:04.417  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:24:04.417  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:04.417  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:04.417  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:24:04.417  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 11:24:04.417  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:24:04.417  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:24:04.417  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 11:24:04.418  4007  4007 D HeadsetService: Received stop request...Stopping profile...
,08-05 11:24:04.419  3843  3843 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 11:24:04.419  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:24:04.422  3927  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-05 11:24:04.422   871   871 D BluetoothHeadset: Proxy object disconnected
,08-05 11:24:04.422  1360  3842 D BluetoothHeadset: Proxy object disconnected
08-05 11:24:04.423  1740  1751 D BluetoothHeadset: Proxy object disconnected
08-05 11:24:04.423   871   871 D BluetoothHeadset: Proxy object disconnected
,08-05 11:24:04.424  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:24:04.424  3927  3938 D BluetoothHeadset: Proxy object disconnected
,08-05 11:24:04.424  4007  4007 D A2dpService: Received stop request...Stopping profile...
08-05 11:24:04.425  1360  1360 D HeadsetProfile: Bluetooth service disconnected
08-05 11:24:04.425  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:04.426  4007  4193 D A2dpStateMachine: Exit Disconnected: -1
08-05 11:24:04.427   871   871 D BluetoothHeadset: Proxy object disconnected
08-05 11:24:04.427   871   871 D BluetoothA2dp: Proxy object disconnected
08-05 11:24:04.427  1360  1360 D BluetoothA2dp: Proxy object disconnected
08-05 11:24:04.428  4007  4007 V BluetoothAdapterState: isTurningOff()=true
,08-05 11:24:04.428  4007  4007 V BluetoothAdapterState: isTurningOn()=false
08-05 11:24:04.428  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:04.428  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:24:04.429  4007  4007 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 11:24:04.430  4007  4007 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-05 11:24:04.430  4007  4007 V BluetoothAdapterState: isTurningOff()=true
08-05 11:24:04.430  4007  4007 V BluetoothAdapterState: isTurningOn()=false
08-05 11:24:04.430  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 11:24:04.430  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:24:04.430  4007  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-05 11:24:04.431  4007  4183 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 11:24:04.431  4007  4007 D HidService: Received stop request...Stopping profile...
,08-05 11:24:04.431  4007  4183 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 11:24:04.431  4007  4183 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-05 11:24:04.431  4007  4177 E bt_btif : btif_hf_upstreams_evt: Invalid index 30574
08-05 11:24:04.431  3927  3927 D HeadsetProfile: Bluetooth service disconnected
08-05 11:24:04.432  4007  4007 D HidService: Stopping Bluetooth HidService
,08-05 11:24:04.433  1360  1360 D BluetoothInputDevice: Proxy object disconnected
08-05 11:24:04.433  1360  1360 D HidProfile: Bluetooth service disconnected
08-05 11:24:04.435  4007  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-05 11:24:04.435  4007  4183 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-05 11:24:04.435  4007  4007 D HealthService: Received stop request...Stopping profile...
,08-05 11:24:04.435  4007  4183 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-05 11:24:04.435  4007  4183 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:24:04.435  4007  4183 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-05 11:24:04.435  4007  4183 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 11:24:04.435  4007  4183 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-05 11:24:04.436  4007  4007 D PanService: Received stop request...Stopping profile...
08-05 11:24:04.438  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 11:24:04.438  1360  1360 D PanProfile: Bluetooth service disconnected
,08-05 11:24:04.439  3927  3927 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:24:04.440  3927  3927 D BluetoothA2dp: Proxy object disconnected
,08-05 11:24:04.441  3927  3927 D BluetoothInputDevice: Proxy object disconnected
08-05 11:24:04.441  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:24:04.441  3927  3927 D HidProfile: Bluetooth service disconnected
,08-05 11:24:04.441  4007  4007 D BluetoothMapService: Received stop request...Stopping profile...
08-05 11:24:04.441  4007  4007 D BluetoothMapService: stop()
08-05 11:24:04.443  3927  3927 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-05 11:24:04.443  3927  3927 D PanProfile: Bluetooth service disconnected
08-05 11:24:04.443  4007  4007 D BluetoothMapAppObserver: deinitObservers()
08-05 11:24:04.443  4007  4007 D BluetoothMapAppObserver: removeReceiver()
,08-05 11:24:04.446  3927  3927 D BluetoothMap: Proxy object disconnected
08-05 11:24:04.446  3927  3927 D MapProfile: Bluetooth service disconnected
08-05 11:24:04.446  1360  1360 D BluetoothMap: Proxy object disconnected
,08-05 11:24:04.446  4007  4007 V BluetoothAdapterState: isTurningOff()=true
08-05 11:24:04.446  1360  1360 D MapProfile: Bluetooth service disconnected
08-05 11:24:04.446  4007  4007 V BluetoothAdapterState: isTurningOn()=false
08-05 11:24:04.446  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false,
08-05 11:24:04.447  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:24:04.447  4007  4007 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-05 11:24:04.447  4007  4007 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 11:24:04.447  4007  4177 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-05 11:24:04.447  4007  4007 V BluetoothAdapterState: isTurningOff()=true
08-05 11:24:04.447  4007  4007 V BluetoothAdapterState: isTurningOn()=false
,08-05 11:24:04.447  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:04.447  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:24:04.448  4007  4007 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 11:24:04.448  4007  4177 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-05 11:24:04.448  4007  4007 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 11:24:04.448  4007  4007 V BluetoothAdapterState: isTurningOff()=true
08-05 11:24:04.448  4007  4007 V BluetoothAdapterState: isTurningOn()=false
08-05 11:24:04.448  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:04.448  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:04.449  4007  4007 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-05 11:24:04.449  4007  4007 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 11:24:04.453  1360  1360 D BluetoothPbap: Proxy object disconnected
08-05 11:24:04.453  1360  1360 D PbapServerProfile: Bluetooth service disconnected
08-05 11:24:04.454  3927  3927 D BluetoothPbap: Proxy object disconnected
08-05 11:24:04.454  3927  3927 D PbapServerProfile: Bluetooth service disconnected
,08-05 11:24:04.456  4007  4007 D BluetoothMapService: MAP Service closeService in
,08-05 11:24:04.456  4007  4007 V BluetoothAdapterState: isTurningOff()=true
08-05 11:24:04.456  4007  4007 V BluetoothAdapterState: isTurningOn()=false
08-05 11:24:04.456  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:04.456  4007  4007 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:04.456  4007  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-05 11:24:04.456  4007  4173 D BluetoothAdapterProperties: Setting state to 15
08-05 11:24:04.456  4007  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-05 11:24:04.457  4007  4173 I BluetoothAdapterState: Entering BleOnState
08-05 11:24:04.457  4007  4007 D BluetoothMapService: cleanup()
08-05 11:24:04.457  4007  4007 D BluetoothMapService: MAP Service closeService in
08-05 11:24:04.459   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:24:04.459  3927  3939 D BluetoothPbap: onBluetoothStateChange: up=false
,08-05 11:24:04.460  1740  1917 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 11:24:04.460  1360  1373 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 11:24:04.461  3927  3938 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-05 11:24:04.462  3927  3939 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 11:24:04.462  3927  3938 D BluetoothMap: onBluetoothStateChange: up=false
,08-05 11:24:04.463  1360  3842 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 11:24:04.463   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:24:04.463  3927  3939 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-05 11:24:04.464  3927  3938 D BluetoothPan: onBluetoothStateChange on: false
,08-05 11:24:04.465   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-05 11:24:04.465  1360  1384 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 11:24:04.465  1360  1824 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-05 11:24:04.466  1360  1373 D BluetoothPan: onBluetoothStateChange on: false
08-05 11:24:04.466   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-05 11:24:04.466  1360  3842 D BluetoothMap: onBluetoothStateChange: up=false
,08-05 11:24:04.467  4007  4173 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-05 11:24:04.467  4007  4173 D BluetoothAdapterProperties: Setting state to 16
08-05 11:24:04.467  4007  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-05 11:24:04.468  4007  4173 D BluetoothAdapterProperties: onBleDisable
,08-05 11:24:04.468  4007  4173 I BluetoothAdapterState: Entering PendingCommandState
08-05 11:24:04.468  4007  4174 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-05 11:24:04.469  4007  4183 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-05 11:24:04.469  4007  4183 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-05 11:24:04.471  4007  4177 D BluetoothAdapterProperties: Scan Mode:20
,08-05 11:24:04.474  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:04.474  3927  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 11:24:04.475  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:04.476  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:04.477  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:04.479  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:24:04.484  3927  3927 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:24:04.673  4007  4177 I bt_hci  : shut_down
,08-05 11:24:04.688  4007  4181 I bt_vendor: low_power_mode_cb
,08-05 11:24:04.689  4007  4181 D bt_hwcfg: hw_epilog_process
,08-05 11:24:04.710  4007  4181 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-05 11:24:04.711  4007  4181 I bt_vendor: epilog_cb
,08-05 11:24:04.711  4007  4181 I bt_hci  : epilog_finished_callback
,08-05 11:24:04.719  4007  4177 I bt_hci_h4: hal_close
,08-05 11:24:04.720  4007  4177 I bt_userial_vendor: device fd = 51 close
,08-05 11:24:04.846  4007  4174 D bt_stack_manager: event_shut_down_stack finished.
,08-05 11:24:04.847  4007  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-05 11:24:04.852  4007  4007 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 11:24:04.854  4007  4007 D BtGatt.GattService: Received stop request...Stopping profile...
,08-05 11:24:04.852  4007  4173 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-05 11:24:04.854  4007  4007 D BtGatt.GattService: stop()
08-05 11:24:04.855  4007  4007 D BtGatt.AdvertiseManager: advertise clients cleared
,08-05 11:24:04.859  4007  4007 V BluetoothAdapterState: isTurningOff()=false
,08-05 11:24:04.859  4007  4007 V BluetoothAdapterState: isTurningOn()=false
08-05 11:24:04.860  4007  4007 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 11:24:04.860  4007  4007 V BluetoothAdapterState: isBleTurningOff()=true
08-05 11:24:04.861  4007  4173 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-05 11:24:04.861  4007  4173 D BluetoothAdapterProperties: Setting state to 10
08-05 11:24:04.862  4007  4173 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-05 11:24:04.863  4007  4173 I BluetoothAdapterState: Entering OffState
,08-05 11:24:04.865   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-05 11:24:04.885  4007  4007 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-05 11:24:04.885  4007  4007 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-05 11:24:04.885  4007  4174 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-05 11:24:04.888  4007  4174 D bt_stack_manager: event_clean_up_stack finished.
08-05 11:24:04.888  4007  4007 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-05 11:24:04.890  4007  4007 I art     : System.exit called, status: 0
,08-05 11:24:04.890  4007  4007 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-05 11:24:04.942   871  1687 I ActivityManager: Process com.android.bluetooth (pid 4007) has died
,08-05 11:24:07.386  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 11:24:07.386  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:24:10.394  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 11:24:10.395  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bbe8e0c added. We now have 6 listener(s)
,08-05 11:24:10.395  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:24:10.399  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:24:10.400  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8b25355 added. We now have 7 listener(s)
,08-05 11:24:10.400  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:24:10.401  3843  3898 I System.out: IsBluetoothEnabled
,08-05 11:24:10.411  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:10.451   871   888 I ActivityManager: Start proc 4221:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-05 11:24:10.579  4221  4221 D AdapterServiceConfig: Adding HeadsetService
,08-05 11:24:10.579  4221  4221 D AdapterServiceConfig: Adding A2dpService
08-05 11:24:10.579  4221  4221 D AdapterServiceConfig: Adding HidService
,08-05 11:24:10.580  4221  4221 D AdapterServiceConfig: Adding HealthService
,08-05 11:24:10.580  4221  4221 D AdapterServiceConfig: Adding PanService
,08-05 11:24:10.580  4221  4221 D AdapterServiceConfig: Adding GattService
,08-05 11:24:10.581  4221  4221 D AdapterServiceConfig: Adding BluetoothMapService
,08-05 11:24:10.596   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fb79574:true
,08-05 11:24:10.597  4221  4221 D BluetoothAdapterState: make() - Creating AdapterState
,08-05 11:24:10.601  4221  4221 I bt_bluedroid: init
,08-05 11:24:10.602  4221  4233 I BluetoothAdapterState: Entering OffState
,08-05 11:24:10.609  4221  4234 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-05 11:24:10.609  4221  4234 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 11:24:10.609  4221  4234 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-05 11:24:10.610  4221  4234 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-05 11:24:10.612  4221  4221 I bt_bluedroid: get_profile_interface socket
,08-05 11:24:10.615  4221  4221 I bt_bluedroid: get_profile_interface sdp
,08-05 11:24:10.621  4221  4232 I bt_bluedroid: config_hci_snoop_log
,08-05 11:24:10.621  4221  4237 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-05 11:24:10.624  4221  4237 D BluetoothAdapterProperties: Name is: Nexus 6
,08-05 11:24:10.626   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-05 11:24:10.633  4221  4233 D BluetoothAdapterState: Current state: OFF, message: 0
,08-05 11:24:10.633  4221  4233 D BluetoothAdapterProperties: Setting state to 14,
,08-05 11:24:10.633  4221  4233 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-05 11:24:10.637  4221  4233 D BluetoothBondStateMachine: make
,08-05 11:24:10.641  4221  4238 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-05 11:24:10.646  4221  4233 I BluetoothAdapterState: Entering PendingCommandState
,08-05 11:24:10.647  4221  4221 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-05 11:24:10.652  4221  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:10.654  4221  4221 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 11:24:10.655  4221  4221 D BtGatt.GattService: Received start request. Starting profile...
,08-05 11:24:10.655  4221  4221 D BtGatt.GattService: start()
,08-05 11:24:10.655  4221  4221 I bt_bluedroid: get_profile_interface gatt
,08-05 11:24:10.657  4221  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
08-05 11:24:10.657  4221  4221 D BtGatt.AdvertiseManager: advertise manager created
,08-05 11:24:10.663  4221  4221 V BluetoothAdapterState: isTurningOff()=false
,08-05 11:24:10.664  4221  4221 V BluetoothAdapterState: isTurningOn()=false
,08-05 11:24:10.664  4221  4221 V BluetoothAdapterState: isBleTurningOn()=true
08-05 11:24:10.664  4221  4221 V BluetoothAdapterState: isBleTurningOff()=false
08-05 11:24:10.665  4221  4233 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-05 11:24:10.665  4221  4233 I bt_bluedroid: enable
,08-05 11:24:10.666  4221  4234 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-05 11:24:10.666  4221  4234 I bt_hci  : start_up
,08-05 11:24:10.679  4221  4234 I bt_vendor: alloc value 0xb3a1c189
,08-05 11:24:10.679  4221  4234 I bt_vendor: init
,08-05 11:24:10.679  4221  4234 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-05 11:24:10.679  4221  4234 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-05 11:24:10.786  4221  4234 D bt_hci  : start_up starting async portion
,08-05 11:24:10.787  4221  4241 I bt_hci  : event_finish_startup
,08-05 11:24:10.788  4221  4241 I bt_hci_h4: hal_open
,08-05 11:24:10.788  4221  4241 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-05 11:24:10.800  4221  4241 I bt_userial_vendor: device fd = 51 open
,08-05 11:24:10.828  4221  4241 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 11:24:10.860  4221  4241 D bt_hwcfg: Chipset BCM4354A2
,08-05 11:24:10.860  4221  4241 D bt_hwcfg: Target name = [BCM4354A2]
,08-05 11:24:10.861  4221  4241 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-05 11:24:11.521  4221  4241 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-05 11:24:11.523  4221  4241 D bt_hwcfg: Settlement delay -- 100 ms
,08-05 11:24:11.523  4221  4241 I bt_hwcfg: Setting fw settlement delay to 100 
,08-05 11:24:11.640  4221  4241 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 11:24:11.641  4221  4241 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-05 11:24:11.671  4221  4241 I bt_hwcfg: vendor lib fwcfg completed
,08-05 11:24:11.672  4221  4241 I bt_vendor: firmware callback
,08-05 11:24:11.672  4221  4241 I bt_hci  : firmware_config_callback
,08-05 11:24:11.685  4221  4243 I bt_btu  : btu_task pending for preload complete event
,08-05 11:24:11.685  4221  4243 I bt_btu_task: Bluetooth chip preload is complete
08-05 11:24:11.685  4221  4243 I bt_btu  : btu_task received preload complete event
,08-05 11:24:11.695  4221  4243 I         : BTE_InitTraceLevels -- TRC_HCI
,08-05 11:24:11.695  4221  4243 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 11:24:11.695  4221  4243 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-05 11:24:11.695  4221  4243 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 11:24:11.696  4221  4243 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-05 11:24:11.696  4221  4243 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 11:24:11.696  4221  4243 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-05 11:24:11.696  4221  4243 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 11:24:11.696  4221  4243 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 11:24:11.697  4221  4243 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 11:24:11.697  4221  4243 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 11:24:11.697  4221  4243 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 11:24:11.697  4221  4243 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 11:24:11.697  4221  4243 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 11:24:11.697  4221  4243 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-05 11:24:11.825  4221  4243 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3999d9d
,08-05 11:24:11.825  4221  4243 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3999d9d 
,08-05 11:24:11.849  4221  4237 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-05 11:24:11.851  4221  4237 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-05 11:24:11.852  4221  4237 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-05 11:24:11.854  4221  4237 D BluetoothAdapterProperties: Name is: Nexus 6
,08-05 11:24:11.858  4221  4237 D BluetoothAdapterProperties: Scan Mode:20
,08-05 11:24:11.858  4221  4237 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-05 11:24:11.858  4221  4237 D bt_hci  : do_postload posting postload work item
,08-05 11:24:11.859  4221  4241 I bt_hci  : event_postload
,08-05 11:24:11.859  4221  4241 I bt_vendor: sco_config_cb
,08-05 11:24:11.859  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:11.859  4221  4241 I bt_hci  : sco_config_callback postload finished.
,08-05 11:24:11.861  4221  4237 D bt_bte_conf: Device ID record 1 : primary
,08-05 11:24:11.861  4221  4237 D bt_bte_conf:   vendorId            = 000f
08-05 11:24:11.861  4221  4237 D bt_bte_conf:   vendorIdSource      = 0001
,08-05 11:24:11.862  4221  4237 D bt_bte_conf:   product             = 1200
08-05 11:24:11.862  4221  4237 D bt_bte_conf:   version             = 1436
08-05 11:24:11.862  4221  4237 D bt_bte_conf:   clientExecutableURL = 
08-05 11:24:11.862  4221  4237 D bt_bte_conf:   serviceDescription  = 
08-05 11:24:11.862  4221  4237 D bt_bte_conf:   documentationURL    = 
08-05 11:24:11.863  4221  4237 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-05 11:24:11.863  4221  4234 D bt_stack_manager: event_start_up_stack finished
08-05 11:24:11.864  4221  4233 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-05 11:24:11.864  4221  4233 D BluetoothAdapterProperties: Setting state to 15
08-05 11:24:11.865  4221  4233 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-05 11:24:11.866  4221  4233 I BluetoothAdapterState: Entering BleOnState
08-05 11:24:11.867  4221  4241 I bt_vendor: low_power_mode_cb
08-05 11:24:11.870  4221  4233 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-05 11:24:11.870  4221  4233 D BluetoothAdapterProperties: Setting state to 11
08-05 11:24:11.872  4221  4233 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-05 11:24:11.879  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:24:11.885  4221  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:11.886  4221  4221 D HeadsetService: Received start request. Starting profile...
08-05 11:24:11.889  4221  4221 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-05 11:24:11.889  4221  4221 D HeadsetStateMachine: make
,08-05 11:24:11.896  4221  4233 I BluetoothAdapterState: Entering PendingCommandState
,08-05 11:24:11.898  4221  4221 D HeadsetStateMachine: max_hf_connections = 1
08-05 11:24:11.898  4221  4221 I bt_bluedroid: get_profile_interface handsfree
,08-05 11:24:11.899  4221  4237 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-05 11:24:11.899  4221  4237 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-05 11:24:11.905  4221  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:11.905  4221  4221 D A2dpService: Received start request. Starting profile...
08-05 11:24:11.906  4221  4221 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-05 11:24:11.906  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-05 11:24:11.906  4221  4221 I bt_bluedroid: get_profile_interface avrcp
,08-05 11:24:11.913  4221  4221 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-05 11:24:11.913  4221  4221 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 11:24:11.913  4221  4221 D A2dpStateMachine: make
,08-05 11:24:11.915  4221  4221 I bt_bluedroid: get_profile_interface a2dp
,08-05 11:24:11.915  4221  4237 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-05 11:24:11.917  4221  4221 I BluetoothHidServiceJni: classInitNative: succeeds
,08-05 11:24:11.917  4221  4252 D A2dpStateMachine: Enter Disconnected: -2
08-05 11:24:11.918  4221  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:11.919  4221  4221 D HidService: Received start request. Starting profile...
,08-05 11:24:11.919  4221  4221 I bt_bluedroid: get_profile_interface hidhost
,08-05 11:24:11.919  4221  4237 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb397b3e5
08-05 11:24:11.919  4221  4237 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-05 11:24:11.919  4221  4221 D HidService: setHidService(): set to: null
,08-05 11:24:11.920  4221  4221 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 11:24:11.920  4221  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
08-05 11:24:11.921  4221  4221 D HealthService: Received start request. Starting profile...
,08-05 11:24:11.922  4221  4221 I bt_bluedroid: get_profile_interface health
,08-05 11:24:11.923  4221  4221 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-05 11:24:11.924  4221  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:11.924  4221  4221 D PanService: Received start request. Starting profile...
08-05 11:24:11.925  4221  4221 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-05 11:24:11.925  4221  4221 I bt_bluedroid: get_profile_interface pan
08-05 11:24:11.925  4221  4237 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-05 11:24:11.928  4221  4221 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:11.928  4221  4221 D BluetoothMapService: Received start request. Starting profile...
08-05 11:24:11.928  4221  4221 D BluetoothMapService: start()
,08-05 11:24:11.930  4221  4221 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-05 11:24:11.931  4221  4221 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-05 11:24:11.931  4221  4221 D BluetoothMapAppObserver: createReceiver()
,08-05 11:24:11.932  4221  4221 D BluetoothMapAppObserver: initObservers()
08-05 11:24:11.933  4221  4221 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-05 11:24:11.941  4221  4221 V BluetoothAdapterState: isTurningOff()=false
,08-05 11:24:11.941  4221  4221 V BluetoothAdapterState: isTurningOn()=true
08-05 11:24:11.941  4221  4221 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:11.941  4221  4221 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:11.943  4221  4250 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-05 11:24:11.943  4221  4221 V BluetoothAdapterState: isTurningOff()=false
,08-05 11:24:11.943  4221  4221 V BluetoothAdapterState: isTurningOn()=true
08-05 11:24:11.943  4221  4221 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:11.943  4221  4221 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:11.943  4221  4221 V BluetoothAdapterState: isTurningOff()=false
08-05 11:24:11.943  4221  4221 V BluetoothAdapterState: isTurningOn()=true
08-05 11:24:11.943  4221  4221 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:11.944  4221  4221 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:11.944  4221  4221 V BluetoothAdapterState: isTurningOff()=false
,08-05 11:24:11.944  4221  4221 V BluetoothAdapterState: isTurningOn()=true
,08-05 11:24:11.944  4221  4221 V BluetoothAdapterState: isBleTurningOn()=false
,08-05 11:24:11.944  4221  4221 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:11.945  4221  4221 V BluetoothAdapterState: isTurningOff()=false
08-05 11:24:11.945  4221  4221 V BluetoothAdapterState: isTurningOn()=true
,08-05 11:24:11.945  4221  4221 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:11.945  4221  4221 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:11.945  4221  4221 V BluetoothAdapterState: isTurningOff()=false
08-05 11:24:11.945  4221  4221 V BluetoothAdapterState: isTurningOn()=true
,08-05 11:24:11.945  4221  4221 V BluetoothAdapterState: isBleTurningOn()=false
08-05 11:24:11.945  4221  4221 V BluetoothAdapterState: isBleTurningOff()=false
,08-05 11:24:11.946  4221  4233 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-05 11:24:11.946  4221  4233 D BluetoothAdapterProperties: ScanMode =  20
08-05 11:24:11.946  4221  4233 D BluetoothAdapterProperties: State =  11
,08-05 11:24:11.947  4221  4237 D BluetoothAdapterProperties: Scan Mode:21
08-05 11:24:11.947  4221  4233 D BluetoothAdapterProperties: Setting state to 12
08-05 11:24:11.947  4221  4237 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-05 11:24:11.947  4221  4233 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-05 11:24:11.948   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:24:11.948  4221  4233 I BluetoothAdapterState: Entering OnState
08-05 11:24:11.948  3927  4214 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 11:24:11.950  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:24:11.950  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:11.950  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:11.950  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:24:11.950  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:11.950  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:24:11.950  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:24:11.950  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:24:11.950  1740  1917 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-05 11:24:11.951  1360  3842 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 11:24:11.951  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 11:24:11.954  3927  3939 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-05 11:24:11.955  1360  1360 D BluetoothA2dp: Proxy object connected
08-05 11:24:11.956  3927  3938 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:24:11.957  3927  3938 D BluetoothMap: onBluetoothStateChange: up=true
,08-05 11:24:11.957  3927  3927 D BluetoothInputDevice: Proxy object connected
08-05 11:24:11.957  3927  3927 D HidProfile: Bluetooth service connected
,08-05 11:24:11.959  1360  1373 D BluetoothPbap: onBluetoothStateChange: up=true
08-05 11:24:11.959  4221  4221 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-05 11:24:11.959  4221  4221 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-05 11:24:11.960   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:24:11.960  3927  3939 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 11:24:11.960  4221  4221 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:24:11.962  4221  4221 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 11:24:11.963  3927  4214 D BluetoothPan: onBluetoothStateChange on: true
08-05 11:24:11.963  4221  4221 D ObexServerSockets: Succeed to create listening sockets 
08-05 11:24:11.963  4221  4221 D ObexServerSockets0: startAccept()
08-05 11:24:11.963  4221  4221 D ObexServerSockets0: prepareForNewConnect()
,08-05 11:24:11.965   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-05 11:24:11.965  4221  4221 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-05 11:24:11.965  4221  4221 D BluetoothSdpJni: SDP Create record success - handle: 0
08-05 11:24:11.965   871   871 D BluetoothA2dp: Proxy object connected
08-05 11:24:11.966  1360  1824 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-05 11:24:11.967  4221  4257 D ObexServerSockets0: Accepting socket connection...
,08-05 11:24:11.968  4221  4258 D ObexServerSockets0: Accepting socket connection...
08-05 11:24:11.969  1360  1360 D BluetoothInputDevice: Proxy object connected
08-05 11:24:11.969  1360  1360 D HidProfile: Bluetooth service connected
08-05 11:24:11.969  1360  1384 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:24:11.969  1360  1373 D BluetoothPan: onBluetoothStateChange on: true
08-05 11:24:11.971  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 11:24:11.971  1360  1360 D PanProfile: Bluetooth service connected
,08-05 11:24:11.972  3927  3927 D BluetoothMap: Proxy object connected
08-05 11:24:11.971   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
08-05 11:24:11.972  1360  1824 D BluetoothMap: onBluetoothStateChange: up=true
,08-05 11:24:11.974  1360  1360 D BluetoothMap: Proxy object connected
,08-05 11:24:11.974  1360  1360 D MapProfile: Bluetooth service connected
08-05 11:24:11.974  1360  1360 D BluetoothMap: getConnectedDevices()
,08-05 11:24:11.976   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-05 11:24:11.976  4221  4221 D BluetoothMapService: onReceive
08-05 11:24:11.976  4221  4221 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 11:24:11.976  4221  4221 D BluetoothMapService: STATE_ON
,08-05 11:24:11.977  3927  3927 D MapProfile: Bluetooth service connected
,08-05 11:24:11.977  3927  3927 D BluetoothMap: getConnectedDevices()
,08-05 11:24:11.978  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:11.980  3927  3927 D BluetoothA2dp: Proxy object connected
,08-05 11:24:11.982  3927  3927 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 11:24:11.982  3927  3927 D PanProfile: Bluetooth service connected
,08-05 11:24:11.985  3927  3927 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 11:24:11.994  1508  1508 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-05 11:24:11.995  3927  3927 D DockEventReceiver: finishStartingService: stopping service
,08-05 11:24:11.999  3927  3927 D BluetoothPbap: Proxy object connected
,08-05 11:24:11.999  4221  4221 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-05 11:24:11.999  4221  4221 D ObexServerSockets0: prepareForNewConnect()
08-05 11:24:11.999  3927  3927 D PbapServerProfile: Bluetooth service connected
08-05 11:24:12.001  1360  1360 D BluetoothPbap: Proxy object connected
08-05 11:24:12.001  4221  4261 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-05 11:24:12.001  1360  1360 D PbapServerProfile: Bluetooth service connected
,08-05 11:24:12.020  4221  4267 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 11:24:12.022  4221  4267 I BtOppRfcommListener: Accept thread started.
,08-05 11:24:12.051   871   871 D BluetoothHeadset: Proxy object connected
,08-05 11:24:12.052  1360  1824 D BluetoothHeadset: Proxy object connected
,08-05 11:24:12.053  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-05 11:24:12.053  1740  1759 D BluetoothHeadset: Proxy object connected
08-05 11:24:12.053   871   871 D BluetoothHeadset: Proxy object connected
,08-05 11:24:12.058  3927  4214 D BluetoothHeadset: Proxy object connected
,08-05 11:24:12.060   871   888 D BluetoothHeadset: Proxy object connected
08-05 11:24:12.060  3927  3939 D BluetoothHeadset: Proxy object connected,
08-05 11:24:12.060   871   871 D BluetoothHeadset: Proxy object connected
08-05 11:24:12.061  3927  3927 D HeadsetProfile: Bluetooth service connected
,08-05 11:24:12.063  3927  3927 D HeadsetProfile: Bluetooth service connected
,08-05 11:24:12.069  1360  3842 D BluetoothHeadset: Proxy object connected
,08-05 11:24:12.070  1360  1360 D HeadsetProfile: Bluetooth service connected
,08-05 11:24:12.072   871   888 D BluetoothHeadset: Proxy object connected
,08-05 11:24:12.432  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:24:12.432  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:12.432  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:12.432  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 11:24:12.432  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:12.432  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:24:12.432  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:24:12.432  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:24:12.439  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:24:12.443  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 11:24:12.443  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@20f916a added. We now have 8 listener(s)
,08-05 11:24:12.444  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:24:12.452   871  1752 D WifiService: setWifiEnabled: false pid=3843, uid=10000
,08-05 11:24:12.452   871  1752 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:24:12.464  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:12.465   871  1687 D WifiService: setWifiEnabled: true pid=3843, uid=10000
,08-05 11:24:12.465   871  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-05 11:24:12.480   871  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-05 11:24:12.498  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:24:12.498  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:12.498  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:12.498  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:24:12.498  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:12.498  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:24:12.498  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:24:12.498  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:24:12.501  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:24:12.512   871  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-05 11:24:12.513   871  1304 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-05 11:24:12.513   871  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-05 11:24:12.514   871  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-05 11:24:12.515   871  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-05 11:24:12.515   871  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-05 11:24:12.516   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-05 11:24:12.516   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-05 11:24:12.529   371   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-05 11:24:12.529   871  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.62 rxSuccessRate=5.69 delta 1000 -> 1000
,08-05 11:24:12.530   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-05 11:24:12.530   371   869 D CommandListener: Setting iface cfg
,08-05 11:24:12.530   871  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-05 11:24:12.531   871  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-05 11:24:12.584   871  1304 E native  : do suspend true
,08-05 11:24:12.597   871  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-05 11:24:12.606   871  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-05 11:24:12.611   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-05 11:24:12.611   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 11:24:12.642   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-05 11:24:12.709   871  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
08-05 11:24:12.713  1454  1454 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-05 11:24:13.145  1454  1454 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-05 11:24:13.199  1454  1454 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-05 11:24:13.201  1454  1454 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-05 11:24:13.209   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-05 11:24:13.230   871  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-05 11:24:13.232   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-05 11:24:13.232   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 11:24:13.262   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 11:24:13.288   371   869 D CommandListener: Setting iface cfg
,08-05 11:24:13.291   871  1304 D WifiStateMachine: Start Dhcp Watchdog 3
,08-05 11:24:13.305   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-05 11:24:13.340   871  4275 D DhcpClient: Receive thread started
,08-05 11:24:13.424   871  1304 E native  : do suspend false
,08-05 11:24:13.444   871  2014 D DhcpClient: Broadcasting DHCPDISCOVER
,08-05 11:24:13.457   871  4275 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-05 11:24:13.459   871  2014 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-05 11:24:13.462   871  2014 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-05 11:24:13.477   871  4275 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-05 11:24:13.478   871  2014 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-05 11:24:13.483   371   869 D CommandListener: Setting iface cfg
,08-05 11:24:13.495  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:24:13.495  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:13.495  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:13.495  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:24:13.495  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:13.495  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 11:24:13.495  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 11:24:13.495  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 11:24:13.495   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-05 11:24:13.496   871  2014 D DhcpClient: Scheduling renewal in 86399s,
,08-05 11:24:13.498   871  1304 E native  : do suspend true
08-05 11:24:13.500  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 11:24:13.504  3843  3898 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-05 11:24:13.505  3843  3898 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-05 11:24:13.507  3843  3898 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bf914ad Bundle[{}]
,08-05 11:24:13.508  3843  3898 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 11:24:13.508  3843  3898 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-05 11:24:13.509  3843  3898 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-05 11:24:13.509  3843  3898 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-05 11:24:13.510  3843  3898 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-05 11:24:13.510  3843  3898 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-05 11:24:13.514  3843  3898 I System.out: Running OutgoingSocketThread
,08-05 11:24:13.517   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-05 11:24:13.518  3843  4276 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 438)
,08-05 11:24:13.518   871  1304 D WifiConfigStore: No blacklist allowed without epno enabled
08-05 11:24:13.518   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-05 11:24:13.519  3843  4276 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37398
08-05 11:24:13.519  3843  4276 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-05 11:24:13.520   871  1306 D ConnectivityService: Adding iface wlan0 to network 102
08-05 11:24:13.521   871  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp,
,08-05 11:24:13.557   871  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-05 11:24:13.557   871  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-05 11:24:13.558   871  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-05 11:24:13.560   871  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-05 11:24:13.561   871  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-05 11:24:13.569   871  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-05 11:24:13.575   871  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-05 11:24:13.576   871  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-05 11:24:13.576   871  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-05 11:24:13.576   871  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-05 11:24:13.576   871  1306 D ConnectivityService:    accepting network in place of null
08-05 11:24:13.577   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-05 11:24:13.578   871  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-05 11:24:13.584   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166656, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:24:13.609   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 11:24:13.654   871  4273 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,08-05 11:24:13.655   371   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-05 11:24:13.658   871  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-05 11:24:13.659   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-05 11:24:13.660   871  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-05 11:24:13.661   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-05 11:24:13.686  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 11:24:13.686  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:13.686  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:13.686  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:24:13.686  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:13.686  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:24:13.686  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:24:13.686  3843  3843 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 11:24:13.694  3843  3843 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:24:13.702  1865  1865 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-05 11:24:13.712  1865  1865 D SystemUpdateService: onCreate
,08-05 11:24:13.726  1865  1865 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-05 11:24:13.738  1865  4285 I SystemUpdateService: active receiver: enabled
,08-05 11:24:13.745  1865  4285 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-05 11:24:13.748  1865  1865 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-05 11:24:13.758  1865  2354 I iu.UploadsManager: num queued entries: 0
,08-05 11:24:13.758  1865  2354 I iu.UploadsManager: num updated entries: 0
08-05 11:24:13.759  1865  2354 I iu.SyncManager: NEXT; no task
08-05 11:24:13.759  1865  4285 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: false
08-05 11:24:13.760  1865  4285 I SystemUpdateService: now status is 0 (complete)
,08-05 11:24:13.760  1865  4285 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-05 11:24:13.760  1865  4285 I SystemUpdateService: file has been verified
08-05 11:24:13.760  1865  4285 I SystemUpdateService: OTA package size = 12249756
,08-05 11:24:13.762  1865  1865 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-05 11:24:13.763  1865  1865 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-05 11:24:13.766  4021  4021 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-05 11:24:13.767   871  4273 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 09:24:13 GMT], X-Android-Received-Millis=[1470389053766], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470389053725]}
,08-05 11:24:13.769   871  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-05 11:24:13.769   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-05 11:24:13.770   871  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-05 11:24:13.775  4021  4021 D SprintDMHelper: simOperator: 
,08-05 11:24:13.775  4021  4021 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-05 11:24:13.776   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-05 11:24:13.787  1865  4287 I MDM     : [218] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-05 11:24:13.787  1865  4287 W BaseAppContext: Using Auth Proxy for data requests.
,08-05 11:24:13.789  1865  4287 V GoogleAuthProtoRequest: [218] a.<init>: mAccountName set to: thalitester@gmail.com
,08-05 11:24:13.805  3785  4293 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 11:24:13.823  1865  4285 I SystemUpdateService: showing system update notification
,08-05 11:24:13.828  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:24:13.832  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:24:13.950  1508  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:24:13.950  1508  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 11:24:13.950  1508  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:24:13.950  1508  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:24:13.960  3977  4292 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-05 11:24:13.973  3480  4295 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 11:24:13.973  3480  4295 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at blb.a(PG:3937)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at czp.a(PG:18188)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at czp.a(PG:9087)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:24:13.973  3480  4295 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	... 12 more
08-05 11:24:13.973  3480  4295 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at fal.a(PG:38)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:24:13.973  3480  4295 E HttpOperation: 	... 14 more
,08-05 11:24:14.013  3785  4301 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 11:24:14.025  1508  2012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-05 11:24:14.025  1508  2012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-05 11:24:14.025  1508  2012 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:24:14.025  1508  2012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:24:14.045  1508  1968 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 11:24:14.045  1508  1968 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 11:24:14.045  1508  1968 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:24:14.045  1508  1968 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:24:14.054  1865  1865 D SystemUpdateService: onDestroy
,08-05 11:24:14.110  1508  2935 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 11:24:14.110  1508  2935 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-05 11:24:14.110  1508  2935 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:24:14.110  1508  2935 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:24:14.150  3785  4301 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-05 11:24:14.151  3785  4293 E BooksSync: Soft error
08-05 11:24:14.151  3785  4293 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:24:14.151  3785  4293 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-05 11:24:14.155  3785  4293 E BooksSync: Sync error
08-05 11:24:14.155  3785  4293 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:24:14.155  3785  4293 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-05 11:24:14.155  3785  4293 I BooksSync: Finished books sync
,08-05 11:24:14.169   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160739, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:24:14.175  1865  4287 E MDM     : [218] SitrepService.a: Error sending sitrep.
,08-05 11:24:14.212  1508  2353 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:24:14.213  1508  2353 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 11:24:14.213  1508  2353 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:24:14.213  1508  2353 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:24:14.230  3480  4304 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 11:24:14.230  3480  4304 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at blb.a(PG:3937)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at czp.a(PG:18188)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:24:14.230  3480  4304 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	... 12 more
08-05 11:24:14.230  3480  4304 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at fal.a(PG:38)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:24:14.230  3480  4304 E HttpOperation: 	... 14 more
,08-05 11:24:14.267  1508  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:24:14.267  1508  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 11:24:14.267  1508  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:24:14.267  1508  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:24:14.285  3480  4304 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 11:24:14.285  3480  4304 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at hec.a(PG:42)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at hee.a(PG:102)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at czr.a(PG:65)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at kka.a(PG:108)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at czp.a(PG:19176)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:24:14.285  3480  4304 E HttpOperation: ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:24:14.285  3480  4304 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	... 15 more
08-05 11:24:14.285  3480  4304 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at fal.a(PG:38)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:24:14.285  3480  4304 E HttpOperation: 	... 17 more
08-05 11:24:14.286  3480  4304 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 11:24:14.286  3480  4304 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at hec.a(PG:42)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at hee.a(PG:102)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at czr.a(PG:65)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at kka.a(PG:108)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	... 15 more
08-05 11:24:14.286  3480  4304 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at fal.a(PG:38)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 11:24:14.286  3480  4304 E ExperimentLoader: 	... 17 more
,08-05 11:24:14.417   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 95487, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:24:14.517  3843  3898 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 439)
08-05 11:24:14.517  3843  3898 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 439)
,08-05 11:24:14.526  3843  3898 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 444)
,08-05 11:24:14.528  3843  3898 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-05 11:24:14.529  3843  3898 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 445)
,08-05 11:24:14.536  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:24:14.536  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb665b added. We now have 2 listener(s)
,08-05 11:24:14.538  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 11:24:14.538  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:24:14.538  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:24:14.538  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:24:14.538  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc7ef8 added. We now have 9 listener(s)
08-05 11:24:14.538  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:24:14.539  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 11:24:14.543  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:24:14.550  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:24:14.550  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:14.550  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:14.550  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:24:14.550  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:14.550  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:24:14.550  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:24:14.550  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:24:14.553  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:24:14.553  3843  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:24:14.554  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 11:24:14.554  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70d5a36 added. We now have 3 listener(s)
,08-05 11:24:14.556  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 11:24:14.556  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 11:24:14.556  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 11:24:14.556  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 11:24:14.557  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df00d37 added. We now have 10 listener(s)
,08-05 11:24:14.557  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:24:14.557  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 11:24:14.557  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 11:24:14.557  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:24:14.557  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:24:14.557  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.557  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:24:14.557  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:24:14.558  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eb665b removed from the list
08-05 11:24:14.558  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:24:14.558  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc7ef8 removed from the list
08-05 11:24:14.559  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:14.559  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 11:24:14.559  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:24:14.560  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.560  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:24:14.561  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:24:14.561  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:24:14.561  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:24:14.561  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2cc7ef8 not in the list
08-05 11:24:14.561  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.561  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:24:14.574  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:24:14.574  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:24:14.574  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:24:14.575  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@df00d37 removed from the list
,08-05 11:24:14.575  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:24:14.575  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.575  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:24:14.575  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:24:14.575  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70d5a36 removed from the list
08-05 11:24:14.576  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 11:24:14.576  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c692a4 added. We now have 2 listener(s)
,08-05 11:24:14.577  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:24:14.578  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 11:24:14.578  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:24:14.578  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:24:14.578  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:24:14.578  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e12980d added. We now have 9 listener(s)
08-05 11:24:14.578  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:24:14.579  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:24:14.581  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:24:14.586  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:24:14.586  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:14.586  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:14.586  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:24:14.586  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:14.586  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:24:14.586  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:24:14.586  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:24:14.588  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:24:14.589  3843  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 11:24:14.589  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 11:24:14.589  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2e45d3 added. We now have 3 listener(s)
,08-05 11:24:14.591  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 11:24:14.591  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:24:14.591  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:24:14.592  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:24:14.592  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 11:24:14.592  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c3510 added. We now have 10 listener(s)
08-05 11:24:14.592  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:24:14.592  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:24:14.592  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:24:14.592  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:24:14.592  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:24:14.592  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 11:24:14.596  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:14.597  3843  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-05 11:24:14.597  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 11:24:14.600  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 11:24:14.601  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-05 11:24:14.601  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 11:24:14.604  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-05 11:24:14.604  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-05 11:24:14.605  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-05 11:24:14.605  3843  3898 D BluetoothAdapter: STATE_ON
,08-05 11:24:14.608  4221  4232 D BtGatt.GattService: registerClient() - UUID=cf2151cc-9957-46d7-9ff5-67cc63adb51e
,08-05 11:24:14.609  4221  4237 D BtGatt.GattService: onClientRegistered() - UUID=cf2151cc-9957-46d7-9ff5-67cc63adb51e, clientIf=5,
08-05 11:24:14.609  3843  4064 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-05 11:24:14.610  4221  4249 D BtGatt.GattService: start scan with filters
,08-05 11:24:14.616  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-05 11:24:14.616  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-05 11:24:14.616  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 11:24:14.616  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
08-05 11:24:14.616  4221  4240 D BtGatt.ScanManager: handling starting scan
,08-05 11:24:14.619  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 11:24:14.619  4221  4240 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7bbc271
,08-05 11:24:14.620  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 11:24:14.620  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 11:24:14.622  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-05 11:24:14.623  4221  4237 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 11:24:14.624  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.625  3843  3898 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-05 11:24:14.625  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-05 11:24:14.625  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-05 11:24:14.625  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.625  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-05 11:24:14.625  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 11:24:14.625  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 11:24:14.625  4221  4240 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-05 11:24:14.625  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-05 11:24:14.625  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-05 11:24:14.626  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 11:24:14.626  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-05 11:24:14.628  3843  3898 D BluetoothAdapter: STATE_ON
08-05 11:24:14.629  4221  4249 D BtGatt.GattService: stopScan() - queue size =1
,08-05 11:24:14.630  4221  4231 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 11:24:14.631  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:24:14.631  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 11:24:14.632  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-05 11:24:14.632  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 11:24:14.632  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 11:24:14.633  4221  4237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-05 11:24:14.633  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.634  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 11:24:14.634  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-05 11:24:14.634  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-05 11:24:14.635  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:24:14.635  4221  4240 D BtGatt.ScanManager: Starting BLE batch scan
,08-05 11:24:14.635  4221  4240 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 11:24:14.636  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 11:24:14.640  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-05 11:24:14.640  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:24:14.640  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 11:24:14.645  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 11:24:14.645  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 11:24:14.645  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 11:24:14.646  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 11:24:14.646  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:24:14.646  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 11:24:14.646  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:24:14.646  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c692a4 removed from the list
,08-05 11:24:14.646  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:24:14.646  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e12980d removed from the list
,08-05 11:24:14.646  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 11:24:14.646  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:24:14.647  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:24:14.647  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:24:14.648  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-05 11:24:14.648  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 11:24:14.648  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:24:14.648  4221  4237 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 11:24:14.649  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.648  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e12980d not in the list
08-05 11:24:14.649  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.649  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:24:14.651  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:24:14.651  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:24:14.651  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:24:14.651  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c3510 removed from the list
08-05 11:24:14.651  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:24:14.651  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.651  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:24:14.651  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:24:14.651  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2e45d3 removed from the list
08-05 11:24:14.652  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 11:24:14.652  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@607923c added. We now have 2 listener(s)
08-05 11:24:14.655  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 11:24:14.655  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:24:14.655  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:24:14.655  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:24:14.655  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62fbbc5 added. We now have 9 listener(s)
08-05 11:24:14.656  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:24:14.656  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 11:24:14.656  4221  4237 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-05 11:24:14.656  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:24:14.660   871  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-05 11:24:14.662  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:24:14.667  4221  4237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 11:24:14.668  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:24:14.668  4221  4240 D BtGatt.ScanManager: stopping BLe Batch
,08-05 11:24:14.670  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:24:14.670  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:14.670  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:14.670  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:24:14.670  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:14.670  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:24:14.670  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:24:14.670  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:24:14.672  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:24:14.672  3843  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:24:14.673  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:24:14.673  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e9c4b added. We now have 3 listener(s)
08-05 11:24:14.675  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 11:24:14.675  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:24:14.675  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 11:24:14.676  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:24:14.676  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d99628 added. We now have 10 listener(s)
08-05 11:24:14.676  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:24:14.676  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:24:14.677  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 11:24:14.677  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:24:14.677  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 11:24:14.677  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:24:14.677  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 11:24:14.679  4221  4237 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-05 11:24:14.680  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:24:14.680  4221  4240 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-05 11:24:14.680  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:14.682  3843  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 11:24:14.682  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 11:24:14.686  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:14.688  4221  4237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-05 11:24:14.688  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:24:14.688  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 11:24:14.689  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 11:24:14.690  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 11:24:14.693  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-05 11:24:14.693  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-05 11:24:14.693  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-05 11:24:14.694  3843  3898 D BluetoothAdapter: STATE_ON
,08-05 11:24:14.697  4221  4259 D BtGatt.GattService: registerClient() - UUID=f904de14-2471-42d1-8ae0-dcafc212878a
,08-05 11:24:14.697  4221  4237 D BtGatt.GattService: onClientRegistered() - UUID=f904de14-2471-42d1-8ae0-dcafc212878a, clientIf=5
08-05 11:24:14.698  3843  3855 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-05 11:24:14.698  4221  4232 D BtGatt.GattService: start scan with filters
,08-05 11:24:14.702  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-05 11:24:14.702  4221  4240 D BtGatt.ScanManager: handling starting scan
,08-05 11:24:14.702  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 11:24:14.702  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 11:24:14.702  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 11:24:14.705  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 11:24:14.705  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 11:24:14.705  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 11:24:14.707  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 11:24:14.711  4221  4237 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 11:24:14.711  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.711  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:24:14.711  3843  3898 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-05 11:24:14.712  4221  4240 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 11:24:14.712  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:24:14.712  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:24:14.712  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 11:24:14.712  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 11:24:14.712  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.712  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-05 11:24:14.713  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:24:14.713  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@607923c removed from the list
,08-05 11:24:14.713  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:24:14.713  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62fbbc5 removed from the list
08-05 11:24:14.713  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:24:14.713  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:24:14.714  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.714  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-05 11:24:14.714  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.714  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 11:24:14.716  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 11:24:14.716  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:24:14.716  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:24:14.716  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@62fbbc5 not in the list
,08-05 11:24:14.716  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 11:24:14.716  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 11:24:14.716  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 11:24:14.717  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 11:24:14.717  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 11:24:14.717  3843  3898 D BluetoothAdapter: STATE_ON
,08-05 11:24:14.718  4221  4249 D BtGatt.GattService: stopScan() - queue size =1
08-05 11:24:14.719  4221  4231 D BtGatt.GattService: unregisterClient() - clientIf=5
08-05 11:24:14.719  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 11:24:14.719  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 11:24:14.720  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 11:24:14.720  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-05 11:24:14.720  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-05 11:24:14.722  4221  4237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-05 11:24:14.722  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.722  4221  4240 D BtGatt.ScanManager: Starting BLE batch scan
08-05 11:24:14.722  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 11:24:14.722  4221  4240 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-05 11:24:14.722  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-05 11:24:14.722  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-05 11:24:14.722  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 11:24:14.723  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:24:14.725  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 11:24:14.725  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:24:14.725  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-05 11:24:14.725  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d99628 removed from the list
08-05 11:24:14.725  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-05 11:24:14.725  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 11:24:14.725  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-05 11:24:14.726  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:24:14.726  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:24:14.726  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-05 11:24:14.726  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10e9c4b removed from the list
,08-05 11:24:14.726  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 11:24:14.727  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 11:24:14.727  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e45ecd4 added. We now have 2 listener(s)
08-05 11:24:14.729  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 11:24:14.730  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:24:14.730  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 11:24:14.730  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 11:24:14.730  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e69e7d added. We now have 9 listener(s)
08-05 11:24:14.730  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 11:24:14.731  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 11:24:14.736  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:24:14.740  4221  4237 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-05 11:24:14.741  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.744  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:24:14.744  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:14.744  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:14.744  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:24:14.744  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:14.744  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:24:14.744  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:24:14.744  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:24:14.747  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:24:14.747  3843  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:24:14.747  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 11:24:14.747  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be449c3 added. We now have 3 listener(s)
,08-05 11:24:14.749  4221  4237 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-05 11:24:14.749  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.751  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 11:24:14.751  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:24:14.751  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:24:14.751  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:24:14.751  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:14.752  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7f0240 added. We now have 10 listener(s)
08-05 11:24:14.753  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:24:14.753  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:24:14.753  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 11:24:14.753  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-05 11:24:14.753  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 11:24:14.753  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 11:24:14.756  3843  3898 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-05 11:24:14.756  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-05 11:24:14.758  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:24:14.760  4221  4237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 11:24:14.760  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.760  4221  4240 D BtGatt.ScanManager: stopping BLe Batch
08-05 11:24:14.764  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 11:24:14.765  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-05 11:24:14.765  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 11:24:14.769  4221  4237 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-05 11:24:14.769  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:24:14.769  4221  4240 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 11:24:14.771  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-05 11:24:14.772  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-05 11:24:14.772  3843  3898 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-05 11:24:14.773  3843  3898 D BluetoothAdapter: STATE_ON
,08-05 11:24:14.777  4221  4231 D BtGatt.GattService: registerClient() - UUID=0c5ebdff-c790-4bc5-817a-9c694b99968b
,08-05 11:24:14.778  4221  4237 D BtGatt.GattService: onClientRegistered() - UUID=0c5ebdff-c790-4bc5-817a-9c694b99968b, clientIf=5
,08-05 11:24:14.779  3843  4064 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-05 11:24:14.779  4221  4237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-05 11:24:14.779  4221  4232 D BtGatt.GattService: start scan with filters
08-05 11:24:14.779  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.783  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-05 11:24:14.783  4221  4240 D BtGatt.ScanManager: handling starting scan
,08-05 11:24:14.783  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-05 11:24:14.783  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-05 11:24:14.783  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-05 11:24:14.787  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-05 11:24:14.787  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-05 11:24:14.788  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-05 11:24:14.790  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-05 11:24:14.791  4221  4237 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-05 11:24:14.791  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.792  4221  4240 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-05 11:24:14.796  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 11:24:14.796  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:24:14.796  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 11:24:14.797  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 11:24:14.797  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:24:14.797  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-05 11:24:14.797  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:24:14.798  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e45ecd4 removed from the list
08-05 11:24:14.798  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:24:14.798  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e69e7d removed from the list
08-05 11:24:14.798  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
08-05 11:24:14.798  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:24:14.799  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.799  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-05 11:24:14.799  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:24:14.799  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:24:14.801  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 11:24:14.801  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:24:14.801  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:24:14.801  4221  4237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-05 11:24:14.801  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e69e7d not in the list
08-05 11:24:14.801  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 11:24:14.801  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:24:14.801  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-05 11:24:14.801  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 11:24:14.802  4221  4240 D BtGatt.ScanManager: Starting BLE batch scan
08-05 11:24:14.802  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 11:24:14.802  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-05 11:24:14.802  4221  4240 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-05 11:24:14.803  3843  3898 D BluetoothAdapter: STATE_ON
08-05 11:24:14.804  4221  4232 D BtGatt.GattService: stopScan() - queue size =1
08-05 11:24:14.805  4221  4249 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-05 11:24:14.806  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-05 11:24:14.806  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-05 11:24:14.806  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-05 11:24:14.806  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-05 11:24:14.806  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-05 11:24:14.808  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 11:24:14.808  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-05 11:24:14.808  3843  3898 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 11:24:14.808  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 11:24:14.809  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:24:14.810  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-05 11:24:14.810  3843  3843 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-05 11:24:14.811  3843  3843 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-05 11:24:14.811  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:24:14.811  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:24:14.811  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:24:14.811  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7f0240 removed from the list
08-05 11:24:14.811  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 11:24:14.811  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 11:24:14.811  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:24:14.811  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 11:24:14.812  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be449c3 removed from the list
08-05 11:24:14.812  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:24:14.812  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c72026c added. We now have 2 listener(s)
08-05 11:24:14.815  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 11:24:14.815  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:24:14.815  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:24:14.815  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 11:24:14.815  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d02035 added. We now have 9 listener(s)
08-05 11:24:14.816  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:24:14.816  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 11:24:14.820  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 11:24:14.825  4221  4237 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-05 11:24:14.825  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.828  3843  3898 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 11:24:14.828  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 11:24:14.828  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 11:24:14.828  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 11:24:14.828  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 11:24:14.828  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 11:24:14.828  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 11:24:14.828  3843  3898 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 11:24:14.831  3843  3898 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 11:24:14.831  3843  3898 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 11:24:14.833  4221  4237 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-05 11:24:14.833  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.833  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 11:24:14.834  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c232e3b added. We now have 3 listener(s)
08-05 11:24:14.835  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 11:24:14.835  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-05 11:24:14.836  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 11:24:14.836  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 11:24:14.836  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 11:24:14.836  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb2d958 added. We now have 10 listener(s)
08-05 11:24:14.836  3843  3898 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 11:24:14.836  3843  3898 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 11:24:14.836  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:24:14.836  3843  3898 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 11:24:14.837  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 11:24:14.837  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:24:14.837  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 11:24:14.837  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-05 11:24:14.837  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c72026c removed from the list
,08-05 11:24:14.837  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:24:14.837  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d02035 removed from the list
,08-05 11:24:14.838  3843  3843 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 11:24:14.838  3843  3898 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 11:24:14.838  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:24:14.839  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:24:14.839  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:24:14.840  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 11:24:14.841  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:24:14.841  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 11:24:14.841  3843  3898 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d02035 not in the list
08-05 11:24:14.841  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:24:14.841  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 11:24:14.843  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 11:24:14.843  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-05 11:24:14.844  3843  3898 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 11:24:14.844  3843  3898 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb2d958 removed from the list
,08-05 11:24:14.844  3843  3898 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 11:24:14.844  3843  3898 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 11:24:14.845  4221  4237 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-05 11:24:14.845  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-05 11:24:14.844  3843  3898 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 11:24:14.845  3843  3898 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-05 11:24:14.845  3843  3898 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c232e3b removed from the list
08-05 11:24:14.847  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything,
08-05 11:24:14.847  4221  4240 D BtGatt.ScanManager: stopping BLe Batch
08-05 11:24:14.847  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 11:24:14.848  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-05 11:24:14.848  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:24:14.848  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-05 11:24:14.849  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-05 11:24:14.856  4221  4237 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-05 11:24:14.856  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:24:14.857  4221  4240 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-05 11:24:14.861  3843  4305 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 452, name: My test thread name)
,08-05 11:24:14.862  3843  4305 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 452, thread name: My test thread name)
,08-05 11:24:14.862  3843  4305 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 452, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-05 11:24:14.864  3843  4306 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 454, name: My test thread name)
,08-05 11:24:14.864  3843  4306 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 454, thread name: My test thread name)
08-05 11:24:14.864  3843  4306 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 454, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-05 11:24:14.865  4221  4237 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-05 11:24:14.865  4221  4237 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-05 11:24:14.866  3843  3898 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-05 11:24:14.866  3843  3898 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,08-05 11:24:14.867  3843  3898 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,08-05 11:24:14.867  3843  3898 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-05 11:24:14.867  3843  3898 D com.test.thalitest.ThaliTestRunner: Total duration: 22886 ms
,08-05 11:24:14.869  3843  3898 I jxcore-log: Total number of executed tests:  80
08-05 11:24:14.869  3843  3898 I jxcore-log: 
,08-05 11:24:14.869  3843  3898 I jxcore-log: Number of passed tests:  80
08-05 11:24:14.869  3843  3898 I jxcore-log: 
08-05 11:24:14.869  3843  3898 I jxcore-log: Number of failed tests:  0
08-05 11:24:14.869  3843  3898 I jxcore-log: 
,08-05 11:24:14.869  3843  3898 I jxcore-log: Number of ignored tests:  0
08-05 11:24:14.869  3843  3898 I jxcore-log: 
08-05 11:24:14.870  3843  3898 I jxcore-log: Total duration:  22886
08-05 11:24:14.870  3843  3898 I jxcore-log: 
,08-05 11:24:14.872  3843  3898 I jxcore-log: Unit Test app is loaded
08-05 11:24:14.872  3843  3898 I jxcore-log: 
,08-05 11:24:14.880  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.880  3843  3898 I jxcore-log: 
,08-05 11:24:14.882  3843  3843 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-05 11:24:14.885  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.885  3843  3898 I jxcore-log: 
,08-05 11:24:14.886  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.886  3843  3898 I jxcore-log: 
,08-05 11:24:14.887  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,08-05 11:24:14.887  3843  3898 I jxcore-log: 
,08-05 11:24:14.888  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.888  3843  3898 I jxcore-log: 
,08-05 11:24:14.889  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.889  3843  3898 I jxcore-log: 
,08-05 11:24:14.891  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.891  3843  3898 I jxcore-log: 
,08-05 11:24:14.893  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:24:14.893  3843  3898 I jxcore-log: 
,08-05 11:24:14.894  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:24:14.894  3843  3898 I jxcore-log: 
,08-05 11:24:14.895  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 11:24:14.895  3843  3898 I jxcore-log: 
,08-05 11:24:14.896  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 11:24:14.896  3843  3898 I jxcore-log: 
,08-05 11:24:14.897  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 11:24:14.897  3843  3898 I jxcore-log: 
,08-05 11:24:14.898  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.898  3843  3898 I jxcore-log: 
,08-05 11:24:14.899  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.899  3843  3898 I jxcore-log: 
,08-05 11:24:14.900  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:24:14.900  3843  3898 I jxcore-log: 
,08-05 11:24:14.901  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:24:14.901  3843  3898 I jxcore-log: 
,08-05 11:24:14.902  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:24:14.902  3843  3898 I jxcore-log: 
,08-05 11:24:14.902  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:24:14.902  3843  3898 I jxcore-log: 
,08-05 11:24:14.903  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:24:14.903  3843  3898 I jxcore-log: 
,08-05 11:24:14.904  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 11:24:14.904  3843  3898 I jxcore-log: 
,08-05 11:24:14.905  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:24:14.905  3843  3898 I jxcore-log: 
08-05 11:24:14.905  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 11:24:14.905  3843  3898 I jxcore-log: 
,08-05 11:24:14.906  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:24:14.906  3843  3898 I jxcore-log: 
,08-05 11:24:14.907  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 11:24:14.907  3843  3898 I jxcore-log: 
,08-05 11:24:14.908  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.908  3843  3898 I jxcore-log: 
,08-05 11:24:14.909  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.909  3843  3898 I jxcore-log: 
,08-05 11:24:14.909  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.909  3843  3898 I jxcore-log: 
,08-05 11:24:14.910  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.910  3843  3898 I jxcore-log: 
08-05 11:24:14.911  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.911  3843  3898 I jxcore-log: 
,08-05 11:24:14.912  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 11:24:14.912  3843  3898 I jxcore-log: 
,08-05 11:24:14.915  3843  3898 I jxcore-log: My device name is: motorola-Nexus 6
08-05 11:24:14.915  3843  3898 I jxcore-log: 
,08-05 11:24:15.140  3843  3843 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 11:24:15.227  3843  3843 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 11:24:15.311  3843  3843 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 11:24:16.335   871  1304 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,08-05 11:24:17.258  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-05 11:24:17.258  3843  3898 I jxcore-log: 
,08-05 11:24:17.873  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-05 11:24:17.873  3843  3898 I jxcore-log: 
,08-05 11:24:17.898  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-05 11:24:17.898  3843  3898 I jxcore-log: 
,08-05 11:24:19.282  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-05 11:24:19.282  3843  3898 I jxcore-log: 
,08-05 11:24:19.512  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-05 11:24:19.512  3843  3898 I jxcore-log: 
,08-05 11:24:19.518  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-05 11:24:19.518  3843  3898 I jxcore-log: 
,08-05 11:24:19.536  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-05 11:24:19.536  3843  3898 I jxcore-log: 
,08-05 11:24:19.540  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
08-05 11:24:19.540  3843  3898 I jxcore-log: 
,08-05 11:24:20.216  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js,
08-05 11:24:20.216  3843  3898 I jxcore-log: 
,08-05 11:24:20.230  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js,
08-05 11:24:20.230  3843  3898 I jxcore-log: 
,08-05 11:24:20.241  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-05 11:24:20.241  3843  3898 I jxcore-log: 
,08-05 11:24:20.248  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-05 11:24:20.248  3843  3898 I jxcore-log: 
,08-05 11:24:20.299  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-05 11:24:20.299  3843  3898 I jxcore-log: 
,08-05 11:24:20.358  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-05 11:24:20.358  3843  3898 I jxcore-log: 
,08-05 11:24:20.366  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-05 11:24:20.366  3843  3898 I jxcore-log: 
,08-05 11:24:20.532  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-05 11:24:20.532  3843  3898 I jxcore-log: 
,08-05 11:24:20.559  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-05 11:24:20.559  3843  3898 I jxcore-log: 
,08-05 11:24:20.566  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-05 11:24:20.566  3843  3898 I jxcore-log: 
,08-05 11:24:20.572  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-05 11:24:20.572  3843  3898 I jxcore-log: 
,08-05 11:24:20.591  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-05 11:24:20.591  3843  3898 I jxcore-log: 
,08-05 11:24:20.676  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-05 11:24:20.676  3843  3898 I jxcore-log: 
,08-05 11:24:20.688  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-05 11:24:20.688  3843  3898 I jxcore-log: 
,08-05 11:24:20.716  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-05 11:24:20.716  3843  3898 I jxcore-log: 
,08-05 11:24:20.729  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-05 11:24:20.729  3843  3898 I jxcore-log: 
,08-05 11:24:20.748  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-05 11:24:20.748  3843  3898 I jxcore-log: 
,08-05 11:24:20.785  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-05 11:24:20.785  3843  3898 I jxcore-log: 
,08-05 11:24:20.792  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-05 11:24:20.792  3843  3898 I jxcore-log: 
,08-05 11:24:21.010  3843  3898 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-05 11:24:21.010  3843  3898 I jxcore-log: 
,08-05 11:24:21.023  3843  3898 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-05 11:24:21.024  3843  3898 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-05 11:24:21.024  3843  3898 I jxcore-log: 
,08-05 11:24:21.072  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 11:24:21.072  3843  3898 I jxcore-log: 
,08-05 11:24:21.073  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 11:24:21.073  3843  3898 I jxcore-log: 
,08-05 11:24:21.074  3843  3898 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 11:24:21.074  3843  3898 I jxcore-log: 
08-05 11:24:21.074  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 11:24:21.074  3843  3898 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,08-05 11:24:21.074  3843  3898 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 11:24:21.074  3843  3898 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-05 11:24:21.583   871  1306 D ConnectivityService: handlePromptUnvalidated 102
,08-05 11:24:44.904  3785  4308 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 11:24:44.958  3785  4309 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 11:24:44.997  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:24:45.002  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:24:45.035  1508  3822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 11:24:45.035  1508  3822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-05 11:24:45.035  1508  3822 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:24:45.036  1508  3822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:24:45.072  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:24:45.078  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:24:45.135  1508  2353 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 11:24:45.135  1508  2353 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 11:24:45.136  1508  2353 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:24:45.136  1508  2353 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:24:45.175  3785  4309 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:24:45.176  3785  4308 E BooksSync: Soft error
08-05 11:24:45.176  3785  4308 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:24:45.176  3785  4308 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-05 11:24:45.177  3785  4308 E BooksSync: Sync error
08-05 11:24:45.177  3785  4308 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:24:45.177  3785  4308 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 11:24:45.177  3785  4308 I BooksSync: Finished books sync
08-05 11:24:45.183   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 197792, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:24:56.926  1655  1772 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-05 11:24:56.926  1655  1772 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-05 11:24:56.970  1508  1508 I ConfigService: onCreate
,08-05 11:25:02.067  1508  1508 I ConfigService: onDestroy
,08-05 11:25:15.569  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:25:15.575  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:25:15.635  1508  2012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:25:15.635  1508  2012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 11:25:15.635  1508  2012 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:25:15.635  1508  2012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:25:15.673  3480  4314 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 11:25:15.673  3480  4314 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at blb.a(PG:3937)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at czp.a(PG:18188)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:25:15.673  3480  4314 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	... 12 more
08-05 11:25:15.673  3480  4314 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at fal.a(PG:38)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:25:15.673  3480  4314 E HttpOperation: 	... 14 more
,08-05 11:25:15.737  1508  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:25:15.737  1508  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 11:25:15.737  1508  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:25:15.737  1508  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:25:15.776  3480  4314 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 11:25:15.776  3480  4314 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at hec.a(PG:42)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at hee.a(PG:102)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at czr.a(PG:65)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at kka.a(PG:108)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at czp.a(PG:19176)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:25:15.776  3480  4314 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	... 15 more
08-05 11:25:15.776  3480  4314 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at fal.a(PG:38)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:25:15.776  3480  4314 E HttpOperation: 	... 17 more
,08-05 11:25:15.776  3480  4314 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 11:25:15.776  3480  4314 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at hec.a(PG:42)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at hee.a(PG:102)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at czr.a(PG:65)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at kka.a(PG:108)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: ,	at czq.run(PG:1686)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
,08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	... 15 more
08-05 11:25:15.776  3480  4314 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at fal.a(PG:38)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 11:25:15.776  3480  4314 E ExperimentLoader: 	... 17 more
,08-05 11:25:15.930   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 198458, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:25:19.725   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=232797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:25:24.912   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=237983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-05 11:25:38.314  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:25:38.316  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:25:38.327  3534  4318 V GoogleAuthProtoRequest: [301] a.<init>: mAccountName set to: thalitester@gmail.com
,08-05 11:25:38.349  1508  1968 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-05 11:25:38.349  1508  1968 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-05 11:25:38.349  1508  1968 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:25:38.349  1508  1968 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:25:38.367  3534  4318 W ExperimentUpdateService: [301] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: [301] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-05 11:25:38.368  3534  4318 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-05 11:25:46.154  3078  4319 V KeepSync: Connecting to GoogleApiClient
,08-05 11:25:46.155   871  1888 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 11:25:46.193  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:25:46.195  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:25:46.218  1508  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 11:25:46.218  1508  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-05 11:25:46.218  1508  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:25:46.218  1508  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:25:46.235  1865  4320 V BaseAuthAsyncOperation: access token request failed
,08-05 11:25:46.236  3078  4319 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 11:25:46.288  1508  3822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-05 11:25:46.288  1508  3822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-05 11:25:46.288  1508  3822 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:25:46.288  1508  3822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:25:46.308  3078  4319 E KeepSync: IOException
08-05 11:25:46.308  3078  4319 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 11:25:46.308  3078  4319 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:25:46.308  3078  4319 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 11:25:46.308  3078  4319 E KeepSync: 	... 10 more
08-05 11:25:46.308  3078  4319 W KeepSync: Sync result 2
,08-05 11:25:46.313   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 246452, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:25:46.359  3785  4321 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 11:25:46.375  3785  4322 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 11:25:46.421  1508  1968 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-05 11:25:46.421  1508  1968 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 11:25:46.421  1508  1968 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:25:46.421  1508  1968 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:25:46.463  1508  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-05 11:25:46.464  1508  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 11:25:46.464  1508  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:25:46.464  1508  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:25:46.488  3785  4322 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:25:46.489  3785  4321 E BooksSync: Soft error
08-05 11:25:46.489  3785  4321 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:25:46.489  3785  4321 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 11:25:46.489  3785  4321 E BooksSync: Sync error
08-05 11:25:46.489  3785  4321 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:25:46.489  3785  4321 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 11:25:46.489  3785  4321 I BooksSync: Finished books sync
,08-05 11:25:46.501   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 259355, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:26:05.486   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=278557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:26:11.552   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=284623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-05 11:26:45.212  1508  2033 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-05 11:26:46.931  3078  4329 V KeepSync: Connecting to GoogleApiClient
08-05 11:26:46.931   871  1521 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 11:26:46.991  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:26:46.993  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:26:47.017  1508  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 11:26:47.017  1508  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-05 11:26:47.017  1508  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:26:47.018  1508  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:26:47.055  1865  4332 V BaseAuthAsyncOperation: access token request failed
,08-05 11:26:47.056  3078  4329 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 11:26:47.060  1508  2353 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:26:47.060  1508  2353 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 11:26:47.060  1508  2353 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:26:47.060  1508  2353 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:26:47.079  3480  4331 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 11:26:47.079  3480  4331 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at blb.a(PG:3937)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at czp.a(PG:18188)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:26:47.079  3480  4331 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	... 12 more
08-05 11:26:47.079  3480  4331 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at fal.a(PG:38)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:26:47.079  3480  4331 E HttpOperation: 	... 14 more
,08-05 11:26:47.115  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:26:47.115  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 11:26:47.115  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:26:47.115  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:26:47.152  3480  4331 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 11:26:47.152  3480  4331 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at hec.a(PG:42)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at hee.a(PG:102)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at czr.a(PG:65)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at kka.a(PG:108)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at czp.a(PG:19176)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:26:47.152  3480  4331 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	... 15 more
08-05 11:26:47.152  3480  4331 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at fal.a(PG:38)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:26:47.152  3480  4331 E HttpOperation: 	... 17 more
,08-05 11:26:47.152  3480  4331 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 11:26:47.152  3480  4331 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at hec.a(PG:42)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at hee.a(PG:102)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at czr.a(PG:65)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at kka.a(PG:108)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	... 15 more
08-05 11:26:47.152  3480  4331 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at fal.a(PG:38)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 11:26:47.152  3480  4331 E ExperimentLoader: 	... 17 more
,08-05 11:26:47.278  1508  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-05 11:26:47.279  1508  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-05 11:26:47.279  1508  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:26:47.279  1508  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:26:47.285   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 290939, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:26:47.298  3078  4329 E KeepSync: IOException
08-05 11:26:47.298  3078  4329 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 11:26:47.298  3078  4329 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:26:47.298  3078  4329 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 11:26:47.298  3078  4329 E KeepSync: 	... 10 more
08-05 11:26:47.299  3078  4329 W KeepSync: Sync result 2
,08-05 11:26:47.313   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 290541, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:26:51.885   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=324957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:26:57.006   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=330077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-05 11:27:09.046  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:27:09.071  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:27:09.078  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:27:09.134  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-05 11:27:09.135  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-05 11:27:09.135  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:27:09.135  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:27:09.169  1508  1520 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-05 11:27:09.169  1508  1520 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-05 11:27:09.169  1508  1520 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-05 11:27:09.169  1508  1520 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-05 11:27:09.169  1508  1520 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-05 11:27:09.169  1508  1520 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-05 11:27:09.169  1508  1520 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-05 11:27:09.179  3443  3472 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-05 11:27:09.179  3443  3472 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-05 11:27:09.179  3443  3472 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-05 11:27:09.179  3443  3472 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-05 11:27:09.179  3443  3472 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-05 11:27:09.179  3443  3472 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-05 11:27:09.179  3443  3472 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-05 11:27:48.811  3785  4347 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 11:27:48.870  3785  4348 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 11:27:48.890  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:27:48.893  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:27:48.956  1508  3822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 11:27:48.956  1508  3822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 11:27:48.956  1508  3822 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:27:48.956  1508  3822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:27:49.005  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:27:49.009  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:27:49.050  1508  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 11:27:49.050  1508  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-05 11:27:49.050  1508  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:27:49.050  1508  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:27:49.078  3785  4348 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-05 11:27:49.079  3785  4347 E BooksSync: Soft error
08-05 11:27:49.079  3785  4347 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:27:49.079  3785  4347 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-05 11:27:49.079  3785  4347 E BooksSync: Sync error
08-05 11:27:49.079  3785  4347 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:27:49.079  3785  4347 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 11:27:49.079  3785  4347 I BooksSync: Finished books sync
,08-05 11:27:49.092   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 381773, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:28:19.252  3078  4350 V KeepSync: Connecting to GoogleApiClient
,08-05 11:28:19.253   871  1889 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 11:28:19.338  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:28:19.341  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:28:19.392  1508  2353 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 11:28:19.392  1508  2353 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.,
08-05 11:28:19.392  1508  2353 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:28:19.392  1508  2353 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:28:19.418  1865  4351 V BaseAuthAsyncOperation: access token request failed
,08-05 11:28:19.419  3078  4350 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 11:28:19.485  1508  3822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-05 11:28:19.485  1508  3822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-05 11:28:19.485  1508  3822 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:28:19.485  1508  3822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:28:19.502  3078  4350 E KeepSync: IOException
08-05 11:28:19.502  3078  4350 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 11:28:19.502  3078  4350 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:28:19.502  3078  4350 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 11:28:19.502  3078  4350 E KeepSync: 	... 10 more
08-05 11:28:19.502  3078  4350 W KeepSync: Sync result 2
,08-05 11:28:19.519   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 382697, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:28:51.477  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:28:51.479  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:28:51.512  1508  1968 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:28:51.512  1508  1968 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 11:28:51.512  1508  1968 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:28:51.512  1508  1968 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:28:51.534  3480  4355 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 11:28:51.534  3480  4355 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at blb.a(PG:3937)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at czp.a(PG:18188)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:28:51.534  3480  4355 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	... 12 more
08-05 11:28:51.534  3480  4355 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at fal.a(PG:38)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:28:51.534  3480  4355 E HttpOperation: 	... 14 more
,08-05 11:28:51.604  1508  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:28:51.604  1508  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 11:28:51.604  1508  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:28:51.605  1508  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:28:51.633  3480  4355 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 11:28:51.633  3480  4355 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at hec.a(PG:42)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at hee.a(PG:102)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at czr.a(PG:65)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at kka.a(PG:108)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at czp.a(PG:19176)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:28:51.633  3480  4355 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	... 15 more
08-05 11:28:51.633  3480  4355 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at fal.a(PG:38)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:28:51.633  3480  4355 E HttpOperation: 	... 17 more
08-05 11:28:51.633  3480  4355 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 11:28:51.633  3480  4355 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at hec.a(PG:42)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at hee.a(PG:102)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at czr.a(PG:65)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at kka.a(PG:108)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	... 15 more
08-05 11:28:51.633  3480  4355 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at fal.a(PG:38)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 11:28:51.633  3480  4355 E ExperimentLoader: 	... 17 more
,08-05 11:28:51.763   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 444230, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:30:24.264  3078  4362 V KeepSync: Connecting to GoogleApiClient
08-05 11:30:24.264   871  1690 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 11:30:24.332  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:30:24.336  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:30:24.375  1508  2935 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 11:30:24.375  1508  2935 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-05 11:30:24.375  1508  2935 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:30:24.375  1508  2935 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:30:24.397  1865  4363 V BaseAuthAsyncOperation: access token request failed
,08-05 11:30:24.398  3078  4362 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 11:30:24.462  1508  3822 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-05 11:30:24.462  1508  3822 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-05 11:30:24.463  1508  3822 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:30:24.463  1508  3822 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:30:24.486  3078  4362 E KeepSync: IOException
08-05 11:30:24.486  3078  4362 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 11:30:24.486  3078  4362 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:30:24.486  3078  4362 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 11:30:24.486  3078  4362 E KeepSync: 	... 10 more
,08-05 11:30:24.487  3078  4362 W KeepSync: Sync result 2
,08-05 11:30:24.496   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 537216, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:31:02.279  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:31:02.281  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:31:02.292  3534  4366 V GoogleAuthProtoRequest: [302] a.<init>: mAccountName set to: thalitester@gmail.com
,08-05 11:31:02.337  1508  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-05 11:31:02.337  1508  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-05 11:31:02.337  1508  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:31:02.337  1508  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:31:02.362  3534  4366 W ExperimentUpdateService: [302] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: [302] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167),
08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-05 11:31:02.363  3534  4366 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-05 11:31:53.537  3785  4369 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 11:31:53.559  3785  4370 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 11:31:53.574  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:31:53.576  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:31:53.599  1508  1968 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 11:31:53.599  1508  1968 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-05 11:31:53.599  1508  1968 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:31:53.599  1508  1968 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:31:53.646  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-05 11:31:53.649  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:31:53.677  1508  2353 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-05 11:31:53.677  1508  2353 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-05 11:31:53.677  1508  2353 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:31:53.677  1508  2353 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-05 11:31:53.695  3785  4370 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:31:53.696  3785  4369 E BooksSync: Soft error
08-05 11:31:53.696  3785  4369 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:31:53.696  3785  4369 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 11:31:53.696  3785  4369 E BooksSync: Sync error
08-05 11:31:53.696  3785  4369 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:31:53.696  3785  4369 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 11:31:53.696  3785  4369 I BooksSync: Finished books sync
,08-05 11:31:53.718   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 626565, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:31:53.730   871   880 I art     : Background partial concurrent mark sweep GC freed 38086(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 5.128ms total 119.608ms
,08-05 11:32:59.807  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:32:59.811  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:32:59.867  1508  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:32:59.867  1508  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 11:32:59.867  1508  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:32:59.868  1508  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:32:59.903  3480  4378 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 11:32:59.903  3480  4378 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at blb.a(PG:3937)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at czp.a(PG:18188)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:32:59.903  3480  4378 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	... 12 more
08-05 11:32:59.903  3480  4378 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at fal.a(PG:38)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:32:59.903  3480  4378 E HttpOperation: 	... 14 more
,08-05 11:32:59.983  1508  1968 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:32:59.983  1508  1968 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 11:32:59.983  1508  1968 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:32:59.983  1508  1968 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:33:00.010  3480  4378 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 11:33:00.010  3480  4378 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at hec.a(PG:42)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at hee.a(PG:102)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at czr.a(PG:65)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at kka.a(PG:108)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at czp.a(PG:19176)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:33:00.010  3480  4378 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	... 15 more
08-05 11:33:00.010  3480  4378 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at fal.a(PG:38)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:33:00.010  3480  4378 E HttpOperation: 	... 17 more
,08-05 11:33:00.010  3480  4378 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 11:33:00.010  3480  4378 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at hec.a(PG:42)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at hee.a(PG:102)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at czr.a(PG:65)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at kka.a(PG:108)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	... 15 more
08-05 11:33:00.010  3480  4378 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at fal.a(PG:38)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 11:33:00.010  3480  4378 E ExperimentLoader: 	... 17 more
,08-05 11:33:00.144   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 692579, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:34:33.839  3078  4386 V KeepSync: Connecting to GoogleApiClient
,08-05 11:34:33.840   871  1888 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 11:34:33.938  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:34:33.941  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:34:33.982  1508  1968 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 11:34:33.982  1508  1968 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-05 11:34:33.982  1508  1968 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:34:33.982  1508  1968 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:34:34.005  1865  4387 V BaseAuthAsyncOperation: access token request failed
,08-05 11:34:34.007  3078  4386 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 11:34:34.081  1508  2935 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-05 11:34:34.081  1508  2935 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-05 11:34:34.081  1508  2935 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:34:34.081  1508  2935 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:34:34.102  3078  4386 E KeepSync: IOException
08-05 11:34:34.102  3078  4386 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 11:34:34.102  3078  4386 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:34:34.102  3078  4386 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 11:34:34.102  3078  4386 E KeepSync: 	... 10 more
08-05 11:34:34.102  3078  4386 W KeepSync: Sync result 2
,08-05 11:34:34.118   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 786816, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:36:00.046   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=873117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:36:14.832   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=887903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:36:22.392   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=895464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:36:40.526   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=913597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:36:47.459   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=920531, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:37:05.592   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=938664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:37:12.525   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=945597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:37:30.645   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=963717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:37:37.565   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=970637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:37:55.712   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=988784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:38:02.632   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=995703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:38:20.766   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1013837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:38:27.698   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1020770, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:38:45.832   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1038904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:38:52.765   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1045837, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:39:10.886   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1063957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:39:14.405  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:39:14.407  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:39:14.420  3534  4399 V GoogleAuthProtoRequest: [303] a.<init>: mAccountName set to: thalitester@gmail.com
,08-05 11:39:14.459  1508  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-05 11:39:14.460  1508  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-05 11:39:14.460  1508  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:39:14.460  1508  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:39:14.478  3534  4399 W ExperimentUpdateService: [303] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: [303] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-05 11:39:14.479  3534  4399 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-05 11:39:26.472   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1079544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:39:35.965   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1089037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:39:42.898   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1095970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:40:01.019   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1114090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:40:02.594  3785  4404 I BooksSync: Starting books sync for 61035162, extras: ade
,08-05 11:40:02.629  3785  4405 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-05 11:40:02.648  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:40:02.651  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:40:02.695  1508  2935 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 11:40:02.696  1508  2935 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-05 11:40:02.696  1508  2935 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:40:02.696  1508  2935 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:40:02.750  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:40:02.755  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:40:02.792  1508  2012 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-05 11:40:02.792  1508  2012 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-05 11:40:02.792  1508  2012 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:40:02.792  1508  2012 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:40:02.809  3785  4405 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-05 11:40:02.810  3785  4404 E BooksSync: Soft error
08-05 11:40:02.810  3785  4404 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:40:02.810  3785  4404 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-05 11:40:02.810  3785  4404 E BooksSync: Sync error
08-05 11:40:02.810  3785  4404 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-05 11:40:02.810  3785  4404 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-05 11:40:02.810  3785  4404 I BooksSync: Finished books sync
,08-05 11:40:02.821   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1115592, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:40:07.939   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1121010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:40:26.072   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1139144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:40:33.005   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1146077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:40:51.138   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1164210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:40:58.072   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1171143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:41:15.982  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:41:15.987  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:41:16.031  1508  2935 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-05 11:41:16.031  1508  2935 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-05 11:41:16.031  1508  2935 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:41:16.031  1508  2935 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:41:16.067  3480  4409 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-05 11:41:16.067  3480  4409 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at blb.a(PG:3937)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at czp.a(PG:18188)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:41:16.067  3480  4409 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	... 12 more
08-05 11:41:16.067  3480  4409 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at fal.a(PG:38)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:41:16.067  3480  4409 E HttpOperation: 	... 14 more
,08-05 11:41:16.113  1508  1520 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-05 11:41:16.113  1508  1520 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-05 11:41:16.113  1508  1520 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:41:16.113  1508  1520 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:41:16.146  3480  4409 E HttpOperation: [getmobileexperiments] Unexpected exception
08-05 11:41:16.146  3480  4409 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at jdm.a(PG:82)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at jcs.o(PG:406)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at jcn.a(PG:1379)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at jcs.i(PG:143)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at hec.a(PG:42)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at hee.a(PG:102)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at czr.a(PG:65)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at kka.a(PG:108)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at czp.a(PG:19176)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at czp.a(PG:9081)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at czq.run(PG:1686)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:41:16.146  3480  4409 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at jdj.a(PG:4091)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at jdj.a(PG:1125)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at jdm.a(PG:77)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	... 15 more
08-05 11:41:16.146  3480  4409 E HttpOperation: Caused by: faj: BadAuthentication
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at fal.a(PG:38)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	at jdj.a(PG:4089)
08-05 11:41:16.146  3480  4409 E HttpOperation: 	... 17 more
,08-05 11:41:16.146  3480  4409 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-05 11:41:16.146  3480  4409 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at jdm.a(PG:82)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at jcs.o(PG:406)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at jcn.a(PG:1379)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at jcs.i(PG:143)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at hec.a(PG:42)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at hee.a(PG:102)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at czr.a(PG:65)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at kka.a(PG:108)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at czp.a(PG:19176)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at czp.a(PG:9081)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at czq.run(PG:1686)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at jdj.a(PG:4091)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at jdj.a(PG:1125)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at jdm.a(PG:77)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	... 15 more
08-05 11:41:16.146  3480  4409 E ExperimentLoader: Caused by: faj: BadAuthentication
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at fal.a(PG:38)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	at jdj.a(PG:4089)
08-05 11:41:16.146  3480  4409 E ExperimentLoader: 	... 17 more
,08-05 11:41:16.191   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1189263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:41:16.276   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1188705, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:41:23.752   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1196823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:41:41.246   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1214317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:41:46.244   871   883 I UsageStatsService: User[0] Flushing usage stats to disk
,08-05 11:41:48.792   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1221864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:42:06.312   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1239383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:42:13.858   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1246930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:42:31.366   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1264437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:42:38.952   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1272023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:42:52.757  3078  4416 V KeepSync: Connecting to GoogleApiClient
08-05 11:42:52.757   871  1753 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-05 11:42:52.806  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:42:52.808  1508  1508 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 11:42:52.841  1508  3821 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-05 11:42:52.841  1508  3821 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-05 11:42:52.841  1508  3821 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-05 11:42:52.841  1508  3821 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:42:52.861  1865  4417 V BaseAuthAsyncOperation: access token request failed
,08-05 11:42:52.862  3078  4416 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-05 11:42:52.919  1508  1519 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-05 11:42:52.919  1508  1519 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-05 11:42:52.919  1508  1519 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 11:42:52.920  1508  1519 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-05 11:42:52.938  3078  4416 E KeepSync: IOException
08-05 11:42:52.938  3078  4416 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-05 11:42:52.938  3078  4416 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-05 11:42:52.938  3078  4416 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-05 11:42:52.938  3078  4416 E KeepSync: 	... 10 more
08-05 11:42:52.938  3078  4416 W KeepSync: Sync result 2
,08-05 11:42:52.951   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1285686, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-05 11:42:56.445   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1289517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:43:03.992   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1297063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:43:21.526   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1314597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:43:29.058   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1322130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:43:46.578   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1339650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:43:54.125   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1347197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:44:11.646   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1364717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:44:19.192   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1372264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:44:36.712   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1389784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:44:44.258   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1397330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:45:01.792   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1414863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:45:09.325   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1422397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:45:26.846   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1439917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:45:34.392   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1447464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:45:51.899   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1464970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:45:59.458   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1472530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:46:16.966   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1490037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:46:32.259   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1505330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-05 11:46:42.018   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1515090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-05 11:46:57.325   871  4274 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1530397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),08-05 11:47:03.736  4432  4432 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 11:47:03.740  4432  4432 D AndroidRuntime: CheckJNI is OFF
08-05 11:47:03.783  4432  4432 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-05 11:47:03.829  4432  4432 I Radio-JNI: register_android_hardware_Radio DONE
08-05 11:47:03.852  4432  4432 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-05 11:47:03.859   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-05 11:47:03.860   871   884 I ActivityManager: Killing 3843:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-05 11:47:03.981   871   894 W PackageSettings: Skipping PackageSetting{759765a com.example.hello/10273} due to missing metadata
08-05 11:47:04.011   871   894 I art     : Starting a blocking GC Explicit
08-05 11:47:04.045   871   881 D GraphicsStats: Buffer count: 2
08-05 11:47:04.046   871  1752 I WindowState: WIN DEATH: Window{92f8576 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 11:47:04.046   871  1305 D WifiService: Client connection lost with reason: 4
08-05 11:47:04.062   871   894 I art     : Explicit concurrent mark sweep GC freed 28895(2MB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 29MB/43MB, paused 909us total 49.123ms
08-05 11:47:04.077   871   884 E libprocessgroup: failed to kill 1 processes for processgroup 3843
08-05 11:47:04.082   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-05 11:47:04.083   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-05 11:47:04.087   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-05 11:47:04.087   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-05 11:47:04.087   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:47:04.087   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:47:04.087   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 11:47:04.087   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-05 11:47:04.090   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-05 11:47:04.090   871   884 I ActivityManager:   Force finishing activity ActivityRecord{fcd8378 u0 com.test.thalitest/.MainActivity t2}
08-05 11:47:04.092  4432  4432 I art     : System.exit called, status: 0
08-05 11:47:04.092  4432  4432 I AndroidRuntime: VM exiting with result code 0.
08-05 11:47:04.113   871   882 W ActivityManager: Spurious death for ProcessRecord{b61e518 0:com.test.thalitest/u0a0}, curProc for 3843: null
08-05 11:47:04.161   871   894 I ActivityManager: Start proc 4443:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-05 11:47:04.170   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-05 11:47:04.196   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-05 11:47:04.199  4221  4221 D BluetoothMapAppObserver: onReceive
08-05 11:47:04.199  4221  4221 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-05 11:47:04.202  3675  3675 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-05 11:47:04.204   871  1293 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 11:47:04.207  1847  2022 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-05 11:47:04.211  1655  1655 I Keyboard.Facilitator: resetDictionaries() : en_US
08-05 11:47:04.214  1655  4457 I Keyboard.Facilitator.DecoderInitializer: run()
08-05 11:47:04.222  1655  4457 I Decoder : createOrResetDecoder
08-05 11:47:04.239   871  1521 I ActivityManager: Start proc 4459:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-05 11:47:04.255   871  1302 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-05 11:47:04.256  1508  1508 I ConfigService: onCreate
08-05 11:47:04.257  1740  1740 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-05 11:47:04.269  1508  4470 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-05 11:47:04.269  1508  4470 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-05 11:47:04.273  1508  4470 W SQLiteOpenHelper: Opened config.db in read-only mode
08-05 11:47:04.280   871   881 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3843 uid 10000
08-05 11:47:04.290  1655  1655 I Keyboard.Facilitator: onFinishInput()
08-05 11:47:04.302   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 11:47:04.312  1655  4457 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-05 11:47:04.317  1754  1826 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-05 11:47:04.317   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-05 11:47:04.317   871   883 E PackageManager: Failed to write settings, restoring backup
08-05 11:47:04.317   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-05 11:47:04.317   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-05 11:47:04.317   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-05 11:47:04.317   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-05 11:47:04.317   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-05 11:47:04.317   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:47:04.317   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:47:04.317   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 11:47:04.321   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-05 11:47:04.321   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-05 11:47:04.321   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 11:47:04.321   871   884 E DropBoxManagerService: 	... 13 more
08-05 11:47:04.321  4459  4459 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-05 11:47:04.330   871  1728 I ActivityManager: Start proc 4472:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-05 11:47:04.330  1754  1826 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-05 11:47:04.330  1754  1826 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1754
08-05 11:47:04.330  1754  1826 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:47:04.330  1754  1826 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 11:47:04.332   871  1367 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-05 11:47:04.333   871  4478 E DropBoxManagerService: Can't write: system_app_crash
08-05 11:47:04.333   871  4478 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 11:47:04.333   871  4478 E DropBoxManagerService: 	... 5 more
08-05 11:47:04.336  1754  1826 I Process : Sending signal. PID: 1754 SIG: 9
08-05 11:47:04.383  1655  4457 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-05 11:47:04.391  1655  4457 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-05 11:47:04.391  1655  4457 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-05 11:47:04.395  1655  4457 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-05 11:47:04.395  1655  4457 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-05 11:47:04.395  1655  4457 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-05 11:47:04.395  1655  4457 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-05 11:47:04.396  1655  4457 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-05 11:47:04.396  1655  4457 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-05 11:47:04.396  1655  4457 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-05 11:47:04.396  1655  4457 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-05 11:47:04.396  1655  4457 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-05 11:47:04.396  1655  4457 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-05 11:47:04.402   871  1887 D GraphicsStats: Buffer count: 1
08-05 11:47:04.402   871  1889 I WindowState: WIN DEATH: Window{4399d7a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-05 11:47:04.413   871  1752 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1754) has died
08-05 11:47:04.414   871  1752 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-05 11:47:04.416   871  1752 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-05 11:47:04.431   871   884 I ActivityManager: Start proc 4492:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-05 11:47:04.453  4459  4459 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:47:04.478  4492  4492 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:47:04.478  4492  4492 D AndroidRuntime: Shutting down VM
08-05 11:47:04.479  1865  4502 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-05 11:47:04.479   871  1889 I ActivityManager: Start proc 4505:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-05 11:47:04.480  1865  4502 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-05 11:47:04.483  4459  4510 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-05 11:47:04.487  4492  4492 E AndroidRuntime: FATAL EXCEPTION: main
08-05 11:47:04.487  4492  4492 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4492
08-05 11:47:04.487  4492  4492 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-05 11:47:04.487  4492  4492 E AndroidRuntime: 	... 10 more
08-05 11:47:04.488   871  1521 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-05 11:47:04.489  4492  4492 I Process : Sending signal. PID: 4492 SIG: 9
08-05 11:47:04.495   871  4517 E DropBoxManagerService: Can't write: system_app_crash
08-05 11:47:04.495   871  4517 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 11:47:04.495   871  4517 E DropBoxManagerService: 	... 5 more
08-05 11:47:04.505  1865  4502 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-05 11:47:04.505  1865  4502 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-05 11:47:04.509   871  1521 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4492) has died
08-05 11:47:04.510   871  1521 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-05 11:47:04.511  4505  4505 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-05 11:47:04.523   871   884 I ActivityManager: Start proc 4520:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-05 11:47:04.544  1508  1508 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-05 11:47:04.546  1508  1508 D AndroidRuntime: Shutting down VM
08-05 11:47:04.546  1508  1508 E AndroidRuntime: FATAL EXCEPTION: main
08-05 11:47:04.546  1508  1508 E AndroidRuntime: Process: com.google.process.gapps, PID: 1508
08-05 11:47:04.546  1508  1508 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-05 11:47:04.546  1508  1508 E AndroidRuntime: 	... 8 more
08-05 11:47:04.549   871  4534 E DropBoxManagerService: Can't write: system_app_crash
08-05 11:47:04.549   871  4534 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 11:47:04.549   871  4534 E DropBoxManagerService: 	... 5 more
08-05 11:47:04.550  1508  1508 I Process : Sending signal. PID: 1508 SIG: 9
08-05 11:47:04.566   871   881 I ActivityManager: Killing 1802:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 11:47:04.568  4520  4520 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 11:47:04.568  4520  4520 D AndroidRuntime: Shutting down VM
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:47:04.586  4459  4490 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-05 11:47:04.587  4459  4490 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 11:47:04.595   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
