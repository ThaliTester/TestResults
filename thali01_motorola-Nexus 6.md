#### Test 832688936f8f85f_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
09-02 11:35:34.434   872   883 I ActivityManager: Start proc 3789:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,--------- beginning of main
09-02 11:35:34.510  3789  3789 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
09-02 11:35:34.576  3789  3803 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
09-02 11:35:34.637  3789  3803 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
09-02 11:35:34.668  3789  3803 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-02 11:35:34.761  3789  3789 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
09-02 11:35:34.777  3815  3815 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads1592639123.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads1592639123.dex
09-02 11:35:34.819  3815  3815 I dex2oat : dex2oat took 43.131ms (threads: 4) arena alloc=224KB java alloc=29KB native alloc=1643KB free=1684KB
09-02 11:35:34.886  3789  3789 W InstanceID/Rpc: Found 10011
09-02 11:35:35.070  3801  3801 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-02 11:35:35.075  3801  3801 D AndroidRuntime: CheckJNI is OFF
09-02 11:35:35.118  3801  3801 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-02 11:35:35.166  3801  3801 I Radio-JNI: register_android_hardware_Radio DONE
09-02 11:35:35.189  3801  3801 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-02 11:35:35.194   872  1399 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-02 11:35:35.254  2052  2062 W SearchService: Abort, client detached.
09-02 11:35:35.264  2052  2346 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@52a204d
09-02 11:35:35.264  2052  2372 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-02 11:35:35.264  2052  2052 I HotwordDetector: Closing mic
09-02 11:35:35.268  3801  3801 D AndroidRuntime: Shutting down VM
09-02 11:35:35.284   872  1992 I ActivityManager: Start proc 3881:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-02 11:35:35.327   375  2374 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-02 11:35:35.328   375  2374 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-02 11:35:35.335   375  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-02 11:35:35.336  2052  2356 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-02 11:35:35.338  2052  2371 I MicroRecognitionRnrImpl: Detection finished
09-02 11:35:35.354  3881  3881 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-02 11:35:35.387  3881  3881 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-02 11:35:35.394  3881  3881 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9409-9412)
09-02 11:35:35.394  3881  3881 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 11:35:35.408  3881  3881 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8ec084}
09-02 11:35:35.409  3881  3881 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-02 11:35:35.409  3881  3881 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-02 11:35:35.414  3881  3881 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-02 11:35:35.416  3881  3881 E SysUtils: ApplicationContext is null in ApplicationStatus
09-02 11:35:35.427  3881  3881 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-02 11:35:35.438  3881  3881 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 11:35:35.438  3881  3881 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 11:35:35.438  3881  3881 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 11:35:35.438  3881  3881 I Adreno  : Build Date                       : 10/20/15
09-02 11:35:35.438  3881  3881 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 11:35:35.438  3881  3881 I Adreno  : Local Branch                     : M14
09-02 11:35:35.438  3881  3881 I Adreno  : Remote Branch                    : 
09-02 11:35:35.438  3881  3881 I Adreno  : Remote Branch                    : 
09-02 11:35:35.438  3881  3881 I Adreno  : Reconstruct Branch               : 
,09-02 11:35:35.497   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bfd029e:true
,09-02 11:35:35.512   872  1999 I ActivityManager: Killing 3104:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,09-02 11:35:35.523  3881  3881 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-02 11:35:35.534  3881  3881 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-02 11:35:35.614  3881  3922 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-02 11:35:35.623  3881  3906 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-02 11:35:35.647  3881  3922 I OpenGLRenderer: Initialized EGL, version 1.4
,09-02 11:35:35.677  1557  1557 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 11:35:35.682  1557  3925 I VacuumService: Vacuum at: now=1472808935682 tag=VacuumService
,09-02 11:35:35.705   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +436ms
,09-02 11:35:35.714  1879  1879 I Keyboard.Facilitator: onFinishInput()
,09-02 11:35:35.801  3881  3881 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3881
,09-02 11:35:35.872  1557  3931 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-02 11:35:35.874  1557  3931 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-02 11:35:35.889  3881  3881 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-02 11:35:35.894  1557  3931 W Uploader:  no longer exists, so no auth token.
,09-02 11:35:36.013  3881  3926 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1700333264
,09-02 11:35:36.019  3881  3926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-02 11:35:36.019  3881  3926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-02 11:35:36.019  3881  3926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-02 11:35:36.019  3881  3926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-02 11:35:36.019  3881  3926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-02 11:35:36.019  3881  3926 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@814e76b added. We now have 1 listener(s)
,09-02 11:35:36.023  3881  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-02 11:35:36.023  3881  3926 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:35:36.024  3881  3926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:35:36.024  3881  3926 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-02 11:35:36.027  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-02 11:35:36.028  3881  3926 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6fd5a86 added. We now have 1 listener(s)
09-02 11:35:36.028  3881  3926 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 11:35:36.031   872  1311 D WifiService: New client listening to asynchronous messages
,09-02 11:35:36.032  3881  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 11:35:36.032  3881  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-02 11:35:36.032  3881  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-02 11:35:36.032  3881  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-02 11:35:36.032  3881  3926 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-02 11:35:36.034  3881  3926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:35:36.037  3881  3926 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-02 11:35:36.041  3881  3926 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-02 11:35:36.042  3881  3926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:35:36.042  3881  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:36.042  3881  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:36.042  3881  3926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:36.042  3881  3926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:35:36.042  3881  3926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:36.042  3881  3926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:35:36.042  3881  3926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:35:36.042  3881  3926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-02 11:35:36.042  3881  3926 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:35:36.043  3881  3926 I io.jxcore.node.LifeCycleMonitor: start: OK
09-02 11:35:36.043  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:36.045  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:36.073  3881  3881 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-02 11:35:36.103   872  1999 I ActivityManager: Killing 2992:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-02 11:35:36.167   872  1999 I ActivityManager: Killing 3215:com.google.android.gm/u0a78 (adj 15): empty #18
,09-02 11:35:36.795  3881  3939 W jxcore-log: Initializing JXcore engine
,09-02 11:35:36.795  3881  3939 W jxcore-log: JXcore engine is ready,
,09-02 11:35:36.833  3939  3939 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-02 11:35:36.833  3939  3939 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12762]" dev="sockfs" ino=12762 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-02 11:35:36.833  3939  3939 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-02 11:35:36.833  3939  3939 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26989]" dev="sockfs" ino=26989 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-02 11:35:36.846  3881  3939 W jxcore-log: Starting JXcore engine
,09-02 11:35:36.926  3881  3939 W jxcore-log: Platform android
09-02 11:35:36.926  3881  3939 W jxcore-log: 
,09-02 11:35:36.927  3881  3939 W jxcore-log: Process ARCH arm
09-02 11:35:36.927  3881  3939 W jxcore-log: 
,09-02 11:35:36.964  1557  1557 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 11:35:36.966  1557  1557 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 11:35:36.993  1557  3931 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-02 11:35:36.994  1557  3931 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-02 11:35:36.994  1557  3931 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 11:35:36.994  1557  3931 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 11:35:37.024  1557  3931 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-02 11:35:37.024  1557  3931 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-02 11:35:37.024  1557  3931 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-02 11:35:37.124  3881  3939 I jxcore-log: JXcore Cordova bridge is ready!
09-02 11:35:37.124  3881  3939 I jxcore-log: 
,09-02 11:35:37.124  3881  3939 W jxcore-log: JXcore engine is started
,09-02 11:35:37.135  3881  3926 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-02 11:35:37.142  3881  3881 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-02 11:35:37.176  1557  3931 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-02 11:35:37.176  1557  3931 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-02 11:35:37.176  1557  3931 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 11:35:37.176  1557  3931 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 11:35:37.192  1557  3931 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-02 11:35:37.192  1557  3931 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-02 11:35:37.192  1557  3931 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-02 11:35:37.467  1557  3931 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-02 11:35:37.467  1557  3931 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-02 11:35:37.467  1557  3931 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 11:35:37.469  1557  3931 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 11:35:37.499  1557  3931 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-02 11:35:37.499  1557  3931 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-02 11:35:37.499  1557  3931 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-02 11:35:37.981  1557  3931 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-02 11:35:37.981  1557  3931 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-02 11:35:37.982  1557  3931 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 11:35:37.982  1557  3931 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 11:35:38.020  1557  3931 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-02 11:35:38.020  1557  3931 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-02 11:35:38.020  1557  3931 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-02 11:35:39.384   872  1310 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-02 11:35:46.929  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-02 11:35:46.929  3881  3939 I jxcore-log: 
,09-02 11:35:46.932  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-02 11:35:46.932  3881  3939 I jxcore-log: 
,09-02 11:35:46.946  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:35:46.946  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:46.946  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:46.946  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:46.946  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:35:46.946  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:46.946  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:35:46.946  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:35:46.952  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 11:35:46.955  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-02 11:35:46.955  3881  3939 I jxcore-log: 
,09-02 11:35:46.957  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-02 11:35:46.957  3881  3939 I jxcore-log: 
,09-02 11:35:47.444  3881  3939 D executeNativeTests: Running unit tests
,09-02 11:35:47.502  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:35:47.503  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 added. We now have 2 listener(s)
,09-02 11:35:47.504  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:35:47.504  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:35:47.504  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:35:47.504  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 11:35:47.504  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 added. We now have 2 listener(s)
,09-02 11:35:47.504  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:35:47.505  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 11:35:47.509  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:35:47.515  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:35:47.515  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:47.515  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:47.515  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:47.515  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:35:47.515  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:47.515  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:35:47.515  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:35:47.518  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 11:35:47.519  3881  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:35:47.521  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-02 11:35:47.523  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:47.525  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:47.525  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 11:35:47.525  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-02 11:35:47.527  3881  3939 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-02 11:35:47.527  3881  3939 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-02 11:35:47.527  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-02 11:35:47.527  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 11:35:47.527  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-02 11:35:47.528  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.528  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 11:35:47.528  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.529  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.529  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.529  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 11:35:47.529  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:35:47.529  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 removed from the list
,09-02 11:35:47.529  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.529  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 removed from the list
09-02 11:35:47.529  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.529  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:35:47.530  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.530  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.532  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.532  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.532  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.532  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.533  3881  3939 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-02 11:35:47.534  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.534  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.534  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.534  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.534  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 11:35:47.534  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.534  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.534  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.534  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.534  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.534  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.534  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.534  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.534  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.535  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.535  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.535  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.535  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
,09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 11:35:47.540  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 11:35:47.541  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-02 11:35:47.541  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.541  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.541  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.542  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.542  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.542  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.542  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.542  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.542  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.542  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.542  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.542  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.542  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.542  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.543  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.543  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.543  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.543  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.544  3881  3939 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 11:35:47.545  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:35:47.550  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:35:47.550  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:47.550  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:47.550  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:47.550  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:35:47.550  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:47.550  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:35:47.550  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:35:47.551  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:47.551  3881  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:35:47.551  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:35:47.551  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:35:47.552  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:35:47.552  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:35:47.552  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 11:35:47.556  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.558  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.561  3881  3939 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 11:35:47.561  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 11:35:47.568  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 11:35:47.571  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 11:35:47.571  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 11:35:47.574  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-02 11:35:47.578  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-02 11:35:47.578  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 11:35:47.578  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 11:35:47.579  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 11:35:47.580  3881  3939 D BluetoothAdapter: STATE_ON
09-02 11:35:47.586  2716  2730 D BtGatt.GattService: registerClient() - UUID=6f81a445-2a7b-4616-a4c5-bd94197bff47
,09-02 11:35:47.587  2716  2768 D BtGatt.GattService: onClientRegistered() - UUID=6f81a445-2a7b-4616-a4c5-bd94197bff47, clientIf=5
09-02 11:35:47.588  3881  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 11:35:47.589  2716  2729 D BtGatt.GattService: start scan with filters
09-02 11:35:47.592  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 11:35:47.592  2716  2772 D BtGatt.ScanManager: handling starting scan
09-02 11:35:47.592  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 11:35:47.592  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 11:35:47.592  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 11:35:47.594  2716  2772 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
09-02 11:35:47.595  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 11:35:47.597  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 11:35:47.597  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 11:35:47.599  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 11:35:47.601  2716  2768 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 11:35:47.601  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.602  3881  3939 I io.jxcore.node.ConnectionHelper: start: OK
09-02 11:35:47.602  2716  2772 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 11:35:47.605  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.606  3881  3939 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 11:35:47.606  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.606  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 11:35:47.606  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.606  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 11:35:47.607  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 11:35:47.607  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 11:35:47.607  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 11:35:47.607  2716  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 11:35:47.607  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.607  2716  2772 D BtGatt.ScanManager: Starting BLE batch scan
09-02 11:35:47.608  2716  2772 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 11:35:47.608  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 11:35:47.608  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 11:35:47.609  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 11:35:47.609  3881  3939 D BluetoothAdapter: STATE_ON
09-02 11:35:47.610  2716  2730 D BtGatt.GattService: stopScan() - queue size =1
09-02 11:35:47.610  2716  2729 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 11:35:47.611  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:35:47.611  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 11:35:47.611  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 11:35:47.611  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 11:35:47.611  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 11:35:47.612  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:35:47.613  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 11:35:47.613  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 11:35:47.614  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 11:35:47.614  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:35:47.615  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:35:47.615  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:35:47.615  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:35:47.616  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.616  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.616  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:35:47.616  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.616  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.616  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.616  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.616  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.617  2716  2768 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 11:35:47.617  3881  3939 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 11:35:47.617  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.618  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:35:47.622  2716  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 11:35:47.622  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.622  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:35:47.622  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:47.622  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:47.622  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:47.622  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:35:47.622  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:47.622  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:35:47.622  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:35:47.625  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:47.625  3881  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 11:35:47.625  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:35:47.625  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:35:47.625  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:35:47.625  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:35:47.625  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 11:35:47.628  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.629  3881  3939 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 11:35:47.629  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 11:35:47.630  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.631  2716  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 11:35:47.631  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.631  2716  2772 D BtGatt.ScanManager: stopping BLe Batch
09-02 11:35:47.632  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 11:35:47.633  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 11:35:47.633  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 11:35:47.636  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 11:35:47.636  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 11:35:47.636  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 11:35:47.637  3881  3939 D BluetoothAdapter: STATE_ON
09-02 11:35:47.637  2716  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 11:35:47.637  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.638  2716  2772 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 11:35:47.640  2716  2729 D BtGatt.GattService: registerClient() - UUID=88d1b922-fa55-4535-9eb5-af4b4948e0a9
09-02 11:35:47.641  2716  2768 D BtGatt.GattService: onClientRegistered() - UUID=88d1b922-fa55-4535-9eb5-af4b4948e0a9, clientIf=5
09-02 11:35:47.641  3881  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 11:35:47.641  2716  2730 D BtGatt.GattService: start scan with filters
09-02 11:35:47.643  2716  2768 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 11:35:47.643  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.644  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 11:35:47.644  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 11:35:47.644  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 11:35:47.644  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 11:35:47.644  2716  2772 D BtGatt.ScanManager: handling starting scan
09-02 11:35:47.646  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 11:35:47.646  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 11:35:47.646  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 11:35:47.647  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 11:35:47.649  3881  3939 I io.jxcore.node.ConnectionHelper: start: OK
09-02 11:35:47.650  2716  2768 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 11:35:47.650  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.650  2716  2772 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 11:35:47.651  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.651  3881  3939 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 11:35:47.651  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.651  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 11:35:47.651  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.651  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 11:35:47.651  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 11:35:47.651  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 11:35:47.651  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 11:35:47.651  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 11:35:47.651  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 11:35:47.651  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 11:35:47.652  3881  3939 D BluetoothAdapter: STATE_ON
09-02 11:35:47.652  2716  2729 D BtGatt.GattService: stopScan() - queue size =1
09-02 11:35:47.653  2716  2730 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 11:35:47.653  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:35:47.653  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 11:35:47.653  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 11:35:47.653  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 11:35:47.653  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 11:35:47.654  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:35:47.654  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 11:35:47.654  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 11:35:47.654  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 11:35:47.654  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:35:47.655  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:35:47.655  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:35:47.655  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:35:47.655  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.655  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.655  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:35:47.655  2716  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 11:35:47.655  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.655  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.655  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.656  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.656  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.656  2716  2772 D BtGatt.ScanManager: Starting BLE batch scan
09-02 11:35:47.656  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.656  2716  2772 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 11:35:47.656  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.656  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.656  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.657  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.657  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.657  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.657  3881  3939 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-02 11:35:47.659  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:35:47.661  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:35:47.661  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:47.661  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:47.661  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:47.661  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:35:47.661  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:47.661  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:35:47.661  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:35:47.663  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:47.663  3881  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:35:47.664  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:35:47.664  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.666  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.666  2716  2768 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 11:35:47.666  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.666  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:35:47.666  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:35:47.666  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:35:47.666  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-02 11:35:47.668  3881  3939 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 11:35:47.668  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-02 11:35:47.671  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-02 11:35:47.671  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 11:35:47.671  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 11:35:47.671  2716  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 11:35:47.672  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.673  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 11:35:47.673  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 11:35:47.673  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 11:35:47.674  3881  3939 D BluetoothAdapter: STATE_ON
09-02 11:35:47.675  2716  2901 D BtGatt.GattService: registerClient() - UUID=e2c18035-755e-493c-a2b3-f4fdcabfc764
09-02 11:35:47.675  2716  2768 D BtGatt.GattService: onClientRegistered() - UUID=e2c18035-755e-493c-a2b3-f4fdcabfc764, clientIf=5
09-02 11:35:47.676  3881  3891 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 11:35:47.676  2716  2730 D BtGatt.GattService: start scan with filters
09-02 11:35:47.678  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 11:35:47.678  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 11:35:47.678  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 11:35:47.678  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 11:35:47.678  2716  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 11:35:47.678  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.678  2716  2772 D BtGatt.ScanManager: stopping BLe Batch
09-02 11:35:47.680  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 11:35:47.681  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 11:35:47.681  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 11:35:47.682  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-02 11:35:47.683  3881  3939 I io.jxcore.node.ConnectionHelper: start: OK
09-02 11:35:47.684  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.684  3881  3939 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 11:35:47.684  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.684  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 11:35:47.684  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.684  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 11:35:47.684  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 11:35:47.684  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 11:35:47.684  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 11:35:47.684  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 11:35:47.684  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 11:35:47.684  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 11:35:47.685  3881  3939 D BluetoothAdapter: STATE_ON
09-02 11:35:47.685  2716  2730 D BtGatt.GattService: stopScan() - queue size =0
09-02 11:35:47.685  2716  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 11:35:47.685  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.685  2716  2772 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 11:35:47.686  2716  2909 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 11:35:47.686  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:35:47.686  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 11:35:47.686  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 11:35:47.686  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 11:35:47.686  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 11:35:47.687  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:35:47.687  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 11:35:47.687  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 11:35:47.687  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 11:35:47.688  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:35:47.688  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:35:47.688  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:35:47.688  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:35:47.689  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.689  3881  3939 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 11:35:47.689  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.689  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.689  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.689  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.689  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:35:47.689  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.689  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.689  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.689  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.689  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.690  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.690  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.690  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.690  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.690  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.691  2716  2768 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 11:35:47.691  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.690  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.691  3881  3939 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-02 11:35:47.691  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.692  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.692  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.692  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.692  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.692  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.692  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.692  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.692  2716  2772 D BtGatt.ScanManager: handling starting scan
09-02 11:35:47.692  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.693  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.693  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.693  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.693  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.693  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.693  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.693  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.693  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.693  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.694  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 11:35:47.694  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.694  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.694  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.695  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.695  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.695  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.695  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.695  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.695  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.695  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.695  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.695  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.695  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.695  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.696  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.696  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.696  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.696  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.696  3881  3939 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-02 11:35:47.696  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.696  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.696  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.697  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.697  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.697  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.697  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.697  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.697  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.697  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.697  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.697  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.697  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.697  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.698  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.698  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 11:35:47.698  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.698  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.698  2716  2768 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 11:35:47.698  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.698  2716  2772 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 11:35:47.698  3881  3939 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-02 11:35:47.699  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.699  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.699  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.699  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.699  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.699  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.699  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.699  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.699  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.699  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.699  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.699  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.699  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.699  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.700  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.700  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.700  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.700  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.700  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 11:35:47.700  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 11:35:47.701  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 11:35:47.701  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 11:35:47.701  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-02 11:35:47.701  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-02 11:35:47.701  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.701  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.701  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.701  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.701  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.701  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.701  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.701  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.701  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.701  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.701  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.702  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.702  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.702  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.702  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.702  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.702  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.702  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.703  3881  3939 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 11:35:47.703  3881  3939 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 11:35:47.703  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-02 11:35:47.704  2716  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 11:35:47.704  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.704  2716  2772 D BtGatt.ScanManager: Starting BLE batch scan
09-02 11:35:47.704  2716  2772 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-02 11:35:47.706  3881  3939 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 11:35:47.706  3881  3939 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-02 11:35:47.706  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-02 11:35:47.706  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-02 11:35:47.706  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-02 11:35:47.706  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-02 11:35:47.706  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-02 11:35:47.706  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-02 11:35:47.706  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-02 11:35:47.706  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-02 11:35:47.706  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-02 11:35:47.706  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-02 11:35:47.707  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-02 11:35:47.707  3881  3939 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-02 11:35:47.708  3881  3939 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 11:35:47.708  3881  3939 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-02 11:35:47.708  3881  3939 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 11:35:47.708  3881  3939 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 11:35:47.708  3881  3939 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-02 11:35:47.708  3881  3939 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 11:35:47.708  3881  3939 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-02 11:35:47.708  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-02 11:35:47.711  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-02 11:35:47.712  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-02 11:35:47.712  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-02 11:35:47.713  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-02 11:35:47.713  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-02 11:35:47.713  3881  3939 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-02 11:35:47.713  3881  3939 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-02 11:35:47.713  3881  3939 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-02 11:35:47.714  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.714  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.714  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.714  2716  2768 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 11:35:47.714  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.714  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.715  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.715  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.715  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-02 11:35:47.716  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.716  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.716  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.716  3881  3957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
09-02 11:35:47.716  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.716  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.716  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.716  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.716  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.716  3881  3958 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
09-02 11:35:47.718  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.718  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.718  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.718  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.720  3881  3939 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-02 11:35:47.720  3881  3957 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:35:47.720  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.720  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.720  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.720  2716  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 11:35:47.720  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.721  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.721  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.721  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.721  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.721  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.721  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.721  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.721  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.721  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.721  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.721  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.723  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.723  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.723  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.723  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.723  3881  3939 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-02 11:35:47.723  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.723  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.723  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.724  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.724  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.724  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.724  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.724  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.724  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.724  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.724  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.724  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.724  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.724  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.725  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.725  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.725  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.725  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.726  3881  3939 D io.jxcore.node.ConnectionHe,lper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-02 11:35:47.726  3881  3939 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-02 11:35:47.726  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 11:35:47.726  3881  3939 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-02 11:35:47.726  3881  3939 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 11:35:47.726  3881  3939 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-02 11:35:47.726  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 11:35:47.726  3881  3939 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-02 11:35:47.726  3881  3939 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-02 11:35:47.726  3881  3939 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-02 11:35:47.726  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 11:35:47.726  3881  3939 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-02 11:35:47.726  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.726  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.726  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.727  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.727  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.727  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.727  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.727  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.727  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.727  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.727  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.727  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.727  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.727  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.728  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.728  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.728  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.728  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.728  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.728  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.728  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.728  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.728  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.729  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.729  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.729  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.729  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.729  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.729  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.729  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.729  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.729  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.729  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.729  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.729  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.729  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.729  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.729  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.729  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.729  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.730  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.730  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.730  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.730  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.730  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.730  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.730  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.730  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.730  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.731  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.731  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.732  3881  3939 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-02 11:35:47.732  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:35:47.732  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-02 11:35:47.732  2716  2768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-02 11:35:47.733  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.733  2716  2772 D BtGatt.ScanManager: stopping BLe Batch
09-02 11:35:47.733  3881  3939 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-02 11:35:47.733  3881  3939 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-02 11:35:47.734  3881  3881 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-02 11:35:47.734  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-02 11:35:47.734  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 11:35:47.736  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.736  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-02 11:35:47.736  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-02 11:35:47.737  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-02 11:35:47.737  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.738  3881  3939 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-02 11:35:47.738  3881  3881 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-02 11:35:47.739  2716  2768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 11:35:47.738  3881  3959 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:35:47.739  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.739  2716  2772 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 11:35:47.739  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.740  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.740  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 11:35:47.740  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 11:35:47.740  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 11:35:47.740  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.740  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.741  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:35:47.741  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.741  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:35:47.741  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:35:47.741  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.741  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:35:47.741  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.741  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.741  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.741  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.741  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.742  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.742  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.742  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.742  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.742  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.742  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.742  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.742  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.742  3881  3959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-02 11:35:47.742  3881  3959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-02 11:35:47.743  3881  3959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-02 11:35:47.743  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.743  2716  2768 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 11:35:47.743  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.743  2716  2768 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:35:47.743  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.743  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.744  3881  3881 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-02 11:35:47.744  3881  3939 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-02 11:35:47.744  3881  3939 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-02 11:35:47.744  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-02 11:35:47.744  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-02 11:35:47.744  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.745  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.745  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.745  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.745  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.745  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.745  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.745  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.745  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.745  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.745  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.745  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.745  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.745  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.746  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.747  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.747  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.747  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.752  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.752  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.752  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.752  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.752  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.752  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.752  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.752  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.752  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.752  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.753  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.753  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.753  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.753  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.754  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.754  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.754  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.754  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.755  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:35:47.755  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:35:47.755  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:35:47.755  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:35:47.755  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.755  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.755  3881  3939 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da7e798 not in the list
09-02 11:35:47.755  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.755  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.755  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:35:47.755  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.755  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.755  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:35:47.755  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:35:47.756  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:35:47.756  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:35:47.756  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:35:47.757  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9e1bf1 not in the list
09-02 11:35:47.757  3881  3939 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-02 11:35:47.757  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 11:35:47.757  3881  3939 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-02 11:35:47.758  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-02 11:35:47.758  3881  3939 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-02 11:35:47.758  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-02 11:35:47.759  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-02 11:35:47.759  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-02 11:35:47.760  3881  3939 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-02 11:35:47.760  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 11:35:47.760  3881  3939 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-02 11:35:47.760  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-02 11:35:47.760  3881  3939 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-02 11:35:47.760  3881  3939 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-02 11:35:47.761  3881  3939 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-02 11:35:47.761  3881  3939 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-02 11:35:47.761  3881  3939 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-02 11:35:47.761  3881  3939 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-02 11:35:47.762  3881  3939 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-02 11:35:47.762  3881  3939 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-02 11:35:47.762  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:35:47.762  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@171cb6b added. We now have 2 listener(s)
09-02 11:35:47.763  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:35:47.764  3881  3939 D BluetoothAdapter: enable(): BT is already enabled..!
09-02 11:35:47.765   872  1687 D WifiService: setWifiEnabled: true pid=3881, uid=10000
09-02 11:35:47.765   872  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 11:35:47.766  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:35:47.766  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@93066c8 added. We now have 3 listener(s)
09-02 11:35:47.766  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:35:47.772  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:35:47.772  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f9ce361 ,added. We now have 4 listener(s)
09-02 11:35:47.773  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:35:47.774  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:35:47.774  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11a8e86 added. We now have 5 listener(s)
09-02 11:35:47.774  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:35:47.776   872   883 D WifiService: setWifiEnabled: false pid=3881, uid=10000
09-02 11:35:47.776   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-02 11:35:47.780  2716  2764 D BluetoothAdapterState: Current state: ON, message: 23
09-02 11:35:47.780  2716  2764 D BluetoothAdapterProperties: Setting state to 13
09-02 11:35:47.780  2716  2764 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-02 11:35:47.780  2716  2764 D BluetoothAdapterProperties: onBluetoothDisable()
,09-02 11:35:47.781  2716  2764 I BluetoothAdapterState: Entering PendingCommandState
09-02 11:35:47.782  2716  2716 D BluetoothMapService: onReceive
09-02 11:35:47.782  2716  2716 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:35:47.782  2716  2716 D BluetoothMapService: STATE_TURNING_OFF
,09-02 11:35:47.782  2716  2716 D BluetoothMapService: MAP Service closeService in
,09-02 11:35:47.782  2716  2716 D BluetoothMapMasInstance0: MAP Service shutdown
09-02 11:35:47.782  2716  2716 D ObexServerSockets0: shutdown(block = true)
09-02 11:35:47.783  2716  2716 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-02 11:35:47.783  2716  2910 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-02 11:35:47.783  2716  2716 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 11:35:47.783  2716  2898 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-02 11:35:47.783  2716  2911 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-02 11:35:47.784  2716  2716 I BtOppRfcommListener: stopping Accept Thread
,09-02 11:35:47.784  2716  3427 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:35:47.784  2716  3427 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 11:35:47.785  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:47.785  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:47.785  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:47.785  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:47.785  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:47.785  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:47.785  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:47.785  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:35:47.785  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:35:47.785  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 11:35:47.786  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 11:35:47.796   872   885 I ActivityManager: Start proc 3962:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-02 11:35:47.796  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-02 11:35:47.797  2716  2768 D BluetoothAdapterProperties: Scan Mode:20
,09-02 11:35:47.797  2716  2764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-02 11:35:47.798   872  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-02 11:35:47.798   872  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-02 11:35:47.798   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 11:35:47.798   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 11:35:47.798  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:35:47.801  2716  2716 D HeadsetService: Received stop request...Stopping profile...
09-02 11:35:47.803  1354  1368 D BluetoothHeadset: Proxy object disconnected
09-02 11:35:47.803  2716  2716 D A2dpService: Received stop request...Stopping profile...
09-02 11:35:47.804  2716  2904 D A2dpStateMachine: Exit Disconnected: -1
09-02 11:35:47.804   872   872 D BluetoothHeadset: Proxy object disconnected
09-02 11:35:47.804   872   872 D BluetoothHeadset: Proxy object disconnected
,09-02 11:35:47.804   872   872 D BluetoothHeadset: Proxy object disconnected
09-02 11:35:47.804  1981  2202 D BluetoothHeadset: Proxy object disconnected
,09-02 11:35:47.806  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.807   872   872 D BluetoothA2dp: Proxy object disconnected
09-02 11:35:47.809  2716  2716 D HidService: Received stop request...Stopping profile...
,09-02 11:35:47.809  2716  2716 D HidService: Stopping Bluetooth HidService
09-02 11:35:47.809   371   868 D CommandListener: Clearing all IP addresses on wlan0
09-02 11:35:47.810   872  1905 D DhcpClient: Clearing IP address
,09-02 11:35:47.811  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:47.811  2716  2716 D HealthService: Received stop request...Stopping profile...
09-02 11:35:47.811  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:35:47.811  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:47.811  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:47.811  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:47.811  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:47.811  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:47.811  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:35:47.811  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:35:47.811  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:47.811  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:47.812  3881  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:35:47.812  2716  2716 V BluetoothAdapterState: isTurningOff()=true
,09-02 11:35:47.812  2716  2716 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:47.812  2716  2716 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:47.812  2716  2716 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:47.813  1557  2499 V NativeCrypto: Read error: ssl=0x9ab5e200: I/O error during system call, Connection timed out
09-02 11:35:47.813  2716  2716 D PanService: Received stop request...Stopping profile...
09-02 11:35:47.814   371   868 D CommandListener: Setting iface cfg
09-02 11:35:47.814  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:47.815  1354  1354 D HeadsetProfile: Bluetooth service disconnected
,09-02 11:35:47.817  1354  1354 D BluetoothA2dp: Proxy object disconnected
09-02 11:35:47.817  1354  1354 D BluetoothInputDevice: Proxy object disconnected
09-02 11:35:47.817  1354  1354 D HidProfile: Bluetooth service disconnected
09-02 11:35:47.817  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-02 11:35:47.817  1354  1354 D PanProfile: Bluetooth service disconnected
09-02 11:35:47.817  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:47.818  1557  2499 V NativeCrypto: SSL shutdown failed: ssl=0x9ab5e200: I/O error during system call, Broken pipe
,09-02 11:35:47.819  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:47.820  2716  2716 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-02 11:35:47.821   872  1310 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-02 11:35:47.821  2716  2768 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-02 11:35:47.821  2716  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 11:35:47.821  2716  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 11:35:47.821  2716  2716 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 11:35:47.821  2716  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 11:35:47.821  2716  2768 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-02 11:35:47.821   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-02 11:35:47.822   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-02 11:35:47.823   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 11:35:47.824   408   408 E Parcel  : Reading a NULL string not supported here.
,09-02 11:35:47.828   872  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-02 11:35:47.831   371   868 D CommandListener: Clearing all IP addresses on wlan0
09-02 11:35:47.834  2716  2716 D BluetoothMapService: Received stop request...Stopping profile...
,09-02 11:35:47.835  2716  2716 D BluetoothMapService: stop()
09-02 11:35:47.835  2716  2716 D BluetoothMapAppObserver: deinitObservers()
09-02 11:35:47.835  2716  2716 D BluetoothMapAppObserver: removeReceiver()
09-02 11:35:47.837  1354  1354 D BluetoothMap: Proxy object disconnected
09-02 11:35:47.837  1354  1354 D MapProfile: Bluetooth service disconnected
09-02 11:35:47.837  2716  2716 V BluetoothAdapterState: isTurningOff()=true
09-02 11:35:47.837  2716  2716 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:47.837  2716  2716 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:47.838  2716  2716 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 11:35:47.839  2716  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 11:35:47.839  2716  2768 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-02 11:35:47.839  2716  2716 V BluetoothAdapterState: isTurningOff()=true
09-02 11:35:47.839  2716  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 11:35:47.839  2716  2716 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:47.839  2716  2716 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:47.839  2716  2892 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:35:47.839  2716  2716 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 11:35:47.839  2716  2892 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:35:47.839  2716  2892 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:35:47.839  2716  2892 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:35:47.839  2716  2716 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 11:35:47.839  2716  2716 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-02 11:35:47.839  2716  2768 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-02 11:35:47.839  2716  2716 V BluetoothAdapterState: isTurningOff()=true
09-02 11:35:47.839  2716  2716 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:47.840  2716  2716 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 11:35:47.840  2716  2716 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:47.840  2716  2716 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 11:35:47.840  2716  2768 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-02 11:35:47.840  2716  2716 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 11:35:47.840  2716  2716 V BluetoothAdapterState: isTurningOff()=true
09-02 11:35:47.840  2716  2716 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:47.840  2716  2716 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:47.840  2716  2716 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:47.840  2716  2716 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 11:35:47.841  2716  2716 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 11:35:47.842  2716  2716 D BluetoothMapService: MAP Service closeService in
,09-02 11:35:47.842  2716  2716 V BluetoothAdapterState: isTurningOff()=true
09-02 11:35:47.842  2716  2716 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:47.842  2716  2716 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:47.842  2716  2716 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:47.842  2716  2764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-02 11:35:47.842  2716  2764 D BluetoothAdapterProperties: Setting state to 15
09-02 11:35:47.842  2716  2716 D BluetoothMapService: cleanup()
09-02 11:35:47.842  2716  2764 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-02 11:35:47.842  2716  2716 D BluetoothMapService: MAP Service closeService in
,09-02 11:35:47.843   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:35:47.843  1981  2270 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:35:47.843  1354  1368 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 11:35:47.843  2716  2764 I BluetoothAdapterState: Entering BleOnState
09-02 11:35:47.844   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:35:47.844   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 11:35:47.844  1354  1367 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 11:35:47.845  1354  2068 D BluetoothMap: onBluetoothStateChange: up=false
09-02 11:35:47.845  1354  1368 D BluetoothPan: onBluetoothStateChange on: false
09-02 11:35:47.846  1354  1367 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-02 11:35:47.846   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:35:47.846  1354  2068 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 11:35:47.847  2716  2764 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-02 11:35:47.847  2716  2764 D BluetoothAdapterProperties: Setting state to 16
09-02 11:35:47.847  2716  2764 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-02 11:35:47.847  2716  2764 D BluetoothAdapterProperties: onBleDisable
09-02 11:35:47.847  2716  2764 I BluetoothAdapterState: Entering PendingCommandState
,09-02 11:35:47.848  2716  2765 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-02 11:35:47.848  2716  2768 D BluetoothAdapterProperties: Scan Mode:20
09-02 11:35:47.852  2716  2892 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-02 11:35:47.852  2716  2892 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 11:35:47.852  3881  3957 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
09-02 11:35:47.854  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:47.854  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:47.854  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:47.854  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:47.854  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:47.854  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:47.854  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:47.854  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:47.854  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:35:47.854  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:47.854  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:35:47.856  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 11:35:47.856  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:47.856  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:47.856  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:47.856  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:47.856  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:47.856  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:47.856  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:47.856  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:35:47.857  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:47.857  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:35:47.858  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.858   872  1906 D DhcpClient: Receive thread stopped
09-02 11:35:47.859  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.870   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 11:35:47.882  3962  3962 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
09-02 11:35:47.887   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-02 11:35:47.888   872  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-02 11:35:47.889   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:35:47.890   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-02 11:35:47.893   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
09-02 11:35:47.894  3412  3412 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@f6483ae and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-02 11:35:47.895  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:47.895  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:47.895  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:47.895  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:47.895  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:35:47.895  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:47.895  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:47.895  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:47.895  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:35:47.896  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:47.896  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 11:35:47.897  2146  2325 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:35:47.897   872  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-02 11:35:47.898  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:47.898  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:47.898  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:47.898  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:47.898  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:35:47.898  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:47.898  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:47.898  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:47.898  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:35:47.898  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:47.898  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 11:35:47.899  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.900  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:47.903  3962  3962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 11:35:47.908  1557  1557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:35:47.911   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@146ab96:true
,09-02 11:35:47.921   872  1999 I ActivityManager: Start proc 3980:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-02 11:35:47.944   371   868 E Netd    : netlink response contains error (No such file or directory)
,09-02 11:35:47.946  3962  3962 D LocalBluetoothProfileManager: Adding local MAP profile
,09-02 11:35:47.948  3962  3962 D BluetoothMap: Create BluetoothMap proxy object
,09-02 11:35:47.955  3962  3962 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-02 11:35:47.960  3980  3980 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-02 11:35:47.969  3962  3962 D DockEventReceiver: finishStartingService: stopping service
,09-02 11:35:47.980   872  1687 I ActivityManager: Killing 3412:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-02 11:35:48.061  2716  2768 I bt_hci  : shut_down
,09-02 11:35:48.087  2716  2773 I bt_vendor: low_power_mode_cb
,09-02 11:35:48.093  2716  2773 D bt_hwcfg: hw_epilog_process
,09-02 11:35:48.106  2716  2773 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-02 11:35:48.106  2716  2773 I bt_vendor: epilog_cb
,09-02 11:35:48.106  2716  2773 I bt_hci  : epilog_finished_callback
,09-02 11:35:48.110  2716  2768 I bt_hci_h4: hal_close
,09-02 11:35:48.110  2716  2768 I bt_userial_vendor: device fd = 51 close
,09-02 11:35:48.149  3980  3980 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 11:35:48.149  3980  3980 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 11:35:48.149  3980  3980 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 11:35:48.149  3980  3980 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityTh,read.java)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 11:35:48.149  3980  3980 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.k.d(PG:583)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.e.b(PG:170)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 11:35:48.149  3980  3980 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:35:48.149  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 11:35:48.150  3980  3980 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at java.io.File.exists(File.java:361)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 11:35:48.150  3980  3980 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:35:48.150  3980  3980 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 11:35:48.162  3962  3962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 11:35:48.170  1557  1557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:35:48.175  3962  3962 D DockEventReceiver: finishStartingService: stopping service
09-02 11:35:48.187   872  1687 I ActivityManager: Killing 3459:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-02 11:35:48.243  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 11:35:48.254  1748  1748 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 11:35:48.265  1748  1748 D SystemUpdateService: onCreate
,09-02 11:35:48.270  1748  1748 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 11:35:48.270  2716  2765 D bt_stack_manager: event_shut_down_stack finished.
09-02 11:35:48.271  2716  2764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-02 11:35:48.275  2716  2764 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-02 11:35:48.275  2716  2716 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 11:35:48.276  2716  2716 D BtGatt.GattService: Received stop request...Stopping profile...
09-02 11:35:48.276  2716  2716 D BtGatt.GattService: stop()
,09-02 11:35:48.276  2716  2716 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 11:35:48.280  2716  2716 V BluetoothAdapterState: isTurningOff()=false
,09-02 11:35:48.280  2716  2716 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:48.280  2716  2716 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:48.280  2716  2716 V BluetoothAdapterState: isBleTurningOff()=true
09-02 11:35:48.281  2716  2764 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-02 11:35:48.281  2716  2764 D BluetoothAdapterProperties: Setting state to 10
09-02 11:35:48.281  2716  2764 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-02 11:35:48.288  2716  2764 I BluetoothAdapterState: Entering OffState
,09-02 11:35:48.290   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-02 11:35:48.303  1748  1748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 11:35:48.305  1748  2464 I iu.UploadsManager: num queued entries: 0
,09-02 11:35:48.318  2716  2716 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-02 11:35:48.318  2716  2716 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-02 11:35:48.318  2716  2716 I BluetoothServiceJni: cleanupNative: return from cleanup
09-02 11:35:48.319  2716  2765 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-02 11:35:48.322  2716  2765 D bt_stack_manager: event_clean_up_stack finished.
,09-02 11:35:48.325  1748  4012 I SystemUpdateService: active receiver: enabled
,09-02 11:35:48.305  1748  2464 I iu.UploadsManager: num updated entries: 0
,09-02 11:35:48.326  1748  2464 I iu.SyncManager: NEXT; no task
,09-02 11:35:48.328  2716  2716 I art     : System.exit called, status: 0
09-02 11:35:48.328  2716  2716 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 11:35:48.330  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 11:35:48.332  1748  1748 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 11:35:48.348   872  1999 I ActivityManager: Start proc 4016:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-02 11:35:48.361  1748  4012 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 11:35:48.366  1748  4012 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-02 11:35:48.367  1748  4012 I SystemUpdateService: now status is 0 (complete)
09-02 11:35:48.367  1748  4012 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 11:35:48.367  1748  4012 I SystemUpdateService: file has been verified
,09-02 11:35:48.367  1748  4012 I SystemUpdateService: OTA package size = 12249756
,09-02 11:35:48.373  1748  4012 I SystemUpdateService: showing system update notification
,09-02 11:35:48.387   872  2010 I ActivityManager: Process com.android.bluetooth (pid 2716) has died
,09-02 11:35:48.414  4016  4016 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-02 11:35:48.416  4016  4016 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:35:48.431  4016  4016 D SprintDMHelper: simOperator: 
09-02 11:35:48.431  4016  4016 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 11:35:48.445  3980  4007 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-02 11:35:48.458   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@516b591:true
,09-02 11:35:48.467   872  1999 I ActivityManager: Start proc 4030:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-02 11:35:48.477  1748  1748 D SystemUpdateService: onDestroy
,09-02 11:35:48.615   872  1999 I ActivityManager: Start proc 4045:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-02 11:35:48.619   872  1999 I ActivityManager: Killing 1671:android.process.acore/u0a5 (adj 15): empty #17
,09-02 11:35:48.688  4045  4045 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-02 11:35:48.739  4045  4045 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-02 11:35:48.739  4045  4045 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-02 11:35:48.739  4045  4045 I GAv4    :   adb logcat -s GAv4
,09-02 11:35:48.753  4045  4045 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-02 11:35:48.758  4045  4045 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-02 11:35:48.797  4045  4062 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-02 11:35:48.881  4045  4045 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-02 11:35:48.912  4045  4045 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-02 11:35:48.919  4045  4045 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2935-2937)
,09-02 11:35:48.919  4045  4045 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 11:35:48.929  4045  4045 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1bcfdf8}
,09-02 11:35:48.930  4045  4045 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-02 11:35:48.930  4045  4045 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-02 11:35:48.937  4045  4045 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-02 11:35:48.939  4045  4045 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-02 11:35:48.957  4045  4045 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-02 11:35:48.970  4045  4045 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-02 11:35:48.971  4045  4045 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-02 11:35:48.971  4045  4045 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 11:35:48.971  4045  4045 I Adreno  : Build Date                       : 10/20/15
09-02 11:35:48.971  4045  4045 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 11:35:48.971  4045  4045 I Adreno  : Local Branch                     : M14
09-02 11:35:48.971  4045  4045 I Adreno  : Remote Branch                    : 
09-02 11:35:48.971  4045  4045 I Adreno  : Remote Branch                    : 
09-02 11:35:48.971  4045  4045 I Adreno  : Reconstruct Branch               : 
,09-02 11:35:49.025  4045  4045 I NSApplication: Starting up...
,09-02 11:35:49.035  4045  4091 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-02 11:35:49.052   872  1400 I ActivityManager: Start proc 4096:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-02 11:35:49.053   872  1400 I ActivityManager: Killing 3649:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-02 11:35:49.143  4096  4096 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-02 11:35:49.340   872  1992 I ActivityManager: Killing 3665:com.android.musicfx/u0a18 (adj 15): empty #17
,09-02 11:35:49.402   872  1399 I ActivityManager: Start proc 4110:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-02 11:35:49.471  4110  4110 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-02 11:35:49.516  4110  4110 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-02 11:35:49.577   872   883 I ActivityManager: Killing 3479:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-02 11:35:50.816   872  1686 D WifiService: setWifiEnabled: true pid=3881, uid=10000
,09-02 11:35:50.817   872  1686 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 11:35:50.828   872  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-02 11:35:50.837  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 11:35:50.838  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:50.838  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:50.838  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:50.838  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:50.838  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:50.838  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:50.838  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:50.838  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:35:50.838  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 11:35:50.838  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 11:35:50.840  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 11:35:50.841  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:50.841  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:50.841  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:50.841  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:50.841  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:50.841  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:50.841  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:50.841  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:35:50.841  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:50.841  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:35:50.852   872  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-02 11:35:50.853   872  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-02 11:35:50.854   872  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-02 11:35:50.855   872  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-02 11:35:50.855   872  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-02 11:35:50.855   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-02 11:35:50.855   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-02 11:35:50.873   371   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-02 11:35:50.873   872  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=15.00 rxSuccessRate=19.25 delta 1000 -> 994
,09-02 11:35:50.875   371   868 D CommandListener: Setting iface cfg
,09-02 11:35:50.876   872  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-02 11:35:50.877   872  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 11:35:50.882   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-02 11:35:50.883   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 11:35:50.890   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-02 11:35:50.925   872  1309 D WifiNative-HAL: p2pGetDeviceAddress
,09-02 11:35:50.928   872  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-02 11:35:50.949   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-02 11:35:50.952  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-02 11:35:51.373  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 11:35:51.436  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-02 11:35:51.440  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-02 11:35:51.448   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 11:35:51.463   872  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 11:35:51.464   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-02 11:35:51.464   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 11:35:51.483   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 11:35:51.494   371   868 D CommandListener: Setting iface cfg
,09-02 11:35:51.496   872  1310 D WifiStateMachine: Start Dhcp Watchdog 2
,09-02 11:35:51.516   872  1312 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-02 11:35:51.520   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-02 11:35:51.543   872  4143 D DhcpClient: Receive thread started
,09-02 11:35:51.628   872  1310 E native  : do suspend false
,09-02 11:35:51.650   872  1905 D DhcpClient: Broadcasting DHCPDISCOVER
,09-02 11:35:51.682   872  4143 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172688, domain null
,09-02 11:35:51.684   872  1905 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172688 seconds
,09-02 11:35:51.687   872  1905 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-02 11:35:51.709   872  4143 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-02 11:35:51.710   872  1905 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-02 11:35:51.714   371   868 D CommandListener: Setting iface cfg
,09-02 11:35:51.726   872  1905 D DhcpClient: Scheduling renewal in 86399s
,09-02 11:35:51.727   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-02 11:35:51.747   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-02 11:35:51.751   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-02 11:35:51.752   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-02 11:35:51.754   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-02 11:35:51.757   872  1312 D ConnectivityService: Adding iface wlan0 to network 101
,09-02 11:35:51.773   872  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 11:35:51.818   872  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-02 11:35:51.818   872  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-02 11:35:51.819   872  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-02 11:35:51.820   872  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-02 11:35:51.822   872  1312 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-02 11:35:51.832   872  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-02 11:35:51.837   872  1312 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-02 11:35:51.838   872  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-02 11:35:51.838   872  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-02 11:35:51.838   872  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-02 11:35:51.838   872  1312 D ConnectivityService:    accepting network in place of null
09-02 11:35:51.838   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-02 11:35:51.839   872  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -51]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 11:35:51.899   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 11:35:51.941   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 11:35:51.951   872  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-02 11:35:51.951   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:35:51.959   872  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-02 11:35:51.964   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-02 11:35:51.976  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:51.976  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:51.976  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:51.976  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:51.976  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:51.976  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:51.976  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:51.976  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:35:51.976  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:35:51.976  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:51.976  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:51.982  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:51.982  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:51.982  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:51.982  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:51.982  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:35:51.982  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:51.982  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:35:51.982  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:35:51.982  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-02 11:35:51.982  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:51.982  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 11:35:51.991  1748  1748 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 11:35:51.994  1748  1748 D SystemUpdateService: onCreate
,09-02 11:35:52.000  1748  1748 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 11:35:52.002  1748  4154 I SystemUpdateService: active receiver: enabled
,09-02 11:35:52.012  1748  4154 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 11:35:52.014  1748  4154 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-02 11:35:52.014  1748  4154 I SystemUpdateService: now status is 0 (complete)
09-02 11:35:52.015  1748  4154 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 11:35:52.015  1748  4154 I SystemUpdateService: file has been verified
09-02 11:35:52.015  1748  4154 I SystemUpdateService: OTA package size = 12249756
,09-02 11:35:52.019  1748  1748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-02 11:35:52.024  1748  2464 I iu.UploadsManager: num queued entries: 0
,09-02 11:35:52.026  1748  4158 I MDM     : [179] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-02 11:35:52.026  1748  4158 W BaseAppContext: Using Auth Proxy for data requests.
,09-02 11:35:52.028  1748  4158 V GoogleAuthProtoRequest: [179] a.<init>: mAccountName set to: thalitester@gmail.com
,09-02 11:35:52.028  1748  4154 I SystemUpdateService: showing system update notification
,09-02 11:35:52.030  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 11:35:52.031  1748  1748 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-02 11:35:52.033  1748  2464 I iu.UploadsManager: num updated entries: 0
09-02 11:35:52.033  4016  4016 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:35:52.037  4016  4016 D SprintDMHelper: simOperator: 
,09-02 11:35:52.037  4016  4016 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-02 11:35:52.038  1557  1557 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 11:35:52.039  1748  2464 I iu.SyncManager: NEXT; no task
,09-02 11:35:52.041  1557  1557 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 11:35:52.063  1748  1748 D SystemUpdateService: onDestroy
,09-02 11:35:52.072  1557  1572 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-02 11:35:52.072  1557  1572 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-02 11:35:52.072  1557  1572 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 11:35:52.073  1557  1572 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 11:35:52.087  1748  4158 E MDM     : [179] SitrepService.a: Error sending sitrep.
,09-02 11:35:52.137  1557  2314 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-02 11:35:52.137  1557  2314 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-02 11:35:52.137  1557  2314 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 11:35:52.137  1557  2314 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 11:35:52.148  3008  4155 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-02 11:35:52.148  3008  4155 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at jdm.a(PG:82)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at jcs.o(PG:406)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at jcn.a(PG:1379)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at jcs.i(PG:143)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at blb.a(PG:3937)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at czp.a(PG:18188)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at czp.a(PG:9081)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at czq.run(PG:1686)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-02 11:35:52.148  3008  4155 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at jdj.a(PG:4091)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at jdj.a(PG:1125)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at jdm.a(PG:77)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	... 12 more
09-02 11:35:52.148  3008  4155 E HttpOperation: Caused by: faj: BadAuthentication
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at fal.a(PG:38)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	at jdj.a(PG:4089)
09-02 11:35:52.148  3008  4155 E HttpOperation: 	... 14 more
,09-02 11:35:52.180  1557  1569 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-02 11:35:52.180  1557  1569 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-02 11:35:52.180  1557  1569 I GLSUser : [GLSUser] Extracting token using key: Auth
09-02 11:35:52.180  1557  1569 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 11:35:52.196  3008  4155 E HttpOperation: [getmobileexperiments] Unexpected exception
09-02 11:35:52.196  3008  4155 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at jdm.a(PG:82)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at jcs.o(PG:406)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at jcn.a(PG:1379)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at jcs.i(PG:143)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at hec.a(PG:42)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at hee.a(PG:102)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at czr.a(PG:65)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at kka.a(PG:108)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at czp.a(PG:19176)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at czp.a(PG:9081)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at czq.run(PG:1686)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-02 11:35:52.196  3008  4155 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at jdj.a(PG:4091)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at jdj.a(PG:1125)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at jdm.a(PG:77)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	... 15 more
09-02 11:35:52.196  3008  4155 E HttpOperation: Caused by: faj: BadAuthentication
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at fal.a(PG:38)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	at jdj.a(PG:4089)
09-02 11:35:52.196  3008  4155 E HttpOperation: 	... 17 more
,09-02 11:35:52.196  3008  4155 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-02 11:35:52.196  3008  4155 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at jdm.a(PG:82)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at jcs.o(PG:406)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at jcn.a(PG:1379)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at jcs.i(PG:143)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at hec.a(PG:42)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at hee.a(PG:102)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at czr.a(PG:65)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at kka.a(PG:108)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at czp.a(PG:19176)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at czp.a(PG:9081)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at czq.run(PG:1686)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at jdj.a(PG:4091)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at jdj.a(PG:1125)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at jdm.a(PG:77)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	... 15 more
09-02 11:35:52.196  3008  4155 E ExperimentLoader: Caused by: faj: BadAuthentication
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at fal.a(PG:38)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	at jdj.a(PG:4089)
09-02 11:35:52.196  3008  4155 E ExperimentLoader: 	... 17 more
,09-02 11:35:52.318   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 134457, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-02 11:35:52.552   872  4142 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-02 11:35:52.950   872  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-02 11:35:53.822   872  2010 D WifiService: setWifiEnabled: false pid=3881, uid=10000
,09-02 11:35:53.823   872  2010 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 11:35:53.864  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-02 11:35:53.875   872  1310 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-02 11:35:53.875   872  1310 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-02 11:35:53.876   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 11:35:53.876   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 11:35:53.904   872  1905 D DhcpClient: Clearing IP address
,09-02 11:35:53.904   371   868 D CommandListener: Clearing all IP addresses on wlan0
,09-02 11:35:53.922   371   868 D CommandListener: Setting iface cfg
,09-02 11:35:53.925   872  4143 D DhcpClient: Receive thread stopped
,09-02 11:35:53.936   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-02 11:35:53.936   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-02 11:35:53.939   872  1310 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-02 11:35:53.940   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 11:35:53.942   408   408 E Parcel  : Reading a NULL string not supported here.
09-02 11:35:53.944   371   868 D CommandListener: Clearing all IP addresses on wlan0
,09-02 11:35:53.954   872  1312 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-02 11:35:53.957   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 11:35:53.962  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 11:35:53.962  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:53.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:53.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:53.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:35:53.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:53.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:53.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:53.962  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:35:53.963  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:53.963  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:35:53.964  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:53.965  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:53.965  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:53.965  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:53.965  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:35:53.965  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:53.965  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:53.965  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:53.965  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:35:53.965  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-02 11:35:53.965  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 11:35:53.968  2146  2325 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-02 11:35:53.970   872  1310 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-02 11:35:53.988   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 11:35:54.014   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 11:35:54.015   872  1312 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-02 11:35:54.015   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:35:54.018   872   889 D Tethering: MasterInitialState.processMessage what=3
09-02 11:35:54.024  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:54.025  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:54.039  1748  1748 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 11:35:54.043  1748  1748 D SystemUpdateService: onCreate
,09-02 11:35:54.046  1748  1748 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 11:35:54.053  1748  4175 I SystemUpdateService: active receiver: enabled
,09-02 11:35:54.056  1748  1748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-02 11:35:54.061  1748  2464 I iu.UploadsManager: num queued entries: 0
,09-02 11:35:54.062  1748  2464 I iu.UploadsManager: num updated entries: 0
,09-02 11:35:54.066  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 11:35:54.067  1748  1748 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 11:35:54.070  4016  4016 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:35:54.075  4016  4016 D SprintDMHelper: simOperator: 
,09-02 11:35:54.075  4016  4016 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-02 11:35:54.087  1748  4175 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 11:35:54.096   371   868 E Netd    : netlink response contains error (No such file or directory)
,09-02 11:35:54.097   872  1312 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-02 11:35:54.101  1748  4175 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-02 11:35:54.101  1748  4175 I SystemUpdateService: now status is 0 (complete)
09-02 11:35:54.101  1748  4175 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-02 11:35:54.101  1748  4175 I SystemUpdateService: file has been verified
09-02 11:35:54.101  1748  4175 I SystemUpdateService: OTA package size = 12249756
,09-02 11:35:54.103  1748  2464 I iu.SyncManager: NEXT; no task
,09-02 11:35:54.110  1748  4175 I SystemUpdateService: showing system update notification
,09-02 11:35:54.118  1748  1748 D SystemUpdateService: onDestroy
,09-02 11:35:56.851   872  4141 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-02 11:35:56.853   872  1312 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-02 11:35:56.879   872   889 I ActivityManager: Start proc 4182:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-02 11:35:57.005  4182  4182 D AdapterServiceConfig: Adding HeadsetService
,09-02 11:35:57.005  4182  4182 D AdapterServiceConfig: Adding A2dpService
09-02 11:35:57.006  4182  4182 D AdapterServiceConfig: Adding HidService
,09-02 11:35:57.006  4182  4182 D AdapterServiceConfig: Adding HealthService
09-02 11:35:57.007  4182  4182 D AdapterServiceConfig: Adding PanService
,09-02 11:35:57.007  4182  4182 D AdapterServiceConfig: Adding GattService
09-02 11:35:57.007  4182  4182 D AdapterServiceConfig: Adding BluetoothMapService
,09-02 11:35:57.022   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e73a787:true
,09-02 11:35:57.022  4182  4182 D BluetoothAdapterState: make() - Creating AdapterState
,09-02 11:35:57.027  4182  4182 I bt_bluedroid: init
,09-02 11:35:57.028  4182  4194 I BluetoothAdapterState: Entering OffState
,09-02 11:35:57.029  4182  4195 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 11:35:57.029  4182  4195 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 11:35:57.029  4182  4195 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 11:35:57.030  4182  4195 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 11:35:57.030  4182  4182 I bt_bluedroid: get_profile_interface socket
,09-02 11:35:57.032  4182  4182 I bt_bluedroid: get_profile_interface sdp
,09-02 11:35:57.036  4182  4193 I bt_bluedroid: config_hci_snoop_log
,09-02 11:35:57.037  4182  4198 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 11:35:57.038   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 11:35:57.040  4182  4198 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 11:35:57.046  4182  4194 D BluetoothAdapterState: Current state: OFF, message: 0
,09-02 11:35:57.047  4182  4194 D BluetoothAdapterProperties: Setting state to 14
,09-02 11:35:57.047  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-02 11:35:57.051  4182  4194 D BluetoothBondStateMachine: make
,09-02 11:35:57.055  4182  4199 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 11:35:57.063  4182  4182 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-02 11:35:57.063  4182  4194 I BluetoothAdapterState: Entering PendingCommandState
,09-02 11:35:57.067  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:35:57.067  4182  4182 D BtGatt.DebugUtils: handleDebugAction() action=null
09-02 11:35:57.068  4182  4182 D BtGatt.GattService: Received start request. Starting profile...
,09-02 11:35:57.068  4182  4182 D BtGatt.GattService: start()
,09-02 11:35:57.068  4182  4182 I bt_bluedroid: get_profile_interface gatt
,09-02 11:35:57.069  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
09-02 11:35:57.070  4182  4182 D BtGatt.AdvertiseManager: advertise manager created
,09-02 11:35:57.080  4182  4182 V BluetoothAdapterState: isTurningOff()=false
,09-02 11:35:57.080  4182  4182 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:57.080  4182  4182 V BluetoothAdapterState: isBleTurningOn()=true
,09-02 11:35:57.081  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:57.081  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-02 11:35:57.082  4182  4194 I bt_bluedroid: enable
,09-02 11:35:57.082  4182  4195 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-02 11:35:57.083  4182  4195 I bt_hci  : start_up
,09-02 11:35:57.088  4182  4195 I bt_vendor: alloc value 0xb39bd189
,09-02 11:35:57.088  4182  4195 I bt_vendor: init
09-02 11:35:57.088  4182  4195 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-02 11:35:57.088  4182  4195 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-02 11:35:57.095  2419  4161 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-02 11:35:57.096  2419  4161 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-02 11:35:57.098  2419  4161 I Babel   : connection state changed from CONNECTED to DISCONNECTED
09-02 11:35:57.103   872  1399 I ActivityManager: Killing 3687:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-02 11:35:57.195  4182  4195 D bt_hci  : start_up starting async portion
,09-02 11:35:57.196  4182  4202 I bt_hci  : event_finish_startup
,09-02 11:35:57.197  4182  4202 I bt_hci_h4: hal_open
,09-02 11:35:57.197  4182  4202 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-02 11:35:57.203  4182  4202 I bt_userial_vendor: device fd = 51 open
,09-02 11:35:57.240  4182  4202 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 11:35:57.271  4182  4202 D bt_hwcfg: Chipset BCM4354A2
,09-02 11:35:57.271  4182  4202 D bt_hwcfg: Target name = [BCM4354A2]
,09-02 11:35:57.272  4182  4202 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-02 11:35:57.932  4182  4202 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-02 11:35:57.933  4182  4202 D bt_hwcfg: Settlement delay -- 100 ms
09-02 11:35:57.933  4182  4202 I bt_hwcfg: Setting fw settlement delay to 100 
,09-02 11:35:58.050  4182  4202 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 11:35:58.051  4182  4202 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-02 11:35:58.081  4182  4202 I bt_hwcfg: vendor lib fwcfg completed
,09-02 11:35:58.081  4182  4202 I bt_vendor: firmware callback
09-02 11:35:58.081  4182  4202 I bt_hci  : firmware_config_callback
,09-02 11:35:58.093  4182  4204 I bt_btu  : btu_task pending for preload complete event
,09-02 11:35:58.093  4182  4204 I bt_btu_task: Bluetooth chip preload is complete
09-02 11:35:58.093  4182  4204 I bt_btu  : btu_task received preload complete event
,09-02 11:35:58.103  4182  4204 I         : BTE_InitTraceLevels -- TRC_HCI
,09-02 11:35:58.103  4182  4204 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-02 11:35:58.103  4182  4204 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-02 11:35:58.104  4182  4204 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 11:35:58.104  4182  4204 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-02 11:35:58.104  4182  4204 I         : BTE_InitTraceLevels -- TRC_A2D
09-02 11:35:58.104  4182  4204 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-02 11:35:58.105  4182  4204 I         : BTE_InitTraceLevels -- TRC_BTM
09-02 11:35:58.105  4182  4204 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 11:35:58.105  4182  4204 I         : BTE_InitTraceLevels -- TRC_PAN
,09-02 11:35:58.106  4182  4204 I         : BTE_InitTraceLevels -- TRC_SDP
09-02 11:35:58.106  4182  4204 I         : BTE_InitTraceLevels -- TRC_GATT
,09-02 11:35:58.106  4182  4204 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 11:35:58.106  4182  4204 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-02 11:35:58.107  4182  4204 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 11:35:58.240  4182  4204 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393ad9d
,09-02 11:35:58.240  4182  4204 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393ad9d 
,09-02 11:35:58.269  4182  4198 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-02 11:35:58.270  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-02 11:35:58.271  4182  4198 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 11:35:58.274  4182  4198 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 11:35:58.278  4182  4198 D BluetoothAdapterProperties: Scan Mode:20
,09-02 11:35:58.278  4182  4198 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 11:35:58.279  4182  4198 D bt_hci  : do_postload posting postload work item
09-02 11:35:58.279  4182  4202 I bt_hci  : event_postload
,09-02 11:35:58.280  4182  4202 I bt_vendor: sco_config_cb
,09-02 11:35:58.280  4182  4202 I bt_hci  : sco_config_callback postload finished.
,09-02 11:35:58.281  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-02 11:35:58.284  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:58.284  4182  4198 D bt_bte_conf: Device ID record 1 : primary
09-02 11:35:58.284  4182  4198 D bt_bte_conf:   vendorId            = 000f
,09-02 11:35:58.284  4182  4198 D bt_bte_conf:   vendorIdSource      = 0001
09-02 11:35:58.284  4182  4198 D bt_bte_conf:   product             = 1200
,09-02 11:35:58.285  4182  4198 D bt_bte_conf:   version             = 1436
,09-02 11:35:58.285  4182  4198 D bt_bte_conf:   clientExecutableURL = 
,09-02 11:35:58.285  4182  4198 D bt_bte_conf:   serviceDescription  = ,
,09-02 11:35:58.286  4182  4198 D bt_bte_conf:   documentationURL    = 
09-02 11:35:58.286  4182  4198 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-02 11:35:58.286  4182  4195 D bt_stack_manager: event_start_up_stack finished
,09-02 11:35:58.287  4182  4202 I bt_vendor: low_power_mode_cb
,09-02 11:35:58.287  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-02 11:35:58.288  4182  4194 D BluetoothAdapterProperties: Setting state to 15
,09-02 11:35:58.288  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-02 11:35:58.291  4182  4194 I BluetoothAdapterState: Entering BleOnState,
09-02 11:35:58.295  4182  4194 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-02 11:35:58.295  4182  4194 D BluetoothAdapterProperties: Setting state to 11
,09-02 11:35:58.295  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-02 11:35:58.304  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:35:58.306  4182  4182 D HeadsetService: Received start request. Starting profile...
,09-02 11:35:58.313  4182  4182 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 11:35:58.314  4182  4182 D HeadsetStateMachine: make
,09-02 11:35:58.318  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:58.320  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:58.322  4182  4194 I BluetoothAdapterState: Entering PendingCommandState
,09-02 11:35:58.331  4182  4182 D HeadsetStateMachine: max_hf_connections = 1
,09-02 11:35:58.332  4182  4182 I bt_bluedroid: get_profile_interface handsfree
09-02 11:35:58.332  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-02 11:35:58.332  4182  4198 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-02 11:35:58.339  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:35:58.340  4182  4182 D A2dpService: Received start request. Starting profile...
,09-02 11:35:58.340  4182  4182 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 11:35:58.341  4182  4182 I bt_bluedroid: get_profile_interface avrcp
,09-02 11:35:58.349  4182  4182 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 11:35:58.349  4182  4182 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 11:35:58.349  4182  4182 D A2dpStateMachine: make
,09-02 11:35:58.351  4182  4182 I bt_bluedroid: get_profile_interface a2dp
,09-02 11:35:58.352  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-02 11:35:58.353  4182  4213 D A2dpStateMachine: Enter Disconnected: -2
09-02 11:35:58.354  4182  4182 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 11:35:58.355  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:35:58.356  3962  3962 D BluetoothInputDevice: Proxy object connected
09-02 11:35:58.357  3962  3962 D HidProfile: Bluetooth service connected
09-02 11:35:58.357  4182  4182 D HidService: Received start request. Starting profile...
09-02 11:35:58.357  4182  4182 I bt_bluedroid: get_profile_interface hidhost
,09-02 11:35:58.358  4182  4198 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb391c3e5
,09-02 11:35:58.358  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-02 11:35:58.358  4182  4182 D HidService: setHidService(): set to: null
09-02 11:35:58.359  4182  4182 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 11:35:58.359  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:35:58.360  4182  4182 D HealthService: Received start request. Starting profile...
,09-02 11:35:58.363  4182  4182 I bt_bluedroid: get_profile_interface health
,09-02 11:35:58.363  4182  4182 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-02 11:35:58.364  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:35:58.365  3962  3962 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 11:35:58.365  4182  4182 D PanService: Received start request. Starting profile...
09-02 11:35:58.366  3962  3962 D PanProfile: Bluetooth service connected
09-02 11:35:58.366  4182  4182 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-02 11:35:58.366  4182  4182 I bt_bluedroid: get_profile_interface pan
,09-02 11:35:58.369  4182  4198 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-02 11:35:58.376  4182  4182 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:35:58.378  3962  3962 D BluetoothMap: Proxy object connected
,09-02 11:35:58.378  4182  4182 D BluetoothMapService: Received start request. Starting profile...
09-02 11:35:58.378  4182  4182 D BluetoothMapService: start()
09-02 11:35:58.379  3962  3962 D MapProfile: Bluetooth service connected
09-02 11:35:58.379  3962  3962 D BluetoothMap: getConnectedDevices()
09-02 11:35:58.380  3962  3962 D BluetoothMap: Bluetooth is Not enabled
,09-02 11:35:58.381  4182  4182 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-02 11:35:58.381  4182  4182 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-02 11:35:58.381  4182  4182 D BluetoothMapAppObserver: createReceiver()
,09-02 11:35:58.382  4182  4182 D BluetoothMapAppObserver: initObservers()
,09-02 11:35:58.383  4182  4182 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-02 11:35:58.391  1557  1557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-02 11:35:58.391  4182  4182 V BluetoothAdapterState: isTurningOff()=false
,09-02 11:35:58.391  4182  4182 V BluetoothAdapterState: isTurningOn()=true
09-02 11:35:58.392  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:58.392  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 11:35:58.395  4182  4182 V BluetoothAdapterState: isTurningOff()=false
09-02 11:35:58.395  4182  4182 V BluetoothAdapterState: isTurningOn()=true
,09-02 11:35:58.395  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:58.395  4182  4210 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-02 11:35:58.395  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:58.395  4182  4182 V BluetoothAdapterState: isTurningOff()=false
09-02 11:35:58.395  4182  4182 V BluetoothAdapterState: isTurningOn()=true
09-02 11:35:58.395  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:58.395  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 11:35:58.395  4182  4182 V BluetoothAdapterState: isTurningOff()=false
09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isTurningOn()=true
09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isTurningOff()=false
09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isTurningOn()=true
,09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isTurningOff()=false
09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isTurningOn()=true
09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:58.396  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 11:35:58.397  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-02 11:35:58.397  4182  4194 D BluetoothAdapterProperties: ScanMode =  20
,09-02 11:35:58.397  4182  4194 D BluetoothAdapterProperties: State =  11
,09-02 11:35:58.401  4182  4198 D BluetoothAdapterProperties: Scan Mode:21
,09-02 11:35:58.401  4182  4198 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 11:35:58.401  4182  4194 D BluetoothAdapterProperties: Setting state to 12
09-02 11:35:58.401  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 11:35:58.402  4182  4194 I BluetoothAdapterState: Entering OnState
09-02 11:35:58.402  3962  3972 D BluetoothPan: onBluetoothStateChange on: true
,09-02 11:35:58.402  3962  3974 D BluetoothMap: onBluetoothStateChange: up=true
09-02 11:35:58.402   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:35:58.404  3962  3972 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 11:35:58.406  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:58.406  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:58.406  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:58.406  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:35:58.406  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:35:58.406  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:58.406  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:58.406  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:35:58.408  1981  1997 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 11:35:58.408  4182  4182 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 11:35:58.409  1354  2068 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 11:35:58.409  4182  4182 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-02 11:35:58.409  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 11:35:58.410  4182  4182 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:35:58.411  3962  3974 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 11:35:58.411   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:35:58.412   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 11:35:58.413  1354  1368 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 11:35:58.413  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:58.413  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:58.413  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:58.413  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:35:58.413  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:35:58.413  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:58.413  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:58.413  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:35:58.415  1354  1367 D BluetoothMap: onBluetoothStateChange: up=true
,09-02 11:35:58.415  4182  4182 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:35:58.416  1354  1354 D BluetoothMap: Proxy object connected
09-02 11:35:58.416  1354  1354 D MapProfile: Bluetooth service connected
09-02 11:35:58.416  1354  1354 D BluetoothMap: getConnectedDevices()
,09-02 11:35:58.417  1354  1368 D BluetoothPan: onBluetoothStateChange on: true
09-02 11:35:58.417  4182  4182 D ObexServerSockets: Succeed to create listening sockets 
09-02 11:35:58.417  4182  4182 D ObexServerSockets0: startAccept()
09-02 11:35:58.417  4182  4182 D ObexServerSockets0: prepareForNewConnect()
,09-02 11:35:58.418  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:35:58.418  1354  1367 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 11:35:58.418  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 11:35:58.419  1354  1354 D PanProfile: Bluetooth service connected
09-02 11:35:58.419  4182  4182 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-02 11:35:58.419  4182  4182 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-02 11:35:58.420   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 11:35:58.420  1354  1354 D BluetoothInputDevice: Proxy object connected
,09-02 11:35:58.420  1354  1368 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 11:35:58.420  1354  1354 D HidProfile: Bluetooth service connected
09-02 11:35:58.421   872   872 D BluetoothA2dp: Proxy object connected
09-02 11:35:58.422  4182  4219 D ObexServerSockets0: Accepting socket connection...
09-02 11:35:58.422  4182  4220 D ObexServerSockets0: Accepting socket connection...
09-02 11:35:58.427  4182  4182 D BluetoothMapService: onReceive
,09-02 11:35:58.427  4182  4182 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:35:58.427  4182  4182 D BluetoothMapService: STATE_ON
09-02 11:35:58.427  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:58.430  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:58.431  1354  1354 D BluetoothA2dp: Proxy object connected
,09-02 11:35:58.432  3962  3962 D LocalBluetoothProfileManager: Adding local A2DP profile
09-02 11:35:58.432   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,09-02 11:35:58.437  3962  3962 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-02 11:35:58.446  3962  3962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 11:35:58.447  4182  4182 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-02 11:35:58.447  4182  4182 D ObexServerSockets0: prepareForNewConnect()
,09-02 11:35:58.450  3962  3962 D BluetoothA2dp: Proxy object connected
,09-02 11:35:58.456  1557  1557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 11:35:58.460  3962  3962 D DockEventReceiver: finishStartingService: stopping service
,09-02 11:35:58.471  3962  3962 D BluetoothPbap: Proxy object connected
,09-02 11:35:58.471  1354  1354 D BluetoothPbap: Proxy object connected
09-02 11:35:58.471  1354  1354 D PbapServerProfile: Bluetooth service connected
09-02 11:35:58.471  3962  3962 D PbapServerProfile: Bluetooth service connected
,09-02 11:35:58.477  4182  4226 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 11:35:58.495  4182  4230 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 11:35:58.499  4182  4230 I BtOppRfcommListener: Accept thread started.
,09-02 11:35:58.506  1354  2068 D BluetoothHeadset: Proxy object connected
,09-02 11:35:58.506  1354  1354 D HeadsetProfile: Bluetooth service connected
09-02 11:35:58.506   872   872 D BluetoothHeadset: Proxy object connected
09-02 11:35:58.506   872   872 D BluetoothHeadset: Proxy object connected
,09-02 11:35:58.507   872   872 D BluetoothHeadset: Proxy object connected
,09-02 11:35:58.507  1981  2202 D BluetoothHeadset: Proxy object connected
,09-02 11:35:58.509  1981  2202 D BluetoothHeadset: Proxy object connected
,09-02 11:35:58.512   872   889 D BluetoothHeadset: Proxy object connected
,09-02 11:35:58.514  1354  1368 D BluetoothHeadset: Proxy object connected
,09-02 11:35:58.514  1354  1354 D HeadsetProfile: Bluetooth service connected
,09-02 11:35:58.520   872   889 D BluetoothHeadset: Proxy object connected
,09-02 11:35:58.544  3962  3974 D BluetoothHeadset: Proxy object connected
09-02 11:35:58.545  3962  3962 D HeadsetProfile: Bluetooth service connected
,09-02 11:35:59.838   872  1312 D ConnectivityService: handlePromptUnvalidated 101
,09-02 11:35:59.841  4182  4194 D BluetoothAdapterState: Current state: ON, message: 23
,09-02 11:35:59.841  4182  4194 D BluetoothAdapterProperties: Setting state to 13
,09-02 11:35:59.842  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-02 11:35:59.844  4182  4194 D BluetoothAdapterProperties: onBluetoothDisable()
,09-02 11:35:59.846  4182  4194 I BluetoothAdapterState: Entering PendingCommandState
,09-02 11:35:59.850  4182  4198 D BluetoothAdapterProperties: Scan Mode:20
,09-02 11:35:59.851  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-02 11:35:59.853  4182  4182 D BluetoothMapService: onReceive
09-02 11:35:59.853  4182  4182 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:35:59.853  4182  4182 D BluetoothMapService: STATE_TURNING_OFF
09-02 11:35:59.854  4182  4182 D BluetoothMapService: MAP Service closeService in
09-02 11:35:59.854  4182  4182 D BluetoothMapMasInstance0: MAP Service shutdown
09-02 11:35:59.854  4182  4182 D ObexServerSockets0: shutdown(block = true)
09-02 11:35:59.855  4182  4182 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 11:35:59.855  4182  4182 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-02 11:35:59.855  4182  4219 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-02 11:35:59.858  4182  4220 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-02 11:35:59.859  4182  4206 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-02 11:35:59.860  4182  4182 I BtOppRfcommListener: stopping Accept Thread
09-02 11:35:59.861  4182  4230 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-02 11:35:59.862  3962  3962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-02 11:35:59.862  4182  4230 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-02 11:35:59.862  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:59.863  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:59.863  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:35:59.863  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:59.863  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:35:59.863  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:59.863  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:59.863  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:59.863  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:35:59.864  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:59.864  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:35:59.866  4182  4182 D HeadsetService: Received stop request...Stopping profile...
09-02 11:35:59.869  1354  1367 D BluetoothHeadset: Proxy object disconnected
09-02 11:35:59.870   872   872 D BluetoothHeadset: Proxy object disconnected
09-02 11:35:59.870   872   872 D BluetoothHeadset: Proxy object disconnected
09-02 11:35:59.870  4182  4182 D A2dpService: Received stop request...Stopping profile...
09-02 11:35:59.872  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:59.872  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:35:59.872  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi,-Fi Direct supported: true
09-02 11:35:59.872  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:35:59.872  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:35:59.872  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-02 11:35:59.872  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:35:59.872  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:35:59.872  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-02 11:35:59.872  4182  4213 D A2dpStateMachine: Exit Disconnected: -1
09-02 11:35:59.873  3962  3974 D BluetoothHeadset: Proxy object disconnected
09-02 11:35:59.873   872   872 D BluetoothHeadset: Proxy object disconnected
09-02 11:35:59.873  3881  3881 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-02 11:35:59.874  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:35:59.874  1981  1997 D BluetoothHeadset: Proxy object disconnected
09-02 11:35:59.874   872   872 D BluetoothA2dp: Proxy object disconnected
09-02 11:35:59.874  4182  4182 V BluetoothAdapterState: isTurningOff()=true
09-02 11:35:59.874  4182  4182 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:59.875  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:59.875  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:59.875  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:59.875  4182  4182 D HidService: Received stop request...Stopping profile...
09-02 11:35:59.875  4182  4182 D HidService: Stopping Bluetooth HidService
09-02 11:35:59.877  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:35:59.879  4182  4182 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-02 11:35:59.879  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-02 11:35:59.879  4182  4204 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 11:35:59.879  4182  4204 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 11:35:59.879  4182  4204 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 11:35:59.879  4182  4182 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-02 11:35:59.879  4182  4198 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
09-02 11:35:59.880  4182  4182 D HealthService: Received stop request...Stopping profile...
,09-02 11:35:59.881  4182  4182 V BluetoothAdapterState: isTurningOff()=true
,09-02 11:35:59.881  4182  4182 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:59.881  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:59.882  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false,
09-02 11:35:59.883  1354  1354 D HeadsetProfile: Bluetooth service disconnected
09-02 11:35:59.884  1354  1354 D BluetoothA2dp: Proxy object disconnected
,09-02 11:35:59.884  1354  1354 D BluetoothInputDevice: Proxy object disconnected
09-02 11:35:59.884  1354  1354 D HidProfile: Bluetooth service disconnected
,09-02 11:35:59.886  1557  1557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 11:35:59.886  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-02 11:35:59.886  4182  4204 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 11:35:59.887  4182  4204 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-02 11:35:59.887  4182  4204 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-02 11:35:59.887  4182  4204 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:35:59.887  4182  4204 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-02 11:35:59.887  4182  4204 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-02 11:35:59.887  4182  4182 D PanService: Received stop request...Stopping profile...
,09-02 11:35:59.891  3962  3962 D DockEventReceiver: finishStartingService: stopping service
,09-02 11:35:59.891  4182  4182 D BluetoothMapService: Received stop request...Stopping profile...
09-02 11:35:59.891  4182  4182 D BluetoothMapService: stop()
09-02 11:35:59.892  4182  4182 D BluetoothMapAppObserver: deinitObservers()
09-02 11:35:59.892  4182  4182 D BluetoothMapAppObserver: removeReceiver()
09-02 11:35:59.893  3962  3962 D BluetoothA2dp: Proxy object disconnected
09-02 11:35:59.893  3962  3962 D HeadsetProfile: Bluetooth service disconnected
09-02 11:35:59.893  3962  3962 D BluetoothInputDevice: Proxy object disconnected
,09-02 11:35:59.893  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 11:35:59.893  3962  3962 D HidProfile: Bluetooth service disconnected
09-02 11:35:59.893  1354  1354 D PanProfile: Bluetooth service disconnected
09-02 11:35:59.893  4182  4182 V BluetoothAdapterState: isTurningOff()=true
09-02 11:35:59.893  3962  3962 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-02 11:35:59.893  4182  4182 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:59.893  1354  1354 D BluetoothMap: Proxy object disconnected
,09-02 11:35:59.893  3962  3962 D PanProfile: Bluetooth service disconnected
09-02 11:35:59.893  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:59.893  1354  1354 D MapProfile: Bluetooth service disconnected
09-02 11:35:59.893  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:59.894  4182  4182 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-02 11:35:59.894  4182  4182 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-02 11:35:59.894  4182  4198 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-02 11:35:59.894  4182  4182 V BluetoothAdapterState: isTurningOff()=true
09-02 11:35:59.894  4182  4182 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:59.894  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:59.894  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 11:35:59.894  4182  4182 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-02 11:35:59.894  4182  4198 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-02 11:35:59.895  4182  4182 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-02 11:35:59.896  1354  1354 D BluetoothPbap: Proxy object disconnected
09-02 11:35:59.896  1354  1354 D PbapServerProfile: Bluetooth service disconnected
09-02 11:35:59.896  4182  4182 V BluetoothAdapterState: isTurningOff()=true
,09-02 11:35:59.896  4182  4182 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:59.896  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:59.897  3962  3962 D BluetoothMap: Proxy object disconnected
09-02 11:35:59.897  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:59.897  3962  3962 D MapProfile: Bluetooth service disconnected
09-02 11:35:59.897  4182  4182 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-02 11:35:59.897  3962  3962 D BluetoothPbap: Proxy object disconnected
09-02 11:35:59.897  3962  3962 D PbapServerProfile: Bluetooth service disconnected
,09-02 11:35:59.897  4182  4182 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-02 11:35:59.899  4182  4182 D BluetoothMapService: MAP Service closeService in
,09-02 11:35:59.900  4182  4182 V BluetoothAdapterState: isTurningOff()=true
09-02 11:35:59.900  4182  4182 V BluetoothAdapterState: isTurningOn()=false
09-02 11:35:59.900  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:35:59.900  4182  4182 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:35:59.900  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-02 11:35:59.900  4182  4194 D BluetoothAdapterProperties: Setting state to 15
09-02 11:35:59.901  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-02 11:35:59.901  4182  4182 D BluetoothMapService: cleanup()
09-02 11:35:59.901  4182  4194 I BluetoothAdapterState: Entering BleOnState
09-02 11:35:59.901  4182  4182 D BluetoothMapService: MAP Service closeService in
09-02 11:35:59.901  3962  3972 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 11:35:59.902  3962  4233 D BluetoothPan: onBluetoothStateChange on: false
09-02 11:35:59.903  3962  3974 D BluetoothMap: onBluetoothStateChange: up=false
09-02 11:35:59.904   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 11:35:59.904  3962  3972 D BluetoothPbap: onBluetoothStateChange: up=false
09-02 11:35:59.905  1981  2270 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:35:59.905  1354  1367 D BluetoothPbap: onBluetoothStateChange: up=false
,09-02 11:35:59.908  3962  4233 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 11:35:59.908   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:35:59.908   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
09-02 11:35:59.909  1354  2068 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-02 11:35:59.909  1354  1368 D BluetoothMap: onBluetoothStateChange: up=false
09-02 11:35:59.909  1354  1367 D BluetoothPan: onBluetoothStateChange on: false
,09-02 11:35:59.910  1354  2068 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-02 11:35:59.910   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:35:59.910  3962  3974 D BluetoothHeadset: onBluetoothStateChange: up=false
09-02 11:35:59.911  1354  1368 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-02 11:35:59.912  4182  4194 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-02 11:35:59.912  4182  4194 D BluetoothAdapterProperties: Setting state to 16
09-02 11:35:59.912  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-02 11:35:59.913  4182  4194 D BluetoothAdapterProperties: onBleDisable
,09-02 11:35:59.914  4182  4194 I BluetoothAdapterState: Entering PendingCommandState
,09-02 11:35:59.914  4182  4195 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-02 11:35:59.915  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:59.915  4182  4204 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-02 11:35:59.915  4182  4204 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-02 11:35:59.916  4182  4198 D BluetoothAdapterProperties: Scan Mode:20
09-02 11:35:59.917  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:59.918  3962  3962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 11:35:59.920  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:59.922  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:35:59.922  1557  1557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 11:35:59.927  3962  3962 D DockEventReceiver: finishStartingService: stopping service
,09-02 11:36:00.115  4182  4198 I bt_hci  : shut_down
,09-02 11:36:00.116  4182  4202 D bt_hwcfg: hw_epilog_process
,09-02 11:36:00.126  4182  4202 I bt_vendor: low_power_mode_cb
,09-02 11:36:00.149  4182  4202 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-02 11:36:00.149  4182  4202 I bt_vendor: epilog_cb
,09-02 11:36:00.149  4182  4202 I bt_hci  : epilog_finished_callback
,09-02 11:36:00.157  4182  4198 I bt_hci_h4: hal_close
,09-02 11:36:00.159  4182  4198 I bt_userial_vendor: device fd = 51 close
,09-02 11:36:00.290  4182  4195 D bt_stack_manager: event_shut_down_stack finished.
,09-02 11:36:00.290  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-02 11:36:00.296  4182  4194 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-02 11:36:00.297  4182  4182 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 11:36:00.298  4182  4182 D BtGatt.GattService: Received stop request...Stopping profile...
,09-02 11:36:00.299  4182  4182 D BtGatt.GattService: stop()
,09-02 11:36:00.299  4182  4182 D BtGatt.AdvertiseManager: advertise clients cleared
,09-02 11:36:00.306  4182  4182 V BluetoothAdapterState: isTurningOff()=false
,09-02 11:36:00.306  4182  4182 V BluetoothAdapterState: isTurningOn()=false
,09-02 11:36:00.307  4182  4182 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 11:36:00.308  4182  4182 V BluetoothAdapterState: isBleTurningOff()=true
09-02 11:36:00.308  4182  4194 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-02 11:36:00.309  4182  4194 D BluetoothAdapterProperties: Setting state to 10
09-02 11:36:00.310  4182  4194 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-02 11:36:00.311  4182  4194 I BluetoothAdapterState: Entering OffState
,09-02 11:36:00.313   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-02 11:36:00.333  4182  4182 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-02 11:36:00.333  4182  4182 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-02 11:36:00.334  4182  4182 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-02 11:36:00.335  4182  4195 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-02 11:36:00.339  4182  4195 D bt_stack_manager: event_clean_up_stack finished.
,09-02 11:36:00.341  4182  4182 I art     : System.exit called, status: 0
,09-02 11:36:00.341  4182  4182 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-02 11:36:00.395   872  1399 I ActivityManager: Process com.android.bluetooth (pid 4182) has died
,09-02 11:36:02.837  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
,09-02 11:36:02.838  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:05.845  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 11:36:05.846  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e492774 added. We now have 6 listener(s)
,09-02 11:36:05.846  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 11:36:05.851  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 11:36:05.852  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6e3549d added. We now have 7 listener(s)
09-02 11:36:05.852  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 11:36:05.853  3881  3939 I System.out: IsBluetoothEnabled
,09-02 11:36:05.865  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:05.926   872   889 I ActivityManager: Start proc 4243:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-02 11:36:06.059  4243  4243 D AdapterServiceConfig: Adding HeadsetService
,09-02 11:36:06.060  4243  4243 D AdapterServiceConfig: Adding A2dpService
09-02 11:36:06.060  4243  4243 D AdapterServiceConfig: Adding HidService
09-02 11:36:06.060  4243  4243 D AdapterServiceConfig: Adding HealthService
09-02 11:36:06.060  4243  4243 D AdapterServiceConfig: Adding PanService
09-02 11:36:06.060  4243  4243 D AdapterServiceConfig: Adding GattService
09-02 11:36:06.060  4243  4243 D AdapterServiceConfig: Adding BluetoothMapService
,09-02 11:36:06.073  4243  4243 D BluetoothAdapterState: make() - Creating AdapterState
,09-02 11:36:06.073   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@93066c8:true
,09-02 11:36:06.078  4243  4243 I bt_bluedroid: init
,09-02 11:36:06.078  4243  4255 I BluetoothAdapterState: Entering OffState
,09-02 11:36:06.080  4243  4256 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-02 11:36:06.080  4243  4256 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-02 11:36:06.080  4243  4256 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-02 11:36:06.080  4243  4256 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-02 11:36:06.082  4243  4243 I bt_bluedroid: get_profile_interface socket
,09-02 11:36:06.083  4243  4243 I bt_bluedroid: get_profile_interface sdp
,09-02 11:36:06.087  4243  4259 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 11:36:06.088  4243  4254 I bt_bluedroid: config_hci_snoop_log
,09-02 11:36:06.089  4243  4259 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 11:36:06.093   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-02 11:36:06.103  4243  4255 D BluetoothAdapterState: Current state: OFF, message: 0
,09-02 11:36:06.104  4243  4255 D BluetoothAdapterProperties: Setting state to 14
09-02 11:36:06.104  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-02 11:36:06.108  4243  4255 D BluetoothBondStateMachine: make
,09-02 11:36:06.113  4243  4260 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-02 11:36:06.120  4243  4255 I BluetoothAdapterState: Entering PendingCommandState
,09-02 11:36:06.122  4243  4243 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-02 11:36:06.127  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:36:06.128  4243  4243 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-02 11:36:06.129  4243  4243 D BtGatt.GattService: Received start request. Starting profile...
,09-02 11:36:06.129  4243  4243 D BtGatt.GattService: start()
09-02 11:36:06.130  4243  4243 I bt_bluedroid: get_profile_interface gatt
,09-02 11:36:06.131  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
09-02 11:36:06.131  4243  4243 D BtGatt.AdvertiseManager: advertise manager created
,09-02 11:36:06.143  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,09-02 11:36:06.143  4243  4243 V BluetoothAdapterState: isTurningOn()=false
09-02 11:36:06.143  4243  4243 V BluetoothAdapterState: isBleTurningOn()=true
,09-02 11:36:06.143  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
09-02 11:36:06.144  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-02 11:36:06.144  4243  4255 I bt_bluedroid: enable
,09-02 11:36:06.146  4243  4256 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-02 11:36:06.149  4243  4256 I bt_hci  : start_up
,09-02 11:36:06.169  4243  4256 I bt_vendor: alloc value 0xb39bd189
,09-02 11:36:06.169  4243  4256 I bt_vendor: init
09-02 11:36:06.170  4243  4256 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-02 11:36:06.170  4243  4256 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-02 11:36:06.275  4243  4256 D bt_hci  : start_up starting async portion
,09-02 11:36:06.276  4243  4263 I bt_hci  : event_finish_startup
09-02 11:36:06.276  4243  4263 I bt_hci_h4: hal_open
09-02 11:36:06.277  4243  4263 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-02 11:36:06.285  4243  4263 I bt_userial_vendor: device fd = 51 open
,09-02 11:36:06.319  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 11:36:06.351  4243  4263 D bt_hwcfg: Chipset BCM4354A2
,09-02 11:36:06.351  4243  4263 D bt_hwcfg: Target name = [BCM4354A2]
,09-02 11:36:06.352  4243  4263 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-02 11:36:07.013  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-02 11:36:07.015  4243  4263 D bt_hwcfg: Settlement delay -- 100 ms
09-02 11:36:07.015  4243  4263 I bt_hwcfg: Setting fw settlement delay to 100 
,09-02 11:36:07.132  4243  4263 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-02 11:36:07.133  4243  4263 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-02 11:36:07.163  4243  4263 I bt_hwcfg: vendor lib fwcfg completed
,09-02 11:36:07.163  4243  4263 I bt_vendor: firmware callback
09-02 11:36:07.163  4243  4263 I bt_hci  : firmware_config_callback
,09-02 11:36:07.174  4243  4265 I bt_btu  : btu_task pending for preload complete event
09-02 11:36:07.175  4243  4265 I bt_btu_task: Bluetooth chip preload is complete
09-02 11:36:07.175  4243  4265 I bt_btu  : btu_task received preload complete event
,09-02 11:36:07.185  4243  4265 I         : BTE_InitTraceLevels -- TRC_HCI
09-02 11:36:07.185  4243  4265 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-02 11:36:07.186  4243  4265 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-02 11:36:07.186  4243  4265 I         : BTE_InitTraceLevels -- TRC_AVDT
09-02 11:36:07.186  4243  4265 I         : BTE_InitTraceLevels -- TRC_AVRC
09-02 11:36:07.187  4243  4265 I         : BTE_InitTraceLevels -- TRC_A2D
,09-02 11:36:07.187  4243  4265 I         : BTE_InitTraceLevels -- TRC_BNEP
09-02 11:36:07.187  4243  4265 I         : BTE_InitTraceLevels -- TRC_BTM
,09-02 11:36:07.187  4243  4265 I         : BTE_InitTraceLevels -- TRC_GAP
09-02 11:36:07.188  4243  4265 I         : BTE_InitTraceLevels -- TRC_PAN
09-02 11:36:07.188  4243  4265 I         : BTE_InitTraceLevels -- TRC_SDP
,09-02 11:36:07.188  4243  4265 I         : BTE_InitTraceLevels -- TRC_GATT
09-02 11:36:07.188  4243  4265 I         : BTE_InitTraceLevels -- TRC_SMP
09-02 11:36:07.189  4243  4265 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-02 11:36:07.189  4243  4265 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-02 11:36:07.323  4243  4265 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb393ad9d
,09-02 11:36:07.323  4243  4265 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb393ad9d 
,09-02 11:36:07.335  4243  4259 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-02 11:36:07.336  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-02 11:36:07.337  4243  4259 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-02 11:36:07.340  4243  4259 D BluetoothAdapterProperties: Name is: Nexus 6
,09-02 11:36:07.343  4243  4259 D BluetoothAdapterProperties: Scan Mode:20
,09-02 11:36:07.344  4243  4259 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-02 11:36:07.345  4243  4259 D bt_hci  : do_postload posting postload work item
,09-02 11:36:07.345  4243  4263 I bt_hci  : event_postload
09-02 11:36:07.346  4243  4263 I bt_vendor: sco_config_cb
09-02 11:36:07.346  4243  4263 I bt_hci  : sco_config_callback postload finished.
09-02 11:36:07.348  4243  4259 D bt_bte_conf: Device ID record 1 : primary
09-02 11:36:07.349  4243  4259 D bt_bte_conf:   vendorId            = 000f
09-02 11:36:07.349  4243  4259 D bt_bte_conf:   vendorIdSource      = 0001
,09-02 11:36:07.349  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:07.349  4243  4259 D bt_bte_conf:   product             = 1200
09-02 11:36:07.349  4243  4259 D bt_bte_conf:   version             = 1436
,09-02 11:36:07.349  4243  4259 D bt_bte_conf:   clientExecutableURL = 
09-02 11:36:07.350  4243  4259 D bt_bte_conf:   serviceDescription  = 
09-02 11:36:07.350  4243  4259 D bt_bte_conf:   documentationURL    = 
09-02 11:36:07.351  4243  4259 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-02 11:36:07.351  4243  4256 D bt_stack_manager: event_start_up_stack finished
09-02 11:36:07.353  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-02 11:36:07.354  4243  4255 D BluetoothAdapterProperties: Setting state to 15
09-02 11:36:07.354  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-02 11:36:07.356  4243  4255 I BluetoothAdapterState: Entering BleOnState
09-02 11:36:07.358  4243  4263 I bt_vendor: low_power_mode_cb
,09-02 11:36:07.361  4243  4255 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-02 11:36:07.361  4243  4255 D BluetoothAdapterProperties: Setting state to 11
,09-02 11:36:07.361  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-02 11:36:07.368  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:07.371  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:36:07.373  4243  4243 D HeadsetService: Received start request. Starting profile...
,09-02 11:36:07.377  4243  4243 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-02 11:36:07.377  4243  4243 D HeadsetStateMachine: make
,09-02 11:36:07.391  4243  4243 D HeadsetStateMachine: max_hf_connections = 1
,09-02 11:36:07.391  4243  4243 I bt_bluedroid: get_profile_interface handsfree
09-02 11:36:07.392  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-02 11:36:07.392  4243  4259 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-02 11:36:07.394  4243  4255 I BluetoothAdapterState: Entering PendingCommandState
,09-02 11:36:07.399  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:36:07.400  4243  4243 D A2dpService: Received start request. Starting profile...
,09-02 11:36:07.401  4243  4243 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-02 11:36:07.402  4243  4243 I bt_bluedroid: get_profile_interface avrcp
,09-02 11:36:07.410  4243  4243 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-02 11:36:07.411  4243  4243 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-02 11:36:07.411  4243  4243 D A2dpStateMachine: make
,09-02 11:36:07.413  4243  4243 I bt_bluedroid: get_profile_interface a2dp
,09-02 11:36:07.413  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-02 11:36:07.417  4243  4274 D A2dpStateMachine: Enter Disconnected: -2
,09-02 11:36:07.417  4243  4243 I BluetoothHidServiceJni: classInitNative: succeeds
09-02 11:36:07.418  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:36:07.419  4243  4243 D HidService: Received start request. Starting profile...
,09-02 11:36:07.419  4243  4243 I bt_bluedroid: get_profile_interface hidhost
09-02 11:36:07.419  4243  4259 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb391c3e5
09-02 11:36:07.419  4243  4259 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-02 11:36:07.420  4243  4243 D HidService: setHidService(): set to: null
,09-02 11:36:07.421  1557  1557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 11:36:07.421  4243  4243 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-02 11:36:07.422  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
09-02 11:36:07.422  4243  4243 D HealthService: Received start request. Starting profile...
,09-02 11:36:07.424  4243  4243 I bt_bluedroid: get_profile_interface health
,09-02 11:36:07.425  4243  4243 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-02 11:36:07.426  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:36:07.427  4243  4243 D PanService: Received start request. Starting profile...
,09-02 11:36:07.427  4243  4243 D BluetoothPanServiceJni: initializeNative(L110): pan
09-02 11:36:07.427  4243  4243 I bt_bluedroid: get_profile_interface pan
,09-02 11:36:07.428  4243  4259 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-02 11:36:07.430  4243  4243 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:36:07.430  4243  4243 D BluetoothMapService: Received start request. Starting profile...
09-02 11:36:07.430  4243  4243 D BluetoothMapService: start()
,09-02 11:36:07.434  4243  4243 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-02 11:36:07.434  4243  4243 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-02 11:36:07.434  4243  4243 D BluetoothMapAppObserver: createReceiver()
,09-02 11:36:07.436  4243  4243 D BluetoothMapAppObserver: initObservers()
09-02 11:36:07.436  4243  4243 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-02 11:36:07.443  4243  4272 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,09-02 11:36:07.444  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,09-02 11:36:07.444  4243  4243 V BluetoothAdapterState: isTurningOn()=true
,09-02 11:36:07.445  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:36:07.445  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 11:36:07.447  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,09-02 11:36:07.447  4243  4243 V BluetoothAdapterState: isTurningOn()=true
,09-02 11:36:07.447  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 11:36:07.447  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 11:36:07.448  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,09-02 11:36:07.448  4243  4243 V BluetoothAdapterState: isTurningOn()=true
,09-02 11:36:07.448  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:36:07.448  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false,
09-02 11:36:07.448  4243  4243 V BluetoothAdapterState: isTurningOff()=false
,09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isTurningOn()=true
,09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false,
09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isTurningOff()=false
09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isTurningOn()=true
,09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isTurningOff()=false
09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isTurningOn()=true
,09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isBleTurningOn()=false
,09-02 11:36:07.449  4243  4243 V BluetoothAdapterState: isBleTurningOff()=false
,09-02 11:36:07.450  4243  4255 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-02 11:36:07.450  4243  4255 D BluetoothAdapterProperties: ScanMode =  20
,09-02 11:36:07.450  4243  4255 D BluetoothAdapterProperties: State =  11
,09-02 11:36:07.450  4243  4255 D BluetoothAdapterProperties: Setting state to 12
,09-02 11:36:07.450  4243  4255 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-02 11:36:07.451  4243  4255 I BluetoothAdapterState: Entering OnState
,09-02 11:36:07.451  3962  3974 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 11:36:07.453  4243  4259 D BluetoothAdapterProperties: Scan Mode:21
09-02 11:36:07.453  4243  4259 D BluetoothAdapterProperties: Discoverable Timeout:120
09-02 11:36:07.456  3962  3972 D BluetoothPan: onBluetoothStateChange on: true
,09-02 11:36:07.456  3962  3962 D BluetoothA2dp: Proxy object connected
09-02 11:36:07.458  3962  3974 D BluetoothMap: onBluetoothStateChange: up=true
09-02 11:36:07.459  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:07.459  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:07.459  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:36:07.459  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:07.459  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:07.459  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:07.459  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:07.459  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:36:07.460   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:36:07.460  3962  3972 D BluetoothPbap: onBluetoothStateChange: up=true
09-02 11:36:07.462  1981  2270 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:36:07.463  1354  1367 D BluetoothPbap: onBluetoothStateChange: up=true
,09-02 11:36:07.463  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-02 11:36:07.464  4243  4243 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-02 11:36:07.464  3962  3974 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-02 11:36:07.464  4243  4243 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-02 11:36:07.465   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 11:36:07.466   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 11:36:07.466   872   872 D BluetoothA2dp: Proxy object connected
09-02 11:36:07.466  1354  2068 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:36:07.466  4243  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:36:07.467  1354  1368 D BluetoothMap: onBluetoothStateChange: up=true
09-02 11:36:07.469  1354  1354 D BluetoothMap: Proxy object connected
09-02 11:36:07.469  1354  1354 D MapProfile: Bluetooth service connected
,09-02 11:36:07.469  1354  1354 D BluetoothMap: getConnectedDevices()
09-02 11:36:07.469  3962  3962 D BluetoothPan: BluetoothPAN Proxy object connected
,09-02 11:36:07.469  3962  3962 D PanProfile: Bluetooth service connected
09-02 11:36:07.469  3962  3962 D BluetoothMap: Proxy object connected
09-02 11:36:07.469  3962  3962 D MapProfile: Bluetooth service connected
,09-02 11:36:07.469  3962  3962 D BluetoothMap: getConnectedDevices()
09-02 11:36:07.470  4243  4243 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-02 11:36:07.471  4243  4243 D ObexServerSockets: Succeed to create listening sockets 
09-02 11:36:07.471  4243  4243 D ObexServerSockets0: startAccept()
09-02 11:36:07.472  4243  4243 D ObexServerSockets0: prepareForNewConnect()
09-02 11:36:07.478  4243  4280 D ObexServerSockets0: Accepting socket connection...
,09-02 11:36:07.471  1354  2068 D BluetoothPan: onBluetoothStateChange on: true
09-02 11:36:07.476  4243  4243 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-02 11:36:07.480  4243  4243 D BluetoothSdpJni: SDP Create record success - handle: 0
09-02 11:36:07.481  4243  4281 D ObexServerSockets0: Accepting socket connection...
09-02 11:36:07.483  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
09-02 11:36:07.483  1354  1368 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-02 11:36:07.483  1354  1354 D PanProfile: Bluetooth service connected
09-02 11:36:07.484   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-02 11:36:07.484  3962  3972 D BluetoothHeadset: onBluetoothStateChange: up=true
09-02 11:36:07.484  1354  1354 D BluetoothInputDevice: Proxy object connected
09-02 11:36:07.485  1354  1354 D HidProfile: Bluetooth service connected
09-02 11:36:07.485  3962  3962 D BluetoothInputDevice: Proxy object connected
09-02 11:36:07.485  3962  3962 D HidProfile: Bluetooth service connected
09-02 11:36:07.485  1354  1368 D BluetoothA2dp: onBluetoothStateChange: up=true
09-02 11:36:07.489   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
09-02 11:36:07.490  1354  1354 D BluetoothA2dp: Proxy object connected
09-02 11:36:07.491  4243  4243 D BluetoothMapService: onReceive
09-02 11:36:07.491  4243  4243 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-02 11:36:07.491  4243  4243 D BluetoothMapService: STATE_ON
,09-02 11:36:07.502  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:07.507  3962  3962 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-02 11:36:07.511  4243  4243 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-02 11:36:07.511  4243  4243 D ObexServerSockets0: prepareForNewConnect()
09-02 11:36:07.518  1557  1557 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-02 11:36:07.522  1354  1354 D BluetoothPbap: Proxy object connected
,09-02 11:36:07.522  1354  1354 D PbapServerProfile: Bluetooth service connected
,09-02 11:36:07.524  4243  4286 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 11:36:07.529  3962  3962 D DockEventReceiver: finishStartingService: stopping service
,09-02 11:36:07.530  3962  3962 D BluetoothPbap: Proxy object connected
09-02 11:36:07.530  3962  3962 D PbapServerProfile: Bluetooth service connected
,09-02 11:36:07.545  4243  4292 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-02 11:36:07.546  4243  4292 I BtOppRfcommListener: Accept thread started.
,09-02 11:36:07.561  1354  4282 D BluetoothHeadset: Proxy object connected
,09-02 11:36:07.561  1354  1354 D HeadsetProfile: Bluetooth service connected
09-02 11:36:07.561   872   872 D BluetoothHeadset: Proxy object connected
09-02 11:36:07.561   872   872 D BluetoothHeadset: Proxy object connected
09-02 11:36:07.561  3962  3974 D BluetoothHeadset: Proxy object connected
09-02 11:36:07.562   872   872 D BluetoothHeadset: Proxy object connected
09-02 11:36:07.562  3962  3962 D HeadsetProfile: Bluetooth service connected
,09-02 11:36:07.562  1981  2009 D BluetoothHeadset: Proxy object connected
09-02 11:36:07.562  1981  2202 D BluetoothHeadset: Proxy object connected
,09-02 11:36:07.566   872   889 D BluetoothHeadset: Proxy object connected
,09-02 11:36:07.567  1354  1368 D BluetoothHeadset: Proxy object connected
,09-02 11:36:07.567  1354  1354 D HeadsetProfile: Bluetooth service connected
,09-02 11:36:07.583   872   889 D BluetoothHeadset: Proxy object connected
,09-02 11:36:07.585  3962  4233 D BluetoothHeadset: Proxy object connected
,09-02 11:36:07.585  3962  3962 D HeadsetProfile: Bluetooth service connected
,09-02 11:36:07.887  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:07.887  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:07.887  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:36:07.887  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-02 11:36:07.887  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:07.887  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:07.887  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:07.887  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:36:07.894  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-02 11:36:07.897  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 11:36:07.897  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1010d12 added. We now have 8 listener(s)
,09-02 11:36:07.898  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 11:36:07.903   872  2010 D WifiService: setWifiEnabled: false pid=3881, uid=10000
09-02 11:36:07.904   872  2010 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 11:36:07.915  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:07.917   872  1999 D WifiService: setWifiEnabled: true pid=3881, uid=10000
,09-02 11:36:07.918   872  1999 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-02 11:36:07.937   872  1310 D WifiConfigStore: Loading config and enabling all networks 
,09-02 11:36:07.955  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:07.955  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:07.955  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:36:07.955  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:07.955  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:07.955  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:07.955  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:07.955  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:36:07.963  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 11:36:07.970   872  1310 D WifiConfigStore: loaded 0 passpoint configs
,09-02 11:36:07.971   872  1310 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-02 11:36:07.972   872  1310 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-02 11:36:07.973   872  1310 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-02 11:36:07.973   872  1310 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-02 11:36:07.974   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-02 11:36:07.974   872  1310 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-02 11:36:07.994   371   868 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-02 11:36:07.995   872  1310 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.26 rxSuccessRate=0.31 delta 1000 -> 1000
,09-02 11:36:07.996   371   868 D CommandListener: Setting iface cfg
,09-02 11:36:07.997   872  1309 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-02 11:36:07.997   872  1309 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-02 11:36:08.001   872  1309 D WifiNative-HAL: p2pGetDeviceAddress
,09-02 11:36:08.006   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-02 11:36:08.007   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-02 11:36:08.007   872  1309 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-02 11:36:08.015   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-02 11:36:08.088   872  1310 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-02 11:36:08.090  1473  1473 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-02 11:36:08.533  1473  1473 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-02 11:36:08.613  1473  1473 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-02 11:36:08.615  1473  1473 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-02 11:36:08.622   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 11:36:08.640   872  1310 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 11:36:08.641   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-02 11:36:08.640   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 11:36:08.663   872  1310 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-02 11:36:08.677   371   868 D CommandListener: Setting iface cfg
,09-02 11:36:08.679   872  1310 D WifiStateMachine: Start Dhcp Watchdog 3
,09-02 11:36:08.704   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-02 11:36:08.705   872  1312 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-02 11:36:08.710   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-02 11:36:08.745   872  4301 D DhcpClient: Receive thread started
,09-02 11:36:08.830   872  1310 E native  : do suspend false
,09-02 11:36:08.851   872  1905 D DhcpClient: Broadcasting DHCPDISCOVER
,09-02 11:36:08.857   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-02 11:36:08.867  1879  1879 I Keyboard.Facilitator: onFinishInput()
,09-02 11:36:08.868   872  4301 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,09-02 11:36:08.869   872  1905 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,09-02 11:36:08.874   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-02 11:36:08.874   872   892 I Adreno  : Build Date                       : 10/20/15
09-02 11:36:08.874   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-02 11:36:08.874   872   892 I Adreno  : Local Branch                     : M14
09-02 11:36:08.874   872   892 I Adreno  : Remote Branch                    : 
09-02 11:36:08.874   872   892 I Adreno  : Remote Branch                    : 
09-02 11:36:08.874   872   892 I Adreno  : Reconstruct Branch               : 
,09-02 11:36:08.881   872  1905 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-02 11:36:08.896   872  4301 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-02 11:36:08.898   872  1905 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-02 11:36:08.903   371   868 D CommandListener: Setting iface cfg
,09-02 11:36:08.912   281   870 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (3273 us)
,09-02 11:36:08.913   872  1905 D DhcpClient: Scheduling renewal in 86399s
09-02 11:36:08.914   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-02 11:36:08.927   872  1310 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-02 11:36:08.930   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-02 11:36:08.932   872  1312 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-02 11:36:08.934   872  1312 D ConnectivityService: Adding iface wlan0 to network 102
,09-02 11:36:08.943  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:08.943  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:08.943  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:36:08.943  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:08.943  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:08.943  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-02 11:36:08.943  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-02 11:36:08.943  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-02 11:36:08.943   872  1310 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-02 11:36:08.947  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-02 11:36:08.950  3881  3939 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-02 11:36:08.951  3881  3939 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-02 11:36:08.953  3881  3939 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@25ff5fa Bundle[{}]
,09-02 11:36:08.953  3881  3939 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-02 11:36:08.953  3881  3939 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-02 11:36:08.954  3881  3939 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-02 11:36:08.954  3881  3939 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-02 11:36:08.955  3881  3939 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-02 11:36:08.956  3881  3939 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 11:36:08.962  3881  3939 I System.out: Running OutgoingSocketThread
,09-02 11:36:08.963  3881  4306 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
,09-02 11:36:08.964  3881  4306 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47458
09-02 11:36:08.964  3881  4306 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-02 11:36:08.974   872  1312 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-02 11:36:08.975   872  1312 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-02 11:36:08.976   872  1312 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-02 11:36:08.977   872  1312 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-02 11:36:08.978   872  1312 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-02 11:36:08.985   872  1312 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-02 11:36:08.990   872  1312 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-02 11:36:08.990   872  1312 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-02 11:36:08.990   872  1312 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-02 11:36:08.990   872  1310 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-02 11:36:08.990   872  1312 D ConnectivityService:    accepting network in place of null
09-02 11:36:08.991   872  1310 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-02 11:36:08.991   872  1312 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-02 11:36:09.018   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 11:36:09.043   371   868 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-02 11:36:09.046   872  1312 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
09-02 11:36:09.047   872  1312 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:36:09.051   872   889 D Tethering: MasterInitialState.processMessage what=3
,09-02 11:36:09.057   872  1312 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-02 11:36:09.061  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-02 11:36:09.061  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:09.061  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:36:09.061  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:09.061  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:09.061  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:36:09.061  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:36:09.061  3881  3881 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:36:09.063  3881  3881 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 11:36:09.074  1748  1748 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-02 11:36:09.077  1748  1748 D SystemUpdateService: onCreate
,09-02 11:36:09.080  1748  1748 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-02 11:36:09.089  1748  4313 I SystemUpdateService: active receiver: enabled
,09-02 11:36:09.095  1748  4313 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-02 11:36:09.098  1748  1748 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-02 11:36:09.100  1748  2464 I iu.UploadsManager: num queued entries: 0
,09-02 11:36:09.107  1748  4313 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-02 11:36:09.107  1748  4313 I SystemUpdateService: now status is 0 (complete)
09-02 11:36:09.107  1748  4313 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-02 11:36:09.107  1748  4313 I SystemUpdateService: file has been verified
,09-02 11:36:09.107  1748  4313 I SystemUpdateService: OTA package size = 12249756
09-02 11:36:09.101  1748  2464 I iu.UploadsManager: num updated entries: 0
09-02 11:36:09.111  1748  1748 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-02 11:36:09.113  1748  1748 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-02 11:36:09.121  4016  4016 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-02 11:36:09.122  1748  4316 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-02 11:36:09.122  1748  4316 W BaseAppContext: Using Auth Proxy for data requests.
,09-02 11:36:09.124  1748  4316 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
09-02 11:36:09.127  4016  4016 D SprintDMHelper: simOperator: 
09-02 11:36:09.128  4016  4016 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-02 11:36:09.129  1748  2464 I iu.SyncManager: NEXT; no task
,09-02 11:36:09.130  1557  1557 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 11:36:09.131  1557  1557 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-02 11:36:09.133  1748  4313 I SystemUpdateService: showing system update notification
,09-02 11:36:09.157  1748  1748 D SystemUpdateService: onDestroy
,09-02 11:36:09.183  1557  2435 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-02 11:36:09.183  1557  2435 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-02 11:36:09.183  1557  2435 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-02 11:36:09.188  1557  2435 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-02 11:36:09.216  1748  4316 E MDM     : [184] SitrepService.a: Error sending sitrep.
,09-02 11:36:09.527  3881  3881 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-02 11:36:09.527  3881  3881 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-02 11:36:09.565  3881  3881 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@25ff5fa Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@d5a3ce3, 16908290=android.view.AbsSavedState$1@d5a3ce3}, android:focusedViewId=100}]}]
,09-02 11:36:09.565   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
09-02 11:36:09.565  3881  3881 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-02 11:36:09.566  3881  3881 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-02 11:36:09.566  3881  3881 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-02 11:36:09.575   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-02 11:36:09.582   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,09-02 11:36:09.584   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,09-02 11:36:09.584   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-02 11:36:09.594   872   881 I art     : Background partial concurrent mark sweep GC freed 30642(1802KB) AllocSpace objects, 3(100KB) LOS objects, 33% free, 29MB/43MB, paused 3.133ms total 103.302ms
,09-02 11:36:09.815   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-02 11:36:09.818   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
09-02 11:36:09.819   872  1335 D SurfaceControl: Excessive delay in setPowerMode(): 237ms
,09-02 11:36:09.827   872   892 I DreamManagerService: Entering dreamland.
,09-02 11:36:09.829   872   892 I PowerManagerService: Dozing...
,09-02 11:36:09.835   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-02 11:36:09.874   375  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-02 11:36:09.875   375  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-02 11:36:09.875   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 11:36:09.879   872  1312 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-02 11:36:09.885   872  1310 E native  : do suspend false
,09-02 11:36:09.892   872  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,09-02 11:36:09.899  1973  4324 D NfcService: Discovery configuration equal, not updating.
,09-02 11:36:09.923   872  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,09-02 11:36:09.927   872  1310 E native  : do suspend true
,09-02 11:36:09.964  3881  3939 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,09-02 11:36:09.965  3881  3939 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
,09-02 11:36:09.973  3881  3939 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,09-02 11:36:09.975  3881  3939 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-02 11:36:09.976  3881  3939 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,09-02 11:36:09.983  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 11:36:09.983  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b46e0 added. We now have 2 listener(s)
,09-02 11:36:09.984  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:36:09.985  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:36:09.985  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:36:09.985  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:09.985  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4259d99 added. We now have 9 listener(s)
,09-02 11:36:09.985  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:09.986  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 11:36:09.989  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:36:10.000  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:10.000  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:10.000  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:36:10.000  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:10.000  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:10.000  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:36:10.000  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:36:10.000  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:36:10.005  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 11:36:10.005  3881  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 11:36:10.006  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:36:10.006  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e9c43f added. We now have 3 listener(s)
,09-02 11:36:10.008  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:10.011  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:10.012  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:36:10.012   375  1319 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
09-02 11:36:10.012   375  1319 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-02 11:36:10.012  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:36:10.012  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 11:36:10.013  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:10.013  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90df10c added. We now have 10 listener(s)
,09-02 11:36:10.013  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:10.014  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:10.014  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 11:36:10.015  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:10.015  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 11:36:10.016  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 11:36:10.016  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:10.017  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:36:10.018  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88b46e0 removed from the list
09-02 11:36:10.019  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.019  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4259d99 removed from the list
09-02 11:36:10.019  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:10.019  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:10.026  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.026  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:10.028  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 11:36:10.029  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 11:36:10.029  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.029  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4259d99 not in the list
09-02 11:36:10.029  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.029  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:10.031  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 11:36:10.031  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:10.031  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.031  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90df10c removed from the list
09-02 11:36:10.031  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:10.031  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 11:36:10.032  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:10.032  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:36:10.032  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e9c43f removed from the list
09-02 11:36:10.033  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:36:10.033  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a97a55 added. We now have 2 listener(s)
09-02 11:36:10.035  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:36:10.035  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 11:36:10.035  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:36:10.035  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:10.035  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2d2c6a added. We now have 9 listener(s)
,09-02 11:36:10.035  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:10.036  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-02 11:36:10.045  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:10.046   872  1312 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-02 11:36:10.052  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:10.052  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:10.052  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:36:10.052  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:10.052  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:10.052  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:36:10.052  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:36:10.052  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:36:10.055  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 11:36:10.055  3881  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:36:10.055  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 11:36:10.055  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92f11f8 added. We now have 3 listener(s)
09-02 11:36:10.058  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:10.062  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:10.063  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:36:10.064  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:36:10.064  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:36:10.064  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:10.064  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5466d1 added. We now have 10 listener(s)
09-02 11:36:10.064  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:10.064  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 11:36:10.064  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:36:10.065  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:36:10.065  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:10.065  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 11:36:10.068  3881  3939 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-02 11:36:10.068  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 11:36:10.072  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 11:36:10.073  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 11:36:10.073  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 11:36:10.076  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 11:36:10.077  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 11:36:10.077  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-02 11:36:10.077  3881  3939 D BluetoothAdapter: STATE_ON
,09-02 11:36:10.080  4243  4279 D BtGatt.GattService: registerClient() - UUID=decf4f7e-7482-45f0-8f0a-0311f1360575
,09-02 11:36:10.081  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=decf4f7e-7482-45f0-8f0a-0311f1360575, clientIf=5
,09-02 11:36:10.082  3881  3891 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-02 11:36:10.083  4243  4271 D BtGatt.GattService: start scan with filters
,09-02 11:36:10.087  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 11:36:10.087  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 11:36:10.087  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 11:36:10.087  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 11:36:10.087  4243  4262 D BtGatt.ScanManager: handling starting scan
,09-02 11:36:10.090  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 11:36:10.090  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 11:36:10.090  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 11:36:10.090  4243  4262 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd538ee
,09-02 11:36:10.092  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 11:36:10.094  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-02 11:36:10.094  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.094  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-02 11:36:10.095  3881  3939 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-02 11:36:10.095  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 11:36:10.095  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-02 11:36:10.095  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.095  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-02 11:36:10.095  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-02 11:36:10.095  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 11:36:10.095  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-02 11:36:10.095  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 11:36:10.096  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-02 11:36:10.096  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 11:36:10.096  3881  3939 D BluetoothAdapter: STATE_ON
,09-02 11:36:10.097  4243  4254 D BtGatt.GattService: stopScan() - queue size =1
09-02 11:36:10.098  4243  4279 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 11:36:10.098  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:10.098  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 11:36:10.098  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 11:36:10.098  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-02 11:36:10.098  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 11:36:10.099  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:36:10.100  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-02 11:36:10.100  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 11:36:10.100  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 11:36:10.100  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 11:36:10.102  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 11:36:10.102  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:36:10.102  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.102  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:36:10.102  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:36:10.102  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
09-02 11:36:10.103  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 11:36:10.104  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 11:36:10.105  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-02 11:36:10.105  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:10.105  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:10.105  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.105  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:10.105  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:36:10.106  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5a97a55 removed from the list
09-02 11:36:10.106  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.106  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2d2c6a removed from the list
,09-02 11:36:10.106  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:10.106  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:10.106  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.106  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:10.107  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:10.107  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 11:36:10.108  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.108  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f2d2c6a not in the list
09-02 11:36:10.108  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 11:36:10.108  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:10.109  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:10.109  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:10.109  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 11:36:10.109  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5466d1 removed from the list
09-02 11:36:10.109  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:10.110  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.110  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:10.110  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:36:10.110  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@92f11f8 removed from the list
,09-02 11:36:10.111  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 11:36:10.111  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe79f0d added. We now have 2 listener(s)
,09-02 11:36:10.113  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:36:10.113  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 11:36:10.114  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 11:36:10.114  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 11:36:10.114  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@922dec2 added. We now have 9 listener(s)
09-02 11:36:10.114  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:10.115  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 11:36:10.115  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 11:36:10.115  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 11:36:10.120  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:36:10.122  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 11:36:10.122  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 11:36:10.124  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:10.124  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:10.124  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:36:10.124  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:10.124  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:10.124  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:36:10.124  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:36:10.124  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:36:10.127  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 11:36:10.128  3881  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
09-02 11:36:10.128  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:36:10.128  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ee2810 added. We now have 3 listener(s)
,09-02 11:36:10.131  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:36:10.131  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:36:10.131  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 11:36:10.132  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:10.132  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 11:36:10.132  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfc1f09 added. We now have 10 listener(s)
,09-02 11:36:10.132  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 11:36:10.132  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.132  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:36:10.132  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:10.133  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:36:10.133  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:36:10.133  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-02 11:36:10.133  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:10.134  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 11:36:10.133  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
09-02 11:36:10.136  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:10.137  3881  3939 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-02 11:36:10.137  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 11:36:10.141  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 11:36:10.142  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-02 11:36:10.142  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-02 11:36:10.142  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 11:36:10.142  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 11:36:10.143  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 11:36:10.146  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-02 11:36:10.146  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-02 11:36:10.146  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 11:36:10.147  3881  3939 D BluetoothAdapter: STATE_ON
,09-02 11:36:10.150  4243  4253 D BtGatt.GattService: registerClient() - UUID=072b27b2-e13f-4faf-b0db-905789989c85
,09-02 11:36:10.150  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=072b27b2-e13f-4faf-b0db-905789989c85, clientIf=5
09-02 11:36:10.151  3881  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 11:36:10.151  4243  4279 D BtGatt.GattService: start scan with filters
,09-02 11:36:10.152  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-02 11:36:10.153  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 11:36:10.154  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-02 11:36:10.154  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 11:36:10.154  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-02 11:36:10.154  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-02 11:36:10.154  4243  4262 D BtGatt.ScanManager: handling starting scan
,09-02 11:36:10.157  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-02 11:36:10.157  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-02 11:36:10.157  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 11:36:10.159  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 11:36:10.161  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 11:36:10.161  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.161  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 11:36:10.164  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 11:36:10.164  3881  3939 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-02 11:36:10.164  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 11:36:10.165  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 11:36:10.165  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-02 11:36:10.165  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:10.165  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.165  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 11:36:10.166  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 11:36:10.166  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe79f0d removed from the list
09-02 11:36:10.166  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.166  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@922dec2 removed from the list
,09-02 11:36:10.166  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:10.166  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:10.166  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-02 11:36:10.166  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 11:36:10.167  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
,09-02 11:36:10.167  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 11:36:10.167  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.167  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 11:36:10.167  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.167  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-02 11:36:10.168  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:10.168  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:10.169  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.169  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@922dec2 not in the list
,09-02 11:36:10.169  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 11:36:10.169  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 11:36:10.169  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 11:36:10.169  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 11:36:10.169  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 11:36:10.170  3881  3939 D BluetoothAdapter: STATE_ON
,09-02 11:36:10.171  4243  4279 D BtGatt.GattService: stopScan() - queue size =1
09-02 11:36:10.172  4243  4271 D BtGatt.GattService: unregisterClient() - clientIf=5
09-02 11:36:10.173  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:10.173  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-02 11:36:10.173  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 11:36:10.173  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 11:36:10.173  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 11:36:10.174  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-02 11:36:10.174  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 11:36:10.174  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 11:36:10.175  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-02 11:36:10.175  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:10.177  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:36:10.177  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:10.178  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 11:36:10.178  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 11:36:10.177  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-02 11:36:10.181  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.181  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-02 11:36:10.181  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfc1f09 removed from the list
09-02 11:36:10.181  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 11:36:10.181  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.181  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:36:10.181  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:10.181  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:36:10.183  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ee2810 removed from the list
09-02 11:36:10.183  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-02 11:36:10.183  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.185  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 11:36:10.185  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebea2c5 added. We now have 2 listener(s)
,09-02 11:36:10.187  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-02 11:36:10.187  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:36:10.187  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:36:10.188  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:10.188  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621841a added. We now have 9 listener(s)
09-02 11:36:10.188  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-02 11:36:10.189  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 11:36:10.190  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-02 11:36:10.191  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.191  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
,09-02 11:36:10.194  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:36:10.198  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-02 11:36:10.198  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.199  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-02 11:36:10.199  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:10.199  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:10.199  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:36:10.199  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:10.199  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:10.199  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:36:10.199  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:36:10.199  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:36:10.202  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-02 11:36:10.202  3881  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 11:36:10.202  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:36:10.202  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d86e928 added. We now have 3 listener(s)
,09-02 11:36:10.205  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-02 11:36:10.205  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.205  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-02 11:36:10.207  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:36:10.207  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:36:10.207  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:36:10.207  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 11:36:10.208  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ba641 added. We now have 10 listener(s)
09-02 11:36:10.208  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:10.208  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-02 11:36:10.208  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-02 11:36:10.208  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-02 11:36:10.208  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-02 11:36:10.208  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-02 11:36:10.209  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:10.211  3881  3939 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-02 11:36:10.211  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-02 11:36:10.215  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-02 11:36:10.216  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-02 11:36:10.216  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-02 11:36:10.219  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-02 11:36:10.219  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-02 11:36:10.219  3881  3939 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-02 11:36:10.220  3881  3939 D BluetoothAdapter: STATE_ON
,09-02 11:36:10.222  4243  4253 D BtGatt.GattService: registerClient() - UUID=7d1e308a-0f12-4b6e-92ca-80c093ff3b9c
,09-02 11:36:10.223  4243  4259 D BtGatt.GattService: onClientRegistered() - UUID=7d1e308a-0f12-4b6e-92ca-80c093ff3b9c, clientIf=5
,09-02 11:36:10.223  3881  3892 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-02 11:36:10.224  4243  4284 D BtGatt.GattService: start scan with filters
,09-02 11:36:10.227  4243  4262 D BtGatt.ScanManager: handling starting scan
,09-02 11:36:10.227  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-02 11:36:10.227  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-02 11:36:10.227  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-02 11:36:10.227  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-02 11:36:10.231  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 11:36:10.231  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-02 11:36:10.231  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-02 11:36:10.234  4243  4259 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-02 11:36:10.234  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.234  4243  4262 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-02 11:36:10.234  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-02 11:36:10.240  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-02 11:36:10.240  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 11:36:10.240  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:10.240  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:10.240  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.240  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-02 11:36:10.240  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-02 11:36:10.240  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ebea2c5 removed from the list
09-02 11:36:10.240  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.240  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621841a removed from the list
09-02 11:36:10.241  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:10.241  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:10.240  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-02 11:36:10.241  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.241  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.241  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-02 11:36:10.241  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.241  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:10.241  4243  4262 D BtGatt.ScanManager: Starting BLE batch scan
09-02 11:36:10.242  4243  4262 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-02 11:36:10.242  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:10.242  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:10.242  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.243  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@621841a not in the list
09-02 11:36:10.243  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-02 11:36:10.243  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-02 11:36:10.243  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-02 11:36:10.243  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-02 11:36:10.243  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-02 11:36:10.244  3881  3939 D BluetoothAdapter: STATE_ON
09-02 11:36:10.244  4243  4254 D BtGatt.GattService: stopScan() - queue size =1
09-02 11:36:10.245  4243  4253 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-02 11:36:10.246  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-02 11:36:10.246  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-02 11:36:10.246  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-02 11:36:10.246  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-02 11:36:10.246  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-02 11:36:10.247  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:36:10.247  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-02 11:36:10.247  3881  3939 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-02 11:36:10.247  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-02 11:36:10.248  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:10.249  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 11:36:10.249  3881  3881 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-02 11:36:10.249  3881  3881 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-02 11:36:10.249  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:10.249  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:10.249  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.249  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ba641 removed from the list
09-02 11:36:10.249  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:10.249  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.250  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:10.250  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 11:36:10.250  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d86e928 removed from the list
,09-02 11:36:10.250  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-02 11:36:10.251  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28b657d added. We now have 2 listener(s)
09-02 11:36:10.252  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:36:10.252  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-02 11:36:10.252  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-02 11:36:10.253  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-02 11:36:10.253  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f47c72 added. We now have 9 listener(s)
09-02 11:36:10.253  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:10.253  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-02 11:36:10.256  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-02 11:36:10.261  3881  3939 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-02 11:36:10.261  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-02 11:36:10.261  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-02 11:36:10.261  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-02 11:36:10.261  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-02 11:36:10.261  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-02 11:36:10.261  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-02 11:36:10.261  3881  3939 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-02 11:36:10.261  4243  4259 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-02 11:36:10.261  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 11:36:10.263  3881  3939 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-02 11:36:10.263  3881  3939 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-02 11:36:10.266  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:10.266  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-02 11:36:10.267  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23b540 added. We now have 3 listener(s)
09-02 11:36:10.268  3881  3881 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-02 11:36:10.269  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-02 11:36:10.269  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-02 11:36:10.270  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-02 11:36:10.270  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-02 11:36:10.270  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-02 11:36:10.270  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-02 11:36:10.270  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@feddc79 added. We now have 10 listener(s)
,09-02 11:36:10.270  3881  3939 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-02 11:36:10.271  3881  3939 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-02 11:36:10.271  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-02 11:36:10.271  3881  3939 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-02 11:36:10.271  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-02 11:36:10.271  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.271  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-02 11:36:10.271  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 11:36:10.272  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28b657d removed from the list
09-02 11:36:10.272  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.272  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f47c72 removed from the list
,09-02 11:36:10.272  3881  3939 D io.jxcore.node.ConnectivityMonitor: stop
09-02 11:36:10.272  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:10.272  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.272  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-02 11:36:10.273  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:10.273  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-02 11:36:10.273  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-02 11:36:10.274  3881  3939 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9f47c72 not in the list
,09-02 11:36:10.274  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-02 11:36:10.274  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:10.274  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-02 11:36:10.275  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-02 11:36:10.275  3881  3939 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-02 11:36:10.275  3881  3939 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@feddc79 removed from the list
09-02 11:36:10.275  3881  3939 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-02 11:36:10.275  3881  3939 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-02 11:36:10.275  3881  3939 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-02 11:36:10.275  3881  3939 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-02 11:36:10.275  3881  3939 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23b540 removed from the list
09-02 11:36:10.276  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-02 11:36:10.276  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-02 11:36:10.277  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-02 11:36:10.277  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-02 11:36:10.277  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-02 11:36:10.277  3881  3939 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-02 11:36:10.279  4243  4259 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-02 11:36:10.279  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.279  4243  4262 D BtGatt.ScanManager: stopping BLe Batch
,09-02 11:36:10.286  3881  4328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
,09-02 11:36:10.286  3881  4328 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
,09-02 11:36:10.286  3881  4328 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 11:36:10.288  4243  4259 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-02 11:36:10.288  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.289  4243  4262 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-02 11:36:10.290  3881  4329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
,09-02 11:36:10.290  3881  4329 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
09-02 11:36:10.290  3881  4329 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-02 11:36:10.292  3881  3939 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-02 11:36:10.293  3881  3939 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-02 11:36:10.293  3881  3939 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-02 11:36:10.293  3881  3939 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-02 11:36:10.293  3881  3939 D com.test.thalitest.ThaliTestRunner: Total duration: 22792 ms
,09-02 11:36:10.295  3881  3939 I jxcore-log: *Native tests were executed*
09-02 11:36:10.295  3881  3939 I jxcore-log: 
,09-02 11:36:10.295  3881  3939 I jxcore-log: Total number of executed tests:  80
09-02 11:36:10.295  3881  3939 I jxcore-log: 
09-02 11:36:10.295  3881  3939 I jxcore-log: Number of passed tests:  80
09-02 11:36:10.295  3881  3939 I jxcore-log: 
,09-02 11:36:10.295  3881  3939 I jxcore-log: Number of failed tests:  0
09-02 11:36:10.295  3881  3939 I jxcore-log: 
09-02 11:36:10.296  3881  3939 I jxcore-log: Number of ignored tests:  0
09-02 11:36:10.296  3881  3939 I jxcore-log: 
,09-02 11:36:10.296  3881  3939 I jxcore-log: Total duration:  22792
,09-02 11:36:10.296  3881  3939 I jxcore-log: 
,09-02 11:36:10.296  3881  3939 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-02 11:36:10.296  3881  3939 I jxcore-log: 
09-02 11:36:10.297  4243  4259 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-02 11:36:10.297  4243  4259 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-02 11:36:10.301  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.301  3881  3939 I jxcore-log: 
09-02 11:36:10.304  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.304  3881  3939 I jxcore-log: 
09-02 11:36:10.305  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.305  3881  3939 I jxcore-log: 
09-02 11:36:10.307  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.307  3881  3939 I jxcore-log: 
09-02 11:36:10.307  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.307  3881  3939 I jxcore-log: 
09-02 11:36:10.308  3881  3881 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-02 11:36:10.309  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.309  3881  3939 I jxcore-log: 
09-02 11:36:10.311  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.311  3881  3939 I jxcore-log: 
09-02 11:36:10.313  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 11:36:10.313  3881  3939 I jxcore-log: 
09-02 11:36:10.314  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 11:36:10.314  3881  3939 I jxcore-log: 
09-02 11:36:10.315  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:36:10.315  3881  3939 I jxcore-log: 
09-02 11:36:10.316  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:36:10.316  3881  3939 I jxcore-log: 
09-02 11:36:10.317  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 11:36:10.317  3881  3939 I jxcore-log: 
09-02 11:36:10.318  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 11:36:10.318  3881  3939 I jxcore-log: 
09-02 11:36:10.318  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-02 11:36:10.318  3881  3939 I jxcore-log: 
09-02 11:36:10.319  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.319  3881  3939 I jxcore-log: 
09-02 11:36:10.319  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.319  3881  3939 I jxcore-log: 
09-02 11:36:10.320  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:36:10.320  3881  3939 I jxcore-log: 
09-02 11:36:10.321  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:36:10.321  3881  3939 I jxcore-log: 
09-02 11:36:10.321  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 11:36:10.321  3881  3939 I jxcore-log: 
09-02 11:36:10.322  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 11:36:10.322  3881  3939 I jxcore-log: 
09-02 11:36:10.322  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:36:10.322  3881  3939 I jxcore-log: 
09-02 11:36:10.323  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-02 11:36:10.323  3881  3939 I jxcore-log: 
09-02 11:36:10.323  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 11:36:10.323  3881  3939 I jxcore-log: 
09-02 11:36:10.324  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-02 11:36:10.324  3881  3939 I jxcore-log: 
09-02 11:36:10.324  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 11:36:10.324  3881  3939 I jxcore-log: 
09-02 11:36:10.325  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-02 11:36:10.325  3881  3939 I jxcore-log: 
09-02 11:36:10.326  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.326  3881  3939 I jxcore-log: 
09-02 11:36:10.327  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.327  3881  3939 I jxcore-log: 
09-02 11:36:10.327  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.327  3881  3939 I jxcore-log: 
09-02 11:36:10.327  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.327  3881  3939 I jxcore-log: 
09-02 11:36:10.328  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.328  3881  3939 I jxcore-log: 
09-02 11:36:10.328  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-02 11:36:10.328  3881  3939 I jxcore-log: 
,09-02 11:36:10.380   872  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,09-02 11:36:10.602  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 11:36:10.605  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 11:36:10.605  3881  3939 I jxcore-log: 
,09-02 11:36:10.682  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 11:36:10.685  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 11:36:10.685  3881  3939 I jxcore-log: 
,09-02 11:36:10.749  3881  3881 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-02 11:36:10.752  3881  3939 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-02 11:36:10.752  3881  3939 I jxcore-log: 
,09-02 11:36:10.950  4330  4330 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-02 11:36:10.955  4330  4330 D AndroidRuntime: CheckJNI is OFF
,09-02 11:36:10.998  4330  4330 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-02 11:36:11.047  4330  4330 I Radio-JNI: register_android_hardware_Radio DONE
,09-02 11:36:11.070  4330  4330 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-02 11:36:11.088   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-02 11:36:11.089   872   885 I ActivityManager: Killing 3881:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-02 11:36:11.180   872   882 D GraphicsStats: Buffer count: 2
,09-02 11:36:11.183   872  1311 D WifiService: Client connection lost with reason: 4
,09-02 11:36:11.181   872  1686 I WindowState: WIN DEATH: Window{d3d4f4e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-02 11:36:11.245   872   895 W PackageSettings: Skipping PackageSetting{c4717c3 com.example.hello/10273} due to missing metadata
,09-02 11:36:11.274   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-02 11:36:11.274   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-02 11:36:11.275   872   885 E ActivityManager: Failure starting process com.test.thalitest
09-02 11:36:11.275   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-02 11:36:11.275   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:36:11.275   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:36:11.275   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 11:36:11.275   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-02 11:36:11.276   872   885 I ActivityManager:   Force finishing activity ActivityRecord{eb3fb97 u0 com.test.thalitest/.MainActivity t2}
,09-02 11:36:11.279   872   895 I art     : Starting a blocking GC Explicit
,09-02 11:36:11.284   872  1399 W ActivityManager: Spurious death for ProcessRecord{fb0aaeb 0:com.test.thalitest/u0a0}, curProc for 3881: null
,09-02 11:36:11.323   872   895 I art     : Explicit concurrent mark sweep GC freed 22251(1353KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 743us total 43.702ms
,09-02 11:36:11.374   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-02 11:36:11.380  4330  4330 I art     : System.exit called, status: 0
,09-02 11:36:11.380  4330  4330 I AndroidRuntime: VM exiting with result code 0.
,09-02 11:36:11.384   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-02 11:36:11.407   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-02 11:36:11.412  4243  4243 D BluetoothMapAppObserver: onReceive
,09-02 11:36:11.413  4243  4243 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-02 11:36:11.416  2146  2297 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-02 11:36:11.416   872  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-02 11:36:11.416  1879  1879 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-02 11:36:11.430  3635  3635 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,09-02 11:36:11.440  1879  4341 I Keyboard.Facilitator.DecoderInitializer: run()
,09-02 11:36:11.447  1879  4341 I Decoder : createOrResetDecoder
,09-02 11:36:11.447  1981  1981 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-02 11:36:11.465   872  1685 I ActivityManager: Start proc 4344:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-02 11:36:11.502  1557  1557 I ConfigService: onCreate
,09-02 11:36:11.505  1557  4356 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-02 11:36:11.505  1557  4356 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-02 11:36:11.505  1557  4356 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-02 11:36:11.507  1557  4356 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-02 11:36:11.518  1879  4341 I Keyboard.Facilitator.MainLanguageModelLoader: run(),
,09-02 11:36:11.524   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-02 11:36:11.530   872  1399 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3881 uid 10000
,09-02 11:36:11.531  1879  1879 I Keyboard.Facilitator: onFinishInput()
,09-02 11:36:11.534  4344  4344 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-02 11:36:11.540   872  1336 W System.err: java.io.IOException: write failed: EBADF (Bad file descriptor)
,09-02 11:36:11.540   872  1336 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-02 11:36:11.540   872  1336 W System.err: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
,09-02 11:36:11.540   872  1336 W System.err: 	at android.graphics.Bitmap.nativeCompress(Native Method)
09-02 11:36:11.541   872  1336 W System.err: 	at android.graphics.Bitmap.compress(Bitmap.java:1027)
09-02 11:36:11.541   872  1336 W System.err: 	at com.android.server.am.TaskPersister$LazyTaskWriterThread.run(TaskPersister.java:557)
09-02 11:36:11.541   872  1336 W System.err: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
09-02 11:36:11.541   872  1336 W System.err: 	at libcore.io.Posix.writeBytes(Native Method)
09-02 11:36:11.541   872  1336 W System.err: 	at libcore.io.Posix.write(Posix.java:271)
09-02 11:36:11.541   872  1336 W System.err: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
,09-02 11:36:11.541   872  1336 W System.err: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-02 11:36:11.541   872  1336 W System.err: 	... 4 more
09-02 11:36:11.541   872  1336 D skia    : ------- write threw an exception
,09-02 11:36:11.564  2002  2073 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-02 11:36:11.565   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-02 11:36:11.565   872   884 E PackageManager: Failed to write settings, restoring backup
09-02 11:36:11.565   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-02 11:36:11.565   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-02 11:36:11.565   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-02 11:36:11.565   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-02 11:36:11.565   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-02 11:36:11.565   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:36:11.565   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:36:11.565   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 11:36:11.569   872   885 E DropBoxManagerService: Can't write: system_server_wtf
09-02 11:36:11.569   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-02 11:36:11.569   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 11:36:11.569   872   885 E DropBoxManagerService: 	... 13 more
09-02 11:36:11.575  1879  4341 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVe,rsion = 20160111
,09-02 11:36:11.578   872  2000 I ActivityManager: Start proc 4361:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-02 11:36:11.579  2002  2073 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-02 11:36:11.579  2002  2073 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2002
09-02 11:36:11.579  2002  2073 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:36:11.579  2002  2073 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 11:36:11.581   872  4370 E DropBoxManagerService: Can't write: system_app_crash
09-02 11:36:11.581   872  4370 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 11:36:11.581   872  4370 E DropBoxManagerService: 	... 5 more
,09-02 11:36:11.581   872  1400 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-02 11:36:11.585  2002  2073 I Process : Sending signal. PID: 2002 SIG: 9
09-02 11:36:11.592  1879  4341 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-02 11:36:11.592  1879  4341 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-02 11:36:11.594  1879  4341 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-02 11:36:11.594  1879  4341 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-02 11:36:11.594  1879  4341 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-02 11:36:11.594  1879  4341 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-02 11:36:11.596  1879  4341 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-02 11:36:11.596  1879  4341 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-02 11:36:11.597  1879  4341 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-02 11:36:11.597  1879  4341 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-02 11:36:11.597  1879  4341 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-02 11:36:11.597  1879  4341 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-02 11:36:11.620  4344  4344 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-02 11:36:11.646   872   883 I ActivityManager: Start proc 4377:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-02 11:36:11.650  4344  4376 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-02 11:36:11.670   872  1685 I WindowState: WIN DEATH: Window{beb2f81 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-02 11:36:11.686   872  2010 D GraphicsStats: Buffer count: 1
,09-02 11:36:11.703   872   882 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2002) has died
09-02 11:36:11.704   872   882 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-02 11:36:11.706   872   882 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-02 11:36:11.715  4377  4377 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-02 11:36:11.717  4344  4376 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	,at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:36:11.717  4344  4376 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-02 11:36:11.718  4344  4376 E AndroidRuntime: Process: android.process.acore, PID: 4344
09-02 11:36:11.718  4344  4376 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:36:11.718  4344  4376 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-02 11:36:11.724   872   885 I ActivityManager: Start proc 4391:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-02 11:36:11.727  4344  4376 I Process : Sending signal. PID: 4344 SIG: 9
,09-02 11:36:11.730   872  4397 E DropBoxManagerService: Can't write: system_app_crash
09-02 11:36:11.730   872  4397 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 11:36:11.730   872  4397 E DropBoxManagerService: 	... 5 more
,09-02 11:36:11.754   279   279 E lowmemorykiller: Error writing /proc/4344/oom_score_adj; errno=22
09-02 11:36:11.756   279   279 E lowmemorykiller: Error writing /proc/4344/oom_score_adj; errno=22
,09-02 11:36:11.760  1557  1557 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-02 11:36:11.760  1557  1557 D AndroidRuntime: Shutting down VM
,09-02 11:36:11.761  1557  1557 E AndroidRuntime: FATAL EXCEPTION: main
09-02 11:36:11.761  1557  1557 E AndroidRuntime: Process: com.google.process.gapps, PID: 1557
09-02 11:36:11.761  1557  1557 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-02 11:36:11.761  1557  1557 E AndroidRuntime: 	... 8 more
,09-02 11:36:11.765  1557  1557 I Process : Sending signal. PID: 1557 SIG: 9
,09-02 11:36:11.765   872  4407 E DropBoxManagerService: Can't write: system_app_crash
09-02 11:36:11.765   872  4407 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 11:36:11.765   872  4407 E DropBoxManagerService: 	... 5 more
,09-02 11:36:11.782  4391  4391 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:36:11.782  4391  4391 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-02 11:36:11.782  4391  4391 D AndroidRuntime: Shutting down VM
,09-02 11:36:11.791  4391  4391 E AndroidRuntime: FATAL EXCEPTION: main
09-02 11:36:11.791  4391  4391 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4391
09-02 11:36:11.791  4391  4391 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-02 11:36:11.791  4391  4391 E AndroidRuntime: 	... 10 more
,09-02 11:36:11.793   872  2010 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-02 11:36:11.793   872  4409 E DropBoxManagerService: Can't write: system_app_crash,
09-02 11:36:11.793   872  4409 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-02 11:36:11.793   872  4409 E DropBoxManagerService: 	... 5 more
,09-02 11:36:11.795  4391  4391 I Process : Sending signal. PID: 4391 SIG: 9
,09-02 11:36:11.805   872   882 I ActivityManager: Process android.process.acore (pid 4344) has died
,09-02 11:36:11.805   872   882 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-02 11:36:11.819   872  1310 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 16 -> obsolete
,09-02 11:36:11.834   872  1311 D WifiService: Client connection lost with reason: 4
,09-02 11:36:11.836  1748  4404 E BulkCursor: Unable to get window because the remote process is dead
,09-02 11:36:11.836  1748  4404 W BulkCursor: Remote process exception when closing
,09-02 11:36:11.838   872  1685 I ActivityManager: Process com.google.process.gapps (pid 1557) has died
,09-02 11:36:11.838   872  1685 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-02 11:36:11.839   872  1685 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 11000ms
09-02 11:36:11.839   872  1685 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-02 11:36:11.839   872  1685 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
,09-02 11:36:11.839   872  1685 I ActivityManager: Killing 1748:com.google.android.gms/u0a11 (adj 5): depends on provider com.google.android.gsf/.gservices.GservicesProvider in dying proc com.google.process.gapps
,09-02 11:36:11.887   872   882 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@45bcf7c)
09-02 11:36:11.887   872  1312 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-02 11:36:11.888   872  1312 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-02 11:36:11.900   872  1687 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4391) has died
,09-02 11:36:11.902   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
