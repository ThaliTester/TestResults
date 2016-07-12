#### Test 72145431744cc2c_thali08_motorola-Nexus 6 Logs


```
--------- beginning of system
07-12 11:37:01.228   872   892 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,--------- beginning of main
07-12 11:37:01.243  1653  1653 I Keyboard.Facilitator: onFinishInput()
07-12 11:37:01.249   872   892 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-12 11:37:01.249   872   892 I Adreno  : Build Date                       : 10/20/15
07-12 11:37:01.249   872   892 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-12 11:37:01.249   872   892 I Adreno  : Local Branch                     : M14
07-12 11:37:01.249   872   892 I Adreno  : Remote Branch                    : 
07-12 11:37:01.249   872   892 I Adreno  : Remote Branch                    : 
07-12 11:37:01.249   872   892 I Adreno  : Reconstruct Branch               : 
07-12 11:37:01.297   281   369 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (546 us)
07-12 11:37:01.871  1804  3277 W SearchService: Abort, client detached.
07-12 11:37:01.879  1804  2104 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@79dc714
07-12 11:37:01.879  1804  1804 I HotwordDetector: Closing mic
07-12 11:37:01.879  1804  2109 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-12 11:37:01.900   872   892 V KeyguardServiceDelegate: onScreenTurnedOff()
07-12 11:37:01.907   872   892 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-12 11:37:01.911   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
07-12 11:37:01.912   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
07-12 11:37:01.911   872   890 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
07-12 11:37:01.911  3291  3291 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 11:37:01.921  3291  3291 D AndroidRuntime: CheckJNI is OFF
07-12 11:37:01.938  1804  1804 W ErrorReporter: reportError [type: 29, code: 917507]: null
07-12 11:37:01.942   374  2111 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-12 11:37:01.943   374  2111 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-12 11:37:01.951   374  1277 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-12 11:37:01.954  1804  2108 I MicroRecognitionRnrImpl: Detection finished
07-12 11:37:01.955  1804  2107 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-12 11:37:01.967  3291  3291 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 11:37:01.972   872  1696 I ActivityManager: Killing 2969:com.qualcomm.telephony/1001 (adj 15): empty #17
07-12 11:37:02.003  3291  3291 I Radio-JNI: register_android_hardware_Radio DONE
07-12 11:37:02.021  3291  3291 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-12 11:37:02.024   872  1726 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-12 11:37:02.139   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
07-12 11:37:02.143   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
07-12 11:37:02.144   872  1330 D SurfaceControl: Excessive delay in setPowerMode(): 233ms
07-12 11:37:02.185   872  1726 I ActivityManager: Start proc 3302:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-12 11:37:02.189  3291  3291 D AndroidRuntime: Shutting down VM
07-12 11:37:02.189   872   892 I DreamManagerService: Entering dreamland.
07-12 11:37:02.189   872   892 I PowerManagerService: Dozing...
07-12 11:37:02.190   872   887 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
07-12 11:37:02.239   374   374 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-12 11:37:02.239   374   374 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
07-12 11:37:02.251   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:37:02.253  1727  3315 D NfcService: Discovery configuration equal, not updating.
07-12 11:37:02.258   872  1304 E native  : do suspend false
07-12 11:37:02.291  3302  3302 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-12 11:37:02.291   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
07-12 11:37:02.295   872  1304 E native  : do suspend true
07-12 11:37:02.343  3302  3302 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-12 11:37:02.371   374  1278 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-12 11:37:02.371   374  1278 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
07-12 11:37:02.394  3302  3302 I LibraryLoader: Time to load native libraries: 45 ms (timestamps 1554-1599)
07-12 11:37:02.395  3302  3302 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:37:02.415  3302  3302 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c5fdd02}
,07-12 11:37:02.415  3302  3302 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:37:02.416  3302  3302 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:37:02.423  3302  3302 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 11:37:02.424  3302  3302 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 11:37:02.463  3302  3322 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,07-12 11:37:02.472  3302  3302 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-12 11:37:02.486  3302  3302 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 11:37:02.487  3302  3302 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:37:02.487  3302  3302 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-12 11:37:02.487  3302  3302 I Adreno  : Build Date                       : 10/20/15
07-12 11:37:02.487  3302  3302 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-12 11:37:02.487  3302  3302 I Adreno  : Local Branch                     : M14
07-12 11:37:02.487  3302  3302 I Adreno  : Remote Branch                    : 
07-12 11:37:02.487  3302  3302 I Adreno  : Remote Branch                    : 
07-12 11:37:02.487  3302  3302 I Adreno  : Reconstruct Branch               : 
,07-12 11:37:02.549   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a597c37:true
,07-12 11:37:02.616  3302  3302 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-12 11:37:02.628  3302  3302 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-12 11:37:02.679  3302  3344 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-12 11:37:02.690  3302  3331 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-12 11:37:02.744  3302  3344 I OpenGLRenderer: Initialized EGL, version 1.4
,07-12 11:37:02.797   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +573ms (total +631ms)
,07-12 11:37:02.805  1653  1653 I Keyboard.Facilitator: onFinishInput()
,07-12 11:37:02.857  3302  3302 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3302
,07-12 11:37:02.972  3302  3302 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-12 11:37:03.189  3302  3347 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1669072592
,07-12 11:37:03.196  3302  3347 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-12 11:37:03.196  3302  3347 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-12 11:37:03.196  3302  3347 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-12 11:37:03.196  3302  3347 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-12 11:37:03.196  3302  3347 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-12 11:37:03.196  3302  3347 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b932741 added. We now have 1 listener(s)
,07-12 11:37:03.199  3302  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
07-12 11:37:03.199  3302  3347 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-12 11:37:03.200  3302  3347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-12 11:37:03.200  3302  3347 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-12 11:37:03.203  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-12 11:37:03.204  3302  3347 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19fa4d4 added. We now have 1 listener(s)
07-12 11:37:03.204  3302  3347 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-12 11:37:03.210   872  1305 D WifiService: New client listening to asynchronous messages
07-12 11:37:03.211  3302  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:03.211  3302  3347 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-12 11:37:03.212  3302  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-12 11:37:03.212  3302  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-12 11:37:03.212  3302  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-12 11:37:03.212  3302  3347 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-12 11:37:03.223  3302  3347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-12 11:37:03.223  3302  3347 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
07-12 11:37:03.229  3302  3347 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:03.230  3302  3347 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:37:03.230  3302  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:03.230  3302  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:37:03.230  3302  3347 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:37:03.230  3302  3347 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:37:03.230  3302  3347 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:37:03.230  3302  3347 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:37:03.230  3302  3347 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:37:03.230  3302  3347 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-12 11:37:03.230  3302  3347 D io.jxcore.node.ConnectivityMonitor: start: OK
07-12 11:37:03.230  3302  3347 I io.jxcore.node.LifeCycleMonitor: start: OK
07-12 11:37:03.231  3302  3302 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 11:37:03.260  3302  3302 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-12 11:37:04.104  3302  3353 W jxcore-log: Initializing JXcore engine
07-12 11:37:04.104  3302  3353 W jxcore-log: JXcore engine is ready
,07-12 11:37:04.141  3353  3353 W Thread-285: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-12 11:37:04.144  3353  3353 W Thread-285: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11675]" dev="sockfs" ino=11675 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-12 11:37:04.144  3353  3353 W Thread-285: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-12 11:37:04.144  3353  3353 W Thread-285: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22231]" dev="sockfs" ino=22231 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-12 11:37:04.157  3302  3353 W jxcore-log: Starting JXcore engine
,07-12 11:37:04.237  3302  3353 W jxcore-log: Platform android
07-12 11:37:04.237  3302  3353 W jxcore-log: 
,07-12 11:37:04.237  3302  3353 W jxcore-log: Process ARCH arm
07-12 11:37:04.237  3302  3353 W jxcore-log: 
,07-12 11:37:04.429  3302  3353 I jxcore-log: JXcore Cordova bridge is ready!
07-12 11:37:04.429  3302  3353 I jxcore-log: 
07-12 11:37:04.429  3302  3353 W jxcore-log: JXcore engine is started
,07-12 11:37:04.437  3302  3347 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-12 11:37:04.443  3302  3302 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-12 11:37:05.909  1841  2301 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:37:12.198  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:12.203  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:12.205  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:12.263  1519  1887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-12 11:37:12.263  1519  1887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-12 11:37:12.263  1519  1887 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:37:12.263  1519  1887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:12.299  2577  2577 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-12 11:37:12.299  2577  2577 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-12 11:37:12.299  2577  2577 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-12 11:37:14.491  3302  3353 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-12 11:37:14.491  3302  3353 I jxcore-log: 
,07-12 11:37:14.493  3302  3353 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-12 11:37:14.493  3302  3353 I jxcore-log: 
,07-12 11:37:14.495  3302  3353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:14.495  3302  3353 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-12 11:37:14.495  3302  3353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:14.495  3302  3353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:37:14.495  3302  3353 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-12 11:37:14.495  3302  3353 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:37:14.495  3302  3353 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:37:14.495  3302  3353 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:37:14.495  3302  3353 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:37:14.495  3302  3353 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-12 11:37:14.495  3302  3353 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:37:14.497  3302  3353 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-12 11:37:14.497  3302  3353 I jxcore-log: 
,07-12 11:37:14.499  3302  3353 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-12 11:37:14.499  3302  3353 I jxcore-log: 
,07-12 11:37:14.826  3302  3353 I jxcore-log: Unit Test app is loaded
07-12 11:37:14.826  3302  3353 I jxcore-log: 
,07-12 11:37:14.832  3302  3353 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-12 11:37:14.832  3302  3353 I jxcore-log: 
,07-12 11:37:14.836   872   882 D WifiService: setWifiEnabled: true pid=3302, uid=10000
,07-12 11:37:14.836   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-12 11:37:14.848  3302  3353 I jxcore-log: My device name is: motorola-Nexus 6
07-12 11:37:14.848  3302  3353 I jxcore-log: 
,07-12 11:37:14.848  3302  3302 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-12 11:37:14.849  3302  3353 I jxcore-log: WARN testUtils: myNameCallback not set!
07-12 11:37:14.849  3302  3353 I jxcore-log: 
,07-12 11:37:14.874   872   889 I ActivityManager: Start proc 3359:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-12 11:37:14.875   872  1304 D WifiConfigStore: Loading config and enabling all networks 
,07-12 11:37:14.877  3302  3302 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 11:37:14.877  3302  3302 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:37:14.877  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:14.877  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-12 11:37:14.877  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:37:14.877  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-12 11:37:14.877  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:37:14.877  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:37:14.877  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:37:14.877  3302  3302 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,07-12 11:37:14.877  3302  3302 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-12 11:37:14.889   872   885 I ActivityManager: Start proc 3369:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-12 11:37:14.894   872  1304 D WifiConfigStore: loaded 0 passpoint configs
07-12 11:37:14.894   872  1304 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-12 11:37:14.895   872  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-12 11:37:14.896   872  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-12 11:37:14.897   872  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-12 11:37:14.897   872  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-12 11:37:14.897   872  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-12 11:37:14.897   872  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-12 11:37:14.948   370   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-12 11:37:14.949   872  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-12 11:37:14.949   370   870 D CommandListener: Setting iface cfg
07-12 11:37:14.950   872  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
,07-12 11:37:14.950   872  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-12 11:37:14.961   872  1303 D WifiNative-HAL: p2pGetDeviceAddress
,07-12 11:37:14.962   872  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-12 11:37:14.965   872  1304 E native  : do suspend true
,07-12 11:37:14.970  3369  3369 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-12 11:37:14.982   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:37:14.986  3359  3359 D AdapterServiceConfig: Adding HeadsetService
,07-12 11:37:14.986  3359  3359 D AdapterServiceConfig: Adding A2dpService
07-12 11:37:14.987  3359  3359 D AdapterServiceConfig: Adding HidService
07-12 11:37:14.987  3359  3359 D AdapterServiceConfig: Adding HealthService
07-12 11:37:14.987  3359  3359 D AdapterServiceConfig: Adding PanService
,07-12 11:37:14.987  3359  3359 D AdapterServiceConfig: Adding GattService
07-12 11:37:14.987  3359  3359 D AdapterServiceConfig: Adding BluetoothMapService
,07-12 11:37:14.996  1458  1458 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
07-12 11:37:14.996  1458  1458 W wpa_supplicant: wlan0: Failed to initiate AP scan
,07-12 11:37:15.016   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@49ce65d:true
,07-12 11:37:15.016  3359  3359 D BluetoothAdapterState: make() - Creating AdapterState
,07-12 11:37:15.018  3359  3359 I bt_bluedroid: init
,07-12 11:37:15.018  3359  3393 I BluetoothAdapterState: Entering OffState
,07-12 11:37:15.022  3369  3369 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-12 11:37:15.022  3359  3394 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-12 11:37:15.022  3359  3394 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-12 11:37:15.023  3359  3394 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-12 11:37:15.023  3359  3394 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-12 11:37:15.024  3359  3359 I bt_bluedroid: get_profile_interface socket
07-12 11:37:15.025  3359  3359 I bt_bluedroid: get_profile_interface sdp
07-12 11:37:15.025  3359  3398 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
07-12 11:37:15.026  3359  3398 D BluetoothAdapterProperties: Name is: Nexus 6
,07-12 11:37:15.027  3359  3380 I bt_bluedroid: config_hci_snoop_log
07-12 11:37:15.028   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,07-12 11:37:15.030  3359  3393 D BluetoothAdapterState: Current state: OFF, message: 0
,07-12 11:37:15.031  3359  3393 D BluetoothAdapterProperties: Setting state to 14
07-12 11:37:15.031  3359  3393 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-12 11:37:15.034  3359  3393 D BluetoothBondStateMachine: make
,07-12 11:37:15.035  3359  3401 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-12 11:37:15.037  3359  3393 I BluetoothAdapterState: Entering PendingCommandState
,07-12 11:37:15.038  3359  3359 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-12 11:37:15.039   872   882 I ActivityManager: Killing 2302:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,07-12 11:37:15.040  3359  3359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@330c17c
07-12 11:37:15.040  3359  3359 D BtGatt.DebugUtils: handleDebugAction() action=null
07-12 11:37:15.040  3359  3359 D BtGatt.GattService: Received start request. Starting profile...
07-12 11:37:15.041  3359  3359 D BtGatt.GattService: start()
,07-12 11:37:15.041  3359  3359 I bt_bluedroid: get_profile_interface gatt
07-12 11:37:15.041  3359  3359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@330c17c
07-12 11:37:15.041  3359  3359 D BtGatt.AdvertiseManager: advertise manager created
,07-12 11:37:15.075  3359  3359 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:37:15.075  3359  3359 V BluetoothAdapterState: isTurningOn()=false
07-12 11:37:15.075  3359  3359 V BluetoothAdapterState: isBleTurningOn()=true
07-12 11:37:15.075  3359  3359 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:15.075  3359  3393 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-12 11:37:15.075  3359  3393 I bt_bluedroid: enable
07-12 11:37:15.076  3359  3394 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-12 11:37:15.076  3359  3394 I bt_hci  : start_up
,07-12 11:37:15.090  3359  3394 I bt_vendor: alloc value 0xb3a4a189
,07-12 11:37:15.090  3359  3394 I bt_vendor: init
07-12 11:37:15.090  3359  3394 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-12 11:37:15.090  3359  3394 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-12 11:37:15.196  3359  3394 D bt_hci  : start_up starting async portion
,07-12 11:37:15.197  3359  3404 I bt_hci  : event_finish_startup
07-12 11:37:15.197  3359  3404 I bt_hci_h4: hal_open
07-12 11:37:15.197  3359  3404 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-12 11:37:15.204  3359  3404 I bt_userial_vendor: device fd = 51 open
,07-12 11:37:15.240  3359  3404 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-12 11:37:15.271  3359  3404 D bt_hwcfg: Chipset BCM4354A2
,07-12 11:37:15.272  3359  3404 D bt_hwcfg: Target name = [BCM4354A2]
07-12 11:37:15.273  3359  3404 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-12 11:37:15.880  3359  3404 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-12 11:37:15.881  3359  3404 D bt_hwcfg: Settlement delay -- 100 ms
07-12 11:37:15.881  3359  3404 I bt_hwcfg: Setting fw settlement delay to 100 
,07-12 11:37:15.998  1458  1458 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,07-12 11:37:15.997  3359  3404 I bt_hwcfg: bt vendor lib: set UART baud 3000000
07-12 11:37:15.998  1458  1458 W wpa_supplicant: wlan0: Failed to initiate AP scan
,07-12 11:37:15.999  3359  3404 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-12 11:37:16.030  3359  3404 I bt_hwcfg: vendor lib fwcfg completed
07-12 11:37:16.030  3359  3404 I bt_vendor: firmware callback
,07-12 11:37:16.031  3359  3404 I bt_hci  : firmware_config_callback
,07-12 11:37:16.039  3359  3406 I bt_btu  : btu_task pending for preload complete event
,07-12 11:37:16.040  3359  3406 I bt_btu_task: Bluetooth chip preload is complete
,07-12 11:37:16.040  3359  3406 I bt_btu  : btu_task received preload complete event
,07-12 11:37:16.049  3359  3406 I         : BTE_InitTraceLevels -- TRC_HCI
,07-12 11:37:16.049  3359  3406 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-12 11:37:16.050  3359  3406 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-12 11:37:16.050  3359  3406 I         : BTE_InitTraceLevels -- TRC_AVDT
,07-12 11:37:16.050  3359  3406 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-12 11:37:16.050  3359  3406 I         : BTE_InitTraceLevels -- TRC_A2D
,07-12 11:37:16.051  3359  3406 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-12 11:37:16.051  3359  3406 I         : BTE_InitTraceLevels -- TRC_BTM
07-12 11:37:16.051  3359  3406 I         : BTE_InitTraceLevels -- TRC_GAP
07-12 11:37:16.051  3359  3406 I         : BTE_InitTraceLevels -- TRC_PAN
07-12 11:37:16.051  3359  3406 I         : BTE_InitTraceLevels -- TRC_SDP
07-12 11:37:16.052  3359  3406 I         : BTE_InitTraceLevels -- TRC_GATT
,07-12 11:37:16.052  3359  3406 I         : BTE_InitTraceLevels -- TRC_SMP
07-12 11:37:16.052  3359  3406 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-12 11:37:16.052  3359  3406 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-12 11:37:16.178  3359  3406 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39c7d9d
,07-12 11:37:16.178  3359  3406 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39c7d9d 
,07-12 11:37:16.207  3359  3398 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
07-12 11:37:16.209  3359  3398 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-12 11:37:16.209  3359  3398 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-12 11:37:16.213  3359  3398 D BluetoothAdapterProperties: Name is: Nexus 6
,07-12 11:37:16.216  3359  3398 D BluetoothAdapterProperties: Scan Mode:20
,07-12 11:37:16.216  3359  3398 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-12 11:37:16.217  3359  3398 D bt_hci  : do_postload posting postload work item
,07-12 11:37:16.217  3359  3404 I bt_hci  : event_postload
,07-12 11:37:16.217  3359  3404 I bt_vendor: sco_config_cb
,07-12 11:37:16.217  3359  3404 I bt_hci  : sco_config_callback postload finished.
,07-12 11:37:16.220  3302  3302 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-12 11:37:16.227  3359  3398 D bt_bte_conf: Device ID record 1 : primary
,07-12 11:37:16.228  3359  3398 D bt_bte_conf:   vendorId            = 000f
,07-12 11:37:16.228  3359  3398 D bt_bte_conf:   vendorIdSource      = 0001
,07-12 11:37:16.228  3359  3398 D bt_bte_conf:   product             = 1200
,07-12 11:37:16.228  3359  3398 D bt_bte_conf:   version             = 1436
07-12 11:37:16.228  3359  3398 D bt_bte_conf:   clientExecutableURL = 
07-12 11:37:16.228  3359  3398 D bt_bte_conf:   serviceDescription  = 
07-12 11:37:16.228  3359  3398 D bt_bte_conf:   documentationURL    = 
,07-12 11:37:16.228  3359  3398 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-12 11:37:16.228  3359  3394 D bt_stack_manager: event_start_up_stack finished
07-12 11:37:16.228  3359  3393 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-12 11:37:16.228  3359  3404 I bt_vendor: low_power_mode_cb
,07-12 11:37:16.229  3359  3393 D BluetoothAdapterProperties: Setting state to 15
07-12 11:37:16.229  3359  3393 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-12 11:37:16.230  3359  3393 I BluetoothAdapterState: Entering BleOnState
,07-12 11:37:16.234  3359  3393 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-12 11:37:16.234  3359  3393 D BluetoothAdapterProperties: Setting state to 11
07-12 11:37:16.234  3359  3393 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-12 11:37:16.255   872   885 I ActivityManager: Start proc 3412:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,07-12 11:37:16.257  3359  3359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@330c17c
07-12 11:37:16.258  3359  3359 D HeadsetService: Received start request. Starting profile...
,07-12 11:37:16.261  3359  3359 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-12 11:37:16.261  3359  3359 D HeadsetStateMachine: make
,07-12 11:37:16.264  3359  3393 I BluetoothAdapterState: Entering PendingCommandState
,07-12 11:37:16.272  3359  3359 D HeadsetStateMachine: max_hf_connections = 1
,07-12 11:37:16.272  3359  3359 I bt_bluedroid: get_profile_interface handsfree
,07-12 11:37:16.272  3359  3398 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-12 11:37:16.272  3359  3398 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-12 11:37:16.278  3359  3359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@330c17c
,07-12 11:37:16.279   872   872 D BluetoothA2dp: Proxy object connected
07-12 11:37:16.282  3359  3359 D A2dpService: Received start request. Starting profile...
07-12 11:37:16.283  3359  3359 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-12 11:37:16.283  3359  3359 I bt_bluedroid: get_profile_interface avrcp
,07-12 11:37:16.283  1458  1458 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-12 11:37:16.289  3359  3359 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-12 11:37:16.289  3359  3359 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-12 11:37:16.289  3359  3359 D A2dpStateMachine: make
,07-12 11:37:16.290  3359  3359 I bt_bluedroid: get_profile_interface a2dp
,07-12 11:37:16.292  3359  3398 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-12 11:37:16.293  3359  3359 I BluetoothHidServiceJni: classInitNative: succeeds
,07-12 11:37:16.294  3359  3359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@330c17c
07-12 11:37:16.295  1350  1350 D BluetoothInputDevice: Proxy object connected
,07-12 11:37:16.296  1350  1350 D HidProfile: Bluetooth service connected
,07-12 11:37:16.296  3359  3359 D HidService: Received start request. Starting profile...
07-12 11:37:16.296  3359  3359 I bt_bluedroid: get_profile_interface hidhost
07-12 11:37:16.297  3359  3398 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39a93e5
07-12 11:37:16.297  3359  3398 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-12 11:37:16.297  3359  3359 D HidService: setHidService(): set to: null
07-12 11:37:16.297  3359  3359 I BluetoothHealthServiceJni: classInitNative: succeeds
07-12 11:37:16.298  3359  3359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@330c17c
07-12 11:37:16.298  3359  3359 D HealthService: Received start request. Starting profile...
,07-12 11:37:16.299  3359  3426 D A2dpStateMachine: Enter Disconnected: -2
07-12 11:37:16.300  3359  3359 I bt_bluedroid: get_profile_interface health
07-12 11:37:16.301  3359  3359 I BluetoothPanServiceJni: classInitNative(L105): succeeds
07-12 11:37:16.301  3359  3359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@330c17c
,07-12 11:37:16.303  1350  1350 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 11:37:16.303  3359  3359 D PanService: Received start request. Starting profile...
,07-12 11:37:16.303  1350  1350 D PanProfile: Bluetooth service connected
07-12 11:37:16.303  3359  3359 D BluetoothPanServiceJni: initializeNative(L110): pan
07-12 11:37:16.303  3359  3359 I bt_bluedroid: get_profile_interface pan,
,07-12 11:37:16.304  3359  3398 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-12 11:37:16.306  3359  3359 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@330c17c
07-12 11:37:16.308  1350  1350 D BluetoothMap: Proxy object connected
,07-12 11:37:16.308  1350  1350 D MapProfile: Bluetooth service connected
07-12 11:37:16.308  1350  1350 D BluetoothMap: getConnectedDevices()
07-12 11:37:16.309  1350  1350 D BluetoothMap: Bluetooth is Not enabled
07-12 11:37:16.309  3359  3359 D BluetoothMapService: Received start request. Starting profile...
,07-12 11:37:16.309  3359  3359 D BluetoothMapService: start()
07-12 11:37:16.311  3412  3412 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
07-12 11:37:16.313  3359  3359 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER,
07-12 11:37:16.313  3359  3359 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-12 11:37:16.314  3359  3359 D BluetoothMapAppObserver: createReceiver()
07-12 11:37:16.315  3359  3359 D BluetoothMapAppObserver: initObservers()
07-12 11:37:16.315  3359  3359 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-12 11:37:16.322  3359  3359 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:37:16.322  3359  3359 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:16.322  3359  3418 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-12 11:37:16.322  3359  3359 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:16.322  3359  3359 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:37:16.323  3359  3359 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:37:16.323  3359  3359 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isTurningOn()=true
,07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isBleTurningOff()=false
,07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isTurningOff()=false
,07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:16.324  3359  3359 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:16.325  3359  3359 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:16.325  3359  3359 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:16.325  3359  3359 V BluetoothAdapterState: isTurningOff()=false
07-12 11:37:16.325  3359  3359 V BluetoothAdapterState: isTurningOn()=true
07-12 11:37:16.325  3359  3359 V BluetoothAdapterState: isBleTurningOn()=false
07-12 11:37:16.325  3359  3359 V BluetoothAdapterState: isBleTurningOff()=false
07-12 11:37:16.325  3359  3393 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-12 11:37:16.325  3359  3393 D BluetoothAdapterProperties: ScanMode =  20
07-12 11:37:16.325  3359  3393 D BluetoothAdapterProperties: State =  11
07-12 11:37:16.328  3359  3398 D BluetoothAdapterProperties: Scan Mode:21
07-12 11:37:16.328  3359  3398 D BluetoothAdapterProperties: Discoverable Timeout:120
07-12 11:37:16.328  3359  3393 D BluetoothAdapterProperties: Setting state to 12
07-12 11:37:16.328  3359  3393 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-12 11:37:16.328   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:37:16.329   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:37:16.330  1350  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-12 11:37:16.330  3359  3393 I BluetoothAdapterState: Entering OnState
07-12 11:37:16.330  3302  3302 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-12 11:37:16.331  1739  1753 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-12 11:37:16.332  1350  1365 D BluetoothPan: onBluetoothStateChange on: true
,07-12 11:37:16.332  1350  1830 D BluetoothMap: onBluetoothStateChange: up=true
07-12 11:37:16.332   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
07-12 11:37:16.332   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-12 11:37:16.332  1350  1373 D BluetoothPbap: onBluetoothStateChange: up=true
,07-12 11:37:16.333  3302  3302 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:37:16.333  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:16.333  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 11:37:16.333  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:37:16.333  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:37:16.333  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-12 11:37:16.333  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-12 11:37:16.333  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-12 11:37:16.335   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
07-12 11:37:16.336  3359  3359 D BluetoothMapService: onReceive
07-12 11:37:16.336  3359  3359 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-12 11:37:16.336  3359  3359 D BluetoothMapService: STATE_ON
07-12 11:37:16.336  3302  3302 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-12 11:37:16.340  3359  3359 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-12 11:37:16.340  3359  3359 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-12 11:37:16.341  1350  1666 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-12 11:37:16.342   872  1384 I ActivityManager: Killing 2666:com.google.android.calendar/u0a37 (adj 15): empty #17
,07-12 11:37:16.360   872  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,07-12 11:37:16.370  1350  1666 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-12 11:37:16.370  1350  1350 D BluetoothA2dp: Proxy object connected
,07-12 11:37:16.373  3359  3359 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:16.374   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-12 11:37:16.374   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:37:16.376  3359  3359 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:16.378  3359  3359 D ObexServerSockets: Succeed to create listening sockets 
,07-12 11:37:16.378  3359  3359 D ObexServerSockets0: startAccept()
07-12 11:37:16.378  3359  3359 D ObexServerSockets0: prepareForNewConnect()
07-12 11:37:16.378   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
07-12 11:37:16.380  3359  3359 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-12 11:37:16.380  3359  3359 D BluetoothSdpJni: SDP Create record success - handle: 0
07-12 11:37:16.381  3359  3359 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-12 11:37:16.381  3359  3359 D ObexServerSockets0: prepareForNewConnect()
07-12 11:37:16.382  3359  3434 D ObexServerSockets0: Accepting socket connection...
07-12 11:37:16.383  3359  3433 D ObexServerSockets0: Accepting socket connection...
,07-12 11:37:16.395  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-12 11:37:16.419   872  1763 I ActivityManager: Start proc 3435:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-12 11:37:16.421   872  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-12 11:37:16.429   872   889 D BluetoothHeadset: Proxy object connected
,07-12 11:37:16.431   872   889 D BluetoothHeadset: Proxy object connected
,07-12 11:37:16.433  1739  1759 D BluetoothHeadset: Proxy object connected
,07-12 11:37:16.435   872   889 D BluetoothHeadset: Proxy object connected
,07-12 11:37:16.452  3435  3435 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-12 11:37:16.476  1350  1365 D BluetoothHeadset: Proxy object connected
,07-12 11:37:16.478  1350  1350 D HeadsetProfile: Bluetooth service connected
,07-12 11:37:16.623  3435  3435 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:37:16.623  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-12 11:37:16.624  3435  3435 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:37:16.624  3435  3435 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:37:16.624  3435  3435 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:37:16.624  3435  3435 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.k.d(PG:583)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.e.b(PG:170)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:37:16.624  3435  3435 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:37:16.624  3435  3435 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.File.exists(File.java:361)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 11:37:16.624  3435  3435 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 11:37:16.624  3435  3435 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-12 11:37:16.664  3412  3412 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-12 11:37:16.679   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5718d2e:true
07-12 11:37:16.679  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-12 11:37:16.690  3412  3412 D LocalBluetoothProfileManager: Adding local A2DP profile
07-12 11:37:16.699  3412  3412 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-12 11:37:16.702  1350  1350 D BluetoothPbap: Proxy object connected
,07-12 11:37:16.703  1350  1350 D PbapServerProfile: Bluetooth service connected
,07-12 11:37:16.714  3412  3412 D LocalBluetoothProfileManager: Adding local MAP profile
,07-12 11:37:16.715  3412  3412 D BluetoothMap: Create BluetoothMap proxy object
,07-12 11:37:16.726  3359  3464 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-12 11:37:16.727  3412  3412 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-12 11:37:16.731  3412  3412 D DockEventReceiver: finishStartingService: stopping service
,07-12 11:37:16.732  3412  3412 D BluetoothA2dp: Proxy object connected
,07-12 11:37:16.735  3412  3412 D BluetoothInputDevice: Proxy object connected
,07-12 11:37:16.735  3412  3412 D HidProfile: Bluetooth service connected
,07-12 11:37:16.738  3412  3412 D BluetoothPan: BluetoothPAN Proxy object connected
,07-12 11:37:16.741  3412  3412 D PanProfile: Bluetooth service connected
,07-12 11:37:16.741  3412  3412 D BluetoothMap: Proxy object connected
,07-12 11:37:16.743  1458  1458 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-12 11:37:16.745  3359  3470 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-12 11:37:16.746  3359  3470 I BtOppRfcommListener: Accept thread started.
,07-12 11:37:16.750  3412  3412 D MapProfile: Bluetooth service connected
07-12 11:37:16.750  3412  3412 D BluetoothMap: getConnectedDevices()
,07-12 11:37:16.752  3412  3412 D BluetoothPbap: Proxy object connected
,07-12 11:37:16.753  3412  3412 D PbapServerProfile: Bluetooth service connected
,07-12 11:37:16.754   872  1751 I ActivityManager: Killing 2799:com.google.android.gm/u0a78 (adj 15): empty #17
,07-12 11:37:16.770  1458  1458 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-12 11:37:16.770  1458  1458 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-12 11:37:16.805  3412  3424 D BluetoothHeadset: Proxy object connected
07-12 11:37:16.806  3412  3412 D HeadsetProfile: Bluetooth service connected
,07-12 11:37:16.808   872  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,07-12 11:37:16.813   872  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:37:16.814   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-12 11:37:16.814   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-12 11:37:16.827   872  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-12 11:37:16.839   370   870 D CommandListener: Setting iface cfg
,07-12 11:37:16.844   872  1304 D WifiStateMachine: Start Dhcp Watchdog 1
,07-12 11:37:16.848   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-12 11:37:16.870   872  3476 D DhcpClient: Receive thread started
,07-12 11:37:16.879  3435  3458 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-12 11:37:16.894   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@53fa9b4:true
,07-12 11:37:16.954   872  1304 E native  : do suspend false
,07-12 11:37:16.966   872  3473 D DhcpClient: Broadcasting DHCPDISCOVER
,07-12 11:37:16.977   872  3476 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 171326, domain null
07-12 11:37:16.978   872  3473 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 171326 seconds
,07-12 11:37:16.979   872  3473 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-12 11:37:16.991   872  3476 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-12 11:37:16.991   872  3473 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-12 11:37:16.992   370   870 D CommandListener: Setting iface cfg
07-12 11:37:16.994   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-12 11:37:16.996   872  3473 D DhcpClient: Scheduling renewal in 86399s
,07-12 11:37:16.996   872  1304 E native  : do suspend true
,07-12 11:37:17.007   872  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-12 11:37:17.007   872  1304 D WifiConfigStore: No blacklist allowed without epno enabled
07-12 11:37:17.008   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-12 11:37:17.009   872  1307 D ConnectivityService: Adding iface wlan0 to network 100
07-12 11:37:17.011   872  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-12 11:37:17.050   872  1307 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-12 11:37:17.051   872  1307 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,07-12 11:37:17.053   872  1307 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100,
,07-12 11:37:17.056   872  1307 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,07-12 11:37:17.057   872  1307 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,07-12 11:37:17.064   872  1307 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,07-12 11:37:17.067   872  1307 D ConnectivityService: scheduleUnvalidatedPrompt 100
07-12 11:37:17.067   872  1307 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,07-12 11:37:17.067   872  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-12 11:37:17.068   872  1307 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
07-12 11:37:17.068   872  1307 D ConnectivityService:    accepting network in place of null
07-12 11:37:17.069   872  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-12 11:37:17.069   872  1307 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-12 11:37:17.086   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=166289, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:37:17.106   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:37:17.126   370   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-12 11:37:17.128   872  1307 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,07-12 11:37:17.133   872  1307 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-12 11:37:17.133   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-12 11:37:17.134   872  1307 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
07-12 11:37:17.136   872   889 D Tethering: MasterInitialState.processMessage what=3
07-12 11:37:17.137   872   882 V BackupManagerService: Scheduling immediate backup pass
,07-12 11:37:17.138   872   872 V BackupManagerService: Running a backup pass
07-12 11:37:17.139   872  1325 V BackupManagerService: clearing pending backups
07-12 11:37:17.143   872  1325 V PerformBackupTask: Beginning backup of 16 targets
07-12 11:37:17.150  2987  2987 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@267720e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-12 11:37:17.165   872  3471 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:800::200e
,07-12 11:37:17.169  3302  3302 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-12 11:37:17.169  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-12 11:37:17.169  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-12 11:37:17.169  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-12 11:37:17.169  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-12 11:37:17.169  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-12 11:37:17.169  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-12 11:37:17.169  3302  3302 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-12 11:37:17.171  3302  3302 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-12 11:37:17.172   872  1325 D PerformBackupTask: invokeAgentForBackup on @pm@
,07-12 11:37:17.176   872  1325 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
,07-12 11:37:17.186  2987  2987 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-12 11:37:17.208   872  1325 I BackupRestoreController: Getting widget state for user: 0
,07-12 11:37:17.241   872  3471 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 12 Jul 2016 09:37:17 GMT], X-Android-Received-Millis=[1468316237240], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1468316237213]}
07-12 11:37:17.242   872  1307 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
07-12 11:37:17.242   872  1307 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
07-12 11:37:17.242   872  1307 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
07-12 11:37:17.243   872  1307 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-12 11:37:17.258  1867  3497 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,07-12 11:37:17.264   872  1384 I ActivityManager: Start proc 3504:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-12 11:37:17.298  3504  3504 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-12 11:37:17.307  1841  1857 W GmsBackupTransport: Unknown package in backup request: @pm@
,07-12 11:37:17.310  1841  1857 V GmsBackupTransport: starting performBackup for @pm@
,07-12 11:37:17.335  1867  1867 D NetworkLogImpl: Loaded NetworkSpeedPredictor
07-12 11:37:17.335  1867  3522 I iu.SyncManager: SYNC; picasa accounts
07-12 11:37:17.336  1867  1867 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-12 11:37:17.340  1841  1857 V GmsBackupTransport: performBackup done for @pm@
07-12 11:37:17.347  1867  1867 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-12 11:37:17.348  1867  1867 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-12 11:37:17.341  1867  3522 I iu.UploadsManager: num queued entries: 0
,07-12 11:37:17.355  1867  3522 I iu.UploadsManager: num updated entries: 0
,07-12 11:37:17.355  1867  3522 I iu.SyncManager: NEXT; no task
,07-12 11:37:17.360   872  1752 I ActivityManager: Start proc 3528:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,07-12 11:37:17.362  1867  3519 I MDM     : [185] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
07-12 11:37:17.362  1867  3519 W BaseAppContext: Using Auth Proxy for data requests.
,07-12 11:37:17.371  1867  3519 V GoogleAuthProtoRequest: [185] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:37:17.372  3504  3521 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-12 11:37:17.389  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:17.415  3528  3528 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
07-12 11:37:17.417  3369  3502 V GoogleAuthProtoRequest: [282] a.<init>: mAccountName set to: thalitester@gmail.com
07-12 11:37:17.421  1519  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
07-12 11:37:17.421  1519  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
,07-12 11:37:17.421  1519  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:37:17.421  1519  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:17.439  1519  1535 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 11:37:17.439  1519  1535 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 11:37:17.439  1519  1535 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 11:37:17.439  1519  1535 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-12 11:37:17.439  1519  1535 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-12 11:37:17.439  1519  1535 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-12 11:37:17.439  1519  1535 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 11:37:17.443  1841  2065 W GmsBackupTransport: Error sending final backup to server: 
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-12 11:37:17.443  1841  2065 W GmsBackupTransport: 	... 1 more
,07-12 11:37:17.458  1841  2071 I GmsBackupTransport: Next backup will happen in 43199983 millis.
,07-12 11:37:17.459   872  1325 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
07-12 11:37:17.467  3528  3528 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
07-12 11:37:17.470  3504  3521 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
07-12 11:37:17.472  3528  3528 D SprintDMHelper: simOperator: 
,07-12 11:37:17.472  3528  3528 D SprintDMReceiver: Not Sprint UICC, don't do anything.
07-12 11:37:17.487   872   882 I ActivityManager: Start proc 3549:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
07-12 11:37:17.508  1519  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-12 11:37:17.509  1519  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 11:37:17.509  1519  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:17.509  1519  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 11:37:17.522  3504  3521 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-12 11:37:17.526  1519  3130 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
07-12 11:37:17.526  1519  3130 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-12 11:37:17.532  1519  3130 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:17.532  1519  3130 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:17.568  1867  3519 E MDM     : [185] SitrepService.a: Error sending sitrep.
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: [282] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: [282] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:37:17.571  3369  3502 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:37:17.649  3504  3504 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-12 11:37:17.651  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:17.651   872  1325 I BackupManagerService: Backup pass finished.
,07-12 11:37:17.671  1519  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 11:37:17.671  1519  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-12 11:37:17.671  1519  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:17.671  1519  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:17.696  3099  3520 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 11:37:17.696  3099  3520 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at blb.a(PG:3937)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at czp.a(PG:18188)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:37:17.696  3099  3520 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	... 12 more
07-12 11:37:17.696  3099  3520 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at fal.a(PG:38)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:37:17.696  3099  3520 E HttpOperation: 	... 14 more
,07-12 11:37:17.716   872  1696 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/1867 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-12 11:37:17.734  1519  2056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-12 11:37:17.735  1519  2056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 11:37:17.735  1519  2056 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:17.735  1519  2056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 11:37:17.747  3099  3520 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 11:37:17.747  3099  3520 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at hec.a(PG:42)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at hee.a(PG:102)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at czr.a(PG:65)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at kka.a(PG:108)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at czp.a(PG:19176)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:37:17.747  3099  3520 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	... 15 more
07-12 11:37:17.747  3099  3520 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at fal.a(PG:38)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:37:17.747  3099  3520 E HttpOperation: 	... 17 more
07-12 11:37:17.747  3099  3520 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 11:37:17.747  3099  3520 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at hec.a(PG:42)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at hee.a(PG:102)
07-12 11:37:17.747  ,3099  3520 E ExperimentLoader: 	at czr.a(PG:65)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at kka.a(PG:108)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	... 15 more
07-12 11:37:17.747  3099  3520 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at fal.a(PG:38)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 11:37:17.747  3099  3520 E ExperimentLoader: 	... 17 more
,07-12 11:37:17.772  3572  3572 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-2095501894.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-2095501894.dex
,07-12 11:37:17.843  3504  3504 W InstanceID/Rpc: Found 10011
,07-12 11:37:17.872   872  1751 I ActivityManager: Start proc 3622:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-12 11:37:17.905   872   882 I ActivityManager: Killing 2987:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-12 11:37:17.905  3572  3572 I dex2oat : dex2oat took 133.730ms (threads: 4) arena alloc=306KB java alloc=29KB native alloc=1641KB free=1686KB
,07-12 11:37:17.961  3622  3622 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-12 11:37:18.029  2341  3613 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-12 11:37:18.032   872   884 I ActivityManager: Start proc 3644:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,07-12 11:37:18.037   872  1384 I ActivityManager: Killing 2461:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-12 11:37:18.047  3644  3644 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,07-12 11:37:18.201   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 22828, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:37:18.202   872  1751 I ActivityManager: Killing 2719:android.process.acore/u0a5 (adj 15): empty #17
,07-12 11:37:18.307  1867  3498 W DriveInitializer: Awaiting to be initialized
,07-12 11:37:18.310  1867  3660 W DriveInitializer: Background init thread started
,07-12 11:37:18.326  3644  3644 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,07-12 11:37:18.334  3644  3644 I BooksApp: Created application version: 3.6.9 (30609)
,07-12 11:37:18.369  1867  3660 W DriveInitializer: Background init thread ended
,07-12 11:37:18.418  2845  3662 V KeepSync: Connecting to GoogleApiClient
,07-12 11:37:18.419   872   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 11:37:18.476  3644  3673 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:37:18.485  1519  2056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-12 11:37:18.485  1519  2056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 11:37:18.486  1519  2056 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:18.486  1519  2056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:18.498  1867  3680 V BaseAuthAsyncOperation: access token request failed
07-12 11:37:18.499  3622  3622 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-12 11:37:18.499  3622  3622 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:37:18.499  3622  3622 I GAv4    :   adb logcat -s GAv4
,07-12 11:37:18.501  2845  3662 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:37:18.514  3622  3622 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:18.519  3622  3622 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:18.553  3622  3685 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:18.693  3622  3622 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-12 11:37:18.744  3622  3622 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-12 11:37:18.771  3622  3622 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7973-7976)
,07-12 11:37:18.771  3622  3622 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-12 11:37:18.797  3622  3622 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c5feb04}
,07-12 11:37:18.798  3622  3622 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-12 11:37:18.798  3622  3622 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-12 11:37:18.810  3622  3622 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-12 11:37:18.811  3622  3622 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-12 11:37:18.831  3622  3622 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-12 11:37:18.847  3622  3622 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-12 11:37:18.847  3622  3622 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-12 11:37:18.847  3622  3622 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-12 11:37:18.847  3622  3622 I Adreno  : Build Date                       : 10/20/15
07-12 11:37:18.847  3622  3622 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-12 11:37:18.847  3622  3622 I Adreno  : Local Branch                     : M14
07-12 11:37:18.847  3622  3622 I Adreno  : Remote Branch                    : 
07-12 11:37:18.847  3622  3622 I Adreno  : Remote Branch                    : 
07-12 11:37:18.847  3622  3622 I Adreno  : Reconstruct Branch               : 
,07-12 11:37:18.933  3622  3622 I NSApplication: Starting up...
,07-12 11:37:18.946  3622  3717 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-12 11:37:18.976   872  1763 I ActivityManager: Start proc 3722:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-12 11:37:19.027  3644  3736 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 11:37:19.064  3722  3722 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-12 11:37:19.065  1519  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 11:37:19.065  1519  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:37:19.065  1519  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:19.065  1519  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:19.097  1519  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:37:19.098  1519  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 11:37:19.098  1519  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:19.098  1519  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-12 11:37:19.098  1519  1885 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-12 11:37:19.099  1519  1885 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-12 11:37:19.099  1519  1885 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:19.099  1519  1885 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:19.111  3644  3736 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:37:19.112  3644  3673 E BooksSync: Soft error
07-12 11:37:19.112  3644  3673 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:37:19.112  3644  3673 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:37:19.112  3644  3673 E BooksSync: Sync error
07-12 11:37:19.112  3644  3673 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:37:19.112  3644  3673 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:37:19.114  2845  3662 E KeepSync: IOException
07-12 11:37:19.114  2845  3662 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89),
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:37:19.114  2845  3662 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:37:19.114  2845  3662 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:37:19.114  2845  3662 E KeepSync: 	... 10 more
07-12 11:37:19.114  2845  3662 W KeepSync: Sync result 2
,07-12 11:37:19.116  3644  3673 I BooksSync: Finished books sync
,07-12 11:37:19.123   872  1384 I ActivityManager: Killing 3189:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-12 11:37:19.123   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 22837, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:37:19.174   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 22837, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:37:19.176   872  1763 I ActivityManager: Killing 3202:com.android.musicfx/u0a18 (adj 15): empty #17
,07-12 11:37:19.460  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-12 11:37:19.460  3302  3353 I jxcore-log: 
,07-12 11:37:19.479   872  1752 I ActivityManager: Killing 3036:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-12 11:37:19.695  1519  2056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,07-12 11:37:19.695  1519  2056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
07-12 11:37:19.695  1519  2056 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:19.695  1519  2056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:19.714  2341  3744 E Babel   : UserRecoverableAuthException.
,07-12 11:37:19.715  2341  3744 E Babel   : efr: BadAuthentication
07-12 11:37:19.715  2341  3744 E Babel   : 	at efp.a(Unknown Source)
07-12 11:37:19.715  2341  3744 E Babel   : 	at efp.a(Unknown Source)
07-12 11:37:19.715  2341  3744 E Babel   : 	at efp.a(Unknown Source)
07-12 11:37:19.715  2341  3744 E Babel   : 	at g.a(Unknown Source)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cbh.a(SourceFile:3092)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cbh.a(SourceFile:1136)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cyr.a(SourceFile:4333)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cyr.a(SourceFile:1419)
07-12 11:37:19.715  2341  3744 E Babel   : 	at ctk.a(SourceFile:492)
07-12 11:37:19.715  2341  3744 E Babel   : 	at ctk.a(SourceFile:1468)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cst.a(SourceFile:4416)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cbv.b(SourceFile:106)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cbs.d(SourceFile:335)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cbt.run(SourceFile:81)
07-12 11:37:19.715  2341  3744 E Babel   : Error getting auth token
07-12 11:37:19.715  2341  3744 E Babel   : dxq
07-12 11:37:19.715  2341  3744 E Babel   : 	at g.a(Unknown Source)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cbh.a(SourceFile:3092)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cbh.a(SourceFile:1136)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cyr.a(SourceFile:4333)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cyr.a(SourceFile:1419)
07-12 11:37:19.715  2341  3744 E Babel   : 	at ctk.a(SourceFile:492)
07-12 11:37:19.715  2341  3744 E Babel   : 	at ctk.a(SourceFile:1468)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cst.a(SourceFile:4416)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cbv.b(SourceFile:106)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cbs.d(SourceFile:335)
07-12 11:37:19.715  2341  3744 E Babel   : 	at cbt.run(SourceFile:81)
,07-12 11:37:19.721  2341  3744 E Babel   : Account registration failed 1-Redacted-21
,07-12 11:37:19.722  2341  3744 E Babel   : dao: null -- null
07-12 11:37:19.722  2341  3744 E Babel   : 	at cbh.a(SourceFile:3124)
07-12 11:37:19.722  2341  3744 E Babel   : 	at cbh.a(SourceFile:1136)
07-12 11:37:19.722  2341  3744 E Babel   : 	at cyr.a(SourceFile:4333)
07-12 11:37:19.722  2341  3744 E Babel   : 	at cyr.a(SourceFile:1419)
07-12 11:37:19.722  2341  3744 E Babel   : 	at ctk.a(SourceFile:492)
07-12 11:37:19.722  2341  3744 E Babel   : 	at ctk.a(SourceFile:1468)
07-12 11:37:19.722  2341  3744 E Babel   : 	at cst.a(SourceFile:4416)
07-12 11:37:19.722  2341  3744 E Babel   : 	at cbv.b(SourceFile:106)
07-12 11:37:19.722  2341  3744 E Babel   : 	at cbs.d(SourceFile:335)
07-12 11:37:19.722  2341  3744 E Babel   : 	at cbt.run(SourceFile:81)
,07-12 11:37:19.731  2341  3744 I art     : Note: end time exceeds epoch: 
,07-12 11:37:19.757  1519  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,07-12 11:37:19.757  1519  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
07-12 11:37:19.757  1519  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:19.757  1519  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:19.778  2341  3752 E Babel   : Unexpected exception while authenticating.
,07-12 11:37:19.778  2341  3752 E Babel   : efs: User intervention required. Notification has been pushed.
07-12 11:37:19.778  2341  3752 E Babel   : 	at efp.b(Unknown Source)
07-12 11:37:19.778  2341  3752 E Babel   : 	at efp.b(Unknown Source)
07-12 11:37:19.778  2341  3752 E Babel   : 	at g.a(Unknown Source)
07-12 11:37:19.778  2341  3752 E Babel   : 	at cbh.b(SourceFile:1151)
07-12 11:37:19.778  2341  3752 E Babel   : 	at def.run(SourceFile:5617)
07-12 11:37:19.778  2341  3752 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:37:19.778  2341  3752 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:37:19.778  2341  3752 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,07-12 11:37:19.883  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-12 11:37:19.883  3302  3353 I jxcore-log: 
,07-12 11:37:19.907  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-12 11:37:19.907  3302  3353 I jxcore-log: 
,07-12 11:37:19.912  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-12 11:37:19.912  3302  3353 I jxcore-log: 
,07-12 11:37:19.928  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-12 11:37:19.928  3302  3353 I jxcore-log: 
,07-12 11:37:19.933  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-12 11:37:19.933  3302  3353 I jxcore-log: 
,07-12 11:37:21.918  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-12 11:37:21.918  3302  3353 I jxcore-log: 
,07-12 11:37:21.930  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-12 11:37:21.930  3302  3353 I jxcore-log: 
,07-12 11:37:21.939  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-12 11:37:21.939  3302  3353 I jxcore-log: 
,07-12 11:37:22.117  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-12 11:37:22.117  3302  3353 I jxcore-log: 
,07-12 11:37:22.203   872  1707 D AlarmManagerService: Setting time of day to sec=1468316242
,07-12 11:37:22.761   872  3489 D GpsLocationProvider: NTP server returned: 1468316242760 (Tue Jul 12 11:37:22 GMT+02:00 2016) reference: 171407 certainty: 9 system time offset: 557
07-12 11:37:22.761   872  1707 W AlarmManagerService: Unable to set rtc to 1468316242: Invalid argument
,07-12 11:37:22.761   872  3489 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,07-12 11:37:22.889   872  1751 I ActivityManager: Start proc 3755:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,07-12 11:37:22.933  3755  3755 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,07-12 11:37:22.980   872   883 I ActivityManager: Start proc 3770:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,07-12 11:37:23.017  3770  3770 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,07-12 11:37:23.067  3770  3770 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@c5fdd02(com.android.providers.calendar.CalendarProvider2@bb3e613)
,07-12 11:37:23.113   872  1384 I ActivityManager: Start proc 3787:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
07-12 11:37:23.115   872  1384 I ActivityManager: Killing 3225:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-12 11:37:23.200  3755  3755 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,07-12 11:37:23.214  3787  3787 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,07-12 11:37:23.237  3787  3787 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
07-12 11:37:23.237  3787  3787 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-12 11:37:23.237  3787  3787 I GAv4    :   adb logcat -s GAv4
,07-12 11:37:23.255  3787  3787 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:23.259  3787  3787 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:23.272  3787  3802 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-12 11:37:23.325   872  1384 I ActivityManager: Start proc 3805:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,07-12 11:37:23.359  3805  3805 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,07-12 11:37:23.367  3805  3805 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1468316243366
07-12 11:37:23.367  3805  3805 D         : TimeServiceNative: User Time to be set is 1468316243367
07-12 11:37:23.367  3805  3805 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
07-12 11:37:23.367  3805  3805 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
,07-12 11:37:23.367  3805  3805 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1468316243367
07-12 11:37:23.367  3805  3805 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
07-12 11:37:23.367   390   991 D QC-time-services: Daemon: Connection accepted:time_genoff
07-12 11:37:23.367   390  3817 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1468316243367
07-12 11:37:23.367   390  3817 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1468316243367, operation = 0
07-12 11:37:23.367   390  3817 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS10/28/70 5:47:59
07-12 11:37:23.367   390  3817 D QC-time-services: Daemon:Value read from RTC seconds = 28619279000
07-12 11:37:23.368   390  3817 D QC-time-services: Daemon:new time 1468316243367 
,07-12 11:37:23.368   390  3817 D QC-time-services: Daemon: delta 1439696964367 genoff 1439696964367 
07-12 11:37:23.368   390  3817 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696964367 to memory
07-12 11:37:23.368   390  3817 D QC-time-services: Daemon:Opening File: /data/time/ats_2
07-12 11:37:23.368   390  3817 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:37:23.371   390  3817 D QC-time-services: Updating the TOD offset
07-12 11:37:23.372   390  3817 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696964367 to memory
07-12 11:37:23.372   390  3817 D QC-time-services: Daemon:Opening File: /data/time/ats_1
,07-12 11:37:23.372   390  3817 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,07-12 11:37:23.373   390  3817 E QC-time-services: Daemon:Update to modem bit set
07-12 11:37:23.373   390  3817 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
,07-12 11:37:23.374   390  3817 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1152351443367
07-12 11:37:23.374  3805  3805 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
07-12 11:37:23.375   872  1696 I ActivityManager: Killing 3152:com.android.defcontainer/u0a7 (adj 15): empty #17
,07-12 11:37:23.441   390   991 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,07-12 11:37:23.447   390   985 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,07-12 11:37:23.507  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-12 11:37:23.507  3302  3353 I jxcore-log: 
,07-12 11:37:23.571  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-12 11:37:23.571  3302  3353 I jxcore-log: 
,07-12 11:37:23.577  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-12 11:37:23.577  3302  3353 I jxcore-log: 
,07-12 11:37:23.777  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-12 11:37:23.777  3302  3353 I jxcore-log: 
,07-12 11:37:23.799  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-12 11:37:23.799  3302  3353 I jxcore-log: 
,07-12 11:37:23.804  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-12 11:37:23.804  3302  3353 I jxcore-log: 
,07-12 11:37:23.809  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-12 11:37:23.809  3302  3353 I jxcore-log: 
,07-12 11:37:23.826  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-12 11:37:23.826  3302  3353 I jxcore-log: 
,07-12 11:37:23.846  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-12 11:37:23.846  3302  3353 I jxcore-log: 
,07-12 11:37:23.900  3644  3663 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:37:23.935  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-12 11:37:23.935  3302  3353 I jxcore-log: 
,07-12 11:37:23.940  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-12 11:37:23.940  3302  3353 I jxcore-log: 
,07-12 11:37:23.967  3302  3353 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-12 11:37:23.967  3302  3353 I jxcore-log: 
,07-12 11:37:23.980  3302  3353 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-12 11:37:23.982  3302  3353 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-12 11:37:23.982  3302  3353 I jxcore-log: 
,07-12 11:37:24.035  3302  3353 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-12 11:37:24.035  3302  3353 I jxcore-log: 
,07-12 11:37:24.037  3302  3353 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-12 11:37:24.037  3302  3353 I jxcore-log: 
07-12 11:37:24.037  3302  3353 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-12 11:37:24.037  3302  3353 I jxcore-log: 
,07-12 11:37:24.224  3770  3770 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,07-12 11:37:24.232  3770  3770 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,07-12 11:37:25.341   872  1696 I ActivityManager: Killing 2577:com.android.vending/u0a19 (adj 15): empty #17
,07-12 11:37:25.626   872  1307 D ConnectivityService: handlePromptUnvalidated 100
,07-12 11:37:28.058  3755  3783 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,07-12 11:37:28.953   872   882 I ActivityManager: Start proc 3825:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,07-12 11:37:29.046  3825  3825 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,07-12 11:37:29.129  3825  3825 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,07-12 11:37:29.195  3825  3825 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,07-12 11:37:29.210  3825  3825 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:37:29.211  3825  3825 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,07-12 11:37:29.249   872  1751 I ActivityManager: Killing 1804:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,07-12 11:37:29.274  3825  3836 D Finsky  : [321] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,07-12 11:37:29.311   872  1305 D WifiService: Client connection lost with reason: 4
,07-12 11:37:29.323  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:29.331  3825  3825 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,07-12 11:37:29.331  3825  3825 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,07-12 11:37:29.333  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:29.339  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:29.347  3825  3859 D Ads     : Skipping gmscore version check
,07-12 11:37:29.373  3825  3859 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-12 11:37:29.386  3825  3825 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,07-12 11:37:29.403  1519  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 11:37:29.404  1519  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-12 11:37:29.404  1519  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:37:29.405  1519  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:29.409  3825  3825 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,07-12 11:37:29.436  3825  3836 D Finsky  : [321] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,07-12 11:37:29.458   872  1384 I ActivityManager: Killing 3412:com.android.settings/1000 (adj 15): empty #17
,07-12 11:37:34.221  3825  3825 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-12 11:37:34.266  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:34.414  1519  3864 I VacuumService: Vacuum at: now=1468316254413 tag=VacuumService
,07-12 11:37:34.415  1519  1519 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:37:34.458  1519  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 11:37:34.458  1519  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-12 11:37:34.458  1519  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:37:34.458  1519  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:34.475  3825  3825 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-12 11:37:34.482  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:34.526  1519  1885 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-12 11:37:34.526  1519  1885 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-12 11:37:34.526  1519  1885 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:34.526  1519  1885 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:34.561  3825  3870 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-12 11:37:34.564  3825  3825 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
07-12 11:37:34.564  3825  3825 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,07-12 11:37:34.570  1519  1885 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-12 11:37:34.571  1519  1885 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-12 11:37:34.571  1519  1885 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:34.571  1519  1885 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:34.597  3825  3825 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-12 11:37:34.597  3825  3825 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-12 11:37:34.598  3825  3825 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-12 11:37:34.634  1519  1885 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 11:37:34.634  1519  1885 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-12 11:37:34.635  1519  1885 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:37:34.635  1519  1885 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:34.667  3825  3825 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-12 11:37:34.967  1519  3865 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
07-12 11:37:34.968  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:34.990  1519  3875 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,07-12 11:37:34.992  1519  3875 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-12 11:37:35.018  1519  3130 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 11:37:35.018  1519  3130 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-12 11:37:35.018  1519  3130 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:37:35.018  1519  3130 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:35.022  1519  3875 W Uploader:  no longer exists, so no auth token.
,07-12 11:37:35.059  3825  3825 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
07-12 11:37:35.059  3825  3825 D Finsky  : [1] WearSupportService.startHygiene: disabled
,07-12 11:37:35.061  3825  3825 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,07-12 11:37:35.065  3825  3825 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6)
,07-12 11:37:35.072  3825  3879 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-12 11:37:35.427  1519  3875 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-12 11:37:35.428  1519  3875 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-12 11:37:35.428  1519  3875 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:35.428  1519  3875 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:35.467  1519  3875 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 11:37:35.467  1519  3875 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-12 11:37:35.467  1519  3875 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-12 11:37:36.041  1519  3875 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-12 11:37:36.041  1519  3875 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-12 11:37:36.041  1519  3875 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:37:36.041  1519  3875 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:36.066  1519  3875 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 11:37:36.066  1519  3875 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-12 11:37:36.066  1519  3875 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-12 11:37:36.355  1519  3875 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
07-12 11:37:36.355  1519  3875 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-12 11:37:36.355  1519  3875 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:36.355  1519  3875 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:36.392  1519  3875 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 11:37:36.392  1519  3875 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-12 11:37:36.392  1519  3875 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-12 11:37:36.607  1519  3875 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-12 11:37:36.608  1519  3875 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-12 11:37:36.608  1519  3875 I GLSUser : [GLSUser] Extracting token using key: Auth,
07-12 11:37:36.608  1519  3875 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:36.660  1519  3875 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 11:37:36.660  1519  3875 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-12 11:37:36.660  1519  3875 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-12 11:37:37.781  1519  3875 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,07-12 11:37:37.781  1519  3875 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
07-12 11:37:37.782  1519  3875 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:37:37.799  1519  3875 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:37.835  1519  3875 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 11:37:37.835  1519  3875 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
07-12 11:37:37.835  1519  3875 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,07-12 11:37:50.925  3644  3883 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:37:50.941  3644  3884 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 11:37:50.964  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:50.966  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:51.001  1519  2056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:37:51.001  1519  2056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:37:51.001  1519  2056 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:51.001  1519  2056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:51.053  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:51.055  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:51.098  1519  2056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 11:37:51.098  1519  2056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 11:37:51.098  1519  2056 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:51.098  1519  2056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:51.116  3644  3884 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:37:51.117  3644  3883 E BooksSync: Soft error
07-12 11:37:51.117  3644  3883 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:37:51.117  3644  3883 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:37:51.117  3644  3883 E BooksSync: Sync error
07-12 11:37:51.117  3644  3883 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:37:51.117  3644  3883 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 11:37:51.118  3644  3883 I BooksSync: Finished books sync
,07-12 11:37:51.126   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 199334, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:37:51.320  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:51.321  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:37:51.357  1519  1887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 11:37:51.357  1519  1887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-12 11:37:51.357  1519  1887 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:37:51.357  1519  1887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:51.372  2845  3888 V KeepSync: Connecting to GoogleApiClient
07-12 11:37:51.373   872  1726 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 11:37:51.384  3099  3887 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 11:37:51.384  3099  3887 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at blb.a(PG:3937)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at czp.a(PG:18188)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at czp.a(PG:9087)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:37:51.384  3099  3887 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	... 12 more
07-12 11:37:51.384  3099  3887 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at fal.a(PG:38)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:37:51.384  3099  3887 E HttpOperation: 	... 14 more
,07-12 11:37:51.476  1519  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 11:37:51.476  1519  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 11:37:51.477  1519  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:51.477  1519  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:51.576  1867  3889 V BaseAuthAsyncOperation: access token request failed
,07-12 11:37:51.578  2845  3888 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:37:51.670  1519  2056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 11:37:51.670  1519  2056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.,
07-12 11:37:51.670  1519  2056 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:51.670  1519  2056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:51.690  3099  3891 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 11:37:51.690  3099  3891 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at blb.a(PG:3937)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at czp.a(PG:18188)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:37:51.690  3099  3891 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	... 12 more
07-12 11:37:51.690  3099  3891 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at fal.a(PG:38)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:37:51.690  3099  3891 E HttpOperation: 	... 14 more
,07-12 11:37:51.720  1519  1885 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-12 11:37:51.720  1519  1885 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 11:37:51.720  1519  1885 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:37:51.720  1519  1885 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:51.752  1519  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 11:37:51.753  1519  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 11:37:51.753  1519  2057 I GLSUser : [GLSUser] Extracting token using key: Auth,
07-12 11:37:51.753  1519  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:37:51.765  3099  3891 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 11:37:51.765  3099  3891 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at hec.a(PG:42)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at hee.a(PG:102)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at czr.a(PG:65)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at kka.a(PG:108)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at czp.a(PG:19176)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:37:51.765  3099  3891 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	... 15 more
07-12 11:37:51.765  3099  3891 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at fal.a(PG:38)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:37:51.765  3099  3891 E HttpOperation: 	... 17 more
,07-12 11:37:51.765  3099  3891 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 11:37:51.765  3099  3891 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at hec.a(PG:42)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at hee.a(PG:102)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at czr.a(PG:65)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at kka.a(PG:108)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	... 15 more
,07-12 11:37:51.765  3099  3891 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at fal.a(PG:38)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 11:37:51.765  3099  3891 E ExperimentLoader: 	... 17 more
,07-12 11:37:51.784  2845  3888 E KeepSync: IOException
07-12 11:37:51.784  2845  3888 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:37:51.784  2845  3888 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:37:51.784  2845  3888 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:37:51.784  2845  3888 E KeepSync: 	... 10 more
,07-12 11:37:51.784  2845  3888 W KeepSync: Sync result 2
,07-12 11:37:51.791   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 199768, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:37:51.982   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 167407, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:38:03.364  1653  1704 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-12 11:38:03.364  1653  1704 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-12 11:38:03.399  1519  1519 I ConfigService: onCreate
,07-12 11:38:08.184  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:08.185  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:08.203  3369  3894 V GoogleAuthProtoRequest: [284] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:38:08.259  1519  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-12 11:38:08.260  1519  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 11:38:08.260  1519  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:38:08.260  1519  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: [284] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: [284] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.,
07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:38:08.280  3369  3894 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:38:08.394  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:08.428  1519  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-12 11:38:08.428  1519  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-12 11:38:08.428  1519  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:08.428  1519  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:08.451  1519  1519 I ConfigService: onDestroy
,07-12 11:38:08.479  3825  3825 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-12 11:38:08.479  3825  3825 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-12 11:38:08.479  3825  3825 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-12 11:38:10.603   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=219250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:38:24.571  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:24.575  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:24.608  1519  1887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-12 11:38:24.608  1519  1887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 11:38:24.608  1519  1887 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:24.608  1519  1887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:24.627  3099  3898 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 11:38:24.627  3099  3898 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at blb.a(PG:3937)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at czp.a(PG:18188)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:38:24.627  3099  3898 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	... 12 more
07-12 11:38:24.627  3099  3898 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at fal.a(PG:38)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:38:24.627  3099  3898 E HttpOperation: 	... 14 more
,07-12 11:38:24.669  1519  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 11:38:24.669  1519  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-12 11:38:24.669  1519  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:24.670  1519  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:24.689  3099  3898 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 11:38:24.689  3099  3898 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at hec.a(PG:42)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at hee.a(PG:102)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at czr.a(PG:65)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at kka.a(PG:108)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at czp.a(PG:19176)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:38:24.689  3099  3898 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	... 15 more
07-12 11:38:24.689  3099  3898 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at fal.a(PG:38)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:38:24.689  3099  3898 E HttpOperation: 	... 17 more
,07-12 11:38:24.689  3099  3898 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 11:38:24.689  3099  3898 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at hec.a(PG:42)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at hee.a(PG:102)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at czr.a(PG:65)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at kka.a(PG:108)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	... 15 more
07-12 11:38:24.689  3099  3898 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at fal.a(PG:38)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 11:38:24.689  3099  3898 E ExperimentLoader: 	... 17 more
,07-12 11:38:24.892   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 232968, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:38:28.743  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:28.830  1519  2056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-12 11:38:28.831  1519  2056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-12 11:38:28.831  1519  2056 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:28.832  1519  2056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:28.909  3825  3825 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-12 11:38:28.910  3825  3825 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-12 11:38:28.911  3825  3825 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-12 11:38:55.160  3644  3901 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:38:55.207  3644  3903 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 11:38:55.223  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:55.226  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:55.245  2845  3902 V KeepSync: Connecting to GoogleApiClient
,07-12 11:38:55.250   872  1751 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 11:38:55.270  1519  1887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:38:55.270  1519  1887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:38:55.270  1519  1887 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:55.270  1519  1887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:55.339  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:55.341  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:55.357  1519  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:38:55.358  1519  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:38:55.358  1519  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:55.358  1519  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:55.373  3644  3903 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:38:55.374  3644  3901 E BooksSync: Soft error
07-12 11:38:55.374  3644  3901 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:38:55.374  3644  3901 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 11:38:55.374  3644  3901 E BooksSync: Sync error
07-12 11:38:55.374  3644  3901 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:38:55.374  3644  3901 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:38:55.374  3644  3901 I BooksSync: Finished books sync
,07-12 11:38:55.385  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:55.389  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:38:55.398   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 261786, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:38:55.410  1519  1887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-12 11:38:55.410  1519  1887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 11:38:55.410  1519  1887 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:38:55.410  1519  1887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:55.425  1867  3904 V BaseAuthAsyncOperation: access token request failed
07-12 11:38:55.426  2845  3902 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:38:55.483  1519  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-12 11:38:55.483  1519  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-12 11:38:55.483  1519  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:38:55.483  1519  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:38:55.505  2845  3902 E KeepSync: IOException
07-12 11:38:55.505  2845  3902 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:38:55.505  2845  3902 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:38:55.505  2845  3902 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:38:55.505  2845  3902 E KeepSync: 	... 10 more
07-12 11:38:55.505  2845  3902 W KeepSync: Sync result 2
,07-12 11:38:55.526   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 263217, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:39:08.390  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:39:08.392  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:39:08.407  3369  3907 V GoogleAuthProtoRequest: [285] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:39:08.436  1519  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-12 11:39:08.437  1519  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-12 11:39:08.437  1519  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:39:08.437  1519  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:39:08.454  3369  3907 W ExperimentUpdateService: [285] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: [285] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:39:08.455  3369  3907 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:39:29.900  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:39:29.902  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:39:29.940  1519  3130 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 11:39:29.940  1519  3130 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 11:39:29.940  1519  3130 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:39:29.940  1519  3130 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:39:29.958  3099  3913 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 11:39:29.958  3099  3913 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at blb.a(PG:3937)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at czp.a(PG:18188)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:39:29.958  3099  3913 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	... 12 more
07-12 11:39:29.958  3099  3913 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at fal.a(PG:38)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:39:29.958  3099  3913 E HttpOperation: 	... 14 more
,07-12 11:39:30.037  1519  1885 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 11:39:30.037  1519  1885 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 11:39:30.038  1519  1885 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:39:30.038  1519  1885 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:39:30.072  3099  3913 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 11:39:30.072  3099  3913 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at hec.a(PG:42)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at hee.a(PG:102)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at czr.a(PG:65)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at kka.a(PG:108)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at czp.a(PG:19176)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:39:30.072  3099  3913 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	... 15 more
07-12 11:39:30.072  3099  3913 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at fal.a(PG:38)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:39:30.072  3099  3913 E HttpOperation: 	... 17 more
,07-12 11:39:30.072  3099  3913 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 11:39:30.072  3099  3913 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at hec.a(PG:42)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at hee.a(PG:102)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at czr.a(PG:65)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at kka.a(PG:108)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at czp.a(PG:19176),
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	... 15 more
07-12 11:39:30.072  3099  3913 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at fal.a(PG:38)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 11:39:30.072  3099  3913 E ExperimentLoader: 	... 17 more
,07-12 11:39:30.231   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 298215, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:40:08.494  1519  1976 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:40:09.690   872  1378 I ActivityManager: Killing 3435:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,07-12 11:40:59.514  3644  3918 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:40:59.549  3644  3919 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 11:40:59.566  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:40:59.570  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:40:59.617  1519  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 11:40:59.617  1519  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 11:40:59.618  1519  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:40:59.618  1519  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:40:59.655  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:40:59.657  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:40:59.699  1519  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:40:59.699  1519  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:40:59.700  1519  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:40:59.700  1519  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:40:59.731  3644  3919 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:40:59.732  3644  3918 E BooksSync: Soft error
07-12 11:40:59.732  3644  3918 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:40:59.732  3644  3918 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:40:59.732  3644  3918 E BooksSync: Sync error
07-12 11:40:59.732  3644  3918 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:40:59.732  3644  3918 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 11:40:59.735  3644  3918 I BooksSync: Finished books sync
,07-12 11:40:59.748   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 388070, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:41:23.030   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=411677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:41:30.032  2845  3922 V KeepSync: Connecting to GoogleApiClient
07-12 11:41:30.033   872   882 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 11:41:30.068  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:41:30.070  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:41:30.095  1519  3130 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 11:41:30.095  1519  3130 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-12 11:41:30.095  1519  3130 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:41:30.095  1519  3130 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:41:30.113  1867  3923 V BaseAuthAsyncOperation: access token request failed
,07-12 11:41:30.114  2845  3922 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:41:30.162  1519  1885 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-12 11:41:30.162  1519  1885 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-12 11:41:30.162  1519  1885 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:41:30.162  1519  1885 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:41:30.185  2845  3922 E KeepSync: IOException
07-12 11:41:30.185  2845  3922 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:41:30.185  2845  3922 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:41:30.185  2845  3922 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:41:30.185  2845  3922 E KeepSync: 	... 10 more
,07-12 11:41:30.185  2845  3922 W KeepSync: Sync result 2
,07-12 11:41:30.200   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 389729, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:41:38.513  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:41:38.516  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:41:38.532  3369  3925 V GoogleAuthProtoRequest: [286] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:41:38.569  1519  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-12 11:41:38.569  1519  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-12 11:41:38.569  1519  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:41:38.569  1519  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: [286] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: [286] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:41:38.594  3369  3925 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:41:55.777   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=444424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:42:00.579  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:42:00.583  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:42:00.625  1519  3130 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-12 11:42:00.625  1519  3130 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 11:42:00.625  1519  3130 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:42:00.625  1519  3130 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:42:00.648  3099  3927 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 11:42:00.648  3099  3927 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at blb.a(PG:3937)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at czp.a(PG:18188)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:42:00.648  3099  3927 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	... 12 more
07-12 11:42:00.648  3099  3927 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at fal.a(PG:38)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:42:00.648  3099  3927 E HttpOperation: 	... 14 more
,07-12 11:42:00.689  1519  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 11:42:00.690  1519  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-12 11:42:00.690  1519  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:42:00.690  1519  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:42:00.715  3099  3927 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 11:42:00.715  3099  3927 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at hec.a(PG:42)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at hee.a(PG:102)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at czr.a(PG:65)
,07-12 11:42:00.715  3099  3927 E HttpOperation: 	at kka.a(PG:108)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at czp.a(PG:19176)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:42:00.715  3099  3927 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	... 15 more
07-12 11:42:00.715  3099  3927 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at fal.a(PG:38)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:42:00.715  3099  3927 E HttpOperation: 	... 17 more
07-12 11:42:00.716  3099  3927 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 11:42:00.716  3099  3927 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at hec.a(PG:42)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at hee.a(PG:102)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at czr.a(PG:65)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at kka.a(PG:108)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	... 15 more
07-12 11:42:00.716  3099  3927 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at fal.a(PG:38)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 11:42:00.716  3099  3927 E ExperimentLoader: 	... 17 more
,07-12 11:42:00.810   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 428231, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:42:22.817   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=471464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:42:29.322  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:42:29.335  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:42:29.340  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:42:29.383  1519  3130 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-12 11:42:29.383  1519  3130 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-12 11:42:29.383  1519  3130 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:42:29.383  1519  3130 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:42:29.418  1519  3130 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-12 11:42:29.418  1519  3130 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-12 11:42:29.418  1519  3130 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-12 11:42:29.418  1519  3130 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-12 11:42:29.418  1519  3130 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-12 11:42:29.418  1519  3130 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-12 11:42:29.418  1519  3130 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 11:42:29.430  3825  3854 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-12 11:42:29.430  3825  3854 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-12 11:42:29.430  3825  3854 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-12 11:42:29.430  3825  3854 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-12 11:42:29.430  3825  3854 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-12 11:42:29.430  3825  3854 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-12 11:42:29.430  3825  3854 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-12 11:43:02.444   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=511091, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:43:24.417   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=533064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:43:57.163   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=565810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:45:07.998  3644  3949 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:45:08.045  3644  3950 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 11:45:08.071  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:08.078  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:08.113  1519  2056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-12 11:45:08.113  1519  2056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 11:45:08.113  1519  2056 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:45:08.114  1519  2056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-12 11:45:08.151  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:08.153  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:08.193  1519  3130 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:45:08.193  1519  3130 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 11:45:08.193  1519  3130 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:45:08.193  1519  3130 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:45:08.218  3644  3950 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:45:08.219  3644  3949 E BooksSync: Soft error
07-12 11:45:08.219  3644  3949 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:45:08.219  3644  3949 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-12 11:45:08.219  3644  3949 E BooksSync: Sync error
07-12 11:45:08.219  3644  3949 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:45:08.219  3644  3949 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:45:08.220  3644  3949 I BooksSync: Finished books sync
,07-12 11:45:08.232   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 636444, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:45:38.753  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:38.754  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:45:38.763  3369  3953 V GoogleAuthProtoRequest: [287] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:45:38.782  1519  1887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-12 11:45:38.782  1519  1887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-12 11:45:38.782  1519  1887 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:45:38.782  1519  1887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:45:38.795  3369  3953 W ExperimentUpdateService: [287] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: [287] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:45:38.796  3369  3953 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:45:41.424  2845  3954 V KeepSync: Connecting to GoogleApiClient
,07-12 11:45:41.424   872  1678 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 11:45:41.486  1519  2057 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-12 11:45:41.486  1519  2057 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-12 11:45:41.486  1519  2057 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:45:41.486  1519  2057 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:45:41.504  1867  3955 V BaseAuthAsyncOperation: access token request failed
,07-12 11:45:41.505  2845  3954 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:45:41.552  1519  2056 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-12 11:45:41.552  1519  2056 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-12 11:45:41.552  1519  2056 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:45:41.552  1519  2056 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:45:41.572  2845  3954 E KeepSync: IOException
07-12 11:45:41.572  2845  3954 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:45:41.572  2845  3954 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:45:41.572  2845  3954 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:45:41.572  2845  3954 E KeepSync: 	... 10 more
,07-12 11:45:41.572  2845  3954 W KeepSync: Sync result 2
,07-12 11:45:41.587   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 669960, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:46:19.894  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:46:19.896  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:46:19.941  1519  1887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-12 11:46:19.942  1519  1887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 11:46:19.942  1519  1887 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:46:19.942  1519  1887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:46:19.972  3099  3958 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 11:46:19.972  3099  3958 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at blb.a(PG:3937)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at czp.a(PG:18188)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:46:19.972  3099  3958 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	... 12 more
07-12 11:46:19.972  3099  3958 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at fal.a(PG:38)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:46:19.972  3099  3958 E HttpOperation: 	... 14 more
,07-12 11:46:20.051  1519  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 11:46:20.051  1519  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 11:46:20.051  1519  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:46:20.051  1519  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:46:20.077  3099  3958 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 11:46:20.077  3099  3958 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at hec.a(PG:42)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at hee.a(PG:102)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at czr.a(PG:65)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at kka.a(PG:108)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at czp.a(PG:19176)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:46:20.077  3099  3958 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	... 15 more
07-12 11:46:20.077  3099  3958 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at fal.a(PG:38)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:46:20.077  3099  3958 E HttpOperation: 	... 17 more
,07-12 11:46:20.077  3099  3958 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 11:46:20.077  3099  3958 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at hec.a(PG:42)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at hee.a(PG:102)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at czr.a(PG:65)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: ,	at kka.a(PG:108)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	... 15 more
07-12 11:46:20.077  3099  3958 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at fal.a(PG:38)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 11:46:20.077  3099  3958 E ExperimentLoader: 	... 17 more
,07-12 11:46:20.207   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 708162, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:46:35.217   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=723864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:47:07.990   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=756637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:47:34.777   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=783424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-12 11:48:07.510   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=816157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:48:20.075  1519  1976 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-12 11:53:08.579  1867  3980 I EventLogService: Opted in for usage reporting
07-12 11:53:08.580  1867  3980 I EventLogService: Aggregate from 1468315115613 (log), 1468315115613 (data)
,07-12 11:53:08.711  1867  3980 W EventLogAggregator: Unknown tag: snet_gcore
07-12 11:53:08.711  1867  3980 W EventLogAggregator: Unknown tag: snet_launch_service
,07-12 11:53:08.770  1867  3980 I ServiceDumpSys: dumping service [account]
,07-12 11:53:13.536   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1122183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-12 11:53:17.550   872  3472 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1126197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-12 11:53:24.387  3644  3983 I BooksSync: Starting books sync for 61035162, extras: ade
,07-12 11:53:24.420  3644  3984 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-12 11:53:24.435  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:24.437  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:24.468  1519  3130 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:53:24.468  1519  3130 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-12 11:53:24.468  1519  3130 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:53:24.468  1519  3130 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:53:24.504  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:24.505  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:24.538  1519  1887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-12 11:53:24.538  1519  1887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-12 11:53:24.539  1519  1887 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:53:24.539  1519  1887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,07-12 11:53:24.562  3644  3984 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-12 11:53:24.563  3644  3983 E BooksSync: Soft error
07-12 11:53:24.563  3644  3983 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:53:24.563  3644  3983 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:53:24.564  3644  3983 E BooksSync: Sync error
07-12 11:53:24.564  3644  3983 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-12 11:53:24.564  3644  3983 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-12 11:53:24.564  3644  3983 I BooksSync: Finished books sync
,07-12 11:53:24.578   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1132976, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:53:38.877  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:38.878  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:53:38.888  3369  3986 V GoogleAuthProtoRequest: [288] a.<init>: mAccountName set to: thalitester@gmail.com
,07-12 11:53:38.907  1519  1535 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-12 11:53:38.907  1519  1535 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,07-12 11:53:38.907  1519  1535 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:53:38.907  1519  1535 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:53:38.920  3369  3986 W ExperimentUpdateService: [288] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: [288] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: 	,at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-12 11:53:38.921  3369  3986 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-12 11:54:03.996  2845  3987 V KeepSync: Connecting to GoogleApiClient
07-12 11:54:03.996   872  1696 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-12 11:54:04.036  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:54:04.039  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:54:04.061  1519  1887 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-12 11:54:04.061  1519  1887 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,07-12 11:54:04.061  1519  1887 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:54:04.061  1519  1887 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:54:04.078  1867  3988 V BaseAuthAsyncOperation: access token request failed
,07-12 11:54:04.079  2845  3987 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-12 11:54:04.148  1519  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-12 11:54:04.148  1519  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-12 11:54:04.148  1519  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-12 11:54:04.148  1519  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:54:04.165  2845  3987 E KeepSync: IOException
07-12 11:54:04.165  2845  3987 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-12 11:54:04.165  2845  3987 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-12 11:54:04.165  2845  3987 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-12 11:54:04.165  2845  3987 E KeepSync: 	... 10 more
07-12 11:54:04.165  2845  3987 W KeepSync: Sync result 2
,07-12 11:54:04.177   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1172459, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-12 11:54:49.166   872   884 I UsageStatsService: User[0] Flushing usage stats to disk
,07-12 11:54:57.883  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:54:57.885  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-12 11:54:57.935  1519  3130 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-12 11:54:57.935  1519  3130 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-12 11:54:57.936  1519  3130 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:54:57.936  1519  3130 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:54:57.965  3099  3992 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-12 11:54:57.965  3099  3992 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at blb.a(PG:3937)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at czp.a(PG:18188)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:54:57.965  3099  3992 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	... 12 more
07-12 11:54:57.965  3099  3992 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at fal.a(PG:38)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:54:57.965  3099  3992 E HttpOperation: 	... 14 more
,07-12 11:54:58.020  1519  1885 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-12 11:54:58.020  1519  1885 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-12 11:54:58.020  1519  1885 I GLSUser : [GLSUser] Extracting token using key: Auth
07-12 11:54:58.021  1519  1885 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-12 11:54:58.040  3099  3992 E HttpOperation: [getmobileexperiments] Unexpected exception
07-12 11:54:58.040  3099  3992 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at jdm.a(PG:82)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at jcs.o(PG:406)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at jcn.a(PG:1379)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at jcs.i(PG:143)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at hec.a(PG:42)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at hee.a(PG:102)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at czr.a(PG:65)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at kka.a(PG:108)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at czp.a(PG:19176)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at czp.a(PG:9081)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at czq.run(PG:1686)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:54:58.040  3099  3992 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at jdj.a(PG:4091)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at jdj.a(PG:1125)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at jdm.a(PG:77)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	... 15 more
07-12 11:54:58.040  3099  3992 E HttpOperation: Caused by: faj: BadAuthentication
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at fal.a(PG:38)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	at jdj.a(PG:4089)
07-12 11:54:58.040  3099  3992 E HttpOperation: 	... 17 more
,07-12 11:54:58.041  3099  3992 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-12 11:54:58.041  3099  3992 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at jdm.a(PG:82)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at jcs.o(PG:406)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at jcn.a(PG:1379)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at jcs.i(PG:143)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at hec.a(PG:42)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at hee.a(PG:102)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at czr.a(PG:65)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at kka.a(PG:108)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at czp.a(PG:19176)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at czp.a(PG:9081)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at czq.run(PG:1686)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
,07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at jdj.a(PG:4091)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at jdj.a(PG:1125)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at jdm.a(PG:77)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	... 15 more
07-12 11:54:58.041  3099  3992 E ExperimentLoader: Caused by: faj: BadAuthentication
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at fal.a(PG:38)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	at jdj.a(PG:4089)
07-12 11:54:58.041  3099  3992 E ExperimentLoader: 	... 17 more
,07-12 11:54:58.180   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1226263, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1400000ms),07-12 12:00:33.636  4009  4009 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-12 12:00:33.641  4009  4009 D AndroidRuntime: CheckJNI is OFF
07-12 12:00:33.677  4009  4009 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-12 12:00:33.720  4009  4009 I Radio-JNI: register_android_hardware_Radio DONE
07-12 12:00:33.740  4009  4009 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-12 12:00:33.753   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
07-12 12:00:33.753   872   885 I ActivityManager: Killing 3302:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
07-12 12:00:33.856   872  1726 D GraphicsStats: Buffer count: 2
07-12 12:00:33.856   872  1751 I WindowState: WIN DEATH: Window{8cbe127 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-12 12:00:33.857   872  1305 D WifiService: Client connection lost with reason: 4
07-12 12:00:33.920   872   895 W PackageSettings: Skipping PackageSetting{507f759 com.example.hello/10273} due to missing metadata
07-12 12:00:33.947   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-12 12:00:33.947   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
07-12 12:00:33.948   872   885 E ActivityManager: Failure starting process com.test.thalitest
07-12 12:00:33.948   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-12 12:00:33.948   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 12:00:33.948   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-12 12:00:33.948   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 12:00:33.948   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-12 12:00:33.948   872   885 I ActivityManager:   Force finishing activity ActivityRecord{935e6c8 u0 com.test.thalitest/.MainActivity t10}
07-12 12:00:33.953   872   895 I art     : Starting a blocking GC Explicit
07-12 12:00:33.964   872  1678 W ActivityManager: Spurious death for ProcessRecord{2df00a3 0:com.test.thalitest/u0a0}, curProc for 3302: null
07-12 12:00:34.024   872   895 I art     : Explicit concurrent mark sweep GC freed 40982(2MB) AllocSpace objects, 11(220KB) LOS objects, 33% free, 28MB/43MB, paused 894us total 69.387ms
07-12 12:00:34.036   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
07-12 12:00:34.040  4009  4009 I art     : System.exit called, status: 0
07-12 12:00:34.040  4009  4009 I AndroidRuntime: VM exiting with result code 0.
07-12 12:00:34.059   872   895 I ActivityManager: Start proc 4021:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
07-12 12:00:34.062   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
07-12 12:00:34.077   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
07-12 12:00:34.080  3359  3359 D BluetoothMapAppObserver: onReceive
07-12 12:00:34.080  3359  3359 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-12 12:00:34.085  1841  2008 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-12 12:00:34.088   872  1295 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-12 12:00:34.089  3175  3175 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
07-12 12:00:34.093  1653  1653 I Keyboard.Facilitator: resetDictionaries() : en_US
07-12 12:00:34.097  1653  4034 I Keyboard.Facilitator.DecoderInitializer: run()
07-12 12:00:34.122   872  1752 I ActivityManager: Start proc 4036:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
07-12 12:00:34.124  1653  4034 I Decoder : createOrResetDecoder
07-12 12:00:34.128  1739  1739 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
07-12 12:00:34.155   872  1378 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3302 uid 10000
07-12 12:00:34.161  1653  1653 I Keyboard.Facilitator: onFinishInput()
07-12 12:00:34.173   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-12 12:00:34.189   872  1384 I ActivityManager: Killing 3528:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
07-12 12:00:34.198  4036  4036 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
07-12 12:00:34.224  1519  1519 I ConfigService: onCreate
07-12 12:00:34.226  4036  4036 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
07-12 12:00:34.242   872   883 I ActivityManager: Start proc 4053:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
07-12 12:00:34.272  1755  1827 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
07-12 12:00:34.273   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
07-12 12:00:34.273   872   884 E PackageManager: Failed to write settings, restoring backup
07-12 12:00:34.273   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-12 12:00:34.273   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-12 12:00:34.273   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-12 12:00:34.273   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-12 12:00:34.273   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-12 12:00:34.273   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 12:00:34.273   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-12 12:00:34.273   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 12:00:34.255  4036  4054 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-12 12:00:34.278   872   885 E DropBoxManagerService: Can't write: system_server_wtf
07-12 12:00:34.278   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-12 12:00:34.278   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 12:00:34.278   872   885 E DropBoxManagerService: 	... 13 more
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-12 12:00:34.284  1519  4052 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-12 12:00:34.286   872  1378 I ActivityManager: Start proc 4066:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
07-12 12:00:34.286  1755  1827 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-12 12:00:34.286  1755  1827 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1755
07-12 12:00:34.286  1755  1827 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-12 12:00:34.286  1755  1827 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 12:00:34.289   872  1726 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-12 12:00:34.289   872  4075 E DropBoxManagerService: Can't write: system_app_crash
07-12 12:00:34.289   872  4075 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 12:00:34.289   872  4075 E DropBoxManagerService: 	... 5 more
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-12 12:00:34.290  1519  4052 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-12 12:00:34.293  1519  4052 W SQLiteOpenHelper: Opened config.db in read-only mode
07-12 12:00:34.296  1755  1827 I Process : Sending signal. PID: 1755 SIG: 9
07-12 12:00:34.315  4053  4053 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-12 12:00:34.317  4036  4054 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-12 12:00:34.317  4036  4054 E AndroidRuntime: Process: android.process.acore, PID: 4036
07-12 12:00:34.317  4036  4054 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-12 12:00:34.317  4036  4054 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: Can't write: system_app_crash
07-12 12:00:34.319   872  4080 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 12:00:34.319   872  4080 E DropBoxManagerService: 	... 5 more
07-12 12:00:34.325  4036  4054 I Process : Sending signal. PID: 4036 SIG: 9
07-12 12:00:34.329  1653  4034 I Keyboard.Facilitator.MainLanguageModelLoader: run()
07-12 12:00:34.381  1519  1519 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
07-12 12:00:34.382   279   279 E lowmemorykiller: Error writing /proc/4036/oom_score_adj; errno=22
07-12 12:00:34.384  1519  1519 D AndroidRuntime: Shutting down VM
07-12 12:00:34.385  1519  1519 E AndroidRuntime: FATAL EXCEPTION: main
07-12 12:00:34.385  1519  1519 E AndroidRuntime: Process: com.google.process.gapps, PID: 1519
07-12 12:00:34.385  1519  1519 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
07-12 12:00:34.385  1519  1519 E AndroidRuntime: 	... 8 more
07-12 12:00:34.387   872  4086 E DropBoxManagerService: Can't write: system_app_crash
07-12 12:00:34.387   872  4086 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-12 12:00:34.387   872  4086 E DropBoxManagerService: 	... 5 more
07-12 12:00:34.387  1519  1519 I Process : Sending signal. PID: 1519 SIG: 9
07-12 12:00:34.402  1653  4034 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
07-12 12:00:34.404  1653  4034 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-12 12:00:34.404  1653  4034 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
07-12 12:00:34.406  1653  4034 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-12 12:00:34.406  1653  4034 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
07-12 12:00:34.407  1653  4034 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-12 12:00:34.407  1653  4034 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-12 12:00:34.408  1653  4034 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-12 12:00:34.408  1653  4034 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-12 12:00:34.408  1653  4034 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-12 12:00:34.408  1653  4034 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-12 12:00:34.408  1653  4034 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-12 12:00:34.408  1653  4034 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
07-12 12:00:34.431   279   279 E lowmemorykiller: Error writing /proc/4036/oom_score_adj; errno=22
07-12 12:00:34.450   872  1696 I ActivityManager: Killing 3549:com.android.chrome/u0a40 (adj 15): empty #17
07-12 12:00:34.463   872   883 I WindowState: WIN DEATH: Window{592a9a u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
07-12 12:00:34.465   872  1752 D GraphicsStats: Buffer count: 1
07-12 12:00:34.480   872  1305 D WifiService: Client connection lost with reason: 4
07-12 12:00:34.534   872   883 I ActivityManager: Process com.google.process.gapps (pid 1519) has died
07-12 12:00:34.534   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
07-12 12:00:34.534   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
07-12 12:00:34.535   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.playlog.service.PlayLogBrokerService in 21000ms
07-12 12:00:34.535   872   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 30999ms
07-12 12:00:34.538   872  1763 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1755) has died
07-12 12:00:34.538   872  1763 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40996ms
07-12 12:00:34.539   872  1763 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-12 12:00:34.543  1867  1867 W RocketImpressions: ClearcutLogger connection suspended: 1
07-12 12:00:34.560   872  1726 I ActivityManager: Start proc 4092:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider

```
