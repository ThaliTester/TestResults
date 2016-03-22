#### Test 636801181df08af_thali08_motorola-Nexus 6 Logs


```
--------- beginning of system
03-22 09:07:22.914   821   862 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,--------- beginning of main
03-22 09:07:22.930   821   862 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
03-22 09:07:22.968   258  1728 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (220 us)
03-22 09:07:23.194  3321  3321 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
03-22 09:07:23.197  3321  3321 D AndroidRuntime: CheckJNI is OFF
03-22 09:07:23.336  3321  3321 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-22 09:07:23.341   821  1381 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-22 09:07:23.349   821  1381 V WindowManager: addAppToken: AppWindowToken{3a1e4e32 token=Token{3a56663d ActivityRecord{287cfb94 u0 com.test.thalitest/.MainActivity t17}}} to stack=1 task=17 at 0
03-22 09:07:23.352  3321  3321 D AndroidRuntime: Shutting down VM
03-22 09:07:23.371  1543  1543 I HotwordDetector: Closing mic
03-22 09:07:23.372  1543  1774 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@2b8cb9d6
03-22 09:07:23.376   821   860 V WindowManager: Adding window Window{2af91ff5 u0 Starting com.test.thalitest} at 2 of 7 (after Window{343a125d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL})
03-22 09:07:23.409   821  1308 I ActivityManager: Start proc 3337:com.test.thalitest/u0a95 for activity com.test.thalitest/.MainActivity
03-22 09:07:23.440   359  1781 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
03-22 09:07:23.441   359  1781 D audio_hw_primary: disable_snd_device: snd_device(55: voice-rec-mic)
03-22 09:07:23.445   371   371 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 7.704ms total 34.654ms
03-22 09:07:23.449   359  1036 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
03-22 09:07:23.451  1543  1776 I HotwordRecognitionRnr: Stopping hotword detection.
03-22 09:07:23.452  1543  1777 I HotwordRecognitionRnr: Hotword detection finished
03-22 09:07:23.464   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 198us total 14.178ms
03-22 09:07:23.472   821  1446 I ActivityManager: Killing 2956:com.android.settings/1000 (adj 15): empty #17
03-22 09:07:23.480   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 305us total 12.824ms
03-22 09:07:23.517   258   258 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
03-22 09:07:23.517   258   258 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
03-22 09:07:23.519   821   860 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": uniqueId="local:0", 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 560, 494.27 x 492.606 dpi, appVsyncOff 7500000, presDeadline 12666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
03-22 09:07:23.519   821   821 V ActivityManager: Display changed displayId=0
03-22 09:07:23.521   821   860 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-22 09:07:23.522   821   860 W DisplayManagerService: Failed to notify process 2956 that displays changed, assuming it died.
03-22 09:07:23.522   821   860 W DisplayManagerService: android.os.TransactionTooLargeException
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at android.os.BinderProxy.transactNative(Native Method)
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at android.os.BinderProxy.transact(Binder.java:496)
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1094)
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:932)
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:112)
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1027)
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at android.os.Looper.loop(Looper.java:135)
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-22 09:07:23.522   821   860 W DisplayManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
03-22 09:07:23.543   821  1264 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):522]: Error : st = 4, ind.status = -1659294995
03-22 09:07:23.543   821  1264 E LocSvc_IzatApiV02: E/virtual int izat_core::IzatApiV02::getBatchSize(int32_t):535]: get batching size failed.Or modem does not support batching 
,03-22 09:07:23.577   821  1446 I ActivityManager: Killing 2924:com.google.android.apps.messaging/u0a75 (adj 15): empty #18
,03-22 09:07:23.630   871   871 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
03-22 09:07:23.631   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_lock,
,03-22 09:07:23.671   871   871 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1
,03-22 09:07:23.671   871   871 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs1' for writing
,03-22 09:07:23.771  3337  3337 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-22 09:07:23.777   258   321 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-22 09:07:23.778   258   258 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-22 09:07:23.783   821  1052 D SurfaceControl: Excessive delay in setPowerMode(): 265ms
,03-22 09:07:23.788   821  1381 I art     : Explicit concurrent mark sweep GC freed 49381(2MB) AllocSpace objects, 1(16KB) LOS objects, 32% free, 33MB/49MB, paused 2.241ms total 91.625ms
,03-22 09:07:23.791   821   862 I DreamManagerService: Entering dreamland.
03-22 09:07:23.791   821   862 I PowerManagerService: Dozing...
03-22 09:07:23.791   821   857 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,03-22 09:07:23.797   359  1038 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-22 09:07:23.797   359  1038 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,03-22 09:07:23.808   821  1017 E WifiStateMachine: cancelDelayedScan -> 16
,03-22 09:07:23.811   821  1017 E native  : do suspend false
,03-22 09:07:23.823  3337  3337 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3608-3610)
,03-22 09:07:23.823  3337  3337 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-22 09:07:23.835  3337  3337 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f7cc6f7}
03-22 09:07:23.835  3337  3337 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-22 09:07:23.835  3337  3337 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-22 09:07:23.846  3337  3337 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-22 09:07:23.847  3337  3337 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-22 09:07:23.848  3337  3337 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-22 09:07:23.853  3337  3362 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,03-22 09:07:23.859  3337  3337 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-22 09:07:23.865  3337  3337 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-22 09:07:23.865  3337  3337 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-22 09:07:23.865  3337  3337 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-22 09:07:23.898   821  1017 E WifiStateMachine: cancelDelayedScan -> 18
,03-22 09:07:23.922   821   859 D BluetoothManagerService: Message: 20
,03-22 09:07:23.924   821   859 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e88cd92:true
,03-22 09:07:23.948   821  1017 E native  : do suspend true
,03-22 09:07:23.955  3337  3337 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-22 09:07:23.962   359  1465 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
03-22 09:07:23.962   359  1465 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,03-22 09:07:23.963  3337  3337 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-22 09:07:23.973  3337  3337 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,03-22 09:07:23.978  3337  3337 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-22 09:07:23.978  3337  3337 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-22 09:07:24.013   821  1017 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 17, 18 -> obsolete
,03-22 09:07:24.024  3337  3386 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-22 09:07:24.026  3337  3337 D Atlas   : Validating map...
,03-22 09:07:24.032   821  1443 V WindowManager: Adding window Window{125bbf42 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 2 of 8 (before Window{2af91ff5 u0 Starting com.test.thalitest})
,03-22 09:07:24.035  3337  3372 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-22 09:07:24.073  3337  3386 I OpenGLRenderer: Initialized EGL, version 1.4
,03-22 09:07:24.083  3337  3386 D OpenGLRenderer: Enabling debug mode 0
,03-22 09:07:24.165   821   860 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +797ms
,03-22 09:07:24.176  1244  1244 I Keyboard.Facilitator: onFinishInput()
,03-22 09:07:24.191  3337  3337 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-22 09:07:24.219  3337  3337 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3337
,03-22 09:07:24.298  3337  3337 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-22 09:07:24.442  3337  3388 D jxcore_app_log: JniHelper::setJavaVM(0xb489d200), pthread_self() = -1580589824
,03-22 09:07:24.449  3337  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-22 09:07:24.449  3337  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-22 09:07:24.449  3337  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-22 09:07:24.449  3337  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-22 09:07:24.449  3337  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true,
03-22 09:07:24.450  3337  3388 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ad61e30 added. We now have 1 listener(s)
03-22 09:07:24.450   821  1443 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-22 09:07:24.454  3337  3388 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,03-22 09:07:24.456  3337  3388 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61",
03-22 09:07:24.457  3337  3388 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-22 09:07:24.457  3337  3388 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
,03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-22 09:07:24.462  3337  3388 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c02bfcf added. We now have 1 listener(s)
03-22 09:07:24.463  3337  3388 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-22 09:07:24.467   821  1018 D WifiService: New client listening to asynchronous messages
03-22 09:07:24.470  3337  3388 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-22 09:07:24.477  3337  3388 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-22 09:07:24.478  3337  3388 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-22 09:07:24.478  3337  3388 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-22 09:07:24.478  3337  3388 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-22 09:07:24.483  3337  3388 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-22 09:07:24.484   821  1381 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,03-22 09:07:24.484  3337  3388 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,03-22 09:07:24.488  3337  3388 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-22 09:07:24.488  3337  3388 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-22 09:07:24.488  3337  3388 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-22 09:07:24.488  3337  3388 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-22 09:07:24.488  3337  3388 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-22 09:07:24.488  3337  3388 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
03-22 09:07:24.488  3337  3388 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
03-22 09:07:24.488  3337  3388 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,03-22 09:07:24.488  3337  3388 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-22 09:07:24.488  3337  3388 D io.jxcore.node.ConnectivityMonitor: start: OK
03-22 09:07:24.489  3337  3388 I io.jxcore.node.LifeCycleMonitor: start: OK
03-22 09:07:24.490  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-22 09:07:24.512  3337  3337 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-22 09:07:24.653   871   871 I kickstart: STATUS: Received file 'm9kefs1'
,03-22 09:07:24.653   871   871 I kickstart: STATUS: 950272 bytes transferred in 0.982400 seconds
03-22 09:07:24.653   871   871 I kickstart: STATUS: Successfully downloaded files from target 
03-22 09:07:24.654   871   871 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
03-22 09:07:24.657   871   871 I kickstart: STATUS: Sahara protocol completed
,03-22 09:07:24.707   821  1017 E WifiStateMachine: WifiStateMachine Disconnected CMD_START_SCAN source -2 15, 18 -> obsolete
,03-22 09:07:25.111  3337  3395 W jxcore-log: Initializing JXcore engine
03-22 09:07:25.111  3337  3395 W jxcore-log: JXcore engine is ready
,03-22 09:07:25.140  3395  3395 W Thread-355: type=1400 audit(0.0:16): avc: denied { ioctl } for path="socket:[10497]" dev="sockfs" ino=10497 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-22 09:07:25.140  3395  3395 W Thread-355: type=1400 audit(0.0:17): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-22 09:07:25.140  3395  3395 W Thread-355: type=1400 audit(0.0:18): avc: denied { ioctl } for path="socket:[10027]" dev="sockfs" ino=10027 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0,
03-22 09:07:25.140  3395  3395 W Thread-355: type=1400 audit(0.0:19): avc: denied { ioctl } for path="socket:[20136]" dev="sockfs" ino=20136 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,03-22 09:07:25.160  3337  3395 W jxcore-log: Starting JXcore engine,
,03-22 09:07:25.236  3337  3395 W jxcore-log: Platform android
03-22 09:07:25.236  3337  3395 W jxcore-log: 
03-22 09:07:25.236  3337  3395 W jxcore-log: Process ARCH arm
03-22 09:07:25.236  3337  3395 W jxcore-log: 
,03-22 09:07:25.431  3337  3395 I jxcore-log: JXcore Cordova bridge is ready!,
03-22 09:07:25.431  3337  3395 I jxcore-log: 
03-22 09:07:25.431  3337  3395 W jxcore-log: JXcore engine is started
,03-22 09:07:25.441  3337  3388 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-22 09:07:25.444  3337  3337 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,03-22 09:07:26.363  1196  1196 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,03-22 09:07:26.787  1196  1196 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,03-22 09:07:26.829  1196  1196 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,03-22 09:07:26.830  1196  1196 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,03-22 09:07:26.847   821  1017 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false}  explicitlySelected{false} }
03-22 09:07:26.847   821  1017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,03-22 09:07:26.847   821  1019 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,03-22 09:07:26.853   821  1017 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,03-22 09:07:26.861   355   815 D CommandListener: Setting iface cfg
,03-22 09:07:26.870   821  1017 E WifiStateMachine: Start Dhcp Watchdog 1
,03-22 09:07:26.875   821  1017 E WifiStateMachine:  WifiLinkLayerStats: 
03-22 09:07:26.875   821  1017 E WifiStateMachine:  my bss beacon rx: 1
03-22 09:07:26.875   821  1017 E WifiStateMachine:  RSSI mgmt: -40
03-22 09:07:26.875   821  1017 E WifiStateMachine:  BE :  rx=0 tx=3 lost=0 retries=0
03-22 09:07:26.875   821  1017 E WifiStateMachine:  BK :  rx=0 tx=0 lost=0 retries=0
03-22 09:07:26.875   821  1017 E WifiStateMachine:  VI :  rx=0 tx=0 lost=0 retries=0
03-22 09:07:26.875   821  1017 E WifiStateMachine:  VO :  rx=2 tx=0 lost=0 retries=0
03-22 09:07:26.875   821  1017 E WifiStateMachine:  on_time : 494 tx_time=62 rx_time=98 scan_time=0
,03-22 09:07:26.978   821  1017 E native  : do suspend false,
,03-22 09:07:26.990   821  1017 E WifiStateMachine: scanCount==0 - aborting
,03-22 09:07:27.229  3398  3398 I dhcpcd  : version 5.5.6 starting
,03-22 09:07:27.330  3398  3398 I dhcpcd  : wlan0: rebinding lease of 192.168.1.125
,03-22 09:07:27.534  3398  3398 I dhcpcd  : wlan0: acknowledged 192.168.1.125 from 192.168.1.1,
,03-22 09:07:27.683  3398  3398 I dhcpcd  : wlan0: leased 192.168.1.125 for 172800 seconds,
,03-22 09:07:28.007   821  1017 E native  : do suspend true
,03-22 09:07:28.045   821  1019 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,03-22 09:07:28.048   821  1019 D ConnectivityService: Adding iface wlan0 to network 100
,03-22 09:07:28.055   821  1017 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,03-22 09:07:28.082   821  1019 E ConnectivityService: Unexpected mtu value: 0, wlan0
,03-22 09:07:28.082   821  1019 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,03-22 09:07:28.083   821  1019 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,03-22 09:07:28.084   821  1019 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,03-22 09:07:28.086   821  1019 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,03-22 09:07:28.093   821  1019 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,03-22 09:07:28.097   821  1019 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
03-22 09:07:28.098   821  3396 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
03-22 09:07:28.098   821  3396 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Connected
03-22 09:07:28.098   821  3396 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
03-22 09:07:28.099   821  3396 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
03-22 09:07:28.100   821  1019 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-22 09:07:28.100   821  1019 D ConnectivityService:    accepting network in place of null
03-22 09:07:28.102   821  1019 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.125/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains:  MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true}  explicitlySelected{false} }
03-22 09:07:28.103   821  1019 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,03-22 09:07:28.105   821  1019 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-22 09:07:28.106   821  1019 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
03-22 09:07:28.106  1073  1531 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,03-22 09:07:28.108   821  1019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
03-22 09:07:28.108   821  1019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,03-22 09:07:28.111   821   859 D Tethering: MasterInitialState.processMessage what=3
,03-22 09:07:28.114   821  1226 V BackupManagerService: Scheduling immediate backup pass
03-22 09:07:28.116   821   821 V BackupManagerService: Running a backup pass
,03-22 09:07:28.117   821  1051 V BackupManagerService: clearing pending backups
,03-22 09:07:28.119  1543  1543 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,03-22 09:07:28.126  2980  2980 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-22 09:07:28.128   821  1051 V PerformBackupTask: Beginning backup of 14 targets
,03-22 09:07:28.132  3337  3337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
03-22 09:07:28.132  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-22 09:07:28.132  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-22 09:07:28.132  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-22 09:07:28.132  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-22 09:07:28.132  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-22 09:07:28.132  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-22 09:07:28.132  3337  3337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-22 09:07:28.132  3337  3337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-22 09:07:28.133   821  1051 D PerformBackupTask: invokeAgentForBackup on @pm@
,03-22 09:07:28.136   821  1051 V BackupServiceBinder: doBackup() invoked
03-22 09:07:28.136  2980  2980 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-22 09:07:28.137   821  1051 I PMBA    : Previous metadata 1570415 mismatch vs 1860966 - rewriting
,03-22 09:07:28.157   821  1051 I BackupRestoreController: Getting widget state for user: 0
,03-22 09:07:28.186   821  1315 I ActivityManager: Start proc 3439:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.steen.receiver.ConnectivityChangeReceiver
,03-22 09:07:28.197  1311  1607 D PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: subId=-1 phoneId=-1
03-22 09:07:28.197  1311  1607 E PhoneInterfaceManager: [PhoneIntfMgr] getDataEnabled: no phone subId=-1 retVal=false
03-22 09:07:28.197   821   854 D TelephonyManager: getDataEnabled: retVal=false
,03-22 09:07:28.222   821   854 E GpsLocationProvider: No APN found to select.
,03-22 09:07:28.226  1822  1838 W GmsBackupTransport: Unknown package in backup request: @pm@
,03-22 09:07:28.229  1822  1838 V GmsBackupTransport: starting performBackup for @pm@
,03-22 09:07:28.237  1822  1838 V GmsBackupTransport: performBackup done for @pm@
,03-22 09:07:28.249  1386  1386 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:28.286  1386  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: android
03-22 09:07:28.286  1386  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> android without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:28.286  1386  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:28.286  1386  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:28.290  1386  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:28.292   821  3458 D GpsLocationProvider: NTP server returned: 1458634048365 (Tue Mar 22 09:07:28 GMT+01:00 2016) reference: 168079 certainty: 28 system time offset: 73
03-22 09:07:28.293   821  1269 D AlarmManagerService: Setting time of day to sec=1458634048
03-22 09:07:28.365   821  1269 W AlarmManagerService: Unable to set rtc to 1458634048: Invalid argument
,03-22 09:07:28.404  1386  1735 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-22 09:07:28.404  1386  1735 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-22 09:07:28.404  1386  1735 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-22 09:07:28.404  1386  1735 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-22 09:07:28.404  1386  1735 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-22 09:07:28.404  1386  1735 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-22 09:07:28.404  1386  1735 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-22 09:07:28.410   821  3396 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 22 Mar 2016 08:07:28 GMT], X-Android-Received-Millis=[1458634048410], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1458634048287]}
,03-22 09:07:28.411   821  3396 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Validated
03-22 09:07:28.411   821  1019 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=0 extraInfo=null
03-22 09:07:28.411   821  1019 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-22 09:07:28.411   821  1019 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-22 09:07:28.411   821  1019 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-22 09:07:28.411   821  1019 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
,03-22 09:07:28.412  1073  1531 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-22 09:07:28.412   821  1019 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,03-22 09:07:28.416  1782  3457 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-22 09:07:28.419  1822  1911 W GmsBackupTransport: Error sending final backup to server: 
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: com.google.android.gms.backup.d.d: Can not get client auth token
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:1080)
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	at com.google.android.gms.backup.BackupTransportService.a(SourceFile:65)
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	at com.google.android.gms.backup.aa.finishBackup(SourceFile:409)
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	at android.app.backup.BackupTransport$TransportImpl.finishBackup(BackupTransport.java:547)
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	at com.android.internal.backup.IBackupTransport$Stub.onTransact(IBackupTransport.java:162)
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	at android.os.Binder.execTransact(Binder.java:446)
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2024)
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1867)
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-22 09:07:28.419  1822  1911 W GmsBackupTransport: 	... 1 more
,03-22 09:07:28.440   821  1051 D BackupManagerService: Now staging backup of com.google.android.talk
,03-22 09:07:28.448   821  1051 D BackupManagerService: Now staging backup of com.google.android.dialer
,03-22 09:07:28.449  1782  3476 W DriveInitializer: Background init thread started
,03-22 09:07:28.457   821  1051 D BackupManagerService: Now staging backup of com.android.providers.settings
,03-22 09:07:28.464   821  1051 D BackupManagerService: Now staging backup of com.android.sharedstoragebackup
,03-22 09:07:28.467  1782  3477 W DriveInitializer: Awaiting to be initialized
,03-22 09:07:28.471   821  1051 D BackupManagerService: Now staging backup of com.google.android.gm
,03-22 09:07:28.478   821  1114 I ActivityManager: Start proc 3479:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,03-22 09:07:28.500   821  1051 D BackupManagerService: Now staging backup of com.android.providers.userdictionary
,03-22 09:07:28.503   821  1051 D BackupManagerService: Now staging backup of com.android.nfc
,03-22 09:07:28.514  3479  3479 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,03-22 09:07:28.529   821  1051 D BackupManagerService: Now staging backup of com.google.android.apps.genie.geniewidget
,03-22 09:07:28.530  3479  3479 D SprintDMHelper: simOperator:  IMSI: null
,03-22 09:07:28.530  3479  3479 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,03-22 09:07:28.533  1782  1782 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,03-22 09:07:28.535   821  1051 D BackupManagerService: Now staging backup of com.google.android.marvin.talkback
,03-22 09:07:28.536  1782  1782 D SystemUpdateService: onCreate
,03-22 09:07:28.538  1782  1782 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-22 09:07:28.539   821  1051 D BackupManagerService: Now staging backup of com.google.android.inputmethod.latin
,03-22 09:07:28.540  1782  3499 I SystemUpdateService: active receiver: enabled
,03-22 09:07:28.543  1782  3499 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,03-22 09:07:28.545  1782  3499 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]; metered: false; mobile allowed: false
,03-22 09:07:28.545  1782  3499 I SystemUpdateService: now status is 0 (complete)
03-22 09:07:28.545  1782  3499 I SystemUpdateService: processDownloadedFile /data/data/com.google.android.gms/app_download/update.zip
03-22 09:07:28.545  1782  3499 I SystemUpdateService: file has been verified
03-22 09:07:28.545  1782  3499 I SystemUpdateService: OTA package size = 25802302
03-22 09:07:28.546   821  1051 D BackupManagerService: Now staging backup of com.google.android.calendar
03-22 09:07:28.547  1782  3499 I SystemUpdateService: showing system update notification
,03-22 09:07:28.557   821  1051 D BackupManagerService: Now staging backup of com.android.vending
,03-22 09:07:28.557   821   821 I ValidateNoPeople: skipping global notification
,03-22 09:07:28.570   821  1051 D BackupManagerService: Now staging backup of android
,03-22 09:07:28.572  1386  2584 I art     : Explicit concurrent mark sweep GC freed 21424(1084KB) AllocSpace objects, 0(0B) LOS objects, 38% free, 26MB/42MB, paused 2.657ms total 50.069ms
,03-22 09:07:28.574  1782  1795 W art     : Suspending all threads took: 9.129ms
,03-22 09:07:28.582   821  1051 D BackupManagerService: Now staging backup of com.google.android.googlequicksearchbox
,03-22 09:07:28.598  1386  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-22 09:07:28.598  1386  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:28.598  1386  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:28.598  1386  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:28.601  1386  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:28.608  1822  1838 I GmsBackupTransport: Next backup will happen in 43199797 millis.
,03-22 09:07:28.619   821  1051 I BackupManagerService: Backup pass finished.
,03-22 09:07:28.624  3136  3468 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
03-22 09:07:28.624  3136  3468 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at jdm.a(PG:82)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at jcs.o(PG:406)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at jcn.a(PG:1379)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at jcs.i(PG:143)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at blb.a(PG:3937)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at czp.a(PG:18188)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at czp.a(PG:9081)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at czq.run(PG:1686)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-22 09:07:28.624  3136  3468 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at jdj.a(PG:4091)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at jdj.a(PG:1125)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at jdm.a(PG:77)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	... 12 more
03-22 09:07:28.624  3136  3468 E HttpOperation: Caused by: faj: BadAuthentication
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at fal.a(PG:38)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	at jdj.a(PG:4089)
03-22 09:07:28.624  3136  3468 E HttpOperation: 	... 14 more
,03-22 09:07:28.661  1386  1626 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
03-22 09:07:28.661  1386  1626 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:28.662  1386  1626 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:28.662  1386  1626 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:28.667  1386  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:28.677  3136  3468 E HttpOperation: [getmobileexperiments] Unexpected exception
03-22 09:07:28.677  3136  3468 E HttpOperation: java.io.IOException: Cannot obtain authentication token
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at jdm.a(PG:82)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at jcs.o(PG:406)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at jcn.a(PG:1379)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at jcs.i(PG:143)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at hec.a(PG:42)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at hee.a(PG:102)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at czr.a(PG:65)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at kka.a(PG:108)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at czp.a(PG:19176)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at czp.a(PG:9081)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at czq.run(PG:1686)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
03-22 09:07:28.677  3136  3468 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at jdj.a(PG:4091)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at jdj.a(PG:1125)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at jdm.a(PG:77)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	... 15 more
03-22 09:07:28.677  3136  3468 E HttpOperation: Caused by: faj: BadAuthentication
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at fal.a(PG:38)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	at jdj.a(PG:4089)
03-22 09:07:28.677  3136  3468 E HttpOperation: 	... 17 more
03-22 09:07:28.678  3136  3468 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
03-22 09:07:28.678  3136  3468 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at jdm.a(PG:82)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at jcs.o(PG:406)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at jcn.a(PG:1379)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at jcs.i(PG:143)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at hec.a(PG:42)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at hee.a(PG:102)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at czr.a(PG:65)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at kka.a(PG:108)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at czp.a(PG:19176)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at czp.a(PG:9081)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at czq.run(PG:1686)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at jdj.a(PG:4091)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at jdj.a(PG:1,125)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at jdm.a(PG:77)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	... 15 more
03-22 09:07:28.678  3136  3468 E ExperimentLoader: Caused by: faj: BadAuthentication
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at fal.a(PG:38)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	at jdj.a(PG:4089)
03-22 09:07:28.678  3136  3468 E ExperimentLoader: 	... 17 more
03-22 09:07:28.687  1782  1782 D SystemUpdateService: onDestroy
03-22 09:07:28.697  1782  3509 I iu.SyncManager: SYNC; picasa accounts
03-22 09:07:28.713  1782  1782 D NetworkLogImpl: Loaded NetworkSpeedPredictor
03-22 09:07:28.715  1782  1782 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-22 09:07:28.718  1782  3509 I iu.UploadsManager: num queued entries: 0
,03-22 09:07:28.720  1782  3509 I iu.UploadsManager: num updated entries: 0
,03-22 09:07:28.722  1782  3509 I iu.SyncManager: NEXT; no task
,03-22 09:07:28.768  1782  3476 W DriveInitializer: Background init thread ended
,03-22 09:07:28.801   821   854 I ActivityManager: Start proc 3515:com.google.android.keep/u0a79 for service com.google.android.keep/.syncadapter.KeepSyncAdapterService
,03-22 09:07:28.820   821  1381 I ActivityManager: Killing 2452:com.google.android.apps.maps/u0a65 (adj 15): empty #17
,03-22 09:07:28.834   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 38310, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-22 09:07:29.000   821   854 I ActivityManager: Start proc 3534:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,03-22 09:07:29.033  1782  1782 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-22 09:07:29.036  1782  1782 I Kids    : [GCoreUtils] Current gmscore version, 7899430 is smaller than the required version 8400000
,03-22 09:07:29.069   821  1381 I ActivityManager: Start proc 3556:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,03-22 09:07:29.096  2166  2231 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-22 09:07:29.253  3556  3556 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-22 09:07:29.253  3556  3556 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-22 09:07:29.253  3556  3556 I GAv4    :   adb logcat -s GAv4
,03-22 09:07:29.255  1386  3577 D GCM     : Connected
,03-22 09:07:29.255  3211  3553 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,03-22 09:07:29.258   821  1446 I ActivityManager: Killing 3046:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,03-22 09:07:29.266   821   854 I art     : Explicit concurrent mark sweep GC freed 55327(2MB) AllocSpace objects, 7(154KB) LOS objects, 32% free, 33MB/49MB, paused 1.788ms total 84.248ms
,03-22 09:07:29.371  3556  3556 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-22 09:07:29.373  1386  3577 D GCM     : Message class com.google.f.a.a.p
,03-22 09:07:29.382  3556  3556 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-22 09:07:29.388  3556  3587 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-22 09:07:29.430  3515  3586 V KeepSync: Connecting to GoogleApiClient
,03-22 09:07:29.461  3534  3534 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-22 09:07:29.471  3534  3534 I BooksApp: Created application version: 3.6.8 (30608)
,03-22 09:07:29.493  1782  3607 W BaseAppContext: Using Auth Proxy for data requests.
,03-22 09:07:29.498  1782  3607 W BaseAppContext: Using Auth Proxy for data requests.
,03-22 09:07:29.529  1386  1735 I art     : Explicit concurrent mark sweep GC freed 16721(944KB) AllocSpace objects, 5(362KB) LOS objects, 38% free, 25MB/41MB, paused 1.307ms total 23.355ms
,03-22 09:07:29.546  1386  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
03-22 09:07:29.546  1386  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:29.546  1386  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:29.546  1386  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:29.549  1386  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:29.566  3556  3556 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: Handling authorization failure
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: com.google.android.gms.drive.auth.c: Authorization failed: BadAuthentication
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:249)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:143)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.e.<init>(SourceFile:209)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.drive.api.a.l.a(SourceFile:62)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at java.lang.Thread.run(Thread.java:818)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: Caused by: com.google.android.gms.auth.ad: BadAuthentication
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.auth.p.a(SourceFile:310)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.common.server.a.a.b(SourceFile:97)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.common.server.c.b(SourceFile:109)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:30)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.b(SourceFile:370)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:340)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.common.server.o.a(SourceFile:319)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.drive.e.a.b.a(SourceFile:689)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	at com.google.android.gms.drive.auth.g.a(SourceFile:220)
03-22 09:07:29.570  1782  3607 E ClientConnectionOperation: 	... 7 more
,03-22 09:07:29.573  3515  3586 V KeepSync: GoogleApiClient failed to connect with error code: 4
,03-22 09:07:29.577  3515  3586 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
,03-22 09:07:29.579  3515  3586 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-22 09:07:29.580  3556  3556 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 9294-9295)
03-22 09:07:29.580  3515  3586 E SQLiteLog: (284) automatic index on blob_node(is_deleted)
03-22 09:07:29.580  3556  3556 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-22 09:07:29.584  3556  3556 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22a1f4ea}
03-22 09:07:29.584  3556  3556 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-22 09:07:29.584  3556  3556 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-22 09:07:29.588  3534  3608 I BooksSync: Starting books sync for 61035162, extras: ade
,03-22 09:07:29.595  3556  3556 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-22 09:07:29.595  3556  3556 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-22 09:07:29.596  3556  3556 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-22 09:07:29.610  3556  3556 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-22 09:07:29.614  3556  3556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-22 09:07:29.614  3556  3556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-22 09:07:29.614  3556  3556 I Adreno  : EGLInit: QTI Build: 01/29/15, 1bccc5d, I0ba6dce82d
,03-22 09:07:29.671  3556  3628 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-22 09:07:29.678  3556  3556 I NSApplication: Starting up...
,03-22 09:07:29.681  1386  1734 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
03-22 09:07:29.681  1386  1734 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:29.682  1386  1734 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:29.682  1386  1734 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:29.685  1386  1734 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:29.707  3534  3635 I BooksConfig: GmsCore Version = 7.8.99 (2134222-430)
,03-22 09:07:29.715   821  1381 I ActivityManager: Start proc 3636:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,03-22 09:07:29.753  3515  3586 E KeepSync: IOException
03-22 09:07:29.753  3515  3586 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.android.keep.util.m$a.intercept(SourceFile:233)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.android.keep.util.m.a(SourceFile:207)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.a(SourceFile:305)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:198)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
03-22 09:07:29.753  3515  3586 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
03-22 09:07:29.753  3515  3586 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
03-22 09:07:29.753  3515  3586 E KeepSync: 	... 10 more
03-22 09:07:29.753  3515  3586 W KeepSync: Sync result 2
,03-22 09:07:29.762   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 38315, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-22 09:07:29.762   821  1226 I ActivityManager: Killing 3067:com.android.musicfx/u0a18 (adj 15): empty #17
,03-22 09:07:29.899  1386  1626 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-22 09:07:29.899  1386  1626 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:29.899  1386  1626 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:29.899  1386  1626 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:29.903  1386  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:29.955  1386  1406 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
03-22 09:07:29.955  1386  1406 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/books without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:29.955  1386  1406 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:29.955  1386  1406 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:29.958  1386  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:29.967  3534  3635 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,03-22 09:07:29.968  3534  3608 E BooksSync: Soft error
03-22 09:07:29.968  3534  3608 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-22 09:07:29.968  3534  3608 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,03-22 09:07:29.969  3534  3608 E BooksSync: Sync error
03-22 09:07:29.969  3534  3608 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
03-22 09:07:29.969  3534  3608 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
03-22 09:07:29.969  3534  3608 I BooksSync: Finished books sync
,03-22 09:07:29.974   821  1226 I ActivityManager: Killing 3094:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,03-22 09:07:29.976   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 38316, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,03-22 09:07:30.083  1782  3658 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
,03-22 09:07:30.089  2980  2980 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-22 09:07:30.090  2980  2980 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-22 09:07:30.097  2980  3659 I MusicLifecycle: Sync started
,03-22 09:07:30.144   821   854 I ActivityManager: Start proc 3662:com.google.android.apps.cloudprint:sync/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.CloudPrintSyncService
,03-22 09:07:30.162   821  1425 I ActivityManager: Start proc 3679:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,03-22 09:07:30.164   821  1425 I ActivityManager: Killing 2839:com.google.android.gms:car/u0a11 (adj 15): empty #17
,03-22 09:07:30.586   821   837 I ActivityManager: Start proc 3698:com.google.android.apps.cloudprint/u0a41 for service com.google.android.apps.cloudprint/.printdialog.services.NotificationIntentService
,03-22 09:07:30.628  1386  1386 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:30.630   821  1446 I ActivityManager: Killing 2469:android.process.acore/u0a5 (adj 15): empty #17
,03-22 09:07:30.691  3662  3716 I com.google.android.apps.cloudprint.printdialog.database.CloudPrintSyncAdapter: Sync request not initiated by GCP app. Dropping
,03-22 09:07:30.705   821  1308 I ActivityManager: Killing 2861:com.google.android.gm/u0a78 (adj 15): empty #17
,03-22 09:07:30.708  1386  2584 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.music, service: sj
03-22 09:07:30.708  1386  2584 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> sj without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:30.708  1386  2584 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:30.708  1386  2584 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:30.814  1386  2584 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:30.889   821   837 I art     : Explicit concurrent mark sweep GC freed 26188(1149KB) AllocSpace objects, 5(174KB) LOS objects, 32% free, 33MB/49MB, paused 1.312ms total 49.614ms
,03-22 09:07:30.908  1386  2584 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-22 09:07:30.908  1386  2584 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-22 09:07:30.908  1386  2584 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-22 09:07:30.908  1386  2584 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-22 09:07:30.908  1386  2584 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-22 09:07:30.908  1386  2584 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-22 09:07:30.908  1386  2584 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:446)
,03-22 09:07:30.919  2980  3659 I MusicLifecycle: Sync ended
03-22 09:07:30.919  2980  3659 W MusicSyncAdapter: Sync failed due to an authentication issue.
,03-22 09:07:30.924   821   854 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 38348, reason: Periodic, SyncResult: stats [ numAuthExceptions: 1]
,03-22 09:07:30.925   821  1114 I ActivityManager: Killing 3191:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,03-22 09:07:30.926   821   854 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.google.android.music.MusicContent, PERIODIC, currentRunTime 203170, reason: Periodic
,03-22 09:07:31.170   821  1315 I ActivityManager: Killing 2392:com.google.android.calendar/u0a37 (adj 15): empty #17
,03-22 09:07:31.459   821   821 I ActivityManager: Start proc 3718:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,03-22 09:07:31.563  3718  3718 E SQLiteLog: (283) recovered 17 frames from WAL file /data/data/com.google.android.calendar/databases/timelydata.db-wal
,03-22 09:07:31.763   821   836 I ActivityManager: Start proc 3742:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,03-22 09:07:31.778  3718  3718 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,03-22 09:07:31.779   371   371 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 318us total 18.651ms
,03-22 09:07:31.794   821  1308 I ActivityManager: Killing 2797:com.android.vending/u0a19 (adj 15): empty #17
,03-22 09:07:31.796   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 923us total 16.309ms
,03-22 09:07:31.804  3742  3742 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458634051803
03-22 09:07:31.804  3742  3742 D         : TimeServiceNative: User Time to be set is 1458634051804
03-22 09:07:31.804  3742  3742 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-22 09:07:31.804  3742  3742 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-22 09:07:31.804  3742  3742 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458634051804
03-22 09:07:31.804  3742  3742 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-22 09:07:31.804   374   880 D QC-time-services: Daemon: Connection accepted:time_genoff
,03-22 09:07:31.806   374  3759 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458634051804
03-22 09:07:31.807   374  3759 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458634051804, operation = 0
03-22 09:07:31.807   374  3759 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS7/8/70 4:19:15
03-22 09:07:31.807   374  3759 D QC-time-services: Daemon:Value read from RTC seconds = 18937155000
03-22 09:07:31.807   374  3759 D QC-time-services: Daemon:new time 1458634051804 
03-22 09:07:31.807   374  3759 D QC-time-services: Daemon: delta 1439696896804 genoff 1439696896804 
03-22 09:07:31.807   374  3759 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696896804 to memory
03-22 09:07:31.807   374  3759 D QC-time-services: Daemon:Opening File: /data/time/ats_2
03-22 09:07:31.807   374  3759 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-22 09:07:31.807   371   371 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 21MB/36MB, paused 222us total 9.856ms
,03-22 09:07:31.810   374  3759 D QC-time-services: Updating the TOD offset
03-22 09:07:31.810   374  3759 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696896804 to memory
03-22 09:07:31.810   374  3759 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-22 09:07:31.810   374  3759 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-22 09:07:31.811   374  3759 E QC-time-services: Daemon:Update to modem bit set
03-22 09:07:31.811   374  3759 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-22 09:07:31.811  3742  3742 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-22 09:07:31.811   374  3759 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1142669251804
,03-22 09:07:31.880   374   880 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-22 09:07:31.886   374   878 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-22 09:07:31.999   821  1315 I ActivityManager: Start proc 3761:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,03-22 09:07:32.010   821   836 I ActivityManager: Killing 1543:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,03-22 09:07:32.075   821  1018 D WifiService: Client connection lost with reason: 4
,03-22 09:07:32.170  3761  3761 I GAv4    : Google Analytics 4.5.0/7324 is starting up. To enable debug logging on a device run:
03-22 09:07:32.170  3761  3761 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-22 09:07:32.170  3761  3761 I GAv4    :   adb logcat -s GAv4
,03-22 09:07:32.185  3761  3761 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.,
,03-22 09:07:32.197  3761  3761 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-22 09:07:32.214  3761  3780 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-22 09:07:32.280   821   837 I ActivityManager: Killing 3479:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,03-22 09:07:32.467  1782  1782 V Herrevad: NQAS connected
,03-22 09:07:32.479   821  1018 D WifiService: New client listening to asynchronous messages
,03-22 09:07:32.488  3211  3211 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-22 09:07:32.489  3211  3211 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-22 09:07:32.539  2980  3786 I MusicLeanback: Conditions not met for autocaching. okToAttempt=false
03-22 09:07:32.540  2980  3786 I MusicLeanback: Stop autocaching.
,03-22 09:07:32.591   821  1441 I ActivityManager: Start proc 3799:com.google.android.gms.wearable/u0a11 for service com.google.android.gms/.wearable.service.WearableService
,03-22 09:07:32.629  3799  3799 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-22 09:07:32.629  3799  3799 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-22 09:07:32.661  1386  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
03-22 09:07:32.661  1386  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:32.661  1386  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:32.661  1386  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:32.662  3799  3799 I MultiDex: VM with version 2.1.0 has multidex support
03-22 09:07:32.662  3799  3799 I MultiDex: install
03-22 09:07:32.662  3799  3799 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-22 09:07:32.665  1386  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-22 09:07:32.673  3211  3789 E Babel   : UserRecoverableAuthException.
03-22 09:07:32.674  3211  3789 E Babel   : eei: BadAuthentication
03-22 09:07:32.674  3211  3789 E Babel   : 	at eeg.a(Unknown Source)
03-22 09:07:32.674  3211  3789 E Babel   : 	at eeg.a(Unknown Source)
03-22 09:07:32.674  3211  3789 E Babel   : 	at eeg.a(Unknown Source)
03-22 09:07:32.674  3211  3789 E Babel   : 	at g.a(Unknown Source)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cae.a(SourceFile:3089)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cae.a(SourceFile:1131)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cws.a(SourceFile:4333)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cws.a(SourceFile:1419)
03-22 09:07:32.674  3211  3789 E Babel   : 	at crl.a(SourceFile:492)
03-22 09:07:32.674  3211  3789 E Babel   : 	at crl.a(SourceFile:1468)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cqu.a(SourceFile:4416)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cas.b(SourceFile:106)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cap.d(SourceFile:335)
03-22 09:07:32.674  3211  3789 E Babel   : 	at caq.run(SourceFile:81)
03-22 09:07:32.674  3211  3789 E Babel   : Error getting auth token
03-22 09:07:32.674  3211  3789 E Babel   : dvm
03-22 09:07:32.674  3211  3789 E Babel   : 	at g.a(Unknown Source)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cae.a(SourceFile:3089)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cae.a(SourceFile:1131)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cws.a(SourceFile:4333)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cws.a(SourceFile:1419)
03-22 09:07:32.674  3211  3789 E Babel   : 	at crl.a(SourceFile:492)
03-22 09:07:32.674  3211  3789 E Babel   : 	at crl.a(SourceFile:1468)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cqu.a(SourceFile:4416)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cas.b(SourceFile:106)
03-22 09:07:32.674  3211  3789 E Babel   : 	at cap.d(SourceFile:335)
03-22 09:07:32.674  3211  3789 E Babel   : 	at caq.run(SourceFile:81)
03-22 09:07:32.676  3211  3789 E Babel   : Account registration failed 1-Redacted-21
03-22 09:07:32.677  3211  3789 E Babel   : cyp: null -- null
03-22 09:07:32.677  3211  3789 E Babel   : 	at cae.a(SourceFile:3121)
03-22 09:07:32.677  3211  3789 E Babel   : 	at cae.a(SourceFile:1131)
03-22 09:07:32.677  3211  3789 E Babel   : 	at cws.a(SourceFile:4333)
03-22 09:07:32.677  3211  3789 E Babel   : 	at cws.a(SourceFile:1419)
03-22 09:07:32.677  3211  3789 E Babel   : 	at crl.a(SourceFile:492)
03-22 09:07:32.677  3211  3789 E Babel   : 	at crl.a(SourceFile:1468)
03-22 09:07:32.677  3211  3789 E Babel   : 	at cqu.a(SourceFile:4416)
03-22 09:07:32.677  3211  3789 E Babel   : 	at cas.b(SourceFile:106)
03-22 09:07:32.677  3211  3789 E Babel   : 	at cap.d(SourceFile:335)
03-22 09:07:32.677  3211  3789 E Babel   : 	at caq.run(SourceFile:81)
03-22 09:07:32.679  3799  3799 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-22 09:07:32.683  3211  3789 I art     : Note: end time exceeds epoch: 
03-22 09:07:32.699  1386  1406 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native
,03-22 09:07:32.699  1386  1406 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.peopleapi.readwrite https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation  https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:32.699  1386  1406 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:32.699  1386  1406 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:32.701  1386  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:32.710  1386  1406 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-22 09:07:32.723  3211  3823 E Babel   : Unexpected exception while authenticating.
,03-22 09:07:32.725  3211  3823 E Babel   : eej: User intervention required. Notification has been pushed.
03-22 09:07:32.725  3211  3823 E Babel   : 	at eeg.b(Unknown Source)
03-22 09:07:32.725  3211  3823 E Babel   : 	at eeg.b(Unknown Source)
03-22 09:07:32.725  3211  3823 E Babel   : 	at g.a(Unknown Source)
03-22 09:07:32.725  3211  3823 E Babel   : 	at cae.b(SourceFile:1146)
03-22 09:07:32.725  3211  3823 E Babel   : 	at dcg.run(SourceFile:5617)
03-22 09:07:32.725  3211  3823 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-22 09:07:32.725  3211  3823 E Babel   : 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-22 09:07:32.725  3211  3823 E Babel   : 	at java.lang.Thread.run(Thread.java:818)
,03-22 09:07:32.727  3799  3799 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-22 09:07:32.729  1386  2125 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
03-22 09:07:32.733  1386  1386 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-22 09:07:32.736  1782  1782 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-22 09:07:32.746  3799  3799 D WearableService: callingUid 10011, callindPid: 3799
03-22 09:07:32.750  1782  3825 D LocationInitializer: Restart initialization of location
,03-22 09:07:32.766  1822  2119 E MDM     : [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-22 09:07:32.775  2980  2980 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-22 09:07:32.776  2980  3814 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-22 09:07:33.136  1386  1386 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:33.290  1386  1386 I art     : Explicit concurrent mark sweep GC freed 26714(1538KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 27MB/43MB, paused 1.207ms total 31.027ms
03-22 09:07:33.291  3439  3833 V GoogleAuthProtoRequest: [345] a.<init>: mAccountName set to: thalitester@gmail.com
,03-22 09:07:33.347  1386  3834 I VacuumService: Vacuum at: now=1458634053347 tag=VacuumService
,03-22 09:07:33.364  1386  1408 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,03-22 09:07:33.364  1386  1408 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:33.365  1386  1408 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:33.365  1386  1408 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:33.368  1386  1408 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:33.456   821  1446 I art     : Explicit concurrent mark sweep GC freed 16293(727KB) AllocSpace objects, 2(220KB) LOS objects, 32% free, 33MB/49MB, paused 1.773ms total 99.161ms
,03-22 09:07:33.558  1386  3836 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,03-22 09:07:33.567  3439  3833 W ExperimentUpdateService: [345] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: [345] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: 	at com.google.android.gms.gcm.c.run(Unknown Source)
03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
03-22 09:07:33.570  3439  3833 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,03-22 09:07:33.578  1386  3836 W Uploader: No account for auth token provided
,03-22 09:07:33.955  1386  3836 W Uploader: No account for auth token provided
,03-22 09:07:34.144  1386  3836 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-22 09:07:34.144  1386  3836 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:34.144  1386  3836 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:34.144  1386  3836 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:34.148  1386  3836 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:34.199  1386  3836 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-22 09:07:34.199  1386  3836 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-22 09:07:34.199  1386  3836 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-22 09:07:34.314  1386  3836 W Uploader: No account for auth token provided
,03-22 09:07:34.487  3534  3592 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-22 09:07:34.568  1386  3836 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-22 09:07:34.569  1386  3836 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:34.569  1386  3836 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:34.569  1386  3836 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:34.579  1386  3836 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:34.650  1386  3836 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-22 09:07:34.650  1386  3836 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-22 09:07:34.650  1386  3836 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-22 09:07:34.900  1386  3836 W Uploader: No account for auth token provided
,03-22 09:07:35.089  1386  3836 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
03-22 09:07:35.090  1386  3836 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:35.090  1386  3836 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:35.090  1386  3836 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-22 09:07:35.093  1386  3836 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:35.136  1386  3836 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-22 09:07:35.136  1386  3836 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-22 09:07:35.136  1386  3836 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-22 09:07:35.269  1386  3836 W Uploader: No account for auth token provided
,03-22 09:07:35.389  1386  3836 W Uploader: No account for auth token provided
,03-22 09:07:35.559  1386  3836 W Uploader: No account for auth token provided
,03-22 09:07:35.654  3337  3395 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-22 09:07:35.654  3337  3395 I jxcore-log: 
,03-22 09:07:35.658  3337  3395 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-22 09:07:35.658  3337  3395 I jxcore-log: 
,03-22 09:07:35.668  3337  3395 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,03-22 09:07:35.668  3337  3395 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-22 09:07:35.668  3337  3395 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-22 09:07:35.668  3337  3395 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-22 09:07:35.668  3337  3395 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-22 09:07:35.668  3337  3395 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-22 09:07:35.668  3337  3395 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-22 09:07:35.668  3337  3395 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-22 09:07:35.671  3337  3395 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,03-22 09:07:35.674  3337  3395 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
,03-22 09:07:35.674  3337  3395 I jxcore-log: 
,03-22 09:07:35.677  3337  3395 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
,03-22 09:07:35.677  3337  3395 I jxcore-log: 
,03-22 09:07:35.734  1386  3836 W Uploader:  no longer exists, so no auth token.
,03-22 09:07:35.882  1386  3836 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-22 09:07:35.882  1386  3836 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:35.882  1386  3836 I GLSUser : [GLSUser] Extracting token using key: Auth,
03-22 09:07:35.883  1386  3836 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:35.888  1386  3836 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:35.925  1386  3836 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-22 09:07:35.925  1386  3836 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-22 09:07:35.925  1386  3836 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-22 09:07:36.173  1386  3836 W Uploader: No account for auth token provided
,03-22 09:07:36.195  3337  3395 I jxcore-log: Unit Test app is loaded
,03-22 09:07:36.195  3337  3395 I jxcore-log: 
,03-22 09:07:36.201  3337  3395 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,03-22 09:07:36.201  3337  3395 I jxcore-log: 
,03-22 09:07:36.211  3337  3395 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,03-22 09:07:36.212  3337  3337 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-22 09:07:36.215  3337  3395 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
,03-22 09:07:36.215  3337  3395 I jxcore-log: 
03-22 09:07:36.216  3337  3395 I jxcore-log: My device name is: motorola-Nexus 6
03-22 09:07:36.216  3337  3395 I jxcore-log: 
,03-22 09:07:36.395  1386  3836 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,03-22 09:07:36.395  1386  3836 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:36.395  1386  3836 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-22 09:07:36.395  1386  3836 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:36.409  1386  3836 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:36.477  1386  3836 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-22 09:07:36.477  1386  3836 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-22 09:07:36.477  1386  3836 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-22 09:07:36.581  1386  3836 W Uploader: No account for auth token provided
,03-22 09:07:36.696  3718  3738 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-22 09:07:36.706  1386  3836 W Uploader: No account for auth token provided
,03-22 09:07:37.777   821  1446 I ActivityManager: Killing 3556:com.google.android.apps.magazines/u0a67 (adj 15): empty #17
,03-22 09:07:39.599   821  1114 I ActivityManager: Start proc 3843:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentFiltersService
,03-22 09:07:39.709  3843  3843 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-22 09:07:39.789  3843  3843 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,03-22 09:07:39.868   821  1443 I ActivityManager: Start proc 3879:com.google.android.gms:car/u0a11 for service com.google.android.gms/.car.CarService
,03-22 09:07:39.890  3843  3843 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-22 09:07:39.891  3843  3843 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-22 09:07:39.909  3879  3879 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-22 09:07:39.909  3879  3879 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-22 09:07:39.932   821  1315 I ActivityManager: Killing 3636:com.android.chrome/u0a40 (adj 15): empty #17
,03-22 09:07:39.935  3843  3859 D Finsky  : [400] 1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
03-22 09:07:39.938  3879  3879 I MultiDex: VM with version 2.1.0 has multidex support
03-22 09:07:39.938  3879  3879 I MultiDex: install
03-22 09:07:39.939  3879  3879 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-22 09:07:39.989  3843  3843 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-22 09:07:39.990  3843  3843 D Finsky  : [1] 2.run: Finished loading 1 libraries.
,03-22 09:07:39.999  1386  1386 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:40.019  3879  3879 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-22 09:07:40.033  3843  3843 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-22 09:07:40.039  1386  1626 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-22 09:07:40.040  1386  1626 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:40.040  1386  1626 I GLSUser : [GLSUser] Extracting token using key: Auth
,03-22 09:07:40.040  1386  1626 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:40.049  1386  1626 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:40.063  3843  3843 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-22 09:07:40.065  3843  3859 D Finsky  : [400] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,03-22 09:07:40.082  3879  3879 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-22 09:07:40.086  1386  2561 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-22 09:07:40.090  1386  1386 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-22 09:07:40.095  1782  1782 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-22 09:07:40.109  3799  3799 D WearableService: callingUid 10011, callindPid: 3799
03-22 09:07:40.110  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
03-22 09:07:40.110  3337  3395 I jxcore-log: 
,03-22 09:07:40.114  1822  2123 E MDM     : [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-22 09:07:40.123  1782  3907 D LocationInitializer: Restart initialization of location
,03-22 09:07:40.287  3843  3843 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-22 09:07:40.477  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
03-22 09:07:40.477  3337  3395 I jxcore-log: 
,03-22 09:07:40.489  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
03-22 09:07:40.489  3337  3395 I jxcore-log: 
,03-22 09:07:40.493  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
03-22 09:07:40.493  3337  3395 I jxcore-log: 
,03-22 09:07:40.530  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
03-22 09:07:40.530  3337  3395 I jxcore-log: 
,03-22 09:07:40.546  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
03-22 09:07:40.546  3337  3395 I jxcore-log: 
,03-22 09:07:40.550  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
03-22 09:07:40.550  3337  3395 I jxcore-log: 
,03-22 09:07:40.805  3843  3843 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-22 09:07:40.847   821  1007 I ActivityManager: Start proc 3915:com.google.android.googlequicksearchbox:search/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.voicesearch.logger.EventLoggerService
,03-22 09:07:40.862  1386  1386 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:40.913  1386  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-22 09:07:40.913  1386  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-22 09:07:40.914  1386  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:40.915  1386  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:40.920  1386  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:40.942  3843  3843 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-22 09:07:40.948  1386  1386 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:40.970  1386  1406 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-22 09:07:40.971  1386  1406 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-22 09:07:40.971  1386  1406 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:40.971  1386  1406 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:40.975  1386  1406 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-22 09:07:40.997  1386  1386 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:41.018  1386  1734 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
03-22 09:07:41.018  1386  1734 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:41.018  1386  1734 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:41.018  1386  1734 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:41.021  1386  1734 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:41.033  3843  3843 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-22 09:07:41.159   821   837 I art     : Explicit concurrent mark sweep GC freed 20963(1024KB) AllocSpace objects, 3(236KB) LOS objects, 31% free, 34MB/50MB, paused 1.656ms total 60.918ms
,03-22 09:07:41.185   821  1308 I ActivityManager: Start proc 3944:com.google.android.partnersetup/u0a16 for content provider com.google.android.partnersetup/.RlzAppProvider
,03-22 09:07:41.250  1386  1386 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:41.267  1386  1735 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,03-22 09:07:41.267  1386  1735 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-22 09:07:41.268  1386  1735 I GLSUser : [GLSUser] Extracting token using key: Auth
03-22 09:07:41.268  1386  1735 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-22 09:07:41.271  1386  1735 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-22 09:07:41.282  3843  3843 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-22 09:07:41.283  3843  3843 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-22 09:07:41.288  3843  3843 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-22 09:07:41.290  3843  3843 D Finsky  : [1] DailyHygiene.reschedule: Giving up. (failures=6)
,03-22 09:07:41.303  1822  1881 D DeviceConnectionService: client connected with version: 7571000
,03-22 09:07:42.564  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
03-22 09:07:42.564  3337  3395 I jxcore-log: 
,03-22 09:07:42.582  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
03-22 09:07:42.582  3337  3395 I jxcore-log: 
,03-22 09:07:42.590  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
03-22 09:07:42.590  3337  3395 I jxcore-log: 
,03-22 09:07:42.713  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
03-22 09:07:42.713  3337  3395 I jxcore-log: 
,03-22 09:07:42.768  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
03-22 09:07:42.768  3337  3395 I jxcore-log: 
,03-22 09:07:42.903  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
03-22 09:07:42.903  3337  3395 I jxcore-log: 
,03-22 09:07:42.909  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
03-22 09:07:42.909  3337  3395 I jxcore-log: 
,03-22 09:07:42.915  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
,03-22 09:07:42.915  3337  3395 I jxcore-log: 
,03-22 09:07:42.936  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
03-22 09:07:42.936  3337  3395 I jxcore-log: 
,03-22 09:07:42.956  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
03-22 09:07:42.956  3337  3395 I jxcore-log: 
,03-22 09:07:43.058  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
03-22 09:07:43.058  3337  3395 I jxcore-log: 
,03-22 09:07:43.065  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
03-22 09:07:43.065  3337  3395 I jxcore-log: 
,03-22 09:07:43.091  3337  3395 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
03-22 09:07:43.091  3337  3395 I jxcore-log: 
,03-22 09:07:43.300   821  1308 I ActivityManager: Killing 3534:com.google.android.apps.books/u0a34 (adj 15): empty #17
,03-22 09:07:43.653  3337  3395 I jxcore-log: --= Surplus to requirements =--
03-22 09:07:43.653  3337  3395 I jxcore-log: 
03-22 09:07:43.653  3337  3395 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-22 09:07:43.653  3337  3395 I jxcore-log: 
,03-22 09:07:43.951  3977  3977 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,03-22 09:07:43.954  3977  3977 D AndroidRuntime: CheckJNI is OFF
,03-22 09:07:44.068  3977  3977 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-22 09:07:44.080   821   855 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=-1: uninstall pkg
03-22 09:07:44.080   821   855 I ActivityManager: Killing 3337:com.test.thalitest/u0a95 (adj 0): stop com.test.thalitest
,03-22 09:07:44.145   821   865 W PackageSettings: Skipping PackageSetting{31f00723 com.example.hello/10273} due to missing metadata
,03-22 09:07:44.213   821   837 I WindowState: WIN DEATH: Window{125bbf42 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-22 09:07:44.215   821  1018 D WifiService: Client connection lost with reason: 4
,03-22 09:07:44.296   821   855 W ActivityManager: Force removing ActivityRecord{287cfb94 u0 com.test.thalitest/.MainActivity t17}: app died, no saved state
,03-22 09:07:44.319   821   821 V ActivityManager: Display changed displayId=0
,03-22 09:07:44.328   821   865 I ActivityManager: Force stopping com.test.thalitest appid=10095 user=0: pkg removed
,03-22 09:07:44.357   821  1425 W ActivityManager: Spurious death for ProcessRecord{e61f471 3337:com.test.thalitest/u0a95}, curProc for 3337: null
,03-22 09:07:44.360   821  1053 D TaskPersister: removeObsoleteFile: deleting file=17_task.xml
,03-22 09:07:44.376  1244  1244 I Keyboard.Facilitator: resetDictionaries() : en_US
,03-22 09:07:44.392  1244  3991 I Keyboard.Facilitator.DecoderInitializer: run()
,03-22 09:07:44.411  3029  3029 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,03-22 09:07:44.415   821  1009 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-22 09:07:44.419  1244  3991 I Decoder : createOrResetDecoder
,03-22 09:07:44.448  1073  1073 I art     : Explicit concurrent mark sweep GC freed 16741(749KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 61MB/77MB, paused 1.663ms total 94.008ms
,03-22 09:07:44.472   821   836 I ActivityManager: Start proc 3994:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,03-22 09:07:44.475  1386  1386 I ConfigService: onCreate
,03-22 09:07:44.512   821  1226 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3337 uid 10095
,03-22 09:07:44.536  1244  3991 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,03-22 09:07:44.537   821   821 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-22 09:07:44.537   821   821 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-22 09:07:44.554  1244  1244 I Keyboard.Facilitator: onFinishInput()
,03-22 09:07:44.564  1348  1348 I art     : Explicit concurrent mark sweep GC freed 4982(363KB) AllocSpace objects, 13(1519KB) LOS objects, 31% free, 35MB/51MB, paused 748us total 21.583ms
,03-22 09:07:44.569  1348  1348 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-22 09:07:44.570  1348  1348 D Launcher.Workspace: 11683562 - stripEmptyScreens()
,03-22 09:07:44.589  1386  1626 I art     : Explicit concurrent mark sweep GC freed 55436(3MB) AllocSpace objects, 14(1386KB) LOS objects, 36% free, 27MB/43MB, paused 1.147ms total 32.735ms
,03-22 09:07:44.603  1244  3991 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/data/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,03-22 09:07:44.605  1244  3991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
03-22 09:07:44.605  1244  3991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
03-22 09:07:44.607  1244  3991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
03-22 09:07:44.607  1244  3991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
03-22 09:07:44.607  1244  3991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
03-22 09:07:44.607  1244  3991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,03-22 09:07:44.609  1244  3991 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
03-22 09:07:44.609  1244  3991 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
03-22 09:07:44.609  1244  3991 I Keyboard.Facilitator.Delight2FileSweeper: run()
03-22 09:07:44.609  1244  3991 I Keyboard.Facilitator.RecurringTaskScheduler: run()
03-22 09:07:44.609  1244  3991 I StatsUtilsManager: startPeriodStatsRecorder() : Success
03-22 09:07:44.609  1244  3991 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,03-22 09:07:44.641   821   865 I art     : Explicit concurrent mark sweep GC freed 19031(1663KB) AllocSpace objects, 8(599KB) LOS objects, 32% free, 33MB/49MB, paused 1.432ms total 228.300ms
,03-22 09:07:44.656  3994  4028 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,03-22 09:07:44.682   821  1446 I ActivityManager: Start proc 4029:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,03-22 09:07:44.689  3915  3915 W LocationOracleImpl: Best location was null
,03-22 09:07:44.707  3915  3915 I VS.Container: create_recognizer
,03-22 09:07:44.709  3977  3977 I art     : System.exit called, status: 0
03-22 09:07:44.709  3977  3977 I AndroidRuntime: VM exiting with result code 0.
,03-22 09:07:44.735  3994  4024 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Ї, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
,03-22 09:07:44.756   821  1308 I ActivityManager: Start proc 4057:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,03-22 09:07:44.775  3915  4075 I HotwordRecognitionRnr: Starting hotword detection.
,03-22 09:07:44.779  3915  4077 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.u@38f1d705
,03-22 09:07:44.780   359  4079 I AudioFlinger: AudioFlinger's thread 0xb4cd0000 ready to run
,03-22 09:07:44.783   359  1036 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,03-22 09:07:44.783  3915  4077 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.u@38f1d705
,03-22 09:07:44.790   821   865 I ActivityManager: Start proc 4080:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,03-22 09:07:44.793   359  4079 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(55: voice-rec-mic)
03-22 09:07:44.793   359  4079 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(55) acdb_id(62)
03-22 09:07:44.793   359  4079 E ACDB-LOADER: Error: ACDB AudProc vol returned = -19
03-22 09:07:44.793   359  4079 D audio_hw_primary: enable_snd_device: snd_device(55: voice-rec-mic)
,03-22 09:07:44.795   821  1308 I ActivityManager: Killing 3136:com.google.android.apps.plus/u0a74 (adj 15): empty #17
,03-22 09:07:44.801   359  4079 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,03-22 09:07:44.810  4057  4057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1692 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2609 
,03-22 09:07:44.921  1386  1386 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
03-22 09:07:44.922  1386  1386 D AndroidRuntime: Shutting down VM
--------- beginning of crash
03-22 09:07:44.922  1386  1386 E AndroidRuntime: FATAL EXCEPTION: main
03-22 09:07:44.922  1386  1386 E AndroidRuntime: Process: com.google.process.gapps, PID: 1386
03-22 09:07:44.922  1386  1386 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2616)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1380)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5254)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:903)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:698)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:734)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at com.google.android.gms.gcm.bh.a(SourceFile:310)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:127)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:321)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2609)
03-22 09:07:44.922  1386  1386 E AndroidRuntime: 	... 9 more
,03-22 09:07:44.931  4057  4097 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-22 09:07:44.931  4057  4097 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-22 09:07:44.932  4057  4097 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
03-22 09:07:44.932  4057  4097 E AndroidRuntime: Process: com.android.keychain, PID: 4057
03-22 09:07:44.932  4057  4097 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1148)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-22 09:07:44.932  4057  4097 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-22 09:07:44.933   821  4100 E DropBoxManagerService: Can't write: system_app_crash
03-22 09:07:44.933   821  4100 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop96.tmp: open failed: EROFS (Read-only file system)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-22 09:07:44.933   821  4100 E DropBoxManagerService: 	... 5 more
,03-22 09:07:44.945   821  4103 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,03-22 09:07:44.946   821   855 D Atlas   : Validating map...
,03-22 09:07:44.951   821  4104 E DropBoxManagerService: Can't write: system_app_crash
03-22 09:07:44.951   821  4104 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop98.tmp: open failed: EROFS (Read-only file system)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$19.run(ActivityManagerService.java:11995)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-22 09:07:44.951   821  4104 E DropBoxManagerService: 	... 5 more
,03-22 09:07:44.985  1782  1888 I art     : Explicit concurrent mark sweep GC freed 17944(1218KB) AllocSpace objects, 19(304KB) LOS objects, 35% free, 28MB/44MB, paused 1.127ms total 30.276ms
,03-22 09:07:44.989   821  4103 I OpenGLRenderer: Initialized EGL, version 1.4
,03-22 09:07:44.995   821  4103 D OpenGLRenderer: Enabling debug mode 0
03-22 09:07:45.000   821   836 I ActivityManager: Killing 3698:com.google.android.apps.cloudprint/u0a41 (adj 15): empty #17
,03-22 09:07:45.233  3915  3915 I HotwordWorker: onReady

```
