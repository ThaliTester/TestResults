#### Test 79751015a5ad772_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
,08-10 17:04:11.376  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 17:04:11.396  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 17:04:11.402  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 17:04:11.480  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-10 17:04:11.480  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 17:04:11.480  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:11.480  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 17:04:11.529  2567  2567 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 17:04:11.530  2567  2567 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 17:04:11.531  2567  2567 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
08-10 17:04:12.034  3299  3299 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 17:04:12.038  3299  3299 D AndroidRuntime: CheckJNI is OFF
08-10 17:04:12.075  3299  3299 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 17:04:12.118  3299  3299 I Radio-JNI: register_android_hardware_Radio DONE
08-10 17:04:12.139  3299  3299 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 17:04:12.146   871  1662 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 17:04:12.199  3299  3299 D AndroidRuntime: Shutting down VM
08-10 17:04:12.202  1777  1797 W SearchService: Abort, client detached.
08-10 17:04:12.227  1777  1777 I HotwordDetector: Closing mic
08-10 17:04:12.227  1777  2088 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@f0c4c07
08-10 17:04:12.227  1777  2129 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-10 17:04:12.232   871  1370 I ActivityManager: Start proc 3309:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-10 17:04:12.251  1777  1777 W ErrorReporter: reportError [type: 29, code: 917507]: null
08-10 17:04:12.292   374  2131 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-10 17:04:12.295   374  2131 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-10 17:04:12.303   374  1275 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 17:04:12.307  1777  2102 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 17:04:12.310  1777  2128 I MicroRecognitionRnrImpl: Detection finished
08-10 17:04:12.314  3309  3309 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-10 17:04:12.336  3309  3309 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-10 17:04:12.349  3309  3309 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 9657-9666)
08-10 17:04:12.349  3309  3309 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 17:04:12.367  3309  3309 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {542e34}
08-10 17:04:12.370  3309  3309 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 17:04:12.370  3309  3309 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 17:04:12.376  3309  3309 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-10 17:04:12.378  3309  3309 E SysUtils: ApplicationContext is null in ApplicationStatus
08-10 17:04:12.419  3309  3324 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
08-10 17:04:12.426  3309  3309 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 17:04:12.436  3309  3309 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 17:04:12.436  3309  3309 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 17:04:12.436  3309  3309 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 17:04:12.436  3309  3309 I Adreno  : Build Date                       : 10/20/15
08-10 17:04:12.436  3309  3309 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 17:04:12.436  3309  3309 I Adreno  : Local Branch                     : M14
08-10 17:04:12.436  3309  3309 I Adreno  : Remote Branch                    : 
08-10 17:04:12.436  3309  3309 I Adreno  : Remote Branch                    : 
08-10 17:04:12.436  3309  3309 I Adreno  : Reconstruct Branch               : 
,08-10 17:04:12.529   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bb09fab:true
,08-10 17:04:12.559  3309  3309 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 17:04:12.570  3309  3309 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-10 17:04:12.644  3309  3348 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 17:04:12.658  3309  3333 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-10 17:04:12.712  3309  3348 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 17:04:12.768   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +561ms
,08-10 17:04:12.775  1642  1642 I Keyboard.Facilitator: onFinishInput()
,08-10 17:04:12.886  3309  3309 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3309
,08-10 17:04:13.046   871  2562 I ActivityManager: Killing 2686:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
,08-10 17:04:13.078   871  2562 I ActivityManager: Killing 2981:com.qualcomm.telephony/1001 (adj 15): empty #18
,08-10 17:04:13.084  3309  3309 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 17:04:13.219  3309  3350 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1679623888
,08-10 17:04:13.252  3309  3350 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 17:04:13.252  3309  3350 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 17:04:13.252  3309  3350 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 17:04:13.252  3309  3350 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 17:04:13.252  3309  3350 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 17:04:13.253  3309  3350 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0c8178 added. We now have 1 listener(s)
,08-10 17:04:13.266  3309  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-10 17:04:13.271  3309  3350 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 17:04:13.273  3309  3350 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 17:04:13.273  3309  3350 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-10 17:04:13.277  3309  3350 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@787d1b7 added. We now have 1 listener(s)
08-10 17:04:13.277  3309  3350 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 17:04:13.280  3309  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 17:04:13.280   871  1305 D WifiService: New client listening to asynchronous messages
08-10 17:04:13.280  3309  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 17:04:13.281  3309  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 17:04:13.281  3309  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 17:04:13.281  3309  3350 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 17:04:13.284  3309  3350 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:04:13.284  3309  3350 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-10 17:04:13.287  3309  3350 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:13.287  3309  3350 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:04:13.287  3309  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:13.287  3309  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:13.287  3309  3350 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:13.287  3309  3350 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:13.287  3309  3350 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:13.287  3309  3350 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:13.287  3309  3350 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:04:13.287  3309  3350 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 17:04:13.287  3309  3350 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 17:04:13.288  3309  3350 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 17:04:13.409  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:04:13.412  3309  3309 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 17:04:14.689  3309  3358 W jxcore-log: Initializing JXcore engine
,08-10 17:04:14.689  3309  3358 W jxcore-log: JXcore engine is ready
,08-10 17:04:14.726  3358  3358 W Thread-281: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-10 17:04:14.726  3358  3358 W Thread-281: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[10618]" dev="sockfs" ino=10618 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-10 17:04:14.726  3358  3358 W Thread-281: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-10 17:04:14.726  3358  3358 W Thread-281: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[22935]" dev="sockfs" ino=22935 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-10 17:04:14.742  3309  3358 W jxcore-log: Starting JXcore engine
,08-10 17:04:14.826  3309  3358 W jxcore-log: Platform android
08-10 17:04:14.826  3309  3358 W jxcore-log: 
08-10 17:04:14.826  3309  3358 W jxcore-log: Process ARCH arm
08-10 17:04:14.826  3309  3358 W jxcore-log: 
,08-10 17:04:15.049  3309  3358 I jxcore-log: JXcore Cordova bridge is ready!
08-10 17:04:15.049  3309  3358 I jxcore-log: 
08-10 17:04:15.050  3309  3358 W jxcore-log: JXcore engine is started
,08-10 17:04:15.057  3309  3350 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 17:04:15.062  3309  3309 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 17:04:23.028   871   891 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-10 17:04:23.034  1642  1642 I Keyboard.Facilitator: onFinishInput()
,08-10 17:04:23.057   871   891 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 17:04:23.057   871   891 I Adreno  : Build Date                       : 10/20/15
08-10 17:04:23.057   871   891 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 17:04:23.057   871   891 I Adreno  : Local Branch                     : M14
08-10 17:04:23.057   871   891 I Adreno  : Remote Branch                    : 
08-10 17:04:23.057   871   891 I Adreno  : Remote Branch                    : 
08-10 17:04:23.057   871   891 I Adreno  : Reconstruct Branch               : 
,08-10 17:04:23.093   280   364 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (150 us)
,08-10 17:04:23.693  3309  3309 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 17:04:23.694  3309  3309 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-10 17:04:23.732   871   891 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-10 17:04:23.733  3309  3309 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8e492a Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@22e97ab, 16908290=android.view.AbsSavedState$1@22e97ab}, android:focusedViewId=100}]}]
,08-10 17:04:23.733  3309  3309 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-10 17:04:23.734  3309  3309 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-10 17:04:23.734  3309  3309 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-10 17:04:23.740   871   891 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-10 17:04:23.744   871   889 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-10 17:04:23.756   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-10 17:04:23.758   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-10 17:04:23.996   280   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-10 17:04:24.001   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-10 17:04:24.006   871  1329 D SurfaceControl: Excessive delay in setPowerMode(): 253ms
,08-10 17:04:24.010   871   891 I DreamManagerService: Entering dreamland.
,08-10 17:04:24.012   871   891 I PowerManagerService: Dozing...
08-10 17:04:24.013   871   886 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-10 17:04:24.094   374  1313 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-10 17:04:24.094   374  1313 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-10 17:04:24.114   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 17:04:24.123  1703  3365 D NfcService: Discovery configuration equal, not updating.
,08-10 17:04:24.124   871  1304 E native  : do suspend false
,08-10 17:04:24.170   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
08-10 17:04:24.173   871  1304 E native  : do suspend true
,08-10 17:04:24.225   374  1312 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-10 17:04:24.226   374  1312 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-10 17:04:28.432  1967  2299 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 17:04:30.983  3309  3358 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 17:04:30.983  3309  3358 I jxcore-log: 
,08-10 17:04:30.985  3309  3358 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 17:04:30.985  3309  3358 I jxcore-log: 
,08-10 17:04:30.987  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:30.987  3309  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:04:30.987  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:30.987  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:30.987  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:30.987  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:30.987  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:30.987  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:30.987  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:04:30.987  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:30.988  3309  3358 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:04:30.989  3309  3358 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 17:04:30.989  3309  3358 I jxcore-log: 
08-10 17:04:30.991  3309  3358 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 17:04:30.991  3309  3358 I jxcore-log: 
,08-10 17:04:31.318  3309  3358 I jxcore-log: Running unit tests
08-10 17:04:31.318  3309  3358 I jxcore-log: 
08-10 17:04:31.319  3309  3358 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 17:04:31.319  3309  3358 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94ede08 added. We now have 2 listener(s)
,08-10 17:04:31.320  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 17:04:31.320  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 17:04:31.320  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 17:04:31.321  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:04:31.321  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b29a1 added. We now have 2 listener(s)
,08-10 17:04:31.321  3309  3358 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 17:04:31.322  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 17:04:31.325  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:04:31.327  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:31.327  3309  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:04:31.327  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:31.327  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:31.327  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:31.327  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:31.327  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-10 17:04:31.327  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:31.327  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:04:31.328  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:31.328  3309  3358 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:04:31.329  3309  3358 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 17:04:31.330  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:04:31.330  3309  3358 D ExecuteNativeTests: Running unit tests
,08-10 17:04:31.417  3309  3358 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 17:04:31.417  3309  3358 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 added. We now have 3 listener(s)
08-10 17:04:31.418  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 17:04:31.419  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 17:04:31.419  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 17:04:31.419  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:04:31.419  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 added. We now have 3 listener(s)
08-10 17:04:31.419  3309  3358 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 17:04:31.420  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 17:04:31.421  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 17:04:31.422  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:31.422  3309  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:04:31.422  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:31.422  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:31.422  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:31.422  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:31.422  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:31.422  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:31.422  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:04:31.422  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:31.422  3309  3358 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:04:31.422  3309  3358 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 17:04:31.423  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:04:31.424  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 17:04:31.424  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 17:04:31.424  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1,
08-10 17:04:31.424  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 17:04:31.425  3309  3358 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-10 17:04:31.426  3309  3358 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 17:04:31.426  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 17:04:31.426  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:04:31.426  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:04:31.426  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:04:31.427  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:31.427  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:31.427  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 17:04:31.428  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:31.428  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:31.428  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 17:04:31.428  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 17:04:31.428  3309  3358 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 removed from the list
08-10 17:04:31.428  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:31.428  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 removed from the list
08-10 17:04:31.428  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:31.428  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:31.429  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:31.429  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:31.429  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 17:04:31.429  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:31.429  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:31.430  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:31.431  3309  3358 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-10 17:04:31.431  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:31.431  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:31.431  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:31.431  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 17:04:31.431  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:31.431  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:31.432  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
,08-10 17:04:31.432  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:31.432  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
,08-10 17:04:31.432  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:31.432  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:31.432  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:31.432  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:31.432  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:31.432  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:31.432  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 17:04:31.432  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:31.432  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 17:04:31.438  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610],
08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 17:04:31.439  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 17:04:31.439  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 17:04:31.439  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:31.439  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:31.439  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:31.439  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:31.439  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:31.440  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:31.440  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:31.440  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:31.440  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 17:04:31.440  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:31.440  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:31.440  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:31.440  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:31.440  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:31.440  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:31.440  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:31.441  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
,08-10 17:04:31.441  3309  3358 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 17:04:31.442  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:04:31.443  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:31.443  3309  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:04:31.443  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:31.443  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:31.443  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:31.443  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:31.443  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:31.443  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:31.443  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:04:31.446  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:31.446  3309  3358 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:04:31.446  3309  3358 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 17:04:31.446  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 17:04:31.446  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-10 17:04:31.446  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 17:04:31.446  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:04:31.446  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 17:04:31.447  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:04:31.448  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
08-10 17:04:31.449  3309  3358 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 17:04:31.449  3309  3358 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 17:04:31.449  3309  3358 I io.jxcore.node.ConnectionHelper: start: OK
08-10 17:04:31.449  3309  3309 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,08-10 17:04:31.951  3309  3309 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 17:04:31.988  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:04:32.012  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:04:32.021  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:04:32.116  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 17:04:32.117  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 17:04:32.117  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:32.118  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:04:32.174  2567  2567 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 17:04:32.176  2567  2567 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 17:04:32.180  2567  2567 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-10 17:04:36.453  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:36.455  3309  3358 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,08-10 17:04:36.459  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 17:04:36.460  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:36.460  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-10 17:04:36.460  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:36.461  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-10 17:04:36.461  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 17:04:36.461  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-10 17:04:36.462  3309  3358 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 17:04:36.462  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 17:04:36.465  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 17:04:36.467  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 17:04:36.468  3309  3358 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 17:04:36.470  3309  3309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 17:04:36.470  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:36.471  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:36.470  3309  3309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 17:04:36.471  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 17:04:36.471  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
,08-10 17:04:36.471  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:36.471  3309  3309 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 17:04:36.471  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:36.471  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 17:04:36.471  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:36.472  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:36.472  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:36.472  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:36.473  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:36.473  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:36.473  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:36.474  3309  3358 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-10 17:04:36.476  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:04:36.477  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:36.477  3309  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:04:36.477  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:36.477  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:36.477  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:36.477  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:36.477  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:36.477  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:36.477  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:04:36.477  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:36.477  3309  3358 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:04:36.477  3309  3358 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 17:04:36.477  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 17:04:36.477  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 17:04:36.477  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 17:04:36.477  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:04:36.477  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 17:04:36.486  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:04:36.486  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
,08-10 17:04:36.486  3309  3358 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
08-10 17:04:36.487  3309  3358 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-10 17:04:36.487  3309  3358 I io.jxcore.node.ConnectionHelper: start: OK
08-10 17:04:36.487  3309  3309 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,08-10 17:04:36.987  3309  3309 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 17:04:41.487  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:41.488  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:41.488  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-10 17:04:41.489  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:41.489  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-10 17:04:41.489  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 17:04:41.490  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 17:04:41.490  3309  3358 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 17:04:41.490  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 17:04:41.491  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 17:04:41.493  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 17:04:41.494  3309  3358 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 17:04:41.495  3309  3309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 17:04:41.496  3309  3309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 17:04:41.496  3309  3309 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 17:04:41.998  3309  3309 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 17:04:41.998  3309  3309 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:41.999  3309  3309 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-10 17:04:46.496  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 17:04:46.497  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:46.497  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:46.497  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 17:04:46.498  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:46.499  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 17:04:46.499  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:46.500  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:46.500  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.500  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 17:04:46.500  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.502  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:46.502  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:46.504  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 17:04:46.504  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:46.504  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:46.505  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.507  3309  3358 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-10 17:04:46.510  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 17:04:46.510  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:46.510  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:46.511  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:46.511  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.511  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.512  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
,08-10 17:04:46.512  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.513  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.514  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:46.514  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.514  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.514  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.514  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.514  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:46.514  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:46.515  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:46.515  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.516  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 17:04:46.516  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:46.516  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:46.516  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 17:04:46.516  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:46.516  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.516  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.516  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:46.516  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.517  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.517  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:46.517  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:46.517  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.517  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.517  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.517  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:46.517  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:46.517  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.518  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.518  3309  3358 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 17:04:46.518  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 17:04:46.518  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:46.519  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:46.519  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:46.519  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.519  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.519  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:46.519  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:46.519  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.519  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:46.519  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.519  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.519  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.519  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.520  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:46.520  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:46.521  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.521  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.521  3309  3358 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-10 17:04:46.522  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:46.522  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:46.522  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:46.522  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:46.522  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:46.522  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.522  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:46.522  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.522  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.522  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:46.522  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.522  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.523  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:46.523  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.523  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:46.523  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:46.523  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.523  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.524  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 17:04:46.526  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 17:04:46.526  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 17:04:46.526  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 17:04:46.526  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:04:46.526  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:04:46.526  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 17:04:46.526  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 17:04:46.527  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 17:04:46.527  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:46.527  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:46.527  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:46.527  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:46.527  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.527  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.527  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:46.527  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.527  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.527  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:46.528  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.528  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.528  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.528  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.528  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:46.528  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:46.528  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.528  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.529  3309  3358 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 17:04:46.529  3309  3358 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 17:04:46.530  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-10 17:04:46.533  3309  3358 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 17:04:46.533  3309  3358 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-10 17:04:46.533  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 17:04:46.533  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-10 17:04:46.533  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 17:04:46.533  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-10 17:04:46.534  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 17:04:46.535  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 17:04:46.536  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 17:04:46.536  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 17:04:46.536  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 17:04:46.536  3309  3358 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 17:04:46.536  3309  3358 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 17:04:46.536  3309  3358 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 17:04:46.537  3309  3358 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 17:04:46.537  3309  3358 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 17:04:46.537  3309  3358 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 17:04:46.537  3309  3358 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 17:04:46.537  3309  3358 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 17:04:46.537  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 17:04:46.539  3309  3358 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
08-10 17:04:46.540  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-10 17:04:46.541  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 17:04:46.541  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 17:04:46.542  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-10 17:04:46.542  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 17:04:46.542  3309  3358 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-10 17:04:46.542  3309  3358 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 17:04:46.543  3309  3358 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 17:04:46.543  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:46.544  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:46.544  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:46.544  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:46.544  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.544  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.544  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-10 17:04:46.545  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:46.545  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.545  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.545  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:46.548  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.549  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.549  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.549  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.545  3309  3372 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 345)
08-10 17:04:46.550  3309  3373 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 345
08-10 17:04:46.550  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:46.550  3309  3372 E BluetoothDevice: Bluetooth is not enabled
08-10 17:04:46.551  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:46.551  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.551  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.552  3309  3372 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 345)
08-10 17:04:46.553  3309  3358 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 17:04:46.554  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:46.554  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:46.554  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:46.554  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:46.554  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.554  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.554  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:46.554  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.554  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.554  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:46.554  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.554  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.554  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.554  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.555  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:46.555  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:46.555  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.555  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.555  3309  3358 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 17:04:46.556  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:46.556  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:46.556  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:46.556  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:46.556  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.556  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.556  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:46.556  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.556  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.556  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:46.556  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.556  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.556  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.556  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.557  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:46.557  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:46.557  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.557  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.560  3309  3358 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 17:04:46.560  3309  3358 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-10 17:04:46.560  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 17:04:46.560  3309  3358 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 17:04:46.560  3309  3358 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 17:04:46.560  3309  3358 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 17:04:46.560  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 17:04:46.560  3309  3358 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 17:04:46.561  3309  3358 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 17:04:46.561  3309  3358 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 17:04:46.561  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 17:04:46.561  3309  3358 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 17:04:46.561  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:46.561  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:46.561  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:46.561  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:46.561  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.561  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.561  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:46.561  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.561  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.561  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:46.562  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.562  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.562  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.562  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.563  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:46.563  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:46.563  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.563  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.564  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:46.564  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.564  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:46.564  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:46.564  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:46.564  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:46.564  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:46.564  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:46.564  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:51.565  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:51.566  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:51.566  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:51.566  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:51.566  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:51.567  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
,08-10 17:04:51.567  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:51.568  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:51.568  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 17:04:51.568  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:51.569  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.569  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.569  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
,08-10 17:04:51.570  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:51.570  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:51.570  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 17:04:51.570  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.571  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.571  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.571  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:51.573  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:51.573  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:51.573  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:51.574  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
,08-10 17:04:51.579  3309  3358 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 17:04:51.580  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 17:04:51.581  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
,08-10 17:04:51.581  3309  3358 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
08-10 17:04:51.582  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 17:04:51.582  3309  3309 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
08-10 17:04:51.583  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:51.584  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 17:04:51.584  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.584  3309  3358 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
,08-10 17:04:51.584  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:51.584  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:51.584  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-10 17:04:51.584  3309  3309 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 17:04:51.584  3309  3358 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 17:04:51.584  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 17:04:51.585  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.585  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.585  3309  3358 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 17:04:51.585  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:51.585  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:51.586  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 17:04:51.586  3309  3309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 17:04:51.587  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:51.587  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:51.587  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.587  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.587  3309  3309 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 17:04:51.588  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:51.588  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:51.589  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
,08-10 17:04:51.590  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:51.588  3309  3309 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 17:04:51.591  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.591  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:51.591  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.591  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.591  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:51.591  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:51.591  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:51.591  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
,08-10 17:04:51.593  3309  3358 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-10 17:04:51.593  3309  3358 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 17:04:51.593  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-10 17:04:51.595  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-10 17:04:51.596  3309  3358 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 17:04:51.596  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:51.596  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:51.596  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:51.596  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:51.597  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.597  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.597  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
,08-10 17:04:51.597  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:51.597  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:51.597  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:51.597  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.597  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.597  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.597  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:51.600  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 17:04:51.601  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 17:04:51.601  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:51.602  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
,08-10 17:04:51.606  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 17:04:51.606  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 17:04:51.606  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:51.606  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:51.606  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:51.606  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.606  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:51.606  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:51.606  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
,08-10 17:04:51.607  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:51.607  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.607  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.607  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.607  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.607  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:51.607  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 17:04:51.607  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:51.608  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:51.608  3309  3358 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 17:04:51.608  3309  3358 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 17:04:51.609  3309  3358 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 17:04:51.609  3309  3358 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 17:04:51.609  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 17:04:51.609  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.609  3309  3358 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@307dc77 not in the list
08-10 17:04:51.609  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:51.609  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
,08-10 17:04:51.609  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:51.609  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.609  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:04:51.609  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.610  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.610  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 17:04:51.610  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 17:04:51.610  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:51.610  3309  3358 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8f50e4 not in the list
08-10 17:04:51.611  3309  3358 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-10 17:04:51.611  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 17:04:51.612  3309  3358 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 17:04:51.612  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 17:04:51.612  3309  3358 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-10 17:04:51.612  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 17:04:51.614  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 17:04:51.614  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-10 17:04:51.615  3309  3358 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-10 17:04:51.615  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 17:04:51.616  3309  3358 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 17:04:51.616  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-10 17:04:51.616  3309  3358 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-10 17:04:51.616  3309  3358 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-10 17:04:51.617  3309  3358 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,08-10 17:04:51.617  3309  3358 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 17:04:51.617  3309  3358 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,08-10 17:04:51.617  3309  3358 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 17:04:51.618  3309  3358 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-10 17:04:51.618  3309  3358 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 17:04:51.619  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 17:04:51.619  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bf2464e added. We now have 3 listener(s)
,08-10 17:04:51.619  3309  3358 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 17:04:51.621   871  2562 D WifiService: setWifiEnabled: true pid=3309, uid=10000
,08-10 17:04:51.621   871  2562 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 17:04:51.624  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:04:51.625  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e7e36f added. We now have 4 listener(s)
08-10 17:04:51.625  3309  3358 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 17:04:51.625  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:51.626  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:51.626  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:04:51.626  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5e7e36f removed from the list
08-10 17:04:51.626  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:51.626  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.626  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.627  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:04:51.627  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e1d87c added. We now have 4 listener(s)
08-10 17:04:51.627  3309  3358 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 17:04:51.628  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:04:51.628  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e1d87c removed from the list
08-10 17:04:51.628  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
08-10 17:04:51.628  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:04:51.628  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:04:51.629  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 17:04:51.629  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9072505 added. We now have 4 listener(s)
08-10 17:04:51.629  3309  3358 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 17:04:51.630   871  1676 D WifiService: setWifiEnabled: false pid=3309, uid=10000
08-10 17:04:51.630   871  1676 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 17:04:51.645   871   888 I ActivityManager: Start proc 3376:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 17:04:51.646   871  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-10 17:04:51.650  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:51.651  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:51.651  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:51.651  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:51.651  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:04:51.651  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:51.651  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:51.651  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:51.651  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:04:51.651  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:51.651  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:04:51.652  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:51.652  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:51.652  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:51.652  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:51.652  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:04:51.652  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:51.652  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:51.652  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:51.652  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:04:51.652  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:51.652  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:04:51.669   871   884 I ActivityManager: Start proc 3387:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
08-10 17:04:51.671  3309  3358 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 17:04:51.672  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:51.672  3309  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 17:04:51.672  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:51.672  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:51.672  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:04:51.672  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:51.672  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:51.672  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:51.672  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:04:51.672  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:51.672  3309  3358 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:04:51.672  3309  3358 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 17:04:51.673  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:04:51.675   871  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-10 17:04:51.676   871  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 17:04:51.677   871  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 17:04:51.680   871  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-10 17:04:51.680   871  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-10 17:04:51.680   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-10 17:04:51.680   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK,
,08-10 17:04:51.712  3387  3387 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-10 17:04:51.740   370   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-10 17:04:51.741   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 17:04:51.741   370   869 D CommandListener: Setting iface cfg
,08-10 17:04:51.743   871  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '34 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 34 Failed to set address (No such device)'
,08-10 17:04:51.743   871  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 17:04:51.751   871  1304 E native  : do suspend true
,08-10 17:04:51.760   871  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 17:04:51.760   871  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 17:04:51.771  3387  3387 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-10 17:04:51.785   871  1370 I ActivityManager: Killing 2651:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-10 17:04:51.830  1465  1465 I wpa_supplicant: wlan0: Reject scan trigger since one is already pending
,08-10 17:04:51.830  1465  1465 W wpa_supplicant: wlan0: Failed to initiate AP scan
,08-10 17:04:51.860   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 17:04:51.862  1967  2115 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 17:04:51.863  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:51.863  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:51.863  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:51.863  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:51.863  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:51.863  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:51.863  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:51.863  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:51.863  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:04:51.863  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:51.863  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:04:51.864  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:51.864  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:51.864  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:51.864  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:51.864  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:51.864  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:51.864  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:51.864  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:51.864  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:04:51.865  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:51.865  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:04:51.866  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:04:51.866  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:51.866  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:51.866  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-10 17:04:51.866  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:51.866  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:04:51.866  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:51.866  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:51.866  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:04:51.866  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:04:51.866  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:04:51.868  3376  3376 D AdapterServiceConfig: Adding HeadsetService,
08-10 17:04:51.871  3376  3376 D AdapterServiceConfig: Adding A2dpService
08-10 17:04:51.871  3376  3376 D AdapterServiceConfig: Adding HidService
08-10 17:04:51.872  3376  3376 D AdapterServiceConfig: Adding HealthService
,08-10 17:04:51.872  3376  3376 D AdapterServiceConfig: Adding PanService
08-10 17:04:51.872  3376  3376 D AdapterServiceConfig: Adding GattService
08-10 17:04:51.873  3376  3376 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 17:04:51.900   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37c12c2:true
,08-10 17:04:51.900  3376  3376 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 17:04:51.903  3376  3376 I bt_bluedroid: init
,08-10 17:04:51.903  3376  3414 I BluetoothAdapterState: Entering OffState
,08-10 17:04:51.907  3376  3415 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 17:04:51.908  3376  3415 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-10 17:04:51.908  3376  3415 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-10 17:04:51.908  3376  3415 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 17:04:51.910  3376  3376 I bt_bluedroid: get_profile_interface socket
,08-10 17:04:51.911  3376  3376 I bt_bluedroid: get_profile_interface sdp
,08-10 17:04:51.914  3376  3388 I bt_bluedroid: config_hci_snoop_log
,08-10 17:04:51.915   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-10 17:04:51.915  3376  3418 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-10 17:04:51.916  3376  3418 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 17:04:51.918  3376  3414 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 17:04:51.918  3376  3414 D BluetoothAdapterProperties: Setting state to 14
08-10 17:04:51.918  3376  3414 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 17:04:51.919  3376  3414 D BluetoothBondStateMachine: make
,08-10 17:04:51.922  3376  3419 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 17:04:51.923  3376  3414 I BluetoothAdapterState: Entering PendingCommandState
,08-10 17:04:51.924  3376  3376 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 17:04:51.926  3376  3376 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:04:51.926  3376  3376 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 17:04:51.927  3376  3376 D BtGatt.GattService: Received start request. Starting profile...
08-10 17:04:51.927  3376  3376 D BtGatt.GattService: start()
08-10 17:04:51.927  3376  3376 I bt_bluedroid: get_profile_interface gatt
,08-10 17:04:51.928  3376  3376 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
08-10 17:04:51.928  3376  3376 D BtGatt.AdvertiseManager: advertise manager created
,08-10 17:04:51.931  3376  3376 V BluetoothAdapterState: isTurningOff()=false
,08-10 17:04:51.931  3376  3376 V BluetoothAdapterState: isTurningOn()=false
,08-10 17:04:51.931  3376  3376 V BluetoothAdapterState: isBleTurningOn()=true
08-10 17:04:51.931  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:04:51.932  3376  3414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-10 17:04:51.932  3376  3414 I bt_bluedroid: enable
,08-10 17:04:51.932  3376  3415 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-10 17:04:51.933  3376  3415 I bt_hci  : start_up
,08-10 17:04:51.950  3376  3415 I bt_vendor: alloc value 0xb3a5c189
,08-10 17:04:51.950  3376  3415 I bt_vendor: init
,08-10 17:04:51.950  3376  3415 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-10 17:04:51.950  3376  3415 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 17:04:52.056  3376  3415 D bt_hci  : start_up starting async portion
,08-10 17:04:52.057  3376  3422 I bt_hci  : event_finish_startup
,08-10 17:04:52.057  3376  3422 I bt_hci_h4: hal_open
,08-10 17:04:52.057  3376  3422 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 17:04:52.062  3376  3422 I bt_userial_vendor: device fd = 51 open
,08-10 17:04:52.091  3309  3309 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 17:04:52.100  3376  3422 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 17:04:52.131  3376  3422 D bt_hwcfg: Chipset BCM4354A2
08-10 17:04:52.132  3376  3422 D bt_hwcfg: Target name = [BCM4354A2]
,08-10 17:04:52.132  3376  3422 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 17:04:52.803  3376  3422 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 17:04:52.805  3376  3422 D bt_hwcfg: Settlement delay -- 100 ms
,08-10 17:04:52.805  3376  3422 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 17:04:52.922  3376  3422 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 17:04:52.923  3376  3422 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 17:04:52.953  3376  3422 I bt_hwcfg: vendor lib fwcfg completed
,08-10 17:04:52.953  3376  3422 I bt_vendor: firmware callback
,08-10 17:04:52.953  3376  3422 I bt_hci  : firmware_config_callback
,08-10 17:04:52.964  3376  3424 I bt_btu  : btu_task pending for preload complete event
,08-10 17:04:52.964  3376  3424 I bt_btu_task: Bluetooth chip preload is complete
,08-10 17:04:52.964  3376  3424 I bt_btu  : btu_task received preload complete event
,08-10 17:04:52.974  3376  3424 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 17:04:52.975  3376  3424 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 17:04:52.975  3376  3424 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-10 17:04:52.975  3376  3424 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-10 17:04:52.976  3376  3424 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 17:04:52.976  3376  3424 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 17:04:52.976  3376  3424 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 17:04:52.976  3376  3424 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 17:04:52.976  3376  3424 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 17:04:52.977  3376  3424 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 17:04:52.977  3376  3424 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 17:04:52.977  3376  3424 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 17:04:52.977  3376  3424 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 17:04:52.977  3376  3424 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 17:04:52.978  3376  3424 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 17:04:53.107  3376  3424 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d9d9d
,08-10 17:04:53.107  3376  3424 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d9d9d 
,08-10 17:04:53.128  3376  3418 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 17:04:53.129  3376  3418 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 17:04:53.130  3376  3418 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 17:04:53.132  3376  3418 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 17:04:53.134  3376  3418 D BluetoothAdapterProperties: Scan Mode:20
,08-10 17:04:53.134  3376  3418 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 17:04:53.134  3376  3418 D bt_hci  : do_postload posting postload work item
,08-10 17:04:53.134  3376  3422 I bt_hci  : event_postload
,08-10 17:04:53.135  3376  3422 I bt_vendor: sco_config_cb
,08-10 17:04:53.135  3376  3422 I bt_hci  : sco_config_callback postload finished.
08-10 17:04:53.138  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:04:53.141  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:04:53.142  3376  3422 I bt_vendor: low_power_mode_cb
,08-10 17:04:53.144  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:04:53.149  3376  3418 D bt_bte_conf: Device ID record 1 : primary
,08-10 17:04:53.149  3376  3418 D bt_bte_conf:   vendorId            = 000f
08-10 17:04:53.149  3376  3418 D bt_bte_conf:   vendorIdSource      = 0001
,08-10 17:04:53.149  3376  3418 D bt_bte_conf:   product             = 1200
,08-10 17:04:53.149  3376  3418 D bt_bte_conf:   version             = 1436
08-10 17:04:53.149  3376  3418 D bt_bte_conf:   clientExecutableURL = 
,08-10 17:04:53.149  3376  3418 D bt_bte_conf:   serviceDescription  = 
,08-10 17:04:53.149  3376  3418 D bt_bte_conf:   documentationURL    = 
08-10 17:04:53.149  3376  3418 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-10 17:04:53.150  3376  3415 D bt_stack_manager: event_start_up_stack finished
,08-10 17:04:53.150  3376  3414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-10 17:04:53.151  3376  3414 D BluetoothAdapterProperties: Setting state to 15
08-10 17:04:53.151  3376  3414 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-10 17:04:53.152  3376  3414 I BluetoothAdapterState: Entering BleOnState
08-10 17:04:53.158  3376  3414 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-10 17:04:53.158  3376  3414 D BluetoothAdapterProperties: Setting state to 11
08-10 17:04:53.158  3376  3414 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 17:04:53.164  3376  3376 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:04:53.166  3376  3376 D HeadsetService: Received start request. Starting profile...
,08-10 17:04:53.169  3376  3376 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-10 17:04:53.170  3376  3376 D HeadsetStateMachine: make
,08-10 17:04:53.177  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:04:53.179  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-10 17:04:53.181  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:04:53.190   871   884 I ActivityManager: Start proc 3433:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,08-10 17:04:53.192  3376  3376 D HeadsetStateMachine: max_hf_connections = 1
,08-10 17:04:53.192  3376  3376 I bt_bluedroid: get_profile_interface handsfree
,08-10 17:04:53.193  3376  3418 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-10 17:04:53.193  3376  3418 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-10 17:04:53.198  3376  3376 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:04:53.199  3376  3414 I BluetoothAdapterState: Entering PendingCommandState
,08-10 17:04:53.200   871   871 D BluetoothA2dp: Proxy object connected
,08-10 17:04:53.200  3376  3376 D A2dpService: Received start request. Starting profile...
,08-10 17:04:53.201  3376  3376 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 17:04:53.202  3376  3376 I bt_bluedroid: get_profile_interface avrcp
08-10 17:04:53.211  3376  3376 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-10 17:04:53.211  3376  3376 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 17:04:53.211  3376  3376 D A2dpStateMachine: make
08-10 17:04:53.212  3376  3376 I bt_bluedroid: get_profile_interface a2dp
08-10 17:04:53.213  3376  3418 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-10 17:04:53.215  3376  3446 D A2dpStateMachine: Enter Disconnected: -2
08-10 17:04:53.217  3376  3376 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 17:04:53.220  3376  3376 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:04:53.222  1363  1363 D BluetoothInputDevice: Proxy object connected
,08-10 17:04:53.222  3376  3376 D HidService: Received start request. Starting profile...
08-10 17:04:53.222  3376  3376 I bt_bluedroid: get_profile_interface hidhost
08-10 17:04:53.222  1363  1363 D HidProfile: Bluetooth service connected
08-10 17:04:53.222  3376  3418 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bb3e5
08-10 17:04:53.222  3376  3376 D HidService: setHidService(): set to: null
,08-10 17:04:53.222  3376  3418 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-10 17:04:53.223  3376  3376 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 17:04:53.226  3376  3376 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:04:53.229  3376  3376 D HealthService: Received start request. Starting profile...
,08-10 17:04:53.230  3376  3376 I bt_bluedroid: get_profile_interface health
,08-10 17:04:53.231  3376  3376 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 17:04:53.232  3376  3376 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:04:53.233  3376  3376 D PanService: Received start request. Starting profile...
,08-10 17:04:53.233  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 17:04:53.233  3376  3376 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 17:04:53.233  3376  3376 I bt_bluedroid: get_profile_interface pan
08-10 17:04:53.233  3376  3418 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-10 17:04:53.234  3376  3376 V BluetoothAdapterState: isTurningOff()=false
08-10 17:04:53.235  3376  3376 V BluetoothAdapterState: isTurningOn()=true
08-10 17:04:53.235  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:04:53.235  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:04:53.236  1363  1363 D PanProfile: Bluetooth service connected
08-10 17:04:53.237  3376  3376 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
08-10 17:04:53.238  1363  1363 D BluetoothMap: Proxy object connected
08-10 17:04:53.238  3376  3376 D BluetoothMapService: Received start request. Starting profile...
08-10 17:04:53.238  3376  3376 D BluetoothMapService: start()
,08-10 17:04:53.239  1363  1363 D MapProfile: Bluetooth service connected
,08-10 17:04:53.239  1363  1363 D BluetoothMap: getConnectedDevices()
08-10 17:04:53.239  1363  1363 D BluetoothMap: Bluetooth is Not enabled
,08-10 17:04:53.240  3376  3376 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 17:04:53.241  3376  3376 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-10 17:04:53.241  3376  3376 D BluetoothMapAppObserver: createReceiver()
08-10 17:04:53.242  3433  3433 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
08-10 17:04:53.242  3376  3376 D BluetoothMapAppObserver: initObservers()
08-10 17:04:53.242  3376  3376 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 17:04:53.248  3376  3376 V BluetoothAdapterState: isTurningOff()=false
08-10 17:04:53.248  3376  3376 V BluetoothAdapterState: isTurningOn()=true
08-10 17:04:53.248  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:04:53.248  3376  3430 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-10 17:04:53.248  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:04:53.248  3376  3376 V BluetoothAdapterState: isTurningOff()=false
08-10 17:04:53.248  3376  3376 V BluetoothAdapterState: isTurningOn()=true
08-10 17:04:53.249  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:04:53.249  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:04:53.249  3376  3376 V BluetoothAdapterState: isTurningOff()=false
08-10 17:04:53.249  3376  3376 V BluetoothAdapterState: isTurningOn()=true
08-10 17:04:53.249  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:04:53.249  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:04:53.249  3376  3376 V BluetoothAdapterState: isTurningOff()=false
08-10 17:04:53.249  3376  3376 V BluetoothAdapterState: isTurningOn()=true
08-10 17:04:53.249  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:04:53.249  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:04:53.250  3376  3376 V BluetoothAdapterState: isTurningOff()=false
08-10 17:04:53.250  3376  3376 V BluetoothAdapterState: isTurningOn()=true
08-10 17:04:53.250  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:04:53.250  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:04:53.250  3376  3414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-10 17:04:53.250  3376  3414 D BluetoothAdapterProperties: ScanMode =  20
08-10 17:04:53.250  3376  3414 D BluetoothAdapterProperties: State =  11
08-10 17:04:53.251  3376  3414 D BluetoothAdapterProperties: Setting state to 12
08-10 17:04:53.251  3376  3414 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-10 17:04:53.252  1363  1820 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 17:04:53.252   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 17:04:53.253  3376  3418 D BluetoothAdapterProperties: Scan Mode:21
08-10 17:04:53.253  3376  3414 I BluetoothAdapterState: Entering OnState
,08-10 17:04:53.253  3376  3418 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 17:04:53.254   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 17:04:53.254  1719  1737 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 17:04:53.254  3309  3309 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-10 17:04:53.255   871  1392 I ActivityManager: Killing 2805:com.google.android.gm/u0a78 (adj 15): empty #17
,08-10 17:04:53.256  1363  1383 D BluetoothMap: onBluetoothStateChange: up=true
08-10 17:04:53.256  3309  3309 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-10 17:04:53.257  1363  1375 D BluetoothPan: onBluetoothStateChange on: true
08-10 17:04:53.257  1363  1820 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 17:04:53.258  3309  3309 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-10 17:04:53.261  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:53.261  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:53.261  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:04:53.261  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:53.261  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:04:53.261  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:53.261  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:53.261  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:04:53.263  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:04:53.266  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:53.266  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:53.266  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:04:53.266  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:53.266  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:04:53.266  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:53.266  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:53.266  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:04:53.267  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:04:53.270  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:53.270  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:53.270  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:04:53.270  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:04:53.270  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:04:53.270  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:53.270  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:53.270  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:04:53.272  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:04:53.314   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 17:04:53.314   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 17:04:53.317   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-10 17:04:53.326  3376  3376 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 17:04:53.327  3376  3376 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-10 17:04:53.333  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:04:53.334  3376  3376 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 17:04:53.335  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:04:53.337  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:04:53.337  1363  1654 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 17:04:53.337  3376  3376 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 17:04:53.339  3376  3376 D ObexServerSockets: Succeed to create listening sockets 
08-10 17:04:53.339  3376  3376 D ObexServerSockets0: startAccept()
08-10 17:04:53.339  3376  3376 D ObexServerSockets0: prepareForNewConnect()
,08-10 17:04:53.340  1363  1363 D BluetoothA2dp: Proxy object connected
,08-10 17:04:53.341  1363  1654 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-10 17:04:53.341  3376  3376 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-10 17:04:53.342  3376  3376 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-10 17:04:53.343  3376  3451 D ObexServerSockets0: Accepting socket connection...
,08-10 17:04:53.343  3376  3452 D ObexServerSockets0: Accepting socket connection...
,08-10 17:04:53.345  3376  3376 D BluetoothMapService: onReceive
,08-10 17:04:53.345  3376  3376 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:04:53.345  3376  3376 D BluetoothMapService: STATE_ON
08-10 17:04:53.345  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 17:04:53.354   871   888 D BluetoothHeadset: Proxy object connected
,08-10 17:04:53.355  1719  1877 D BluetoothHeadset: Proxy object connected
,08-10 17:04:53.361   871  1662 I ActivityManager: Start proc 3453:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-10 17:04:53.365  3376  3376 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 17:04:53.365  3376  3376 D ObexServerSockets0: prepareForNewConnect()
,08-10 17:04:53.397  3453  3453 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-10 17:04:53.413   871   888 D BluetoothHeadset: Proxy object connected
,08-10 17:04:53.415   871   888 D BluetoothHeadset: Proxy object connected
,08-10 17:04:53.446  1363  1383 D BluetoothHeadset: Proxy object connected
08-10 17:04:53.448  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-10 17:04:53.599  3453  3453 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 17:04:53.599  3453  3453 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 17:04:53.599  3453  3453 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5417)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 17:04:53.599  3453  3453 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 17:04:53.599  3453  3453 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.k.d(PG:583)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 17:04:53.599  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 17:04:53.600  3453  3453 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 17:04:53.600  3453  3453 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 17:04:53.600  3453  3453 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 17:04:53.600  3453  3453 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 17:04:53.644  3433  3433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 17:04:53.651   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ccb4fd2:true
08-10 17:04:53.658  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 17:04:53.665  3433  3433 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 17:04:53.670  3433  3433 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-10 17:04:53.683  1363  1363 D BluetoothPbap: Proxy object connected
,08-10 17:04:53.684  1363  1363 D PbapServerProfile: Bluetooth service connected
,08-10 17:04:53.692  3433  3433 D LocalBluetoothProfileManager: Adding local MAP profile
,08-10 17:04:53.693  3433  3433 D BluetoothMap: Create BluetoothMap proxy object
,08-10 17:04:53.704  3433  3433 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-10 17:04:53.705  3376  3482 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 17:04:53.715  3433  3433 D DockEventReceiver: finishStartingService: stopping service
,08-10 17:04:53.716  3433  3433 D BluetoothA2dp: Proxy object connected
,08-10 17:04:53.718  3433  3433 D BluetoothInputDevice: Proxy object connected
,08-10 17:04:53.719  3433  3433 D HidProfile: Bluetooth service connected
,08-10 17:04:53.721  3433  3433 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 17:04:53.722  3433  3433 D PanProfile: Bluetooth service connected
08-10 17:04:53.722  3433  3433 D BluetoothMap: Proxy object connected
,08-10 17:04:53.724  3433  3433 D MapProfile: Bluetooth service connected
,08-10 17:04:53.724  3433  3433 D BluetoothMap: getConnectedDevices()
08-10 17:04:53.724  3376  3488 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 17:04:53.726  3376  3488 I BtOppRfcommListener: Accept thread started.,
,08-10 17:04:53.727  3433  3433 D BluetoothPbap: Proxy object connected
08-10 17:04:53.728  3433  3433 D PbapServerProfile: Bluetooth service connected
08-10 17:04:53.729   871  2817 I ActivityManager: Killing 3001:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-10 17:04:53.779  3433  3443 D BluetoothHeadset: Proxy object connected
,08-10 17:04:53.779  3433  3433 D HeadsetProfile: Bluetooth service connected
,08-10 17:04:53.829  3453  3468 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-10 17:04:53.850   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c85b483:true
,08-10 17:04:54.562  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:04:54.593  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:04:54.597  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:04:54.638  1519  2165 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 17:04:54.638  1519  2165 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 17:04:54.638  1519  2165 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 17:04:54.638  1519  2165 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:04:54.671  2567  2567 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 17:04:54.671  2567  2567 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 17:04:54.672  2567  2567 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-10 17:04:56.677   871   882 D WifiService: setWifiEnabled: true pid=3309, uid=10000
,08-10 17:04:56.677   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 17:04:56.690   871  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-10 17:04:56.711  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:56.711  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:56.711  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:04:56.711  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:04:56.711  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:04:56.711  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:56.711  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
,08-10 17:04:56.711  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:04:56.717  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:04:56.727   871  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-10 17:04:56.728  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:56.728  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:56.728  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:04:56.728  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:04:56.728  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:04:56.728  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:56.728  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:56.728  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:04:56.728   871  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 17:04:56.729   871  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 17:04:56.730   871  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-10 17:04:56.730   871  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-10 17:04:56.730   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-10 17:04:56.730   871  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-10 17:04:56.732  1465  1465 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-10 17:04:56.734  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:04:56.741  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:56.741  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:56.741  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:04:56.741  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:04:56.741  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:04:56.741  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:04:56.741  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:04:56.741  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:04:56.746  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:04:56.798   370   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-10 17:04:56.799   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2,
,08-10 17:04:56.801   370   869 D CommandListener: Setting iface cfg
,08-10 17:04:56.802  1465  1465 E wpa_supplicant: PNO: In assoc process
,08-10 17:04:56.803   871  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '36 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 36 Failed to set address (No such device)'
,08-10 17:04:56.803   871  1304 E WifiStateMachine:  Fail to set up pno, want true now false
,08-10 17:04:56.803   871  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 17:04:56.806   871  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 17:04:56.807   871  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 17:04:56.811   871  1304 E native  : do suspend true
,08-10 17:04:56.839   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 17:04:57.192  1465  1465 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 17:04:57.234  1465  1465 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 17:04:57.235  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 17:04:57.244   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 17:04:57.263   871  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 17:04:57.263   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 17:04:57.264   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-10 17:04:57.280   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 17:04:57.292   370   869 D CommandListener: Setting iface cfg
,08-10 17:04:57.301   871  1304 D WifiStateMachine: Start Dhcp Watchdog 1
,08-10 17:04:57.318   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 17:04:57.340   871  3498 D DhcpClient: Receive thread started
,08-10 17:04:57.425   871  1304 E native  : do suspend false
,08-10 17:04:57.450   871  3497 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 17:04:57.464   871  3498 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 165831, domain null
,08-10 17:04:57.467   871  3497 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 165831 seconds
,08-10 17:04:57.471   871  3497 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 17:04:57.485   871  3498 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 17:04:57.486   871  3497 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 17:04:57.492   370   869 D CommandListener: Setting iface cfg
,08-10 17:04:57.505   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-10 17:04:57.505   871  3497 D DhcpClient: Scheduling renewal in 86399s
,08-10 17:04:57.511   871  1304 E native  : do suspend true
,08-10 17:04:57.530   871  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 17:04:57.532   871  1304 D WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-10 17:04:57.533   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-10 17:04:57.535   871  1306 D ConnectivityService: Adding iface wlan0 to network 100
,08-10 17:04:57.544   871  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 17:04:57.585   871  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-10 17:04:57.586   871  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,08-10 17:04:57.591   871  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,08-10 17:04:57.594   871  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-10 17:04:57.597   871  1306 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,08-10 17:04:57.614   871  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-10 17:04:57.621   871  1306 D ConnectivityService: scheduleUnvalidatedPrompt 100
,08-10 17:04:57.622   871  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
,08-10 17:04:57.623   871  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-10 17:04:57.626   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 17:04:57.628   871  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,08-10 17:04:57.628   871  1306 D ConnectivityService:    accepting network in place of null
,08-10 17:04:57.632   871  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 17:04:57.641   871  3496 D NetlinkSocketObserver: NeighborEvent{elapsedMs=184953, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 17:04:57.696   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 17:04:57.701   871  3495 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:80f::200e
,08-10 17:04:57.741   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 17:04:57.747   871  1306 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,08-10 17:04:57.754   871  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-10 17:04:57.754   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 17:04:57.758   871  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,08-10 17:04:57.762   871   888 D Tethering: MasterInitialState.processMessage what=3
,08-10 17:04:57.770   871  1662 V BackupManagerService: Scheduling immediate backup pass
,08-10 17:04:57.781   871   871 V BackupManagerService: Running a backup pass
,08-10 17:04:57.782   871  1328 V BackupManagerService: clearing pending backups
,08-10 17:04:57.784  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:57.784  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:57.784  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:04:57.784  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:04:57.784  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:04:57.784  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 17:04:57.784  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 17:04:57.784  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 17:04:57.785   871  1328 V PerformBackupTask: Beginning backup of 16 targets
,08-10 17:04:57.789   871  3495 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 15:04:57 GMT], X-Android-Received-Millis=[1470841497788], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470841497758]}
,08-10 17:04:57.790  2034  2034 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 17:04:57.791   871  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 17:04:57.792   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
08-10 17:04:57.792  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 17:04:57.792   871  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-10 17:04:57.793   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-10 17:04:57.795  2034  2034 D SystemUpdateService: onCreate
,08-10 17:04:57.799  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:57.799  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:57.799  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:04:57.799  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:04:57.799  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:04:57.799  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 17:04:57.799  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 17:04:57.799  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 17:04:57.801  2034  2034 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 17:04:57.803  1777  1777 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-10 17:04:57.804  2034  3511 I SystemUpdateService: active receiver: enabled
,08-10 17:04:57.812   871  1688 D AlarmManagerService: Setting time of day to sec=1470841498
,08-10 17:04:58.019   871  1688 W AlarmManagerService: Unable to set rtc to 1470841498: Invalid argument
,08-10 17:04:58.027   871  1328 D PerformBackupTask: invokeAgentForBackup on @pm@
,08-10 17:04:58.028  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 17:04:58.031  2034  3511 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 17:04:58.032  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:04:58.032  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:04:58.032  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:04:58.032  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 17:04:58.032  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:04:58.032  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 17:04:58.032  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 17:04:58.032  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 17:04:58.034  2034  3511 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-10 17:04:58.034  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 17:04:58.034  2034  3511 I SystemUpdateService: now status is 0 (complete)
08-10 17:04:58.034  2034  3511 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 17:04:58.034  2034  3511 I SystemUpdateService: file has been verified
08-10 17:04:58.034   871  1328 I PMBA    : Previous metadata 1570415 mismatch vs 2862625 - rewriting
08-10 17:04:58.034  2034  3511 I SystemUpdateService: OTA package size = 12249756
,08-10 17:04:58.047  2034  3511 I SystemUpdateService: showing system update notification
,08-10 17:04:58.062  2034  2034 D SystemUpdateService: onDestroy
,08-10 17:04:58.076   871  1328 I BackupRestoreController: Getting widget state for user: 0
,08-10 17:04:58.087   871  3523 D GpsLocationProvider: NTP server returned: 1470841498019 (Wed Aug 10 17:04:58 GMT+02:00 2016) reference: 185128 certainty: 4 system time offset: -68
,08-10 17:04:58.088   871  3523 E LocSvc_eng: E/int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int): log_eng state error: instance not initialized
,08-10 17:04:58.104   871  1786 I ActivityManager: Start proc 3526:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-10 17:04:58.131  2034  3522 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,08-10 17:04:58.132  3526  3526 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-10 17:04:58.134  2034  3541 I iu.SyncManager: SYNC; picasa accounts
08-10 17:04:58.135  3387  3525 V GoogleAuthProtoRequest: [278] a.<init>: mAccountName set to: thalitester@gmail.com
08-10 17:04:58.141  2034  2034 D NetworkLogImpl: Loaded NetworkSpeedPredictor
08-10 17:04:58.142  2034  2034 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-10 17:04:58.153  2034  2034 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 17:04:58.154  2034  3541 I iu.UploadsManager: num queued entries: 0
08-10 17:04:58.155  2034  2034 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-10 17:04:58.155  2034  3541 I iu.UploadsManager: num updated entries: 0
,08-10 17:04:58.156  2034  3541 I iu.SyncManager: NEXT; no task
,08-10 17:04:58.175   871   882 I ActivityManager: Start proc 3546:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-10 17:04:58.182  2034  3540 I MDM     : [203] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-10 17:04:58.182  2034  3540 W BaseAppContext: Using Auth Proxy for data requests.
,08-10 17:04:58.187  1967  2040 W GmsBackupTransport: Unknown package in backup request: @pm@
,08-10 17:04:58.195  3526  3545 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-10 17:04:58.194  1967  2040 V GmsBackupTransport: starting performBackup for @pm@
,08-10 17:04:58.202  2034  3540 V GoogleAuthProtoRequest: [203] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 17:04:58.222  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 17:04:58.222  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 17:04:58.222  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:58.223  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:04:58.247  1967  2040 V GmsBackupTransport: performBackup done for @pm@
,08-10 17:04:58.255  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:04:58.267  3546  3546 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
08-10 17:04:58.270  3546  3546 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: [278] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: [278] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 17:04:58.271  3387  3525 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 17:04:58.297  3546  3546 D SprintDMHelper: simOperator: 
,08-10 17:04:58.297  3546  3546 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 17:04:58.303   871  1392 D ConnectivityService: listenForNetwork for Listen from uid/pid:10011/2034 for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-10 17:04:58.315   871  2817 I ActivityManager: Start proc 3571:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-10 17:04:58.332  3526  3545 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-10 17:04:58.351  1519  1917 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: android
,08-10 17:04:58.351  1519  1917 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> android without consulting the cloud.
08-10 17:04:58.351  1519  1917 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:58.351  1519  1917 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 17:04:58.362  1519  1917 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 17:04:58.362  1519  1917 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 17:04:58.362  1519  1917 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 17:04:58.362  1519  1917 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 17:04:58.362  1519  1917 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 17:04:58.362  1519  1917 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 17:04:58.362  1519  1917 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-10 17:04:58.363  3526  3545 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-10 17:04:58.367  1967  1979 W GmsBackupTransport: Error sending final backup to server: 
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1078)
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:583)
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:453)
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 17:04:58.367  1967  1979 W GmsBackupTransport: 	... 1 more
,08-10 17:04:58.369  1967  1978 I GmsBackupTransport: Next backup will happen in 43199997 millis.
,08-10 17:04:58.369   871  1328 V KeyValueBackupJob: Scheduling k/v pass in 719 minutes
,08-10 17:04:58.386  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-10 17:04:58.386  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-10 17:04:58.386  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:58.386  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:04:58.401  2034  3540 E MDM     : [203] SitrepService.a: Error sending sitrep.
,08-10 17:04:58.431  3526  3526 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-10 17:04:58.468   871  1328 I BackupManagerService: Backup pass finished.
,08-10 17:04:58.492   871   883 I ActivityManager: Start proc 3598:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-10 17:04:58.507  3603  3603 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1150972431.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1150972431.dex
08-10 17:04:58.509  3598  3598 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-10 17:04:58.530  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 17:04:58.530  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 17:04:58.530  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:58.530  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:04:58.558  3117  3543 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 17:04:58.558  3117  3543 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at jdm.a(PG:82)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at jcs.o(PG:406)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at jcn.a(PG:1379)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at jcs.i(PG:143)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at blb.a(PG:3937)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at czp.a(PG:18188)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at czp.a(PG:9081)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at czq.run(PG:1686)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 17:04:58.558  3117  3543 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at jdj.a(PG:4091)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at jdj.a(PG:1125)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at jdm.a(PG:77)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	... 12 more
08-10 17:04:58.558  3117  3543 E HttpOperation: Caused by: faj: BadAuthentication
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at fal.a(PG:38)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	at jdj.a(PG:4089)
08-10 17:04:58.558  3117  3543 E HttpOperation: 	... 14 more
,08-10 17:04:58.605  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 17:04:58.605  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 17:04:58.606  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:58.606  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:04:58.619  3117  3543 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 17:04:58.619  3117  3543 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at jdm.a(PG:82)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at jcs.o(PG:406)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at jcn.a(PG:1379)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at jcs.i(PG:143)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at hec.a(PG:42)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at hee.a(PG:102)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at czr.a(PG:65)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at kka.a(PG:108)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at czp.a(PG:19176)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at czp.a(PG:9081)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at czq.run(PG:1686)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 17:04:58.619  3117  3543 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at jdj.a(PG:4091)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at jdj.a(PG:1125)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at jdm.a(PG:77)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	... 15 more
08-10 17:04:58.619  3117  3543 E HttpOperation: Caused by: faj: BadAuthentication
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at fal.a(PG:38)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	at jdj.a(PG:4089)
08-10 17:04:58.619  3117  3543 E HttpOperation: 	... 17 more
,08-10 17:04:58.619  3117  3543 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 17:04:58.619  3117  3543 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at hec.a(PG:42)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at hee.a(PG:102)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at czr.a(PG:65)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at kka.a(PG:108)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	... 15 more
08-10 17:04:58.619  3117  3543 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at fal.a(PG:38)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 17:04:58.619  3117  3543 E ExperimentLoader: 	... 17 more
08-10 17:04:58.621  2034  3524 W DriveInitializer: Awaiting to be initialized
08-10 17:04:58.621  2034  3627 W DriveInitializer: Background init thread started
,08-10 17:04:58.648  3603  3603 I dex2oat : dex2oat took 141.701ms (threads: 4) arena alloc=379KB java alloc=41KB native alloc=1643KB free=1428KB
,08-10 17:04:58.653  3526  3526 W InstanceID/Rpc: Found 10011
,08-10 17:04:58.714   871  1676 I ActivityManager: Start proc 3659:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-10 17:04:58.748  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 17:04:58.751  3598  3598 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-10 17:04:58.762  2034  3627 W DriveInitializer: Background init thread ended
08-10 17:04:58.768  3598  3598 I BooksApp: Created application version: 3.6.9 (30609)
,08-10 17:04:58.793   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 24323, reason: Periodic, SyncResult: stats [ numIoExceptions: 1],
,08-10 17:04:58.849  3659  3659 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-10 17:04:58.939  3598  3689 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 17:04:58.947  2353  3658 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-10 17:04:58.954  2839  3691 V KeepSync: Connecting to GoogleApiClient
,08-10 17:04:58.955   871  2817 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 17:04:59.022  1519  2164 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 17:04:59.022  1519  2164 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 17:04:59.022  1519  2164 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:59.022  1519  2164 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:04:59.036  2034  3699 V BaseAuthAsyncOperation: access token request failed
,08-10 17:04:59.037  2839  3691 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 17:04:59.188  3659  3659 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-10 17:04:59.188  3659  3659 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 17:04:59.188  3659  3659 I GAv4    :   adb logcat -s GAv4
,08-10 17:04:59.205  3659  3659 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 17:04:59.215  3659  3659 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 17:04:59.273  3659  3709 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 17:04:59.420  3659  3659 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-10 17:04:59.485  3659  3659 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-10 17:04:59.513  3659  3659 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6619-6623)
,08-10 17:04:59.513  3659  3659 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 17:04:59.534  3659  3659 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {64f6366}
,08-10 17:04:59.534  3659  3659 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 17:04:59.535  3659  3659 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 17:04:59.556  3659  3659 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 17:04:59.558  3659  3659 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 17:04:59.574  3598  3729 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 17:04:59.620  1519  1917 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 17:04:59.620  1519  1917 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 17:04:59.620  1519  1917 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:59.620  1519  1917 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:04:59.654  1519  2165 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 17:04:59.654  1519  2165 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 17:04:59.654  1519  2165 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:59.655  1519  2165 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:04:59.666  3598  3729 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 17:04:59.669  3598  3689 E BooksSync: Soft error
08-10 17:04:59.669  3598  3689 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 17:04:59.669  3598  3689 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 17:04:59.669  3598  3689 E BooksSync: Sync error
08-10 17:04:59.669  3598  3689 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 17:04:59.669  3598  3689 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 17:04:59.669  3598  3689 I BooksSync: Finished books sync
,08-10 17:04:59.684   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 24332, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-10 17:04:59.684   871  1676 I ActivityManager: Killing 2462:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-10 17:04:59.698  3659  3659 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 17:04:59.723  3659  3659 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 17:04:59.723  3659  3659 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 17:04:59.723  3659  3659 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 17:04:59.723  3659  3659 I Adreno  : Build Date                       : 10/20/15
08-10 17:04:59.723  3659  3659 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 17:04:59.723  3659  3659 I Adreno  : Local Branch                     : M14
08-10 17:04:59.723  3659  3659 I Adreno  : Remote Branch                    : 
08-10 17:04:59.723  3659  3659 I Adreno  : Remote Branch                    : 
08-10 17:04:59.723  3659  3659 I Adreno  : Reconstruct Branch               : 
,08-10 17:04:59.793  3659  3743 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-10 17:04:59.805  3659  3659 I NSApplication: Starting up...
,08-10 17:04:59.841   871  3490 I ActivityManager: Start proc 3749:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
08-10 17:04:59.843   871  3490 I ActivityManager: Killing 1663:android.process.acore/u0a5 (adj 15): empty #17
,08-10 17:04:59.930  3749  3749 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-10 17:04:59.932  1519  2165 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-10 17:04:59.932  1519  2165 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-10 17:04:59.932  1519  2165 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:04:59.932  1519  2165 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:04:59.964  2839  3691 E KeepSync: IOException
08-10 17:04:59.964  2839  3691 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 17:04:59.964  2839  3691 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 17:04:59.964  2839  3691 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 17:04:59.964  2839  3691 E KeepSync: 	... 10 more
,08-10 17:04:59.964  2839  3691 W KeepSync: Sync result 2
,08-10 17:04:59.969   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 24332, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 17:04:59.971   871  1392 I ActivityManager: Killing 3197:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-10 17:05:00.303   871  3490 I ActivityManager: Killing 3035:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-10 17:05:00.345   871  3490 I ActivityManager: Killing 3212:com.android.musicfx/u0a18 (adj 15): empty #18
,08-10 17:05:00.562  1519  1519 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-10 17:05:00.606  1519  3770 I VacuumService: Vacuum at: now=1470841500606 tag=VacuumService
,08-10 17:05:01.001  1519  2672 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,08-10 17:05:01.001  1519  2672 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
08-10 17:05:01.001  1519  2672 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 17:05:01.002  1519  2672 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 17:05:01.015  2353  3777 E Babel   : UserRecoverableAuthException.
,08-10 17:05:01.015  2353  3777 E Babel   : efr: BadAuthentication
08-10 17:05:01.015  2353  3777 E Babel   : 	at efp.a(Unknown Source)
08-10 17:05:01.015  2353  3777 E Babel   : 	at efp.a(Unknown Source)
08-10 17:05:01.015  2353  3777 E Babel   : 	at efp.a(Unknown Source)
08-10 17:05:01.015  2353  3777 E Babel   : 	at g.a(Unknown Source)
08-10 17:05:01.015  2353  3777 E Babel   : 	at cbh.a(SourceFile:3092)
08-10 17:05:01.015  2353  3777 E Babel   : 	at cbh.a(SourceFile:1136)
08-10 17:05:01.015  2353  3777 E Babel   : 	at cyr.a(SourceFile:4333)
08-10 17:05:01.015  2353  3777 E Babel   : 	at cyr.a(SourceFile:1419)
08-10 17:05:01.015  2353  3777 E Babel   : 	at ctk.a(SourceFile:492)
08-10 17:05:01.015  2353  3777 E Babel   : 	at ctk.a(SourceFile:1468)
08-10 17:05:01.015  2353  3777 E Babel   : 	at cst.a(SourceFile:4416)
08-10 17:05:01.015  2353  3777 E Babel   : 	at cbv.b(SourceFile:106)
08-10 17:05:01.015  2353  3777 E Babel   : 	at cbs.d(SourceFile:335)
08-10 17:05:01.015  2353  3777 E Babel   : 	at cbt.run(SourceFile:81)
,08-10 17:05:01.016  2353  3777 E Babel   : Error getting auth token
,08-10 17:05:01.016  2353  3777 E Babel   : dxq
08-10 17:05:01.016  2353  3777 E Babel   : 	at g.a(Unknown Source)
08-10 17:05:01.016  2353  3777 E Babel   : 	at cbh.a(SourceFile:3092)
08-10 17:05:01.016  2353  3777 E Babel   : 	at cbh.a(SourceFile:1136)
08-10 17:05:01.016  2353  3777 E Babel   : 	at cyr.a(SourceFile:4333)
08-10 17:05:01.016  2353  3777 E Babel   : 	at cyr.a(SourceFile:1419)
08-10 17:05:01.016  2353  3777 E Babel   : 	at ctk.a(SourceFile:492)
08-10 17:05:01.016  2353  3777 E Babel   : 	at ctk.a(SourceFile:1468)
08-10 17:05:01.016  2353  3777 E Babel   : 	at cst.a(SourceFile:4416)
08-10 17:05:01.016  2353  3777 E Babel   : 	at cbv.b(SourceFile:106)
08-10 17:05:01.016  2353  3777 E Babel   : 	at cbs.d(SourceFile:335)
08-10 17:05:01.016  2353  3777 E Babel   : 	at cbt.run(SourceFile:81)
08-10 17:05:01.020  2353  3777 E Babel   : Account registration failed 1-Redacted-21
08-10 17:05:01.021  2353  3777 E Babel   : dao: null -- null
08-10 17:05:01.021  2353  3777 E Babel   : 	at cbh.a(SourceFile:3124)
08-10 17:05:01.021  2353  3777 E Babel   : 	at cbh.a(SourceFile:1136)
08-10 17:05:01.021  2353  3777 E Babel   : 	at cyr.a(SourceFile:4333)
08-10 17:05:01.021  2353  3777 E Babel   : 	at cyr.a(SourceFile:1419)
08-10 17:05:01.021  2353  3777 E Babel   : 	at ctk.a(SourceFile:492)
08-10 17:05:01.021  2353  3777 E Babel   : 	at ctk.a(SourceFile:1468)
08-10 17:05:01.021  2353  3777 E Babel   : 	at cst.a(SourceFile:4416)
08-10 17:05:01.021  2353  3777 E Babel   : 	at cbv.b(SourceFile:106)
08-10 17:05:01.021  2353  3777 E Babel   : 	at cbs.d(SourceFile:335)
08-10 17:05:01.021  2353  3777 E Babel   : 	at cbt.run(SourceFile:81)
,08-10 17:05:01.041  2353  3777 I art     : Note: end time exceeds epoch: 
,08-10 17:05:01.076  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
08-10 17:05:01.076  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud.
,08-10 17:05:01.076  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:05:01.076  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:05:01.090  2353  3788 E Babel   : Unexpected exception while authenticating.
08-10 17:05:01.090  2353  3788 E Babel   : efs: User intervention required. Notification has been pushed.
08-10 17:05:01.090  2353  3788 E Babel   : 	at efp.b(Unknown Source)
08-10 17:05:01.090  2353  3788 E Babel   : 	at efp.b(Unknown Source)
08-10 17:05:01.090  2353  3788 E Babel   : 	at g.a(Unknown Source)
08-10 17:05:01.090  2353  3788 E Babel   : 	at cbh.b(SourceFile:1151)
08-10 17:05:01.090  2353  3788 E Babel   : 	at def.run(SourceFile:5617)
08-10 17:05:01.090  2353  3788 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 17:05:01.090  2353  3788 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 17:05:01.090  2353  3788 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,08-10 17:05:01.138  1519  3784 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-10 17:05:01.140  1519  3784 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-10 17:05:01.234  1519  3768 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,08-10 17:05:01.422  1519  3784 W Uploader:  no longer exists, so no auth token.
,08-10 17:05:01.553  1519  3784 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 17:05:01.554  1519  3784 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 17:05:01.554  1519  3784 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 17:05:01.554  1519  3784 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:05:01.567  1519  3784 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 17:05:01.567  1519  3784 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 17:05:01.567  1519  3784 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 17:05:01.890   871  1786 D WifiService: setWifiEnabled: false pid=3309, uid=10000
08-10 17:05:01.890   871  1786 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 17:05:01.898  1465  1465 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-10 17:05:01.900   871  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-10 17:05:01.900   871  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-10 17:05:01.900   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 17:05:01.900   871  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 17:05:01.929   871  1304 E native  : do suspend true
,08-10 17:05:01.935   370   869 D CommandListener: Clearing all IP addresses on wlan0
,08-10 17:05:01.935   871  3497 D DhcpClient: Clearing IP address
,08-10 17:05:01.939   370   869 D CommandListener: Setting iface cfg
,08-10 17:05:01.941  1519  3583 V NativeCrypto: Read error: ssl=0x9a87da00: I/O error during system call, Connection timed out
08-10 17:05:01.943  1519  3583 V NativeCrypto: SSL shutdown failed: ssl=0x9a87da00: I/O error during system call, Broken pipe
,08-10 17:05:01.946   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 17:05:01.947   871  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-10 17:05:01.952   393   393 E Parcel  : Reading a NULL string not supported here.
,08-10 17:05:01.956   871  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
08-10 17:05:01.957   871  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 17:05:01.957   871  1304 E native  : do suspend true
,08-10 17:05:01.965   871  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-10 17:05:01.966   871  3498 D DhcpClient: Receive thread stopped
,08-10 17:05:01.966   370   869 D CommandListener: Clearing all IP addresses on wlan0
,08-10 17:05:01.969   871  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 17:05:01.992  1967  2115 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 17:05:01.992   871  1304 D WifiConfigStore: Retrieve network priorities after PNO.
08-10 17:05:01.995   871  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-10 17:05:01.996  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:01.996  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:01.996  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:01.996  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:01.996  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true,
08-10 17:05:01.996  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:01.996  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:01.996  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:05:01.998  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:05:02.003  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:02.003  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:02.003  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:02.003  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:02.003  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:05:02.003  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:02.003  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:02.003  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:05:02.006  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:05:02.008   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 17:05:02.009  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:02.009  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:02.009  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:02.009  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:02.009  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:05:02.009  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:02.009  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:02.009  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:05:02.016  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:05:02.041   370   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 17:05:02.043   871  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,08-10 17:05:02.043   871  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 17:05:02.048  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:02.049   871   888 D Tethering: MasterInitialState.processMessage what=3
08-10 17:05:02.050  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:02.051  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:02.052  1777  1777 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-10 17:05:02.056  2034  2034 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 17:05:02.060  2034  2034 D SystemUpdateService: onCreate
,08-10 17:05:02.063  2034  2034 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 17:05:02.075  2034  2034 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 17:05:02.077  2034  3541 I iu.UploadsManager: num queued entries: 0
,08-10 17:05:02.081  2034  2034 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 17:05:02.082  2034  2034 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 17:05:02.084  3546  3546 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 17:05:02.087  3546  3546 D SprintDMHelper: simOperator: 
,08-10 17:05:02.087  3546  3546 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 17:05:02.121   370   869 E Netd    : netlink response contains error (No such file or directory)
,08-10 17:05:02.127  2353  3804 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-10 17:05:02.129  2034  3541 I iu.UploadsManager: num updated entries: 0
,08-10 17:05:02.132  2034  3800 I SystemUpdateService: active receiver: enabled
,08-10 17:05:02.140  2034  3541 I iu.SyncManager: NEXT; no task
,08-10 17:05:02.149  2034  3800 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 17:05:02.159  2034  3800 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-10 17:05:02.160  2034  3800 I SystemUpdateService: now status is 0 (complete)
08-10 17:05:02.160  2034  3800 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 17:05:02.160  2034  3800 I SystemUpdateService: file has been verified
08-10 17:05:02.160  2034  3800 I SystemUpdateService: OTA package size = 12249756
,08-10 17:05:02.171  2034  3800 I SystemUpdateService: showing system update notification
,08-10 17:05:02.235  2034  2034 D SystemUpdateService: onDestroy
,08-10 17:05:02.726  1519  3784 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 17:05:02.727  1519  3784 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 17:05:02.727  1519  3784 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:05:02.727  1519  3784 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:05:02.742  1519  3784 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 17:05:02.742  1519  3784 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 17:05:02.742  1519  3784 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 17:05:02.816  1519  3784 D Uploader: Network request failed class java.net.ConnectException(failed to connect to play.googleapis.com/216.58.214.74 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable))
,08-10 17:05:03.800  3598  3679 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-10 17:05:05.833   871  1306 D ConnectivityService: handlePromptUnvalidated 100
,08-10 17:05:06.777   871  1370 I ActivityManager: Killing 3157:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-10 17:05:06.907  3376  3414 D BluetoothAdapterState: Current state: ON, message: 23
,08-10 17:05:06.909  3376  3414 D BluetoothAdapterProperties: Setting state to 13
08-10 17:05:06.909  3376  3414 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13,
08-10 17:05:06.910  3376  3414 D BluetoothAdapterProperties: onBluetoothDisable(),
,08-10 17:05:06.915  3376  3414 I BluetoothAdapterState: Entering PendingCommandState
,08-10 17:05:06.916  3376  3418 D BluetoothAdapterProperties: Scan Mode:20
,08-10 17:05:06.917  3376  3414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-10 17:05:06.923  3376  3376 D HeadsetService: Received stop request...Stopping profile...
,08-10 17:05:06.924  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:05:06.924  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:06.924  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:06.924  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:06.924  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:06.924  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:05:06.924  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:06.924  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:06.924  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:05:06.925  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:05:06.925  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:05:06.927  3376  3376 D A2dpService: Received stop request...Stopping profile...
,08-10 17:05:06.927  3376  3446 D A2dpStateMachine: Exit Disconnected: -1
,08-10 17:05:06.930  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:05:06.931  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:06.931  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:06.931  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:06.931  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:06.931  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:05:06.931  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:06.931  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:06.931  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:05:06.931  1719  2041 D BluetoothHeadset: Proxy object disconnected
,08-10 17:05:06.932  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:05:06.932  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:05:06.934  1363  1363 D BluetoothA2dp: Proxy object disconnected
,08-10 17:05:06.935   871   871 D BluetoothHeadset: Proxy object disconnected
,08-10 17:05:06.935  3376  3376 V BluetoothAdapterState: isTurningOff()=true
08-10 17:05:06.935  3376  3376 V BluetoothAdapterState: isTurningOn()=false
,08-10 17:05:06.935  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:06.935  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:05:06.935  1363  1375 D BluetoothHeadset: Proxy object disconnected
,08-10 17:05:06.936  3376  3376 D HidService: Received stop request...Stopping profile...
08-10 17:05:06.936  3376  3376 D HidService: Stopping Bluetooth HidService
,08-10 17:05:06.936  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:05:06.936  1363  1363 D HeadsetProfile: Bluetooth service disconnected,
08-10 17:05:06.937  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:06.937  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:06.937  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:06.937  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:06.937  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:05:06.937  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:06.937  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:06.937  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:05:06.937  1363  1363 D BluetoothInputDevice: Proxy object disconnected
08-10 17:05:06.937  3433  3433 D BluetoothA2dp: Proxy object disconnected
,08-10 17:05:06.937  1363  1363 D HidProfile: Bluetooth service disconnected
,08-10 17:05:06.938  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:05:06.938  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:05:06.938   871   871 D BluetoothHeadset: Proxy object disconnected
,08-10 17:05:06.939  3433  3433 D BluetoothInputDevice: Proxy object disconnected
08-10 17:05:06.939   871   871 D BluetoothHeadset: Proxy object disconnected
08-10 17:05:06.939  3433  3433 D HidProfile: Bluetooth service disconnected
,08-10 17:05:06.939  3433  3445 D BluetoothHeadset: Proxy object disconnected
08-10 17:05:06.940  3376  3376 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 17:05:06.940  3376  3418 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-10 17:05:06.940  3376  3424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 17:05:06.940  3433  3433 D HeadsetProfile: Bluetooth service disconnected
08-10 17:05:06.941  3376  3424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 17:05:06.941  3376  3424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 17:05:06.942   871   871 D BluetoothA2dp: Proxy object disconnected
,08-10 17:05:06.942  3376  3418 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-10 17:05:06.942  3376  3376 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-10 17:05:06.947  3376  3376 D HealthService: Received stop request...Stopping profile...
08-10 17:05:06.948  3376  3376 D PanService: Received stop request...Stopping profile...
08-10 17:05:06.949  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 17:05:06.950  1363  1363 D PanProfile: Bluetooth service disconnected
08-10 17:05:06.950  3433  3433 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-10 17:05:06.950  3433  3433 D PanProfile: Bluetooth service disconnected
,08-10 17:05:06.950  3376  3376 D BluetoothMapService: Received stop request...Stopping profile...
,08-10 17:05:06.950  3376  3376 D BluetoothMapService: stop()
,08-10 17:05:06.951  3376  3376 D BluetoothMapAppObserver: deinitObservers()
08-10 17:05:06.951  3376  3376 D BluetoothMapAppObserver: removeReceiver()
,08-10 17:05:06.953  1363  1363 D BluetoothMap: Proxy object disconnected
08-10 17:05:06.953  1363  1363 D MapProfile: Bluetooth service disconnected
08-10 17:05:06.953  3433  3433 D BluetoothMap: Proxy object disconnected
,08-10 17:05:06.953  3433  3433 D MapProfile: Bluetooth service disconnected
,08-10 17:05:06.953  3376  3376 V BluetoothAdapterState: isTurningOff()=true
08-10 17:05:06.954  3376  3376 V BluetoothAdapterState: isTurningOn()=false
,08-10 17:05:06.954  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:06.954  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:05:06.955  3376  3418 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-10 17:05:06.955  3376  3424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 17:05:06.955  3376  3424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 17:05:06.955  3376  3424 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-10 17:05:06.955  3376  3424 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-10 17:05:06.955  3376  3424 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-10 17:05:06.955  3376  3424 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-10 17:05:06.956  3376  3376 V BluetoothAdapterState: isTurningOff()=true
,08-10 17:05:06.956  3376  3376 V BluetoothAdapterState: isTurningOn()=false
,08-10 17:05:06.956  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 17:05:06.956  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:05:06.957  3376  3376 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-10 17:05:06.957  3376  3418 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 17:05:06.957  3376  3376 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-10 17:05:06.957  3376  3376 V BluetoothAdapterState: isTurningOff()=true
,08-10 17:05:06.957  3376  3376 V BluetoothAdapterState: isTurningOn()=false
,08-10 17:05:06.957  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 17:05:06.957  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:05:06.958  3376  3376 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-10 17:05:06.958  3376  3418 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-10 17:05:06.960  3376  3376 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 17:05:06.960  3376  3376 V BluetoothAdapterState: isTurningOff()=true
08-10 17:05:06.960  3376  3376 V BluetoothAdapterState: isTurningOn()=false
08-10 17:05:06.960  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:06.960  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:05:06.961  3376  3376 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 17:05:06.961  3376  3376 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 17:05:06.962  3376  3376 D BluetoothMapService: MAP Service closeService in
08-10 17:05:06.962  3376  3376 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 17:05:06.963  3376  3376 D ObexServerSockets0: shutdown(block = true)
08-10 17:05:06.963  3376  3451 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-10 17:05:06.964  3376  3376 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 17:05:06.964  3376  3426 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 17:05:06.964  3376  3452 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 17:05:06.964  3376  3376 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 17:05:06.965  3376  3376 V BluetoothAdapterState: isTurningOff()=true
08-10 17:05:06.965  3376  3376 V BluetoothAdapterState: isTurningOn()=false
08-10 17:05:06.965  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:06.965  3376  3376 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:05:06.965  3376  3414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 17:05:06.965  3376  3414 D BluetoothAdapterProperties: Setting state to 15
08-10 17:05:06.965  3376  3414 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-10 17:05:06.966  3376  3376 D BluetoothMapService: cleanup()
08-10 17:05:06.966  3376  3376 D BluetoothMapService: MAP Service closeService in
08-10 17:05:06.966  3433  3443 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:05:06.966  3376  3414 I BluetoothAdapterState: Entering BleOnState
08-10 17:05:06.966  1363  1820 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 17:05:06.967  3376  3376 I BtOppRfcommListener: stopping Accept Thread
08-10 17:05:06.967  3376  3488 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 17:05:06.967  3433  3445 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 17:05:06.967  3376  3488 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 17:05:06.968   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 17:05:06.968   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 17:05:06.968  3433  3443 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 17:05:06.969  1719  1729 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:05:06.969  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:06.970  1363  1383 D BluetoothMap: onBluetoothStateChange: up=false
08-10 17:05:06.970  3433  3445 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 17:05:06.970  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:06.971  1363  1375 D BluetoothPan: onBluetoothStateChange on: false
,08-10 17:05:06.972  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:06.972  1363  1820 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:05:06.972  1363  1383 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 17:05:06.972  1363  1375 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 17:05:06.973   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:05:06.973  3433  3443 D BluetoothPan: onBluetoothStateChange on: false
08-10 17:05:06.974   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 17:05:06.974  3433  3445 D BluetoothMap: onBluetoothStateChange: up=false
08-10 17:05:06.974  3376  3414 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-10 17:05:06.974  3376  3414 D BluetoothAdapterProperties: Setting state to 16
08-10 17:05:06.974  3376  3414 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-10 17:05:06.975  3376  3414 D BluetoothAdapterProperties: onBleDisable
08-10 17:05:06.975  3376  3414 I BluetoothAdapterState: Entering PendingCommandState
08-10 17:05:06.975  3376  3415 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-10 17:05:06.976  3376  3424 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms,
08-10 17:05:06.976  3433  3433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 17:05:06.976  3376  3424 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 17:05:06.978  3376  3418 D BluetoothAdapterProperties: Scan Mode:20
,08-10 17:05:06.978  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:06.979  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:06.981  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:06.982  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:06.985  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 17:05:06.985  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:06.988  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:06.999  3433  3433 D DockEventReceiver: finishStartingService: stopping service
08-10 17:05:07.003  3433  3433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 17:05:07.009  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 17:05:07.014  3433  3433 D DockEventReceiver: finishStartingService: stopping service
,08-10 17:05:07.184  3376  3418 I bt_hci  : shut_down
,08-10 17:05:07.184  3376  3422 D bt_hwcfg: hw_epilog_process
,08-10 17:05:07.206  3376  3422 I bt_vendor: low_power_mode_cb
,08-10 17:05:07.216  3376  3422 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-10 17:05:07.216  3376  3422 I bt_vendor: epilog_cb
08-10 17:05:07.216  3376  3422 I bt_hci  : epilog_finished_callback
,08-10 17:05:07.221  3376  3418 I bt_hci_h4: hal_close
,08-10 17:05:07.223  3376  3418 I bt_userial_vendor: device fd = 51 close
,08-10 17:05:07.350  3376  3415 D bt_stack_manager: event_shut_down_stack finished.
,08-10 17:05:07.352  3376  3414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 17:05:07.360  3376  3376 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 17:05:07.361  3376  3414 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-10 17:05:07.362  3376  3376 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 17:05:07.363  3376  3376 D BtGatt.GattService: stop()
08-10 17:05:07.363  3376  3376 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 17:05:07.368  3376  3376 V BluetoothAdapterState: isTurningOff()=false
08-10 17:05:07.368  3376  3376 V BluetoothAdapterState: isTurningOn()=false
,08-10 17:05:07.368  3376  3376 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 17:05:07.368  3376  3376 V BluetoothAdapterState: isBleTurningOff()=true
08-10 17:05:07.369  3376  3414 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-10 17:05:07.370  3376  3414 D BluetoothAdapterProperties: Setting state to 10
08-10 17:05:07.371  3376  3414 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-10 17:05:07.372  3376  3414 I BluetoothAdapterState: Entering OffState
,08-10 17:05:07.373   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-10 17:05:07.388  3376  3376 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-10 17:05:07.388  3376  3376 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-10 17:05:07.388  3376  3415 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-10 17:05:07.390  3376  3415 D bt_stack_manager: event_clean_up_stack finished.
08-10 17:05:07.391  3376  3376 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-10 17:05:07.393  3376  3376 I art     : System.exit called, status: 0
,08-10 17:05:07.393  3376  3376 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 17:05:07.473   871  2817 I ActivityManager: Process com.android.bluetooth (pid 3376) has died
,08-10 17:05:08.853  2567  2577 D Finsky  : [172] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-10 17:05:08.878  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:05:08.891  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:05:08.897  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:05:08.969  1519  2672 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 17:05:08.970  1519  2672 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-10 17:05:08.970  1519  2672 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 17:05:08.971  1519  2672 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:05:09.037  2567  2577 D Finsky  : [172] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-10 17:05:11.952   871   888 I ActivityManager: Start proc 3822:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 17:05:12.065  3822  3822 D AdapterServiceConfig: Adding HeadsetService
,08-10 17:05:12.065  3822  3822 D AdapterServiceConfig: Adding A2dpService
08-10 17:05:12.065  3822  3822 D AdapterServiceConfig: Adding HidService
,08-10 17:05:12.066  3822  3822 D AdapterServiceConfig: Adding HealthService
,08-10 17:05:12.066  3822  3822 D AdapterServiceConfig: Adding PanService
08-10 17:05:12.066  3822  3822 D AdapterServiceConfig: Adding GattService
,08-10 17:05:12.066  3822  3822 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 17:05:12.085  3822  3822 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 17:05:12.085   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c506303:true
,08-10 17:05:12.090  3822  3822 I bt_bluedroid: init
,08-10 17:05:12.091  3822  3834 I BluetoothAdapterState: Entering OffState
,08-10 17:05:12.097  3822  3835 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 17:05:12.097  3822  3835 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-10 17:05:12.097  3822  3835 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-10 17:05:12.098  3822  3835 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 17:05:12.099  3822  3822 I bt_bluedroid: get_profile_interface socket
,08-10 17:05:12.102  3822  3822 I bt_bluedroid: get_profile_interface sdp
,08-10 17:05:12.108  3822  3832 I bt_bluedroid: config_hci_snoop_log
08-10 17:05:12.110  3822  3838 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-10 17:05:12.112   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-10 17:05:12.113  3822  3838 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 17:05:12.124  3822  3834 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 17:05:12.124  3822  3834 D BluetoothAdapterProperties: Setting state to 14
,08-10 17:05:12.125  3822  3834 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 17:05:12.129  3822  3834 D BluetoothBondStateMachine: make
,08-10 17:05:12.133  3822  3839 I BluetoothBondStateMachine: StableState(): Entering Off State
08-10 17:05:12.139  3822  3834 I BluetoothAdapterState: Entering PendingCommandState
08-10 17:05:12.142  3822  3822 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
08-10 17:05:12.148  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
08-10 17:05:12.150  3822  3822 D BtGatt.DebugUtils: handleDebugAction() action=null
08-10 17:05:12.151  3822  3822 D BtGatt.GattService: Received start request. Starting profile...
08-10 17:05:12.152  3822  3822 D BtGatt.GattService: start()
08-10 17:05:12.152  3822  3822 I bt_bluedroid: get_profile_interface gatt
08-10 17:05:12.153  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
08-10 17:05:12.154  3822  3822 D BtGatt.AdvertiseManager: advertise manager created
08-10 17:05:12.166  3822  3822 V BluetoothAdapterState: isTurningOff()=false
08-10 17:05:12.166  3822  3822 V BluetoothAdapterState: isTurningOn()=false
08-10 17:05:12.166  3822  3822 V BluetoothAdapterState: isBleTurningOn()=true
08-10 17:05:12.167  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:05:12.169  3822  3834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-10 17:05:12.170  3822  3834 I bt_bluedroid: enable
08-10 17:05:12.170  3822  3835 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-10 17:05:12.171  3822  3835 I bt_hci  : start_up
08-10 17:05:12.194  3822  3835 I bt_vendor: alloc value 0xb3a5c189
08-10 17:05:12.194  3822  3835 I bt_vendor: init
08-10 17:05:12.195  3822  3835 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-10 17:05:12.195  3822  3835 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 17:05:12.304  3822  3835 D bt_hci  : start_up starting async portion
,08-10 17:05:12.305  3822  3842 I bt_hci  : event_finish_startup
,08-10 17:05:12.305  3822  3842 I bt_hci_h4: hal_open
08-10 17:05:12.306  3822  3842 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 17:05:12.312  3822  3842 I bt_userial_vendor: device fd = 51 open
,08-10 17:05:12.347  3822  3842 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 17:05:12.379  3822  3842 D bt_hwcfg: Chipset BCM4354A2
,08-10 17:05:12.379  3822  3842 D bt_hwcfg: Target name = [BCM4354A2]
,08-10 17:05:12.380  3822  3842 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 17:05:13.037  3822  3842 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 17:05:13.038  3822  3842 D bt_hwcfg: Settlement delay -- 100 ms
08-10 17:05:13.039  3822  3842 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 17:05:13.156  3822  3842 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 17:05:13.157  3822  3842 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 17:05:13.186  3822  3842 I bt_hwcfg: vendor lib fwcfg completed
,08-10 17:05:13.187  3822  3842 I bt_vendor: firmware callback
,08-10 17:05:13.187  3822  3842 I bt_hci  : firmware_config_callback
,08-10 17:05:13.199  3822  3844 I bt_btu  : btu_task pending for preload complete event
,08-10 17:05:13.199  3822  3844 I bt_btu_task: Bluetooth chip preload is complete
08-10 17:05:13.199  3822  3844 I bt_btu  : btu_task received preload complete event
,08-10 17:05:13.210  3822  3844 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 17:05:13.210  3822  3844 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 17:05:13.210  3822  3844 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-10 17:05:13.210  3822  3844 I         : BTE_InitTraceLevels -- TRC_AVDT
08-10 17:05:13.211  3822  3844 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 17:05:13.211  3822  3844 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 17:05:13.211  3822  3844 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 17:05:13.211  3822  3844 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 17:05:13.212  3822  3844 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 17:05:13.212  3822  3844 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 17:05:13.212  3822  3844 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 17:05:13.212  3822  3844 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 17:05:13.213  3822  3844 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 17:05:13.213  3822  3844 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 17:05:13.213  3822  3844 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 17:05:13.347  3822  3844 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39d9d9d
,08-10 17:05:13.347  3822  3844 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39d9d9d 
,08-10 17:05:13.375  3822  3838 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 17:05:13.377  3822  3838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 17:05:13.377  3822  3838 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 17:05:13.378  3822  3838 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 17:05:13.381  3822  3838 D BluetoothAdapterProperties: Scan Mode:20
,08-10 17:05:13.382  3822  3838 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 17:05:13.383  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:13.383  3822  3838 D bt_hci  : do_postload posting postload work item
08-10 17:05:13.384  3822  3842 I bt_hci  : event_postload
08-10 17:05:13.384  3822  3842 I bt_vendor: sco_config_cb
08-10 17:05:13.384  3822  3842 I bt_hci  : sco_config_callback postload finished.
08-10 17:05:13.386  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:13.387  3822  3838 D bt_bte_conf: Device ID record 1 : primary
08-10 17:05:13.387  3822  3838 D bt_bte_conf:   vendorId            = 000f
08-10 17:05:13.387  3822  3838 D bt_bte_conf:   vendorIdSource      = 0001
08-10 17:05:13.387  3822  3838 D bt_bte_conf:   product             = 1200
08-10 17:05:13.387  3822  3838 D bt_bte_conf:   version             = 1436
08-10 17:05:13.387  3822  3838 D bt_bte_conf:   clientExecutableURL = 
08-10 17:05:13.387  3822  3838 D bt_bte_conf:   serviceDescription  = 
08-10 17:05:13.387  3822  3838 D bt_bte_conf:   documentationURL    = 
08-10 17:05:13.387  3822  3838 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-10 17:05:13.387  3822  3835 D bt_stack_manager: event_start_up_stack finished
,08-10 17:05:13.388  3822  3834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-10 17:05:13.388  3822  3834 D BluetoothAdapterProperties: Setting state to 15
,08-10 17:05:13.388  3822  3834 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-10 17:05:13.390  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:13.391  3822  3834 I BluetoothAdapterState: Entering BleOnState
,08-10 17:05:13.397  3822  3834 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-10 17:05:13.397  3822  3834 D BluetoothAdapterProperties: Setting state to 11
,08-10 17:05:13.397  3822  3834 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 17:05:13.409  3822  3842 I bt_vendor: low_power_mode_cb
,08-10 17:05:13.413  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:13.415  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:13.417  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:13.419  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:05:13.421  3822  3822 D HeadsetService: Received start request. Starting profile...
,08-10 17:05:13.425  3822  3822 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-10 17:05:13.425  3822  3822 D HeadsetStateMachine: make
,08-10 17:05:13.432  3822  3834 I BluetoothAdapterState: Entering PendingCommandState
,08-10 17:05:13.446  3822  3822 D HeadsetStateMachine: max_hf_connections = 1
,08-10 17:05:13.447  3822  3822 I bt_bluedroid: get_profile_interface handsfree
,08-10 17:05:13.449  3822  3838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-10 17:05:13.450  3822  3838 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-10 17:05:13.455  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:05:13.455  3822  3822 D A2dpService: Received start request. Starting profile...
,08-10 17:05:13.456  3822  3822 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 17:05:13.456  3822  3822 I bt_bluedroid: get_profile_interface avrcp
,08-10 17:05:13.457  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 17:05:13.464  3822  3822 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 17:05:13.464  3822  3822 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 17:05:13.464  3822  3822 D A2dpStateMachine: make
,08-10 17:05:13.466  3822  3822 I bt_bluedroid: get_profile_interface a2dp
,08-10 17:05:13.466  3822  3838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-10 17:05:13.467  3822  3852 D A2dpStateMachine: Enter Disconnected: -2
08-10 17:05:13.468  3822  3822 I BluetoothHidServiceJni: classInitNative: succeeds
08-10 17:05:13.469  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
08-10 17:05:13.469  3822  3822 D HidService: Received start request. Starting profile...
08-10 17:05:13.470  3822  3822 I bt_bluedroid: get_profile_interface hidhost
,08-10 17:05:13.470  3822  3822 D HidService: setHidService(): set to: null
,08-10 17:05:13.470  3822  3838 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bb3e5
,08-10 17:05:13.470  3822  3838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-10 17:05:13.470  3822  3822 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 17:05:13.471  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:05:13.472  3822  3822 D HealthService: Received start request. Starting profile...
,08-10 17:05:13.474  3822  3822 I bt_bluedroid: get_profile_interface health
,08-10 17:05:13.475  3822  3822 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 17:05:13.476  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:05:13.476  3822  3822 D PanService: Received start request. Starting profile...
,08-10 17:05:13.477  3822  3822 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-10 17:05:13.477  3822  3822 I bt_bluedroid: get_profile_interface pan
,08-10 17:05:13.478  3822  3838 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 17:05:13.483  3822  3822 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@63b91e
,08-10 17:05:13.484  3822  3822 D BluetoothMapService: Received start request. Starting profile...
,08-10 17:05:13.485  3822  3822 D BluetoothMapService: start()
,08-10 17:05:13.489  3822  3822 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 17:05:13.490  3822  3822 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-10 17:05:13.490  3822  3822 D BluetoothMapAppObserver: createReceiver()
,08-10 17:05:13.492  3822  3822 D BluetoothMapAppObserver: initObservers()
,08-10 17:05:13.492  3822  3822 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 17:05:13.505  3822  3822 V BluetoothAdapterState: isTurningOff()=false
,08-10 17:05:13.506  3822  3822 V BluetoothAdapterState: isTurningOn()=true
,08-10 17:05:13.506  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 17:05:13.506  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:05:13.509  3822  3850 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-10 17:05:13.509  3822  3822 V BluetoothAdapterState: isTurningOff()=false
08-10 17:05:13.509  3822  3822 V BluetoothAdapterState: isTurningOn()=true
,08-10 17:05:13.509  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:13.510  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:05:13.510  3822  3822 V BluetoothAdapterState: isTurningOff()=false
,08-10 17:05:13.510  3822  3822 V BluetoothAdapterState: isTurningOn()=true
08-10 17:05:13.510  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:13.510  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:05:13.510  3822  3822 V BluetoothAdapterState: isTurningOff()=false
,08-10 17:05:13.510  3822  3822 V BluetoothAdapterState: isTurningOn()=true
08-10 17:05:13.510  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 17:05:13.510  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:05:13.511  3822  3822 V BluetoothAdapterState: isTurningOff()=false
08-10 17:05:13.511  3822  3822 V BluetoothAdapterState: isTurningOn()=true
08-10 17:05:13.511  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 17:05:13.511  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:05:13.511  3822  3822 V BluetoothAdapterState: isTurningOff()=false
08-10 17:05:13.511  3822  3822 V BluetoothAdapterState: isTurningOn()=true
08-10 17:05:13.511  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 17:05:13.511  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:05:13.512  3822  3834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-10 17:05:13.512  3822  3834 D BluetoothAdapterProperties: ScanMode =  20
,08-10 17:05:13.512  3822  3834 D BluetoothAdapterProperties: State =  11
08-10 17:05:13.512  3822  3834 D BluetoothAdapterProperties: Setting state to 12
,08-10 17:05:13.512  3822  3834 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 17:05:13.513  3822  3834 I BluetoothAdapterState: Entering OnState
08-10 17:05:13.513  3433  3443 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 17:05:13.514  3822  3838 D BluetoothAdapterProperties: Scan Mode:21
08-10 17:05:13.514  3822  3838 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 17:05:13.517  1363  1383 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 17:05:13.518  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:13.518  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:13.518  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:13.518  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:13.518  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:05:13.518  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:13.518  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:13.518  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:05:13.520  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:05:13.523  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:13.523  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:13.523  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:13.523  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:13.523  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:05:13.523  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:13.523  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:13.523  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:05:13.524  3822  3822 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 17:05:13.525  3822  3822 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-10 17:05:13.525  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:05:13.526  3433  3445 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 17:05:13.526  3822  3822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 17:05:13.529  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:13.529  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:13.529  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:13.529  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:13.529  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 17:05:13.529  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:13.529  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:13.529  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:05:13.530  3822  3822 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 17:05:13.531   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 17:05:13.531   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 17:05:13.532  3822  3822 D ObexServerSockets: Succeed to create listening sockets 
08-10 17:05:13.532  3822  3822 D ObexServerSockets0: startAccept()
08-10 17:05:13.532  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:05:13.532  3822  3822 D ObexServerSockets0: prepareForNewConnect()
08-10 17:05:13.532  3433  3443 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 17:05:13.534  3822  3822 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-10 17:05:13.534  3822  3822 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-10 17:05:13.535  3822  3858 D ObexServerSockets0: Accepting socket connection...
,08-10 17:05:13.535  3822  3859 D ObexServerSockets0: Accepting socket connection...
,08-10 17:05:13.536  1363  1363 D BluetoothInputDevice: Proxy object connected
08-10 17:05:13.536  1363  1363 D HidProfile: Bluetooth service connected
08-10 17:05:13.537   871   871 D BluetoothA2dp: Proxy object connected
08-10 17:05:13.537  1719  1729 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 17:05:13.538  1363  1820 D BluetoothMap: onBluetoothStateChange: up=true
08-10 17:05:13.538  3433  3433 D BluetoothInputDevice: Proxy object connected
08-10 17:05:13.539  3433  3433 D HidProfile: Bluetooth service connected
,08-10 17:05:13.541  3433  3445 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 17:05:13.541  1363  1363 D BluetoothMap: Proxy object connected
,08-10 17:05:13.542  1363  1363 D MapProfile: Bluetooth service connected
08-10 17:05:13.542  1363  1363 D BluetoothMap: getConnectedDevices()
08-10 17:05:13.542  3433  3433 D BluetoothA2dp: Proxy object connected
,08-10 17:05:13.544  1363  1375 D BluetoothPan: onBluetoothStateChange on: true
,08-10 17:05:13.546  1363  1820 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 17:05:13.546  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 17:05:13.546  1363  1363 D PanProfile: Bluetooth service connected
08-10 17:05:13.546  1363  1375 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 17:05:13.548  1363  1363 D BluetoothA2dp: Proxy object connected
,08-10 17:05:13.548  1363  1820 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 17:05:13.550   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 17:05:13.550  3433  3443 D BluetoothPan: onBluetoothStateChange on: true
,08-10 17:05:13.553   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 17:05:13.553  3433  3433 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 17:05:13.553  3433  3445 D BluetoothMap: onBluetoothStateChange: up=true
08-10 17:05:13.553  3433  3433 D PanProfile: Bluetooth service connected
,08-10 17:05:13.554  3433  3433 D BluetoothMap: Proxy object connected
08-10 17:05:13.554  3433  3433 D MapProfile: Bluetooth service connected
,08-10 17:05:13.554  3433  3433 D BluetoothMap: getConnectedDevices()
08-10 17:05:13.555   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,08-10 17:05:13.558  3822  3822 D BluetoothMapService: onReceive
,08-10 17:05:13.558  3822  3822 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 17:05:13.559  3822  3822 D BluetoothMapService: STATE_ON
,08-10 17:05:13.560  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:13.561  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:13.563  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:13.566  3433  3433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 17:05:13.573  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 17:05:13.574  3433  3433 D DockEventReceiver: finishStartingService: stopping service
,08-10 17:05:13.583  1363  1363 D BluetoothPbap: Proxy object connected
,08-10 17:05:13.583  1363  1363 D PbapServerProfile: Bluetooth service connected
08-10 17:05:13.583  3433  3433 D BluetoothPbap: Proxy object connected
,08-10 17:05:13.584  3433  3433 D PbapServerProfile: Bluetooth service connected
,08-10 17:05:13.588  3822  3822 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 17:05:13.588  3822  3822 D ObexServerSockets0: prepareForNewConnect()
,08-10 17:05:13.591  3822  3866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 17:05:13.607  3822  3870 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 17:05:13.609  3822  3870 I BtOppRfcommListener: Accept thread started.
,08-10 17:05:13.615  1719  1737 D BluetoothHeadset: Proxy object connected
,08-10 17:05:13.615   871   871 D BluetoothHeadset: Proxy object connected
,08-10 17:05:13.615  1363  1383 D BluetoothHeadset: Proxy object connected
08-10 17:05:13.615  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-10 17:05:13.615   871   871 D BluetoothHeadset: Proxy object connected
08-10 17:05:13.616   871   871 D BluetoothHeadset: Proxy object connected
08-10 17:05:13.616  3433  3443 D BluetoothHeadset: Proxy object connected,
08-10 17:05:13.617  3433  3433 D HeadsetProfile: Bluetooth service connected
,08-10 17:05:13.632   871   888 D BluetoothHeadset: Proxy object connected
,08-10 17:05:13.637  1719  1877 D BluetoothHeadset: Proxy object connected
,08-10 17:05:13.647  1363  1820 D BluetoothHeadset: Proxy object connected
,08-10 17:05:13.647  1363  1363 D HeadsetProfile: Bluetooth service connected
,08-10 17:05:13.651   871   888 D BluetoothHeadset: Proxy object connected
,08-10 17:05:13.653   871   888 D BluetoothHeadset: Proxy object connected
,08-10 17:05:14.984  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:05:14.995  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:05:14.998  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:05:15.054  1519  1531 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 17:05:15.055  1519  1531 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-10 17:05:15.055  1519  1531 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 17:05:15.055  1519  1531 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:05:15.111  2567  2567 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 17:05:15.111  2567  2567 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 17:05:15.112  2567  2567 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-10 17:05:15.173   871   880 I art     : Background partial concurrent mark sweep GC freed 28200(1791KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 28MB/43MB, paused 5.591ms total 102.650ms
,08-10 17:05:16.905  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 17:05:16.906  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:05:21.911  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 17:05:21.912  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9072505 removed from the list
,08-10 17:05:21.912  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 17:05:21.912  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:05:21.913  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 17:05:21.915  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 17:05:21.916  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5a0c81 added. We now have 4 listener(s)
08-10 17:05:21.916  3309  3358 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 17:05:21.920  3309  3358 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 17:05:21.921  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f5a0c81 removed from the list
08-10 17:05:21.921  3309  3358 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 17:05:21.921  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 17:05:21.922  3309  3358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 17:05:21.924  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 17:05:21.924  3309  3358 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ecd126 added. We now have 4 listener(s)
08-10 17:05:21.925  3309  3358 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 17:05:21.931  3309  3358 I System.out: IsBluetoothEnabled
,08-10 17:05:21.940  3822  3834 D BluetoothAdapterState: Current state: ON, message: 23
,08-10 17:05:21.940  3822  3834 D BluetoothAdapterProperties: Setting state to 13
08-10 17:05:21.940  3822  3834 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-10 17:05:21.943  3822  3834 D BluetoothAdapterProperties: onBluetoothDisable()
,08-10 17:05:21.947  3822  3834 I BluetoothAdapterState: Entering PendingCommandState
08-10 17:05:21.950  3822  3822 D BluetoothMapService: onReceive
08-10 17:05:21.950  3822  3822 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-10 17:05:21.951  3822  3822 D BluetoothMapService: STATE_TURNING_OFF
,08-10 17:05:21.952  3822  3822 D BluetoothMapService: MAP Service closeService in
,08-10 17:05:21.952  3822  3822 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 17:05:21.952  3822  3822 D ObexServerSockets0: shutdown(block = true)
08-10 17:05:21.957  3822  3838 D BluetoothAdapterProperties: Scan Mode:20
,08-10 17:05:21.957  3822  3834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-10 17:05:21.958  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:05:21.958  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:21.958  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:21.958  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:21.958  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:21.958  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:05:21.958  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:21.958  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:21.958  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 17:05:21.959  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:05:21.959  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:05:21.962  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:05:21.962  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:21.962  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:21.962  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:21.962  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:21.962  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:05:21.962  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:21.962  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:21.962  3309  3309 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:05:21.963  3822  3822 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 17:05:21.963  3822  3858 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-10 17:05:21.963  3822  3859 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 17:05:21.964  3822  3822 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-10 17:05:21.964  3822  3847 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-10 17:05:21.965  3822  3822 D HeadsetService: Received stop request...Stopping profile...
08-10 17:05:21.965  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:05:21.965  3309  3358 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 17:05:21.965  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 17:05:21.965  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 17:05:21.965  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 17:05:21.965  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 17:05:21.965  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 17:05:21.965  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 17:05:21.965  3309  3358 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 17:05:21.967  3309  3309 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 17:05:21.967  3309  3309 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 17:05:21.969  3822  3822 D A2dpService: Received stop request...Stopping profile...
08-10 17:05:21.970  3309  3358 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 17:05:21.970  3309  3358 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 17:05:21.970  3822  3852 D A2dpStateMachine: Exit Disconnected: -1
08-10 17:05:21.971  1719  1729 D BluetoothHeadset: Proxy object disconnected
08-10 17:05:21.971   871   871 D BluetoothHeadset: Proxy object disconnected
08-10 17:05:21.972  3433  3433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 17:05:21.974  1363  1363 D BluetoothA2dp: Proxy object disconnected
,08-10 17:05:21.975  1363  1375 D BluetoothHeadset: Proxy object disconnected
08-10 17:05:21.976  1363  1363 D HeadsetProfile: Bluetooth service disconnected
08-10 17:05:21.976   871   871 D BluetoothHeadset: Proxy object disconnected
08-10 17:05:21.976   871   871 D BluetoothHeadset: Proxy object disconnected
,08-10 17:05:21.976  3433  3445 D BluetoothHeadset: Proxy object disconnected
08-10 17:05:21.977  3822  3822 D HidService: Received stop request...Stopping profile...
08-10 17:05:21.977   871   871 D BluetoothA2dp: Proxy object disconnected
08-10 17:05:21.977  3822  3822 D HidService: Stopping Bluetooth HidService
08-10 17:05:21.977  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:21.979  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:21.982  1363  1363 D BluetoothInputDevice: Proxy object disconnected
08-10 17:05:21.982  1363  1363 D HidProfile: Bluetooth service disconnected
,08-10 17:05:21.983  3822  3822 D HealthService: Received stop request...Stopping profile...
08-10 17:05:21.983  3822  3834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
08-10 17:05:21.983  3822  3834 I BluetoothAdapterState: Deferring BLE_TURN_ON request...
,08-10 17:05:21.984  3822  3822 I BtOppRfcommListener: stopping Accept Thread
08-10 17:05:21.985  3822  3870 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 17:05:21.985  3822  3870 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-10 17:05:21.988  3433  3433 D BluetoothA2dp: Proxy object disconnected
,08-10 17:05:21.988  3433  3433 D HeadsetProfile: Bluetooth service disconnected
,08-10 17:05:21.988  3822  3822 D PanService: Received stop request...Stopping profile...
08-10 17:05:21.989  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 17:05:21.989  3822  3822 V BluetoothAdapterState: isTurningOff()=true
08-10 17:05:21.990  1363  1363 D PanProfile: Bluetooth service disconnected
08-10 17:05:21.990  3822  3822 V BluetoothAdapterState: isTurningOn()=false
,08-10 17:05:21.990  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:21.990  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:05:21.991  3822  3822 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-10 17:05:21.991  3822  3822 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-10 17:05:21.992  3822  3838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-10 17:05:21.992  3822  3844 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 17:05:21.992  3822  3844 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 17:05:21.992  3822  3844 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 17:05:21.992  3822  3838 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-10 17:05:21.992  3822  3822 D BluetoothMapService: Received stop request...Stopping profile...
,08-10 17:05:21.993  3822  3822 D BluetoothMapService: stop()
08-10 17:05:21.994  3822  3822 D BluetoothMapAppObserver: deinitObservers()
,08-10 17:05:21.994  3822  3822 D BluetoothMapAppObserver: removeReceiver()
,08-10 17:05:21.995  1363  1363 D BluetoothMap: Proxy object disconnected
08-10 17:05:21.995  1363  1363 D MapProfile: Bluetooth service disconnected
08-10 17:05:21.996  3822  3822 V BluetoothAdapterState: isTurningOff()=true
08-10 17:05:21.996  3822  3822 V BluetoothAdapterState: isTurningOn()=false
,08-10 17:05:21.996  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:21.996  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:05:21.999  3822  3822 V BluetoothAdapterState: isTurningOff()=true
,08-10 17:05:21.999  3822  3822 V BluetoothAdapterState: isTurningOn()=false
,08-10 17:05:21.999  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:21.999  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:05:21.999  3822  3822 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-10 17:05:21.999  3822  3822 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 17:05:22.000  3822  3844 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 17:05:22.000  3822  3844 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 17:05:22.000  3822  3844 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 17:05:22.000  3822  3844 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 17:05:22.000  3822  3844 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-10 17:05:22.000  3822  3844 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 17:05:22.000  3822  3838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 17:05:22.000  3822  3838 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 17:05:22.001  3822  3822 V BluetoothAdapterState: isTurningOff()=true
08-10 17:05:22.001  3822  3822 V BluetoothAdapterState: isTurningOn()=false
08-10 17:05:22.001  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:22.001  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:05:22.002  3822  3822 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-10 17:05:22.002  3822  3838 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-10 17:05:22.003  3822  3822 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-10 17:05:22.007  3822  3822 V BluetoothAdapterState: isTurningOff()=true
,08-10 17:05:22.007  3822  3822 V BluetoothAdapterState: isTurningOn()=false
08-10 17:05:22.007  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:22.007  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 17:05:22.010  3822  3822 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 17:05:22.010  3822  3822 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-10 17:05:22.011  3822  3822 D BluetoothMapService: MAP Service closeService in
,08-10 17:05:22.011  3822  3822 V BluetoothAdapterState: isTurningOff()=true
,08-10 17:05:22.011  3822  3822 V BluetoothAdapterState: isTurningOn()=false
08-10 17:05:22.011  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:22.011  3822  3822 V BluetoothAdapterState: isBleTurningOff()=false
08-10 17:05:22.011  3822  3834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 17:05:22.011  3822  3834 D BluetoothAdapterProperties: Setting state to 15
,08-10 17:05:22.011  3822  3834 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-10 17:05:22.012  3433  3443 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:05:22.012  3822  3834 I BluetoothAdapterState: Entering BleOnState
08-10 17:05:22.012  1363  1820 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 17:05:22.013  3822  3834 D BluetoothAdapterState: Current state: BLE ON, message: 0
08-10 17:05:22.013  3822  3822 D BluetoothMapService: cleanup()
08-10 17:05:22.013  3822  3822 D BluetoothMapService: MAP Service closeService in
08-10 17:05:22.013  3433  3445 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 17:05:22.013   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:05:22.013   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 17:05:22.014  3433  3860 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 17:05:22.014  1719  1737 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:05:22.015  1363  1375 D BluetoothMap: onBluetoothStateChange: up=false
08-10 17:05:22.015  1363  1363 D BluetoothPbap: Proxy object disconnected
08-10 17:05:22.015  1363  1363 D PbapServerProfile: Bluetooth service disconnected
08-10 17:05:22.015  3433  3445 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 17:05:22.016  1363  1383 D BluetoothPan: onBluetoothStateChange on: false
08-10 17:05:22.017  1363  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:05:22.017  1363  1820 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 17:05:22.017  1363  1383 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 17:05:22.018   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:05:22.018  3433  3860 D BluetoothPan: onBluetoothStateChange on: false
08-10 17:05:22.018   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 17:05:22.018  3433  3443 D BluetoothMap: onBluetoothStateChange: up=false
08-10 17:05:22.014  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 17:05:22.019  3822  3834 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-10 17:05:22.019  3822  3834 D BluetoothAdapterProperties: Setting state to 16
08-10 17:05:22.019  3822  3834 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-10 17:05:22.019  3822  3834 D BluetoothAdapterProperties: onBleDisable
08-10 17:05:22.021  3822  3834 I BluetoothAdapterState: Entering PendingCommandState
08-10 17:05:22.021  3822  3835 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-10 17:05:22.022  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:22.022  3822  3838 D BluetoothAdapterProperties: Scan Mode:20
08-10 17:05:22.023  3822  3844 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 17:05:22.023  3822  3844 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 17:05:22.023  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:22.024  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 17:05:22.026  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:22.031  3433  3433 D DockEventReceiver: finishStartingService: stopping service
,08-10 17:05:22.033  3433  3433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 17:05:22.038  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 17:05:22.045  3433  3433 D DockEventReceiver: finishStartingService: stopping service
,08-10 17:05:22.233  3822  3838 I bt_hci  : shut_down
,08-10 17:05:22.233  3822  3842 D bt_hwcfg: hw_epilog_process
,08-10 17:05:22.247  3822  3842 I bt_vendor: low_power_mode_cb
,08-10 17:05:22.267  3822  3842 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-10 17:05:22.268  3822  3842 I bt_vendor: epilog_cb
08-10 17:05:22.268  3822  3842 I bt_hci  : epilog_finished_callback
,08-10 17:05:22.275  3822  3838 I bt_hci_h4: hal_close
,08-10 17:05:22.277  3822  3838 I bt_userial_vendor: device fd = 51 close
,08-10 17:05:22.403  3822  3835 D bt_stack_manager: event_shut_down_stack finished.
,08-10 17:05:22.404  3822  3834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 17:05:22.414  3822  3822 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 17:05:22.414  3822  3834 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-10 17:05:22.416  3822  3822 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 17:05:22.417  3822  3822 D BtGatt.GattService: stop()
,08-10 17:05:22.419  3822  3822 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 17:05:22.425  3822  3822 V BluetoothAdapterState: isTurningOff()=false
,08-10 17:05:22.427  3822  3822 V BluetoothAdapterState: isTurningOn()=false
08-10 17:05:22.427  3822  3822 V BluetoothAdapterState: isBleTurningOn()=false
08-10 17:05:22.427  3822  3822 V BluetoothAdapterState: isBleTurningOff()=true
,08-10 17:05:22.428  3822  3834 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-10 17:05:22.428  3822  3834 D BluetoothAdapterProperties: Setting state to 10
08-10 17:05:22.428  3822  3834 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-10 17:05:22.430  3822  3834 I BluetoothAdapterState: Entering OffState
,08-10 17:05:22.438  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:22.441  3433  3433 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 17:05:22.442  3309  3309 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 17:05:22.449  1519  1519 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 17:05:22.459  3433  3433 D DockEventReceiver: finishStartingService: stopping service
,08-10 17:05:23.282  1642  1761 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-10 17:05:23.283  1642  1761 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-10 17:05:23.319  1519  1519 I ConfigService: onCreate
,08-10 17:05:28.393  1519  1519 I ConfigService: onDestroy
,08-10 17:06:02.101   871  1306 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-10 17:06:59.077  1519  1948 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 17:07:24.373  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:07:24.382  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:07:24.393  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:07:24.435  1519  2165 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 17:07:24.436  1519  2165 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 17:07:24.436  1519  2165 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 17:07:24.436  1519  2165 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:07:24.457  1519  2165 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 17:07:24.457  1519  2165 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 17:07:24.457  1519  2165 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 17:07:24.457  1519  2165 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 17:07:24.457  1519  2165 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 17:07:24.457  1519  2165 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 17:07:24.457  1519  2165 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 17:07:24.460  2567  2601 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 17:07:24.460  2567  2601 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 17:07:24.460  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 17:07:24.460  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 17:07:24.460  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 17:07:24.460  2567  2601 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 17:07:24.460  2567  2601 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 17:12:24.611  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:12:24.624  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:12:24.629  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:12:24.681  1519  2672 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-10 17:12:24.681  1519  2672 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 17:12:24.681  1519  2672 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 17:12:24.681  1519  2672 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:12:24.714  1519  2672 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 17:12:24.714  1519  2672 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 17:12:24.714  1519  2672 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 17:12:24.714  1519  2672 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 17:12:24.714  1519  2672 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 17:12:24.714  1519  2672 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 17:12:24.714  1519  2672 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 17:12:24.720  2567  2601 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 17:12:24.720  2567  2601 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 17:12:24.720  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 17:12:24.720  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 17:12:24.720  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 17:12:24.720  2567  2601 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 17:12:24.720  2567  2601 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 17:17:24.859  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:17:24.871  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:17:24.873  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:17:24.939  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 17:17:24.939  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 17:17:24.940  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:17:24.940  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:17:24.992  1519  1530 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 17:17:24.992  1519  1530 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 17:17:24.992  1519  1530 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 17:17:24.992  1519  1530 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 17:17:24.992  1519  1530 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 17:17:24.992  1519  1530 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 17:17:24.992  1519  1530 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 17:17:25.007  2567  2601 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 17:17:25.007  2567  2601 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 17:17:25.007  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 17:17:25.007  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 17:17:25.007  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 17:17:25.007  2567  2601 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 17:17:25.007  2567  2601 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 17:22:11.527   871   883 I UsageStatsService: User[0] Flushing usage stats to disk
,08-10 17:22:25.158  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:22:25.171  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:22:25.174  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:22:25.230  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-10 17:22:25.230  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-10 17:22:25.230  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:22:25.231  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:22:25.283  1519  1530 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 17:22:25.283  1519  1530 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 17:22:25.283  1519  1530 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 17:22:25.283  1519  1530 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 17:22:25.283  1519  1530 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 17:22:25.283  1519  1530 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 17:22:25.283  1519  1530 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 17:22:25.293  2567  2601 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 17:22:25.293  2567  2601 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 17:22:25.293  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 17:22:25.293  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 17:22:25.293  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 17:22:25.293  2567  2601 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 17:22:25.293  2567  2601 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 17:27:25.439  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:27:25.455  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:27:25.457  1519  1519 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 17:27:25.511  1519  1530 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 17:27:25.512  1519  1530 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 17:27:25.512  1519  1530 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 17:27:25.512  1519  1530 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 17:27:25.540  1519  1530 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 17:27:25.540  1519  1530 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 17:27:25.540  1519  1530 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 17:27:25.540  1519  1530 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 17:27:25.540  1519  1530 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 17:27:25.540  1519  1530 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 17:27:25.540  1519  1530 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 17:27:25.546  2567  2601 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 17:27:25.546  2567  2601 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 17:27:25.546  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-10 17:27:25.546  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 17:27:25.546  2567  2601 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 17:27:25.546  2567  2601 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 17:27:25.546  2567  2601 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms),08-10 17:27:43.304  3963  3963 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 17:27:43.308  3963  3963 D AndroidRuntime: CheckJNI is OFF
08-10 17:27:43.344  3963  3963 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 17:27:43.384  3963  3963 I Radio-JNI: register_android_hardware_Radio DONE
08-10 17:27:43.405  3963  3963 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-10 17:27:43.416   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-10 17:27:43.416   871   884 I ActivityManager: Killing 3309:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-10 17:27:43.457   871  1295 W InputDispatcher: channel 'c7cc99b com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-10 17:27:43.457   871  1295 E InputDispatcher: channel 'c7cc99b com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
08-10 17:27:43.462   871  1406 D GraphicsStats: Buffer count: 2
08-10 17:27:43.465   871  2562 I WindowState: WIN DEATH: Window{c7cc99b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 17:27:43.465   871  2562 W InputDispatcher: Attempted to unregister already unregistered input channel 'c7cc99b com.test.thalitest/com.test.thalitest.MainActivity (server)'
08-10 17:27:43.472   871  1305 D WifiService: Client connection lost with reason: 4
08-10 17:27:43.562   871   894 W PackageSettings: Skipping PackageSetting{7e24933 com.example.hello/10273} due to missing metadata
08-10 17:27:43.595   871   884 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-10 17:27:43.596   871   884 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-10 17:27:43.599   871   884 E ActivityManager: Failure starting process com.test.thalitest
08-10 17:27:43.599   871   884 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-10 17:27:43.599   871   884 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:27:43.599   871   884 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:27:43.599   871   884 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 17:27:43.599   871   884 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 17:27:43.601   871   884 I ActivityManager:   Force finishing activity ActivityRecord{68d6fc0 u0 com.test.thalitest/.MainActivity t8}
08-10 17:27:43.604   871   894 I art     : Starting a blocking GC Explicit
08-10 17:27:43.644   871  2817 W ActivityManager: Spurious death for ProcessRecord{277d72e 0:com.test.thalitest/u0a0}, curProc for 3309: null
08-10 17:27:43.685   871   894 I art     : Explicit concurrent mark sweep GC freed 33558(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 810us total 81.050ms
08-10 17:27:43.717   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-10 17:27:43.721  3963  3963 I art     : System.exit called, status: 0
08-10 17:27:43.721  3963  3963 I AndroidRuntime: VM exiting with result code 0.
08-10 17:27:43.784   871   894 I ActivityManager: Start proc 3978:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-10 17:27:43.784   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-10 17:27:43.812   871   884 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-10 17:27:43.823   871  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-10 17:27:43.828  1967  2058 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-10 17:27:43.833  1642  1642 I Keyboard.Facilitator: resetDictionaries() : en_US
08-10 17:27:43.836  3183  3183 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-10 17:27:43.840  1642  3992 I Keyboard.Facilitator.DecoderInitializer: run()
08-10 17:27:43.842  1642  3992 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-10 17:27:43.842  1642  3992 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
08-10 17:27:43.843  1642  3992 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-10 17:27:43.843  1642  3992 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
08-10 17:27:43.844  1642  3992 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-10 17:27:43.844  1642  3992 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
08-10 17:27:43.846  1642  3992 I Decoder : createOrResetDecoder
08-10 17:27:43.855   871  2562 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3309 uid 10000
08-10 17:27:43.863   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-10 17:27:43.865  1642  1642 I Keyboard.Facilitator: onFinishInput()
08-10 17:27:43.867   871  1406 I ActivityManager: Start proc 3994:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-10 17:27:43.883  1719  1719 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-10 17:27:43.884   871   883 E PackageManager: Failed to write settings, restoring backup
08-10 17:27:43.884   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-10 17:27:43.884   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-10 17:27:43.884   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-10 17:27:43.884   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-10 17:27:43.884   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-10 17:27:43.884   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:27:43.884   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:27:43.884   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 17:27:43.893   871  1302 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
08-10 17:27:43.896   871   884 E DropBoxManagerService: Can't write: system_server_wtf
08-10 17:27:43.896   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 17:27:43.896   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 17:27:43.896   871   884 E DropBoxManagerService: 	... 13 more
08-10 17:27:43.940   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 17:27:43.955   871  1676 I ActivityManager: Killing 3235:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-10 17:27:43.964  3994  3994 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:27:44.001  3994  4007 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:27:44.001  3994  4007 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 17:27:44.021  3994  4007 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
--------- beginning of crash
08-10 17:27:44.025  3994  4007 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-10 17:27:44.025  3994  4007 E AndroidRuntime: Process: android.process.acore, PID: 3994
08-10 17:27:44.025  3994  4007 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:27:44.025  3994  4007 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 17:27:44.028  1519  1519 I ConfigService: onCreate
08-10 17:27:44.030  1730  1812 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-10 17:27:44.031  3994  3994 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-10 17:27:44.035   871  4010 E DropBoxManagerService: Can't write: system_app_crash
08-10 17:27:44.035   871  4010 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 17:27:44.035   871  4010 E DropBoxManagerService: 	... 5 more
08-10 17:27:44.049   871   884 I ActivityManager: Start proc 4011:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-10 17:27:44.050   871  2562 I ActivityManager: Killing 1777:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-10 17:27:44.060  3994  4007 I Process : Sending signal. PID: 3994 SIG: 9
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 17:27:44.068  1519  4009 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 17:27:44.069  1519  4009 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-10 17:27:44.071  1519  4009 W SQLiteOpenHelper: Opened config.db in read-only mode
08-10 17:27:44.097   871  1305 D WifiService: Client connection lost with reason: 4
08-10 17:27:44.121   871   881 I ActivityManager: Start proc 4023:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-10 17:27:44.122  1730  1812 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-10 17:27:44.122  1730  1812 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1730
08-10 17:27:44.122  1730  1812 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 17:27:44.122  1730  1812 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 17:27:44.128   871  1406 I ActivityManager: Process android.process.acore (pid 3994) has died
08-10 17:27:44.131   871  1662 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 17:27:44.134  1730  1812 I Process : Sending signal. PID: 1730 SIG: 9
08-10 17:27:44.141   871  4034 E DropBoxManagerService: Can't write: system_app_crash
08-10 17:27:44.141   871  4034 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop117.tmp: open failed: EROFS (Read-only file system)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 17:27:44.141   871  4034 E DropBoxManagerService: 	... 5 more
08-10 17:27:44.148  1642  3992 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-10 17:27:44.171  4011  4011 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm

```
